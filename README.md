# sitehub

<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HUB - Hardware Unity Bussiness</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
    <section id="header">
      <div class="container">
        <h1 class="logo">HUB</h1>
        <div class="header-text"> 
         <h1>HUB. Sempre Apontando Para o Futuro!</h1>
         <span class="square">

         </span>
         <p>HUB renova com segurança a tecnologia doada localmente e a devolve à nossa comunidade sem custo ou baixo custo para fornecer às populações mais vulneráveis ​​da nossa comunidade as habilidades de alfabetização digital de que precisam para ter sucesso e prosperar.</p>

          
        <button class="common-btn">Ler Mais</button>
        
        </p>
        </div>
      </div>
    </section>
       <nav id="sidenav">
        <ul>
          
            <li><a href="#">Inicio</a></li>
            <li><a href="#">Login</a></li>
          
        </ul>
       </nav>
       <img src="menu.png" id="menuBtn">
       <!--sobre-->
        <section id="about">
         <div class="about-left-col">
         <img src="WhatsApp Image 2023-06-26 at 03.53.10.jpeg">
         </div>
         <div class="about-right-col">
          <div class="about-text">

            <h1>Sobre Nós</h1>
            <span class="square">
            </span>
            <p>Somos uma organização com a missão de reutilizar tecnologia de forma sustentável, permitir acesso digital e fornecer educação para criar uma comunidade que capacita as pessoas a realizarem seu potencial.</p> <br>
            <br>
         
            <h2>A reciclagem transforma coisas em outras, o que é quase mágico.</h2>
            <h3>----João de Paula</h3>
          </div>
         </div>
        </section>

         <!--xxxx-->
         <section id="features">
          <div class="feature-row">
            <div class="feature-col">
              <img src="eletronico.png">
              <h4>Coletar</h4>
              <p>Coletamos o E-Lixo</p>
            </div>
            <div class="feature-col">
              <img src="ferramentas.png">
              <h4>Reformar</h4>
              <p>Reformamos para transformar em material de qualidade</p>
            </div>
            <div class="feature-col">
              <img src="computador-portatil.png">
              <h4>Disponibilizar</h4>
              <p>Disponibilizamos a quem precisa</p>
            </div>
          </div>
         </section>
       
             <section id="c">
              <div class="container c-row">
                <div class="c-left-col">
                  <div class="c-text">
                    <h1>Distribuição Regional de Números de Pessoas que não possuem acesso a tecnologia</h1>
                    <p>Em milhões de pessoas. Números de 2022, segundo o IBGE</p>
                  </div>
                </div>
                <div class="c-right-col">
                  <img src="Pie.jpg">
                </div>
              </div>
             </section>

             <section id="of">
              <div class="about-left-col">
              <img src="WhatsApp Image 2023-06-26 at 03.21.53.jpeg">
              </div>
              <div class="about-right-col">
               <div class="about-text">
     
                 <h1>História</h1>
                 <span class="square">
                 </span>
                 <p>Hub nasceu em meio um projeto escolar, onde quatro alunos se juntaram e discutiram em como o futuro da tecnologia poderia afetar negativamnete o meio ambiente...</p> 
                
                 <h2>Cuide do meio ambiente, faça o descarte correto de lixo eletrônico.</h2>
                 <h3>----Ecotronics</h3>
                 <button class="common-btn">Começar Agora</button>
               </div>
              </div>
             </section>

              <section id="contact">
                <div class="container-contact-row">
                    <div class="contact-left-col">
                    <h1> Se você precisa de um aparelho ligado a tecnologia, inscreva-se!</h1>
                    <form>
                      <input type="text" placeholder="Nome">
                      <input type="email" placeholder="E-Mail">
                      <input type="password" placeholder="Senha">
                      <div class="btn-box">
                        <button class="common-btn">Criar Conta</button>
                        <button class="common-btn">Entrar</button>
                      </div>
                    </form>
                    </div>
                    <div class="contact-right-col">
                      <img src="WhatsApp Image 2023-06-26 at 03.05.00.jpeg">
                    </div>
                </div>
              </section>



              <section id="footer">
                <div class="container-footer-row">
                  <hr>
                  <div class="footer-left-col">
                 <div class="footer-links">
                  <div class="link-title">
    <h4>xxxx</h4>
    <small>xxx xxxx</small>
    <small>xxxx xxxxx</small> <br>
    </div>
              <div class="link-title">
    <h4>xxxx</h4>
    <small>xxx xxxx</small>
    <small>xxxx xxxxx</small> <br>
      </div>
           <div class="link-title">
    <h4>xxxx</h4>
    <small>xxx xxxx</small>
    <small>xxxx xxxxx</small> <br>
        </div>
       </div>
                  </div>
                  <div class="footer-right-col">
         <div class="footer-info">
           <div class="copyright-text">
            <small>Support@HUB.com</small><br>
            <small>Copyright 2023 HUB</small>

             </div>
          <div class="footer-logo">
     <h1>HUB</h1>
        </div>
         </div>
                  </div>
                </div>
              </section>
            
              <div class="social-icons">
                <img src="facebook.png">
                <img src="instagram.png">
                <img src="twitter.png">
                <img src="linkedin.png">
              </div>
          

       <script>
         var menuBtn = document.getElementById("menuBtn");
         var sidenav = document.getElementById("sidenav");
         
         sidenav.style.right = "-250px";
         menuBtn.onclick = function(){
          if(sidenav.style.right == "-250px"){
            sidenav.style.right = "0";
          }
          else{
            sidenav.style.right = "-250px";
          }
         }
       </script>
</body>
</html>
