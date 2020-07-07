
# Start

## My Environment
```
λ python --version
Python 3.8.3

λ pip --version
pip 20.1.1 
```

## Install

```py
pip install mkdocs

# Plugs
pip install mkdocs-minify-plugin
pip install mkdocs-git-revision-date-localized-plugin
```

# Command

```

# Start Serve
mkdocs serve

# Build Static pages
mkdocs build
mkdocs build --clean # Clean Cache
```

- Static pages all in ./site

# Deploy gh-pages
```
mkdocs gh-deploy --clean
```