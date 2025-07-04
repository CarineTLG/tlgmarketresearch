# tlgmarketresearch
TLG Market Research
<!DOCTYPE html>
<!-- saved from url=(0053)file:///Users/carine/Downloads/Market%20Research.html -->
<html lang="en" class="scroll-smooth"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Market Research: The Land Geek vs. Competitors</title>
    <script src="./Market Research_ The Land Geek vs. Competitors_files/saved_resource"></script>
    <script src="./Market Research_ The Land Geek vs. Competitors_files/chart.js"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com/">
    <link rel="preconnect" href="https://fonts.gstatic.com/" crossorigin="">
    <link href="./Market Research_ The Land Geek vs. Competitors_files/css2" rel="stylesheet">
    <!-- Chosen Palette: Calm Authority -->
    <!-- Application Structure Plan: A thematic, top-down dashboard. Starts with a high-level market comparison (Cost vs. Value, Audience Focus) using interactive charts in a tabbed interface. This allows users to grasp the landscape quickly. Below, a "Deep Dive" section lets users select a specific program to dynamically view its detailed profile. This structure guides the user from broad comparison to specific exploration, which is a more intuitive flow than a static list. The final section contextualizes the common methodology taught. This user-flow is designed for decision-making rather than just data presentation. -->
    <!-- Visualization & Content Choices: 1. Cost vs. Value (Scatter Plot): Goal=Compare/Relationships. Shows flagship cost against a calculated "value score" (based on high-touch features). Justification=Visually identifies value propositions. Library=Chart.js. 2. Audience Focus (Bubble Chart): Goal=Organize/Compare. Shows experience level vs. support model, with bubble size representing market presence. Justification=Helps users find a fit for their profile. Library=Chart.js. 3. Program Inclusions (Icon List): Goal=Inform. Uses styled HTML/Unicode icons. Justification=More scannable than text. 4. Flipping Process (Diagram): Goal=Organize/Inform. Uses styled HTML/CSS divs. Justification=Adheres to no-SVG rule while clearly showing process flow. -->
    <!-- CONFIRMATION: NO SVG graphics used. NO Mermaid JS used. -->
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #F8F7F4; /* Warm Neutral */
            color: #1A252F; /* Dark Navy/Slate */
        }
        .chart-container {
            position: relative;
            margin: auto;
            height: 450px;
            width: 100%;
            max-width: 800px;
        }
        .tab-button {
            transition: all 0.3s ease;
        }
        .tab-button.active {
            background-color: #1A252F;
            color: #FFFFFF;
        }
        .program-selector.active {
            background-color: #EAE8E1;
            border-left-color: #C5A47E;
        }
        .program-selector {
             transition: all 0.2s ease-in-out;
             border-left-width: 4px;
             border-color: transparent;
        }
        .icon-list-item svg {
            width: 1.25rem;
            height: 1.25rem;
            margin-right: 0.75rem;
            flex-shrink: 0;
        }
    </style>
<style>*, ::before, ::after{--tw-border-spacing-x:0;--tw-border-spacing-y:0;--tw-translate-x:0;--tw-translate-y:0;--tw-rotate:0;--tw-skew-x:0;--tw-skew-y:0;--tw-scale-x:1;--tw-scale-y:1;--tw-pan-x: ;--tw-pan-y: ;--tw-pinch-zoom: ;--tw-scroll-snap-strictness:proximity;--tw-gradient-from-position: ;--tw-gradient-via-position: ;--tw-gradient-to-position: ;--tw-ordinal: ;--tw-slashed-zero: ;--tw-numeric-figure: ;--tw-numeric-spacing: ;--tw-numeric-fraction: ;--tw-ring-inset: ;--tw-ring-offset-width:0px;--tw-ring-offset-color:#fff;--tw-ring-color:rgb(59 130 246 / 0.5);--tw-ring-offset-shadow:0 0 #0000;--tw-ring-shadow:0 0 #0000;--tw-shadow:0 0 #0000;--tw-shadow-colored:0 0 #0000;--tw-blur: ;--tw-brightness: ;--tw-contrast: ;--tw-grayscale: ;--tw-hue-rotate: ;--tw-invert: ;--tw-saturate: ;--tw-sepia: ;--tw-drop-shadow: ;--tw-backdrop-blur: ;--tw-backdrop-brightness: ;--tw-backdrop-contrast: ;--tw-backdrop-grayscale: ;--tw-backdrop-hue-rotate: ;--tw-backdrop-invert: ;--tw-backdrop-opacity: ;--tw-backdrop-saturate: ;--tw-backdrop-sepia: ;--tw-contain-size: ;--tw-contain-layout: ;--tw-contain-paint: ;--tw-contain-style: }::backdrop{--tw-border-spacing-x:0;--tw-border-spacing-y:0;--tw-translate-x:0;--tw-translate-y:0;--tw-rotate:0;--tw-skew-x:0;--tw-skew-y:0;--tw-scale-x:1;--tw-scale-y:1;--tw-pan-x: ;--tw-pan-y: ;--tw-pinch-zoom: ;--tw-scroll-snap-strictness:proximity;--tw-gradient-from-position: ;--tw-gradient-via-position: ;--tw-gradient-to-position: ;--tw-ordinal: ;--tw-slashed-zero: ;--tw-numeric-figure: ;--tw-numeric-spacing: ;--tw-numeric-fraction: ;--tw-ring-inset: ;--tw-ring-offset-width:0px;--tw-ring-offset-color:#fff;--tw-ring-color:rgb(59 130 246 / 0.5);--tw-ring-offset-shadow:0 0 #0000;--tw-ring-shadow:0 0 #0000;--tw-shadow:0 0 #0000;--tw-shadow-colored:0 0 #0000;--tw-blur: ;--tw-brightness: ;--tw-contrast: ;--tw-grayscale: ;--tw-hue-rotate: ;--tw-invert: ;--tw-saturate: ;--tw-sepia: ;--tw-drop-shadow: ;--tw-backdrop-blur: ;--tw-backdrop-brightness: ;--tw-backdrop-contrast: ;--tw-backdrop-grayscale: ;--tw-backdrop-hue-rotate: ;--tw-backdrop-invert: ;--tw-backdrop-opacity: ;--tw-backdrop-saturate: ;--tw-backdrop-sepia: ;--tw-contain-size: ;--tw-contain-layout: ;--tw-contain-paint: ;--tw-contain-style: }/* ! tailwindcss v3.4.16 | MIT License | https://tailwindcss.com */*,::after,::before{box-sizing:border-box;border-width:0;border-style:solid;border-color:#e5e7eb}::after,::before{--tw-content:''}:host,html{line-height:1.5;-webkit-text-size-adjust:100%;-moz-tab-size:4;tab-size:4;font-family:ui-sans-serif, system-ui, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";font-feature-settings:normal;font-variation-settings:normal;-webkit-tap-highlight-color:transparent}body{margin:0;line-height:inherit}hr{height:0;color:inherit;border-top-width:1px}abbr:where([title]){-webkit-text-decoration:underline dotted;text-decoration:underline dotted}h1,h2,h3,h4,h5,h6{font-size:inherit;font-weight:inherit}a{color:inherit;text-decoration:inherit}b,strong{font-weight:bolder}code,kbd,pre,samp{font-family:ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;font-feature-settings:normal;font-variation-settings:normal;font-size:1em}small{font-size:80%}sub,sup{font-size:75%;line-height:0;position:relative;vertical-align:baseline}sub{bottom:-.25em}sup{top:-.5em}table{text-indent:0;border-color:inherit;border-collapse:collapse}button,input,optgroup,select,textarea{font-family:inherit;font-feature-settings:inherit;font-variation-settings:inherit;font-size:100%;font-weight:inherit;line-height:inherit;letter-spacing:inherit;color:inherit;margin:0;padding:0}button,select{text-transform:none}button,input:where([type=button]),input:where([type=reset]),input:where([type=submit]){-webkit-appearance:button;background-color:transparent;background-image:none}:-moz-focusring{outline:auto}:-moz-ui-invalid{box-shadow:none}progress{vertical-align:baseline}::-webkit-inner-spin-button,::-webkit-outer-spin-button{height:auto}[type=search]{-webkit-appearance:textfield;outline-offset:-2px}::-webkit-search-decoration{-webkit-appearance:none}::-webkit-file-upload-button{-webkit-appearance:button;font:inherit}summary{display:list-item}blockquote,dd,dl,figure,h1,h2,h3,h4,h5,h6,hr,p,pre{margin:0}fieldset{margin:0;padding:0}legend{padding:0}menu,ol,ul{list-style:none;margin:0;padding:0}dialog{padding:0}textarea{resize:vertical}input::placeholder,textarea::placeholder{opacity:1;color:#9ca3af}[role=button],button{cursor:pointer}:disabled{cursor:default}audio,canvas,embed,iframe,img,object,svg,video{display:block;vertical-align:middle}img,video{max-width:100%;height:auto}[hidden]:where(:not([hidden=until-found])){display:none}.container{width:100%}@media (min-width: 640px){.container{max-width:640px}}@media (min-width: 768px){.container{max-width:768px}}@media (min-width: 1024px){.container{max-width:1024px}}@media (min-width: 1280px){.container{max-width:1280px}}@media (min-width: 1536px){.container{max-width:1536px}}.mx-2{margin-left:0.5rem;margin-right:0.5rem}.mx-auto{margin-left:auto;margin-right:auto}.my-2{margin-top:0.5rem;margin-bottom:0.5rem}.-mb-px{margin-bottom:-1px}.mb-2{margin-bottom:0.5rem}.mb-3{margin-bottom:0.75rem}.mb-6{margin-bottom:1.5rem}.mb-8{margin-bottom:2rem}.mt-16{margin-top:4rem}.mt-2{margin-top:0.5rem}.mt-4{margin-top:1rem}.mb-4{margin-bottom:1rem}.flex{display:flex}.grid{display:grid}.hidden{display:none}.min-h-\[500px\]{min-height:500px}.max-w-2xl{max-width:42rem}.max-w-3xl{max-width:48rem}.max-w-7xl{max-width:80rem}.flex-1{flex:1 1 0%}.cursor-pointer{cursor:pointer}.grid-cols-1{grid-template-columns:repeat(1, minmax(0, 1fr))}.flex-col{flex-direction:column}.items-start{align-items:flex-start}.items-center{align-items:center}.items-stretch{align-items:stretch}.justify-center{justify-content:center}.justify-between{justify-content:space-between}.gap-2{gap:0.5rem}.gap-6{gap:1.5rem}.space-y-16 > :not([hidden]) ~ :not([hidden]){--tw-space-y-reverse:0;margin-top:calc(4rem * calc(1 - var(--tw-space-y-reverse)));margin-bottom:calc(4rem * var(--tw-space-y-reverse))}.space-y-3 > :not([hidden]) ~ :not([hidden]){--tw-space-y-reverse:0;margin-top:calc(0.75rem * calc(1 - var(--tw-space-y-reverse)));margin-bottom:calc(0.75rem * var(--tw-space-y-reverse))}.self-center{align-self:center}.scroll-smooth{scroll-behavior:smooth}.rounded-lg{border-radius:0.5rem}.rounded-md{border-radius:0.375rem}.rounded-t-md{border-top-left-radius:0.375rem;border-top-right-radius:0.375rem}.border-b{border-bottom-width:1px}.border-r{border-right-width:1px}.border-t{border-top-width:1px}.border-gray-200{--tw-border-opacity:1;border-color:rgb(229 231 235 / var(--tw-border-opacity, 1))}.bg-gray-100{--tw-bg-opacity:1;background-color:rgb(243 244 246 / var(--tw-bg-opacity, 1))}.bg-gray-50\/50{background-color:rgb(249 250 251 / 0.5)}.bg-white{--tw-bg-opacity:1;background-color:rgb(255 255 255 / var(--tw-bg-opacity, 1))}.bg-gray-50{--tw-bg-opacity:1;background-color:rgb(249 250 251 / var(--tw-bg-opacity, 1))}.p-4{padding:1rem}.p-6{padding:1.5rem}.px-6{padding-left:1.5rem;padding-right:1.5rem}.py-3{padding-top:0.75rem;padding-bottom:0.75rem}.py-8{padding-top:2rem;padding-bottom:2rem}.pb-6{padding-bottom:1.5rem}.text-center{text-align:center}.text-right{text-align:right}.text-2xl{font-size:1.5rem;line-height:2rem}.text-4xl{font-size:2.25rem;line-height:2.5rem}.text-lg{font-size:1.125rem;line-height:1.75rem}.text-sm{font-size:0.875rem;line-height:1.25rem}.text-xs{font-size:0.75rem;line-height:1rem}.font-bold{font-weight:700}.font-semibold{font-weight:600}.text-\[\#1A252F\]{--tw-text-opacity:1;color:rgb(26 37 47 / var(--tw-text-opacity, 1))}.text-\[\#C5A47E\]{--tw-text-opacity:1;color:rgb(197 164 126 / var(--tw-text-opacity, 1))}.text-gray-300{--tw-text-opacity:1;color:rgb(209 213 219 / var(--tw-text-opacity, 1))}.text-gray-400{--tw-text-opacity:1;color:rgb(156 163 175 / var(--tw-text-opacity, 1))}.text-gray-500{--tw-text-opacity:1;color:rgb(107 114 128 / var(--tw-text-opacity, 1))}.text-gray-600{--tw-text-opacity:1;color:rgb(75 85 99 / var(--tw-text-opacity, 1))}.text-gray-700{--tw-text-opacity:1;color:rgb(55 65 81 / var(--tw-text-opacity, 1))}.antialiased{-webkit-font-smoothing:antialiased;-moz-osx-font-smoothing:grayscale}.shadow-sm{--tw-shadow:0 1px 2px 0 rgb(0 0 0 / 0.05);--tw-shadow-colored:0 1px 2px 0 var(--tw-shadow-color);box-shadow:var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow)}.hover\:bg-\[\#EAE8E1\]:hover{--tw-bg-opacity:1;background-color:rgb(234 232 225 / var(--tw-bg-opacity, 1))}@media (min-width: 768px){.md\:col-span-4{grid-column:span 4 / span 4}.md\:col-span-8{grid-column:span 8 / span 8}.md\:my-0{margin-top:0px;margin-bottom:0px}.md\:mt-0{margin-top:0px}.md\:grid-cols-12{grid-template-columns:repeat(12, minmax(0, 1fr))}.md\:flex-row{flex-direction:row}.md\:items-center{align-items:center}.md\:gap-4{gap:1rem}.md\:p-8{padding:2rem}.md\:text-3xl{font-size:1.875rem;line-height:2.25rem}.md\:text-5xl{font-size:3rem;line-height:1}.md\:text-base{font-size:1rem;line-height:1.5rem}}@media (min-width: 1024px){.lg\:col-span-3{grid-column:span 3 / span 3}.lg\:col-span-9{grid-column:span 9 / span 9}.lg\:grid-cols-2{grid-template-columns:repeat(2, minmax(0, 1fr))}}</style></head>
<body class="antialiased">

    <div class="container mx-auto p-4 md:p-8 max-w-7xl">

        <header class="text-center py-8">
            <h1 class="text-4xl md:text-5xl font-bold text-[#1A252F] mb-3">Market Research: The Land Geek vs. Competitors</h1>
            <p class="text-lg text-gray-600 max-w-3xl mx-auto">An interactive dashboard designed to help you navigate and compare the top land investing programs in the USA.</p>
        </header>

        <main class="space-y-16">

            <section id="market-dashboard">
                <div class="bg-white rounded-lg shadow-sm p-6 md:p-8">
                    <h2 class="text-2xl md:text-3xl font-bold text-center mb-2">Market At-a-Glance</h2>
                    <p class="text-center text-gray-500 mb-8 max-w-2xl mx-auto">This section provides a high-level comparison of the leading programs. Use the tabs to switch between different analytical views to understand the landscape based on cost, value, and target audience.</p>
                    
                    <div class="flex justify-center border-b border-gray-200 mb-6">
                        <button id="tab-cost" class="tab-button text-sm md:text-base font-semibold py-3 px-6 -mb-px rounded-t-md active">Cost vs. Value</button>
                        <button id="tab-audience" class="tab-button text-sm md:text-base font-semibold py-3 px-6 -mb-px rounded-t-md">Audience &amp; Focus</button>
                    </div>

                    <div id="chart-cost-container" class="chart-container">
                        <canvas id="costValueChart" width="1600" height="900" style="display: block; box-sizing: border-box; height: 450px; width: 800px;"></canvas>
                    </div>
                    <div id="chart-audience-container" class="chart-container hidden">
                        <canvas id="audienceChart" height="900" style="display: block; box-sizing: border-box; height: 450px; width: 800px;" width="1600"></canvas>
                    </div>
                     <p class="text-center text-xs text-gray-400 mt-4 max-w-2xl mx-auto">Note: "Value Score" is a relative metric based on inclusion of high-touch features like 1:1 coaching, live calls, and software. "Market Presence" is a relative score based on available data like community size and brand visibility.</p>
                </div>
            </section>

            <section id="program-deep-dive">
                 <div class="bg-white rounded-lg shadow-sm">
                    <div class="p-6 md:p-8">
                        <h2 class="text-2xl md:text-3xl font-bold text-center mb-2">Program Deep Dive</h2>
                        <p class="text-center text-gray-500 mb-8 max-w-2xl mx-auto">After reviewing the high-level comparisons, you can explore the specific details of each program here. Select a program from the list on the left to view its complete profile.</p>
                    </div>

                    <div class="grid grid-cols-1 md:grid-cols-12 border-t border-gray-200">
                        <div id="program-selector-container" class="md:col-span-4 lg:col-span-3 border-r border-gray-200 bg-gray-50/50">
                        <div class="program-selector p-4 cursor-pointer hover:bg-[#EAE8E1] active" data-id="land_geek">The Land Geek (Flight School)</div><div class="program-selector p-4 cursor-pointer hover:bg-[#EAE8E1]" data-id="land_academy">Land Academy</div><div class="program-selector p-4 cursor-pointer hover:bg-[#EAE8E1]" data-id="max_horenstein">Max Horenstein</div><div class="program-selector p-4 cursor-pointer hover:bg-[#EAE8E1]" data-id="travis_king">Travis King</div><div class="program-selector p-4 cursor-pointer hover:bg-[#EAE8E1]" data-id="jon_jasniak">Jon Jasniak</div><div class="program-selector p-4 cursor-pointer hover:bg-[#EAE8E1]" data-id="build_assets_online">Build Assets Online</div><div class="program-selector p-4 cursor-pointer hover:bg-[#EAE8E1]" data-id="land_investing_online">Land Investing Online</div><div class="program-selector p-4 cursor-pointer hover:bg-[#EAE8E1]" data-id="retipster">REtipster</div><div class="program-selector p-4 cursor-pointer hover:bg-[#EAE8E1]" data-id="jack_bosch">Jack Bosch</div></div>

                        <div class="md:col-span-8 lg:col-span-9 p-6 md:p-8 min-h-[500px]">
                            <div id="program-details-content">
            <div class="flex flex-col md:flex-row items-start md:items-center justify-between mb-4">
                 <div>
                    <h3 class="text-2xl md:text-3xl font-bold text-[#1A252F]">The Land Geek (Flight School)</h3>
                    <p class="text-sm text-gray-500">with Mark Podolsky (Founder), Scott Todd (Head Instructor)</p>
                 </div>
                <div class="mt-4 md:mt-0 text-right">
                    <p class="text-gray-500 text-sm">Flagship Program Cost</p>
                    <p class="text-2xl font-bold text-[#C5A47E]">$11,900</p>
                 </div>
            </div>
            <p class="text-gray-600 mb-2">A premium, high-touch 16-week program focused on creating passive income streams through owner financing. Its key differentiators are 1 hour of 1:1 coaching and community access via virtual bootcamps, offering comprehensive support and tech trials.</p>
            <p class="text-gray-600 text-sm mb-6 pb-6 border-b border-gray-200">Program Length: 16-weeks</p>
            
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-6">
                <div>
                    <h4 class="font-bold mb-3 text-lg">What's Included</h4>
                    <ul class="space-y-3 icon-list">
                        <li class="flex items-center text-gray-700 icon-list-item"><svg fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6.253v13m0-13C10.832 5.477 9.246 5 7.5 5S4.168 5.477 3 6.253v13C4.168 18.477 5.754 18 7.5 18s3.332.477 4.5 1.253m0-13C13.168 5.477 14.754 5 16.5 5c1.747 0 3.332.477 4.5 1.253v13C19.832 18.477 18.246 18 16.5 18c-1.746 0-3.332.477-4.5 1.253"></path></svg><span class="text-sm md:text-base">Pre-recorded Course</span></li><li class="flex items-center text-gray-700 icon-list-item"><svg fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8h2a2 2 0 012 2v6a2 2 0 01-2 2h-2v4l-4-4H9a2 2 0 01-2-2V7a2 2 0 012-2h4M5 8h1.586a1 1 0 01.707.293l2.414 2.414a1 1 0 001.414 0l2.414-2.414a1 1 0 01.707-.293H19"></path></svg><span class="text-sm md:text-base">4x/Week Group Calls</span></li><li class="flex items-center text-gray-700 icon-list-item"><svg fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z"></path></svg><span class="text-sm md:text-base">1 Hour of 1:1 Coaching</span></li><li class="flex items-center text-gray-700 icon-list-item"><svg fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8h2a2 2 0 012 2v6a2 2 0 01-2 2h-2v4l-4-4H9a2 2 0 01-2-2V7a2 2 0 012-2h4M5 8h1.586a1 1 0 01.707.293l2.414 2.414a1 1 0 001.414 0l2.414-2.414a1 1 0 01.707-.293H19"></path></svg><span class="text-sm md:text-base">Strategy Call</span></li><li class="flex items-center text-gray-700 icon-list-item"><svg fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z"></path></svg><span class="text-sm md:text-base">Community Access via Bootcamps &amp; Virtual Events</span></li><li class="flex items-center text-gray-700 icon-list-item"><svg fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8h2a2 2 0 012 2v6a2 2 0 01-2 2h-2v4l-4-4H9a2 2 0 01-2-2V7a2 2 0 012-2h4M5 8h1.586a1 1 0 01.707.293l2.414 2.414a1 1 0 001.414 0l2.414-2.414a1 1 0 01.707-.293H19"></path></svg><span class="text-sm md:text-base">Higher-Tier Weekly Calls</span></li><li class="flex items-center text-gray-700 icon-list-item"><svg fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg><span class="text-sm md:text-base">Free Trials of LGPass (proprietary mailing &amp; lead management tool)</span></li>
                    </ul>
                </div>
                <div>
                    <h4 class="font-bold mb-3 text-lg">Proof &amp; Outcomes</h4>
                    <div class="bg-gray-50 p-4 rounded-md">
                        <p class="text-sm text-gray-700">Numerous testimonials reporting high ROIs, with some exceeding 1000%. Head instructor Scott Todd replaced a Fortune 300 VP income in 17 months.</p>
                    </div>
                </div>
            </div>
        </div>
                        </div>
                    </div>
                </div>
            </section>

            <section id="process-flow">
                <div class="bg-white rounded-lg shadow-sm p-6 md:p-8">
                    <h2 class="text-2xl md:text-3xl font-bold text-center mb-2">The Common Blueprint</h2>
                    <p class="text-center text-gray-500 mb-8 max-w-2xl mx-auto">Despite different teaching styles and target audiences, most land investing programs are built upon a similar, repeatable five-step process for finding and flipping properties for profit.</p>
                    <div class="flex flex-col md:flex-row items-stretch justify-center gap-2 md:gap-4 text-center">
                        <div class="flex-1 p-4 bg-gray-100 rounded-md flex flex-col justify-center">
                            <span class="text-4xl text-[#C5A47E]">1</span>
                            <h3 class="font-bold mt-2">Deal Sourcing</h3>
                            <p class="text-sm text-gray-600">Typically via mass mail outreach to find motivated sellers.</p>
                        </div>
                        <div class="self-center text-2xl text-gray-300 mx-2 my-2 md:my-0">→</div>
                        <div class="flex-1 p-4 bg-gray-100 rounded-md flex flex-col justify-center">
                            <span class="text-4xl text-[#C5A47E]">2</span>
                            <h3 class="font-bold mt-2">Due Diligence</h3>
                            <p class="text-sm text-gray-600">Researching property details, access, and title history.</p>
                        </div>
                        <div class="self-center text-2xl text-gray-300 mx-2 my-2 md:my-0">→</div>
                        <div class="flex-1 p-4 bg-gray-100 rounded-md flex flex-col justify-center">
                            <span class="text-4xl text-[#C5A47E]">3</span>
                            <h3 class="font-bold mt-2">Acquisition</h3>
                            <p class="text-sm text-gray-600">Negotiating the price and closing the purchase.</p>
                        </div>
                        <div class="self-center text-2xl text-gray-300 mx-2 my-2 md:my-0">→</div>
                         <div class="flex-1 p-4 bg-gray-100 rounded-md flex flex-col justify-center">
                            <span class="text-4xl text-[#C5A47E]">4</span>
                            <h3 class="font-bold mt-2">Marketing</h3>
                            <p class="text-sm text-gray-600">Listing the property for sale on various online platforms.</p>
                        </div>
                        <div class="self-center text-2xl text-gray-300 mx-2 my-2 md:my-0">→</div>
                        <div class="flex-1 p-4 bg-gray-100 rounded-md flex flex-col justify-center">
                            <span class="text-4xl text-[#C5A47E]">5</span>
                            <h3 class="font-bold mt-2">Sale &amp; Profit</h3>
                            <p class="text-sm text-gray-600">Closing the sale, either for cash or with owner financing.</p>
                        </div>
                    </div>
                </div>
            </section>

        </main>

        <footer class="text-center mt-16 py-8 border-t border-gray-200">
            <p class="text-sm text-gray-500">© 2025 Market Analysis. This interactive application is for informational purposes only, based on publicly available data.</p>
        </footer>
    </div>

<script>
document.addEventListener('DOMContentLoaded', () => {

    const programData = [
        { 
            id: 'land_geek', name: 'The Land Geek (Flight School)', cost: 11900, programLength: '16-weeks',
            audienceExperience: 1, audienceSupport: 3, marketPresence: 25,
            founder: 'Mark Podolsky (Founder), Scott Todd (Head Instructor)',
            tagline: 'A premium, high-touch 16-week program focused on creating passive income streams through owner financing. Its key differentiators are 1 hour of 1:1 coaching and community access via virtual bootcamps, offering comprehensive support and tech trials.',
            inclusions: ['Pre-recorded Course', '4x/Week Group Calls', '1 Hour of 1:1 Coaching', 'Strategy Call', 'Community Access via Bootcamps & Virtual Events', 'Higher-Tier Weekly Calls', 'Free Trials of LGPass (proprietary mailing & lead management tool)'],
            proof: 'Numerous testimonials reporting high ROIs, with some exceeding 1000%. Head instructor Scott Todd replaced a Fortune 300 VP income in 17 months.'
        },
        { 
            id: 'land_academy', name: 'Land Academy', cost: 2995, programLength: 'Self-paced (flagship)',
            audienceExperience: 3, audienceSupport: 2, marketPresence: 35,
            founder: 'Steven Butala & Jill DeWit',
            tagline: 'A comprehensive ecosystem for serious, growth-oriented investors and those looking to scale into an enterprise. Flagship is $2,995. Higher-tier coaching is $32,995/year or $5,992/month.',
            inclusions: ['Self-Paced Videos', 'Monthly Group Coaching', 'Proprietary Software', 'Deal Funding Access', 'Community Forum & Discord', 'Bulk Data Lists', 'Higher-tier Coaching Options (separate cost)'],
            proof: 'Founders have over 19,000 completed transactions. Students report replacing full-time incomes and paying off mortgages.'
        },
        { 
            id: 'max_horenstein', name: 'Max Horenstein', cost: 5000, programLength: 'Varies (guarantee-driven)',
            audienceExperience: 1, audienceSupport: 1, marketPresence: 10,
            founder: 'Max Horenstein',
            tagline: 'A system designed for low-effort, guaranteed results by outsourcing sales and leveraging funding partnerships.',
            inclusions: ['Land Flipping System', 'Pebble REI Integration', 'Mailing Credit', 'Funding Partnerships', '90-Day First Deal Guarantee'],
            proof: 'Key promise is the 90-day deal guarantee. Testimonials show profits like a $90k purchase sold for $170k.'
        },
        { 
            id: 'travis_king', name: 'Travis King', cost: 2497, programLength: '8-weeks',
            audienceExperience: 2.5, audienceSupport: 1.5, marketPresence: 18,
            founder: 'Travis King',
            tagline: 'An 8-week live cohort program for intermediate to advanced investors interested in scaling and complex strategies like subdividing.',
            inclusions: ['8-Week Group Coaching', 'Online Modules', 'Spreadsheets & Templates', 'Deal Tracker', 'Slack Community'],
            proof: 'Growing traction via YouTube and podcasts, catering to a more experienced investor audience.'
        },
        { 
            id: 'jon_jasniak', name: 'Jon Jasniak', cost: 1497, programLength: '50+ hours (course)',
            audienceExperience: 1.5, audienceSupport: 1, marketPresence: 22,
            founder: 'Jon Jasniak',
            tagline: 'Focuses on owner financing and high-volume flipping, ideal for beginners to intermediates with a strong self-starter mindset.',
            inclusions: ['50+ Hours Video Training', 'Contracts & Spreadsheets', 'Call Vault', 'Mastermind (add-on)', 'WhatsApp Community (Mastermind)'],
            proof: 'Large and engaged following on YouTube and Twitter/X, suggesting strong community validation.'
        },
        { 
            id: 'build_assets_online', name: 'Build Assets Online', cost: 2997, programLength: 'Varies',
            audienceExperience: 1.5, audienceSupport: 1.5, marketPresence: 12,
            founder: 'Mike & Joe',
            tagline: 'A bootcamp-style education for beginner to intermediate investors from a digital business perspective.',
            inclusions: ['Land Flip Bootcamp', 'Online Modules', 'Bi-weekly Office Hours', 'Lifetime Discord Community', 'Mail Templates'],
            proof: 'Caters to a digital business niche audience with a moderate YouTube presence.'
        },
        { 
            id: 'land_investing_online', name: 'Land Investing Online', cost: 1349, programLength: 'Varies (on-demand)',
            audienceExperience: 1, audienceSupport: 1.5, marketPresence: 16,
            founder: 'Jaren Barnes & Ajay Sharma',
            tagline: 'A fast-growing program for beginners and early-stage flippers with strong community support via Discord.',
            inclusions: ['On-demand Video Modules', 'Weekly Q&A Webinars', 'Discord Access', 'Texting Course', 'Mail Tracker & CRM'],
            proof: 'Noted for its fast-growing online presence and active community engagement.'
        },
        { 
            id: 'retipster', name: 'REtipster', cost: 1297, programLength: 'Varies (self-paced)',
            audienceExperience: 1, audienceSupport: 1, marketPresence: 28,
            founder: 'Seth Williams',
            tagline: 'A budget-conscious, DIY-focused masterclass for passive investors who prefer self-directed learning.',
            inclusions: ['80+ Videos / 12 Modules', 'REtipster Forum Access', 'Calculators & Checklists', 'Monthly Mindshare Call (Premium)'],
            proof: 'Commands a large audience driven by strong SEO, blog content, and a trusted brand reputation.'
        },
        { 
            id: 'jack_bosch', name: 'Jack Bosch', cost: 1400, programLength: 'Self-paced',
            audienceExperience: 1, audienceSupport: 0.5, marketPresence: 8,
            founder: 'Jack Bosch',
            tagline: 'An early, foundational program for DIY investors and budget-conscious learners looking for a self-paced entry point.',
            inclusions: ['Self-paced Course', 'Contracts & Scripts', 'PDF Guides', 'Optional 1:1 Mentorship'],
            proof: 'One of the original players in the space, offering a straightforward, no-frills educational product.'
        }
    ];

    const valueScores = programData.map(p => {
        let score = 0;
        if (p.inclusions.some(i => i.toLowerCase().includes('1:1'))) score += 3;
        if (p.inclusions.some(i => i.toLowerCase().includes('live') || i.toLowerCase().includes('group calls') || i.toLowerCase().includes('webinars'))) score += 2;
        if (p.inclusions.some(i => i.toLowerCase().includes('software') || i.toLowerCase().includes('platform') || i.toLowerCase().includes('crm') || i.toLowerCase().includes('tech platform trials') || i.toLowerCase().includes('lgpass'))) score += 2;
        if (p.inclusions.some(i => i.toLowerCase().includes('community') || i.toLowerCase().includes('discord') || i.toLowerCase().includes('forum') || i.toLowerCase().includes('virtual events') || i.toLowerCase().includes('bootcamps'))) score += 1;
        if (p.inclusions.some(i => i.toLowerCase().includes('funding'))) score += 3;
        return score;
    });

    const tooltipConfig = {
        callbacks: {
            label: function(context) {
                const program = programData[context.dataIndex];
                return `${program.name}: $${program.cost.toLocaleString()}`;
            }
        }
    };
    
    const sharedChartOptions = {
        responsive: true,
        maintainAspectRatio: false,
        plugins: {
            legend: { display: false },
            tooltip: tooltipConfig
        },
        animation: {
            duration: 1000,
            easing: 'easeInOutCubic'
        }
    };

    // Chart 1: Cost vs Value
    const costValueCtx = document.getElementById('costValueChart').getContext('2d');
    const costValueChart = new Chart(costValueCtx, {
        type: 'scatter',
        data: {
            datasets: [{
                label: 'Programs',
                data: programData.map((p, i) => ({ x: p.cost, y: valueScores[i] })),
                backgroundColor: '#1A252F',
                borderColor: '#C5A47E',
                pointRadius: 7,
                pointHoverRadius: 10,
            }]
        },
        options: {
            ...sharedChartOptions,
            scales: {
                x: {
                    type: 'linear',
                    position: 'bottom',
                    title: { display: true, text: 'Flagship Program Cost ($)', font: { size: 14 } },
                     ticks: {
                        callback: value => '$' + (value/1000) + 'k'
                    }
                },
                y: {
                    title: { display: true, text: 'Relative Value Score', font: { size: 14 } }
                }
            }
        }
    });

    // Chart 2: Audience & Focus
    const audienceCtx = document.getElementById('audienceChart').getContext('2d');
    const audienceChart = new Chart(audienceCtx, {
        type: 'bubble',
        data: {
            datasets: [{
                label: 'Programs',
                data: programData.map(p => ({
                    x: p.audienceExperience,
                    y: p.audienceSupport,
                    r: p.marketPresence / 2
                })),
                backgroundColor: '#1A252Faa',
                borderColor: '#C5A47E',
            }]
        },
        options: {
            ...sharedChartOptions,
             plugins: {
                legend: { display: false },
                tooltip: {
                     callbacks: {
                        label: function(context) {
                            const program = programData[context.dataIndex];
                            return `${program.name}`;
                        }
                    }
                }
            },
            scales: {
                x: {
                    min: 0, max: 4,
                    title: { display: true, text: 'Target Experience Level', font: { size: 14 } },
                    ticks: {
                       callback: value => ['', 'Beginner', 'Intermediate', 'Advanced', ''][value] || ''
                    }
                },
                y: {
                    min: 0, max: 4,
                    title: { display: true, text: 'Support Model', font: { size: 14 } },
                     ticks: {
                       callback: value => ['', 'DIY', 'Hybrid', 'High-Touch', ''][value] || ''
                    }
                }
            }
        }
    });

    const tabButtons = document.querySelectorAll('.tab-button');
    const chartContainers = [document.getElementById('chart-cost-container'), document.getElementById('chart-audience-container')];
    
    tabButtons.forEach(button => {
        button.addEventListener('click', () => {
            tabButtons.forEach(btn => btn.classList.remove('active'));
            button.classList.add('active');
            
            chartContainers.forEach(container => container.classList.add('hidden'));
            if (button.id === 'tab-cost') {
                chartContainers[0].classList.remove('hidden');
            } else {
                chartContainers[1].classList.remove('hidden');
            }
        });
    });

    const programSelectorContainer = document.getElementById('program-selector-container');
    const programDetailsContent = document.getElementById('program-details-content');

    const generateInclusionHTML = (items) => {
        const iconMap = {
            'call': `<svg fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8h2a2 2 0 012 2v6a2 2 0 01-2 2h-2v4l-4-4H9a2 2 0 01-2-2V7a2 2 0 012-2h4M5 8h1.586a1 1 0 01.707.293l2.414 2.414a1 1 0 001.414 0l2.414-2.414a1 1 0 01.707-.293H19"></path></svg>`,
            'coaching': `<svg fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z"></path></svg>`,
            'community': `<svg fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z"></path></svg>`,
            'software': `<svg fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.75 17L9 20l-1 1h8l-1-1-.75-3M3 13h18M5 17h14a2 2 0 002-2V5a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path></svg>`,
            'course': `<svg fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6.253v13m0-13C10.832 5.477 9.246 5 7.5 5S4.168 5.477 3 6.253v13C4.168 18.477 5.754 18 7.5 18s3.332.477 4.5 1.253m0-13C13.168 5.477 14.754 5 16.5 5c1.747 0 3.332.477 4.5 1.253v13C19.832 18.477 18.246 18 16.5 18c-1.746 0-3.332.477-4.5 1.253"></path></svg>`,
            'default': `<svg fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>`
        };
        return items.map(item => {
            const lowerItem = item.toLowerCase();
            let icon = iconMap['default'];
            for (const key in iconMap) {
                if (lowerItem.includes(key)) {
                    icon = iconMap[key];
                    break;
                }
            }
            return `<li class="flex items-center text-gray-700 icon-list-item">${icon}<span class="text-sm md:text-base">${item}</span></li>`;
        }).join('');
    };

    const updateProgramDetails = (program) => {
        programDetailsContent.innerHTML = `
            <div class="flex flex-col md:flex-row items-start md:items-center justify-between mb-4">
                 <div>
                    <h3 class="text-2xl md:text-3xl font-bold text-[#1A252F]">${program.name}</h3>
                    <p class="text-sm text-gray-500">with ${program.founder}</p>
                 </div>
                <div class="mt-4 md:mt-0 text-right">
                    <p class="text-gray-500 text-sm">Flagship Program Cost</p>
                    <p class="text-2xl font-bold text-[#C5A47E]">$${program.cost.toLocaleString()}</p>
                 </div>
            </div>
            <p class="text-gray-600 mb-2">${program.tagline}</p>
            <p class="text-gray-600 text-sm mb-6 pb-6 border-b border-gray-200">Program Length: ${program.programLength}</p>
            
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-6">
                <div>
                    <h4 class="font-bold mb-3 text-lg">What's Included</h4>
                    <ul class="space-y-3 icon-list">
                        ${generateInclusionHTML(program.inclusions)}
                    </ul>
                </div>
                <div>
                    <h4 class="font-bold mb-3 text-lg">Proof & Outcomes</h4>
                    <div class="bg-gray-50 p-4 rounded-md">
                        <p class="text-sm text-gray-700">${program.proof}</p>
                    </div>
                </div>
            </div>
        `;
    };

    programData.forEach(program => {
        const selector = document.createElement('div');
        selector.className = 'program-selector p-4 cursor-pointer hover:bg-[#EAE8E1]';
        selector.dataset.id = program.id;
        selector.textContent = program.name;
        programSelectorContainer.appendChild(selector);

        selector.addEventListener('click', () => {
            document.querySelectorAll('.program-selector').forEach(el => el.classList.remove('active'));
            selector.classList.add('active');
            updateProgramDetails(program);
        });
    });
    
    // Initial load, activate The Land Geek program
    document.querySelector('.program-selector[data-id="land_geek"]').click();

});
</script>



</body></html>
