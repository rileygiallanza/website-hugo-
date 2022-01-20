---
widget: blank

headless: false

title: Articles

view: community/article

type: article

design:
  columns: "1"
---
<html>
	<body>
		<div class="grid-container">
			<div class="ui card">
			<div class="image">
				<img src=
"/public-art/featured.jpg">
			</div>
			<div class="content">
				<a class="header">Public Art, Profit, and Climate Change</a>
			</div>
		<form method="get" action="/public-art/">
    <button class="btn1"type="submit">Read!</button>
</form>	
		</div>
	</body>
	<body>
		<div class="grid-container">
			<div class="ui card">
			<div class="image">
				<img src=
"/candid/DSC_3167 (1).jpg">
			</div>
			<div class="content">
				<a class="header">Candid - Photography in the Modern Technological Age                      </a>
			</div>
		<form method="get" action="/candid/">
    <button class="btn1"type="submit">Read!</button>
</form>	
		</div>
	</body>
	<body>
		<div class="grid-container">
			<div class="ui card">
			<div class="image">
				<img src=
"/dramatizing-women/featured.jpg">
			</div>
			<div class="content">
				<a class="header">A Dramatic Response to Being Called Emotional                                </a>
			</div>
		<form method="get" action="/dramatizing-women/">
    <button class="btn1"type="submit">Read!</button>
</form>	
		</div>
	</body>
</html>


<html>
<style>
.grid-container{
  display: grid;
  grid-template-columns: repeat(3, 325px);
  grid-auto-rows: auto;
  grid-gap: 7rem;
}
img {
  height: 250px;
  width: 3000px;
  vertical-align: middle;
}
.card{
  width: 325px;
  padding: 20px;
  text-align: center;
  background: linear-gradient(to top, #f2f7f7 40%, #90a6a6 70%);
  background-color: #00000000;
  border: 0;
  box-shadow: 0 20px 40px -14px rgba(0, 0, 0, 0.25);
  display: flex;
  flex-direction: column;
  overflow: hidden;
}
.btn1 {
  color: #8ba0a3;
  padding: 0.8rem;
  font-size: 14px;
  text-transform: uppercase;
  border-radius: 0.5px;
  font-weight: 500;
  display: block;
  width: 100%;
  cursor: pointer;
  background: transparent;
  tect-align: center;
}
</style>
</html>