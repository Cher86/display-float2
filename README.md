# display-float2
Web development section 8. CSS Display &amp; Float
<!DOCTYPE html>
<html lang = "en">


<head>
    <meta charset="UTF-8">
  <title>CSS Float</title>

  <style>
    h1{
        background-color:burlywood;
        text-align: center;
        font-family:Georgia, 'Times New Roman', Times, serif;
        font-style: italic;
        color:white;
        font-size: 4em;

    }

    .cat{
        background-color: bisque;
        display:block;
        height:200px;
        width:fit-content
        padding:0px;
        margin:0px;
        border:0px;

    
    }

    .dog{
        background-color: beige;
        display:block;
        height:250px;

    }

    .cat>img{
        float:left;
        height:60%
    }

    .dog>img{
        float:right;
       

    }

    footer{
        clear: both;
        text-align: center;
        background-color: wheat;
        font-style: italic;
    }

    h2{
        text-align: center;
    }

    .bulldog{
       padding:3em;
       
    }

    .ginger{
        padding: 3em;
      
    }

    .pictures>img{
        display:inline-block;
        height: 20%; width:25%
    }

    .pictures{
        background-color:rgb(224, 209, 151);  
    }




  </style>
</head>

<body>
    <h1>What's cute about cats and dogs</h1>
<div class="cat" >
    <h2 class="cats-cuddle"> Cats are great cuddlers</h2>
    <img  src="cat.jpeg"/>
    
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Arcu bibendum at varius vel pharetra vel turpis nunc eget. Urna id volutpat lacus laoreet. Iaculis at erat pellentesque adipiscing commodo elit at. Sed ullamcorper morbi tincidunt ornare massa eget. Non tellus orci ac auctor. Turpis nunc eget lorem dolor sed viverra ipsum. Volutpat lacus laoreet non curabitur. Ornare massa eget egestas purus. Sapien et ligula ullamcorper malesuada proin libero nunc consequat. Ipsum a arcu cursus vitae congue mauris rhoncus. Quis varius quam quisque id. Elit ullamcorper dignissim cras tincidunt.</p>
</div>

<div class= "dog"> 
    <h2 class="best-firend">Dogs are a man's best friend</h2>
    <img  src="https://picsum.photos/id/237/200" alt=" cute dog"/>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Arcu bibendum at varius vel pharetra vel turpis nunc eget. Urna id volutpat lacus laoreet. Iaculis at erat pellentesque adipiscing commodo elit at. Sed ullamcorper morbi tincidunt ornare massa eget. Non tellus orci ac auctor. Turpis nunc eget lorem dolor sed viverra ipsum. Volutpat lacus laoreet non curabitur. Ornare massa eget egestas purus. Sapien et ligula ullamcorper malesuada proin libero nunc consequat. Ipsum a arcu cursus vitae congue mauris rhoncus. Quis varius quam quisque id. Elit ullamcorper dignissim cras tincidunt.</p>
</div>

<div class="pictures">
    <img class="bulldog" src="https://i.pinimg.com/736x/bf/79/c9/bf79c95971ab7ac8c38cd00cd52d33eb.jpg"/>
    <img  class= "kitten" src="https://d4.alternativeto.net/Lfh9gYkENELOXP3kNFXZU53fFQSv75UHym4LuxY1Qag/rs:fill:400:400:1/g:ce:0:0/YWJzOi8vZGlzdC9zLzhjNzljYjExLWZkOTctZTMxMS04OWNlLTAwMjU5MGEwNWY1Zl8yX2Z1bGwuanBn.jpg"/>
    <img  class= "ginger" src="https://placekitten.com/640/360"/>
</div>



<footer>Copyright CCrichlow 2023</footer>

</body>
</html>
