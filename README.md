General Explanation
• An efficient elevator system should be designed and built using only Web client technologies (html, js, css).
• After loading the page in the browser, the user will see the building that will include the floors, elevators and elevator controls.
• On each floor a call control will be displayed for the elevator that says the number of the floor. Pressing the button will invite an elevator to the floor (even if there is no elevator available at the moment).
• When ordering an elevator to the floor, a descending number representing the number of seconds left until the elevator arrives will be displayed next to the elevator button.
• The elevator algorithm should bring the minimum possible waiting time for the elevator without prolonging the waiting times of those who have already ordered an elevator.
• The number of floors and the number of elevators in the building should be easily defined / changed (by changing settings in the code or configuration file).
• The elevators will move at a speed of half a second to the floor (the animation should be presented smoothly - not for example jumps between the floors), and when they reach the destination (to which the elevator is ordered) they will be delayed for two seconds.
• The system should be built to allow easy viewing of more than one building on the screen (with separate lift system).

User Interface Settings
• Each floor will be displayed with a background of brick. To do this, use the floor definition found in help.css.
• Each floor will be at a total height of 110 pixels.
• A black stripe of 7 pixels will be displayed between each two floors, which will be calculated as part of the height of the floor below it.
• The elevator will be displayed using a given image (elv.png file).
• When the elevator reaches the floor, a given sound must be played (ding.mp3 file).
• To display the elevator reading controls, use the following code format:
<button class = "metal linear"> 0 </ button>
The metal and linear settings are in help.css.
• When pressed, paint the call control text to the elevator in green and return it to its normal color when the elevator reaches it.
