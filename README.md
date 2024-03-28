# Google Classroom Theme
A description will be added here later.

## Theme Preview
Here are some visuals of the theme.
### Home Page
![Preview Image 01](https://github.com/Zy1ux/GoogleClassroomTheme/blob/main/Home_Page.png?raw=true)

## How to Apply
Follow these steps to apply a theme and enhance the appearance of Google Classroom.

### Installation
- Begin by installing an extension such as Stylebot from the Chrome Web Store.
- Once installed, go to [Google Classroom](https://classroom.google.com/).
- Click on the Stylebot extension icon to open a menu with options like Readability, Open Stylebot, and Options.
- Choose 'Open Stylebot' to bring up a sidebar.
- Scroll to the bottom of this sidebar to find three options: Basic, Code, and Magic.
- Select the 'Code' option.
- Copy the code provided below and paste it into the text box.
```css
:root {
  --background-image-url: url("https://media.discordapp.net/attachments/1207879896097882112/1221849828741349386/file.jpg?ex=66141354&is=66019e54&hm=13e5698ae8060fbf51b01e2f326861801cef8a52ebc8ed4951e228967a9336e2&=");
  --text-color: 255,255,255;
  --background-opacity-top: 0.9;
  --background-opacity-bottom: 0.1;
  --image-color-overlay: 80,80,80;
  --element-background-color: 60,120,180;
  --element-border-radius: 10px;
  --element-brightness: 200,200,240;
  --element-background-blur: 10px;
  --background-blur: 0px;
}

@import url("https://raw.githubusercontent.com/Zy1ux/GoogleClassroomTheme/main/main.theme.css");
```

### Customization
- `--background-image-url` - The URL for the background image you wish to use.
- `--text-color` - The color of the text on the webpage.
- `--background-opacity-top` - The opacity of the background image overlay gradient at the top.
- `--background-opacity-bottom` - The opacity of the background image overlay gradient at the bottom.
- `--image-color-overlay` - The color of the gradient overlay on the background image.
- `--element-background-color` - The color of buttons and other interface elements.
- `--element-border-radius` - The curvature of the corners of elements.
- `--element-brightness` - The brightness level of the elements (function unknown).
- `--element-background-blur` - The amount of blur applied to the background behind elements.
- `--background-blur` - The degree of blur applied to the background (not recommended for adjustment as it is currently not functioning properly).
