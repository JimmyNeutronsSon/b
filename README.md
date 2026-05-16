## Installation

To install this bookmarklet, follow these steps:

1. Create a new bookmark in your browser (any page will do).
2. Edit the bookmark, and change the name to something like **Run Script**.
3. Copy the code block below and paste it directly into the **URL** or **Location** field of the bookmark:

```javascript
javascript:(function(){const script=document.createElement("script");script.src="https://cdn.jsdelivr.net/gh/JimmyNeutronsSon/JimmyNeutronsSon.github.io@main/iboss.js";script.onload=()=>{alert("Script loaded and executed successfully!");};script.onerror=()=>{alert("Failed to load the script. Check the console or the URL.");};document.body.appendChild(script);})();
