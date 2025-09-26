---
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
/* Wrapper for two-column layout */
.custom-home-wrapper {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  max-width: 1200px;
  margin: 30px auto 0 auto;
  padding: 0 40px;
  gap: 80px;
}

/* Right-hand side content */
.custom-home-text {
  flex: 1;
  margin-top: 40px;
  max-width: 750px;
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
  font-size: 17px;
  line-height: 1.75;
  text-align: justify;
}

/* Responsive fallback */
@media (max-width: 992px) {
  .custom-home-wrapper {
    flex-direction: column;
    padding: 20px;
    gap: 20px;
  }

  .custom-home-text {
    margin-top: 10px;
    max-width: 100%;
  }
}
</style>

<div class="custom-home-wrapper">
  <!-- The left side (author profile) is auto-injected by author_profile: true -->
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
