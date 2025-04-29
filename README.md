Starter code for CSCI 497F / 597F at WWU University.

To run the code, you may need to install some dependencies. I recommend starting a virtual environment and installing the dependencies there.

Dependencies:
- numpy
- matplotlib

To run the program:

```python
python find_wall.py
```

This will run the main function of the program, which will:

1. Generate simulated sensor data given a list of the endpoints of the wall, and the position of the robot.
2. Print this simulated data to the console, and save in a CSV (comma separated value) file, which you can open in a spreadsheet or import into another program to process the data (if you don't want to use Python).
3. Runs the `fit_line` function (empty right now), where you should implement your least squares fit routine. You do not need to implement least squares from scratch, although you should read about it in the recommended reading to understand what is happening.
    - [The documentation for Numpy's least squares function](https://numpy.org/doc/stable/reference/generated/numpy.linalg.lstsq.html)
4. Visualizes the results (another window should open), showing the robot with its orientation indicated with a line, as well as the "ground truth" of what the sensor data is reporting, and a line indicating your computed best-fit line for the data.
