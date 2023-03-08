---
title: "Bubblestrap - Buttons"
datePublished: Wed Mar 08 2023 03:07:29 GMT+0000 (Coordinated Universal Time)
cuid: clez3nho5000a09mmfu1u6n71
slug: bubblestrap-buttons

---

```css
/* Define button styles */
.btn {
  display: inline-block;
  padding: 12px 24px;
  font-size: 18px;
  font-weight: 700;
  border-radius: 50px;
  border: 2px solid #FF5252;
  background-color: #FF5252;
  color: #fff;
  transition: all 0.3s ease;
}

.btn:hover {
  background-color: transparent;
  color: #FF5252;
}

.btn-secondary {
  border-color: #5C6BC0;
  background-color: transparent;
  color: #5C6BC0;
}

.btn-secondary:hover {
  background-color: #5C6BC0;
  color: #fff;
}

.btn-outline {
  border-color: #FF5252;
  background-color: transparent;
  color: #FF5252;
}

.btn-outline:hover {
  background-color: #FF5252;
  color: #fff;
}

/* Define custom button styles */
.btn-custom {
  border-color: #FFC107;
  background-color: #FFC107;
  color: #fff;
}

.btn-custom:hover {
  background-color: transparent;
  color: #FFC107;
}

.btn-custom-outline {
  border-color: #4CAF50;
  background-color: transparent;
  color: #4CAF50;
}

.btn-custom-outline:hover {
  background-color: #4CAF50;
  color: #fff;
}

.btn-custom-2 {
  border-color: #FF9800;
  background-color: #FF9800;
  color: #fff;
}

.btn-custom-2:hover {
  background-color: transparent;
  color: #FF9800;
}

.btn-custom-3 {
  border-color: #03A9F4;
  background-color: #03A9F4;
  color: #fff;
}

.btn-custom-3:hover {
  background-color: transparent;
  color: #03A9F4;
}

/* Assign custom styles */
.btn-custom-2 {
  font-size: 20px;
  padding: 16px 32px;
}

.btn-custom-3 {
  font-size: 22px;
  padding: 18px 36px;
}
```

You can use these button styles by applying the appropriate classes to your HTML elements. For example:

```css
<a href="#" class="btn">Click me!</a>

<button class="btn btn-secondary">Learn more</button>

<input type="submit" class="btn btn-outline" value="Submit">
```

You can use these custom button styles by applying the appropriate classes to your HTML elements. For example:

```xml
<a href="#" class="btn btn-custom">Click me!</a>
<button class="btn btn-custom-outline">Learn more</button>
<input type="submit" class="btn btn-custom-2" value="Submit">
<button class="btn btn-custom-3">Read more</button>
```

And the custom styles assigned to .btn-custom-2 and .btn-custom-3 will be applied to those buttons, giving them a larger font size and different padding than the other buttons.