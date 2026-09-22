# Hand Clash

Hand Clash is a single-file rock, paper, scissors game with a steel-and-brass duel aesthetic. Everything lives in one HTML file with no external libraries, fonts, or images, so it runs straight from the file system or from GitHub Pages with nothing to build.

Open hand-clash.html in a browser to play. Pick rock, paper, or scissors from the row of brass-rimmed buttons at the bottom, and the two pads in the arena above will lunge toward each other to reveal both hands. A short headline in the center calls the round, and the scoreplate in the header keeps a running tally of wins, draws, and losses for as long as the page stays open. Scores reset on reload since there's no storage involved.

The whole thing is plain HTML, CSS, and vanilla JavaScript, so it's easy to restyle or extend. The hand icons are inline SVGs drawn in the markup and reused by the script when it fills in each round's result, and the color palette is defined as a small set of CSS variables near the top of the stylesheet if you want to retheme it.
