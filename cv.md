#Andrey Grishkov

---

##My Contacts:

- **E-mail:** [andreygorm@gmail.com](andreygorm@gmail.com)
- **Telegram:** [Andreygorm](https://t.me/Andreygorm)
- **GitHub:** [Andrey-Grishkov](https://github.com/Andrey-Grishkov)
- **Linkedin:** [andrey-grishkov](https://www.linkedin.com/in/andrey-grishkov/)

---

##About Me:

I am a web developer. At the moment I am strengthening my knowledge,
learning new technologies and looking job. I graduated from the
Moscow Power Engineering Institute and worked as a design engineer for a
long time. Since childhood, I liked use computer for every day
(mostly playing games, of course), and I also studed different programs,
and maked first steps to development (Fortran, Pascal). Finally,
I decided to change profession. In addition, working as a
web developer goes well with my passion for traveling (I am visited lot countries
like as Spain, India, Sweden, Thailand, Austria, Vietnam etc).
I have a little experience in the collective creation of a non-commercial
web-site project ([https://distsamgtu.ru](https://distsamgtu.ru)).
For this web-site I worked as a developer and technical
leader of the front-end development team. In the project We were able to learn
new technologies (Sass, Redux, Axios), shared and learned the experience
of other developers, gained teamwork skills and communication with another IT
specialists (backend development, testers, product managers, designers).

---

##Technology stack:

*HTML, CSS, Sass, JavaScript, Git, BEM, Figma, Webpack, React, Redux, 
TypeScript, Node.js, Postman, MongoDB, Express*

---

##Code Example:

- Example how extract the domain name from a URL with use regular expressions

```
function domainName(url) {
  const regexFirstPart=/^(https*:\/\/)*(w{3}\.)*/gmi;
  const regexLastPart=/(\.([\w]{2,}))+(\/[\w-]*\.*[\w-]*)*$/gmi;
  const urlWithoutFirstPart=url.replace(regexFirstPart,'');
  const urlDomain=urlWithoutFirstPart.replace(regexLastPart,'');
  return urlDomain
}
```

---

##Education and experience:

- Course web-development from Yandex Practicum (January - December 2022)
  - [Movies-explorer](https://github.com/Andrey-Grishkov/movies-explorer-frontend)
    \- graduation project web-site for search movies. 
    (Have back-end and frontend part, registration and authorization users, 
    validation input parameters. Stack: *HTML, CSS, React, Node.js, MongoDB, Express*)
  - [Mesto](https://github.com/Andrey-Grishkov/mesto-react-frontend)
    \- project model social net where users post foto interesting places.
    (Have back-end and frontend part, registration and authorization users,
    validation input parameters, realize function to make like with count for foto. 
    Stack: *HTML, CSS, React, Node.js, MongoDB, Express*)
  - [Russian-travel](https://github.com/Andrey-Grishkov/russian-travel)
    \- One-page landing with adaptive layout about travelling for Russia.
    (Stack: *HTML, CSS, Flexbox, Grid layout, BEM, Media queries*)
- Non-commercial pet-project (January - to present 2023)
  - [Samgstudist](https://github.com/Andrey-Grishkov/samgstudist)
    \- Web-site for searching examples of students work.
    (Stack: *HTML, Sass, React, Redux, Axios*)
  - [Minesweeper](https://github.com/Andrey-Grishkov/sapper)
    \- Game where users need find mine.
    (Stack: *JavaScript*)
  - [Postcard](https://github.com/Andrey-Grishkov/postcard-eight-march-for-mom)
    \- Web-site like a postcard where have photo album for my Mom
    (Stack: *HTML, CSS, React*)
