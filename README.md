<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name — AI-Driven Drug Discovery Researcher</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --bg-color: #0f172a;
            --card-bg: #1e293b;
            --text-main: #f8fafc;
            --text-muted: #94a3b8;
            --accent: #38bdf8;
            --accent-glow: rgba(56, 189, 248, 0.15);
            --border: #334155;
        }
        * { box-sizing: border-box; margin: 0; padding: 0; }
        body {
            font-family: 'Inter', sans-serif;
            background-color: var(--bg-color);
            color: var(--text-main);
            line-height: 1.6;
            padding: 0 1rem;
        }
        header {
            max-width: 1100px;
            margin: 2rem auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 1px solid var(--border);
            padding-bottom: 1rem;
        }
        header a.logo {
            font-weight: 700;
            font-size: 1.2rem;
            color: var(--text-main);
            text-decoration: none;
        }
        nav a {
            color: var(--text-muted);
            text-decoration: none;
            margin-left: 1.5rem;
            font-size: 0.95rem;
            transition: color 0.2s;
        }
        nav a:hover { color: var(--accent); }
        main { max-width: 1100px; margin: 0 auto; }
        
        /* Hero Section */
        .hero {
            display: grid;
            grid-template-columns: 2fr 1fr;
            gap: 3rem;
            padding: 4rem 0;
            align-items: start;
        }
        @media (max-width: 768px) { .hero { grid-template-columns: 1fr; } }
        .hero-content p.tagline {
            color: var(--accent);
            font-weight: 600;
            margin-bottom: 0.5rem;
            text-transform: uppercase;
            font-size: 0.85rem;
            letter-spacing: 0.05em;
        }
        .hero-content h1 {
            font-size: 2.75rem;
            font-weight: 700;
            margin-bottom: 1rem;
            letter-spacing: -0.02em;
        }
        .hero-content p {
            color: var(--text-muted);
            margin-bottom: 1.5rem;
            font-size: 1.05rem;
        }
        .cta-buttons {
            display: flex;
            gap: 1rem;
            margin-top: 2rem;
        }
        .btn {
            padding: 0.75rem 1.5rem;
            border-radius: 6px;
            font-weight: 500;
            text-decoration: none;
            font-size: 0.95rem;
            transition: all 0.2s;
        }
        .btn-primary {
            background-color: var(--accent);
            color: #0f172a;
        }
        .btn-primary:hover { background-color: #7dd3fc; }
        .btn-outline {
            border: 1px solid var(--border);
            color: var(--text-main);
        }
        .btn-outline:hover { border-color: var(--accent); color: var(--accent); }

        /* Sidebar card */
        .sidebar-card {
            background: var(--card-bg);
            border: 1px solid var(--border);
            border-radius: 12px;
            padding: 1.5rem;
            text-align: center;
        }
        .sidebar-card img {
            width: 140px;
            height: 140px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 1rem;
            border: 2px solid var(--accent);
        }
        .social-links {
            display: flex;
            justify-content: center;
            gap: 1rem;
            margin-top: 1rem;
        }
        .social-links a { color: var(--text-muted); text-decoration: none; font-size: 0.9rem; }
        .social-links a:hover { color: var(--accent); }

        /* Sections */
        section { padding: 4rem 0; border-top: 1px solid var(--border); }
        section h2 { font-size: 2rem; margin-bottom: 2rem; letter-spacing: -0.01em; }
        
        /* Grid Cards */
        .grid-3 {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1.5rem;
        }
        .card {
            background: var(--card-bg);
            border: 1px solid var(--border);
            border-radius: 8px;
            padding: 1.5rem;
            transition: transform 0.2s, border-color 0.2s;
        }
        .card:hover {
            transform: translateY(-3px);
            border-color: var(--accent);
        }
        .card h3 { margin-bottom: 0.75rem; font-size: 1.2rem; }
        .card p { color: var(--text-muted); font-size: 0.95rem; }

        footer {
            text-align: center;
            padding: 3rem 0;
            color: var(--text-muted);
            font-size: 0.85rem;
            border-top: 1px solid var(--border);
        }
    </style>
</head>
<body>

    <header>
        <a href="#" class="logo">Dr. / Researcher Name</a>
        <nav>
            <a href="#about">About</a>
            <a href="#research">Research</a>
            <a href="#projects">Projects</a>
            <a href="#publications">Publications</a>
        </nav>
    </header>

    <main>
        <!-- Hero Section -->
        <section class="hero" style="border-top: none;">
            <div class="hero-content">
                <p class="tagline">AI-Driven Drug Discovery Researcher &amp; Computational Biologist</p>
                <h1>Designing Next-Gen Therapeutics via AI &amp; Physics</h1>
                <p>
                    I bridge structural biology, quantum mechanics, and deep learning to accelerate therapeutic discovery. My work pioneers multi-modal frameworks integrating molecular dynamics simulations and network topology for complex pharmacological targets.
                </p>
                <p>
                    Currently building computational pipelines for novel antiviral and precision therapeutics. Actively seeking high-impact PhD / Research positions.
                </p>
                <div class="cta-buttons">
                    <a href="#projects" class="btn btn-primary">View Frameworks</a>
                    <a href="mailto:your.email@domain.com" class="btn btn-outline">Direct Contact</a>
                </div>
            </div>
            <div class="sidebar-card">
                <!-- Replace with your actual portrait image path -->
                <img src="images/profile-placeholder.jpg" alt="Professional Portrait">
                <p style="font-size: 0.9rem; color: var(--text-muted); margin-bottom: 0.5rem;">Based in [Your Location]</p>
                <div class="social-links">
                    <a href="https://github.com/yourusername" target="_blank">GitHub</a>
                    <a href="https://linkedin.com/in/yourusername" target="_blank">LinkedIn</a>
                    <a href="https://scholar.google.com" target="_blank">Scholar</a>
                </div>
            </div>
        </section>

        <!-- Research Expertise -->
        <section id="research">
            <h2>Core Research Pillars</h2>
            <div class="grid-3">
                <div class="card">
                    <h3>Systems Pharmacology &amp; Networks</h3>
                    <p>Mapping complex biological networks, identifying polypharmacological targets, and using network topology to assess systemic drug impact and drug-repurposing pipelines.</p>
                </div>
                <div class="card">
                    <h3>Molecular Dynamics &amp; QM</h3>
                    <p>Conducting high-throughput docking, classical molecular dynamics simulations, and quantum mechanical calculations to probe binding free energies and conformational states.</p>
                </div>
                <div class="card">
                    <h3>Generative AI &amp; GNNs</h3>
                    <p>Deploying geometric deep learning, graph neural networks, and generative models to engineer de novo molecular candidates with optimized ADMET profiles.</p>
                </div>
            </div>
        </section>

        <!-- Featured Projects / Frameworks -->
        <section id="projects">
            <h2>Featured Framework</h2>
            <div class="card" style="display: grid; grid-template-columns: 2fr 1fr; gap: 2rem; align-items: center;">
                <div>
                    <span style="color: var(--accent); font-size: 0.85rem; font-weight: 600;">RSC MEDICINAL CHEMISTRY TEMPLATE</span>
                    <h3 style="margin: 0.5rem 0; font-size: 1.5rem;">Systems Pharmacology-Driven Discovery of Tri-Modal Anti-Mpox Therapeutics</h3>
                    <p style="margin-bottom: 1rem;">
                        Developed an integrated in-silico framework uniting Quantum Mechanics, Molecular Dynamics, and Network Topology. Identified three distinct lead candidates through rigorous computational evaluation of antiviral targets.
                    </p>
                    <a href="#" class="btn btn-outline" style="display: inline-block;">Read Manuscript Overview</a>
                </div>
                <div style="background: var(--bg-color); padding: 1.5rem; border-radius: 6px; border: 1px solid var(--border); text-align: center;">
                    <p style="font-size: 0.85rem; color: var(--text-muted);">Methodology Pipeline</p>
                    <p style="font-weight: 600; color: var(--accent); margin-top: 0.5rem;">QM ➔ MD ➔ Network Topology</p>
                </div>
            </div>
        </section>

        <!-- Publications Placeholder -->
        <section id="publications">
            <h2>Selected Publications &amp; Preprints</h2>
            <div style="display: flex; flex-direction: column; gap: 1rem;">
                <div class="card">
                    <span style="font-size: 0.8rem; color: var(--accent);">RSC Medicinal Chemistry (Template / In Review)</span>
                    <h4 style="font-size: 1.1rem; margin: 0.25rem 0;">Systems Pharmacology-Driven Discovery of Tri-Modal Anti-Mpox Therapeutics</h4>
                    <p>Your Name et al., 2026.</p>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 Your Name. Built for precision science.</p>
    </footer>

</body>
</html>
