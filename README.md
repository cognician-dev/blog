# Eleventy Blog

This project is based on the [Eleventy Base Blog](https://github.com/11ty/eleventy-base-blog), a starter repository for building a blog with the [Eleventy](https://www.11ty.dev/) static site generator.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/11ty/eleventy-base-blog.git .
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Build the site:
   ```bash
   npx @11ty/eleventy
   ```

4. Serve locally:
   ```bash
   npx @11ty/eleventy --serve
   ```

## Features

- Static site generation with Eleventy.
- Pre-rendered content with zero-JavaScript output.
- Draft content support (`draft: true` in front matter).
- Automated tag pages, navigation menus, and next/previous links.
- Built-in syntax highlighting and image optimization.

## Deployment

This project can be deployed to various platforms, including GitHub Pages, Netlify, and Vercel. For detailed deployment instructions, refer to the [Eleventy Base Blog documentation](https://github.com/11ty/eleventy-base-blog).

## Customization

- Modify `eleventy.config.js` to configure input/output directories and plugins.
- Update `_data/metadata.js` to customize site metadata.
- Add or edit content in the `content/` directory.

## Resources

- [Eleventy Documentation](https://www.11ty.dev/docs/)
- [Eleventy Base Blog Repository](https://github.com/11ty/eleventy-base-blog)
