<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Skeleton Video Loader</title>
    <style>
        .skeleton {
            width: 100px;
            height: 100px;
            background-color: #f0f0f0;
            animation: pulse 1s infinite alternate;
        }

        @keyframes pulse {
            0% {
                opacity: 1;
            }
            100% {
                opacity: 0.3;
            }
        }
    </style>
</head>
<body>
<!-- Video Section -->
<video width="320" height="240" controls>
    <source src="your_video.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>

<!-- Skeleton Loading Animation -->
<div class="skeleton"></div>
</body>
</html>
