# Book 3: Advanced States, Transitions & Dark Mode

Static designs are boring. Tailwind makes it incredibly easy to add interactivity, smooth animations, and adapt to system themes like Dark Mode.

## 1. Pseudo-classes (Hover, Focus, Active)
You can target state variants just like you target responsive breakpoints: by adding a prefix.

*   `hover:bg-blue-600`: Changes background on mouse hover.
*   `focus:ring-2`: Adds a focus ring (vital for accessibility when users tab through inputs).
*   `active:scale-95`: Slightly shrinks a button when it is clicked.
*   `disabled:opacity-50`: Fades out an element when it has the `disabled` HTML attribute.

## 2. The "Group" Pattern (Crucial for Cards)
Sometimes you want to hover over a parent card and have a *child* element inside it change color. This is done using `group` and `group-hover`.

## 3. Transitions & Animation
Never jump instantly between states. Always use transitions for a premium feel.

*   `transition`: Enables transitions on color, background, border, and shadow.
*   `duration-300`: How long the animation takes (in milliseconds).
*   **Built-in Animations:** `animate-spin` (loading spinners), `animate-pulse` (skeleton loaders), `animate-bounce`.

## 4. Dark Mode
Tailwind has built-in dark mode support. Just add the `dark:` prefix to any class!