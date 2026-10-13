# Alimus-tech.Com
Alimus tech énergie en toute confiance 
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>ALIMUS-TECH | Électricité du bâtiment et solutions techniques</title>

  <meta name="description" content="ALIMUS-TECH propose des services d'installation électrique, de maintenance, de formation théorique et pratique en électricité du bâtiment et d'assistance informatique. Contactez-nous pour demander un devis.">

  <meta name="theme-color" content="#101b32">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, Helvetica, sans-serif;
      line-height: 1.7;
      color: #243047;
      background: #f5f7fb;
    }

    header {
      background: #101b32;
      color: white;
      padding: 15px 6%;
      display: flex;
      align-items: center;
      justify-content: space-between;
      flex-wrap: wrap;
      gap: 15px;
    }

    .brand {
      display: flex;
      align-items: center;
      gap: 12px;
      font-size: 22px;
      font-weight: bold;
      letter-spacing: 1px;
    }

    .brand img {
      width: 60px;
      height: 60px;
      object-fit: contain;
    }

    nav {
      display: flex;
      flex-wrap: wrap;
      gap: 18px;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-size: 14px;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #f2b632;
    }

    .hero {
      background: linear-gradient(135deg, #101b32, #164b78);
      color: white;
      text-align: center;
      padding: 90px 20px;
    }

    .hero h1 {
      font-size: clamp(32px, 5vw, 48px);
      line-height: 1.2;
      margin-bottom: 22px;
    }

    .hero p {
      max-width: 750px;
      margin: 0 auto 28px;
      font-size: 17px;
    }

    .button {
      display: inline-block;
      padding: 13px 23px;
      background: #f2b632;
      color: #101b32;
      text-decoration: none;
      border-radius: 6px;
      font-weight: bold;
      margin: 6px;
      transition: 0.3s;
      border: 2px solid #f2b632;
    }

    .button:hover {
      background: transparent;
      color: #f2b632;
    }

    .button-outline {
      background: transparent;
      color: white;
      border-color: white;
    }

    .button-outline:hover {
      background: white;
      color: #101b32;
    }

    section {
      padding: 65px 7%;
      scroll-margin-top: 20px;
    }

    section h2 {
      text-align: center;
      font-size: 30px;
      color: #101b32;
      margin-bottom: 20px;
    }

    .intro {
      max-width: 850px;
      text-align: center;
      margin: 0 auto;
    }

    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
      gap: 24px;
      margin-top: 38px;
    }

    .card {
      background: white;
      padding: 28px 24px;
      border-radius: 10px;
      box-shadow: 0 4px 18px rgba(16, 27, 50, 0.08);
      border-bottom: 4px solid #f2b632;
      transition: transform 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    .card h3 {
      color: #164b78;
      font-size: 20px;
      margin-bottom: 12px;
    }

    .card p {
      font-size: 15px;
    }

    #apropos {
      background: white;
    }

    #devis {
      background: #e9eef5;
    }

    .devis-box {
      max-width: 850px;
      margin: 25px auto 0;
      padding: 30px;
      background: white;
      border-radius: 10px;
      text-align: center;
      box-shadow: 0 4px 18px rgba(16, 27, 50, 0.07);
    }

    .devis-box h3 {
      color: #164b78;
      margin-bottom: 12px;
    }

    #contact {
      text-align: center;
      background: white;
    }

    #contact p {
      margin: 10px 0;
    }

    footer {
      background: #101b32;
      color: white;
      text-align: center;
      padding: 25px 15px;
      font-size: 14px;
    }

    footer p {
      margin: 5px 0;
    }

    @media (max-width: 650px) {
      header {
        justify-content: center;
      }

      .brand {
        justify-content: center;
      }

      nav {
        justify-content: center;
        gap: 12px;
      }

      .hero {
        padding: 65px 18px;
      }

      section {
        padding: 48px 6%;
      }

      section h2 {
        font-size: 26px;
      }

      .devis-box {
        padding: 22px 16px;
      }
    }
  </style>
</head>

<body>

  <!-- EN-TÊTE ET LOGO -->
  <header>
    <div class="brand">
      <img src="logo.png" alt="Logo officiel ALIMUS-TECH">
      <span>ALIMUS-TECH</span>
    </div>

    <nav aria-label="Navigation principale">
      <a href="#accueil">Accueil</a>
      <a href="#apropos">À propos</a>
      <a href="#services">Services</a>
      <a href="#formation">Formation</a>
      <a href="#devis">Devis</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main>

    <!-- PAGE D'ACCUEIL -->
    <section class="hero" id="accueil">
      <h1>Bienvenue chez ALIMUS-TECH</h1>

      <p>
        Votre partenaire en électricité du bâtiment, maintenance
        et solutions techniques. Nous mettons notre savoir-faire
        au service de vos projets avec une approche fondée sur
        la qualité, la sécurité et le professionnalisme.
      </p>

      <a class="button"
         href="https://wa.me/243966692973?text=Bonjour%20ALIMUS-TECH%2C%20je%20souhaite%20obtenir%20des%20informations%20sur%20vos%20services.">
        Contactez-nous
      </a>

      <a class="button button-outline" href="#devis">
        Demander un devis
      </a>
    </section>

    <!-- À PROPOS -->
    <section id="apropos">
      <h2>À propos d'ALIMUS-TECH</h2>

      <p class="intro">
        ALIMUS-TECH est une initiative spécialisée dans les
        solutions techniques, avec un accent particulier sur
        l'électricité du bâtiment et la formation professionnelle.
        Notre objectif est d'accompagner les particuliers,
        les professionnels et les organisations dans leurs projets,
        en privilégiant la qualité du travail, la sécurité
        des installations et le développement des compétences.
      </p>
    </section>

    <!-- NOS SERVICES -->
    <section id="services">
      <h2>Nos services</h2>

      <p class="intro">
        ALIMUS-TECH vous accompagne dans vos travaux et projets
        techniques grâce à des prestations adaptées à vos besoins.
      </p>

      <div class="services">

        <article class="card">
          <h3>Installations électriques</h3>
          <p>
            Réalisation d'installations électriques dans les
            bâtiments, câblage, mise en place des équipements
            et organisation des circuits électriques dans le
            respect des règles de sécurité applicables.
          </p>
        </article>

        <article class="card">
          <h3>Maintenance et dépannage</h3>
          <p>
            Diagnostic des pannes, entretien des installations
            électriques et recherche de solutions adaptées
            afin de contribuer au bon fonctionnement
            et à la sécurité des équipements.
          </p>
        </article>

        <article class="card" id="formation">
          <h3>Formation en électricité du bâtiment</h3>
          <p>
            Formation théorique et pratique destinée aux débutants
            et aux personnes souhaitant renforcer leurs compétences.
            Le programme aborde les principes fondamentaux,
            les installations électriques, le câblage, les règles
            de sécurité et les exercices pratiques en électricité
            du bâtiment.
          </p>
        </article>

        <article class="card">
          <h3>Assistance informatique</h3>
          <p>
            Accompagnement et assistance dans l'utilisation
            des outils informatiques, selon les besoins
            et les prestations disponibles.
          </p>
        </article>

        <article class="card">
          <h3>Conseils techniques</h3>
          <p>
            Accompagnement dans la préparation de vos projets,
            conseils sur les travaux envisagés et orientation
            vers des solutions techniques adaptées à vos besoins.
          </p>
        </article>

      </div>
    </section>

    <!-- DEMANDE DE DEVIS -->
    <section id="devis">
      <h2>Demandez votre devis</h2>

      <p class="intro">
        Vous avez un projet d'installation électrique, de maintenance
        ou de formation en électricité du bâtiment ? ALIMUS-TECH
        vous accompagne dans l'évaluation de vos besoins afin
        de préparer une proposition adaptée à votre projet.
      </p>

      <div class="devis-box">
        <h3>Parlons de votre projet</h3>

        <p>
          Pour nous permettre d'étudier votre demande, veuillez
          préparer une description des travaux souhaités, le lieu
          d'exécution, les dimensions ou caractéristiques utiles
          et, si possible, votre budget indicatif.
        </p>

        <p>
          Notre équipe pourra examiner les informations transmises
          et vous communiquer les prochaines étapes pour
          l'établissement de votre devis.
        </p>

        <a class="button"
           href="https://wa.me/243966692973?text=Bonjour%20ALIMUS-TECH%2C%20je%20souhaite%20demander%20un%20devis.%0A%0ANom%20%3A%0AType%20de%20service%20%3A%0ALieu%20du%20projet%20%3A%0ADescription%20des%20travaux%20%3A%0ABudget%20indicatif%20(si%20disponible)%20%3A">
          Envoyer une demande de devis
        </a>
      </div>
    </section>

    <!-- CONTACT -->
    <section id="contact">
      <h2>Contactez-nous</h2>

      <p>
        Vous avez une question ou souhaitez discuter
        de votre projet ? Contactez directement ALIMUS-TECH.
      </p>

      <p>
        <strong>Téléphone :</strong> +243 966 692 973
      </p>

      <a class="button"
         href="https://wa.me/243966692973?text=Bonjour%20ALIMUS-TECH%2C%20je%20vous%20contacte%20depuis%20votre%20site%20internet.">
        Nous écrire sur WhatsApp
      </a>
    </section>

  </main>

  <!-- PIED DE PAGE -->
  <footer>
    <p><strong>ALIMUS-TECH</strong></p>
    <p>Électricité du bâtiment, formation et solutions techniques.</p>
    <p>&copy; 2026 ALIMUS-TECH. Tous droits réservés.</p>
  </footer>

</body>
</html>
