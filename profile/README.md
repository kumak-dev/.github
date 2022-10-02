
# Project Cyklon

Hello there, and welcome. I'm Kumak, and this is my pond.
Feel free to look around, and do not hesitate to ping me in any case.

## Overview
**TL:DR This exercise is a part of my studies. The company is fictional but solves real problems.**

Kumak.dev is a fictional organization that used a test case for <link> course I have just spontaneously enrolled.

One of the requirements is to apply acquired knowledge to real-world examples of organizations or companies. I want to take a bit different approach. I will create a fictional 
a company called "kumak.dev", that will have an authentic purpose, goals, problems, metrics, budget, ambitions, and out-of-control lunatic CEO posting silly Twits without consulting them with PR *

*Style Convention: Although I will try to be genuine in my approach to methodology and engineering, please don't expect me to keep 100% business vocabulary and a severe tone. I will approach the problems seriously but informally communicate them. Expect dank memes and emojis.  

## Project Cyklon
It is an attempt to create a "My Perfect Development Environment."

A collection of libraries, workflows, generators, utilities, services, and cool useless features to help me in everyday tasks.

I will use the proposed folder structure (subject to a change) to illustrate what I'm on about:

```
apps/
  ├── moms-pottery-store/     #private
    ├── config/
    ├── web/            :nextjs
      ├── pages/
      ...
  ├── side-project-94   #private
    ├── config/
    ├── cms/            :strapi
    ├── blog/           :astro
    ├── mobile/         :react-native
  ├── goldman           #corporate
    ├── config/
    ├── todo-app/      :create-react-app
    ├── assets/
      ├── The_Big_Short_(2015)_YIFY_MOVIE_YTS
    ...
  ...
libs/
  ├── components/
    ├── .storybook/
    ├── .cypress/
    ├── src/
      ├── inputs/
      ├── buttons/
      ...
    project.json
    tsconfig.json
    README.md
    ...
  ├── features/
  ...
      ├── blog/
      ├── landing/
      ├── dashboard/
      ├── login/
  ...
  ├── utilities/
      ├── hooks/
      ├── helpers/
      ├── states/
    ...
  ├── data-access/
      ...
      ├── api/
      ├── types/
      ├── configs/
      ...
```

Yet another React monorepo. But with some twists here and there.

NX - Helps me to maintain only one library of "carefully selected with love" components, utilities, and models ready to be reused in different projects with different frameworks. It has some excellent generators to speed up development, quality of life metrics boosters like building affected using distributed cloud cache, and features that would like to explore ( to be defined )

Learna & pnpm - This should help me to keep the size of node_modules in check and provide control over the dependencies that this project will use very extensively.

### Other:

#### "One script to rule them all."
Backend, Fronted, Mobile, Tests, Styles, Runners, and Actions will be written in one language, and its name is ECMA.
Style Guides and Lint rules will be enforced through all repo.

Besides making the prophecy come to life, it has a clear business value. The whole dev team writes only in JS. That simplifies many things: recruitment, knowledge sharing, mentoring, skills matrix management, outsourced training, cross-project mobility, etc.

...and address my skill gap pretty well ( Rust, maybe one day, I promise )

#### "I'm in control."
This project assumes the integration will a large number of different services based on third-party frameworks, so for business and security reasons, the aim will be to use self-hosted equivalents where possible. 

* Socketi instead of Pusher.
* Sorry Cypress instead of Cypress.
* Coder instead of Github Codespaces.
* listmonk instead of Mailchimp.


#### "It's up to you guys."
Devs should be able to contribute how they see fit. Want to use the company laptop? There you go. Prefer using your custom rig? Go ahead and use the Repo Package or Codespaces; here are some legal security rules to accept, but that's it. 

TBC
