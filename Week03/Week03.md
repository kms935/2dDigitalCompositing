# Week3: Colorspaces, Gamma and more

Class: Mon123
Date of class: Sep 21, 2020
Week: 03

# What is Colorspaces?

We studied RGB and CMYK last week, are there anything else more?

Color + Space 

RGB / CIE XYZ 

[https://www.youtube.com/watch?v=x0-qoXOCOow](https://www.youtube.com/watch?v=x0-qoXOCOow)

[https://www.youtube.com/watch?v=AS1OHMW873s](https://www.youtube.com/watch?v=AS1OHMW873s)

# Various Colorspaces(Models)

### YUV

Y: Luminance, U-V(UV we saying in Texture painting space)

![Week3%20Colorspaces,%20Gamma%20and%20more%209d9798a5a6aa4ecd9e6783d8c0dd3321/Untitled.png](Week3%20Colorspaces,%20Gamma%20and%20more%209d9798a5a6aa4ecd9e6783d8c0dd3321/Untitled.png)

YCbCr / YPbPr  —> RGB

YCbCr: Digital color codes 

YPbPr: Analog color signal 

![Week3%20Colorspaces,%20Gamma%20and%20more%209d9798a5a6aa4ecd9e6783d8c0dd3321/Untitled%201.png](Week3%20Colorspaces,%20Gamma%20and%20more%209d9798a5a6aa4ecd9e6783d8c0dd3321/Untitled%201.png)

### ACES Colorspace

![Week3%20Colorspaces,%20Gamma%20and%20more%209d9798a5a6aa4ecd9e6783d8c0dd3321/Untitled%202.png](Week3%20Colorspaces,%20Gamma%20and%20more%209d9798a5a6aa4ecd9e6783d8c0dd3321/Untitled%202.png)

[https://docs.arnoldrenderer.com/display/A5AFHUG/ACES+Workflow](https://docs.arnoldrenderer.com/display/A5AFHUG/ACES+Workflow)

Why was ACES created?

***ACES was created to reign in all the various formats and codecs.***

[https://www.premiumbeat.com/blog/what-is-aces-in-color-grading/](https://www.premiumbeat.com/blog/what-is-aces-in-color-grading/)

[https://mixinglight.com/guide/what-is-aces/](https://mixinglight.com/guide/what-is-aces/)

## Common mis-understood about colorspace: 
Is new colorspace more beautiful?

**Anser is... ?**

### Color Gamut Comparison

![Week3%20Colorspaces,%20Gamma%20and%20more%209d9798a5a6aa4ecd9e6783d8c0dd3321/Untitled%203.png](Week3%20Colorspaces,%20Gamma%20and%20more%209d9798a5a6aa4ecd9e6783d8c0dd3321/Untitled%203.png)

Gamut comparison (image courtesy of Haarm-Pieter Duiker and Thomas Mansencal)

# Gamma / Linear workflow

### Why Gamma is important?

Let's get back to ~~RGB~~ **sRGB**

![Week3%20Colorspaces,%20Gamma%20and%20more%209d9798a5a6aa4ecd9e6783d8c0dd3321/Untitled%204.png](Week3%20Colorspaces,%20Gamma%20and%20more%209d9798a5a6aa4ecd9e6783d8c0dd3321/Untitled%204.png)

CIE 1931 xy chromaticity diagram shows sRGB colorspace

### Why Gamma is important?

### What we see and What we save is different

![Week3%20Colorspaces,%20Gamma%20and%20more%209d9798a5a6aa4ecd9e6783d8c0dd3321/Untitled%205.png](Week3%20Colorspaces,%20Gamma%20and%20more%209d9798a5a6aa4ecd9e6783d8c0dd3321/Untitled%205.png)

[https://www.japanistry.com/understanding-gamma-in-photography/](https://www.japanistry.com/understanding-gamma-in-photography/)

![Week3%20Colorspaces,%20Gamma%20and%20more%209d9798a5a6aa4ecd9e6783d8c0dd3321/Untitled%206.png](Week3%20Colorspaces,%20Gamma%20and%20more%209d9798a5a6aa4ecd9e6783d8c0dd3321/Untitled%206.png)

[https://www.japanistry.com/understanding-gamma-in-photography/](https://www.japanistry.com/understanding-gamma-in-photography/)

![Week3%20Colorspaces,%20Gamma%20and%20more%209d9798a5a6aa4ecd9e6783d8c0dd3321/Untitled%207.png](Week3%20Colorspaces,%20Gamma%20and%20more%209d9798a5a6aa4ecd9e6783d8c0dd3321/Untitled%207.png)

[https://forum.reallusion.com/Topic308094.aspx](https://forum.reallusion.com/Topic308094.aspx)

![Week3%20Colorspaces,%20Gamma%20and%20more%209d9798a5a6aa4ecd9e6783d8c0dd3321/Untitled%208.png](Week3%20Colorspaces,%20Gamma%20and%20more%209d9798a5a6aa4ecd9e6783d8c0dd3321/Untitled%208.png)

[https://www.sidefx.com/docs/houdini/render/linear.html](https://www.sidefx.com/docs/houdini/render/linear.html)

Our data is originally linear data but by the technological limitation we used gamma 2.2 and 0.45

감마가 어디감마 

[https://chulin28ho.tistory.com/477](https://chulin28ho.tistory.com/477)

**BUT, don't worry.** 

**Modern DCC tools support linear workflow.**

# Color-correction

Offset / Gain / Gamma / Contrast / Clamp 

[https://digitalidea.gitbook.io/nuke/basic/colortheory/colorcorrection](https://digitalidea.gitbook.io/nuke/basic/colortheory/colorcorrection)

# Assignments

- [ ]  Research topics we covered today
- [ ]  What is LUT? Color LookUpTable ?
- [ ]  What is Logspace and what is main difference with sRGB, why and when we use?
