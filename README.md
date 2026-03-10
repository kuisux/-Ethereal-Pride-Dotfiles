<div align="center">
  <h1>🏳️‍⚧️ Ethereal Pride</h1>
  <p><i>A dreamy, high-contrast design system inspired by the Transgender Pride flag.</i></p>

  <img src="https://raw.githubusercontent.com/rktjmp/lush.nvim/main/assets/lush_logo.png" width="100" alt="Lush Logo">
</div>

<hr />

## 🎨 The Palette
This palette is engineered for professional readability by balancing deep "Night Sky" foundations with vibrant pastel accents.

<table>
  <tr>
    <th>Color</th>
    <th>Hex</th>
    <th>Usage</th>
  </tr>
  <tr>
    <td><img src="https://via.placeholder.com/15/F7A8B8/000000?text=+" alt="Pink"> <b>Cotton Pink</b></td>
    <td><code>#F7A8B8</code></td>
    <td>Active borders, Keywords, Primary accents</td>
  </tr>
  <tr>
    <td><img src="https://via.placeholder.com/15/5BCEFA/000000?text=+" alt="Blue"> <b>Sky Blue</b></td>
    <td><code>#5BCEFA</code></td>
    <td>Functions, Links, Selection borders</td>
  </tr>
  <tr>
    <td><img src="https://via.placeholder.com/15/FFFFFF/000000?text=+" alt="White"> <b>Cloud White</b></td>
    <td><code>#FFFFFF</code></td>
    <td>Strings, Constants, Pure highlights</td>
  </tr>
  <tr>
    <td><img src="https://via.placeholder.com/15/111218/000000?text=+" alt="Black"> <b>Deep Night</b></td>
    <td><code>#111218</code></td>
    <td>Main application background</td>
  </tr>
  <tr>
    <td><img src="https://via.placeholder.com/15/E4E7ED/000000?text=+" alt="Gray"> <b>Trans Gray</b></td>
    <td><code>#E4E7ED</code></td>
    <td>Primary foreground text</td>
  </tr>
</table>

---

## 🌟 Visual Principles

### 🌈 Hex-Gradients
Ethereal Pride utilizes **linear hex-gradients** to represent the full pride flag on a single element. By transitioning between `#F7A8B8` and `#5BCEFA` at a 45° angle, UI elements gain a vibrant, "glowing" effect.



### 🧪 Design Implementation
* **Active Borders**: 3px wide 45deg gradient for high-visibility focus tracking.
* **Background Layering**: Primary content sits on **Deep Night**, while sidebars use the slightly lighter **Deep Mantle** (`#191B24`) for depth.
* **Motion**: Custom `overshot` Bezier curves (`0.05, 0.9, 0.1, 1.1`) provide a tactile, "bouncy" feel to the soft color palette.

---

## 🛠️ Configuration Snippets

### 🌙 Discord (Midnight CSS)
```css
:root {
    --accent-1: #F7A8B8; /* Cotton Pink */
    --accent-2: #5BCEFA; /* Sky Blue */
    --text-1: #E4E7ED;   /* Primary Text */
    --bg-4: #111218;     /* Main Background */
}
❄️ Hyprland (2026 Unified Syntax)
Ini, TOML
windowrule {
    name = active-glow
    match:class = .*
    col.active_border = rgba(F7A8B8ee) rgba(5BCEFAee) 45deg
}
<hr />

<div align="center">
<p>Built with ❤️ for the Trans community.</p>
</div>
