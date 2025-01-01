<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>📚 Must-Read Collection</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(to right, #f8f9fa, #e9ecef);
            color: #343a40;
            margin: 0;
            padding: 0;
        }
        header {
            text-align: center;
            padding: 2rem 0;
            background-color: #007bff;
            color: white;
            animation: pulse 3s infinite;
        }
        header h1 {
            font-size: 3rem;
            margin: 0;
            text-shadow: 0px 4px 6px rgba(0, 0, 0, 0.2);
        }
        header p {
            font-size: 1.2rem;
            margin-top: 1rem;
        }

        @keyframes pulse {
            0% { background-color: #0056b3; }
            50% { background-color: #007bff; }
            100% { background-color: #0056b3; }
        }

        .container {
            max-width: 800px;
            margin: 2rem auto;
            padding: 1rem;
            background: white;
            border-radius: 8px;
            box-shadow: 0px 4px 12px rgba(0, 0, 0, 0.1);
        }

        .book {
            display: flex;
            align-items: center;
            margin-bottom: 1.5rem;
            border-bottom: 1px solid #e9ecef;
            padding-bottom: 1rem;
        }

        .book:last-child {
            border-bottom: none;
        }

        .book img {
            width: 60px;
            height: 90px;
            object-fit: cover;
            border-radius: 4px;
            margin-right: 1rem;
        }

        .book-details {
            flex: 1;
        }

        .book-title {
            font-size: 1.2rem;
            font-weight: bold;
        }

        .book-author {
            color: #6c757d;
            font-size: 0.9rem;
        }

        footer {
            text-align: center;
            padding: 1rem;
            font-size: 0.9rem;
            color: #6c757d;
        }
    </style>
</head>
<body>

<header>
    <h1>📚 Must-Read Collection</h1>
    <p>Transform your world one book at a time! 🚀</p>
</header>

<div class="container">
    <div class="book">
        <img src="https://via.placeholder.com/60x90" alt="Just for Fun">
        <div class="book-details">
            <div class="book-title">Just for Fun: The Story of an Accidental Revolutionary</div>
            <div class="book-author">by Linus Torvalds</div>
        </div>
    </div>

    <div class="book">
        <img src="https://via.placeholder.com/60x90" alt="Digital Minimalism">
        <div class="book-details">
            <div class="book-title">Digital Minimalism</div>
            <div class="book-author">by Cal Newport</div>
        </div>
    </div>

    <div class="book">
        <img src="https://via.placeholder.com/60x90" alt="Irresistible">
        <div class="book-details">
            <div class="book-title">Irresistible: The Rise of Addictive Technology and the Business of Keeping Us Hooked</div>
            <div class="book-author">by Adam Alter</div>
        </div>
    </div>
</div>

<footer>
    Happy Reading! 🌟
</footer>

</body>
</html>
