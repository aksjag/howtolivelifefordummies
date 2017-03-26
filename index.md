<!DOCTYPE html>
<html>
<head>
<style>
.nav {
    list-style: none;
    text-align: right;
    padding: 1.3%;
    position: fixed;
    width: 100%;
    z-index: 20;

}

/* Option 1 - Display Inline */
.nav li {
    display: inline-block;
    font-size: 150%;
    margin-right: 3%;
    font-family: 'Fjalla One', sans-serif;
    font-weight: 100;

}

.nav a {
    text-decoration: none;
    color: #fff;
    display: block;
    transition: .3s background-color;
    -webkit-transition: font-size ease 2s;
    -moz-transition: font-size ease 2s;
    -o-transition: font-size ease 2s;
    text-decoration: none;
    position: relative;
    color: #ffffff;
}

.nav a:hover:after {
    width: 100%;
    font-size: 109%;
}


.nav a:after {
    content: '';
    position: absolute;
    bottom: 0;
    left: 0;
    width: 0%;
    border-bottom: 3px solid #32CD32;
    transition: 0.4s;
}

nav.navbar {
    background: #ffffff;
    -webkit-transition: all 0.4s ease;
    transition: all 0.4s ease;

}
   

</style>
<title>Livin Life</title>
</head>
<body>
<div class="nav_bar">
<ul>
<li><a href="/howtolivelifefordummies">Home</a></li>
<li><a href="/about">About</a></li>
<li><a href="/login">Log in</a></li>
<li><a href="/register">Register</a></li>
</ul>
</div>

<a href="about.html" target="_self">Link to About Page</a>
<h>About</h>




<h1>Log in</h1>
<p>Username</p>
<input>
<p>Password</p>
<input>
<button>Log in</button>

<h2>Don't have one? Sign up for a free account today!</h2>
<p>Name</p>
<input>
<p>Email</p>
<input>
<p>Gender</p>
<input>
<p>Age</p>
<input>
<button>Continue</button>


</body>
</html>
