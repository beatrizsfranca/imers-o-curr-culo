<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Currículo | Anna Beatriz</title>
    <link rel="stylesheet" href="Style.css">
</head>
<body>
    <div class="container">
       <div class="header">
        <img src="beatrizfoto.jpg" alt="Foto de Anna Beatriz">
       </div>
       <div class="main">
           <h1>Currículo de Anna Beatriz</h1>
           <p>Brasileira, 18 anos</p>
           <p>Recife, Pernambuco</p>
           <p>📞 (81) 9 8595-5445 - 📧 beatrizlvfranca91@gmail.com</p>
           <P> 
                 <a href="https://www.linkedin.com/in/annabeatriz" target="_blank">LinkedIn</a> | 
                 <a href="https://github.com/annabeatriz" target="_blank">GitHub</a>
           </P>
           
            <!-- Perfil -->
    <h2>Perfil</h2>
    <p>Seu perfil profissional em 3–5 linhas. Fale sobre suas áreas de interesse, principais habilidades e objetivos de carreira.</p>

    <!-- Formação -->
    <h2>Formação</h2>
    <ul>
      <li>Seu Curso – Sua Instituição (AAAA–AAAA)</li>
      <li>Outro Curso/Certificação – Instituição (AAAA–AAAA)</li>
      <li>Curso em andamento – Instituição (AAAA) – Cursando</li>
    </ul>
        <!-- Experiência Profissional -->
        <h2>Experiência Profissional</h2>
        <ul>
          <li><b>Seu Cargo</b> – Nome da Empresa (MMM/AAAA – MMM/AAAA)</li>
          <li><b>Seu Cargo</b> – Nome da Empresa (MMM/AAAA – Atual)</li>
        </ul>
    
        <!-- Projetos -->
        <h2>Projetos</h2>
        <ul>
          <li><b>Nome do Projeto</b> (AAAA) – Breve descrição, tecnologias usadas e seu papel.</li>
          <li><b>Outro Projeto</b> (AAAA) – O que foi feito, impacto e stack.</li>
        </ul>
    
        <!-- Qualificações -->
        <h2>Qualificações</h2>
        <ul>
          <li>Habilidade/Competência 1</li>
          <li>Habilidade/Competência 2</li>
          <li>Habilidade/Competência 3</li>
        </ul>
    
        <!-- Idiomas -->
        <h2>Idiomas</h2>
        <ul>
          <li>Inglês – Nível (ex.: B2)</li>
          <li>Outro Idioma – Nível</li>
        </ul>
    
        <!-- Informações Adicionais -->
        <h2>Informações Adicionais</h2>
        <ul>
          <li>Tecnologias: HTML, CSS, JavaScript, Python, …</li>
          <li>Ferramentas: Pacote Office, Git, Figma, …</li>
          <li>Outros: Edição de imagens, participação em eventos, voluntariado, …</li>
        </ul>
        <div class="buttons">
            <button id="btn-print">Imprimir/salvar pdf</button>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
document.getElementById("btn-print").addEventListener(
"click", () => {
    window.print();
}
);
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Currículo</title>
  <style>
    /* ======== CONTAINER PRINCIPAL ======== */
    .container {
      max-width: 900px;                 
      margin: 40px auto;                
      background: #fff;                 
      padding: 30px;                    
      box-shadow: 0 4px 10px rgba(0,0,0,.1); 
      border-radius: 10px;              
      font-family: Arial, sans-serif;
    }
    
    /* ======== CABEÇALHO (foto + nome + contatos) ======== */
    .header {
      text-align: center;               
      margin-bottom: 20px;              
    }
    
    .header img {
      width: 150px;                     
      height: 150px;                    
      object-fit: cover;                
      border-radius: 50%;               
      border: 3px solid #dd69d5;        
    }
    
    .header h1 {
      margin: 15px 0 5px;               
      color: #dd69d5;                   
    }
    
    .header p {
      margin: 2px 0;                    
      color: #555;                      
    }
    
    /* ======== TÍTULOS DE SEÇÃO ======== */
    h2 {
      color: #000000;                   
      border-bottom: 2px solid #000000; 
      padding-bottom: 5px;              
      margin-top: 30px;                 
    }
    
    /* ======== TEXTO ======== */
    p,
    li {
      text-align: justify;              
      line-height: 1.6;                 
    }
    
    /* ======== LISTAS ======== */
    ul {
      list-style: none;                 
      padding: 0;                       
    }
    
    ul li::before {
      content: "• ";                    
      color: #6b1365;                   
      font-weight: bold;  

      #btn-print {
        background-color: #ab26a2;
        color: #fff;
        border: none;
        border-radius: 5px;
        padding: 10px 15px;
        cursor: pointer;
      }

    }
  </style>
</head>
<body>
  <div class="container">
    <!-- Cabeçalho -->
    <div class="header">
      <img src="https://via.placeholder.com/150" alt="Foto de Perfil">
      <h1>Seu Nome</h1>
      <p>Idade: 20 anos</p>
      <p>Cidade: Recife - PE</p>
      <p>Email: exemplo@email.com</p>
    </div>

    <!-- Sobre -->
    <h2>Sobre Mim</h2>
    <p>
      Sou uma pessoa dedicada, apaixonada por tecnologia e com grande interesse em aprender novas habilidades.
    </p>

    <!-- Formação -->
    <h2>Formação</h2>
    <ul>
      <li>Ensino Médio Completo</li>
      <li>Curso Técnico em Informática</li>
    </ul>

    <!-- Experiência -->
    <h2>Experiência</h2>
    <ul>
      <li>Estágio em Suporte Técnico - Empresa X</li>
      <li>Atendimento ao Cliente - Empresa Y</li>
    </ul>

    <!-- Habilidades -->
    <h2>Habilidades</h2>
    <ul>
      <li>HTML, CSS e JavaScript</li>
      <li>Boa comunicação</li>
      <li>Trabalho em equipe</li>
    </ul>
  </div>
</body>
</html>
