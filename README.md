<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nova Creations Codes - Professional Web Development Services</title>
    <meta name="description" content="Get fully completed websites at cheaper prices. Fast, reliable, professional web development, design, and app building services by Nova Creations Codes.">
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap');
        
        * {
            font-family: 'Inter', sans-serif;
        }
        
        .gradient-bg {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        }
        
        .hero-pattern {
            background-image: url("data:image/svg+xml,%3Csvg width='60' height='60' viewBox='0 0 60 60' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='none' fill-rule='evenodd'%3E%3Cg fill='%23ffffff' fill-opacity='0.1'%3E%3Ccircle cx='30' cy='30' r='2'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E");
        }
        
        .card-hover {
            transition: all 0.3s ease;
        }
        
        .card-hover:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
        }
        
        .star-rating {
            color: #fbbf24;
        }
        
        .whatsapp-float {
            position: fixed;
            width: 60px;
            height: 60px;
            bottom: 40px;
            right: 40px;
            background-color: #25d366;
            color: #FFF;
            border-radius: 50px;
            text-align: center;
            font-size: 30px;
            box-shadow: 2px 2px 3px #999;
            z-index: 100;
            transition: all 0.3s ease;
        }
        
        .whatsapp-float:hover {
            transform: scale(1.1);
        }
        
        .whatsapp-float i {
            margin-top: 16px;
        }
        
        .smooth-scroll {
            scroll-behavior: smooth;
        }
        
        .section-padding {
            padding: 80px 0;
        }
        
        .nav-link {
            transition: color 0.3s ease;
        }
        
        .nav-link:hover {
            color: #667eea;
        }
    </style>
</head>
<body class="smooth-scroll">
    <!-- Navigation -->
    <nav class="bg-white shadow-lg fixed w-full top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16">
                <div class="flex items-center">
                    <div class="flex-shrink-0">
                        <h1 class="text-2xl font-bold text-gray-800">Nova Creations Codes</h1>
                    </div>
                </div>
                <div class="hidden md:flex items-center space-x-8">
                    <a href="#home" class="nav-link text-gray-700 hover:text-blue-600 px-3 py-2 text-sm font-medium">Home</a>
                    <a href="#services" class="nav-link text-gray-700 hover:text-blue-600 px-3 py-2 text-sm font-medium">Services</a>
                    <a href="#reviews" class="nav-link text-gray-700 hover:text-blue-600 px-3 py-2 text-sm font-medium">Reviews</a>
                    <a href="#about" class="nav-link text-gray-700 hover:text-blue-600 px-3 py-2 text-sm font-medium">About</a>
                    <a href="#contact" class="nav-link text-gray-700 hover:text-blue-600 px-3 py-2 text-sm font-medium">Contact</a>
                    <a href="#terms" class="nav-link text-gray-700 hover:text-blue-600 px-3 py-2 text-sm font-medium">Terms</a>
                </div>
                <div class="md:hidden flex items-center">
                    <button id="mobile-menu-btn" class="text-gray-700 hover:text-blue-600 focus:outline-none">
                        <i class="fas fa-bars text-xl"></i>
                    </button>
                </div>
            </div>
        </div>
        <!-- Mobile menu -->
        <div id="mobile-menu" class="md:hidden hidden bg-white border-t">
            <div class="px-2 pt-2 pb-3 space-y-1">
                <a href="#home" class="block px-3 py-2 text-gray-700 hover:text-blue-600">Home</a>
                <a href="#services" class="block px-3 py-2 text-gray-700 hover:text-blue-600">Services</a>
                <a href="#reviews" class="block px-3 py-2 text-gray-700 hover:text-blue-600">Reviews</a>
                <a href="#about" class="block px-3 py-2 text-gray-700 hover:text-blue-600">About</a>
                <a href="#contact" class="block px-3 py-2 text-gray-700 hover:text-blue-600">Contact</a>
                <a href="#terms" class="block px-3 py-2 text-gray-700 hover:text-blue-600">Terms</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="gradient-bg hero-pattern section-padding mt-16">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <div class="text-white">
                <h1 class="text-4xl md:text-6xl font-bold mb-6">Get a Fully Completed Website at Cheaper Prices</h1>
                <p class="text-xl md:text-2xl mb-8 opacity-90">Fast, Reliable, Professional</p>
                <p class="text-lg mb-10 max-w-3xl mx-auto opacity-80">
                    Transform your business with stunning, fully functional websites that don't break the bank. 
                    We deliver professional web solutions tailored to your needs.
                </p>
                <button onclick="scrollToSection('contact')" class="bg-white text-blue-600 px-8 py-4 rounded-full text-lg font-semibold hover:bg-gray-100 transition duration-300 shadow-lg">
                    Get Your Website Now
                </button>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="section-padding bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold text-gray-800 mb-4">Our Services</h2>
                <p class="text-xl text-gray-600 max-w-2xl mx-auto">
                    We offer comprehensive digital solutions to help your business thrive online
                </p>
            </div>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
                <div class="bg-white p-8 rounded-xl shadow-lg card-hover text-center">
                    <div class="w-16 h-16 bg-blue-100 rounded-full flex items-center justify-center mx-auto mb-6">
                        <i class="fas fa-code text-2xl text-blue-600"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-4 text-gray-800">Web Development</h3>
                    <p class="text-gray-600">Custom websites built with modern technologies, optimized for performance and user experience.</p>
                </div>
                
                <div class="bg-white p-8 rounded-xl shadow-lg card-hover text-center">
                    <div class="w-16 h-16 bg-purple-100 rounded-full flex items-center justify-center mx-auto mb-6">
                        <i class="fas fa-palette text-2xl text-purple-600"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-4 text-gray-800">Web Design</h3>
                    <p class="text-gray-600">Beautiful, responsive designs that capture your brand essence and engage your audience.</p>
                </div>
                
                <div class="bg-white p-8 rounded-xl shadow-lg card-hover text-center">
                    <div class="w-16 h-16 bg-green-100 rounded-full flex items-center justify-center mx-auto mb-6">
                        <i class="fas fa-mobile-alt text-2xl text-green-600"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-4 text-gray-800">App Building</h3>
                    <p class="text-gray-600">Mobile applications that bring your business to your customers' fingertips.</p>
                </div>
                
                <div class="bg-white p-8 rounded-xl shadow-lg card-hover text-center">
                    <div class="w-16 h-16 bg-orange-100 rounded-full flex items-center justify-center mx-auto mb-6">
                        <i class="fas fa-cogs text-2xl text-orange-600"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-4 text-gray-800">Personal Customization</h3>
                    <p class="text-gray-600">Tailored solutions designed specifically for your unique business requirements and goals.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Reviews Section -->
    <section id="reviews" class="section-padding">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold text-gray-800 mb-4">Client Reviews</h2>
                <p class="text-xl text-gray-600">See what our satisfied clients have to say</p>
            </div>
            
            <div id="reviews-container" class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Reviews will be populated by JavaScript -->
            </div>
            
            <!-- Admin Panel for Reviews (Hidden by default) -->
            <div id="admin-panel" class="mt-12 bg-gray-100 p-6 rounded-lg hidden">
                <h3 class="text-xl font-semibold mb-4">Add New Review</h3>
                <form id="review-form" class="space-y-4">
                    <input type="text" id="client-name" placeholder="Client Name" class="w-full p-3 border rounded-lg" required>
                    <input type="number" id="rating" placeholder="Rating (1-5)" min="1" max="5" class="w-full p-3 border rounded-lg" required>
                    <textarea id="review-text" placeholder="Review Text" class="w-full p-3 border rounded-lg h-24" required></textarea>
                    <button type="submit" class="bg-blue-600 text-white px-6 py-3 rounded-lg hover:bg-blue-700">Add Review</button>
                </form>
            </div>
            
            <div class="text-center mt-8">
                <button id="toggle-admin" class="text-blue-600 hover:text-blue-800 text-sm">Admin Panel</button>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="section-padding bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid lg:grid-cols-2 gap-12 items-center">
                <div>
                    <h2 class="text-4xl font-bold text-gray-800 mb-6">About Nova Creations Codes</h2>
                    <div class="space-y-6 text-gray-600">
                        <p class="text-lg">
                            Founded by <strong class="text-gray-800">Astik Sharma</strong>, Nova Creations Codes was born from a vision to make professional web development accessible to businesses of all sizes.
                        </p>
                        <p>
                            We believe that every business deserves a stunning online presence without the hefty price tag. Our mission is to deliver high-quality, fully functional websites that help our clients succeed in the digital world.
                        </p>
                        <p>
                            With a focus on modern design, cutting-edge technology, and exceptional customer service, we've helped numerous businesses establish their online presence and grow their digital footprint.
                        </p>
                        <p>
                            At Nova Creations Codes, we don't just build websites – we create digital experiences that drive results and exceed expectations.
                        </p>
                    </div>
                </div>
                <div class="text-center">
                    <div class="bg-white p-8 rounded-xl shadow-lg">
                        <div class="w-32 h-32 bg-gradient-to-r from-blue-500 to-purple-600 rounded-full mx-auto mb-6 flex items-center justify-center">
                            <span class="text-white text-4xl font-bold">AS</span>
                        </div>
                        <h3 class="text-2xl font-semibold text-gray-800 mb-2">Astik Sharma</h3>
                        <p class="text-blue-600 font-medium mb-4">Founder & Lead Developer</p>
                        <p class="text-gray-600">
                            Passionate about creating digital solutions that make a difference in businesses and people's lives.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="section-padding">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold text-gray-800 mb-4">Get In Touch</h2>
                <p class="text-xl text-gray-600">Ready to start your project? Let's discuss your needs</p>
            </div>
            
            <div class="grid lg:grid-cols-2 gap-12">
                <div>
                    <h3 class="text-2xl font-semibold mb-6 text-gray-800">Contact Information</h3>
                    <div class="space-y-6">
                        <div class="flex items-center">
                            <div class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center mr-4">
                                <i class="fas fa-phone text-blue-600"></i>
                            </div>
                            <div>
                                <p class="font-medium text-gray-800">Phone</p>
                                <a href="tel:+916260943446" class="text-blue-600 hover:text-blue-800">+91 6260943446</a>
                            </div>
                        </div>
                        
                        <div class="flex items-center">
                            <div class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center mr-4">
                                <i class="fas fa-envelope text-blue-600"></i>
                            </div>
                            <div>
                                <p class="font-medium text-gray-800">Email</p>
                                <a href="mailto:ashuv6131@gmail.com" class="text-blue-600 hover:text-blue-800">ashuv6131@gmail.com</a>
                            </div>
                        </div>
                        
                        <div class="flex items-center">
                            <div class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center mr-4">
                                <i class="fab fa-instagram text-blue-600"></i>
                            </div>
                            <div>
                                <p class="font-medium text-gray-800">Instagram</p>
                                <a href="https://instagram.com/astik_sharma" target="_blank" rel="noopener noreferrer" class="text-blue-600 hover:text-blue-800">@astik_sharma</a>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div>
                    <form id="contact-form" class="space-y-6">
                        <div>
                            <label for="name" class="block text-sm font-medium text-gray-700 mb-2">Name</label>
                            <input type="text" id="name" name="name" required class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-transparent">
                        </div>
                        
                        <div>
                            <label for="email" class="block text-sm font-medium text-gray-700 mb-2">Email</label>
                            <input type="email" id="email" name="email" required class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-transparent">
                        </div>
                        
                        <div>
                            <label for="message" class="block text-sm font-medium text-gray-700 mb-2">Message</label>
                            <textarea id="message" name="message" rows="5" required class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-transparent"></textarea>
                        </div>
                        
                        <button type="submit" class="w-full bg-blue-600 text-white py-3 px-6 rounded-lg hover:bg-blue-700 transition duration-300 font-semibold">
                            Send Message
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Terms & Conditions Section -->
    <section id="terms" class="section-padding bg-gray-50">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-4xl font-bold text-gray-800 mb-8 text-center">Terms & Conditions</h2>
            
            <div class="bg-white p-8 rounded-xl shadow-lg">
                <div class="space-y-6 text-gray-600">
                    <div>
                        <h3 class="text-xl font-semibold text-gray-800 mb-3">1. Service Charges</h3>
                        <p>All service charges are non-refundable after project initiation. Once work has begun on your project, no refunds will be provided regardless of project status or completion.</p>
                    </div>
                    
                    <div>
                        <h3 class="text-xl font-semibold text-gray-800 mb-3">2. Project Timelines</h3>
                        <p>Project timelines may vary depending on project scope, complexity, and client requirements. While we strive to meet all agreed-upon deadlines, Nova Creations Codes reserves the right to adjust timelines as necessary to ensure quality delivery.</p>
                    </div>
                    
                    <div>
                        <h3 class="text-xl font-semibold text-gray-800 mb-3">3. Service Refusal Rights</h3>
                        <p>Nova Creations Codes reserves the right to refuse service to any client for any reason, including but not limited to inappropriate behavior, unrealistic expectations, or projects that conflict with our values and capabilities.</p>
                    </div>
                    
                    <div>
                        <h3 class="text-xl font-semibold text-gray-800 mb-3">4. Client Responsibilities</h3>
                        <p>Clients must provide accurate project requirements and timely feedback throughout the development process. Delays in client response may result in project timeline extensions. Clear communication and prompt feedback are essential for successful project completion.</p>
                    </div>
                    
                    <div>
                        <h3 class="text-xl font-semibold text-gray-800 mb-3">5. Intellectual Property</h3>
                        <p>Upon full payment, clients will own the rights to their custom website design and content. However, Nova Creations Codes retains the right to showcase completed work in our portfolio unless otherwise agreed upon in writing.</p>
                    </div>
                    
                    <div>
                        <h3 class="text-xl font-semibold text-gray-800 mb-3">6. Limitation of Liability</h3>
                        <p>Nova Creations Codes' liability is limited to the amount paid for services. We are not responsible for any indirect, incidental, or consequential damages arising from the use of our services.</p>
                    </div>
                </div>
                
                <div class="mt-8 pt-6 border-t border-gray-200">
                    <p class="text-sm text-gray-500">
                        Last updated: <span id="last-updated"></span><br>
                        By engaging our services, you agree to these terms and conditions.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid md:grid-cols-3 gap-8">
                <div>
                    <h3 class="text-2xl font-bold mb-4">Nova Creations Codes</h3>
                    <p class="text-gray-300 mb-4">Professional web development services at affordable prices. Fast, reliable, and tailored to your needs.</p>
                    <div class="flex space-x-4">
                        <a href="https://instagram.com/astik_sharma" target="_blank" rel="noopener noreferrer" class="text-gray-300 hover:text-white">
                            <i class="fab fa-instagram text-xl"></i>
                        </a>
                    </div>
                </div>
                
                <div>
                    <h4 class="text-lg font-semibold mb-4">Quick Links</h4>
                    <ul class="space-y-2">
                        <li><a href="#home" class="text-gray-300 hover:text-white">Home</a></li>
                        <li><a href="#services" class="text-gray-300 hover:text-white">Services</a></li>
                        <li><a href="#about" class="text-gray-300 hover:text-white">About</a></li>
                        <li><a href="#contact" class="text-gray-300 hover:text-white">Contact</a></li>
                        <li><a href="#terms" class="text-gray-300 hover:text-white">Terms & Conditions</a></li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="text-lg font-semibold mb-4">Contact Info</h4>
                    <div class="space-y-2 text-gray-300">
                        <p><i class="fas fa-phone mr-2"></i> +91 6260943446</p>
                        <p><i class="fas fa-envelope mr-2"></i> ashuv6131@gmail.com</p>
                        <p><i class="fab fa-instagram mr-2"></i> @_astik_sharma_</p>
                    </div>
                </div>
            </div>
            
            <div class="border-t border-gray-700 mt-8 pt-8 text-center">
                <p class="text-gray-300">&copy; 2024 Nova Creations Codes. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <!-- WhatsApp Float Button -->
    <a href="https://wa.me/916260943446" target="_blank" rel="noopener noreferrer" class="whatsapp-float">
        <i class="fab fa-whatsapp"></i>
    </a>

    <script>
        // Mobile menu toggle
        document.getElementById('mobile-menu-btn').addEventListener('click', function() {
            const mobileMenu = document.getElementById('mobile-menu');
            mobileMenu.classList.toggle('hidden');
        });

        // Smooth scrolling function
        function scrollToSection(sectionId) {
            document.getElementById(sectionId).scrollIntoView({
                behavior: 'smooth'
            });
        }

        // Contact form handling
        document.getElementById('contact-form').addEventListener('submit', function(e) {
            e.preventDefault();
            
            const name = document.getElementById('name').value;
            const email = document.getElementById('email').value;
            const message = document.getElementById('message').value;
            
            // Simulate form submission
            alert(Thank you, ${name}! Your message has been received. We'll get back to you soon at ${email}.);
            
            // Reset form
            this.reset();
        });

        // Reviews system
        let reviews = [
            {
                name: "Ankit Tiwari",
                rating: 5,
                text: "Excellent service! Nova Creations Codes delivered exactly what I needed for my business website. Professional, fast, and affordable.",
                id: 1
            },
            {
                name: "Harshit Chaursia",
                rating: 5,
                text: "Amazing work on my e-commerce site. The design is beautiful and the functionality is perfect. Highly recommend!",
                id: 2
            },
            {
                name: "Ankit Sahu",
                rating: 4,
                text: "Great experience working with Astik. The website looks professional and loads quickly. Very satisfied with the results.",
                id: 3
            }
        ];

        function renderReviews() {
            const container = document.getElementById('reviews-container');
            container.innerHTML = '';
            
            reviews.forEach(review => {
                const reviewCard = document.createElement('div');
                reviewCard.className = 'bg-white p-6 rounded-xl shadow-lg card-hover';
                
                const stars = '★'.repeat(review.rating) + '☆'.repeat(5 - review.rating);
                
                reviewCard.innerHTML = `
                    <div class="flex items-center mb-4">
                        <div class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center mr-4">
                            <span class="text-blue-600 font-semibold">${review.name.charAt(0)}</span>
                        </div>
                        <div>
                            <h4 class="font-semibold text-gray-800">${review.name}</h4>
                            <div class="star-rating text-lg">${stars}</div>
                        </div>
                    </div>
                    <p class="text-gray-600">"${review.text}"</p>
                `;
                
                container.appendChild(reviewCard);
            });
        }

        // Admin panel for reviews
        document.getElementById('toggle-admin').addEventListener('click', function() {
            const adminPanel = document.getElementById('admin-panel');
            adminPanel.classList.toggle('hidden');
        });

        document.getElementById('review-form').addEventListener('submit', function(e) {
            e.preventDefault();
            
            const name = document.getElementById('client-name').value;
            const rating = parseInt(document.getElementById('rating').value);
            const text = document.getElementById('review-text').value;
            
            const newReview = {
                name: name,
                rating: rating,
                text: text,
                id: reviews.length + 1
            };
            
            reviews.push(newReview);
            renderReviews();
            
            // Reset form
            this.reset();
            
            alert('Review added successfully!');
        });

        // Initialize reviews
        renderReviews();

        // Set last updated date for terms
        document.getElementById('last-updated').textContent = new Date().toLocaleDateString();

        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
                
                // Close mobile menu if open
                const mobileMenu = document.getElementById('mobile-menu');
                if (!mobileMenu.classList.contains('hidden')) {
                    mobileMenu.classList.add('hidden');
                }
            });
        });

        // Add scroll effect to navigation
        window.addEventListener('scroll', function() {
            const nav = document.querySelector('nav');
            if (window.scrollY > 100) {
                nav.classList.add('shadow-xl');
            } else {
                nav.classList.remove('shadow-xl');
            }
        });
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'9843745d33a49a7d',t:'MTc1ODcyOTIwNi4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nova Creations Codes - Professional Web Development Services</title>
    <meta name="description" content="Get fully completed websites at cheaper prices. Fast, reliable, professional web development, design, and app building services by Nova Creations Codes.">
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap');
        
        * {
            font-family: 'Inter', sans-serif;
        }
        
        .gradient-bg {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        }
        
        .hero-pattern {
            background-image: url("data:image/svg+xml,%3Csvg width='60' height='60' viewBox='0 0 60 60' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='none' fill-rule='evenodd'%3E%3Cg fill='%23ffffff' fill-opacity='0.1'%3E%3Ccircle cx='30' cy='30' r='2'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E");
        }
        
        .card-hover {
            transition: all 0.3s ease;
        }
        
        .card-hover:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
        }
        
        .star-rating {
            color: #fbbf24;
        }
        
        .whatsapp-float {
            position: fixed;
            width: 60px;
            height: 60px;
            bottom: 40px;
            right: 40px;
            background-color: #25d366;
            color: #FFF;
            border-radius: 50px;
            text-align: center;
            font-size: 30px;
            box-shadow: 2px 2px 3px #999;
            z-index: 100;
            transition: all 0.3s ease;
        }
        
        .whatsapp-float:hover {
            transform: scale(1.1);
        }
        
        .whatsapp-float i {
            margin-top: 16px;
        }
        
        .smooth-scroll {
            scroll-behavior: smooth;
        }
        
        .section-padding {
            padding: 80px 0;
        }
        
        .nav-link {
            transition: color 0.3s ease;
        }
        
        .nav-link:hover {
            color: #667eea;
        }
    </style>
</head>
<body class="smooth-scroll">
    <!-- Navigation -->
    <nav class="bg-white shadow-lg fixed w-full top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16">
                <div class="flex items-center">
                    <div class="flex-shrink-0">
                        <h1 class="text-2xl font-bold text-gray-800">Nova Creations Codes</h1>
                    </div>
                </div>
                <div class="hidden md:flex items-center space-x-8">
                    <a href="#home" class="nav-link text-gray-700 hover:text-blue-600 px-3 py-2 text-sm font-medium">Home</a>
                    <a href="#services" class="nav-link text-gray-700 hover:text-blue-600 px-3 py-2 text-sm font-medium">Services</a>
                    <a href="#reviews" class="nav-link text-gray-700 hover:text-blue-600 px-3 py-2 text-sm font-medium">Reviews</a>
                    <a href="#about" class="nav-link text-gray-700 hover:text-blue-600 px-3 py-2 text-sm font-medium">About</a>
                    <a href="#contact" class="nav-link text-gray-700 hover:text-blue-600 px-3 py-2 text-sm font-medium">Contact</a>
                    <a href="#terms" class="nav-link text-gray-700 hover:text-blue-600 px-3 py-2 text-sm font-medium">Terms</a>
                </div>
                <div class="md:hidden flex items-center">
                    <button id="mobile-menu-btn" class="text-gray-700 hover:text-blue-600 focus:outline-none">
                        <i class="fas fa-bars text-xl"></i>
                    </button>
                </div>
            </div>
        </div>
        <!-- Mobile menu -->
        <div id="mobile-menu" class="md:hidden hidden bg-white border-t">
            <div class="px-2 pt-2 pb-3 space-y-1">
                <a href="#home" class="block px-3 py-2 text-gray-700 hover:text-blue-600">Home</a>
                <a href="#services" class="block px-3 py-2 text-gray-700 hover:text-blue-600">Services</a>
                <a href="#reviews" class="block px-3 py-2 text-gray-700 hover:text-blue-600">Reviews</a>
                <a href="#about" class="block px-3 py-2 text-gray-700 hover:text-blue-600">About</a>
                <a href="#contact" class="block px-3 py-2 text-gray-700 hover:text-blue-600">Contact</a>
                <a href="#terms" class="block px-3 py-2 text-gray-700 hover:text-blue-600">Terms</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="gradient-bg hero-pattern section-padding mt-16">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <div class="text-white">
                <h1 class="text-4xl md:text-6xl font-bold mb-6">Get a Fully Completed Website at Cheaper Prices</h1>
                <p class="text-xl md:text-2xl mb-8 opacity-90">Fast, Reliable, Professional</p>
                <p class="text-lg mb-10 max-w-3xl mx-auto opacity-80">
                    Transform your business with stunning, fully functional websites that don't break the bank. 
                    We deliver professional web solutions tailored to your needs.
                </p>
                <button onclick="scrollToSection('contact')" class="bg-white text-blue-600 px-8 py-4 rounded-full text-lg font-semibold hover:bg-gray-100 transition duration-300 shadow-lg">
                    Get Your Website Now
                </button>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="section-padding bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold text-gray-800 mb-4">Our Services</h2>
                <p class="text-xl text-gray-600 max-w-2xl mx-auto">
                    We offer comprehensive digital solutions to help your business thrive online
                </p>
            </div>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
                <div class="bg-white p-8 rounded-xl shadow-lg card-hover text-center">
                    <div class="w-16 h-16 bg-blue-100 rounded-full flex items-center justify-center mx-auto mb-6">
                        <i class="fas fa-code text-2xl text-blue-600"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-4 text-gray-800">Web Development</h3>
                    <p class="text-gray-600">Custom websites built with modern technologies, optimized for performance and user experience.</p>
                </div>
                
                <div class="bg-white p-8 rounded-xl shadow-lg card-hover text-center">
                    <div class="w-16 h-16 bg-purple-100 rounded-full flex items-center justify-center mx-auto mb-6">
                        <i class="fas fa-palette text-2xl text-purple-600"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-4 text-gray-800">Web Design</h3>
                    <p class="text-gray-600">Beautiful, responsive designs that capture your brand essence and engage your audience.</p>
                </div>
                
                <div class="bg-white p-8 rounded-xl shadow-lg card-hover text-center">
                    <div class="w-16 h-16 bg-green-100 rounded-full flex items-center justify-center mx-auto mb-6">
                        <i class="fas fa-mobile-alt text-2xl text-green-600"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-4 text-gray-800">App Building</h3>
                    <p class="text-gray-600">Mobile applications that bring your business to your customers' fingertips.</p>
                </div>
                
                <div class="bg-white p-8 rounded-xl shadow-lg card-hover text-center">
                    <div class="w-16 h-16 bg-orange-100 rounded-full flex items-center justify-center mx-auto mb-6">
                        <i class="fas fa-cogs text-2xl text-orange-600"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-4 text-gray-800">Personal Customization</h3>
                    <p class="text-gray-600">Tailored solutions designed specifically for your unique business requirements and goals.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Reviews Section -->
    <section id="reviews" class="section-padding">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold text-gray-800 mb-4">Client Reviews</h2>
                <p class="text-xl text-gray-600">See what our satisfied clients have to say</p>
            </div>
            
            <div id="reviews-container" class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Reviews will be populated by JavaScript -->
            </div>
            
            <!-- Admin Panel for Reviews (Hidden by default) -->
            <div id="admin-panel" class="mt-12 bg-gray-100 p-6 rounded-lg hidden">
                <h3 class="text-xl font-semibold mb-4">Add New Review</h3>
                <form id="review-form" class="space-y-4">
                    <input type="text" id="client-name" placeholder="Client Name" class="w-full p-3 border rounded-lg" required>
                    <input type="number" id="rating" placeholder="Rating (1-5)" min="1" max="5" class="w-full p-3 border rounded-lg" required>
                    <textarea id="review-text" placeholder="Review Text" class="w-full p-3 border rounded-lg h-24" required></textarea>
                    <button type="submit" class="bg-blue-600 text-white px-6 py-3 rounded-lg hover:bg-blue-700">Add Review</button>
                </form>
            </div>
            
            <div class="text-center mt-8">
                <button id="toggle-admin" class="text-blue-600 hover:text-blue-800 text-sm">Admin Panel</button>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="section-padding bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid lg:grid-cols-2 gap-12 items-center">
                <div>
                    <h2 class="text-4xl font-bold text-gray-800 mb-6">About Nova Creations Codes</h2>
                    <div class="space-y-6 text-gray-600">
                        <p class="text-lg">
                            Founded by <strong class="text-gray-800">Astik Sharma</strong>, Nova Creations Codes was born from a vision to make professional web development accessible to businesses of all sizes.
                        </p>
                        <p>
                            We believe that every business deserves a stunning online presence without the hefty price tag. Our mission is to deliver high-quality, fully functional websites that help our clients succeed in the digital world.
                        </p>
                        <p>
                            With a focus on modern design, cutting-edge technology, and exceptional customer service, we've helped numerous businesses establish their online presence and grow their digital footprint.
                        </p>
                        <p>
                            At Nova Creations Codes, we don't just build websites – we create digital experiences that drive results and exceed expectations.
                        </p>
                    </div>
                </div>
                <div class="text-center">
                    <div class="bg-white p-8 rounded-xl shadow-lg">
                        <div class="w-32 h-32 bg-gradient-to-r from-blue-500 to-purple-600 rounded-full mx-auto mb-6 flex items-center justify-center">
                            <span class="text-white text-4xl font-bold">AS</span>
                        </div>
                        <h3 class="text-2xl font-semibold text-gray-800 mb-2">Astik Sharma</h3>
                        <p class="text-blue-600 font-medium mb-4">Founder & Lead Developer</p>
                        <p class="text-gray-600">
                            Passionate about creating digital solutions that make a difference in businesses and people's lives.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="section-padding">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold text-gray-800 mb-4">Get In Touch</h2>
                <p class="text-xl text-gray-600">Ready to start your project? Let's discuss your needs</p>
            </div>
            
            <div class="grid lg:grid-cols-2 gap-12">
                <div>
                    <h3 class="text-2xl font-semibold mb-6 text-gray-800">Contact Information</h3>
                    <div class="space-y-6">
                        <div class="flex items-center">
                            <div class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center mr-4">
                                <i class="fas fa-phone text-blue-600"></i>
                            </div>
                            <div>
                                <p class="font-medium text-gray-800">Phone</p>
                                <a href="tel:+916260943446" class="text-blue-600 hover:text-blue-800">+91 6260943446</a>
                            </div>
                        </div>
                        
                        <div class="flex items-center">
                            <div class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center mr-4">
                                <i class="fas fa-envelope text-blue-600"></i>
                            </div>
                            <div>
                                <p class="font-medium text-gray-800">Email</p>
                                <a href="mailto:ashuv6131@gmail.com" class="text-blue-600 hover:text-blue-800">ashuv6131@gmail.com</a>
                            </div>
                        </div>
                        
                        <div class="flex items-center">
                            <div class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center mr-4">
                                <i class="fab fa-instagram text-blue-600"></i>
                            </div>
                            <div>
                                <p class="font-medium text-gray-800">Instagram</p>
                                <a href="https://instagram.com/_astik_sharma_" target="_blank" rel="noopener noreferrer" class="text-blue-600 hover:text-blue-800">@_astik_sharma_</a>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div>
                    <form id="contact-form" class="space-y-6">
                        <div>
                            <label for="name" class="block text-sm font-medium text-gray-700 mb-2">Name</label>
                            <input type="text" id="name" name="name" required class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-transparent">
                        </div>
                        
                        <div>
                            <label for="email" class="block text-sm font-medium text-gray-700 mb-2">Email</label>
                            <input type="email" id="email" name="email" required class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-transparent">
                        </div>
                        
                        <div>
                            <label for="message" class="block text-sm font-medium text-gray-700 mb-2">Message</label>
                            <textarea id="message" name="message" rows="5" required class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-transparent"></textarea>
                        </div>
                        
                        <button type="submit" class="w-full bg-blue-600 text-white py-3 px-6 rounded-lg hover:bg-blue-700 transition duration-300 font-semibold">
                            Send Message
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Terms & Conditions Section -->
    <section id="terms" class="section-padding bg-gray-50">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-4xl font-bold text-gray-800 mb-8 text-center">Terms & Conditions</h2>
            
            <div class="bg-white p-8 rounded-xl shadow-lg">
                <div class="space-y-6 text-gray-600">
                    <div>
                        <h3 class="text-xl font-semibold text-gray-800 mb-3">1. Service Charges</h3>
                        <p>All service charges are non-refundable after project initiation. Once work has begun on your project, no refunds will be provided regardless of project status or completion.</p>
                    </div>
                    
                    <div>
                        <h3 class="text-xl font-semibold text-gray-800 mb-3">2. Project Timelines</h3>
                        <p>Project timelines may vary depending on project scope, complexity, and client requirements. While we strive to meet all agreed-upon deadlines, Nova Creations Codes reserves the right to adjust timelines as necessary to ensure quality delivery.</p>
                    </div>
                    
                    <div>
                        <h3 class="text-xl font-semibold text-gray-800 mb-3">3. Service Refusal Rights</h3>
                        <p>Nova Creations Codes reserves the right to refuse service to any client for any reason, including but not limited to inappropriate behavior, unrealistic expectations, or projects that conflict with our values and capabilities.</p>
                    </div>
                    
                    <div>
                        <h3 class="text-xl font-semibold text-gray-800 mb-3">4. Client Responsibilities</h3>
                        <p>Clients must provide accurate project requirements and timely feedback throughout the development process. Delays in client response may result in project timeline extensions. Clear communication and prompt feedback are essential for successful project completion.</p>
                    </div>
                    
                    <div>
                        <h3 class="text-xl font-semibold text-gray-800 mb-3">5. Intellectual Property</h3>
                        <p>Upon full payment, clients will own the rights to their custom website design and content. However, Nova Creations Codes retains the right to showcase completed work in our portfolio unless otherwise agreed upon in writing.</p>
                    </div>
                    
                    <div>
                        <h3 class="text-xl font-semibold text-gray-800 mb-3">6. Limitation of Liability</h3>
                        <p>Nova Creations Codes' liability is limited to the amount paid for services. We are not responsible for any indirect, incidental, or consequential damages arising from the use of our services.</p>
                    </div>
                </div>
                
                <div class="mt-8 pt-6 border-t border-gray-200">
                    <p class="text-sm text-gray-500">
                        Last updated: <span id="last-updated"></span><br>
                        By engaging our services, you agree to these terms and conditions.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid md:grid-cols-3 gap-8">
                <div>
                    <h3 class="text-2xl font-bold mb-4">Nova Creations Codes</h3>
                    <p class="text-gray-300 mb-4">Professional web development services at affordable prices. Fast, reliable, and tailored to your needs.</p>
                    <div class="flex space-x-4">
                        <a href="https://instagram.com/astik_sharma" target="_blank" rel="noopener noreferrer" class="text-gray-300 hover:text-white">
                            <i class="fab fa-instagram text-xl"></i>
                        </a>
                    </div>
                </div>
                
                <div>
                    <h4 class="text-lg font-semibold mb-4">Quick Links</h4>
                    <ul class="space-y-2">
                        <li><a href="#home" class="text-gray-300 hover:text-white">Home</a></li>
                        <li><a href="#services" class="text-gray-300 hover:text-white">Services</a></li>
                        <li><a href="#about" class="text-gray-300 hover:text-white">About</a></li>
                        <li><a href="#contact" class="text-gray-300 hover:text-white">Contact</a></li>
                        <li><a href="#terms" class="text-gray-300 hover:text-white">Terms & Conditions</a></li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="text-lg font-semibold mb-4">Contact Info</h4>
                    <div class="space-y-2 text-gray-300">
                        <p><i class="fas fa-phone mr-2"></i> +91 6260943446</p>
                        <p><i class="fas fa-envelope mr-2"></i> ashuv6131@gmail.com</p>
                        <p><i class="fab fa-instagram mr-2"></i> @astik_sharma</p>
                    </div>
                </div>
            </div>
            
            <div class="border-t border-gray-700 mt-8 pt-8 text-center">
                <p class="text-gray-300">&copy; 2024 Nova Creations Codes. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <!-- WhatsApp Float Button -->
    <a href="https://wa.me/916260943446" target="_blank" rel="noopener noreferrer" class="whatsapp-float">
        <i class="fab fa-whatsapp"></i>
    </a>

    <script>
        // Mobile menu toggle
        document.getElementById('mobile-menu-btn').addEventListener('click', function() {
            const mobileMenu = document.getElementById('mobile-menu');
            mobileMenu.classList.toggle('hidden');
        });

        // Smooth scrolling function
        function scrollToSection(sectionId) {
            document.getElementById(sectionId).scrollIntoView({
                behavior: 'smooth'
            });
        }

        // Contact form handling
        document.getElementById('contact-form').addEventListener('submit', function(e) {
            e.preventDefault();
            
            const name = document.getElementById('name').value;
            const email = document.getElementById('email').value;
            const message = document.getElementById('message').value;
            
            // Simulate form submission
            alert(Thank you, ${name}! Your message has been received. We'll get back to you soon at ${email}.);
            
            // Reset form
            this.reset();
        });

        // Reviews system
        let reviews = [
            {
                name: "Ankit Sahu",
                rating: 5,
                text: "Excellent service! Nova Creations Codes delivered exactly what I needed for my business website. Professional, fast, and affordable.",
                id: 1
            },
            {
                name: "Harshit Chaurasia",
                rating: 5,
                text: "Amazing work on my e-commerce site. The design is beautiful and the functionality is perfect. Highly recommend!",
                id: 2
            },
            {
                name: "Ankit Tiwari",
                rating: 4,
                text: "Great experience working with Astik. The website looks professional and loads quickly. Very satisfied with the results.",
                id: 3
            }
        ];

        function renderReviews() {
            const container = document.getElementById('reviews-container');
            container.innerHTML = '';
            
            reviews.forEach(review => {
                const reviewCard = document.createElement('div');
                reviewCard.className = 'bg-white p-6 rounded-xl shadow-lg card-hover';
                
                const stars = '★'.repeat(review.rating) + '☆'.repeat(5 - review.rating);
                
                reviewCard.innerHTML = `
                    <div class="flex items-center mb-4">
                        <div class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center mr-4">
                            <span class="text-blue-600 font-semibold">${review.name.charAt(0)}</span>
                        </div>
                        <div>
                            <h4 class="font-semibold text-gray-800">${review.name}</h4>
                            <div class="star-rating text-lg">${stars}</div>
                        </div>
                    </div>
                    <p class="text-gray-600">"${review.text}"</p>
                `;
                
                container.appendChild(reviewCard);
            });
        }

        // Admin panel for reviews
        document.getElementById('toggle-admin').addEventListener('click', function() {
            const adminPanel = document.getElementById('admin-panel');
            adminPanel.classList.toggle('hidden');
        });

        document.getElementById('review-form').addEventListener('submit', function(e) {
            e.preventDefault();
            
            const name = document.getElementById('client-name').value;
            const rating = parseInt(document.getElementById('rating').value);
            const text = document.getElementById('review-text').value;
            
            const newReview = {
                name: name,
                rating: rating,
                text: text,
                id: reviews.length + 1
            };
            
            reviews.push(newReview);
            renderReviews();
            
            // Reset form
            this.reset();
            
            alert('Review added successfully!');
        });

        // Initialize reviews
        renderReviews();

        // Set last updated date for terms
        document.getElementById('last-updated').textContent = new Date().toLocaleDateString();

        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
                
                // Close mobile menu if open
                const mobileMenu = document.getElementById('mobile-menu');
                if (!mobileMenu.classList.contains('hidden')) {
                    mobileMenu.classList.add('hidden');
                }
            });
        });

        // Add scroll effect to navigation
        window.addEventListener('scroll', function() {
            const nav = document.querySelector('nav');
            if (window.scrollY > 100) {
                nav.classList.add('shadow-xl');
            } else {
                nav.classList.remove('shadow-xl');
            }
        });
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'9843745d33a49a7d',t:'MTc1ODcyOTIwNi4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nova Creations Codes - Professional Web Development Services</title>
    <meta name="description" content="Get fully completed websites at cheaper prices. Fast, reliable, professional web development, design, and app building services by Nova Creations Codes.">
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap');
        
        * {
            font-family: 'Inter', sans-serif;
        }
        
        .gradient-bg {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        }
        
        .hero-pattern {
            background-image: url("data:image/svg+xml,%3Csvg width='60' height='60' viewBox='0 0 60 60' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='none' fill-rule='evenodd'%3E%3Cg fill='%23ffffff' fill-opacity='0.1'%3E%3Ccircle cx='30' cy='30' r='2'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E");
        }
        
        .card-hover {
            transition: all 0.3s ease;
        }
        
        .card-hover:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
        }
        
        .star-rating {
            color: #fbbf24;
        }
        
        .whatsapp-float {
            position: fixed;
            width: 60px;
            height: 60px;
            bottom: 40px;
            right: 40px;
            background-color: #25d366;
            color: #FFF;
            border-radius: 50px;
            text-align: center;
            font-size: 30px;
            box-shadow: 2px 2px 3px #999;
            z-index: 100;
            transition: all 0.3s ease;
        }
        
        .whatsapp-float:hover {
            transform: scale(1.1);
        }
        
        .whatsapp-float i {
            margin-top: 16px;
        }
        
        .smooth-scroll {
            scroll-behavior: smooth;
        }
        
        .section-padding {
            padding: 80px 0;
        }
        
        .nav-link {
            transition: color 0.3s ease;
        }
        
        .nav-link:hover {
            color: #667eea;
        }
    </style>
</head>
<body class="smooth-scroll">
    <!-- Navigation -->
    <nav class="bg-white shadow-lg fixed w-full top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16">
                <div class="flex items-center">
                    <div class="flex-shrink-0">
                        <h1 class="text-2xl font-bold text-gray-800">Nova Creations Codes</h1>
                    </div>
                </div>
                <div class="hidden md:flex items-center space-x-8">
                    <a href="#home" class="nav-link text-gray-700 hover:text-blue-600 px-3 py-2 text-sm font-medium">Home</a>
                    <a href="#services" class="nav-link text-gray-700 hover:text-blue-600 px-3 py-2 text-sm font-medium">Services</a>
                    <a href="#reviews" class="nav-link text-gray-700 hover:text-blue-600 px-3 py-2 text-sm font-medium">Reviews</a>
                    <a href="#about" class="nav-link text-gray-700 hover:text-blue-600 px-3 py-2 text-sm font-medium">About</a>
                    <a href="#contact" class="nav-link text-gray-700 hover:text-blue-600 px-3 py-2 text-sm font-medium">Contact</a>
                    <a href="#terms" class="nav-link text-gray-700 hover:text-blue-600 px-3 py-2 text-sm font-medium">Terms</a>
                </div>
                <div class="md:hidden flex items-center">
                    <button id="mobile-menu-btn" class="text-gray-700 hover:text-blue-600 focus:outline-none">
                        <i class="fas fa-bars text-xl"></i>
                    </button>
                </div>
            </div>
        </div>
        <!-- Mobile menu -->
        <div id="mobile-menu" class="md:hidden hidden bg-white border-t">
            <div class="px-2 pt-2 pb-3 space-y-1">
                <a href="#home" class="block px-3 py-2 text-gray-700 hover:text-blue-600">Home</a>
                <a href="#services" class="block px-3 py-2 text-gray-700 hover:text-blue-600">Services</a>
                <a href="#reviews" class="block px-3 py-2 text-gray-700 hover:text-blue-600">Reviews</a>
                <a href="#about" class="block px-3 py-2 text-gray-700 hover:text-blue-600">About</a>
                <a href="#contact" class="block px-3 py-2 text-gray-700 hover:text-blue-600">Contact</a>
                <a href="#terms" class="block px-3 py-2 text-gray-700 hover:text-blue-600">Terms</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="gradient-bg hero-pattern section-padding mt-16">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <div class="text-white">
                <h1 class="text-4xl md:text-6xl font-bold mb-6">Get a Fully Completed Website at Cheaper Prices</h1>
                <p class="text-xl md:text-2xl mb-8 opacity-90">Fast, Reliable, Professional</p>
                <p class="text-lg mb-10 max-w-3xl mx-auto opacity-80">
                    Transform your business with stunning, fully functional websites that don't break the bank. 
                    We deliver professional web solutions tailored to your needs.
                </p>
                <button onclick="scrollToSection('contact')" class="bg-white text-blue-600 px-8 py-4 rounded-full text-lg font-semibold hover:bg-gray-100 transition duration-300 shadow-lg">
                    Get Your Website Now
                </button>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="section-padding bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold text-gray-800 mb-4">Our Services</h2>
                <p class="text-xl text-gray-600 max-w-2xl mx-auto">
                    We offer comprehensive digital solutions to help your business thrive online
                </p>
            </div>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
                <div class="bg-white p-8 rounded-xl shadow-lg card-hover text-center">
                    <div class="w-16 h-16 bg-blue-100 rounded-full flex items-center justify-center mx-auto mb-6">
                        <i class="fas fa-code text-2xl text-blue-600"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-4 text-gray-800">Web Development</h3>
                    <p class="text-gray-600">Custom websites built with modern technologies, optimized for performance and user experience.</p>
                </div>
                
                <div class="bg-white p-8 rounded-xl shadow-lg card-hover text-center">
                    <div class="w-16 h-16 bg-purple-100 rounded-full flex items-center justify-center mx-auto mb-6">
                        <i class="fas fa-palette text-2xl text-purple-600"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-4 text-gray-800">Web Design</h3>
                    <p class="text-gray-600">Beautiful, responsive designs that capture your brand essence and engage your audience.</p>
                </div>
                
                <div class="bg-white p-8 rounded-xl shadow-lg card-hover text-center">
                    <div class="w-16 h-16 bg-green-100 rounded-full flex items-center justify-center mx-auto mb-6">
                        <i class="fas fa-mobile-alt text-2xl text-green-600"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-4 text-gray-800">App Building</h3>
                    <p class="text-gray-600">Mobile applications that bring your business to your customers' fingertips.</p>
                </div>
                
                <div class="bg-white p-8 rounded-xl shadow-lg card-hover text-center">
                    <div class="w-16 h-16 bg-orange-100 rounded-full flex items-center justify-center mx-auto mb-6">
                        <i class="fas fa-cogs text-2xl text-orange-600"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-4 text-gray-800">Personal Customization</h3>
                    <p class="text-gray-600">Tailored solutions designed specifically for your unique business requirements and goals.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Reviews Section -->
    <section id="reviews" class="section-padding">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold text-gray-800 mb-4">Client Reviews</h2>
                <p class="text-xl text-gray-600">See what our satisfied clients have to say</p>
            </div>
            
            <div id="reviews-container" class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Reviews will be populated by JavaScript -->
            </div>
            
            <!-- Admin Panel for Reviews (Hidden by default) -->
            <div id="admin-panel" class="mt-12 bg-gray-100 p-6 rounded-lg hidden">
                <h3 class="text-xl font-semibold mb-4">Add New Review</h3>
                <form id="review-form" class="space-y-4">
                    <input type="text" id="client-name" placeholder="Client Name" class="w-full p-3 border rounded-lg" required>
                    <input type="number" id="rating" placeholder="Rating (1-5)" min="1" max="5" class="w-full p-3 border rounded-lg" required>
                    <textarea id="review-text" placeholder="Review Text" class="w-full p-3 border rounded-lg h-24" required></textarea>
                    <button type="submit" class="bg-blue-600 text-white px-6 py-3 rounded-lg hover:bg-blue-700">Add Review</button>
                </form>
            </div>
            
            <div class="text-center mt-8">
                <button id="toggle-admin" class="text-blue-600 hover:text-blue-800 text-sm">Admin Panel</button>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="section-padding bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid lg:grid-cols-2 gap-12 items-center">
                <div>
                    <h2 class="text-4xl font-bold text-gray-800 mb-6">About Nova Creations Codes</h2>
                    <div class="space-y-6 text-gray-600">
                        <p class="text-lg">
                            Founded by <strong class="text-gray-800">Astik Sharma</strong>, Nova Creations Codes was born from a vision to make professional web development accessible to businesses of all sizes.
                        </p>
                        <p>
                            We believe that every business deserves a stunning online presence without the hefty price tag. Our mission is to deliver high-quality, fully functional websites that help our clients succeed in the digital world.
                        </p>
                        <p>
                            With a focus on modern design, cutting-edge technology, and exceptional customer service, we've helped numerous businesses establish their online presence and grow their digital footprint.
                        </p>
                        <p>
                            At Nova Creations Codes, we don't just build websites – we create digital experiences that drive results and exceed expectations.
                        </p>
                    </div>
                </div>
                <div class="text-center">
                    <div class="bg-white p-8 rounded-xl shadow-lg">
                        <div class="w-32 h-32 bg-gradient-to-r from-blue-500 to-purple-600 rounded-full mx-auto mb-6 flex items-center justify-center">
                            <span class="text-white text-4xl font-bold">AS</span>
                        </div>
                        <h3 class="text-2xl font-semibold text-gray-800 mb-2">Astik Sharma</h3>
                        <p class="text-blue-600 font-medium mb-4">Founder & Lead Developer</p>
                        <p class="text-gray-600">
                            Passionate about creating digital solutions that make a difference in businesses and people's lives.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="section-padding">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold text-gray-800 mb-4">Get In Touch</h2>
                <p class="text-xl text-gray-600">Ready to start your project? Let's discuss your needs</p>
            </div>
            
            <div class="grid lg:grid-cols-2 gap-12">
                <div>
                    <h3 class="text-2xl font-semibold mb-6 text-gray-800">Contact Information</h3>
                    <div class="space-y-6">
                        <div class="flex items-center">
                            <div class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center mr-4">
                                <i class="fas fa-phone text-blue-600"></i>
                            </div>
                            <div>
                                <p class="font-medium text-gray-800">Phone</p>
                                <a href="tel:+916260943446" class="text-blue-600 hover:text-blue-800">+91 6260943446</a>
                            </div>
                        </div>
                        
                        <div class="flex items-center">
                            <div class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center mr-4">
                                <i class="fas fa-envelope text-blue-600"></i>
                            </div>
                            <div>
                                <p class="font-medium text-gray-800">Email</p>
                                <a href="mailto:ashuv6131@gmail.com" class="text-blue-600 hover:text-blue-800">ashuv6131@gmail.com</a>
                            </div>
                        </div>
                        
                        <div class="flex items-center">
                            <div class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center mr-4">
                                <i class="fab fa-instagram text-blue-600"></i>
                            </div>
                            <div>
                                <p class="font-medium text-gray-800">Instagram</p>
                                <a href="https://instagram.com/astik_sharma" target="_blank" rel="noopener noreferrer" class="text-blue-600 hover:text-blue-800">@astik_sharma</a>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div>
                    <form id="contact-form" class="space-y-6">
                        <div>
                            <label for="name" class="block text-sm font-medium text-gray-700 mb-2">Name</label>
                            <input type="text" id="name" name="name" required class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-transparent">
                        </div>
                        
                        <div>
                            <label for="email" class="block text-sm font-medium text-gray-700 mb-2">Email</label>
                            <input type="email" id="email" name="email" required class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-transparent">
                        </div>
                        
                        <div>
                            <label for="message" class="block text-sm font-medium text-gray-700 mb-2">Message</label>
                            <textarea id="message" name="message" rows="5" required class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-transparent"></textarea>
                        </div>
                        
                        <button type="submit" class="w-full bg-blue-600 text-white py-3 px-6 rounded-lg hover:bg-blue-700 transition duration-300 font-semibold">
                            Send Message
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Terms & Conditions Section -->
    <section id="terms" class="section-padding bg-gray-50">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-4xl font-bold text-gray-800 mb-8 text-center">Terms & Conditions</h2>
            
            <div class="bg-white p-8 rounded-xl shadow-lg">
                <div class="space-y-6 text-gray-600">
                    <div>
                        <h3 class="text-xl font-semibold text-gray-800 mb-3">1. Service Charges</h3>
                        <p>All service charges are non-refundable after project initiation. Once work has begun on your project, no refunds will be provided regardless of project status or completion.</p>
                    </div>
                    
                    <div>
                        <h3 class="text-xl font-semibold text-gray-800 mb-3">2. Project Timelines</h3>
                        <p>Project timelines may vary depending on project scope, complexity, and client requirements. While we strive to meet all agreed-upon deadlines, Nova Creations Codes reserves the right to adjust timelines as necessary to ensure quality delivery.</p>
                    </div>
                    
                    <div>
                        <h3 class="text-xl font-semibold text-gray-800 mb-3">3. Service Refusal Rights</h3>
                        <p>Nova Creations Codes reserves the right to refuse service to any client for any reason, including but not limited to inappropriate behavior, unrealistic expectations, or projects that conflict with our values and capabilities.</p>
                    </div>
                    
                    <div>
                        <h3 class="text-xl font-semibold text-gray-800 mb-3">4. Client Responsibilities</h3>
                        <p>Clients must provide accurate project requirements and timely feedback throughout the development process. Delays in client response may result in project timeline extensions. Clear communication and prompt feedback are essential for successful project completion.</p>
                    </div>
                    
                    <div>
                        <h3 class="text-xl font-semibold text-gray-800 mb-3">5. Intellectual Property</h3>
                        <p>Upon full payment, clients will own the rights to their custom website design and content. However, Nova Creations Codes retains the right to showcase completed work in our portfolio unless otherwise agreed upon in writing.</p>
                    </div>
                    
                    <div>
                        <h3 class="text-xl font-semibold text-gray-800 mb-3">6. Limitation of Liability</h3>
                        <p>Nova Creations Codes' liability is limited to the amount paid for services. We are not responsible for any indirect, incidental, or consequential damages arising from the use of our services.</p>
                    </div>
                </div>
                
                <div class="mt-8 pt-6 border-t border-gray-200">
                    <p class="text-sm text-gray-500">
                        Last updated: <span id="last-updated"></span><br>
                        By engaging our services, you agree to these terms and conditions.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid md:grid-cols-3 gap-8">
                <div>
                    <h3 class="text-2xl font-bold mb-4">Nova Creations Codes</h3>
                    <p class="text-gray-300 mb-4">Professional web development services at affordable prices. Fast, reliable, and tailored to your needs.</p>
                    <div class="flex space-x-4">
                        <a href="https://instagram.com/astik_sharma" target="_blank" rel="noopener noreferrer" class="text-gray-300 hover:text-white">
                            <i class="fab fa-instagram text-xl"></i>
                        </a>
                    </div>
                </div>
                
                <div>
                    <h4 class="text-lg font-semibold mb-4">Quick Links</h4>
                    <ul class="space-y-2">
                        <li><a href="#home" class="text-gray-300 hover:text-white">Home</a></li>
                        <li><a href="#services" class="text-gray-300 hover:text-white">Services</a></li>
                        <li><a href="#about" class="text-gray-300 hover:text-white">About</a></li>
                        <li><a href="#contact" class="text-gray-300 hover:text-white">Contact</a></li>
                        <li><a href="#terms" class="text-gray-300 hover:text-white">Terms & Conditions</a></li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="text-lg font-semibold mb-4">Contact Info</h4>
                    <div class="space-y-2 text-gray-300">
                        <p><i class="fas fa-phone mr-2"></i> +91 6260943446</p>
                        <p><i class="fas fa-envelope mr-2"></i> ashuv6131@gmail.com</p>
                        <p><i class="fab fa-instagram mr-2"></i> @astik_sharma</p>
                    </div>
                </div>
            </div>
            
            <div class="border-t border-gray-700 mt-8 pt-8 text-center">
                <p class="text-gray-300">&copy; 2024 Nova Creations Codes. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <!-- WhatsApp Float Button -->
    <a href="https://wa.me/916260943446" target="_blank" rel="noopener noreferrer" class="whatsapp-float">
        <i class="fab fa-whatsapp"></i>
    </a>

    <script>
        // Mobile menu toggle
        document.getElementById('mobile-menu-btn').addEventListener('click', function() {
            const mobileMenu = document.getElementById('mobile-menu');
            mobileMenu.classList.toggle('hidden');
        });

        // Smooth scrolling function
        function scrollToSection(sectionId) {
            document.getElementById(sectionId).scrollIntoView({
                behavior: 'smooth'
            });
        }

        // Contact form handling
        document.getElementById('contact-form').addEventListener('submit', function(e) {
            e.preventDefault();
            
            const name = document.getElementById('name').value;
            const email = document.getElementById('email').value;
            const message = document.getElementById('message').value;
            
            // Simulate form submission
            alert(Thank you, ${name}! Your message has been received. We'll get back to you soon at ${email}.);
            
            // Reset form
            this.reset();
        });

        // Reviews system
        let reviews = [
            {
                name: "Priya Patel",
                rating: 5,
                text: "Excellent service! Nova Creations Codes delivered exactly what I needed for my business website. Professional, fast, and affordable.",
                id: 1
            },
            {
                name: "Rahul Kumar",
                rating: 5,
                text: "Amazing work on my e-commerce site. The design is beautiful and the functionality is perfect. Highly recommend!",
                id: 2
            },
            {
                name: "Sneha Gupta",
                rating: 4,
                text: "Great experience working with Astik. The website looks professional and loads quickly. Very satisfied with the results.",
                id: 3
            }
        ];

        function renderReviews() {
            const container = document.getElementById('reviews-container');
            container.innerHTML = '';
            
            reviews.forEach(review => {
                const reviewCard = document.createElement('div');
                reviewCard.className = 'bg-white p-6 rounded-xl shadow-lg card-hover';
                
                const stars = '★'.repeat(review.rating) + '☆'.repeat(5 - review.rating);
                
                reviewCard.innerHTML = `
                    <div class="flex items-center mb-4">
                        <div class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center mr-4">
                            <span class="text-blue-600 font-semibold">${review.name.charAt(0)}</span>
                        </div>
                        <div>
                            <h4 class="font-semibold text-gray-800">${review.name}</h4>
                            <div class="star-rating text-lg">${stars}</div>
                        </div>
                    </div>
                    <p class="text-gray-600">"${review.text}"</p>
                `;
                
                container.appendChild(reviewCard);
            });
        }

        // Admin panel for reviews
        document.getElementById('toggle-admin').addEventListener('click', function() {
            const adminPanel = document.getElementById('admin-panel');
            adminPanel.classList.toggle('hidden');
        });

        document.getElementById('review-form').addEventListener('submit', function(e) {
            e.preventDefault();
            
            const name = document.getElementById('client-name').value;
            const rating = parseInt(document.getElementById('rating').value);
            const text = document.getElementById('review-text').value;
            
            const newReview = {
                name: name,
                rating: rating,
                text: text,
                id: reviews.length + 1
            };
            
            reviews.push(newReview);
            renderReviews();
            
            // Reset form
            this.reset();
            
            alert('Review added successfully!');
        });

        // Initialize reviews
        renderReviews();

        // Set last updated date for terms
        document.getElementById('last-updated').textContent = new Date().toLocaleDateString();

        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
                
                // Close mobile menu if open
                const mobileMenu = document.getElementById('mobile-menu');
                if (!mobileMenu.classList.contains('hidden')) {
                    mobileMenu.classList.add('hidden');
                }
            });
        });

        // Add scroll effect to navigation
        window.addEventListener('scroll', function() {
            const nav = document.querySelector('nav');
            if (window.scrollY > 100) {
                nav.classList.add('shadow-xl');
            } else {
                nav.classList.remove('shadow-xl');
            }
        });
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'9843745d33a49a7d',t:'MTc1ODcyOTIwNi4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
