octocolor
=========

An easy way to change the default colors of your octopress blog.

Select a color palette then paste the css into ~/octopress/sass/custom/_styles.scss

To add a new color swatch, include a new thumbnail and color values in index.html:

img width="160" height="80" src="http://kuler-api.adobe.com/kuler/themeImages/theme_2156664.png"  onclick="change_colors('#3d0b06', '#59140c', '#6f1c11', '#892a1f', '#b2382a', '#fff', '#fff', '#fff', '#fff', '#fff', '#fff');"

Order of colors:
1. navhex - color of nav bar
2. sidebarhex - color of side bar
3. bghex - color of page background
4. headerhex - color of header
5. footerhex - color of footer
6. sidetext - color of sidebar text
7. titletext - color of main blog title
8. navlinktext - color of navigation link item
9. footerlink - color of footer link item
10. plast - color of footer paragraph
11. subtitle - color of main blog subtitle

Integration with the Kuler API coming soon.

Pull requests welcome.

Made with <3 at the Flatiron School in NYC.


