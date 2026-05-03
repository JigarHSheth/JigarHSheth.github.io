<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jigar Sheth | Portfolio</title>
    <style>
        :root {
            --primary-color: #2C3E50;
            --secondary-color: #18BC9C;
            --text-color: #333;
            --bg-color: #f4f7f6;
            --white: #ffffff;
        }
         body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            background-color: var(--bg-color);
            margin: 0;
            padding: 0;
        }
          header {
            background-color: var(--primary-color);
            color: var(--white);
            text-align: center;
            padding: 4rem 2rem;
        }
          header h1 {
            margin: 0;
            font-size: 3rem;
            letter-spacing: 2px;
        }
         header p {
            font-size: 1.2rem;
            margin-top: 10px;
            color: var(--secondary-color);
        }

 nav {
            background-color: #fff;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            position: sticky;
            top: 0;
            z-index: 1000;
        }

  nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            margin: 0;
            padding: 1rem;
        }

  nav ul li {
            margin: 0 15px;
        }

   nav ul li a {
            text-decoration: none;
            color: var(--primary-color);
            font-weight: bold;
            transition: color 0.3s ease;
        }

nav ul li a:hover {
            color: var(--secondary-color);
        }

  .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 2rem;
        }

  section {
            background: var(--white);
            padding: 2.5rem;
            margin-bottom: 2rem;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
        }

  h2 {
            color: var(--primary-color);
            border-bottom: 2px solid var(--secondary-color);
            padding-bottom: 10px;
            margin-top: 0;
        }

  .project-card {
            margin-bottom: 1.5rem;
            padding-bottom: 1.5rem;
            border-bottom: 1px solid #eee;
        }

  .project-card:last-child {
            border-bottom: none;
            margin-bottom: 0;
            padding-bottom: 0;
        }

   .project-title {
            font-size: 1.2rem;
            font-weight: bold;
            color: var(--primary-color);
            margin-bottom: 5px;
        }

 .project-role {
            font-style: italic;
            color: #666;
            margin-bottom: 10px;
        }

  ul.publication-list li, ul.project-details li {
            margin-bottom: 10px;
        }

 footer {
            background-color: var(--primary-color);
            color: var(--white);
            text-align: center;
            padding: 2rem;
            margin-top: 2rem;
        }

  footer a {
            color: var(--secondary-color);
            text-decoration: none;
        }
        
  .contact-info {
            font-size: 1.1rem;
            margin-top: 15px;
        }
    </style>
</head>
<body>

<header>
        <h1>Jigar Sheth</h1>
        <p>Bioinformatician & Researcher</p>
    </header>

   <nav>
        <ul>
            <li><a href="#about">About Me</a></li>
            <li><a href="#projects">Research Projects</a></li>
            <li><a href="#publications">Publications</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

   <div class="container">
        <section id="about">
            <h2>About Me</h2>
            <p>I am a Bioinformatician with strong experience in NGS and Nanopore sequencing data analysis, computational drug discovery, and ML pipeline development[cite: 4]. I am highly proficient in managing and transforming large-scale biological datasets into actionable insights using programming languages and high-performance computing (HPC) environments[cite: 5].</p>
            <p>My expertise spans Metagenomics, Transcriptomics, Single-cell genomics, Structural bioinformatics, and Statistical modeling[cite: 6]. I am a keen, motivated researcher, always curious to stay abreast of the latest advancements in bioinformatics[cite: 7].</p>
        </section>

  <section id="projects">
            <h2>Research Projects</h2>
            
  <div class="project-card">
                <div class="project-title">Zoonotic Spillover Surveillance & Pathogen Tracking [cite: 11]</div>
                <div class="project-role">Project Research Scientist-1 | Gujarat Biotechnology Research Centre (GBRC) [cite: 9, 10]</div>
                <ul class="project-details">
                    <li>Built surveillance models for detecting zoonotic spillover in bird-human and animal-human interaction settings using a One Health approach[cite: 11, 21].</li>
                    <li>Analyzed and visualized clinical, bird, and environmental metagenomic data from NGS and Oxford Nanopore platforms[cite: 13].</li>
                    <li>Reported the co-circulation of SARS-CoV-2 and Rhinovirus A and B among bird sanctuary workers[cite: 15].</li>
                    <li>Automated bioinformatics workflows through custom scripting and developed SOPs for reproducible analysis[cite: 14].</li>
                </ul>
            </div>

 <div class="project-card">
                <div class="project-title">Machine Learning for Transcriptomics & Single-Cell Genomics [cite: 30, 44]</div>
                <div class="project-role">ML Research Intern & Graduate Student | University of Manchester [cite: 31, 39, 40]</div>
                <ul class="project-details">
                    <li>Designed a machine learning workflow utilizing Random Forest models to classify single-cell eRNA signatures by tumor subtype[cite: 32, 33].</li>
                    <li>Analyzed GRO-seq and KAS-seq datasets to identify noncoding RNA activity in estrogen response pathways related to breast cancer[cite: 40].</li>
                    <li>Managed data processing on HPC using SLURM and utilized DESeq2, Diffbind, and Bioconductor for transcriptomic analysis[cite: 40].</li>
                </ul>
            </div>

  <div class="project-card">
                <div class="project-title">Structural Bioinformatics & Drug Discovery [cite: 40, 46]</div>
                <div class="project-role">Researcher | University of Manchester & GBU [cite: 40]</div>
                <ul class="project-details">
                    <li>Modeled pH-sensing residues in Lassa Virus to identify therapeutic targets, identifying novel candidate residues H141 and H305[cite: 40].</li>
                    <li>Developed a high-throughput drug repurposing pipeline targeting antimicrobial resistance in ESKAPE pathogens using molecular docking and dynamics simulations[cite: 40].</li>
                </ul>
            </div>
        </section>

 <section id="publications">
            <h2>Publications</h2>
            <ul class="publication-list">
                <li><strong>Subtype-specific enhancer RNAs define transcriptional regulators and prognosis in breast cancers.</strong> [cite: 53]</li>
                <li><strong>In silico structural and mechanical insights into bedaquiline resistance associated with high-grade non-synonymous mutations in atpE, mmpR5, and pepQ.</strong> [cite: 53]</li>
                <li><strong>Designing multi-epitope based peptide vaccine targeting spike protein SARS-CoV-2 B1.1.529 (Omicron) variant using computational approaches.</strong> [cite: 54]</li>
            </ul>
        </section>

   <section id="contact">
            <h2>Contact</h2>
            <p>If you work in Bioinformatics or a related field and want to collaborate, if you're looking to step into Computational Biology, or even if you just want to discuss science, I would be happy to hear from you!</p>
            <div class="contact-info">
                <strong>Email:</strong> <a href="mailto:jigarsheth03@gmail.com">jigarsheth03@gmail.com</a> [cite: 2]<br>
                <strong>GitHub:</strong> <a href="https://github.com/inquisithustler" target="_blank">github.com/inquisithustler</a> <br>
            </div>
        </section>
    </div>

  <footer>
        <p>&copy; 2026 Jigar Sheth. Designed for GitHub Pages.</p>
    </footer>
  <script>
        // Smooth scrolling for navigation links
        document.querySelectorAll('nav a').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
