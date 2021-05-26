ul {
    text-align: center;
      list-style: none;
      margin: 100;
      padding: 0;
      background-color: rgba(212, 172, 62, 0.596);
      
    }
    
  
    .menu >li 
    {
      display:inline-block;
      
    }
    .menu > li > a {
      display: block;
      color: rgb(255, 255, 255);
      padding: 20px 50px;
      text-decoration: none;
      
          }
    
    li a:hover 
    {
      background-color:  #1a550e;
      transition: all .3s;
      
    }
  
     .submenu
     {
       width: 13%;
      text-align: center;
      position: absolute;
      background: rgba(61, 55, 55, 0.644);
      visibility:hidden;
      opacity:3 ;
      transition: opacity 1.5s;
      z-index: 9;
      position: absolute
      
     }
     .submenu li a
     {
      
         display: block;
         padding:17px;       
         color: #fff;
         font-family:Verdana, Geneva, Tahoma, sans-serif;
         text-decoration: none;
         text-align: center;
         
     }
     .menu li:hover .submenu
     {
         visibility: visible;
         opacity: 1;
        
     }
  
    /* .active 
     {
      background-color: #1a550e
     }
   end of navigation bar */
   body {
      background-image: url(fondo5.jpg);
      background-repeat: no-repeat;
        background-attachment: fixed;
        background-size: cover;
        background-position: bottom;
        
       }
     
      
      
      
    
    div1
     {
  background-color: rgba(207, 207, 207, 0.397);
  text-align: center;
  font-size: 60px;
  font-weight:bold;
  color: rgb(247, 247, 247);
  font-family: monospace;
  position:absolute;
  left: 5%;
  
     }
     .otro
     {
      display:block;
      position:absolute;
      text-align: center;
      margin: auto;
      width: 30%;
      padding:80px;
          
      
    }
     div2
     {
     
  background-color: rgba(78, 165, 61, 0.295);
  text-align: center;
  font-size: 20px;
  font-weight:bold;
  color: rgb(247, 247, 247);
  font-family: monospace;
  position: absolute;
  right: 5%; 
    }

    .container {
      position: relative;
      left: 3%;
      width: 40%;
    }
 
    
    .image {
      opacity: 0.9;
      display: block;
      width: 100%;
      height: auto;
      transition: .5s ease;
      backface-visibility: hidden;
    }
    
    .middle {
      transition: .5s ease;
      opacity: 0;
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      -ms-transform: translate(-50%, -50%);
      text-align: center;
    }
    
    .container:hover .image {
      opacity: 0.3;
    }
    
    .container:hover .middle {
      opacity: 1;
    }

    
    .text {
      background-color: #04AA6D;
      color: white;
      font-size: 16px;
      padding: 16px 32px;

      /*Final container*/
    } 

    .container1{
      position:relative;
      right:10%;
      width: 40%;
          }
          



