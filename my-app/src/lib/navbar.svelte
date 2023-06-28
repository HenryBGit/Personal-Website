<nav>
    <ul>
        <li><a href="/"> Crafting Creations</a></li>
        <li><a href="/worlds">Worlds</a></li>
        <li><a href="/about"> About Crafting Creations</a></li>
    </ul>
</nav>
<style>   

nav {
    background-color: blue;
}
nav ul {
    display: flex;
	justify-content: center;
	text-decoration: none;
	list-style-type: none;
    line-height: 45px;
	margin: 0;
	padding: 0;
	overflow: hidden;
}
nav li a {
    padding: 15px;
    font-size: 30px;
	color: #ececec;
	text-align: center;
    justify-items: center;
	text-decoration: none;
	font-family: 'Cinzel', serif;
}
nav li a:hover {
    background-color: #ec008c;
}
/*Start of Media Queries*/
/* Extra small devices (phones, 600px and down) */
@media only screen and (max-width: 600px) {
    nav li a {
        font-size: 20px;
    }
} 

/* Small devices (portrait tablets and large phones, 600px and up) */
@media only screen and (min-width: 600px) {
    nav li a {
        font-size: 25px;
    }
}

/* Medium devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) {
    nav li a {
        font-size: 20px;
    }
}
/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (min-width: 992px) {
    nav li a {
        font-size: 20px;
    }
}

/* Extra large devices (large laptops and desktops, 1200px and up) */
@media only screen and (min-width: 1200px) {
    nav li a {
        font-size: 30px;
    }
}
/*End of Media Queries*/
</style>