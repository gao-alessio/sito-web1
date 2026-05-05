<!DOCTYPE html>
<html lang="it">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>NexaStore — Cloud semplice e sicuro</title>
<style>
       * {
           margin: 0;
           padding: 0;
           box-sizing: border-box;
           font-family: 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
       }
       body {
           background-color: #0f172a;
           color: #f1f5f9;
           line-height: 1.6;
       }
       /* Navbar Dark */
       nav {
           background-color: #1e293b;
           box-shadow: 0 2px 15px rgba(0,0,0,0.3);
           padding: 1rem 5%;
           display: flex;
           justify-content: space-between;
           align-items: center;
           position: sticky;
           top: 0;
           z-index: 100;
       }
       .logo {
           font-size: 1.8rem;
           font-weight: 700;
           color: #38bdf8;
           text-decoration: none;
       }
       .nav-links {
           display: flex;
           gap: 2rem;
       }
       .nav-links a {
           text-decoration: none;
           color: #cbd5e1;
           font-weight: 500;
           transition: color 0.3s ease;
       }
       .nav-links a:hover {
           color: #38bdf8;
       }
       .btn {
           padding: 0.7rem 1.5rem;
           border-radius: 8px;
           border: none;
           cursor: pointer;
           font-weight: 600;
           transition: all 0.3s ease;
       }
       .btn-primary {
           background-color: #38bdf8;
           color: #0f172a;
       }
       .btn-primary:hover {
           background-color: #0ea5e9;
       }
       .btn-outline {
           background-color: transparent;
           color: #38bdf8;
           border: 2px solid #38bdf8;
       }
       .btn-outline:hover {
           background-color: rgba(56, 189, 248, 0.1);
       }
       /* Hero Section */
       .hero {
           padding: 5rem 5%;
           display: flex;
           flex-direction: column;
           align-items: center;
           text-align: center;
           gap: 2rem;
       }
       .hero h1 {
           font-size: 3rem;
           max-width: 800px;
           color: #ffffff;
       }
       .hero p {
           font-size: 1.2rem;
           color: #94a3b8;
           max-width: 700px;
       }
       .hero-buttons {
           display: flex;
           gap: 1rem;
           margin-top: 1rem;
       }
       /* Footer */
       footer {
           background-color: #0f172a;
           color: #94a3b8;
           padding: 3rem 5%;
           text-align: center;
           margin-top: 4rem;
       }
       .footer-links {
           display: flex;
           justify-content: center;
           gap: 2rem;
           margin: 2rem 0;
       }
       .footer-links a {
           color: #cbd5e1;
           text-decoration: none;
       }
       .footer-links a:hover {
           color: #38bdf8;
       }
       /* Responsive */
       @media (max-width: 768px) {
           .nav-links {
               display: none;
           }
           .hero h1 {
               font-size: 2rem;
           }
           .hero-buttons {
               flex-direction: column;
               width: 100%;
           }
           .btn {
               width: 100%;
           }
       }
</style>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
<nav>
<a href="index.html" class="logo">NexaStore</a>
<div class="nav-links">
<a href="funzioni.html">Vantaggi</a>
<a href="spazio.html">Spazio</a>
<a href="upload.html">Upload</a>
<a href="#prezzi">Piani</a>
</div>
<div class="nav-buttons">
<button class="btn btn-outline">Accedi</button>
<button class="btn btn-primary">Registrati</button>
</div>
</nav>

<section class="hero">
<h1>Salva i tuoi file in modo semplice</h1>
<p>NexaStore è un cloud europeo facile da usare. Puoi salvare foto, video e documenti da qualsiasi telefono o computer.</p>
<div class="hero-buttons">
<button class="btn btn-primary">Inizia gratis</button>
<button class="btn btn-outline">Scopri di più</button>
</div>
</section>

<footer>
<h3>NexaStore — Cloud semplice e sicuro</h3>
<div class="footer-links">
<a href="#">Regole d’uso</a>
<a href="#">Privacy</a>
<a href="#">Contatti</a>
<a href="#">Domande comuni</a>
</div>
<p>© 2026 NexaStore — Tutti i diritti riservati</p>
</footer>
</body>
</html>