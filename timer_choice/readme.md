# Timer Choice Web Page

## Overview
The Timer Choice web page is a simple and interactive tool designed to facilitate icebreaker sessions. It provides a countdown timer and random choice functionality, making it ideal for group activities, decision-making, and fun challenges.

## Features

### Timer Functionality
- **Predefined Timer Options**: Choose from 1, 2, 3, 5, or 10-minute timers by clicking on the corresponding button.
- **Custom Timer**: Enter a custom time in `mm:ss` format to set a timer for any duration.
- **Visual Countdown**: A large circle displays the remaining time, changing colors based on the time left:
  - Light Blue at the start.
  - Green when 20% of the time remains.
  - Orange when 10% of the time remains.
  - Red when the timer elapses.
- **Automatic Start**: The timer starts immediately when a predefined or custom time is selected.

### Random Choice Functionality
- **Random Choice 1**: Selects a random option from a predefined list (`list1.js`) and displays it on the page.
- **Random Choice 2**: Selects a random option from another predefined list (`list2.js`) and displays it on the page.

### General
- **Responsive Design**: The web page is designed to work seamlessly across different devices and screen sizes.
- **Clean and Intuitive Interface**: Easy-to-use layout for quick interaction.

## Use Case
This tool is perfect for icebreaker sessions, where participants can:
- Use the timer to manage activity durations.
- Use the random choice buttons to select topics, questions, or tasks for group discussions or challenges.

## Technical Details
- **HTML, CSS, and JavaScript**: The web page is built using standard web technologies for easy deployment and use.
- **No Server Required**: The lists for random choices are embedded in JavaScript files (`list1.js` and `list2.js`), avoiding CORS issues.
- **Local Usage**: Open the `index.html` file in a browser to use the tool.

## How to Use
1. Open the `index.html` file in your browser.
2. Select a timer option or enter a custom time to start the countdown.
3. Click on the random choice buttons to display a random option from the predefined lists.

## Folder Structure
```
timer_choice/
├── index.html       # Main HTML file
├── list1.js         # Predefined list for Random Choice 1
├── list2.js         # Predefined list for Random Choice 2
├── requirements.md  # Detailed requirements for the tool
├── readme.md        # This README file
```

Enjoy using the Timer Choice tool for your icebreaker sessions!