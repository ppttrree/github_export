# Ascend - Static Site Export

This folder contains the static build of the Ascend landing page, ready for deployment to GitHub Pages, Netlify, or Vercel.

## File Structure

```
.
├── index.html          # Main entry point
├── favicon.png         # Site icon
├── assets/
│   ├── css/            # Compiled stylesheets
│   ├── js/             # Compiled JavaScript bundles
│   └── images/         # Optimized images
```

## How to Deploy

### GitHub Pages
1. Push this folder's contents to a GitHub repository.
2. Go to Settings > Pages.
3. Select the branch and folder (root) to deploy.
4. Your site will be live at `https://your-username.github.io/repo-name`.

### Netlify / Vercel
1. Drag and drop this folder into the deployment area.
2. OR connect your GitHub repo and set the build command to (empty) and publish directory to `.` (root).
