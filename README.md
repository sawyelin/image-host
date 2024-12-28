# My Personel Image Host On Github
# Image Hosting Guide

This guide will help you use the images hosted in this repository, such as logos, icons, and banners, on your website.

## Folder Structure

The images are organized into the following folders:

- `logos/`: Contains logo images.
- `icons/`: Contains icon images.
- `banners/`: Contains banner images.

## How to Use the Images

### Step 1: Access the Image URL

Each image in the repository can be accessed via a **raw URL**. Here's how you can get the URL:

1. Navigate to the image you want to use in the repository.
2. Click on the image file.
3. Click on the **"Download"** button or **right-click** on the image and select **"Copy image address"**.

Alternatively, you can construct the raw URL using this format:

https://raw.githubusercontent.com/<your-username>/<repo-name>/<branch>/<folder-name>/<image-name>

bash
Copy code

### Example URLs

1. **Logo Image:**
   ```html
   <img src="https://raw.githubusercontent.com/your-username/image-host/main/logos/logo.png" alt="Logo">
Icon Image:

html
Copy code
<img src="https://raw.githubusercontent.com/your-username/image-host/main/icons/icon.svg" alt="Icon">
Banner Image:

html
Copy code
<img src="https://raw.githubusercontent.com/your-username/image-host/main/banners/banner.jpg" alt="Banner">
Step 2: Embed in Your Website
To embed the image in your website, simply use the image URL inside the src attribute of an <img> tag in your HTML file.

Example:
html
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your Website</title>
</head>
<body>
  <header>
    <!-- Logo -->
    <img src="https://raw.githubusercontent.com/your-username/image-host/main/logos/logo.png" alt="Logo">
  </header>

  <main>
    <!-- Icon -->
    <img src="https://raw.githubusercontent.com/your-username/image-host/main/icons/icon.svg" alt="Icon">
  </main>

  <footer>
    <!-- Banner -->
    <img src="https://raw.githubusercontent.com/your-username/image-host/main/banners/banner.jpg" alt="Banner">
  </footer>
</body>
</html>
Optional: Using GitHub Pages for Clean URLs
To make the URLs cleaner, you can enable GitHub Pages for your repository:

Go to the repository Settings > Pages.
Select the main branch and /root folder for the source.
Your images will then be available at:
arduino
Copy code
https://your-username.github.io/image-host/logo.png
License
Feel free to use these images for your website. If you'd like to contribute or add new images, please follow the contribution guidelines.



markdown
Copy code

---

### Instructions for Use:
1. Replace `<your-username>` with your GitHub username.
2. Replace `<repo-name>` with the name of your repository.
3. Replace `<branch>` with the branch name (typically `main` or `master`).
4. Add the appropriate folder and image name.

This `README.md` provides clear steps for anyone using your repository to easily include images in t