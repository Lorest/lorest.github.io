<h1> En cliquant sur ce bouton vous gagnez 300 € !</h1>
<button id="btn">CLICK</button>
<div display="none" id="disp"> Bravo vous avez gagné 300€</div>
<script>
  document.getElementById("btn").onclick = display;
  
  function display() {
    document.getElementById("btn").style.display = "block";
  }


</script>
