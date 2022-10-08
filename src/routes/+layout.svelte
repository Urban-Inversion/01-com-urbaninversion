<script>
import '../app.css';
</script>


<style>
@import url('https://fonts.googleapis.com/css2?family=Marmelad&family=Pacifico&family=Special+Elite&family=Tangerine:wght@400;700&family=Ultra&display=swap');


ul.no-bullets {
  list-style-type: none;
  margin: 0;
  padding: 0;
}
ul {
  text-align: left;
} 
li {
  display: inline;
}
nav a {
    padding: 5px;
    font-family: 'Special Elite', sans-serif;
    color: darkolivegreen;
    font-size: 24px;
     }

</style>
<nav>
<ul class="no-bullets">
<li>
<a href="/">Photos</a>
</li>
<li>
<a href="/about">History</a>
</li>
<li>
<a href="/ode">Poem</a>
</li>
<li>
<a href="/contact">Contact</a>
</li>
</nav>

                

<slot></slot>

