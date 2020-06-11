


## Table of Contents

- [Technology Stack 🛠️](#technology-stack-)
- [Structure ⚓](#structure-)
- [Sharing 💗](#sharing-)
- [Prerequisites 🍪](#prerequisites-)
- [Setup And Deployment 🔧](#setup-and-deployment-)
- [Contributing 🙌](#contributing-)
- [Issues](#issues)
- [Upcoming Features / Improvements 🔗](#upcoming-features-/-improvements-)
- [Showcase 🚀](#showcase-)
- [Contributors ✨](#contributors-)
- [License 📄](#license-)

## Technology Stack 🛠️

Dependencies defined in package.json:

[Reactjs](https://reactjs.org/)
| [Bootstrap](https://getbootstrap.com/)
| [Typist](https://github.com/jstejada/react-typist)
| [GitHub API](https://developer.github.com/v3/repos/)
| [Instagram API](https://www.instagram.com/developer/embedding/)

## Structure ⚓

- Body
  - Name | Profession
  - Contact / Follow / Find me / Facebook / LinkedIn / GitHub / Instagram / Email / CodePen
  - Resume
- About Me
  - Display picture (using Instagram API)
  - Interests, Goals and Hobbies
  - Things I'm good at (Skills)
- Projects (using GitHub API)
- Footer
  - Acknowledgements (contributors)
  - Copyrights - open source
  - (quote: Dream big, Think big)

## Sharing 💗

Project is open source. Feel free to make your own version. All you need to do is to fork this repository, edit [src/editable-stuff/configurations.json](./src/editable-stuff/configurations.json) and add resume. Mark star ⭐ if you like the project.

## Prerequisites 🍪

You should have [Node.js](https://nodejs.org/en/) and [Git](https://git-scm.com/) installed on your PC. You should also own a GitHub account.

## Setup And Deployment 🔧

1. To Get Started, Fork this repository to your GitHub account:
2. Clone the forked repo from your account using:

   ```bash
     git clone https://github.com/<your-username>/home.git
   ```

3. Open in editor and edit [src/editable-stuff/configurations.json](./src/editable-stuff/configurations.json) file.

4. Add your resume as <resume.pdf> in place of [src/editable-stuff/resume.pdf](./src/editable-stuff/)
5. Change URL in [package.json](./package.json) file:

   ```json
   "homepage": "https://<your-username>.github.io/home"
   ```

6. Edit [title](./public/index.html#L34) and meta [description](./public/index.html#L13) in [public/index.html](./public/index.html).

7. After editing run the following bash commands:

   ```bash
   npm install
   npm start
   ```

8. To deploy website run:

   ```bash
    npm run deploy
   ```

9. Congrats your site is up and running. To see it live, visit:

   ```https
     https://<your-username>.github.io/home
   ```

## Contributing 🙌

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Issues

If anyone is looking to make some contribution, the following are issues that you can solve:

- [ ] UI improvements
- [x] Grammar check | Spelling mistakes
- [ ] Code optimization
- [x] Hover property on social icons
- [ ] Routing

## Upcoming Features / Improvements 🔗

- [x] Button and place for resume/CV.
- [x] Option: add or not to add Instagram's display picture.
- [x] Number of projects to show in website.
- [ ] If the Number of Projects are zero, hide the heading (Recent Projects)
- [ ] Make resume optional.




## License 📄

[LGPL-3.0](https://www.gnu.org/licenses/lgpl-3.0.en.html)
