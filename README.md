<p align="center" >
   <img src="https://images.ctfassets.net/gm98wzqotmnx/3Ufcb7yYqcXBDlAhJ30gce/c237bb3254190795b30bf734f3cbc1d4/prefect-logo-full-gradient.svg" width="500" style="max-width: 500px;" alt="Prefect Logo">
</p>

<p align="center">
<a href="https://prefect.io">
    <img src="https://images.ctfassets.net/gm98wzqotmnx/3mwImS57DEydMQXU1FCGG/6e36e2d49faf78cf4a166f123c2c43ca/image__5_.png" height="27" alt="Powered By Prefect">
    </a>
</p>

# Prefect Front End Software Engineer Challenge

Welcome to the Prefect Front End Software Engineer Challenge!

This challenge consists of 3 exercises. The goal is to get a sense of how you solve problems and implement your code - the  questions are not designed to trick you.

No additional packages or libraries are required but you may add any that you wish.  Please do not modify the instructions component (found at `/src/pages/HomeInstructions. vue`) or any of the instruction text for the exercise (these will be clearly denoted in  the code with an `...__instructions` class) until your submission has been graded.  Any other code (including router, store, styling, and components) are free for you to modify at your discretion.

Continue reading for project setup and submission.

## Project setup

- Clone this repository
- Change the remote to a private GitHub repository under your username
- Push code to that remote, using clear Commits and Pull Requests with clear messages
- Code!

## Submission

This project should be submitted by adding [@znicholasbrown](https://github.com/znicholasbrown), [@pleek91](https://github.com/pleek91), [@zhen0](https://github.com/zhen0) as collaborators to your cloned repository on GitHub. Once you've done so, please send an email to [jenny@prefect.io](jenny@prefect.io) to confirm your submission.

## Recommended IDE

- [VSCode](https://code.visualstudio.com/)
- [Volar](https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.volar) (vscode extension) is registered as a workspace recommended extension. 

## Local Development

To start, install the project dependencies.

```
npm install
```


### Transpiles and hot-reloads for development

Then, start your development server.

```
npm run dev
```

### Lints and fixes files

This project is setup to use the same ESLint config our frontend developers actually use. https://www.npmjs.com/package/@prefecthq/eslint-config. The workspace settings (assuming you're using vscode) are setup to automatically fix any fixable eslint errors on save.

## Making your work public

_The work you do on this project is your own_. As such, you can make it publicly  available at your discretion (on your GitHub, as part of a portfolio etc.).

If you plan to make this repository public, **please do not do so until after your  submission has been graded** (we'll let you know when that is!). In addition, please  remove or replace Prefect in the `<title>` block of the root html file (found in `/public/index.html`), the `<link>` and `<meta>` blocks between the comments in that same  file, as well as the associated logos in that folder. Last, please remove or  replace the Prefect logo in the root application file (found in `/src/App.vue`) and the  associated `.svg` found in the assets folder.

If you haven't modified the `index.html` file as part of your challenge (you shouldn't  need to), you can run the following command from the root of the project directory to automatically remove / replace all of the above:

```bash
$ mv public/index-template.html public/index.html && \
  rm public/{*.png,*.xml,*.ico,*.svg,*.webmanifest} && \
  mv src/assets/vue-logo.svg src/assets/logo.svg
```
