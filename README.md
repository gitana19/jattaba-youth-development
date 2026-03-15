# Jattaba Youth Development Association

Welcome to the Jattaba Youth Development Association website project! This project is built using Hugo and is designed to showcase the initiatives and programs of the association aimed at empowering youth in the community.

## Project Structure

The project is organized as follows:

- **content/**: Contains all the content files for the website.
  - **_index.md**: Homepage content.
  - **about.md**: Information about the association.
  - **programs.md**: Details of various projects undertaken.
  - **events.md**: Information on upcoming and past events.
  - **gallery.md**: A showcase of images related to projects.
  - **contact.md**: Contact information and inquiry form.
  - **blog/**: Directory for blog posts.
  
- **layouts/**: Contains the layout templates for the website.
  - **_default/**: Default templates for pages and lists.
  - **index.html**: Layout for the homepage.
  - **partials/**: Contains reusable components like header, footer, and navigation.

- **static/**: Contains static files such as CSS and JavaScript.
  - **css/**: Stylesheets for the website.
  - **js/**: JavaScript files for interactive elements.

- **themes/**: Directory for custom themes.

- **config.toml**: Configuration file for the Hugo site.

- **.github/**: Contains GitHub Actions workflows for deployment.

## Getting Started

To get started with the Jattaba Youth Development Association website:

1. **Clone the repository**:
   ```
   git clone https://github.com/yourusername/Jattaba-youth-development.git
   cd Jattaba-youth-development
   ```

2. **Install Hugo**: Follow the [Hugo installation guide](https://gohugo.io/getting-started/installation/) to install Hugo on your machine.

3. **Run the development server**:
   ```
   hugo server
   ```
   Open your browser and navigate to `http://localhost:1313` to view the website.

4. **Deploy to GitHub Pages**: Follow the instructions in the `.github/workflows/hugo.yml` file to set up automatic deployment to GitHub Pages.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.