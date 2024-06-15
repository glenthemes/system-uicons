## system-uicons / icon font

Originally by https://github.com/CoreyGinnivan/system-uicons  
Compiled all 420 icons into an icon font for easier use.

License info: https://git.io/JauxP

Last updated: Oct. 5th 2021 10:39AM (GMT+8)

---

🛎️ As of June 2024, a CSS-only icon font version is now available! Check it out [on the main page](https://git.io/Jaz87).

---

#### 🔥 HOW TO USE:

Paste the following under the `<head>` tag on your site:
```html
<script src="//glenthemes.github.io/system-uicons/init-icons.js"></script>
<link href="//glenthemes.github.io/system-uicons/style.css" rel="stylesheet">
```

To use an icon, insert the following in your HTML wherever you want it:
```
<i class="system-uicons" icon-name="create"></i>
```

Choose one from [the list](https://systemuicons.com/) and copy the name (don't click on it), and paste it between the quotation marks `""` of `icon-name=""`
.

If the icon name contains dashes, brackets, or `%` signs, **please include them.**

---

#### 🔥 HOW TO CUSTOMIZE:

To set the general size & color of the icons, add this to your CSS and adjust as necesary:
```css
.system-uicons {
  --System-UIcons-Color:#beabea;
  --System-UIcons-Size:16px;
}
```

If you want to use the icons again in another location with different styling:  
e.g.:
```css
.special-class {
  --System-UIcons-Color:#c2a7a8;
}
```
---

#### 🔥 TROUBLESHOOTING:

https://discord.gg/RcMKnwz
