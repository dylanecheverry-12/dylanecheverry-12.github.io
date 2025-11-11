<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Mi Página de GitHub</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f4f8;
            color: #333;
        }
        header {
            background-color: #2d3e50;
            color: white;
            text-align: center;
            padding: 40px 0;
        }
        header h1 {
            margin: 0;
            font-size: 36px;
        }
        .container {
            padding: 40px;
            max-width: 1200px;
            margin: 0 auto;
        }
        .content {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 20px;
        }
        .card {
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }
        .card:hover {
            transform: translateY(-10px);
        }
        .card h2 {
            color: #2d3e50;
            margin-bottom: 10px;
        }
        .card p {
            font-size: 14px;
            color: #555;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #2d3e50;
