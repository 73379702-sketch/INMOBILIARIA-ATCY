<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>LimaHome Inmobiliaria</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body{
      margin:0;
      font-family: Arial, sans-serif;
      background:#f4f6f8;
      color:#333;
    }
    header{
      background:#0a3d62;
      color:#fff;
      padding:15px 30px;
      display:flex;
      justify-content:space-between;
      align-items:center;
    }
    header h1{
      margin:0;
      font-size:24px;
    }
    nav a{
      color:#fff;
      text-decoration:none;
      margin:0 10px;
      font-weight:bold;
    }
    nav a:hover{
      text-decoration:underline;
    }
    .hero{
      background:url("https://images.unsplash.com/photo-1560185127-6ed189bf02f4") center/cover no-repeat;
      height:400px;
      display:flex;
      align-items:center;
      justify-content:center;
      color:#fff;
      text-align:center;
    }
    .hero h2{
      font-size:36px;
      background:rgba(0,0,0,0.6);
      padding:15px 25px;
      border-radius:8px;
    }
    section{
      padding:40px 30px;
    }
    .section-title{
      text-align:center;
      margin-bottom:30px;
      color:#0a3d62;
    }
    .cards{
      display:grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap:20px;
    }
    .card{
      background:#fff;
      border-radius:10px;
      box-shadow:0 4px 8px rgba(0,0,0,0.1);
      overflow:hidden;
    }
    .card img{
      width:100%;
      height:180px;
      object-fit:cover;
    }
    .card-body{
      padding:15px;
    }
    .card-body h3{
      margin:0 0 10px;
      color:#0a3d62;
    }
    .card-body p{
      font-size:14px;
    }
    .btn{
      display:inline-block;
      background:#0a3d62;
      color:#fff;
      padding:10px 15px;
      border-radius:5px;
      text-decoration:none;
      margin-top:10px;
    }
    .btn:hover{
      background:#07406b;
    }
    .contact-form{
      max-width:500px;
      margin:0 auto;
      background:#fff;
      padding:25px;
      border-radius:10px;
      box-shadow:0 4px 8px rgba(0,0,0,0.1);
    }
    .contact-form input,
    .contact-form textarea{
      width:100%;
      padding:10px;
      margin:10px 0;
      border-radius:5px;
      border:1px solid #ccc;
    }
    footer{
      background:#0a3d62;
      color:#fff;
      text-align:center;
      padding:15px;
    }
  </style>
</head>
<body>

<header>
  <h1>LimaHome Inmobiliaria</h1>
  <nav>
    <a href="#inicio">Inicio</a>
    <a href="#departamentos">Departamentos</a>
    <a href="#nosotros">Nosotros</a>
    <a href="#contacto">Contacto</a>
  </nav>
</header>

<div class="hero" id="inicio">
  <h2>Tu nuevo departamento en Lima te espera</h2>
</div>

<section id="departamentos">
  <h2 class="section-title">Departamentos en Venta</h2>
  <div class="cards">
    <div class="card">
      <img src="https://images.unsplash.com/photo-1568605114967-8130f3a36994" alt="Departamento Miraflores">
      <div class="card-body">
        <h3>Miraflores</h3>
        <p>Departamento moderno de 2 habitaciones, cerca al malecón. Precio: USD 180,000</p>
        <a href="#" class="btn">Ver más</a>
      </div>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1522708323590-d24dbb6b0267" alt="Departamento San Isidro">
      <div class="card-body">
        <h3>San Isidro</h3>
        <p>Amplio departamento de 3 habitaciones, zona financiera. Precio: USD 250,000</p>
        <a href="#" class="btn">Ver más</a>
      </div>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1502673530728-f79b4cab31b1" alt="Departamento Surco">
      <div class="card-body">
        <h3>Santiago de Surco</h3>
        <p>Departamento familiar, áreas verdes y seguridad. Precio: USD 140,000</p>
        <a href="#" class="btn">Ver más</a>
      </div>
    </div>
  </div>
</section>

<section id="nosotros">
  <h2 class="section-title">¿Quiénes Somos?</h2>
  <p style="text-align:center; max-width:800px; margin:auto;">
    En <strong>LimaHome Inmobiliaria</strong> somos especialistas en la venta de departamentos en Lima, Perú. 
    Brindamos asesoría legal, seguridad en la compra y acompañamiento durante todo el proceso para que 
    encuentres el hogar ideal sin preocupaciones.
  </p>
</section>

<section id="contacto">
  <h2 class="section-title">Contáctanos</h2>
  <div class="contact-form">
    <input type="text" placeholder="Nombre completo" required>
    <input type="email" placeholder="Correo electrónico" required>
    <input type="tel" placeholder="Teléfono" required>
    <textarea rows="4" placeholder="Mensaje"></textarea>
    <button class="btn" style="width:100%; border:none;">Enviar mensaje</button>
  </div>
</section>

<footer>
  <p>© 2026 LimaHome Inmobiliaria | Lima - Perú</p>
</footer>

</body>
</html>
