---
title: "Contact Me"
layout: page 
---

Email: [jesusfsa@usc.edu](mailto:jesusfsa@usc.edu)

LinkedIn: [Jesus Sanchez](https://www.linkedin.com/in/jesus-sanchez1/)

<div style="text-align: right;">
  
  <a href="/index">Return Home</a>
  
</div>


<div style="position: relative;">
  <input type="text" id="hiddenInput" value="'Hello, World!';" style="position: absolute; left: -9999px;">
  <button 
    onclick="copyToClipboard()"
    class="copy-button"
    style="background-color: #4CAF50"
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

