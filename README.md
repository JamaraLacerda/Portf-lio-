<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Jamara Lacerda - Portfólio</title>
  
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    html { scroll-behavior: smooth; }
    body {
      font-family: 'Inter', sans-serif;
      background: #fff;
      color: #111;
      line-height: 1.6;
      min-height: 100vh;
    }
    a {
      color: #FF4C60;
      text-decoration: none;
      font-weight: 600;
    }
    a:hover { text-decoration: underline; }

    header {
      position: fixed;
      top: 0; left: 0; right: 0;
      background: #fff;
      border-bottom: 1px solid #eee;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      z-index: 100;
      font-weight: 600;
      font-size: 1.2rem;
    }
    nav a { margin-left: 2rem; transition: color 0.3s; }
    nav a:hover { color: #FF4C60; }

    main { max-width: 850px; margin: 5rem auto 3rem; padding: 0 1rem; }
    section { margin-bottom: 4rem; opacity: 0; transform: translateY(20px); transition: opacity 0.6s ease-out, transform 0.6s ease-out; }
    section.visible { opacity: 1; transform: none; }

    h1, h2, h3 { color: #222; }
    h1 { font-size: 2.8rem; font-weight: 800; margin-bottom: 0.2rem; }
    h2 { font-size: 2rem; margin-bottom: 1rem; font-weight: 700; }
    h3 { font-weight: 700; margin-bottom: 0.5rem; }

    p { color: #555; font-size: 1.1rem; margin-bottom: 1rem; }

    .project {
      background: #f9f9f9;
      border-radius: 10px;
      padding: 1.5rem;
      margin-bottom: 1.5rem;
      box-shadow: 0 2px 6px rgba(0,0,0,0.05);
      transition: box-shadow 0.3s ease;
    }
    .project:hover { box-shadow: 0 6px 15px rgba(255, 76, 96, 0.3); }
    .project a { font-weight: 600; color: #FF4C60; display: inline-block; margin-top: 0.5rem; }

    footer { text-align: center; padding: 2rem 1rem; color: #aaa; font-size: 0.9rem; }

    .contact-links a {
      margin-right: 1.5rem;
      font-size: 2rem;
      color: #FF4C60;
      transition: color 0.3s;
    }
    .contact-links a:hover { color: #e0324a; }

    @media (max-width: 600px) {
      header { flex-direction: column; align-items: flex-start; }
      nav a { margin: 0.5rem 1rem 0 0; }
      main { margin: 7rem 1rem 3rem; }
    }
  </style>
</head>
<body>

<header>
  <div><strong>Jamara Lacerda</strong></div>
  <nav>
    <a href="#about">Sobre</a>
    <a href="#projects">Projetos</a>
    <a href="#contact">Contato</a>
  </nav>
</header>

<main>
  <section id="about">
    <h1>Olá, eu sou a Jamara!</h1>
    <p>Sou estudante de Tecnologia da Informação, desenvolvendo projetos em PHP, JavaScript e SQL. Tenho interesse em criar soluções simples e funcionais e estou sempre em busca de novos aprendizados.</p>
    <p>Sou dedicada, organizada e busco aprimorar meus conhecimentos por meio de projetos práticos e estudos constantes.</p>
  </section>

  <section id="projects">
    <h2>Projetos</h2>

    <div class="project">
      <h3>Calculadora PHP</h3>
      <p>Aplicação web que realiza operações matemáticas básicas e verifica se um número é par ou ímpar. Desenvolvido para praticar lógica de programação em PHP.</p>
      <p><strong>Tecnologias:</strong> PHP, HTML, CSS</p>
      <a href="#" target="_blank" rel="noopener noreferrer">Ver código no GitHub</a>
    </div>

    <div class="project">
      <h3>Sistema de Cadastro com SQL</h3>
      <p>Sistema para cadastro, edição e exclusão de usuários, utilizando banco de dados MySQL. Prática de CRUD e organização de dados.</p>
      <p><strong>Tecnologias:</strong> PHP, MySQL</p>
      <a href="#" target="_blank" rel="noopener noreferrer">Ver código no GitHub</a>
    </div>

    <div class="project">
      <h3>Site “Anne with an E”</h3>
      <p>Site temático da série ‘Anne with an E’, com páginas de personagens, episódios e curiosidades. Desenvolvido com foco em organização de conteúdo, design limpo e layout responsivo.</p>
      <p><strong>Tecnologias:</strong> PHP, HTML, CSS</p>
      <a href="https://anne.infinityfreeapp.com/" target="_blank" rel="noopener noreferrer">Ver site online</a>
      <a href="#" target="_blank" rel="noopener noreferrer">Ver código no GitHub</a>
    </div>

    <div class="project">
      <h3>Site “Lana Del Rey”</h3>
      <p>Site sobre a cantora Lana Del Rey, com seções de discografia, curiosidades e imagens. Desenvolvido com atenção ao design limpo, navegação intuitiva e conteúdo organizado.</p>
      <p><strong>Tecnologias:</strong> PHP, HTML, CSS</p>
      <a href="https://laninhadiva.infinityfreeapp.com/" target="_blank" rel="noopener noreferrer">Ver site online</a>
      <a href="#" target="_blank" rel="noopener noreferrer">Ver código no GitHub</a>
    </div>

  </section>

  <section id="contact">
    <h2>Contato</h2>
    <p>Vamos nos conectar!</p>
    <div class="contact-links">
      <a href="mailto:jamara.trabalhos@gmail.com" aria-label="Email"><i class="fas fa-envelope"></i></a>
      <a href="https://linkedin.com/in/jamara-lacerda-a2803836a" target="_blank" aria-label="LinkedIn"><i class="fab fa-linkedin"></i></a>
      <a href="https://github.com/JamaraLacerda" target="_blank" aria-label="GitHub"><i class="fab fa-github"></i></a>
    </div>
  </section>
</main>

<footer>
  <p>© 2025 Jamara Lacerda — Portfólio Pessoal</p>
</footer>

<script>
  const sections = document.querySelectorAll('section');

  function checkSections() {
    const triggerBottom = window.innerHeight * 0.85;

    sections.forEach(section => {
      const sectionTop = section.getBoundingClientRect().top;

      if(sectionTop < triggerBottom) {
        section.classList.add('visible');
      } else {
        section.classList.remove('visible');
      }
    });
  }

  window.addEventListener('scroll', checkSections);
  window.addEventListener('load', checkSections);
</script>

</body>
</html>
