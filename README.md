# Contact-Page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Page!</title>
    <style>
        body {
            font-family:Helvetica, sans-serif,Times new Roman, Nolo Sans;
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
            color: black;
            padding: 0.5em;
        }

        nav a {
            color: black;
            text-decoration: none;
            padding: 0.5em 1em;
            margin: 0 1em;
        }
        header {
            background-color: #ff3363;
            color: white;
            text-align: center;
            padding: 2em;
            width: 100%;
        }

        main {
            text-align: left; 
            padding: 2em;
            width: 100%; 
            box-sizing: border-box;
        }

        
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
            <a href="#">Home Page</a>
            <a href="#">About Us Page</a>
            <a href="#">Contact Page</a>
        </nav>
        <!--for this part ive added a placeholder image to be used for social media contact buttons later on-->

        <div class="image-container">
            <img src="image1.jpg" alt="Image 1">
           
        </div>
        <form>
          <!--the form box will go here below the header -->
          <!-- will also have javascript coding here once youv're submitted the button-->
        </form>
        <footer>
            Creative Minds.
        </footer>
    </main>

</body>
</html>
