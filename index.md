<!-- index.md -->

<style>
  .nav-buttons {
    margin-bottom: 1.2rem;
  }

  .nav-buttons a {
    display: inline-block;
    background-color: #1C3F5A;    /* deep navy blue */
    color: white;
    padding: 0.3rem 0.6rem;       /* smaller buttons */
    margin-right: 0.3rem;
    font-size: 0.85rem;
    text-decoration: none;
    border-radius: 3px;
    font-weight: 600;
  }

  .nav-buttons a:hover {
    background-color: #162F44;   /* darker navy hover */
  }

  /* Headings in deep navy */
  h1 { color: #1C3F5A; }
  h2 { color: #1C3F5A; }
  h3 { color: #1C3F5A; }

  /* If you want h3 to stay blue-ish rather than navy: */
  /* h3 { color: #1C538E; } */
</style>

<div class="nav-buttons">
  <a href="#description">Description</a>
  <a href="#call-for-presentations">Call for Presentations</a>
  <a href="#key-dates">Key Dates</a>
  <a href="#organizers">Organizers</a>
  <a href="#agenda-materials">Agenda & Materials</a>
</div>

![Arch4Health Logo](arch4health-logo3.jpeg){: width="700px" }

<h3 style="color: #7F7FFF;font-style: italic;">
  A half-day workshop exploring the key computational challenges in health-related applications <br> 
  and the vital role of computing system design in overcoming them to advance healthcare
</h3>

**29th September 2026, Prague, Czechia**  
**In conjunction with [the 32nd Symposium on Operating Systems Principles 2026 (SOSP 2026)](https://sigops.org/s/conferences/sosp/2026/)**

## Workshop Description {#description}

**<span style="color: #7F7FFF;">Opportunities</span>.** Recent biotechnological advances enable high-throughput, low-cost, and accurate biological data generation (e.g., using genome sequencing, multimodal medical imaging, continuous wearable sensing). This wealth of data enables unique opportunities for advancing healthcare. These opportunities include, but are not limited to, precision medicine, bedside personalized care, discovering early warning signs of communicable diseases, continuous physiological tracking, and enhanced diagnostic capabilities.

**<span style="color: #7F7FFF;">Challenges</span>.** Despite these opportunities, efficiently analyzing large-scale biological data poses significant challenges for conventional computing systems. These systems often cannot keep up with the high-throughput rate at which data is generated, and they face additional constraints related to energy efficiency, scalability, privacy, and security. High-throughput processing is particularly crucial in clinical settings, where real-time data processing can significantly impact patient outcomes by improving both response times in time-critical scenarios as well as the decision-making processes for therapeutic schemes. Therefore, to facilitate the wide adoption of recent advances in healthcare, there is a need to optimize the computing systems to enable high-performance, energy-efficient, low-cost, private, and secure analysis of biological data.

**<span style="color: #7F7FFF;">Architecture for Health</span>.** This workshop will focus on identifying key computational challenges in health-related applications and discussing how computer architects can contribute to advancing healthcare by addressing these challenges. First, we will provide invited talks and keynotes that summarize (i) a series of research in computing system designs for healthcare applications and (ii) new trends and bottlenecks in data-intensive healthcare applications. Second, we will invite researchers to submit their ongoing work on these topics.

**<span style="color: #7F7FFF;">Fostering Diverse and Cross-Disciplinary Discussions</span>.** Since cross-disciplinary discussions are crucial for better identifying challenges in real-world health-related applications, we aim to foster open discussions and cooperation between researchers with diverse backgrounds (i.e., from both computer architecture and health sciences communities, industry, and academia).


## Call for Presentations {#call-for-presentations}

This workshop consists of talks on the general topic of computing system designs for healthcare applications and new trends and bottlenecks in data-intensive healthcare applications. There are a limited number of slots for talks. If you are interested in delivering a talk on related topics, **please submit your talk's title and extended abstract via <a href="https://docs.google.com/forms/d/e/1FAIpQLSfVEc_Bm2eaRYAyskezGPs_buNmVYzcfbMnu232hXnth2L7nA/viewform">this Google Form</a>**. You may either paste the abstract directly into the form or upload a two-page PDF prepared in any standard conference template. Each submission must include the talk title, all authors' names, and their affiliations.

We invite abstract submissions related to (but not limited to) the following topics:

- Computational Biology
  - Genomics
  - Metagenomics
  - Gene editing
  - Drug Design and Discovery
  - Proteomics
  - Other Areas in Precision Medicine
- Neuroscience
  - Brain-Machine Interfaces
  - Prosthetics
- Wearable Systems for Health
- Medical robotics
  - Surgery
  - Haptics
- Mental Health
- Medical Imaging
  - Brain scans
  - Radiology
  - Single-Cell Analysis
- Agent-Based Simulations
- Medical Privacy
- Bio-Sensors

## Key Dates {#key-dates}

- **Extended Abstract Submission Deadline:** 28 August 2026
- **Notification:** 4 September 2026
- **Workshop Date:** 29 September 2026

## Organizers {#organizers}

<style>
  .organizers { 
    display: flex; 
    flex-direction: column; 
    gap: 2rem; 
  }
  .organizer {
    display: flex;
    align-items: flex-start;       /* keep photo & bio top-aligned */
  }
  .organizer .photo-name {
    width: 120px;                  /* FIXED WIDTH so all bios start at same x */
    text-align: center;
    margin-right: 1.5rem;
  }
  .organizer .photo-name img {
    width: 120px;
    height: auto;
    border-radius: 8px;
    display: block;
    margin-bottom: 0.5rem;
  }
  .organizer .photo-name p {
    margin: 0;
    font-weight: bold;
  }
  .organizer .bio {
    flex: 1;
  }
  .organizer .bio p {
    margin: 0.25rem 0;             /* spacing between bio paragraphs */
  }
  .organizer .bio p:first-child {
    margin-top: 0;                 /* flush top margin */
  }
</style>

<div class="organizers">

  <div class="organizer">
    <div class="photo-name">
      <img src="{{ 'nika_pic.jpeg' | relative_url }}" alt="Nika Mansouri Ghiasi">
      <p><a href="https://sites.google.com/view/nikamansourighiasi/" style="color: inherit; text-decoration: none;">Nika Mansouri Ghiasi</a></p>
    </div>
    <div class="bio">
      <p>Email: <a href="mailto:nika.mansourighiasi@safari.ethz.ch">nika.mansourighiasi@safari.ethz.ch</a></p>
      <p>Nika Mansouri Ghiasi is a PhD student in the SAFARI Research Group at ETH Zurich, advised by Professor Onur Mutlu. Her research interests are in computer architecture and computational biology, focusing on 1) storage systems, large-scale bioinformatics applications, and their interactions, and 2) emerging technologies such as ultra-dense 3D integrated systems. She is interested in designing high-performance, energy-efficient, and low-cost systems that facilitate the widespread adoption of data-intensive applications needed in healthcare and precision medicine. For more information, please see her website: <a href="https://bit.ly/nikamgh">bit.ly/nikamgh</a>.</p>
    </div>
  </div>

  <div class="organizer">
    <div class="photo-name">
      <img src="{{ 'konstantina_pic.jpeg' | relative_url }}" alt="Dr. Konstantina Koliogeorgi">
      <p><a href="https://ihpcs.ethz.ch/people/person-detail.MzQ0MTU2.TGlzdC8zOTQxLDc2NTU1MzE0Mg==.html" style="color: inherit; text-decoration: none;">Dr. Konstantina Koliogeorgi</a></p>
    </div>
    <div class="bio">
      <p>Email: <a href="mailto:kkoliogeorgi@ethz.ch">kkoliogeorgi@ethz.ch</a></p>
      <p>Konstantina Koliogeorgi is a Postdoctoral Researcher at the SAFARI Research Group at ETH Zurich, led by Prof. Onur Mutlu. She received her Ph.D. degree in Electrical and Computer Engineering in 2023 at National Technical University of Athens (NTUA), advised by Prof. Dimitrios Soudris. Her research interests are in the field of computer systems and architecture, heterogeneous computing, and hardware acceleration. Her research has focused on hardware-software co-design, efficient high-level synthesis optimization, and design space exploration, targeting mainly genome analysis applications.</p>
    </div>
  </div>
  
  <div class="organizer">
    <div class="photo-name">
      <img src="{{ 'eirini_pic.jpeg' | relative_url }}" alt="Eirini Tzermpou">
      <p><a href="https://ihpcs.ethz.ch/people/person-detail.Mzc3MTQ0.TGlzdC8zOTQxLDc2NTU1MzE0Mg==.html" style="color: inherit; text-decoration: none;">Eirini Tzermpou</a></p>
    </div>
    <div class="bio">
      <p>Email: <a href="mailto:etzermpou@ethz.ch">etzermpou@ethz.ch</a></p>
      <p>Eirini Tzermpou is currently a graduate researcher in the SAFARI Research Group at ETH Zurich, led by Prof. Onur Mutlu. She recently received her Integrated Master’s in Electrical and Computer Engineering from the National Technical University of Athens (NTUA) and her Bachelor’s in Biomedical Sciences from DEREE-The American College of Greece. Her research interests lie in the intersection of computer architecture with bioinformatics and biomedicine, with a focus on designing software-hardware co-designed systems for accelerating bio-analysis workflows.</p>
    </div>
  </div>
  
  <div class="organizer">
    <div class="photo-name">
      <img src="{{ 'onur_pic.jpeg' | relative_url }}" alt="Prof. Onur Mutlu">
      <p><a href="https://people.inf.ethz.ch/omutlu/" style="color: inherit; text-decoration: none;">Professor Onur Mutlu</a></p>
    </div>
    <div class="bio">
      <p>Email: <a href="mailto:omutlu@gmail.com">omutlu@gmail.com</a></p>
      <p>Onur Mutlu is a Professor of Computer Science at ETH Zurich. He previously held the William D. and Nancy W. Strecker Early Career Professorship at Carnegie Mellon University. His research interests are in computer architecture, computing systems, hardware security, memory & storage systems, and bioinformatics, with a major focus on designing fundamentally energy-efficient, high-performance, and robust computing systems. He started the Computer Architecture Group at Microsoft Research (2006-2009), and held product, research, and visiting positions at Intel Corporation, Advanced Micro Devices, VMware, Google, and Stanford University. He received various honors for his research, including the 2025 IEEE Computer Society Harry H. Goode Memorial Award “for seminal contributions to computer architecture research and practice, especially in memory systems.” He is an ACM Fellow, IEEE Fellow, and an elected member of the Academy of Europe. He enjoys teaching, mentoring, and enabling & democratizing access to high-quality research and education. He has supervised 24 PhD graduates, many of whom received major dissertation awards, 15 postdoctoral trainees, and more than 60 Master’s and Bachelor’s students. His computer architecture and digital logic design course lectures and materials are freely available on YouTube, and his research group makes a wide variety of artifacts freely available online. For more information, please see his webpage at <a href="https://people.inf.ethz.ch/omutlu/">https://people.inf.ethz.ch/omutlu/</a>.</p>
    </div>
  </div>

</div>



## Agenda & Workshop Materials {#agenda-materials}

<style>
  /* Specific styling for the Agenda Table */
  table.agenda-table {
    width: 100%;
    border-collapse: collapse;
    margin-top: 1.5rem;
    font-size: 0.95rem;
    box-shadow: 0 1px 3px rgba(0,0,0,0.1);
  }

  table.agenda-table th {
    background-color: #1C3F5A; /* Deep navy */
    color: white;
    text-align: left;
    padding: 10px 12px;
    border: 1px solid #162F44;
  }

  table.agenda-table td {
    border: 1px solid #ddd;
    padding: 10px 12px;
    vertical-align: top;
    color: #333;
  }

  /* Column widths — only take effect because of the <colgroup> in the table */
  table.agenda-table col:nth-child(1) { width: 15%; } /* Time */
  table.agenda-table col:nth-child(2) { width: 35%; } /* Presenter */
  table.agenda-table col:nth-child(3) { width: 50%; } /* Title */

  /* Keep time ranges on one line */
  table.agenda-table td.time {
    white-space: nowrap;
    font-variant-numeric: tabular-nums;
  }

  /* Affiliation shown under the presenter name */
  table.agenda-table .affiliation {
    display: block;
    font-size: 0.85em;
    color: #5a6b7a;
    margin-top: 2px;
  }

  /* Optional zebra striping — delete this rule if you prefer plain white rows */
  table.agenda-table tbody tr:nth-child(even):not(.break-row) {
    background-color: #f7f9fb;
  }

  /* Styling for Break rows */
  table.agenda-table tr.break-row {
    background-color: #dae8f4; /* Light blue */
  }
  table.agenda-table tr.break-row td {
    font-weight: 600;
    color: #1C3F5A;
    text-align: center;      /* Center text horizontally */
    vertical-align: middle;  /* Center text vertically */
  }
</style>

<table class="agenda-table">
  <colgroup>
    <col>
    <col>
    <col>
  </colgroup>
  <thead>
    <tr>
      <th>Time</th>
      <th>Presenter</th>
      <th>Title</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="time">8:30 - 8:35</td>
      <td>Organizers</td>
      <td>Welcome</td>
    </tr>
    <tr>
      <td class="time">8:35 - 9:15</td>
      <td>
        Onur Mutlu / Nika Mansouri Ghiasi
        <span class="affiliation">(ETH Zurich)</span>
      </td>
      <td>Accelerating Genome Analysis</td>
    </tr>
    <tr>
      <td class="time">9:15 - 10:00</td>
      <td>
        Mingkai Dong
        <span class="affiliation">(SJTU)</span>
      </td>
      <td>DNA Storage as a Systems Problem: From Molecular Media to Storage Abstractions</td>
    </tr>
    <tr class="break-row">
      <td class="time">10:00 - 10:30</td>
      <td colspan="2">Coffee Break</td>
    </tr>
    <tr>
      <td class="time">10:30 - 10:50</td>
      <td>
        Ziqiang &ldquo;Joe&rdquo; Zhu, Thomas Screven
        <span class="affiliation">(University of California, Davis)</span>
      </td>
      <td>TypeZero: Building Trustworthy Computer Systems for Human Augmentation</td>
    </tr>
    <tr>
      <td class="time">10:50 - 11:10</td>
      <td>
        Timur Eke
        <span class="affiliation">(ETH Zurich)</span>
      </td>
      <td>Benchmarking and Accelerating Single-Cell Analysis</td>
    </tr>
    <tr>
      <td class="time">11:10 - 11:30</td>
      <td>
        Nika Mansouri Ghiasi
        <span class="affiliation">(ETH Zurich)</span>
      </td>
      <td>Storage-Centric Genomic and Metagenomic Analyses</td>
    </tr>
    <tr>
      <td class="time">11:30 - 11:50</td>
      <td>
        Yifan Li
        <span class="affiliation">(Cornell)</span>
      </td>
      <td>Sparse Linear Algebra Accelerates Genotype Representation Graph Computation at Biobank Scale</td>
    </tr>
    <tr>
      <td class="time">11:50 - 12:00</td>
      <td>Organizers</td>
      <td>Concluding Remarks</td>
    </tr>
  </tbody>
</table>

##Livestream {#livestream}

<iframe width="560" height="315" src="https://www.youtube.com/embed/rzzepjCeo5s?si=353Yi5vUj7PUTTcM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Previous Iteration {#previous-iteration}

<p>
You can find information regarding the previous iterations of the workshop (held in conjunction with MICRO 2025 in Seoul and HPCA 2026 in Sydney) 
<strong><a href="https://events.safari.ethz.ch/micro25-arch4health/" target="_blank">here</a></strong> and <strong><a href="https://events.safari.ethz.ch/hpca26-arch4health/" target="_blank">here</a></strong>.
</p>


 




