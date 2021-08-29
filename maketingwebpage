<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8" />
    <title> using the grid system</title>
    <link rel="stylesheet" type="text/css" href="grid_layout_samplewebpage.css"/>
    <style>
    body {
    @import url('https://fonts.googleapis.com/css2?family=Rubik:wght@300&display=swap');
* {
    box-sizing: border-box;
}

body{
    font-family: 'Rubik', sans-serif;
}
.wrapper{
    display: grid;
    grid-gap: 5px;
    grid-template-columns: 15% 35% 35% 15%;
    grid-template-areas:
    'header header header header'
    'nav nav nav nav'
    'side content content ads'
    'footer footer footer footer';
}

.main-nav {
    grid-area: nav;
}
.main-nav ul {
    display: flex;
    list-style: none;
    margin: 0;
    padding: 0;
    background: black;
    columns: white;
}

.main-nav a {
    display: block;
    text-align: center;
    font-size: 1.5em;
    text-decoration: none;
    color: white;
    padding: 5px 10px;
}
.main-nav a:hover{
    background: #ccc;
}
.main-head{
    grid-area: header;
    background: blue;
    padding: 40px;
    font-size: 3em;
    text-align: center;
}

.content{
    grid-area: content;
}
.ads{
    grid-area: ads;
    background: palegreen;
    min-height: 200px;
    text-align: center;
}
.side{
    grid-area: side;
    background: rgb(178, 241, 30);
    min-height: 200px;
    text-align: center;
}

.main-footer{
    grid-area: footer;
    background: crimson;
    padding: 40px;
    font-size: 3em;
    text-align: center;
}
@media (max-width: 600px) {
    .main-nav ul{
     flex-direction:column;
    }
    .wrapper{
        grid-template-columns:auto;
        grid-template-areas: 
       'header' 
       'nav' 
       'content' 
       'side' 
       'ads' 
       'footer';
}

}
    }
    </sytle>
    
    </head>

<body>
    <div class="wrapper">
    <header class="main-head">Header Company Logo</header>
        <nav class="main-nav">
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Products</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    <article class="content">
    <h1>Main area</h1>
    <p>	
    To see the responsive design for tablet and mobile phone screen sizes,right-click.
    Drag the || bar to make the viewport narrower and look at the width value appearing .
    When the width value < 768px (for example, 767px, tablet size), there are 2 sections .
    When the value < 576px (for example, 567px, phone size), there is one section per row.
    To see the responsive design for tablet and mobile phone screen sizes, right-click.
    Drag the || bar to make the viewport narrower and look at the width value appearing . 
    When the width value < 768px (for example, 767px, tablet size), there are 2 sections. 
    When the value < 576px (for example, 567px, phone size), there is one section per row.</p>
    </article>
    <div class="ads">Advertising Here</div>
    <aside class="side">Sidebar</aside>
    <footer class="main-footer">The footer (C) My Company 2025</footer>
  </div>  
   
</body>

</html
