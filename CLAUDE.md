# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Site Information
- Site is built with Jekyll using the jekyll-theme-hacker theme
- Blog posts are stored in directories by category and date (YYYY/MM/DD)
- The site is hosted on GitHub Pages
- All new posts must be created in English

## Creating New Posts
- Create new posts in appropriate directory structure (category/YYYY/MM/DD/post-name.html)
- Use front matter with layout: post, title, date, categories, tags, author
- Follow existing post format with proper HTML structure
- Categories are used for URL paths (e.g., infosec/pentest/YYYY/MM/DD/post-name.html)
- Date format in front matter: YYYY-MM-DD HH:MM:SS -0300
- Use current date for new posts
- Include a brief description in the post front matter

## Homepage Updates
- Update index.html with new post entries when creating new content
- Add posts at the top of the list with the latest date
- Format: date, title, link, and brief description

## Site Testing
- Test locally with: `bundle exec jekyll serve`
- Check site structure with: `bundle exec jekyll build --verbose`