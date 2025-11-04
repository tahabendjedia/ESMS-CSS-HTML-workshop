# CSS Basic Properties

## Text Properties
- `color`: Sets text color
    - Example: `color: #FF0000;` (red)
    - Values: hex colors, rgb(), named colors
- `font-family`: Specifies font type
    - Example: `font-family: Arial, sans-serif;`
    - Common values: Arial, Times New Roman, Helvetica
- `font-size`: Sets text size
    - Example: `font-size: 16px;`,
    - Units: px, em, rem, %
- `font-weight`: Sets text boldness
    - Example: `font-weight: bold;`
    - Values: normal, bold, 100-900
- `text-align`: Aligns text
    - Example: `text-align: center;`
    - Values: left, right, center, justify
- `text-decoration`: Adds underline, line-through, etc.
    - Example: `text-decoration: underline;`
    - Values: none, underline, line-through

## Box Model
- `margin`: Space outside element
    - Example: `margin: 10px;` or `margin: 10px 20px;`
    - Can set individual sides: margin-top, margin-right, etc.
- `padding`: Space inside element
    - Example: `padding: 15px;`
    - Similar to margin, can be set per side
- `border`: Element's border
    - Example: `border: 1px solid black;`
    - Properties: width, style, color
- `width`: Element width
    - Example: `width: 200px;` or `width: 50%;`
    - Auto for default sizing
- `height`: Element height
    - Example: `height: 100px;`
    - Can use auto or specific units

## Background
- `background-color`: Sets background color
    - Example: `background-color: #f0f0f0;`
    - Supports all color formats
- `background-image`: Sets background image
    - Example: `background-image: url('image.jpg');`
    - Can use local or remote URLs
- `background-repeat`: Controls image repetition
    - Example: `background-repeat: no-repeat;`
    - Values: repeat, no-repeat, repeat-x, repeat-y
- `background-position`: Sets image position
    - Example: `background-position: center center;`
    - Values: top, bottom, left, right, center, or pixels

## Basic Positioning
- `position`: Element positioning method
    - Example: `position: relative;`
    - Values: static, relative, absolute, fixed
- `top`, `right`, `bottom`, `left`: Position coordinates
    - Example: `top: 20px;`
    - Used with position property
- `float`: Element floating direction
    - Example: `float: left;`
    - Values: left, right, none

## Other Common Properties
- `cursor`: Mouse cursor type
    - Example: `cursor: pointer;`
    - Values: default, pointer, help, wait
- `opacity`: Element transparency
    - Example: `opacity: 0.5;`
    - Values: 0 (transparent) to 1 (solid)
- `overflow`: Handles content overflow
    - Example: `overflow: hidden;`
    - Values: visible, hidden, scroll, auto
- `visibility`: Shows/hides element
    - Example: `visibility: hidden;`
    - Values: visible, hidden
- `z-index`: Stack order
    - Example: `z-index: 100;`
    - Higher numbers appear on top

## Colors and Units
- Colors:
    - Hex: `#FF0000`
    - RGB: `rgb(0, 0, 0)`
    - RGBA: `rgba(255, 0, 0, 0.5)`
    - Named: `red`, `blue`, `green`
- Units:
    - px: Pixels (`16px`)
    - em: Relative to parent (`1.5em`)
    - rem: Relative to root (`2rem`)
    - %: Percentage (`50%`)
    - vh/vw: Viewport units (`100vh`)