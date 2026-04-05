# Book 2: Mastering Responsive Design & Layouts

Tailwind CSS uses a **mobile-first** approach. This means any class you write without a prefix (like `p-4` or `text-center`) applies to *all* screen sizes, starting from mobile.

To change the design on larger screens, you use responsive prefixes.

## 1. The Responsive Breakpoints
These are the default breakpoints you will use every day:

*   **No prefix:** Mobile (default, starts at 0px)
*   `sm:` (Tablet/Large Mobile, 640px and up)
*   `md:` (Tablet Landscape/Small Desktop, 768px and up)
*   `lg:` (Desktop, 1024px and up)
*   `xl:` (Large Desktop, 1280px and up)
*   `2xl:` (Massive Screens, 1536px and up)

**The Golden Rule:** Always design your mobile view first. Then, scale it up.
*Example:* `w-full md:w-1/2 lg:w-1/3` 
*(100% width on mobile, 50% on tablet, 33% on desktop).*

## 2. CSS Grid: The Layout King
While Flexbox is great for aligning items in a single direction (row or column), **Grid** is built for 2D layouts (rows AND columns).

*   `grid`: Turns the element into a grid container.
*   `grid-cols-1`: 1 column (Great for mobile).
*   `grid-cols-2`, `grid-cols-3`, `grid-cols-4`: Divides the container into equal columns.
*   `gap-4` or `gap-6`: Adds spacing between grid items (both rows and columns).
*   `col-span-2`: Makes a single child element take up 2 columns of space.

## 3. Advanced Flexbox (Wrapping and Growing)
Sometimes you don't need a strict grid, but you want items to flow naturally.

*   `flex-wrap`: If items run out of space, they wrap to the next line instead of shrinking.
*   `flex-1` or `grow`: Tells an item to take up all available remaining space.
*   `shrink-0`: Prevents an item from shrinking when space gets tight.