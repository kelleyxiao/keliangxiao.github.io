---
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


<style>
/* Expand the main container */
.page__content {
  max-width: 1200px !important;
  width: 100%;
}

/* Two-column layout with spacing */
.custom-home-wrapper {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  margin-top: 20px;
  gap: 100px;
}

/* Right-side (text area) styling */
.custom-home-text {
  flex-grow: 1;
  min-width: 700px;
  margin-top: 20px;
  padding-right: 30px;
}

.custom-home-text h2 {
  font-weight: 700;
  font-size: 24px;
  margin-bottom: 8px;
}

.custom-home-text h3 {
  font-weight: 600;
  font-size: 20px;
  margin-top: 0;
  margin-bottom: 20px;
}

.custom-home-text p {
  font-size: 16px;
  line-height: 1.75;
  text-align: justify;
}

/* Responsive fallback */
@media (max-width: 992px) {
  .custom-home-wrapper {
    flex-direction: column;
    gap: 20px;
  }

  .custom-home-text {
    min-width: unset;
    padding-right: 0;
  }
}
</style>

<div class="custom-home-wrapper">
  <!-- Left side: profile info auto-injected by author_profile -->
  <div class="custom-home-text">
    <h2>Ph.D. Candidate in Agricultural and Consumer Economics</h2>
    <h3>University of Illinois Urbana-Champaign</h3>
    <p>
      My research lies at the intersection of international trade and environmental economics.
      I investigate how trade policies influence global trade patterns and assess their downstream
      environmental impacts—particularly greenhouse gas emissions from agriculture and land-use
      changes such as deforestation in Southeast Asia.
    </p>
  </div>
</div>
