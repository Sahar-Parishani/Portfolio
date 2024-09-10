<!-- Custom Title without Link -->
<div style="display: flex; justify-content: space-between; align-items: center;">
  <!-- Left: Tabs -->
  <div>
    <style>
    /* Styles for the tab buttons */
    .tab {
      overflow: hidden;
      border-bottom: 1px solid #ccc;
    }

    .tab button {
      background-color: inherit;
      float: left;
      border: none;
      outline: none;
      cursor: pointer;
      padding: 14px 16px;
      transition: 0.3s;
      font-size: 17px;
    }

    .tab button:hover {
      background-color: #ddd;
    }

    .tab button.active {
      background-color: #ccc;
    }

    /* Styles for the tab content */
    .tabcontent {
      display: none;
      padding: 20px 0;
      border-top: none;
    }
    </style>

    <div class="tab">
      <button class="tablinks" onclick="openTab(event, 'Portfolio')" id="defaultOpen">Portfolio</button>
      <button class="tablinks" onclick="openTab(event, 'Resume')">Resume</button>
    </div>
  </div>

  <!-- Center: Title -->
  <div style="font-size: 32px; font-weight: bold; text-align: center;">
    Sahar Parishani <br>
    <span style="font-size: 22px; font-weight: normal;">Part 1 Architectural Graduate of CCAE</span>
  </div>

  <!-- Right: Photo -->
  <div>
  <img src="https://github.com/user-attachments/assets/a742fe61-9d54-4d9e-98b0-8a0723bff73c" alt="Sahar Parishani" style="width: 150px; border-radius: 50%;">
  </div>
</div>

<!-- Start of Tabs Section -->
<div id="Portfolio" class="tabcontent">
  <h2>Portfolio</h2>
  <p>Here is my complete portfolio. Scroll down to view all pages:</p>
  <iframe src="https://github.com/Sahar-Parishani/Portfolio/raw/main/Sahar_Parishani_Portfolio.pdf" width="100%" height="600px"></iframe>
</div>

<div id="Resume" class="tabcontent">
  <h2>Resume</h2>
  <h3>Summary</h3>
  <p>I hold two Bachelor’s degrees in Architecture, each specializing in different aspects of the field, providing me with a diverse and comprehensive skill set. With several years of professional experience, I have developed expertise in architectural design and technical execution. Proficient in AutoCAD and various architectural software, I bring a well-rounded approach to every project, combining innovative design solutions with practical application.</p>

  <h3>Professional Experience</h3>
  <h4>Architectural Assistant (Freelance), Cork, Ireland, Oct/2019 – Aug/2022</h4>
  <ul>
    <li>Assisted in developing architectural designs, contributing to both conceptual and detailed design phases under the supervision of senior architects.</li>
    <li>Produced and revised architectural drawings, plans, and documentation using drafting software to support project progression.</li>
    <li>Collaborated with project teams to coordinate design ideas, ensuring alignment with client requirements and project goals.</li>
    <li>Prepared presentations and design materials for client meetings to effectively communicate design concepts.</li>
  </ul>

  <h4>Architectural Technologist, Samatarh Co., Tehran, Iran, Aug/2014 – May/2019</h4>
  <ul>
    <li>Led the technical design and detailing of architectural projects, ensuring buildability and compliance with relevant regulations.</li>
    <li>Collaborated with architects, engineers, and clients to ensure designs were efficient and practical for construction.</li>
    <li>Reviewed and approved technical drawings and documentation, ensuring accuracy and adherence to project specifications.</li>
    <li>Focused on designing key components of architectural projects.</li>
    <li>Produced detailed layouts and technical drawings to support project development.</li>
  </ul>

  <h4>Graduate Architectural Technologist, PBP Co., Tehran, Iran, May/2009 - Jul/2014</h4>
  <ul>
    <li>Developed and produced detailed technical drawings and construction documents, ensuring compliance with building regulations and standards.</li>
    <li>Assisted in the design and detailing of building projects, focusing on practical construction methods under the supervision of senior Technologists and Architects.</li>
    <li>Conducted site visits to assess construction progress and ensure alignment with technical drawings and project specifications.</li>
    <li>Supported the preparation of architectural plans and designs for different building projects.</li>
  </ul>

  <h3>Education</h3>
  <p><strong>University College Cork (CCAE), Ireland</strong><br>
  Bachelor (Hons) of Architecture (May-2024)</p>

  <p><strong>University of Yazd, Iran</strong><br>
  Bachelor of Architectural Technology (Feb-2009)</p>

  <h3>Academic Projects</h3>
  <ul>
    <li>Climate-Informed Design: Harmonising Tradition & Sustainability in Residential Buildings</li>
    <li>Commuting & Active Travel in Cork City</li>
    <li>Sustainable Multi-Functional Building in Cork City</li>
  </ul>

  <h3>Skills</h3>
  <strong>Software skills</strong>
  <ul>
    <li>Familiar with Revit</li>
    <li>Advanced AutoCAD 2D skills</li>
    <li>Proficient in AutoCAD 3D modelling</li>
    <li>Fluent in Microsoft Office, PowerPoint, Adobe Illustrator, and SketchUp</li>
  </ul>

  <strong>Design skills</strong>
  <ul>
    <li>Passive Architectural Design skills</li>
    <li>Sustainable and Energy-efficient Design</li>
    <li>Knowledge of Irish Building Regulations</li>
    <li>Attention to detail</li>
    <li>Reasoning and analytical thinking skills</li>
  </ul>

  <h3>Hobbies & Interests</h3>
  <ul>
    <li>Travelling</li>
    <li>Reading: Psychology and historical books</li>
    <li>Team sports: Aerobic</li>
    <li>Singing: Traditional Persian music</li>
    <li>Painting: Building and urban sketch</li>
  </ul>

  <h3>Languages</h3>
  <ul>
    <li>English</li>
    <li>Persian</li>
  </ul>
</div>

<script>
function openTab(evt, tabName) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none"; 
  }
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }
  document.getElementById(tabName).style.display = "block";
  evt.currentTarget.className += " active";
}

// Open default tab
document.getElementById("defaultOpen").click();
</script>

<!-- End of Tabs Section -->
