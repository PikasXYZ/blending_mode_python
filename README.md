# blending_mode_python

This repository contains a collection of image blending modes implemented in Python. These blending modes are commonly used in image processing and graphics applications to combine two images in various ways, such as adjusting brightness, contrast, and color.

## Features

- **Normal**: Directly overlays the top image onto the bottom image.
- **Dissolve**: Randomly replaces pixels from the bottom image with those from the top image based on alpha.
- **Multiply**: Multiplies the color values of the two images.
- **Screen**: Lightens the bottom image to reflect the top image.
- **Overlay**: Combines Multiply and Screen blending modes.
- **Soft Light**: Applies either a darkening or lightening effect depending on the top image.
- **Hard Light**: A combination of Multiply and Screen modes that emphasizes contrast.
- **Color Dodge**: Brightens the bottom image to reflect the top image.
- **Linear Dodge**: Adds the color values of the two images.
- **Color Burn**: Darkens the bottom image to reflect the top image.
- **Linear Burn**: Subtracts color values to darken the image.
- **Vivid Light**: Increases contrast dramatically, combining Color Dodge and Color Burn.
- **Linear Light**: Adds or subtracts brightness to darken or lighten the image.
- **Lighten**: Retains the brighter pixels from both images.
- **Darken**: Retains the darker pixels from both images.
- **Darker Color**: Keeps the darkest color from the two images.
- **Lighter Color**: Keeps the lightest color from the two images.
- **Pin Light**: Combines Lighten and Darken modes.
- **Hard Mix**: Adds color channels and applies a threshold to create high-contrast images.
- **Divide**: Divides the bottom image by the top image.
- **Difference**: Subtracts the bottom image from the top image, or vice versa, to get the absolute difference.
- **Exclusion**: A more subtle difference blend mode.
- **Subtract**: Subtracts the top image from the bottom image.
- **Hue**: Uses the hue of the top image and the saturation and luminosity of the bottom image.
- **Saturation**: Uses the saturation of the top image and the hue and luminosity of the bottom image.
- **Color**: Uses the hue and saturation of the top image and the luminosity of the bottom image.
- **Luminosity**: Uses the luminosity of the top image and the hue and saturation of the bottom image.

