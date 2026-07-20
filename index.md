---
layout: default
title: Home
---

<!-- Hero Section -->
<section class="hero-container">
    <div class="hero-text-block">
        <span class="specialty-badge">Data Analytics & Consulting</span>
        <h1>Hi, I'm <span class="gradient-text">Gabriel Pham</span></h1>
        <p class="hero-subtitle">Data Analyst & Consultant | Co-Lead of US Graph Capability at Capco. Specializing in Knowledge Graphs, AI, and enterprise data remediation.</p>
        
        <div class="d-flex flex-wrap gap-3">
            <a href="#projects" class="btn-premium">Explore Projects</a>
            <a href="https://1drv.ms/w/s!AjsfM_rVXFdnjAwuHBlj9Nbh1yxl?e=4yuueR" target="_blank" rel="noopener noreferrer" class="btn-premium-outline">
                View Resume
            </a>
        </div>
    </div>
    
    <div class="hero-visual-block">
        <div class="profile-frame">
            <div class="profile-frame-inner">
                <img src="{{ "/images/profile.png" | relative_url }}" alt="Gabriel Pham Profile">
            </div>
        </div>
    </div>
</section>

<!-- Interactive Knowledge Graph Section -->
<section class="graph-section">
    <div class="section-title">
        <h2>Interactive Knowledge Graph</h2>
    </div>
    <p class="text-center text-muted mb-4" style="max-width: 700px; margin: 0 auto;">
        Interactive visual map mapping the connections between my background, core skills, technologies, and projects. Hover over nodes to inspect details, and drag them to adjust layout.
    </p>
    
    <div class="graph-container">
        <canvas id="kg-canvas"></canvas>
        <div class="graph-instruction">
            <span></span> Hover nodes to inspect | Drag to rearrange
        </div>
        <div id="kg-tooltip" class="graph-tooltip"></div>
    </div>
</section>

<!-- Projects Section -->
<section id="projects" class="py-4">
    <div class="section-title">
        <h2>Featured Projects</h2>
    </div>
    
    <div class="projects-grid">
        <!-- Project 0: SEC EDGAR GraphRAG -->
        <div class="glass-card project-card">
            <div class="project-img-wrapper">
                <img src="{{ "/images/AdobeStock_271297554.jpeg" | relative_url }}" alt="SEC EDGAR Knowledge Graph & Agentic GraphRAG">
            </div>
            <h3 class="project-title">SEC EDGAR Agentic GraphRAG</h3>
            <p class="project-desc">Enterprise RDF/OWL knowledge graph & dual-pass hybrid RAG system built on SEC EDGAR 10-Ks with SHACL constraints, Gemini 2.0, and interactive Vis.js visualizer.</p>
            <div class="tech-badges mb-4">
                <span class="tech-badge">RDF/OWL</span>
                <span class="tech-badge">SHACL</span>
                <span class="tech-badge">Gemini 2.0</span>
                <span class="tech-badge">Splink</span>
                <span class="tech-badge">Python</span>
            </div>
            <div class="d-flex gap-2 w-100 mt-auto">
                <a href="https://gpham93.github.io/sec-knowledge-graph/" target="_blank" rel="noopener noreferrer" class="btn-premium flex-grow-1 text-center" style="padding: 0.6rem 0.8rem; font-size: 0.85rem;">Live Demo</a>
                <a href="https://github.com/gpham93/sec-knowledge-graph" target="_blank" rel="noopener noreferrer" class="btn-premium-outline flex-grow-1 text-center" style="padding: 0.6rem 0.8rem; font-size: 0.85rem;">GitHub</a>
            </div>
        </div>

        <!-- Project 1 -->
        <div class="glass-card project-card">
            <div class="project-img-wrapper">
                <img src="{{ "/images/project1.jpeg" | relative_url }}" alt="Fraud Detection Knowledge Graph">
            </div>
            <h3 class="project-title">Fraud Detection Graph</h3>
            <p class="project-desc">A transactional knowledge graph mapping financial interactions in real time to trace asset flows, flag circular transfers, and identify anomalies.</p>
            <div class="tech-badges mb-4">
                <span class="tech-badge">Neo4j</span>
                <span class="tech-badge">Python</span>
                <span class="tech-badge">Cypher</span>
                <span class="tech-badge">NetworkX</span>
            </div>
            <a href="https://github.com/gpham93/fraud-detection-graph" class="btn-premium w-100 mt-auto">View Source</a>
        </div>

        <!-- Project 2 -->
        <div class="glass-card project-card">
            <div class="project-img-wrapper">
                <img src="{{ "/images/project2.jpeg" | relative_url }}" alt="Movie Recommendation Engine">
            </div>
            <h3 class="project-title">Graph Movie Recommender</h3>
            <p class="project-desc">Collaborative filtering recommendation engine built on top of a movie ontology mapping actors, genres, directors, and ratings.</p>
            <div class="tech-badges mb-4">
                <span class="tech-badge">Neo4j</span>
                <span class="tech-badge">Python</span>
                <span class="tech-badge">FastAPI</span>
                <span class="tech-badge">RDF/OWL</span>
            </div>
            <a href="https://github.com/gpham93/movie-recommendation-graph" class="btn-premium w-100 mt-auto">View Source</a>
        </div>

        <!-- Project 3 -->
        <div class="glass-card project-card">
            <div class="project-img-wrapper">
                <img src="{{ "/images/project3.jpeg" | relative_url }}" alt="Gen AI Financial Chatbot">
            </div>
            <h3 class="project-title">GenAI Investing Advisor</h3>
            <p class="project-desc">Context-aware conversational chatbot powered by retrieval-augmented generation (RAG) mapped to a financial knowledge base.</p>
            <div class="tech-badges mb-4">
                <span class="tech-badge">LangChain</span>
                <span class="tech-badge">OpenAI API</span>
                <span class="tech-badge">Pinecone</span>
                <span class="tech-badge">Python</span>
            </div>
            <a href="https://github.com/gpham93/financial-investing-chatbot" class="btn-premium w-100 mt-auto">View Source</a>
        </div>

        <!-- Project 4 -->
        <div class="glass-card project-card">
            <div class="project-img-wrapper">
                <img src="{{ "/images/soccer.jpg" | relative_url }}" alt="Undefeated XI">
            </div>
            <h3 class="project-title">Undefeated XI</h3>
            <p class="project-desc">An independent soccer simulator mobile game featuring comprehensive database architecture, player conversion metrics, and advanced team statistics.</p>
            <div class="tech-badges mb-4">
                <span class="tech-badge">SQL</span>
                <span class="tech-badge">Python</span>
                <span class="tech-badge">iOS / Swift</span>
                <span class="tech-badge">SQLite</span>
                <span class="tech-badge">Analytics</span>
            </div>
            <a href="https://github.com/gpham93/undefeated-xi" class="btn-premium w-100 mt-auto">View Source</a>
        </div>
    </div>
</section>

<!-- Favorite Music Section -->
<section class="music-section">
    <div class="section-title">
        <h2>🎵 Music & Focus</h2>
    </div>
    
    <div class="glass-card">
        <p class="text-muted mb-4 text-center">Here is one of my favorite curation mixes on Spotify that I listen to while coding and working with graph data:</p>
        <div class="spotify-embed-container">
            <iframe style="border-radius:12px" 
                    src="https://open.spotify.com/embed/playlist/37i9dQZF1EVHGWrwldPRtj?utm_source=generator&theme=0" 
                    width="100%" height="352" frameBorder="0" allowfullscreen="" 
                    allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy">
            </iframe>
        </div>
    </div>
</section>

<!-- Script for Interactive Knowledge Graph -->
<script>
document.addEventListener("DOMContentLoaded", function() {
    const canvas = document.getElementById('kg-canvas');
    if (!canvas) return;
    const ctx = canvas.getContext('2d');
    const container = canvas.parentElement;
    const tooltip = document.getElementById('kg-tooltip');

    let canvasWidth = container.clientWidth;
    let canvasHeight = container.clientHeight;

    function resize() {
        canvasWidth = container.clientWidth;
        canvasHeight = container.clientHeight;
        canvas.width = canvasWidth;
        canvas.height = canvasHeight;
    }
    resize();
    
    // Add resize observer or direct event listener
    window.addEventListener('resize', resize);

    // Nodes definition
    const nodes = [
        { id: 'Gabriel Pham', radius: 24, color: '#8b5cf6', category: 'Profile', details: 'Knowledge Graph Lead, Data Analyst & Consultant' },
        { id: 'Capco', radius: 18, color: '#6366f1', category: 'Career', details: 'Consultant & Knowledge Graph Lead' },
        { id: 'Freddie Mac', radius: 18, color: '#3b82f6', category: 'Career', details: 'Capital Markets Data Analyst (Former)' },
        { id: 'Georgia Tech', radius: 18, color: '#eab308', category: 'Education', details: 'M.S. in Economics' },
        { id: 'VCU', radius: 18, color: '#f59e0b', category: 'Education', details: 'B.S. in Economics' },
        { id: 'Knowledge Graphs', radius: 16, color: '#06b6d4', category: 'Expertise', details: 'Semantic Web, RDF/OWL, Neo4j, Linked Data' },
        { id: 'AI & LLMs', radius: 16, color: '#06b6d4', category: 'Expertise', details: 'Generative AI, Chatbots, Prompt Engineering, RAG' },
        { id: 'Data Remediation', radius: 15, color: '#10b981', category: 'Expertise', details: 'Data Quality, Mapping, ETL, Standardization' },
        { id: 'Economics', radius: 15, color: '#ec4899', category: 'Background', details: 'Quantitative analysis, econometrics, behavioral econ' },
        { id: 'Fraud Detection', radius: 15, color: '#06b6d4', category: 'Project', details: 'Knowledge Graph fraud identification pipeline' },
        { id: 'Movie Recommender', radius: 15, color: '#06b6d4', category: 'Project', details: 'Graph-powered collaborative recommender' },
        { id: 'GenAI Chatbot', radius: 15, color: '#06b6d4', category: 'Project', details: 'Context-aware financial advisor chatbot' },
        { id: 'Undefeated XI', radius: 15, color: '#06b6d4', category: 'Project', details: 'Soccer simulator game with statistical databases' },
        { id: 'SEC GraphRAG', radius: 15, color: '#06b6d4', category: 'Project', details: 'Enterprise SEC EDGAR 10-K Knowledge Graph & Hybrid Agentic RAG' },
        { id: 'Neo4j', radius: 12, color: '#14b8a6', category: 'Technology', details: 'Graph Database Management System' },
        { id: 'Python', radius: 12, color: '#14b8a6', category: 'Technology', details: 'General-purpose programming & data analysis' },
        { id: 'SQL', radius: 12, color: '#14b8a6', category: 'Technology', details: 'Relational database query language' }
    ];

    const links = [
        { source: 'Gabriel Pham', target: 'Capco' },
        { source: 'Gabriel Pham', target: 'Freddie Mac' },
        { source: 'Gabriel Pham', target: 'Georgia Tech' },
        { source: 'Gabriel Pham', target: 'VCU' },
        { source: 'Gabriel Pham', target: 'Knowledge Graphs' },
        { source: 'Gabriel Pham', target: 'AI & LLMs' },
        { source: 'Gabriel Pham', target: 'Data Remediation' },
        { source: 'Gabriel Pham', target: 'Economics' },
        { source: 'Capco', target: 'Knowledge Graphs' },
        { source: 'Freddie Mac', target: 'Data Remediation' },
        { source: 'Georgia Tech', target: 'Economics' },
        { source: 'VCU', target: 'Economics' },
        { source: 'Knowledge Graphs', target: 'Fraud Detection' },
        { source: 'Knowledge Graphs', target: 'Movie Recommender' },
        { source: 'AI & LLMs', target: 'GenAI Chatbot' },
        { source: 'Knowledge Graphs', target: 'Neo4j' },
        { source: 'AI & LLMs', target: 'Python' },
        { source: 'Data Remediation', target: 'SQL' },
        { source: 'Fraud Detection', target: 'Neo4j' },
        { source: 'Fraud Detection', target: 'Python' },
        { source: 'Movie Recommender', target: 'Neo4j' },
        { source: 'GenAI Chatbot', target: 'Python' },
        { source: 'Gabriel Pham', target: 'Undefeated XI' },
        { source: 'Undefeated XI', target: 'Python' },
        { source: 'Undefeated XI', target: 'SQL' },
        { source: 'Gabriel Pham', target: 'SEC GraphRAG' },
        { source: 'SEC GraphRAG', target: 'Knowledge Graphs' },
        { source: 'SEC GraphRAG', target: 'AI & LLMs' },
        { source: 'SEC GraphRAG', target: 'Python' }
    ];

    // Build references
    links.forEach(link => {
        link.sourceNode = nodes.find(n => n.id === link.source);
        link.targetNode = nodes.find(n => n.id === link.target);
    });

    // Initialize positions randomly around center
    nodes.forEach(node => {
        node.x = canvasWidth / 2 + (Math.random() - 0.5) * 300;
        node.y = canvasHeight / 2 + (Math.random() - 0.5) * 300;
        node.vx = 0;
        node.vy = 0;
    });

    let hoveredNode = null;
    let draggedNode = null;
    const mouse = { x: 0, y: 0 };

    // Interaction handlers
    canvas.addEventListener('mousemove', e => {
        const rect = canvas.getBoundingClientRect();
        mouse.x = e.clientX - rect.left;
        mouse.y = e.clientY - rect.top;

        if (draggedNode) {
            draggedNode.x = mouse.x;
            draggedNode.y = mouse.y;
            return;
        }

        let found = null;
        for (let i = 0; i < nodes.length; i++) {
            const n = nodes[i];
            const dx = n.x - mouse.x;
            const dy = n.y - mouse.y;
            const dist = Math.sqrt(dx * dx + dy * dy);
            if (dist <= n.radius) {
                found = n;
                break;
            }
        }

        if (found !== hoveredNode) {
            hoveredNode = found;
            if (hoveredNode) {
                canvas.style.cursor = 'grab';
                tooltip.style.display = 'block';
                tooltip.style.left = `${e.clientX - rect.left + 15}px`;
                tooltip.style.top = `${e.clientY - rect.top + 15}px`;
                tooltip.innerHTML = `
                    <h5 style="margin:0 0 4px 0; color:#fff; font-size:0.95rem;">${hoveredNode.id}</h5>
                    <span style="display:inline-block; background-color:${hoveredNode.color}; color:#fff; border-radius:4px; padding:2px 6px; font-size:0.65rem; font-weight:bold; margin-bottom:6px;">${hoveredNode.category}</span>
                    <p style="margin:0; font-size:0.75rem; color:#94a3b8; line-height:1.3;">${hoveredNode.details}</p>
                `;
            } else {
                canvas.style.cursor = 'default';
                tooltip.style.display = 'none';
            }
        } else if (hoveredNode) {
            tooltip.style.left = `${e.clientX - rect.left + 15}px`;
            tooltip.style.top = `${e.clientY - rect.top + 15}px`;
        }
    });

    canvas.addEventListener('mousedown', () => {
        if (hoveredNode) {
            draggedNode = hoveredNode;
            canvas.style.cursor = 'grabbing';
        }
    });

    window.addEventListener('mouseup', () => {
        if (draggedNode) {
            draggedNode = null;
            canvas.style.cursor = hoveredNode ? 'grab' : 'default';
        }
    });

    // Main animation loop
    function loop() {
        // Physics update
        const center = { x: canvasWidth / 2, y: canvasHeight / 2 };

        // Center pull gravity
        nodes.forEach(node => {
            const dx = center.x - node.x;
            const dy = center.y - node.y;
            const dist = Math.sqrt(dx * dx + dy * dy);
            if (dist > 0) {
                node.vx += (dx / dist) * 0.04;
                node.vy += (dy / dist) * 0.04;
            }
        });

        // Coulomb Repulsion
        for (let i = 0; i < nodes.length; i++) {
            const n1 = nodes[i];
            for (let j = i + 1; j < nodes.length; j++) {
                const n2 = nodes[j];
                const dx = n2.x - n1.x;
                const dy = n2.y - n1.y;
                const dist = Math.sqrt(dx * dx + dy * dy) || 1;
                
                const minDist = n1.radius + n2.radius + 50;
                if (dist < minDist) {
                    const force = (minDist - dist) * 0.25;
                    const fx = (dx / dist) * force;
                    const fy = (dy / dist) * force;
                    n1.vx -= fx;
                    n1.vy -= fy;
                    n2.vx += fx;
                    n2.vy += fy;
                } else {
                    const force = 180 / (dist * dist);
                    const fx = (dx / dist) * force;
                    const fy = (dy / dist) * force;
                    n1.vx -= fx;
                    n1.vy -= fy;
                    n2.vx += fx;
                    n2.vy += fy;
                }
            }
        }

        // Spring Attraction
        links.forEach(link => {
            const n1 = link.sourceNode;
            const n2 = link.targetNode;
            if (!n1 || !n2) return;
            const dx = n2.x - n1.x;
            const dy = n2.y - n1.y;
            const dist = Math.sqrt(dx * dx + dy * dy) || 1;
            const desiredLength = 90;
            const force = (dist - desiredLength) * 0.04;
            
            const fx = (dx / dist) * force;
            const fy = (dy / dist) * force;
            
            n1.vx += fx;
            n1.vy += fy;
            n2.vx -= fx;
            n2.vy -= fy;
        });

        // Step coordinates
        nodes.forEach(node => {
            if (node === draggedNode) {
                node.x = mouse.x;
                node.y = mouse.y;
                node.vx = 0;
                node.vy = 0;
            } else {
                node.vx *= 0.82;
                node.vy *= 0.82;
                node.x += node.vx;
                node.y += node.vy;

                // Keep inside canvas bounds
                node.x = Math.max(node.radius + 15, Math.min(canvasWidth - node.radius - 15, node.x));
                node.y = Math.max(node.radius + 15, Math.min(canvasHeight - node.radius - 15, node.y));
            }
        });

        // RENDER DRAWINGS
        ctx.clearRect(0, 0, canvasWidth, canvasHeight);

        // Draw Links
        links.forEach(link => {
            const n1 = link.sourceNode;
            const n2 = link.targetNode;
            if (!n1 || !n2) return;

            let isHighlighted = false;
            if (hoveredNode) {
                isHighlighted = (n1.id === hoveredNode.id || n2.id === hoveredNode.id);
            }

            ctx.beginPath();
            ctx.moveTo(n1.x, n1.y);
            ctx.lineTo(n2.x, n2.y);
            
            if (hoveredNode) {
                if (isHighlighted) {
                    ctx.strokeStyle = '#6366f1';
                    ctx.lineWidth = 2.5;
                    ctx.shadowColor = '#6366f1';
                    ctx.shadowBlur = 4;
                } else {
                    ctx.strokeStyle = 'rgba(255, 255, 255, 0.03)';
                    ctx.lineWidth = 1;
                    ctx.shadowBlur = 0;
                }
            } else {
                ctx.strokeStyle = 'rgba(255, 255, 255, 0.08)';
                ctx.lineWidth = 1.2;
                ctx.shadowBlur = 0;
            }
            ctx.stroke();
        });
        
        // Reset shadow for nodes
        ctx.shadowBlur = 0;

        // Draw Nodes
        nodes.forEach(node => {
            const isHovered = (hoveredNode && node.id === hoveredNode.id);
            const isNeighbor = hoveredNode && links.some(link => 
                (link.sourceNode.id === hoveredNode.id && link.targetNode.id === node.id) ||
                (link.targetNode.id === hoveredNode.id && link.sourceNode.id === node.id)
            );

            ctx.beginPath();
            ctx.arc(node.x, node.y, node.radius, 0, 2 * Math.PI);
            
            // Draw radial gradient for node
            const gradient = ctx.createRadialGradient(node.x - 2, node.y - 2, 2, node.x, node.y, node.radius);
            gradient.addColorStop(0, adjustColorBrightness(node.color, 40));
            gradient.addColorStop(1, node.color);
            ctx.fillStyle = gradient;

            // Highlight glow effects
            if (isHovered) {
                ctx.shadowBlur = 20;
                ctx.shadowColor = node.color;
                ctx.strokeStyle = '#ffffff';
                ctx.lineWidth = 2;
            } else if (isNeighbor) {
                ctx.shadowBlur = 10;
                ctx.shadowColor = node.color;
                ctx.strokeStyle = 'rgba(255, 255, 255, 0.5)';
                ctx.lineWidth = 1.5;
            } else {
                ctx.shadowBlur = 0;
                ctx.strokeStyle = 'rgba(255, 255, 255, 0.15)';
                ctx.lineWidth = 1;
            }
            
            ctx.fill();
            ctx.stroke();
            
            // Draw Labels
            ctx.shadowBlur = 0; // turn off shadow for text
            ctx.fillStyle = '#ffffff';
            ctx.font = `600 ${node.radius > 18 ? '12px' : '10px'} 'Plus Jakarta Sans', sans-serif`;
            ctx.textAlign = 'center';
            ctx.textBaseline = 'middle';
            
            // Text stroke for readability
            ctx.strokeStyle = '#000000';
            ctx.lineWidth = 3;
            ctx.strokeText(node.id, node.x, node.y);
            ctx.fillText(node.id, node.x, node.y);
        });

        requestAnimationFrame(loop);
    }

    // Helper function to dynamically adjust hex color brightness
    function adjustColorBrightness(hex, percent) {
        let R = parseInt(hex.substring(1, 3), 16);
        let G = parseInt(hex.substring(3, 5), 16);
        let B = parseInt(hex.substring(5, 7), 16);

        R = parseInt(R * (100 + percent) / 100);
        G = parseInt(G * (100 + percent) / 100);
        B = parseInt(B * (100 + percent) / 100);

        R = (R < 255) ? R : 255;
        G = (G < 255) ? G : 255;
        B = (B < 255) ? B : 255;

        const rHex = ((R.toString(16).length === 1) ? "0" + R.toString(16) : R.toString(16));
        const gHex = ((G.toString(16).length === 1) ? "0" + G.toString(16) : G.toString(16));
        const bHex = ((B.toString(16).length === 1) ? "0" + B.toString(16) : B.toString(16));

        return "#" + rHex + gHex + bHex;
    }

    loop();
});
</script>
