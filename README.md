   <h1>Color Picker Chrome Extension</h1>
   <p> This is a simple Chrome extension that allows you to pick a color from any webpage and copy its hexadecimal value
      to the clipboard. It uses the Chrome storage API to save the selected color, and the Chrome scripting API to
      inject a content script into the active tab and retrieve the selected color.</p>

   <h1>How to Use</h1>
   <p> To use this extension, simply click on the extension icon and then click the "Pick Color" button. This will
      activate an eye dropper tool that you can use to select a color from any part of the page. Once you have selected
      a color, the extension will display its hexadecimal value and set the background color of the extension popup to
      the selected color.</p>

   <h1>Code Overview</h1>
   <p>The extension is built using HTML, CSS, and JavaScript. Here is an overview of the main components:
   </p>

   <h1>Manifest</h1>
   <p>The manifest.json file contains the metadata for the extension, including its name, description, version, and
      permissions. It also specifies the background script (background.js), options page (options.html), popup
      (popup.html), and icon images.
   </p>

   <h1>Popup</h1>
   <p>The popup.html file defines the HTML structure for the extension popup. It contains a button to trigger the color
      picker, a color grid to display the selected color, and a text element to display the hexadecimal value of the
      selected color.
   </p>
   <h1>JavaScript</h1>
   <p>The popup.js file contains the main JavaScript code for the extension. It defines an event listener for the color
      picker button, which uses the Chrome storage API to retrieve the selected color and the Chrome scripting API to
      inject a content script into the active tab and retrieve the selected color. The selected color is then displayed
      in the color grid and the hexadecimal value is copied to the clipboard.
      <br>The background.js file contains a service worker that listens for events from the extension and performs
      background tasks, such as managing the Chrome storage.
   </p>

   <h1>CSS</h1>
   <p>The popup.css file contains the CSS styling for the extension popup.
   </p>
   <h1>Installation</h1>
   <p>
   <ol>
   <p style="color: red;">Note: The extension has not been published to the Chrome Web Store, so it can only be installed manually as an unpacked extension.</p>
</br>
    <li>Download the source code as a ZIP file from the project's GitHub repository.</li>
    <li>Extract the ZIP file to a folder on your computer.</li>
    <li>Open the Google Chrome browser and go to the "Extensions" page (chrome://extensions/).</li>
    <li>Turn on the "Developer mode" toggle switch in the top right corner of the page.</li>
    <li>Click the "Load unpacked" button that appears and select the folder where you extracted the extension's source code.</li>
    <li>The extension will now be installed and ready to use. You can access it by clicking on the extension icon in the Chrome toolbar.</li>
</ol>
   </p>
   <h1>License</h1>
   <p>This extension is licensed under the MIT License. Feel free to use it and modify it as you see fit.
   </p>
</body>

</html>
