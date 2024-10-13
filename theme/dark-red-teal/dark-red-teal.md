---
marp: true
theme: dark-red-teal
paginate: false
header: '🎨 和風カラーパレット'
---

<div class="content">
  <h1>Dark-red-teal</h1>
  <h2>〜和風カラーパレット〜</h2>

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

</div>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Shippori+Mincho:wght@400;500;600&display=swap');

.content {
  font-family: 'Shippori Mincho', serif;
  display: flex;
  flex-direction: column;
  align-items: center;
  height: 100%;
}

h1 {
  font-size: 2.5em;
  margin-bottom: 3;
}

h2 {
  font-size: 1.5em;
  margin-top: 5;
  color: #348c91;
}

.color-palette {
  display: flex;
  justify-content: space-around;
  width: 100%;
  margin: 20px 0;
}

.color-item {
  text-align: center;
  width: 20%;
}

.color-swatch {
  height: 80px;
  border-radius: 0;
  box-shadow: 0 4px 6px rgba(176, 33, 60, 0.1);
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

.color-info h3 {
  margin: 10px 0 5px;
  font-size: 1.2em;
  font-weight: 600;
}

.color-info p {
  margin: 5px 0;
  font-size: 0.9em;
  color: #348c91;
}

.color-info code {
  font-size: 0.8em;
  background: none;
  border: 1px solid #9c5f98;
  border-radius: 0;
  padding: 2px 5px;
}

.usage {
  width: 100%;
  text-align: center;
}

.usage ul {
  list-style-type: none;
  padding: 0;
  display: flex;
  justify-content: space-around;
}

.usage li {
  margin: 0 10px;
  font-size: 0.9em;
}

footer {
  position: absolute;
  bottom: 10px;
  right: 10px;
  font-size: 0.8em;
  color: #9c5f98;
}
</style>

<footer>和の心、色にあり</footer>
