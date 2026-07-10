<!DOCTYPE html><html class="dark" lang="en"><head><meta charset="utf-8"><meta content="width=device-width, initial-scale=1.0" name="viewport"><link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=block" rel="stylesheet"><link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;500;700;800&amp;family=Hanken+Grotesk:wght@400;700;800&amp;display=swap" rel="stylesheet"><script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script><script id="tailwind-config">try{
        tailwind.config = {
          darkMode: "class",
          theme: {
            extend: {
              "colors": {
                      "on-primary-container": "#340080",
                      "on-primary": "#3c0091",
                      "on-secondary": "#38294d",
                      "surface-dim": "#1f0e18",
                      "outline": "#958ea0",
                      "outline-variant": "#494454",
                      "on-primary-fixed-variant": "#5516be",
                      "on-tertiary": "#3f0689",
                      "surface-variant": "#432f3a",
                      "secondary": "#d3beeb",
                      "on-surface": "#fadae9",
                      "surface-bright": "#48333e",
                      "inverse-on-surface": "#3e2b35",
                      "on-error": "#690005",
                      "surface-container-highest": "#432f3a",
                      "primary": "#d0bcff",
                      "tertiary-container": "#a37af1",
                      "on-secondary-fixed": "#231437",
                      "on-surface-variant": "#cbc3d7",
                      "surface-container-lowest": "#190913",
                      "inverse-surface": "#fadae9",
                      "error": "#ffb4ab",
                      "primary-fixed": "#e9ddff",
                      "primary-fixed-dim": "#d0bcff",
                      "surface-container-low": "#281620",
                      "error-container": "#93000a",
                      "tertiary-fixed-dim": "#d3bbff",
                      "on-tertiary-container": "#37007c",
                      "tertiary": "#d3bbff",
                      "surface-container": "#2c1a24",
                      "surface-container-high": "#37242f",
                      "primary-container": "#a078ff",
                      "on-primary-fixed": "#23005c",
                      "on-tertiary-fixed-variant": "#572ba0",
                      "on-tertiary-fixed": "#260059",
                      "background": "#1f0e18",
                      "on-secondary-fixed-variant": "#4f4065",
                      "on-error-container": "#ffdad6",
                      "inverse-primary": "#6d3bd7",
                      "on-background": "#fadae9",
                      "secondary-fixed": "#eddcff",
                      "surface": "#1f0e18",
                      "secondary-container": "#524267",
                      "surface-tint": "#d0bcff",
                      "secondary-fixed-dim": "#d3beeb",
                      "tertiary-fixed": "#ebdcff",
                      "on-secondary-container": "#c4b0dd"
              },
              "borderRadius": {
                      "DEFAULT": "0.125rem",
                      "lg": "0.25rem",
                      "xl": "0.5rem",
                      "full": "0.75rem"
              },
              "spacing": {
                      "margin-mobile": "16px",
                      "margin-desktop": "64px",
                      "gutter": "24px",
                      "unit": "4px",
                      "container-max": "1200px"
              },
              "fontFamily": {
                      "code-sm": [
                              "JetBrains Mono"
                      ],
                      "body-md": [
                              "JetBrains Mono"
                      ],
                      "headline-lg": [
                              "Hanken Grotesk"
                      ],
                      "label-caps": [
                              "JetBrains Mono"
                      ],
                      "headline-lg-mobile": [
                              "Hanken Grotesk"
                      ],
                      "headline-xl": [
                              "Hanken Grotesk"
                      ]
              },
              "fontSize": {
                      "code-sm": [
                              "14px",
                              {
                                      "lineHeight": "1.4",
                                      "fontWeight": "500"
                              }
                      ],
                      "body-md": [
                              "16px",
                              {
                                      "lineHeight": "1.6",
                                      "fontWeight": "400"
                              }
                      ],
                      "headline-lg": [
                              "32px",
                              {
                                      "lineHeight": "1.2",
                                      "letterSpacing": "-0.02em",
                                      "fontWeight": "700"
                              }
                      ],
                      "label-caps": [
                              "12px",
                              {
                                      "lineHeight": "1",
                                      "letterSpacing": "0.1em",
                                      "fontWeight": "700"
                              }
                      ],
                      "headline-lg-mobile": [
                              "28px",
                              {
                                      "lineHeight": "1.2",
                                      "fontWeight": "700"
                              }
                      ],
                      "headline-xl": [
                              "48px",
                              {
                                      "lineHeight": "1.1",
                                      "letterSpacing": "-0.04em",
                                      "fontWeight": "800"
                              }
                      ]
              }
      },
          },
        }
      }catch(_e){}</script></head><body class="font-body-md text-body-md antialiased min-h-screen flex flex-col bg-black">
<!-- Top Navigation App Bar -->
<header class="fixed top-0 w-full bg-black/80 backdrop-blur-xl border-b border-zinc-800 flex justify-between items-center px-margin-desktop h-16 z-50">
<div class="flex items-center gap-4 cursor-pointer active:scale-95">
<span class="material-symbols-outlined text-zinc-300">terminal</span>
<span class="font-label-caps text-label-caps tracking-widest text-zinc-300">NEVERMORE_OS</span>
</div>
<div class="flex items-center gap-6">
<span class="font-code-sm text-code-sm text-zinc-300 underline cursor-pointer hover:text-zinc-100 transition-colors">Terminal</span>
<span class="font-code-sm text-code-sm text-zinc-500 cursor-pointer hover:text-zinc-100 transition-colors">Arsenal</span>
<span class="font-code-sm text-code-sm text-zinc-500 cursor-pointer hover:text-zinc-100 transition-colors">Grimoire</span>
<span class="font-code-sm text-code-sm text-zinc-500 cursor-pointer hover:text-zinc-100 transition-colors">Séance</span>
<span class="material-symbols-outlined text-zinc-500 hover:text-zinc-100 transition-colors cursor-pointer">settings_ethernet</span>
</div>
</header>
<main class="flex-grow pt-24 pb-12 px-margin-mobile md:px-margin-desktop max-w-[1400px] mx-auto w-full grid grid-cols-1 gap-8">
<!-- Neofetch Terminal Hero -->
<section class="glass-panel w-full">
<div class="terminal-header flex items-center px-4 py-2 gap-2">
<div class="flex gap-1.5">
<div class="w-3 h-3 rounded-full bg-zinc-700"></div>
<div class="w-3 h-3 rounded-full bg-zinc-600"></div>
<div class="w-3 h-3 rounded-full bg-zinc-500"></div>
</div>
<div class="flex-grow text-center">
<span class="font-label-caps text-label-caps text-zinc-500">daniel@carvalho: ~ — bash</span>
</div>
</div>
<div class="p-8 flex flex-col md:flex-row gap-12 items-center md:items-start">
<!-- ASCII/Pixel Art Area -->
<div class="w-64 h-64 flex-shrink-0 flex items-center justify-center relative bg-transparent">
<img alt="Pixel art raven" class="object-contain w-full h-full pixelated" src="https://lh3.googleusercontent.com/aida-public/AB6AXuA3BNmqVpkm-dDS-0Gy4EjB3IAGmXBLBfKEZ62Nk5htiUMEyMGrg5wOyVQtJU4CcS6dhWr0Ej3A20EJmjWl-UNTZG11iUf0CUohh3fymvTXLq94VrUYrejiuOU_4Qs6aBH50T4uVquURf7a7It-Fu2NuxMCRzgsHS9vTdXpur5pIzZyqQcUgoy4pkP0fgHhycbh7GB8m4XDmbHPyAaRoTRfke3jBW6LNRrHECbJcg4qBhNREEf7fiS-">
</div>
<!-- System Info Output -->
<div class="flex-grow font-code-sm text-code-sm text-zinc-300">
<div class="mb-4">
<span class="text-zinc-200 font-bold">daniel@carvalho</span><br>
<span class="text-zinc-600">-----------------</span>
</div>
<div class="grid grid-cols-1 gap-2">
<div class="flex"><span class="text-zinc-400 w-24">OS</span><span class="text-zinc-600">:</span><span class="ml-2">Windows 11 / Shadow Arch</span></div>
<div class="flex"><span class="text-zinc-400 w-24">Host</span><span class="text-zinc-600">:</span><span class="ml-2">Custom Built Desktop</span></div>
<div class="flex"><span class="text-zinc-400 w-24">Kernel</span><span class="text-zinc-600">:</span><span class="ml-2">5.15.0-shadow-core</span></div>
<div class="flex"><span class="text-zinc-400 w-24">Uptime</span><span class="text-zinc-600">:</span><span class="ml-2">765 days</span></div>
<div class="flex"><span class="text-zinc-400 w-24">Shell</span><span class="text-zinc-600">:</span><span class="ml-2">Bash 5.1.16</span></div>
<div class="flex"><span class="text-zinc-400 w-24">IDE</span><span class="text-zinc-600">:</span><span class="ml-2">IntelliJ, VS Code, Vim</span></div>
<div class="flex"><span class="text-zinc-400 w-24">Palette</span><span class="text-zinc-600">:</span><span class="ml-2">Obsidian / Void</span></div>
</div>
<div class="mt-6 flex gap-2">
<div class="w-6 h-6 bg-black border border-zinc-800"></div>
<div class="w-6 h-6 bg-zinc-800"></div>
<div class="w-6 h-6 bg-zinc-600"></div>
<div class="w-6 h-6 bg-zinc-500"></div>
<div class="w-6 h-6 bg-zinc-400"></div>
<div class="w-6 h-6 bg-zinc-200"></div>
</div>
<div class="mt-4 flex items-center">
<span class="text-zinc-400">~/daniel $ </span><span class="ml-2 text-zinc-300 blinking-cursor">_</span>
</div>
</div>
</div>
</section>
<!-- Two Column Grid for Arsenal and Grimoire -->
<div class="grid grid-cols-1 lg:grid-cols-2 gap-8">
<!-- ARSENAL Section -->
<section class="glass-panel flex flex-col h-full">
<div class="terminal-header flex items-center px-4 py-2 gap-2">
<div class="flex gap-1.5">
<div class="w-3 h-3 rounded-full bg-zinc-700"></div>
<div class="w-3 h-3 rounded-full bg-zinc-700"></div>
<div class="w-3 h-3 rounded-full bg-zinc-700"></div>
</div>
<div class="flex-grow text-center">
<span class="font-label-caps text-label-caps text-zinc-500">/BIN/ARSENAL</span>
</div>
</div>
<div class="p-6 flex-grow">
<div class="font-code-sm text-code-sm text-zinc-600 mb-4">ls -la ./tech_stack</div>
<div class="grid grid-cols-2 md:grid-cols-3 gap-3">
<!-- Tech Chips -->
<div class="bg-black border border-zinc-800 p-2 rounded flex items-center gap-2 glow-border transition-all cursor-crosshair group">
<span class="material-symbols-outlined text-zinc-400 text-[18px]">terminal</span>
<span class="font-code-sm text-code-sm text-zinc-300 group-hover:text-zinc-100 transition-colors">Java</span>
<div class="w-1.5 h-1.5 rounded-full bg-zinc-400 ml-auto shadow-[0_0_5px_#a1a1aa]"></div>
</div>
<div class="bg-black border border-zinc-800 p-2 rounded flex items-center gap-2 glow-border transition-all cursor-crosshair group">
<span class="material-symbols-outlined text-zinc-400 text-[18px]">code</span>
<span class="font-code-sm text-code-sm text-zinc-300 group-hover:text-zinc-100 transition-colors">C</span>
</div>
<div class="bg-black border border-zinc-800 p-2 rounded flex items-center gap-2 glow-border transition-all cursor-crosshair group">
<span class="material-symbols-outlined text-zinc-400 text-[18px]">data_object</span>
<span class="font-code-sm text-code-sm text-zinc-300 group-hover:text-zinc-100 transition-colors">C++</span>
</div>
<div class="bg-black border border-zinc-800 p-2 rounded flex items-center gap-2 glow-border transition-all cursor-crosshair group">
<span class="material-symbols-outlined text-zinc-400 text-[18px]">integration_instructions</span>
<span class="font-code-sm text-code-sm text-zinc-300 group-hover:text-zinc-100 transition-colors">C#</span>
</div>
<div class="bg-black border border-zinc-800 p-2 rounded flex items-center gap-2 glow-border transition-all cursor-crosshair group">
<span class="material-symbols-outlined text-zinc-400 text-[18px]">bug_report</span>
<span class="font-code-sm text-code-sm text-zinc-300 group-hover:text-zinc-100 transition-colors">Python</span>
<div class="w-1.5 h-1.5 rounded-full bg-zinc-400 ml-auto shadow-[0_0_5px_#a1a1aa]"></div>
</div>
<div class="bg-black border border-zinc-800 p-2 rounded flex items-center gap-2 glow-border transition-all cursor-crosshair group">
<span class="material-symbols-outlined text-zinc-400 text-[18px]">lan</span>
<span class="font-code-sm text-code-sm text-zinc-300 group-hover:text-zinc-100 transition-colors">Redes</span>
</div>
<div class="bg-black border border-zinc-800 p-2 rounded flex items-center gap-2 glow-border transition-all cursor-crosshair group">
<span class="material-symbols-outlined text-zinc-500 text-[18px]">security</span>
<span class="font-code-sm text-code-sm text-zinc-300 group-hover:text-zinc-100 transition-colors">Ciber</span>
<div class="w-1.5 h-1.5 rounded-full bg-zinc-500 ml-auto shadow-[0_0_5px_#71717a]"></div>
</div>
<div class="bg-black border border-zinc-800 p-2 rounded flex items-center gap-2 glow-border transition-all cursor-crosshair group">
<span class="material-symbols-outlined text-zinc-400 text-[18px]">router</span>
<span class="font-code-sm text-code-sm text-zinc-300 group-hover:text-zinc-100 transition-colors">IoT</span>
</div>
</div>
</div>
</section>
<!-- GRIMOIRE Section -->
<section class="glass-panel flex flex-col h-full">
<div class="terminal-header flex items-center px-4 py-2 gap-2">
<div class="flex gap-1.5">
<div class="w-3 h-3 rounded-full bg-zinc-700"></div>
<div class="w-3 h-3 rounded-full bg-zinc-700"></div>
<div class="w-3 h-3 rounded-full bg-zinc-700"></div>
</div>
<div class="flex-grow text-center">
<span class="font-label-caps text-label-caps text-zinc-500">SYSTEM_STATS.LOG</span>
</div>
</div>
<div class="p-6 flex-grow flex flex-col gap-6">
<div class="font-code-sm text-code-sm text-zinc-600">tail -f /var/log/github_stats</div>
<div class="flex flex-col gap-4">
<!-- Stat Item -->
<div>
<div class="flex justify-between font-code-sm text-code-sm mb-1">
<span class="text-zinc-300 flex items-center gap-2"><span class="material-symbols-outlined text-[16px] text-zinc-400">commit</span> Commits</span>
<span class="text-zinc-200 glow-text">1,432</span>
</div>
<div class="h-2 progress-track w-full">
<div class="h-full progress-fill" style="width: 85%"></div>
</div>
</div>
<!-- Stat Item -->
<div>
<div class="flex justify-between font-code-sm text-code-sm mb-1">
<span class="text-zinc-300 flex items-center gap-2"><span class="material-symbols-outlined text-[16px] text-zinc-400">all_out</span> PRs Opened</span>
<span class="text-zinc-200 glow-text">84</span>
</div>
<div class="h-2 progress-track w-full">
<div class="h-full progress-fill" style="width: 45%"></div>
</div>
</div>
<!-- Stat Item -->
<div>
<div class="flex justify-between font-code-sm text-code-sm mb-1">
<span class="text-zinc-300 flex items-center gap-2"><span class="material-symbols-outlined text-[16px] text-zinc-400">bug_report</span> Issues Closed</span>
<span class="text-zinc-200 glow-text">215</span>
</div>
<div class="h-2 progress-track w-full">
<div class="h-full progress-fill" style="width: 60%"></div>
</div>
</div>
</div>
<div class="mt-auto grid grid-cols-2 gap-4 border-t border-zinc-800 pt-4">
<div class="text-center">
<div class="font-label-caps text-label-caps text-zinc-600 mb-1">LONGEST STREAK</div>
<div class="font-headline-lg text-headline-lg text-zinc-200 glow-text">42 DAYS</div>
</div>
<div class="text-center border-l border-zinc-800">
<div class="font-label-caps text-label-caps text-zinc-600 mb-1">CURRENT STREAK</div>
<div class="font-headline-lg text-headline-lg text-zinc-400">12 DAYS</div>
</div>
</div>
</div>
</section>
</div>
<!-- SÉANCE Section (Activity Graph) -->
<section class="glass-panel w-full">
<div class="terminal-header flex items-center px-4 py-2 gap-2">
<div class="flex gap-1.5">
<div class="w-3 h-3 rounded-full bg-zinc-700"></div>
<div class="w-3 h-3 rounded-full bg-zinc-700"></div>
<div class="w-3 h-3 rounded-full bg-zinc-700"></div>
</div>
<div class="flex-grow text-center">
<span class="font-label-caps text-label-caps text-zinc-500">NEURAL_NETWORK_ACTIVITY</span>
</div>
</div>
<div class="p-6 overflow-x-auto">
<div class="font-code-sm text-code-sm text-zinc-600 mb-4">cat .git/objects/activity.matrix</div>
<!-- Simulated Contribution Graph -->
<div class="min-w-[800px] flex gap-1">
<!-- Generating a few columns to simulate the graph, styling with tailwind arbitrary values just for this specific vis -->
<script>
                        for(let i=0; i<52; i++) {
                            document.write('<div class="flex flex-col gap-1">');
                            for(let j=0; j<7; j++) {
                                let intensity = Math.random();
                                let colorClass = 'bg-black border border-zinc-900'; // base empty
                                if(intensity > 0.8) colorClass = 'bg-zinc-300 shadow-[0_0_8px_rgba(255,255,255,0.2)]';
                                else if(intensity > 0.6) colorClass = 'bg-zinc-500';
                                else if(intensity > 0.3) colorClass = 'bg-zinc-700';
                                
                                document.write(`<div class="w-3 h-3 rounded-sm ${colorClass}"></div>`);
                            }
                            document.write('</div>');
                        }
                    </script>
</div>
<div class="flex justify-end gap-2 mt-4 font-label-caps text-label-caps text-zinc-500 items-center">
                    Less <div class="w-3 h-3 rounded-sm bg-black border border-zinc-900"></div>
<div class="w-3 h-3 rounded-sm bg-zinc-700"></div>
<div class="w-3 h-3 rounded-sm bg-zinc-500"></div>
<div class="w-3 h-3 rounded-sm bg-zinc-300 shadow-[0_0_5px_rgba(255,255,255,0.2)]"></div> More
                </div>
</div>
</section>
<!-- LOG ENTRIES Section -->
<section class="glass-panel w-full">
<div class="terminal-header flex items-center px-4 py-2 gap-2">
<div class="flex gap-1.5">
<div class="w-3 h-3 rounded-full bg-zinc-700"></div>
<div class="w-3 h-3 rounded-full bg-zinc-700"></div>
<div class="w-3 h-3 rounded-full bg-zinc-700"></div>
</div>
<div class="flex-grow text-center">
<span class="font-label-caps text-label-caps text-zinc-500">/VAR/LOG/MILESTONES.LOG</span>
</div>
</div>
<div class="p-6 font-code-sm text-code-sm flex flex-col gap-4">
<div class="flex gap-4 items-start group">
<div class="text-zinc-500 w-32 flex-shrink-0 pt-1">[2023-05-12]</div>
<div class="flex flex-col border-l border-zinc-800 pl-4 py-1">
<span class="text-zinc-300 font-bold">INIT_SEQUENCE: BSc Computer Science</span>
<span class="text-zinc-500">University of Technology. Core modules loaded successfully.</span>
</div>
</div>
<div class="flex gap-4 items-start group">
<div class="text-zinc-500 w-32 flex-shrink-0 pt-1">[2022-11-04]</div>
<div class="flex flex-col border-l border-zinc-800 pl-4 py-1">
<span class="text-zinc-300 font-bold">ACHIEVEMENT_UNLOCKED: Hackathon Winner</span>
<span class="text-zinc-500">Deployed IoT security solution. Status: 0 Exit Code (Success).</span>
</div>
</div>
<div class="flex gap-4 items-start group">
<div class="text-zinc-500 w-32 flex-shrink-0 pt-1">[2021-08-20]</div>
<div class="flex flex-col border-l border-zinc-800 pl-4 py-1">
<span class="text-zinc-300 font-bold">CERTIFICATE_ACQUIRED: Adv. Cyber Security</span>
<span class="text-zinc-500">Offensive Security Certified Professional (OSCP) - Root obtained.</span>
</div>
</div>
<div class="flex items-center mt-2">
<span class="text-zinc-400">~/logs $ </span><span class="ml-2 text-zinc-300 blinking-cursor">_</span>
</div>
</div>
</section>
</main>
<!-- Footer -->
</body></html>
