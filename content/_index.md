---

title: ""
date: 2022-10-24
type: landing

design:
spacing: "6rem"

sections:

# ============================================================

# 1. HERO / PROFIL

# ============================================================

* block: resume-biography-3
  content:
  username: admin
  text: ""
  button:
  text: "Télécharger mon CV"
  url: "uploads/resume.pdf"
  headings:
  about: "À propos"
  education: "Formation"
  interests: "Domaines d'intérêt"
  design:
  css_class: "hbx-bg-gradient"
  avatar:
  size: large
  shape: circle

# ============================================================

# 2. PRÉSENTATION

# ============================================================

* block: markdown
  content:
  title: "Ingénieur en électronique, microélectronique et systèmes embarqués"
  subtitle: ""
  text: |-
  Ingénieur en électronique, microélectronique et systèmes embarqués, avec une expérience en recherche appliquée et en plateforme technologique.

  ```
  Mon parcours combine la conception de circuits intégrés, le layout et la vérification physique, le packaging électronique, les FPGA, les systèmes embarqués ainsi que l'intelligence artificielle.

  Je m'intéresse particulièrement aux technologies CMOS et Beyond CMOS, à la spintronique, au calcul neuromorphique et aux applications du Deep Learning dans les domaines scientifiques et médicaux.
  ```

  design:
  columns: "1"

# ============================================================

# 3. EXPERTISE

# ============================================================

* block: markdown
  content:
  title: "Expertise"
  subtitle: ""
  text: |-
  **Microélectronique & IC Design**

  ```
  Conception et simulation de circuits intégrés, IC Layout, DRC/LVS/PEX, technologies AMS et prototypage.

  **Packaging de circuits intégrés**

  Wire bonding, flip-chip, assemblage sur PCB multicouches et caractérisation électrique.

  **FPGA & systèmes numériques**

  SystemVerilog, VHDL, FPGA, architectures numériques et conception de systèmes embarqués.

  **Systèmes embarqués**

  STM32, firmware, C/C++, instrumentation électronique et développement d'interfaces.

  **Intelligence artificielle**

  Python, TensorFlow, PyTorch, Deep Learning, Computer Vision et analyse d'images médicales.
  ```

  design:
  columns: "1"

# ============================================================

# 4. PROJETS

# ============================================================

* block: collection
  id: projects
  content:
  title: "Projets sélectionnés"
  subtitle: ""
  text: "Quelques projets techniques et de recherche en électronique, microélectronique, FPGA et intelligence artificielle."
  filters:
  folders:
  - projects
  featured_only: true
  design:
  view: article-grid
  columns: 2

# ============================================================

# 5. EXPÉRIENCE

# ============================================================

* block: markdown
  content:
  title: "Expérience"
  subtitle: ""
  text: |-
  Mon expérience professionnelle couvre la recherche en microélectronique, les technologies de packaging, le prototypage de circuits intégrés, la caractérisation de dispositifs électroniques et le développement de systèmes embarqués.

  ```
  J'ai également travaillé sur le calcul neuromorphique, la spintronique et le développement de modèles de Deep Learning.

  **[Voir mon expérience complète](experience/)**
  ```

  design:
  columns: "1"

# ============================================================

# 6. PUBLICATIONS

# ============================================================

* block: collection
  id: publications
  content:
  title: "Publications & travaux de recherche"
  subtitle: ""
  text: ""
  filters:
  folders:
  - publications
  featured_only: true
  design:
  view: citation
  columns: 1

# ============================================================

# 7. CONTACT

# ============================================================

* block: cta-card
  content:
  title: "Vous souhaitez échanger ?"
  text: |-
  Je suis ouvert aux discussions autour de projets de recherche, de collaborations et de technologies liées à l'électronique, la microélectronique, les systèmes embarqués et l'intelligence artificielle.

  button:
  text: "Me contacter"
  url: "mailto:yacine[.mehadji@outlook.com](mailto:.mehadji@outlook.com)"

  design:
  card:
  css_class: "bg-primary-300"

---
