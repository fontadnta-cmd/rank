<!DOCTYPE html>

<html class="light" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Booking - Step 1: Select Service</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;600;700&amp;family=Inter:wght@400;500;600&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "on-secondary-fixed-variant": "#484745",
                        "tertiary": "#5f5e5e",
                        "inverse-primary": "#f6b99e",
                        "tertiary-fixed": "#e5e2e1",
                        "on-error-container": "#93000a",
                        "on-tertiary-fixed": "#1c1b1b",
                        "tertiary-fixed-dim": "#c8c6c5",
                        "on-tertiary": "#ffffff",
                        "surface-container-highest": "#e2e2e2",
                        "on-secondary": "#ffffff",
                        "on-error": "#ffffff",
                        "secondary-container": "#e5e2df",
                        "error-container": "#ffdad6",
                        "surface": "#f9f9f9",
                        "on-tertiary-fixed-variant": "#474746",
                        "surface-tint": "#82533d",
                        "primary-container": "#c68e75",
                        "surface-container": "#eeeeee",
                        "on-primary-container": "#4f2916",
                        "tertiary-container": "#9c9a9a",
                        "outline": "#84746d",
                        "surface-dim": "#dadada",
                        "surface-container-high": "#e8e8e8",
                        "outline-variant": "#d6c3bb",
                        "on-primary": "#ffffff",
                        "surface-variant": "#e2e2e2",
                        "inverse-on-surface": "#f0f1f1",
                        "secondary": "#605e5c",
                        "primary-fixed": "#ffdbcc",
                        "on-secondary-fixed": "#1c1b1a",
                        "surface-container-lowest": "#ffffff",
                        "secondary-fixed-dim": "#c9c6c3",
                        "surface-bright": "#f9f9f9",
                        "on-tertiary-container": "#333232",
                        "inverse-surface": "#2f3131",
                        "on-surface": "#1a1c1c",
                        "surface-container-low": "#f3f3f4",
                        "on-background": "#1a1c1c",
                        "on-primary-fixed": "#321203",
                        "on-primary-fixed-variant": "#673c28",
                        "on-secondary-container": "#666462",
                        "background": "#f9f9f9",
                        "error": "#ba1a1a",
                        "primary-fixed-dim": "#f6b99e",
                        "primary": "#82533d",
                        "on-surface-variant": "#51443e",
                        "secondary-fixed": "#e5e2df"
                    },
                    "borderRadius": {
                        "DEFAULT": "0.25rem",
                        "lg": "0.5rem",
                        "xl": "0.75rem",
                        "full": "9999px"
                    },
                    "spacing": {
                        "sm": "8px",
                        "lg": "24px",
                        "md": "16px",
                        "unit": "4px",
                        "xs": "4px",
                        "xl": "40px",
                        "bento-gap": "12px",
                        "container-margin": "20px"
                    },
                    "fontFamily": {
                        "display-lg": ["Playfair Display"],
                        "headline-lg": ["Playfair Display"],
                        "headline-lg-mobile": ["Playfair Display"],
                        "body-lg": ["Inter"],
                        "body-md": ["Inter"],
                        "headline-md": ["Playfair Display"],
                        "label-md": ["Inter"],
                        "label-sm": ["Inter"]
                    },
                    "fontSize": {
                        "display-lg": ["40px", { "lineHeight": "1.2", "letterSpacing": "-0.02em", "fontWeight": "700" }],
                        "headline-lg": ["32px", { "lineHeight": "1.3", "fontWeight": "600" }],
                        "headline-lg-mobile": ["28px", { "lineHeight": "1.3", "fontWeight": "600" }],
                        "body-lg": ["18px", { "lineHeight": "1.6", "fontWeight": "400" }],
                        "body-md": ["16px", { "lineHeight": "1.6", "fontWeight": "400" }],
                        "headline-md": ["24px", { "lineHeight": "1.4", "fontWeight": "500" }],
                        "label-md": ["14px", { "lineHeight": "1.2", "letterSpacing": "0.05em", "fontWeight": "600" }],
                        "label-sm": ["12px", { "lineHeight": "1.2", "fontWeight": "500" }]
                    }
                }
            }
        }
    </script>
<style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
  </head>
<body class="bg-surface-container-lowest text-on-surface antialiased min-h-screen flex flex-col pt-[72px] pb-[96px] md:pb-0">
<!-- TopAppBar -->
<header class="fixed top-0 left-0 w-full z-50 flex justify-between items-center px-container-margin py-md bg-surface-container-lowest/80 backdrop-blur-xl border-b border-outline-variant/30 flat no shadows">
<div class="flex items-center gap-sm cursor-pointer hover:bg-primary-container/20 transition-colors rounded-full p-2 active:scale-95 duration-200">
<span class="material-symbols-outlined text-primary" data-icon="arrow_back">arrow_back</span>
</div>
<h1 class="font-headline-md text-headline-md text-primary font-bold">DermClinical</h1>
<div class="flex items-center gap-sm">
<span class="material-symbols-outlined text-primary text-[28px]" data-icon="medical_services">medical_services</span>
</div>
</header>
<!-- Progress Indicator -->
<div class="w-full px-container-margin py-md mt-md">
<div class="flex justify-between items-center mb-xs">
<span class="font-label-sm text-label-sm text-secondary">Step 1 of 4</span>
<span class="font-label-sm text-label-sm text-primary font-bold">Select Service</span>
</div>
<div class="w-full h-[2px] bg-surface-container rounded-full overflow-hidden">
<div class="h-full bg-primary-container w-1/4 rounded-full transition-all duration-500"></div>
</div>
</div>
<!-- Main Content Canvas -->
<main class="flex-grow px-container-margin w-full max-w-7xl mx-auto flex flex-col mt-md">
<div class="mb-xl">
<h2 class="font-headline-lg-mobile md:font-headline-lg text-headline-lg-mobile md:text-headline-lg text-on-surface mb-xs">What brings you in today?</h2>
<p class="font-body-lg text-body-lg text-on-surface-variant">Select a primary service to begin your booking process.</p>
</div>
<!-- Bento Grid / Cards -->
<div class="grid grid-cols-1 md:grid-cols-3 gap-bento-gap w-full">
<!-- Card 1: Acne Check -->
<button class="bg-surface-container-lowest border border-primary-container rounded-[16px] p-[20px] flex flex-col items-start text-left shadow-[0_4px_20px_rgba(0,0,0,0.04)] hover:shadow-[0_8px_24px_rgba(198,142,117,0.15)] transition-all duration-300 group focus:outline-none focus:ring-2 focus:ring-primary-container focus:ring-offset-2 aspect-square md:aspect-auto md:h-full">
<div class="w-12 h-12 rounded-full bg-surface-container flex items-center justify-center mb-auto group-hover:bg-primary-container/10 transition-colors">
<span class="material-symbols-outlined text-primary" data-icon="search" style="font-variation-settings: 'wght' 300;">search</span>
</div>
<div class="mt-lg">
<h3 class="font-headline-md text-headline-md text-on-surface mb-xs group-hover:text-primary transition-colors">Acne Check</h3>
<p class="font-body-md text-body-md text-on-surface-variant line-clamp-2">Comprehensive evaluation and personalized treatment plan for clear skin.</p>
</div>
</button>
<!-- Card 2: Glow Facials -->
<button class="bg-surface-container-lowest border border-outline-variant hover:border-primary-container rounded-[16px] p-[20px] flex flex-col items-start text-left shadow-[0_4px_20px_rgba(0,0,0,0.04)] hover:shadow-[0_8px_24px_rgba(198,142,117,0.15)] transition-all duration-300 group focus:outline-none focus:ring-2 focus:ring-primary-container focus:ring-offset-2 aspect-square md:aspect-auto md:h-full">
<div class="w-12 h-12 rounded-full bg-surface-container flex items-center justify-center mb-auto group-hover:bg-primary-container/10 transition-colors">
<span class="material-symbols-outlined text-primary" data-icon="spa" style="font-variation-settings: 'wght' 300;">spa</span>
</div>
<div class="mt-lg">
<h3 class="font-headline-md text-headline-md text-on-surface mb-xs group-hover:text-primary transition-colors">Glow Facials</h3>
<p class="font-body-md text-body-md text-on-surface-variant line-clamp-2">Revitalizing treatments designed to restore your skin's natural radiance.</p>
</div>
</button>
<!-- Card 3: Mole Scan -->
<button class="bg-surface-container-lowest border border-outline-variant hover:border-primary-container rounded-[16px] p-[20px] flex flex-col items-start text-left shadow-[0_4px_20px_rgba(0,0,0,0.04)] hover:shadow-[0_8px_24px_rgba(198,142,117,0.15)] transition-all duration-300 group focus:outline-none focus:ring-2 focus:ring-primary-container focus:ring-offset-2 aspect-square md:aspect-auto md:h-full">
<div class="w-12 h-12 rounded-full bg-surface-container flex items-center justify-center mb-auto group-hover:bg-primary-container/10 transition-colors">
<span class="material-symbols-outlined text-primary" data-icon="center_focus_strong" style="font-variation-settings: 'wght' 300;">center_focus_strong</span>
</div>
<div class="mt-lg">
<h3 class="font-headline-md text-headline-md text-on-surface mb-xs group-hover:text-primary transition-colors">Mole Scan</h3>
<p class="font-body-md text-body-md text-on-surface-variant line-clamp-2">Detailed full-body mapping and clinical assessment for peace of mind.</p>
</div>
</button>
</div>
<!-- Sticky Bottom Action (Mobile) / Regular Action (Desktop) -->
<div class="mt-auto pt-xl w-full flex justify-end">
<button class="bg-primary-container text-on-primary font-label-md text-label-md py-3 px-6 rounded-full hover:bg-primary transition-colors shadow-[0_4px_12px_rgba(198,142,117,0.2)] w-full md:w-auto">
                 Continue
             </button>
</div>
</main>
<!-- Navigation Suppressed: Transactional Step-by-Step Flow -->
</body></html>