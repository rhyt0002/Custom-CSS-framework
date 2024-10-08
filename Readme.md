# Custom CSS Framework

Welcome to Custom CSS Framework, a lightweight, customizable CSS framework designed to simplify web development by providing essential utility classes and pre-styled components. Built using Sass, our framework offers flexibility and consistency across all standard HTML elements, allowing developers to quickly prototype and build responsive websites.

Open you Visual Studio code and open the terminal and then run these codes for Instalation.

## Instalation
- Step 1 (Clone the repository)

     `git clone https://github.com/rhyt0002/Custom-CSS-framework.git`
 - Step 2 (Navigate to the project folder)
 
    `cd custom-css-framework`
 - Step 3 (Install dependencies)
 
    `npm install`
- Step 4 (Compile Sass to css)

    `sass --watch src/main.scss:css/main.css`

## Usage

- Link css in your Html

    `<link rel="stylesheet" href="main/css">`

Now you can use any of the class to add direct css to your element.

## Customization

The Custom CSS Framework is highly customizable using Sass. You can easily modify colors, padding, margins, and other styling aspects by editing in the src folder which contais all scss open any of these and change any value you like according to your needs.

### Example

Open typography.scss in that There are different Font Sizes you can just Edit according to the sizes you need to use throughout your websitev like you want more small size for h6

`$font-sm : 0.8rem;`
