---
layout: project
title: Trust Tax Projection Calculator
order: 1
description: An Excel-based, comprehensive trust tax projection model designed to calculate current-year federal tax liability and project the following year's liability using updated income, distribution, and tax assumptions. The model emphasizes transparency by showing how income, deductions, distributions, and tax rates flow through the calculation, including an integrated Schedule B income distribution deduction estimate.
prepared_by: Alexander Jenkins
project_meta: Excel Modeling &middot; Trust Taxation &middot; Financial Planning
preview_image: /assets/Trust-Tax-Projection-Preview.png
preview_alt: Financial summary comparing actual and projected trust tax results
preview_width: 946
preview_height: 868
preview_fit: contain
detail_image: /assets/Clean Trust Calc Image.png
detail_image_alt: Trust federal tax projection worksheet showing actual and projected inputs
detail_image_width: 877
detail_image_height: 788
detail_fit: contain
detail_image_link: /assets/Clean Trust Calc Image.png
detail_image_link_label: Open the full-size trust tax projection worksheet
detail_image_link_text: Open full-size calculator image
case_study: true
hide_description_heading: true
hide_default_actions: true
---

<section class="case-study-section">
  <h2>The Objective</h2>
  <p>Trust tax planning requires combining information from multiple tax forms, investment statements, distribution assumptions, and even the original trust governing documents. I developed this model to make that process more structured and repeatable while allowing actual tax information from one year to serve as the basis for the following year's projection.</p>
  <p>The goal was not only to calculate an estimated tax liability, but to create a workbook that could be updated efficiently as new information became available. That repeatability is particularly important when applying the same planning process across multiple trusts.</p>
</section>

<section class="case-study-section">
  <h2>What I Built</h2>
  <p>The workbook uses a year-by-year structure that separates actual results from projected values and incorporates inputs for investment income, deductions, capital gains, distributions, and tax payments.</p>

  <div class="case-study-subsection">
    <h3>Key Components</h3>
    <ul class="case-study-feature-list">
      <li>Federal fiduciary income tax calculations</li>
      <li>Schedule B income distribution deduction modeling</li>
      <li>Ordinary and qualified dividend treatment</li>
      <li>Short- and long-term capital gains</li>
      <li>Net Investment Income Tax (NIIT) considerations</li>
      <li>Alternative Minimum Tax (AMT) inputs</li>
      <li>Capital loss and tax credit carryforwards</li>
      <li>Trust distributions and K-1 allocation considerations</li>
    </ul>
  </div>

  <figure class="case-study-figure case-study-figure-document">
    <a class="case-study-figure-frame" href="{{ '/assets/Alex-Jenkins-Trust-Tax-Projection-Exhibit.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="Open the full trust tax projection exhibit PDF">
      <img src="{{ '/assets/Alex-Jenkins-Trust-Tax-Projection-Exhibit.png' | relative_url }}" alt="One-page trust tax projection exhibit comparing 2025 actual results with 2026 projected results" width="720" height="1400" loading="lazy" decoding="async">
    </a>
    <figcaption>
      <span>Projection exhibit summarizing actual and projected tax results.</span>
      <a class="case-study-figure-link" href="{{ '/assets/Alex-Jenkins-Trust-Tax-Projection-Exhibit.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer">Open full exhibit (PDF) <span aria-hidden="true">&nearr;</span></a>
    </figcaption>
  </figure>
</section>

<section class="case-study-section">
  <h2>Building the Model</h2>
  <p>A major part of the project involved determining how information from the underlying tax return should flow through the projection without requiring the workbook to be rebuilt each year. I structured the model so that a completed year's information can be used as the starting point for the next projection period. Formulas incorporate safeguards such as minimum and maximum limits where necessary to prevent unrealistic results when assumptions change.</p>
  <p>The most challenging component of the model was integrating the Schedule B income distribution deduction. A fully detailed calculation can become significantly more involved, so I had to balance precision with usability. I ultimately designed a simplified calculation that captures the major inputs affecting the deduction without overwhelming the user. Testing the projection against completed returns allowed me to evaluate the model's accuracy and refine the methodology.</p>

  <figure class="case-study-figure case-study-figure-schedule">
    <a class="case-study-figure-frame" href="{{ '/assets/Schedule B Calc.png' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="Open the Schedule B calculation image at full size">
      <img src="{{ '/assets/Schedule B Calc.png' | relative_url }}" alt="Schedule B distribution projection worksheet with projected inputs and the calculated income distribution deduction" width="627" height="705" loading="lazy" decoding="async">
    </a>
    <figcaption>
      <span>Integrated Schedule B income distribution deduction estimate.</span>
      <a class="case-study-figure-link" href="{{ '/assets/Schedule B Calc.png' | relative_url }}" target="_blank" rel="noopener noreferrer">Open full-size image <span aria-hidden="true">&nearr;</span></a>
    </figcaption>
  </figure>
</section>

<section class="case-study-section">
  <h2>Why it Matters</h2>
  <p>The finished model converts a complicated tax planning process into a more consistent analytical framework. Instead of evaluating individual tax items independently, the workbook connects income, distributions, deductions, and tax calculations so that changes to assumptions can be evaluated within the broader trust tax picture.</p>
  <p>It also provides a foundation that can be updated as actual tax returns become available, allowing projected results to be compared with actual outcomes and the methodology to be refined over time.</p>
</section>

<section class="case-study-section">
  <h2>Skills Demonstrated</h2>
  <ul class="case-study-skill-list" aria-label="Skills demonstrated in this project">
    <li>Advanced Excel Modeling</li>
    <li>Financial Analysis</li>
    <li>Tax Research</li>
    <li>Fiduciary Accounting</li>
    <li>Process Improvement</li>
    <li>Quality Control</li>
  </ul>
</section>

<aside class="project-contact-cta" aria-label="Discuss the Trust Tax Projection Calculator">
  <a class="button" href="{{ '/contact/' | relative_url }}">Discuss the Model</a>
  <p>Interested in the underlying workbook or methodology? Contact me to discuss the project in more detail.</p>
</aside>
