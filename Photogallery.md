<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Photo Gallery</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            background-color: #f4f4f4;
        }

        .gallery {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }

        .gallery img {
            width: 200px;
            height: 200px;
            object-fit: cover;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }

        .gallery img:hover {
            transform: scale(1.1);
        }
    </style>
</head>
<body>
    <div class="gallery">
        <img src="https://th.bing.com/th/id/R.2042a41c584462a59025b68baf5d52fc?rik=hg2jsoZicRLgWg&riu=http%3a%2f%2fwallpapercave.com%2fwp%2fhfPxyMp.jpg&ehk=Cb9Z5NZysJkn0dYO4A5weSDLhsdnZcq0jawlJoC5ldA%3d&risl=&pid=ImgRaw&r=0" alt="Photo 1">
        <img src="https://www.classicdriver.com/cdn-cgi/image/format=auto,fit=cover,width=821,height=440/sites/default/files/users/31114/cars_images/feed_806559/4145aa902c76bc0df1dc9dac9265d665.jpeg" alt="Photo 2">
        <img src="https://th.bing.com/th/id/OIP.S_OJ-PisH4bxzQzVzzzKtwHaEm?w=1640&h=1020&rs=1&pid=ImgDetMain" alt="Photo 3">
        <img src="https://th.bing.com/th/id/OIP.SFL07u4DvZAVhqMThGauqgHaEK?rs=1&pid=ImgDetMain" alt="Photo 4">
        <img src="https://th.bing.com/th/id/OIP.X66RdvrpbEwUmGcaryLTywHaDD?w=1700&h=700&rs=1&pid=ImgDetMain" alt="Photo 5">
        <img src="https://th.bing.com/th/id/OIP.yZ-fhxSCVRaDsrHNxoe-8gHaE4?rs=1&pid=ImgDetMain" alt="Photo 6">
    </div>
</body>
</html>



