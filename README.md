# Zenn Content Repository

This repository contains articles and books for [Zenn](https://zenn.dev/).

## Setup

1. Connect this repository to your Zenn account:
   - Go to https://zenn.dev/dashboard/deploys
   - Connect this GitHub repository

2. Configure environment variables:
   ```bash
   export OPENAI_API_KEY="your-openai-api-key"
   export GITHUB_TOKEN="your-github-token"
   export ZENN_REPO_PATH="/Users/yumotoyoshiaki/Desktop/zenn-content"
   ```

## Directory Structure

- `articles/` - Zenn articles (markdown files)
- `books/` - Zenn books

## Using the Auto-Zenn MCP

### Generate an article:
```
generate_article(topic="Next.js", type="tech", length="medium")
```

### Create article file:
```
create_article_file(content="...", filename="nextjs-tutorial.md")
```

### Publish to Zenn:
```
publish_to_zenn(filename="nextjs-tutorial.md", publish_immediately=true)
```

## Commands

- `npx zenn preview` - Preview articles locally
- `npx zenn new:article` - Create new article
- `npx zenn new:book` - Create new book

Generated with Auto-Zenn MCP
