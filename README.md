# Full-Page Web Countdown

A lightweight, full-screen countdown timer built using HTML, CSS, and vanilla JavaScript. The application displays the remaining time until a specified date and can be customised for events, trips, launches, or other scheduled occasions.

## Overview

This project provides a simple and visually focused countdown interface that updates in real time. The countdown calculates the remaining days, hours, minutes, and seconds until the configured target date.

## Features

- Real-time countdown updates every second
- Full-page countdown display
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
- JavaScript

## Installation

Clone the repository:

    git clone https://github.com/your-username/Full-Page-Web-Countdown.git

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

## Future Enhancements

Potential improvements include:

- Adding custom background images
- Supporting user-defined countdowns
- Adding timezone configuration
- Displaying a message when the countdown reaches zero

## License

This project is available under the MIT License.
