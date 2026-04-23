---
layout: page
permalink: /teaching/
title: Teaching
description: Course materials, schedules, and resources for classes taught.
nav: true
nav_order: 2
calendar: true
---

<style>
  /* ── Section headers (h2) ───────────────────────────── */
  .teaching-section {
    font-size: 1.6rem;
    font-weight: 700;
    color: #4a4a8a;           /* deep indigo — change this hex to any color */
    border-bottom: 2px solid #4a4a8a;
    padding-bottom: 6px;
    margin-top: 2rem;
    font-family: 'Roboto', sans-serif;  /* serif font for section titles */
  }
  /* ── Term headers (e.g. Fall 2024) ─────────────────── */
  .term-header {
    font-size: 1.05rem;
    font-weight: 600;
    color: #888;              /* muted gray */
    text-transform: uppercase;
    letter-spacing: 0.08em;  /* spaced out letters */
    margin-top: 1.2rem;
    margin-bottom: 0.3rem;
    font-family: 'Arial', sans-serif;
  }
  /* ── Course list items ──────────────────────────────── */
  .course-list {
    list-style: none;
    padding-left: 0;
  }
  .course-list li {
    font-size: 0.97rem;
    font-family: 'Courier New', monospace;  /* monospace for a code-lab feel */
    color: #333;
    padding: 4px 0;
    border-left: 3px solid #c8b8f0;   /* soft purple left accent bar */
    padding-left: 10px;
    margin-bottom: 4px;
  }
  /* ── PhD section course items — slightly different style ── */
  .course-list.phd li {
    border-left-color: #f0c8b8;       /* warm peach accent for PhD courses */
    color: #555;
    font-style: italic;
  }
</style>
 
---
 
<h2 class="teaching-section">Teachings at Champlain College</h2>
 
<p class="term-header">Fall 2024</p>
<ul class="course-list">
  <li>Course Name 1 (CSC XXX)</li>
  <li>Course Name 2 (CSC XXX)</li>
</ul>
<p class="term-header">Spring 2024</p>
<ul class="course-list">
  <li>Course Name 1 (CSC XXX)</li>
  <li>Course Name 2 (CSC XXX)</li>
</ul>
<p class="term-header">Fall 2023</p>
<ul class="course-list">
  <li>Course Name 1 (CSC XXX)</li>
  <li>Course Name 2 (CSC XXX)</li>
</ul>
---
 
<h2 class="teaching-section">Teaching and Assisted Courses as a PhD Student</h2>
 
<p class="term-header">Fall 2022 — University Name</p>
<ul class="course-list phd">
  <li>Course Name 1 (CS XXX) — Instructor of Record</li>
  <li>Course Name 2 (CS XXX) — Teaching Assistant</li>
</ul>
<p class="term-header">Spring 2022 — University Name</p>
<ul class="course-list phd">
  <li>Course Name 1 (CS XXX) — Teaching Assistant</li>
  <li>Course Name 2 (CS XXX) — Teaching Assistant</li>
</ul>
<p class="term-header">Fall 2021 — University Name</p>
<ul class="course-list phd">
  <li>Course Name 1 (CS XXX) — Teaching Assistant</li>
</ul>
---
 
<h2 class="teaching-section">Sample Courses</h2>
 
{% include courses.liquid %}
