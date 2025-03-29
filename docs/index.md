<div style="position: relative; text-align: center;">
    <!-- Banner Image -->
    <img src="assets/images/suresh_banner.jpeg" alt="Banner" style="width: 100%; height: auto;">

    <!-- Profile Image - Positioned Overlapping the Banner -->
    <img src="assets/images/suresh_profile_image.jpeg" alt="Profile" width="200" style="position: absolute; top: 90%; left: 10%; transform: translate(-50%, -50%); border-radius: 50%; border: 4px solid #ffffff; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);">
</div>

<br /><br/>

<h1>Let's explore <span class="highlight">Behind the CODE</span></h1>


This site features a collection of projects I've contributed to, including open-source contributions, APIs, large-scale data analysis, and scalable systems.


<div class="grid cards" markdown="3">

    <div class="card">
        <img src="assets/images/crosslinking/crosslinking_card.png" alt="Crosslinking">
        <h3>Crosslinking</h3>
        <p>Advanced protein crosslinking analysis tool.</p>
        <div class="technologies">
            <span class="chip">Python</span>
            <span class="chip">Gitlab CI/CD</span>
            <span class="chip">Kubernates</span>
            <span class="chip">OpenStack</span>
        </div>
        <a href="projects/crosslinking">Read more</a>
    </div>

    <div class="card">
        <img src="assets/images/file_download_stats/file_download_stats_card.png" alt="File Download Stats">
        <h3>Nextflow File Download Statistics Pipeline</h3>
        <p>Pipeline to analyze file download statistics.</p>
        <div class="technologies">
            <span class="chip">Nextflow</span>
            <span class="chip">Slurm</span>
            <span class="chip">Dask</span>
            <span class="chip">Parallel Computing</span>
        </div>
        <a href="projects/file_download_stats">Read more</a>
    </div>

    <div class="card">
        <img src="assets/images/orphangenes/orphangenes_card.PNG" alt="Orfan-genes">
        <h3>Orfan-genes</h3>
        <p>Many sequenced genomes reveal that a significant percentage of genes in a given organism's taxon lack orthologous sequences in other taxa. These are called "orphans" or "ORFans" if present in one species or "taxonomically restricted genes" (TRGs) at higher levels. Research on these genes is key to understanding their origins, but current software for identifying them is limited, complex, and has restricted database access. ORFanID is a user-friendly web-based tool that efficiently identifies orphan genes and TRGs across taxonomic levels, using sequences from large bioinformatics repositories like NCBI. It allows users to control search parameters and presents results in sortable, filterable tables with graphical displays of taxonomic trees.</p>
        <div class="technologies">
            <span class="chip">JAVAFX</span>
            <span class="chip">Software Architect</span>
            <span class="chip">Google Cloud</span>
            <span class="chip">AWS</span>
        </div>
        <a href="projects/orfangenes">Read more</a>
    </div>

    <div class="card">
        <img src="assets/images/pridepy/pridepy_card.png" alt="pridepy">
        <h3>pridepy</h3>
        <p>The Proteomics Identification Database (PRIDE) is the world’s largest repository for proteomics data and a founding member of ProteomeXchange. Here, we introduce pridepy, a Python client designed to access PRIDE Archive data, including project metadata and file downloads. pridepy offers a flexible programmatic interface for searching, retrieving, and downloading data via the PRIDE REST API. This tool simplifies the integration of PRIDE datasets into bioinformatics pipelines, making it easier for researchers to handle large datasets programmatically.</p>
        <div class="technologies">
            <span class="chip">Python</span>
            <span class="chip">FTP</span>
            <span class="chip">Globus</span>
            <span class="chip">HPC Cluster</span>
        </div>
        <a href="projects/pridepy">Read more</a>
    </div>

    <div class="card">
        <img src="assets/images/geodiver/geodiver_card.jpg" alt="GeoDiver">
        <h3>GeoDiver</h3>
        <p>GeoDiver is an online web application for performing Differential Gene Expression Analysis (DGEA) and Generally Applicable Gene-set Enrichment Analysis (GAGE) on gene expression datasets from the publicly available Gene Expression Omnibus (GEO). The output produced includes numerous high quality interactive graphics, allowing users to easily explore and examine complex datasets instantly. Furthermore, the results produced can be reviewed at a later date and shared with collaborators.</p>
        <div class="technologies">
            <span class="chip">R language</span>
            <span class="chip">Ruby</span>
            <span class="chip">Sinatra</span>
            <span class="chip">MaterialisedCSS</span>
        </div>
        <a href="projects/geodiver">Read more</a>
    </div>



    <div class="card">
        <img src="assets/images/galaxy/galaxy_card.png" alt="Galaxy Plugin">
        <h3>Galaxy Plugin</h3>
        <p>This project developed ProExtractor, a Java library that extracts proteomics data from mzIdentML files and converts it into a lightweight JSON format. The ProViewer plugin, built with web technologies, visualizes this data interactively in Galaxy. ProExtractor is 83% faster than MzidToHTML, and ProViewer reduces visualization delays by 98% through caching. ProViewer is integrated into Galaxy and available on the public GIO Galaxy server, with an easy installation script for custom servers.</p>
        <div class="technologies">
            <span class="chip">Visualisation</span>
            <span class="chip">Multi-threading</span>
            <span class="chip">AJAX</span>
            <span class="chip">XML parsing</span>
        </div>
        <a href="projects/viz_galaxy_plugin">Read more</a>
    </div>

     <div class="card">
        <img src="assets/images/ocr_neural_network/ocr_neural_network_card.png" alt="OCR System">
        <h3>Automated Bank Cheque Recongition System using OCR</h3>
        <p>Automated bank cheque details extraction using Optical Charactor Recongition system. It was recongising Bank No, Account No which are printed charactors 99%, handwritten date recognised 80% and handwritten amount in letters and numbers 63%.</p>
        <div class="technologies">
            <span class="chip">Neural Networks</span>
            <span class="chip">Mathlab</span>
            <span class="chip">OCR</span>
            <span class="chip">C#.NET</span>
        </div>
        <a href="projects/ocr_neural_network">Read more</a>
    </div>

    <div class="card">
        <img src="assets/images/pride_api_core/pride_api_core_card.png" alt="PRIDE API Core">
        <h3>PRIDE-AI-CORE</h3>
        <p>The Pride-LLM-API is a modular, scalable, and secure API designed for integrating LLM-powered functionalities with structured data storage and retrieval. Built in Python, the project follows a clean architecture with well-defined components.This project act as the base API for AI-driven document processing, retrieval-augmented generation (RAG), and secure NLP applications.</p>
        <div class="technologies">
            <span class="chip">LLM</span>
            <span class="chip">Gemini</span>
            <span class="chip">ChromaDB</span>
            <span class="chip">Prompt Engineering</span>
        </div>
        <a href="projects/pride_api_core">Read more</a>
    </div>
  
</div>

  


   