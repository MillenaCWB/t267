<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Portfólio</title>
    <link rel="stylesheet" href="style.css" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Josefin+Sans:ital,wght@0,100..700;1,100..700&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap"
      rel="stylesheet"
    />
    <script src="script.js"></script>
  </head>
  <body>
    <header class="menu">
      <ul>
        <li><a href="#section01">Section 01</a></li>
        <li><a href="#section02">Section 02</a></li>
        <li><a href="#section03">Section 03</a></li>
        <li><a href="#section04">Section 04</a></li>
      </ul>
    </header>
    <main>
      <section id="section01">
        <div class="section01-left-div">
          <img
            src="../assets/images/imgTeste.webp"
            alt="Imagem teste"
            class="img-style-section01"
          />
        </div>
        <div class="section01-right-div">
          <h2 class="l01">Nome do cidadão</h2>
          <p class="p01">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis,
            accusantium modi, voluptatibus deleniti illo dignissimos id voluptas
            natus reiciendis maiores explicabo dolores quaerat architecto autem
            unde incidunt ipsa? Ipsam, error. Lorem ipsum dolor sit amet
            consectetur adipisicing elit. Corporis, accusantium modi,
            voluptatibus deleniti illo dignissimos id voluptas natus reiciendis
            maiores explicabo dolores quaerat architecto autem unde incidunt
            ipsa? Ipsam, error.
          </p>
        </div>
      </section>
      <section id="section02">
        <h2 class="tec-title">Tecnologias</h2>
        <div class="wrap-tecs">
          <div>
            <img
              width="100px"
              height="auto"
              src="../assets/images/html.png"
              alt=""
            />
            <br />
            <p>
              Lorem ipsum dolor sit amet, consectetur adipisicing elit.
              Blanditiis temporibus fugiat odio, dicta tempora, cumque nulla a,
              delectus est optio doloribus soluta sit culpa natus! Repellat,
              quae! Nam, optio et.
            </p>
          </div>
          <div>
            <img
              width="100px"
              height="auto"
              src="../assets/images/css-3.png"
              alt=""
            />
            <br />
            <p>
              Lorem ipsum dolor sit amet, consectetur adipisicing elit.
              Blanditiis temporibus fugiat odio, dicta tempora, cumque nulla a,
              delectus est optio doloribus soluta sit culpa natus! Repellat,
              quae! Nam, optio et.
            </p>
          </div>
          <div>
            <img
              width="100px"
              height="auto"
              src="../assets/images/js.png"
              alt=""
            />
            <br />
            <p>
              Lorem ipsum dolor sit amet, consectetur adipisicing elit.
              Blanditiis temporibus fugiat odio, dicta tempora, cumque nulla a,
              delectus est optio doloribus soluta sit culpa natus! Repellat,
              quae! Nam, optio et.
            </p>
          </div>
        </div>
      </section>
      <section id="section03">
        <h2>parte 03</h2>
      </section>
      <section id="section04">
        <div class="left-contact">
          <h2 class="heading-contact">Contato</h2>
          <div
            style="
              display: flex;
              flex-direction: column;
              gap: 0.5vh;
              position: relative;
            "
          >
            <label for="nome">Nome</label>
            <input type="text" id="nome" />
          </div>
          <div style="display: flex; flex-direction: column; gap: 0.5vh">
            <label for="mensagem">Mensagem</label>
            <input type="text" id="mensagem" />
          </div>
          <br />
          <button onclick="conferirMensagemWhatsApp()">
            Conferir Mensagem
          </button>
        </div>
        <div class="right-contact" id="rightDiv">
          <div>
            <p>Nome: <span id="confNome"></span></p>
            <br />
            <p class="text">Mensagem: <span id="confMsg"></span></p>
          </div>
          <button onclick="enviar()">ZAP</button>
        </div>
      </section>
      <footer>
        <a href="https://www.instagram.com/" target="_blank"
          ><p style="color: white">Instagram</p>
          <img
            width="40px"
            height="40px"
            src="../assets/images/instagram.png"
            alt="Instagram"
        /></a>
        <a href="https://www.facebook.com/" target="_blank"
          ><p style="color: white">Facebook</p>
          <img
            width="40px"
            height="40px"
            src="../assets/images/instagram.png"
            alt="Facebook"
        /></a>
        <a href="https://www.linkedin.com/in/andredev88/" target="_blank"
          ><p style="color: white">Linkedin</p>
          <img
            width="40px"
            height="40px"
            src="../assets/images/instagram.png"
            alt="Linkedin"
        /></a>
      </footer>
    </main>
  </body>
</html>
            </section>
            <section id="section4">
                <h2 class="heading-contact">contact</h2>
                <div class="left-contact">
                </div>
                <label for="nome"></label>
                <input type="text" id="nome" />
                </div>
                <div>
                    <label for="mensagem">mensagem</label>
                    <input type="text" id="mensagem" />
                </div>
                <button onclick="conferirMensagemwhatsApp()">
                conferir mensagem
            </button>
        </div>
                <div class="right-contact">
                </div>
                <p>nome:<span id="confNome"></span></p>
                <p>mensagem: <span id="confMsg"></span></p>
            </div>
            <button onclick="enviar()">ZAP</button>
            </div>
            </section>
        </main>
    </body>
</html>
