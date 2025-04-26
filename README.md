<!DOCTYPE html>
<html>
<head>
  <style>
    body { 
      margin: 0; 
      background: transparent; /* 关键：设置页面背景透明 */
    }
    video {
      width: 100%; /* 视频尺寸自适应容器 */
      height: 100%;
    }
  </style>
</head>
<body>
  <video autoplay loop muted playsinline>
    <source src="your-video.webm" type="video/webm">
  </video>
</body>
</html>
