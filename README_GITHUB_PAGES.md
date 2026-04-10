# Engr zoroz Website V2

This version supports:
- Profile photo (DP)
- Project gallery
- Each project can have:
  - image
  - title
  - description
  - price
  - category
- Floating WhatsApp button

## Important
This is a static GitHub Pages website.
That means visitors can view content, but content changes happen by editing repository files.
So only the person with repository write access can update the site.

## Files you will edit
- `data.js` → change text, DP path, links, skills, and projects
- `assets/profile-placeholder.svg` → replace with your own DP image if you want
- `assets/projects/` → put your project photos here

## How to change your DP
1. Upload your photo to the repository, for example:
   `assets/profile.jpg`
2. Open `data.js`
3. Find:
   `dp: "assets/profile-placeholder.svg"`
4. Change it to:
   `dp: "assets/profile.jpg"`
5. Commit changes

## How to add a new project
1. Upload your project photo to:
   `assets/projects/`
2. Open `data.js`
3. Inside the `projects` array, add a new object like this:

```js
{
  title: "My New Project",
  description: "Write your project description here.",
  price: "PKR 25,000",
  image: "assets/projects/my-project.jpg",
  category: "Robotics"
}
```

4. Commit changes
5. GitHub Pages will update the website

## How to publish on GitHub Pages
1. Create a public GitHub repository
2. Upload all files from this folder
3. Go to `Settings` → `Pages`
4. Under `Build and deployment`, choose `Deploy from a branch`
5. Select `main` and `/ (root)`
6. Click `Save`

## Tip
You can manage everything from your phone too by editing `data.js` and uploading images in GitHub's mobile interface.
