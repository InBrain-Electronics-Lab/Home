---
title: Our Team
nav:
  order: 3
  tooltip: Our Team
---

# {% include icon.html icon="fa-solid fa-users" %}A small but mighty team makes up the InBrain Electronics Lab!

{% include section.html %}

<div class="team-cards">

  <div class="team-card">
    {% include figure.html image="images/Ilke.png" %}
    <div class="team-info">
      <p class="team-name">Ilke Uguz, Ph.D.</p>
      <p class="team-role">Principal Investigator · Assistant Professor, Biomedical Engineering</p>
      <hr class="team-divider" />
      <div class="team-edu">
        <span>Postdoctoral Researcher, Electrical Engineering — Columbia University</span>
        <span>Ph.D., Microelectronics — École des Mines de Saint-Étienne</span>
        <span>M.S., Biophysics — Dresden Technical University</span>
        <span>B.S., Electrical Engineering — Yildiz Technical University</span>
      </div>
    </div>
  </div>

  <div class="team-card">
    {% include figure.html image="images/Sara.jpg" %}
    <div class="team-info">
      <p class="team-name">Sara Bender-Bier</p>
      <p class="team-role">Ph.D. Student · Biomedical Engineering</p>
      <hr class="team-divider" />
      <div class="team-edu">
        <span>M.B.E., Applied Bioengineering — Rice University</span>
        <span>B.S., Cellular & Molecular Biology: Biomedical Engineering — University of Michigan</span>
      </div>
      <p class="team-bio">Expertise in bipolar and multipolar electrical sensing and stimulation. Previously at Abbott (Cardiac Rhythm Management), XN Health (Lead Product Development Engineer), and an ORISE Fellow at the FDA's CDRH.</p>
      <div class="tag-row">
        <span class="tag interest">Visual prosthetics</span>
        <span class="tag interest">Flexible microelectronics</span>
        <span class="tag interest">Chemical sensing</span>
        <span class="tag hobby">Soccer</span>
        <span class="tag hobby">Hiking</span>
        <span class="tag hobby">3D printing</span>
      </div>
    </div>
  </div>

  <div class="team-card">
    {% include figure.html image="images/Julia.jpeg" %}
    <div class="team-info">
      <p class="team-name">Julia Reznik</p>
      <p class="team-role">Undergraduate Student · Biomedical Engineering, Neuroengineering & Biomedical Imaging</p>
      <hr class="team-divider" />
      <p class="team-bio">Proficient in MATLAB, SolidWorks, COMSOL, and Simulink. Undergraduate Lab & Grading Assistant for ENGR 245 (Circuits & Systems) and ENGR 212 (Design of Dynamical Systems).</p>
      <div class="tag-row">
        <span class="tag interest">Implantable neuroprosthetics</span>
        <span class="tag interest">Neurorehabilitation</span>
        <span class="tag hobby">Snowboarding</span>
        <span class="tag hobby">Traveling</span>
        <span class="tag hobby">Guitar</span>
        <span class="tag hobby">3D design</span>
      </div>
    </div>
  </div>

</div>

<style>
.team-cards { display: flex; flex-direction: column; gap: 1rem; margin-top: 1.5rem; }
.team-card { display: flex; gap: 1.25rem; padding: 1.25rem; border: 1px solid rgba(0,0,0,0.1); border-radius: 12px; background: #fff; }
.team-photo { width: 110px; height: 130px; object-fit: cover; border-radius: 8px; flex-shrink: 0; }
.team-info { flex: 1; min-width: 0; }
.team-name { font-size: 16px; font-weight: 600; margin: 0 0 2px; }
.team-role { font-size: 13px; color: #666; margin: 0 0 10px; }
.team-divider { border: none; border-top: 1px solid rgba(0,0,0,0.08); margin: 8px 0; }
.team-edu { font-size: 12px; color: #666; line-height: 1.7; margin-bottom: 10px; }
.team-edu span { display: block; }
.team-bio { font-size: 13px; color: #555; line-height: 1.6; margin: 0 0 10px; }
.tag-row { display: flex; flex-wrap: wrap; gap: 6px; }
.tag { font-size: 11px; padding: 3px 8px; border-radius: 99px; }
.tag.interest { background: #E6F1FB; color: #0C447C; border: 1px solid #B5D4F4; }
.tag.hobby { background: #E1F5EE; color: #085041; border: 1px solid #9FE1CB; }
</style>
