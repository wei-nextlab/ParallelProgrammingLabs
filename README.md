# ParallelProgammingLabs
FPGA SoC Verilog HLS 

## Publishing the site (GitHub Pages)

This repository uses Jekyll with the `just-the-docs` theme. A GitHub Actions workflow is included to build the site and publish it to the `gh-pages` branch automatically when `main` or `master` is pushed.

- To preview locally:

```bash
gem install bundler
bundle install
bundle exec jekyll serve
```

- The workflow file is at `.github/workflows/gh-pages.yml` and will build the site and publish the generated `_site` directory to the `gh-pages` branch using the built-in `GITHUB_TOKEN`.

- After pushing, enable GitHub Pages in the repository settings (if needed) to serve the `gh-pages` branch.

If you'd like, I can also create a `CNAME` file or configure a custom domain for Pages.
