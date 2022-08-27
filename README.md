# Energy flow animation

This is an animated SVG which illustarates the energy flow of your PV system.  
* The direction of the current flow is animated by some moving bubbles
* The bubbles move faster at higher power

# Requirements
* The SVG and the HTML file have to be on the same server. This example will not run on your local PC!

# Functions
- SetBatteryStateOfCharge(value) 
   - Value: Will set the state of charge text and will animate the battery symbol

- Animation(Power, x_dir, y_dir, invert, bubble_id, text_id, MaxPower)
   - Power: Power in Watt
      - Positive values --> Bubble is moving positive
      - Negative values --> Bubble is moving negative
      - 0 --> Bubble is invisible
   - x_dir: true --> bubble is moving left to right (Use the values from the example)
   - y_dir: true --> bubble is moving from top to bottom (Use the values from the example)
   - invert: true --> invert the moving direction of the bubble 
   - bubble_id --> Use the values from the example
   - text_id --> Use the values from the example
   - MaxPower  --> The bubble will move faster with rising power values. The bubble will move with maximum speed if this value will be exceeded