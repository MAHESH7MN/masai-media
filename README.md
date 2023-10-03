# masai-media
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Media-Querise</title>
</head>
<style>
    *{
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }
    #parant{
        width: 1200px;
        padding: 20px 10px;
        margin: 50px auto;
        display: flex;
        flex-wrap: wrap;
        justify-content: space-evenly;
        align-items: center;
        box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
        border-radius: 10px;
        gap: 16px;
    }
    #parant>.card{
        width: 367px;
        padding: 20px;
        border-radius: 10px;
        box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px; 
    }
    #parant > .card > div {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    #parant > .card > div h2{   
        width: 50%;
        font-family: poppins;
    }
    #parant > .card > div span{
        width: 10%;
        font-weight: 700;
        font-size: 1.5rem;
        /* margin-left: 150px; */
        color: coral;
    }
    p{
        font-size: 20px;
        /* margin-left: 15px; */
        margin-top: 60px;
        color:  #6c6768;
    }

    @media (min-width: 575px) and (max-width: 767px) {
        #parant{
            width: 80%;
        }
        #parant>.card{
            width: 80%;
        }
    }
    
    @media (min-width: 768px) and (max-width: 997px){
        #parant{
            width: 80%;
        }
        #parant>.card{
            width: 48%;
        }
    }

</style>
<body>
   <div id="parant">
    <div class="card">
        <div>
            <h2>Cappuccino</h2>
            <span>$49</span>
        </div>
        
        <p>Usage of the internet is becoming more common due to rapid advance.</p>    
    </div>
   <div class="card">
        <div>
            <h2>Americano</h2>
            <span>$49</span>
        </div>
        <p>Usage of the internet is becoming more common due to rapid advance.</p>    
   </div>
   <div class="card">
        <div>
            <h2>Espresso</h2>
            <span>$49</span>
        </div>
        
        <p>Usage of the internet is becoming more common due to rapid advance.</p>    
   </div>
   <div class="card">
        <div>
            <h2>Macchiato </h2>
            <span>$49</span>
        </div>
        
        <p>Usage of the internet is becoming more common due to rapid advance.</p>    
   </div>
   <div class="card">
        <div>
            <h2>Mocha </h2>
            <span>$49</span>
        </div>
       
        <p>Usage of the internet is becoming more common due to rapid advance.</p>    
   </div>
   <div class="card">
        <div>
            <h2>Coffee Latte</h2>
            <span>$49</span>
        </div>
        
        <p>Usage of the internet is becoming more common due to rapid advance.</p>    
   </div>
   <div class="card">
        <div>
            <h2>Piccolo Latte</h2>
            <span>$49</span>
        </div>
       
        <p>Usage of the internet is becoming more common due to rapid advance.</p>    
   </div>
   <div class="card">
        <div>
            <h2>Ristretto</h2>
            <span>$49</span>
        </div>
         <p>Usage of the internet is becoming more common due to rapid advance.</p>    
   </div>
   <div class="card">
        <div> 
            <h2>Affogato </h2>
            <span>$49</span>
        </div>
        <p>Usage of the internet is becoming more common due to rapid advance.</p>    
   </div>
   </div>
   

</body>
</html>
