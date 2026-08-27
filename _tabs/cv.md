---
title: "CV"
layout: page
icon: fas fa-user-tie
order: 1
---


<!-- About me -->
{% capture content %}
I am a PhD scholar in the Department of Metallurgical and Materials Engineering at the Indian Institute of Technology Madras, Chennai, India, working with Prof. Anand K. Kanjarla (MME) and Prof. Sundararajan Natarajan (ME). My research lies in computational mechanics, with a particular interest in developing efficient and scalable computational methods for complex problems in solid mechanics and materials science. My current work focuses on modelling deformation and fracture in polycrystalline materials using the Octree-based Scaled Boundary Finite Element Method (SBFEM).
{% endcapture %}

{% include cv-section.html
  title="About Me"
  icon="fas fa-user-tie"
  content=content
%}

<!-- Research Interests -->
{% capture content %}
  {% include tag.html keywords="Scaled boundary finite element method" %}
  {% include tag.html keywords="Phase-field modelling of damage" %}
  {% include tag.html keywords="Crystal plasticity" %}
  {% include tag.html keywords="High-performance computing" %}
{% endcapture %}

{% include cv-section.html
  title="Research Interests"
  icon="fas fa-microscope"
  content=content
%}


<!-- Education -->
{% capture content %}
  <!-- PhD -->
  <div class="item">
    <strong>Doctor of Philosophy</strong> in Metallurgical and Materials Engineering
    <span class="education-year">[2022 – Present]</span>
    <br>
    <small>Indian Institute of Technology Madras, Tamil Nadu, India.</small>
  </div>
  <!-- MTech -->
  <div class="item">
    <strong>Master of Technology</strong> in Metallurgical Engineering
    <span class="education-year">[2020 – 2022]</span>
    <br>
    <small>Indian Institute of Technology Indore, Madhya Pradesh, India.</small>
  </div>
  <!-- BTech -->
  <div class="item">
    <strong>Bachelor of Technology</strong> in Mechanical Engineering
    <span class="education-year">[2012 – 2016]</span>
    <br>
    <small>JNTUH College of Engineering Manthani, Telangana, India.</small>
  </div>
{% endcapture %}

{% include cv-section.html
  title="Education"
  icon="fas fa-graduation-cap"
  content=content
%}


<!-- Research -->
{% capture content %}
  <!-- Doctoral Research -->
  <div class="item">
    <strong>Doctoral Research</strong> <br>
    <small>Jul 2022 – Present</small>
    <ul class="mb-0 mt-2">
      <li><strong>Title:</strong> A computational framework for fracture simulation in polycrystalline materials using adaptive phase-field modelling and octree-based SBFEM </li>
      <li><strong>Supervisors:</strong>
        <ol>
          <li><em>Prof. Anand K Kanjarla</em> – Laboratory for Mechanics of Microstructures, Dept. of Metallurgical and Materials Engineering, IIT Madras.</li>
          <li><em>Prof. Sundararajan Natarajan</em> – Integrated Modelling and Simulation Laboratory, Dept. of Mechanical Engineering, IIT Madras.</li>
        </ol>
      </li>
      <li><strong>Description:</strong>
        <ul>
          <li>The aim is to develop a computationally efficient framework that combines phase-field modelling with crystal plasticity using the scaled boundary finite element method to simulate nucleation and propagation of cracks in metallic materials.</li>
          <li>The developed framework will be used to understand the effect of microstructural features on crack nucleation and propagation in metals.</li>
        </ul>
      </li>
    </ul>
  </div>

  <!-- Master's Research -->
  <div class="item">
    <strong>Master’s Research</strong> <br>
    <small>Jun 2021 – Jun 2022</small>
    <ul class="mb-0 mt-2">
      <li><strong>Title:</strong> Continuum mechanics based modelling of material deformation</li>
      <li><strong>Supervisors:</strong>
        <ol>
          <li><em>Prof. Abhijit Ghosh</em> – Microstructure and Texture Engineering Laboratory, Dept. of Metallurgical Engineering and Materials Science, IIT Indore</li>
          <li><em>Prof. Saikat Sarkar</em> – Stochastic and Geometric Mechanics of Resilient Structures Group, Dept. of Civil Engineering, IIT Delhi</li>
        </ol>
      </li>
      <li><strong>Description:</strong>
        <ul>
          <li>Studied the effect of crystallographic anisotropy and crystal orientation on the formation of shear bands during ductile fracture in Fe single crystals.</li>
          <li>Explored the modelling of shear band formation through crystal plasticity simulations using DAMASK.</li>
        </ul>
      </li>
    </ul>
  </div>

  <!-- Bachelor's Project -->
  <div class="item">
    <strong>Bachelor’s Project</strong> <br>
    <small>Jan 2016 – May 2016</small>
    <ul class="mb-0 mt-2">
      <li><strong>Title:</strong> Design and development of an ornithopter using Autodesk Inventor</li>
      <li><strong>Supervisor:</strong> <em>Prof. K. Prasanna Lakshmi</em>, Dept. of Mechanical Engineering, JNTUHCEM</li>
      <li><strong>Description:</strong>
        <ul>
          <li>Studied the flight theory and techniques of different kinds of birds to understand their superior aerodynamic efficiency.</li>
          <li>Designed and developed a 3D CAD model of a remote-controlled ornithopter using Autodesk Inventor to achieve aerodynamic efficiency close to that of a bird. <a href="https://www.youtube.com/watch?v=vuNpXTk4Amw" target="_blank">video</a></li>
        </ul>
      </li>
    </ul>
  </div>
{% endcapture %}

{% include cv-section.html
  title="Research"
  icon="fas fa-flask me-2"
  content=content
%}

<!-- Conferences -->
{% capture content %}
  <ol class="conference-list">
    <li class="conference-item">
      <strong>S. K. Gaddam</strong>, S. Natarajan, A. K. Kanjarla,
      "Application of SBFEM for Polycrystal RVEs: A comparison with conventional FEM",
      <em>17th World Congress on Computational Mechanics & 10th European Congress on Computational Methods in Applied Sciences and Engineering (WCCM-ECCOMAS)</em>,
      19–24 July 2026, Munich, Germany.
    </li>

    <li class="conference-item">
      <strong>S. K. Gaddam</strong>, S. Natarajan, A. K. Kanjarla,
      "Octree-based scaled boundary finite element approach for polycrystal RVEs: implementation of crystal plasticity and comparison with conventional FEM",
      <em>14th International Symposium on Plasticity and Impact Mechanics (IMPLAST)</em>,
      12–16 October 2025, IIT Roorkee, India.
    </li>

    <li class="conference-item">
      <strong>S. K. Gaddam</strong>, S. Natarajan, A. K. Kanjarla,
      "Octree-based scaled boundary finite element approach for polycrystal RVEs: a comparison with FEM and FFT",
      <em>5th International Structural Integrity Conference & Exhibition (SICE)</em>,
      22–24 October 2024, VNIT Nagpur, India.
    </li>
  </ol>
{% endcapture %}

{% include cv-section.html
  title="Conferences"
  icon="fas fa-users"
  content=content
%}


<!-- Teaching Assistantships & Instruction -->
{% capture content %}
  <ol style="padding-left: 20px; margin-bottom: 0;">
    <li style="margin-bottom: 5px;">
      Mechanical Behaviour of Materials (Graduate Core Course) at IIT Madras
    </li>
    <li style="margin-bottom: 5px;">
      Finite Element Method in Materials Engineering (Graduate Elective Course) at IIT Madras.
    </li>
  </ol>
{% endcapture %}

{% include cv-section.html
  title="Teaching Assistantships & Instruction"
  icon="fas fa-chalkboard-teacher"
  content=content
%}
  
<!-- Academic Training / Short Courses -->
{% capture content %}
  <ol style="padding-left: 20px; margin-bottom: 0;">
    <li style="margin-bottom: 5px;">
      A summer school course on "Variational fracture mechanics and phase-field models" at the International Centre for Mechanical Sciences (CISM), Udine, Italy. [Jul 2024]
      <br><strong>Instructors:</strong> Prof. Blaise Bourdin - McMaster University; Prof. Laura De Lorenzis - ETH Zürich; Dr. Jack S. Hale - Université du Luxembourg; Prof. Flaviana Iurlano - Sorbonne Université; Prof. Corrado Maurini - Sorbonne Université; Prof. Peter W. Voorhees - Northwestern University.
    </li>
    <li style="margin-bottom: 5px;">
      GIAN course on "Modeling Defects in Crystalline Solids" at IIT Madras, Chennai, India. [Jan 2025]
      <br><strong>Instructor:</strong> Prof. David Rodney - University of Lyon. 
    </li>
    <li style="margin-bottom: 5px;">
      GIAN course on phase field modelling of fracture fatigue and chemo-mechanical degradation of materials at IIT Madras, Chennai, India. [Mar 2025]
      <br><strong>Instructor:</strong> Prof. Emilio Martínez Pañeda - University of Oxford.
    </li>
  </ol>
{% endcapture %}

{% include cv-section.html
  title="Academic Training / Short Courses"
  icon="fas fa-certificate"
  content=content
%}

<!-- Academic Courses -->
{% capture content %}
  {% include tag.html keywords="Applied finite element analysis" background="#797777" %}
  {% include tag.html keywords="Nonlinear FEA of solid continua" background="#797777" %}
  {% include tag.html keywords="Parallel scientific computing" background="#797777" %}
  {% include tag.html keywords="Engineering Plasticity" background="#797777" %}
  {% include tag.html keywords="Micromechanics" background="#797777" %}
  {% include tag.html keywords="Defects in materials" background="#797777" %}
  {% include tag.html keywords="Computational methods in engg" background="#797777" %}
  {% include tag.html keywords="Mechanical behaviour of materials" background="#797777" %}
  {% include tag.html keywords="Mathematical methods for chemical engineers" background="#797777" %}
  {% include tag.html keywords="Advanced phase transformations" background="#797777" %}
{% endcapture %}

{% include cv-section.html
  title="Academic Courses"
  icon="fas fa-book-open"
  content=content
%}

<!-- Technical Skills -->
{% capture content %}
  {% include tag.html keywords="Fortran" background="#2B7FFF" %}
  {% include tag.html keywords="Abaqus" background="#FB2C36" %}
  {% include tag.html keywords="Julia" background="#2B7FFF" %}
  {% include tag.html keywords="PETSc" background="#2B7FFF" %}
  {% include tag.html keywords="MPI" background="#2B7FFF" %}
  {% include tag.html keywords="OpenMP" background="#2B7FFF" %}
  {% include tag.html keywords="DAMASK" background="#FB2C36" %}
  {% include tag.html keywords="MATLAB" background="#2B7FFF" %}
  {% include tag.html keywords="Python" background="#2B7FFF" %}
  {% include tag.html keywords="Git" background="#2B7FFF" %}
  {% include tag.html keywords="Gmsh" background="#FB2C36" %}
  {% include tag.html keywords="Autodesk Inventor Pro" background="#2D9966" %}
  {% include tag.html keywords="Fusion 360" background="#2D9966" %}
  {% include tag.html keywords="Ansys" background="#FB2C36" %}
  {% include tag.html keywords="AutoCAD" background="#2D9966" %}
{% endcapture %}

{% include cv-section.html
  title="Technical Skills"
  icon="fas fa-laptop-code me-2"
  content=content
%}

<!-- Contact -->
{% capture content %}
  <strong>Email: </strong> 
  <a href="mailto:shivakumar.gdm@gmail.com">shivakumar.gdm@gmail.com</a><br>
  <strong>LinkedIn: </strong> 
  <a href="https://www.linkedin.com/in/shivakumargaddam" target="_blank">
    linkedin.com/in/shivakumargaddam
  </a>
{% endcapture %}

{% include cv-section.html
  title="Contact"
  icon="fas fa-envelope me-2"
  content=content
%}