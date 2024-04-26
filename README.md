# Web-page-
link-for html page - https://1drv.ms/w/c/b35664573fa968ef/EVj-NU9ETENDvszV653kMGUB5-BVBCRodeTUSsLLMygiVg?e=qVjnC2

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>File Upload</title>
    <style>
        body {
            background-image: url('background.jpg');
            background-size: cover;
            background-repeat: no-repeat;
            font-family: Arial, sans-serif;
        }
        #upload-form {
            width: 50%;
            margin: 50px auto;
            padding: 20px;
            background: rgba(255, 255, 255, 0.8);
            border-radius: 10px;
        }
        input[type="file"] {
            margin-bottom: 10px;
        }
    </style>
</head>
<body>
    <div id="upload-form">
        <h2>Upload Files</h2>
        <form action="upload.php" method="post" enctype="multipart/form-data">
            <input type="file" name="video" accept="video/*" />
            <input type="file" name="image" accept="image/*" />
            <input type="submit" value="Upload" />
        </form>
    </div>
    <audio autoplay loop>
        <source src="background_music.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>
</body>
</html>

