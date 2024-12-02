# Docker setup and run
    docker run --rm -it -v ${PWD}:/docs squidfunk/mkdocs-material new .
    docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material

# Python setup
    pip install mkdocs-material
    pip install mkdocs-print-site-plugin

# Mkdocs run
    mkdocs serve

# Generate static site
    mkdocs build