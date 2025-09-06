## 🚀 Tech Stack

- **HTML5** – Markup for all demo pages
- **Tailwind CSS v4** – Utility-first CSS framework
- **PostCSS** – For processing Tailwind directives
- **Node.js** – For running Tailwind CLI
- **Custom CSS** – For extended styles and custom classes

---

## 📦 Dependencies

All dependencies are managed via `npm`:

```json
{
  "dependencies": {
    "@tailwindcss/cli": "^4.0.17",
    "tailwindcss": "^4.0.17"
  }
}
```

- **@tailwindcss/cli**: For compiling Tailwind CSS
- **tailwindcss**: The core Tailwind CSS framework

---

## 🗂️ Folder Structur

```
Tailwind-CSS-Study-main-master/
│
├── images/
│   └── TheBoseBaby.jpeg
│
├── node_modules/
│   └── ... (npm dependencies)
│
├── src/
│   ├── input.css         # Source Tailwind CSS with custom layers
│   └── output.css        # Compiled CSS (generated)
│
├── *.html                # Demo pages for each concept
├── package.json
├── package-lock.json
└── README.md             # ← You are here!
```

---

## 📖 What’s Inside?

### 1. **Tailwind CSS Concepts & Demos**

Each HTML file demonstrates a specific Tailwind CSS feature or concept, with real code and visual output.

| File                                 | Demo                                                                     |
| ------------------------------------ | ------------------------------------------------------------------------ |
| **start.html**                       | Navigation bar with hover effects                                        |
| **colors.html**                      | Text, background, border, and outline color utilities                    |
| **margin-pading.html**               | Margin and padding utilities (all sides, px/rem, inline/block)           |
| **marginPaddingSpacingCustom.html**  | Custom spacing, padding, margin, height, width, and size                 |
| **height.html**                      | Height utilities, min/max heights                                        |
| **width.html**                       | Width utilities, min/max widths, responsive widths                       |
| **size.html**                        | Unified size (width & height) utilities                                  |
| **background.html**                  | Background images, gradients, box shadows                                |
| **border.html**                      | Border width, color, style, radius, and dashed borders                   |
| **flex.html**                        | Flexbox layouts, direction, wrapping, alignment                          |
| **grid.html**                        | Grid layouts, responsive columns, row/column spans                       |
| **column.html**                      | Multi-column layouts, responsive columns                                 |
| **mediaQueryAndBreakpoints.html**    | Responsive design with custom breakpoints                                |
| **breakPointsCustomize.html**        | Custom breakpoints in Tailwind                                           |
| **transitionAndTransformation.html** | Transitions, transforms, hover/active/focus states                       |
| **interactivity.html**               | Hover, focus, active, and group-hover utilities                          |
| **filters.html**                     | Image filters: blur, brightness, contrast, grayscale, invert, hue-rotate |
| **animation.html**                   | Built-in animations: bounce, spin, pulse, ping                           |
| **customClass.html**                 | Creating and using custom classes with `@apply`                          |
| **buttons.html**                     | Bootstrap-like button styles with custom classes                         |
| **photoGallery-miniProject1.html**   | Responsive photo gallery mini-project                                    |
| **containers.html**                  | Container utility and responsive layouts                                 |
| **directives.html**                  | Using Tailwind directives and custom base styles                         |
| **positions.html**                   | Positioning utilities: absolute, relative, fixed, inset, z-index         |

---

### 2. **Definitions & Explanations**

- **Utility-First CSS**: Tailwind provides low-level utility classes for every CSS property, enabling rapid UI development without writing custom CSS.
- **Responsive Design**: Easily create layouts that adapt to any screen size using Tailwind’s breakpoint system.
- **Custom Classes**: Use `@apply` to compose utilities into reusable custom classes.
- **Transitions & Animations**: Add smooth transitions and engaging animations with simple utility classes.
- **Filters & Effects**: Apply advanced CSS filters like blur, brightness, and grayscale directly in your markup.
- **Interactivity**: Use state-based utilities (`hover:`, `focus:`, `active:`, `group-hover:`) for interactive UIs.

---

### 3. **How to Use**

#### 1. **Install Dependencies**

```bash
npm install
```

#### 2. **Start Tailwind CLI (Watch Mode)**

```bash
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
```

#### 3. **Open Any HTML File**

Just open any `.html` file in your browser to see the demo in action!

---

## 🌟 Highlights

- **All core Tailwind CSS utilities demonstrated**
- **Custom breakpoints, spacing, and sizing**
- **Responsive layouts with Flexbox and Grid**
- **Custom classes and component styling**
- **Mini-projects for real-world practice**
- **Image filters and advanced effects**
- **Animations and transitions for modern UIs**
- **Bootstrap-like button system using Tailwind**

---

## 💡 Why Use This Project?

- **Learn by Example**: See every Tailwind utility in action.
- **Quick Reference**: Use as a cheat-sheet for your own projects.
- **Practice**: Tweak and extend the demos to deepen your understanding.
- **Portfolio**: Use the mini-projects as a base for your own portfolio pieces.

---

## 🤝 Contributing

Feel free to fork, improve, and submit pull requests! Suggestions and feedback are always welcome.

---

## 📚 Resources

- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [Play Tailwind Online](https://play.tailwindcss.com/)

---

> **Happy Styling! 🚀**
>
> _Explore, experiment, and master Tailwind CSS with this all-in-one study project._
