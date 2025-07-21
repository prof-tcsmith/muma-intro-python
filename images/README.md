# Images Directory

## Overview

This directory contains visual assets used throughout the ISM2411 Python for Business course materials. Images are referenced in various Quarto documents to enhance learning and visual appeal.

## Current Contents

- **`python-banner.webp`** - Course banner image featuring Python branding, used in course introduction materials

## Usage Guidelines

### Adding New Images

1. **File Formats**: Prefer web-optimized formats (WebP, PNG, JPEG)
2. **File Naming**: Use descriptive, lowercase names with hyphens (e.g., `module01-flowchart.png`)
3. **File Size**: Optimize images to balance quality and loading speed
4. **Dimensions**: Consider responsive display; avoid extremely large dimensions

### Referencing Images in Quarto

In Quarto (.qmd) files, reference images using relative paths:

```markdown
![Description of image](../images/filename.webp)
```

For HTML attributes:
```markdown
![Description](../images/filename.webp){width=600}
```

### Image Categories

Organize images by type if the directory grows:
- **banners/** - Course and module banners
- **diagrams/** - Technical diagrams and flowcharts
- **screenshots/** - Software screenshots
- **icons/** - Small icons and symbols

## Best Practices

1. **Accessibility**: Always include descriptive alt text
2. **Copyright**: Only use images with proper licensing
3. **Consistency**: Maintain visual style across course materials
4. **Performance**: Optimize file sizes for web delivery

## Maintenance

- Remove unused images periodically
- Update this README when adding new images
- Check image references when reorganizing

---

**Last Updated**: July 2025  
**Course**: ISM2411 Python for Business