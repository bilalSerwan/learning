# Tailwind CSS Cheat Sheet

## Installation

To install Tailwind via npm:

```bash
npm install tailwindcss
```

## Usage

Add the Tailwind directives to your CSS:

```css
tailwind base;
tailwind components;
tailwind utilities;
```

## Utilities

- `m-` for margin
- `p-` for padding
- `text-` for text color
- `bg-` for background color

## Responsive Design

Tailwind uses a mobile-first approach:
- `sm:` for small screens
- `md:` for medium screens
- `lg:` for large screens
- `xl:` for extra-large screens

## Example

Here's a simple button:

```html
<button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">
  Button
</button>
```

## Customization

You can customize Tailwind's default theme in the `tailwind.config.js` file:

```javascript
module.exports = {
  theme: {
    extend: {
      colors: {
        customColor: '#123456',
      },
    },
  },
};
```