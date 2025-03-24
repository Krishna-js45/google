
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Photo Gallery</title>
    <style>
        body {
            background: linear-gradient(to right, #555, #222);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .gallery {
            display: flex;
            gap: 20px;
        }
        .gallery img {
            width: 200px;
            height: 150px;
            object-fit: cover;
            border-radius: 10px;
            box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .gallery img:hover {
            transform: scale(1.1);
            box-shadow: 4px 4px 15px rgba(0, 0, 0, 0.5);
        }
    </style>
</head>
<body>
    <div class="gallery">
        <img src="1742818245773.png" alt="Image 1">
        <img src="1742818245785.png" alt="Image 2">
        <img src="1742818245796.png" alt="Image 3">
        <img src="1742818245806.png" alt="Image 4">
    </div>
</body>
</html>
