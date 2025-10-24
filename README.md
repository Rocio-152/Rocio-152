<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Currículum de Rocio</title>
    <style>
        .fotos {
            display: flex;          
            gap: 10px;              
            flex-wrap: wrap;        
            justify-content: flex-start; 
        }       
        .fotos img {
            width: 150px;           
            height: 150px;         
            border-radius: 8px;    
            object-fit: cover;     
            display: block;        
        }
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            line-height: 1.6;
        }
        h1, h2 {
            color: #333;
        }
        ul {
            list-style: disc;
            margin-left: 20px;
        }
    </style>
</head>
<body>
    <h1>Hola, Soy Rocio!</h1>
    <h2>Mi currículum:</h2>
    <h2>Trayectoria:</h2>
    <ul>
        <li>Experiencia en concursos de programación.</li>
        <li>Medalla de bronce en Copa UCI 2024.</li>
        <li>Medalla de plata en Concurso Provincial de Matanzas, Cuba.</li>
        <li>Medalla de bronce en Concurso Nacional de Cuba.</li>
        <li>Estudiante de Ingeniería Informática en la Universidad de Matanzas, Cuba.</li>
    </ul>
    <h2>Conocimientos:</h2>
    <ul>
        <li>Programación Competitiva.</li>
    </ul>
    <h2>Lenguajes:</h2>
    <div class="fotos">
        <img src="foto1.jpg" alt="Lenguaje 1">
        <img src="foto2.jpg" alt="Lenguaje 2">
        <img src="foto3.jpg" alt="Lenguaje 3">
        <img src="foto4.jpg" alt="Lenguaje 4">
    </div>
</body>
</html>
