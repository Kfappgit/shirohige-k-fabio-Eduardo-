1<!DOCTYPE html>
<html lang="pt-br" dir="ltr">
    <head>
        <meta charset="UTF-8">
        <title></title>
        <style>

            body {
            font-family: Gotham,Arial,Helvetica Neue,Helvetica,sans-serif;
            font-weight: 300;
            font-size: 14px;
            color: #4a4a4a;
            -webkit-font-smoothing: antialiased;
            -webkit-overflow-scrolling: touch;
            -webkit-tap-highlight-color: transparent;
            overflow-x: hidden;
        }
        html {
            line-height: 1.15;
            -webkit-text-size-adjust: 100%;
        }

                        h1{
                            text-align: center;
                            font-size: 50px;
                            margin: 0px;
                            padding: 0;
                            margin-top: 10px;
                            margin: 0;
                            }

                            .main{
                            text-align: center;
                            width: 800px;
                            height: 650px;
                            background-color: yellowgreen;
                            top:300px;
                            vertical-align: middle;
                            }

                            div.main div{
                                position: relative;
                                margin: 3px 0;
                                text-align: center;
                                right: 0;
                                left: 0;

                                }
                                .form-group{
                    margin-bottom:1em;
                    transition:all .3s;

                }
                .form-label{
                    font-size:2em;
                    color:black;
                    opacity: 1;
                    display: block;
                    transform: translateY(-1.25em);
                    transform-origin:0 0 ;
                    transition: all.3;
                    }
                 .form-control{
                    margin-top: 10px;
                    background-color: rgba(0,0,0,.02);
                    border-radius: 0px;
                    border-color: #ccc;
                    width: 100%;
                    transition: all.5s;
                }
                .form-control:focus{
                    box-shadow: none;
                    outline: none;
                    border-color: black;
                }
                .form-group:focus-within{
                    transform: scale(1.5,1.5);
                }
                .form-control:focus + .form-label,
                .form-control:not(:placeholder-shown) + .form-label
                {
                    transform: translateY(-2.5em) scale(.4);
                }
                .form-group:focus-within{
                    transform: scale(1.05,1.05);
                }


        button {
        background-color: transparent;
        width:220px;
        height: 60px;
        display: inline-block;
        text-align: center;
        text-transform: uppercase;
        text-decoration: none;
        line-height: 56px;
        display: inline-block;
        font-size: 20px;
        font-weight: bold;
        border:2px solid;
        box-sizing: border-box;
        border-radius: 50%;
        outline: none;
        }
        .sidebar{
            height: 271px;
         width: 300px;
         display: block;
        }
        .sidebar img{
         height: 324px;
         width: 700px;
         position: relative;

        }
        section{
        margin: 5px 5px 5px 5px;
        height: 567px ;
        width:100%;
        display: flex;
        }
        input[type=text]{
        width: 70%;
        padding: 10px;
        border: 2px solid white;
        border-radius: 50px;
        font-size: 20px;
        font-weight: 40;
        }
        input[type="text"]:focus{
          outline: none;
        }
        .grid{
        display: grid;
        grid-template-columns: 1fr 200px;
        grid-gap: 20px;
        max-width: 10px;
        padding: 10px;
        margin:0;
        }
        .sidebar > div{
        margin-bottom: 5px;
        margin-left: 70%;
        }
        @media(max-width:600px){
        .grid{
        grid-template-columns: 1fr;
        }
        .sidebar{
        display: relative ;
        }
        }
        .card-deck{
            margin: 100px;
            display: grid;
            gap: 20px;
            grid-template-columns: repeat(3,5fr);
            grid-template-areas:"imagem" "text"  ;
            padding: 30px;
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;



        }
        .card-text{
            grid-area: text;
            margin: 25px;

        }

        .card{

          border-radius:18px;
            box-shadow: 5px 5px 5px rgba(0,0,0,0.9);
            text-align: center;


        }
        .card-img-top{
            grid-area: image;
            border-top-left-radius:15px;
            border-top-right-radius: 15px;
            background-size:cover;
            width: 100%;
            display: block;
        }
        .card-title{
          text-align: center;
        }
        .card-body{
            line-height: 1.5;
          font-size: 0.9em;
          padding: 15px;

        }
        .landing-application[data-v-0a922ae7] {
                    position: relative;
                    margin-top: 90px;
                    }
        .landing-application__bg[data-v-0a922ae7] {
            background-image: linear-gradient(90deg,#fff,yellowgreen);
            width: 100%;
            height: 400px;
            position: absolute;
            top: 40px;
        }

        div{display:block;}
        @media (max-width: 1024px){
        .landing-application__bg[data-v-0a922ae7] {
            height: 230px;
            top: 15px;
        }}
        .landing-application__bg[data-v-0a922ae7] {
            background-image: linear-gradient(90deg,#fff,yellowgreen);
            width: 100%;
            height: 400px;
            position: absolute;
            top: 40px;
        }
        .landing-application-container[data-v-0a922ae7] {
            flex-direction: row;
            display: flex;
            justify-content: center;
            flex-wrap: nowrap;
        }
        @media (max-width: 1140px){
            .container {
            padding-left: 10px!important;
            padding-right: 10px!important;
        }
        }

        .container {
            margin: 0 auto;
            max-width: 1120px;
            padding: 0;
            position: relative;
            width: 100%;
            box-sizing: border-box;
        }
        @media (max-width: 1024px){
        .landing-application-container__phone[data-v-0a922ae7] {
            max-height: 270px;
            width: auto;
        }
        }
        .landing-application-container__phone[data-v-0a922ae7] {
            height: 100%;
            max-height: 500px;
            width: auto;
        }
        img {
            border-style: none;
        }
        @media (max-width: 1024px){
            .landing-application-container__description .title[data-v-0a922ae7] {
            margin-top: 55px;
            font-size: 24px;
            line-height: 30px;
        }
        }

        .landing-application-container__description .title[data-v-0a922ae7] {
            font-size: 40px;
            margin: 110px 0 0;
        }
        .title {
            font-size: 36px;
            line-height: 50px;
            color: #000;
            font-weight: 600;
        }
        folha de estilos de agente de usuário
        h2 {
            display: block;
            font-size: 1.5em;
            margin-block-start: 0.83em;
            margin-block-end: 0.83em;
            margin-inline-start: 0px;
            margin-inline-end: 0px;
            font-weight: bold;
        }
        @media (max-width: 1024px){
        .landing-application-container__description .title__line[data-v-0a922ae7]:first-child {
            margin-left: -35px;
        }
        }
        .landing-application-container__description .title__line[data-v-0a922ae7]:first-child {
            margin-left: -60px;
        }
        .landing-application-container__description .title__line[data-v-0a922ae7] {
            display: block;
        }
        @media (max-width: 1024px){
        .landing-application-container__description .title[data-v-0a922ae7] {
            margin-top: 55px;
            font-size: 24px;
            line-height: 30px;
        }
        }
        .landing-application-container__description .title[data-v-0a922ae7] {
            font-size: 40px;
            margin: 110px 0 0;
        }
        .title {
            font-size: 36px;
            line-height: 50px;
            color: #000;
            font-weight: 600;
        }
       
        h2 {
            font-size: 1.5em;
            font-weight: bold;
        }
        .landing-application-container__description .title__line[data-v-0a922ae7] {
            display: block;
        }
        .landing-application-container__description .title__brand[data-v-0a922ae7] {
            color: #2abb9b;
        }
        @media (max-width: 1024px){
        .landing-application-container__description .description[data-v-0a922ae7] {
            font-size: 14px;

            line-height: 20px;
        }
        }
        .landing-application-container__description .description[data-v-0a922ae7] {
            line-height: 1.44;
            font-size: 18px;
            margin: 18px 0 0;
            padding-left: 50px;
        }

      
        p {
            display: block;
            margin-block-start: 1em;
            margin-block-end: 1em;
            margin-inline-start: 0px;
            margin-inline-end: 0px;
        }
        .landing-corporate[data-v-abe475c0] {
            padding: 0;
        }
        @media (max-width: 1140px){
        .container {
            padding-left: 10px!important;
            padding-right: 10px!important;
        }
        }
        .container {
            margin: 0 auto;
            max-width: 1120px;
            padding: 0;
            position: relative;
            width: 100%;
            box-sizing: border-box;
        }
        @media (max-width: 1024px){
        .landing-corporate[data-v-abe475c0] .title {
            text-align: center;
        }
        }
        .landing-corporate[data-v-abe475c0] .title {
            line-height: 1.2em;
            margin-bottom: 5px;
        }
        .title {
            font-size: 36px;
            line-height: 50px;
            color: #000;
            font-weight: 600;
        }
        .landing-corporate[data-v-abe475c0] >.collection {
            justify-content: center;
        }
        .collection {
            padding: 10px 0;
            flex-wrap: wrap;
        }
        .cols {
            display: flex;
            flex-wrap: wrap;
            margin-left: -.75%;
            margin-right: -.75%;
        }
        @media (max-width: 1024px){
        .landing-corporate[data-v-abe475c0] .collection-item--with-button {
            width: 80%;
        }
        }

        .collection-item--with-button[data-v-4f722d34] {
            display: flex;
            flex-direction: column;
            justify-content: space-between;
        }
        @media (max-width: 1024px){
        .col:not(.col--preserve-mobile) {
            width: 47.5%;
        }
        }
        .col.one-third {
            width: 30.83333%;
            flex: none;
        }
        .collection-item {
            border-radius: 10px;
            box-shadow: 0 2px 20px 0 rgba(0,0,0,.1);
            text-decoration: none;
            overflow: hidden;
            margin-bottom: 40px;
            transition: .3s;
            min-width: 260px;
        }
        .col {
            margin: 1.25%;
            box-sizing: border-box;
        }
        @media (max-width: 1024px){
        .collection-item--with-button .card-image[data-v-4f722d34] {
            height: 350px;
        }
        }
        .collection-item--with-button .card-image[data-v-4f722d34] {
            height: 270px;
        }
        .collection-item .card-image, .collection-item .card-image>img {
            width: 100%;
            height: 168px;
            -o-object-fit: cover;
            object-fit: cover;
        }
        @media (max-width: 1024px){
        .landing-corporate[data-v-abe475c0] .collection-item--with-button .card-content {
            text-align: center;
        }
        }
        .collection-item--with-button .card-content[data-v-4f722d34] {
            flex: 1;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            padding: 24px 24px 28px;
        }
        .collection-item .card-content {
            padding: 20px;
        }
        @media (max-width: 1024px){
        .landing-corporate[data-v-abe475c0] .collection-item--with-button .card-content {
            text-align: center;
        }
        }
        .collection-item--with-button .card-content[data-v-4f722d34] {
            flex: 1;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            padding: 24px 24px 28px;
        }
        .collection-item .card-content {
            padding: 20px;
        }
        @media (max-width: 1024px){
        .landing-corporate[data-v-abe475c0] .collection-item--with-button {
            width: 80%;
        }
        }
        .collection-item--with-button[data-v-4f722d34] {
            display: flex;
            flex-direction: column;
            justify-content: space-between;
        }
        @media (max-width: 1024px){
        .col:not(.col--preserve-mobile) {
            width: 47.5%;
        }
        }
        .col.one-third {
            width: 30.83333%;
            flex: none;
        }
        .collection-item {
            border-radius: 10px;
            box-shadow: 0 2px 20px 0 rgba(0,0,0,.1);
            text-decoration: none;
            overflow: hidden;
            margin-bottom: 40px;
            transition: .3s;
            min-width: 260px;
        }
        .col {
            margin: 1.25%;
            box-sizing: border-box;
        }
        @media (max-width: 1024px){
        .landing-corporate[data-v-abe475c0] .collection-item--with-button .card-content {
            text-align: center;
        }
        }
        @media (max-width: 1024px){
        .landing-corporate[data-v-abe475c0] .collection-item--with-button .card-content .button {
            display: block;
            margin: 0 auto 10px;
        }
        }
        .collection-item--with-button .card-content .button[data-v-4f722d34] {
            display: block;
            width: 100%;
            box-sizing: border-box;
            white-space: nowrap;
        }
        .button.md {
            padding: 16px 28px;
        }
        .button {
            font-weight: 700;
            text-decoration: none;
            padding: 20px 60px;
            min-width: 120px;
            color: #fff;
            background-color: #2abb9b;
            font-size: 18px;
            border-radius: 100px;
            border: none;
            text-align: center;
            cursor: pointer;
            outline: none;
            box-shadow: 0 3px 5px 0 rgba(0,0,0,.1);
            -webkit-backdrop-filter: blur(10px);
            backdrop-filter: blur(10px);
            max-width: 340px;
            margin: 0 auto;
            box-sizing: border-box;
        }
        body a {
            -webkit-tap-highlight-color: deepskyblue;
        }
        a {
            background-color: transparent;
        }

        folha de estilos de agente de usuário
        a:-webkit-any-link {
            color: -webkit-link;
            cursor: pointer;
            text-decoration: underline;
        }
        .site-footer
{
  background-color:#26272b;
  padding:45px 0 20px;
  font-size:15px;
  line-height:24px;
  color:#737373;
  height: 100vh;
  width: 100vw;
}
.site-footer hr
{
  border-top-color:#bbb;
  opacity:0.5
}
.site-footer hr.small
{
  margin:20px 0
}
.site-footer h6
{
  color:#fff;
  font-size:16px;
  text-transform:uppercase;
  margin-top:5px;
  letter-spacing:2px
}
.site-footer a
{
  color:#737373;
}
.site-footer a:hover
{
  color:#3366cc;
  text-decoration:none;
}
.footer-links
{
  padding-left:0;
  list-style:none
}
.footer-links li
{
  display:block
}
.footer-links a
{
  color:#737373
}
.footer-links a:active,.footer-links a:focus,.footer-links a:hover
{
  color:#3366cc;
  text-decoration:none;
}
.footer-links.inline li
{
  display:inline-block
}
.site-footer .social-icons
{
  text-align:right
}
.site-footer .social-icons a
{
  width:40px;
  height:40px;
  line-height:40px;
  margin-left:6px;
  margin-right:0;
  border-radius:100%;
  background-color:#33353d
}
.copyright-text
{
  margin:0
}
@media (max-width:991px)
{
  .site-footer [class^=col-]
  {
    margin-bottom:30px
  }
}
@media (max-width:767px)
{
  .site-footer
  {
    padding-bottom:0
  }
  .site-footer .copyright-text,.site-footer .social-icons
  {
    text-align:center
  }
}
.social-icons
{
  padding-left:0;
  margin-bottom:0;
  list-style:none
}
.social-icons li
{
  display:inline-block;
  margin-bottom:4px
}
.social-icons li.title
{
  margin-right:15px;
  text-transform:uppercase;
  color:#96a2b2;
  font-weight:700;
  font-size:13px
}
.social-icons a{
  background-color:#eceeef;
  color:#818a91;
  font-size:16px;
  display:inline-block;
  line-height:44px;
  width:44px;
  height:44px;
  text-align:center;
  margin-right:8px;
  border-radius:100%;
  -webkit-transition:all .2s linear;
  -o-transition:all .2s linear;
  transition:all .2s linear
}
.social-icons a:active,.social-icons a:focus,.social-icons a:hover
{
  color:#fff;
  background-color:#29aafe
}
.social-icons.size-sm a
{
  line-height:34px;
  height:34px;
  width:34px;
  font-size:14px
}
.social-icons a.facebook:hover
{
  background-color:#3b5998
}
.social-icons a.twitter:hover
{
  background-color:#00aced
}
.social-icons a.linkedin:hover
{
  background-color:#007bb6
}
.social-icons a.dribbble:hover
{
  background-color:#ea4c89
}
@media (max-width:767px)
{
  .social-icons li.title
  {
    display:block;
    margin-right:0;
    font-weight:600
  }
}
     

</style>
    </head>

        <body>
            <section>
                <div class="main" id="app" @submit.prevent="submit">
                  <h1>Email</h1>
                  <div class="form-group" :class="{ 'form-group--error': $v.name.$error }">
                    <input class="form-control"  placeholder="Email" type="text" v-model.trim="$v.name.$model"/>
                    <label class="form-label"></label>
                  </div>
                  <div class="form-group" :class="{ 'form-group--error': $v.prop.$error }">
                   <input class="form-control" placeholder="Proprietario"type="text" v-model.trim="$v.prop.$model"/>
                    <label class="form-label"></label>
                  </div>
                  <div class="form-group" :class="{ 'form-group--error': $v.email.$error }">
                    <input class="form-control" placeholder="E-mail"type="text" v-model.trim="$v.email.$model"/>
                    <label class="form-label"></label>
                  </div>
                  <div class="error" v-if="!$v.name.required">Name is required</div>
                  <div class="error" v-if="!$v.email.required">Email is required</div>
                  <div class="error" v-if="!$v.prop.required">Proprietario is required</div>
                  <button class="button-submit" type="submit" :disabled="submitStatus === 'PENDING'">Submit!</button>
                  <p class="typo__p" v-if="submitStatus === 'OK'">Thanks for your submission!</p>
                  <p class="typo__p" v-if="submitStatus === 'ERROR'">Please fill the form correctly.</p>
                  <p class="typo__p" v-if="submitStatus === 'PENDING'">Sending...</p>

                </div>
                <div class="sidebar">
                    <img src="C:\Users\fabio\OneDrive\program past\Imagens\baloes.jpeg"align:left >
                    <img src="C:\Users\fabio\OneDrive\program past\Imagens\baloes.jpeg"align:left >
                </div>
            </section>
            <div data-v-0a922ae7="" class="landing-application">
                <div data-v-0a922ae7="" class="landing-application__bg">
                </div>
                 <div data-v-0a922ae7="" class="container landing-application-container">
                     <img data-v-0a922ae7="" src="https://res.cloudinary.com/glovoapp/image/fetch//w_500,h_466,c_fit,f_auto,q_auto/https://glovoapp.com/images/landing/phone_courier_promo.png" alt="Glovo App" class="column landing-application-container__phone">
                     <div data-v-0a922ae7="" class="column landing-application-container__description">
                         <h2 data-v-0a922ae7="" class="title title__install-app">
                             <span data-v-0a922ae7="" class="title__line">Siga suas entregas</span>
                             <span data-v-0a922ae7="" class="title__line">
                com o
                <span data-v-0a922ae7="" class="title__brand">iKaza App</span>
            </span>
        </h2>
        <p data-v-0a922ae7="" class="description">
            <span data-v-0a922ae7="" class="description__line">
                Veja o andamento de suas entregas
              </span>
              <span data-v-0a922ae7="" class="description__line">
                em tempo real e peça de qualquer lugar
              </span>
            </p>
             <div data-v-0a922ae7="" class="buttons">
                <a data-v-0a922ae7="" href="https://app.adjust.com/xle4el" class="column">
                    <img data-v-0a922ae7="" src="https://res.cloudinary.com/glovoapp/image/fetch///https://glovoapp.com/images/app_store/download-button.svg" alt="App Store" class="store-icon"></a> <a data-v-0a922ae7="" href="https://app.adjust.com/ule61n?redirect=http%3A%2F%2Fplay.google.com/store/apps/details?id=com.glovo&amp;hl=es" class="column"><img data-v-0a922ae7="" src="https://res.cloudinary.com/glovoapp/image/fetch///https://glovoapp.com/images/google_play/download-button.svg" alt="Google play" class="store-icon">
                    </a>
                </div>
            </div>
        </div>
    </div>
    <div data-v-abe475c0="" class="landing-corporate container">
        <div data-v-abe475c0="" class="title">Estamos construindo a Glovo juntos!</div>
        <div data-v-abe475c0="" class="collection cols">
            <div data-v-4f722d34="" data-test-id="collection-item" class="collection-item collection-item--with-button col one-third" full-width-mobile="true">
                <img data-v-4f722d34="" src="C:\Users\fabio\OneDrive\program past\Imagens\Vaga-para-Entregador-em-Teresina.jpg" alt="Entregadores" class="card-image card-image--top">
                 <div data-v-4f722d34="" class="card-content">
                     <div data-v-4f722d34="">
                         <div data-v-4f722d34="" class="title">Entregadores</div>
                         <div data-v-4f722d34="" class="subtitle">
        Apenas nas horas que você quiser
      </div> <div data-v-4f722d34="" class="description">
        Seja seu próprio chefe. Faça seu horário, tarifas competitivas e oportunidade de você conhecer sua cidade. Cadastre-se e esteja conectado ao App em menos de 24 horas.
      </div>
    </div>
     <a data-v-4f722d34="" target="_blank" rel="noopener" href="https://glovoapp.com/pt-br/glovers" class="button md">Faz entregas connosco</a>
    </div>
</div>
<div data-v-4f722d34="" data-test-id="collection-item" class="collection-item collection-item--with-button col one-third" full-width-mobile="true">
    <img data-v-4f722d34="" src="C:\Users\fabio\OneDrive\program past\Imagens\shop-icon.png" alt="Lojas parceiras" class="card-image card-image--center">
    <div data-v-4f722d34="" class="card-content">
        <div data-v-4f722d34="">
            <div data-v-4f722d34="" class="title">Lojas parceiras</div>
            <div data-v-4f722d34="" class="subtitle">
        Conheça seus novos clientes
      </div>
      <div data-v-4f722d34="" class="description">
        Turbine seus negócios tornando-se um parceiro e aproveitando as ferramentas, a tecnologia e a base de clientes que traz uma cidade inteira à sua porta.
      </div>
    </div>
    <a data-v-4f722d34="" href="https://cloud.partner.glovoapp.com/Partners" class="button md">Seja nosso parceiro</a>
</div>
</div>
<div data-v-4f722d34="" data-test-id="collection-item" class="collection-item collection-item--with-button col one-third" full-width-mobile="true">
    <img data-v-4f722d34="" src="C:\Users\fabio\OneDrive\program past\Imagens\transferir.png" alt="Carreiras" class="card-image card-image--center">
     <div data-v-4f722d34="" class="card-content">
         <div data-v-4f722d34="">
             <div data-v-4f722d34="" class="title">Carreiras</div>
              <div data-v-4f722d34="" class="subtitle">
        Desafios para combinar com o seu talento
      </div>
      <div data-v-4f722d34="" class="description">
        Estamos nos destacando num ambiente competitivo. É preciso objetividade, coração e muito trabalho em equipe. Pronto para entrar?
      </div>
    </div>
     <a data-v-4f722d34="" href="https://jobs.glovoapp.com" class="button md">Junta-te à equipa</a>
    </div>
</div>
</div>
</div>
<footer class="site-footer">
    <div class="container">
      <div class="row">
        <div class="col-sm-12 col-md-6">
          <h6>About</h6>
          <p class="text-justify">Scanfcode.com <i>CODE WANTS TO BE SIMPLE </i> is an initiative  to help the upcoming programmers with the code. Scanfcode focuses on providing the most efficient code or snippets as the code wants to be simple. We will help programmers build up concepts in different programming languages that include C, C++, Java, HTML, CSS, Bootstrap, JavaScript, PHP, Android, SQL and Algorithm.</p>
        </div>

        <div class="col-xs-6 col-md-3">
          <h6>Categories</h6>
          <ul class="footer-links">
            <li><a href="http://scanfcode.com/category/c-language/">C</a></li>
            <li><a href="http://scanfcode.com/category/front-end-development/">UI Design</a></li>
            <li><a href="http://scanfcode.com/category/back-end-development/">PHP</a></li>
            <li><a href="http://scanfcode.com/category/java-programming-language/">Java</a></li>
            <li><a href="http://scanfcode.com/category/android/">Android</a></li>
            <li><a href="http://scanfcode.com/category/templates/">Templates</a></li>
          </ul>
        </div>

        <div class="col-xs-6 col-md-3">
          <h6>Quick Links</h6>
          <ul class="footer-links">
            <li><a href="http://scanfcode.com/about/">About Us</a></li>
            <li><a href="http://scanfcode.com/contact/">Contact Us</a></li>
            <li><a href="http://scanfcode.com/contribute-at-scanfcode/">Contribute</a></li>
            <li><a href="http://scanfcode.com/privacy-policy/">Privacy Policy</a></li>
            <li><a href="http://scanfcode.com/sitemap/">Sitemap</a></li>
          </ul>
        </div>
      </div>
      <hr>
    </div>
    <div class="container">
      <div class="row">
        <div class="col-md-8 col-sm-6 col-xs-12">
          <p class="copyright-text">Copyright &copy; 2017 All Rights Reserved by 
       <a href="#">Scanfcode</a>.
          </p>
        </div>

        <div class="col-md-4 col-sm-6 col-xs-12">
          <ul class="social-icons">
            <li><a class="facebook" href="#"><i class="fa fa-facebook"></i></a></li>
            <li><a class="twitter" href="#"><i class="fa fa-twitter"></i></a></li>
            <li><a class="dribbble" href="#"><i class="fa fa-dribbble"></i></a></li>
            <li><a class="linkedin" href="#"><i class="fa fa-linkedin"></i></a></li>   
          </ul>
        </div>
      </div>
    </div>
</footer>
            <script>

            </script>
        </body>
</html>
