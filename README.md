# Hometask: webdev

### Create a web page, according to 
Figma:
**[webdev](https://www.figma.com/file/2Zev0HVCKABbZoAsuWTdcD/webdev_newVersion-18.09?node-id=1%3A5)**  
or 
JPG:
**[webdev-jpg-version](https://github.com/rolling-scopes-school/tasks/blob/master/tasks/markups/level-1/webdev/webdev-latest-version.jpg)**

### Functional requirements:
- The task is performed in the private repository of the school 
- In the private repository of the school, create a branch called `webdev`, then create a folder in it called `webdev`, and here place the project files - HTML (`index.html`), CSS (`style.css`) and the `assets` folder with images and font files, if any
- For deployment use `gh-pages`
- The commit history should reflect the development process of the application. **[Commit requirements](https://docs.rs.school/#/en/git-convention)**
- After finishing development, you should make a Pull Request from the `webdev` branch to the `main` branch . You don't need to merge the Pull Request until you receive your final score
- **To submit the task for cross-check, you will need to host the page on gh-pages and submit the generated link via app.rs.school in 'Cross-Check : Submit'**

### Requirements for commits, pull request, repository
- the work should be done in your private repository, created using the dashboard in app.rs.school
- source code should be committed to a separate branch called `webdev`
- the **main** branch should be empty (contain only files like README.md or .gitignore)
- commit messages should follow the [guideline](https://www.conventionalcommits.org/en)
- once the work is finished, create a pull request from a development branch to master
- the pull request name should contain **the task name**
- the pull request description should contain the following information:
    - link to the task
    - screenshot of your application (one would be enough)
    - link to your application
    - date of completion/deadline
    - your self-check with a preliminary evaluation that is based on the evaluation criteria from the task


- Pull request `should not contain commented code, redundant files, changes from other branches and generated files`, for instance, `.bundle.js`. Please, check your changes before creating a pull request. `.editorconfig`, `.gitignore`, etc. could be included in your pull request
- Comments on a PR is a good practice
- [How to write the perfect pull request](https://github.com/blog/1943-how-to-write-the-perfect-pull-request)

### Pay attention to the following important and common points:
- The main blocks should be exactly placed on the screen width `1600px`, except for the `Sign up block`, which background should span the whole screen. **-5 points penalty if the 1600 width requirement is not done, -2 points if the sign up block requirement is not done**
- Images, logos (if any) should be positioned within a logical container with the correct centering and positioning approach. 
- Should work on the latest Chrome version
- Task will be checked by a `cross-check`

### Technical requirements:
-	usage of JQuery and other JS libraries is **not allowed 0 points**
-	usage of normalize.css, css-preprocessors, Bootstrap and other UI libraries is **not allowed 0 points**
-	usage of Angular/React/Vue and other frameworks is **not allowed 0 points**
-	position the layout in the *center* with equal margins along the edges. **-2 points otherwise**
-	Add interactivities. **"Interactive"** means that the element has a visual effect or animation (up to you: cursor animation, background color change, shadow, underline,font change) upon any user action, for example, when the cursor is hovering. You do not need to use JavaScript to handle custom events for this task.Basically, this effect is implemented using the `:hover` pseudo-class and the following properties:
      - cursor: pointer,
      -	background,
      -	text-decoration: underline,
      -	color.

1. #### Header (`<header>` contains just logo and navigation bar)
  - Interactive navigation bar. The first item should be highlighted
  - The logo is centered.
  - The header doesn't have any special positional behaviors. If you scroll through the page, the header is no longer visible
  - The background image should be placed behind the text. (the navbar gets it's black color from the background, not explicitly set to black)

2. #### *Your Life* block
  - The get started button should be interactive.
  - Social icons should be interactive
  - The background image should be placed behind the text.
  - There should be one `<h1>` element on the entire page. The placement of it up to you. It should have the 'Your life is webdev' text inside of it.

3. #### *Represent* block
- The text box contains important text in bold. You need to use an appropriate semantic element.
- The `get started` button should be interactive.
- The image should have correct placement.

4. #### *Our Community* block
- `1`, `/`, `5` should be separate elements
- Arrows should be interactive.
- The design consists of 2 multi-dimensional layouts.
    -   Two-row.  On the left. The user icon and the sentence.
    -   Three-column. On the right. Columns - images with the same width. Pay attention that part of the third image goes off-screen. Thus, it also needs to be trimmed using styles.
-  Slider functionality is not needed, it is static

5. #### *Implement* block
- The text block contains important text in bold. You need to use an appropriate semantic element.
- The `learn more` button should be interactive.
- The image should have correct placement.

6. #### *Sign Up* Block
- The image should be placed behind the text.
- The check mark should be interactive.
- `Your email` field should be validated for the email type.

7. ##### *Download* block
- `apple store`, `play store`, and their icons should be interactive.

8. ##### Footer (`<footer>` contains text, logo, and navigation bar):
- There are separators between menu items.
- The navigation bar should be interactive.
