---
layout: default
title: Projects
---

<div class="section-title">
    <h2>My Projects</h2>
</div>

<p class="text-center text-muted mb-5" style="max-width: 600px; margin: 0 auto;">
    A collection of independent projects demonstrating my focus in Graph Databases, Semantic Models, and Retrieval-Augmented GenAI solutions.
</p>

<div class="d-flex flex-column gap-5 mt-4">
    <!-- Project 1 -->
    <div class="glass-card">
        <div class="row align-items-center">
            <div class="col-lg-4 mb-4 mb-lg-0">
                <div class="project-img-wrapper mb-0" style="height: 220px;">
                    <img src="{{ "/images/project1.jpeg" | relative_url }}" alt="Fraud Detection Knowledge Graph" style="width: 100%; height: 100%; object-fit: cover;">
                </div>
            </div>
            <div class="col-lg-8">
                <span class="specialty-badge" style="background: rgba(16, 185, 129, 0.15); border-color: rgba(16, 185, 129, 0.3); color: #a7f3d0;">Fintech & Graphs</span>
                <h3 class="gradient-text mt-2 mb-3">Knowledge Graph for Fraud Detection</h3>
                <p class="text-light">
                    Designed and built a real-time transaction query engine using Neo4j to map accounts, credit cards, device fingerprints, and IPs. The graph models entity relationships to identify high-risk behavioral anomalies (e.g. cycle transaction loops, multi-account sharing, and structured deposits).
                </p>
                <div class="tech-badges mb-4">
                    <span class="tech-badge">Neo4j</span>
                    <span class="tech-badge">Cypher</span>
                    <span class="tech-badge">Python</span>
                    <span class="tech-badge">NetworkX</span>
                    <span class="tech-badge">Docker</span>
                </div>
                <a href="https://github.com/gpham93/fraud-detection-graph" class="btn-premium">View Source Code</a>
            </div>
        </div>
    </div>

    <!-- Project 2 -->
    <div class="glass-card">
        <div class="row align-items-center">
            <div class="col-lg-4 mb-4 mb-lg-0">
                <div class="project-img-wrapper mb-0" style="height: 220px;">
                    <img src="{{ "/images/project2.jpeg" | relative_url }}" alt="Movie Recommendation Engine" style="width: 100%; height: 100%; object-fit: cover;">
                </div>
            </div>
            <div class="col-lg-8">
                <span class="specialty-badge" style="background: rgba(6, 182, 212, 0.15); border-color: rgba(6, 182, 212, 0.3); color: #a5f3fc;">Recommender Systems</span>
                <h3 class="gradient-text mt-2 mb-3">Movie Recommendation Engine</h3>
                <p class="text-light">
                    Developed a recommendation engine powered by a custom movie taxonomy and relational rating graph. Links semantic concepts like genre parent-child relationships, actor influence clusters, and director styles with user profile embeddings to generate highly context-aware recommendations.
                </p>
                <div class="tech-badges mb-4">
                    <span class="tech-badge">Neo4j</span>
                    <span class="tech-badge">RDF / SPARQL</span>
                    <span class="tech-badge">FastAPI</span>
                    <span class="tech-badge">Pandas</span>
                    <span class="tech-badge">HTML/CSS/JS</span>
                </div>
                <a href="https://github.com/gpham93/movie-recommendation-graph" class="btn-premium">View Source Code</a>
            </div>
        </div>
    </div>

    <!-- Project 3 -->
    <div class="glass-card">
        <div class="row align-items-center">
            <div class="col-lg-4 mb-4 mb-lg-0">
                <div class="project-img-wrapper mb-0" style="height: 220px;">
                    <img src="{{ "/images/project3.jpeg" | relative_url }}" alt="Gen AI Chatbot for Financial Investing" style="width: 100%; height: 100%; object-fit: cover;">
                </div>
            </div>
            <div class="col-lg-8">
                <span class="specialty-badge" style="background: rgba(139, 92, 246, 0.15); border-color: rgba(139, 92, 246, 0.3); color: #ddd6fe;">Generative AI</span>
                <h3 class="gradient-text mt-2 mb-3">GenAI Investing Chatbot</h3>
                <p class="text-light">
                    Built a retrieval-augmented generation (RAG) agent that parses market filings, earnings call transcripts, and corporate structures into a vector store. The agent queries an indexed knowledge base to deliver context-grounded stock insights, minimizing hallucinations in financial forecasting.
                </p>
                <div class="tech-badges mb-4">
                    <span class="tech-badge">LangChain</span>
                    <span class="tech-badge">OpenAI GPT-4o</span>
                    <span class="tech-badge">Pinecone</span>
                    <span class="tech-badge">Streamlit</span>
                    <span class="tech-badge">Python</span>
                </div>
                <a href="https://github.com/gpham93/financial-investing-chatbot" class="btn-premium">View Source Code</a>
            </div>
        </div>
    </div>

    <!-- Project 4 -->
    <div class="glass-card">
        <div class="row align-items-center">
            <div class="col-lg-4 mb-4 mb-lg-0">
                <div class="project-img-wrapper mb-0" style="height: 220px;">
                    <img src="{{ "/images/soccer.jpg" | relative_url }}" alt="Undefeated XI" style="width: 100%; height: 100%; object-fit: cover;">
                </div>
            </div>
            <div class="col-lg-8">
                <span class="specialty-badge" style="background: rgba(168, 85, 247, 0.15); border-color: rgba(168, 85, 247, 0.3); color: #c084fc;">Mobile Gaming & Stats</span>
                <h3 class="gradient-text mt-2 mb-3">Undefeated XI</h3>
                <p class="text-light">
                    An independent soccer simulator mobile game featuring comprehensive database architecture, player conversion metrics, and advanced team statistics.
                </p>
                <div class="tech-badges mb-4">
                    <span class="tech-badge">SQL</span>
                    <span class="tech-badge">Python</span>
                    <span class="tech-badge">iOS / Swift</span>
                    <span class="tech-badge">SQLite</span>
                    <span class="tech-badge">Analytics</span>
                </div>
                <a href="https://github.com/gpham93/undefeated-xi" class="btn-premium">View Source Code</a>
            </div>
        </div>
    </div>
</div>