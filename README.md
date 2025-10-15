# HornPub

🎭 A dynamic video player with real-time visual filters for tango videos.

## Features

- **Video Player**: HTML5 video player with standard controls (play, pause, volume, fullscreen)
- **Three Dynamic Filters**:
  - 🎨 **Saturation**: Adjust color intensity (0-200%)
  - 🌈 **Hue Rotate**: Shift colors through the spectrum (0-360°)
  - 💡 **Brightness**: Control video brightness (0-200%)
- **Reset Button**: Quickly restore all filters to default values
- **Responsive Design**: Works on desktop and mobile devices
- **Real-time Updates**: Filters apply instantly as you adjust sliders

## Usage

1. Open `index.html` in a web browser
2. Replace the video source URL with your tango video
3. Use the three sliders to adjust video appearance:
   - Drag sliders left or right to change values
   - Watch the video update in real-time
4. Click "Reset Filters" to restore default settings

## Customization

To use your own tango video, edit `index.html` and replace the video source:

```html
<source src="YOUR_VIDEO_URL.mp4" type="video/mp4">
```

## Technologies

- Pure HTML5, CSS3, and JavaScript
- No external dependencies or frameworks
- CSS filters for real-time video manipulation
- Responsive design with modern UI