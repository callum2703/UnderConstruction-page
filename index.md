---
layout: default
title: Page Temporarily Unavailable
---


<div class="maintenance-page">

  <div class="maintenance-card">
    <div class="maintenance-icon">⚙️</div>

    <h1>We're making improvements</h1>

    <p>
      This page is temporarily unavailable while we carry out updates.
      We're working to bring it back online shortly.
    </p>

    <!-- a href="/" class="maintenance-button">Return Home</a> -->
  </div>

</div>

<style>
.maintenance-page {
  min-height: 80vh;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 2rem;
  background:
    radial-gradient(circle at top left, #1fcada22, transparent 30%),
    radial-gradient(circle at bottom right, #1e355022, transparent 30%),
    linear-gradient(135deg, #f4f7fb, #ffffff);
}

.maintenance-card {
  max-width: 650px;
  width: 100%;
  background: white;
  padding: 3rem;
  border-radius: 20px;
  text-align: center;
  box-shadow: 0 20px 50px rgba(0,0,0,0.08);
  border: 1px solid #e5e7eb;
}

.maintenance-icon {
  font-size: 4rem;
  margin-bottom: 1rem;
  animation: spin 6s linear infinite;
}

h1 {
  margin-bottom: 1rem;
  color: #1e3550;
}

p {
  font-size: 1.1rem;
  color: #4b5563;
  line-height: 1.6;
  margin-bottom: 2rem;
}

.maintenance-button {
  display: inline-block;
  padding: 0.9rem 1.5rem;
  background: #1fcada;
  color: white;
  text-decoration: none;
  border-radius: 10px;
  font-weight: 600;
  transition: 0.3s ease;
}

.maintenance-button:hover {
  background: #17b2c0;
}

@keyframes spin {
  from {
    transform: rotate(0deg);
  }
  to {
    transform: rotate(360deg);
  }
}

@media (max-width: 768px) {
  .maintenance-card {
    padding: 2rem;
  }

  .maintenance-icon {
    font-size: 3rem;
  }
}

.page-header,
.site-footer,
.page-title,
footer {
  display: none;
}

main {
  padding: 0;
  margin: 0;
}

.maintenance-page {
  min-height: 100vh;
}
</style>
