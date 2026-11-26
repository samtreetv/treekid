# APOLLON / KIDZ PRAY

A standalone first-person gallery. No framework, build, account, or CDN. All visual assets and archive data are inside `index.html`.

## Publish

1. Create a GitHub repository, or open your existing gallery repository.
2. Upload `index.html`, `assets/` (optional), and `.nojekyll` to the repository root on `main`. Commit.
3. In Settings → Pages, choose Deploy from a branch, then `main` and `/ (root)`. Save.
4. Open the Pages URL shown by GitHub.

For a local HTTP preview, run `python3 -m http.server 8000` from this folder and open `http://localhost:8000`. The separately supplied standalone HTML runs directly from disk with music embedded.

## Music and publishing rights

`assets/distant-music.mp3` is the recording supplied by the user (Frank Kim, Spiegel im Spiegel, Arvo Pärt). It is not represented as open-licensed. Include it on a public repository/site only if you have appropriate rights to the composition and recording. Otherwise omit `assets/distant-music.mp3`; the gallery still works silently and visitors can press M to load their own local audio. Also review rights to embedded artwork, photos and archive material before public publication. No blanket asset license is asserted.

The music starts 60–90 seconds after a browser interaction, with a 30-second fade, 0.82× playback and distant spatial processing. N mutes; M loads a local recording.

## Controls

- WASD: walk; drag: look; Q/E: turn; Space: jump.
- Click art to open its editorial folio; Escape to return.
- Click ceiling: X-ray; semicircle above either blue door: polychrome.
- Click blue doors to open; walk through to loop.
- First left window opens; approach and jump to enter freefall. Escape returns.
- Hidden spray can: back-left corner of the room (facing forward from entry), lying on its side. Approach and click. Click surfaces to paint. 1–6 / C select colors; G / Escape put it back. Marks last for the current session.
- V: render mode; Home: entrance.

The skateboard and halfpipe are removed in this release.
