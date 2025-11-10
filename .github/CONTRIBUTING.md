# Contributing to Play Integrity Fix Guide

Thank you for considering contributing to this project! Here are some guidelines to help maintain the quality and performance of the repository.

## Image Guidelines

To keep the repository lightweight and fast, please follow these guidelines when adding images:

### Image Optimization

Before committing images to the repository, please optimize them:

**For PNG images:**
```bash
# Install optimization tools
sudo apt-get install pngquant optipng

# Optimize with pngquant (lossy compression, good for photos/complex images)
pngquant --quality=65-80 --speed 1 --force --output optimized.png original.png

# Optimize with optipng (lossless compression, good for simple graphics)
optipng -o7 image.png
```

**Target sizes:**
- Icons/logos: < 20KB
- Screenshots: < 500KB
- Banners: < 800KB

### Binary Files

- **Do NOT commit binary files** like APKs, ZIPs, or executables
- Instead, reference download links to official releases on GitHub or other sources
- This keeps the repository lightweight and ensures users get the latest versions

### Best Practices

1. **Use relative paths** for local assets in markdown files
2. **Compress images** before committing
3. **Reference external files** via links instead of committing them
4. **Test your changes** to ensure images load correctly
5. **Keep commits focused** on a single improvement or fix

## Pull Request Guidelines

When submitting a PR:

1. Ensure all images are optimized
2. Test that documentation renders correctly
3. Verify all links work properly
4. Include a clear description of changes

Thank you for helping keep this project efficient and maintainable!
