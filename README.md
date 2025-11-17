<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Faith</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            background: url('https://scontent.fsgn8-3.fna.fbcdn.net/v/t39.30808-6/480607015_1179309273565045_16055116333067686_n.jpg?_nc_cat=106&ccb=1-7&_nc_sid=127cfc&_nc_ohc=D6i6GwsLqQcQ7kNvwGgmQ7j&_nc_oc=AdmJVhlHwBFttqfrbJeDMiUuuHMqRO-YCP7o7PWMZLHNI0eiMeqJZSUHqurzWN2XqGKjzEUcZeLzPAHha9clMB15&_nc_zt=23&_nc_ht=scontent.fsgn8-3.fna&_nc_gid=Yj8QeuSQu9GT163QM5LRxg&oh=00_AfjHOaNwr-EmKwcNX2Uz3NQBmtPM8Q8Up7IDE8u0AaLhcA&oe=691FE694') center top no-repeat;
            background-size: contain;
            background-attachment: fixed;
            background-color: black;  /* fills space if the image doesn't cover fully */
            color: #222;
        }

        header {
    background: rgba(0, 0, 0, 0.4); /* transparent black */
    color: white;
    padding: 20px;
    text-align: center;
    backdrop-filter: blur(5px); /* optional but makes it look clean */
        }

        nav {
            background: rgba(0, 0, 0, 0.3); /* transparent */
            display: flex;
            justify-content: center;
            padding: 10px 0;
            backdrop-filter: blur(5px); /* optional */
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .hero {
            background: url('https://via.placeholder.com/1600x500') center/cover no-repeat;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-shadow: 2px 2px 10px black;
            font-size: 2.5rem;
            font-weight: bold;
        }

        .content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            padding: 40px;
        }

        .card {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
        }

        footer {
            background: #111;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 30px;
        }
    </style>
</head>
<body>

    <header>
        <h1>My Faith</h1>
        <p>Lord Jesus, have mercy on me, a sinner.</p>
    </header>

    <nav>
        <a href="#">Jesus is King</a>

    </nav>

    <div class="hero">
        The parables of Jesus.
    </div>

    <section class="content">
        <div class="card">
            <h2>The Parable of the Sower</h2>
            <p>The Lord is the Sower - Matthew 13</p>
        </div>

        <div class="card">
            <h2>The Parable of the Lost Son</h2>
            <p>The Lord is The Father - Luke 15:11-32</p>
        </div>

        <div class="card">
            <h2>The Parable of The Good Samaritan</h2>
            <p>The Lord shown Mercy - Luke 10:25-37</p>
        </div>
    </section>

    <footer>
        <p>© 2025 My Faith — All Rights Reserved</p>
    </footer>

</body>
</html>
