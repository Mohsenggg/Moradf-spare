
<!-- sidebare code -->
<!-- <div id="sidebar" class="">
	<ul>
			<li><a href="#vission">Vision</a></li>
			<li><a href="#lense">Lens</a></li>
			<li><a href="#skills">Skills</a></li>
			<li><a href="#students">Students</a></li>
			<li><a href="#springs">Springs</a></li>
			<li><a href="#team">Team</a></li>
	</ul>
</div>
<div id="sidebar-btn" class="sidebar-c">
	<span></span>
	<span></span>
	<span></span>
</div>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js">
</script>
<script >
	$(document).ready(function() {
		$('#sidebar-btn').click(function() {
			$('#sidebar').toggleClass('visible');
		});
	});
</script> -->





/* side bar */
/* #sidebar{
  background: yellow;
  width: 200px;
  height: 100%;
  display: block;
  position: absolute;
  left: -200px;
  top: 0px;
  transition: left 0.3s linear;
} */

/* #sidebar.visible{
  left: 0px;
  transition: left 0.3s linear;
}

#sidebar ul {
  margin: 0px;
  padding: 0px;
}

#sidebar ul li {
  list-style: none;
}

#sidebar ul li a{
  background: gray;
  color: red;
  border-bottom: 1px solid black;
  display: block;
  width: 180px;
  padding: 10px;
  text-decoration: none;
}

#sidebar-btn {
  display: inline-block;
  vertical-align: middle;
  width: 20px;
  height: 15px;
  /* left: 0px;
  /* right: -60px; */
  /* top: 0px; */
  /* position: absolute;
  cursor: pointer;
  margin: 3px 10px 3px 10px;
  padding: 15px 20px 15px 20px;
}


#sidebar-btn span{
  height: 2px;
  background: white;
  margin-bottom: 5px;
  display: block;
}

#sidebar-btn span:nth-child(2){
  width: 75%;
}

#sidebar-btn span:nth-child(3){
  width: 50%;
}

#sidebar-btn:hover {
  background-color: #ddd;
  color: #ddb000;
} */ */


/* Set the width of the side navigation to 250px */
function openNav() {
  document.getElementById("mySidenav").style.width = "250px";
}

/* Set the width of the side navigation to 0 */
function closeNav() {
  document.getElementById("mySidenav").style.width = "0";
}
