---
marp: true
theme: dark-red-teal
paginate: true
header: '🎨 和風カラーパレット'
---

<!-- _class: lead -->

# 和風カラーパレット
## 〜深み和色の世界〜

---

<div class="color-palette">
  <div class="color-item">
    <div class="color-swatch" style="background-color: #b0213c;"></div>
    <div class="color-info">
      <h3>濃紅</h3>
      <p>Kōbeni</p>
      <code>#b0213c</code>
    </div>
  </div>
  <div class="color-item">
    <div class="color-swatch" style="background-color: #348c91;"></div>
    <div class="color-info">
      <h3>天色</h3>
      <p>Amairo</p>
      <code>#348c91</code>
    </div>
  </div>
  <div class="color-item">
    <div class="color-swatch" style="background-color: #9c5f98;"></div>
    <div class="color-info">
      <h3>菫色</h3>
      <p>Sumire-iro</p>
      <code>#9c5f98</code>
    </div>
  </div>
  <div class="color-item">
    <div class="color-swatch" style="background-color: #b8cfd0;"></div>
    <div class="color-info">
      <h3>白磁</h3>
      <p>Hakuji</p>
      <code>#b8cfd0</code>
    </div>
  </div>
</div>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Shippori+Mincho:wght@400;500;600&display=swap');

.color-palette {
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
  margin-top: 40px;
}
.color-item {
  text-align: center;
  margin: 10px;
  width: 200px;
  font-family: 'Shippori Mincho', serif;
}
.color-swatch {
  height: 120px;
  border-radius: 0;
  box-shadow: 0 4px 6px rgba(176, 33, 60, 0.1);
  transition: all 0.3s ease;
  position: relative;
  overflow: hidden;
}
.color-swatch::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: 
    linear-gradient(45deg, transparent 49.5%, #b8cfd0 49.5%, #b8cfd0 50.5%, transparent 50.5%),
    linear-gradient(-45deg, transparent 49.5%, #b8cfd0 49.5%, #b8cfd0 50.5%, transparent 50.5%);
  background-size: 20px 20px;
  opacity: 0.1;
}
.color-swatch:hover {
  transform: scale(1.05);
}
.color-info h3 {
  margin: 15px 0 5px;
  font-size: 1.4em;
  font-weight: 600;
}
.color-info p {
  margin: 5px 0;
  font-size: 1em;
  color: #348c91;
}
.color-info code {
  font-size: 0.9em;
  background: none;
  border: 1px solid #9c5f98;
  border-radius: 0;
  padding: 2px 5px;
}
</style>

---

<!-- _class: invert -->

# 和風カラーパレットの使い方

- **濃紅（Kōbeni）**: 強調や警告に使用
- **天色（Amairo）**: リンクやアクセントに最適
- **菫色（Sumire-iro）**: 優しさや女性らしさを表現
- **白磁（Hakuji）**: 背景や文字色として使用

---

# 配色例

<div class="example-box">
  <h3>和風ウェブサイトのヘッダー</h3>
  <div class="example-content">
    <div class="header-example">
      <div class="logo">素敵な和菓子屋</div>
      <div class="nav">
        <a href="#">ホーム</a>
        <a href="#">商品一覧</a>
        <a href="#">お問い合わせ</a>
      </div>
    </div>
  </div>
</div>

<style scoped>
.example-box {
  background: #f7f7f7;
  border: 1px solid #348c91;
  padding: 20px;
  border-radius: 5px;
}
.header-example {
  background: #b0213c;
  color: #b8cfd0;
  padding: 15px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.logo {
  font-size: 1.5em;
  font-weight: bold;
}
.nav a {
  color: #b8cfd0;
  margin-left: 15px;
  text-decoration: none;
  border-bottom: 2px solid transparent;
  transition: border-color 0.3s;
}
.nav a:hover {
  border-color: #9c5f98;
}
</style>

---

<!-- _class: lead -->

# ご清聴ありがとうございました
## 和の心、色にあり
