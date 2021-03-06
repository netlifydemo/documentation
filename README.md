# Netlify Docs

This is the documentation for Netlify.

It's built with [mkdocs](mkdocs.org), a static site generator for documentation.

We use Netlify for continuous deployment, so every time we accepts a pull request for this repository the changes will automatically be rebuilt and deployed to http://docs.netlify.com

## Running locally

```bash
git clone https://github.com/netlify/docs.git netlify-docs
cd netlify-docs
pip install requirements.txt
mkdocs serve
```

Now you'll be able to view the docs at http://localhost:8000/
