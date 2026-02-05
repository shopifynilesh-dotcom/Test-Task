## 🌐 Demo Store Access

You can preview the implementation on the development store below:

**Shop URL:**
[https://test-nilesh.myshopify.com/?pb=0](https://test-nilesh.myshopify.com/?pb=0)

**Password:**
`test-nilesh`

Video : https://www.loom.com/share/843379678d7a4b2091560d7f0e66dc6a
---

# Hero Background Layout – Shopify Section (Dawn Theme)

## 📌 Overview

This custom Shopify section is built for the **Dawn theme**.
It creates a **Hero Background Layout** that includes:

* Background image section
* Image + text hero content
* Review slider with dynamic blocks
* Customizable settings via Shopify schema

The section is fully manageable from the Shopify Theme Customizer.

---

## 📂 File Location

```
/sections/hero-background.liquid
```

It also renders the following snippets:

```
/snippets/image-text-hero.liquid
/snippets/review-slider.liquid
```

---

## ✨ Features

* Dynamic background image
* Editable heading, subheading, button & hero image
* Text below button option
* Review slider with:

  * Star rating (1–5)
  * Review text
  * Location
  * Date
* Optional:

  * Navigation arrows
  * Pagination dots
* Fully responsive layout
* Custom radial gradient decorative effect

---

## ⚙️ Section Settings

### Background

* Background Image

### Image Text Section

* Heading
* Subheading
* Button Text
* Button URL
* Text below button
* Hero Image

### Review Slider Settings

* Show arrows (checkbox)
* Show dots (checkbox)

---

## 🧱 Blocks

### Review Block

Each review includes:

* Review Text
* Rating (1–5)
* Location
* Review Date

Multiple review blocks can be added from the theme customizer.

---

## 🚀 Installation

1. Go to **Online Store → Themes**
2. Click **Edit Code**
3. Upload `hero-background.liquid` into:

   ```
   /sections
   ```
4. Make sure these snippets exist:

   ```
   image-text-hero.liquid
   review-slider.liquid
   ```
5. Go to **Customize Theme**
6. Add section → Select **Hero Background Layout**

---

## 🎨 Styling

Custom CSS is included inside the section using:

```liquid
{% style %} ... {% endstyle %}
```

Includes:

* Background cover styling
* Responsive padding
* Decorative radial gradient
* Mobile optimization

---

## 📱 Responsive Behavior

* Desktop padding: `64px 80px`
* Mobile padding: `48px 16px`
* Gradient effect scales down on smaller screens

---

## 📦 Dependencies

* Shopify Dawn Theme
* Swiper used inside `review-slider` snippet
* Shopify 2.0 

---
