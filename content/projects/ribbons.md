---
title: Ribbons
date: 
subtitle: 
image: '/images/ribbons.jpg'
---
Tie it all together with a ribbon that speaks your style. From soft satins to bold prints and dreamy pastels, pick the perfect finishing touch to match your mood—or your outfit.

<!-- <div class="gallery-box">
  <div class="gallery gallery-columns-2">
    <img src="https://via.placeholder.com/1200x800" loading="lazy" alt="Project">
    <img src="https://via.placeholder.com/1200x800" loading="lazy" alt="Project">
    <img src="https://via.placeholder.com/1200x800" loading="lazy" alt="Project">
    <img src="https://via.placeholder.com/1200x800" loading="lazy" alt="Project">
  </div>
  <em>Gallery / <a href="https://via.placeholder.com/1200x800">Unsplash</a></em>
</div> -->
<br>
<br>

## Current Stock
<br>

<style>
.table-container table {
  border-collapse: collapse;
  width: 100%;
  background: transparent;
}
.table-container tr {
  transition: background 0.4s;
  position: relative;
  overflow: hidden;
}
.table-container tr:hover {
  background: linear-gradient(90deg, #fffbe6 0%, #fff 50%, #fffbe6 100%);
}
.table-container tr:hover::after {
  content: '';
  position: absolute;
  left: -75%;
  top: 0;
  width: 50%;
  height: 100%;
  background: linear-gradient(120deg, rgba(255,255,255,0) 0%, rgba(255,255,255,0.6) 50%, rgba(255,255,255,0) 100%);
  animation: shine 0.8s;
  pointer-events: none;
}
@keyframes shine {
  100% {
    left: 125%;
  }
}
.table-container td {
  border: 1px solid #ccc;
  color: inherit;
  background: transparent;
  padding: 8px 12px;
  text-align: left;
}
.table-container th {
  font-weight: 600;
  background: transparent;
}
.ribbon-color-cell {
  width: 40px;
  height: 24px;
  border-radius: 6px;
  border: 1px solid #ccc;
  display: inline-block;
}
.ribbon-purple { background: #a259e6; }
.ribbon-yellow { background: #ffe066; }
.ribbon-white { background: #fff; }
.ribbon-pink { background: #ffb6c1; }
.ribbon-red { background: #ff4d4f; }
</style>

<div class="table-container">
  <table>
    <tr>
      <th>Ribbon Color</th>
      <th>Color</th>
      <th>In Stock</th>
    </tr>
    <tr>
      <td>Purple</td>
      <td><span class="ribbon-color-cell ribbon-purple"></span></td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Yellow</td>
      <td><span class="ribbon-color-cell ribbon-yellow"></span></td>
      <td>✅</td>
    </tr>
    <tr>
      <td>White</td>
      <td><span class="ribbon-color-cell ribbon-white"></span></td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Pink</td>
      <td><span class="ribbon-color-cell ribbon-pink"></span></td>
      <td>❌ (coming soon)</td>
    </tr>
    <tr>
      <td>Red</td>
      <td><span class="ribbon-color-cell ribbon-red"></span></td>
      <td>❌ (coming soon)</td>
    </tr>
  </table>
</div>