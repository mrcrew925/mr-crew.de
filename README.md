<!DOCTYPE html>

<html class="scroll-smooth" lang="de"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>MR-CREW - Facility Management &amp; Umzüge</title>
<link href="https://fonts.googleapis.com" rel="preconnect"/>
<link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&amp;family=Work+Sans:wght@500;700;800;900&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            colors: {
              "error-container": "#ffdad6",
              "surface-dim": "#dcd9d9",
              "surface-tint": "#0061a7",
              "on-primary-fixed": "#001c37",
              "on-tertiary": "#ffffff",
              "inverse-primary": "#a1c9ff",
              "on-surface": "#1b1c1c",
              "on-surface-variant": "#404752",
              "primary-fixed": "#d2e4ff",
              "error": "#ba1a1a",
              "secondary": "#5f5e5e",
              "on-primary": "#ffffff",
              "on-secondary-fixed-variant": "#474746",
              "surface-bright": "#fbf9f8",
              "on-primary-container": "#fdfcff",
              "outline": "#717783",
              "on-secondary-container": "#636262",
              "on-primary-fixed-variant": "#00487f",
              "surface-variant": "#e4e2e1",
              "on-tertiary-fixed": "#1a1c1c",
              "tertiary-fixed": "#e2e2e2",
              "on-tertiary-container": "#fdfdfd",
              "background": "#fbf9f8",
              "outline-variant": "#c0c7d3",
              "on-secondary-fixed": "#1b1c1c",
              "inverse-on-surface": "#f3f0f0",
              "inverse-surface": "#303030",
              "tertiary": "#5b5c5d",
              "secondary-container": "#e2dfde",
              "on-error-container": "#93000a",
              "surface": "#fbf9f8",
              "on-background": "#1b1c1c",
              "on-secondary": "#ffffff",
              "surface-container-lowest": "#ffffff",
              "surface-container-high": "#eae8e7",
              "tertiary-container": "#737575",
              "tertiary-fixed-dim": "#c6c6c7",
              "surface-container-low": "#f6f3f2",
              "secondary-fixed": "#e5e2e1",
              "primary-fixed-dim": "#a1c9ff",
              "secondary-fixed-dim": "#c8c6c5",
              "surface-container-highest": "#e4e2e1",
              "on-error": "#ffffff",
              "primary": "#005ea3",
              "on-tertiary-fixed-variant": "#454747",
              "primary-container": "#0077cc",
              "surface-container": "#f0eded"
            },
            fontFamily: {
              "headline": ["Work Sans"],
              "body": ["Inter"],
              "label": ["Inter"]
            },
            borderRadius: {"DEFAULT": "0.125rem", "lg": "0.25rem", "xl": "0.5rem", "full": "0.75rem"},
          },
        },
      }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        .glass-header {
            backdrop-filter: blur(20px);
            -webkit-backdrop-filter: blur(20px);
        }
        .blueprint-grid {
            background-image: radial-gradient(circle, #717783 1px, transparent 1px);
            background-size: 40px 40px;
            opacity: 0.03;
        }
    </style>
</head>
<body class="bg-background text-on-surface font-body selection:bg-primary/20 selection:text-primary" data-mode="connect">
<!-- TopAppBar -->
<header class="fixed top-0 w-full z-50 bg-white/80 dark:bg-stone-900/80 backdrop-blur-md border-b border-stone-200/20 shadow-sm transition-all duration-300">
<!-- Center Logo Section -->
<div class="w-full bg-white flex justify-center py-4 border-b border-stone-100">
<img alt="MR-CREW Logo" class="h-20 w-auto object-contain" src="https://lh3.googleusercontent.com/aida/ADBb0ugbCA9x-BAt5xZ-dhZuSyreXsVPGFSPk-2KSUgez3X_PsCp9zmVIS07xtBWF9WFCIfCQOyJ0qXEMjz0M_fVMErnc9DZMLMjyXmNfGM4CsAeyH80LE-ccm2Kma2ncHNZeImdZ1Y9TBy0SXL2ZeTfXO4fBOO1CL_B15HdvW8JJHlSmvHeo4O7S_d6Xsl41VHwyOLZpzGJ-NEPYEsk6N76lTdMVwTi-pQRWhuJfgY-6sNyqtveHP0WJQi-JBbhrZLjdLgE7nZb3h0rvg"/>
</div>
<div class="flex justify-between items-center px-6 md:px-12 py-4 max-w-screen-2xl mx-auto">
<div class="flex items-center gap-3 invisible">
<!-- Left side space for alignment if needed, logo is centered above -->
<div class="h-10 w-24"></div>
</div>
<nav class="hidden md:flex items-center gap-8">
<a class="font-work-sans text-stone-900 font-medium tracking-tight text-blue-700 border-b-2 border-blue-700 pb-1" href="#home">Home</a>
<a class="font-work-sans text-stone-900 font-medium tracking-tight text-stone-600 hover:text-blue-700 transition-colors" href="#services">Leistungen</a>
<a class="font-work-sans text-stone-900 font-medium tracking-tight text-stone-600 hover:text-blue-700 transition-colors" href="#contact">Kontakt</a>
</nav>
<div class="flex items-center gap-4">
<a class="bg-gradient-to-br from-primary to-primary-container text-on-primary px-6 py-2.5 rounded shadow-sm font-medium hover:opacity-90 transition-all active:scale-95" href="#quote">
                    Angebot anfordern
                </a>
</div>
</div>
</header>
<main>
<!-- Hero Section -->
<section class="relative min-h-[1024px] flex items-center pt-48 overflow-hidden" data-stitch-vh="min-h-[1024px]===min-h-screen" id="home">
<div class="absolute inset-0 blueprint-grid pointer-events-none"></div>
<div class="max-w-7xl mx-auto px-6 md:px-12 grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
<div class="lg:col-span-7 z-10">
<h1 class="font-headline text-5xl md:text-7xl font-black text-on-surface leading-[1.1] tracking-tight mb-8">
                        MR-CREW - Ihr Partner für <span class="text-primary">Entrümpelungen, Baudienstleistungen</span> &amp; Umzüge
                    </h1>
<p class="text-xl text-on-surface-variant max-w-xl leading-relaxed mb-10">
                        Professionell, diskret und termingerecht. Wir übernehmen die harte Arbeit, damit Sie sich auf das Wesentliche konzentrieren können.
                    </p>
<div class="flex flex-wrap gap-4">
<a class="bg-gradient-to-br from-primary to-primary-container text-on-primary px-8 py-4 rounded font-bold text-lg hover:shadow-xl transition-all flex items-center gap-2" href="#services">
                            Jetzt Angebot anfordern
                            <span class="material-symbols-outlined">arrow_forward</span>
</a>
<a class="bg-surface-container-high text-on-surface px-8 py-4 rounded font-bold text-lg hover:bg-surface-container-highest transition-all flex items-center gap-2" href="tel:052217612509">
<span class="material-symbols-outlined">call</span>
                            05221-7612509
                        </a>
</div>
</div>
<div class="lg:col-span-5 relative">
<div class="aspect-[4/5] rounded-lg overflow-hidden shadow-2xl relative z-10">
<img alt="Modern Architecture" class="w-full h-full object-cover" data-alt="clean minimal architectural lines of a high-end corporate building facade with glass and steel elements under clear blue sky" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBMCKXJNJTHmXkke-8J85vpVOZSuVqbEPuvZDXTT4rHk2WWkDoh7z8pFfHrYtoIjUrA7Wy0zSZPjXQ08v7r-TugwZpyiFKaMYWMxQulyb1CAFuX0DfA9BsqZk9GdFN8d-yy5UW0FzE8lIpWg47rKhLyalxPeT02tOEF4sCzaKADxFZ3ZCYk8f6YrCdlX9KmuqKkctH2yHu19Sx1DRVm0DL7L3u78rJ4uVt5lFAT7TktJqF1NdCE5vmP9VtJMtmNGNx4f5HKn30B9Vg"/>
<div class="absolute inset-0 bg-gradient-to-t from-black/40 to-transparent"></div>
</div>
<!-- Asymmetric design element -->
<div class="absolute -bottom-6 -left-6 w-48 h-48 bg-primary/10 -z-10 rounded-sm"></div>
<div class="absolute -top-12 -right-12 w-64 h-64 border border-outline-variant/20 -z-10 rounded-sm"></div>
</div>
</div>
</section>
<!-- Services Bento Grid -->
<section class="py-32 bg-surface-container-low" id="services">
<div class="max-w-7xl mx-auto px-6 md:px-12">
<div class="flex flex-col md:flex-row md:items-end justify-between mb-20 gap-8">
<div class="max-w-2xl">
<h2 class="font-headline text-4xl md:text-5xl font-black tracking-tight text-on-surface mb-6">
                            Umfassende Lösungen aus einer Hand.
                        </h2>
<div class="h-1.5 w-24 bg-primary mb-6"></div>
<p class="text-on-surface-variant text-lg">
                            Von der privaten Wohnungsauflösung bis hin zum gewerblichen Großprojekt – unsere Crew steht für Präzision und Zuverlässigkeit.
                        </p>
</div>
<div class="text-primary font-bold text-sm tracking-widest uppercase flex items-center gap-2">
                        Unsere Leistungen <span class="material-symbols-outlined">keyboard_double_arrow_down</span>
</div>
</div>
<div class="grid grid-cols-1 md:grid-cols-3 lg:grid-cols-4 gap-6">
<!-- Card 1: Entrümpelungen (Large) -->
<div class="md:col-span-2 md:row-span-2 bg-surface-container-lowest rounded shadow-sm hover:shadow-md transition-all flex flex-col justify-between group overflow-hidden relative p-6">
<div>
<img alt="MR-CREW Logo" class="w-auto mb-3 object-contain h-24 mx-auto" src="https://lh3.googleusercontent.com/aida/ADBb0ugbCA9x-BAt5xZ-dhZuSyreXsVPGFSPk-2KSUgez3X_PsCp9zmVIS07xtBWF9WFCIfCQOyJ0qXEMjz0M_fVMErnc9DZMLMjyXmNfGM4CsAeyH80LE-ccm2Kma2ncHNZeImdZ1Y9TBy0SXL2ZeTfXO4fBOO1CL_B15HdvW8JJHlSmvHeo4O7S_d6Xsl41VHwyOLZpzGJ-NEPYEsk6N76lTdMVwTi-pQRWhuJfgY-6sNyqtveHP0WJQi-JBbhrZLjdLgE7nZb3h0rvg"/><h3 class="font-headline text-2xl font-bold mb-2">Entrümpelungen</h3>
<p class="text-on-surface-variant leading-relaxed">
                                Komplette Haushalts- und Wohnungsauflösungen. Wir räumen besenrein, diskret und kümmern uns um die fachgerechte Entsorgung aller Materialien.
                            </p>
</div>
<div class="border-t border-outline-variant/10 mt-4 pt-4">
<ul class="space-y-2">
<li class="flex items-center gap-2 text-sm text-on-surface-variant"><span class="material-symbols-outlined text-primary text-sm">check_circle</span> Haushaltsauflösungen</li>
<li class="flex items-center gap-2 text-sm text-on-surface-variant"><span class="material-symbols-outlined text-primary text-sm">check_circle</span> Firmenauflösungen</li>
<li class="flex items-center gap-2 text-sm text-on-surface-variant"><span class="material-symbols-outlined text-primary text-sm">check_circle</span> Sperrmüllentsorgung</li>
</ul>
</div>
</div>
<!-- Card 2: Umzüge -->
<div class="bg-surface-container-lowest p-8 rounded shadow-sm hover:shadow-md transition-all group">
<span class="material-symbols-outlined text-primary text-4xl mb-6" data-icon="local_shipping">local_shipping</span>
<h3 class="font-headline text-xl font-bold mb-3">Umzüge</h3>
<p class="text-on-surface-variant text-sm leading-relaxed">
                            Privat- und Firmenumzüge. Stressfrei und sicher an Ihr neues Ziel.
                        </p>
</div>
<!-- Card 3: Montagearbeiten -->
<div class="bg-surface-container-lowest p-8 rounded shadow-sm hover:shadow-md transition-all group">
<span class="material-symbols-outlined text-primary text-4xl mb-6" data-icon="build">build</span>
<h3 class="font-headline text-xl font-bold mb-3">Montagearbeiten</h3>
<p class="text-on-surface-variant text-sm leading-relaxed">
                            Möbel-, Küchen- und Innenmontagen durch geschultes Fachpersonal.
                        </p>
</div>
<!-- Card 4: Entkernungen -->
<div class="bg-surface-container-lowest p-8 rounded shadow-sm hover:shadow-md transition-all group">
<span class="material-symbols-outlined text-primary text-4xl mb-6" data-icon="construction">construction</span>
<h3 class="font-headline text-xl font-bold mb-3">Entkernungen</h3>
<p class="text-on-surface-variant text-sm leading-relaxed">
                            Fachgerechte Entkernung als Vorbereitung für Ihre Sanierungsprojekte.
                        </p>
</div>
<!-- Card 5: Baudienstleistungen -->
<div class="bg-surface-container-lowest p-8 rounded shadow-sm hover:shadow-md transition-all group">
<span class="material-symbols-outlined text-primary text-4xl mb-6" data-icon="home_repair_service">home_repair_service</span>
<h3 class="font-headline text-xl font-bold mb-3">Baudienstleistungen</h3>
<p class="text-on-surface-variant text-sm leading-relaxed">
                            Renovierung, Reparatur und Instandhaltung Ihrer Bausubstanz.
                        </p>
</div>
<!-- Card 6: Hausmeisterservice -->
<div class="md:col-span-2 bg-primary p-8 rounded shadow-lg flex items-center justify-between text-on-primary group overflow-hidden relative">
<div class="relative z-10">
<h3 class="font-headline text-2xl font-bold mb-3">Hausmeisterservice</h3>
<p class="text-on-primary/80 leading-relaxed max-w-md">
                                Regelmäßige Betreuung Ihrer Immobilie. Wir sorgen für Ordnung, Sauberkeit und Funktionalität rund um die Uhr.
                            </p>
</div>
<span class="material-symbols-outlined text-on-primary/20 !text-8xl relative z-10" data-icon="vignette">vignette</span>
<!-- Decorative background texture -->
<div class="absolute inset-0 bg-white/5 opacity-10 blueprint-grid"></div>
</div>
<!-- Card 7: Gartenarbeiten -->
<div class="bg-surface-container-lowest p-8 rounded shadow-sm hover:shadow-md transition-all group">
<span class="material-symbols-outlined text-primary text-4xl mb-6" data-icon="park">park</span>
<h3 class="font-headline text-xl font-bold mb-3">Gartenarbeiten</h3>
<p class="text-on-surface-variant text-sm leading-relaxed">
                            Pflege, Rückschnitt und Gestaltung Ihrer Außenanlagen.
                        </p>
</div>
</div>
</div>
</section>
<!-- Stats / Trust Section -->
<section class="py-24 bg-surface">
<div class="max-w-7xl mx-auto px-6 md:px-12">
<div class="grid grid-cols-2 md:grid-cols-4 gap-12 text-center">
<div>
<div class="text-4xl md:text-5xl font-black text-primary mb-2 font-headline">10+</div>
<div class="text-sm font-bold uppercase tracking-widest text-on-surface-variant">Jahre Erfahrung</div>
</div>
<div>
<div class="text-4xl md:text-5xl font-black text-primary mb-2 font-headline">500+</div>
<div class="text-sm font-bold uppercase tracking-widest text-on-surface-variant">Projekte</div>
</div>
<div>
<div class="text-4xl md:text-5xl font-black text-primary mb-2 font-headline">100%</div>
<div class="text-sm font-bold uppercase tracking-widest text-on-surface-variant">Diskretion</div>
</div>
<div>
<div class="text-4xl md:text-5xl font-black text-primary mb-2 font-headline">24/7</div>
<div class="text-sm font-bold uppercase tracking-widest text-on-surface-variant">Service</div>
</div>
</div>
</div>
</section>
<!-- Contact Section -->
<section class="py-32 relative overflow-hidden" id="contact">
<div class="max-w-7xl mx-auto px-6 md:px-12 grid grid-cols-1 lg:grid-cols-2 gap-20">
<div>
<h2 class="font-headline text-4xl md:text-5xl font-black tracking-tight mb-8">Nehmen Sie <span class="text-primary">Kontakt</span> auf.</h2>
<p class="text-xl text-on-surface-variant mb-12 leading-relaxed">
                        Haben Sie Fragen zu unseren Dienstleistungen oder wünschen Sie ein unverbindliches Angebot? Wir freuen uns auf Ihre Nachricht.
                    </p>
<div class="space-y-8">
<div class="flex items-start gap-6">
<div class="w-14 h-14 bg-primary/10 rounded-full flex items-center justify-center shrink-0">
<span class="material-symbols-outlined text-primary">call</span>
</div>
<div>
<div class="text-sm font-bold uppercase tracking-widest text-on-surface-variant mb-1">Rufen Sie uns an</div>
<a class="text-2xl font-bold hover:text-primary transition-colors" href="tel:052217612509">05221-7612509</a>
</div>
</div>
<div class="flex items-start gap-6">
<div class="w-14 h-14 bg-primary/10 rounded-full flex items-center justify-center shrink-0">
<span class="material-symbols-outlined text-primary">mail</span>
</div>
<div>
<div class="text-sm font-bold uppercase tracking-widest text-on-surface-variant mb-1">Schreiben Sie uns</div>
<a class="text-2xl font-bold hover:text-primary transition-colors" href="mailto:info@mr-crew.de">info@mr-crew.de</a>
</div>
</div>
<div class="flex items-start gap-6">
<div class="w-14 h-14 bg-primary/10 rounded-full flex items-center justify-center shrink-0">
<span class="material-symbols-outlined text-primary">location_on</span>
</div>
<div>
<div class="text-sm font-bold uppercase tracking-widest text-on-surface-variant mb-1">Unser Standort</div>
<address class="text-2xl font-bold not-italic">Ginsterweg 5,<br/>32049 Herford</address>
</div>
</div>
</div>
</div>
<div class="bg-surface-container p-8 md:p-12 rounded shadow-2xl relative">
<form class="space-y-6" id="quote">
<div class="grid grid-cols-1 md:grid-cols-2 gap-6">
<div class="space-y-2">
<label class="text-xs font-bold uppercase tracking-wider text-on-surface-variant">Name</label>
<input class="w-full bg-transparent border-0 border-b-2 border-outline-variant focus:ring-0 focus:border-primary transition-colors py-3 px-0 placeholder:text-outline-variant" placeholder="Ihr voller Name" type="text"/>
</div>
<div class="space-y-2">
<label class="text-xs font-bold uppercase tracking-wider text-on-surface-variant">Email</label>
<input class="w-full bg-transparent border-0 border-b-2 border-outline-variant focus:ring-0 focus:border-primary transition-colors py-3 px-0 placeholder:text-outline-variant" placeholder="name@beispiel.de" type="email"/>
</div>
</div>
<div class="space-y-2">
<label class="text-xs font-bold uppercase tracking-wider text-on-surface-variant">Leistung</label>
<select class="w-full bg-transparent border-0 border-b-2 border-outline-variant focus:ring-0 focus:border-primary transition-colors py-3 px-0">
<option>Entrümpelung</option>
<option>Umzug</option>
<option>Hausmeisterservice</option>
<option>Anderes</option>
</select>
</div>
<div class="space-y-2">
<label class="text-xs font-bold uppercase tracking-wider text-on-surface-variant">Nachricht</label>
<textarea class="w-full bg-transparent border-0 border-b-2 border-outline-variant focus:ring-0 focus:border-primary transition-colors py-3 px-0 placeholder:text-outline-variant" placeholder="Wie können wir Ihnen helfen?" rows="4"></textarea>
</div>
<button class="w-full bg-primary text-on-primary font-bold py-4 rounded hover:bg-primary-container transition-all shadow-lg active:scale-95 uppercase tracking-widest" type="submit">
                            Anfrage Senden
                        </button>
</form>
</div>
</div>
<!-- Decorative Large Logo Watermark -->
<div class="absolute -bottom-24 -right-24 opacity-5 pointer-events-none select-none">
<img alt="Decorative Logo" class="w-[600px] h-auto grayscale" data-alt="large faint watermark of the MR-CREW logo with geometric precision and clean industrial aesthetics" src="https://lh3.googleusercontent.com/aida/ADBb0ugbCA9x-BAt5xZ-dhZuSyreXsVPGFSPk-2KSUgez3X_PsCp9zmVIS07xtBWF9WFCIfCQOyJ0qXEMjz0M_fVMErnc9DZMLMjyXmNfGM4CsAeyH80LE-ccm2Kma2ncHNZeImdZ1Y9TBy0SXL2ZeTfXO4fBOO1CL_B15HdvW8JJHlSmvHeo4O7S_d6Xsl41VHwyOLZpzGJ-NEPYEsk6N76lTdMVwTi-pQRWhuJfgY-6sNyqtveHP0WJQi-JBbhrZLjdLgE7nZb3h0rvg"/>
</div>
</section>
</main>
<!-- Footer -->
<footer class="w-full mt-24 bg-stone-50 border-t border-stone-100">
<div class="grid grid-cols-1 md:grid-cols-3 gap-12 px-8 py-16 max-w-7xl mx-auto">
<div class="space-y-6">
<div class="flex items-center gap-3">
<img alt="MR-CREW Logo" class="h-12 w-auto object-contain" src="https://lh3.googleusercontent.com/aida/ADBb0ugbCA9x-BAt5xZ-dhZuSyreXsVPGFSPk-2KSUgez3X_PsCp9zmVIS07xtBWF9WFCIfCQOyJ0qXEMjz0M_fVMErnc9DZMLMjyXmNfGM4CsAeyH80LE-ccm2Kma2ncHNZeImdZ1Y9TBy0SXL2ZeTfXO4fBOO1CL_B15HdvW8JJHlSmvHeo4O7S_d6Xsl41VHwyOLZpzGJ-NEPYEsk6N76lTdMVwTi-pQRWhuJfgY-6sNyqtveHP0WJQi-JBbhrZLjdLgE7nZb3h0rvg"/>
</div>
<p class="font-inter text-sm text-stone-600 leading-relaxed max-w-xs">
                    Ihr zuverlässiger Partner für professionelles Facility Management, Umzüge und Baudienstleistungen. Präzision in jeder Aufgabe.
                </p>
</div>
<div class="space-y-6">
<h4 class="text-stone-900 font-bold uppercase tracking-widest text-xs">Navigation</h4>
<nav class="flex flex-col gap-4">
<a class="font-inter text-sm text-stone-500 hover:text-stone-900 hover:underline transition-all" href="#home">Home</a>
<a class="font-inter text-sm text-stone-500 hover:text-stone-900 hover:underline transition-all" href="#services">Leistungen</a>
<a class="font-inter text-sm text-stone-500 hover:text-stone-900 hover:underline transition-all" href="#contact">Kontakt</a>
</nav>
</div>
<div class="space-y-6">
<h4 class="text-stone-900 font-bold uppercase tracking-widest text-xs">Impressum &amp; Kontakt</h4>
<div class="space-y-4">
<div class="text-xs text-stone-500 leading-relaxed">
<p class="font-bold text-stone-700 mb-1">Anbieterkennzeichnung gemäß § 5 TMG:</p>
<p>Sadiye Kader Roncevic</p>
<p>Ginsterweg 5</p>
<p>32049 Herford</p>
</div>
<nav class="flex flex-col gap-3">
<a class="font-inter text-sm text-stone-500 hover:text-stone-900 hover:underline transition-all flex items-center gap-2" href="tel:052217612509">
<span class="material-symbols-outlined text-xs">call</span> Tel: 05221-7612509
        </a>
<a class="font-inter text-sm text-stone-500 hover:text-stone-900 hover:underline transition-all flex items-center gap-2" href="mailto:info@mr-crew.de">
<span class="material-symbols-outlined text-xs">mail</span> Email: info@mr-crew.de
        </a>
</nav>
<nav class="flex flex-col gap-3 pt-2 border-t border-stone-100">
<a class="font-inter text-sm text-stone-500 hover:text-stone-900 hover:underline transition-all" href="#">Datenschutz</a>
<a class="font-inter text-sm text-stone-500 hover:text-stone-900 hover:underline transition-all" href="#">AGB</a>
</nav>
</div>
</div>
</div>
<div class="max-w-7xl mx-auto px-8 py-8 border-t border-stone-100 flex flex-col md:flex-row justify-between items-center gap-4">
<p class="font-inter text-sm text-stone-600">
                © 2024 MR-CREW Facility Management. Alle Rechte vorbehalten.
            </p>
<div class="flex gap-6">
<span class="material-symbols-outlined text-stone-400 cursor-pointer hover:text-primary transition-colors" data-icon="facebook">social_leaderboard</span>
<span class="material-symbols-outlined text-stone-400 cursor-pointer hover:text-primary transition-colors" data-icon="instagram">retweet</span>
<span class="material-symbols-outlined text-stone-400 cursor-pointer hover:text-primary transition-colors" data-icon="linkedin">link</span>
</div>
</div>
</footer>
</body></html>
<!DOCTYPE html>

<html class="scroll-smooth" lang="de"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Impressum | MR-CREW Facility Management</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Work+Sans:wght@400;500;700;800;900&amp;family=Inter:wght@300;400;500;600&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            colors: {
              "on-tertiary-container": "#fdfdfd",
              "on-tertiary": "#ffffff",
              "tertiary-fixed-dim": "#c6c6c7",
              "surface-variant": "#e4e2e1",
              "on-secondary-fixed": "#1b1c1c",
              "inverse-primary": "#a1c9ff",
              "secondary": "#5f5e5e",
              "on-primary-fixed": "#001c37",
              "on-secondary-fixed-variant": "#474746",
              "surface-container-high": "#eae8e7",
              "secondary-fixed": "#e5e2e1",
              "surface-container-lowest": "#ffffff",
              "secondary-fixed-dim": "#c8c6c5",
              "surface-container-low": "#f6f3f2",
              "surface-container": "#f0eded",
              "on-primary-fixed-variant": "#00487f",
              "surface-container-highest": "#e4e2e1",
              "on-secondary": "#ffffff",
              "on-surface": "#1b1c1c",
              "tertiary-container": "#737575",
              "surface-tint": "#0061a7",
              "on-tertiary-fixed-variant": "#454747",
              "surface-dim": "#dcd9d9",
              "secondary-container": "#e2dfde",
              "outline": "#717783",
              "on-tertiary-fixed": "#1a1c1c",
              "on-error": "#ffffff",
              "inverse-surface": "#303030",
              "on-primary": "#ffffff",
              "on-background": "#1b1c1c",
              "primary-fixed-dim": "#a1c9ff",
              "on-secondary-container": "#636262",
              "outline-variant": "#c0c7d3",
              "primary-container": "#0077cc",
              "surface-bright": "#fbf9f8",
              "primary-fixed": "#d2e4ff",
              "tertiary-fixed": "#e2e2e2",
              "background": "#fbf9f8",
              "on-primary-container": "#fdfcff",
              "error": "#ba1a1a",
              "inverse-on-surface": "#f3f0f0",
              "surface": "#fbf9f8",
              "on-error-container": "#93000a",
              "on-surface-variant": "#404752",
              "tertiary": "#5b5c5d",
              "primary": "#005ea3",
              "error-container": "#ffdad6"
            },
            fontFamily: {
              "headline": ["Work Sans"],
              "body": ["Inter"],
              "label": ["Inter"]
            },
            borderRadius: {"DEFAULT": "0.125rem", "lg": "0.25rem", "xl": "0.5rem", "full": "0.75rem"},
          },
        },
      }
    </script>
<style>
      .material-symbols-outlined {
        font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
      }
      .blue-blueprint-bg {
        background-image: linear-gradient(to right, rgba(192, 199, 211, 0.1) 1px, transparent 1px),
                          linear-gradient(to bottom, rgba(192, 199, 211, 0.1) 1px, transparent 1px);
        background-size: 40px 40px;
      }
    </style>
</head>
<body class="bg-surface font-body text-on-surface antialiased">
<!-- TopNavBar -->
<nav class="fixed top-0 w-full z-50 bg-white/80 dark:bg-stone-900/80 backdrop-blur-md shadow-sm dark:shadow-none font-['Work_Sans'] font-medium antialiased">
<div class="flex justify-between items-center px-8 py-4 max-w-7xl mx-auto">
<div class="flex items-center gap-4">
<img alt="MR-CREW Logo" class="h-10 w-auto" data-alt="high-contrast minimalist black and white professional corporate logo for facility management company MR-CREW" src="https://lh3.googleusercontent.com/aida-public/AB6AXuD8XiCbfHnrGCZFSpzU4Busy19nqPXEB-FoCu1ayAmJZX57IwDcBsF_dqFEob2VyhW6GCiXd8NKUja_McYXJhv2OZ2IZaBNoZL8U5LruJitcZAfEXxJqY5I2p2zMylFGKkRKPxTfUmu97Ur4UjNCbm2S6vCiw13UHrLT0VhgWvDbc-j0nRWQk8stVMwPWQ8Mx0-YcGNvXRvBwubBX-CLXrXcm6v8dMt7s4mlcKsVdfZfotjpSTjLIwk3IoG97RRggw-tDDU0-ONOJk"/>
<span class="text-2xl font-black tracking-tighter text-stone-900 dark:text-stone-50 uppercase">MR-CREW</span>
</div>
<div class="hidden md:flex gap-8">
<a class="text-stone-600 dark:text-stone-400 hover:text-blue-600 dark:hover:text-blue-300 transition-colors" href="#">Home</a>
<a class="text-stone-600 dark:text-stone-400 hover:text-blue-600 dark:hover:text-blue-300 transition-colors" href="#">Services</a>
<a class="text-stone-600 dark:text-stone-400 hover:text-blue-600 dark:hover:text-blue-300 transition-colors" href="#">Contact</a>
</div>
<div class="flex items-center">
<button class="bg-gradient-to-br from-primary to-primary-container text-on-primary px-6 py-2.5 rounded hover:opacity-80 transition-opacity duration-300 font-headline font-bold text-sm tracking-tight active:scale-95 duration-150">
                    Get a Quote
                </button>
</div>
</div>
</nav>
<main class="pt-32 pb-24 min-h-screen relative overflow-hidden">
<!-- Background Branding Watermark -->
<div class="absolute -top-20 -right-20 opacity-[0.03] pointer-events-none select-none">
<span class="text-[20rem] font-black tracking-tighter uppercase">CREW</span>
</div>
<div class="max-w-7xl mx-auto px-8 relative z-10">
<!-- Hero Header -->
<div class="mb-20">
<span class="font-label uppercase tracking-widest text-primary font-semibold text-xs mb-4 block">Rechtliche Hinweise</span>
<h1 class="font-headline text-6xl md:text-7xl font-black text-on-surface tracking-tighter leading-none mb-8">
                    Impressum
                </h1>
<div class="w-24 h-2 bg-primary"></div>
</div>
<!-- Content Grid: Asymmetric Layout -->
<div class="grid grid-cols-1 lg:grid-cols-12 gap-12">
<!-- Main Legal Columns -->
<div class="lg:col-span-8 space-y-20">
<!-- Section: TMG -->
<section class="p-12 bg-surface-container-low relative group">
<div class="absolute top-0 left-0 w-1 h-full bg-primary opacity-20 group-hover:opacity-100 transition-opacity"></div>
<h2 class="font-headline text-3xl font-extrabold mb-8 tracking-tight">Angaben gemäß § 5 TMG</h2>
<div class="space-y-6 text-lg leading-relaxed text-on-surface-variant">
<div>
<p class="font-label text-xs uppercase text-secondary font-bold tracking-widest mb-1">Inhaber</p>
<p class="text-on-surface font-semibold text-xl">Sadiye Kader Roncevic</p>
</div>
<div>
<p class="font-label text-xs uppercase text-secondary font-bold tracking-widest mb-1">Anschrift</p>
<p class="text-on-surface">Ginsterweg 5<br/>32049 Herford</p>
</div>
</div>
</section>
<!-- Section: Kontakt -->
<section class="grid grid-cols-1 md:grid-cols-2 gap-px bg-outline-variant/15">
<div class="p-12 bg-surface-container-high">
<h2 class="font-headline text-2xl font-extrabold mb-6 tracking-tight">Kontakt</h2>
<div class="space-y-4">
<div class="flex items-start gap-4">
<span class="material-symbols-outlined text-primary" data-icon="call">call</span>
<div>
<p class="font-label text-xs uppercase text-secondary font-bold tracking-widest">Telefon</p>
<p class="text-on-surface text-lg">05221-7612509</p>
</div>
</div>
<div class="flex items-start gap-4">
<span class="material-symbols-outlined text-primary" data-icon="mail">mail</span>
<div>
<p class="font-label text-xs uppercase text-secondary font-bold tracking-widest">E-Mail</p>
<p class="text-on-surface text-lg">info@mr-crew.de</p>
</div>
</div>
</div>
</div>
<div class="p-12 bg-surface-container-highest flex flex-col justify-end">
<p class="text-on-surface-variant italic mb-4">"Präzision in jeder Facette des Facility Managements."</p>
<span class="font-label text-xs font-bold uppercase tracking-tighter text-primary">MR-CREW Standards</span>
</div>
</section>
<!-- Section: Verantwortlich -->
<section class="p-12 bg-surface-container-low border-l-4 border-primary/10">
<h2 class="font-headline text-2xl font-extrabold mb-6 tracking-tight">Verantwortlich für den Inhalt</h2>
<p class="font-label text-xs uppercase text-secondary font-bold tracking-widest mb-2">nach § 55 Abs. 2 RStV</p>
<p class="text-xl font-semibold text-on-surface">Sadiye Kader Roncevic</p>
<p class="text-on-surface-variant mt-2">Ginsterweg 5, 32049 Herford</p>
</section>
</div>
<!-- Sidebar Metadata -->
<aside class="lg:col-span-4 space-y-8">
<div class="bg-primary p-8 text-on-primary">
<span class="material-symbols-outlined text-4xl mb-6" data-icon="gavel" style="font-variation-settings: 'FILL' 1;">gavel</span>
<h3 class="font-headline text-2xl font-bold mb-4">Streitbeilegung</h3>
<p class="text-on-primary-container text-sm leading-relaxed opacity-90">
                            Die Europäische Kommission stellt eine Plattform zur Online-Streitbeilegung (OS) bereit: <a class="underline hover:text-white transition-colors" href="https://ec.europa.eu/consumers/odr">https://ec.europa.eu/consumers/odr</a>.
                            Unsere E-Mail-Adresse finden Sie oben im Impressum. Wir sind nicht bereit oder verpflichtet, an Streitbeilegungsverfahren vor einer Verbraucherschlichtungsstelle teilzunehmen.
                        </p>
</div>
<div class="aspect-square bg-surface-container-high flex items-center justify-center relative overflow-hidden group">
<div class="absolute inset-0 blue-blueprint-bg opacity-30"></div>
<div class="relative text-center p-8">
<span class="material-symbols-outlined text-6xl text-outline mb-4" data-icon="location_on">location_on</span>
<p class="font-headline font-bold text-lg">Zentrale Herford</p>
<p class="text-secondary text-sm">Präzise Planung vor Ort.</p>
</div>
</div>
</aside>
</div>
</div>
</main>
<!-- Footer -->
<footer class="w-full py-12 border-t border-stone-200/15 bg-stone-50 dark:bg-stone-950 font-['Inter'] text-sm tracking-wide">
<div class="grid grid-cols-1 md:grid-cols-3 gap-8 px-8 max-w-7xl mx-auto items-start">
<div>
<span class="text-lg font-bold text-stone-900 dark:text-stone-100 block mb-4">MR-CREW</span>
<p class="text-stone-500 max-w-xs leading-relaxed">
                    Ihr Partner für erstklassiges Facility Management und Logistikdienstleistungen in Herford und Umgebung.
                </p>
</div>
<div class="grid grid-cols-2 gap-4">
<div class="flex flex-col gap-3">
<a class="text-stone-500 dark:text-stone-500 hover:text-stone-800 dark:hover:text-stone-200 hover:underline decoration-blue-500/30" href="#">Home</a>
<a class="text-stone-500 dark:text-stone-500 hover:text-stone-800 dark:hover:text-stone-200 hover:underline decoration-blue-500/30" href="#">Services</a>
</div>
<div class="flex flex-col gap-3">
<a class="text-blue-700 dark:text-blue-400 font-semibold hover:underline decoration-blue-500/30" href="#">Impressum</a>
<a class="text-stone-500 dark:text-stone-500 hover:text-stone-800 dark:hover:text-stone-200 hover:underline decoration-blue-500/30" href="#">Datenschutz</a>
</div>
</div>
<div class="md:text-right">
<p class="text-stone-400 mb-2">Kontaktieren Sie uns</p>
<p class="text-stone-900 dark:text-stone-100 font-bold">05221-7612509</p>
<p class="text-stone-500 mt-8">© 2024 MR-CREW Facility Management. All rights reserved.</p>
</div>
</div>
</footer>
</body></html>
<!DOCTYPE html>

<html class="scroll-smooth" lang="de"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Work+Sans:wght@300;400;500;600;700;900&amp;family=Inter:wght@300;400;500;600&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            colors: {
              "secondary": "#5f5e5e",
              "on-primary-fixed": "#001c37",
              "inverse-primary": "#a1c9ff",
              "surface-container-high": "#eae8e7",
              "secondary-fixed": "#e5e2e1",
              "on-secondary-fixed-variant": "#474746",
              "surface-container-lowest": "#ffffff",
              "secondary-fixed-dim": "#c8c6c5",
              "on-tertiary-container": "#fdfdfd",
              "on-tertiary": "#ffffff",
              "tertiary-fixed-dim": "#c6c6c7",
              "surface-variant": "#e4e2e1",
              "on-secondary-fixed": "#1b1c1c",
              "surface-container-highest": "#e4e2e1",
              "on-secondary": "#ffffff",
              "on-surface": "#1b1c1c",
              "tertiary-container": "#737575",
              "surface-tint": "#0061a7",
              "on-tertiary-fixed-variant": "#454747",
              "surface-container-low": "#f6f3f2",
              "surface-container": "#f0eded",
              "on-primary-fixed-variant": "#00487f",
              "primary-fixed-dim": "#a1c9ff",
              "on-secondary-container": "#636262",
              "primary-container": "#0077cc",
              "outline-variant": "#c0c7d3",
              "surface-bright": "#fbf9f8",
              "primary-fixed": "#d2e4ff",
              "surface-dim": "#dcd9d9",
              "secondary-container": "#e2dfde",
              "outline": "#717783",
              "on-tertiary-fixed": "#1a1c1c",
              "on-error": "#ffffff",
              "inverse-surface": "#303030",
              "on-background": "#1b1c1c",
              "on-primary": "#ffffff",
              "on-error-container": "#93000a",
              "surface": "#fbf9f8",
              "tertiary": "#5b5c5d",
              "on-surface-variant": "#404752",
              "primary": "#005ea3",
              "error-container": "#ffdad6",
              "tertiary-fixed": "#e2e2e2",
              "background": "#fbf9f8",
              "error": "#ba1a1a",
              "on-primary-container": "#fdfcff",
              "inverse-on-surface": "#f3f0f0"
            },
            fontFamily: {
              "headline": ["Work Sans"],
              "body": ["Inter"],
              "label": ["Inter"]
            },
            borderRadius: {"DEFAULT": "0.125rem", "lg": "0.25rem", "xl": "0.5rem", "full": "0.75rem"},
          },
        },
      }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
            vertical-align: middle;
        }
        .blueprint-grid {
            background-image: radial-gradient(circle, #c0c7d3 1px, transparent 1px);
            background-size: 40px 40px;
            opacity: 0.1;
        }
    </style>
</head>
<body class="bg-surface text-on-surface font-body leading-relaxed">
<!-- Top Navigation Bar -->
<header class="fixed top-0 w-full z-50 bg-white/80 dark:bg-stone-900/80 backdrop-blur-md border-b border-stone-200/15 dark:border-stone-700/15 shadow-sm dark:shadow-none">
<div class="flex justify-between items-center px-6 py-4 max-w-7xl mx-auto">
<div class="text-2xl font-black tracking-tighter text-[#1b1c1c] dark:text-stone-100 uppercase font-headline">
                MR-CREW
            </div>
<nav class="hidden md:flex items-center gap-8 font-headline font-medium tracking-tight">
<a class="text-[#5f5e5e] dark:text-stone-400 hover:text-[#1b1c1c] dark:hover:text-stone-100 transition-colors" href="#">Services</a>
<a class="text-[#5f5e5e] dark:text-stone-400 hover:text-[#1b1c1c] dark:hover:text-stone-100 transition-colors" href="#">Projects</a>
<a class="text-[#5f5e5e] dark:text-stone-400 hover:text-[#1b1c1c] dark:hover:text-stone-100 transition-colors" href="#">About</a>
<a class="text-[#5f5e5e] dark:text-stone-400 hover:text-[#1b1c1c] dark:hover:text-stone-100 transition-colors" href="#">Contact</a>
</nav>
<button class="bg-primary hover:opacity-80 transition-opacity text-on-primary px-5 py-2 rounded-lg font-headline font-semibold text-sm">
                Get a Quote
            </button>
</div>
</header>
<main class="pt-32 pb-24 relative overflow-hidden">
<!-- Blueprint Background Texture -->
<div class="absolute inset-0 blueprint-grid pointer-events-none"></div>
<div class="max-w-7xl mx-auto px-6 relative z-10">
<!-- Hero Section / Header -->
<div class="mb-20">
<span class="label-md uppercase tracking-[0.2em] text-primary font-bold block mb-4">Rechtliches</span>
<h1 class="font-headline text-5xl md:text-7xl font-black text-on-surface tracking-tighter leading-none mb-6">
                    Datenschutz-<br/><span class="text-primary">erklärung</span>
</h1>
<div class="w-24 h-2 bg-primary mb-8"></div>
<p class="text-body-lg text-secondary max-w-2xl text-lg italic">
                    Ihre Privatsphäre ist das Fundament unserer professionellen Zusammenarbeit. Hier erfahren Sie transparent, wie wir mit Ihren Daten bei MR-CREW umgehen.
                </p>
</div>
<!-- Bento Layout for Privacy Content -->
<div class="grid grid-cols-1 lg:grid-cols-12 gap-8">
<!-- 1. Datenschutz auf einen Blick (Large Card) -->
<section class="lg:col-span-8 bg-surface-container-low p-8 md:p-12 rounded-xl relative">
<div class="flex items-center gap-4 mb-8">
<span class="material-symbols-outlined text-primary text-3xl" data-icon="visibility">visibility</span>
<h2 class="font-headline text-3xl font-bold tracking-tight">1. Datenschutz auf einen Blick</h2>
</div>
<div class="space-y-6 text-on-surface-variant">
<h3 class="font-headline font-bold text-xl text-on-surface">Allgemeine Hinweise</h3>
<p>Die folgenden Hinweise geben einen einfachen Überblick darüber, was mit Ihren personenbezogenen Daten passiert, wenn Sie diese Website besuchen. Personenbezogene Daten sind alle Daten, mit denen Sie persönlich identifiziert werden können.</p>
<div class="grid grid-cols-1 md:grid-cols-2 gap-6 mt-8">
<div class="bg-surface-container-lowest p-6 rounded-lg border-l-4 border-primary">
<h4 class="font-bold mb-2">Datenerfassung</h4>
<p class="text-sm">Die Datenerfassung auf dieser Website erfolgt durch den Websitebetreiber.</p>
</div>
<div class="bg-surface-container-lowest p-6 rounded-lg border-l-4 border-primary">
<h4 class="font-bold mb-2">Ihre Rechte</h4>
<p class="text-sm">Sie haben jederzeit das Recht, unentgeltlich Auskunft über Herkunft, Empfänger und Zweck zu erhalten.</p>
</div>
</div>
</div>
</section>
<!-- Sidebar Content (Responsibility) -->
<aside class="lg:col-span-4 space-y-8">
<div class="bg-primary text-on-primary p-8 rounded-xl shadow-xl">
<span class="material-symbols-outlined mb-4 text-4xl" data-icon="admin_panel_settings">admin_panel_settings</span>
<h2 class="font-headline text-2xl font-bold mb-4">Verantwortliche Stelle</h2>
<address class="not-italic space-y-1 opacity-90">
<p class="font-bold">Sadiye Kader Roncevic</p>
<p>MR-CREW </p>
<p>Ginsterweg 5</p>
<p>32049 Herford</p>
<p class="pt-4 flex items-center gap-2">
<span class="material-symbols-outlined text-sm" data-icon="mail">mail</span>
                                info@mr-crew.de
                            </p>
</address>
</div>
<div class="bg-surface-container-high p-8 rounded-xl">
<h3 class="font-headline font-bold mb-4">Aufsichtsbehörde</h3>
<p class="text-sm text-secondary">
                            Landesbeauftragte für Datenschutz und Informationsfreiheit Nordrhein-Westfalen.
                        </p>
</div>
</aside>
<!-- 2. Allgemeine Hinweise & Pflichtinformationen -->
<section class="lg:col-span-12 bg-white p-8 md:p-12 rounded-xl border border-outline-variant/15">
<div class="flex items-center gap-4 mb-8">
<span class="material-symbols-outlined text-primary text-3xl" data-icon="info">info</span>
<h2 class="font-headline text-3xl font-bold tracking-tight">2. Allgemeine Hinweise und Pflichtinformationen</h2>
</div>
<div class="grid grid-cols-1 md:grid-cols-2 gap-12">
<div class="space-y-4">
<h3 class="font-headline font-bold text-lg">Widerruf Ihrer Einwilligung</h3>
<p class="text-secondary">Viele Datenverarbeitungsvorgänge sind nur mit Ihrer ausdrücklichen Einwilligung möglich. Sie können eine bereits erteilte Einwilligung jederzeit widerrufen. Dazu reicht eine formlose Mitteilung per E-Mail an uns.</p>
</div>
<div class="space-y-4">
<h3 class="font-headline font-bold text-lg">Beschwerderecht</h3>
<p class="text-secondary">Im Falle von Datenschutzverstößen steht dem Betroffenen ein Beschwerderecht bei der zuständigen Aufsichtsbehörde zu. Zuständige Aufsichtsbehörde ist der Landesdatenschutzbeauftragte des Bundeslandes.</p>
</div>
<div class="space-y-4">
<h3 class="font-headline font-bold text-lg">SSL- bzw. TLS-Verschlüsselung</h3>
<p class="text-secondary">Diese Seite nutzt aus Sicherheitsgründen eine SSL- bzw. TLS-Verschlüsselung. Eine verschlüsselte Verbindung erkennen Sie daran, dass die Adresszeile des Browsers von „http://“ auf „https://“ wechselt.</p>
</div>
<div class="space-y-4">
<h3 class="font-headline font-bold text-lg">Recht auf Datenübertragbarkeit</h3>
<p class="text-secondary">Sie haben das Recht, Daten, die wir auf Grundlage Ihrer Einwilligung oder in Erfüllung eines Vertrags automatisiert verarbeiten, an sich oder an einen Dritten aushändigen zu lassen.</p>
</div>
</div>
</section>
<!-- 3. Datenerfassung (The Architectural Grid) -->
<section class="lg:col-span-7 bg-surface-container-low p-8 md:p-12 rounded-xl">
<div class="flex items-center gap-4 mb-8">
<span class="material-symbols-outlined text-primary text-3xl" data-icon="database">database</span>
<h2 class="font-headline text-3xl font-bold tracking-tight">3. Datenerfassung auf dieser Website</h2>
</div>
<div class="space-y-8">
<div class="relative pl-8 border-l-2 border-primary/30">
<h3 class="font-headline font-bold text-xl mb-2">Cookies</h3>
<p class="text-secondary text-sm leading-relaxed">Unsere Internetseiten verwenden so genannte „Cookies“. Cookies sind kleine Textdateien und richten auf Ihrem Endgerät keinen Schaden an. Sie dienen dazu, unser Angebot nutzerfreundlicher, effektiver und sicherer zu machen.</p>
</div>
<div class="relative pl-8 border-l-2 border-primary/30">
<h3 class="font-headline font-bold text-xl mb-2">Server-Log-Dateien</h3>
<p class="text-secondary text-sm leading-relaxed">Der Provider der Seiten erhebt und speichert automatisch Informationen in so genannten Server-Log-Dateien, die Ihr Browser automatisch an uns übermittelt. Dies sind: Browsertyp, Betriebssystem, Referrer URL, Hostname, Uhrzeit.</p>
</div>
<div class="relative pl-8 border-l-2 border-primary/30">
<h3 class="font-headline font-bold text-xl mb-2">Kontaktformular</h3>
<p class="text-secondary text-sm leading-relaxed">Wenn Sie uns per Kontaktformular Anfragen zukommen lassen, werden Ihre Angaben aus dem Anfrageformular inklusive der von Ihnen dort angegebenen Kontaktdaten zwecks Bearbeitung der Anfrage gespeichert.</p>
</div>
</div>
</section>
<!-- Visual Anchor -->
<div class="lg:col-span-5 h-[400px] lg:h-auto rounded-xl overflow-hidden relative group">
<img alt="Moderne Architektur Glasfassade" class="w-full h-full object-cover grayscale brightness-75 group-hover:grayscale-0 transition-all duration-700" data-alt="Close-up of a high-end modern glass building facade reflecting the blue sky, architectural precision with clean vertical lines and steel elements" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAZYkfiofTwCEgoRS6uIiD2mllAT3CV01CLiLQapCZamySL7NEIeyGye7qr6u4Xnsl_SgxGLE6YgUl0Via-FHB-gtwAfrVEJd0esDHf5to3uXkfgDjXlCbS3GjnQKix2YbuHaICsr2pSsRKWPfT6skPEHlsPyDK0VF3YyDLA_rTdRxqUNbN0_UNguhGIbELuMyKd8fvF7xsJxxvPFy2GZcU8fIuZjPwEzCXNFjLLObEvhgncpO-3m12dLo5z6QS71e4M9mCYnbrkKg"/>
<div class="absolute inset-0 bg-gradient-to-t from-primary/80 to-transparent flex items-end p-8">
<p class="text-on-primary font-headline font-bold text-xl tracking-tight italic">"Präzision in jedem Detail – auch beim Schutz Ihrer Daten."</p>
</div>
</div>
<!-- 4. & 5. Social Media & Tools -->
<section class="lg:col-span-12 grid grid-cols-1 md:grid-cols-2 gap-8">
<div class="bg-surface-container-highest p-8 rounded-xl">
<div class="flex items-center gap-4 mb-6">
<span class="material-symbols-outlined text-primary text-3xl" data-icon="share">share</span>
<h2 class="font-headline text-2xl font-bold tracking-tight">4. Soziale Medien</h2>
</div>
<p class="text-secondary text-sm">
                            Wir setzen auf unserer Website keine Social-Media-Plugins direkt ein. Sofern Verlinkungen zu unseren sozialen Profilen bestehen, werden keine Daten beim bloßen Seitenaufruf übertragen. Erst beim Klick auf den Button verlassen Sie unsere Umgebung.
                        </p>
</div>
<div class="bg-surface-container-highest p-8 rounded-xl">
<div class="flex items-center gap-4 mb-6">
<span class="material-symbols-outlined text-primary text-3xl" data-icon="analytics">analytics</span>
<h2 class="font-headline text-2xl font-bold tracking-tight">5. Analyse-Tools und Werbung</h2>
</div>
<p class="text-secondary text-sm">
                            Wir verzichten weitgehend auf Tracking-Tools von Drittanbietern. Sollten wir punktuell Analyse-Tools einsetzen (z.B. zur Performance-Messung), erfolgt dies ausschließlich nach Ihrer expliziten Einwilligung im Cookie-Banner.
                        </p>
</div>
</section>
</div>
</div>
</main>
<!-- Footer Component -->
<footer class="bg-stone-100 dark:bg-stone-950 w-full py-12 border-t border-stone-200 dark:border-stone-800">
<div class="grid grid-cols-1 md:grid-cols-2 gap-8 px-8 max-w-7xl mx-auto">
<div class="space-y-4">
<div class="text-lg font-bold text-[#1b1c1c] dark:text-stone-200 font-headline uppercase">MR-CREW</div>
<p class="text-[#5f5e5e] dark:text-stone-500 font-body text-sm tracking-wide max-w-sm">
                    © 2024 MR-CREW Facility Management. All rights reserved. Precision in Motion.
                </p>
</div>
<div class="flex flex-wrap gap-x-8 gap-y-4 items-center md:justify-end">
<a class="text-[#5f5e5e] dark:text-stone-500 hover:text-[#005ea3] text-sm font-label transition-colors" href="#">Impressum</a>
<a class="text-[#005ea3] underline text-sm font-label" href="#">Datenschutz</a>
<a class="text-[#5f5e5e] dark:text-stone-500 hover:text-[#005ea3] text-sm font-label transition-colors" href="#">AGB</a>
<a class="text-[#5f5e5e] dark:text-stone-500 hover:text-[#005ea3] text-sm font-label transition-colors" href="#">Cookie Settings</a>
</div>
</div>
</footer>
</body></html>
