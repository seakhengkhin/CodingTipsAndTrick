## Full Examples of Flexbox Properties

Here are full examples of each flexbox property, showcasing their various values:

### 1. flex-direction

The `flex-direction` property defines the main axis of the flex container, which determines the direction of its children. It can take the following values:

* **row:** The main axis is horizontal, and the children are laid out in a row from left to right.
* **row-reverse:** The main axis is horizontal, but the children are laid out in a row from right to left.
* **column:** The main axis is vertical, and the children are laid out in a column from top to bottom.
* **column-reverse:** The main axis is vertical, but the children are laid out in a column from bottom to top.

**Example:**

```html
<div class="container" style="display: flex; flex-direction: row;">
  <div>Item 1</div>
  <div>Item 2</div>
  <div>Item 3</div>
</div>

<div class="container" style="display: flex; flex-direction: column;">
  <div>Item 1</div>
  <div>Item 2</div>
  <div>Item 3</div>
</div>
```

### 2. justify-content

The `justify-content` property defines the alignment of the flex items along the main axis of the container. It can take the following values:

* **flex-start:** Aligns the items to the start of the main axis.
* **flex-end:** Aligns the items to the end of the main axis.
* **center:** Centers the items along the main axis.
* **space-between:** Distributes the items evenly between the start and end of the main axis.
* **space-around:** Distributes the items evenly, with equal spacing between them and the container edges.
* **space-evenly:** Distributes the items evenly, with equal spacing between them.

**Example:**

```html
<div class="container" style="display: flex; justify-content: flex-start;">
  <div>Item 1</div>
  <div>Item 2</div>
  <div>Item 3</div>
</div>

<div class="container" style="display: flex; justify-content: space-between;">
  <div>Item 1</div>
  <div>Item 2</div>
  <div>Item 3</div>
</div>
```

### 3. align-items

The `align-items` property defines the alignment of the flex items along the cross axis of the container. It can take the following values:

* **flex-start:** Aligns the items to the start of the cross axis.
* **flex-end:** Aligns the items to the end of the cross axis.
* **center:** Centers the items along the cross axis.
* **baseline:** Aligns the items to their baselines.
* **stretch:** Stretches the items to fill the cross axis.

**Example:**

```html
<div class="container" style="display: flex; align-items: flex-start;">
  <div>Item 1</div>
  <div>Item 2</div>
  <div>Item 3</div>
</div>

<div class="container" style="display: flex; align-items: center;">
  <div>Item 1</div>
  <div>Item 2</div>
  <div>Item 3</div>
</div>
```

### 4. align-content

The `align-content` property defines the alignment of the flex lines along the cross axis of the container. It can take the following values:

* **flex-start:** Aligns the lines to the start of the cross axis.
* **flex-end:** Aligns the lines to the end of the cross axis.
* **center:** Centers the lines along the cross axis.
* **space-between:** Distributes the lines evenly between the start and end of the cross axis.
* **space-around:** Distributes the lines evenly, with equal spacing between them and the container edges.
* **space-evenly:** Distributes the lines evenly, with equal spacing between them.
* **stretch:** Stretches the lines to fill the cross axis.

**Example:**

```html
<div class="container" style="display: flex; flex-wrap: wrap; align-content: flex-start;">
  <div>Item 1</div>
  <div>Item 2</div>
  <div>Item 3</div>
</div>

<div class="container" style="display: flex; flex-wrap: wrap; align-content: space-between;">
  <div>Item 1</div>
  <div>Item 2</div>
  <div>Item 3</div>
</div>
```

### 5. flex-wrap

The `flex-wrap` property defines whether the flex items should wrap onto multiple lines if they don't fit on one line. It can take the following values:

* **nowrap:** The flex items will not wrap onto multiple lines.
* **wrap:** The flex items will wrap onto multiple lines if they don't fit on one line.
* **wrap-reverse:** The flex items will wrap onto multiple lines in reverse order.

**Example:**

```html
<div class="container" style="display: flex; flex-wrap: nowrap;">
  <div>Item 1</div>
  <div>Item 2</div>
  <div>Item 3</div>
</div>

<div class="container" style="display: flex; flex-wrap: wrap;">
  <div>Item 1</div>
  <div>Item 2</div>
  <div>Item 3</div>
</div>
```

These examples demonstrate the various ways you can use flexbox properties to control the layout of your flex items. By understanding these properties and their values, you can create flexible and responsive layouts that adapt to different screen sizes and devices.