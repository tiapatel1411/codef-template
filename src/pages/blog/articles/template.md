---
layout: "@layouts/ArticleLayout.astro"
title: Gallery
date: 30 June 2023
image: /images/...
imageDescription: 
draft: true
---
<!DOCTYPE html>
<html>
<head>
    <title>Gallery View</title>
    <style>
        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        
        .gallery-item {
            margin: 10px;
            width: 200px;
        }
        
        .gallery-item img {
            width: 100%;
            height: auto;
        }
    </style>
</head>
<body>
    <div class="gallery">
        <div class="gallery-item">
            <img src="/images/image1.jpg" alt="Image 1">
        </div>
        <div class="gallery-item">
            <img src="/images/image2.jpg" alt="Image 2">
        </div>
        <div class="gallery-item">
            <img src="/images/image3.jpg" alt="Image 3">
        </div>
        <div class="gallery-item">
            <img src="/images/image4.jpg" alt="Image 4">
        </div>
        <div class="gallery-item">
            <img src="/images/image5.jpg" alt="Image 4">
        </div>
        <div class="gallery-item">
            <img src="/images/image6.jpg" alt="Image 4">
        </div>
        <div class="gallery-item">
            <img src="/images/image7.jpg" alt="Image 4">
        </div>
        <div class="gallery-item">
            <img src="/images/image8.jpg" alt="Image 4">
        </div>
        <div class="gallery-item">
            <img src="/images/image9.jpg" alt="Image 4">
        </div>
        <div class="gallery-item">
            <img src="/images/image11.jpg" alt="Image 4">
        </div>
        <div class="gallery-item">
            <img src="/images/image12.jpg" alt="Image 4">
        </div>
    </div>
</body>
</html>


