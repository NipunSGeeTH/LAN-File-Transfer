

<h1>Share Files Effortlessly on Your Network</h1>

<p>This easy-to-use server, powered by Python Flask, lets you share files between devices on the same network, like your home Wi-Fi. No internet connection is needed!. Local Network Files Sharing Through Browser with any devices.</p>

<h3 align="center">See It in Action</h3>
<p align="center">
  <img src="https://raw.githubusercontent.com/NipunSGeeTH/github-readme-images-host/main/Local-Network-files-Sharing-server/1.png" alt="Demo Image" style="width: auto; height: auto;">
</p>

<h2>🚀 Start Sharing</h2>

<ol>
  <li><strong>Download the Project 📂:</strong> Click the <b>"Code"</b> button and download the ZIP file. Extract it.</li>

  <li><strong>Navigate to the Files 📁:</strong> Open a terminal and use the <code>cd</code> command to go to the project folder:
    <pre><code>cd path/to/project-folder</code></pre>
  </li>

  <li><strong>Install Flask ⚙️:</strong> Run this command:
    <pre><code>pip install Flask</code></pre>
  </li>

  <li><strong>Start the Server 🚀:</strong> Type and press Enter:
    <pre><code>python app.py</code></pre>
  </li>

  <li><strong>Access the Server 🌐:</strong> Open your browser and enter the URL displayed in the terminal (e.g., <code>http://192.168.X.XXX:80</code>).</li>
</ol>

<h2>📱 Connect From Your Phone or Tablet</h2>

<ol>
  <li><strong>Same Wi-Fi 📶:</strong> Ensure your phone/tablet is connected to the same Wi-Fi network as your computer.</li>
  <li><strong>Enter the URL 🔗:</strong> Open a browser and type in the URL from Step 5 above.</li>
</ol>

<h2>⚙️ Customization (Optional)</h2>

<ul>
  <li><strong>Allow More File Types 📄:</strong>
    <ol>
      <li>Open <code>app.py</code> in a text editor.</li>
      <li>Find this line:
        <pre><code>ALLOWED_EXTENSIONS = {'txt', 'pdf', 'png', 'jpg', 'jpeg', 'gif'}</code></pre>
      </li>
      <li>Add more file types (e.g., MP3):
        <pre><code>ALLOWED_EXTENSIONS = {'txt', 'pdf', 'png', 'jpg', 'jpeg', 'gif', 'mp3'}</code></pre>
      </li>
      <li>Save the file and restart the server (<code>Ctrl + C</code> then <code>python app.py</code>).</li>
    </ol>
  </li>

  <li><strong>Change IP and Port 🌍:</strong>
    <ol>
      <li>Open <code>app.py</code> in a text editor.</li>
      <li>Find this line:
        <pre><code>app.run(debug=True)</code></pre>
      </li>
      <li>Modify it:
        <pre><code>app.run(debug=True, host="YOUR_IP", port=8080)</code></pre>
      </li>
      <li>Save and restart the server.</li>
    </ol>
  </li>
</ul>

<h2>⛔ Stopping the Server</h2>

<p>To stop sharing, simply press <strong>Ctrl + C</strong> in the terminal window where the server is running.</p>



















