<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Jigar Sheth | Bioinformatics Portfolio</title>

<style>
:root {
    --accent: #00b894;
    --dark: #1e272e;
    --muted: #6c757d;
}

/* FORCE WHITE BACKGROUND */
html, body {
    margin: 0;
    padding: 0;
    background: #ffffff !important;
    color: var(--dark);
    font-family: Arial, sans-serif;
}

/* HERO */
.hero {
    text-align: center;
    padding: 6rem 2rem;
}

.hero h1 {
    font-size: 3rem;
}

/* NAV */
nav {
    background: #ffffff;
    border-bottom: 1px solid #eee;
    text-align: center;
    padding: 1rem;
}

nav a {
    margin: 0 10px;
    text-decoration: none;
    color: var(--dark);
}

/* SECTION */
section {
    max-width: 1000px;
    margin: auto;
    padding: 3rem 1rem;
}

/* GRID */
.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
}

.card {
    border: 1px solid #eee;
    padding: 20px;
    border-radius: 10px;
}

footer {
    text-align: center;
    padding: 2rem;
}
</style>
</head>

<body>

<div class="hero">
    <h1>Jigar Sheth</h1>
    <p>Bioinformatics | NGS | Metagenomics | ML in Biology</p>
</div>

<nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#publications">Publications</a>
</nav>

<section id="about">
    <h2>About Me</h2>
    <p>Bioinformatician specializing in NGS, Nanopore, and metagenomics.</p>
</section>

<section id="projects">
    <h2>Projects</h2>
    <div class="grid">
        <div class="card">Zoonotic Surveillance</div>
        <div class="card">Single-cell ML</div>
        <div class="card">Drug Discovery</div>
    </div>
</section>

<section id="publications">
    <h2>Publications</h2>
    <ul>
        <li>Enhancer RNAs in breast cancer</li>
        <li>Bedaquiline resistance mutations</li>
    </ul>
</section>

<footer>
    © 2026 Jigar Sheth
</footer>

</body>
</html>
