<template>
  <main class="A4">
    <header class="flex items-center gap-8 mb-6">
      <AppCard>
        <div class="avatar" />
      </AppCard>
      <div class="flex-auto">
        <AppTitle title="Lucas Surdi Franco" />
        <AppSubtitle>
          lucassurdifranco@gmail.com • <small>(49) 98896-8998</small>
        </AppSubtitle>
      </div>
      <AppCard class="flex flex-col items-end font-light p-4">
        <a
          href="https://github.com/LucasSFranco"
          class="text-white text-xs flex items-center gap-2"
        >
          LucasSFranco
          <i class="text-lg fab fa-github" />
        </a>
        <a
          href="https://br.linkedin.com/in/lucas-surdi-franco-032143230/pt"
          class="text-white text-xs flex items-center gap-2"
        >
          Lucas Surdi Franco
          <i class="text-lg fab fa-linkedin" />
        </a>
      </AppCard>
    </header>

    <AppCard class="flex text-sm">
      <AppArticle
        :content="'Em 2016, conheci o universo da programação quando meu irmão me apresentou a uma plataforma de desafios de programação, esse foi o impulso que me direcionou a cursar o ensino médio integrado a um curso técnico de informática. Durante esse tempo, realizei projetos pessoais com foco no aprendizado. Após terminar meus estudos, no início de 2021, comecei a trabalhar como desenvolvedor na empresa em que estou atualmente. Meu ponto de partida foi o desenvolvimento frontend, hoje sou desenvolvedor fullstack e curioso por aprender novas tecnologias. Sou proativo, dedicado e prezo pela qualidade.'"
      />
      <div class="flex-none bg-zinc-800 w-64">
        <AppArticle
          :content="'### Tecnologias\n`JavaScript` `TypeScript` `HTML` `CSS` `SCSS` `Tailwind` `Stitches` `Styled Components` `Bootstrap` `React` `Vue.js` `Imba` `Redux` `Vuex` `Pinia` `Git` `PostgreSQL` `Oracle Database` `Firebase` `IndexedDB` `SQL` `PL/SQL` `Prisma` `Cypress` `Jest` `Node.js` `Socket.io` `Express` `PHP` `Figma` `Storybook` `Webpack` `Vite`'"
        />
      </div>
    </AppCard>

    <AppTitle
      class="text-center my-4"
      title="Formação Acadêmica"
    />

    <AppCard
      class="text-xs"
      title="Instituto Federal de Santa Catarina"
      subtitle="jan de 2017 - dez de 2020"
    >
      <AppArticle
        class="text-sm"
        :content="'Curso técnico integrado em Informática'"
      />
    </AppCard>

    <AppTitle
      class="text-center my-4"
      title="Experiência Profissional"
    />

    <AppCard
      class="text-xs"
      title="Compass UOL"
      subtitle="desenvolvedor pleno • abr de 2021 - momento"
    >
      <AppArticle
        :content="'A Compass UOL é uma empresa de tecnologia que oferece serviços e soluções de tecnologia para outras empresas, como comércios digitais, aplicativos mobile, modernização de aplicativos, etc. Assim, a empresa possui um sistema interno que contém a gestão de todos esses projetos, controles financeiros, inúmeros relatórios, programas e informações para funcionários e muitos outros recursos. No entanto, o sistema foi criado antes de 2000 estruturado em um banco de dados `Oracle`, portanto, contém muito código legado. Desde quando ingressei na empresa, fui alocado neste projeto, trabalhando para modernizá-lo e melhorá-lo.\n\n---\n\nAtualmente, o frontend está embutido no código `PL/SQL`. Estávamos utilizando jQuery inicialmente, porém concordamos em alterar para o `Vue.js`. Então, fui responsável por criar um repositório Vue.js com a ideia de separar o frontend e backend no futuro. O projeto inclui `Pinia`, `Vue Router`, `Typescript`, `SCSS`, `i18next`, `Cypress` e `Storybook`. Nesse projeto, criei todos os componentes da interface baseando-se nos estilos criados pelo designer e documentei-os usando o Storybook. Todos esses componentes foram, então, incorporados ao código PL/SQL em uma versão simplicada do projeto Vue.js, incluindo apenas o Pinia. Isso renovou completamento as interfaces do sistema, facilitou a implementação de novos módulos e permitiu a criação de novas funcionalidades.'"
      />
    </AppCard>
  </main>
  <main
    class="A4"
    style="margin-top: 1px"
  >
    <AppTitle
      class="text-center"
      title="Projetos"
      subtitle=""
    >
      <AppSubtitle class="text-center text-xs mb-4">
        <small>Clique no ícone <i class="fab fa-github" /> para acessar os repositórios</small>
      </AppSubtitle>
    </AppTitle>

    <div class="grid grid-cols-2 gap-6">
      <div class="flex flex-col gap-6">
        <AppCard
          class="text-xs"
          title="Aplicativo de Mensagens"
          href="https://www.figma.com/file/LG7zpm5vc2nCZ7mkRIQsHh/Chat-Application?node-id=2%3A2700"
          repository="https://github.com/LucasSFranco/chat-frontend"
        >
          <AppArticle
            :content="'Projeto em desenvolvimento que baseia-se em aplicativos como WhatsApp, Telegram e Discord. No backend, estão sendo criadas duas APIs `Node.js`: API REST para gerenciamento da autenticação utilizando JWTs; e, API Socket para comunicação em tempo real utilizando a biblioteca `Socket.io`. Ambas estão conectadas a um banco `PostgreSQL` utilizando a ORM `Prisma`. O frontend utiliza `React` como framework web, `Stitches` para a criação da estilização e a `Context API` nativa do React para gerenciar o estado da aplicação. Pretende-se fazer o deploy de tudo na `AWS` por meio de um pipeline automatizado criado com `Github Actions`, o qual deve garantir que está tudo funcionando ao rodar os testes em `Jest`, no backend, e em `Cypress`, no frontend.'"
          />
        </AppCard>
        <AppCard
          class="text-xs"
          title="Lista de Tarefas"
          href="https://angry-nobel-17e7b9.netlify.app/"
          repository="https://github.com/LucasSFranco/vue-task-app"
        >
          <AppArticle
            :content="'Um aplicativo de lista de tarefas criado usando `Vue.js` e `Dexie.js`. Também inclui `Vuex` como gerenciador de estado, `Sass` como pré-processador de CSS e testes de algumas funcionalidades utilizando `Cypress`. Algumas de suas características:\n- formulário de adição de tarefas colapsável;\n- teclas de atalho para abrir e fechar o formulário de adicionar tarefas (teclas ENTER e ESC);\n- skeleton loading;\n- botão para excluir tarefa;\n- botão para alterar o status da tarefa (concluída/pendente);\n- área de texto auto-expansível; e,\n- um design elegante, baseado no Discord.'"
          />
        </AppCard>
        <AppCard
          class="text-xs"
          title="Aplicativo de Agendamento"
          href="https://schedule-app-a70b5.web.app"
          repository="https://github.com/LucasSFranco/schedule-app"
        >
          <AppArticle
            :content="'Ferramenta desenvolvida em `Imba` para agendar o dia e registrar as atividades realizadas a cada hora. Consiste em adicionar as tarefas diárias a uma lista e, após concluí-las, adicionar o tempo em que cada tarefa foi realizada por meio de uma legenda colorida. Todos esses dados, então, são armazenados localmente no `IndexedDB`. Eu acreditava que realmente usaria a ferramenta nos meus estudos, mas faltou praticidade, então ficou de aprendizado.'"
          />
        </AppCard>
      </div>
      <div class="flex flex-col gap-6">
        <AppCard
          class="text-xs"
          title="Haka Website"
          href="https://haka-website.web.app"
          repository="https://github.com/LucasSFranco/haka-website"
        >
          <AppArticle
            :content="'Um site de portfólio animado desenvolvido para a empresa de publicidade dos meus pais utilizando `Imba` e `Firebase`. Inclui cabeçalho, rodapé e as seções “sobre”, “serviços”, “portfólio” e “contato”. Além disso, é responsivo e possui uma página de administrador na qual é possível alterar as categorias do portfólio e as imagens dos trabalhos de cada categoria.'"
          />
        </AppCard>
        <AppCard
          class="text-xs"
          title="Portal de Notícias"
          href="https://brave-engelbart-cb0aae.netlify.app"
          repository="https://github.com/LucasSFranco/react-exam"
        >
          <AppArticle
            :content="'O aplicativo é um portal de notícias construído igualmente em `React` e `Vue.js` para exibir notícias sobre dois tópicos (tecnologia e ciência), que são fornecidos pela API do The New York Times. Foi um teste de habilidade que fiz quando ingressei na Compass UOL. Informações detalhadas podem ser encontradas nos repositórios dos projetos.'"
          />
        </AppCard>
        <AppCard
          class="text-xs"
          title="E-commerce"
          href="https://drive.google.com/drive/folders/1XMB89zABOQ5cJ4vcyEGoVVhQ0kqDDk53?usp=sharing"
          repository="https://github.com/LucasSFranco/php-ecommerce"
        >
          <AppArticle
            :content="'Plataforma de vendas responsiva elaborada para um projeto escolar em `PHP`, `HTML`, `CSS` e `JavaScript` utilizando um banco `MySQL`. Utiliza três níveis de acesso:\n- __administrador__: pode listar, adicionar, excluir e editar produtos e categorias de produtos;\n- __cliente__: pode ver os produtos disponíveis na loja, adicioná-los ao carrinho de compras e finalizar a compra utilizando a API de desenvolvimento do PagSeguro;\n- __visitante__: pode se cadastrar, realizar login e ver os produtos disponíveis na loja.'"
          />
        </AppCard>
        <AppCard
          class="text-xs"
          title="Jogo de Xadrez"
          href="https://imba-chess.web.app"
          repository="https://github.com/LucasSFranco/imba-chess"
        >
          <AppArticle
            :content="'Jogo de Xadrez desenvolvido em `Imba`. Não está completo, mas já possui muitos recursos que um verdadeiro jogo de xadrez deve possuir. Foi muito divertido codificar e aprendi muito sobre frameworks de desenvolvimento web e sobre a própria lógica de programação.'"
          />
        </AppCard>
      </div>
    </div>
  </main>
</template>

<script>

import AppArticle from './components/AppArticle.vue';
import AppCard from './components/AppCard.vue';
import AppSubtitle from './components/AppSubtitle.vue';
import AppTitle from './components/AppTitle.vue';

export default {
  name: 'App',
  components: {
    AppArticle,
    AppCard,
    AppSubtitle,
    AppTitle,
  },
};

</script>

<style lang="sass">
  html
    background: var(--gray-900)

  .A4
    width: 210mm
    height: 297mm

    display: flex
    flex-direction: column

    padding: 24px
    z-index: -1

  *
    padding: 0
    margin: 0

    box-sizing: border-box
    list-style: none
    text-decoration: none

    font-family: "Poppins", sans-serif

  .avatar
    background: url("/assets/avatar.jpg")
    background-size: 100%

    width: 100px
    height: 100px

    img
      width: 100%

</style>
