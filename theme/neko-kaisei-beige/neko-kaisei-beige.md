---
marp: true
theme: neko-kaisei-beige
---

<style>
section {
  background-color: #f5e6d3;
  color: #5d4037;
  font-family: 'Kaisei Decol', serif;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  height: 100%;
}
h1 {
  color: #795548;
  border-bottom: 2px solid #795548;
  padding-bottom: 0.3em;
  margin-bottom: 0.5em;
}
.color-palette {
  display: flex;
  justify-content: space-around;
  width: 100%;
  margin: 20px 0;
}
.color-item {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.color-box {
  width: 100px;
  height: 100px;
  border: 2px solid #5d4037;
  border-radius: 10px;
  margin-bottom: 10px;
}
.font-samples {
  display: flex;
  justify-content: space-around;
  width: 100%;
  margin: 20px 0;
}
.icon-row {
  display: flex;
  justify-content: space-around;
  width: 100%;
  margin-top: 20px;
}
.icon {
  width: 40px;
  height: 40px;
  fill: #795548;
}
</style>

# Neko Kaisei Beige Theme

<div class="color-palette">
  <div class="color-item">
    <div class="color-box" style="background-color: #f5e6d3;"></div>
    <span>背景色</span>
  </div>
  <div class="color-item">
    <div class="color-box" style="background-color: #5d4037;"></div>
    <span>前景色</span>
  </div>
  <div class="color-item">
    <div class="color-box" style="background-color: #d7ccc8;"></div>
    <span>ハイライト</span>
  </div>
  <div class="color-item">
    <div class="color-box" style="background-color: #8d6e63;"></div>
    <span>薄い色</span>
  </div>
  <div class="color-item">
    <div class="color-box" style="background-color: #795548;"></div>
    <span>アクセント</span>
  </div>
</div>

<div class="font-samples">
  <span style="font-weight: 400;">Kaisei Decol Regular</span>
  <span style="font-weight: 500;">Kaisei Decol Medium</span>
  <span style="font-weight: 700;">Kaisei Decol Bold</span>
</div>

<div class="icon-row">
  <svg class="icon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 2l-5.5 9h11L12 2z"/><circle cx="17.5" cy="17.5" r="3.5"/><circle cx="6.5" cy="17.5" r="3.5"/></svg>
  <svg class="icon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"></path><circle cx="12" cy="7" r="4"></circle></svg>
  <svg class="icon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"></circle><path d="M12 16v-4M12 8h.01"></path></svg>
  <svg class="icon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 8A6 6 0 0 0 6 8c0 7-3 9-3 9h18s-3-2-3-9"></path><path d="M13.73 21a2 2 0 0 1-3.46 0"></path></svg>
</div>
