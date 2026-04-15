<!-- Elevify Landing Page -->
<!DOCTYPE html>

<html class="dark" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Elevify | Unlock the Secrets of Your Soul</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Noto+Serif:ital,wght@0,400;0,700;1,400&amp;family=Manrope:wght@300;400;500;700;800&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "outline": "#978d9d",
                        "secondary": "#ddb7ff",
                        "surface-bright": "#39374d",
                        "inverse-on-surface": "#302e44",
                        "on-tertiary-fixed-variant": "#8d004e",
                        "tertiary-container": "#660037",
                        "on-surface-variant": "#cec3d3",
                        "on-secondary-container": "#d1a1ff",
                        "primary-container": "#4a0084",
                        "on-error-container": "#ffdad6",
                        "surface-tint": "#dcb8ff",
                        "primary-fixed": "#efdbff",
                        "surface-container-high": "#2a273d",
                        "primary": "#dcb8ff",
                        "surface-container-low": "#1b192e",
                        "surface-container-highest": "#353248",
                        "inverse-primary": "#8422dc",
                        "on-tertiary": "#640036",
                        "on-secondary-fixed-variant": "#622599",
                        "inverse-surface": "#e4dffc",
                        "on-surface": "#e4dffc",
                        "surface": "#131125",
                        "on-secondary-fixed": "#2c0050",
                        "error": "#ffb4ab",
                        "on-primary": "#480081",
                        "on-background": "#e4dffc",
                        "surface-dim": "#131125",
                        "secondary-fixed-dim": "#ddb7ff",
                        "background": "#131125",
                        "tertiary-fixed": "#ffd9e3",
                        "on-primary-fixed-variant": "#6700b5",
                        "tertiary-fixed-dim": "#ffb0ca",
                        "on-primary-container": "#bb7bff",
                        "secondary-fixed": "#f0dbff",
                        "surface-variant": "#353248",
                        "on-tertiary-fixed": "#3e001f",
                        "secondary-container": "#622599",
                        "error-container": "#93000a",
                        "on-secondary": "#4a0080",
                        "on-primary-fixed": "#2c0051",
                        "on-tertiary-container": "#ff5ea3",
                        "outline-variant": "#4c4451",
                        "on-error": "#690005",
                        "surface-container-lowest": "#0e0c20",
                        "tertiary": "#ffb0ca",
                        "primary-fixed-dim": "#dcb8ff",
                        "surface-container": "#1f1d32"
                    },
                    "borderRadius": {
                        "DEFAULT": "0.25rem",
                        "lg": "0.5rem",
                        "xl": "0.75rem",
                        "full": "9999px"
                    },
                    "fontFamily": {
                        "headline": ["Noto Serif"],
                        "body": ["Manrope"],
                        "label": ["Manrope"]
                    }
                }
            }
        }
    </script>
<style>
        body {
            font-family: 'Manrope', sans-serif;
            background-color: #131125;
            color: #e4dffc;
            scroll-behavior: smooth;
        }
        .glass-panel {
            background: rgba(53, 50, 72, 0.4);
            backdrop-filter: blur(20px);
            border: 1px solid rgba(151, 141, 157, 0.1);
        }
        .hero-gradient {
            background: radial-gradient(circle at top right, rgba(98, 37, 153, 0.3), transparent 50%),
                        radial-gradient(circle at bottom left, rgba(74, 0, 132, 0.2), transparent 50%);
        }
    </style>
</head>
<body class="bg-surface text-on-surface overflow-x-hidden">
<!-- Top Navigation -->
<nav class="fixed top-0 w-full z-50 bg-transparent backdrop-blur-xl bg-opacity-60 shadow-2xl shadow-indigo-900/20">
<div class="flex justify-between items-center max-w-7xl mx-auto px-8 h-20">
<div class="text-2xl font-bold tracking-tighter text-white dark:text-purple-50 font-headline">Elevify</div>
<div class="hidden md:flex items-center space-x-8">
<a class="text-white border-b-2 border-purple-400 pb-1 font-['Noto_Serif'] text-lg tracking-tight" href="#">Features</a>
<a class="text-purple-200/70 hover:text-white transition-colors font-['Noto_Serif'] text-lg tracking-tight" href="#">Methodology</a>
<a class="text-purple-200/70 hover:text-white transition-colors font-['Noto_Serif'] text-lg tracking-tight" href="#">Universe</a>
<a class="text-purple-200/70 hover:text-white transition-colors font-['Noto_Serif'] text-lg tracking-tight" href="#">Pricing</a>
</div>
<div class="flex items-center space-x-6">
<span class="material-symbols-outlined text-purple-200 cursor-pointer hover:bg-white/10 p-2 rounded-lg transition-all" data-icon="star_rate">star_rate</span>
<button class="bg-gradient-to-br from-primary to-primary-container text-on-primary px-6 py-2.5 rounded-xl font-bold transition-transform scale-95 active:opacity-80 shadow-[0_0_20px_rgba(220,184,255,0.3)]">
                    Begin Journey
                </button>
</div>
</div>
</nav>
<!-- Hero Section -->
<header class="relative min-h-screen flex items-center justify-center pt-20 hero-gradient">
<div class="absolute inset-0 z-0">
<img alt="Cosmic background" class="w-full h-full object-cover opacity-30 mix-blend-screen" data-alt="Stunning nebula with swirling deep purple and blue gases, distant glittering stars, and subtle light streaks in a cosmic expanse" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBu951pbfpmMb6o18nc1i5dCNsSTMYMdgy0mOQLr3AtN207jwDX-c9kcEc1go2LLwwx7uQe4LOzwKc2vZCG5h7IZLS-RPNlANu9tNdXbZFEC3PCxwOvH_0QB233yCOTLlllEKeTWHGMMiU0R08mhGTYagzxDt8ex6t6Py9S-aQbeu3MUqxzRv9MJh2Dr4ELz_P_fjLJ7K-HrqDmkOGNB676B2fe9xdECdkpkrIT2e36zWXPw0h2bDklCFsTinN63Ok_Bvm2UuSryDs"/>
</div>
<div class="relative z-10 max-w-5xl mx-auto px-8 text-center">
<span class="inline-block px-4 py-1.5 rounded-full glass-panel text-tertiary text-xs font-bold tracking-[0.2em] uppercase mb-8 border border-outline-variant/20">
                Ascend Your Spirit
            </span>
<h1 class="text-6xl md:text-8xl font-headline font-bold text-white tracking-tighter leading-[1.1] mb-8">
                Unlock the Secrets <br/> of Your <span class="text-transparent bg-clip-text bg-gradient-to-r from-secondary via-primary to-tertiary">Soul</span>
</h1>
<p class="text-lg md:text-xl text-on-surface-variant font-body max-w-2xl mx-auto mb-12 leading-relaxed">
                Experience a revolutionary synthesis of ancient celestial wisdom and next-generation neural intelligence designed to illuminate your path.
            </p>
<div class="flex flex-col sm:flex-row items-center justify-center gap-6">
<button class="w-full sm:w-auto bg-gradient-to-br from-primary to-primary-container text-on-primary px-10 py-4 rounded-xl font-bold text-lg hover:shadow-[0_0_30px_rgba(220,184,255,0.4)] transition-all transform hover:-translate-y-1">
                    Begin Journey
                </button>
<button class="w-full sm:w-auto glass-panel text-white px-10 py-4 rounded-xl font-bold text-lg border border-outline-variant/30 hover:bg-white/5 transition-all">
                    Explore Universe
                </button>
</div>
</div>
</header>
<!-- Features Bento Grid -->
<section class="py-32 px-8 max-w-7xl mx-auto">
<div class="mb-20">
<span class="text-tertiary font-bold tracking-widest text-sm uppercase">The Oracle Suite</span>
<h2 class="text-4xl md:text-5xl font-headline font-bold mt-4">Transcendental Features</h2>
</div>
<div class="grid grid-cols-1 md:grid-cols-12 gap-8">
<!-- Feature 1: AI Therapy -->
<div class="md:col-span-8 group relative overflow-hidden rounded-[2.5rem] bg-surface-container-low min-h-[450px] flex flex-col justify-end p-10">
<img alt="AI Therapy Illustration" class="absolute inset-0 w-full h-full object-cover opacity-50 group-hover:scale-105 transition-transform duration-700" data-alt="Abstract ethereal silhouette of a human head filled with glowing neural connections and soft purple particles on a dark background" src="https://lh3.googleusercontent.com/aida-public/AB6AXuC5wnaQao6282va46t6cyUfrcP8b3FapBemqdDwLksP6-_BOotAasEQXDYDfk0AOu4RgU4z_t0asSlZA_tybmKJLFIsQav-1YAD522ZX7yEK-ke1PxwbB7a52O0G9P2vnUFSkXIgHtBB5zQmWWCJWI6ZAPsWZBcGfQjBtDDDDc5bH_niIKPw3KB_dijp-sNx857oiufnNRYR_RvetzFlWV3X-Hm3i0Hhm5ezuBSPjv7QIX0UFv6EAwhJuydQRhdt2Ib9pmX9RGK9SA"/>
<div class="absolute inset-0 bg-gradient-to-t from-surface via-surface/60 to-transparent"></div>
<div class="relative z-10">
<div class="bg-secondary/20 backdrop-blur-md w-14 h-14 rounded-2xl flex items-center justify-center mb-6 border border-secondary/30">
<span class="material-symbols-outlined text-secondary text-3xl" data-icon="psychology">psychology</span>
</div>
<h3 class="text-3xl font-headline font-bold mb-3">AI Therapy</h3>
<p class="text-on-surface-variant max-w-md text-lg">Personalized Soul Guide. An empathetic artificial intelligence trained on diverse psychotherapeutic and spiritual frameworks.</p>
</div>
</div>
<!-- Feature 2: Dream Interpretation -->
<div class="md:col-span-4 group relative overflow-hidden rounded-[2.5rem] bg-surface-container-low p-10 flex flex-col">
<div class="relative z-10">
<div class="bg-tertiary/20 backdrop-blur-md w-14 h-14 rounded-2xl flex items-center justify-center mb-6 border border-tertiary/30">
<span class="material-symbols-outlined text-tertiary text-3xl" data-icon="bedtime">bedtime</span>
</div>
<h3 class="text-2xl font-headline font-bold mb-3">Dream Interpretation</h3>
<p class="text-on-surface-variant text-sm leading-relaxed mb-8">Subconscious Insights. Decode the cryptic symbols of your sleep to unlock hidden messages from your deeper self.</p>
</div>
<div class="mt-auto h-48 relative rounded-2xl overflow-hidden border border-outline-variant/10">
<img alt="Dream Imagery" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-1000" data-alt="Surreal landscape with floating islands and a giant moon reflected in a calm dark lake at night with ethereal mist" src="https://lh3.googleusercontent.com/aida-public/AB6AXuD_sIQQrp_xXfNh2mPOeD6xUUuLFYxcgAIJgfyz4JCx7NOaI97-NvjPfvt5y15PrHcG9RPANd_UCx1OStY-pZRiGVWo0WZEHB2y9xM8Err1UOYvJcEM1h5lmGlsH_JeFE7kMvujPx3JI3uDYlXsigpgg9G8mEeVz7v40RZ9cEI6-RglL5TO4ga1IQoGSQ7rOQfLE3eRMVSm_o5YmYyCe7EGqv3IIVqvfi8xsDdcGhri6iiQ8k58Du2-XjAP2CNzXdvnJ8JX4hEKynA"/>
</div>
</div>
<!-- Feature 3: Mood & Horoscope -->
<div class="md:col-span-5 group relative overflow-hidden rounded-[2.5rem] bg-surface-container-low p-10 flex flex-col">
<div class="relative z-10">
<div class="bg-primary/20 backdrop-blur-md w-14 h-14 rounded-2xl flex items-center justify-center mb-6 border border-primary/30">
<span class="material-symbols-outlined text-primary text-3xl" data-icon="auto_awesome">auto_awesome</span>
</div>
<h3 class="text-2xl font-headline font-bold mb-3">Daily Mood &amp; Horoscope</h3>
<p class="text-on-surface-variant text-sm mb-8">Cosmic Alignment. Real-time planetary transit tracking mapped directly to your emotional circadian rhythm.</p>
</div>
<div class="flex-grow flex items-center justify-center">
<div class="w-full h-32 glass-panel rounded-2xl flex items-center justify-around px-6">
<div class="flex flex-col items-center">
<span class="text-xs font-bold text-tertiary uppercase">Moon</span>
<span class="text-xl font-headline">Waxing</span>
</div>
<div class="w-[1px] h-12 bg-outline-variant/20"></div>
<div class="flex flex-col items-center">
<span class="text-xs font-bold text-secondary uppercase">Energy</span>
<span class="text-xl font-headline">88%</span>
</div>
<div class="w-[1px] h-12 bg-outline-variant/20"></div>
<div class="flex flex-col items-center">
<span class="text-xs font-bold text-primary uppercase">Sign</span>
<span class="text-xl font-headline">Leo</span>
</div>
</div>
</div>
</div>
<!-- Feature 4: Palm Reader -->
<div class="md:col-span-7 group relative overflow-hidden rounded-[2.5rem] bg-surface-container-low min-h-[350px] flex items-center p-10">
<div class="absolute inset-0">
<img alt="Palm Reading" class="w-full h-full object-cover opacity-40 group-hover:scale-105 transition-transform duration-700" data-alt="Close up of an open palm with intricate glowing golden lines tracing the life and heart lines against a dark moody background" src="https://lh3.googleusercontent.com/aida-public/AB6AXuA5JEm7bJItek0FQVdkBVU1vvYQeUYiqOLsSZPx5K2SVw2lqRGVWGS61xsv29KGItFLXFxx0KgJjXzMzjjQxmLrGCpclTIOiin8Bc_YTjzhoDXCs6-cXm4tZdrcRhIH5HQ2Lha_eUvIXfcw061o2CQb--p3G9d55xkcYSdw_VUT-FlXPK4okEWDWNRcyPu9rzALsjA4WavLW4g19TMXbPKJTy_FutlWmvOU1MK8AjOvsqKYdclx0khhQ3XGG-4pxnmgpWF978a2StQ"/>
<div class="absolute inset-0 bg-gradient-to-r from-surface-container-low via-surface-container-low/80 to-transparent"></div>
</div>
<div class="relative z-10 max-w-sm">
<div class="bg-secondary-container/30 backdrop-blur-md w-14 h-14 rounded-2xl flex items-center justify-center mb-6 border border-secondary/30">
<span class="material-symbols-outlined text-secondary text-3xl" data-icon="front_hand">front_hand</span>
</div>
<h3 class="text-3xl font-headline font-bold mb-3">Palm Reader</h3>
<p class="text-on-surface-variant text-lg">Written in the Stars. Advanced computer vision technology that reads the unique topography of your hands to reveal destiny markers.</p>
</div>
</div>
</div>
</section>
<!-- Pricing Section -->
<section class="py-32 relative overflow-hidden">
<div class="absolute top-0 left-1/2 -translate-x-1/2 w-[800px] h-[800px] bg-primary/10 blur-[120px] rounded-full -z-10"></div>
<div class="max-w-7xl mx-auto px-8">
<div class="text-center mb-20">
<h2 class="text-4xl md:text-5xl font-headline font-bold mb-6">Subscription Plans</h2>
<p class="text-on-surface-variant text-lg max-w-xl mx-auto">Select the depth of your immersion into the Elevify ecosystem.</p>
</div>
<div class="grid grid-cols-1 md:grid-cols-3 gap-8">
<!-- Star Plan -->
<div class="glass-panel p-10 rounded-[2.5rem] flex flex-col border border-outline-variant/10 hover:border-outline-variant/30 transition-all group">
<div class="mb-8">
<h3 class="text-xl font-bold text-white mb-2">Star</h3>
<div class="flex items-baseline gap-1">
<span class="text-4xl font-headline font-bold">$9</span>
<span class="text-on-surface-variant text-sm">/month</span>
</div>
</div>
<ul class="space-y-4 mb-10 flex-grow">
<li class="flex items-center gap-3 text-on-surface-variant text-sm">
<span class="material-symbols-outlined text-primary text-xl" data-icon="check_circle" style="font-variation-settings: 'FILL' 1;">check_circle</span>
                            Daily Horoscope Analysis
                        </li>
<li class="flex items-center gap-3 text-on-surface-variant text-sm">
<span class="material-symbols-outlined text-primary text-xl" data-icon="check_circle" style="font-variation-settings: 'FILL' 1;">check_circle</span>
                            Standard Dream Logs
                        </li>
<li class="flex items-center gap-3 text-on-surface-variant text-sm">
<span class="material-symbols-outlined text-primary text-xl" data-icon="check_circle" style="font-variation-settings: 'FILL' 1;">check_circle</span>
                            3 Palm Readings / month
                        </li>
</ul>
<button class="w-full py-4 rounded-xl font-bold border border-outline-variant text-white hover:bg-white/5 transition-all">Choose Star</button>
</div>
<!-- Galaxy Plan (Popular) -->
<div class="relative bg-surface-container-highest p-10 rounded-[2.5rem] flex flex-col shadow-[0_20px_50px_rgba(0,0,0,0.5)] border border-primary/20 scale-105 z-10">
<div class="absolute top-0 right-10 -translate-y-1/2 bg-gradient-to-r from-primary to-secondary text-on-primary px-4 py-1.5 rounded-full text-xs font-black tracking-widest uppercase shadow-lg">Most Popular</div>
<div class="mb-8">
<h3 class="text-xl font-bold text-white mb-2">Galaxy</h3>
<div class="flex items-baseline gap-1">
<span class="text-4xl font-headline font-bold">$24</span>
<span class="text-on-surface-variant text-sm">/month</span>
</div>
</div>
<ul class="space-y-4 mb-10 flex-grow">
<li class="flex items-center gap-3 text-on-surface-variant text-sm">
<span class="material-symbols-outlined text-secondary text-xl" data-icon="check_circle" style="font-variation-settings: 'FILL' 1;">check_circle</span>
                            Unlimited AI Therapy Guided
                        </li>
<li class="flex items-center gap-3 text-on-surface-variant text-sm">
<span class="material-symbols-outlined text-secondary text-xl" data-icon="check_circle" style="font-variation-settings: 'FILL' 1;">check_circle</span>
                            Advanced Dream Interpretation
                        </li>
<li class="flex items-center gap-3 text-on-surface-variant text-sm">
<span class="material-symbols-outlined text-secondary text-xl" data-icon="check_circle" style="font-variation-settings: 'FILL' 1;">check_circle</span>
                            Weekly Soul Path Reports
                        </li>
<li class="flex items-center gap-3 text-on-surface-variant text-sm">
<span class="material-symbols-outlined text-secondary text-xl" data-icon="check_circle" style="font-variation-settings: 'FILL' 1;">check_circle</span>
                            Sync with Celestial Events
                        </li>
</ul>
<button class="w-full py-4 rounded-xl font-bold bg-gradient-to-r from-primary to-primary-container text-on-primary hover:shadow-[0_0_20px_rgba(220,184,255,0.4)] transition-all">Begin Galaxy</button>
</div>
<!-- Universe Plan -->
<div class="glass-panel p-10 rounded-[2.5rem] flex flex-col border border-outline-variant/10 hover:border-outline-variant/30 transition-all group">
<div class="mb-8">
<h3 class="text-xl font-bold text-white mb-2">Universe</h3>
<div class="flex items-baseline gap-1">
<span class="text-4xl font-headline font-bold">$49</span>
<span class="text-on-surface-variant text-sm">/month</span>
</div>
</div>
<ul class="space-y-4 mb-10 flex-grow">
<li class="flex items-center gap-3 text-on-surface-variant text-sm">
<span class="material-symbols-outlined text-tertiary text-xl" data-icon="check_circle" style="font-variation-settings: 'FILL' 1;">check_circle</span>
                            Full Oracle Suite Access
                        </li>
<li class="flex items-center gap-3 text-on-surface-variant text-sm">
<span class="material-symbols-outlined text-tertiary text-xl" data-icon="check_circle" style="font-variation-settings: 'FILL' 1;">check_circle</span>
                            1-on-1 Astral Consultation
                        </li>
<li class="flex items-center gap-3 text-on-surface-variant text-sm">
<span class="material-symbols-outlined text-tertiary text-xl" data-icon="check_circle" style="font-variation-settings: 'FILL' 1;">check_circle</span>
                            Historical Lifeline Mapping
                        </li>
</ul>
<button class="w-full py-4 rounded-xl font-bold border border-outline-variant text-white hover:bg-white/5 transition-all">Enter Universe</button>
</div>
</div>
</div>
</section>
<!-- Footer -->
<footer class="bg-[#131125] dark:bg-[#0e0c20] w-full py-12 px-8">
<div class="flex flex-col md:flex-row justify-between items-center max-w-7xl mx-auto gap-8">
<div class="text-xl font-black text-white font-headline">Elevify</div>
<div class="flex flex-wrap justify-center gap-8">
<a class="text-slate-500 hover:text-purple-200 font-['Manrope'] text-sm tracking-wide uppercase transition-all hover:translate-x-1" href="#">Privacy Policy</a>
<a class="text-slate-500 hover:text-purple-200 font-['Manrope'] text-sm tracking-wide uppercase transition-all hover:translate-x-1" href="#">Terms of Service</a>
<a class="text-slate-500 hover:text-purple-200 font-['Manrope'] text-sm tracking-wide uppercase transition-all hover:translate-x-1" href="#">Cosmic Guidelines</a>
<a class="text-slate-500 hover:text-purple-200 font-['Manrope'] text-sm tracking-wide uppercase transition-all hover:translate-x-1" href="#">Contact</a>
</div>
<div class="text-purple-300 dark:text-purple-200 font-['Manrope'] text-xs tracking-widest opacity-80">
                © 2024 Elevify Astral Systems. All rights reserved.
            </div>
</div>
</footer>
</body></html>

<!-- Privacy Policy -->
<!DOCTYPE html>

<html class="dark" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<link href="https://fonts.googleapis.com/css2?family=Noto+Serif:wght@400;700&amp;family=Manrope:wght@300;400;600;800&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            "colors": {
                    "outline": "#978d9d",
                    "secondary": "#ddb7ff",
                    "surface-bright": "#39374d",
                    "inverse-on-surface": "#302e44",
                    "on-tertiary-fixed-variant": "#8d004e",
                    "tertiary-container": "#660037",
                    "on-surface-variant": "#cec3d3",
                    "on-secondary-container": "#d1a1ff",
                    "primary-container": "#4a0084",
                    "on-error-container": "#ffdad6",
                    "surface-tint": "#dcb8ff",
                    "primary-fixed": "#efdbff",
                    "surface-container-high": "#2a273d",
                    "primary": "#dcb8ff",
                    "surface-container-low": "#1b192e",
                    "surface-container-highest": "#353248",
                    "inverse-primary": "#8422dc",
                    "on-tertiary": "#640036",
                    "on-secondary-fixed-variant": "#622599",
                    "inverse-surface": "#e4dffc",
                    "on-surface": "#e4dffc",
                    "surface": "#131125",
                    "on-secondary-fixed": "#2c0050",
                    "error": "#ffb4ab",
                    "on-primary": "#480081",
                    "on-background": "#e4dffc",
                    "surface-dim": "#131125",
                    "secondary-fixed-dim": "#ddb7ff",
                    "background": "#131125",
                    "tertiary-fixed": "#ffd9e3",
                    "on-primary-fixed-variant": "#6700b5",
                    "tertiary-fixed-dim": "#ffb0ca",
                    "on-primary-container": "#bb7bff",
                    "secondary-fixed": "#f0dbff",
                    "surface-variant": "#353248",
                    "on-tertiary-fixed": "#3e001f",
                    "secondary-container": "#622599",
                    "error-container": "#93000a",
                    "on-secondary": "#4a0080",
                    "on-primary-fixed": "#2c0051",
                    "on-tertiary-container": "#ff5ea3",
                    "outline-variant": "#4c4451",
                    "on-error": "#690005",
                    "surface-container-lowest": "#0e0c20",
                    "tertiary": "#ffb0ca",
                    "primary-fixed-dim": "#dcb8ff",
                    "surface-container": "#1f1d32"
            },
            "borderRadius": {
                    "DEFAULT": "0.25rem",
                    "lg": "0.5rem",
                    "xl": "0.75rem",
                    "full": "9999px"
            },
            "fontFamily": {
                    "headline": ["Noto Serif"],
                    "body": ["Manrope"],
                    "label": ["Manrope"]
            }
          },
        },
      }
    </script>
<style>
      .material-symbols-outlined {
        font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
      }
      .glass-card {
        background: rgba(53, 50, 72, 0.6);
        backdrop-filter: blur(20px);
      }
      .aura-glow {
        box-shadow: 0 0 40px rgba(220, 184, 255, 0.1);
      }
    </style>
</head>
<body class="bg-surface text-on-surface font-body selection:bg-primary-container selection:text-primary">
<!-- TopNavBar -->
<nav class="fixed top-0 w-full z-50 bg-transparent backdrop-blur-xl bg-opacity-60 shadow-2xl shadow-indigo-900/20">
<div class="flex justify-between items-center max-w-7xl mx-auto px-8 h-20">
<div class="text-2xl font-bold tracking-tighter text-white dark:text-purple-50 font-headline">
                Elevify
            </div>
<div class="hidden md:flex items-center gap-8">
<a class="font-['Noto_Serif'] text-lg tracking-tight text-purple-200/70 hover:text-white transition-colors" href="#">Features</a>
<a class="font-['Noto_Serif'] text-lg tracking-tight text-purple-200/70 hover:text-white transition-colors" href="#">Methodology</a>
<a class="font-['Noto_Serif'] text-lg tracking-tight text-purple-200/70 hover:text-white transition-colors" href="#">Universe</a>
<a class="font-['Noto_Serif'] text-lg tracking-tight text-purple-200/70 hover:text-white transition-colors" href="#">Pricing</a>
</div>
<div class="flex items-center gap-4">
<span class="material-symbols-outlined text-purple-300 dark:text-purple-200 p-2 hover:bg-white/10 rounded-lg transition-all duration-300 cursor-pointer">star_rate</span>
<button class="bg-gradient-to-br from-primary to-primary-container text-on-primary px-6 py-2 rounded-xl font-semibold scale-95 active:opacity-80 transition-transform shadow-lg shadow-primary/30">
                    Begin Journey
                </button>
</div>
</div>
</nav>
<main class="pt-32 pb-24 px-6 md:px-12 max-w-5xl mx-auto">
<!-- Hero Header -->
<header class="mb-20 text-center md:text-left">
<span class="text-tertiary font-label text-xs uppercase tracking-[0.2em] mb-4 block">Last Updated: October 2024</span>
<h1 class="font-headline text-5xl md:text-7xl font-bold text-white tracking-tighter leading-tight mb-6">
                Privacy of the <span class="text-transparent bg-clip-text bg-gradient-to-r from-primary to-secondary">Cosmic Mind</span>
</h1>
<p class="text-on-surface-variant text-lg md:text-xl max-w-2xl leading-relaxed">
                At Elevify, your ethereal essence and digital footprint are guarded with celestial precision. We believe your subconscious is your most sacred sanctuary.
            </p>
</header>
<!-- Data Collection Section -->
<section class="mb-24">
<div class="flex flex-col md:flex-row gap-12 items-start">
<div class="w-full md:w-1/3">
<h2 class="font-headline text-3xl font-bold text-primary mb-4">Data Collection</h2>
<p class="text-on-surface-variant leading-relaxed">The fragments we gather to weave your astral map.</p>
</div>
<div class="w-full md:w-2/3 grid grid-cols-1 gap-6">
<div class="surface-container-low p-8 rounded-2xl aura-glow">
<div class="flex items-start gap-6">
<div class="bg-primary-container/30 p-3 rounded-xl">
<span class="material-symbols-outlined text-primary text-3xl">nights_stay</span>
</div>
<div>
<h3 class="text-xl font-bold text-white mb-2">Dreams &amp; Subconscious Inputs</h3>
<p class="text-on-surface-variant">We collect narrative descriptions, emotional tones, and recurring symbols from your dream journals to decode latent patterns.</p>
</div>
</div>
</div>
<div class="surface-container-low p-8 rounded-2xl aura-glow">
<div class="flex items-start gap-6">
<div class="bg-secondary-container/30 p-3 rounded-xl">
<span class="material-symbols-outlined text-secondary text-3xl">temp_preferences_custom</span>
</div>
<div>
<h3 class="text-xl font-bold text-white mb-2">Mood &amp; Biometric Resonance</h3>
<p class="text-on-surface-variant">Real-time emotional states and physiological indicators are synchronized to align your physical self with your astral trajectory.</p>
</div>
</div>
</div>
<div class="surface-container-low p-8 rounded-2xl aura-glow">
<div class="flex items-start gap-6">
<div class="bg-tertiary-container/30 p-3 rounded-xl">
<span class="material-symbols-outlined text-tertiary text-3xl">pan_tool</span>
</div>
<div>
<h3 class="text-xl font-bold text-white mb-2">Palm Scans &amp; Geometry</h3>
<p class="text-on-surface-variant">Unique hand topography is analyzed to create a secure, immutable biometric anchor for your Elevify profile.</p>
</div>
</div>
</div>
</div>
</div>
</section>
<!-- AI Processing Section (Bento Style) -->
<section class="mb-24 py-16 px-8 rounded-[2rem] bg-surface-container-lowest border border-outline-variant/20">
<h2 class="font-headline text-4xl font-bold text-center text-white mb-12">AI Processing &amp; Therapy</h2>
<div class="grid grid-cols-1 md:grid-cols-3 gap-8">
<div class="glass-card p-8 rounded-3xl col-span-1 md:col-span-2">
<h3 class="text-2xl font-bold text-primary mb-4">Neural Archetyping</h3>
<p class="text-on-surface-variant mb-6 leading-relaxed">
                        Our proprietary AI, *Aether-1*, processes your data through a 12-dimensional archetypal filter. This transforms raw inputs into actionable therapeutic insights, identifying blocks in your creative or emotional energy without exposing your raw identity.
                    </p>
<img class="w-full h-48 object-cover rounded-2xl opacity-60" data-alt="Abstract fluid visualization of flowing purple and blue energy waves representing neural pathways in a dark void" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAgQBV73CPmIJF4BL1m96V-Z1KzkK9h4bVDn4kX7AyiMyJfBEreh6H__aoBTfCFPkFGr-ooXQQEER-o3S6YN4a2tvBVnrvU83nTz_Fy-kKE5UTsuRFi3FJEgbcZOc0l2WgpxWcMSrPDvppAMI_V6zDA3KLjn2uQeRCaRTrki30oNTWC9PADEzFkPPimpYdkDC3HRSPDGKGx0l8hnOy-HB2wwZ09UGdytC_R6rJlbj5KlNCzufTdxHMJEZnWce83Df7NHnVdYt91f7k"/>
</div>
<div class="surface-container-high p-8 rounded-3xl flex flex-col justify-between">
<div>
<h3 class="text-2xl font-bold text-secondary mb-4">Anonymization</h3>
<p class="text-on-surface-variant">Every byte of data is stripped of PII (Personally Identifiable Information) before it reaches our processing clusters.</p>
</div>
<div class="mt-8 pt-8 border-t border-outline-variant/30">
<span class="text-4xl font-black text-white/10">0101001</span>
</div>
</div>
</div>
</section>
<!-- Data Security & User Rights -->
<div class="grid grid-cols-1 md:grid-cols-2 gap-12">
<section>
<div class="flex items-center gap-3 mb-6">
<span class="material-symbols-outlined text-tertiary">security</span>
<h2 class="font-headline text-3xl font-bold text-white">Data Security</h2>
</div>
<div class="space-y-6 text-on-surface-variant leading-relaxed">
<p>Elevify utilizes 4096-bit quantum-resistant encryption. Your data is stored in decentralized "Celestial Nodes" across three continents, ensuring that no single physical failure or breach can compromise your privacy.</p>
<div class="p-4 rounded-xl bg-surface-container-high border-l-4 border-primary">
<p class="text-sm italic">"We treat your data as if it were our own consciousness—infinite and invaluable."</p>
</div>
</div>
</section>
<section>
<div class="flex items-center gap-3 mb-6">
<span class="material-symbols-outlined text-primary">key</span>
<h2 class="font-headline text-3xl font-bold text-white">User Rights</h2>
</div>
<ul class="space-y-4">
<li class="flex items-start gap-3">
<span class="material-symbols-outlined text-secondary text-sm mt-1">check_circle</span>
<span class="text-on-surface-variant"><strong>The Right to Oblivion:</strong> Request total data erasure at any time.</span>
</li>
<li class="flex items-start gap-3">
<span class="material-symbols-outlined text-secondary text-sm mt-1">check_circle</span>
<span class="text-on-surface-variant"><strong>Portal Access:</strong> Download a full transcript of your astral journey data.</span>
</li>
<li class="flex items-start gap-3">
<span class="material-symbols-outlined text-secondary text-sm mt-1">check_circle</span>
<span class="text-on-surface-variant"><strong>The Aura Lock:</strong> Disable specific sensors (like Palm Scans) without losing app functionality.</span>
</li>
</ul>
</section>
</div>
<!-- Contact/Inquiry CTA -->
<div class="mt-24 p-12 rounded-[3rem] bg-gradient-to-br from-surface-container-low to-surface text-center">
<h2 class="font-headline text-3xl font-bold text-white mb-4">Curious about your data?</h2>
<p class="text-on-surface-variant mb-8">Our Privacy Guardians are standing by in the astral plane.</p>
<button class="bg-white/5 hover:bg-white/10 text-primary border border-primary/30 px-8 py-3 rounded-full font-bold transition-all duration-300">
                Contact Data Guardians
            </button>
</div>
</main>
<!-- Footer -->
<footer class="bg-[#131125] dark:bg-[#0e0c20] w-full py-12 px-8">
<div class="flex flex-col md:flex-row justify-between items-center max-w-7xl mx-auto gap-8">
<div class="text-xl font-black text-white font-headline">
                Elevify
            </div>
<div class="flex flex-wrap justify-center gap-8">
<a class="font-['Manrope'] text-sm tracking-wide uppercase text-slate-500 hover:text-purple-200 hover:translate-x-1 transition-transform duration-200" href="#">Privacy Policy</a>
<a class="font-['Manrope'] text-sm tracking-wide uppercase text-slate-500 hover:text-purple-200 hover:translate-x-1 transition-transform duration-200" href="#">Terms of Service</a>
<a class="font-['Manrope'] text-sm tracking-wide uppercase text-slate-500 hover:text-purple-200 hover:translate-x-1 transition-transform duration-200" href="#">Cosmic Guidelines</a>
<a class="font-['Manrope'] text-sm tracking-wide uppercase text-slate-500 hover:text-purple-200 hover:translate-x-1 transition-transform duration-200" href="#">Contact</a>
</div>
<div class="font-['Manrope'] text-sm tracking-wide uppercase text-purple-300 dark:text-purple-200 opacity-80">
                © 2024 Elevify Astral Systems. All rights reserved.
            </div>
</div>
</footer>
</body></html>