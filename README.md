# cloud-based-event-driven-car-dealership-system
Analytical and evolving cloud-based event-driven management system for car dealerships, designed to apply each Cloud Computing topic progressively

# Project Title

Design and Analysis of a Cloud-Based Event-Driven Management System for Car Dealerships

---

## Team Members / أعضاء الفريق

- **عدي سعد علي القرا / Adi Alqarra**  – oalqarra1@smail.ucas.edu.ps  
- **عمر شعبان يوسف حرب / Omar Shaaban** – oh6@smail.ucas.edu.ps  
- **سارة مندييل / Sarah Mandil**  – smandeil@smail.ucas.edu.ps  

## Supervisor / المشرفة

- **د.إسراء فروانة / Israa Farwanah** – ifarwanah@ucas.edu.ps

---

## Repository Short Description (GitHub)

> Analytical design and study of a cloud-based, event-driven management system for car dealerships, focusing on architecture, performance, and scalability.

---

## Project Description

This repository contains the design, analysis, and academic study of a cloud-based, event-driven management system tailored for car dealerships.

The project emphasizes:

- **System architecture design**  
- **Event-driven communication models**  
- **Cloud deployment strategies**  
- **Analytical evaluation of performance, scalability, and cost**  

The methodology aligns with academic research-style projects commonly found in Google Scholar, ensuring clarity and rigor.

---

## Project Motivation

Traditional car dealership management systems often suffer from:

- Limited scalability  
- Delayed data processing  
- High infrastructure and maintenance costs  
- Poor real-time event handling  

This project explores how **cloud computing + event-driven architecture** can address these limitations efficiently.

---

## Project Objectives

1. Design a cloud-based management system architecture for car dealerships  
2. Apply an event-driven model to handle dealership operations  
3. Analyze system performance under increasing workloads  
4. Evaluate scalability across multiple dealership branches  
5. Compare cost efficiency between cloud-based and traditional systems  

---

## Project Scope (Important for Students)

**Analytical and design-oriented project – no full coding expected.**

Included:

- Conceptual system design and architecture diagrams  
- Event-driven workflow analysis  
- Cloud deployment model analysis  
- Performance, scalability, and cost analysis  
- Real-world dealership case study  

Not included:

- Full software implementation  
- Frontend/backend development  
- Real cloud deployment  

---

## System Overview (High-Level)

- Car dealership users (sales, inventory, management)  
- Cloud-based services  
- Event-driven components (events & triggers)  
- Centralized data storage & analytics layer  

**Example:** A car sale triggers inventory update, customer record update, and invoice generation **in real time**.

---

## Repository Structure

- `abstract/` – Project summary  
- `problem-statement/` – Problem definition  
- `literature-review/` – Related academic work  
- `system-design/` – Architecture & event-driven design  
- `analysis/` – Performance, scalability, cost  
- `case-study/` – Realistic dealership scenario  
- `future-work/` – Future improvements  
- `references/` – Academic & technical references  

---

## Team Responsibilities

- Each member contributes to at least one section:  
  - Literature review  
  - System architecture  
  - Analytical evaluation  
  - Case study writing  

**All work must follow academic writing style.**

---

## Academic Requirements (Instructor-Oriented)

This project fulfills the following requirements:

- Research-based system analysis  
- Cloud computing concepts application  
- Event-driven architecture evaluation  
- Analytical comparison & reasoning  
- Clear documentation & structured presentation  

**This aligns with the expectations discussed in class**: analytical approach, design-focused, research-oriented.

---

## Expected Deliverables

- Complete, well-documented GitHub repository  
- Clear academic explanations in all sections  
- Logical analysis with reasoning & references  
- Structured content for academic evaluation  

---

## Target Audience

- Course instructor & teaching assistants  
- Team members  
- Students reviewing cloud-based system designs  
- Academic readers interested in event-driven systems

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Cloud-Based Car Dealership System</title>
<style>
body {
    font-family: Arial, sans-serif;
    background-color: #fff8dc; /* Butter yellow */
    color: #8b0000; /* Dark red */
    max-width: 900px;
    margin: auto;
    padding: 20px;
    line-height: 1.6;
}
h1, h2, h3 { color: #8b0000; }
.tab {
    overflow: hidden;
    border-bottom: 3px solid #8b0000;
    margin-bottom: 20px;
}
.tab button {
    background-color: #fffacd; /* lighter butter yellow */
    float: left;
    border: 1px solid #8b0000;
    outline: none;
    cursor: pointer;
    padding: 10px 16px;
    transition: 0.3s;
    font-size: 16px;
    margin-right: 2px;
}
.tab button:hover { background-color: #f5e68a; }
.tab button.active { background-color: #f0e68c; border-bottom: 3px solid #8b0000; }
.tabcontent {
    display: none;
    padding: 15px;
    border-left: 4px solid #8b0000;
    background-color: #fffacd;
    margin-bottom: 20px;
}
.collapsible {
    background-color: #8b0000;
    color: #fff8dc;
    cursor: pointer;
    padding: 10px;
    width: 100%;
    border: none;
    text-align: left;
    outline: none;
    font-size: 16px;
    margin-top: 10px;
}
.activeCollapsible, .collapsible:hover { background-color: #b22222; }
.content {
    padding: 0 15px;
    display: none;
    overflow: hidden;
    background-color: #fffacd;
    margin-bottom: 10px;
    border-left: 4px solid #8b0000;
}
table { border-collapse: collapse; width: 100%; margin-bottom: 15px; }
th, td { border: 1px solid #8b0000; padding: 8px; text-align: left; }
th { background-color: #fff8dc; }
a { color: #8b0000; text-decoration: none; }
a:hover { text-decoration: underline; }
</style>
</head>
<body>

<h1>Cloud-Based Event-Driven Car Dealership System</h1>
<p><b>Analytical and growing project: we design a cloud system for car dealerships step by step, covering all cloud topics.</b></p>

<h2>Team Members</h2>
<table>
<tr><th>Name</th><th>Student ID</th><th>Email</th></tr>
<tr><td>Adi Alqarra</td><td>120244732</td><td>oalqarra1@smail.ucas.edu.ps</td></tr>
<tr><td>Omar Shaaban</td><td>–</td><td>oh6@smail.ucas.edu.ps</td></tr>
<tr><td>Sarah Mandil</td><td>220XXXXX</td><td>smandeil@smail.ucas.edu.ps</td></tr>
</table>

<h2>Supervisor</h2>
<p>Dr. Israa Farwanah – ifarwanah@ucas.edu.ps</p>

<div class="tab">
  <button class="tablinks active" onclick="openTab(event, 'Objectives')">Objectives</button>
  <button class="tablinks" onclick="openTab(event, 'Scope')">Scope</button>
  <button class="tablinks" onclick="openTab(event, 'Repo')">Repository Structure</button>
  <button class="tablinks" onclick="openTab(event, 'Deliverables')">Deliverables</button>
</div>

<div id="Objectives" class="tabcontent" style="display:block;">
  <button type="button" class="collapsible">Main Goals</button>
  <div class="content">
    <ul>
      <li>Design a cloud-based system for dealerships</li>
      <li>Use event-driven model for all operations</li>
      <li>Analyze system performance under many tasks</li>
      <li>Check scalability across multiple branches</li>
      <li>Compare cloud vs traditional system costs</li>
    </ul>
  </div>
</div>

<div id="Scope" class="tabcontent">
  <button type="button" class="collapsible">Included</button>
  <div class="content">
    <ul>
      <li>System design and architecture diagrams</li>
      <li>Event-driven workflow analysis</li>
      <li>Cloud deployment model analysis</li>
      <li>Performance, scalability, and cost study</li>
      <li>Case study example</li>
    </ul>
  </div>
  <button type="button" class="collapsible">Not Included</button>
  <div class="content">
    <ul>
      <li>No real software coding</li>
      <li>No front-end or back-end development</li>
      <li>No real cloud deployment</li>
    </ul>
  </div>
</div>

<div id="Repo" class="tabcontent">
  <button type="button" class="collapsible">Repository Folders</button>
  <div class="content">
    <ul>
      <li>abstract/ – Project summary</li>
      <li>problem-statement/ – Define main problem</li>
      <li>literature-review/ – Study similar academic work</li>
      <li>system-design/ – Architecture and event design</li>
      <li>analysis/ – Performance, scalability, cost study</li>
      <li>case-study/ – Real dealership example</li>
      <li>future-work/ – Possible improvements</li>
      <li>references/ – Academic & technical references</li>
    </ul>
  </div>
</div>

<div id="Deliverables" class="tabcontent">
  <ul>
    <li>Well-documented GitHub repository</li>
    <li>Clear explanation in all sections</li>
    <li>Logical analysis with references</li>
    <li>Structured and easy to read for students and instructor</li>
  </ul>
</div>

<script>
function openTab(evt, tabName) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) { tabcontent[i].style.display = "none"; }
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) { tablinks[i].className = tablinks[i].className.replace(" active", ""); }
  document.getElementById(tabName).style.display = "block";
  evt.currentTarget.className += " active";
}

var coll = document.getElementsByClassName("collapsible");
for (var i = 0; i < coll.length; i++) {
  coll[i].addEventListener("click", function() {
    this.classList.toggle("activeCollapsible");
    var content = this.nextElementSibling;
    if (content.style.display === "block") { content.style.display = "none"; } 
    else { content.style.display = "block"; }
  });
}
</script>

</body>
</html>
