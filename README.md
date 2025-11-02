<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HOMEDIQ | Premium Home Healthcare & Recovery Services</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Use Inter font family -->
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap');
        body {
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
        }
        .text-primary { color: #059669; } /* Emerald 600 - slightly darker for contrast */
        .bg-primary { background-color: #10B981; } /* Emerald 500 */
        .bg-primary-dark { background-color: #059669; }
        .border-primary { border-color: #10B981; }

        /* Custom shadow for better lift */
        .card-shadow { box-shadow: 0 10px 15px -3px rgba(16, 185, 129, 0.1), 0 4px 6px -2px rgba(16, 185, 129, 0.05); }

        /* Animation for trust badges */
        @keyframes fadeInSlide {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .animate-trust { animation: fadeInSlide 0.7s ease-out forwards; }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <!-- Header & Navigation -->
    <header class="sticky top-0 z-50 bg-white shadow-lg">
        <div class="max-w-7xl mx-auto p-4 flex justify-between items-center">
            <a href="#" class="text-3xl font-extrabold text-primary tracking-tight">HOMEDIQ</a>
            <nav class="hidden lg:flex space-x-8 text-gray-600 font-medium">
                <a href="#services" class="hover:text-primary-dark transition duration-300">Our Services</a>
                <a href="#whyus" class="hover:text-primary-dark transition duration-300">Why HOMEDIQ</a>
                <a href="#clinical" class="hover:text-primary-dark transition duration-300">Clinical Assurance</a>
                <a href="#contact" class="hover:text-primary-dark transition duration-300">Contact</a>
            </nav>
            <a href="https://wa.me/918709554520?text=I%20am%20interested%20in%20HOMEDIQ%20home%20healthcare%20services." target="_blank" class="hidden sm:inline-flex items-center px-6 py-2 border border-primary-dark text-sm font-semibold rounded-full text-white bg-primary-dark hover:bg-emerald-700 transition duration-300 shadow-md">
                Book Care Now
            </a>
            <!-- Mobile Menu Button -->
            <button id="menu-button" class="lg:hidden p-2 text-gray-700 hover:text-primary rounded-lg focus:outline-none focus:ring-2 focus:ring-primary-dark">
                <!-- Menu Icon -->
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="w-6 h-6"><line x1="4" y1="12" x2="20" y2="12"></line><line x1="4" y1="6" x2="20" y2="6"></line><line x1="4" y1="18" x2="20" y2="18"></line></svg>
            </button>
        </div>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden lg:hidden bg-white border-t border-gray-200">
            <a href="#services" class="block py-3 px-4 text-gray-700 hover:bg-gray-50 border-b">Our Services</a>
            <a href="#whyus" class="block py-3 px-4 text-gray-700 hover:bg-gray-50 border-b">Why HOMEDIQ</a>
            <a href="#clinical" class="block py-3 px-4 text-gray-700 hover:bg-gray-50 border-b">Clinical Assurance</a>
            <a href="#contact" class="block py-3 px-4 text-gray-700 hover:bg-gray-50 border-b">Contact & Support</a>
            <a href="https://wa.me/918709554520?text=I%20am%20interested%20in%20HOMEDIQ%20home%20healthcare%20services." target="_blank" class="block text-center py-3 m-4 text-base font-semibold rounded-full text-white bg-primary hover:bg-primary-dark transition duration-300">
                Book Care Now
            </a>
        </div>
    </header>

    <main>
        <!-- Hero Section -->
        <section class="relative bg-white pt-16 pb-12 sm:pt-24 sm:pb-20 overflow-hidden">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="lg:grid lg:grid-cols-12 lg:gap-12 items-center">
                    <div class="lg:col-span-7 flex flex-col justify-center">
                        <span class="text-sm font-semibold uppercase text-primary tracking-widest mb-3">Rehab, Recovery Care</span>
                        <h2 class="text-5xl sm:text-6xl font-extrabold text-gray-900 leading-tight mb-6">
                            Expert Medical Care, Delivered to Your Home.
                        </h2>
                        <p class="mt-3 text-xl text-gray-600">
                            Skip the stress of the hospital. HOMEDIQ provides comprehensive, **tech-enabled clinical and rehabilitation support**, bringing quality healthcare to your doorstep in Bihar and Eastern India.
                        </p>
                        <div class="mt-10 flex flex-col space-y-4 sm:flex-row sm:space-y-0 sm:space-x-4">
                            <a href="#services" class="w-full sm:w-auto inline-flex items-center justify-center px-8 py-4 text-base font-bold rounded-full shadow-xl text-white bg-primary hover:bg-primary-dark transition duration-300 transform hover:scale-105">
                                View Care Plans
                            </a>
                            <a href="tel:+919241380109" class="w-full sm:w-auto inline-flex items-center justify-center px-8 py-4 border border-gray-300 text-base font-semibold rounded-full text-primary bg-white hover:bg-gray-100 transition duration-300 shadow-lg">
                                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="mr-2"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6.72-6.72 19.79 19.79 0 0 1-3.07-8.63A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"></path></svg>
                                Call for Assistance
                            </a>
                        </div>
                    </div>
                    <!-- Mock Illustration Panel -->
                    <div class="mt-12 lg:mt-0 lg:col-span-5 flex justify-center lg:justify-end">
                        <div class="relative w-full max-w-md h-96 bg-primary/10 rounded-3xl shadow-2xl p-6 flex items-center justify-center transform lg:translate-x-4 hover:shadow-primary/50 transition duration-500">
                            <!-- Placeholder for a complex medical illustration/icon or map of service area -->
                            <div class="absolute inset-0 bg-gradient-to-br from-white to-primary/5 rounded-3xl opacity-90"></div>
                            <div class="relative text-center z-10 p-4">
                                <svg xmlns="http://www.w3.org/2000/svg" width="80" height="80" viewBox="0 0 24 24" fill="none" stroke="#059669" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" class="mx-auto text-primary-dark animate-pulse"><path d="M20 10c0 6-8 12-8 12s-8-6-8-12a8 8 0 0 1 16 0Z"></path><circle cx="12" cy="10" r="3"></circle><path d="M16 17H8"></path><path d="M17 19H7"></path><path d="M19 21H5"></path></svg>
                                <p class="mt-4 text-2xl font-bold text-gray-900">Care in Your City</p>
                                <p class="text-md text-gray-600 mt-2">Currently serving Patna, Bihar. Expanding to Ranchi, Lucknow, and Kolkata soon.</p>
                                <button onclick="document.getElementById('service-check-input').focus()" class="mt-4 inline-flex items-center px-4 py-2 border border-transparent text-sm font-medium rounded-full text-white bg-primary-dark hover:bg-emerald-700 shadow-lg transition">Check Pin Code</button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Clinical Assurance / Doctor Supervision Section (NEW) -->
        <section id="clinical" class="py-16 sm:py-20 bg-white border-t border-gray-200">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="grid grid-cols-1 lg:grid-cols-3 gap-12 items-center">
                    <div class="lg:col-span-1">
                        <h2 class="text-4xl font-extrabold text-gray-900 leading-tight">
                            Clinical Assurance. Hospital Standards.
                        </h2>
                        <p class="mt-4 text-lg text-gray-600">
                            Every care plan is structured and monitored by our clinical directors and affiliated senior doctors to ensure the highest standards of safety and efficacy.
                        </p>
                        <a href="#team" class="mt-6 inline-block text-primary-dark font-semibold hover:text-emerald-700 transition duration-300">
                            Meet our Clinical Team &rarr;
                        </a>
                    </div>
                    <div class="lg:col-span-2 grid grid-cols-2 sm:grid-cols-4 gap-6">
                        <!-- Badge 1 -->
                        <div class="p-4 bg-gray-100 rounded-xl text-center animate-trust" style="animation-delay: 0s;">
                            <svg xmlns="http://www.w3.org/2000/svg" width="36" height="36" viewBox="0 0 24 24" fill="none" stroke="#059669" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="mx-auto mb-2"><path d="M11 19c-3.3 0-6-2.7-6-6s2.7-6 6-6 6 2.7 6 6-2.7 6-6 6z"></path><path d="M11 15v-4h2"></path></svg>
                            <p class="text-sm font-bold text-gray-900">ICU Protocol</p>
                            <p class="text-xs text-gray-500">Certified Setup</p>
                        </div>
                        <!-- Badge 2 -->
                        <div class="p-4 bg-gray-100 rounded-xl text-center animate-trust" style="animation-delay: 0.1s;">
                            <svg xmlns="http://www.w3.org/2000/svg" width="36" height="36" viewBox="0 0 24 24" fill="none" stroke="#059669" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="mx-auto mb-2"><path d="M4 14.8c1.7 1.7 4 2.2 6 2.2 2 0 4.3-.5 6-2.2"></path><path d="M10 14.8c1.7 1.7 4 2.2 6 2.2 2 0 4.3-.5 6-2.2"></path><path d="M16 14.8c1.7 1.7 4 2.2 6 2.2 2 0 4.3-.5 6-2.2"></path><path d="M22 14.8c1.7 1.7 4 2.2 6 2.2 2 0 4.3-.5 6-2.2"></path><path d="M2 14.8c1.7 1.7 4 2.2 6 2.2 2 0 4.3-.5 6-2.2"></path><path d="M8 14.8c1.7 1.7 4 2.2 6 2.2 2 0 4.3-.5 6-2.2"></path><circle cx="12" cy="12" r="10"></circle><path d="M12 8V12L15 14"></path></svg>
                            <p class="text-sm font-bold text-gray-900">24/7 Supervision</p>
                            <p class="text-xs text-gray-500">Remote Monitoring</p>
                        </div>
                        <!-- Badge 3 -->
                        <div class="p-4 bg-gray-100 rounded-xl text-center animate-trust" style="animation-delay: 0.2s;">
                            <svg xmlns="http://www.w3.org/2000/svg" width="36" height="36" viewBox="0 0 24 24" fill="none" stroke="#059669" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="mx-auto mb-2"><path d="M12 2L2 7l10 5 10-5-10-5z"></path><path d="M2 17l10 5 10-5"></path><path d="M2 12l10 5 10-5"></path></svg>
                            <p class="text-sm font-bold text-gray-900">100% Verified</p>
                            <p class="text-xs text-gray-500">Trained Staff</p>
                        </div>
                        <!-- Badge 4 -->
                        <div class="p-4 bg-gray-100 rounded-xl text-center animate-trust" style="animation-delay: 0.3s;">
                            <svg xmlns="http://www.w3.org/2000/svg" width="36" height="36" viewBox="0 0 24 24" fill="none" stroke="#059669" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="mx-auto mb-2"><rect x="2" y="7" width="20" height="15" rx="2" ry="2"></rect><polyline points="16 11 12 15 8 11"></polyline><path d="M12 7V3"></path><path d="M12 3H8"></path><path d="M12 3H16"></path></svg>
                            <p class="text-sm font-bold text-gray-900">Integrated Reporting</p>
                            <p class="text-xs text-gray-500">Digital Patient Records</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        
        <!-- Why Choose Us Section (Key Differentiators) -->
        <section id="whyus" class="py-16 sm:py-24 bg-primary-dark/95">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center mb-16">
                    <h2 class="text-4xl font-extrabold text-white sm:text-5xl">
                        The HOMEDIQ Advantage
                    </h2>
                    <p class="mt-4 text-xl text-emerald-200">
                        Blending Clinical Excellence with Local Trust and Technology.
                    </p>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                    <!-- Feature 1 -->
                    <div class="bg-white p-6 rounded-xl shadow-2xl text-center transform hover:scale-105 transition duration-300">
                        <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="#059669" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="mx-auto mb-4"><path d="M12 21.5V17"></path><path d="M12 17a2 2 0 0 1 2 2h0a2 2 0 0 1-2 2v0a2 2 0 0 1-2-2h0a2 2 0 0 1 2-2z"></path><path d="M12 15V3"></path><path d="M18 6L12 3L6 6"></path><path d="M18 6L12 9L6 6"></path></svg>
                        <h3 class="text-lg font-bold text-gray-900 mb-1">Trained Professionals</h3>
                        <p class="text-sm text-gray-600">Verified nurses, physiotherapists, and GDA staff ensure clinical safety and quality.</p>
                    </div>
                    <!-- Feature 2 -->
                    <div class="bg-white p-6 rounded-xl shadow-2xl text-center transform hover:scale-105 transition duration-300">
                        <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="#059669" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="mx-auto mb-4"><circle cx="12" cy="12" r="10"></circle><path d="M12 8V12L15 14"></path></svg>
                        <h3 class="text-lg font-bold text-gray-900 mb-1">24/7 Monitoring</h3>
                        <p class="text-sm text-gray-600">Tech-enabled patient monitoring (via future app) for real-time safety and care adjustments.</p>
                    </div>
                    <!-- Feature 3 -->
                    <div class="bg-white p-6 rounded-xl shadow-2xl text-center transform hover:scale-105 transition duration-300">
                        <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="#059669" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="mx-auto mb-4"><rect x="3" y="4" width="18" height="18" rx="2" ry="2"></rect><line x1="16" y1="2" x2="16" y2="6"></line><line x1="8" y1="2" x2="8" y2="6"></line><line x1="3" y1="10" x2="21" y2="10"></line></svg>
                        <h3 class="text-lg font-bold text-gray-900 mb-1">Affordable Care</h3>
                        <p class="text-sm text-gray-600">High-quality care and ICU setups at home, significantly reducing hospital expenditure.</p>
                    </div>
                    <!-- Feature 4 -->
                    <div class="bg-white p-6 rounded-xl shadow-2xl text-center transform hover:scale-105 transition duration-300">
                        <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="#059669" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="mx-auto mb-4"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"></path><path d="M8 12L11 15L16 10"></path></svg>
                        <h3 class="text-lg font-bold text-gray-900 mb-1">Localized Focus</h3>
                        <p class="text-sm text-gray-600">Dedicated service and deep understanding of healthcare needs in Bihar and Eastern India.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Services Section -->
        <section id="services" class="py-16 sm:py-24 bg-gray-50">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center mb-16">
                    <span class="text-sm font-semibold uppercase text-primary tracking-widest mb-2">Our Offerings</span>
                    <h2 class="text-4xl font-extrabold text-gray-900 sm:text-5xl mt-2">
                        Comprehensive Care Packages
                    </h2>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                    <!-- Service Card 1: Nursing Care -->
                    <div class="bg-white p-8 rounded-2xl card-shadow border-t-8 border-primary hover:border-primary-dark transition duration-300">
                        <div class="flex items-center space-x-4 mb-4">
                            <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="#059669" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="flex-shrink-0 text-primary-dark"><line x1="12" y1="18" x2="12" y2="22"></line><line x1="9" y1="21" x2="15" y2="21"></line><path d="M17 12V3H7v9l3 3h4l3-3z"></path></svg>
                            <h3 class="text-xl font-bold text-gray-900">24/7 Nursing Care</h3>
                        </div>
                        <p class="text-gray-600 text-base">Skilled nurses for post-operative recovery, wound care, medication management, injections, and overall patient monitoring.</p>
                        <ul class="mt-4 space-y-2 text-sm text-gray-700">
                            <li class="flex items-center"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="#10B981" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="mr-2 flex-shrink-0"><polyline points="20 6 9 17 4 12"></polyline></svg>Post-surgical Care</li>
                            <li class="flex items-center"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="#10B981" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="mr-2 flex-shrink-0"><polyline points="20 6 9 17 4 12"></polyline></svg>Chronic Disease Management</li>
                        </ul>
                    </div>
                    <!-- Service Card 2: Physiotherapy -->
                    <div class="bg-white p-8 rounded-2xl card-shadow border-t-8 border-primary hover:border-primary-dark transition duration-300">
                        <div class="flex items-center space-x-4 mb-4">
                            <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="#059669" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="flex-shrink-0 text-primary-dark"><circle cx="12" cy="5" r="1"></circle><path d="M12 22v-4l-3-3 3-3 3 3v4l-3 3"></path><path d="M16 16.2l-4-4-4 4"></path></svg>
                            <h3 class="text-xl font-bold text-gray-900">Home Physiotherapy</h3>
                        </div>
                        <p class="text-gray-600 text
