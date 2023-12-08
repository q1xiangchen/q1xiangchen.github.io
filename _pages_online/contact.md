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
  display: none;
  position: fixed;
  bottom: 20px;
  left: 50%;
  transform: translateX(-50%);
  padding: 10px;
  background-color: #f8f8f8;
  border: 1px solid #ddd;
  border-radius: 5px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.2);
  z-index: 1000;
}
</style>

<script>
function copyToClipboard(text) {
  var dummy = document.createElement("textarea");
  document.body.appendChild(dummy);
  dummy.value = text;
  dummy.select();
  document.execCommand("copy");
  document.body.removeChild(dummy);
  
  var confirmation = document.getElementById('copyConfirmation');
  confirmation.style.display = 'block';
  setTimeout(function(){ confirmation.style.display = 'none'; }, 2000);
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