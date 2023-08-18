# automatic-umbrella

This code prompts the user for input related to manufacturing bowling balls, performs calculations based on the provided information, and then displays the amount of filler required for the given number of balls. Here's a step-by-step explanation of the code:

1. **Prompt User for Inputs**:
   - The code starts by prompting the user for three inputs:
     - `num_balls`: The number of bowling balls to be manufactured.
     - `diameter`: The diameter of each bowling ball in inches.
     - `core_volume`: The core volume of each bowling ball in inches cubed.

2. **Calculate Radius**:
   - After receiving the input, the code calculates the radius of the bowling ball using the formula `radius = diameter / 2`.

3. **Calculate Filler Volume**:
   - The code then calculates the volume of the filler material required for each bowling ball using the formula for the volume of a sphere minus the core volume.
   - The formula used is `(4 / 3) * π * radius^3 - core_volume`, where `π` is the mathematical constant pi.

4. **Calculate Total Filler**:
   - The total filler required for the given number of bowling balls is calculated by multiplying the filler volume by the `num_balls`.

5. **Print Result**:
   - Finally, the code prints the calculated total filler amount using the `print` statement. The output message indicates the amount of filler required in inches cubed.

In summary, this code calculates and displays the amount of filler material required to manufacture a given number of bowling balls, based on their diameter and core volume. The calculations involve calculating the radius of the balls, determining the filler volume for each ball, and then computing the total filler needed for the specified number of balls.
