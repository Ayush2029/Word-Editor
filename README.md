# Word-Editor

A responsive, feature-rich in-browser word editor with real-time autocomplete suggestions and basic text formatting capabilities, built purely with HTML, CSS, and JavaScript. <br>

<h2>Features: </h2>
- Rich Text Formatting: Bold, Italic, Underline, and Strikethrough text with dedicated buttons. <br>
- Real-time Autocomplete: Suggestions appear instantly as you type, based on a comprehensive built-in vocabulary (Trie data structure). <br>
- Intelligent Suggestion Positioning: The suggestion box appears precisely on the next line below your cursor, adapting to your typing position and respecting editor boundaries. <br>
- Keyboard Navigation: Easily navigate through suggestions using Arrow Up/Down keys. <br>
- Quick Insertion: Insert highlighted suggestions using Enter or Tab keys.<br>
- Dynamic Instructions: A captivating moving instruction bar at the top provides helpful tips and engages the user.<br>
- Responsive Design: The editor's layout adjusts gracefully to different screen sizes, from mobile to desktop.<br>
- Custom Theming: A vibrant, dark theme with neon-like accents and custom scrollbar styling for an enhanced visual experience.<br>

<h2> How to Run: </h2>
This project is a static web application, meaning it runs directly in your browser without needing any backend server or complex build tools. <br>
- Locate the Word Editor.html file and double-click it. It will open automatically in your default web browser. <br>
That's it! The Word Editor should now be running in your browser, ready for you to start typing.

<h2>Technologies Used: </h2>
- HTML5: For the basic structure and contenteditable functionality. <br>
- CSS3: For all styling, animations, responsiveness, and custom UI elements. <br>
- JavaScript: For all interactive logic, including: <br>
(1) Trie data structure for efficient autocomplete.<br>
(2) DOM manipulation for dynamically updating suggestions and applying formatting. <br>
(3) Event handling for user interactions (typing, clicks, key presses). <br>
(4) Cursor position tracking for accurate suggestion box placement. <br>
