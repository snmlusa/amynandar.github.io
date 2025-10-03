<html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title "Mystery — Independent Music Band" /> <title
  <meta name="description" content="Mystery — Independent Music Band" for GitHub Pages. Stream tracks, show cover art, and link to downloads." />
  <link rel="stylesheet" href="assets/css/style.css" />
</head>
<body>
  <main class="wrap">
    <header class="hero">
      <img class="cover" src="assets/cover.jpg" alt="Album cover — replace assets/cover.jpg" />
      <div class="meta">
        <h1>Mystery<h1>
        <p class="tagline">Fans page မှာ နွေးထွေးစွာကြိုဆိုပါ၏ </p>
        <div class="actions">
          <a class="btn" href="#player">Open Player</a>
          <a class="btn ghost" href="#tracks">View Tracks</a>
        </div>
      </div>
    </header>

    <section id="player" class="player">
      <div class="player-left">
        <img id="now-cover" src="assets/cover.jpg" alt="Now playing cover" />
      </div>

      <div class="player-right">
        <div class="now">
          <div class="now-title" id="now-title">Select a track</div>
          <div class="now-artist" id="now-artist">—</div>
        </div>

        <div class="controls">
          <button id="prev" title="Previous">⏮</button>
          <button id="play" title="Play/Pause">▶️</button>
          <button id="next" title="Next">⏭</button>
        </div>

        <div class="progress-wrap">
          <input id="progress" type="range" min="0" max="100" value="0" />
          <div class="time">
            <span id="time-current">0:00</span>
            <span id="time-total">0:00</span>
          </div>
        </div>

        <div class="player-actions">
          <a id="download" class="btn small" href="#" download>Download</a>
          <a id="external" class="btn small ghost" href="#" target="_blank" rel="noopener">Open in new tab</a>
        </div>
      </div>
    </section>

    <section id="tracks" class="tracks">
      <h2>Tracks</h2>
      <ul id="playlist">
        <!-- Example tracks. Replace href src values with your real files in /tracks/ -->
        <li data-src="tracks/track1.mp3" data-title="Sunset Drive" data-artist="Artist Name" data-cover="assets/cover-1.jpg">
          <div class="track-meta">
            <strong>Sunset Drive</strong>
            <span class="artist">Artist Name</span>
          </div>
          <div class="track-actions">
            <button class="play-btn" title="Play">Play</button>
            <a class="download-link" href="tracks/track1.mp3" download title="Download">⬇</a>
          </div>
        </li>

        <li data-src="tracks/track2.mp3" data-title="Night City" data-artist="Artist Name" data-cover="assets/cover-2.jpg">
          <div class="track-meta">
            <strong>Night City</strong>
            <span class="artist">Artist Name</span>
          </div>
          <div class="track-actions">
            <button class="play-btn" title="Play">Play</button>
            <a class="download-link" href="tracks/track2.mp3" download title="Download">⬇</a>
          </div>
        </li>

        <li data-src="tracks/track3.mp3" data-title="Ocean Echoes" data-artist="Artist Name" data-cover="assets/cover-3.jpg">
          <div class="track-meta">
            <strong>Ocean Echoes</strong>
            <span class="artist">Artist Name</span>
          </div>
          <div class="track-actions">
            <button class="play-btn" title="Play">Play</button>
            <a class="download-link" href="tracks/track3.mp3" download title="Download">⬇</a>
          </div>
        </li>
      </ul>
    </section>

    <footer class="site-footer">
      <p>Made with ♥ — put your credits, license, or links here.</p>
      <p>
        Example: <a href="https://github.com/yourname/yourrepo" target="_blank" rel="noopener">Source on GitHub</a>
      </p>
    </footer>
  </main>

  <!-- Minimal player audio & script -->
  <audio id="audio" preload="metadata"></audio>
  <script src="assets/js/player.js"></script>
</body>
</html>
