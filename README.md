# My Portfolio Website

Welcome to the source code for my personal portfolio website, built with [Hugo](https://gohugo.io/) and hosted on [GitHub Pages](https://pages.github.com/). This project uses the **Hugo Profile** theme and showcases my projects, skills, and achievements.

## Table of Contents

- [About](#about)
- [Live Demo](#live-demo)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## About

This portfolio website is built using Hugo, a fast and modern static site generator written in Go. It features a simple, clean design with sections for:

- About Me
- Projects
- Skills
- Blog (optional)
- Contact Information

## Live Demo

You can view the live website at:  
[https://d3mah-24.github.io/](https://d3mah-24.github.io/)

## Installation

To set up the website on your local machine, follow these steps:

1. **Install Hugo:**

   Follow the [official Hugo installation guide](https://gohugo.io/getting-started/installing/) to install Hugo on your machine.

2. **Install theme submodule:**

   If the theme is a git submodule, make sure to pull it:

   ```bash
   git submodule update --init --recursive
   ```

3. **Run the Hugo development server:**

   You can now run the Hugo server locally to preview the website.

   ```bash
   hugo server
   ```

   The site will be available at `http://localhost:1313/`.

## Usage

### Creating Content

To create a new content page (e.g., a blog post or project), use the following command:

```bash
hugo new posts/my-first-post.md
```

This will create a new markdown file in the `content` directory. You can then edit this file and add your content.

### Customizing the Theme

You can customize the site's appearance by editing the theme files located in the `themes/hugo-profile` directory. You can also adjust the configuration in `config.toml`.

## Contributing

Feel free to fork this repository and make improvements. If you have any suggestions or find issues, please submit a pull request or open an issue.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
