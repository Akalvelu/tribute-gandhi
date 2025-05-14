# tribute-gandhi
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mahatma Gandhi Tribute</title>
    <link rel="stylesheet" href="style.css">
    <style>
        body {
            background-color: rgb(245, 240, 243); /* You can change this to any color you prefer */
            font-family: Arial, sans-serif; /* Added a default font for better readability */
        }

        #main {
            width: 80%; /* Set the width of the main content */
            margin: 0 auto; /* Centers the content horizontally */
            background-color: white; /* Background color for content area */
            padding: 20px; /* Space inside the border */
            border: 5px solid #000000; /* Black square border */
            border-radius: 10px; /* Rounded corners for a softer look (optional) */
        }

        .img-resize {
            width: 250px; /* Set width of the image */
            height: auto; /* Maintains the aspect ratio */
        }

        h1 {
            color: #2c3e50; /* Set a color for the title */
        }

        #img-div {
            margin: 20px 0;
        }

        #img-caption {
            font-size: 14px;
            color: #7f8c8d; /* Set a lighter color for the caption */
            text-align: center;
            margin-top: 10px;
        }

        /* Styling for the timeline tables */
        .table-container {
            margin-top: 20px;
            padding: 20px;
            background-color: #f4f4f4;
            border-radius: 8px;
        }

        .timeline-table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }

        .timeline-table th,
        .timeline-table td {
            padding: 10px;
            border: 1px solid #ddd;
            text-align: left;
        }

        .timeline-table th {
            background-color: #2c3e50;
            color: white;
        }

        .table-container h2 {
            color: #2c3e50;
            text-align: center;
        }

        p {
            text-align: center;
            font-size: 16px;
        }

        a {
            text-decoration: none;
            color: #2980b9;
        }

        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

<main id="main">
    <center>
        <h1 id="title">Mahatma Gandhi</h1>
    </center>

    <figure id="img-div">
        <center>
            <img id="image" class="img-resize" src="https://media.licdn.com/dms/image/v2/D4D12AQGhTsFGDiN3Bw/article-cover_image-shrink_720_1280/article-cover_image-shrink_720_1280/0/1696078236848?e=2147483647&v=beta&t=_6Z0AIciGJ_iO8z0X_Ay9jYsQMPA6QpBxxqyyXvvomw" alt="Mahatma Gandhi">
        </center>
        <figcaption id="img-caption">Mahatma Gandhi, a prominent figure in India's independence movement...</figcaption>
    </figure>
<p>Mahatma Gandhi, a prominent figure in India's independence movement, was a lawyer, politician, and social activist who championed non-violence and truth. He is widely known as the "Father of the Nation" in India for his role in leading the country to independence from British rule. Assuming leadership of the Indian National Congress in 1921, Gandhi led nationwide campaigns for easing poverty, expanding women's rights, building religious and ethnic amity, ending untouchability, and, above all, achieving swaraj or self-rule. Gandhi adopted the short dhoti woven with hand-spun yarn as a mark of identification with India's rural poor. He began to live in a self-sufficient residential community, to eat simple food, and undertake long fasts as a means of both introspection and political protest. Bringing anti-colonial nationalism to the common Indians, Gandhi led them in challenging the British-imposed salt tax with the 400 km (250 mi) Dandi Salt March in 1930.</p>
    <p>If you would like to read more about this check out <a id="tribute-link" href="https://www.codsoft.in/">codsoft entry</a>.</p>

    <div class="table-container general">
        <h2>General Timeline</h2>
        <table class="timeline-table">
            <tr>
                <th>Year</th>
                <th>Event</th>
            </tr>
            <tr>
                <td>1869</td>
                <td>Born on October 2 in Porbandar, India</td>
            </tr>
            <tr>
                <td>1894</td>
                <td>Founded Natal Indian Congress</td>
            </tr>
            <tr>
                <td>1913</td>
                <td>Led miners' march in Transvaal</td>
            </tr>
            <tr>
                <td>1915</td>
                <td>Returned to India; joined Indian National Congress</td>
            </tr>
            <tr>
                <td>1917</td>
                <td>Champaran Satyagraha</td>
            </tr>
            <tr>
                <td>1920–22</td>
                <td>Non-Cooperation Movement</td>
            </tr>
            <tr>
                <td>1948</td>
                <td>Assassinated on January 30</td>
            </tr>
        </table>
    </div>

    <div class="table-container highlight">
        <h2>Key Highlights</h2>
        <table class="timeline-table">
            <tr>
                <th>Year</th>
                <th>Highlight</th>
            </tr>
            <tr>
                <td>1893</td>
                <td>Faced racial discrimination in South Africa</td>
            </tr>
            <tr>
                <td>1932</td>
                <td>Protested Dalit electorates; signed Poona Pact</td>
            </tr>
            <tr>
                <td>1942</td>
                <td>Launched Quit India Movement</td>
            </tr>
            <tr>
                <td>1947</td>
                <td>India gained independence</td>
            </tr>
        </table>
    </div>
</main>

</body>
</html>
