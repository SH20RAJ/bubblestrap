---
title: "Bubblestrap - Color Schemes"
datePublished: Wed Mar 08 2023 02:55:40 GMT+0000 (Coordinated Universal Time)
cuid: clez38aa0000a09ia65v6awx5
slug: bubblestrap-color-schemes

---

```css
/* Define color schemes */
:root {
  --primary-color: #FF5252;
  --secondary-color: #5C6BC0;
}

:root.blue {
  --primary-color: #2196F3;
  --secondary-color: #FF5252;
}

:root.green {
  --primary-color: #4CAF50;
  --secondary-color: #FF5252;
}

:root.yellow {
  --primary-color: #FFC107;
  --secondary-color: #FF5252;
}
```

You can use these color schemes by applying the appropriate `:root` class to your HTML document. For example, to use the blue color scheme, add the `blue` class to the `html` or `body` element like this:

```css
<html class="blue">
<!-- ... -->
</html>
```

Then you can use the `var(--primary-color)` and `var(--secondary-color)` variables in your CSS to apply the colors. For example:

```css
.header {
  background-color: var(--primary-color);
  color: var(--secondary-color);
}

.btn {
  background-color: var(--secondary-color);
  color: var(--primary-color);
  border-color: var(--primary-color);
}

.btn:hover {
  background-color: var(--primary-color);
  color: #fff;
}
```