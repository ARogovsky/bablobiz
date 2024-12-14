---
draft: false
contactform:
  formAction: "https://api.web3forms.com/submit"
  accessKey: "YOUR_ACCESS_KEY_HERE"
  fields:
    - name: "Full Name"
      type: "text"
      required: true
      placeholder: "Full Name"
      feedback: "Please provide your full name."
    - name: "Email Address"
      type: "email"
      required: true
      placeholder: "Email Address"
      feedback:
        empty: "Please provide your email address."
        invalid: "Please provide a valid email address."
    - name: "Message"
      type: "textarea"
      required: true
      placeholder: "Your Message"
      feedback: "Please enter your message."
  button:
    text: "Send Message"
    size: "lg"
    block: true
  resultId: "result"
  feedbackTimeout: 5000

cta:
  title: "Build faster websites."
  description: "Pull content from anywhere and serve it fast with Astro's next-gen island architecture."
  button:
    text: "Get Started"
    href: "#"
    style: "inverted"

features:
  title: "Everything you need to start a website"
  description: "Astro comes batteries included. It takes the best parts of state-of-the-art tools and adds its own innovations."
  items:
    - title: "Bring Your Own Framework"
      description: "Build your site using React, Svelte, Vue, Preact, web components, or just plain ol' HTML + JavaScript."
      icon: "bx:bxs-briefcase"
    - title: "100% Static HTML, No JS"
      description: "Astro renders your entire page to static HTML, removing all JavaScript from your final build by default."
      icon: "bx:bxs-window-alt"
    - title: "On-Demand Components"
      description: "Need some JS? Astro can automatically hydrate interactive components when they become visible on the page."
      icon: "bx:bxs-data"
    - title: "Broad Integration"
      description: "Astro supports TypeScript, Scoped CSS, CSS Modules, Sass, Tailwind, Markdown, MDX, and any other npm packages."
      icon: "bx:bxs-bot"
    - title: "SEO Enabled"
      description: "Automatic sitemaps, RSS feeds, pagination, and collections take the pain out of SEO and syndication."
      icon: "bx:bxs-file-find"
    - title: "Community"
      description: "Astro is an open source project powered by hundreds of contributors making thousands of individual contributions."
      icon: "bx:bxs-user"

footer:
  text: "Copyright © {year} Astroship. All rights reserved."
  credits:
    text: "Made by Web3Templates"
    url: "https://web3templates.com"

hero:
  title: "Marketing website done with Astro"
  description: "Astroship is a starter template for startups, marketing websites & landing pages. Built with Astro and TailwindCSS."
  buttons:
    - text: "Download for Free"
      href: "https://web3templates.com/templates/astroship-starter-website-template-for-astro"
      icon: "bx:bxs-cloud-download"
      style: "primary"
    - text: "GitHub Repo"
      href: "https://github.com/surjithctly/astroship"
      icon: "bx:bxl-github"
      style: "outline"
  heroImage: "../assets/hero.png"

logos:
  title: "Works with your technologies"
  logos:
    - "simple-icons:react"
    - "simple-icons:svelte"
    - "simple-icons:astro"
    - "simple-icons:tailwindcss"
    - "simple-icons:alpinedotjs"
    - "simple-icons:vercel"

sectionhead:
  defaultTitle: "Title"
  defaultDescription: "Some description goes here"

navbar:
  brand:
    name: "Astroship"
    logo: "/"
  menuitems:
    - title: "Features"
      path: "#"
      children:
        - title: "Action"
          path: "/"
        - title: "Another action"
          path: "#"
        - title: "Dropdown Submenu"
          path: "#"
        - title: "404 Page"
          path: "/404"
    - title: "Pricing"
      path: "/pricing"
    - title: "About"
      path: "/about"
    - title: "Blog"
      path: "/blog"
    - title: "Contact"
      path: "/contact"
    - title: "Pro Version"
      path: "https://astroship-pro.web3templates.com/"
      badge: "New"
  actions:
     login: "Log in"
     signup: "Sign up"
---