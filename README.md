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
    --light: #ffffff;
    --muted: #6c757d;
}

body {
    margin: 0;
    font-family: 'Inter', sans-serif;
    background: #ffffff;
    color: var(--dark);
}

/* HERO */
.hero {
    text-align: center;
    padding: 6rem 2rem;
}

.hero h1 {
    font-size: 3.5rem;
    margin: 0;
}

.hero p {
    font-size: 1.2rem;
    color: var(--muted);
    margin: 1rem 0;
}

.btn {
    display: inline-block;
    padding: 10px 20px;
    margin: 10px;
    border-radius: 25px;
    text-decoration: none;
    font-weight: bold;
    border: 1px solid var(--accent);
    color: var(--accent);
    transition: 0.3s;
}

.btn:hover {
    background: var(--accent);
    color: white;
}

/* NAV */
nav {
    position: sticky;
    top: 0;
    background: white;
    border-bottom: 1px solid #eee;
    text-align: center;
    padding: 1rem;
}

nav a {
    margin: 0 15px;
    text-decoration: none;
    color: var(--dark);
    font-weight: 600;
}

/* SECTION */
section {
    max-width: 1100px;
    margin: auto;
    padding: 4rem 2rem;
}

/* GRID PROJECTS */
.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 20px;
}

.card {
    border: 1px solid #eee;
    border-radius: 12px;
    padding: 20px;
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 25px rgba(0,0,0,0.05);
}

/* FOOTER */
footer {
    text-align: center;
    padding: 2rem;
    border-top: 1px solid #eee;
}
</style>
</head>

<body>

<div class="hero">
    <h1>Jigar Sheth</h1>
    <p>Bioinformatics | NGS | Metagenomics | ML in Biology</p>
    <a href="https://github.com/inquisithustler" class="btn">GitHub</a>
    <a href="#contact" class="btn">Contact</a>
</div>

<nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#publications">Publications</a>
</nav>

<section id="about">
    <h2>About Me</h2>
    <p>
        Bioinformatician specializing in NGS, Nanopore, and metagenomics. 
        Experienced in large-scale biological data analysis, ML pipelines, and HPC workflows.
    </p>
</section>

<section id="projects">
    <h2>Projects</h2>
    <div class="grid">

        <div class="card">
            <h3>Zoonotic Surveillance</h3>
            <p>Metagenomic analysis of bird-human transmission using One Health approach.</p>
        </div>

        <div class="card">
            <h3>Single-cell ML</h3>
            <p>Random Forest classification of enhancer RNA signatures in cancer.</p>
        </div>

        <div class="card">
            <h3>Drug Discovery</h3>
            <p>Molecular docking & dynamics for AMR targets.</p>
        </div>

    </div>
</section>

<section id="publications">
    <h2>Publications</h2>
    <ul>
        <li>Enhancer RNAs in breast cancer</li>
        <li>Bedaquiline resistance mutations</li>
        <li>Multi-epitope SARS-CoV-2 vaccine</li>
    </ul>
</section>

<section id="contact">
    <h2>Contact</h2>
    <p>Email: jigarsheth03@gmail.com</p>
</section>

<footer>
    <p>© 2026 Jigar Sheth</p>
</footer>

</body>
</html>
