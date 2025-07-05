# Teaching Data Visualization with Python & R

A comprehensive workshop resource for educators teaching data visualization using free, web-based platforms.

**[Visit the Workshop Hub](https://zarifaz.github.io/dataviz-workshop/)**

## Overview

This repository contains materials for a 10-minute workshop demonstrating how to teach data visualization without installation barriers. Perfect for middle and high school educators looking to integrate data science into their curriculum.

## Repository Structure

```
dataviz-workshop/
├── index.html                 # Main workshop hub page
├── presentation.qmd          # Quarto presentation slides
├── python_dataviz_intro.ipynb # Python notebook for Google Colab
├── r_dataviz_intro.Rmd       # R Markdown for Posit Cloud
├── social_media_use.csv      # Dataset for all examples
├── data_dictionary.md        # Description of dataset variables
├── slides/                   # Rendered presentation
│   └── index.html
├── images/                   # Images for ethics examples
│   ├── truncated-axis.jpg
│   └── dual-axis.jpg
└── README.md
```

## Quick Start

### For Workshop Participants

1. **Python Track**: 
   - Click this button to open in Google Colab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/zarifaz/dataviz-workshop/blob/main/python_dataviz_intro.ipynb)

2. **R Track**:
   - [Open in Posit Cloud](https://posit.cloud/content/yours) (requires free account)
   - Or download `r_dataviz_intro.Rmd` and use locally

3. **View Slides**:
   - [Workshop Presentation](https://zarifaz.github.io/dataviz-workshop/slides)

### For Instructors

1. Fork this repository
2. Enable GitHub Pages (Settings → Pages → Deploy from branch → main → / (root))
3. Update links in `index.html` to point to your fork
4. Customize materials as needed

## Dataset Information

The `social_media_use.csv` dataset contains survey responses about social media usage and mental health indicators:

- **481 observations** from participants aged 13-91
- **Variables include**: age, gender, social media usage per day, anxiety level, depression level, insomnia level, and more
- **Source**: Cleaned version of publicly available Kaggle dataset

See `data_dictionary.md` for complete variable descriptions.

## Setup Instructions

### Google Colab (Python)
1. No installation required
2. Sign in with Google account
3. Click "Copy to Drive" when opening notebook
4. Run cells with `Shift+Enter`

### Posit Cloud (R)
1. Create free account at [posit.cloud](https://posit.cloud)
2. Click "Copy Project" when opening
3. All packages pre-installed
4. Click "Knit" to run document

### Local Setup (Optional)

**Python Requirements:**
```bash
pip install pandas matplotlib seaborn numpy jupyter
```

**R Requirements:**
```r
install.packages(c("tidyverse", "viridis"))
```

## In this section of the workshop, we will cover

### 1. Platform Overview (2 min)
- Google Colab advantages
- Posit Cloud features
- Jupyter alternatives

### 2. Live Coding Demos (5 min)
- Creating bar charts in both languages
- Data ordering and color palettes
- Side-by-side syntax comparison

### 3. Ethics Discussion (1.5 min)
- Truncated axes
- Dual axis manipulation
- Teaching responsible visualization

## Ethics Resources

The workshop emphasizes ethical data visualization:

- **Deceptive practices to avoid**: Truncated axes, misleading scales, cherry-picked ranges
- **Cairo's principle**: "Ethical thinking is about not only intentions, but consequences"
- **Teaching approach**: Students learn to both create AND critique visualizations

## License

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

## Acknowledgments

- Dataset adapted from [Kaggle](https://www.kaggle.com/datasets/souvikahmed071/social-media-and-mental-health)

## Contact

Workshop questions: [zarifazakaria@gmail.com]

---
**Remember**: We're not just teaching code, we're empowering students to tell honest stories with data!