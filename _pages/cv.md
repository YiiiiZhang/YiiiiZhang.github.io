---
layout: page
title: "CV"
permalink: /cv/
hide_title: true
cv_pdf: /files/CV_Yi_Zhang_LMU.pdf
redirect_from:
  - /resume
---

<div style="display:flex; justify-content:space-between; align-items:center; flex-wrap:wrap; gap:12px; margin-bottom:18px;">
  <h1 style="margin:0;">CV</h1>
  <a href="{{ page.cv_pdf | relative_url }}" target="_blank" rel="noopener"
     style="display:inline-block; font-weight:600; font-size:0.9rem; padding:7px 16px; border:1px solid var(--accent); border-radius:18px; color:var(--accent);">
    Download PDF ↓
  </a>
</div>

<object data="{{ page.cv_pdf | relative_url }}" type="application/pdf"
        style="width:100%; height:88vh; border:1px solid var(--border); border-radius:8px;">
  <p style="color:var(--muted);">
    Your browser can't display the embedded PDF.
    <a href="{{ page.cv_pdf | relative_url }}" target="_blank" rel="noopener">Open the CV in a new tab</a> instead.
  </p>
</object>
