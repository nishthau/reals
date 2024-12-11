/**
* Template Name: Arsha
* Updated: Jan 29 2024 with Bootstrap v5.3.2
* Template URL: https://bootstrapmade.com/arsha-free-bootstrap-html-template-corporate/
* Author: BootstrapMade.com
* License: https://bootstrapmade.com/license/
*/

(function() {
  "use strict";

  /**
   * Easy selector helper function
   */
  const select = (el, all = false) => {
    el = el.trim()
    if (all) {
      return [...document.querySelectorAll(el)]
    } else {
      return document.querySelector(el)
    }
  }

  /**
   * Easy event listener function
   */
  const on = (type, el, listener, all = false) => {
    let selectEl = select(el, all)
    if (selectEl) {
      if (all) {
        selectEl.forEach(e => e.addEventListener(type, listener))
      } else {
        selectEl.addEventListener(type, listener)
      }
    }
  }

  /**
   * Easy on scroll event listener 
   */
  const onscroll = (el, listener) => {
    el.addEventListener('scroll', listener)
  }

  /**
   * Navbar links active state on scroll
   */
  let navbarlinks = select('#navbar .scrollto', true)
  const navbarlinksActive = () => {
    let position = window.scrollY + 200
    navbarlinks.forEach(navbarlink => {
      if (!navbarlink.hash) return
      let section = select(navbarlink.hash)
      if (!section) return
      if (position >= section.offsetTop && position <= (section.offsetTop + section.offsetHeight)) {
        navbarlink.classList.add('active')
      } else {
        navbarlink.classList.remove('active')
      }
    })
  }
  window.addEventListener('load', navbarlinksActive)
  onscroll(document, navbarlinksActive)

  /**
   * Scrolls to an element with header offset
   */
  const scrollto = (el) => {
    let header = select('#header')
    let offset = header.offsetHeight

    let elementPos = select(el).offsetTop
    window.scrollTo({
      top: elementPos - offset,
      behavior: 'smooth'
    })
  }

  /**
   * Toggle .header-scrolled class to #header when page is scrolled
   */
  let selectHeader = select('#header')
  if (selectHeader) {
    const headerScrolled = () => {
      if (window.scrollY > 100) {
        selectHeader.classList.add('header-scrolled')
      } else {
        selectHeader.classList.remove('header-scrolled')
      }
    }
    window.addEventListener('load', headerScrolled)
    onscroll(document, headerScrolled)
  }

  /**
   * Back to top button
   */
  let backtotop = select('.back-to-top')
  if (backtotop) {
    const toggleBacktotop = () => {
      if (window.scrollY > 100) {
        backtotop.classList.add('active')
      } else {
        backtotop.classList.remove('active')
      }
    }
    window.addEventListener('load', toggleBacktotop)
    onscroll(document, toggleBacktotop)
  }

  /**
   * Mobile nav toggle
   */
  on('click', '.mobile-nav-toggle', function(e) {
    select('#navbar').classList.toggle('navbar-mobile')
    this.classList.toggle('bi-list')
    this.classList.toggle('bi-x')
  })

  /**
   * Mobile nav dropdowns activate
   */
  on('click', '.navbar .dropdown > a', function(e) {
    if (select('#navbar').classList.contains('navbar-mobile')) {
      e.preventDefault()
      this.nextElementSibling.classList.toggle('dropdown-active')
    }
  }, true)

  /**
   * Scrool with ofset on links with a class name .scrollto
   */
  on('click', '.scrollto', function(e) {
    if (select(this.hash)) {
      e.preventDefault()

      let navbar = select('#navbar')
      if (navbar.classList.contains('navbar-mobile')) {
        navbar.classList.remove('navbar-mobile')
        let navbarToggle = select('.mobile-nav-toggle')
        navbarToggle.classList.toggle('bi-list')
        navbarToggle.classList.toggle('bi-x')
      }
      scrollto(this.hash)
    }
  }, true)





  /**
   * Scroll with ofset on page load with hash links in the url
   */
  window.addEventListener('load', () => {
    if (window.location.hash) {
      if (select(window.location.hash)) {
        scrollto(window.location.hash)
      }
    }
  });

  /**
   * Preloader
   */
  let preloader = select('#preloader');
  if (preloader) {
    window.addEventListener('load', () => {
      preloader.remove()
    });
  }

  /**
   * Initiate  glightbox 
   */
  const glightbox = GLightbox({
    selector: '.glightbox'
  });

  /**
   * Skills animation
   */
  let skilsContent = select('.skills-content');
  if (skilsContent) {
    new Waypoint({
      element: skilsContent,
      offset: '80%',
      handler: function(direction) {
        let progress = select('.progress .progress-bar', true);
        progress.forEach((el) => {
          el.style.width = el.getAttribute('aria-valuenow') + '%'
        });
      }
    })
  }

  /**
   * Porfolio isotope and filter
   */
  window.addEventListener('load', () => {
    let portfolioContainer = select('.portfolio-container');
    if (portfolioContainer) {
      let portfolioIsotope = new Isotope(portfolioContainer, {
        itemSelector: '.portfolio-item'
      });

      let portfolioFilters = select('#portfolio-flters li', true);

      on('click', '#portfolio-flters li', function(e) {
        e.preventDefault();
        portfolioFilters.forEach(function(el) {
          el.classList.remove('filter-active');
        });
        this.classList.add('filter-active');

        portfolioIsotope.arrange({
          filter: this.getAttribute('data-filter')
        });
        portfolioIsotope.on('arrangeComplete', function() {
          AOS.refresh()
        });
      }, true);
    }

  });

  /**
   * Initiate portfolio lightbox 
   */
  const portfolioLightbox = GLightbox({
    selector: '.portfolio-lightbox'
  });

  /**
   * Portfolio details slider
   */
  new Swiper('.portfolio-details-slider', {
    speed: 400,
    loop: true,
    autoplay: {
      delay: 5000,
      disableOnInteraction: false
    },
    pagination: {
      el: '.swiper-pagination',
      type: 'bullets',
      clickable: true
    }
  });

  /**
   * Animation on scroll
   */
  window.addEventListener('load', () => {
    AOS.init({
      duration: 1000,
      easing: "ease-in-out",
      once: true,
      mirror: false
    });
  });


}

)();
  

var privacyContent ='<h3>Privacy Policy</h3>';                                                     
privacyContent +='<p><strong>Effective Date:</strong> 09/12/2024</p>';
privacyContent +='  <p>Reals ("we," "our," or "us") is committed to protecting your privacy. This Privacy Policy outlines how we collect, use, store, and share your information when you use our services.</p>';
privacyContent +='<br>';
privacyContent +='  <h5>1. Information We Collect</h5>';
privacyContent +='  <p>We may collect the following types of information:</p>';
privacyContent +='  <ul>';
privacyContent +='    <li><strong>Personal Information:</strong> Name, email address, phone number, and payment details provided during account creation or transactions.</li>';
privacyContent +='    <li><strong>Usage Data:</strong> Information about how you use our services, including IP address, device information, and browsing activity.</li>';
privacyContent +='    <li><strong>Transactional Data:</strong> Records of mobile recharges, data top-ups, and wallet usage.</li>';
privacyContent +='  </ul>';
privacyContent +='<br>';
privacyContent +='  <h5>2. How We Use Your Information</h5>';
privacyContent +='  <p>We use the information we collect for the following purposes:</p>';
privacyContent +='  <ul>';
privacyContent +='    <li>To process transactions, including mobile recharges and data top-ups.</li>';
privacyContent +='    <li>To provide and improve our services.</li>';
privacyContent +='    <li>To secure your account and prevent fraud.</li>';
privacyContent +='    <li>To send you updates, promotional offers, and service notifications.</li>';
privacyContent +='    <li>To comply with legal obligations and resolve disputes.</li>';
privacyContent +='  </ul>';
privacyContent +='<br>';
privacyContent +='  <h5>3. How We Share Your Information</h5>';
privacyContent +='  <p>We do not sell or rent your personal information to third parties. However, we may share your information with:</p>';
privacyContent +='  <ul>';
privacyContent +='    <li><strong>Service Providers:</strong> Third-party partners who assist with payment processing, security, and other operational tasks.</li>';
privacyContent +='    <li><strong>Legal Authorities:</strong> If required by law or in response to a valid legal request.</li>';
privacyContent +='  </ul>';
privacyContent +='<br>';
privacyContent +='  <h5>4. Data Security</h5>';
privacyContent +='  <p>We use industry-standard encryption and security measures to protect your personal information. Despite our efforts, no system can guarantee 100% security.</p>';
privacyContent +='<br>';
privacyContent +='  <h5>5. Your Rights</h5>';
privacyContent +='  <p>You have the right to:</p>';
privacyContent +='  <ul>';
privacyContent +='    <li>Access, update, or delete your personal information by logging into your account or contacting us.</li>';
privacyContent +='    <li>Opt-out of receiving marketing communications by following the unsubscribe instructions in our emails.</li>';
privacyContent +='  </ul>';
privacyContent +='<br>';
privacyContent +='  <h5>6. Cookies and Tracking Technologies</h5>';
privacyContent +='  <p>We use cookies and similar technologies to improve your experience on our website. These help us analyze usage patterns and deliver personalized content.</p>';
privacyContent +='<br>';
privacyContent +='  <h5>7. Third-Party Links</h5>';
privacyContent +='  <p>Our website may contain links to third-party websites. We are not responsible for the privacy practices of these sites and encourage you to review their policies.</p>';
privacyContent +='<br>';
privacyContent +='  <h5>8. Changes to This Policy</h5>';
privacyContent +='  <p>We may update this Privacy Policy from time to time. Any changes will be posted on this page, and the "Effective Date" will be revised accordingly.</p>';
privacyContent +='<br>';
privacyContent +='  <h5>9. Contact Us</h5>';
privacyContent +='  <p>If you have questions about this Privacy Policy or how we handle your information, please contact us:</p>';
privacyContent +='  <p><strong>Email:</strong> relas@gmail.com</p>';
privacyContent +='  <p><strong>Phone:</strong> +1 999-999-9999</p>';

// Add Privacy Policy content to the modal
document.getElementById("privacyPolicyContent").innerHTML = privacyContent;
  
// // Clear Login form on close
// $(document).ready(function() {
//   // When the modal is hidden, clear the form fields
//   $('#loginModal').on('hidden.bs.modal', function () {
//       $('#loginForm')[0].reset();
//   });
// });

// // Clear Free Trial form on close
// $(document).ready(function() {
//   // When the modal is hidden, clear the form fields
//   $('#freeTrialModal').on('hidden.bs.modal', function () {
//       $('#freeTrialForm')[0].reset();
//   });
// });


// $(document).ready(function() {
//   $('#freeTrialModal').on('hidden.bs.modal', function () {
//       $('#freeTrialForm')[0].reset();
//   });
// });

document.querySelectorAll('.open-modal').forEach(function (link) {
  link.addEventListener('click', function (event) {
    event.preventDefault();
    const modalId = link.getAttribute('data-toggle'); // Get the target modal ID
    const modal = new bootstrap.Modal(document.querySelector(modalId));
    modal.show();
  });
});

document.querySelectorAll('.scroll-link').forEach(link => {
  link.addEventListener('click', function(event) {
    event.preventDefault();
    const targetId = this.getAttribute('href').substring(1); // Get the ID without #
    const targetElement = document.getElementById(targetId);
    if (targetElement) {
      targetElement.scrollIntoView({ behavior: 'smooth' }); // Scroll to the target element
    }
  });
});
