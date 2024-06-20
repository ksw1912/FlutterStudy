<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flutter Study</title>
    <style>
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }
        .image-container {
            flex: 1;
            min-width: 45%;
            box-sizing: border-box;
            padding: 10px;
        }
        .image-container img {
            width: 100%;
            height: auto;
        }
    </style>
</head>
<body>
    <h1>Flutter study</h1>
    <hr>

    <div>
        <h3>2 week Shazam</h3>
        <div class="container">
            <div class="image-container">
                <p>1page</p>
                <img src="https://github.com/ksw1912/FlutterStudy/assets/150943603/d7824521-fe19-4c6d-8a80-c01f16cba71a" alt="1page">
            </div>
            <div class="image-container">
                <p>2page</p>
                <img src="https://github.com/ksw1912/FlutterStudy/assets/150943603/1b23bf31-b36d-4469-9235-09d235bf11a3" alt="2page">
            </div>
        </div>
        <div class="image-container">
            <p>3page</p>
            <img src="https://github.com/ksw1912/FlutterStudy/assets/150943603/3f7e6736-8fc5-41e2-9a9e-776e85b7e7d2" alt="3page" style="width: 400px; height: 400px;">
        </div>
    </div>
</body>
</html>
