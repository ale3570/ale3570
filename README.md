<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Social Hours - Horas Sociales</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f8ff; /* Light blue background */
            color: #000;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #ffffff; /* White background for header */
            padding: 20px;
            text-align: center;
            border-bottom: 2px solid #000;
        }
        header img {
            width: 100px;
        }
        h1 {
            color: #0056b3; /* Dark blue text */
        }
        .container {
            margin: 20px auto;
            padding: 20px;
            max-width: 800px;
            background-color: #ffffff;
            border-radius: 10px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
        }
        label {
            display: block;
            margin-bottom: 10px;
        }
        input[type="text"], input[type="number"], textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        input[type="submit"] {
            background-color: #0056b3;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        input[type="submit"]:hover {
            background-color: #003366;
        }
        a {
            color: #0056b3;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <header>
        <img src="LOGO-COLNAZARETH.png" alt="Logo de la Institución">
        <h1>Horas Sociales - Institución Educativa Técnica</h1>
        <p>Nuestra Señora de Nazareth, Chinavita, Boyacá</p>
    </header>

    <div class="container">
        <h2>Formulario de Servicio Social</h2>
        <form action="#" method="post">
            <label for="studentName">Nombre del Estudiante:</label>
            <input type="text" id="studentName" name="studentName" required>

            <label for="grade">Grado:</label>
            <input type="text" id="grade" name="grade" required>

            <label for="hours">Horas a cumplir:</label>
            <input type="number" id="hours" name="hours" required>

            <label for="projectName">Nombre del Proyecto:</label>
            <input type="text" id="projectName" name="projectName" required>

            <label for="justification">Justificación del Proyecto:</label>
            <textarea id="justification" name="justification" rows="4" required></textarea>

            <input type="submit" value="Enviar">
        </form>

        <h2>Sube los documentos</h2>
        <form action="#" method="post" enctype="multipart/form-data">
            <label for="document">Subir documentos en PDF:</label>
            <input type="file" id="document" name="document" accept=".pdf">
            <input type="submit" value="Subir">
        </form>

        <h2>Formatos descargables</h2>
        <p>Puedes descargar los siguientes formatos en blanco para rellenar:</p>
        <ul>
            <li><a href="HORAS%20SOCIALES%20.pdf" download>Descargar Formato de Carta de Intención</a></li>
            <li><a href="HORAS%20SOCIALES%20.pdf#page=2" download>Descargar Formato de Descripción de Proyecto</a></li>
            <li><a href="HORAS%20SOCIALES%20.pdf#page=3" download>Descargar Planilla de Control de Horas</a></li>
        </ul>
    </div>

</body>
</html>
