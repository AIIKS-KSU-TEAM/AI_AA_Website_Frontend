<script setup>
import { useEvents } from '@/composables/useEvents';
import { useContact } from '@/composables/useContact';
import Navbar from '@/components/Navbar.vue';
import Footer from '@/components/Footer.vue';

const { recentHighlights, upcomingEvents } = useEvents();
const { name, email, message, formMessage, alertType, submitForm } = useContact();
</script>

<template>
  <Navbar />
  <div class="contact">
    <div class="container py-4">
      <div class="row">
        <!-- Contact Form -->
        <div class="col-md-6 mb-4 mb-md-0">
          <h2 class="h2 text-md-start mb-4">Contact Us</h2>
          <hr class="bg-warning w-25 mx-0 mx-md-0" />
          <p class="lead">
            Want to learn more about our work or discuss a potential partnership? Reach out to us, and let's build a better future together.
          </p>
          <form @submit="submitForm">
            <div v-if="formMessage" :class="['alert', alertType]" role="alert">
              {{ formMessage }}
            </div>
            <div class="mb-3">
              <label for="name" class="form-label">Name</label>
              <input
                type="text"
                class="form-control border-secondary shadow-sm"
                id="name"
                v-model="name"
                placeholder="Your Name"
                required
              />
            </div>
            <div class="mb-3">
              <label for="email" class="form-label">Email address</label>
              <input
                type="email"
                class="form-control border-secondary shadow-sm"
                id="email"
                placeholder="Your Email"
                v-model="email"
                required
              />
            </div>
            <div class="mb-3">
              <label for="message" class="form-label">Message</label>
              <textarea
                class="form-control border-secondary shadow-sm"
                id="message"
                v-model="message"
                rows="4"
                placeholder="Your Message"
                required
              ></textarea>
            </div>
            <button type="submit" class="btn btn-secondary w-100">
              Send Message
            </button>
          </form>
        </div>

        <!-- Map and Events Section -->
        <div class="col-md-6">
          <h2 class="h2 mb-4">Our Location</h2>
          <hr class="bg-warning w-25 mx-0 mx-md-0" />
          <div class="embed-responsive embed-responsive-16by9 mb-4">
            <iframe
              src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3286.8217088203!2d34.781737376012316!3d-0.6923034873102553!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x182b3f6840164ff1%3A0x8040e0d2e546b570!2sKisii%20University%20Main%20Campus!5e0!3m2!1sen!2ske!4v1723017296428!5m2!1sen!2ske"
              class="embed-responsive-item"
              width="100%"
              height="300"
              style="border-radius: 5px"
              allowfullscreen=""
              loading="lazy"
            >
            </iframe>
          </div>

          <!-- Recent Highlights -->
          <h2 class="h2 mt-2">Recent Highlights</h2>
          <hr class="bg-warning w-25 mx-0 mx-md-0" />
          <ul class="list-unstyled">
            <li v-for="event in recentHighlights" :key="event.id">
              <strong>{{ new Date(event.date).toLocaleDateString() }}:</strong>
              {{ event.title }} - {{ event.description }}
            </li>
          </ul>
        </div>
      </div>
    </div>
    <footer class="mt-2">
      <Footer />
    </footer>
  </div>
</template>
