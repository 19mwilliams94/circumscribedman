---
{"dg-publish":true,"permalink":"/05-gallery/"}
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>3 Columns with Infinite Rows</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            background-color: #f0f0f0;
        }
        .gallery-header {
            text-align: center;
            width: 90vw;
            max-width: 800px;
            margin-top: 20px; /* Add top margin to center on the page */
        }
        .gallery-header img {
            max-width: 100%;
            height: auto;
        }
        .content {
            width: 90vw;
            max-width: 800px;
            text-align: left;
            margin-top: 20px;
            margin-bottom: 20px;
        }
        .grid-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); /* Adjust as needed */
            gap: 2px; /* Set gap to 2px */
            width: 90vw; /* Adjust as needed */
            max-width: 800px;
        }
        .grid-item {
            aspect-ratio: 1; /* Maintain square aspect ratio */
            position: relative; /* For absolutely positioned img */
        }
        .grid-item a {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            display: block;
        }
        .grid-item img {
            width: 100%;
            height: 100%;
            object-fit: cover; /* Ensure the image covers the container */
            border-radius: 0; /* Remove border radius for clean edges */
        }

        @media only screen and (max-width: 768px) {
            .grid-container {
                width: 90vw; /* Adjust for smaller screens */
                grid-template-columns: repeat(auto-fit, minmax(120px, 1fr)); /* Adjust for smaller screens */
            }
        }
    </style>
</head>
<body>
    <div class="gallery-header">
        <h1>Gallery</h1>
        <h2>Silence of A Contemplative Life</h2>
        <img src="https://i.imgur.com/aBsK8GA_d.jpg?maxwidth=520&shape=thumb&fidelity=high" alt="Description of the image">
        <hr>
    </div>

    <div class="content">
        <!-- Space for a paragraph or two -->
        <p>I want to learn photography! But I rarely go outside to take photos so for now, I'll just share the images and paintings that interest me. I'll try to link them to its respective post so at least make this really boring of a website into a more engaging one, I think. They say a photograph paints a thousand word so that's a lot of words against my word count!</p>
        <p> Yep, this is peak braining.</p>
        <hr>
    </div>

    <div class="grid-container">
        <div class="grid-item"><a href="https://example.com/page1" target="_blank"><img src="https://i.imgur.com/zRzbKi4_d.jpg?maxwidth=520&shape=thumb&fidelity=high" alt="Image 1"></a></div>
        <div class="grid-item"><a href="https://example.com/page2" target="_blank"><img src="https://i.imgur.com/ErA2nl4_d.jpg?maxwidth=520&shape=thumb&fidelity=high" alt="Image 2"></a></div>
        <div class="grid-item"><a href="https://example.com/page3" target="_blank"><img src="https://i.imgur.com/ltrHco6_d.jpg?maxwidth=520&shape=thumb&fidelity=high" alt="Image 3"></a></div>
        <div class="grid-item"><a href="https://example.com/page4" target="_blank"><img src="https://i.imgur.com/hRarqLK_d.jpg?maxwidth=520&shape=thumb&fidelity=high" alt="Image 4"></a></div>
        <div class="grid-item"><a href="https://example.com/page5" target="_blank"><img src="https://i.imgur.com/mG7XUYU_d.jpg?maxwidth=520&shape=thumb&fidelity=high" alt="Image 5"></a></div>
        <div class="grid-item"><a href="https://example.com/page6" target="_blank"><img src="https://i.imgur.com/xbvIUUW_d.jpg?maxwidth=520&shape=thumb&fidelity=high" alt="Image 6"></a></div>
        <div class="grid-item"><a href="https://example.com/page7" target="_blank"><img src="https://i.imgur.com/mFyZ82V_d.jpg?maxwidth=520&shape=thumb&fidelity=high" alt="Image 7"></a></div>
        <div class="grid-item"><a href="https://example.com/page8" target="_blank"><img src="https://i.imgur.com/3V5zBjj_d.jpg?maxwidth=520&shape=thumb&fidelity=high" alt="Image 8"></a></div>
        <div class="grid-item"><a href="https://example.com/page9" target="_blank"><img src="https://i.imgur.com/E1Bacfe_d.jpg?maxwidth=520&shape=thumb&fidelity=high" alt="Image 9"></a></div>
        <div class="grid-item"><a href="https://example.com/page10" target="_blank"><img src="https://i.imgur.com/GJUcqac_d.jpg?maxwidth=520&shape=thumb&fidelity=high" alt="Image 10"></a></div>
        <div class="grid-item"><a href="https://example.com/page11" target="_blank"><img src="https://i.imgur.com/7TtKsLd_d.jpg?maxwidth=520&shape=thumb&fidelity=high" alt="Image 11"></a></div>
        <div class="grid-item"><a href="https://example.com/page12" target="_blank"><img src="https://i.imgur.com/QiFUhHq_d.jpg?maxwidth=520&shape=thumb&fidelity=high" alt="Image 12"></a></div>
        <div class="grid-item"><a href="https://example.com/page13" target="_blank"><img src="https://i.imgur.com/UqwPzKu_d.jpg?maxwidth=520&shape=thumb&fidelity=high" alt="Image 13"></a></div>
        <div class="grid-item"><a href="https://example.com/page14" target="_blank"><img src="https://i.imgur.com/Z0QaPo7_d.jpg?maxwidth=520&shape=thumb&fidelity=high" alt="Image 14"></a></div>
        <div class="grid-item"><a href="https://example.com/page15" target="_blank"><img src="https://i.imgur.com/2Py3Zb0_d.jpg?maxwidth=520&shape=thumb&fidelity=high" alt="Image 15"></a></div>
        <div class="grid-item"><a href="https://example.com/page16" target="_blank"><img src="https://i.imgur.com/Y6MB6GD_d.jpg?maxwidth=520&shape=thumb&fidelity=high" alt="Image 16"></a></div>
    </div>
</body>
</html>

