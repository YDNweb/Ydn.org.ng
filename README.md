<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Youths Development of Nigeria (YDN) - Let's Do It Together</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800&display=swap" rel="stylesheet">
    <style>
        /* Custom Tailwind Configuration for YDN's Colors */
        :root {
            --color-ydn-primary: #15803d; /* Tailwind green-700, reflecting the logo */
            --color-ydn-secondary: #facc15; /* Tailwind yellow-400/500, reflecting the logo */
            --color-ydn-dark: #1f2937; /* Gray-800 */
        }
        .text-ydn-primary { color: var(--color-ydn-primary); }
        .bg-ydn-primary { background-color: var(--color-ydn-primary); }
        .text-ydn-secondary { color: var(--color-ydn-secondary); }
        .bg-ydn-secondary { background-color: var(--color-ydn-secondary); }
        
        /* Apply Inter font family */
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f7f7f7;
        }
    </style>
</head>
<body class="text-gray-800 antialiased">

    <!-- Navigation Header -->
    <header class="bg-white shadow-md sticky top-0 z-10">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-4 flex justify-between items-center">
            <!-- Logo/Brand Section -->
            <a href="#" class="flex items-center space-x-2">
                <!-- Placeholder for YDN Logo (Green/Yellow circle) -->
                <div class="w-10 h-10 rounded-full bg-ydn-primary flex items-center justify-center font-bold text-white text-lg">YDN</div>
                <span class="text-xl font-extrabold text-ydn-primary hidden sm:block">YOUTHS DEVELOPMENT OF NIGERIA</span>
                <span class="text-xl font-extrabold text-ydn-primary block sm:hidden">YDN</span>
            </a>
            
            <!-- Navigation Links -->
            <nav class="hidden md:flex space-x-6 text-gray-600 font-medium">
                <a href="#mission" class="hover:text-ydn-primary transition duration-150">Our Mission</a>
                <a href="#programs" class="hover:text-ydn-primary transition duration-150">Programs</a>
                <a href="#join" class="hover:text-ydn-primary transition duration-150">Join Us</a>
                <a href="#contact" class="hover:text-ydn-primary transition duration-150">Contact</a>
            </nav>
            
            <!-- Mobile Menu Placeholder (simple for single page) -->
            <button class="md:hidden text-ydn-primary focus:outline-none p-2 rounded-md hover:bg-gray-100">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path></svg>
            </button>
        </div>
    </header>

    <main>
        <!-- Hero Section -->
        <section class="bg-gray-900 bg-cover bg-center" style="background-image: url('https://placehold.co/1920x800/15803d/ffffff?text=Empowering+Nigerian+Youths');">
            <div class="bg-black bg-opacity-50 py-24 md:py-36">
                <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center text-white">
                    <p class="text-xl sm:text-2xl font-semibold mb-4 text-ydn-secondary">EST: 2025</p>
                    <h1 class="text-4xl sm:text-6xl font-extrabold leading-tight mb-6 tracking-tight">
                        Youth Development is the Key to Nigeria's Success.
                    </h1>
                    <p class="text-xl mb-8 max-w-2xl mx-auto">
                        We are the Youths Development of Nigeria (YDN).
                        <span class="font-bold text-ydn-secondary block mt-2">LET'S DO IT TOGETHER!</span>
                    </p>
                    <a href="#join" class="bg-ydn-secondary text-gray-900 font-bold py-3 px-8 rounded-full shadow-lg hover:bg-yellow-500 transition duration-300 transform hover:scale-105 inline-block">
                        Become a Member Today
                    </a>
                </div>
            </div>
        </section>

        <!-- Mission Section -->
        <section id="mission" class="py-16 md:py-24 bg-white">
            <div class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
                <h2 class="text-3xl sm:text-4xl font-extrabold text-ydn-primary mb-4">Our Mission: Transforming Nigeria</h2>
                <p class="text-lg text-gray-600 mb-8">
                    Youth development is the key to Nigeria's success. We are dedicated to creating a vibrant future by empowering the youth with skills, opportunities, and a platform for community action.
                </p>
                <div class="grid md:grid-cols-3 gap-8 text-left">
                    <div class="p-6 rounded-xl shadow-lg hover:shadow-xl transition duration-300 border-t-4 border-ydn-primary">
                        <h3 class="text-xl font-bold text-gray-900 mb-3">Empowerment</h3>
                        <p class="text-gray-600">Providing the tools, training, and resources necessary for every young Nigerian to reach their full potential.</p>
                    </div>
                    <div class="p-6 rounded-xl shadow-lg hover:shadow-xl transition duration-300 border-t-4 border-ydn-primary">
                        <h3 class="text-xl font-bold text-gray-900 mb-3">Community</h3>
                        <p class="text-gray-600">Fostering a strong network where youth can collaborate, share ideas, and drive positive change locally and nationally.</p>
                    </div>
                    <div class="p-6 rounded-xl shadow-lg hover:shadow-xl transition duration-300 border-t-4 border-ydn-primary">
                        <h3 class="text-xl font-bold text-gray-900 mb-3">Impact</h3>
                        <p class="text-gray-600">Creating measurable, long-lasting impact in key areas like education, skills acquisition, and civic engagement.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Programs Section (Mock Content + Gemini Feature) -->
        <section id="programs" class="py-16 md:py-24 bg-ydn-primary text-white">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <h2 class="text-3xl sm:text-4xl font-extrabold text-center mb-12">Our Core Programs</h2>
                
                <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8 mb-16">
                    <!-- Program 1: Skill Acquisition -->
                    <div class="bg-white text-gray-800 p-6 rounded-xl shadow-xl">
                        <div class="text-ydn-primary text-4xl mb-4">🛠️</div>
                        <h3 class="text-2xl font-bold mb-3">Skill Acquisition Workshops</h3>
                        <p class="text-gray-600">Hands-on training in in-demand digital and vocational skills, preparing youth for the modern economy. From coding to carpentry, we bridge the skill gap.</p>
                    </div>
                    <!-- Program 2: Community Service -->
                    <div class="bg-white text-gray-800 p-6 rounded-xl shadow-xl">
                        <div class="text-ydn-primary text-4xl mb-4">🤝</div>
                        <h3 class="text-2xl font-bold mb-3">Community & Civic Engagement</h3>
                        <p class="text-gray-600">Mobilizing youth for volunteer work, environmental projects, and civic education to promote responsible citizenship.</p>
                    </div>
                    <!-- Program 3: Leadership Development -->
                    <div class="bg-white text-gray-800 p-6 rounded-xl shadow-xl">
                        <div class="text-ydn-primary text-4xl mb-4">🏆</div>
                        <h3 class="text-2xl font-bold mb-3">Leadership and Mentorship</h3>
                        <p class="text-gray-600">Connecting aspiring youth leaders with experienced mentors to cultivate leadership qualities and entrepreneurial mindsets.</p>
                    </div>
                </div>

                <!-- NEW: AI Program Idea Generator Section -->
                <div class="max-w-4xl mx-auto mt-16 p-6 sm:p-8 bg-white rounded-xl shadow-2xl text-gray-800">
                    <h3 class="text-2xl sm:text-3xl font-extrabold text-ydn-primary mb-4 text-center">
                        ✨ AI Program Idea Generator
                    </h3>
                    <p class="text-center text-gray-600 mb-6">
                        Need an innovative project idea? Enter a topic and state/city (e.g., "Youth employment initiative in Lagos") to get a grounded program proposal.
                    </p>

                    <div class="flex flex-col sm:flex-row space-y-4 sm:space-y-0 sm:space-x-4">
                        <input type="text" id="ideaPrompt" placeholder="E.g., Digital literacy training for rural youth in Kano" class="flex-grow p-3 border border-gray-300 rounded-lg focus:ring-ydn-primary focus:border-ydn-primary" required>
                        <button id="generateButton" onclick="generateIdea()" class="bg-ydn-primary text-white font-bold py-3 px-6 rounded-lg shadow-md hover:bg-green-800 transition duration-300 flex-shrink-0">
                            Generate Idea
                        </button>
                    </div>

                    <!-- Loading and Output Area -->
                    <div id="ideaOutput" class="mt-8 p-4 bg-gray-50 rounded-lg border border-gray-200 min-h-[100px] hidden">
                        <div id="loadingIndicator" class="text-center text-gray-500 hidden">
                            <svg class="animate-spin h-5 w-5 text-ydn-primary mx-auto mb-2" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24">
                                <circle class="opacity-25" cx="12" cy="12" r="10" stroke="currentColor" stroke-width="4"></circle>
                                <path class="opacity-75" fill="currentColor" d="M4 12a8 8 0 018-8V0C5.373 0 0 5.373 0 12h4zm2 5.291A7.962 7.962 0 014 12H0c0 3.042 1.135 5.824 3 7.938l3-2.647z"></path>
                            </svg>
                            Generating brilliant program idea...
                        </div>
                        <div id="resultContent" class="prose max-w-none">
                            <!-- LLM result will be inserted here -->
                        </div>
                        <div id="sourceAttributions" class="mt-4 pt-4 border-t border-gray-200 text-xs text-gray-500 hidden">
                            <!-- Sources will be inserted here -->
                        </div>
                    </div>
                </div>
                <!-- END: AI Program Idea Generator Section -->

            </div>
        </section>

        <!-- Call to Action / Join Us Section -->
        <section id="join" class="py-16 md:py-24 bg-ydn-secondary">
            <div class="max-w-3xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
                <h2 class="text-3xl sm:text-4xl font-extrabold text-gray-900 mb-4">Join Us! Make a Difference.</h2>
                <p class="text-lg text-gray-700 mb-8">
                    Become a member of YDN and make a difference in your community. Let your voice be heard and your potential be realized.
                </p>
                <!-- Simple mock registration form/link -->
                <form action="#" class="bg-white p-6 rounded-xl shadow-xl">
                    <input type="email" placeholder="Enter your email address to get started" class="w-full p-3 mb-4 border border-gray-300 rounded-md focus:ring-ydn-primary focus:border-ydn-primary" required>
                    <button type="submit" class="w-full bg-ydn-primary text-white font-bold py-3 rounded-md hover:bg-green-800 transition duration-300">
                        Sign Up for Updates
                    </button>
                    <p class="text-sm text-gray-500 mt-3">We promise not to spam your inbox.</p>
                </form>
            </div>
        </section>

    </main>

    <!-- Footer / Contact Section -->
    <footer id="contact" class="bg-gray-800 text-white py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid md:grid-cols-4 gap-8 border-b border-gray-700 pb-8 mb-8">
                <!-- Brand Info -->
                <div>
                    <h4 class="text-2xl font-extrabold text-ydn-secondary mb-3">YDN</h4>
                    <p class="text-gray-400 text-sm">Youths Development of Nigeria. Let's Do It Together.</p>
                    <p class="text-gray-500 text-xs mt-2">EST: 2025</p>
                </div>
                
                <!-- Quick Links -->
                <div>
                    <h4 class="text-lg font-semibold mb-3 text-white">Quick Links</h4>
                    <ul class="space-y-2 text-gray-400 text-sm">
                        <li><a href="#mission" class="hover:text-ydn-secondary transition duration-150">Our Mission</a></li>
                        <li><a href="#programs" class="hover:text-ydn-secondary transition duration-150">Programs</a></li>
                        <li><a href="#join" class="hover:text-ydn-secondary transition duration-150">Get Involved</a></li>
                        <li><a href="#contact" class="hover:text-ydn-secondary transition duration-150">Contact Us</a></li>
                    </ul>
                </div>

                <!-- Contact Information -->
                <div class="md:col-span-2">
                    <h4 class="text-lg font-semibold mb-3 text-white">Contact Information</h4>
                    <p class="flex items-center space-x-2 text-gray-400 mb-2">
                        <!-- Icon Placeholder for Email -->
                        <span>📧</span>
                        <a href="mailto:youthsdevelopmentofnigeria@gmail.com" class="hover:text-ydn-secondary transition duration-150">youthsdevelopmentofnigeria@gmail.com</a>
                    </p>
                    <p class="flex items-center space-x-2 text-gray-400 mb-2">
                        <!-- Icon Placeholder for Phone 1 -->
                        <span>📞</span>
                        <a href="tel:09063734367" class="hover:text-ydn-secondary transition duration-150">09063734367</a>
                    </p>
                    <p class="flex items-center space-x-2 text-gray-400">
                        <!-- Icon Placeholder for Phone 2 -->
                        <span>📱</span>
                        <a href="tel:07081921262" class="hover:text-ydn-secondary transition duration-150">07081921262</a>
                    </p>
                    <p class="text-gray-500 text-sm mt-4">We aim to respond to all inquiries within 24 hours.</p>
                </div>
            </div>

            <div class="text-center text-gray-500 text-sm">
                &copy; 2025 Youths Development of Nigeria (YDN). All Rights Reserved.
            </div>
        </div>
    </footer>

    <!-- JavaScript for Gemini API Interaction -->
    <script>
        const API_KEY = ""; // Provided by environment
        const API_URL = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.5-flash-preview-09-2025:generateContent?key=${API_KEY}`;
        
        // Element references
        const ideaPromptInput = document.getElementById('ideaPrompt');
        const generateButton = document.getElementById('generateButton');
        const ideaOutputDiv = document.getElementById('ideaOutput');
        const loadingIndicator = document.getElementById('loadingIndicator');
        const resultContentDiv = document.getElementById('resultContent');
        const sourceAttributionsDiv = document.getElementById('sourceAttributions');

        /**
         * Retries a failed fetch call with exponential backoff.
         * @param {function} fn - The function to retry (e.g., fetch).
         * @param {Array} args - Arguments to pass to the function.
         * @param {number} retries - Number of retries remaining.
         */
        async function fetchWithBackoff(fn, args, retries = 5, delay = 1000) {
            try {
                const response = await fn(...args);
                if (!response.ok) {
                    throw new Error(`HTTP error! status: ${response.status}`);
                }
                return response;
            } catch (error) {
                if (retries === 0) {
                    throw error;
                }
                await new Promise(resolve => setTimeout(resolve, delay));
                return fetchWithBackoff(fn, args, retries - 1, delay * 2);
            }
        }

        async function generateIdea() {
            const userQuery = ideaPromptInput.value.trim();
            if (!userQuery) {
                alert("Please enter a topic for the program idea.");
                return;
            }

            // UI State: Show loading, hide previous results
            ideaOutputDiv.classList.remove('hidden');
            resultContentDiv.innerHTML = '';
            sourceAttributionsDiv.innerHTML = '';
            sourceAttributionsDiv.classList.add('hidden');
            loadingIndicator.classList.remove('hidden');
            generateButton.disabled = true;
            generateButton.textContent = 'Generating...';

            const systemPrompt = `You are a visionary youth development program specialist for Nigeria. Your goal is to create a detailed, realistic, and highly impactful program proposal based on the user's request. 
            The output MUST be formatted using Markdown headings (##) and bullet points. The proposal must be tailored to the Nigerian context and include the following sections:
            1. Program Title
            2. Problem Statement (1-2 sentences)
            3. Program Objectives (3-5 measurable points)
            4. Target Audience
            5. Key Activities (A detailed, step-by-step list of what the program will do)
            6. Estimated Resources (A brief note on staffing, technology, or facilities required).`;
            
            const fullQuery = `Generate a comprehensive youth development program proposal for the following request, ensuring all details are highly relevant to Nigeria: ${userQuery}`;

            const payload = {
                contents: [{ parts: [{ text: fullQuery }] }],
                tools: [{ "google_search": {} }],
                systemInstruction: { parts: [{ text: systemPrompt }] },
            };

            try {
                const response = await fetchWithBackoff(fetch, [API_URL, {
                    method: 'POST',
                    headers: { 'Content-Type': 'application/json' },
                    body: JSON.stringify(payload)
                }]);

                const result = await response.json();
                const candidate = result.candidates?.[0];

                if (candidate && candidate.content?.parts?.[0]?.text) {
                    const text = candidate.content.parts[0].text;
                    resultContentDiv.innerHTML = convertMarkdownToHtml(text); // Use helper function for formatting
                    
                    let sources = [];
                    const groundingMetadata = candidate.groundingMetadata;
                    if (groundingMetadata && groundingMetadata.groundingAttributions) {
                        sources = groundingMetadata.groundingAttributions
                            .map(attribution => ({
                                uri: attribution.web?.uri,
                                title: attribution.web?.title,
                            }))
                            .filter(source => source.uri && source.title);
                    }

                    if (sources.length > 0) {
                        sourc
