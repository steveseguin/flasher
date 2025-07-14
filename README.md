# Flash Pattern Website

A mobile-optimized website that displays a flashing pattern at adjustable frame rates.

## Features

- Displays a repeating color pattern: black → white → black → white → blue → white
- Default frame rate: 30 FPS
- Touch/click controls:
  - Tap top half of screen: Increase speed by 0.5 FPS
  - Tap bottom half of screen: Decrease speed by 0.5 FPS
- Real-time FPS and frame time display
- Fully responsive and optimized for mobile devices

## Usage

Simply open `index.html` in a web browser. The page will start flashing immediately at 30 FPS.

## Technical Details

- Uses HTML5 Canvas for rendering
- RequestAnimationFrame for smooth animation
- Touch-optimized with proper viewport settings
- No external dependencies