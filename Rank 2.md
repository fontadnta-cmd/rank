<!DOCTYPE html>

<html lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>DermClinical - Booking Confirmation</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&amp;family=Playfair+Display:wght@500;600;700&amp;display=swap" rel="stylesheet"/>
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
<body class="bg-surface-container-lowest text-on-surface font-body-md h-screen flex flex-col antialiased">
<!-- Top Navigation (Transactional - No shell nav) -->
<header class="bg-surface/80 dark:bg-surface-dim/80 backdrop-blur-xl fixed top-0 left-0 w-full z-50 flex justify-between items-center px-container-margin py-md border-b border-outline-variant/30">
<div class="flex items-center gap-md">
<button class="text-primary dark:text-primary-fixed-dim hover:bg-primary-container/20 transition-colors rounded-full p-sm active:scale-95 duration-200">
<span class="material-symbols-outlined">arrow_back</span>
</button>
<h1 class="font-display-lg text-display-lg text-primary dark:text-primary-fixed-dim">DermClinical</h1>
</div>
<div>
<span class="material-symbols-outlined text-primary dark:text-primary-fixed-dim">medical_services</span>
</div>
</header>
<!-- Main Content Area -->
<main class="flex-grow pt-[88px] pb-[100px] px-container-margin overflow-y-auto">
<div class="max-w-3xl mx-auto space-y-lg">
<!-- Progress Indicator -->
<div class="w-full">
<div class="flex justify-between font-label-sm text-label-sm text-secondary mb-sm">
<span>Service</span>
<span>Time</span>
<span class="text-primary font-bold">Confirm</span>
</div>
<div class="h-1 bg-surface-container rounded-full overflow-hidden">
<div class="h-full bg-primary-container w-full"></div>
</div>
</div>
<div class="space-y-sm">
<h2 class="font-headline-lg-mobile text-headline-lg-mobile md:font-headline-lg md:text-headline-lg text-on-surface">Appointment Summary</h2>
<p class="font-body-md text-body-md text-on-surface-variant">Please review your booking details before confirming.</p>
</div>
<!-- Bento Grid Layout for Summary -->
<div class="grid grid-cols-1 md:grid-cols-2 gap-bento-gap">
<!-- Treatment Details Card -->
<div class="bg-surface-container-lowest border border-surface-container-highest rounded-xl p-container-margin shadow-[0_4px_20px_rgba(0,0,0,0.04)] col-span-1 md:col-span-2">
<div class="flex items-start gap-md">
<div class="w-16 h-16 rounded-lg bg-surface-container overflow-hidden shrink-0">
<img alt="Clinical treatment" class="w-full h-full object-cover" data-alt="A close-up shot of a pristine, high-end medical spa treatment room. Soft, diffused lighting illuminates a clean, modern aesthetic with warm beige and white tones. The focus is on a sleek, minimalist treatment bed and advanced dermatological equipment. The overall mood is calm, professional, and luxurious." src="https://lh3.googleusercontent.com/aida-public/AB6AXuAbl1JPE4esnySjL95hM4NsJ-gxQGheAX8gsRww5uSl91PQdbJmgLs2IwbQ41nWpn7816vHOFHFQNYAmYpK5i9lBmt151u00Wgsk5ev-3SwxYxZavfRfMnc5WKy9NzKVribi4mX-2VeypqyszccVI6e9PB403iurjj_lgDixbBK-iGXSJc-BWIEYZrAIjVR0U0WA-1ug4Yk_v8-OI4-mvwkRqT9Oqb_gj1lZ-VeiEG1xSM8Ljc4zrqSbl4Qf71nHBSM-6tcdBS47U0M"/>
</div>
<div class="flex-grow">
<h3 class="font-headline-md text-headline-md text-on-surface mb-xs">Advanced Microneedling</h3>
<p class="font-body-md text-body-md text-on-surface-variant mb-sm">Collagen induction therapy for skin rejuvenation.</p>
<div class="inline-flex items-center gap-xs px-sm py-xs bg-surface-container rounded-full font-label-sm text-label-sm text-on-surface-variant">
<span class="material-symbols-outlined" style="font-size: 16px;">schedule</span>
                                60 min
                            </div>
</div>
<div class="text-right">
<span class="font-headline-md text-headline-md text-primary">$250</span>
</div>
</div>
</div>
<!-- Date & Time Card -->
<div class="bg-surface-container-lowest border border-surface-container-highest rounded-xl p-container-margin shadow-[0_4px_20px_rgba(0,0,0,0.04)] flex items-center gap-md">
<div class="w-12 h-12 rounded-full bg-primary-container/10 flex items-center justify-center text-primary-container shrink-0">
<span class="material-symbols-outlined" style="font-variation-settings: 'FILL' 1;">calendar_month</span>
</div>
<div>
<p class="font-label-sm text-label-sm text-secondary uppercase tracking-wider mb-xs">Date &amp; Time</p>
<p class="font-body-lg text-body-lg text-on-surface font-medium">Oct 24, 2023</p>
<p class="font-body-md text-body-md text-on-surface-variant">10:00 AM - 11:00 AM</p>
</div>
</div>
<!-- Clinician Card -->
<div class="bg-surface-container-lowest border border-surface-container-highest rounded-xl p-container-margin shadow-[0_4px_20px_rgba(0,0,0,0.04)] flex items-center gap-md">
<div class="w-12 h-12 rounded-full bg-surface-container overflow-hidden shrink-0 border border-outline-variant/30">
<img alt="Dr. Sarah Jenkins" class="w-full h-full object-cover" data-alt="A professional headshot of a female dermatologist in a crisp white lab coat. She has a warm, reassuring smile. The background is a soft, blurred modern clinical setting with natural light and minimalist decor in shades of warm sand and white. High fidelity and clean aesthetic." src="https://lh3.googleusercontent.com/aida-public/AB6AXuAqNf3r5VzD7Bs0-hLfIMh5J1M18xGIJY3Qn31bPEh_CDXe57o0hjw6_yZ7tE0LNqtfIyZzu4FsqMQtPGCOLWD79SZ5Qgba2riGW9i17aAFuNEfu67JPrqLZFCWPOtV-whGwyF483opDrprS-LutgEwbUcYzQmO7SdK4ud0LP8Lf4Ci_TbKRtSwzMODnNbI64c0xOvnIX_YKEshf4_45Ievk3las7vgXdVGV6xM_2Uj-4AK14JCCT3ayQnZ9SfA3-g2pel6y5_R17AX"/>
</div>
<div>
<p class="font-label-sm text-label-sm text-secondary uppercase tracking-wider mb-xs">Clinician</p>
<p class="font-body-lg text-body-lg text-on-surface font-medium">Dr. Sarah Jenkins</p>
<p class="font-body-md text-body-md text-on-surface-variant">Lead Dermatologist</p>
</div>
</div>
<!-- Location Card (Full Width) -->
<div class="bg-surface-container-lowest border border-surface-container-highest rounded-xl p-container-margin shadow-[0_4px_20px_rgba(0,0,0,0.04)] col-span-1 md:col-span-2 flex items-center gap-md">
<div class="w-12 h-12 rounded-full bg-primary-container/10 flex items-center justify-center text-primary-container shrink-0">
<span class="material-symbols-outlined" style="font-variation-settings: 'FILL' 1;">location_on</span>
</div>
<div class="flex-grow">
<p class="font-label-sm text-label-sm text-secondary uppercase tracking-wider mb-xs">Location</p>
<p class="font-body-lg text-body-lg text-on-surface font-medium">Beverly Hills Clinic</p>
<p class="font-body-md text-body-md text-on-surface-variant">456 Rodeo Drive, Suite 200, CA 90210</p>
</div>
</div>
</div>
<!-- Cancellation Policy -->
<div class="bg-surface p-container-margin rounded-xl border border-surface-container-high">
<div class="flex items-start gap-sm">
<span class="material-symbols-outlined text-secondary text-sm mt-xs">info</span>
<div>
<h4 class="font-label-md text-label-md text-on-surface mb-xs">Cancellation Policy</h4>
<p class="font-body-md text-body-md text-on-surface-variant text-sm">Please provide at least 24 hours notice if you need to cancel or reschedule your appointment to avoid a cancellation fee.</p>
</div>
</div>
</div>
</div>
</main>
<!-- Sticky Bottom Action Bar -->
<div class="fixed bottom-0 left-0 w-full bg-surface/80 dark:bg-surface-dim/80 backdrop-blur-xl border-t border-outline-variant/20 p-container-margin shadow-[0_-4px_20px_rgba(0,0,0,0.04)] z-50 pb-safe">
<div class="max-w-3xl mx-auto flex items-center justify-between gap-md">
<div class="hidden sm:block">
<p class="font-label-sm text-label-sm text-secondary uppercase tracking-wider mb-xs">Total Due Today</p>
<p class="font-headline-md text-headline-md text-on-surface">$250.00</p>
</div>
<button class="flex-grow sm:flex-grow-0 bg-primary-container text-on-primary font-label-md text-label-md py-md px-xl rounded-full shadow-[0_4px_14px_rgba(198,142,117,0.2)] hover:bg-surface-tint transition-all active:scale-95 duration-200 text-center">
                Confirm Appointment
            </button>
</div>
</div>
</body></html>