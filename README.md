# Datacrux
* {
    box-sizing: border-box;
}

body{
    padding: 0px;
    margin: 0px;
    background: #f6f6f6;
}

header{
    background: #008489;
    height: 70px;
}

header * {
    color: white;
}

header.logo {
    float: right;
    height: inherit;

}

header.logo-text{
    margin: 9px;
}

header.logo-text span{
    color: #05f7ff;
}

header ul {
    float: right;
    margin-top: 0px;
    margin: 0px;
    padding: 0px;
    list-style: none;
}

header ul li {
    float: left; 
    margin-top: -3.5em;
}

header ul li a{
    display: block;
    padding: 21px;
    font-size: 1.3em;
    text-decoration: none;
    
}

header ul li a:hover{
    background: #006669;
    transition: 0.5s;
    box-sizing: content-box;
}


@media only screen and (max-width: 750px) {
    header ul {
        width: 100%;
    }
}
