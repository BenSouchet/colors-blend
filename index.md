## Differences between blending methods
Depending on how the colors are stored (RGB, HSB, HSL, ...), the calculation and therefore the result of the blending between two colors is different.

This website show you three blending results according to the most popular color models: **RGB**, **HSB/HSV** & **HSL**. Since the color model doesn't store a color the same way the blending differ.

## Color Models
### RGB
The **RGB** (**R**ed, **G**reen, **B**lue) color model is the most known, and the most used every day. It defines a color space in terms of three components: Red, Green and Blue. Each of them with a value between `0` and `255`.  
The **RGB** color model is an additive one. In other words, Red, Green and Blue values (known as the three primary colors) are combined to reproduce other colors.

### HSB / HSV
The **HSB** (**H**ue, **S**aturation, **B**rightness) color model defines a color space in terms of three constituent components:
 - Hue, the color indice determining the "pure" color base. Ranges from 0° to 360° most of the time (sometimes between `0.0` and `1.0`).
 - Saturation, the intensity of the color. Ranges from 0% to 100%, or `0.0` to `1.0` (0 means no color, that's a shade of grey between black and white. 100 means full color).
 - Brightness (or Value) : the brightness of the color. Ranges from 0 to 100%, or `0.0` to `1.0` (0 is always black. Depending on the saturation, 100 may be white or a more or less saturated color).

The **HSB** model is a nonlinear transformation of the RGB color space. In other words, color is not defined as a simple combination (addition/substraction) of primary colors but as a mathematical transformation.

The **HSB** model is also known as **HSV** (**H**ue, **S**aturation, **V**alue) model.

### HSL
The **HSL** color model also defines a color space in terms of three constituent components:
 - Hue, the color indice determining the "pure" color base. Ranges from 0° to 360° most of the time (sometimes between `0.0` and `1.0`).
 - Saturation, the variation of the color depending on the lightness. Ranges from 0% to 100%, or `0.0` to `1.0` (from the center of the *black & white* axis).
 - Lightness (also referred to as Luminance or Luminosity or Intensity). Ranges from 0 to 100%, or `0.0` to `1.0` (from black to white).

HSL is similar to HSB. The main difference is that HSL is symmetrical to lightness and darkness. This means that:
 1. In **HSL**, the Saturation component always goes from fully saturated color to the equivalent gray (in **HSB**, with **B** at maximum, it goes from saturated color to white).
 2. In **HSL**, the Lightness always spans the entire range from black through the chosen hue to white (in **HSB**, the **B** component only goes half that way, from black to the chosen hue).

Often **HSL** offers a more accurate (even if it's not absolute) color approximation than **HSB**.

## Play with the colors
To understand better the correlation between components of color models, what's the new result when you tweak values I **HIGHLY** recommend you check **[colorizer.org](http://colorizer.org/)**

## Others Ressouces & Useful links
 - [colorizer.org](http://colorizer.org/)
 - [Paletton.com](https://paletton.com/)