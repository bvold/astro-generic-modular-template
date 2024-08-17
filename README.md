# Astro Generic Template

This is a generic Astro template with a modular layout, including an area chooser, header, left navigation, main content area, and footer.

## Features

- Modular component-based structure
- Responsive grid layout
- Easy to customize and extend

## How to Use This Template

To use this template for your new Astro project, follow these steps:

1. Ensure you have Node.js installed on your system (version 14.18.0 or higher).

2. Open your terminal and run the following command:

   ```bash
   npm create astro@latest my-astro-project -- --template bvold/astro-generic-modullar-template
   ```

3. Follow the prompts to set up your new project:
* Enter a name for your project if you didn't enter on initial command
* Choose whether to install dependencies
* Select your preferred package manager (npm, yarn, or pnpm)


4. Once the setup is complete, navigate to your new project directory:

    ```bash
    cd my-astro-project
    ```

5. Start the development server:

    ```bash
    npm run dev
    ```

6. Open your browser and visit http://localhost:4321 to see your new Astro site!

## Customizing the Template
This template provides a basic structure that you can easily customize:

* `src/components/`: Contains individual components (AreaChooser, Header, LeftNavigation, MainContent, Footer)
* `src/layouts/MainLayout.astro`: The main layout file that brings all components together
* `src/pages/index.astro`: The home page of your site

Feel free to modify these files or add new components and pages as needed for your project.

## Contributing
If you'd like to contribute to this template, please fork the repository, make your changes, and submit a pull request.
## Issues
If you encounter any problems or have suggestions for improvements, please open an issue on the Gitea repository.
## License
This template is released under the MIT License.
