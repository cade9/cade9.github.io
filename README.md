## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/cade9/cade9.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/cade9/cade9.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.



Tests- Rotation Issue
Problem Statement: 
R throws the below error when trying to read in AVIRIS flightlines.
Warning message: In .rasterFromGDAL(x, band = band, objecttype, …) : This file has a rotation Support for such files is limited and results of data processing might be wrong. Proceed with caution & consider using the “rectify” function 
1.Approach one : Rotation issue - with qgis and polygons - Dec 2017
Issue: 
On diablo I do not have this issue where I get an rgdal error with regards to the orientation and prior to 2/18/2018 I not received such an error for a while.
Error below: Goal: 
In this section, we will extract the spectra of the first aviris file from those that Kate provided. Currently, they are located in: “E:/AVIRIS-NG L2 Data/L2” and compare them to those in ENVI.
Steps: 
Create 1 points in an ENVI shapefile - this references the first file from those that kate provided 
file name: “/Data/testfiles/test_pixel_20161009”
file created from flightline: “ang20161009t193202_corr_v1n2_img”
Extract spectra in ENVI
