<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Maroc Move Express — Fast & Affordable Transport in Casablanca</title>
  <meta name="description" content="Pickup & triporteur transport in Morocco for furniture, building materials, and small deliveries. Fast, reliable, and affordable." />

  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            brandBlue: '#2563eb',
            brandBlueDark: '#1e40af',
            brandGreen: '#10b981',
            brandGreenDark: '#059669',
            brandGray: '#1f2937',
          },
          fontFamily: {
            sans: ['Inter', 'ui-sans-serif', 'system-ui', 'Segoe UI', 'Helvetica Neue', 'Arial', 'Noto Sans', 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol']
          },
          boxShadow: {
            soft: '0 8px 30px rgba(2, 17, 37, 0.08)'
          }
        }
      }
    }
  </script>
  <style>
    html { scroll-behavior: smooth; }
    .hero-bg {
      background: radial-gradient(1200px 600px at 80% -10%, rgba(37,99,235,0.12), transparent 60%),
                  radial-gradient(1000px 500px at -10% 20%, rgba(16,185,129,0.14), transparent 50%);
    }
    .focus-ring:focus-visible {
      outline: none;
      box-shadow: 0 0 0 4px rgba(37,99,235,0.25);
    }
    /* Optional tweak for RTL spacing */
    body.rtl [class*="ml-"], body.rtl [class^="ml-"] { margin-left: 0 !important; }
    body.rtl [class*="mr-"], body.rtl [class^="mr-"] { margin-right: 0 !important; }
  </style>
</head>
<body class="font-sans antialiased text-brandGray bg-white">
  <!-- Top Bar -->
  <header class="sticky top-0 z-40 bg-white/85 backdrop-blur border-b border-slate-200">
    <div class="max-w-7xl mx-auto px-6 py-3 flex items-center justify-between">
      <a href="#home" class="flex items-center gap-3 group">
        <span class="inline-flex h-9 w-9 rounded-xl bg-brandBlue text-white items-center justify-center shadow-soft">
          <span class="font-bold text-lg">MM</span>
        </span>
        <div class="leading-tight">
          <div class="font-extrabold text-lg tracking-tight group-hover:text-brandBlue transition-colors" id="navBrand">Maroc Move Express</div>
          <div class="text-sm text-slate-500" id="navTag">Pickup & Triporteur</div>
        </div>
      </a>

      <nav class="hidden md:flex items-center gap-6 text-sm">
        <a href="#services" class="text-slate-600 hover:text-brandBlue transition-colors" id="navServices">Services</a>
        <a href="#about" class="text-slate-600 hover:text-brandBlue transition-colors" id="navAbout">About</a>
        <a href="#contact" class="text-slate-600 hover:text-brandBlue transition-colors" id="navPricing">Pricing & Contact</a>
      </nav>

      <div class="flex items-center gap-3">
        <!-- Language menu -->
        <div class="relative">
          <button id="langBtn" class="inline-flex items-center gap-2 px-4 py-2 rounded-lg border border-slate-300 hover:border-brandBlue text-slate-700 hover:text-brandBlue transition-colors focus-ring" aria-haspopup="true" aria-expanded="false">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 opacity-80" viewBox="0 0 24 24" fill="currentColor"><path d="M12 2a10 10 0 100 20 10 10 0 000-20zm6.93 6h-3.26a14.6 14.6 0 00-1.24-3.38A8.03 8.03 0 0118.93 8zM12 4c.7 0 1.97 1.6 2.7 4H9.3C10.03 5.6 11.3 4 12 4zM7.57 4.62A14.6 14.6 0 006.33 8H3.07a8.03 8.03 0 014.5-3.38zM4 12c0-.69.07-1.36.2-2h3.3a21.9 21.9 0 000 4H4.2A8.14 8.14 0 014 12zm.07 4h3.26c.3 1.2.73 2.35 1.24 3.38A8.03 8.03 0 014.07 16zM12 20c-.7 0-1.97-1.6-2.7-4h5.4c-.73 2.4-2 4-2.7 4zm4.43-.62c.51-1.03.94-2.18 1.24-3.38h3.26a8.03 8.03 0 01-4.5 3.38zM19.8 14h-3.3a21.9 21.9 0 000-4h3.3c.17.64.2 1.31.2 2s-.07 1.36-.2 2z"/></svg>
            <span id="langCurrent">English</span>
          </button>
          <div id="langMenu" class="absolute right-0 mt-2 w-44 rounded-lg border border-slate-200 bg-white shadow-soft py-1 hidden">
            <button data-lang="en" class="w-full text-left px-4 py-2 hover:bg-slate-50">English</button>
            <button data-lang="ar" class="w-full text-left px-4 py-2 hover:bg-slate-50">العربية</button>
            <button data-lang="es" class="w-full text-left px-4 py-2 hover:bg-slate-50">Español</button>
            <button data-lang="fr" class="w-full text-left px-4 py-2 hover:bg-slate-50">Français</button>
          </div>
        </div>

        <a href="tel:+212612345678" class="hidden sm:inline-flex items-center gap-2 px-4 py-2 rounded-lg border border-slate-300 hover:border-brandBlue text-slate-700 hover:text-brandBlue transition-colors focus-ring" aria-label="Call us now" id="navCall">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 opacity-80" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
            <path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h1.28a2 2 0 011.94 1.515l.57 2.281a2 2 0 01-.45 1.901l-1.21 1.21a16 16 0 006.364 6.364l1.21-1.21a2 2 0 011.9-.45l2.282.57A2 2 0 0121 18.72V20a2 2 0 01-2 2h-1C9.82 22 2 14.18 2 5V4a1 1 0 011-1z" />
          </svg>
          Call
        </a>
        <a id="navQuote" href="#contact" class="inline-flex items-center gap-2 px-4 py-2 rounded-lg bg-brandBlue hover:bg-brandBlueDark text-white shadow-soft transition-colors focus-ring">
          Request a Quote
        </a>
      </div>
    </div>
  </header>

  <!-- Hero -->
  <section id="home" class="hero-bg">
    <div class="max-w-7xl mx-auto px-6 pt-16 md:pt-24 pb-16 md:pb-24 grid md:grid-cols-2 gap-10 items-center">
      <div>
        <span class="inline-flex items-center gap-2 bg-emerald-50 text-brandGreen px-3 py-1 rounded-full text-sm font-medium" id="heroBadge">
          Fast response • 7 days/week
        </span>
        <h1 class="mt-4 text-4xl md:text-5xl font-extrabold tracking-tight text-brandGray" id="heroTitle">
          Fast & Affordable Transport in Casablanca
        </h1>
        <p class="mt-4 text-lg text-slate-600" id="heroSubtitle">
          Reliable pickup and triporteur service for furniture, building materials, and small deliveries — quick arrivals, careful handling, and fair pricing.
        </p>

        <div class="mt-6 flex flex-wrap gap-3">
          <a href="#contact" class="inline-flex items-center gap-2 px-5 py-3 rounded-xl bg-brandBlue hover:bg-brandBlueDark text-white font-semibold shadow-soft transition-colors focus-ring" id="heroCTAQuote">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 opacity-95" viewBox="0 0 24 24" fill="currentColor">
              <path d="M13 2L3 14h7l-1 8 10-12h-7l1-8z"/>
            </svg>
            <span id="heroCTAQuoteText">Request a Quote</span>
          </a>
          <a id="heroWhatsAppBtn" href="https://wa.me/212612345678?text=Hello%20Maroc%20Move%20Express%2C%20I%27d%20like%20a%20transport%20quote." target="_blank" rel="noopener" class="inline-flex items-center gap-2 px-5 py-3 rounded-xl bg-brandGreen hover:bg-brandGreenDark text-white font-semibold shadow-soft transition-colors focus-ring">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 opacity-95" viewBox="0 0 32 32" fill="currentColor">
              <path d="M19.11 17.16c-.27-.14-1.57-.77-1.81-.86-.24-.09-.42-.14-.6.14s-.69.86-.85 1.04-.31.2-.58.07a9.76 9.76 0 0 1-2.87-1.77 10.74 10.74 0 0 1-1.99-2.47c-.21-.36 0-.55.16-.75.16-.2.36-.49.54-.73.18-.24.24-.4.36-.66s.06-.49-.03-.69c-.09-.2-.6-1.45-.82-1.98-.22-.53-.44-.45-.6-.46-.16-.01-.34-.01-.52-.01s-.49.07-.75.35c-.26.28-1 1-1 2.43s1.03 2.82 1.18 3.02c.15.2 2.04 3.11 4.94 4.36.69.3 1.22.48 1.64.62.69.22 1.32.19 1.82.11.56-.08 1.57-.64 1.79-1.27.22-.63.22-1.16.16-1.27-.06-.11-.25-.18-.52-.32z"/>
              <path d="M27.61 4.39A13.5 13.5 0 1 0 5.08 25.92L3 29l3.3-1.95a13.5 13.5 0 0 0 21.31-10.7 13.43 13.43 0 0 0-3.99-9.96zm-10.1 22.72a10.98 10.98 0 1 1 0-21.96 10.98 10.98 0 0 1 0 21.96z"/>
            </svg>
            <span id="heroWhatsAppText">WhatsApp</span>
          </a>
        </div>

        <div class="mt-6 text-slate-500 text-sm" id="heroNote">
          Pickup trucks and triporteurs available • City & surrounding areas • Same‑day service
        </div>
      </div>

      <!-- Feature Panel -->
      <div class="relative">
        <div class="rounded-2xl border border-slate-200 bg-white shadow-soft p-6 md:p-8">
          <div class="grid grid-cols-3 gap-4">
            <div class="col-span-3 flex flex-wrap gap-2">
              <span class="inline-flex items-center gap-2 px-3 py-2 rounded-xl bg-blue-50 text-brandBlue text-sm font-semibold" id="pillPickup">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" viewBox="0 0 24 24" fill="currentColor">
                  <path d="M3 7a2 2 0 012-2h8v8H3V7zm10 0h3l3 3v3h-6V7zM5 19a2 2 0 100-4 2 2 0 000 4zm12 0a2 2 0 100-4 2 2 0 000 4z"/>
                </svg>
                Pickup
              </span>
              <span class="inline-flex items-center gap-2 px-3 py-2 rounded-xl bg-emerald-50 text-brandGreen text-sm font-semibold" id="pillTriporteur">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" viewBox="0 0 24 24" fill="currentColor">
                  <path d="M4 16a3 3 0 116 0H8.5l1-2h3.382a3 3 0 015.236 0H20v2h-1.382a3 3 0 11-5.236 0H9.5l-1 2H10a3 3 0 11-6 0zM18 14a1 1 0 100 2 1 1 0 000-2zM6 14a1 1 0 100 2 1 1 0 000-2z"/>
                </svg>
                Triporteur
              </span>
              <span class="inline-flex items-center gap-2 px-3 py-2 rounded-xl bg-slate-50 text-slate-700 text-sm font-semibold" id="pillSameDay">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" viewBox="0 0 24 24" fill="currentColor">
                  <path d="M12 1.75a10.25 10.25 0 1 0 0 20.5 10.25 10.25 0 0 0 0-20.5zM12.75 6a.75.75 0 0 0-1.5 0v6c0 .2.08.39.22.53l3.5 3.5a.75.75 0 1 0 1.06-1.06l-3.28-3.28V6z"/>
                </svg>
                Same‑day
              </span>
            </div>

            <div class="col-span-3 grid sm:grid-cols-3 gap-4 mt-2">
              <div class="rounded-xl bg-slate-50 p-4">
                <div class="text-sm text-slate-500" id="hiStartLabel">Starting at</div>
                <div class="text-xl font-extrabold" id="hiStartValue">120 MAD</div>
              </div>
              <div class="rounded-xl bg-slate-50 p-4">
                <div class="text-sm text-slate-500" id="hiCoverageLabel">Coverage</div>
                <div class="text-xl font-extrabold" id="hiCoverageValue">City + Nearby</div>
              </div>
              <div class="rounded-xl bg-slate-50 p-4">
                <div class="text-sm text-slate-500" id="hiSupportLabel">Support</div>
                <div class="text-xl font-extrabold" id="hiSupportValue">7/7</div>
              </div>
            </div>

            <div class="col-span-3 mt-4 text-sm text-slate-500" id="hiPanelNote">
              Transparent rates depending on distance, floor, and load. Get your free quote in minutes.
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Services -->
  <section id="services" class="py-16 md:py-20 bg-white">
    <div class="max-w-7xl mx-auto px-6">
      <div class="text-center max-w-2xl mx-auto">
        <h2 class="text-3xl md:text-4xl font-extrabold tracking-tight" id="servicesHeading">Our Services</h2>
        <p class="mt-3 text-slate-600" id="servicesSub">Flexible transport options for homes, businesses, and quick errands.</p>
      </div>

      <div class="mt-10 grid gap-6 md:grid-cols-3">
        <!-- Furniture Moving -->
        <div class="group rounded-2xl border border-slate-200 bg-white p-6 shadow-soft hover:-translate-y-1 hover:shadow-lg transition-all">
          <div class="flex items-center justify-between">
            <span class="inline-flex h-12 w-12 items-center justify-center rounded-xl bg-blue-50 text-brandBlue">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" viewBox="0 0 24 24" fill="currentColor">
                <path d="M6 10a2 2 0 10-4 0v5h2v2h2v-2h12v2h2v-2h2v-5a2 2 0 10-4 0H6z"/>
              </svg>
            </span>
            <span class="text-xs font-semibold px-2 py-1 rounded-full bg-emerald-50 text-brandGreen" id="svc1Badge">Pickup • Triporteur</span>
          </div>
          <h3 class="mt-5 text-xl font-bold" id="svc1Title">Furniture Moving</h3>
          <p class="mt-2 text-slate-600" id="svc1Desc">Beds, sofas, tables, wardrobes — careful loading, protection, and safe delivery to your door.</p>
        </div>

        <!-- Small Deliveries -->
        <div class="group rounded-2xl border border-slate-200 bg-white p-6 shadow-soft hover:-translate-y-1 hover:shadow-lg transition-all">
          <div class="flex items-center justify-between">
            <span class="inline-flex h-12 w-12 items-center justify-center rounded-xl bg-emerald-50 text-brandGreen">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" viewBox="0 0 24 24" fill="currentColor">
                <path d="M21 8l-9-5-9 5 9 5 9-5zm-9 7l-9-5v7l9 5 9-5v-7l-9 5z"/>
              </svg>
            </span>
            <span class="text-xs font-semibold px-2 py-1 rounded-full bg-blue-50 text-brandBlue" id="svc2Badge">Same‑day</span>
          </div>
          <h3 class="mt-5 text-xl font-bold" id="svc2Title">Small Deliveries</h3>
          <p class="mt-2 text-slate-600" id="svc2Desc">Documents, parcels, shop purchases, and quick errands around town — fast and secure.</p>
        </div>

        <!-- Building Materials Transport -->
        <div class="group rounded-2xl border border-slate-200 bg-white p-6 shadow-soft hover:-translate-y-1 hover:shadow-lg transition-all">
          <div class="flex items-center justify-between">
            <span class="inline-flex h-12 w-12 items-center justify-center rounded-xl bg-slate-100 text-brandGray">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" viewBox="0 0 24 24" fill="currentColor">
                <path d="M2 11h8v4H2v-4zm10 0h10v4H12v-4zM5 6h6v4H5V6zm8 0h6v4h-6V6zM3 16h6v4H3v-4zm8 0h10v4H11v-4z"/>
              </svg>
            </span>
            <span class="text-xs font-semibold px-2 py-1 rounded-full bg-slate-100 text-slate-700" id="svc3Badge">Heavy loads</span>
          </div>
          <h3 class="mt-5 text-xl font-bold" id="svc3Title">Building Materials Transport</h3>
          <p class="mt-2 text-slate-600" id="svc3Desc">Cement, bricks, tiles, paint, wood — efficient loading and delivery directly to your site.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- About -->
  <section id="about" class="py-16 md:py-20 bg-slate-50">
    <div class="max-w-7xl mx-auto px-6 grid md:grid-cols-2 gap-10 items-center">
      <div>
        <h2 class="text-3xl md:text-4xl font-extrabold tracking-tight" id="aboutHeading">Why Choose Us</h2>
        <p class="mt-4 text-slate-700 leading-relaxed" id="aboutParagraph">
          At Maroc Move Express, we combine reliability, speed, and affordability to make transport effortless.
          Our friendly team responds quickly, plans the best route, and treats your items with care. Whether it’s one sofa or a full load of materials, we deliver on time and at a price that makes sense.
        </p>
        <ul class="mt-6 space-y-3 text-slate-700">
          <li class="flex items-start gap-3" id="aboutBullet1">
            <span class="inline-flex h-6 w-6 items-center justify-center rounded-full bg-emerald-100 text-brandGreen">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" viewBox="0 0 24 24" fill="currentColor"><path d="M9 16.2l-3.5-3.5L4 14.2l5 5 12-12-1.5-1.5z"/></svg>
            </span>
            <span>Reliable arrivals and careful handling</span>
          </li>
          <li class="flex items-start gap-3" id="aboutBullet2">
            <span class="inline-flex h-6 w-6 items-center justify-center rounded-full bg-emerald-100 text-brandGreen">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" viewBox="0 0 24 24" fill="currentColor"><path d="M9 16.2l-3.5-3.5L4 14.2l5 5 12-12-1.5-1.5z"/></svg>
            </span>
            <span>Transparent pricing with no surprises</span>
          </li>
          <li class="flex items-start gap-3" id="aboutBullet3">
            <span class="inline-flex h-6 w-6 items-center justify-center rounded-full bg-emerald-100 text-brandGreen">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" viewBox="0 0 24 24" fill="currentColor"><path d="M9 16.2l-3.5-3.5L4 14.2l5 5 12-12-1.5-1.5z"/></svg>
            </span>
            <span>Citywide coverage and 7‑day availability</span>
          </li>
        </ul>
      </div>

      <div class="rounded-2xl border border-slate-200 bg-white p-6 md:p-8 shadow-soft">
        <div class="grid sm:grid-cols-3 gap-4">
          <div class="rounded-xl bg-blue-50 p-5 text-center">
            <div class="text-3xl font-extrabold text-brandBlue">500+</div>
            <div class="text-sm text-slate-600" id="aboutJobsLabel">Jobs completed</div>
          </div>
          <div class="rounded-xl bg-emerald-50 p-5 text-center">
            <div class="text-3xl font-extrabold text-brandGreen">4.9★</div>
            <div class="text-sm text-slate-600" id="aboutHappyLabel">Happy clients</div>
          </div>
          <div class="rounded-xl bg-slate-100 p-5 text-center">
            <div class="text-3xl font-extrabold text-brandGray">7/7</div>
            <div class="text-sm text-slate-600" id="aboutAvailLabel">Available</div>
          </div>
        </div>
        <p class="mt-5 text-sm text-slate-500" id="aboutStatsNote">
          Figures are indicative. Contact us to get an exact quote based on distance, floors, and load size.
        </p>
      </div>
    </div>
  </section>

  <!-- Pricing / Contact -->
  <section id="contact" class="py-16 md:py-20 bg-white">
    <div class="max-w-7xl mx-auto px-6">
      <div class="grid lg:grid-cols-3 gap-8">
        <!-- Contact Cards -->
        <div class="lg:col-span-1 space-y-6">
          <h2 class="text-3xl font-extrabold tracking-tight" id="contactHeading">Pricing & Contact</h2>
          <p class="text-slate-600" id="contactParagraph">Tell us what you need moved, from where to where, and we’ll send a quick quote.</p>

          <div class="rounded-2xl border border-slate-200 bg-white p-6 shadow-soft">
            <div class="flex items-start gap-4">
              <span class="inline-flex h-10 w-10 items-center justify-center rounded-xl bg-blue-50 text-brandBlue">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 24 24" fill="currentColor"><path d="M6.62 10.79a15.05 15.05 0 0 0 6.59 6.59l2.2-2.2a1 1 0 0 1 1.01-.24c1.11.37 2.31.57 3.58.57a1 1 0 0 1 1 1V20a1 1 0 0 1-1 1C10.07 21 3 13.93 3 5a1 1 0 0 1 1-1h2.49a1 1 0 0 1 1 1c0 1.27.2 2.47.57 3.58a1 1 0 0 1-.24 1.01l-2.2 2.2z"/></svg>
              </span>
              <div>
                <div class="text-sm text-slate-500" id="contactPhoneLabel">Phone</div>
                <a href="tel:+212612345678" class="text-lg font-bold text-brandGray hover:text-brandBlue transition-colors">+212 6 12 34 56 78</a>
              </div>
            </div>

            <div class="mt-4 flex items-start gap-4">
              <span class="inline-flex h-10 w-10 items-center justify-center rounded-xl bg-emerald-50 text-brandGreen">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 32 32" fill="currentColor"><path d="M27.61 4.39A13.5 13.5 0 1 0 5.08 25.92L3 29l3.3-1.95a13.5 13.5 0 0 0 21.31-10.7 13.43 13.43 0 0 0-3.99-9.96zm-10.1 22.72a10.98 10.98 0 1 1 0-21.96 10.98 10.98 0 0 1 0 21.96z"/><path d="M19.11 17.16c-.27-.14-1.57-.77-1.81-.86-.24-.09-.42-.14-.6.14s-.69.86-.85 1.04-.31.2-.58.07a9.76 9.76 0 0 1-2.87-1.77 10.74 10.74 0 0 1-1.99-2.47c-.21-.36 0-.55.16-.75.16-.2.36-.49.54-.73.18-.24.24-.4.36-.66s.06-.49-.03-.69c-.09-.2-.6-1.45-.82-1.98-.22-.53-.44-.45-.6-.46-.16-.01-.34-.01-.52-.01s-.49.07-.75.35c-.26.28-1 1-1 2.43s1.03 2.82 1.18 3.02c.15.2 2.04 3.11 4.94 4.36.69.3 1.22.48 1.64.62.69.22 1.32.19 1.82.11.56-.08 1.57-.64 1.79-1.27.22-.63.22-1.16.16-1.27-.06-.11-.25-.18-.52-.32z"/></svg>
              </span>
              <div>
                <div class="text-sm text-slate-500" id="contactWhatsAppLabel">WhatsApp</div>
                <a class="text-lg font-bold text-brandGray hover:text-brandGreen transition-colors" target="_blank" rel="noopener" id="contactWhatsAppCTA" href="https://wa.me/212612345678?text=Hello%20Maroc%20Move%20Express%2C%20I%27d%20like%20a%20transport%20quote.">Chat on WhatsApp</a>
              </div>
            </div>

            <div class="mt-6 rounded-xl bg-slate-50 p-4 text-sm text-slate-600" id="contactPricingNote">
              Typical range: <span class="font-semibold">120–450 MAD</span> within city. Long‑distance priced per km. Extra for floors without elevator.
            </div>
          </div>
        </div>

        <!-- Form -->
        <div class="lg:col-span-2">
          <form id="quoteForm" class="rounded-2xl border border-slate-200 bg-white p-6 md:p-8 shadow-soft space-y-5" novalidate>
            <div class="flex items-start justify-between gap-4">
              <div>
                <h3 class="text-2xl font-extrabold tracking-tight" id="formTitle">Request a Free Quote</h3>
                <p class="text-slate-600 text-sm mt-1" id="formSubtitle">We’ll reply quickly by WhatsApp or phone.</p>
              </div>
              <span class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-slate-100 text-slate-700 text-xs font-semibold" id="formDemoBadge">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" viewBox="0 0 24 24" fill="currentColor"><path d="M12 2l7 4v6c0 5-3.5 9.5-7 10-3.5-.5-7-5-7-10V6l7-4z"/></svg>
                Demo: opens WhatsApp to send
              </span>
            </div>

            <div class="grid md:grid-cols-2 gap-5">
              <div>
                <label for="name" class="block text-sm font-semibold text-slate-700" id="labelName">Name</label>
                <input id="name" name="name" type="text" required placeholder="Your name" class="mt-2 w-full rounded-xl border border-slate-300 bg-white px-4 py-3 placeholder-slate-400 focus-ring">
                <p class="mt-1 text-xs text-red-600 hidden" id="nameError">Please enter your name.</p>
              </div>

              <div>
                <label for="phone" class="block text-sm font-semibold text-slate-700" id="labelPhone">Phone</label>
                <input id="phone" name="phone" type="tel" required placeholder="+212 6 XX XX XX XX" class="mt-2 w-full rounded-xl border border-slate-300 bg-white px-4 py-3 placeholder-slate-400 focus-ring">
                <p class="mt-1 text-xs text-red-600 hidden" id="phoneError">Please enter a valid phone number.</p>
              </div>
            </div>

            <div class="grid md:grid-cols-2 gap-5">
              <div>
                <label for="service" class="block text-sm font-semibold text-slate-700" id="labelServiceType">Type of Service</label>
                <select id="service" name="service" required class="mt-2 w-full rounded-xl border border-slate-300 bg-white px-4 py-3 focus-ring"></select>
                <p class="mt-1 text-xs text-red-600 hidden" id="serviceError">Please choose a service.</p>
              </div>

              <div>
                <label for="vehicle" class="block text-sm font-semibold text-slate-700" id="labelVehicle">Vehicle</label>
                <select id="vehicle" name="vehicle" required class="mt-2 w-full rounded-xl border border-slate-300 bg-white px-4 py-3 focus-ring"></select>
                <p class="mt-1 text-xs text-red-600 hidden" id="vehicleError">Please select a vehicle.</p>
              </div>
            </div>

            <div>
              <label for="message" class="block text-sm font-semibold text-slate-700" id="labelMessage">Message</label>
              <textarea id="message" name="message" rows="4" placeholder="From: Address A • To: Address B • Floors • Date/Time • Extra info" class="mt-2 w-full rounded-xl border border-slate-300 bg-white px-4 py-3 placeholder-slate-400 focus-ring"></textarea>
            </div>

            <div class="flex flex-wrap items-center gap-3">
              <button type="submit" class="inline-flex items-center gap-2 px-5 py-3 rounded-xl bg-brandBlue hover:bg-brandBlueDark text-white font-semibold shadow-soft transition-colors focus-ring" id="submitButton">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 opacity-95" viewBox="0 0 24 24" fill="currentColor"><path d="M2 21l21-9L2 3v7l15 2-15 2v7z"/></svg>
                <span id="submitButtonLabel">Send via WhatsApp</span>
              </button>
              <a href="tel:+212612345678" class="inline-flex items-center gap-2 px-5 py-3 rounded-xl border border-slate-300 hover:border-brandBlue text-slate-700 hover:text-brandBlue font-semibold transition-colors focus-ring" id="callInsteadBtn">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 opacity-90" viewBox="0 0 24 24" fill="currentColor"><path d="M6.62 10.79a15.05 15.05 0 0 0 6.59 6.59l2.2-2.2a1 1 0 0 1 1.01-.24c1.11.37 2.31.57 3.58.57a1 1 0 0 1 1 1V20a1 1 0 0 1-1 1C10.07 21 3 13.93 3 5a1 1 0 0 1 1-1h2.49a1 1 0 0 1 1 1c0 1.27.2 2.47.57 3.58a1 1 0 0 1-.24 1.01l-2.2 2.2z"/></svg>
                <span id="callInsteadLabel">Call Instead</span>
              </a>
              <div id="formNotice" class="text-sm text-slate-500">No payment or signup needed.</div>
            </div>

            <div id="formSuccess" class="hidden mt-3 rounded-xl bg-emerald-50 text-brandGreen px-4 py-3 text-sm font-medium">
              Thanks! A WhatsApp window has opened with your quote details. If it didn’t, please check your popup blocker or use the WhatsApp button above.
            </div>
          </form>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="border-t border-slate-200 bg-white">
    <div class="max-w-7xl mx-auto px-6 py-10 grid md:grid-cols-3 gap-8">
      <div>
        <div class="flex items-center gap-3">
          <span class="inline-flex h-9 w-9 rounded-xl bg-brandBlue text-white items-center justify-center shadow-soft">
            <span class="font-bold text-lg">MM</span>
          </span>
          <span class="font-extrabold text-lg" id="footerBrandName">Maroc Move Express</span>
        </div>
        <p class="mt-3 text-slate-600 text-sm" id="footerDescription">
          Fast, reliable pickup and triporteur transport in Casablanca and nearby areas.
        </p>
      </div>

      <div>
        <h4 class="font-bold text-slate-800" id="footerContactHeading">Contact</h4>
        <ul class="mt-3 space-y-2 text-sm">
          <li><a class="hover:text-brandBlue transition-colors" href="tel:+212612345678">+212 6 12 34 56 78</a></li>
          <li><a class="hover:text-brandGreen transition-colors" target="_blank" rel="noopener" id="footerWhatsAppChat" href="https://wa.me/212612345678">WhatsApp Chat</a></li>
          <li><span class="text-slate-600" id="footerLocation">Casablanca, Morocco</span></li>
        </ul>
      </div>

      <div>
        <h4 class="font-bold text-slate-800" id="footerFollowHeading">Follow</h4>
        <div class="mt-3 flex items-center gap-3">
          <a href="#" aria-label="Facebook" class="inline-flex h-9 w-9 items-center justify-center rounded-full bg-slate-100 text-slate-600 hover:text-brandBlue transition-colors">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 24 24" fill="currentColor"><path d="M22 12a10 10 0 10-11.6 9.87v-6.98H7.9v-2.9h2.5V9.8c0-2.47 1.47-3.84 3.72-3.84 1.08 0 2.2.19 2.2.19v2.42h-1.24c-1.22 0-1.6.76-1.6 1.54v1.85h2.72l-.43 2.9h-2.29v6.98A10 10 0 0022 12z"/></svg>
          </a>
          <a href="#" aria-label="Instagram" class="inline-flex h-9 w-9 items-center justify-center rounded-full bg-slate-100 text-slate-600 hover:text-brandBlue transition-colors">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 24 24" fill="currentColor"><path d="M7 2h10a5 5 0 015 5v10a5 5 0 01-5 5H7a5 5 0 01-5-5V7a5 5 0 015-5zm0 2a3 3 0 00-3 3v10a3 3 0 003 3h10a3 3 0 003-3V7a3 3 0 00-3-3H7zm5 3.5a5.5 5.5 0 110 11 5.5 5.5 0 010-11zm0 2a3.5 3.5 0 100 7 3.5 3.5 0 000-7zm5.75-.75a1.25 1.25 0 110 2.5 1.25 1.25 0 010-2.5z"/></svg>
          </a>
          <a href="#" aria-label="LinkedIn" class="inline-flex h-9 w-9 items-center justify-center rounded-full bg-slate-100 text-slate-600 hover:text-brandBlue transition-colors">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 24 24" fill="currentColor"><path d="M4.98 3.5C4.98 4.88 3.86 6 2.5 6S0 4.88 0 3.5 1.12 1 2.5 1s2.48 1.12 2.48 2.5zM0 8h5v16H0zM8 8h4.8v2.2h.07c.67-1.27 2.3-2.6 4.73-2.6 5.06 0 6 3.33 6 7.66V24h-5v-6.8c0-1.62-.03-3.7-2.25-3.7-2.25 0-2.6 1.76-2.6 3.58V24H8z"/></svg>
          </a>
        </div>
      </div>
    </div>
    <div class="border-t border-slate-200">
      <div class="max-w-7xl mx-auto px-6 py-6 text-sm text-slate-500 flex flex-wrap items-center justify-between gap-3">
        <span>© <span id="year"></span> <span id="rightsBrand">Maroc Move Express</span>. <span id="footerRightsText">All rights reserved.</span></span>
        <span id="footerBuilt">Built with care in Morocco 🇲🇦</span>
      </div>
    </div>
  </footer>

  <!-- Floating WhatsApp -->
  <a href="https://wa.me/212612345678?text=Hello%20Maroc%20Move%20Express%2C%20I%27d%20like%20a%20transport%20quote." target="_blank" rel="noopener"
     class="fixed bottom-5 right-5 inline-flex items-center justify-center h-14 w-14 rounded-full bg-brandGreen hover:bg-brandGreenDark text-white shadow-2xl focus-ring"
     aria-label="WhatsApp">
    <svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-7" viewBox="0 0 32 32" fill="currentColor"><path d="M27.61 4.39A13.5 13.5 0 1 0 5.08 25.92L3 29l3.3-1.95a13.5 13.5 0 0 0 21.31-10.7 13.43 13.43 0 0 0-3.99-9.96zm-10.1 22.72a10.98 10.98 0 1 1 0-21.96 10.98 10.98 0 0 1 0 21.96z"/><path d="M19.11 17.16c-.27-.14-1.57-.77-1.81-.86-.24-.09-.42-.14-.6.14s-.69.86-.85 1.04-.31.2-.58.07a9.76 9.76 0 0 1-2.87-1.77 10.74 10.74 0 0 1-1.99-2.47c-.21-.36 0-.55.16-.75.16-.2.36-.49.54-.73.18-.24.24-.4.36-.66s.06-.49-.03-.69c-.09-.2-.6-1.45-.82-1.98-.22-.53-.44-.45-.6-.46-.16-.01-.34-.01-.52-.01s-.49.07-.75.35c-.26.28-1 1-1 2.43s1.03 2.82 1.18 3.02c.15.2 2.04 3.11 4.94 4.36.69.3 1.22.48 1.64.62.69.22 1.32.19 1.82.11.56-.08 1.57-.64 1.79-1.27.22-.63.22-1.16.16-1.27-.06-.11-.25-.18-.52-.32z"/></svg>
  </a>

  <script>
    // Current year
    document.getElementById('year').textContent = new Date().getFullYear();

    // i18n content
    const translations = {
      en: {
        nav: { brandName: "Maroc Move Express", tagline: "Pickup & Triporteur", services: "Services", about: "About", pricingContact: "Pricing & Contact", call: "Call", requestQuote: "Request a Quote" },
        hero: {
          badge: "Fast response • 7 days/week",
          title: "Fast & Affordable Transport in Casablanca",
          subtitle: "Reliable pickup and triporteur service for furniture, building materials, and small deliveries — quick arrivals, careful handling, and fair pricing.",
          ctaQuote: "Request a Quote", ctaWhatsApp: "WhatsApp",
          note: "Pickup trucks and triporteurs available • City & surrounding areas • Same‑day service",
          badges: { pickup: "Pickup", triporteur: "Triporteur", sameDay: "Same‑day" },
          highlights: { startingAt: "Starting at", startingAtValue: "120 MAD", coverage: "Coverage", coverageValue: "City + Nearby", support: "Support", supportValue: "7/7", panelNote: "Transparent rates depending on distance, floor, and load. Get your free quote in minutes." }
        },
        services: {
          heading: "Our Services", subheading: "Flexible transport options for homes, businesses, and quick errands.",
          items: [
            { title: "Furniture Moving", badge: "Pickup • Triporteur", description: "Beds, sofas, tables, wardrobes — careful loading, protection, and safe delivery to your door." },
            { title: "Small Deliveries", badge: "Same‑day", description: "Documents, parcels, shop purchases, and quick errands around town — fast and secure." },
            { title: "Building Materials Transport", badge: "Heavy loads", description: "Cement, bricks, tiles, paint, wood — efficient loading and delivery directly to your site." }
          ]
        },
        about: {
          heading: "Why Choose Us",
          paragraph: "At Maroc Move Express, we combine reliability, speed, and affordability to make transport effortless. Our friendly team responds quickly, plans the best route, and treats your items with care. Whether it’s one sofa or a full load of materials, we deliver on time and at a price that makes sense.",
          bullets: ["Reliable arrivals and careful handling", "Transparent pricing with no surprises", "Citywide coverage and 7‑day availability"],
          stats: { jobsCompleted: "Jobs completed", happyClients: "Happy clients", available: "Available", note: "Figures are indicative. Contact us to get an exact quote based on distance, floors, and load size." }
        },
        contact: {
          heading: "Pricing & Contact", paragraph: "Tell us what you need moved, from where to where, and we’ll send a quick quote.",
          phoneLabel: "Phone", whatsappLabel: "WhatsApp", whatsappCTA: "Chat on WhatsApp",
          pricingNote: "Typical range: 120–450 MAD within city. Long‑distance priced per km. Extra for floors without elevator.",
          form: {
            title: "Request a Free Quote", subtitle: "We’ll reply quickly by WhatsApp or phone.", demoBadge: "Demo: opens WhatsApp to send",
            fields: { name: "Name", phone: "Phone", serviceType: "Type of Service", vehicle: "Vehicle", message: "Message", messagePlaceholder: "From: Address A • To: Address B • Floors • Date/Time • Extra info" },
            options: { chooseService: "Choose a service", furnitureMoving: "Furniture Moving", smallDeliveries: "Small Deliveries", materialsTransport: "Building Materials Transport", selectVehicle: "Select vehicle", pickup: "Pickup", triporteur: "Triporteur", either: "Either (recommend)" },
            buttons: { submit: "Send via WhatsApp", callInstead: "Call Instead" },
            notice: "No payment or signup needed.",
            successMessage: "Thanks! A WhatsApp window has opened with your quote details. If it didn’t, please check your popup blocker or use the WhatsApp button above."
          }
        },
        footer: { description: "Fast, reliable pickup and triporteur transport in Casablanca and nearby areas.", contactHeading: "Contact", followHeading: "Follow", whatsappChat: "WhatsApp Chat", location: "Casablanca, Morocco", rights: "All rights reserved.", builtWithCare: "Built with care in Morocco 🇲🇦" }
      },
      ar: {
        nav: { brandName: "Maroc Move Express", tagline: "بيك‑أب & تريبورتور", services: "الخدمات", about: "من نحن", pricingContact: "الأسعار والتواصل", call: "اتصال", requestQuote: "اطلب عرض سعر" },
        hero: {
          badge: "استجابة سريعة • 7 أيام/الأسبوع",
          title: "نقل سريع وبأسعار مناسبة في الدار البيضاء",
          subtitle: "خدمة بيك‑أب وتريبورتور موثوقة لنقل الأثاث ومواد البناء والتوصيلات الصغيرة — وصول سريع، تعامل بعناية، وأسعار عادلة.",
          ctaQuote: "اطلب عرض سعر", ctaWhatsApp: "واتساب",
          note: "شاحنات بيك‑أب وتريبورتور متوفرة • داخل المدينة والمناطق المجاورة • خدمة في نفس اليوم",
          badges: { pickup: "بيك‑أب", triporteur: "تريبورتور", sameDay: "في نفس اليوم" },
          highlights: { startingAt: "ابتداءً من", startingAtValue: "120 درهم", coverage: "التغطية", coverageValue: "المدينة + المناطق القريبة", support: "التوفر", supportValue: "7/7", panelNote: "أسعار شفافة حسب المسافة والطابق والحمولة. احصل على عرض سعر مجاناً في دقائق." }
        },
        services: {
          heading: "خدماتنا", subheading: "خيارات نقل مرنة للمنازل والشركات والمشاوير السريعة.",
          items: [
            { title: "نقل الأثاث", badge: "بيك‑أب • تريبورتور", description: "أسرة، أرائك، طاولات، خزائن — تحميل بعناية، حماية أثناء النقل، وتسليم آمن حتى بابك." },
            { title: "توصيلات صغيرة", badge: "في نفس اليوم", description: "وثائق، طرود، مشتريات من المتاجر، ومشاوير سريعة داخل المدينة — بسرعة وأمان." },
            { title: "نقل مواد البناء", badge: "حمولات ثقيلة", description: "إسمنت، طوب، بلاط، دهانات، وخشب — تحميل فعال وتسليم مباشرة إلى موقعك." }
          ]
        },
        about: {
          heading: "لماذا تختارنا",
          paragraph: "في Maroc Move Express، نجمع بين الموثوقية والسرعة والأسعار المناسبة لنجعل النقل سهلاً. فريقنا الودود يستجيب بسرعة، يختار أفضل مسار، ويتعامل مع أغراضك بعناية. سواء كانت أريكة واحدة أو حمولة كاملة من المواد، نصل في الوقت المتفق عليه وبسعر يناسبك.",
          bullets: ["مواعيد دقيقة وتعامل بعناية", "أسعار واضحة بدون مفاجآت", "تغطية شاملة داخل المدينة وتوفر طيلة أيام الأسبوع"],
          stats: { jobsCompleted: "أكثر من 500 مهمة", happyClients: "تقييم 4.9★", available: "متاحون", note: "الأرقام تقريبية للإيضاح. تواصل معنا للحصول على عرض دقيق حسب المسافة والطوابق وحجم الحمولة." }
        },
        contact: {
          heading: "الأسعار والتواصل", paragraph: "أخبرنا بما تريد نقله، ومن أين إلى أين، وسنرسل لك عرض سعر سريع.",
          phoneLabel: "الهاتف", whatsappLabel: "واتساب", whatsappCTA: "الدردشة على واتساب",
          pricingNote: "النطاق المعتاد: 120–450 درهم داخل المدينة. المسافات الطويلة تُسعَّر لكل كيلومتر. تكلفة إضافية للطوابق بدون مصعد.",
          form: {
            title: "اطلب عرض سعر مجاني", subtitle: "سنرد بسرعة عبر واتساب أو الهاتف.", demoBadge: "تجريبي: يفتح واتساب للإرسال",
            fields: { name: "الاسم", phone: "رقم الهاتف", serviceType: "نوع الخدمة", vehicle: "المركبة", message: "الرسالة", messagePlaceholder: "من: العنوان أ • إلى: العنوان ب • الطوابق • التاريخ/الوقت • معلومات إضافية" },
            options: { chooseService: "اختر خدمة", furnitureMoving: "نقل الأثاث", smallDeliveries: "توصيلات صغيرة", materialsTransport: "نقل مواد البناء", selectVehicle: "اختر المركبة", pickup: "بيك‑أب", triporteur: "تريبورتور", either: "أي منهما (مُفضّل)" },
            buttons: { submit: "إرسال عبر واتساب", callInstead: "اتصال بدلاً من ذلك" },
            notice: "لا حاجة لأي دفع أو تسجيل.",
            successMessage: "شكراً لك! تم فتح نافذة واتساب مع تفاصيل طلبك. إذا لم تُفتح، تأكد من مانع النوافذ المنبثقة أو استخدم زر واتساب أعلاه."
          }
        },
        footer: { description: "نقل سريع وموثوق ببيك‑أب وتريبورتور في الدار البيضاء والمناطق المجاورة.", contactHeading: "تواصل", followHeading: "تابعنا", whatsappChat: "دردشة واتساب", location: "الدار البيضاء، المغرب", rights: "جميع الحقوق محفوظة.", builtWithCare: "تم بناؤه بحب في المغرب 🇲🇦" }
      },
      es: {
        nav: { brandName: "Maroc Move Express", tagline: "Pickup & triciclo de carga", services: "Servicios", about: "Sobre nosotros", pricingContact: "Precios y contacto", call: "Llamar", requestQuote: "Solicitar presupuesto" },
        hero: {
          badge: "Respuesta rápida • 7 días/semana",
          title: "Transporte rápido y económico en Casablanca",
          subtitle: "Servicio confiable de pickup y triciclo de carga para muebles, materiales de construcción y entregas pequeñas — llegada rápida, manejo cuidadoso y precios justos.",
          ctaQuote: "Solicitar presupuesto", ctaWhatsApp: "WhatsApp",
          note: "Pickups y triciclos de carga disponibles • Ciudad y alrededores • Servicio en el día",
          badges: { pickup: "Pickup", triporteur: "Triciclo de carga", sameDay: "En el día" },
          highlights: { startingAt: "Desde", startingAtValue: "120 MAD", coverage: "Cobertura", coverageValue: "Ciudad + alrededores", support: "Disponibilidad", supportValue: "7/7", panelNote: "Tarifas transparentes según distancia, piso y carga. Obtén tu presupuesto gratis en minutos." }
        },
        services: {
          heading: "Nuestros servicios", subheading: "Opciones de transporte flexibles para hogares, negocios y recados rápidos.",
          items: [
            { title: "Mudanza de muebles", badge: "Pickup • Triciclo", description: "Camas, sofás, mesas, armarios — carga cuidadosa, protección y entrega segura hasta tu puerta." },
            { title: "Entregas pequeñas", badge: "En el día", description: "Documentos, paquetes, compras de tiendas y recados rápidos — rápido y seguro." },
            { title: "Transporte de materiales de construcción", badge: "Cargas pesadas", description: "Cemento, ladrillos, azulejos, pintura y madera — carga eficiente y entrega directa a tu obra." }
          ]
        },
        about: {
          heading: "Por qué elegirnos",
          paragraph: "En Maroc Move Express combinamos fiabilidad, rapidez y precios accesibles para que el transporte sea sencillo. Nuestro equipo responde con rapidez, planifica la mejor ruta y cuida tus pertenencias. Ya sea un sofá o una carga completa de materiales, entregamos a tiempo y a un precio justo.",
          bullets: ["Puntualidad y manejo cuidadoso", "Precios transparentes sin sorpresas", "Cobertura en toda la ciudad y disponibilidad 7 días"],
          stats: { jobsCompleted: "500+ trabajos realizados", happyClients: "4.9★ clientes satisfechos", available: "Disponibles", note: "Cifras orientativas. Contáctanos para un presupuesto exacto según distancia, pisos y tamaño de carga." }
        },
        contact: {
          heading: "Precios y contacto", paragraph: "Cuéntanos qué necesitas mover, de dónde a dónde, y te enviaremos un presupuesto rápido.",
          phoneLabel: "Teléfono", whatsappLabel: "WhatsApp", whatsappCTA: "Chat en WhatsApp",
          pricingNote: "Rango habitual: 120–450 MAD dentro de la ciudad. Larga distancia por km. Extra por pisos sin ascensor.",
          form: {
            title: "Solicita un presupuesto gratis", subtitle: "Responderemos rápido por WhatsApp o teléfono.", demoBadge: "Demostración: abre WhatsApp para enviar",
            fields: { name: "Nombre", phone: "Teléfono", serviceType: "Tipo de servicio", vehicle: "Vehículo", message: "Mensaje", messagePlaceholder: "Desde: Dirección A • Hasta: Dirección B • Pisos • Fecha/Hora • Info extra" },
            options: { chooseService: "Elige un servicio", furnitureMoving: "Mudanza de muebles", smallDeliveries: "Entregas pequeñas", materialsTransport: "Transporte de materiales de construcción", selectVehicle: "Elige el vehículo", pickup: "Pickup", triporteur: "Triciclo de carga", either: "Cualquiera (recomendado)" },
            buttons: { submit: "Enviar por WhatsApp", callInstead: "Llamar en su lugar" },
            notice: "No se requiere pago ni registro.",
            successMessage: "¡Gracias! Se ha abierto una ventana de WhatsApp con los detalles de tu solicitud. Si no se abrió, revisa el bloqueador de ventanas emergentes o usa el botón de WhatsApp."
          }
        },
        footer: { description: "Transporte rápido y confiable con pickup y triciclo en Casablanca y alrededores.", contactHeading: "Contacto", followHeading: "Síguenos", whatsappChat: "Chat en WhatsApp", location: "Casablanca, Marruecos", rights: "Todos los derechos reservados.", builtWithCare: "Hecho con cariño en Marruecos 🇲🇦" }
      },
      fr: {
        nav: { brandName: "Maroc Move Express", tagline: "Pickup & triporteur", services: "Services", about: "À propos", pricingContact: "Tarifs & Contact", call: "Appeler", requestQuote: "Demander un devis" },
        hero: {
          badge: "Réponse rapide • 7j/7",
          title: "Transport rapide et abordable à Casablanca",
          subtitle: "Service fiable de pickup et triporteur pour meubles, matériaux de construction et petites livraisons — arrivée rapide, manipulation soignée et prix justes.",
          ctaQuote: "Demander un devis", ctaWhatsApp: "WhatsApp",
          note: "Pickups et triporteurs disponibles • Ville et environs • Service le jour même",
          badges: { pickup: "Pickup", triporteur: "Triporteur", sameDay: "Le jour même" },
          highlights: { startingAt: "À partir de", startingAtValue: "120 MAD", coverage: "Couverture", coverageValue: "Ville + alentours", support: "Disponibilité", supportValue: "7/7", panelNote: "Tarifs transparents selon la distance, l’étage et la charge. Obtenez votre devis gratuit en quelques minutes." }
        },
        services: {
          heading: "Nos services", subheading: "Des options de transport flexibles pour particuliers, entreprises et courses rapides.",
          items: [
            { title: "Déménagement de meubles", badge: "Pickup • Triporteur", description: "Lits, canapés, tables, armoires — chargement soigné, protection et livraison sécurisée jusqu’à votre porte." },
            { title: "Petites livraisons", badge: "Le jour même", description: "Documents, colis, achats en magasin et courses rapides — rapide et sécurisé." },
            { title: "Transport de matériaux de construction", badge: "Charges lourdes", description: "Ciment, briques, carreaux, peinture, bois — chargement efficace et livraison directe sur votre chantier." }
          ]
        },
        about: {
          heading: "Pourquoi nous choisir",
          paragraph: "Chez Maroc Move Express, nous allions fiabilité, rapidité et prix abordables pour simplifier votre transport. Notre équipe réactive choisit le meilleur itinéraire et traite vos biens avec soin. Qu’il s’agisse d’un canapé ou d’une charge complète, nous livrons à l’heure et au juste prix.",
          bullets: ["Ponctualité et manipulation soignée", "Tarification transparente sans mauvaises surprises", "Couverture de toute la ville et disponibilité 7j/7"],
          stats: { jobsCompleted: "500+ missions réalisées", happyClients: "4.9★ clients satisfaits", available: "Disponible", note: "Chiffres indicatifs. Contactez‑nous pour un devis précis selon la distance, les étages et le volume." }
        },
        contact: {
          heading: "Tarifs & Contact", paragraph: "Dites‑nous ce qu’il faut transporter, d’où à où, et nous vous enverrons un devis rapidement.",
          phoneLabel: "Téléphone", whatsappLabel: "WhatsApp", whatsappCTA: "Discuter sur WhatsApp",
          pricingNote: "Fourchette habituelle : 120–450 MAD en ville. Longue distance au km. Supplément pour étages sans ascenseur.",
          form: {
            title: "Demander un devis gratuit", subtitle: "Nous répondons rapidement par WhatsApp ou téléphone.", demoBadge: "Démo : ouvre WhatsApp pour envoyer",
            fields: { name: "Nom", phone: "Téléphone", serviceType: "Type de service", vehicle: "Véhicule", message: "Message", messagePlaceholder: "De : Adresse A • À : Adresse B • Étages • Date/Heure • Infos supplémentaires" },
            options: { chooseService: "Choisir un service", furnitureMoving: "Déménagement de meubles", smallDeliveries: "Petites livraisons", materialsTransport: "Transport de matériaux", selectVehicle: "Choisir le véhicule", pickup: "Pickup", triporteur: "Triporteur", either: "Au choix (recommandé)" },
            buttons: { submit: "Envoyer via WhatsApp", callInstead: "Appeler à la place" },
            notice: "Aucun paiement ni inscription requis.",
            successMessage: "Merci ! Une fenêtre WhatsApp s’est ouverte avec les détails de votre demande. Si ce n’est pas le cas, vérifiez le bloqueur de fenêtres ou utilisez le bouton WhatsApp ci‑dessus."
          }
        },
        footer: { description: "Transport rapide et fiable en pickup et triporteur à Casablanca et alentours.", contactHeading: "Contact", followHeading: "Suivez‑nous", whatsappChat: "Chat WhatsApp", location: "Casablanca, Maroc", rights: "Tous droits réservés.", builtWithCare: "Réalisé avec soin au Maroc 🇲🇦" }
      }
    };

    // Helpers to rebuild selects
    function buildServiceOptions(lang) {
      const opts = translations[lang].contact.form.options;
      const sel = document.getElementById('service');
      sel.innerHTML = '';
      [
        { value: '', label: opts.chooseService },
        { value: 'Furniture Moving', label: opts.furnitureMoving },
        { value: 'Small Deliveries', label: opts.smallDeliveries },
        { value: 'Building Materials Transport', label: opts.materialsTransport }
      ].forEach(o => {
        const opt = document.createElement('option');
        opt.value = o.value;
        opt.textContent = o.label;
        sel.appendChild(opt);
      });
    }
    function buildVehicleOptions(lang) {
      const opts = translations[lang].contact.form.options;
      const sel = document.getElementById('vehicle');
      sel.innerHTML = '';
      [
        { value: '', label: opts.selectVehicle },
        { value: 'Pickup', label: opts.pickup },
        { value: 'Triporteur', label: opts.triporteur },
        { value: 'Either', label: opts.either }
      ].forEach(o => {
        const opt = document.createElement('option');
        opt.value = o.value;
        opt.textContent = o.label;
        sel.appendChild(opt);
      });
    }

    function applyLang(lang) {
      const t = translations[lang];
      // html attributes
      document.documentElement.lang = lang;
      const isRTL = lang === 'ar';
      document.documentElement.dir = isRTL ? 'rtl' : 'ltr';
      document.body.classList.toggle('rtl', isRTL);

      // Title / meta
      document.title = `${t.nav.brandName} — ${t.hero.title}`;

      // Navbar
      document.getElementById('navBrand').textContent = t.nav.brandName;
      document.getElementById('footerBrandName').textContent = t.nav.brandName;
      document.getElementById('rightsBrand').textContent = t.nav.brandName;
      document.getElementById('navTag').textContent = t.nav.tagline;
      document.getElementById('navServices').textContent = t.nav.services;
      document.getElementById('navAbout').textContent = t.nav.about;
      document.getElementById('navPricing').textContent = t.nav.pricingContact;
      document.getElementById('navCall').lastChild.textContent = t.nav.call;
      document.getElementById('navQuote').lastChild.textContent = t.nav.requestQuote;
      document.getElementById('langCurrent').textContent =
        lang === 'en' ? 'English' : lang === 'ar' ? 'العربية' : lang === 'es' ? 'Español' : 'Français';

      // Hero
      document.getElementById('heroBadge').textContent = t.hero.badge;
      document.getElementById('heroTitle').textContent = t.hero.title;
      document.getElementById('heroSubtitle').textContent = t.hero.subtitle;
      document.getElementById('heroCTAQuoteText').textContent = t.hero.ctaQuote;
      document.getElementById('heroWhatsAppText').textContent = t.hero.ctaWhatsApp;
      document.getElementById('heroNote').textContent = t.hero.note;
      document.getElementById('pillPickup').lastChild.textContent = ' ' + t.hero.badges.pickup;
      document.getElementById('pillTriporteur').lastChild.textContent = ' ' + t.hero.badges.triporteur;
      document.getElementById('pillSameDay').lastChild.textContent = ' ' + t.hero.badges.sameDay;
      document.getElementById('hiStartLabel').textContent = t.hero.highlights.startingAt;
      document.getElementById('hiStartValue').textContent = t.hero.highlights.startingAtValue;
      document.getElementById('hiCoverageLabel').textContent = t.hero.highlights.coverage;
      document.getElementById('hiCoverageValue').textContent = t.hero.highlights.coverageValue;
      document.getElementById('hiSupportLabel').textContent = t.hero.highlights.support;
      document.getElementById('hiSupportValue').textContent = t.hero.highlights.supportValue;
      document.getElementById('hiPanelNote').textContent = t.hero.highlights.panelNote;

      // Services
      document.getElementById('servicesHeading').textContent = t.services.heading;
      document.getElementById('servicesSub').textContent = t.services.subheading;
      document.getElementById('svc1Title').textContent = t.services.items[0].title;
      document.getElementById('svc1Badge').textContent = t.services.items[0].badge;
      document.getElementById('svc1Desc').textContent = t.services.items[0].description;
      document.getElementById('svc2Title').textContent = t.services.items[1].title;
      document.getElementById('svc2Badge').textContent = t.services.items[1].badge;
      document.getElementById('svc2Desc').textContent = t.services.items[1].description;
      document.getElementById('svc3Title').textContent = t.services.items[2].title;
      document.getElementById('svc3Badge').textContent = t.services.items[2].badge;
      document.getElementById('svc3Desc').textContent = t.services.items[2].description;

      // About
      document.getElementById('aboutHeading').textContent = t.about.heading;
      document.getElementById('aboutParagraph').textContent = t.about.paragraph;
      document.querySelector('#aboutBullet1 span + span').textContent = t.about.bullets[0];
      document.querySelector('#aboutBullet2 span + span').textContent = t.about.bullets[1];
      document.querySelector('#aboutBullet3 span + span').textContent = t.about.bullets[2];
      document.getElementById('aboutJobsLabel').textContent = t.about.stats.jobsCompleted;
      document.getElementById('aboutHappyLabel').textContent = t.about.stats.happyClients;
      document.getElementById('aboutAvailLabel').textContent = t.about.stats.available;
      document.getElementById('aboutStatsNote').textContent = t.about.stats.note;

      // Contact
      document.getElementById('contactHeading').textContent = t.contact.heading;
      document.getElementById('contactParagraph').textContent = t.contact.paragraph;
      document.getElementById('contactPhoneLabel').textContent = t.contact.phoneLabel;
      document.getElementById('contactWhatsAppLabel').textContent = t.contact.whatsappLabel;
      document.getElementById('contactWhatsAppCTA').textContent = t.contact.whatsappCTA;
      document.getElementById('contactPricingNote').textContent = t.contact.pricingNote;

      // Form
      document.getElementById('formTitle').textContent = t.contact.form.title;
      document.getElementById('formSubtitle').textContent = t.contact.form.subtitle;
      document.getElementById('formDemoBadge').lastChild.textContent = ' ' + t.contact.form.demoBadge;
      document.getElementById('labelName').textContent = t.contact.form.fields.name;
      document.getElementById('labelPhone').textContent = t.contact.form.fields.phone;
      document.getElementById('labelServiceType').textContent = t.contact.form.fields.serviceType;
      document.getElementById('labelVehicle').textContent = t.contact.form.fields.vehicle;
      document.getElementById('labelMessage').textContent = t.contact.form.fields.message;
      document.getElementById('message').placeholder = t.contact.form.fields.messagePlaceholder;
      buildServiceOptions(lang);
      buildVehicleOptions(lang);
      document.getElementById('submitButtonLabel').textContent = t.contact.form.buttons.submit;
      document.getElementById('callInsteadLabel').textContent = t.contact.form.buttons.callInstead;
      document.getElementById('formNotice').textContent = t.contact.form.notice;
      document.getElementById('formSuccess').textContent = t.contact.form.successMessage;

      // Footer
      document.getElementById('footerDescription').textContent = t.footer.description;
      document.getElementById('footerContactHeading').textContent = t.footer.contactHeading;
      document.getElementById('footerFollowHeading').textContent = t.footer.followHeading;
      document.getElementById('footerWhatsAppChat').textContent = t.footer.whatsappChat;
      document.getElementById('footerLocation').textContent = t.footer.location;
      document.getElementById('footerRightsText').textContent = t.footer.rights;
      document.getElementById('footerBuilt').textContent = t.footer.builtWithCare;

      // Save choice
      localStorage.setItem('lang', lang);
    }

    // Language menu behavior
    const langBtn = document.getElementById('langBtn');
    const langMenu = document.getElementById('langMenu');
    langBtn.addEventListener('click', () => {
      const isOpen = !langMenu.classList.contains('hidden');
      langMenu.classList.toggle('hidden', isOpen);
      langBtn.setAttribute('aria-expanded', String(!isOpen));
    });
    document.addEventListener('click', (e) => {
      if (!langMenu.contains(e.target) && !langBtn.contains(e.target)) {
        langMenu.classList.add('hidden');
        langBtn.setAttribute('aria-expanded', 'false');
      }
    });
    langMenu.querySelectorAll('button[data-lang]').forEach(b => {
      b.addEventListener('click', () => {
        const lang = b.getAttribute('data-lang');
        applyLang(lang);
        langMenu.classList.add('hidden');
        langBtn.setAttribute('aria-expanded', 'false');
      });
    });

    // Form handling: validate, then open WhatsApp with prefilled message
    const form = document.getElementById('quoteForm');
    const success = document.getElementById('formSuccess');
    function show(id, showIt) {
      const el = document.getElementById(id);
      if (!el) return;
      el.classList.toggle('hidden', !showIt);
    }
    function validatePhone(value) {
      const cleaned = value.replace(/[^\d+]/g, '');
      return cleaned.length >= 10;
    }
    form.addEventListener('submit', (e) => {
      e.preventDefault();
      const name = document.getElementById('name').value.trim();
      const phone = document.getElementById('phone').value.trim();
      const service = document.getElementById('service').value;
      const vehicle = document.getElementById('vehicle').value;
      const message = document.getElementById('message').value.trim();

      let ok = true;
      show('nameError', name.length < 1 ? (ok = false, true) : false);
      show('phoneError', !validatePhone(phone) ? (ok = false, true) : false);
      show('serviceError', service === '' ? (ok = false, true) : false);
      show('vehicleError', vehicle === '' ? (ok = false, true) : false);
      if (!ok) return;

      const lines = [
        'New transport quote request:',
        `• Name: ${name}`,
        `• Phone: ${phone}`,
        `• Service: ${service}`,
        `• Vehicle: ${vehicle}`,
        message ? `• Details: ${message}` : '',
        '',
        'Sent from Maroc Move Express website'
      ].filter(Boolean);

      const text = encodeURIComponent(lines.join('\n'));
      const waNumber = '212612345678';
      const url = `https://wa.me/${waNumber}?text=${text}`;
      const win = window.open(url, '_blank', 'noopener');
      if (win) { win.opener = null; }
      success.classList.remove('hidden');
      success.scrollIntoView({ behavior: 'smooth', block: 'center' });
    });

    // Init language
    const saved = localStorage.getItem('lang') || 'en';
    applyLang(saved);
  </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'97da627705089d86',t:'MTc1NzYyNzQ2Ny4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
