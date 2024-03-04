# Contact-Page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Page</title>
    <style>
        body {
            font-family:Helvetica, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            display: flex;
            flex-direction: column;
            align-items: flex-start; 
            justify-content: center;
            min-height: 100vh;
        }
        nav {
            background-color: #33d1ff;
            color: white;
            padding: 0.5em;
        }

        nav a {
            color: white;
            text-decoration: none;
            padding: 0.5em 1em;
            margin: 0 1em;
        }
        header {
            background-color: #ff3363;
            color: white;
            text-align: center;
            padding: 1em;
            width: 100%;
        }

        main {
            text-align: left; 
            padding: 2em;
            width: 100%; 
            box-sizing: border-box;
        }

        form {
            display: flex;
            flex-direction: column;
            width: 100%;
            max-width: 400px; 
        }

        label {
            margin-bottom: 0.5em;
        }

        input, textarea {
            width: 100%;
            padding: 0.5em;
            margin-bottom: 1em;
            box-sizing: border-box;
        }

        button {
            padding: 1em 2em;
            font-size: 16px;
            background-color: #ff3363;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        button:hover {
            background-color: #ff3352;
        }
        .image-container {
            display: flex;
            justify-content: flex-end; 
        }

        img {
            max-width: 100%; 
            height: auto; 
            margin-left: 1em; 
        }

        footer{
            background-color: #ff3363;
            color: white;
            text-align: center;
            padding: 0.4em;
            position: absolute;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

    <header>
        <h1>Creative Minds</h1>
    </header>
<!--ive made a form to be used for the contact page.-->
    <main>
        <h1>Contact Us!</h1>
        <nav>
            <a href="#">Home</a>
            <a href="#">About</a>
            <a href="#">Contact</a>
        </nav>
        <!--for this part ive added a placeholder image to be used for social media contact buttons later on-->
        <div class="image-container">
            <img src="image1.jpg" alt="Image 1">
           
        </div>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="4" required></textarea>

            <button type="submit">Submit</button>
        </form>
        <footer>
            Creative Minds.
        </footer>
    </main>

</body>
</html>
