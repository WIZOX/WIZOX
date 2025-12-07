<!doctype html>
<html lang="fr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Léo Jimenez — UI/UX Freelance & Lua Dev (FiveM)</title>
  <meta name="description" content="UI/UX Freelance · Développeur Lua — Scripts FiveM. Portfolio : UI design, prototypes, scripts et customisations pour serveurs GTA V (FiveM)." />
  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
  <!-- Font Awesome (icônes) -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" integrity="" crossorigin="anonymous" />
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header class="site-header">
    <nav class="nav container">
      <a class="brand" href="#">LéoJ — UI/UX · Lua</a>
      <div class="nav-right">
        <a class="btn-outline" href="#projects">Projets</a>
        <a class="btn-outline" href="#services">Services</a>
        <a class="btn-primary" href="#contact">Contact</a>
      </div>
    </nav>
  </header>

  <main>
    <section class="hero">
      <div class="container hero-grid">
        <div class="hero-left">
          <h1>UI/UX Freelance & <span>Développeur Lua</span> — Scripts <span>FiveM</span></h1>
          <p class="lead">
            Je conçois des interfaces modernes qui enchantent les utilisateurs, et j'implémente des scripts Lua optimisés pour FiveM.  
            Prototypage rapide — Design orienté joueur — Code propre et commenté.
          </p>
          <div class="hero-cta">
            <a class="btn-primary" href="#contact"><i class="fa fa-paper-plane"></i> Travaillons ensemble</a>
            <a class="btn-ghost" href="https://github.com/ton-username" target="_blank" rel="noopener"><i class="fa fa-github"></i> Voir mon GitHub</a>
          </div>

          <ul class="skills">
            <li><strong>UI/UX</strong> Prototypage, Figma → HTML/CSS</li>
            <li><strong>Lua</strong> Scripts FiveM, optimisation, events</li>
            <li><strong>RageUI / NativeUI</strong> Menus & systèmes de garage</li>
            <li><strong>Responsive</strong> Mobile-first & performance</li>
          </ul>
        </div>

        <div class="hero-right">
          <div class="card-glass project-quick">
            <div class="mock">
              <!-- simple phone mockup with gradient -->
              <svg viewBox="0 0 200 380" class="phone">
                <rect rx="22" ry="22" width="200" height="380" fill="url(#g)"/>
                <rect x="18" y="48" width="164" height="280" rx="10" fill="#ffffff10"/>
                <defs>
                  <linearGradient id="g" x1="0" x2="1">
                    <stop offset="0" stop-color="#6D5CFF"/>
                    <stop offset="1" stop-color="#00D4FF"/>
                  </linearGradient>
                </defs>
              </svg>
            </div>
            <div class="meta">
              <h3>Extrait UI — Dashboard serveur</h3>
              <p>Menu rapide, état du serveur, gestion joueurs + actions admin.</p>
              <div class="tags">
                <span>Figma → HTML</span>
                <span>Lua</span>
                <span>FiveM</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="services" class="container services">
      <h2>Services</h2>
      <div class="grid-3">
        <article class="service">
          <i class="fa fa-palette icon"></i>
          <h3>UI/UX Design</h3>
          <p>Design d'interfaces modernes, prototypes interactifs et expérience utilisateur optimisée.</p>
        </article>
        <article class="service">
          <i class="fa fa-code icon"></i>
          <h3>Développement Lua</h3>
          <p>Scripts sur-mesure pour FiveM : menus, garages, economy, téléport, etc. Code documenté.</p>
        </article>
        <article class="service">
          <i class="fa fa-rocket icon"></i>
          <h3>Intégration & Optimisation</h3>
          <p>Conversion de maquettes en UI réactif, optimisation pour performance et faible latence.</p>
        </article>
      </div>
    </section>

    <section id="projects" class="portfolio container">
      <h2>Projets récents</h2>
      <div class="grid-3 cards">
        <div class="card">
          <div class="card-head">
            <h4>Garage system — Ténéré</h4>
            <span class="label">Lua • FiveM</span>
          </div>
          <p>Instance-based garage, gestion clefs, vente/achat véhicules, intégration IPL & spawn.</p>
          <div class="card-footer">
            <a href="#" class="link">Voir le repo</a>
            <span class="muted">⭐ 120</span>
          </div>
        </div>

        <div class="card">
          <div class="card-head">
            <h4>Dashboard Admin</h4>
            <span class="label">UI/UX • JS</span>
          </div>
          <p>Tableau de bord responsive pour admins — monitoring, bans, logs et actions rapides.</p>
          <div class="card-footer">
            <a href="#" class="link">Voir le repo</a>
            <span class="muted">⭐ 86</span>
          </div>
        </div>

        <div class="card">
          <div class="card-head">
            <h4>Market & Shops</h4>
            <span class="label">Lua • SQL</span>
          </div>
          <p>Système d'économie avec shops, stocks, et commandes asynchrones côté serveur.</p>
          <div class="card-footer">
            <a href="#" class="link">Voir le repo</a>
            <span class="muted">⭐ 98</span>
          </div>
        </div>
      </div>
      <p class="center small-note">Tu veux que j'ajoute plus de projets ? Je peux générer des README & screenshots pour chaque repo.</p>
    </section>

    <section id="contact" class="contact container">
      <h2>Contact</h2>
      <div class="contact-grid">
        <div class="contact-card card-glass">
          <h3>Envie de collaborer ?</h3>
          <p>Envoie un message pour discuter d'un projet, d'un devis ou d'une intégration.</p>
          <ul class="contact-list">
            <li><i class="fa fa-envelope"></i> <a href="mailto:ton-email@exemple.com">ton-email@exemple.com</a></li>
            <li><i class="fa fa-phone"></i> <a href="tel:+212600000000">+212 6 00 00 00 00</a></li>
            <li><i class="fa fa-github"></i> <a href="https://github.com/ton-username" target="_blank">github.com/ton-username</a></li>
          </ul>
          <a class="btn-primary" href="mailto:ton-email@exemple.com"><i class="fa fa-envelope-open"></i> Envoyer un e-mail</a>
        </div>

        <form class="contact-form card-glass" action="#" onsubmit="alert('Remplace action par ton endpoint ou GitHub issues.'); return false;">
          <label>
            Nom
            <input type="text" name="name" placeholder="Ton nom" required>
          </label>
          <label>
            E-mail
            <input type="email" name="email" placeholder="ton@email.com" required>
          </label>
          <label>
            Projet / message
            <textarea name="message" rows="5" placeholder="Décris ton projet, budget, deadlines..." required></textarea>
          </label>
          <div class="form-actions">
            <button class="btn-primary" type="submit">Envoyer</button>
            <button class="btn-ghost" type="reset">Effacer</button>
          </div>
        </form>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container footer-grid">
      <div>
        <strong>Léo Jimenez</strong>
        <p>UI/UX Freelancer • Lua Developer — FiveM</p>
      </div>
      <div class="footer-links">
        <a href="#">Privacy</a>
        <a href="#">Terms</a>
        <a href="#">CV (PDF)</a>
      </div>
    </div>
    <div class="copyright">© <span id="year"></span> Léo Jimenez — Tous droits réservés.</div>
  </footer>

  <script>
    // petits helpers
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
 





