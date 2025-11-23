---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Version Control Theory, GitHub University, 2018 (expected)
* M.S. in Jekyll, GitHub University, 2014
* B.S. in GitHub, GitHub University, 2012

Work experience
======
* Spring 2024: Academic Pages Collaborator
  * GitHub University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * GitHub University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * GitHub University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

<section id="skills" class="container">
    <!-- Nous n'utilisons plus "skills-grid" mais une nouvelle classe "skills-list-container" -->
    <div class="skills-list-container">

        <!-- Compétence Principale (anciennement skill-card) -->
        <div class="skill-item">
            <i class="fas fa-code"></i> C / C++
        </div>

        <!-- Compétence Principale avec sous-compétences -->
        <div class="skill-item">
            <i class="fas fa-microchip"></i> Électronique & Hardware
            <!-- La sous-liste est maintenant à l'intérieur du skill-item -->
            <div class="sub-skill-list">
                <div class="sub-skill-item">Arduino / ESP32</div>
                <div class="sub-skill-item">Électronique Analogique & Numérique</div>
                <div class="sub-skill-item">Analyse de signaux (Oscilloscope)</div>
            </div>
        </div>

        <!-- Autre compétence principale -->
        <div class="skill-item">
            <i class="fas fa-cogs"></i> Automatisme & Robotique
        </div>
        
        <!-- Autre compétence principale -->
        <div class="skill-item">
            <i class="fab fa-python"></i> Python (Notions)
        </div>

    </div>
</section>

<!-- Le CSS adapté à partir de vos styles -->
<style>
    /* On abandonne la grille pour un affichage simple */
    .skills-list-container {
        /* Pas de 'display: grid' ici. Les divs s'afficheront les uns sous les autres par défaut. */
    }

    /* Style pour les compétences principales (votre ancien .skill-card) */
    .skill-item {
        /* On enlève le fond, la bordure, etc. pour un look de liste */
        font-size: 1.2rem;
        font-weight: 600;
        margin-bottom: 1rem; /* Espace entre les compétences principales */
        display: flex; /* Aligne l'icône et le texte */
        align-items: center;
        flex-wrap: wrap; /* Permet à la sous-liste de passer à la ligne */
    }

    /* Style pour les icônes (votre ancien .skill-card i) */
    .skill-item > i {
        /* On ne veut plus que l'icône soit un bloc au-dessus du texte */
        font-size: 1rem; /* Plus petit, comme une puce */
        color: #333; /* Couleur sobre, à adapter */
        margin-right: 0.75rem; /* Espace entre l'icône et le texte */
        width: 20px;
        text-align: center;
    }

    /* NOUVEAUX STYLES pour la hiérarchie */
    .sub-skill-list {
        width: 100%; /* La sous-liste prend toute la largeur */
        padding-left: 45px; /* INDENTATION pour aligner avec le texte principal */
        margin-top: 0.75rem;
    }

    .sub-skill-item {
        font-size: 1rem;
        font-weight: 400; /* Police plus légère pour les sous-compétences */
        margin-bottom: 0.5rem;
        position: relative;
        padding-left: 20px; /* Espace pour la puce personnalisée */
    }

    /* Crée la puce "cercle vide" comme sur votre image */
    .sub-skill-item::before {
        content: '○';
        position: absolute;
        left: 0;
        top: 0;
        color: #555;
    }
</style>

    

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
