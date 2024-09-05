---
title: "Contact Me"
layout: page 
---

Email: jesusfsa@usc.edu

LinkedIn: [Jesus Sanchez](https://www.linkedin.com/in/jesus-sanchez1/)

<div style="text-align: right;">
  
  <a href="/index">Return Home</a>
  
</div>


<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Position Button Next to Email</title>
  <style>
    .copy-button {
      background-color: #ffffff; /* White background */
      color: #000000; /* Black text */
      border: 1px solid #ddd; /* Border */
      padding: 5px 10px; /* Padding */
      font-size: 14px; /* Font size */
      cursor: pointer; /* Pointer cursor */
      border-radius: 4px; /* Rounded corners */
      margin-left: 10px; /* Space between email and button */
    }
    .email-container {
      display: flex;
      align-items: center; /* Vertically centers items */
    }
  </style>
</head>
<body>
  <div class="email-container">
    <span>Email: jesusfsa@usc.edu</span>
    <button 
      onclick="copyToClipboard()"
      class="copy-button"
    >
      Copy
    </button>
  </div>

  <script>
    function copyToClipboard() {
      var copyText = document.getElementById("hiddenInput");
      copyText.select();
      copyText.setSelectionRange(0, 99999); // For mobile devices
      document.execCommand("copy");
      alert("Copied the text: " + copyText.value);
    }
  </script>

  <input type="text" id="hiddenInput" value="Hello, World!" style="position: absolute; left: -9999px;">
</body>
