<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Mini CodePen</title>
  <style>
    body { margin:0; background:#111; color:white; font-family:Arial; display:flex; height:100vh; }

    #editors {
      width:50%;
      display:flex;
      flex-direction:column;
      padding:10px;
      gap:10px;
      background:#1a1a1a;
    }

    textarea {
      width:100%;
      height:33%;
      background:#222;
      color:#0f0;
      border:none;
      padding:10px;
      font-size:16px;
      resize:none;
      outline:none;
    }

    #preview {
      width:50%;
      background:white;
      border:none;
    }
  </style>
</head>
<body>

<div id="editors">
  <textarea id="htmlCode" placeholder="HTML"></textarea>
  <textarea id="cssCode" placeholder="CSS"></textarea>
  <textarea id="jsCode" placeholder="JavaScript"></textarea>
</div>

<iframe id="preview"></iframe>

<script src="editor.js"></script>
</body>
</html>
