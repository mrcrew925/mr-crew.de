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
