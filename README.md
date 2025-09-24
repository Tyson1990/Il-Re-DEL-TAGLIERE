# Il-RE-DEL-TAGLIERE
<!DOCTYPE html>
<html lang="it">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Il Re del Tagliere</title>
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
<style>
* { margin:0; padding:0; box-sizing:border-box; }
body { font-family: 'Roboto', sans-serif; background:#fff8f0; color:#333; scroll-behavior: smooth; }
header { position:relative; height:90vh; overflow:hidden; }
header video { width:100%; height:100%; object-fit:cover; position:absolute; top:0; left:0; z-index:0; }
header .overlay { position:absolute; inset:0; background: rgba(0,0,0,0.4); display:flex; flex-direction:column; justify-content:center; align-items:center; color:white; text-align:center; padding:0 20px; z-index:1; }
header h1 { font-size:3em; margin-bottom:15px; }
header p { font-size:1.5em; margin-bottom:25px; }
header .btn { background:#e74c3c; color:white; padding:12px 30px; text-decoration:none; border-radius:8px; transition:0.3s; }
header .btn:hover { background:#c0392b; }
nav { display:flex; justify-content:center; background:#e74c3c; position:sticky; top:0; z-index:10; }
nav a { color:white; text-decoration:none; padding:15px 25px; display:block; transition:0.3s; }
nav a:hover { background:#c0392b; }
section { padding:60px 20px; text-align:center; }
section h2 { font-size:2.5em; margin-bottom:25px; color:#c0392b; }
section p { max-width:700px; margin:0 auto 30px; line-height:1.6; }
.menu-container { display:grid; grid-template-columns:repeat(auto-fit,minmax(250px,1fr)); gap:30px; max-width:1200px; margin:0 auto; }
.menu-item { position:relative; overflow:hidden; border-radius:15px; cursor:pointer; transition:transform 0.5s, box-shadow 0.5s; }
.menu-item img { width:100%; display:block; border-radius:15px; transition:transform 0.5s; }
.menu-item:hover img { transform:scale(1.1); }
.menu-item .overlay { position:absolute; inset:0; background:rgba(192,57,43,0.7); color:white; display:flex; flex-direction:column; justify-content:center; align-items:center; opacity:0; transition:0.5s; text-align:center; padding:20px; }
.menu-item:hover .overlay { opacity:1; }
.menu-item h3 { margin-bottom:10px; font-size:1.5em; }
.menu-item p { font-size:1em; }
.contact-info p { margin:10px 0; }
.contact-info .btn { margin-top:15px; }
.reservation form { display:flex; flex-direction:column; max-width:400px; margin:20px auto; }
.reservation input, .reservation textarea, .reservation button { padding:10px; margin:5px 0; border-radius:5px; border:1px solid #ccc; }
.reservation button { background:#e74c3c; color:white; border:none; cursor:pointer; transition:0.3s; }
.reservation button:hover { background:#c0392b; }
footer { background:#c0392b; color:white; text-align:center; padding:25px 20px; }
footer .social { margin-top:10px; }
footer .social a { color:white; margin:0 10px; font-size:1.2em; transition:0.3s; }
footer .social a:hover { color:#ffd700; }
@media(max-width:768px){ header h1{ font-size:2.2em;} header p{ font-size:1.2em;} }
</style>
</head>
<body>
<header>
  <video autoplay muted loop playsinline>
    <source src="https://www.w3schools.com/howto/rain.mp4" type="video/mp4">
  </video>
  <div class="overlay">
    <h1>Il Re del Tagliere</h1>
    <p>Cucina tipica sangiovannese e specialità italiane</p>
    <a href="#apertura" class="btn">Scopri di più</a>
  </div>
</header>
<nav>
  <a href="#chi-siamo">Chi Siamo</a>
  <a href="#apertura">Prossima Apertura</a>
  <a href="#menu">Menu</a>
  <a href="#contatti">Contatti</a>
  <a href="#prenotazioni">Prenotazioni</a>
</nav>
<section id="chi-siamo">
  <h2>Chi Siamo</h2>
  <p>Benvenuti a <strong>Il Re del Tagliere</strong>, il ristorante dove la passione per la cucina italiana si fonde con i sapori autentici della <strong>cucina tipica sangiovannese</strong>. Offriamo un’esperienza culinaria unica, dai taglieri ricchi di salumi e formaggi locali, alle specialità della tradizione preparate con cura e creatività. Il nostro obiettivo è farvi sentire come a casa, regalando momenti di gusto indimenticabili in un ambiente accogliente e raffinato.</p>
</section>
<section id="apertura">
  <h2>Prossima Apertura</h2>
  <p>Il nostro ristorante aprirà presto! Seguiteci per restare aggiornati sulla data di apertura e sulle novità del menu.</p>
  <p>Da noi, la maggior parte dei piatti viene servita su eleganti <strong>taglieri in legno</strong>, per un’esperienza autentica e conviviale della cucina sangiovannese.</p>
</section>
<section id="menu">
  <h2>Il Nostro Menu</h2>
  <div class="menu-container">
    <div class="menu-item">
      <img src="https://images.unsplash.com/photo-1603078655530-34f20de3d3e1?auto=format&fit=crop&w=400&q=80" alt="Pizza Margherita">
      <div class="overlay">
        <h3>Pizza Margherita</h3>
        <p>Pomodoro, mozzarella, basilico fresco</p>
      </div>
    </div>
    <div class="menu-item">
      <img src="https://images.unsplash.com/photo-1589308078053-2e5ec1c0c8df?auto=format&fit=crop&w=400&q=80" alt="Spaghetti Carbonara">
      <div class="overlay">
        <h3>Spaghetti alla Carbonara</h3>
        <p>Uova, guanciale, pecorino romano</p>
      </div>
    </div>
    <div class="menu-item">
      <img src="https://images.unsplash.com/photo-1604917868555-ef0323e5d0a6?auto=format&fit=crop&w=400&q=80" alt="Tiramisu">
      <div class="overlay">
        <h3>Tiramisu</h3>
        <p>Dolce classico italiano con mascarpone e caffè</p>
      </div>
    </div>
  </div>
</section>
<section id="contatti">
  <h2>Contatti</h2>
  <div class="contact-info">
    <p>Indirizzo: Via Crotone, 90, 87055 San Giovanni in Fiore CS, Italia</p>
    <p>Email: <a href="mailto:Biagiomnc90@gmail.com">Biagiomnc90@gmail.com</a></p>
    <a href="mailto:Biagiomnc90@gmail.com" class="btn">Scrivici</a>
  </div>
</section>
<section id="prenotazioni">
  <h2>Prenotazioni Online</h2>
  <div class="reservation">
    <form action="#" target="_blank">
      <input type="text" placeholder="Nome e Cognome" required>
      <input type="email" placeholder="Email" required>
      <input type="tel" placeholder="Telefono" required>
      <textarea placeholder="Note o richieste speciali" rows="4"></textarea>
      <button type="submit">Prenota Ora</button>
    </form>
  </div>
</section>
<footer>
  <p>© 2025 Il Re del Tagliere | Tutti i diritti riservati</p>
  <div class="social">
    <a href="#"><i class="fab fa-facebook-f"></i></a>
    <a href="#"><i class="fab fa-instagram"></i></a>
    <a href="#"><i class="fab fa-tripadvisor"></i></a>
  </div>
</footer>
</body>
</html>
