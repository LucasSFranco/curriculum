<template>
  <header>
    <div class="avatar container">
      <div class="shadow"></div>
      <img src="/assets/avatar-3.jpg" alt="" />
    </div>
    <div class="wrapper">
      <h1>
        <em>L</em>ucas <em>S</em>urdi <em>F</em>ranco
      </h1>
      <h6>
        surdifranco@gmail.com • <small>(49) 98896-8998</small>
      </h6>
    </div>
  </header>

  <div class="bio container">
    <div class="content">
      <div class="shadow"></div>
      Sou Lucas, possuo 19 anos, tenho formação de técnico em informativa pelo Instituto Federal de
      Santa Catarina e experiência com desenvolvimento web, sobretudo front-end. Gosto dessa área
      e sou curioso para aprender novas técnicas e tecnologias. Também possuo um pouco de
      experiência em edição de vídeos e animação em <i>After Effects</i>.
    </div>
    <div class="content techs">
      <h3> Tecnologias </h3>
      <b>HTML</b>
      <i></i> <b>CSS</b>
      <i></i> <b>JavaScript</b>
      <i></i> <b>Imba</b>
      <i></i> <b>Firebase</b>
      <i></i> <b>React.js</b>
      <i></i> <b>SQL</b>
      <i></i> <b>Dexie.js</b>
      <i></i> <b>Styled Components</b>
      <i></i> <b>SCSS</b>
      <i></i> <b>Redux</b>
      <i></i> <b>Git</b>
      <i></i> <b>Bootstrap</b>
      <i></i> <b>Vue.js</b>
      <i></i> <b>PHP</b>
      <i></i> <b>Cypress</b>
      <i></i> <b>Vuex</b>
      <i></i> <b>Typescript</b>
      <i></i> <b>Webpack</b>
    </div>
  </div>

  <div class="title">
    <h1><em>P</em>ortfolio</h1>
    <h6>
      <small>Clique no ícone <i class="fab fa-github"></i> para acessar os repositórios</small>
    </h6>
  </div>

  <div class="row">
    <div class="col">
      <div class="card container">
        <a href="https://github.com/LucasSFranco/imba-chess" class="icon">
          <i class="fab fa-github"></i>
        </a>
        <div class="shadow"></div>
        <h3>Jogo de xadrez</h3>
        <div class="content">
          Jogo de xadrez desenvolvido em <b>Imba</b>. Inclui várias das funcionalidades e regras
          existentes em um jogo de xadrez real.
        </div>
      </div>
      <div class="card container">
        <a href="https://github.com/LucasSFranco/Churrastop" class="icon">
          <i class="fab fa-github"></i>
        </a>
        <div class="shadow"></div>
        <h3>Plataforma de academia</h3>
        <div class="content">
          Plataforma para academia com venda de produtos desenvolvida inteiramente com
          <b>HTML</b>,
          <b>CSS</b>,
          <b>JavaScript</b> e
          <b>Bootstrap</b>. Contém três níveis de acesso:
          <ul>
            <li>
              <strong>administrador:</strong>
              pode listar, excluir e editar funcionários, clientes e produtos, atualizar o
              histórico de evolução dos clientes e ver o relatório de vendas;
            </li>
            <li>
              <strong>funcionário:</strong>
              pode realizar as mesmas ações que o administrador com relação aos clientes; e,
            </li>
            <li>
              <strong>cliente:</strong>
              pode visualizar os produtos disponíveis, as notificações e seu histórico de evolução.
            </li>
          </ul>
        </div>
      </div>
      <div class="card container">
        <a href="https://github.com/LucasSFranco/haka-website" class="icon">
          <i class="fab fa-github"></i>
        </a>
        <div class="shadow"></div>
        <h3>Website de portfólio</h3>
        <div class="content">
          Site de portfólio desenvolvido com
          <b>Imba</b> e
          <b>Firebase</b>. Inclui o cabeçalho e as seções de sobre, serviços, portfólio e contato.
          Também é responsivo e possui uma área administrativa para editar as categorias do
          portfólio e as imagens de cada categoria.
        </div>
      </div>
    </div>
    <div class="col">
      <div class="card container">
        <a href="https://github.com/LucasSFranco/php-ecommerce" class="icon">
          <i class="fab fa-github"></i>
        </a>
        <div class="shadow"></div>
        <h3>E-commerce</h3>
        <div class="content">
          Plataforma de vendas responsiva elaborada em
          <b>PHP</b>,
          <b>HTML</b>,
          <b>CSS</b> e
          <b>JavaScript</b>, utilizando um banco
          <b>MySQL</b>. Utiliza três níveis de acesso:
          <ul>
            <li>
              <strong>administrador:</strong>
              pode listar, adicionar, excluir e editar produtos e categorias de produtos;
            </li>
            <li>
              <strong>cliente:</strong>
              pode ver os produtos, adicioná-los ao carrinho de compras e finalizar a compra; e,
            </li>
            <li>
              <strong>visitante:</strong>
              pode se cadastrar, realizar login e ver os produtos.
            </li>
          </ul>
        </div>
      </div>
      <div class="card container">
        <a href="https://github.com/LucasSFranco/vue-task-app" class="icon">
          <i class="fab fa-github"></i>
        </a>
        <div class="shadow"></div>
        <h3>Aplicativo de tarefas</h3>
        <div class="content">
          Feito com
          <b>Vue.js</b> e
          <b>Dexie.js</b>. Também inclui
          <b>Vuex</b> como gerenciador de estado e
          <b>Cypress</b> como biblioteca de testes. Algumas das funcionalidades são:
          <ul>
            <li>
              formulário de adição de tarefas colapsável;
            </li>
            <li>
              atalhos nas teclas ENTER e ESC para abrir e fechar o formulário de adição;
            </li>
            <li>
              <i>skeleton loading</i>;
            </li>
            <li>
              botão para excluir tarefa;
            </li>
            <li>
              botão para alterar o estado da tarefa: concluída ou pendente; e,
            </li>
            <li>
              <i>textarea</i> autoexpansível.
            </li>
          </ul>
        </div>
      </div>
      <div class="more container">
        <a href="https://github.com/LucasSFranco" class="icon">
          <i class="fab fa-github"></i>
        </a>
        <div class="shadow"></div>
        <div class="content">
          Veja outros repositórios no meu
          <a href="https://github.com/LucasSFranco">Github</a>.
        </div>
      </div>
    </div>
  </div>

</template>

<script>
export default {
  name: 'App',
};
</script>

<style lang="sass">
  $gray-50: #fafafa
  $gray-100: #f4f4f5
  $gray-200: #e4e4e7
  $gray-300: #d4d4d8
  $gray-400: #a1a1aa
  $gray-500: #71717a
  $gray-600: #52525b
  $gray-700: #3f3f46
  $gray-800: #27272a
  $gray-900: #18181b

  $red-50: #fef2f2
  $red-100: #fee2e2
  $red-200: #fecaca
  $red-300: #fca5a5
  $red-400: #f87171
  $red-500: #ef4444
  $red-600: #dc2626
  $red-700: #b91c1c
  $red-800: #991b1b
  $red-900: #7f1d1d

  $blue-50: #eff6ff
  $blue-100: #dbeafe
  $blue-200: #bfdbfe
  $blue-300: #93c5fd
  $blue-400: #60a5fa
  $blue-500: #3b82f6
  $blue-600: #2563eb
  $blue-700: #1d4ed8
  $blue-800: #1e40af
  $blue-900: #1e3a8a

  $green-50: #f0fdf4
  $green-100: #dcfce7
  $green-200: #bbf7d0
  $green-300: #86efac
  $green-400: #4ade80
  $green-500: #22c55e
  $green-600: #16a34a
  $green-700: #15803d
  $green-800: #166534
  $green-900: #14532d

  $purple-50: #f5f3ff
  $purple-100: #ede9fe
  $purple-200: #ddd6fe
  $purple-300: #c4b5fd
  $purple-400: #a78bfa
  $purple-500: #8b5cf6
  $purple-600: #7c3aed
  $purple-700: #6d28d9
  $purple-800: #5b21b6
  $purple-900: #4c1d95

  body
    width: 210mm
    height: 297mm

    display: flex
    flex-direction: column

    background: $gray-900
    padding: 24px

  *
    padding: 0
    margin: 0

    box-sizing: border-box
    list-style: none
    text-decoration: none

    font-family: "Poppins", sans-serif

  .container
    position: relative

    background: $gray-700

    &::after, &::before
      content: ''

      width: -1px
      height: -1px

      position: absolute

    &::before
      top: -1px
      left: -1px

      border-top: 11px solid $gray-900
      border-right: 31px solid transparent

    &::after
      bottom: -1px
      right: -1px

      border-bottom: 11px solid $purple-900
      border-left: 31px solid transparent

    .shadow
      width: 100%
      height: 100%

      position: absolute
      top: 8px
      left: 8px

      background: $purple-900
      z-index: -1

      &::after
        content: ''

        position: absolute
        bottom: -1px
        right: -1px

        border-bottom: 11px solid $gray-900
        border-left: 31px solid transparent

  header
    display: flex
    align-items: center

    .avatar
      flex-shrink: 0

      width: 100px
      height: 100px

      img
        width: 100%

    .wrapper
      flex-grow: 1
      padding: 0 32px

  .title
    line-height: 1
    margin: 16px 0
    text-align: center

    h6
      small
        font-size: 10px

  h1
    color: $purple-700
    font-size: 24px
    font-weight: 600
    text-transform: uppercase

    em
      font-size: 32px
      font-style: normal
      font-weight: 500

  h6
    color: $purple-300
    font-size: 14px
    font-weight: 300

    small
      font-size: 12px

  .bio
    display: flex

    margin: 24px 0 0

    .techs
      width: 240px

      text-align: left

      background: $gray-800
      flex-shrink: 0

      h3
        font-size: 12px
        padding: 0 0 4px 0
        text-align: left

      b
        font-size: 10px

  .row
    display: flex

    .col
      width: 50%
      margin: 0 12px 0 0

    .col + .col
      margin: 0 0 0 12px

  .card
    & + &
      margin-top: 24px

    .content
      padding-bottom: 24px

    .icon
      position: absolute
      bottom: -8px
      right: -8px

      width: 64px
      height: 40px

      display: flex
      justify-content: center
      align-items: center

      background: $purple-900
      z-index: 1

      i
        font-size: 24px
        color: white

      &::after, &::before
        content: ''

        position: absolute

      &::before
        top: -1px
        left: -1px

        border-top: 11px solid $gray-700
        border-right: 31px solid transparent

      &::after
        bottom: -1px
        right: -1px

        border-bottom: 11px solid $gray-900
        border-left: 31px solid transparent

  h3
    background: $gray-800
    color: white
    font-size: 14px
    font-weight: 500
    padding: 8px 0
    text-align: center
    text-transform: uppercase

  .content
    font-size: 14px
    font-weight: 300
    text-align: justify
    color: $gray-50
    padding: 16px

    b
      background: $purple-500
      border-radius: 3px
      color: white
      font-size: 12px
      font-weight: 400
      padding: 0 4px
      white-space: nowrap

    ul
      margin: 8px 0

      li
        color: $gray-50
        font-size: 12px
        font-weight: 300
        text-align: justify
        text-indent: 8px

        &::before
          content: "•"
          position: absolute
          left: 8px
          color: $purple-500

        strong
          color: white
          font-weight: 500

  .more
    width: calc(100% - 40px)

    margin-top: 32px

    .icon
      width: 48px
      height: 44px

      display: flex
      align-items: center
      justify-content: center

      color: white
      position: absolute
      top: 8px
      right: -48px

      i
        font-size: 28px

    .shadow
      width: calc(100% + 40px)

    .content
      padding-bottom: 16px

      a
        color: $purple-400
        text-decoration: underline
        text-decoration-thickness: 2px

  .light
    background: $gray-50

    .container
      background: $gray-200

      &::before
        border-top: 11px solid $gray-50

      &::after
        border-bottom: 11px solid $blue-400

      .shadow
        background: $blue-400

        &::after
          border-bottom: 11px solid $gray-50

    header
      .wrapper
        h1
          color: $blue-400

        h6
          color: $gray-400

    .bio
      .techs
        background: $gray-300

    .card
      .icon
        background: $blue-400

        i
          color: white

        &::before
          border-top: 11px solid $gray-200

        &::after
          border-bottom: 11px solid $gray-50

    h3
      background: $gray-300
      color: $gray-800

    .content
      color: $gray-800

      b
        background: $blue-400
        color: white

      ul
        li
          color: $gray-800

          &::before
            color: $blue-500

          strong
            color: $gray-900

    .more
      .icon
        color: white

      .content
        a
          color: $blue-400

</style>
