# Inside the CPU

An interactive, single-page lesson on how a simple CPU runs `x = x + 1`.

- **3D lab** (three.js): step through fetch–decode–execute with animated transfers between PC, MAR, MDR, CIR, CU, ALU, ACC and RAM over the address, data and control buses.
- **Opcode & operand**: click bits to decode 8-bit instructions (4-bit opcode, 4-bit operand).
- **Adding with gates**: AND/OR/XOR, an interactive full adder, and an 8-bit ripple-carry adder with ADD/SUB.
- **Two's complement**: sign-and-magnitude vs two's complement, place-value/negation explorer, and a number wheel.

Open `index.html` in a browser, or serve it with GitHub Pages.

# Ocean Chess

`chess.html` is a complete chess game in one HTML file. It runs entirely in the browser, with no server.

- **2D and 3D boards.** The 3D board uses three.js: drag to orbit, scroll to zoom, click to move. In 2D you can click or drag pieces.
- **Play the computer or a friend.** The computer has 5 difficulty levels (Novice, Casual, Club, Expert, Master). It runs alpha-beta search with quiescence in a Web Worker, so the page stays responsive while it thinks.
- **Full rules.** Castling, en passant, promotion to any piece, check and checkmate. Draws are declared automatically for stalemate (the side to move has no legal moves), threefold repetition, the fifty-move rule and insufficient material.
- **Move record.** Moves are listed in standard notation (SAN). Step back through earlier positions with the arrows or ← →, and copy or download the game as PGN.
- **Speedy mode.** Countdown clocks: 1+0, 3+2, 5+0, 10+0 or 15+10. If your flag falls you lose, unless your opponent has too little material to checkmate, in which case it is a draw.
- **Extras.** Hint, undo (untimed games only), offer a draw, resign, flip the board, sound.
- **Background.** An animated ocean in GitHub-dark colours.

Open `chess.html` in a browser, or serve it with GitHub Pages. The 3D view loads three.js from a CDN.
