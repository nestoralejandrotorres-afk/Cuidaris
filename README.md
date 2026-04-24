<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CUIDARIS</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<style>
body {
    margin: 0;
    font-family: 'Poppins', sans-serif;
    background: #f7fbfb;
    color: #333;
}

/* HEADER */
header {
    background: linear-gradient(135deg, #2a9d8f, #1d6f63);
    color: white;
    padding: 60px 20px;
    text-align: center;
}

header h1 {
    margin: 0;
    font-size: 40px;
}

header p {
    font-size: 18px;
    margin-top: 10px;
}

/* BOTON */
.btn {
    display: inline-block;
    margin-top: 20px;
    background: #e76f51;
    color: white;
    padding: 12px 20px;
    border-radius: 8px;
    text-decoration: none;
    font-weight: bold;
}

/* SECCIONES */
section {
    padding: 50px 20px;
    max-width: 1000px;
    margin: auto;
}

h2 {
    text-align: center;
    color: #2a9d8f;
}

/* SERVICIOS */
.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 20px;
    margin-top: 30px;
}

.card {
    background: white;
    padding: 20px;
    border-radius: 12px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.05);
    text-align: center;
}

/* FOOTER */
footer {
    background: #264653;
    color: white;
    text-align: center;
    padding: 30px;
}

/* WHATSAPP FLOAT */
.whatsapp {
    position: fixed;
    bottom: 20px;
    right: 20px;
    background: #25D366;
    color: white;
    padding: 15px;
    border-radius: 50%;
    font-size: 20px;
    text-decoration: none;
}
</style>

</head>

<body>

<header>
    <h1>CUIDARIS</h1>
    <p>Cuidado y acompañamiento en Tunja y Boyacá</p>
    <a class="btn" href="https://wa.me/573143118410">Contactar ahora</a>
</header>

<section>
    <h2>¿Qué ofrecemos?</h2>
    <p style="text-align:center;">
        Brindamos apoyo confiable a personas que necesitan ayuda en diligencias médicas,
        compra de medicamentos y acompañamiento a adultos mayores.
    </p>
</section>

<section>
    <h2>Servicios</h2>
    <div class="grid">
        <div class="card">Acompañamiento a citas médicas</div>
        <div class="card">Compra de medicamentos</div>
        <div class="card">Diligencias personales</div>
        <div class="card">Apoyo a adultos mayores</div>
        <div class="card">Trámites en EPS</div>
        <div class="card">Cuidado por horas</div>
    </div>
</section>

<section>
    <h2>Cobertura</h2>
    <p style="text-align:center;">
        Tunja, alrededores y todo el departamento de Boyacá
    </p>
</section>

<footer>
    <h2>Contáctanos</h2>
    <p>📞 314 311 8410</p>
    <p>CUIDARIS - Cuidado que acompaña</p>
</footer>

<a class="whatsapp" href="https://wa.me/573143118410">💬</a>

</body>
</html>
