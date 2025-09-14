# L'Aurore du pain

A local bakery website with multilingual support, built with Jekyll and Markdown.

## Languages
- [English](/en/)
- [Français](/fr/)

## Local Development

This is a Jekyll site. To run it locally:

### Prerequisites
- Ruby 3.3.0+ (managed with rbenv)
- Bundler gem

### Setup
1. Install dependencies:
   ```bash
   bundle install
   ```

2. Start the Jekyll server:
   ```bash
   bundle exec jekyll serve --livereload
   ```

3. Visit http://localhost:4000

### Content Management
- Edit `fr/index.md` for French content
- Edit `en/index.md` for English content
- Edit `_layouts/default.html` for styling changes

The site will automatically rebuild when you make changes (live reload enabled).

### Troubleshooting

**Live reload port conflict:**
If you see "port is in use" errors with live reload, try:
```bash
bundle exec jekyll serve
```
(without `--livereload`)

**Ruby warnings:**
The CSV and base64 warnings are fixed in the current Gemfile. If you see them, run:
```bash
bundle install
```
