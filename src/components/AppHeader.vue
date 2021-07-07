<template>
  <div class="topnav">
<ul>
<li>
<a href="#">Home</a>
</li>
<li>
<a href="#">Products</a>
</li>
<li>
<a href="#">Cart</a>
</li>
</ul>
</div>
</template>

<script>
export default {};
</script>

<style scoped>

* {
margin: 0%;
box-sizing: border-box;
}

.topnav {
overflow: hidden;
margin: 0%;
background-color: rgb(77, 67, 67);
top: 0%;
/* background-size: cover; */

padding: 0;
}

.topnav a {
  float: left;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;

}

.topnav ul li {
list-style-type: none;
/* overflow: hidden; */

}

.topnav a:hover {
  background-color: #ddd;
  color: black;
}

</style>