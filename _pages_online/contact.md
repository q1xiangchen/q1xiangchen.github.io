---
title: "Contact"
layout: archive
permalink: /contact/
---

<style>
a:link, a:visited {
  text-decoration: none;
}

a:hover, a:active {
  text-decoration: underline;
}

#copyAlert {
  display: none;
  position: fixed;
  bottom: 20px;
  left: 50%;
  transform: translateX(-50%);
  background-color: #f8f8f8;
  color: #333;
  padding: 10px;
  border: 1px solid #ddd;
  border-radius: 5px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  z-index: 1000;
}

.fadeOut {
  animation: fadeOut 2s;
}

@keyframes fadeOut {
  from { opacity: 1; }
  to { opacity: 0; }
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

  var alertBox = document.getElementById("copyAlert");
  alertBox.innerHTML = "Email address copied: " + text;
  alertBox.style.display = "block";

  setTimeout(function() {
    alertBox.classList.add("fadeOut");
    setTimeout(function() {
      alertBox.style.display = "none";
      alertBox.classList.remove("fadeOut");
    }, 2000);
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

<div id="copyAlert"></div>