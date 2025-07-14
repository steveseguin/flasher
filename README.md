# Flash Pattern Website

A mobile-optimized website that displays a flashing pattern at adjustable frame rates.

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

## Technical Details

- Uses HTML5 Canvas for rendering
- RequestAnimationFrame for smooth animation
- Touch-optimized with proper viewport settings
- No external dependencies