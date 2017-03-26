<!DOCTYPE html>
<html>
<head>
<style>
.nav {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
}

li {
    float: left;
}

li a {
    display: inline-block;
    color: light green;
    text-align: center;
    padding: 14px, 16px;
    text-decoration: none;
}

li a:hover {
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
<li><a href="./about.html">About</a></li>
<li><a href="./login.html">Log in</a></li>
<li><a href="./register.html">Register</a></li>
</ul>
</div>

<a href = "login.html">
<head>
<title>Login</title>
Log in
</head>
<body>
<p>Username</p>
<input>
<p>Password</p>
<input>
<button>Log in</button>
</body>




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
