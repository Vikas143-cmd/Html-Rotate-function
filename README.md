# Html-Rotate-function
<html>
    <title></title>
    <body>
        <canvas id ="canvas1" height="2000" width="2000">
        </canvas>
       
        
        <script>
            var  rect1=document.getElementById("canvas1");
            var ctx1 = rect1.getContext("2d");
            
            ctx1.fillStyle="red";
            ctx1.fill();
            ctx1.fillRect(100,100,100,100);
            ctx1.rotate((Math.PI/180)*25);
            ctx1.translate(34,-52);
            
            ctx1.fillStyle="green";
            ctx1.fill();
            ctx1.fillRect(100,100,100,100);
            
        </script>
    </body>
</html>    
