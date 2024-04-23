# tetris
My ascii/cli rendition of tetris.

<img src=docs/.gif width=500px>

## Installation

### Source
If on linux, install `libncursesw5-dev` as dependency.

```bash
git clone 'https://github.com/svish001/tetris' && cd tetris
make
sudo make install
```
### Homebrew
```bash
brew tap svish001/tap
brew install tetris
```

## Usage 

To begin the game, simply type `tetris` in the terminal. Levels can be specified by the flag `--start-level x` (where x is a number 1-25). The ghost block can be turned on from the command line as well, with `--easy`.

### Control:
Use the arrow keys to control the falling blocks:  
- <kbd>e</kbd> to enable/disable the ghost block
- <kbd>↑</kbd> to rotate the falling block
- <kbd>→</kbd> to move right
- <kbd>←</kbd> to move left
- <kbd>↓</kbd> to soft drop. There are known bugs with soft dropping that will be fixed relatively soon. If the program is segfaulting for you, this is likely why.
- <kbd>SPACE</kbd> to hard drop
- <kbd>CTRL</kbd>+<kbd>C</kbd> at any time to quit the game
