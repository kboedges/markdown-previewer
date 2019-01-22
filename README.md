# Project

## Introduction

Project is being designed after the web-based project challenge [Front End Libraries Projects - Build a Markdown Previewer on freeCodeCamp](https://learn.freecodecamp.org/front-end-libraries/front-end-libraries-projects/build-a-markdown-previewer/). This project will use a Test Driven Development approach with feature tests being written _before_ code and then code is written to _satisfy_ failing tests.

- **Objective:** Build an app that is functionally similar to this: https://codepen.io/freeCodeCamp/full/GrZVVO.
  Fulfill the below user stories and get all of the tests to pass. Give it your own personal style.
  You can use any mix of HTML, JavaScript, CSS, Bootstrap, SASS, React, Redux, and jQuery to complete this project. You should use a frontend framework (like React for example) because this section is about learning frontend frameworks. Additional technologies not listed above are not recommended and using them is at your own risk. We are looking at supporting other frontend frameworks like Angular and Vue, but they are not currently supported. We will accept and try to fix all issue reports that use the suggested technology stack for this project. Happy coding!

## User Stories

- **User Story #1:** I can see a textarea element with a corresponding id="editor".
- **User Story #2:** I can see an element with a corresponding id="preview".
- **User Story #3:** When I enter text into the #editor element, the #preview element is updated as I type to display the content of the textarea.
- **User Story #4:** When I enter GitHub flavored markdown into the #editor element, the text is rendered as HTML in the #preview element as I type (HINT: You don't need to parse Markdown yourself - you can import the Marked library for this: https://cdnjs.com/libraries/marked).
- **User Story #5:** When my markdown previewer first loads, the default text in the #editor field should contain valid markdown that represents at least one of each of the following elements: a header (H1 size), a sub header (H2 size), a link, inline code, a code block, a list item, a blockquote, an image, and bolded text.
- **User Story #6:** When my markdown previewer first loads, the default markdown in the #editor field should be rendered as HTML in the #preview element.

## User Story Tests

1. A `textarea` element exists with a id of "editor"
2. An element exists with an id of "preview"
3. When text is entered into #editor, the #preview element is updated
4. When markdown is entered into the #editor, the text is rendered as HTML in #preview
5. When the app loads, the default text in #editor should contain valid markdown that represents at least one of each of the following elements: a header (H1 size), a sub header (H2 size), a link, inline code, a code block, a list item, a blockquote, an image, and bolded text.
6. When the app loads, the default markdown in #editor should be rendered as HTML in #preview

## Optional User Stories

- **Optional Bonus (you do not need to make this test pass):** When I click a link rendered by my markdown previewer, the link is opened up in a new tab (HINT: read the Marked.js docs for this one!).
- **Optional Bonus (you do not need to make this test pass):** My markdown previewer interprets carriage returns and renders them as br (line break) elements.

## Optional User Story Tests

1. When a link is clicked, a new tab opens up to a URL
2. Line break elements `<br>` are added for carrage returns

## freeCodeCamp Resources

You can build your project by forking this CodePen pen. Or you can use this CDN link to run the tests in any environment you like: https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js

- Once you're done, submit the URL to your working project with all its tests passing.
  Remember to use the Read-Search-Ask method if you get stuck.

# React Resources

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

# Testing

## Tests to Create

1. A `textarea` element exists with a id of "editor"
2. An element exists with an id of "preview"
3. When text is entered into #editor, the #preview element is updated
4. When markdown is entered into the #editor, the text is rendered as HTML in #preview
5. When the app loads, the default text in #editor should contain valid markdown that represents at least one of each of the following elements: a header (H1 size), a sub header (H2 size), a link, inline code, a code block, a list item, a blockquote, an image, and bolded text.
6. When the app loads, the default markdown in #editor should be rendered as HTML in #preview

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `npm run build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
