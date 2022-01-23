---
widget: blank

headless: false

title: PHOTOGRAPHY

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
"/portraits/image.jpg">
			</div>
			<div class="content">
			</div>
		<a method="get" href="/portraits/">
    <button class="btn1"type="submit">Portraits</button>
</a>	
		</div>
	</body>
</html>

<html>
	<body>
		<div  class="grid-container">
			<div class="ui card">
			<div class="image">
				<img src=
"/travel/image.jpg">
			</div>
			<div class="content">
			</div>
		<a method="get" href="/travel/">
    <button class="btn1"type="submit">Landscapes & Cityscapes</button>
</a>	
		</div>
	</body>
</html>

<html>
<style>
.grid-container{
  display: grid;
  grid-template-columns: repeat(2, 500px);
  grid-auto-rows: auto;
  grid-gap: 13.5rem;
  align: center;
}
.card{
  width: 500px;
  padding: 20px;
  border: 1px;
  text-align: center;
  background: transparent;

}
img {
  width: auto;
  align: center;
}
.btn1 {
  color: hsla(195, 58%, 43%, 1.0);
  font-size: 25px;
  border: 0;
  font-weight: 50;
  width: 100%;
  cursor: pointer;
  background: transparent;
  padding: 15px;
}
.btn1:hover {
  background-color: #e9ecee;
}
</style>
</html>