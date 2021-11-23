# projetoP2

/* Reset */
*{
    margin: 0;
    padding: 0;
    font-size: 100%;
    font-family: "Crimson Text, serif;";
    font-weight: normal;
    box-sizing: border-box;
    border: none;
    outline: none;
    
}
img{max-width: 100%;}
ul{list-style: none;}
a{text-decoration: none;}
h2{font-size: 2em; color: #050000;}
h3{font-size: 3em; color: #333333;}
h4{font-size: 4em; color: black;}
p{font-size: 1em; color: #080000;}

body {
    background-color: lightblue;
  }

h5{
    color: white;
    text-shadow: 4px 4px 6px #000000;
    font-size: 3em;
}

.p1 {
    font-family: "Crimson Text", cursive;
  }

.cabecalho{
    width: 100%;
    float: left;
    padding: 20px 6%;
    background-color: #FFD700;

}

.cabecalho form{
    width: 30%;
    float: right;
}

.cabecalho input[type="text"]{
    width: 85%;
    float: left;
    padding: 10px 10px;
    border-radius: 5px 0 0 5px;
}

.cabecalho button{
    width: 15%;
    float: right;
    padding: 10px 10px;
    background-color: #D8BFD8;
    color: white;
    cursor: pointer;
    border-radius: 0 5px 5px 0;

}

.logo a{
    width: 180px;
    height: 100px;
    float: left;
    background: url(../img/logo.jpg) no-repeat;
    font-size: 0; /* esconder o texto */
    background-size: contain;
}

/* menu */
.menu{
    width: 100%;
    float: left;
    background-color: #FF8C00;
    padding: 18px 8%;
}

.menu li{
    float: left;
}

.menu li a{
    font-size: 150%;
    color: white;
    margin-right: 50px;
}

.menu li a:hover{
    color: slategrey;
}

/* social icons */
.social-icons{
    float: right;
}

.social-icons a{
    color: white;
    float: left;
    margin-left: 12px;
}

.btn-facebook:hover{color: #3B5998;}
.btn-twitter:hover{color:#65A5D6;}
.btn-google:hover{color: #D73D32;}
.btn-instagram:hover{color: #3f729b;}

/* principal */
.principal{
    width: 100%;
    float: left;
    padding: 20px 8%;
}

.sobre{
    width: 100%;
    float: left;
    padding: 0 20px 20px 0;
}
.sobre h2{margin-bottom: 15px;}
.sobre p{text-align: justify;}

/* rodapé*/
.rodape{
    width: 100%;
    float: left;
    background-color: #45a4ed;
    padding: 20px 8%;
}

.rodapep{
    color: white;
}

/*testes*/
  
  div.desc {
    padding: 20px;
    text-align: justify;
    float: left;
    padding: 0 20px 20px 0;
  }

  div.polaroid {
    width: 60%;
    background-color: white;
    box-shadow: 0 4px 6px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
    margin-bottom: 25px;
  }
  
  div.container {
    text-align: center;
    padding: 10px 20px;
  }
