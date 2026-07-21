# Full-Page Web Countdown

A lightweight, full-screen countdown timer built using HTML, CSS, and vanilla JavaScript. The application displays the remaining time until a specified date and can be customised for events, trips, launches, or other scheduled occasions.

## Overview

This project provides a simple and visually focused countdown interface that updates in real time. The countdown calculates the remaining days, hours, minutes, and seconds until the configured target date.

## Features

- Real-time countdown updates every second
- Full-page countdown display
- Customisable background image
- Displays remaining:
  - Days
  - Hours
  - Minutes
  - Seconds
- Easily configurable target date and event information
- No dependencies or external libraries required

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)

## Installation

Clone the repository:

    git clone https://github.com/Tom-Bow/Full-Page-Web-Countdown.git

Open `index.html` in a web browser to run the application.

No additional setup or dependencies are required.

## Configuration

### Updating the Countdown Date

The target date can be changed in `script.js`:

    const targetDate = new Date("2026-01-18T14:50:00").getTime();

Replace the value with the required date and time.

### Updating Event Information

The displayed location and date can be modified in `index.html`:

    <div class="message">
        <p>Tromsø, Norway</p>
        <p>Sunday, 18th Jan 2026</p>
    </div>

Update the text values to match the desired event.

### Changing the Background Image

The countdown background can be customised by replacing the existing image in the `resources` folder.

To update the background:

1. Add your desired image to the `resources` folder.
2. Rename the image to:

    background.jpg

3. Replace the existing file.

The new image will automatically be used as the countdown background.

## Project Structure

    Full-Page-Web-Countdown/
    |
    ├── resources/
    │   └── background.jpg
    ├── index.html
    ├── styles.css
    ├── script.js
    └── README.md

## Future Enhancements

Potential improvements include:

- Supporting additional image formats
- Allowing users to configure the countdown without editing source files
- Adding timezone selection
- Displaying a message when the countdown reaches zero
