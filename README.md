# Flash Pattern Website

A mobile-optimized website that displays a flashing pattern at adjustable frame rates, plus a visual timer for capturing time differences through an out-of-focus camera.

## Features

- Displays a repeating color pattern: black → white → black → white → blue → white
- Default frame rate: 1 FPS
- Touch/click controls:
  - Tap top half of screen: Increase speed by 5%
  - Tap bottom half of screen: Decrease speed by 5%
- Real-time FPS and frame time display
- Fully responsive and optimized for mobile devices

## Usage

Simply open `index.html` in a web browser. The page will start flashing immediately at 1 FPS.

## Timer Page (timer.html)

A visual timer designed to be readable even when photographed with an out-of-focus camera:

- Large, high-contrast time display (MM:SS format)
- Extra-large milliseconds display (000-999)
- Moving bar pattern that changes every 100ms for visual reference
- Tap anywhere to start/stop the timer
- Black background with white text for maximum contrast

## Technical Details

- Uses HTML5 Canvas for rendering (index.html)
- RequestAnimationFrame for smooth animation
- Touch-optimized with proper viewport settings
- No external dependencies