---
layout: default
---

<!doctype html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <title>Markdown Slideshow</title>
    <meta name="description" content="A slideshow created with reveal.js and Markdown.">
    <meta name="author" content="Your Name">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/reveal.js/dist/reveal.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/reveal.js/dist/theme/white.css" id="theme">
    <link rel="stylesheet" href="css/custom.css">
</head>
<body>
    <div class="reveal">
        <div class="slides">
            <section data-markdown="slides/01-slide.md" data-separator="^---$" data-separator-vertical="^--$" data-separator-notes="^Note:"></section>
        </div>
    </div>
    <script src="https://cdn.jsdelivr.net/npm/reveal.js/dist/reveal.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/reveal.js/plugin/markdown/markdown.js"></script>
    <script>
        Reveal.initialize({
            plugins: [ RevealMarkdown ]
        });
    </script>
</body>
</html>
