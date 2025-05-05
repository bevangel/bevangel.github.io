# Barbara Evangelista's Blog

A personal blog built with Jekyll, featuring articles about software development, book reviews, and life experiences.

## Features

- Clean, modern design
- Responsive layout
- Category-based organization
- Social media integration
- SEO optimized

## Setup

1. Make sure you have Ruby installed (version 2.5.0 or higher)
2. Install Jekyll and Bundler:
   ```bash
   gem install jekyll bundler
   ```
3. Clone this repository
4. Install dependencies:
   ```bash
   bundle install
   ```
5. Start the development server:
   ```bash
   bundle exec jekyll serve
   ```
6. Visit `http://localhost:4000` in your browser

## Writing Posts

Posts are organized into three categories:
- `_software/` - Technical articles and programming insights
- `_books/` - Book reviews and reading recommendations
- `_life/` - Personal experiences and reflections

To create a new post:
1. Create a new markdown file in the appropriate category directory
2. Add the required front matter:
   ```yaml
   ---
   layout: post
   title: "Your Post Title"
   date: YYYY-MM-DD
   ---
   ```
3. Write your content in Markdown format

## Customization

- Edit `_config.yml` to modify site settings
- Modify `assets/css/main.css` to change the styling
- Update `_layouts/default.html` to modify the site structure

## License

This project is open source and available under the [MIT License](LICENSE). 