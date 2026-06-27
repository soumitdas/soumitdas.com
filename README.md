# Personal portfolio

<p align="center">
  <img alt="screenshot of soumitdas.com" src="https://i.imgur.com/nt83qi9.jpg">
</p>

[![Netlify Status](https://api.netlify.com/api/v1/badges/cb041b5d-a2a5-4f7b-87c3-d98d19e68e6d/deploy-status)](https://app.netlify.com/sites/stupefied-swirles-696fea/deploys)

## Demo

### [Click here](https://www.soumitdas.com/) for the Live Demo

## Getting Started 🚀

Download the .zip file from Github or run the below command to clone the repo locally.

```bash
git clone https://github.com/soumitdas/soumitdas.com.git
```

This project is using HTML and CSS only. Just update the HTML according to your needs.

## Blog workflow

Blog posts are static HTML files under `public/blog/<slug>/index.html`. No build step required — deploy root is `public/`.

- Blog list: `public/blog/index.html`
- Individual posts: `public/blog/<slug>/index.html`

To add a new post:
1. Create `public/blog/<slug>/index.html` using an existing post as template.
2. Add a listing entry in `public/blog/index.html`.
3. Optionally link from the homepage `public/index.html` blog section.

**Future SSG migration**: A static site generator can replace the manual HTML files while keeping `/blog/<slug>/` URLs intact — the directory-per-post structure is forward-compatible.

## License

[MIT licensed](http://opensource.org/licenses/MIT)

## References

Used various resources to create this website. Some of thems are:

- [Portfolio Template](https://github.com/nisarhassan12/portfolio-template) by [nisarhassan12](https://github.com/nisarhassan12)
- [fireship.io](http://fireship.io/)
- [CSS Tricks](http://css-tricks.com/)
