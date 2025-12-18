# Ex.06 Restaurant Website
# Date:15/12/2025
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```
<html>
    <head>
    <meta charset="UFT-8">
    <meta name="viewport" content="width=device-width,initial-scale=1">
    <title>restaurent</title>
    <style>
        
                
                    
                   body {
                    margin: 0;
                    padding: 0;
                    display: flex;
                    justify-content: center;   /* centers the whole div */
                    height: 100vh;
                    background: #fff; 
                    background-image: url("c:/Users/acer/Downloads/gastwerk-hotel-hamburg_restaurant-mangold_interior_06.1760x1100.jpg")
                }
            
            
               
               .one {
                position: absolute;
                top: 20px;
                right: 600px;
                background: antiquewhite;
                padding: 20px;
                overflow: hidden;
                border-radius: 20%;
                font-style: italic;
                font-size: larger;
                text-decoration-color: black;
}



           
            
            
            .container {
                display: grid;
                grid-template-columns: repeat(4, 1fr);
                gap: 30px;
                width: 90%;
                margin: auto;
                padding: 20px;
                margin-top: 400px;
            }


        

       #food {

            width: 300px;                 /* div width */
            height: 450px;                /* div height */
            background-color: bisque;
            background-position: center;/* center image */
            background-repeat: no-repeat; /* do not repeat */
            border: 2px solid black;    /* optional */
            overflow: hidden;
            border-radius: 10%;
            top: 20px;
            
        }

        
        #food h1{
            position: relative;
            font-size: x-large;
            font-style: inherit;
            text-align: center;
            color: rgb(255, 255, 255);
        }
        #food p {
            position: relative;
            font-size: larger;
            color: black;
            font-style: normal;
            top: 10px;
            padding: 20px;
        
        
        }
    
        #food-img {
            display: block;
            margin: 20px auto;   /* centers image */
            width: 200px;        /* adjust size */
            height: 100px;
            border-radius: 10px; /* optional */
        }

       
    </style>
    </head>

    <body>
        


        <div class="container">
        
            <div id="food">
            <h1>biriyani</h1>
            <img src="c:\Users\acer\Downloads\Ambur-Chicken-Biriyani.jpg" width="100px" height="100px" id="food-img">
            <p >Biryani is a mixed rice dish originating in South Asia, traditionally made with rice, meat or seafood, vegetables, and spices. The dish is thought to derive from a combination of colourful and aromatic Persian pilau rice and Persian yoghurt-marinaded meat with spicy Indian styles of cooking rice.</p>
            
            
        </div>

        <div id="food">
            <h1>biriyani</h1>
            <img src="c:\Users\acer\Downloads\Ambur-Chicken-Biriyani.jpg" width="100px" height="100px" id="food-img">
            <p >Biryani is a mixed rice dish originating in South Asia, traditionally made with rice, meat or seafood, vegetables, and spices. The dish is thought to derive from a combination of colourful and aromatic Persian pilau rice and Persian yoghurt-marinaded meat with spicy Indian styles of cooking rice.</p>
            
            
        </div>

        <div id="food">
            <h1>biriyani</h1>
            <img src="c:\Users\acer\Downloads\Ambur-Chicken-Biriyani.jpg" width="100px" height="100px" id="food-img">
            <p >Biryani is a mixed rice dish originating in South Asia, traditionally made with rice, meat or seafood, vegetables, and spices. The dish is thought to derive from a combination of colourful and aromatic Persian pilau rice and Persian yoghurt-marinaded meat with spicy Indian styles of cooking rice.</p>
            
            
        </div>

        <div id="food">
            <h1>biriyani</h1>
            <img src="c:\Users\acer\Downloads\Ambur-Chicken-Biriyani.jpg" width="100px" height="100px" id="food-img">
            <p >Biryani is a mixed rice dish originating in South Asia, traditionally made with rice, meat or seafood, vegetables, and spices. The dish is thought to derive from a combination of colourful and aromatic Persian pilau rice and Persian yoghurt-marinaded meat with spicy Indian styles of cooking rice.</p>
            
            
        </div>

        <div id="food">
            <h1>biriyani</h1>
            <img src="c:\Users\acer\Downloads\Ambur-Chicken-Biriyani.jpg" width="100px" height="100px" id="food-img">
            <p >Biryani is a mixed rice dish originating in South Asia, traditionally made with rice, meat or seafood, vegetables, and spices. The dish is thought to derive from a combination of colourful and aromatic Persian pilau rice and Persian yoghurt-marinaded meat with spicy Indian styles of cooking rice.</p>
            
            
        </div>

        <div id="food">
            <h1>biriyani</h1>
            <img src="c:\Users\acer\Downloads\Ambur-Chicken-Biriyani.jpg" width="100px" height="100px" id="food-img">
            <p >Biryani is a mixed rice dish originating in South Asia, traditionally made with rice, meat or seafood, vegetables, and spices. The dish is thought to derive from a combination of colourful and aromatic Persian pilau rice and Persian yoghurt-marinaded meat with spicy Indian styles of cooking rice.</p>
            
            
        </div>

        <div id="food">
            <h1>biriyani</h1>
            <img src="c:\Users\acer\Downloads\Ambur-Chicken-Biriyani.jpg" width="100px" height="100px" id="food-img">
            <p >Biryani is a mixed rice dish originating in South Asia, traditionally made with rice, meat or seafood, vegetables, and spices. The dish is thought to derive from a combination of colourful and aromatic Persian pilau rice and Persian yoghurt-marinaded meat with spicy Indian styles of cooking rice.</p>
            
        </div>

        <div id="food">
            <h1>biriyani</h1>
            <img src="c:\Users\acer\Downloads\Ambur-Chicken-Biriyani.jpg" width="100px" height="100px" id="food-img">
            <p >Biryani is a mixed rice dish originating in South Asia, traditionally made with rice, meat or seafood, vegetables, and spices. The dish is thought to derive from a combination of colourful and aromatic Persian pilau rice and Persian yoghurt-marinaded meat with spicy Indian styles of cooking rice.</p>
            
        </div>
        

        </div>


        <div class="one">
            <h1>MEAT AND EAT</h1>
        </div>



    </body>

</html>
```
# OUTPUT:
<img width="1920" height="1080" alt="Screenshot 2025-12-15 084726" src="https://github.com/user-attachments/assets/0d170837-d895-4234-a1ee-f86657c6b5d7" />

<img width="1920" height="1080" alt="{1EC15BBC-CEBE-4C75-96AD-A3CB3D0C6622}" src="https://github.com/user-attachments/assets/4323cb22-c43e-4226-9df7-786836faf5e5" />

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
