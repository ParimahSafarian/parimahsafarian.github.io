# Website Style Customization Guide

## 🎨 Easy Color Theme Changes

Your website now uses CSS custom properties (variables) that make it easy to change the entire color scheme. Here are some popular alternatives:

### Option 1: Professional Blue Theme (Current)
```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --accent-color: #ffd700;
}
```

### Option 2: Modern Green Theme
```css
:root {
    --primary-color: #10b981;
    --secondary-color: #059669;
    --accent-color: #f59e0b;
}
```

### Option 3: Elegant Dark Theme
```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #4f46e5;
    --accent-color: #fbbf24;
    --text-color: #1f2937;
    --background-color: #f9fafb;
}
```

### Option 4: Warm Orange Theme
```css
:root {
    --primary-color: #f97316;
    --secondary-color: #ea580c;
    --accent-color: #3b82f6;
}
```

### Option 5: Professional Teal Theme
```css
:root {
    --primary-color: #0891b2;
    --secondary-color: #0e7490;
    --accent-color: #f59e0b;
}
```

## 🎯 How to Apply a New Theme

1. Open `styles.css` file
2. Find the `:root` section at the top
3. Replace the color values with your preferred theme
4. Save the file
5. Refresh your browser to see changes

## 🖼️ Typography Options

### Option 1: Modern Sans-Serif (Current)
```css
:root {
    --font-primary: 'Inter', sans-serif;
}
```

### Option 2: Elegant Serif
```css
:root {
    --font-primary: 'Playfair Display', serif;
}
```
Add to HTML head: `<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@300;400;500;600;700&display=swap" rel="stylesheet">`

### Option 3: Tech-Style Monospace
```css
:root {
    --font-primary: 'JetBrains Mono', monospace;
}
```
Add to HTML head: `<link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@300;400;500;600;700&display=swap" rel="stylesheet">`

### Option 4: Clean Minimalist
```css
:root {
    --font-primary: 'Poppins', sans-serif;
}
```
Add to HTML head: `<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">`

## 🎨 Layout Styles

### Minimalist Style
- Reduce shadows and gradients
- Use flat colors
- Increase white space

### Bold & Modern
- Increase gradient intensity
- Add more animations
- Use larger typography

### Corporate Professional
- Use muted colors
- Reduce animations
- Clean, structured layout

## 🛠️ Quick Customization Commands

To change your theme quickly, you can:

1. **Copy one of the color themes above**
2. **Paste it into your styles.css file** (replacing the existing :root section)
3. **Save and refresh** your browser

## 🎪 Advanced Customization

For more advanced changes, you can modify:
- Section backgrounds
- Button styles
- Card layouts
- Animation effects
- Responsive breakpoints

Would you like me to implement any specific theme or style changes?
