<script>
  import Step from "./Step.svelte";

  let steps = [
    {
      name: "Summarize AI",
      icon: "fa-solid fa-computer",
      siteLink: "https://youtube-ai-summarizer.vercel.app/",
      repoLink: "https://github.com/briankjkim/youtube_ai_summarizer/",
    },
    {
      name: "Tes.ai-GPT",
      icon: "fa-solid fa-atom",
      siteLink: "https://mern-ai-chatbot-client.vercel.app/",
      repoLink: "https://github.com/briankjkim/MERN-AI-Chatbot/",
    },
    {
      name: "ODEN: Open-data DevEloper Network",
      icon: "fa-solid fa-globe",
      siteLink: "https://terratap-oden-client-v2.web.app/",
      repoLink: "https://github.com/OpendataDeveloperNetwork/ODEN-Client/",
    },
    {
      name: "RestStop Vancity",
      icon: "fa-solid fa-restroom",
      siteLink:
        "http://ec2-3-96-16-60.ca-central-1.compute.amazonaws.com:3000/",
      repoLink: "https://github.com/briankjkim/RestStop_Vancity_Project",
    },
    {
      name: "Redact Pii",
      icon: "fa-solid fa-eraser",
      siteLink: "https://redact-phi.vercel.app/",
      repoLink: "https://github.com/briankjkim/redact-phi",
    },
    {
      name: "Admin Dashboard",
      icon: "fa-solid fa-chart-line",
      siteLink: "https://react-admin-dashboard-nine-rouge.vercel.app/",
      repoLink: "https://github.com/briankjkim/react_admin_dashboard",
    },
  ];

  let benefits = [
    {
      metric: "10x",
      name: "a full-stack developer with passion and curiosity",
      description:
        "I fell in love with the creativity and problem solving that is involved in developing and engineering innovative technological solutions to the problems of our world. Starting of with JavaScript, HTML & CSS and evolving my knowledge base to include JavaScript frameworks, backend programming, design, cloud services and much much more.",
    },
    {
      name: "an UI/UX design enthusiast",
      description:
        "Carefully crafting and designing amazing user experiences allows me to express and experiment with every morsel of creativity I have. I love the challenge of learning new design concepts and enabling users with amazing online experiences.",
    },
    {
      name: "an excellent communicator and teammate",
      description:
        "Communication is key and it's a paramount value of mine. I believe in transparency and constructive communication above all else. This helps me develop deep relationships and ensures my effectiveness and productivity in any work space with any team.",
    },
  ];
</script>

<main class="flex flex-col flex-1 p-4">
  <section
    id="introPage"
    class="grid grid-cols-1 lg:grid-cols-2 gap-10 py-8 px-10 sm:py-14"
  >
    <div
      class="flex flex-col lg:justify-center text-center lg:text-left gap-6 md:gap-8 lg:gap-10"
    >
      <h2 class="font-semibold text-4xl sm:text-5xl md:text-6xl">
        Hi 🖐️
        <br />
        I'm <span class="poppins text-violet-400">Brian KJ Kim</span>
        <br />
        Software
        <span class="poppins text-violet-400">Developer</span>
      </h2>
      <p class="text-base sm:text-lg md:text-xl">
        My <span class="text-violet-400">favourite tech</span> are React, Next.JS,
        Strapi, TaildwindCSS, Node.js + Express.js, Prisma, and Firebase!
      </p>
      <a
        class="blueShadow mx-auto lg:ml-0 text-base sm:text-lg md:text-xl poppins relative overflow-hidden px-6 py-3 group rounded-full bg-white text-slate-950 cursor-pointer"
        href="https://www.linkedin.com/in/brian-kj-kim/"
        target="_blank"
      >
        <div
          class="absolute top-0 right-full w-full h-full bg-violet-400 opacity-20 group-hover:translate-x-full z-0 duration-200"
        />
        <h4 class="relative z-9">Get in touch &rarr;</h4>
      </a>
    </div>
    <div class="relative shadow-2xl grid place-items-center">
      <img
        src={"images/profile.png"}
        alt="Profile"
        class="object-cover z-[2] max-h-[70vh]"
      />
    </div>
  </section>

  <section id="projects" class="py-20 lg:py-32 flex flex-col gap-24">
    <div class="flex flex-col gap-2 text-center">
      <h6 class="text-lg sm:text-xl md:text-2xl">
        A few of my software development endeavors,
      </h6>
      <h3 class="font-semibold text-3xl sm:text-4xl md:text-5xl">
        Curious to <span class="poppins text-violet-400">see</span> my works?
      </h3>
    </div>
    <a
      href="https://github.com/briankjkim"
      target="_blank"
      class="mx-auto px-4 py-2 rounded-md border border-solid border-white flex items-center gap-2 -mb-4 sm:-mb-0 -mt-10 hover:border-violet-700 duration-200"
    >
      <i class="fa-regular fa-circle-play"></i>
      <p>Go To GitHub</p>
    </a>
    <div class="grid grid-cols-1 gap-12 lg:grid-cols-3 lg:gap-10">
      <Step step={steps[0]}>
        <strong class="text-violet-400"
          >React, TypeScript, Next.JS, Strapi, PostgreSQL, OpenAI, ShadCN UI</strong
        >
        Summarize AI is a web application that summarizes the content of YouTube
        videos into concise and organized texts. Save your summaries and access them
        anytime!
      </Step>
      <Step step={steps[1]}>
        <strong class="text-violet-400"
          >React, TypeScript, Node.js + Express.js, MongoDB (MERN)</strong
        >
        Tes.ai is a web application that provides ChatGPT-like conversations between
        the user and the application’s AI engine, where the AI engine aims to mimic
        the characteristics of Ancient Greek Philosophers, such as Socrates.
      </Step>
      <Step step={steps[2]}>
        <strong class="text-violet-400"
          >React, MongoDB, Google Firebase, Node.js + Express.js
        </strong>
        Open Data Development Network (ODEN) is an open-source initiative aimed at
        streamlining developers' access to open data by consolidating scattered datasets
        from various cities into a centralized platform.
      </Step>
      <Step step={steps[3]}>
        <strong class="text-violet-400"
          >React, NextJS, TailwindCSS, Open Data Portal, Docker
        </strong>
        RestStop Vancity is an open source independent project that provides nearby
        public washroom locations to the client by utilizing Open Data Portal API
        from municipalities in Lower Mainland.
      </Step>
      <Step step={steps[4]}>
        <strong class="text-violet-400"
          >React, NextJS, TailwindCSS, ShadCN UI, OctoAI
        </strong>
        Redact PHI is a document PHI redaction application that automatically redacts
        Personal Health Information (PHI) from the user's uploaded document. It also
        has an experimental feature where the user has an option to use a Gen AI
        service for redaction.
      </Step>
      <Step step={steps[5]}>
        <strong class="text-violet-400"
          >React, NextJS, TailwindCSS, NextAuth, Tremor, Prisma
        </strong>
        React Admin Dashboard is a sample dashboard application that utilizes Tremor
        to display charts and NextAuth for authentication.
      </Step>
    </div>
  </section>
  <section
    id="about"
    class="py-20 pt-10 lg:pt-16 lg:py-32 flex flex-col gap-16 sm:gap-20 md:gap-24 relative"
  >
    <div
      class="flex flex-col gap-2 text-center relative before:absolute before:top-0 before:left-0 before:w-2/3 before:h-1.5 before:bg-violet-700 after:absolute after:bottom-0 after:right-0 after:w-2/3 after:h-1.5 after:bg-violet-700 py-4"
    >
      <h6 class="text-lg sm:text-xl md:text-2xl">Want to know more?</h6>
      <h3 class="font-semibold text-3xl sm:text-4xl md:text-5xl">
        A bit <span class="poppins text-violet-400">about</span> me.
      </h3>
    </div>
    <p class="mx-auto poppins font-semibold text-lg sm:text-xl md:text-2xl">
      I am . . .
    </p>
    <div class="flex flex-col gap-20 w-full mx-auto max-w-[800px]">
      {#each benefits as benefit, index}
        <div class="flex gap-6 sm:gap-8">
          <p
            class="poppins text-4xl sm:text-5xl md:text-6xl text-slate-500 font-semibold"
          >
            0{index + 1}
          </p>
          <div class="flex flex-col gap-6 sm:gap-8">
            <h3 class="text-2xl sm:text-3xl md:text-5xl">
              {benefit.name}
            </h3>
            <p>{benefit.description}</p>
          </div>
        </div>
      {/each}
    </div>
  </section>
</main>
