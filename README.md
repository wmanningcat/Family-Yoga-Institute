<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Family Yoga Institute – Growing Together</title>
  <meta name="description" content="Family Yoga Institute (FYI): Community-centered yoga for moms, moms-to-be, and little ones." />
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    :root{
      --fyi-green:#3BAA7A;
      --fyi-teal:#00A3A3;
      --fyi-purple:#7C4DFF;
    }
    .btn{ @apply px-5 py-3 rounded-2xl font-medium transition; }
    .btn-primary{ background:var(--fyi-green); color:white; }
    .btn-outline{ @apply border; border-color:var(--fyi-teal); color:var(--fyi-teal); }
    .btn-outline:hover{ background:var(--fyi-teal); color:white; }
  </style>
</head>
<body class="min-h-screen bg-gradient-to-b from-teal-50 via-white to-purple-50 text-slate-800">

  <!-- HEADER -->
  <header class="sticky top-0 z-50 bg-white/85 backdrop-blur border-b border-teal-100">
    <div class="mx-auto max-w-6xl px-4 py-3 flex items-center justify-between">
      <div class="flex items-center gap-3">
        <img src="logo.png" alt="Family Yoga Institute Logo" class="h-12 w-auto rounded-2xl shadow-sm ring-1 ring-teal-200/50">
        <div class="leading-tight">
          <div class="font-semibold tracking-wide text-slate-900">Family Yoga Institute</div>
          <div class="text-xs text-slate-500 -mt-0.5">growing together</div>
        </div>
      </div>
      <nav class="hidden md:flex items-center gap-6 text-sm">
        <a href="#classes" class="hover:text-[color:var(--fyi-teal)]">Classes</a>
        <a href="#schedule" class="hover:text-[color:var(--fyi-teal)]">Schedule</a>
        <a href="#about" class="hover:text-[color:var(--fyi-teal)]">About</a>
        <a href="#faq" class="hover:text-[color:var(--fyi-teal)]">FAQ</a>
        <a href="#signup" class="px-4 py-2 rounded-xl border" style="border-color:var(--fyi-teal); color:var(--fyi-teal);">Sign up</a>
      </nav>
    </div>
  </header>

  <!-- HERO -->
  <section class="relative overflow-hidden">
    <div class="mx-auto max-w-6xl px-6 py-16 md:py-24 grid md:grid-cols-2 gap-10 items-center">
      <div>
        <h1 class="text-4xl md:text-5xl font-bold tracking-tight text-slate-900">Family Yoga Institute</h1>
        <p class="mt-4 text-lg text-slate-600">Community-centered yoga for moms, moms-to-be, and little ones — with a focus on mindfulness, connection, and accessible movement.</p>
        <p class="mt-3 text-sm text-slate-500">Pending final approval at the September association meeting, our neighborhood will promote classes and provide space. We’re excited to begin soon!</p>
        <div class="mt-6 flex flex-wrap gap-3">
          <a href="#classes" class="btn btn-primary">Explore classes</a>
          <a href="#signup" class="btn btn-outline">Join the list</a>
        </div>
      </div>
      <div class="relative">
        <img src="logo.png" alt="Family Yoga Institute Logo" class="max-h-full max-w-full rounded-2xl">
        <p class="mt-3 text-center text-sm text-slate-500 italic">Growing together</p>
      </div>
    </div>
  </section>

  <!-- CLASSES -->
  <section id="classes" class="py-16 bg-white">
    <div class="max-w-6xl mx-auto px-6">
      <h2 class="text-3xl font-bold text-slate-900 mb-8">Our Classes</h2>
      <div class="grid md:grid-cols-2 gap-10">
        <div>
          <h3 class="text-xl font-semibold text-fyi-green">Mindful Mommy and Me</h3>
          <p class="mt-2 text-slate-600">A bonding yoga experience for mothers and their little ones. Gentle postures, breathing exercises, and mindfulness techniques to foster connection and relaxation.</p>
        </div>
        <div>
          <h3 class="text-xl font-semibold text-fyi-purple">Mindful Mommies To Be</h3>
          <p class="mt-2 text-slate-600">A prenatal yoga class designed to support expectant mothers physically and emotionally. Gentle movement, breathwork, and meditation to prepare for birth and motherhood.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- SCHEDULE -->
  <section id="schedule" class="py-16 bg-gradient-to-r from-teal-50 to-purple-50">
    <div class="max-w-6xl mx-auto px-6">
      <h2 class="text-3xl font-bold text-slate-900 mb-8">Schedule</h2>
      <p class="text-slate-600">Class schedule coming soon. Please check back after the September association meeting!</p>
    </div>
  </section>

  <!-- ABOUT -->
  <section id="about" class="py-16 bg-white">
    <div class="max-w-6xl mx-auto px-6">
      <h2 class="text-3xl font-bold text-slate-900 mb-8">About Us</h2>
      <p class="text-slate-600">The Family Yoga Institute is dedicated to creating a welcoming space for mothers and families to connect, move, and grow together through yoga and mindfulness practices.</p>
    </div>
  </section>

  <!-- FAQ -->
  <section id="faq" class="py-16 bg-gradient-to-r from-teal-50 to-purple-50">
    <div class="max-w-6xl mx-auto px-6">
      <h2 class="text-3xl font-bold text-slate-900 mb-8">Frequently Asked Questions</h2>
      <ul class="space-y-6 text-slate-600">
        <li><strong>What should I bring?</strong> Comfortable clothing, a yoga mat, and water.</li>
        <li><strong>Do I need prior yoga experience?</strong> Not at all! Our classes are beginner-friendly.</li>
        <li><strong>Can partners join?</strong> Yes, partners are welcome in certain classes.</li>
      </ul>
    </div>
  </section>

  <!-- SIGNUP -->
  <section id="signup" class="py-16 bg-white">
    <div class="max-w-6xl mx-auto px-6">
      <h2 class="text-3xl font-bold text-slate-900 mb-8">Sign Up</h2>
      <p class="mb-4 text-slate-600">Use the link below to register for classes via our Google Form:</p>
      <a href="#" class="btn btn-primary">Go to Google Form</a>
    </div>
  </section>

  <!-- CONTACT -->
  <footer class="py-10 bg-slate-900 text-slate-200">
    <div class="max-w-6xl mx-auto px-6">
      <p>&copy; 2025 Family Yoga Institute. All rights reserved.</p>
      <p class="mt-2">Contact: <a href="mailto:info@familyyogainstitute.com" class="underline">info@familyyogainstitute.com</a></p>
    </div>
  </footer>

</body>
</html>

