<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mailänderli Recipe</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #318b29;
            color: rgb(13, 66, 15);
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #2d7027;
            color: rgb(144, 221, 148);
            padding: 1rem 0;
            text-align: center;
        }

        section {
            padding: 2rem;
        }

        footer {
            background-color: #1d5518;
            color: rgb(144, 221, 148);
            text-align: center;
            padding: 1rem 0;
        }

        .recipe-step img {
            width: 50%;
            height: auto;
        }

        .download{
            background-color: #2d7027;
            color: rgb(144, 221, 148)
        }
        .download-button-btn{
            background-color: #1c4b18;
            color: rgb(144, 221, 148);
        }
        
    </style>
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Mailänderli Recipe</h1>
        <p>A recipe with pictures</p>
    </header>

    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">Cookies</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#steps">Steps</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#download">Download</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#impressum">Impressum</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Recipe Steps Section -->
    <section id="steps">
        <div class="container">
            <h2 class="text-center">Recipe Steps</h2>
            <div class="row">
                <div class="col-md-6 recipe-step">
                    <h5>Step 1</h5>
                    <p>First mix butter until its soft.</p>
                    <img src="01_RepetitionHTML_KW50/Pictures/MixingButter.jpg" alt="Mixed Butter in a Plastic Bowl">
                </div>
                <div class="col-md-6 recipe-step">
                    <h5>Step 2</h5>
                    <p>Next add a grain of salt and 225 grams of sugar.</p>
                    <img src="01_RepetitionHTML_KW50/Pictures/AddSugar.jpg" alt="Step 2 Photo">
                </div>
                <div class="col-md-6 recipe-step">
                    <h5>Step 3</h5>
                    <p>Next add one after another egg and mix until the mass turns yellow.</p>
                </div>
                <div class="col-md-6 recipe-step">
                    <h5>Step 4</h5>
                    <p>Now add the zest of one lemon and mix with the rest.</p>
                    <img src="01_RepetitionHTML_KW50/Pictures/LemonZest.jpg" alt="Step 4 Photo">
                </div>
                <div class="col-md-6 recipe-step">
                    <h5>Step 5</h5>
                    <p>Then mix in the flour until it starts to clump together.</p>
                    <img src="01_RepetitionHTML_KW50/Pictures/Flour.jpg" alt="Step 5 Photo">
                </div>
                <div class="col-md-6 recipe-step">
                    <h5>Step 6</h5>
                    <p>After that put the dough in the Refrigerator for around 2 Hours.</p>
                    <img src="01_RepetitionHTML_KW50/Pictures/Refrigerator.jpg" alt="Step 6 Photo">
                </div>
                <div class="col-md-6 recipe-step">
                    <h5>Step 7</h5>
                    <p>Preheat the Oven to around 200 Degres Celcius.</p>
                    <img src="01_RepetitionHTML_KW50/Pictures/PreHeatTheOven.jpg" alt="Step 7 Photo">
                </div>
                <div class="col-md-6 recipe-step">
                    <h5>Step 8</h5>
                    <p>Now sprinkle a surface with flour and roll out the dough to a thickness of about 7 mm.</p>
                </div>
                <div class="col-md-6 recipe-step">
                    <h5>Step 9</h5>
                    <p>Now cut out the cookies.</p>
                    <img src="01_RepetitionHTML_KW50/Pictures/MakeForms.jpg" alt="Step 8 Photo">
                </div>
                <div class="col-md-6 recipe-step">
                    <h5>Step 10</h5>
                    <p>After that make the icing. For that mix one egg yellow with 1 teaspoon of milk.</p>
                    <img src="01_RepetitionHTML_KW50/Pictures/Milk.jpg" alt="Step 8 Photo">
                </div>
                <div class="col-md-6 recipe-step">
                    <h5>Step 12</h5>
                    <p>Then place the cutout cookies on a baking tray, brush them with the icing and place them in the preheated oven.
                       Leave them in there for around 10 minutes.</p>
                    <img src="01_RepetitionHTML_KW50/Pictures/PutThemOnAMetal.jpg" alt="Step 8 Photo">
                </div>
                <div class="col-md-6 recipe-step">
                    <h5>Step 13</h5>
                    <p>After that they are finished.</p>
                    <img src="01_RepetitionHTML_KW50/Pictures/FinishedCookies.jpg" alt="Step 8 Photo">
                </div>
            </div>
        </div>
    </section>

    <!-- Download Section -->
    <section id="download" class="download">
        <div class="download">
            <h2 class="text-center">Download the Recipe</h2>
            <p class="text-center">
                <a href="Mailaenderli.pdf" class="download-button-btn btn" download>Download PDF</a>
            </p>
        </div>
    </section>

    <!-- Impressum Section -->
    <section id="impressum" class="download">
        <div class="container">
            <h2 class="text-center">Impressum</h2>
            <p>
                <strong>Name: </strong>Mika End<br>
                <strong>Email: </strong>Mika.End@Outlook.com<br>
                <strong>Phone: </strong>+41 79 404 24 03<br>
            </p>
        </div>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 Mailänderli Baking Project.</p>
    </footer>
</body>
</html>
