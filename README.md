<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Debayan Roy | Portfolio</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@3.4.1/dist/tailwind.min.css" rel="stylesheet">
  <script>    document.addEventListener('DOMContentLoaded', () => {
      const instruments = document.querySelectorAll('.instrument');
      instruments.forEach(i => {
        i.addEventListener('mouseenter', () => {
          i.classList.add('scale-110', 'shadow-xl');
        });
        i.addEventListener('mouseleave', () => {
          i.classList.remove('scale-110', 'shadow-xl');
        });
      });
    });
  </script>
</head>
<body class="bg-gradient-to-tr from-blue-100 via-purple-50 to-pink-100 min-h-screen font-sans">

  <div class="max-w-2xl mx-auto my-12 bg-white rounded-3xl shadow-lg p-8 border border-purple-200 animate-fadeIn">
    <header class="flex flex-col items-center mb-6">
      <img src="https://avatars.githubusercontent.com/u/676?v=4" alt="Debayan Roy" class="w-28 h-28 rounded-full border-4 border-purple-300 shadow-lg mb-3">
      <h1 class="text-4xl font-bold text-purple-700 mb-1">Debayan Roy</h1>
      <p class="text-lg text-gray-600 italic">Computer Science & Engineering Student</p>
      <p class="text-sm text-gray-500">Government College of Engineering and Textile Technology, Serampore, West Bengal, India</p>
    </header>
    
    <main>
      <section class="mb-7">
        <h2 class="text-2xl font-semibold text-blue-600 mb-2">About Me</h2>
        <p class="text-gray-700 leading-relaxed">
          Hi! I'm Debayan, a passionate Computer Science and Engineering student with a knack for problem-solving and creativity. I secured <span class="font-bold text-purple-600">8th position</span> with my team at <span class="font-bold text-blue-600">Smart Bengal Hackathon 2023</span> – a state-level event! My journey in tech is just beginning, and I'm excited to build innovative projects using <span class="font-bold text-yellow-800">Java</span> and <span class="font-bold text-green-700">Python</span>. Beyond code, music is my soul—I play multiple instruments and love exploring new melodies.
        </p>
      </section>

      <section class="mb-7">
        <h2 class="text-2xl font-semibold text-purple-600 mb-2">Skills</h2>
        <div class="flex flex-wrap gap-3">
          <span class="bg-yellow-100 text-yellow-800 px-3 py-1 rounded-full font-semibold shadow instrument transition-transform">Java</span>
          <span class="bg-green-100 text-green-700 px-3 py-1 rounded-full font-semibold shadow instrument transition-transform">Python</span>
          <span class="bg-blue-100 text-blue-700 px-3 py-1 rounded-full font-semibold shadow instrument transition-transform">Problem Solving</span>
          <span class="bg-pink-100 text-pink-700 px-3 py-1 rounded-full font-semibold shadow instrument transition-transform">Teamwork</span>
          <span class="bg-purple-100 text-purple-700 px-3 py-1 rounded-full font-semibold shadow instrument transition-transform">Music</span>
        </div>
      </section>

      <section class="mb-7">
        <h2 class="text-2xl font-semibold text-pink-700 mb-2">Achievements</h2>
        <ul class="list-disc pl-5 text-gray-700 space-y-1">
          <li>Secured <span class="font-bold text-purple-600">8th Position</span> at <span class="font-bold">Smart Bengal Hackathon 2023</span></li>
          <li>Learning and Growing in Java & Python Programming language</li>
        </ul>
      </section>

      <section class="mb-7">
        <h2 class="text-2xl font-semibold text-blue-700 mb-2">Music Passion</h2>
        <p class="text-gray-700 leading-relaxed">
          When I'm not coding, you'll find me lost in music. I play:
        </p>
        <div class="flex flex-wrap gap-3 mt-3">
          <span class="bg-pink-200 text-pink-800 px-3 py-1 rounded-full font-semibold shadow instrument cursor-pointer transition-transform">Sitar</span>
          <span class="bg-green-200 text-green-800 px-3 py-1 rounded-full font-semibold shadow instrument cursor-pointer transition-transform">Guitar</span>
          <span class="bg-blue-200 text-blue-800 px-3 py-1 rounded-full font-semibold shadow instrument cursor-pointer transition-transform">Flute</span>
          <span class="bg-purple-200 text-purple-800 px-3 py-1 rounded-full font-semibold shadow instrument cursor-pointer transition-transform">Violin</span>
        </div>
      </section>

      <section class="mb-7">
        <h2 class="text-2xl font-semibold text-gray-700 mb-2">Let's Connect!</h2>
        <div class="flex gap-4">
          <a href="https://github.com/debayanroy676" target="_blank" class="hover:scale-110 transition-transform text-pink-600 font-bold underline">GitHub</a>
          <a href="https://instagram.com/debayan_roy__" target="_blank" class="hover:scale-110 transition-transform text-green-600 font-bold underline">Instagram</a>
          <a href="https://www.linkedin.com/in/debayan-roy-3814a4300?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" target="_blank" class="hover:scale-110 transition-transform text-blue-600 font-bold underline">LinkedIn</a>
        </div>
      </section>
    </main>
  </div>

  <style>
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px);}
      to { opacity: 1; transform: translateY(0);}
    }
    .animate-fadeIn {
      animation: fadeIn 1s ease-out;
    }
  </style>
</body>
</html>
