# Simple CSS - styling guide

Simple CSS is a writing style for easy lookups. It follows 3 basic rules: **size**, **position**, and **looks**.
1. The first part is about sizing - `margins`, `paddings`, `height`, and `widths`.
2. The second part is used to position the element on the screen. Use it for - `position`, `display`, and their helper properties.
3. All the rest goes here - `fonts`, `colors`, `borders`, etc.

Example:
```css
.note {
  max-width: 80vw;
  padding: 1rem;

  display: flex;
  align-items: center;
  position: absolute;
  bottom: 3rem;

  font-size: 1.4rem;
  background-color: #121212;
  border-radius: 3px;
}
```

## ToDo
- Create IDE extension for automatic sorting CSS properties
- Create ESLint or Prettier plugin

#keepItSimple
