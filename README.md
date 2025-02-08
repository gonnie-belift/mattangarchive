# mattangarchive
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>카톡 아카이브</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 50px;
        }
        button {
            padding: 15px 30px;
            font-size: 20px;
            cursor: pointer;
        }
        #image-container {
            display: none;
            margin-top: 20px;
        }
        img {
            width: 100%;
            max-width: 500px;
            border-radius: 10px;
        }
    </style>
</head>
<body>
    <h1>카톡 아카이브</h1>
    <button onclick="showImage()">이미지 보기</button>

    <div id="image-container">
        <img src="이미지_파일_경로.jpg" alt="카톡 이미지">
    </div>

    <script>
        function showImage() {
            document.getElementById('image-container').style.display = 'block';
        }
    </script>
</body>
</html>
