---
# Homepage
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:

  # ============================================================
  # PROFILE
  # ============================================================
  - block: resume-biography-3
    content:
      username: me
      text: ''
      headings:
        about: 'Professional Summary'
        education: 'Education'
        interests: 'Research Interests'
    design:
      date_format: '2006'
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle


  # ============================================================
  # SELECTED RESEARCH
  # ============================================================
  - block: portfolio
    id: research
    content:
      title: 'Selected Research'
      subtitle: ''
      count: 4
      filters:
        folders:
          - projects
      archive:
        enable: false
    design:
      columns: 2


    # =========================================================
  # SELECTED PUBLICATIONS
  # =========================================================
  - block: markdown
    id: publications
    content:
      title: 'Selected Publications'
      subtitle: ''
      text: |-
        **Bhunia, S.** et al. (2025). *Bursty Acceleration and 3D Trajectories of Electrons in a Solar Flare*. Astronomy & Astrophysics, 695, A136.

        **Bhunia, S.**, Carley, E. P., & Oberoi, D. (2023). *Imaging-spectroscopy of a band-split Type II solar radio burst with the MWA*. Astronomy & Astrophysics, 670, A169.

        [Google Scholar — Full Publication List](https://scholar.google.com/citations?user=XZoiuWsAAAAJ)
    design:
      columns: '1'

  # ============================================================
  # COLLABORATIONS & TECHNICAL RESPONSIBILITIES
  # ============================================================
  - block: markdown
    id: collaborations
    content:
      title: 'Collaborations & Technical Responsibilities'
      subtitle: ''
      text: |-
        ### Chief Observer — [Irish LOFAR Telescope (I-LOFAR)](https://lofar.ie)

        Coordinated telescope observation schedules based on scientific requirements, monitored execution of planned observations, and verified successful data acquisition.

        ### [Bridging Gaps in Heliospheric Radio Data Analyses](https://lc-radio-workshop.github.io/)

        Collaborated with an international team on shared data conventions and interoperable tools for multi-instrument radio observations. Contributor to the open-source [`radiospectra`](https://zenodo.org/records/20719374) Python package.

        ### [Maximising Science from Solar Orbiter’s Solar Flare Campaigns](https://teams.issibern.ch/solarflare/)

        Participated in an international team combining Solar Orbiter observations with complementary ground- and space-based measurements to investigate the temporal and spatial evolution of solar flares.
    design:
      columns: '1'


  # ============================================================
  # TALKS & SEMINARS
  # ============================================================
  - block: markdown
    id: talks
    content:
      title: 'Recent Talks & Seminars'
      subtitle: ''
      text: |-
        **2026/06 — Invited Talk**  
        Community of European Solar Radio Astronomers (CESRA)

        **2026 — Oral Presentation**  
        URSI General Assembly and Scientific Symposium (GASS)

        **2025/12 — Oral Presentation**  
        Science at Low Frequencies (SALF), Orléans, France

        **2025/10 — Invited Seminar**  
        National Centre for Radio Astrophysics (NCRA-TIFR), Pune, India

        **2025/09 — Oral Presentation**  
        XVIIIth Hvar Astrophysical Colloquium, Hvar, Croatia

        **2025/05 — Oral Presentation**  
        In Situ Heliospheric Science Meeting, Lyon, France

        **2024/02 — Oral Presentation**  
        Royal Astronomical Society Specialist Discussion Meeting, London, UK

        **2024/02 — Invited Seminar**  
        Mullard Space Science Laboratory, UK

        
    design:
      columns: '1'


  # ============================================================
  # TECHNICAL SKILLS
  # ============================================================
  - block: markdown
    id: skills
    content:
      title: 'Technical Skills'
      subtitle: ''
      text: |-
        **Signal Processing & Data Analysis**  
        Spectral and time-frequency analysis · transient and quasi-periodic signals · autocorrelation and cross-correlation · peak detection · noise and background estimation · feature extraction

        **Scientific Computing**  
        Python · NumPy · SciPy · pandas · Matplotlib · UNIX/Linux · Git/GitHub · IDL

        **Quantitative & Spatial Analysis**  
        Gaussian fitting · spatial analysis · quantitative source characterization

        **Instrumentation & Observational Analysis**  
        Radio interferometry · calibration · imaging spectroscopy · spectropolarimetry · multi-instrument analysis
    design:
      columns: '1'

  # ============================================================
  # FELLOWSHIPS & AWARDS
  # ============================================================
  - block: markdown
    id: awards
    content:
      title: 'Fellowships & Awards'
      subtitle: ''
      text: |-
        **2023–2024 — ESA Archival Visitor Programme**  
        Funding to conduct research with Dr. Laura Hayes at ESA/ESTEC.

        **2023 — French Research Residency**  
        Funding to conduct research with Dr. Nicole Vilmer at Observatoire de Paris.

        **2020–2024 — Hamilton Scholarship**  
        Dublin Institute for Advanced Studies (DIAS), supporting PhD research.

        **2015–2020 — INSPIRE Scholarship for Higher Education (SHE)**  
        Department of Science and Technology, Government of India, supporting the BS-MS dual degree programme.
    design:
      columns: '1'

  # ============================================================
  # LANGUAGES
  # ============================================================
  - block: markdown
    id: languages
    content:
      title: 'Languages'
      subtitle: ''
      text: |-
        **Bengali** — Native · **English** — Fluent · **Hindi** — Fluent · **French** — Beginner
    design:
      columns: '1'




---
