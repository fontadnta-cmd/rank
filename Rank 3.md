<!DOCTYPE html>

<html class="light" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Booking - Date &amp; Time</title>
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
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }
    </style>
<style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
  </head>
<body class="bg-surface-container-lowest text-on-background min-h-screen font-body-md selection:bg-primary-container selection:text-on-primary antialiased flex flex-col">
<!-- TopAppBar -->
<header class="fixed top-0 left-0 w-full z-50 flex justify-between items-center px-container-margin py-md bg-surface-container-lowest/90 backdrop-blur-xl border-b border-outline-variant/30">
<button aria-label="Go back" class="w-10 h-10 flex items-center justify-center text-primary active:scale-95 duration-200">
<span class="material-symbols-outlined" style="font-variation-settings: 'FILL' 0;">arrow_back</span>
</button>
<h1 class="font-headline-md text-headline-md text-primary font-bold">DermClinical</h1>
<div class="w-10 h-10 flex items-center justify-center text-primary">
<!-- Empty placeholder to balance flex-between -->
</div>
</header>
<!-- Main Content Canvas -->
<main class="flex-grow pt-[72px] pb-[100px] md:pb-[24px]">
<!-- Progress Bar -->
<div class="w-full h-1 bg-surface-container-high">
<div class="h-full bg-primary-container w-1/2 transition-all duration-500"></div>
</div>
<div class="max-w-screen-md mx-auto px-container-margin py-lg space-y-xl">
<!-- Step Header -->
<div class="text-center space-y-sm">
<span class="font-label-md text-label-md text-secondary uppercase tracking-widest">Step 2 of 4</span>
<h2 class="font-headline-lg-mobile text-headline-lg-mobile md:font-headline-lg md:text-headline-lg text-on-surface">Select Date &amp; Time</h2>
</div>
<!-- Date Picker Section -->
<section class="space-y-md">
<div class="flex justify-between items-center">
<h3 class="font-label-md text-label-md text-on-surface-variant font-semibold">September 2023</h3>
<div class="flex gap-sm">
<button class="w-8 h-8 rounded-full flex items-center justify-center bg-surface-container-low text-secondary hover:bg-surface-container-high transition-colors"><span class="material-symbols-outlined text-[20px]">chevron_left</span></button>
<button class="w-8 h-8 rounded-full flex items-center justify-center bg-surface-container-low text-secondary hover:bg-surface-container-high transition-colors"><span class="material-symbols-outlined text-[20px]">chevron_right</span></button>
</div>
</div>
<!-- Horizontal Scroll Calendar -->
<div class="flex overflow-x-auto no-scrollbar snap-x snap-mandatory gap-sm pb-xs -mx-container-margin px-container-margin">
<!-- Date Cards -->
<button class="snap-start shrink-0 w-[64px] h-[80px] rounded-lg flex flex-col items-center justify-center border border-outline-variant/50 bg-surface-container-lowest text-on-surface hover:border-primary-container/50 transition-colors">
<span class="font-label-sm text-label-sm text-secondary">Mon</span>
<span class="font-headline-md text-headline-md">11</span>
</button>
<button class="snap-start shrink-0 w-[64px] h-[80px] rounded-lg flex flex-col items-center justify-center border border-outline-variant/50 bg-surface-container-lowest text-on-surface hover:border-primary-container/50 transition-colors">
<span class="font-label-sm text-label-sm text-secondary">Tue</span>
<span class="font-headline-md text-headline-md">12</span>
</button>
<!-- Selected Date -->
<button class="snap-start shrink-0 w-[64px] h-[80px] rounded-lg flex flex-col items-center justify-center bg-primary-container text-on-primary shadow-[0_4px_20px_rgba(198,142,117,0.25)] transition-all transform scale-105">
<span class="font-label-sm text-label-sm text-on-primary/80">Wed</span>
<span class="font-headline-md text-headline-md font-semibold">13</span>
</button>
<button class="snap-start shrink-0 w-[64px] h-[80px] rounded-lg flex flex-col items-center justify-center border border-outline-variant/50 bg-surface-container-lowest text-on-surface hover:border-primary-container/50 transition-colors">
<span class="font-label-sm text-label-sm text-secondary">Thu</span>
<span class="font-headline-md text-headline-md">14</span>
</button>
<button class="snap-start shrink-0 w-[64px] h-[80px] rounded-lg flex flex-col items-center justify-center border border-outline-variant/50 bg-surface-container-lowest text-on-surface hover:border-primary-container/50 transition-colors">
<span class="font-label-sm text-label-sm text-secondary">Fri</span>
<span class="font-headline-md text-headline-md">15</span>
</button>
<button class="snap-start shrink-0 w-[64px] h-[80px] rounded-lg flex flex-col items-center justify-center border border-outline-variant/50 bg-surface-container-lowest text-on-surface hover:border-primary-container/50 transition-colors">
<span class="font-label-sm text-label-sm text-secondary">Sat</span>
<span class="font-headline-md text-headline-md">16</span>
</button>
<button class="snap-start shrink-0 w-[64px] h-[80px] rounded-lg flex flex-col items-center justify-center border border-outline-variant/30 bg-surface-container-low text-tertiary-fixed-dim cursor-not-allowed">
<span class="font-label-sm text-label-sm">Sun</span>
<span class="font-headline-md text-headline-md">17</span>
</button>
</div>
</section>
<!-- Time Slots Section -->
<section class="space-y-md">
<h3 class="font-label-md text-label-md text-on-surface-variant font-semibold">Available Time</h3>
<div class="grid grid-cols-3 gap-bento-gap">
<!-- Time Buttons -->
<button class="h-12 rounded-full border border-outline-variant/50 bg-surface-container-lowest text-on-surface font-label-md text-label-md hover:border-primary-container hover:text-primary-container transition-colors flex items-center justify-center">
                        09:00 AM
                    </button>
<button class="h-12 rounded-full border border-outline-variant/50 bg-surface-container-lowest text-on-surface font-label-md text-label-md hover:border-primary-container hover:text-primary-container transition-colors flex items-center justify-center">
                        09:30 AM
                    </button>
<button class="h-12 rounded-full border border-outline-variant/50 bg-surface-container-lowest text-on-surface font-label-md text-label-md hover:border-primary-container hover:text-primary-container transition-colors flex items-center justify-center">
                        10:00 AM
                    </button>
<!-- Selected Time -->
<button class="h-12 rounded-full bg-primary-container text-on-primary font-label-md text-label-md shadow-[0_4px_20px_rgba(198,142,117,0.15)] flex items-center justify-center">
                        10:30 AM
                    </button>
<button class="h-12 rounded-full border border-outline-variant/50 bg-surface-container-lowest text-on-surface font-label-md text-label-md hover:border-primary-container hover:text-primary-container transition-colors flex items-center justify-center">
                        11:00 AM
                    </button>
<button class="h-12 rounded-full border border-outline-variant/50 bg-surface-container-lowest text-on-surface font-label-md text-label-md hover:border-primary-container hover:text-primary-container transition-colors flex items-center justify-center">
                        11:30 AM
                    </button>
<button class="h-12 rounded-full border border-outline-variant/50 bg-surface-container-lowest text-on-surface font-label-md text-label-md hover:border-primary-container hover:text-primary-container transition-colors flex items-center justify-center">
                        01:00 PM
                    </button>
<button class="h-12 rounded-full border border-outline-variant/50 bg-surface-container-lowest text-on-surface font-label-md text-label-md hover:border-primary-container hover:text-primary-container transition-colors flex items-center justify-center">
                        01:30 PM
                    </button>
<button class="h-12 rounded-full border border-outline-variant/30 bg-surface-container-low text-tertiary-fixed-dim font-label-md text-label-md cursor-not-allowed flex items-center justify-center line-through decoration-1">
                        02:00 PM
                    </button>
</div>
</section>
</div>
</main>
<!-- Bottom Action Bar (Contextual for Booking) -->
<div class="fixed bottom-0 left-0 w-full z-40 bg-surface-container-lowest/90 backdrop-blur-xl border-t border-outline-variant/20 px-container-margin py-md flex items-center justify-between shadow-[0_-4px_20px_rgba(0,0,0,0.04)] pb-safe">
<div class="flex flex-col">
<span class="font-label-sm text-label-sm text-secondary">Selected</span>
<span class="font-label-md text-label-md text-on-surface">Wed 13, 10:30 AM</span>
</div>
<button class="bg-primary-container text-on-primary font-label-md text-label-md px-lg py-sm rounded-full shadow-[0_4px_20px_rgba(198,142,117,0.15)] active:scale-95 transition-all">
            Continue
        </button>
</div>
</body></html>