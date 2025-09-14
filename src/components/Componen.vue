<template setup>
  <!-- gambar nav -->
   
  <div class="relative w-full">
    <!-- Gambar -->
    <img src="/gambar/gambar2.jpg" alt="Desk with a laptop and a coffee cup" class="w-full object-cover h-[33rem]" />

    <!-- Teks di tengah -->
    <div class="absolute inset-0 flex items-center justify-center">
      <p id="jaring" class="text-white text-7xl">My Network</p>
    </div>
  </div>

  <!-- keterangan -->
  <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6 my-[4rem]">
    <!-- Card 1 -->
    <div class="bg-white rounded-2xl shadow-lg p-4 text-center h-[28rem] flex flex-col justify-center">
      <img src="/gambar/remoteacces.png" alt="Remote Access" class="w-28 h-28 object-cover rounded-lg mb-4 mx-auto" />
      <h3 class="text-lg font-semibold text-gray-800">Remote Access</h3>
      <p class="text-gray-600 text-sm mt-2">Ini adalah keterangan bio singkat untuk kotak pertama.</p>
      <button class="mt-4 px-5 py-2 bg-gradient-to-r from-blue-400 to-blue-600 text-white font-medium rounded-full shadow-md hover:from-blue-500 hover:to-blue-600 hover:shadow-lg transition-all duration-300">Lihat Selengkapnya</button>
    </div>

    <!-- Card 2 -->
    <div class="bg-white rounded-2xl shadow-lg p-4 text-center h-[28rem] flex flex-col justify-center mt-14">
      <img src="/gambar/speed.png" alt="Internet Speed" class="w-28 h-28 object-cover rounded-lg mb-4 mx-auto" />
      <h3 class="text-lg font-semibold text-gray-800">Internet Speed</h3>
      <p class="text-gray-600 text-sm mt-2">Ini adalah keterangan bio singkat untuk kotak kedua.</p>
      <button class="mt-4 px-5 py-2 bg-gradient-to-r from-blue-400 to-blue-600 text-white font-medium rounded-full shadow-md hover:from-blue-500 hover:to-blue-600 hover:shadow-lg transition-all duration-300">Lihat Selengkapnya</button>
    </div>

    <!-- Card 3 -->
    <div class="bg-white rounded-2xl shadow-lg p-4 text-center h-[28rem] flex flex-col justify-center">
      <img src="/gambar/services.png" alt="IT Services" class="w-28 h-28 object-cover rounded-lg mb-4 mx-auto" />
      <h3 class="text-lg font-semibold text-gray-800">IT Services</h3>
      <p class="text-gray-600 text-sm mt-2">Ini adalah keterangan bio singkat untuk kotak ketiga.</p>
      <button class="mt-4 px-5 py-2 bg-gradient-to-r from-blue-400 to-blue-600 text-white font-medium rounded-full shadow-md hover:from-blue-500 hover:to-blue-600 hover:shadow-lg transition-all duration-300">Lihat Selengkapnya</button>
    </div>

    <!-- Card 4 -->
    <div class="bg-white rounded-2xl shadow-lg p-4 text-center h-[28rem] flex flex-col justify-center mt-14">
      <img src="/gambar/Network.png" alt="Network Security" class="w-28 h-28 object-cover rounded-lg mb-4 mx-auto" />
      <h3 class="text-lg font-semibold text-gray-800">Network Security</h3>
      <p class="text-gray-600 text-sm mt-2">Ini adalah keterangan bio singkat untuk kotak keempat.</p>
      <button class="mt-4 px-5 py-2 bg-gradient-to-r from-blue-400 to-blue-600 text-white font-medium rounded-full shadow-md hover:from-blue-500 hover:to-blue-600 hover:shadow-lg transition-all duration-300">Lihat Selengkapnya</button>
    </div>
  </div>

  <!-- About My Network -->
  <section class="bg-gray-50 py-12 px-6" id="About">
    <div class="max-w-6xl mx-auto grid md:grid-cols-2 gap-8 items-center">
      <!-- Bagian Kiri -->
      <div>
        <h2 class="text-4xl font-bold text-gray-800 mb-6">About My Network</h2>
        <ul class="space-y-4 text-gray-700">
          <li class="flex items-center"><span class="text-blue-500 mr-3">✔</span> Smart Lighting Setup</li>
          <li class="flex items-center"><span class="text-blue-500 mr-3">✔</span> Media Room Setup</li>
          <li class="flex items-center"><span class="text-blue-500 mr-3">✔</span> Home Theater Setup</li>
          <li class="flex items-center"><span class="text-blue-500 mr-3">✔</span> Smart Doorbell Installation</li>
          <li class="flex items-center"><span class="text-blue-500 mr-3">✔</span> Smart Thermostat Installation</li>
          <li class="flex items-center"><span class="text-blue-500 mr-3">✔</span> Smart Door Lock Installation</li>
        </ul>

        <!-- Tombol -->
        <button class="mt-8 px-6 py-3 border-2 border-blue-300 text-blue-500 font-semibold rounded-full bg-white hover:bg-gradient-to-r hover:from-blue-400 hover:to-blue-600 hover:text-white transition-all duration-500 ease-in-out">
          GET INSPIRED
        </button>
      </div>

      <!-- Bagian Kanan -->
      <div class="flex justify-center">
        <img src="/gambar/Router.jpg" alt="Smart Home Device" class="rounded-3xl shadow-lg object-cover w-full max-w-sm" />
      </div>
    </div>
  </section>

  <!-- penggunaan my network -->
  <section class="py-16" id="Layanan">
    <div class="max-w-7xl mx-auto px-6">
      <!-- Judul -->
      <h2 class="text-4xl font-bold text-center text-gray-900 mb-12">Manage Everything</h2>

      <!-- Grid -->
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
        <!-- Card 1 -->
      <div class="relative rounded-xl overflow-hidden shadow-lg hover:brightness-50 transition duration-300">
          <img src="/gambar/proses1.jpg" alt="Outdoor CCTV" class="w-full h-80 object-cover" />
          <div class="absolute inset-0 bg-black/20 flex items-end">
            <div class="p-4">
              <h3 class="text-white text-lg font-semibold">Outdoor CCTV</h3>
              <p class="text-gray-200 text-sm">Ut enim ad minim veniam</p>
            </div>
          </div>
        </div>

        <!-- Card 2 -->
          <div class="relative rounded-xl overflow-hidden shadow-lg hover:brightness-50 transition duration-300">
          <img src="/gambar/proses2.jpg" alt="Temperature Controller" class="w-full h-80 object-cover" />
          <div class="absolute inset-0 bg-black/20 flex items-end">
            <div class="p-4">
              <h3 class="text-white text-lg font-semibold">Temperature Controller</h3>
              <p class="text-gray-200 text-sm">Ut enim ad minim veniam</p>
            </div>
          </div>
        </div>

        <!-- Card 3 -->
         <div class="relative rounded-xl overflow-hidden shadow-lg hover:brightness-50 transition duration-300">
          <img src="/gambar/proses3.jpg" alt="Tracking" class="w-full h-80 object-cover" />
          <div class="absolute inset-0 bg-black/20 flex items-end">
            <div class="p-4">
              <h3 class="text-white text-lg font-semibold">Tracking</h3>
              <p class="text-gray-200 text-sm">Ut enim ad minim veniam</p>
            </div>
          </div>
        </div>

        <!-- Card 4 -->
       <div class="relative rounded-xl overflow-hidden shadow-lg hover:brightness-50 transition duration-300">
          <img src="/gambar/proses4.jpg" alt="Smart Speaker" class="w-full h-80 object-cover" />
          <div class="absolute inset-0 bg-black/20 flex items-end">
            <div class="p-4">
              <h3 class="text-white text-lg font-semibold">Smart Speaker</h3>
              <p class="text-gray-200 text-sm">Ut enim ad minim veniam</p>
            </div>
          </div>
        </div>

        <!-- Card 5 -->
          <div class="relative rounded-xl overflow-hidden shadow-lg hover:brightness-50 transition duration-300">
          <img src="/gambar/proses5.jpg" alt="Smart Lamp" class="w-full h-80 object-cover" />
          <div class="absolute inset-0 bg-black/20 flex items-end">
            <div class="p-4">
              <h3 class="text-white text-lg font-semibold">Smart Lamp</h3>
              <p class="text-gray-200 text-sm">Ut enim ad minim veniam</p>
            </div>
          </div>
        </div>

        <!-- Card 6 -->
          <div class="relative rounded-xl overflow-hidden shadow-lg hover:brightness-50 transition duration-300">
          <img src="/gambar/proses6.jpg" alt="Planning" class="w-full h-80 object-cover" />
          <div class="absolute inset-0 bg-black/20 flex items-end">
            <div class="p-4">
              <h3 class="text-white text-lg font-semibold">Planning</h3>
              <p class="text-gray-200 text-sm">Ut enim ad minim veniam</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Rady Build -->
  <div class="relative min-h-screen overflow-hidden">
    <!-- Background overlay -->
    <div class="absolute inset-0 bg-gradient-to-br from-gray-700 to-gray-900"></div>

    <!-- Top status bar -->
    <div class="relative z-10 flex justify-between items-center p-4 text-white text-sm">
      <div class="flex items-center space-x-2">
        <div class="w-4 h-2 bg-white rounded-full"></div>
        <span>Song</span>
      </div>

      <div class="text-right">
        <div class="text-xs opacity-75">Mostly cloudy</div>
        <div class="text-2xl font-light">30°</div>
      </div>
    </div>

    <!-- Main content -->
    <div class="relative z-10 flex flex-col items-center justify-center min-h-screen px-6 -mt-20">
      <!-- Plant decoration -->
      <div class="absolute left-8 bottom-32 w-24 h-32 opacity-60">
        <div class="w-4 h-16 bg-green-800 rounded-full mx-auto"></div>
        <div class="relative -mt-12">
          <div class="w-8 h-6 bg-green-600 rounded-full transform -rotate-12 absolute -left-2"></div>
          <div class="w-10 h-8 bg-green-700 rounded-full transform rotate-12 absolute right-0 -top-1"></div>
          <div class="w-6 h-4 bg-green-500 rounded-full transform -rotate-45 absolute -left-1 top-4"></div>
          <div class="w-8 h-6 bg-green-600 rounded-full transform rotate-45 absolute right-1 top-6"></div>
        </div>
      </div>

      <!-- Main heading -->
      <h1 class="text-4xl md:text-5xl lg:text-6xl font-light text-white text-center mb-8 max-w-4xl">Ready to build a My Network?</h1>

      <!-- Description -->
      <p class="text-gray-300 text-center max-w-2xl mb-12 text-lg leading-relaxed">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam.</p>

      <!-- CTA Button -->
      <button class="bg-transparent border-2 border-white text-white px-8 py-4 rounded-full text-lg font-medium hover:bg-white hover:text-gray-900 transition-all duration-300 transform hover:scale-105">GET FREE ESTIMATE</button>

      <!-- Smart device mockup -->
      <div class="absolute right-8 bottom-20 transform rotate-12">
        <div class="w-32 h-48 bg-gray-800 rounded-2xl border-4 border-gray-600 shadow-2xl">
          <!-- Screen -->
          <div class="w-full h-full bg-gray-900 rounded-xl p-3">
            <!-- Status bar -->
            <div class="flex justify-center items-center mb-4">
              <div class="text-blue-400 text-xs">10:00</div>
            </div>

            <!-- Content -->
            <div class="space-y-3">
              <div class="w-full h-2 bg-gray-700 rounded"></div>
              <div class="w-3/4 h-2 bg-gray-700 rounded"></div>

              <!-- Circular indicator -->
              <div class="flex justify-center my-6">
                <div class="w-16 h-16 border-2 border-blue-400 rounded-full flex items-center justify-center">
                  <div class="w-3 h-3 bg-blue-400 rounded-full"></div>
                </div>
              </div>

              <!-- Bottom elements -->
              <div class="flex justify-between">
                <div class="w-6 h-6 bg-gray-700 rounded"></div>
                <div class="w-6 h-6 bg-gray-700 rounded"></div>
                <div class="w-6 h-6 bg-gray-700 rounded"></div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Bottom navigation dots -->
    <div class="absolute bottom-8 left-1/2 transform -translate-x-1/2 flex space-x-3">
      <div class="w-2 h-2 bg-white rounded-full opacity-50"></div>
      <div class="w-8 h-2 bg-white rounded-full"></div>
      <div class="w-2 h-2 bg-white rounded-full opacity-50"></div>
      <div class="w-2 h-2 bg-white rounded-full opacity-50"></div>
    </div>
  </div>

  <!-- penggunaan jumlah -->
  <section class="bg-gray-100 flex items-center justify-center min-h-screen">
    <div class="max-w-6xl mx-auto rounded-2xl py-16 grid grid-cols-1 md:grid-cols-2 gap-8">
      <!-- Bagian Kiri (Gambar) -->
      <div class="flex justify-center items-center">
        <img src="/gambar/ruangan.jpg" alt="Smart Home" class="rounded-2xl w-full h-96 object-cover" />
      </div>

      <!-- Bagian Kanan (Text) -->
      <div class="flex flex-col justify-center text-center md:text-left">
        <h2 class="text-4xl font-bold text-gray-900 mb-4">About My Network</h2>
        <p class="text-gray-600 mb-6">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation.</p>

        <!-- Statistik -->
        <div class="grid grid-cols-3 gap-4 mt-4">
          <div>
            <p class="text-2xl font-bold text-sky-600">300+</p>
            <p class="text-sm font-semibold text-gray-700">HAPPY CLIENTS</p>
          </div>
          <div>
            <p class="text-2xl font-bold text-sky-600">10+</p>
            <p class="text-sm font-semibold text-gray-700">YEARS OF EXPERIENCE</p>
          </div>
          <div>
            <p class="text-2xl font-bold text-sky-600">17</p>
            <p class="text-sm font-semibold text-gray-700">AWARDS</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- info pengguna -->
  <div class="h-screen p-8">
    <h2 class="text-3xl font-bold text-center mb-12 mt-[5rem]">What People Say?</h2>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
      <div class="bg-gray-100 p-6 rounded-xl shadow-md border border-gray-200">
        <h3 class="text-lg font-semibold mb-2">Stella Larson</h3>
        <p class="text-gray-700">Proin sed libero enim sed faucibus turpis. At imperdiet dui accumsan sit amet nulla facilisi morbi tempus. Ut sem nulla pharetra diam sit amet nisl.</p>
        <div class="h-px bg-gray-300 my-4"></div>
        <p class="text-sm text-gray-500">MONDAY, MAY 2024</p>
      </div>

      <div class="bg-gray-100 p-6 rounded-xl shadow-md border border-gray-200">
        <h3 class="text-lg font-semibold mb-2">Nick Jhonsoon</h3>
        <p class="text-gray-700">Proin sed libero enim sed faucibus turpis. At imperdiet dui accumsan sit amet nulla facilisi morbi tempus. Ut sem nulla pharetra diam sit amet nisl.</p>
        <div class="h-px bg-gray-300 my-4"></div>
        <p class="text-sm text-gray-500">MONDAY, JUNE 2024</p>
      </div>

      <div class="bg-gray-100 p-6 rounded-xl shadow-md border border-gray-200">
        <h3 class="text-lg font-semibold mb-2">Olga Ivanova</h3>
        <p class="text-gray-700">Proin sed libero enim sed faucibus turpis. At imperdiet dui accumsan sit amet nulla facilisi morbi tempus. Ut sem nulla pharetra diam sit amet nisl.</p>
        <div class="h-px bg-gray-300 my-4"></div>
        <p class="text-sm text-gray-500">MONDAY, MAY 2024</p>
      </div>
    </div>
  </div>

  <!-- penejalasan -->
  <div class="max-w-4xl mx-auto px-6 py-12 bg-white">
    <!-- Header -->
    <div class="text-center mb-12">
      <h1 class="text-4xl md:text-5xl font-bold text-gray-900 mb-4">Facts & Questions</h1>
      <p class="text-gray-600 text-lg max-w-2xl mx-auto">Sample text. Click to select the text box. Click again or double click to start editing the text.</p>
    </div>

    <!-- FAQ Accordion -->
    <div class="space-y-4">
      <div v-for="(item, index) in faqItems" :key="index" class="bg-gray-100 rounded-2xl overflow-hidden transition-all duration-300 ease-in-out">
        <button @click="toggleAccordion(index)" class="w-full px-6 py-5 text-left flex justify-between items-center hover:bg-gray-200 transition-colors duration-200">
          <span class="text-lg font-semibold text-gray-900 pr-4">
            {{ item.question }}
          </span>
          <div class="flex-shrink-0">
            <svg :class="['w-6 h-6 text-gray-600 transition-transform duration-300', openItems[index] ? 'rotate-45' : '']" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6v6m0 0v6m0-6h6m-6 0H6" />
            </svg>
          </div>
        </button>

        <div :class="['overflow-hidden transition-all duration-300 ease-in-out', openItems[index] ? 'max-h-96 opacity-100' : 'max-h-0 opacity-0']">
          <div class="px-6 pb-6">
            <div class="text-gray-700 leading-relaxed">
              {{ item.answer }}
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Kontak -->
  <div id="Kontak" class="flex flex-col lg:flex-row items-center justify-center min-h-screen bg-white px-6 lg:px-12">
    <!-- Left side (Form) -->
    <div class="w-full lg:w-1/2 flex flex-col items-start space-y-6">
      <h2 class="text-2xl font-semibold">We are here to help</h2>

      <form class="w-full bg-gray-100 p-6 rounded-2xl space-y-4 shadow-sm">
        <!-- Name -->
        <div class="flex flex-col">
          <label for="name" class="block text-sm font-medium text-gray-700 rounded-md px-2 py-1 transition peer-focus-within:shadow peer-focus-within:shadow-blue-400"> Name </label>
          <input id="name" type="text" placeholder="Enter your Name" class="peer mt-1 w-full rounded-full border-gray-300 shadow-sm focus:border-blue-500 focus:ring focus:ring-blue-200 focus:ring-opacity-50 px-4 py-2" />
        </div>

        <!-- Email -->
        <div class="flex flex-col">
          <label for="email" class="block text-sm font-medium text-gray-700 rounded-md px-2 py-1 transition peer-focus-within:shadow peer-focus-within:shadow-blue-400"> Email </label>
          <input id="email" type="email" placeholder="Enter a valid email address" class="peer mt-1 w-full rounded-full border-gray-300 shadow-sm focus:border-blue-500 focus:ring focus:ring-blue-200 focus:ring-opacity-50 px-4 py-2" />
        </div>

        <!-- Message -->
        <div class="flex flex-col">
          <label for="message" class="block text-sm font-medium text-gray-700 rounded-md px-2 py-1 transition peer-focus-within:shadow peer-focus-within:shadow-blue-400"> Message </label>
          <textarea id="message" rows="4" placeholder="Enter your message" class="peer mt-1 w-full rounded-2xl border-gray-300 shadow-sm focus:border-blue-500 focus:ring focus:ring-blue-200 focus:ring-opacity-50 px-4 py-2"></textarea>
        </div>

        <!-- Button -->
        <button type="submit" class="bg-sky-400 text-white font-semibold px-8 py-2 rounded-full hover:bg-sky-500 transition">SEND</button>
      </form>
    </div>

    <!-- Right side (Image) -->
    <div class="w-full lg:w-1/2 flex justify-center mt-10 lg:mt-0">
      <img src="/gambar/kontak.png" alt="Help illustration" class="rounded-2xl ml-3 mt-10" />
    </div>
  </div>
</template>

<script>
import { ref, reactive } from "vue";

export default {
  name: "Componen",
  name: "FaqAccordion",
  setup() {
    const faqItems = ref([
      {
        question: "How much does it cost?",
        answer: "Our pricing varies depending on the scope and complexity of your project. We offer competitive rates and flexible packages to suit different budgets. Contact us for a detailed quote tailored to your specific needs.",
      },
      {
        question: "How Fast Are Your Services?",
        answer:
          "Project timelines depend on complexity and scope. Simple projects can be completed within 1-2 weeks, while more complex solutions may take 4-8 weeks. We always provide realistic timelines upfront and keep you updated throughout the process.",
      },
      {
        question: "What types of customers have you worked with?",
        answer:
          "We've worked with a diverse range of clients including startups, small businesses, enterprise companies, non-profit organizations, and individual entrepreneurs across various industries such as technology, healthcare, finance, and e-commerce.",
      },
      {
        question: "What education and/or training do you have that relates to your work?",
        answer:
          "Our team has extensive experience in software development, design, and project management. We hold relevant degrees in computer science and related fields, along with industry certifications and continuous learning to stay current with the latest technologies and best practices.",
      },
      {
        question: "Nunc sit amet nibh dolor. Integer iaculis nisl nec libero elementum?",
        answer:
          "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.",
      },
    ]);

    const openItems = reactive({});

    const toggleAccordion = (index) => {
      openItems[index] = !openItems[index];
    };

    return {
      faqItems,
      openItems,
      toggleAccordion,
    };
  },
};
</script>

<style scoped>
#jaring {
  font-family: "Lexend Giga", sans-serif;
  font-weight: 600;
}
</style>
