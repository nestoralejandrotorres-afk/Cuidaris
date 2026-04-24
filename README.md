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

/* HERO */
.hero {
    background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)),
    url('https://images.unsplash.com/photo-1584515933487-779824d29309');
    background-size: cover;
    background-position: center;
    color: white;
    text-align: center;
    padding: 100px 20px;
}

.hero h1 {
    font-size: 45px;
    margin: 0;
}

.hero p {
    font-size: 20px;
}

.btn {
    display: inline-block;
    margin-top: 20px;
    background: #25D366;
    padding: 12px 20px;
    color: white;
    border-radius: 8px;
    text-decoration: none;
}

/* SECCIONES */
section {
    padding: 60px 20px;
    max-width: 1100px;
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
    box-shadow: 0 10px 20px rgba(0,0,0,0.05);
    text-align: center;
}

/* TESTIMONIOS */
.testimonio {
    background: white;
    padding: 20px;
    border-left: 5px solid #2a9d8f;
    margin-top: 20px;
}

/* FOOTER */
footer {
    background: #264653;
    color: white;
    text-align: center;
    padding: 30px;
}

/* WHATSAPP */
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

<div class="hero">
    <h1>CUIDARIS</h1>
    <p>Cuidado y acompañamiento en Tunja y Boyacá</p>
    <a class="btn" href="https://wa.me/573143118410">📲 Escríbenos ahora</a>
</div>

<section>
    <h2>¿Qué hacemos?</h2>
    <p style="text-align:center;">
        Ayudamos a personas y familias con diligencias médicas, compra de medicamentos 
        y acompañamiento a adultos mayores, brindando confianza, respeto y puntualidad.
    </p>
</section>

<section>
    <h2>Servicios</h2>
    <div class="grid">
        <div class="card">👨‍⚕️ Acompañamiento a citas médicas</div>
        <div class="card">💊 Compra de medicamentos</div>
        <div class="card">📄 Trámites en EPS</div>
        <div class="card">👴 Cuidado de adultos mayores</div>
        <div class="card">🛵 Diligencias personales</div>
        <div class="card">⏱️ Servicio por horas</div>
    </div>
</section>

<section>
    <h2>Por qué elegirnos</h2>
    <div class="testimonio">✔ Atención confiable y humana</div>
    <div class="testimonio">✔ Puntualidad y responsabilidad</div>
    <div class="testimonio">✔ Atención en Tunja y Boyacá</div>
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
