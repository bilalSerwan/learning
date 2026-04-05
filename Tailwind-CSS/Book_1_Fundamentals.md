# Book 1: Tailwind CSS Fundamentals & The "Daily Drivers"

As a front-end developer, you will use 20% of Tailwind's classes 80% of the time. This cheat sheet focuses on the absolute essentials that you will write every single day.

## 1. Sizing and Spacing (The Box Model)
Tailwind's spacing scale is proportional. `1` usually equals `0.25rem` (4px).

### Padding (Inside spacing)
*   `p-4` : Padding all sides (16px)
*   `px-4`: Padding horizontal (left/right)
*   `py-4`: Padding vertical (top/bottom)
*   `pt-4`, `pr-4`, `pb-4`, `pl-4`: Top, right, bottom, left.

### Margin (Outside spacing)
*   `m-4` : Margin all sides
*   `mx-auto` : **Crucial!** Centers a block element horizontally.
*   `mb-4`: Margin bottom (very common for spacing out stacked elements).

### Width & Height
*   `w-full`: 100% width.
*   `w-screen`: 100vw (viewport width).
*   `w-1/2`: 50% width (fractions are great!).
*   `w-[300px]`: Arbitrary value (use sparingly, but great for exact sizes).
*   `h-full`, `h-screen`, `h-64`: Same concepts apply to height.

## 2. Typography (Text & Fonts)
*   **Size:** `text-xs`, `text-sm`, `text-base` (default 16px), `text-lg`, `text-xl`, `text-2xl`, `text-4xl`.
*   **Weight:** `font-light`, `font-normal`, `font-medium`, `font-semibold` (600), `font-bold` (700).
*   **Alignment:** `text-left`, `text-center`, `text-right`.
*   **Color:** `text-gray-500`, `text-blue-600`, `text-slate-900`.

## 3. Backgrounds & Borders
*   **Backgrounds:** `bg-white`, `bg-gray-100`, `bg-blue-500`, `bg-transparent`.
*   **Borders:** `border` (adds a 1px border), `border-2`, `border-gray-200`.
*   **Border Radius:** `rounded-sm`, `rounded` (default), `rounded-md`, `rounded-lg`, `rounded-xl`, `rounded-full`.

## 4. The Flexbox Essentials
*   `flex`: Turns the element into a flex container (defaults to a row).
*   `flex-col`: Stacks children vertically.
*   `items-center`: Centers children vertically.
*   `justify-center`: Centers children horizontally.
*   `justify-between`: Pushes the first item to the left, last to the right.
*   `gap-4`: Adds 16px of space between flex children.