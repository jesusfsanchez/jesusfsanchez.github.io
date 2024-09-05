---
title: "Contact Me"
layout: page 
---

Email: [jesusfsa@usc.edu](mailto:jesusfsa@usc.edu)

LinkedIn: [Jesus Sanchez](https://www.linkedin.com/in/jesus-sanchez1/)

<div style="text-align: right;">
  
  <a href="/index">Return Home</a>
  
</div>

<h2>Code Snippet</h2>

<div style="position: relative;">
  <textarea id="codeSnippet" style="width: 100%; height: 100px;">
  // Your code goes here
  console.log('Hello, World!');
  </textarea>
  <button onclick="copyToClipboard()">Copy</button>
</div>

<script>
  function copyToClipboard() {
    var copyText = document.getElementById("codeSnippet");
    copyText.select();
    copyText.setSelectionRange(0, 99999); // For mobile devices
    document.execCommand("copy");
    alert("Copied the text: " + copyText.value);
  }
</script>
