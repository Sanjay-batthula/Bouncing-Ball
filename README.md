# Bouncing Ball

This is a simple Python project that demonstrates a bouncing ball animation using Tkinter.

## Features
- The ball moves continuously within a window.
- It bounces off the walls when it reaches the edges.
- Smooth animation using `canvas.after()`.

## Requirements
- Python 3.x
- Tkinter (included with most Python installations)

## Installation
1. Clone the repository:
   
   git clone https://github.com/your-username/Bouncing-Ball.git
  
2. Navigate to the project directory:

   cd Bouncing-Ball

3. Run the script:
   
   python main.py

## Code Explanation
- **Creating the main window:** The `Tk` class is used to create the application window.
- **Creating a canvas and a ball:** A `Canvas` widget is used to draw a ball using `create_oval()`.
- **Moving the ball:** The `moveBall()` function updates the ball’s position and reverses its direction when it hits the window edges.

## Usage
Run `main.py` to start the animation. The ball will continuously bounce off the edges of the canvas.

## License
This project is open-source and available under the [MIT License](LICENSE).

