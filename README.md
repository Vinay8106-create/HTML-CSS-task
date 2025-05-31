<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>skew_task</title>
    <!-- <link rel="stylesheet" href="../../CSS/skew_task.css"> -->
    <style>
        nav{
    border: 1px solid black;
    text-align: center;
    word-spacing: 200px;
    line-height: 50px;
    /* padding: 20px; */
    background-color: black;
}
#main{
    background-image: url(https://cdn.pixabay.com/photo/2018/03/10/18/03/laptop-3214756_640.png);
    height: 100vh;
    margin: 0 auto;
}
#sec{
    border: 1px solid beige;
    background-color:beige;
    height: 110vh;
}
a{
    text-decoration: none;
    color: white;
}
#content1{
    border: 0px solid black;
   font-family: 'Times New Roman', Times, serif;
    background-color: white;
    height: 200px;
    width: 500px;
    transform: translatex(350px);
    margin-top: 120px;
    margin-left: 200px;
    padding: 10px;
    text-align: center;
    transform: skew(20deg);  
}
#content1:hover{
    background-color: yellow;
}
#content2{
    border: 0px solid black;
    background-color: white;
    font-family: 'Times New Roman', Times, serif;
    height: 200px ;
    width: 500px;
    transform: translatex(800px);
    margin-top: -220px;
    margin-left: 800px;
    padding: 10px;
    text-align: center;
    transform: skew(20deg);  
}
#content2:hover{
    background-color: yellow;
}
#content3{
    border: 0px solid black;
    background-color: white;
    font-family: 'Times New Roman', Times, serif;
    height: 200px;
    width: 500px;
    transform: translatex(500px);
    margin-top: 50px;
    margin-left: 500px;
    text-align: center;
    padding: 10px;
    transform: skew(20deg);  
}
#content3:hover{
    background-color: yellow;
}
#blog1{
    border: 0px solid black;
    background-color:white;
    border-radius: 10px;
    height: 630px;
    width: 450px;
    line-height: 30px;
    margin-left: 200px;
    margin-top: 100px;
    transition: 1s;
}
#blog2{
    border: 0px solid black;
    background-color:white;
    border-radius: 10px;
    line-height: 30px;
    height: 630px;
    width: 450px;
    margin-left: 800px;
    margin-top: -630px;
    transition: 1s;
}
h3{
    margin-left: 10px;
}
.conp{
    
    margin-left: 10px;
    
}
img{
    border: 0px solid black;
    border-radius: 10px;
    height: 300px;
    width: 450px;
}
#but{
    border-style: none;
    margin-left: 130px;
    padding: 10px;
    font-size: 25px;
    width: 200px;
    background-color: lightskyblue;
    color: white;
}
#blog1:hover{
    transform: scale(1.1,1.1);
    box-shadow: 10px 10px 20px 20px olivedrab;

}
#blog2:hover{
    transform: scale(1.1,1.1);
    box-shadow: 10px 10px 20px 20px olivedrab;

}
    </style>
</head>
<body>
    <main id="main">
    <div>
        <nav>
            <a href="#">Home</a>
            <a href="##">Content</a>
            <a href="###">Policy</a>
            <a href="#">About</a>
            <a href="##">Register</a>
        </nav>
    </div>
    
    
    <div id="content1">
        <h2>Content1 </h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Error quidem ea quod dicta porro assumenda qui eligendi veniam voluptate id quia iure quasi molestiae doloribus voluptas, rerum placeat molestias tenetur?</p>
    </div>

    <div id="content2">
        <h2>Content2 </h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestiae quidem dolore laudantium maiores minus voluptates, labore ex suscipit? Fugiat corporis sapiente possimus! Enim, necessitatibus explicabo!</p>
    </div>
    <div id="content3">
        <h2>Content3 </h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolor architecto, nemo corporis iure atque cumque mollitia, officia nihil, commodi debitis quos neque fugit nostrum?</p>
    </div>
</main>
<br>
<main id="sec">
    <div id="blog1">
        <img src="https://cdn.pixabay.com/photo/2014/12/27/15/31/camera-581126_640.jpg" alt="image-1">
        <h3>Content</h3>
        <p class="conp">Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure in cupiditate voluptas ipsa aliquam quasi illo aut culpa impedit est? Lorem ipsum dolor sit, amet consectetur adipisicing elit. Vel,<br> neque aperiam nam deleniti voluptas aliquam.</p>
        <button id="but">Add to cart</button>

    </div>

    <div id="blog2">
        <img src="https://cdn.pixabay.com/photo/2014/07/31/23/00/wristwatch-407096_640.jpg" alt="image-2">
        <h3>Content</h3>
        <p class="conp">Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure in cupiditate voluptas ipsa aliquam quasi illo aut culpa impedit est? Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellendus officiis eius eos, aperiam expedita rem!</p>
        <button id="but">Add to cart</button>
    </div>
</main>
    
</body>
</html>
