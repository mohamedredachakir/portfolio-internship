# Portfolio

## About Me

Full Stack Web Developer passionate about designing and building scalable, efficient, and user-centered web applications. Currently undergoing advanced training at YouCode (UM6P), with hands-on experience in web content management, SEO on-page optimization, RGPD compliance, and digital accessibility (WCAG). Comfortable across the full development cycle from concept to deployment, with a strong focus on clean code, performance, and quality. Also experienced in UI/UX design and graphic design.

## Links

- **Live Demo:** [Check out the live portfolio](https://mohamedredachakir.github.io/portfolio-internship/)
- **GitHub:** [mohamedredachakir](https://github.com/mohamedredachakir)
- **LinkedIn:** [Mohamed Reda Chakir](https://www.linkedin.com/in/mohamed-reda-chakir-7339b135a/)
- **LeetCode:** [mohamedredachakir](https://leetcode.com/u/mohamedredachakir/)

## Deploy

### GitHub Pages (automatic)

This repo includes [.github/workflows/deploy-pages.yml](.github/workflows/deploy-pages.yml), which deploys automatically on every push to `main`.

1. Open GitHub repository settings.
2. Go to **Pages**.
3. In **Build and deployment**, set **Source** to **GitHub Actions**.
4. Push to `main` and wait for the workflow to finish.

### Any Server (Nginx / Docker)

You can deploy as a static site on any server.

Using Docker:

```bash
docker build -t portfolio-internship .
docker run -d -p 8080:80 --name portfolio-site portfolio-internship
```

Then open `http://localhost:8080`.

The repo includes:

- [Dockerfile](Dockerfile)
- [nginx.conf](nginx.conf)
- [.nojekyll](.nojekyll)
