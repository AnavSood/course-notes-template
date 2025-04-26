# Course Notes Template with Quarto

This repository provides a template for creating a course reader or course notes using [Quarto](https://quarto.org/). To use it, follow these steps:

## 1. Install and Verify Quarto

   * Go to the Quarto website ([https://quarto.org/](https://quarto.org/)) and download the installer for your operating system. Run the installer.
   * Open your terminal or command prompt and type `quarto --version`. If Quarto is installed correctly, you should see the version number.

## 2. Clone this Repository

   * Open your terminal or command prompt.
   * Navigate to the directory where you want to store your course materials.
   * Use the following command to clone this repository:

     ```bash
     git clone https://github.com/AnavSood/course-notes-template.git
     ```

## 3. Preview the Website Locally

   * To preview your course notes as a website, navigate to the cloned repository and use command:

     ```bash
     quarto preview
     ```

   * This will start a local server and open your notes in your web browser. Quarto will automatically update the browser when you make changes to your `.qmd` files.

## 4. Deploy the Webpage

   * Quarto generates static websites that can be deployed to any standard web server or hosting service.
   * The output files are located in the `_book` directory after you render your Quarto project.
   * Common deployment options include:
        * **GitHub Pages:** A free hosting service for GitHub repositories.
        * **Netlify:** A platform for building, deploying, and hosting web applications.
        * **Posit Connect:** A platform for publishing and sharing Quarto documents and applications.
        * Any other static site hosting service.

   * Refer to the Quarto documentation for detailed deployment instructions: [https://quarto.org/docs/publishing/](https://quarto.org/docs/publishing/)
