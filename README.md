# CLASE-5-de-HTML-BOX-MODEL-
<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejemplo de Box Model</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            margin: 0;
        }

        .caja {
            width: 400px;
            padding: 20px;
            border: 3px dashed #007BFF;
            margin: 20px;
            background-color: #fff;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            border-radius: 10px;
            text-align: center;
        }

        .caja p {
            margin: 0;
            font-size: 16px;
        }

        .inline {
            display: inline;
            padding: 10px;
            border: 2px solid blue;
            margin: 5px;
        }

        .imagen {
            width: 300px;
            padding: 10px;
            border: 5px solid black;
            margin: 50px;
            box-sizing: border-box;
            display: block;
        }
    </style>
</head>

<body>
    <div class="caja">
        <h2> QUEEN</h2>
        <p>
            The Show Must Go On
        </p>
    </div>
</body>

<body>
    <div class="caja">
        <img src="C:\Users\LENOVO\Desktop\TAREAS\PROGRAMACION WEB\LASIN HTML\CLASE 1\queen-wordpress.webp"
            class="imagen">
    </div>
</body>

<body>
    <div class="inline">
        <p>
            Queen es una banda británica de rock formada en 1970 en Londres, integrada originalmente por el cantante y
            pianista Freddie Mercury, el guitarrista Brian May, el baterista Roger Taylor y el bajista John Deacon (el
            cual llegaría un año después al grupo para completar la formación clásica). Sus primeros trabajos estuvieron
            influenciados por el rock progresivo y el hard rock, pero la banda se aventuró gradualmente en trabajos más
            convencionales y amigables con la radio, incorporando más estilos como el arena rock y el pop rock.
        </p>
    </div>
</body>
</html>
