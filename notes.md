#notes


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- LINKS -->
    <!-- <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css">

    <link rel="stylesheet" href="style.css">

    <title>Document</title>
</head>
<body>
    
    <header>
        <div class="container">
            <div class="nav">
                <h2> <i class="fa-brands fa-unsplash"></i> Unsplash</h2>
                <div class="search-box">
                    <input type="text" id="input" placeholder="Search..."> <i onclick="loadImg()" class="fa-solid fa-magnifying-glass"></i>
                </div>
            </div>
        </div>
    </header>


<div class="container">
    <div class="grid">

    </div>
</div>

<script src="index.js"></script>
</body>
</html> 













/* @import url('https://fonts.googleapis.com/css2?family=Gamja+Flower&family=Poppins&display=swap');
*{
    padding:0;
    margin:0;
}

body{
    font-family: 'Poppins', sans-serif;
    background-color:black;
    color: white;
}

header{
    border-bottom:5px solid yellowgreen;
}

.container{
    width:95%;
    margin: auto;
}

.nav{
    display:flex;
    justify-content:space-between;
    flex-wrap: wrap;
    padding:25px;
}

.nav h2{
    font-size:2rem;
}

.nav h2 i{
    color: yellowgreen;
}

.search-box{
    position: relative;
    width:350px;
}

.search-box input{
    box-sizing: border-box;
    width: 100%;
    font-size: 1rem;
    padding:8px;
    border-radius: 25px;
    outline: none;
}

input{
    box-shadow:0 0 5px yellowgreen;
    border:1px solid yellowgreen;
}

.search-box i{
    color:rgb(63, 61, 61);
    position:absolute;
    top:25%;
    right:4%;
    transition:.5s;

}

.search-box i:hover{
    color:yellowgreen;
    
}

.grid{
    width:100%;
    display:flex;
    flex-wrap: wrap;
    justify-content:space-evenly;
    align-items: flex-start;
}

.img{
    width: 380px;
    height: 200px;
    margin-top: 15px;
    background-position: 50% 50%;
    background-size: cover;
    border-radius: 2px;
}

@media(max-width:768px){
    .img{
        width:100%;
    }

    .nav{
        justify-content: center;
    }
    .nav h2{
        padding: 5px 0;
    }
}

@media (max-width: 480px){
    .nav h2{
        text-align: center;
        font-size:rem;
    }

    .search-box{
        width:80%;
        margin:auto;
    }
} */





// const input = document.getElementById('input');
// const grid = document.getElementsByClassName('grid')[0];

// window.addEventListener('load',dayNightMode)

// input.addEventListener('keydown', function (event) {
//     if (event.key === 'enter')
//         loadImg();
// })

// function loadImg() {
//     removeImages();

//     const url = 'https://api.unsplash.com/search/photos?query=' + input.value + '&per_page=9&client_id=6H9w37lzD4XXUcEwaas4n7Q_9kb3tvVmrQkWGA88K5E';

//     fetch(url)

//         .then(response => {
//             if (response.ok)
//                 return response.json();
//             else
//                 alert(response.status)
//         })

//         .then(data =>{
//             const imageNodes =[];
//             for(let  i = 0; i < data.results.length; i++){
//                 imageNodes[i] = document.createElement('div');
//                 imageNodes[i].class ='img';
//                 imageNodes[i].style.backgroundImage ='url('+data.results[i].urls.raw+')';
//                 imageNodes[i].addEventListener("dblclick", function(){
//                     window.open(data.results[i].links.download, '_blank');

//             })

//             grid.appendChild(imageNodes[i]);
//         }      
    
// })
// }

// function removeImages() {
//     grid.innerHTML = '';
// }


// Day Night Mode

// function dayNightMode() {
//     const date = new Date();
//     const hour = date.getHours();

//     if (hour >= 7 && hour <= 19) {
//         document.body.style.backgroundColor = 'whitesmoke';
//         document.body.style.color = 'black';
//     } else {
//         document.body.style.backgroundColor = 'black';
//         document.body.style.color = 'whitesmoke';
//     }
// }

















