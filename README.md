**Keizer Blogs** is an open-source, static blogging platform built with Astro and Novel Editor, designed for simplicity, performance, and extensibility. This platform allows users to read articles seamlessly, while administrators can create and manage content with advanced tools like LangDB for AI-driven auto-completions.

---

## Features

- **Static Site with Astro**: Ultra-fast performance, optimized for static content.
- **Rich Text Editor**: Administrators can create and edit blogs using Novel Editor.
- **Database**: SQLite for lightweight, efficient data management.
- **AI-Powered Auto-Completion**: LangDB is integrated as a separate input field to assist in content creation.
- **Open Source**: Perfect for startups, developers, and businesses to self-host and customize.

### For Readers:
- Browse and read articles easily.

### For Admins:
- Access a secure route to manage blog posts.
- Create and edit content with advanced auto-completion tools.
- Upload and manage images seamlessly.

---

## Upcoming Premium Features

1. **Custom Branding**: Ability to add logos, themes, and personalized branding to the blog.
2. **Advanced Analytics**: Track user engagement, page views, and other metrics.
3. **Monetization Tools**: Enable ad placements or paid subscriptions for premium content.

These features will be available as premium add-ons to help monetize your blog.

---

## Tech Stack

- **Frontend**: Astro for a static and fast blog.
- **Editor**: Novel Editor for rich text editing.
- **Database**: SQLite for simplicity and reliability.
- **AI Tool**: [LangDB](https://langdb.ai/) for AI-driven auto-completions.

---

## Self-Hosting Instructions

Keizer Blogs can be self-hosted by startups, businesses, or individual users who want to maintain their blog page. Follow the steps below:

### Prerequisites:
1. **Node.js**: Install the latest version from [Node.js](https://nodejs.org).
2. **Astro CLI**: Install Astro globally using `npm install -g astro`.

### Steps to Set Up Locally:
1. Clone the repository:
   ```bash
   git clone https://github.com/keizer-org/keizer-blogs.git
   cd keizer-blogs
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```
4. Open your browser and navigate to `http://localhost:3000`.

### Deploying:
Keizer Blogs is optimized for deployment on platforms like Vercel, Netlify, or any static hosting service. 

To deploy on Vercel:
1. Install the Vercel CLI:
   ```bash
   npm install -g vercel
   ```
2. Link and deploy your project:
   ```bash
   vercel
   ```

Your blog will be live at the Vercel-provided URL!

---

## Contributing

We welcome contributions to Keizer Blogs! Here's how you can get involved:

1. Fork the repository and clone it to your local machine.
2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature/my-new-feature
   ```
3. Commit your changes and push your branch:
   ```bash
   git commit -m "Add my new feature"
   git push origin feature/my-new-feature
   ```
4. Submit a pull request and describe your changes in detail.

### Guidelines:
- Follow the existing coding style and structure.
- Add comments and documentation for your code.
- Ensure your changes do not break existing functionality.

### Project Structure:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

To learn more about the folder structure of an Astro project, refer to [our guide on project structure](https://docs.astro.build/en/basics/project-structure/).

### Commands:

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

---

## License

Keizer Blogs is open-source software licensed under the MIT License. See the `LICENSE` file for more details.

---
If you have any doubts you can ask in our [discord](https://discord.gg/UGyDwmQs). We are ready help you.  

Start building your blog with **Keizer Blogs** today! Stay tuned for more updates and premium features!
