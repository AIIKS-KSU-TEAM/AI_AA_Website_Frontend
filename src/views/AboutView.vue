<script setup>
import { useMembers } from "@/composables/useMembers";
import Navbar from "@/components/Navbar.vue";
import Footer from "@/components/Footer.vue";

const { teamMembers } = useMembers();
</script>

<template>
  <div class="about-us">
    <Navbar />
    <!-- About Us Section -->
    <section class="about-section">
      <div class="container">
        <div class="row align-items-center">
          <div class="col-md-6">
            <img
              src="@/assets/images/collaborations.jpg"
              alt="About Us Image"
              class="img-fluid about-img"
            />
          </div>
          <div class="col-md-6">
            <h2 class="text-center text-md-start mt-3">About Us</h2>
            <hr class="bg-warning w-25 mx-auto mx-md-0" />
            <p>
              The Artificial Intelligence Alliance in Agriculture (AIAA) is a
              registered NGO in Kenya, operating in the counties of Kisii,
              Turkana, Baringo, Lamu, and Mombasa. Founded on the belief that
              technology can drive positive change, we focus on integrating AI
              and ICT in key sectors such as agriculture, education, health,
              governance, and environmental conservation. Our work is rooted in
              our vision of transforming Kenya into a leading model of
              sustainable development in Africa.
            </p>
          </div>
        </div>
      </div>
    </section>

   <!-- Directors Section -->
   <section class="services py-5">
      <div class="container">
        <h2 class="text-center mb-2">Directors</h2>
        <hr class="bg-warning w-25 mb-4 mx-auto" />
        <div class="row">
          <!-- Card 1 -->
          <div class="col-md-4 col-sm-6 col-12 mb-4">
            <div class="card service-card">
              <div class="card-img-container position-relative">
                <img
                  src="@/assets/images/Directors/ronald2.jpg"
                  alt="Dr. Ronald Tombe"
                  class="card-img-top "
                />
              </div>
              <div class="card-body">
                <h5 class="card-title fw-bold">Dr. Ronald Tombe</h5>
                <p class="card-text font-semibold">
                  Founder and Chairperson
                </p>
                <p>Dr. Tombe, Founder and Chairperson of AIAA-Kenya, leads strategic AI initiatives and ensures compliance.</p>
              </div>
            </div>
          </div>

          <!-- Card 2 -->
          <div class="col-md-4 col-sm-6 col-12 mb-4">
            <div class="card service-card">
              <div class="card-img-container position-relative">
                <img
                  src="@/assets/images/Directors/abuga.jpg"
                  alt="Dr. Jonathan Abuga"
                  class="card-img-top "
                />
              </div>
              <div class="card-body">
                <h5 class="card-title fw-bold">Dr. Jonathan Abuga</h5>
                <p class="card-text font-semibold">
                  Director, Epidemiology and Biostatistics
                </p>
                <p>Dr. Abuga, an expert in epidemiology and biostatistics, leads health projects using AI and data mining techniques.</p>
              </div>
            </div>
          </div>

          <!-- Card 3 -->
          <div class="col-md-4 col-sm-6 col-12 mb-4">
            <div class="card service-card">
              <div class="card-img-container position-relative">
                <img
                  src="@/assets/images/Directors/Chelal.jpg"
                  alt="Mrs. Evans Kipkemboi"
                  class="card-img-top "
                />
              </div>
              <div class="card-body">
                <h5 class="card-title fw-bold">Mrs. Evans Kipkemboi</h5>
                <p class="card-text font-semibold">
                  Director, Audit, Finance, and Human Resource Management
                </p>
                <p>Mr. Chelal, a skilled accountant, leads NGO auditing, financial oversight, and human resource management for optimal resource utilization.</p>
              </div>
            </div>
          </div>

          <!-- Additional cards follow the same pattern -->
          <div class="col-md-4 col-sm-6 col-12 mb-4">
            <div class="card service-card">
              <div class="card-img-container position-relative">
                <img
                  src="@/assets/images/Directors/Lenah1.jpg"
                  alt="Mrs. Lenah Nyamete"
                  class="card-img-top "
                />
              </div>
              <div class="card-body">
                <h5 class="card-title fw-bold">Mrs. Lenah Nyamete</h5>
                <p class="card-text font-semibold">
                  Director, ICT and AI Implementation
                </p>
                <p>Ms. Barongo, an ICT professional, leads AI-based NGO projects, driving implementation and strategic planning for impactful technological outcomes.</p>
              </div>
            </div>
          </div>

          <div class="col-md-4 col-sm-6 col-12 mb-4">
            <div class="card service-card">
              <div class="card-img-container position-relative">
                <img
                  src="@/assets/images/Directors/Levy1.jpg"
                  alt="Dr. Levy Otwoma"
                  class="card-img-top "
                />
              </div>
              <div class="card-body">
                <h5 class="card-title fw-bold">Dr. Levy Otwoma</h5>
                <p class="card-text font-semibold">
                  Director, Blue Economy and Sustainable Fish Farming
                </p>
                <p>Dr. Otwoma, a Blue Economy expert, leads AI-driven sustainable fish farming solutions, enhancing efficiency and conservation.</p>
              </div>
            </div>
          </div>

          <div class="col-md-4 col-sm-6 col-12 mb-4">
            <div class="card service-card">
              <div class="card-img-container position-relative">
                <img
                  src="@/assets/images/Directors/Linet1.jpg"
                  alt="Mrs. Linet Bosibori"
                  class="card-img-top "
                />
              </div>
              <div class="card-body">
                <h5 class="card-title fw-bold">Mrs. Linet Bosibori</h5>
                <p class="card-text font-semibold">
                  Director, Finance and Accounting
                </p>
                <p>
                  Ms. Bosibori, a finance expert, leads transparent financial management, overseeing budgeting, reporting, and compliance for the NGO.</p>
              </div>
            </div>
          </div>

          <div class="col-md-4 col-sm-6 col-12 mb-4">
            <div class="card service-card">
              <div class="card-img-container position-relative">
                <img
                  src="@/assets/images/Directors/Thairu.jpg"
                  alt="Mr. Paul Thairu"
                  class="card-img-top  "
                />
              </div>
              <div class="card-body">
                <h5 class="card-title fw-bold">Mr. Paul Thairu</h5>
                <p class="card-text font-semibold">
                  Director, Education and Governance
                </p>
                <p>
                  Mr. Thairu leads AI integration in education, driving inclusive learning and innovative projects across schools and TVET institutions.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Our Team Section -->
    <section class="our-team py-5">
      <div class="container">
        <h2 class="text-center mb-4">Secretariat</h2>
        <hr class="bg-warning mx-auto" style="width: 10%" />
        <div class="row">
          <div
            v-for="member in teamMembers"
            :key="member.name"
            class="col-md-4 col-sm-6 col-12 mb-4"
          >
            <div class="card team-card shadow-lg">
              <div class="team-img-container">
                <img
                  :src="member.image"
                  alt="Team Member Image"
                  class="team-img img-fluid"
                />
              </div>
              <div class="card-body text-center">
                <h5 class="card-title fw-bold">{{ member.name }}</h5>
                <p class="card-text lead">{{ member.title }}</p>
                <p class="card-text">{{ member.about }}</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Services Section -->
    <section class="services py-5">
      <div class="container">
        <h2 class="text-center mb-4">Explore Our Initiatives</h2>
        <hr class="bg-warning w-25 mx-auto" />
        <div class="row">
          <!-- Service 1 -->
          <div class="col-md-4 col-sm-6 col-12 mb-4">
            <div class="card service-card">
              <img
                src="@/assets/images/custom.png"
                alt="Custom Software Development"
                class="card-img-top"
              />
              <div class="card-body">
                <h5 class="card-title fw-bold">Custom Software Development</h5>
                <p class="card-text">
                  We build tailored software solutions to meet the unique needs
                  of farmers and agricultural businesses, enhancing operational
                  efficiency through AI technologies.
                </p>
              </div>
            </div>
          </div>

          <!-- Service 2 -->
          <div class="col-md-4 col-sm-6 col-12 mb-4">
            <div class="card service-card">
              <img
                src="@/assets/images/ed1.png"
                alt="Education and Training"
                class="card-img-top"
              />
              <div class="card-body">
                <h5 class="card-title fw-bold">Education and Literacy</h5>
                <p class="card-text">
                  Our education initiatives focus on integrating AI tools in the
                  curriculum and enhancing digital literacy among students,
                  teachers, and the wider community.
                </p>
              </div>
            </div>
          </div>

          <!-- Service 3 -->
          <div class="col-md-4 col-sm-6 col-12 mb-4">
            <div class="card service-card">
              <img
                src="@/assets/images/conservation.png"
                alt="AI-based Crop Monitoring"
                class="card-img-top"
              />
              <div class="card-body">
                <h5 class="card-title fw-bold">Environmental Conservation</h5>
                <p class="card-text">
                  Our commitment to environmental sustainability is reflected in
                  our initiatives to promote AI-powered solutions that protect
                  Kenya’s natural resources and ecosystems.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>

  <Footer />
</template>

<style scoped>
.about-us {
  font-family: Arial, sans-serif;
}

.about-section {
  padding: 3rem 0;
}

.about-img {
  width: 100%;
  height: auto;
  max-height: 400px;
  border-radius: 8px;
  object-fit: cover;
}
.services .service-card .card-img-top {
  height: 240px; 
  object-fit: cover;
}

.our-team {
  background-color: #f8f9fa;
  padding: 3rem 0;
}

.team-card {
  border: 1px solid #e0e0e0;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  text-align: center;
  height: 90%;
  position: relative;
  margin-top: 80px;
  z-index: 0;
}

.team-img-container {
  position: absolute;
  top: -80px;
  left: 50%;
  transform: translateX(-50%);
  z-index: 10;
}

.team-img {
  width: 150px;
  height: 150px;
  object-fit: cover;
  border-radius: 50%;
  border: 5px solid rgb(229, 226, 226);
}

.card-body {
  padding-top: 80px;
}

.card-title {
  font-size: 1.5rem;
  margin-bottom: 0.5rem;
  font-weight: bold;
}

.card-text.lead {
  font-size: 1.25rem;
  margin-bottom: 1rem;
}

.card-text {
  font-size: 1rem;
  line-height: 1.6;
}

.services .service-card {
  border: 1px solid #e0e0e0;
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.services .card-img-top {
  height: 350px;
  object-fit: cover;
}

.services .card-body {
  text-align: center;
}

.services .card-title {
  font-size: 1.25rem;
  font-weight: bold;
  margin-bottom: 0.25rem;
}

.services .card-text {
  font-size: 1rem;
  line-height: 1.6;
}

@media (max-width: 768px) {
  .about-section .row {
    flex-direction: column;
  }

  .our-team .row {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
}
</style>

