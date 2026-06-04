# Personal Website

## Local Development

### Prerequisites
- Ruby (version 2.5 or higher)
- Bundler

### Setup

1. Install dependencies:
   ```bash
   bundle install
   ```

2. Run the development server:
   ```bash
   bundle exec jekyll serve
   ```

3. Open your browser and navigate to:
   ```
   http://localhost:4000
   ```

The site will automatically rebuild when you make changes to the files.

### Building the Site

To build the static site without running a server:
```bash
bundle exec jekyll build
```

The generated site will be in the `_site` directory.
