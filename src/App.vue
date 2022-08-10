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
        :content="'In 2016, I discovered the coding universe when my brother introduced me to a platform of programming challenges. It encouraged me to join a high school integrated with an IT vocational training course. During this time, I developed many personal projects focusing on learning. After finish my studies, at the beginning of 2021, I started to work as a developer at the company I am currently working for. I\'m a heavy frontend developer, because it was my starting point, but today I am fullstack, curious to learn new technologies and improve my skills. I am proactive, dedicated and like to face technical challenges.'"
      />
      <div class="flex-none bg-zinc-800 w-64">
        <AppArticle
          :content="'### Technologies\n`JavaScript` `TypeScript` `HTML` `CSS` `SCSS` `Tailwind` `Stitches` `Styled Components` `Bootstrap` `React` `Vue.js` `Imba` `Redux` `Vuex` `Pinia` `Git` `PostgreSQL` `Oracle Database` `Firebase` `IndexedDB` `SQL` `PL/SQL` `Prisma` `Cypress` `Jest` `Node.js` `Socket.io` `Express` `PHP` `Figma` `Storybook` `Webpack` `Vite`'"
        />
      </div>
    </AppCard>

    <AppTitle
      class="text-center my-4"
      title="Education"
    />

    <AppCard
      class="text-xs"
      title="Instituto Federal de Santa Catarina"
      subtitle="jan 2017 - dec 2020"
    >
      <AppArticle
        class="text-sm"
        :content="'Technical course in Information Technology'"
      />
    </AppCard>

    <AppTitle
      class="text-center my-4"
      title="Professional Experience"
    />

    <AppCard
      class="text-xs"
      title="Compass UOL"
      subtitle="apr 2021 - moment"
    >
      <AppArticle
        :content="'Compass UOL is a technology company that offers technology services and solutions to other companies, such as digital commerce, mobile applications, application modernization, etc. Thus, the company has a system to manage all these projects, administer the bills, provide information and contents to employees and many other resources. However, the system was created before 2000s structured on an `Oracle database`, so it contains a lot of legacy code. Since I joined the company, I was allocated to this project, working to modernize and improve it.\n\n---\n\nCurrently, the frontend is embedded in `PL/SQL` code. We were using jQuery initially, but we agreed to switch to `Vue.js`. So, I was responsible for creating a Vue.js repository with the idea of separating the frontend and backend in the future. The project includes `Pinia`, `Vue Router`, `Typescript`, `SCSS`, `i18next`, `Cypress` and `Storybook`. In this project, I created all the interface components as per the UX design and documented them using Storybook. All these components were then merged into the PL/SQL code in a simplified version of the Vue.js project, including just Pinia. This completely renewed the system\'s interfaces, facilitated the implementation of new modules and allowed the creation of new functionalities.'"
      />
    </AppCard>
  </main>
  <main
    class="A4"
    style="margin-top: 1px"
  >
    <AppTitle
      class="text-center"
      title="Side Projects"
      subtitle=""
    >
      <AppSubtitle class="text-center text-xs mb-4">
        <small>Click in the <i class="fab fa-github" /> icon to access the repositories</small>
      </AppSubtitle>
    </AppTitle>

    <div class="grid grid-cols-2 gap-6">
      <div class="flex flex-col gap-6">
        <AppCard
          class="text-xs"
          title="Messaging App"
          href="https://www.figma.com/file/LG7zpm5vc2nCZ7mkRIQsHh/Chat-Application?node-id=2%3A2700"
          repository="https://github.com/LucasSFranco/chat-frontend"
        >
          <AppArticle
            :content="'Project in development that is based on applications like WhatsApp, Telegram and Discord. On the backend, two `Node.js` APIs are being created: REST API for managing authentication using JWTs; and, Socket API for real-time communication using the `Socket.io` library. Both are connected to a `PostgreSQL` database using the `Prisma` ORM. The frontend uses `React` as the web framework, `Stitches` for styling and React\'s built-in `Context API` for managing application state. It is intended to deploy everything on `AWS` through an automated pipeline created with `Github Actions`, which should guarantee that everything is working when running the `Jest` tests, on the backend, and the `Cypress` tests, on the frontend.'"
          />
        </AppCard>
        <AppCard
          class="text-xs"
          title="Task List"
          href="https://angry-nobel-17e7b9.netlify.app/"
          repository="https://github.com/LucasSFranco/vue-task-app"
        >
          <AppArticle
            :content="'A to-do list application created using `Vue.js` and `Dexie.js`. It also includes `Vuex` as a state manager, `Sass` as a CSS preprocessor and `Cypress` to test some functionalities. Some of its features:\n- collapsible add task form;\n- hotkeys to open and close add task form (ENTER and ESC keys);\n- skeleton loading;\n- delete task button;\n- toggle task completion (completed/pending) button;\n- self-expandable textarea; and,\n- an elegant design, inspired by Discord.'"
          />
        </AppCard>
        <AppCard
          class="text-xs"
          title="Scheduling Application"
          href="https://schedule-app-a70b5.web.app"
          repository="https://github.com/LucasSFranco/schedule-app"
        >
          <AppArticle
            :content="'Tool developed in `Imba` to schedule the day and record the activities performed every hour. It consists of adding the daily tasks to a list and, after completing them, adding the time each task was performed through a colored legend. All this data is then stored locally in `IndexedDB`. I believed that I would really use the tool in my studies, but the user experience ended up being not so good, so it was just a learning experience.'"
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
            :content="'An animated portfolio website developed for my parents\' advertising company using `Imba` and `Firebase`. Includes header, footer and the sections “about”, “services”, “portfolio” and “contact”. In addition, it is responsive and has an admin page where the user can change the portfolio categories and the images of the work done for each category.'"
          />
        </AppCard>
        <AppCard
          class="text-xs"
          title="News Portal"
          href="https://brave-engelbart-cb0aae.netlify.app"
          repository="https://github.com/LucasSFranco/react-exam"
        >
          <AppArticle
            :content="'The app is a news portal built equally on `React` and `Vue.js` to display news on two topics (technology and science), which are provided by The New York Times API. It was a skill test I took when I joined the company Compass UOL.'"
          />
        </AppCard>
        <AppCard
          class="text-xs"
          title="Ecommerce"
          href="https://drive.google.com/drive/folders/1XMB89zABOQ5cJ4vcyEGoVVhQ0kqDDk53?usp=sharing"
          repository="https://github.com/LucasSFranco/php-ecommerce"
        >
          <AppArticle
            :content="'Responsive sales platform designed for a school project in `PHP`, `HTML`, `CSS` and `JavaScript` using a `MySQL` database. It uses three levels of access:\n- __administrator__: can list, add, delete and edit products and product categories;\n- __customer__: can see the products available in the store, add them to the shopping cart and complete the purchase using the PagSeguro development API;\n- __visitor__: can register, login and see the products available in the store.'"
          />
        </AppCard>
        <AppCard
          class="text-xs"
          title="Chess Game"
          href="https://imba-chess.web.app"
          repository="https://github.com/LucasSFranco/imba-chess"
        >
          <AppArticle
            :content="'Chess game developed in `Imba`. It\'s not complete, but it already has many features that a real chess game should have. It was very funny to code and I learned a lot about Imba language and about programming logic itself.'"
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
