# Personal-website

Hi, this is my personal website :). reference: [hacked-jekyll] (https://github.com/piazzai/hacked-jekyll/).

## Viewing Locally

To view this Jekyll site on your local machine, follow these steps:

### Prerequisites

- Ruby (version 2.6 or higher) - Already installed ✓
- Bundler gem

### Setup Instructions

1. **Install Bundler** (if not already installed):

   ```bash
   gem install bundler
   ```

2. **Install dependencies**:

   ```bash
   bundle install
   ```

3. **Start the Jekyll server**:

   ```bash
   bundle exec jekyll serve
   ```

   Or simply:

   ```bash
   jekyll serve
   ```

4. **View your site**:
   Open your browser and navigate to:
   ```
   http://localhost:4000
   ```

### Additional Options

- **Enable live reload** (automatically refreshes when files change):

  ```bash
  bundle exec jekyll serve --livereload
  ```

- **Build the site without serving**:
  ```bash
  bundle exec jekyll build
  ```
  The built site will be in the `_site` directory.

### Troubleshooting

- If you get permission errors, you may need to use `sudo` for gem installation (not recommended) or use a Ruby version manager like `rbenv` or `rvm`.
- If port 4000 is already in use, Jekyll will automatically try the next available port (4001, 4002, etc.).
- To stop the server, press `Ctrl+C` in the terminal.
