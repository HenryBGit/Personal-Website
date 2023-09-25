<nav>
    <ul>
        <div class="container">
            <li><a href="/"><img src="\Images\Pixel.png" class="logo-img" alt="Pixel Crafters Logo"></a></li>
            <!-- Clickable link on whole container need to talk to adon about this -->
                <div class="text">
                    <li>
                        <a href="/games"> Games
                            <div class="border"></div>
                        </a>                        
                    </li>
                    <li>
                        <a href="/about"> About
                            <div class="border"></div>
                        </a>                        
                    </li>
                    <div class="icons">
                        <li><a><i class="fa-brands fa-instagram"></i></a> </li>
                        <li><a><i class="fa-brands fa-twitter"></i></a></li>
                        <li><a><i class="fa-brands fa-youtube"></i></a></li>
                        <li><a><i class="fa-brands fa-facebook"></i></a></li>
                        <li><a><i class="fa-brands fa-tiktok"></i></a></li>
                    </div>
            </div>
        </div>        
    </ul>
</nav>
<style>
nav {
    width: 100%;
    overflow: hidden;
    background-color: black;
}
nav ul {
    display: flex;
	justify-content: center;
	text-decoration: none;
	list-style-type: none;
	margin: 0;
	padding: 0;
	overflow: hidden;
}
nav li a {
    font-size: 25px; 
	color: white;
	text-decoration: none;
	font-family: 'Cinzel', serif;
    transition: color ease-in 0.35s;
}
nav li a:hover {
    color: #afdbf6;
}
nav li a img {
    padding-top: 3%;
    padding-left: 7%;
    width: 200px;
    display: flex;
    overflow: hidden;
    border-radius: 25px;
}
nav li a img:hover {
    opacity: 0.7;
}

.icons {
    display: inline-flex;
    justify-content: right;
    gap:7px;
    padding-right:75px;
    align-items: center;
    overflow: hidden;
    margin:none;
}
i {
    color: gray;
}
i:hover {
    color: white;
    transition: color 0.5s ease-out;
    cursor: pointer;
}

/*Css For underline hover*/
/*Container that holds the content*/
 .container{
  display:grid;
  grid-template-columns:repeat(2, 1fr);
  width: 100%;
}
/*styling for the underline*/
.border{
  height:2px;
  width:0;
  background:red;
  transition: width .3s linear;
}
/*Positioning the text*/
.text {
    display:inline-flex;
    gap: 10px;
    justify-content: right;
    align-items: center;
}
/*width of the underline*/
.text a:hover .border{
  width:65%;
}

</style>