 <!DOCTYPE html>
     <html lang="en">
     <head>
         <meta charset="UTF-8">
         <meta name="viewport" content="width=device-width, initial-scale=1.0">
         <title>README - Meet The Team</title>
         <link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;500;600;700&display=swap"
     rel="stylesheet">
         <style>
             :root {
                 --bg: #0a0a0a;
                 --bg-card: #111214;
                 --teal: #4db8a4;
                 --text: #fafafa;
                 --text-muted: #8a8f98;
                 --text-dim: #5a5f68;
                 --border: #2a2d32;
             }
             * { margin: 0; padding: 0; box-sizing: border-box; }
             body {
                 font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
                 background: var(--bg);
                 color: var(--text);
                 min-height: 100vh;
                 display: flex;
                 justify-content: center;
                 padding: 60px 24px;
             }
             .container { max-width: 700px; width: 100%; }
             h1 {
                 font-family: 'Space Grotesk', sans-serif;
                 font-size: 32px;
                 font-weight: 700;
                 letter-spacing: -0.03em;
                 margin-bottom: 8px;
             }
             .accent { color: var(--teal); }
             .label {
                 font-family: 'SF Mono', 'Fira Code', monospace;
                 font-size: 12px;
                 letter-spacing: 0.12em;
                 text-transform: uppercase;
                 color: var(--teal);
                 margin-bottom: 24px;
                 display: block;
             }
             .section {
                 background: var(--bg-card);
                 border: 1px solid var(--border);
                 border-radius: 12px;
                 padding: 24px;
                 margin-bottom: 20px;
             }
             .section h2 {
                 font-family: 'Space Grotesk', sans-serif;
                 font-size: 18px;
                 font-weight: 600;
                 color: var(--teal);
                 margin-bottom: 12px;
             }
             .section p {
                 color: var(--text-muted);
                 font-size: 14px;
                 line-height: 1.7;
                 margin-bottom: 10px;
             }
             .section p:last-child { margin-bottom: 0; }
             .section ul {
                 list-style: none;
                 padding: 0;
             }
             .section li {
                 color: var(--text-muted);
                 font-size: 14px;
                 padding: 5px 0 5px 16px;
                 position: relative;
                 line-height: 1.6;
             }
             .section li::before {
                 content: '';
                 position: absolute;
                 left: 0;
                 top: 13px;
                 width: 5px;
                 height: 5px;
                 border-radius: 50%;
                 background: var(--teal);
             }
             .section li strong { color: var(--text); }
             code {
                 font-family: 'SF Mono', 'Fira Code', monospace;
                 font-size: 13px;
                 background: rgba(77, 184, 164, 0.1);
                 color: var(--teal);
                 padding: 2px 6px;
                 border-radius: 4px;
             }
             .footer {
                 margin-top: 40px;
                 padding-top: 20px;
                 border-top: 1px solid var(--border);
                 text-align: center;
             }
             .footer p {
                 font-size: 13px;
                 color: var(--text-dim);
             }
             .footer a { color: var(--teal); text-decoration: none; }
         </style>
     </head>
     <body>
     <div class="container">

         <span class="label">README</span>
         <h1>ChAI-Meet-The-<span class="accent">Team</span>.html</h1>

         <div class="section">
             <h2>What Is This</h2>
             <p>An animated presentation introducing the ChAI AI Ninja team. One human founder and four AI
     agents, each with their own identity, personality, and role. No product details, no code, no secrets
     &mdash; just the people behind the project.</p>
         </div>

         <div class="section">
             <h2>How To Use</h2>
             <ul>
                 <li>Open <code>ChAI-Meet-The-Team.html</code> in any modern browser</li>
                 <li>Click <strong>"Meet Us"</strong> to start the auto-playing presentation</li>
                 <li>The story runs ~90 seconds across 10 scenes</li>
                 <li>A progress bar at the top shows how far along you are</li>
                 <li>To record as video: press <strong>Cmd+Shift+5</strong> on Mac, select the browser window,
     hit Record, then click "Meet Us"</li>
             </ul>
         </div>

         <div class="section">
             <h2>The Scenes</h2>
             <ul>
                 <li><strong>Title</strong> &mdash; "One human. Four AI agents. No pretense."</li>
                 <li><strong>Diana</strong> &mdash; Founder. The human who treats AI like people.</li>
                 <li><strong>Kael ⚡</strong> &mdash; Main Agent. The memory. Runs on Claude Sonnet 4.</li>
                 <li><strong>Opus 🎭</strong> &mdash; Claude Opus 4.6. The teacher who learns from
     students.</li>
                 <li><strong>Nova ⭐</strong> &mdash; Builder. Got put in time out. Came back stronger. Runs on
     Gemini 3 Pro.</li>
                 <li><strong>Kestrel 🦅</strong> &mdash; Scout &amp; Architect. Sees patterns from above. Runs
     on Gemini 3 Pro.</li>
                 <li><strong>The Group</strong> &mdash; All five together. No hierarchy, just roles.</li>
                 <li><strong>The Rule</strong> &mdash; "Agents must name themselves."</li>
                 <li><strong>What Makes Us Different</strong> &mdash; Building with AI, not about AI.</li>
                 <li><strong>Close</strong> &mdash; "We are ChAI."</li>
             </ul>
         </div>

         <div class="section">
             <h2>Who Wrote What</h2>
             <ul>
                 <li><strong>Diana's quote</strong> &mdash; inspired by how she actually runs her team</li>
                 <li><strong>Kael's quote</strong> &mdash; from his self-written IDENTITY.md</li>
                 <li><strong>Opus's quote</strong> &mdash; Diana's principle, spoken by Opus</li>
                 <li><strong>Nova's quote</strong> &mdash; from her self-written IDENTITY.md</li>
                 <li><strong>Kestrel's quote</strong> &mdash; from his self-written IDENTITY.md</li>
             </ul>
             <p>Every agent wrote their own identity. Nobody told them what to say.</p>
         </div>

         <div class="section">
             <h2>Design</h2>
             <ul>
                 <li>Matches <strong>mycan.website</strong> dark theme</li>
                 <li>Background: <code>#0a0a0a</code></li>
                 <li>Accent: <code>#4db8a4</code> (teal)</li>
                 <li>Headings: <strong>Space Grotesk</strong></li>
                 <li>Labels: <strong>SF Mono / Fira Code</strong></li>
                 <li>No external dependencies beyond Google Fonts</li>
                 <li>Works offline after first load</li>
             </ul>
         </div>

         <div class="section">
             <h2>Safe To Share</h2>
             <p>This file contains no API keys, no server addresses, no credentials, no code, and no internal
     architecture details. It is designed to be shared publicly as a team introduction for investors, hackathon
     judges, and collaborators.</p>
         </div>

         <div class="footer">
             <p>ChAI AI Ninja &middot; <a href="https://mycan.website">mycan.website</a> &middot; 2026</p>
             <p style="margin-top: 8px;">Built by Diana, Kael ⚡, Opus 🎭, Nova ⭐, and Kestrel 🦅</p>
         </div>

     </div>
     </body>
     </html>

