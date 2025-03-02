# Tworzenie prostego szablonu strony w HTML + CSS



html_content = """<!DOCTYPE html>

<html lang="pl">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>KupaMC - Serwer Minecraft</title>

    <link rel="stylesheet" href="style.css">

</head>

<body>

    <header>

        <h1>Witaj na serwerze KupaMC!</h1>

        <p>Najlepszy serwer Minecraft - dołącz już teraz!</p>

    </header>



    <section>

        <h2>📌 Informacje o serwerze</h2>

        <p><strong>IP serwera:</strong> <span class="highlight">kupamc.aternos.me</span></p>

        <p><strong>Tryby gry:</strong> Survival, Minigames</p>

        <p><strong>Wersja:</strong> Najnowsza</p>

    </section>



    <section>

        <h2>💬 Dołącz do społeczności</h2>

        <p>Chcesz pogadać z innymi graczami? Dołącz na nasz <a href="https://discord.gg/ETPSX8Qw" target="_blank">Discord</a>!</p>

    </section>



    <footer>

        <p>&copy; 2025 KupaMC - Wszelkie prawa zastrzeżone.</p>

    </footer>

</body>

</html>

"""



css_content = """body {

    font-family: Arial, sans-serif;

    text-align: center;

    background-color: #282c34;

    color: white;

    margin: 0;

    padding: 0;

}



header {

    background-color: #4CAF50;

    padding: 20px;

    font-size: 24px;

}



section {

    margin: 20px;

    padding: 15px;

    background-color: #3b3f47;

    border-radius: 10px;

}



.highlight {

    color: #ffcc00;

    font-weight: bold;

}



a {

    color: #ffcc00;

    text-decoration: none;

}



a:hover {

    text-decoration: underline;

}



footer {

    margin-top: 20px;

    padding: 10px;

    background-color: #222;

}

"""



# Zapisanie plików

html_path = "/mnt/data/index.html"

css_path = "/mnt/data/style.css"



with open(html_path, "w", encoding="utf-8") as html_file:

    html_file.write(html_content)



with open(css_path, "w", encoding="utf-8") as css_file:

    css_file.write(css_content)



# Zwracamy linki do pobrania

html_path, css_path
# Tworzenie prostego szablonu strony w HTML + CSS



html_content = """<!DOCTYPE html>

<html lang="pl">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>KupaMC - Serwer Minecraft</title>

    <link rel="stylesheet" href="style.css">

</head>

<body>

    <header>

        <h1>Witaj na serwerze KupaMC!</h1>

        <p>Najlepszy serwer Minecraft - dołącz już teraz!</p>

    </header>



    <section>

        <h2>📌 Informacje o serwerze</h2>

        <p><strong>IP serwera:</strong> <span class="highlight">kupamc.aternos.me</span></p>

        <p><strong>Tryby gry:</strong> Survival, Minigames</p>

        <p><strong>Wersja:</strong> Najnowsza</p>

    </section>



    <section>

        <h2>💬 Dołącz do społeczności</h2>

        <p>Chcesz pogadać z innymi graczami? Dołącz na nasz <a href="https://discord.gg/ETPSX8Qw" target="_blank">Discord</a>!</p>

    </section>



    <footer>

        <p>&copy; 2025 KupaMC - Wszelkie prawa zastrzeżone.</p>

    </footer>

</body>

</html>

"""



css_content = """body {

    font-family: Arial, sans-serif;

    text-align: center;

    background-color: #282c34;

    color: white;

    margin: 0;

    padding: 0;

}



header {

    background-color: #4CAF50;

    padding: 20px;

    font-size: 24px;

}



section {

    margin: 20px;

    padding: 15px;

    background-color: #3b3f47;

    border-radius: 10px;

}



.highlight {

    color: #ffcc00;

    font-weight: bold;

}



a {

    color: #ffcc00;

    text-decoration: none;

}



a:hover {

    text-decoration: underline;

}



footer {

    margin-top: 20px;

    padding: 10px;

    background-color: #222;

}

"""



# Zapisanie plików

html_path = "/mnt/data/index.html"

css_path = "/mnt/data/style.css"



with open(html_path, "w", encoding="utf-8") as html_file:

    html_file.write(html_content)



with open(css_path, "w", encoding="utf-8") as css_file:

    css_file.write(css_content)



# Zwracamy linki do pobrania

html_path, css_path
