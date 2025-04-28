# music-
Музыкалық аспаптар 
<!DOCTYPE html>

<html lang="kk">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Біз туралы - Музыкалық Аспаптар Дүкені</title>

    <style>

        * {

            margin: 0;

            padding: 0;

            box-sizing: border-box;

            font-family: Arial, sans-serif;

        }



        body {

            background-image: url('https://www.transparenttextures.com/patterns/arabesque.png'); /* Ою-өрнек фоны */

            background-size: cover;

            color: #333;

        }



        /* Header стилі */

        header {

            background-color: #0052cc; /* Көк түс */

            color: #ffd700; /* Алтын түс */

            padding: 1rem 2rem;

            display: flex;

            justify-content: space-between;

            align-items: center;

            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);

        }



        header h1 {

            font-size: 1.8rem;

        }



        nav a {

            color: #ffd700;

            text-decoration: none;

            margin-left: 1.5rem;

            font-weight: bold;

            transition: color 0.3s;

        }



        nav a:hover {

            color: #ffffff;

        }



        /* Біз туралы бөлімі */

        .about-section {

            background-color: #e6f3ff;

            padding: 2rem;

            text-align: center;

            border: 2px solid #ffd700;

            margin: 2rem 1rem;

            border-radius: 10px;

        }



        .about-section h2 {

            color: #0052cc;

            margin-bottom: 1rem;

        }



        .about-section p {

            max-width: 800px;

            margin: 0 auto;

            line-height: 1.6;

            margin-bottom: 1rem;

        }



        /* Шеберлер бөлімі */

        .masters-section {

            max-width: 1200px;

            margin: 2rem auto;

            padding: 0 1rem;

        }



        .masters-section h2 {

            text-align: center;

            color: #0052cc;

            margin-bottom: 2rem;

        }



        .masters {

            display: grid;

            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));

            gap: 1.5rem;

        }



        .master-card {

            background-color: white;

            border: 2px solid #ffd700;

            border-radius: 10px;

            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);

            overflow: hidden;

            transition: transform 0.3s;

            text-align: center;

        }



        .master-card:hover {

            transform: scale(1.05);

        }



        .master-card img {

            width: 100%;

            height: 200px;

            object-fit: cover;

        }



        .master-info {

            padding: 1rem;

        }



        .master-info h3 {

            font-size: 1.2rem;

            color: #0052cc;

            margin-bottom: 0.5rem;

        }



        .master-info p {

            color: #555;

            font-size: 0.9rem;

        }



        /* Footer стилі */

        footer {

            background-color: #0052cc;

            color: #ffd700;

            text-align: center;

            padding: 1rem;

            margin-top: 2rem;

        }



        /* Мобильді құрылғыларға бейімдеу */

        @media (max-width: 768px) {

            header {

                flex-direction: column;

                text-align: center;

            }



            nav {

                margin-top: 1rem;

            }



            nav a {

                margin: 0 0.5rem;

            }



            .masters {

                grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));

            }

        }

    </style>

</head>

<body>

    <header>

        <h1>Музыкалық Аспаптар Дүкені</h1>

        <nav>

            <a href="index.html">Басты бет</a>

            <a href="catalog.html">Каталог</a>

            <a href="about.html">Біз туралы</a>

            <a href="contact.html">Байланыс</a>

            <a href="services.html">Қызметтер</a>

        </nav>

    </header>



    <div class="about-section">

        <h2>Біз туралы</h2>

        <p>"Музыкалық Аспаптар Дүкені" – ұлттық және халықаралық музыкалық аспаптарды шығаруға және сатуға маманданған бірегей дүкен. Біздің миссиямыз – қазақтың дәстүрлі музыкасын сақтау және әлемдік музыкалық мәдениетті байыту. Біз домбыра, қобыз, сазсырнай, жетіген, шаңқобыз сияқты дәстүрлі қазақ аспаптарын, сондай-ақ гитара, скрипка, пианино сияқты заманауи аспаптарды ұсынамыз.</p>

        <p>Біздің тарихымыз 2010 жылы шағын шеберханадан басталды. Бүгінде біз жоғары сапалы аспаптарды жасаумен және сатумен айналысамыз, әрбір клиентке жеке көзқарас ұсынамыз. Біздің шеберлер – өз ісінің мамандары, олар әр аспапты қолмен және үлкен махаббатпен жасайды.</p>

    </div>



    <div class="masters-section">

        <h2>Біздің шеберлер</h2>

        <div class="masters">

            <div class="master-card">

                <img src="https://avatars.mds.yandex.net/i?id=cb7dae4a1ccf073bafa9bf2d0dd89f768e83902c-5315434-images-thumbs&n=13" alt="Жолаушы Турдығұлов">

                <div class="master-info">

                    <h3>Жолаушы Турдығұлов </h3>

                    <p>20 жылдық тәжірибесі бар домбыра және жетіген шебері.</p>

                </div>

            </div>

            <div class="master-card">

                <img src="https://el.kz/upload/storage_el/a9/a9b1cffeb2b88af1c99bacc595bfca86.jpg" alt="Қанат Қазақбаев">

                <div class="master-info">

                    <h3>Қанат Қазақбаев</h3>

                    <p>Қобыз және шаңқобыз жасауға маманданған шебер.</p>

                </div>

            </div>

            <div class="master-card">

                <img src="https://avatars.mds.yandex.net/i?id=ae2a0915f227762ad4a99b4c5f7a942767c8eaa4-5481636-images-thumbs&n=13" alt="Нұрлан Байжанов">

                <div class="master-info">

                    <h3>Нұрлан Байжанов</h3>

                    <p>Гитара және скрипка баптау бойынша сарапшы.</p>

                </div>

            </div>

        </div>

    </div>



    <footer>

        <p>Байланыс: +7 (777) 777-77-77 | musicstore.kz</p>

        <p>© 2025 Музыкалық Аспаптар Дүкені. Барлық құқықтар қорғалған.</p>

    </footer>



    <script>

        console.log("Біз туралы бетіне қош келд
      іңіз!");

    </script>

</body>

</html>
