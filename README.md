<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta http-equiv="X-UA-Compatible" content="ie=edge">
<title>React.js Todo App</title>
</head>

<body>
<h1>📝 React.js Todo App</h1>
<p>Check out the live app here: <a href="https://react-cool-todo-app.netlify.app/" target="_blank">Live Demo</a></p>
<p><strong>GitHub Repository:</strong> <a href="https://github.com/dggtn/TodoApp" target="_blank">GitHub Repo</a></p>
<p><strong>Status:</strong> <span id="netlify-status"></span></p>
<p><strong>GitHub Code Size:</strong> <span id="github-size"></span> bytes</p>
<p><strong>Last Commit:</strong> <span id="last-commit"></span></p>
<p><strong>License:</strong> <span id="license"></span></p>

<h2>💻 Tech Stack</h2>
<ul>
    <li><strong>React:</strong> A JavaScript library for building user interfaces.</li>
    <li><strong>TypeScript:</strong> A typed superset of JavaScript that compiles to plain JavaScript.</li>
    <li><strong>Vite:</strong> A fast build tool and development server.</li>
    <li><strong>Vitest:</strong> A testing framework that works seamlessly with Vite.</li>
    <li><strong>Emotion:</strong> A library for writing CSS styles with JavaScript.</li>
    <li><strong>Material UI (MUI):</strong> A popular React component library for building user interfaces.</li>
</ul>

<h2>⚡ Features</h2>
<h3>🔗 Share Tasks by Link or QR Code</h3>
<p>Easily share your tasks with others using a link or QR code. You can even download the QR code for sharing.</p>
<p><strong>Example Link:</strong> <a href="#">Shared Task</a></p>

<h3>🤖 AI Emoji Suggestions</h3>
<p>This feature uses <code>window.ai</code> (currently in an experimental phase) that works in the dev version of Chrome with certain flags enabled. For more information, refer to the <a href="#">documentation</a>.</p>
<p><strong>Code:</strong> <a href="#">src/components/EmojiPicker.tsx</a></p>
<p><strong>AI Emoji:</strong> <span>🤖</span></p>

<h3>🎨 Color Themes</h3>
<p>Users can select from several color themes and toggle between light and dark modes.</p>

<h3>🗣️ Task Reading Aloud</h3>
<p>This feature allows users to have tasks read aloud using the native <code>SpeechSynthesis</code> API. You can choose from a variety of voices.</p>
<p><strong>Task Reading Aloud Example:</strong> <span>🗣️ Listen to Task</span></p>

<h3>📥 Import/Export Tasks</h3>
<p>Import and export your tasks to and from JSON files. This makes it easy to back up tasks or transfer them between devices.</p>
<p><strong>Example Import File:</strong> <a href="#">Download</a></p>

<h3>📴 Progressive Web App (PWA)</h3>
<p>The app is a Progressive Web App (PWA), meaning it can be installed on your device, used offline, and behaves like a native application with shortcuts and badges.</p>
<p><strong>Taskbar Example:</strong> <img src="taskbar.png" alt="Taskbar Example" /></p>

<h3>🔄 Update Prompt</h3>
<p>A custom update prompt notifies users when a new version is available. A simple refresh grants access to the latest features and improvements.</p>

<h3>🔎 Additional Features</h3>
<ul>
    <li>📦 Local and session storage to save tasks locally and retain form data.</li>
    <li>🌐 Native <code>Intl</code> API integration to adapt to your language, timezone, and date preferences.</li>
    <li>🔍 Automatic link highlighting in task descriptions for easy identification.</li>
    <li>🌍 Browser translation support for seamless language translation, making the app accessible worldwide.</li>
    <li>🗂️ Customizable task categories to suit your preferences.</li>
    <li>🗃️ Multi-task selection to perform bulk actions on tasks.</li>
    <li>📱 Responsive design for a smooth experience across all devices.</li>
    <li>😜 Custom emojis with multiple styles, including Apple, Facebook, Twitter, Google, and native options.</li>
</ul>
