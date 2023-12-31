# 🏞️ Thumbnail Image Generator

This app allows you to create thumbnail images for YouTube videos.

## Demo App

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://thumbnail-image.streamlit.app/)

## App screenshot

<p align="center">
   <img src="app-screenshot.png" width="50%">
</p>

## How the app works?

Herein are the general workflow of the app.

**Input:**
- User selects 2 colors they like (or randomly select complementary colors, blue + orange, green + red)
- Enter title text to display on thumbnail image
- Option to add logo
- Upload photo
  
**App:**
- Generates a wallpaper based on user-selected colors
- Add text + bounding box to thumbnail image
- If user upload their photo, overlays the photo on top of the wallpaper

**Output:**
- Finally, the generated thumbnail image can be downloaded

## Resources and Libraries used
- Wallpaper generation was performed using the [wallpaper-generator](https://github.com/timozattol/wallpaper-generator) GitHub repo from [timozattol](https://github.com/timozattol/).
- Python libraries used: `PIL`, `subprocess`, `math`, `os`, `random`, `rembg`, `sys` and `streamlit`.
