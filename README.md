# Watermark Pictures Project

## Description
This project is a simple web application that allows users to add custom watermarks to their images. Users can upload multiple images, specify watermark text, adjust the watermark rotation angle, and download the watermarked images. The application is built using HTML, CSS, and JavaScript.

---

## Features
1. **Upload Multiple Images**: Supports uploading multiple images at once via the file input field.
2. **Custom Watermark Text**: Allows users to enter their desired watermark text.
3. **Adjustable Watermark Rotation**: Provides an input field to specify the rotation angle of the watermark text (default: 45 degrees).
4. **Download Watermarked Images**: Users can download images with the watermark applied.

---

## File Structure
- **index.html**: Contains the main HTML structure and the JavaScript code.
- **styles.css**: (Optional) Contains additional styles if extracted from inline styles.

---

## How to Use
1. Open the `index.html` file in any modern web browser.
2. Upload one or more images using the "Choose File" button.
3. Enter the desired watermark text in the input field.
4. (Optional) Specify a custom rotation angle for the watermark in degrees.
5. Click the "Apply Watermark" button to process the images.
6. Preview the watermarked images in the "Image Preview" section.
7. Click the "Download Watermarked Images" button to download all processed images.

---

## Requirements
- A modern web browser (Chrome, Firefox, Edge, or Safari).

---

## Customization
### Change Default Rotation Angle
- The default rotation angle is set to 45 degrees. To change this:
  - Open `index.html`.
  - Locate the line:
    ```javascript
    const angle = parseInt(rotationAngle.value) || 45;
    ```
  - Replace `45` with your desired default angle.

### Modify Watermark Style
- The watermark's font, color, and opacity can be adjusted in the `applyWatermark` function:
  ```javascript
  ctx.font = '50px Arial';
  ctx.fillStyle = 'rgba(144, 238, 144, 0.3)';
  ```
  - Change `'50px Arial'` to adjust font size or type.
  - Modify `'rgba(144, 238, 144, 0.3)'` for a different color or opacity.

---

## License
This project is provided as-is for educational purposes. Feel free to modify and use it for personal or commercial projects.

