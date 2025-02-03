<h2>Chatbot Versions</h2>

<h3>Version 1 (Basic)</h3>
<p>This version of the chatbot provides a simple text-based interaction. It includes:</p>
<ul>
  <li>Message exchange between the user and the bot.</li>
  <li>Basic UI with an input field and a send button.</li>
  <li>JavaScript event listeners to handle message sending and receiving.</li>
  <li>Uses the <code>fetch()</code> API to communicate with an external AI service (e.g., Gemini API) for responses.</li>
  <li>Does <strong>not</strong> store chat history; messages exist only within the current session.</li>
</ul>
<p>This version is implemented in <code>index.js</code> and is suitable for lightweight applications requiring minimal memory usage.</p>

<h3>Version 2 (Advanced)</h3>
<p>The advanced chatbot includes additional features, enhancing user experience with:</p>
<ul>
  <li><strong>File Uploads:</strong> Allows users to send files (e.g., images, documents) by reading them using <code>FileReader</code> and encoding them in Base64 format.</li>
  <li><strong>Emoji Support:</strong> Integrates <code>EmojiMart</code> to allow users to insert emojis into their messages.</li>
  <li><strong>Chat History:</strong> Maintains a history of messages by storing them in an array, allowing persistent conversation flow within the session.</li>
  <li><strong>Enhanced UI:</strong> Implements dynamic message rendering using <code>document.createElement</code> and CSS animations for a smoother chat experience.</li>
  <li><strong>Typing Indicators:</strong> Displays a bot "thinking" animation before responding to messages.</li>
</ul>
<p>This version is implemented in <code>script.js</code> and provides a more interactive and feature-rich chat experience.</p>
