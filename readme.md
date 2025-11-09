# My Video Analyzer Project

This is a Python script for Google Colab. It looks at a video and tries to find interesting stuff in it.

## What it Finds

* **Cuts:** Tries to find when the scene changes.
* **Motion:** Checks if there is a lot of movement in the video.
* **Text:** Tries to read any words on the screen.
* **People/Objects:** Uses a model (YOLO) to count people and other things it sees.

## How to Use

1.  Open the `WhitePanda_Final.ipynb` file in Google Colab.
2.  Run the cells one by one, from top to bottom.
3.  When you run the "Video Upload" cell, pick a video file from your computer.
4.  Keep running the rest of the cells.
5.  The last cell will automatically download a file called `video_output.json` with all the results.

## Output

a file named `video_output.json` is created. open it in any text editor to see what the script found.