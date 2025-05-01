<!DOCTYPE html>
<html>
<head>
  <title>BORBAAD</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background-color: #000;
    }
    .video-wrapper {
      transform: translateY(-50px); /* ভিডিও প্লেয়ারকে একটু উপরে তোলে */
    }
    iframe {
      border: none;
      width: 1280px;
      height: 720px;
      max-width: 100%;
      max-height: 100%;
    }
  </style>
</head>
<body>

<div class="video-wrapper">
  <iframe src="https://drive.google.com/file/d/1Y7TDa4WXf86CUL_b-VZZK-q0s7QogGFQ/preview"
          allow="autoplay" allowfullscreen>
  </iframe>
</div>

</body>
</html>
