## Building a Portfolio Homepage
Build two key sections: an **Introduction banner** (featuring your photo and a short blurb) and a **Latest Projects** section. You’ll work from a provided wireframe to match the layout as closely as possible. Your site will be fully responsive across devices and meet **A and AA accessibility standards**.

Demonstrate your proficiency with CSS methodologies, preprocessors, accessibility practices, and advanced CSS techniques, all while creating a polished addition to your portfolio.

## Instructions for Reviewers
1. Download zip and uncompress the project folder
2. Use cd starter
3. Use npm run install to update the dependencies
4. Use npm run watch --> It will compile src/scss/main.scss into dist/main.css
5. Double-click index.html to open the browser

## Project Instructions
1. **Starter Code**:
    - Download and unzip the provided starter code, which includes:
        - **Dist Folder**: Where your compiled CSS file (`main.css`) will live.
        - **Src Folder**:
            - `img`: Store all image files here. This folder has a placeholder image for your Introduction banner. You're welcome to use it, but are encouraged to find your own image, which better reflects your personality.
            - `scss`: Store all CSS preprocessor folders and files here. Rename this folder to match the preprocessor you are using (`scss`).
    - Download the wireframes to guide the website layout for desktop and mobile views.

2. **Folder Structure**:
    - As per BEM methodology, your `scss` folder will contain `base`, `blocks`, and `utils` folders with a primary stylesheet that matches the name:
        - **Base**: Contains foundational styles such as resets, typography, and general element styles (e.g., for body, headings, links).
        - **Blocks**: Houses styles for individual components, each in its own file, following the BEM methodology (e.g., `button.scss`, `header.scss`).
        - **Utils**: Includes reusable helper styles like variables, mixins, and utility classes that support the design system.
    - Compile all preprocessor files into a single `main.css` file inside the `dist` folder.

3. **Introduction**:
    - **Bio Content**:
        - Include a background image for the banner.
        - Add a bio section with:
            - A profile image.
            - A main heading (e.g., "[Your Name]'s Web Development Portfolio").
            - A short paragraph describing yourself.
        - **Note**: If you don't feel comfortable using your own photo, you can use a placeholder image for the purpose of this project. Using a professional headshot can positively contribute to a developer's personal branding, but you don't have to make that decision just yet.
    - **Responsive Behavior**:
        - Align the profile image and text content side by side on larger screens.
        - Stack the profile image above the text content on mobile.

4. **Latest Projects Section**:
    - **Content**:
        - Include a heading (e.g., "Latest Projects").
        - Add three project cards, each with:
            - An image (placeholder images are fine).
            - A title.
            - A short description.
        - Add a centered button below the cards that would link to a projects page.
    - **Design**:
        - Ensure the cards are equal in width and height.
        - Apply hover or tabbing transitions to project cards.

5. **Navigation Header**:
    - Create a fixed navbar with projects, skills, resume, and contact links.
    - The navbar should:
        - Stick to the top of the page and shrink in height on scroll.
        - Display links on desktop and optionally collapse into a mobile-friendly "burger" menu for smaller screens.
        - **Note**: If you choose not to incorporate a burger menu into your mobile view, keep in mind that you still need to adhere to responsiveness standards and ensure that your links do not overflow beyond the width of the header.

6. **Footer**:
    - Create a footer at the bottom of your page with copyright information. (e.g. `&copy; Joseph Debao Chua 2026`)

7. **Accessibility**:

Meet the **A and AA accessibility standards** outlined in the provided checklist.

8. **Submission**:
    - Submit the entire project, including:
        - `dist`: Compiled main.css file.
        - `src`:
            - `scss`: All scss folder that contains base, blocks and utils folder.
            - `index.html`: HTML file containing your web components.
            - `package.json`: For reviewers to install dependencies.

9. Zip the project folder as `JosephDebao_Chua_homepage` and upload it.

### Example Style Folder Structure

```javascript
src
├── index.html
├── pages
│     ├── about.html
│     ├── contact.html
│     ├── projects.html 
├── scss
│     ├── base 
│     │   ├── _resets.scss
│     │   └── base.scss
│     ├── blocks
│     │   ├── _bio.scss
│     │   ├── _buttons.scss
│     │   ├── _footer.scss
│     │   ├── _header.scss
│     │   ├── _page.scss
│     │   ├── _projects.scss
│     └── utils 
│         ├── _mixins.scss
│         ├── _variables.scss
```