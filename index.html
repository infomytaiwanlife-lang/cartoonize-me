<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ToonMe \u2014 Cartoon Avatar Generator</title>
  <link href="https://fonts.googleapis.com/css2?family=Bangers&family=Nunito:wght@400;600;800&display=swap" rel="stylesheet" />
  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    :root {
      --ink:    #1a1a2e;
      --paper:  #fffdf4;
      --yellow: #ffd600;
      --red:    #ff3b3b;
      --blue:   #3b82f6;
      --shadow: 5px 5px 0 var(--ink);
      --radius: 10px;
    }

    body {
      background-color: var(--paper);
      background-image: radial-gradient(circle, #ddd 1px, transparent 1px);
      background-size: 24px 24px;
      font-family: 'Nunito', sans-serif;
      color: var(--ink);
      min-height: 100vh;
    }

    /* \u2500\u2500 HEADER \u2500\u2500 */
    header {
      background: var(--ink);
      padding: 1rem 2rem;
      display: flex;
      align-items: center;
      gap: 1rem;
      border-bottom: 4px solid var(--yellow);
    }

    .logo {
      font-family: 'Bangers', cursive;
      font-size: 2.4rem;
      letter-spacing: 3px;
      color: var(--yellow);
      text-shadow: 3px 3px 0 var(--red);
      line-height: 1;
    }
    .logo span { color: var(--red); text-shadow: 3px 3px 0 #c00; }

    .header-sub {
      color: #aaa;
      font-size: 0.8rem;
      font-weight: 700;
      letter-spacing: 1px;
      text-transform: uppercase;
    }

    /* \u2500\u2500 API KEY BANNER \u2500\u2500 */
    #key-banner {
      background: #fff8dc;
      border-bottom: 3px solid var(--yellow);
      padding: 0.75rem 2rem;
      display: flex;
      align-items: center;
      gap: 1rem;
      flex-wrap: wrap;
    }

    #key-banner label {
      font-weight: 800;
      font-size: 0.85rem;
      white-space: nowrap;
    }

    #key-banner .key-input-wrap {
      display: flex;
      gap: 0.5rem;
      flex: 1;
      min-width: 260px;
      max-width: 480px;
    }

    #key-input {
      flex: 1;
      padding: 0.45rem 0.75rem;
      border: 3px solid var(--ink);
      border-radius: var(--radius);
      font-family: 'Courier New', monospace;
      font-size: 0.85rem;
      background: white;
      box-shadow: 3px 3px 0 var(--ink);
      outline: none;
    }
    #key-input:focus { border-color: var(--blue); box-shadow: 3px 3px 0 var(--blue); }

    .btn-save-key {
      padding: 0.45rem 1rem;
      background: var(--ink);
      color: var(--yellow);
      border: 3px solid var(--ink);
      border-radius: var(--radius);
      font-family: 'Nunito', sans-serif;
      font-weight: 800;
      font-size: 0.8rem;
      cursor: pointer;
      box-shadow: 3px 3px 0 #555;
      transition: transform 0.1s, box-shadow 0.1s;
    }
    .btn-save-key:hover { transform: translate(-1px,-1px); box-shadow: 4px 4px 0 #555; }
    .btn-save-key:active { transform: translate(2px,2px); box-shadow: 1px 1px 0 #555; }

    #key-status { font-size: 0.8rem; font-weight: 700; }
    #key-status.ok   { color: #16a34a; }
    #key-status.warn { color: var(--red); }

    .key-hint { font-size: 0.75rem; color: #777; }
    .key-hint a { color: var(--blue); font-weight: 700; }

    /* \u2500\u2500 MAIN LAYOUT \u2500\u2500 */
    main {
      max-width: 1080px;
      margin: 0 auto;
      padding: 2rem 1.5rem;
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 2rem;
      align-items: start;
    }

    @media (max-width: 720px) { main { grid-template-columns: 1fr; } }

    /* \u2500\u2500 PANEL \u2500\u2500 */
    .panel {
      background: white;
      border: 3px solid var(--ink);
      border-radius: var(--radius);
      box-shadow: var(--shadow);
      overflow: hidden;
    }

    .panel-title {
      background: var(--ink);
      color: var(--yellow);
      font-family: 'Bangers', cursive;
      font-size: 1.3rem;
      letter-spacing: 2px;
      padding: 0.6rem 1.2rem;
    }

    .panel-body { padding: 1.2rem; }

    /* \u2500\u2500 STYLE GRID
