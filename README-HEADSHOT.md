# Adding Your Headshot to the Portfolio

## Quick Setup Instructions

### 1. Prepare Your Image
- **Format**: JPG or PNG recommended
- **Size**: Square aspect ratio (1:1) works best
- **Resolution**: 400x400 pixels or higher for crisp display
- **File name**: Use something like `aaron-ge-headshot.jpg` or `profile-photo.jpg`

### 2. Add the Image to Your Website

**Option A: Place image in the same folder as your HTML file**
1. Put your image file in the same directory as `index.html`
2. Edit `index.html` and find this section (around line 74):

```html
<!-- Replace 'your-headshot.jpg' with your actual headshot image -->
<!-- <img src="your-headshot.jpg" alt="Aaron Ge - AI & Computational Medicine Researcher"> -->

<!-- Placeholder until you add your photo -->
<div class="hero-profile-placeholder">
    <i class="fas fa-user"></i>
</div>
```

3. Replace it with:

```html
<img src="your-image-filename.jpg" alt="Aaron Ge - AI & Computational Medicine Researcher">
```

**Option B: Use an images folder (recommended)**
1. Create a folder called `images` in your project directory
2. Put your image in the `images` folder
3. Update the HTML to:

```html
<img src="images/your-image-filename.jpg" alt="Aaron Ge - AI & Computational Medicine Researcher">
```

### 3. Example
If your image is named `aaron-headshot.jpg` and placed in an `images` folder:

```html
<img src="images/aaron-headshot.jpg" alt="Aaron Ge - AI & Computational Medicine Researcher">
```

## Features of the Headshot Display

- **Glowing Border**: Your photo will have an animated cyan/blue gradient border
- **Responsive**: Automatically resizes on mobile devices
- **Professional Look**: Circular crop with subtle glow effects
- **Accessible**: Includes proper alt text for screen readers

## Tips for Best Results

- Use a professional headshot with good lighting
- Make sure your face is clearly visible and centered
- A neutral or slightly smiling expression works well
- The background doesn't matter much as it will be cropped to a circle
- Higher resolution images will look crisp on all devices

Once you add your image, the placeholder icon will be replaced with your professional headshot! 