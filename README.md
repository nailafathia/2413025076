<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: #f5ffbf;
        }
        
        header {
            background: #fa83d2;
            color: #f5ffbf;
            padding: 20px;
            text-align: center;
        }
        
        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
        }
        
        .profile {
            text-align: center;
        }
        
        .profile img {
            width: 150px;
            border-radius: 50%;
        }
        
        .portfolio {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        
        .portfolio img {
            width: 300px;
            height: 200px;
            object-fit: cover;
            border-radius: 10px;
        }
        
        .contact {
            text-align: center;
            padding: 20px;
            background: #ddd;
        }
    </style>
</head>

<body>
    <header>
        <h1>My Portfolio</h1>
    </header>

    <div class="container">
        <section class="profile">
            <img src="gambar/Profile pict.jpg" alt="Profile Picture">
            <h2>Naila Fathia</h2>
            <p>Mahasiswa| Universitas Lampung | Pendidikan Teknologi Informasi</p>
        </section>

        <section class="portfolio">

        </section>
    </div>

    <section class="contact">
        <h2>Contact Me</h2>
        <p>Email: nailafathia123@gmail.com</p>
        <p>Phone: +62 878 9459 0492</p>
    </section>
</body>

</html>
