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
  <button 
    onclick="copyTextToClipboard('jesus');')"
    class="copy-button"
  >
    Copy
  </button>
</div>

<script>
  function copyTextToClipboard(text) {
    navigator.clipboard.writeText(text).then(function() {
      alert("Copied to clipboard: " + text);
    }).catch(function(err) {
      console.error("Failed to copy text: ", err);
    });
  }
</script>
