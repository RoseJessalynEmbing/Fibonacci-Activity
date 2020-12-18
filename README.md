<html version="1.0" enoding ="UTF-8">
    <html>
        <head>
            <title> fibonacci.html</title>                    
        </head>
        
       <body>
       <style>
           .image
           {
               background-image: url(https://i.pinimg.com/originals/1e/3d/47/1e3d471b00fc79a07c656588f01708f3.jpg);
               background-repeat: no-repeat;
               background-position: center;
               background-size: cover;
               position: center;
               height: 900px;
               width: 1240px;
           }
           h1
           {
               font-size: 35px;
               color: rgb(157, 78, 189);
               font-family: NoirPro, sans-serif;
               margin-top: 75px;
           }
           h2
           {
               font-size: 35px;
               font-family: NoirPro, sans-serif;
               text-align: center;
               margin-top: 50px;
               color: rgb(157, 78, 189);
           }
       </style>
       </body>

       <h1> Activity 3</h1>
       &nbsp;
       &nbsp;
       <hr>
       <body>
       <h2> Fibonacci Sequence</h2>

       <script type="text/javascript">
        var limit = prompt("Enter the limit 'n' to generate the fibonacci series:"," ");
        var f1 =0;
        var f2 =1;

        
        
        document.write("The limit entered is: " ,limit,"<br/> ");
        document.write("The fibonacci sequence : ");
        document.write("",f1," ");
        document.write("",f2," ");
        

        var i,f3;
        for(i=2; i<limit; i++)
        {
            f3= f1+f2;
            document.write("",f3," ");
            f1=f2;
            f2=f3;
        }
        </script>
    </body>
    </html>
