---
layout: default
title: Research
permalink: /research/
---

# Research Archive

Click any manuscript to view.

---

<div class="manuscripts">

<button onclick="openPDF(0)">वेदाक्षर स्वरूपं (Form Of The Vēdākshara)</button>
<button onclick="openPDF(1)">वेदाक्षरोच्चारण (Pronunciation Of The Vēdākshara)</button>
<button onclick="openPDF(2)">वेदाक्षर यज्ञं (Origination Of The Vēdākshara)</button>
<button onclick="openPDF(3)">वेदाक्षर निर्माणं (Formation of the Vēdic Language)</button>
<button onclick="openPDF(4)">वेदशास्त्राणि - कल्पशास्त्रम् (Vēda Śāstras - Kalpa-śāstra)</button>
<button onclick="openPDF(5)">इन्द्रिय देवता अवधारणा (Concept Of Senses)</button>
<button onclick="openPDF(6)">उखा मंत्राः - उखाग्निः (The Transformative Power of Ukha)</button>
<button onclick="openPDF(7)">मन्त्रपुष्पम् (Mantrapushpam)</button>
<button onclick="openPDF(8)">य एवं वेद (The One Who Knows Thus)</button>
<button onclick="openPDF(9)">वैदिक पथः (The Vēdic Path)</button>
<button onclick="openPDF(10)">वैदिकरूपस्य प्रयोजनम्</button>
<button onclick="openPDF(11)">चिनुति (A Study of Divine Manifestation through Yajna)</button>
<button onclick="openPDF(12)">वैदिक शास्त्र दर्शन -वाज्ञज्ञ  (Vēdic Vēdākshara-Insight -The Yajna of Speech)</button>

</div>

<!-- ✅ ONLY ONE MODAL (KEEP THIS ONLY) -->
<div id="pdfModal" class="modal">

<!-- TOP BAR -->
<div class="pdf-header">
  <span id="pdfTitle">Manuscript Title</span>

  <div class="controls">
    <button onclick="zoomOut()">−</button>
    <button onclick="zoomIn()">+</button>
    <span id="pageIndicator">1 / 13</span>
    <span class="close" onclick="closePDF()">&times;</span>
  </div>
</div>

<div id="pdfViewer"></div>

<div class="nav-buttons">
<button onclick="prevPDF()">⬅ Previous</button>
<button onclick="nextPDF()">Next ➡</button>
</div>

</div>
