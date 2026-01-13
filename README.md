<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FC•27 ♟️ Dashboard</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #ffffff;  /* Blanco armonizado */
            margin: 0;
            padding: 0;
            color: #1a1a1a;
        }
        header {
            background-color: #ffffff;
            text-align: center;
            padding: 20px 10px 0px 10px;
            position: sticky;
            top: 0;
            z-index: 100;
            border-bottom: 1px solid #ddd;
        }
        header h1 {
            margin: 0;
            font-size: 2.2em;
            font-weight: bold;
            color: #a71d31;
        }
        header h2 {
            margin-top: 5px;
            font-size: 1em;
            font-weight: normal;
            color: #999;
        }
        .container {
            max-width: 800px;
            margin: 40px auto;
            padding: 0 20px;
        }
        .card {
            background-color: #f8f8f8;
            border-radius: 10px;
            padding: 20px;
            margin-bottom: 20px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.06);
        }
        .card h3 {
            margin: 0 0 10px 0;
            font-size: 1.1em;
            color: #333;
        }
        .bar-container {
            background-color: #ddd;
            border-radius: 20px;
            overflow: hidden;
            height: 25px;
        }
        .bar {
            height: 100%;
            background: linear-gradient(90deg, #FFD700, #DAA520, #B8860B); /* dorado metálico */
            text-align: right;
            padding-right: 10px;
            color: #fff;
            line-height: 25px;
            font-weight: bold;
        }
        footer {
            text-align: center;
            font-size: 0.85em;
            color: #777;
            margin-top: 50px;
            padding-bottom: 30px;
        }
    </style>
</head>
<body>
    <header>
        <h1>FC•27 ♟️</h1>
        <h2>Dashboard</h2>
    </header>

    <div class="container">
        <div class="card">
            <h3>Comités conformados</h3>
            <p><strong>48</strong> comités en total</p>
        </div>

        <div class="card">
            <h3>Asambleas celebradas</h3>
            <p>48 de 53 secciones</p>
            <div class="bar-container">
                <div class="bar" style="width: 91%;">91%</div>
            </div>
        </div>

        <div class="card">
            <h3>Asambleas ganadas</h3>
            <p><strong>36</strong></p>
        </div>

        <div class="card">
            <h3>Comités perdidos</h3>
            <p><strong>12</strong></p>
        </div>

        <div class="card">
            <h3>Participación al corte</h3>
            <p>36 de 48 asambleas</p>
            <div class="bar-container">
                <div class="bar" style="width: 75%;">75%</div>
            </div>
        </div>

        <div class="card">
            <h3>Participación general</h3>
            <div class="bar-container">
                <div class="bar" style="width: 68%;">68%</div>
            </div>
        </div>

        <div class="card">
            <h3>Registros aportados a la campaña “Súmate, somos millones”</h3>
            <p><strong>2,857</strong> registros</p>
        </div>
    </div>

    <footer>
        Luis Alberto Ramón • 2026 &reg;<br>
        Última actualización: 12 de january de 2026
    </footer>
</body>
</html>
