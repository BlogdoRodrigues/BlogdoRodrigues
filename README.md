## Blog do Rodrigues

<!--
**BlogdoRodrigues/BlogdoRodrigues** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

echo "# BlogdoRodrigues" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/BlogdoRodrigues/BlogdoRodrigues.git
git push -u origin main

/* Import Google Fonts */
@import url('https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;700&display=swap');

/* Body and Basic Typography */
body {
    font-family: 'Space Grotesk', sans-serif;
    color: #333;
    background-color: #f9f9f9;
    line-height: 1.8;
    padding: 0;
    margin: 0;
}

h1, h2, h3, h4, h5, h6 {
    font-family: 'Space Grotesk', sans-serif;
    color: #222;
    margin-top: 1.2em;
    margin-bottom: 0.5em;
}

a {
    color: #0000ff; /* Azul */
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}

/* Layout */
.container {
    max-width: 900px;
    margin: 0 auto;
    padding: 20px;
    background-color: #fff;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

header {
    text-align: center;
    padding: 40px 0;
}

header h1 {
    font-size: 2.5em;
    margin-bottom: 0.3em;
}

header p {
    font-size: 1.1em;
    color: #555;
}
    display: none;
    padding: 10px 15px;
    background-color: #f0e6dc;
    margin-bottom: 15px;
    border-radius: 5px;
    font-weight: bold;
    cursor: pointer;
    color: #333;
    text-decoration: none;
}

.article-title:hover {
    background-color: #e0d4c1;
}

/* Hide Article Content Initially */
article .content {
    display: none;
    margin-top: 15px;
}

article.visible .content {
    display: block;
}

/* Blog Post Styling */
article {
    margin-bottom: 50px;
}

article h2 {
    font-size: 2em;
    margin-bottom: 0.3em;
}

article p {
    margin-bottom: 1.5em;
}

article img {
    max-width: 100%;
    height: auto;
    display: block;
    margin: 20px auto;
}

blockquote {
    font-style: italic;
    color: #666;
    border-left: 4px solid #ccc;
    padding-left: 16px;
    margin: 1.5em 0;
}

/* Footer */
footer {
    text-align: center;
    padding: 20px 0;
    color: #777;
    font-size: 0.9em;
}

/* Responsive Design */
@media (max-width: 768px) {
    header h1 {
        font-size: 2em;
    }
    
    article h2 {
        font-size: 1.5em;
    }

    .article-title {
        font-size: 1em;
        padding: 10px;
    }
}
