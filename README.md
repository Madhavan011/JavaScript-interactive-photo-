# JavaScript-interactive-photo-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Interactive Photo Gallery</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1>Interactive Photo Gallery</h1>
  <div class="gallery">
    <img src="https://via.placeholder.com/200x150?text=Photo+1" alt="Photo 1" onmouseover="highlightImage(this)" onmouseout="unhighlightImage(this)">
    <img src="https://via.placeholder.com/200x150?text=Photo+2" alt="Photo 2" onmouseover="highlightImage(this)" onmouseout="unhighlightImage(this)">
    <img src="https://via.placeholder.com/200x150?text=Photo+3" alt="Photo 3" onmouseover="highlightImage(this)" onmouseout="unhighlightImage(this)">
    <img src="https://via.placeholder.com/200x150?text=Photo+4" alt="Photo 4" onmouseover="highlightImage(this)" onmouseout="unhighlightImage(this)">
  </div>
  <script src="script.js"></script>
</body>
</html>
