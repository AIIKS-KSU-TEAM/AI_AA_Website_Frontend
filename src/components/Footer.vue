<script setup></script>

<template>
  <!-- Footer -->
  <footer class="bg-dark text-white pt-4">
    <div class="container">
      <div class="row">
        <!-- Footer Items -->
        <div class="col-md-3 mb-3">
          <img
            src="@/assets/images/logoA.png"
            class="img-fluid rounded"
            alt="AI AA NGO"
          />
          <p>
            Follow Us on Social Media.<br />
            Stay connected with AIAA and be the first to know about our latest
            news and initiatives.
          </p>
        </div>

        <div class="col-md-3 mb-3">
          <h2 class="h5">Quick Links</h2>
          <hr class="bg-warning w-25" />
          <ul class="list-unstyled">
            <li>
              <a href="/" class="text-white text-decoration-none">Home</a>
            </li>
            <li>
              <a href="/about" class="text-white text-decoration-none"
                >About Us</a
              >
            </li>
            <li>
              <a href="/impact" class="text-white text-decoration-none"
                >Our Impact</a
              >
            </li>
            <li>
              <a href="/blog" class="text-white text-decoration-none"
                >Educational Resources</a
              >
            </li>
            <li>
              <a href="/get-involved" class="text-white text-decoration-none"
                >Get Involved</a
              >
            </li>
            <li>
              <a href="/contact" class="text-white text-decoration-none"
                >Contact</a
              >
            </li>
          </ul>
        </div>

        <div class="col-md-3 mb-3">
          <h2 class="h5">Connect with Us</h2>
          <hr class="bg-warning w-25" />
          <ul class="list-unstyled">
            <li>
              <i class="bi bi-geo-alt me-2"></i>P.O.Box 12345-00100, Nairobi,
              Kenya
            </li>
            <li><i class="bi bi-telephone me-2"></i>+254-700-000-000</li>
            <li>
              <i class="bi bi-envelope me-2"></i
              ><a
                href="mailto:info@aiaango.org"
                class="text-white text-decoration-none"
                >info@aiaa-kenya.org</a
              >
            </li>
          </ul>
          <div class="mt-3">
            <a href="#" class="text-white text-decoration-none me-3"
              ><i class="bi bi-facebook"></i
            ></a>
            <a href="#" class="text-white text-decoration-none me-3"
              ><i class="bi bi-twitter"></i
            ></a>
            <a href="#" class="text-white text-decoration-none me-3"
              ><i class="bi bi-instagram"></i
            ></a>
            <a href="#" class="text-white text-decoration-none"
              ><i class="bi bi-linkedin"></i
            ></a>
          </div>
        </div>

        <div class="col-md-3 mb-3">
          <h2 class="h5">Important Links</h2>
          <hr class="bg-warning w-25" />
          <ul class="list-unstyled">
            <li>
              <a href="/privacy-policy" class="text-white text-decoration-none"
                >Privacy Policy</a
              >
            </li>
            <li>
              <a
                href="/terms-of-service"
                class="text-white text-decoration-none"
                >Terms of Service</a
              >
            </li>
            <li>
              <a href="/faq" class="text-white text-decoration-none">FAQ</a>
            </li>
            <li>
              <a href="/support" class="text-white text-decoration-none"
                >Support</a
              >
            </li>
          </ul>
        </div>
      </div>
    </div>
    <div class="bg-secondary text-center py-2">
      <small>&copy; 2024 AI AA NGO. All rights reserved.</small>
    </div>
  </footer>
</template>

<style scoped>
hr {
  height: 2px;
  border: none;
}
img {
  height: 50px;
}
</style>
