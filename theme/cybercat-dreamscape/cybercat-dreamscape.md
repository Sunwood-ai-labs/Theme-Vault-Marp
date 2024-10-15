---
marp: true
theme: cybercat-dreamscape
---

<!-- _class: lead -->
<style>
h1, h2 {
  margin-bottom: 0.5em;
}
.container {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.color-palette, .gradient-examples {
  display: flex;
  justify-content: space-around;
  align-items: center;
  width: 100%;
  margin-bottom: 2em;
}
.color-item{
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 180px;
}
gradient-item {
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 280px;
}
.color-swatch {
  width: 100px;
  height: 100px;
  border-radius: 50%;
  margin-bottom: 10px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: none;
}
.color-name, .gradient-name {
  font-weight: 900;
  margin-bottom: 5px;
  font-size: 0.9em;
}
.color-code, .gradient-code {
  font-size: 0.8em;
}
.gradient-bar {
  width: 260px;
  height: 30px;
  border-radius: 15px;
  margin-bottom: 10px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}
</style>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

<div class="container">

# Cybercat Dreamscape

<div class="color-palette">
  <div class="color-item">
    <div class="color-swatch">
      <i class="fas fa-cat fa-4x" style="color: #8C3545;"></i>
    </div>
    <div class="color-name">バーガンディ</div>
    <div class="color-code">#8C3545</div>
  </div>
  <div class="color-item">
    <div class="color-swatch">
      <i class="fas fa-paw fa-4x" style="color: #26020C;"></i>
    </div>
    <div class="color-name">ダーク</div>
    <div class="color-code">#26020C</div>
  </div>
  <div class="color-item">
    <div class="color-swatch">
      <i class="fas fa-fish fa-4x" style="color: #253C59;"></i>
    </div>
    <div class="color-name">ネイビー</div>
    <div class="color-code">#253C59</div>
  </div>
  <div class="color-item">
    <div class="color-swatch">
      <i class="fas fa-ghost fa-4x" style="color: #329AA6;"></i>
    </div>
    <div class="color-name">ティール</div>
    <div class="color-code">#329AA6</div>
  </div>
  <div class="color-item">
    <div class="color-swatch">
      <i class="fas fa-moon fa-4x" style="color: #F2DDB6;"></i>
    </div>
    <div class="color-name">サンド</div>
    <div class="color-code">#F2DDB6</div>
  </div>
</div>

<div class="gradient-examples">
  <div class="gradient-item">
    <div class="gradient-bar" style="background: linear-gradient(45deg, #8C3545, #329AA6);"></div>
    <div class="gradient-name">バーガンディ to ティール</div>
  </div>
  <div class="gradient-item">
    <div class="gradient-bar" style="background: linear-gradient(to right, #26020C, #F2DDB6);"></div>
    <div class="gradient-name">ダーク to サンド</div>
  </div>
  <div class="gradient-item">
    <div class="gradient-bar" style="background: linear-gradient(to right, #253C59, #8C3545);"></div>
    <div class="gradient-name">ネイビー to バーガンディ</div>
  </div>
</div>

</div>
