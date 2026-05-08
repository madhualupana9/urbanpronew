# Repository Guidelines

This is a PHP-based website for Urban Pro. It uses a straightforward structure with PHP templating and jQuery for interactivity.

## Project Structure & Module Organization

- **Root Directory**: Contains main PHP pages (e.g., [./index.php](./index.php), [./about.php](./about.php), [./contact.php](./contact.php)).
- **[./includes/](./includes/)**: Shared PHP template parts included in main pages.
  - [./includes/header.php](./includes/header.php): Metadata and CSS links.
  - [./includes/menu.php](./includes/menu.php): Navigation menu.
  - [./includes/footer.php](./includes/footer.php): Footer content and JS scripts.
- **[./assets/](./assets/)**: Centralized directory for project assets.
  - `stylesheet/`: CSS files (e.g., `style.css`, `responsive.css`).
  - `javascript/`: jQuery plugins and `main.js`.
  - `images/` & `fonts/`: Media and typography.

Note: Root-level directories like `stylesheet/` and `javascript/` appear to be duplicates or legacy versions; active templates primarily reference the [./assets/](./assets/) directory.

## Build, Test, and Development Commands

This project does not use a modern build system (e.g., NPM, Composer). Development is performed directly on the PHP files and assets.

- **Local Development**: Host the project root on a PHP-enabled server (e.g., Apache, Laragon, or `php -S localhost:8000`).

## Coding Style & Naming Conventions

- **PHP**: Used for basic templating and includes.
- **Frontend**: jQuery is used for DOM manipulation and interactivity in [./assets/javascript/main.js](./assets/javascript/main.js).
- **CSS**: Custom styles are located in [./assets/stylesheet/style.css](./assets/stylesheet/style.css) and [./assets/stylesheet/shortcodes.css](./assets/stylesheet/shortcodes.css).

## Commit & Pull Request Guidelines

The repository has an initial "First commit." Maintain descriptive commit messages following the pattern: `Action: Description of changes`.
