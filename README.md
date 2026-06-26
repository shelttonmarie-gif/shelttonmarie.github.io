# shelttonmarie.github.io
<!doctype html>
<html lang="en">
 <head><script src="/_sdk/telemetry_sdk.js"></script>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Language Teacher Portfolio</title>
  <script src="https://cdn.tailwindcss.com/3.4.17"></script>
  <script src="https://cdn.jsdelivr.net/npm/lucide@0.263.0/dist/umd/lucide.min.js"></script>
  <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;700&amp;family=Playfair+Display:wght@400;600;700&amp;display=swap" rel="stylesheet">
  <style>
        :root {
            --bg: #FDFBF7;
            --bg-alt: #F5F1EB;
            --text: #2D2D2D;
            --text-muted: #6B6B6B;
            --accent: #7C9A82;
            --accent-hover: #5F7D64;
            --card: #FFFFFF;
            --border: #E8E4DE;
        }
        .dark {
            --bg: #1A1A1A;
            --bg-alt: #242424;
            --text: #F0EDE8;
            --text-muted: #A8A8A8;
            --accent: #94B89A;
            --accent-hover: #B0D4B6;
            --card: #2A2A2A;
            --border: #3A3A3A;
        }
        body { font-family: 'DM Sans', sans-serif; background: var(--bg); color: var(--text); }
        .font-display { font-family: 'Playfair Display', serif; }
        .bg-main { background: var(--bg); }
        .bg-alt { background: var(--bg-alt); }
        .bg-card { background: var(--card); }
        .text-main { color: var(--text); }
        .text-muted { color: var(--text-muted); }
        .text-accent { color: var(--accent); }
        .bg-accent { background: var(--accent); }
        .bg-accent-hover:hover { background: var(--accent-hover); }
        .border-c { border-color: var(--border); }
        .nav-link { position: relative; }
        .nav-link::after { content:''; position:absolute; bottom:-2px; left:0; width:0; height:2px; background:var(--accent); transition:width .3s; }
        .nav-link:hover::after { width:100%; }
        @keyframes fadeUp { from { opacity:0; transform:translateY(20px); } to { opacity:1; transform:translateY(0); } }
        .fade-up { opacity:0; }
        .fade-up.visible { animation: fadeUp .6s ease forwards; }
        .mobile-menu { transform: translateX(100%); transition: transform .3s ease; }
        .mobile-menu.open { transform: translateX(0); }
    </style>
  <script>
        tailwind.config = { darkMode: 'class' }
    </script>
  <script src="/_sdk/data_sdk.js" type="text/javascript"></script>
  <script src="/_sdk/resizing_sdk.js" type="text/javascript"></script>
 </head>
 <body data-template-id="__page-root" class="min-h-screen"><!-- Navigation -->
  <nav class="fixed top-0 w-full bg-card/80 backdrop-blur-md z-50 border-b border-c">
   <div class="max-w-6xl mx-auto px-4 h-16 flex items-center justify-between"><a href="#home" data-template-id="nav-logo" class="canva-text font-display text-xl font-bold text-accent"></a>
    <div class="hidden md:flex items-center gap-6"><a href="#home" class="nav-link text-main text-sm">Home</a> <a href="#about" class="nav-link text-main text-sm">About</a> <a href="#lessons" class="nav-link text-main text-sm">Lessons</a> <a href="#blog" class="nav-link text-main text-sm">Blog</a> <a href="#resources" class="nav-link text-main text-sm">Resources</a> <a href="#contact" class="nav-link text-main text-sm">Contact</a> <button id="dark-toggle" class="p-2 rounded-full hover:bg-alt transition"><i data-lucide="moon" class="w-4 h-4"></i></button>
    </div><button id="mobile-toggle" class="md:hidden p-2"><i data-lucide="menu" class="w-5 h-5"></i></button>
   </div>
  </nav><!-- Mobile Menu -->
  <div id="mobile-menu" class="mobile-menu fixed top-0 right-0 w-64 h-full bg-card z-50 p-6 shadow-xl"><button id="mobile-close" class="mb-6"><i data-lucide="x" class="w-5 h-5"></i></button>
   <div class="flex flex-col gap-4"><a href="#home" class="text-main mobile-link">Home</a> <a href="#about" class="text-main mobile-link">About</a> <a href="#lessons" class="text-main mobile-link">Lessons</a> <a href="#blog" class="text-main mobile-link">Blog</a> <a href="#resources" class="text-main mobile-link">Resources</a> <a href="#contact" class="text-main mobile-link">Contact</a>
   </div>
  </div><!-- Hero -->
  <section id="home" class="pt-24 pb-16 px-4">
   <div class="max-w-6xl mx-auto grid md:grid-cols-2 gap-12 items-center">
    <div class="fade-up">
     <h1 data-template-id="hero-headline" class="canva-text font-display text-4xl md:text-5xl font-bold leading-tight mb-6"></h1>
     <p data-template-id="hero-intro" class="canva-text text-muted text-lg mb-8"></p>
     <div class="flex flex-wrap gap-4"><a href="#lessons" data-template-id="cta-book" class="canva-button px-6 py-3 bg-accent text-white rounded-full font-medium hover:bg-accent-hover transition"></a> <a href="#blog" data-template-id="cta-blog" class="canva-button px-6 py-3 border-2 border-c rounded-full font-medium text-main hover:bg-alt transition"></a>
     </div>
    </div>
    <div class="fade-up"><img data-template-id="hero-image" class="canva-image w-full h-80 object-cover rounded-2xl shadow-lg" loading="lazy">
    </div>
   </div>
  </section><!-- Featured Blog Posts -->
  <section class="py-16 px-4 bg-alt">
   <div class="max-w-6xl mx-auto">
    <h2 data-template-id="featured-title" class="canva-text font-display text-3xl font-bold text-center mb-10"></h2>
    <div class="grid md:grid-cols-3 gap-6">
     <article class="bg-card rounded-xl overflow-hidden shadow-sm fade-up"><img data-template-id="feat-post-1-img" class="canva-image w-full h-44 object-cover" loading="lazy">
      <div class="p-5"><span class="text-xs text-accent font-medium">English</span>
       <h3 data-template-id="feat-post-1-title" class="canva-text font-semibold mt-2 mb-1"></h3>
       <p data-template-id="feat-post-1-desc" class="canva-text text-muted text-sm"></p>
      </div>
     </article>
     <article class="bg-card rounded-xl overflow-hidden shadow-sm fade-up"><img data-template-id="feat-post-2-img" class="canva-image w-full h-44 object-cover" loading="lazy">
      <div class="p-5"><span class="text-xs text-accent font-medium">Study Tips</span>
       <h3 data-template-id="feat-post-2-title" class="canva-text font-semibold mt-2 mb-1"></h3>
       <p data-template-id="feat-post-2-desc" class="canva-text text-muted text-sm"></p>
      </div>
     </article>
     <article class="bg-card rounded-xl overflow-hidden shadow-sm fade-up"><img data-template-id="feat-post-3-img" class="canva-image w-full h-44 object-cover" loading="lazy">
      <div class="p-5"><span class="text-xs text-accent font-medium">Productivity</span>
       <h3 data-template-id="feat-post-3-title" class="canva-text font-semibold mt-2 mb-1"></h3>
       <p data-template-id="feat-post-3-desc" class="canva-text text-muted text-sm"></p>
      </div>
     </article>
    </div>
   </div>
  </section><!-- Testimonials -->
  <section class="py-16 px-4">
   <div class="max-w-4xl mx-auto text-center">
    <h2 data-template-id="testimonials-title" class="canva-text font-display text-3xl font-bold mb-10"></h2>
    <div class="grid md:grid-cols-3 gap-6">
     <div class="bg-card p-6 rounded-xl shadow-sm fade-up border border-c"><img data-template-id="testimonial-1-avatar" class="canva-image w-14 h-14 rounded-full mx-auto mb-4 object-cover" loading="lazy">
      <p data-template-id="testimonial-1-text" class="canva-text text-muted text-sm italic mb-3"></p>
      <p data-template-id="testimonial-1-name" class="canva-text font-semibold text-sm"></p>
     </div>
     <div class="bg-card p-6 rounded-xl shadow-sm fade-up border border-c"><img data-template-id="testimonial-2-avatar" class="canva-image w-14 h-14 rounded-full mx-auto mb-4 object-cover" loading="lazy">
      <p data-template-id="testimonial-2-text" class="canva-text text-muted text-sm italic mb-3"></p>
      <p data-template-id="testimonial-2-name" class="canva-text font-semibold text-sm"></p>
     </div>
     <div class="bg-card p-6 rounded-xl shadow-sm fade-up border border-c"><img data-template-id="testimonial-3-avatar" class="canva-image w-14 h-14 rounded-full mx-auto mb-4 object-cover" loading="lazy">
      <p data-template-id="testimonial-3-text" class="canva-text text-muted text-sm italic mb-3"></p>
      <p data-template-id="testimonial-3-name" class="canva-text font-semibold text-sm"></p>
     </div>
    </div>
   </div>
  </section><!-- Newsletter -->
  <section class="py-12 px-4 bg-alt">
   <div class="max-w-xl mx-auto text-center fade-up">
    <h3 data-template-id="newsletter-title" class="canva-text font-display text-2xl font-bold mb-3"></h3>
    <p data-template-id="newsletter-desc" class="canva-text text-muted mb-6"></p>
    <form id="newsletter-form" class="flex gap-2 max-w-md mx-auto"><input type="email" data-template-id="newsletter-input" class="canva-input flex-1 px-4 py-3 rounded-full border border-c bg-card text-main text-sm" required> <button type="submit" data-template-id="newsletter-btn" class="canva-button px-6 py-3 bg-accent text-white rounded-full font-medium hover:bg-accent-hover transition"></button>
    </form>
    <p id="newsletter-success" class="text-accent text-sm mt-3 hidden">Thanks for subscribing! 🎉</p>
   </div>
  </section><!-- About -->
  <section id="about" class="py-16 px-4">
   <div class="max-w-6xl mx-auto">
    <h2 data-template-id="about-title" class="canva-text font-display text-3xl font-bold text-center mb-12"></h2>
    <div class="grid md:grid-cols-2 gap-12 items-center fade-up"><img data-template-id="about-image" class="canva-image w-full h-96 object-cover rounded-2xl shadow-md" loading="lazy">
     <div>
      <p data-template-id="about-story" class="canva-text text-muted leading-relaxed mb-4"></p>
      <p data-template-id="about-philosophy" class="canva-text text-muted leading-relaxed"></p>
     </div>
    </div><!-- Languages -->
    <div class="mt-12 fade-up">
     <h3 data-template-id="languages-title" class="canva-text font-display text-2xl font-bold text-center mb-6"></h3>
     <div class="grid grid-cols-2 md:grid-cols-4 gap-4 max-w-2xl mx-auto">
      <div class="bg-card border border-c rounded-xl p-4 text-center"><span class="text-2xl">🇬🇧</span>
       <p data-template-id="lang-english" class="canva-text font-medium mt-2 text-sm"></p>
      </div>
      <div class="bg-card border border-c rounded-xl p-4 text-center"><span class="text-2xl">🇫🇷</span>
       <p data-template-id="lang-french" class="canva-text font-medium mt-2 text-sm"></p>
      </div>
      <div class="bg-card border border-c rounded-xl p-4 text-center"><span class="text-2xl">🇩🇪</span>
       <p data-template-id="lang-german" class="canva-text font-medium mt-2 text-sm"></p>
      </div>
      <div class="bg-card border border-c rounded-xl p-4 text-center"><span class="text-2xl">🇸🇰</span>
       <p data-template-id="lang-slovak" class="canva-text font-medium mt-2 text-sm"></p>
      </div>
     </div>
    </div><!-- Timeline -->
    <div class="mt-12 max-w-2xl mx-auto fade-up">
     <h3 data-template-id="timeline-title" class="canva-text font-display text-2xl font-bold text-center mb-8"></h3>
     <div class="space-y-6 border-l-2 border-c pl-6">
      <div><span class="text-accent font-medium text-sm">2015</span>
       <p data-template-id="timeline-1" class="canva-text text-muted text-sm"></p>
      </div>
      <div><span class="text-accent font-medium text-sm">2017</span>
       <p data-template-id="timeline-2" class="canva-text text-muted text-sm"></p>
      </div>
      <div><span class="text-accent font-medium text-sm">2019</span>
       <p data-template-id="timeline-3" class="canva-text text-muted text-sm"></p>
      </div>
      <div><span class="text-accent font-medium text-sm">2022</span>
       <p data-template-id="timeline-4" class="canva-text text-muted text-sm"></p>
      </div>
     </div>
    </div>
   </div>
  </section><!-- Lessons -->
  <section id="lessons" class="py-16 px-4 bg-alt">
   <div class="max-w-6xl mx-auto">
    <h2 data-template-id="lessons-title" class="canva-text font-display text-3xl font-bold text-center mb-4"></h2>
    <p data-template-id="lessons-subtitle" class="canva-text text-muted text-center mb-12"></p>
    <div class="grid md:grid-cols-3 gap-6">
     <div class="bg-card rounded-xl p-6 shadow-sm border border-c fade-up text-center">
      <div class="w-12 h-12 bg-accent/10 rounded-full flex items-center justify-center mx-auto mb-4">
       <i data-lucide="user" class="w-5 h-5 text-accent"></i>
      </div>
      <h4 data-template-id="lesson-1-title" class="canva-text font-semibold mb-2"></h4>
      <p data-template-id="lesson-1-desc" class="canva-text text-muted text-sm mb-4"></p>
      <p data-template-id="lesson-1-price" class="canva-text text-accent font-bold text-xl"></p>
     </div>
     <div class="bg-card rounded-xl p-6 shadow-sm border-2 border-accent fade-up text-center relative"><span class="absolute -top-3 left-1/2 -translate-x-1/2 bg-accent text-white text-xs px-3 py-1 rounded-full">Popular</span>
      <div class="w-12 h-12 bg-accent/10 rounded-full flex items-center justify-center mx-auto mb-4">
       <i data-lucide="message-circle" class="w-5 h-5 text-accent"></i>
      </div>
      <h4 data-template-id="lesson-2-title" class="canva-text font-semibold mb-2"></h4>
      <p data-template-id="lesson-2-desc" class="canva-text text-muted text-sm mb-4"></p>
      <p data-template-id="lesson-2-price" class="canva-text text-accent font-bold text-xl"></p>
     </div>
     <div class="bg-card rounded-xl p-6 shadow-sm border border-c fade-up text-center">
      <div class="w-12 h-12 bg-accent/10 rounded-full flex items-center justify-center mx-auto mb-4">
       <i data-lucide="book-open" class="w-5 h-5 text-accent"></i>
      </div>
      <h4 data-template-id="lesson-3-title" class="canva-text font-semibold mb-2"></h4>
      <p data-template-id="lesson-3-desc" class="canva-text text-muted text-sm mb-4"></p>
      <p data-template-id="lesson-3-price" class="canva-text text-accent font-bold text-xl"></p>
     </div>
     <div class="bg-card rounded-xl p-6 shadow-sm border border-c fade-up text-center">
      <div class="w-12 h-12 bg-accent/10 rounded-full flex items-center justify-center mx-auto mb-4">
       <i data-lucide="award" class="w-5 h-5 text-accent"></i>
      </div>
      <h4 data-template-id="lesson-4-title" class="canva-text font-semibold mb-2"></h4>
      <p data-template-id="lesson-4-desc" class="canva-text text-muted text-sm mb-4"></p>
      <p data-template-id="lesson-4-price" class="canva-text text-accent font-bold text-xl"></p>
     </div>
     <div class="bg-card rounded-xl p-6 shadow-sm border border-c fade-up text-center">
      <div class="w-12 h-12 bg-accent/10 rounded-full flex items-center justify-center mx-auto mb-4">
       <i data-lucide="smile" class="w-5 h-5 text-accent"></i>
      </div>
      <h4 data-template-id="lesson-5-title" class="canva-text font-semibold mb-2"></h4>
      <p data-template-id="lesson-5-desc" class="canva-text text-muted text-sm mb-4"></p>
      <p data-template-id="lesson-5-price" class="canva-text text-accent font-bold text-xl"></p>
     </div>
     <div class="bg-card rounded-xl p-6 shadow-sm border border-c fade-up text-center">
      <div class="w-12 h-12 bg-accent/10 rounded-full flex items-center justify-center mx-auto mb-4">
       <i data-lucide="users" class="w-5 h-5 text-accent"></i>
      </div>
      <h4 data-template-id="lesson-6-title" class="canva-text font-semibold mb-2"></h4>
      <p data-template-id="lesson-6-desc" class="canva-text text-muted text-sm mb-4"></p>
      <p data-template-id="lesson-6-price" class="canva-text text-accent font-bold text-xl"></p>
     </div>
    </div>
   </div>
  </section><!-- Blog -->
  <section id="blog" class="py-16 px-4">
   <div class="max-w-6xl mx-auto">
    <h2 data-template-id="blog-title" class="canva-text font-display text-3xl font-bold text-center mb-4"></h2>
    <p data-template-id="blog-subtitle" class="canva-text text-muted text-center mb-8"></p><!-- Filters -->
    <div class="flex flex-wrap justify-center gap-2 mb-8" id="blog-filters"><button class="blog-filter active px-4 py-2 rounded-full text-sm border border-c bg-accent text-white" data-cat="all">All</button> <button class="blog-filter px-4 py-2 rounded-full text-sm border border-c text-main hover:bg-alt" data-cat="english">English</button> <button class="blog-filter px-4 py-2 rounded-full text-sm border border-c text-main hover:bg-alt" data-cat="french">French</button> <button class="blog-filter px-4 py-2 rounded-full text-sm border border-c text-main hover:bg-alt" data-cat="german">German</button> <button class="blog-filter px-4 py-2 rounded-full text-sm border border-c text-main hover:bg-alt" data-cat="productivity">Productivity</button> <button class="blog-filter px-4 py-2 rounded-full text-sm border border-c text-main hover:bg-alt" data-cat="study-tips">Study Tips</button>
    </div><!-- Posts Grid -->
    <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6" id="blog-grid">
     <article class="blog-post bg-card rounded-xl overflow-hidden shadow-sm border border-c fade-up" data-cat="english"><img data-template-id="blog-1-img" class="canva-image w-full h-40 object-cover" loading="lazy">
      <div class="p-5">
       <div class="flex items-center gap-2 text-xs text-muted mb-2">
        <span>5 min read</span><span>·</span><span>Jun 20, 2026</span>
       </div>
       <h4 data-template-id="blog-1-title" class="canva-text font-semibold mb-1"></h4>
       <p data-template-id="blog-1-desc" class="canva-text text-muted text-sm"></p><span class="inline-block mt-3 text-xs bg-accent/10 text-accent px-2 py-1 rounded">English</span>
      </div>
     </article>
     <article class="blog-post bg-card rounded-xl overflow-hidden shadow-sm border border-c fade-up" data-cat="study-tips"><img data-template-id="blog-2-img" class="canva-image w-full h-40 object-cover" loading="lazy">
      <div class="p-5">
       <div class="flex items-center gap-2 text-xs text-muted mb-2">
        <span>4 min read</span><span>·</span><span>Jun 15, 2026</span>
       </div>
       <h4 data-template-id="blog-2-title" class="canva-text font-semibold mb-1"></h4>
       <p data-template-id="blog-2-desc" class="canva-text text-muted text-sm"></p><span class="inline-block mt-3 text-xs bg-accent/10 text-accent px-2 py-1 rounded">Study Tips</span>
      </div>
     </article>
     <article class="blog-post bg-card rounded-xl overflow-hidden shadow-sm border border-c fade-up" data-cat="productivity"><img data-template-id="blog-3-img" class="canva-image w-full h-40 object-cover" loading="lazy">
      <div class="p-5">
       <div class="flex items-center gap-2 text-xs text-muted mb-2">
        <span>6 min read</span><span>·</span><span>Jun 10, 2026</span>
       </div>
       <h4 data-template-id="blog-3-title" class="canva-text font-semibold mb-1"></h4>
       <p data-template-id="blog-3-desc" class="canva-text text-muted text-sm"></p><span class="inline-block mt-3 text-xs bg-accent/10 text-accent px-2 py-1 rounded">Productivity</span>
      </div>
     </article>
     <article class="blog-post bg-card rounded-xl overflow-hidden shadow-sm border border-c fade-up" data-cat="french"><img data-template-id="blog-4-img" class="canva-image w-full h-40 object-cover" loading="lazy">
      <div class="p-5">
       <div class="flex items-center gap-2 text-xs text-muted mb-2">
        <span>3 min read</span><span>·</span><span>Jun 5, 2026</span>
       </div>
       <h4 data-template-id="blog-4-title" class="canva-text font-semibold mb-1"></h4>
       <p data-template-id="blog-4-desc" class="canva-text text-muted text-sm"></p><span class="inline-block mt-3 text-xs bg-accent/10 text-accent px-2 py-1 rounded">French</span>
      </div>
     </article>
     <article class="blog-post bg-card rounded-xl overflow-hidden shadow-sm border border-c fade-up" data-cat="german"><img data-template-id="blog-5-img" class="canva-image w-full h-40 object-cover" loading="lazy">
      <div class="p-5">
       <div class="flex items-center gap-2 text-xs text-muted mb-2">
        <span>7 min read</span><span>·</span><span>May 28, 2026</span>
       </div>
       <h4 data-template-id="blog-5-title" class="canva-text font-semibold mb-1"></h4>
       <p data-template-id="blog-5-desc" class="canva-text text-muted text-sm"></p><span class="inline-block mt-3 text-xs bg-accent/10 text-accent px-2 py-1 rounded">German</span>
      </div>
     </article>
     <article class="blog-post bg-card rounded-xl overflow-hidden shadow-sm border border-c fade-up" data-cat="english"><img data-template-id="blog-6-img" class="canva-image w-full h-40 object-cover" loading="lazy">
      <div class="p-5">
       <div class="flex items-center gap-2 text-xs text-muted mb-2">
        <span>5 min read</span><span>·</span><span>May 20, 2026</span>
       </div>
       <h4 data-template-id="blog-6-title" class="canva-text font-semibold mb-1"></h4>
       <p data-template-id="blog-6-desc" class="canva-text text-muted text-sm"></p><span class="inline-block mt-3 text-xs bg-accent/10 text-accent px-2 py-1 rounded">English</span>
      </div>
     </article>
    </div>
   </div>
  </section><!-- Resources -->
  <section id="resources" class="py-16 px-4 bg-alt">
   <div class="max-w-6xl mx-auto">
    <h2 data-template-id="resources-title" class="canva-text font-display text-3xl font-bold text-center mb-4"></h2>
    <p data-template-id="resources-subtitle" class="canva-text text-muted text-center mb-10"></p>
    <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6">
     <div class="bg-card rounded-xl p-6 text-center border border-c fade-up">
      <div class="w-12 h-12 bg-accent/10 rounded-full flex items-center justify-center mx-auto mb-4">
       <i data-lucide="file-text" class="w-5 h-5 text-accent"></i>
      </div>
      <h4 data-template-id="resource-1-title" class="canva-text font-semibold mb-2"></h4>
      <p data-template-id="resource-1-desc" class="canva-text text-muted text-sm mb-4"></p><button data-template-id="resource-1-btn" class="canva-button text-sm bg-accent text-white px-4 py-2 rounded-full hover:bg-accent-hover transition"></button>
     </div>
     <div class="bg-card rounded-xl p-6 text-center border border-c fade-up">
      <div class="w-12 h-12 bg-accent/10 rounded-full flex items-center justify-center mx-auto mb-4">
       <i data-lucide="book-open" class="w-5 h-5 text-accent"></i>
      </div>
      <h4 data-template-id="resource-2-title" class="canva-text font-semibold mb-2"></h4>
      <p data-template-id="resource-2-desc" class="canva-text text-muted text-sm mb-4"></p><button data-template-id="resource-2-btn" class="canva-button text-sm bg-accent text-white px-4 py-2 rounded-full hover:bg-accent-hover transition"></button>
     </div>
     <div class="bg-card rounded-xl p-6 text-center border border-c fade-up">
      <div class="w-12 h-12 bg-accent/10 rounded-full flex items-center justify-center mx-auto mb-4">
       <i data-lucide="calendar" class="w-5 h-5 text-accent"></i>
      </div>
      <h4 data-template-id="resource-3-title" class="canva-text font-semibold mb-2"></h4>
      <p data-template-id="resource-3-desc" class="canva-text text-muted text-sm mb-4"></p><button data-template-id="resource-3-btn" class="canva-button text-sm bg-accent text-white px-4 py-2 rounded-full hover:bg-accent-hover transition"></button>
     </div>
     <div class="bg-card rounded-xl p-6 text-center border border-c fade-up">
      <div class="w-12 h-12 bg-accent/10 rounded-full flex items-center justify-center mx-auto mb-4">
       <i data-lucide="download" class="w-5 h-5 text-accent"></i>
      </div>
      <h4 data-template-id="resource-4-title" class="canva-text font-semibold mb-2"></h4>
      <p data-template-id="resource-4-desc" class="canva-text text-muted text-sm mb-4"></p><button data-template-id="resource-4-btn" class="canva-button text-sm bg-accent text-white px-4 py-2 rounded-full hover:bg-accent-hover transition"></button>
     </div>
    </div>
   </div>
  </section><!-- Contact -->
  <section id="contact" class="py-16 px-4">
   <div class="max-w-4xl mx-auto">
    <h2 data-template-id="contact-title" class="canva-text font-display text-3xl font-bold text-center mb-4"></h2>
    <p data-template-id="contact-subtitle" class="canva-text text-muted text-center mb-10"></p>
    <div class="grid md:grid-cols-2 gap-10">
     <form id="contact-form" class="space-y-4 fade-up">
      <div><label for="c-name" data-template-id="contact-name-label" class="canva-text text-sm font-medium mb-1 block"></label> <input id="c-name" type="text" class="w-full px-4 py-3 rounded-lg border border-c bg-card text-main text-sm" required>
      </div>
      <div><label for="c-email" data-template-id="contact-email-label" class="canva-text text-sm font-medium mb-1 block"></label> <input id="c-email" type="email" class="w-full px-4 py-3 rounded-lg border border-c bg-card text-main text-sm" required>
      </div>
      <div><label for="c-msg" data-template-id="contact-msg-label" class="canva-text text-sm font-medium mb-1 block"></label> <textarea id="c-msg" rows="4" class="w-full px-4 py-3 rounded-lg border border-c bg-card text-main text-sm" required></textarea>
      </div><button type="submit" data-template-id="contact-submit" class="canva-button w-full py-3 bg-accent text-white rounded-lg font-medium hover:bg-accent-hover transition"></button>
      <p id="contact-success" class="text-accent text-sm text-center hidden">Message sent successfully! ✨</p>
     </form>
     <div class="fade-up">
      <div class="flex gap-4 mb-6"><a href="#" target="_blank" rel="noopener noreferrer" class="w-10 h-10 bg-alt rounded-full flex items-center justify-center hover:bg-accent/20 transition"><i data-lucide="instagram" class="w-4 h-4"></i></a> <a href="#" target="_blank" rel="noopener noreferrer" class="w-10 h-10 bg-alt rounded-full flex items-center justify-center hover:bg-accent/20 transition"><i data-lucide="send" class="w-4 h-4"></i></a> <a href="#" target="_blank" rel="noopener noreferrer" class="w-10 h-10 bg-alt rounded-full flex items-center justify-center hover:bg-accent/20 transition"><i data-lucide="youtube" class="w-4 h-4"></i></a> <a href="#" target="_blank" rel="noopener noreferrer" class="w-10 h-10 bg-alt rounded-full flex items-center justify-center hover:bg-accent/20 transition"><i data-lucide="linkedin" class="w-4 h-4"></i></a>
      </div>
      <div class="bg-alt rounded-xl h-64 flex items-center justify-center border border-c">
       <p class="text-muted text-sm">📍 Google Maps placeholder</p>
      </div>
     </div>
    </div>
   </div>
  </section><!-- Footer -->
  <footer class="py-10 px-4 bg-alt border-t border-c">
   <div class="max-w-6xl mx-auto flex flex-col md:flex-row justify-between items-center gap-4">
    <p data-template-id="footer-text" class="canva-text text-muted text-sm"></p>
    <div class="flex gap-6 text-sm"><a href="#home" class="text-muted hover:text-accent transition">Home</a> <a href="#about" class="text-muted hover:text-accent transition">About</a> <a href="#lessons" class="text-muted hover:text-accent transition">Lessons</a> <a href="#blog" class="text-muted hover:text-accent transition">Blog</a> <a href="#contact" class="text-muted hover:text-accent transition">Contact</a>
    </div>
   </div>
  </footer>
  <script src="/_sdk/editing_sdk.js"></script>
  <script>
    // Dark mode
    const toggle = document.getElementById('dark-toggle');
    toggle.addEventListener('click', () => {
        document.documentElement.classList.toggle('dark');
    });

    // Mobile menu
    document.getElementById('mobile-toggle').addEventListener('click', () => document.getElementById('mobile-menu').classList.add('open'));
    document.getElementById('mobile-close').addEventListener('click', () => document.getElementById('mobile-menu').classList.remove('open'));
    document.querySelectorAll('.mobile-link').forEach(l => l.addEventListener('click', () => document.getElementById('mobile-menu').classList.remove('open')));

    // Scroll animations
    const observer = new IntersectionObserver(entries => {
        entries.forEach(e => { if (e.isIntersecting) { e.target.classList.add('visible'); observer.unobserve(e.target); } });
    }, { threshold: 0.1 });
    document.querySelectorAll('.fade-up').forEach(el => observer.observe(el));

    // Blog filter
    document.querySelectorAll('.blog-filter').forEach(btn => {
        btn.addEventListener('click', () => {
            document.querySelectorAll('.blog-filter').forEach(b => { b.classList.remove('bg-accent', 'text-white'); b.classList.add('text-main'); });
            btn.classList.add('bg-accent', 'text-white'); btn.classList.remove('text-main');
            const cat = btn.dataset.cat;
            document.querySelectorAll('.blog-post').forEach(p => {
                p.style.display = (cat === 'all' || p.dataset.cat === cat) ? '' : 'none';
            });
        });
    });

    // Newsletter form
    document.getElementById('newsletter-form').addEventListener('submit', e => {
        e.preventDefault();
        document.getElementById('newsletter-success').classList.remove('hidden');
        e.target.reset();
    });

    // Contact form
    document.getElementById('contact-form').addEventListener('submit', e => {
        e.preventDefault();
        document.getElementById('contact-success').classList.remove('hidden');
        e.target.reset();
    });

    lucide.createIcons();
</script>
 <script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'a11e3df2f11c77bf',t:'MTc4MjQ5ODE5NC4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
