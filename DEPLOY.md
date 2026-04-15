# Birthday Surprise Website 🎂

A beautiful, vintage-themed birthday surprise website built with HTML5, CSS3, and JavaScript.

## Features ✨

- 7-section emotional journey for birthday celebration
- Vintage aesthetic with animated elements
- Media player support (audio & video)
- Responsive design for all devices
- Smooth animations and transitions
- Interactive elements throughout

## Deployment Status

### Files Included:
- `birthday-wishes.html` - Main landing page
- `section2.html` to `section7.html` - Journey sections
- `video.mp4` - Video message (≈0.87 MB)
- `voice.mp4` - Audio message (≈0.47 MB)
- `kiii.png`, `kiri.png` - Images
- `index.html` - Redirect to main page
- `status.html` - Diagnostic page to check file availability

## How to Deploy

### Option 1: GitHub Pages (Free)
1. Go to repository Settings → Pages
2. Select "Deploy from a branch"
3. Choose `main` branch and root folder
4. Wait for deployment to complete
5. Visit: `https://username.github.io/birthday_k`

### Option 2: Vercel (Recommended for large files)
1. Go to https://vercel.com
2. Click "New Project"
3. Import this GitHub repository
4. Click "Deploy"
5. Vercel will automatically handle large files

### Option 3: Netlify
1. Go to https://netlify.com
2. Click "New site from Git"
3. Select GitHub and this repo
4. Netlify automatically deploys

## Testing File Availability

Visit `/status.html` on your deployed site to run diagnostics and check if all files are accessible.

Example: `https://your-domain.com/status.html`

## Troubleshooting

### Media files (video.mp4, voice.mp4) not loading?
1. Verify files are tracked in git: `git ls-files | grep \.mp4`
2. Check deployment platform file size limits
3. Use `/status.html` to diagnose which files are missing
4. Consider using Vercel or Netlify for better large file support

### Images not showing?
1. Ensure `kiii.png` and `kiri.png` are in repository root
2. Check file paths in HTML (should be simple filenames: `kiii.png`)
3. Verify image files aren't corrupted

### Site not accessible?
1. Check GitHub Pages settings (Settings → Pages)
2. Verify the deployment URL in repository settings
3. Clear browser cache (Ctrl+F5 or Cmd+Shift+R)
4. Check deployment logs for errors

## File Structure

```
birthday_k/
├── birthday-wishes.html      # Main page
├── section2.html             # From My Heart
├── section3.html             # Our Memories
├── section4.html             # Missing You
├── section5.html             # Audio Message
├── section6.html             # Video Message
├── section7.html             # Birthday Celebration
├── index.html                # Redirect page
├── status.html               # Status checker
├── video.mp4                 # Video message
├── voice.mp4                 # Audio message
├── kiii.png                  # Couple image
├── kiri.png                  # Secondary image
├── vercel.json               # Vercel config
├── netlify.toml              # Netlify config
├── .netlify/                 # Netlify settings
├── .github/workflows/        # GitHub Actions
├── .gitattributes            # Git LFS config
└── .nojekyll                 # GitHub Pages config
```

## Customization

### Edit Text Content:
- Open any `.html` file
- Modify text inside the content divs
- Save and push to GitHub

### Change Colors:
- Look for `#8b6f47`, `#d4a574`, `#f5ede2` in CSS
- Modify `background:` and `color:` properties

### Replace Images:
- Replace `kiii.png` and `kiri.png` with your own
- Keep the same filenames or update HTML references

## Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Tips

- Media files are optimized at ≈0.87 MB and ≈0.47 MB
- Images are large for quality; consider hosting separately if issues occur
- Use `/status.html` to monitor deployment health

## Support

If deployment fails:
1. Check `.github/workflows/deploy.yml` in Actions tab
2. Visit `/status.html` to diagnose file availability
3. Verify all files in git: `git ls-files`
4. Check deployment platform (Vercel, Netlify, GitHub Pages) settings

---

**Created:** April 2026
**Version:** 1.0
**Last Updated:** April 15, 2026
