# Puzzle Game Project

This is a simple puzzle game project with two different types of puzzles: one using buttons to move the missing piece (Puzzle 1) and another where the user drags puzzle pieces into place (Puzzle 2). The project is built using HTML, CSS, and jQuery.

## Project Structure

The project consists of four main files:

- `home.html` - The homepage of the puzzle game, providing links to both puzzles.
- `puzzle1.html` - A sliding puzzle where users can move pieces using buttons.
- `puzzle2.html` - A drag-and-drop puzzle where users drag pieces to their correct location.
- `UnionSq.jpg` - The background image used in both puzzles.

## Features

- **Home Page**: Links to both puzzles (Puzzle 1 and Puzzle 2).
- **Puzzle 1**: A sliding puzzle where pieces can be moved using buttons (Up, Down, Left, Right).
- **Puzzle 2**: A drag-and-drop puzzle where users drag pieces to their correct location.
- Both puzzles use the `UnionSq.jpg` image as the puzzle image.
- Navigation buttons allow users to switch between the puzzles and the home page.

## Requirements

- A modern web browser (Chrome, Firefox, etc.) with JavaScript enabled.
- jQuery and jQuery UI are used for the puzzle functionality.

## Files

### 1. `home.html`

This is the main entry page of the puzzle game. It contains links to Puzzle 1 and Puzzle 2.

### 2. `puzzle1.html`

This is the first puzzle, where a piece of an image are moved using buttons. It uses jQuery for DOM manipulation and animations to move pieces.

**Features**:
- A 3x3 grid with one empty space.
- Buttons for moving pieces up, down, left, and right.
- The user can solve the puzzle by putting the missing piece in the correct place
-  Includes a "Home" button that will bring users back to the home page.

### 3. `puzzle2.html`

This is the second puzzle, where the pieces are dragged and dropped into their correct positions.

**Features**:
- A 3x3 grid with draggable pieces.
- Pieces are moved into place by dragging them within the grid.
-  Includes a "Home" button that will bring users back to the home page.

### 4. `UnionSq.jpg`

The image used for the puzzles. It should be placed in the same directory as the HTML files to ensure proper loading in both puzzles.
