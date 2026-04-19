# Complete File List for GitHub Deployment

## HTML Files (Root Directory)
1. index.html - Main homepage
2. fromtran.html - From the Transistor project page
3. stock-prediction.html - LSTM Stock Prediction project
4. blazepose-accelerator.html - Master's thesis project
5. pose-detection-app.html - Pose detection app documentation
6. j4jweb.html - Live pose detection application (NEW!)
7. socket-networking.html - TCP/UDP networking project
8. raspberrypi-pic32mm.html - Raspberry Pi & PIC32MM project

## Supporting Files (Root Directory)
9. README.md - Repository documentation
10. .gitignore - Git ignore file

## Assets Directory Structure
assets/
├── img/
│   ├── bg-masthead.jpg
│   ├── bg-signup.jpg
│   ├── demo-image-01.jpg
│   ├── demo-image-02.jpg
│   ├── devboard.jpg (Used in raspberrypi-pic32mm.html)
│   ├── favicon.ico
│   ├── fromtransistor.jpg
│   ├── programming.jpg
│   ├── webicon.png
│   └── webicons.png
└── sec1/
    ├── ActiveHighLatch.PNG (Used in fromtran.html)
    ├── flipflop.jpg (Used in fromtran.html)
    ├── IC.jpg (Used in fromtran.html)
    ├── Mux.PNG (Used in fromtran.html)
    └── Nand.PNG (Used in fromtran.html)

## Total Files to Commit
- 10 files in root directory
- 10 images in assets/img/
- 5 images in assets/sec1/
= 25 files total

## Git Commands to Deploy

```bash
# Navigate to your repository
cd /path/to/your/resume/repo

# Copy all files from outputs folder (replace existing)
# [Copy the 10 HTML/MD files to root]
# [Ensure assets/ directory is in place]

# Stage all changes
git add .

# Commit
git commit -m "Updated portfolio website with integrated j4jweb app and all project pages"

# Push to GitHub
git push origin main
```

## Deployment Notes
- GitHub Pages will automatically deploy from the main branch
- The site will be live at: https://vibishanw.github.io/resume/
- The j4jweb app will be accessible at: https://vibishanw.github.io/resume/j4jweb.html
- All assets are referenced relatively, so they'll work automatically

## Key Features
✅ Dark theme with cyan accents
✅ Mobile responsive design
✅ Live pose detection app embedded
✅ All 7 project pages complete
✅ Section 1 added to From the Transistor
✅ Stock prediction workflow detailed
✅ j4jweb app fully integrated
✅ All images properly linked
