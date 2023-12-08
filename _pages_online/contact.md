---
title: "Contact"
layout: archive
permalink: /contact/
---

<style>
a:link {
  text-decoration: none;
}

a:visited {
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

a:active {
  text-decoration: underline;
}

#copyConfirmation {
  visibility: hidden; /* Changed from display to visibility */
  opacity: 0;
  position: fixed;
  bottom: 60%;
  left: 50%;
  transform: translateX(-50%);
  padding: 10px;
  background-color: #f8f8f8;
  border: 1px solid #ddd;
  border-radius: 8px;
  box-shadow: 0 4px 6px rgb(0 0 0 / 17%);
  z-index: 1000;
  font-size: 12px;
  transition: visibility 0s, opacity 0.5s linear; /* Added transition */
}
</style>

<script>
function copyToClipboard(event, text) {
  event.preventDefault();
  var dummy = document.createElement("textarea");
  document.body.appendChild(dummy);
  dummy.value = text;
  dummy.select();
  document.execCommand("copy");
  document.body.removeChild(dummy);
  
  var confirmation = document.getElementById('copyConfirmation');
  confirmation.style.visibility = 'visible';
  confirmation.style.opacity = '1';
  setTimeout(function(){ 
    confirmation.style.opacity = '0'; 
    confirmation.style.visibility = 'hidden';
  }, 2000);
}
</script>

My contact information is below.

<div>
<table style="white-space:nowrap; width:100%; border: none;">
  <tr>
    <th style="width:1px; white-space:nowrap; border: none;">Email address</th>
    <td style="white-space:nowrap; border: none;">
      <a href="javascript:void(0)" onclick="copyToClipboard('u7227010@anu.edu.au')">u7227010@anu.edu.au</a>
    </td>
  </tr>
</table>
</div>

<div id="copyConfirmation">Email address copied to clipboard!</div>