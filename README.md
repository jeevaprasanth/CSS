<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <Style>
        body {
    background-image: linear-gradient(120deg, #a1c4fd 0%, #c2e9fb 100%);
    font-family: 'Courier New', Courier, monospace;
    text-align: center;
    padding: 20px;
    font-size: 20px;
    color: rgb(32, 6, 126);
    line-height: 1.6;
    border-radius: 10px;
    max-width: 500px;
    margin: 50px auto;
    transition: background-color 0.3s ease;
        }
       
        .card:hover {
    transform: scale(1.05);
    }
        img {
    width: 100%;
    max-width: 300px;
    margin: 20px 0;
    border: 2px solid #fff;
    box-shadow: 0 10px 5px rgba(0, 0, 0, 0.2);
    transition: transform 0.3s ease;
    object-fit: cover;
    border-radius: 10px;   
    box-shadow: 0 10px 5px rgba(0, 0, 0, 0.2);
}
button {
    background-image: linear-gradient( 109.6deg,  rgba(163,213,255,1) 11.3%, rgba(4,137,137,1) 86.7% );
    color: rgb(255, 255, 255);
    padding: 10px 20px;
    border: 1px solid rgb(0, 0, 0);
    border-radius: 50px;
    cursor: pointer;
    font-size: 16px;
}
</Style>
</head>
<body>
    <div class="card">
        <img src="jeeva.jpg" alt="">
    <h2>Jeevaprasanth</h2>
    <p>MERN developer</p>
    <button>Click Me</button>
    </div>
</body>
</html>
