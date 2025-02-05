# gowtham-personal-bucket-list-html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Bucket List</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <header>
        <h1>My Personal Bucket List</h1>
    </header>

    <main>
        <section>
            <h2>Things I Want to Do</h2>
            <ul class="bucket-list">
                <li><span class="icon">&#9733;</span> Travel to Japan</li>
                <li><span class="icon">&#10003;</span> Learn to Play the Guitar</li>
                <li><span class="icon">&#9733;</span> Go Skydiving</li>
                <li><span class="icon">&#10003;</span> Visit Paris</li>
                <li><span class="icon">&#9733;</span> Hike the Grand Canyon</li>
                <li><span class="icon">&#10003;</span> Write a Book</li>
            </ul>
        </section>
    </main>

    <footer>
        <p>Created by [Your Name] &copy; 2025</p>
    </footer>

</body>
</html>
Css
/* General Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    background-color: #f0f4f8;
    color: #333;
    line-height: 1.6;
}

header {
    background-color: #4CAF50;
    color: white;
    text-align: center;
    padding: 20px 0;
}

h1 {
    font-size: 2.5rem;
}

main {
    padding: 20px;
}

section h2 {
    font-size: 2rem;
    margin-bottom: 20px;
    color: #333;
}

.bucket-list {
    list-style-type: none;
    padding-left: 0;
}

.bucket-list li {
    font-size: 1.2rem;
    padding: 10px;
    background-color: #fff;
    border: 1px solid #ddd;
    margin-bottom: 10px;
    border-radius: 5px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    transition: background-color 0.3s ease;
}

.bucket-list li:hover {
    background-color: #f1f1f1;
}

.icon {
    margin-right: 10px;
    font-size: 1.5rem;
}

footer {
    text-align: center;
    background-color: #4CAF50;
    color: white;
    padding: 10px 0;
    position: absolute;
    bottom: 0;
    width: 100%;
}

@media screen and (max-width: 768px) {
    header h1 {
        font-size: 2rem;
    }

    main {
        padding: 10px;
    }

    section h2 {
        font-size: 1.5rem;
    }

    .bucket-list li {
        font-size: 1rem;
    }
}
