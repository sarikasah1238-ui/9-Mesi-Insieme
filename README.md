<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>9 Month Insieme</title>
  <link href="https://fonts.googleapis.com/css2?family=Dancing+Script&display=swap" rel="stylesheet">
  <style>
    body {
      background: #f7e9dc;
      min-height: 100vh;
      margin: 0;
      font-family: 'Dancing Script', cursive;
      display: flex;
      justify-content: center;
      align-items: center;
    }
    .diary-container {
      background: #fffbe7;
      border-radius: 32px;
      box-shadow: 0 6px 32px rgba(120, 70, 24, 0.13);
      width: 700px;
      max-width: 95vw;
      padding: 40px 36px 24px 36px;
      position: relative;
      overflow: hidden;
    }
    .deco-top {
      width: 100%;
      height: 42px;
      background: repeating-linear-gradient(-45deg, #ffe4a9, #fffbe7 18px);
      position: absolute;
      top: 0; left: 0;
      border-radius: 32px 32px 0 0;
      opacity: 0.4;
      z-index: 0;
    }
    .letter {
      font-size: 1.3em;
      color: #856142;
      margin-bottom: 35px;
      position: relative;
      z-index: 2;
      text-align: left;
      line-height: 1.6;
      padding-top: 15px;
      padding-left: 10px;
      padding-right: 10px;
      letter-spacing: 0.01em;
    }
    .polaroid-row {
      display: flex;
      gap: 28px;
      justify-content: center;
      margin-top: 30px;
      flex-wrap: wrap;
    }
    .polaroid {
      background: #fff;
      border-radius: 17px 17px 30px 30px;
      border: 2.2px solid #f7d6ad;
      box-shadow: 0 6px 18px rgba(130, 100, 50, 0.18);
      width: 185px;
      height: 260px;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: flex-end;
      position: relative;
      margin-bottom: 12px;
      overflow: hidden;
      transition: transform 0.18s;
    }
    .polaroid:hover {
      transform: scale(1.05) rotate(-2deg);
      box-shadow: 0 12px 32px rgba(120, 70, 24, 0.19);
      z-index: 3;
    }
    .polaroid img {
      width: 97%;
      height: 78%;
      object-fit: cover;
      border-radius: 11px 11px 17px 17px;
      margin-top: 8px;
      margin-bottom: 0;
      box-shadow: 0 3px 10px rgba(80, 60, 20, 0.10);
      border: 1.2px solid #f7d6ad;
    }
    .caption {
      font-size: 1.04em;
      color: #856142;
      margin: 7px 0 10px 0;
      font-family: 'Dancing Script', cursive;
      text-align: center;
      letter-spacing: 0.
