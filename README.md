# Chess Lab

A single-page trainer that runs entirely in the browser.

- Pulls a player's games from the Chess.com public API
- Forecasts the rating trend (damped-trend exponential smoothing on end-of-week rating)
- Scores every opening against the expected score from rating gaps and flags leaks
- Repertoire drills with a click-to-move board
- Puzzles from the Lichess API, with adaptive difficulty and a weekly record
- Engine blunder scans of your own games (Stockfish 10 in WebAssembly, depth 11)
- Strategy findings from clock, session, and game-length patterns
- Week-over-week review with export/import of records

Everything is stored in the browser (localStorage). Use Export records to move progress between devices.

Credits: Stockfish (GPL v3) compiled by Niklas Fiekas; chess.js (BSD) by Jeff Hlywa; piece set by Colin M.L. Burnett (CC BY-SA 3.0).
