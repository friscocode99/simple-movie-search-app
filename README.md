# This was Fork from : [ianshulx - React-projects-for-beginners](https://github.com/ianshulx/React-projects-for-beginners)

## Fix MovieCard App.css Error. 
---
## for depecrated NPM solution. 
---
### Delete package-lock.json

```bash
rm -rf node_modules package-lock.json
```

### reinstall react-scripts

```bash
npm install react-scripts --save
```

### verify script

```bash
ls node_modules/.bin | grep react-scripts
```

### start App

```bash
npm start
```

```css
/* =========================================
   Obsidian Canvas – Orange, Yellow & Green + Themed Blue
   ========================================= */

/* Headings */
.canvas-node-content h1,
.canvas-node-content h2,
.canvas-node-content h3 {
  text-align: center;
  color: #ff8c00; /* Orange */
  font-weight: 700;
}

/* Dark mode headings */
.theme-dark .canvas-node-content h1,
.theme-dark .canvas-node-content h2,
.theme-dark .canvas-node-content h3 {
  color: #ffb347; /* Brighter orange */
}

/* Paragraphs */
.canvas-node-content p {
  color: #ff8c00;
}

.theme-dark .canvas-node-content p {
  color: #ffb347;
}

/* Bullet points */
.canvas-node-content ul,
.canvas-node-content ol,
.canvas-node-content li {
  color: #ffd700; /* Yellow */
}

.canvas-node-content li::marker {
  color: #ffd700;
}

/* ... rest of your CSS ... */
