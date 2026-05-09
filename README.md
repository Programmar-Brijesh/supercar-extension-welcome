<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Supercar Live Wallpaper 4K – README</title>
    
    <!-- Bootstrap 5 CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Bootstrap Icons -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.css" rel="stylesheet">
    
    <style>
        :root {
            --cyan: #00e5ff;
            --deep: #020812;
            --surface: rgba(10, 20, 40, 0.7);
            --border: rgba(0, 229, 255, 0.15);
        }
        body {
            background: var(--deep);
            color: #e0e6f0;
            font-family: 'Inter', system-ui, -apple-system, sans-serif;
            line-height: 1.7;
        }
        .glass-card {
            background: rgba(5, 12, 30, 0.7);
            backdrop-filter: blur(18px);
            -webkit-backdrop-filter: blur(18px);
            border: 1px solid var(--border);
            border-radius: 20px;
        }
        .text-cyan-gradient {
            background: linear-gradient(135deg, #00e5ff, #0077ff);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            font-weight: 800;
        }
        h1, h2, h3 {
            color: #ffffff;
        }
        h1 {
            border-bottom: 2px solid var(--cyan);
            display: inline-block;
            padding-bottom: 8px;
        }
        h2 {
            border-left: 4px solid var(--cyan);
            padding-left: 15px;
            margin-top: 2.5rem;
            font-weight: 700;
        }
        h3 {
            color: var(--cyan);
            margin-top: 2rem;
        }
        code {
            background: #112233;
            color: var(--cyan);
            padding: 2px 8px;
            border-radius: 5px;
            font-family: 'Fira Code', monospace;
        }
        pre {
            background: #0a1628;
            border: 1px solid var(--border);
            border-radius: 12px;
            padding: 20px;
            color: #d0dae8;
        }
        a {
            color: var(--cyan);
            text-decoration: none;
            font-weight: 500;
        }
        a:hover {
            color: #33ffff;
            text-decoration: underline;
        }
        .badge-custom {
            background: rgba(0,229,255,0.1);
            border: 1px solid var(--cyan);
            color: var(--cyan);
            font-size: 0.85rem;
            padding: 5px 12px;
            border-radius: 50px;
            margin: 0 4px 8px 0;
            display: inline-block;
        }
        .feature-list {
            list-style: none;
            padding-left: 0;
        }
        .feature-list li {
            padding: 8px 0;
            border-bottom: 1px solid rgba(255,255,255,0.05);
        }
        .command-table {
            background: rgba(0,0,0,0.3);
            border-radius: 12px;
            overflow: hidden;
        }
        .command-table table {
            margin-bottom: 0;
        }
        .command-table th {
            background: rgba(0,229,255,0.1);
            color: var(--cyan);
        }
        .command-table td, .command-table th {
            border-color: rgba(255,255,255,0.05);
        }
        footer {
            border-top: 1px solid rgba(255,255,255,0.1);
            padding: 30px 0;
        }
    </style>
</head>
<body>

<div class="container py-5">
    <!-- Back to home link -->
    <a href="index.html" class="btn btn-outline-info btn-sm mb-4">← Back to Home</a>

    <!-- Title and Badges -->
    <div class="glass-card p-4 p-md-5 mb-4">
        <h1 class="fw-bold mb-3">
            🏎️ <span class="text-white">Supercar Live Wallpaper 4K</span><br>
            <small class="text-cyan-gradient">Racing New Tab with Voice & Cursor Effects</small>
        </h1>
        <p class="lead" style="color: #b0c4de;">
            Transform every new tab into a high‑octane cockpit with live wallpapers, HUD stats, voice commands & futuristic cursor effects.
        </p>
        <div class="d-flex flex-wrap align-items-center gap-2 mb-3">
            <span class="badge-custom"><i class="bi bi-google-chrome"></i> Chrome Web Store</span>
            <span class="badge-custom"><i class="bi bi-git"></i> Version 1.0</span>
            <span class="badge-custom"><i class="bi bi-file-earmark-code"></i> Manifest V3</span>
            <span class="badge-custom"><i class="bi bi-shield-lock"></i> Privacy First</span>
        </div>
    </div>

    <!-- Features -->
    <h2>🔥 Features</h2>
    <div class="glass-card p-4">
        <ul class="feature-list">
            <li>🎥 <strong>4K Live Wallpapers</strong> – Formula Racing & Matrix loops, smooth video playback</li>
            <li>🕒 <strong>Personalised Clock</strong> – Greeting, live time, and date (name stored locally)</li>
            <li>🔍 <strong>Smart Search Bar</strong> – Google search or direct URL navigation</li>
            <li>🏁 <strong>HUD Performance Stats</strong> – Animated RPM & speed gauges (pure eye candy)</li>
            <li>🧲 <strong>Magnetic Quick‑Dock</strong> – Add your favourite sites with a hover lift effect</li>
            <li>🎤 <strong>Jarvis‑Style Voice Assistant</strong> – Click the AI orb & speak commands</li>
            <li>🖱️ <strong>5 Futuristic Cursor Effects</strong> – Cyber Trail, Neon Particles, Matrix Code, HUD Ring, Lightning Flow</li>
            <li>🎨 <strong>Customizable Dashboard</strong> – Drag, resize, show/hide widgets, reset layout</li>
            <li>🔒 <strong>Privacy First</strong> – All data stored locally; no account needed</li>
        </ul>
    </div>

    <!-- Screenshot / Preview -->
    <h2>📸 Screenshot</h2>
    <div class="glass-card p-4 text-center">
        <img src="images/dashboard-preview.png" alt="Dashboard preview" class="img-fluid rounded-4" style="max-width: 600px;">
        <p class="text-secondary mt-2"><em>Your dashboard in action</em></p>
    </div>

    <!-- Installation -->
    <h2>🚀 Installation</h2>
    <div class="glass-card p-4">
        <ol>
            <li>Install from the <strong>Chrome Web Store</strong> (link coming soon).</li>
            <li>Open a <strong>New Tab</strong> – the dashboard appears instantly.</li>
            <li>Enter your name on the welcome popup (stored only on your device).</li>
            <li>(Optional) Enable <strong>Incognito</strong> support in <code>chrome://extensions</code>.</li>
        </ol>
    </div>

    <!-- Voice Commands -->
    <h2>🎤 Voice Commands</h2>
    <div class="glass-card p-4 command-table">
        <table class="table table-dark table-borderless">
            <thead>
                <tr>
                    <th>Command</th>
                    <th>Action</th>
                </tr>
            </thead>
            <tbody>
                <tr><td><code>"Open YouTube"</code></td><td>Opens YouTube in a new tab</td></tr>
                <tr><td><code>"Matrix wallpaper"</code></td><td>Switches to Matrix background</td></tr>
                <tr><td><code>"Neon particles"</code></td><td>Changes cursor effect</td></tr>
                <tr><td><code>"Hide clock"</code></td><td>Toggles clock visibility</td></tr>
                <tr><td><code>"Customize mode"</code></td><td>Enables drag‑and‑drop layout</td></tr>
            </tbody>
        </table>
        <div class="mt-3 p-3 rounded-3" style="background: rgba(0,229,255,0.05); border-left: 3px solid var(--cyan);">
            <i class="bi bi-info-circle text-cyan"></i> <strong>Privacy Note:</strong> Voice uses the browser's built‑in Web Speech API and sends audio to Google for speech‑to‑text. No audio is stored.
        </div>
    </div>

    <!-- Tech Stack -->
    <h2>🛠️ Tech Stack</h2>
    <div class="glass-card p-4">
        <ul>
            <li><strong>Chrome Extension (Manifest V3)</strong></li>
            <li>Vanilla JavaScript (no frameworks)</li>
            <li>Interact.js for drag‑and‑drop</li>
            <li>HTML5 video backgrounds</li>
            <li>CSS custom effects</li>
        </ul>
    </div>

    <!-- Project Structure -->
    <h2>📁 Project Structure</h2>
    <div class="glass-card p-4">
        <pre>
supercar-extension/
├── manifest.json
├── newtab.html
├── newtab.css
├── newtab.js
├── assets/
│   ├── videos/
│   └── js/
│       └── interact.min.js
└── icons/
    ├── icon16.png
    ├── icon48.png
    └── icon128.png
        </pre>
    </div>

    <!-- Related Pages -->
    <h2>🔗 Related Pages</h2>
    <div class="glass-card p-4 d-flex flex-wrap gap-3">
        <a href="https://supercar-extension-welcome.netlify.app" target="_blank" class="btn btn-outline-info">
            <i class="bi bi-house-door"></i> Landing Page
        </a>
        <a href="https://supercar-extension-welcome.netlify.app/privacy" target="_blank" class="btn btn-outline-info">
            <i class="bi bi-shield-check"></i> Privacy Policy
        </a>
        <a href="https://supercar-extension-welcome.netlify.app/support" target="_blank" class="btn btn-outline-info">
            <i class="bi bi-headset"></i> Support
        </a>
    </div>

    <!-- Contributing -->
    <h2>🤝 Contributing</h2>
    <div class="glass-card p-4">
        <p>Found a bug or want a feature? Open an issue on <a href="https://github.com/yourusername/supercar-extension/issues" target="_blank">GitHub</a>. Pull requests are welcome!</p>
    </div>

    <!-- License -->
    <h2>📜 License</h2>
    <div class="glass-card p-4">
        <p>MIT License – feel free to use, modify, and share.</p>
    </div>

    <!-- Footer -->
    <div class="text-center mt-5">
        <p class="small">
            Built with ⚡ by <a href="#">Developer Brijesh</a>
        </p>
    </div>
</div>

<footer class="text-center py-4 border-top border-dark">
    <p class="small mb-1">© 2026 Supercar Live Wallpaper 4K. Not affiliated with any car brand.</p>
    <p class="small text-secondary">Chrome is a trademark of Google LLC.</p>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
