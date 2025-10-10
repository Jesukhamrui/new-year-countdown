# How to Add Your Photo

To add a profile photo to the birthday animation:

1. **Add your photo file** to the same folder as the HTML file
2. **Rename your photo** to `profile.jpg` (or update the filename in the JavaScript)
3. **Supported formats**: JPG, PNG, GIF
4. **Recommended size**: Square image (e.g., 300x300px or 500x500px)

## Alternative Method:
If you want to use a different filename, edit the `happy birtday.js` file and change this line:
```javascript
profileImage.src = "profile.jpg"; // Change this to your image file name
```

For example:
```javascript
profileImage.src = "my-photo.png";
```

## Image Requirements:
- The image will automatically be displayed as a small circle in the center
- Size: Responsive (25-50px radius depending on screen size)
- Border: White border with glow effect
- Position: Center of the screen, behind the animated text

## Note:
If no image is found, the animation will work normally without the photo.