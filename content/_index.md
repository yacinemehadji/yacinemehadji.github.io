---
title: ''
date: 2022-10-24
type: landing

design:
  spacing: '6rem'

sections:

# ============================================================
# 1. HERO / BIOGRAPHIE
# ============================================================

- block: resume-biography-3
  content:
    username: admin

    text: ''

    button:
      text: "Télécharger mon CV"
      url: uploads/resume.pdf

    headings:
      about: 'À propos'
      education: 'Formation'
      interests: 'Domaines d’intérêt'

  design:
    css_class: hbx-bg-gradient

    avatar:
      size: large
      shape: circle


# ============================================================
# 2. PRÉSENTATION
# ============================================================

- block: markdown
  content:
    title: 'Ingénieur en électronique & technologies avancées'
    subtitle: ''
    text: |-

      Je suis ingénieur en électronique et je m'intéresse particulièrement
      à la microélectronique, aux systèmes embarqués et à l'intelligence
      artificielle.

      Mon parcours combine les technologies électroniques, la conception
      de systèmes, la recherche expérimentale et le développement de
      solutions basées sur le Deep Learning.

      Je travaille notamment sur des problématiques liées à la
      microélectronique, aux nanotechnologies, aux systèmes embarqués
      et à l'intelligence artificielle appliquée à l'imagerie.

  design:
    columns: '1'


# ============================================================
# 3. EXPERTISE
# ============================================================

- block: markdown
  content:
    title: 'Expertise'
    subtitle: ''
    text: |-

      **Microélectronique**

      Packaging de circuits intégrés, caractérisation, technologies
      électroniques et nanotechnologies.

      **Électronique & systèmes embarqués**

      Conception électronique, systèmes numériques, FPGA et architectures
      matérielles.

      **Intelligence artificielle**

      Machine Learning, Deep Learning, Computer Vision, réseaux de neurones
      convolutifs et traitement d'images.

      **Programmation**

      Python, TensorFlow, Keras, SystemVerilog et outils de développement
      scientifique.

  design:
    columns: '1'


# ============================================================
# 4. PROJETS
# ============================================================

- block: collection
  id: projects
  content:
    title: 'Projets sélectionnés'
    subtitle: ''
    text: 'Quelques projets techniques et de recherche.'
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

- block: markdown
  content:
    title: 'Expérience'
    subtitle: ''
    text: |-

      Mon expérience couvre la recherche en microélectronique, les
      technologies de packaging, la caractérisation de dispositifs
      électroniques ainsi que le développement de solutions numériques
      et basées sur l'intelligence artificielle.

      Pour découvrir mon parcours professionnel en détail :

      **[Voir mon expérience complète](experience/)**

  design:
    columns: '1'


# ============================================================
# 6. PUBLICATIONS
# ============================================================

- block: collection
  id: publications
  content:
    title: 'Publications & travaux de recherche'
    subtitle: ''
    text: ''
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

- block: cta-card
  content:
    title: 'Vous souhaitez échanger ?'
    text: |-
      Je suis ouvert aux discussions autour de projets de recherche,
      collaborations, technologies électroniques, microélectronique
      et intelligence artificielle.

    button:
      text: 'Me contacter'
      url: '/#contact'

  design:
    card:
      css_class: 'bg-primary-300'

---
