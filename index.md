---
<a id="top"></a>

<!-- Sticky mini navigation -->

<div class="mini-nav" align="center">
  <a href="#overview">Overview</a> •
  <a href="#topics">Topics</a> •
  <a href="#call-for-papers">CFP</a> •
  <a href="#important-dates-aoe">Dates</a> •
  <a href="#submission">Submission</a> •
  <a href="#program">Program</a> •
  <a href="#organizers">Organizers</a> •
  <a href="#previous-editions">Previous Editions</a> •
  <a href="#contact">Contact</a>
</div>

<section id="overview" class="container band band--alt">
  <h2>Overview</h2>

  <p>
    The workshop <strong>Smarter Extraction of ScholArly MEtadata using Knowledge Graphs and Language Models (SESAME)</strong>
    brings together researchers and practitioners interested in improving scholarly metadata through large language models,
    knowledge graphs, natural language processing, and linked-data technologies.
  </p>

  <p>
    High-quality scholarly metadata is essential for search, discovery, research assessment, reproducibility, and the
    long-term operation of digital-library infrastructures. However, metadata about publications, authors, affiliations,
    datasets, software, models, citations, and other research objects is frequently incomplete, inconsistent, or distributed
    across heterogeneous sources.
  </p>

  <p>
    SESAME focuses on methods that combine language models and structured knowledge to support reliable metadata extraction,
    normalization, enrichment, linking, validation, and evaluation. The workshop provides a platform for researchers,
    digital-library professionals, data curators, infrastructure providers, and policy experts to exchange methods,
    datasets, systems, evaluation practices, and lessons learned.
  </p>

  <p>
    The workshop particularly welcomes work connecting large language models with linked data and knowledge graphs for
    tasks such as author disambiguation, affiliation normalization, citation-context understanding, persistent-identifier
    linking, provenance tracking, and transparent metadata curation.
  </p>
</section>

<section id="topics" class="container">
  <h2>Topics of Interest</h2>

  <p>Topics include, but are not limited to:</p>

  <ul>
    <li>
      <strong>Research Artifact Metadata Modeling and Granularity</strong>
      <ul>
        <li>Metadata for scholarly publications, datasets, software, models, and other research artifacts</li>
        <li>Metadata quality assessment, enrichment, repair, and curation</li>
        <li>Provenance and versioning of scholarly metadata</li>
        <li>Cross-disciplinary and cross-repository metadata interoperability</li>
        <li>Persistent identifiers, including DOI, ORCID, ROR, and related identifier systems</li>
      </ul>
    </li>

```
<li>
  <strong>Large Language Models and NLP for Scholarly Metadata</strong>
  <ul>
    <li>Scholarly metadata extraction using large and small language models</li>
    <li>Prompt engineering, fine-tuning, and retrieval-augmented generation</li>
    <li>Agentic workflows for scholarly information extraction</li>
    <li>Entity recognition, relation extraction, and document understanding</li>
    <li>Author disambiguation and affiliation normalization</li>
    <li>Citation parsing and citation-context analysis</li>
    <li>Extraction from PDFs, tables, figures, supplementary material, and repositories</li>
    <li>Comparisons between LLM-based and traditional extraction methods</li>
  </ul>
</li>

<li>
  <strong>Knowledge Graphs and Linked Data</strong>
  <ul>
    <li>Construction and enrichment of scholarly knowledge graphs</li>
    <li>Linking and aligning entities across repositories and research infrastructures</li>
    <li>Ontology and vocabulary design for scholarly communication</li>
    <li>Entity linking and identity resolution</li>
    <li>Neuro-symbolic and hybrid LLM–knowledge-graph approaches</li>
    <li>Validation using schemas, constraints, and competency questions</li>
    <li>Knowledge-graph applications for discovery, recommendation, and research analytics</li>
  </ul>
</li>

<li>
  <strong>Digital Libraries and Research Infrastructures</strong>
  <ul>
    <li>Integration of metadata workflows into digital-library systems</li>
    <li>Metadata services for repositories and research-information systems</li>
    <li>Benchmarks, datasets, shared tasks, and evaluation frameworks</li>
    <li>System design for metadata-intensive digital-library applications</li>
    <li>Scalable and sustainable metadata-processing infrastructures</li>
    <li>Multilingual and multidisciplinary scholarly communication</li>
  </ul>
</li>

<li>
  <strong>Trustworthiness, Evaluation, and Responsible AI</strong>
  <ul>
    <li>Evaluation of LLM-generated scholarly metadata</li>
    <li>Hallucination detection and factual consistency</li>
    <li>Human-in-the-loop metadata curation</li>
    <li>Explainability, provenance, transparency, and auditability</li>
    <li>Bias, fairness, privacy, copyright, and research ethics</li>
    <li>Metadata for open science, reproducibility, and research integrity</li>
    <li>Policy frameworks and governance for interoperable metadata infrastructures</li>
  </ul>
</li>

<li>
  <strong>Applications, Systems, and Practical Experiences</strong>
  <ul>
    <li>System demonstrations and deployed metadata services</li>
    <li>Case studies from digital libraries and scholarly infrastructures</li>
    <li>Datasets, software tools, and reusable research resources</li>
    <li>Negative results and lessons learned</li>
    <li>Cost, performance, scalability, and deployment considerations</li>
  </ul>
</li>
```

  </ul>
</section>

<section id="call-for-papers" class="container">
  <h2>Call for Papers</h2>

  <p>
    SESAME 2026 invites original contributions addressing the topics listed above. We welcome research papers,
    position papers, system and demonstration papers, dataset papers, benchmark papers, and reports describing
    practical experiences.
  </p>

  <p>
    Submissions should clearly describe:
  </p>

  <ol>
    <li>the scholarly-metadata problem being addressed;</li>
    <li>the role of language models, knowledge graphs, or both;</li>
    <li>the data, system, or methodology used;</li>
    <li>the evaluation procedure and identified limitations; and</li>
    <li>the contribution to digital libraries or scholarly communication.</li>
  </ol>

  <h3>Submission Categories</h3>

  <ul>
    <li><strong>Long Papers:</strong> 6–8 pages, excluding references</li>
    <li><strong>Short or Position Papers:</strong> 2–4 pages, excluding references</li>
    <li><strong>Demo, Dataset, or Benchmark Papers:</strong> 2–4 pages, excluding references</li>
  </ul>

  <p>
    <em>
      Final page limits, formatting requirements, review policy, and proceedings information will be confirmed
      after the host conference has announced its official workshop guidelines.
    </em>
  </p>

  <style>
    /* Local styles for the submission button */
    #submit-btn {
      display: inline-block;
      padding: 0.6rem 1rem;
      border-radius: 8px;
      background-color: #0969da;
      border: 1px solid #0969da;
      color: #ffffff;
      font-weight: 600;
      text-decoration: none;
    }

    #submit-btn:hover,
    #submit-btn:focus {
      background-color: #0550ae;
      border-color: #0550ae;
      color: #ffffff;
      text-decoration: none;
    }

    #submit-btn.disabled {
      background-color: #6e7781;
      border-color: #6e7781;
      cursor: not-allowed;
      pointer-events: none;
    }
  </style>

  <p align="center">
    <span id="submit-btn" class="btn btn-primary disabled">
      Submission System: To Be Announced
    </span>
  </p>
</section>

<section id="important-dates-aoe" class="container band band--alt">
  <h2>Important Dates (AoE)</h2>

  <p>
    All deadlines will use <strong>Anywhere on Earth (AoE)</strong> time.
  </p>

  <ul class="dates">
    <li><strong>Paper submission:</strong> To be announced</li>
    <li><strong>Author notification:</strong> To be announced</li>
    <li><strong>Camera-ready submission:</strong> To be announced</li>
    <li><strong>Workshop date:</strong> To be announced</li>
  </ul>
</section>

<section id="submission" class="container">
  <h2>Submission</h2>

  <p>
    The official submission system and formatting instructions will be published after confirmation by the
    host conference.
  </p>

  <ul>
    <li><strong>Submission site:</strong> To be announced</li>
    <li><strong>Language:</strong> All submissions must be written in English</li>
    <li><strong>Format:</strong> The official proceedings format will be announced</li>
    <li><strong>Review policy:</strong> The anonymization and review policy will be announced</li>
    <li><strong>Supplementary material:</strong> Data, code, models, prompts, and preprints are encouraged where appropriate</li>
  </ul>

  <p>
    Submissions should contain original work and should not be simultaneously under review elsewhere, unless
    the host conference explicitly permits non-archival or previously published contributions.
  </p>
</section>

<section id="program" class="container band band--alt">
  <h2>Program</h2>

  <p>
    The SESAME 2026 workshop program will be published after the paper-review process.
  </p>

  <p>
    The program is expected to include:
  </p>

  <ul>
    <li>invited keynote presentations;</li>
    <li>research-paper presentations;</li>
    <li>short, position, demo, dataset, and benchmark presentations;</li>
    <li>interactive discussion sessions; and</li>
    <li>a panel or community discussion on future research directions.</li>
  </ul>

  <p>
    Accepted papers, speakers, session times, and multi-time-zone information will be added here when confirmed.
  </p>
</section>

<section id="organizers" class="container">
  <h2>Organizers</h2>

  <p>
    <strong>Dr. Muhammad Asif Suryani</strong><br>
    Knowledge Technologies for the Social Sciences (KTS),<br>
    GESIS – Leibniz Institute for the Social Sciences, Cologne, Germany
  </p>

  <p>
    <strong>Dr. Brigitte Mathiak</strong><br>
    Knowledge Technologies for the Social Sciences (KTS),<br>
    GESIS – Leibniz Institute for the Social Sciences, Cologne, Germany
  </p>

  <p>
    <strong>Dr. Florian Reitz</strong><br>
    Schloss Dagstuhl – Leibniz Center for Informatics,<br>
    Wadern, Germany
  </p>

  <p>
    <strong>Dr. Florian Jäckel</strong><br>
    Schloss Dagstuhl – Leibniz Center for Informatics,<br>
    Wadern, Germany
  </p>

  <p>
    <strong> Florian Hauss</strong><br>
    Data Science and Big Data Analytics,<br>
    Ulm University, Ulm, Germany
  </p>

  <p>
    <strong>Prof. Dr. Ansgar Scherp</strong><br>
    Data Science and Big Data Analytics,<br>
    Ulm University, Ulm, Germany
  </p>

  <h3>Program Committee</h3>

  <p>
    The SESAME 2026 Program Committee will be announced soon.
  </p>
</section>

<section class="container band band--alt">
  <h2>Registration</h2>

  <p>
    Registration information will be published after registration for the host conference has opened.
  </p>

  <h2>Venue and Participation</h2>

  <p>
    The workshop venue, participation format, travel information, and online-participation details will be
    announced after confirmation by the host conference.
  </p>

  <h2>Code of Conduct</h2>

  <p>
    SESAME 2026 will follow the code of conduct of its host conference. The official code-of-conduct link
    will be added when available.
  </p>
</section>

<section id="previous-editions" class="container">
  <h2>Previous Editions</h2>

  <ul>
    <li>
      <a href="previous-editions/2025/">
        SESAME 2025 — 1st Workshop
      </a>
    </li>
  </ul>
</section>

<section id="contact" class="container band band--alt">
  <h2>Contact</h2>

  <p>
    Questions? Email
    <a href="mailto:asif.suryani@gesis.org">asif.suryani@gesis.org</a>
    or open an issue in the
    <a href="https://github.com/sesame-workshop/SESAME">SESAME GitHub repository</a>.
  </p>
</section>

<hr>

<p align="center" style="font-size:0.95rem;">
  © 2026 SESAME Organizers •
  <a href="previous-editions/2025/">Previous Edition</a> •
  <a href="mailto:asif.suryani@gesis.org">Contact</a> •
  <a href="https://github.com/sesame-workshop/SESAME">GitHub Repository</a>
</p>

<p align="center">
  <a href="#top">Back to top ↑</a>
</p>
