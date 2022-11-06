# Manthan Ank's Digital Resume

A digital resume website built based on the content from my personal REAL [resume](./assets/resume.pdf)

View live demo here using github pages: [Live Demo](https://manthanank.github.io/digital-resume/)

## Dark Mode Preview

![dark mode preview](assets/images/dark-mode-preview.png)

## Light Mode Preview

![light mode preview](assets/images/light-mode-preview.png)

## Switching between color themes

This website has no auto toggle theme switcher, therefor to change themes you must manual go into `/styles/main.css` and the css variables to use either theme. Default is dark, so do the following here:

```css
--mainTextColor:var(--mainTextColor-light); 
--secondaryTextColor:var(--secondaryTextColor-light);
--mainLinkColor:var(--mainLinkColor-light);
--mainBorderColor:var(--mainBorderColor-light);
--mainBgColor:var(--mainBgColor-light);
```
