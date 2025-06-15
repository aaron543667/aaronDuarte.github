<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <title>Invitación a la Fiesta</title>
    <style>
        body {
            font-family: Arial, sans-serif;
             background-color: #f5e6d3;
            text-align: center;
            padding: 50px;
        }

        h1 {
            font-size: 3em;
            color: #d64550;
        }

        h2 {
            color: #333;
        }

        .details {
            margin: 20px auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            display: inline-block;
            box-shadow: 0 0 10px rgba(0,0,0,0.2);
            text-align: left;
        }

        ul {
            list-style: none;
            padding: 0;
        }

        li {
            margin: 10px 0;
        }

        .rsvp-button {
            margin-top: 20px;
            padding: 12px 25px;
            background-color: #d64550;
            color: white;
            border: none;
            border-radius: 5px;
            font-size: 1em;
            cursor: pointer;
        }

        .rsvp-button:hover {
            background-color: #a9333f;
        }
    </style>
</head>
<body>

    <h1>¡Estás Invitado!</h1>
    <h2>A la Fiesta de Cumpleaños de </h2>

    <div class="details">
        <p><strong>Detalles del evento:</strong></p>
        <ul>
            <li>📅 Fecha: Sábado, 20 de julio de 2025</li>
            <li>hora: 5:00 PM</li>
            <li> Lugar:....</li>
            <li> habrá comida, juegos, música y pastel</li>
        </ul>

        <button class="rsvp-button" onclick="alert('¡Gracias por confirmar tu asistencia! )">Confirmar Asistencia</button>
    </div>

</body>
</html>
