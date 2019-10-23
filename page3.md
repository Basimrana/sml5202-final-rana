<h1>Homework 3</h1>

<p>
<img src="https://www.tanzania-expeditions.com/wp-content/uploads/2014/05/africa-wildlife-giraffes-trees-sky-photo.jpg" width="70%" height="613">
</p>





<h1>Change background colour</h1>

<button type="button" onclick="myFunction()">Set background
color</button>


<script>
var colors = ["red", "green", "blue", "purple"];

function myFunction() {
color = colors[Math.floor(Math.random() *
colors.length)];
document.body.style.backgroundColor = color;
}

