// Smooth Scroll
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
  anchor.addEventListener("click", function(e) {
    e.preventDefault();
    document.querySelector(this.getAttribute("href")).scrollIntoView({
      behavior: "smooth"
    });
  });
});

// Contact Form Submission (demo only)
document.querySelector("form").addEventListener("submit", function(e) {
  e.preventDefault();
  alert("Message Sent Successfully!");
  this.reset();
});

// Section fade-in on scroll
document.querySelectorAll("section").forEach(section => {
  function revealSection() {
    const rect = section.getBoundingClientRect();
    if (rect.top < window.innerHeight - 50) {
      section.classList.add("visible");
    }
  }

  window.addEventListener("scroll", revealSection);
  // Initial check in case the section is already in view
  revealSection();
});
