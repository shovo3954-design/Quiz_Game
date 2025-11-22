# html_project

*{
    padding:0;
    margin:0;
}

#index{
    background-color:rgb(21, 21, 91);
    background-image:url(/badminton_background.jpg);
    background-size:cover;

}
#football{
    background-color:orange;
    background-image:url(/football_background.jpg);
    background-size:cover;

}
#cricket{
    background-color:aqua;
    background-image:url(/cricket_background.jpg);
    background-size:cover;
}
#badminton{
    background-color:yellowgreen;
    background-image:url(/badminton_background.jpg);
    background-size:cover;
}
#tennis{
    background-image:url(/tennis_background.jpg);
    background-size:cover;
}
#account{background-color:rgb(21, 21, 91)}
.myclass{
    color:white;
    font-size:25px;
    margin-left:20px;
}
i{color:bisque;}
#information{color:white;}
#attention{color:yellow;}
u{color:red;}
.hi{color:white;}
#option{color:yellow;}
#scroll{color:black;}
/* #price{color:blue;} */
.C_price{
    text-decoration:line-through;
    color:red;
    font-size:35px;

}

.price{
    font-size:30px;
    position:relative;
    left:600px;

}

.enter{
    font-size:25px;
    background-color:white;
    color:black;
    position:relative;
    left:600px;
}
.border{
    border:3px solid black;
    position:relative;
    left:600px;
}
#header_footer{
    background-color:#0f1111;
    /* margin-right:200px; */
    height:70px;
    width:1600px;
    font-size:27px;
    color:white;
    position:fixed;
    z-index:2;
    display:flex;
    justify-content:space-evenly;

}

.header_button{
    height:20px;
}
#logo{
    font-size:25px;
    color:#f08804;
    margin-right:220px;
}
.account{
    margin-right:220px;
    color:white;
}
#firstbutton{
    color:#f08804;
}
#margin_account{
    margin-left:600px;
    font-size:35px;
}
.li_color{
    color:yellow;
}

#footer_index{
    background-color:#0f1111;
    height:500px;
    color:white;

}

.footer_div_one{
    height:280px;
    width:280px;
    color:white;
    display:inline-block;
    margin:25px;
    padding:25px;
    /* background-color:blue; */
}
.foter_link{
    color:white;
}
.products_ol{
    position:relative;
    left:600px;
}
.badminton_div_one{
    background-image:url(/badminton_background.jpg);
    background-size:cover;
    color:white;
}
.cricket_div_one{
    background-image:url(/cricket_background.jpg);
    background-size:cover;
    color:white;

}
.football_div_one{
    background-image:url(/football_background.jpg);
    background-size:cover;
    color:white;    
}
.tennis_div_one{
    background-image:url(/tennis_background.jpg);
    background-size:cover;
    color:white; 
}

.my_animation{
    width:1600px;
    height:650px;
    background-image:url(/sport.webp);
    background-size:cover;
    animation: imageAnimate 10s ease-in 3s infinite normal;
}

@keyframes imageAnimate{
    from{background-image:url(/sport.webp)}
    to{background-image:url(/badminton_background.jpg)}
}
  
