# User Stories for Timer Choice Web Page

## Timer Functionality
1. **As a user**, I want to see timer options for 1, 2, 3, 5, and 10 minutes as buttons, to start the timer countdown so that I can choose the duration that suits my needs.
    - The timer options should be clearly labeled and easy to understand.
    - The timer should start counting down when I click on one of the buttons.
    - The timer should display the remaining time in a large, easy-to-read format.
    - The timer should be visually distinct from the random choice buttons.
    - The timer should reset when I click on a different timer option.
    - The timer should not start automatically when the page loads.
2. **As a user**, I want the timer to start counting down in a large circle when I click the timer option so that I can visually track the remaining time.
3. **As a user**, I should be able to provide a custom time option in mm:ss format so that I can set a timer for any duration I need.
    - The custom time option should be clearly labeled and easy to understand.
    - The custom time should be validated to ensure it is in the correct format (mm:ss).
    - The timer should start counting down when I click on the custom time button.
    - The timer should display the remaining time in a large, easy-to-read format.
    - The timer should reset when I click on a different timer option.
    - The timer should not start automatically when the page loads.
4. **As a user**, I want the circle to change colors based on the remaining time:
    - Light Blue at the start.
    - Green when 20% of the time remains.
    - Orange when 10% of the time remains.
    - Red when the timer elapses.
    - The timer should reset when I click on a different timer option.
    - The timer should not start automatically when the page loads.

## Random Choice Functionality
5. **As a user**, I want a button to select a random choice from a predefined list in one file so that I can quickly make a decision.
    - The random choice should be displayed prominently on the web page.
    - The random choice should be visually distinct from the timer display.
6. **As a user**, I want a second button to select a random choice from another predefined list in a separate file so that I can explore different options.
    - The second random choice should be displayed prominently on the web page.
    - The second random choice should be visually distinct from the timer display.

## General
7. **As a user**, I want the web page to have a clean and intuitive design so that I can easily interact with the timer and buttons.
8. **As a user**, I want the timer and buttons to be responsive and work seamlessly across different devices and screen sizes.

## Technical
9. **As a developer**, I want to handle the "fetch from origin 'null' has been blocked by CORS policy" error by using a client-side workaround such as a proxy or browser extension.
10. **As a developer**, I want to ensure that the timer and random choice functionalities are implemented using JavaScript so that they are interactive and dynamic.
11. **As a developer**, I want to ensure that the timer and random choice functionalities are implemented using HTML and CSS for the layout and styling so that they are visually appealing.
