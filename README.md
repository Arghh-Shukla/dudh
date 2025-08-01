
3. Clean up social media icon styles:
```html
```diff
<<<<<<< SEARCH
                            <a href="#" class="bg-green-700 hover:bg-green-600 p-3 rounded-full" style="">
                                <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24" style="">
                                    <path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.Here is the updated HTML content after applying above edits:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>दूध - Premium Dairy Products</title>
    <meta name="description" content="Pure, fresh dairy products from दूध - milk, paneer, ghee, yogurt and more. Farm to table freshness guaranteed.">
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');
        body {
            font-family: 'Poppins', sans-serif;
            scroll-behavior: smooth;
        }
        .hero-image {
            background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.4)), url('https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/488dd607-139e-434e-a9bd-f13038cc6f94.png');
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
        }
        .product-card {
            transition: all 0.3s ease;
        }
        .product-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
        }
        .testimonial-slide {
            opacity: 0;
            transition: opacity 0.5s ease;
            position: absolute;
            width: 100%;
        }
        .testimonial-slide.active {
            opacity: 1;
        }
    </style>
</head>
<body class="text-gray-800 bg-gray-50">
    <!-- Navigation -->
    <nav class="bg-white shadow-md fixed w-full z-10">
        <div class="container mx-auto px-6 py-3">
            <div class="flex items-center justify-between">
                <div class="flex items-center">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/756a3f66-83a0-4880-84c6-0dc119050123.png" alt="दूध logo - circular emblem with a milk jug and cow silhouette in white against dark green background" class="h-12 mr-3">
                    <span class="text-xl font-bold text-green-800">दूध</span>
                </div>
                <div class="hidden md:flex space-x-8">
                    <a href="#home" class="text-green-800 hover:text-green-600">Home</a>
                    <a href="#about" class="text-gray-600 hover:text-green-600">About</a>
                    <a href="#products" class="text-gray-600 hover:text-green-600">Products</a>
                    <a href="#testimonials" class="text-gray-600 hover:text-green-600">Testimonials</a>
                    <a href="#contact" class="text-gray-600 hover:text-green-600">Contact</a>
                </div>
                <button class="md:hidden focus:outline-none">
                    <svg class="w-6 h-6 text-green-800" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
                    </svg>
                </button>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero-image min-h-screen flex items-center justify-center text-white pt-16">
        <div class="container mx-auto px-6 text-center">
            <h1 class="text-4xl md:text-6xl font-bold mb-4">Pure. Fresh. Natural.</h1>
            <p class="text-xl md:text-2xl mb-8">Premium dairy products from our farm to your table</p>
            <div class="flex flex-col md:flex-row justify-center gap-4">
                <a href="#products" class="bg-green-700 hover:bg-green-600 text-white px-8 py-3 rounded-full font-bold transition duration-300">Our Products</a>
                <a href="#contact" class="border-2 border-white hover:bg-white hover:text-green-800 text-white px-8 py-3 rounded-full font-bold transition duration-300">Contact Us</a>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-10 md:mb-0 md:pr-10">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/6cb3a6b9-ad7e-4075-bf98-92bcef26a7bd.png" alt="Happy cows grazing in lush green pastures with farm buildings in the background" class="rounded-lg shadow-lg">
                </div>
                <div class="md:w-1/2">
                    <h2 class="text-3xl font-bold text-green-800 mb-6">Our Story</h2>
                    <p class="text-gray-600 mb-4">Founded in 2010, Dudh Diary started with just five cows on a small family farm. Today, we serve thousands of households with our premium dairy products while maintaining the same commitment to quality and ethics.</p>
                    <p class="text-gray-600 mb-6">We believe in sustainable farming practices, ethical treatment of our animals, and delivering nutrition in its purest form.</p>
                    <div class="grid grid-cols-2 gap-4">
                        <div class="flex items-center">
                            <div class="bg-green-100 p-3 rounded-full mr-3">
                                <svg class="w-6 h-6 text-green-700" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                                </svg>
                            </div>
                            <span class="text-gray-700">100% Natural</span>
                        </div>
                        <div class="flex items-center">
                            <div class="bg-green-100 p-3 rounded-full mr-3">
                                <svg class="w-6 h-6 text-green-700" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                                </svg>
                            </div>
                            <span class="text-gray-700">No Preservatives</span>
                        </div>
                        <div class="flex items-center">
                            <div class="bg-green-100 p-3 rounded-full mr-3">
                                <svg class="w-6 h-6 text-green-700" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                                </svg>
                            </div>
                            <span class="text-gray-700">Farm Fresh</span>
                        </div>
                        <div class="flex items-center">
                            <div class="bg-green-100 p-3 rounded-full mr-3">
                                <svg class="w-6 h-6 text-green-700" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                                </svg>
                            </div>
                            <span class="text-gray-700">Daily Delivery</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Products Section -->
    <section id="products" class="py-20 bg-gray-50">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-green-800 mb-4">Our Premium Products</h2>
                <p class="text-gray-600 max-w-3xl mx-auto">Handcrafted with care and tradition for uncompromised quality and taste</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- Product 1 -->
                <div class="product-card bg-white rounded-lg overflow-hidden shadow-md">
                    <div class="h-48 overflow-hidden">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/32db6ffe-4ec2-437c-936d-edc64617000f.png" alt="Glass bottle of fresh milk with droplets on the side showing condensation" class="w-full h-full object-cover">
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-green-800 mb-2">Fresh Milk</h3>
                        <p class="text-gray-600 mb-4">Packed with essential nutrients, our milk is pasteurized to perfection while retaining all natural goodness.</p>
                        <div class="flex justify-between items-center">
                            <span class="text-lg font-bold text-green-700">₹60/Liter</span>
                            <button class="bg-green-700 hover:bg-green-600 text-white px-4 py-2 rounded-full text-sm">Add to Cart</button>
                        </div>
                    </div>
                </div>
                
                <!-- Product 2 -->
                <div class="product-card bg-white rounded-lg overflow-hidden shadow-md">
                    <div class="h-48 overflow-hidden">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/d734a678-af74-4c7d-aaba-7aa394c38e8e.png" alt="Freshly made paneer cubes on a wooden board with herbs" class="w-full h-full object-cover">
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-green-800 mb-2">Homemade Paneer</h3>
                        <p class="text-gray-600 mb-4">Made fresh daily from pure milk, our paneer is soft, crumbly and perfect for all your favorite dishes.</p>
                        <div class="flex justify-between items-center">
                            <span class="text-lg font-bold text-green-700">₹220/Kg</span>
                            <button class="bg-green-700 hover:bg-green-600 text-white px-4 py-2 rounded-full text-sm">Add to Cart</button>
                        </div>
                    </div>
                </div>
                
                <!-- Product 3 -->
                <div class="product-card bg-white rounded-lg overflow-hidden shadow-md">
                    <div class="h-48 overflow-hidden">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/49e46a6b-8c09-484b-a36a-3a3bafa255dc.png" alt="Golden ghee in a traditional clay pot with wooden spoon" class="w-full h-full object-cover">
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-green-800 mb-2">Pure Ghee</h3>
                        <p class="text-gray-600 mb-4">Made using traditional bilona method, our ghee has rich aroma and texture that enhances any dish.</p>
                        <div class="flex justify-between items-center">
                            <span class="text-lg font-bold text-green-700">₹550/Kg</span>
                            <button class="bg-green-700 hover:bg-green-600 text-white px-4 py-2 rounded-full text-sm">Add to Cart</button>
                        </div>
                    </div>
                </div>
                
                <!-- Product 4 -->
                <div class="product-card bg-white rounded-lg overflow-hidden shadow-md">
                    <div class="h-48 overflow-hidden">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/c7ef8c17-fb8e-4855-a6f1-6e3b557a7c95.png" alt="Creamy yogurt in earthen pot with mint garnish on top" class="w-full h-full object-cover">
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-green-800 mb-2">Curd/Dahi</h3>
                        <p class="text-gray-600 mb-4">Set in traditional earthen pots for enhanced taste and probiotic benefits that aid digestion.</p>
                        <div class="flex justify-between items-center">
                            <span class="text-lg font-bold text-green-700">₹50/200g</span>
                            <button class="bg-green-700 hover:bg-green-600 text-white px-4 py-2 rounded-full text-sm">Add to Cart</button>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="text-center mt-12">
                <a href="#" class="border-2 border-green-700 text-green-700 hover:bg-green-700 hover:text-white px-8 py-3 rounded-full font-bold transition duration-300 inline-block">View All Products</a>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials" class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-green-800 mb-4">What Our Customers Say</h2>
                <p class="text-gray-600 max-w-3xl mx-auto">Authentic feedback from happy customers across the city</p>
            </div>
            
            <div class="relative max-w-4xl mx-auto h-64">
                <!-- Testimonial 1 -->
                <div class="testimonial-slide active text-center">
                    <div class="flex justify-center mb-6">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/658d43f1-7f5f-4dc3-b157-e4dd21878e16.png" alt="Middle-aged woman smiling with groceries in her hands" class="rounded-full w-20 h-20 object-cover">
                    </div>
                    <p class="text-gray-600 italic mb-4">"Dudh Diary milk has transformed our morning tea ritual. The richness and creaminess is unmatched by any other brand we've tried. We've been loyal customers for 5 years now!"</p>
                    <h4 class="font-bold text-green-800">Mrs. Sharma</h4>
                    <p class="text-gray-500 text-sm">Regular Customer Since 2018</p>
                </div>
                
                <!-- Testimonial 2 -->
                <div class="testimonial-slide text-center">
                    <div class="flex justify-center mb-6">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/a0206647-2c60-4098-84c8-072e4001fbae.png" alt="Elderly gentleman holding a glass of milk" class="rounded-full w-20 h-20 object-cover">
                    </div>
                    <p class="text-gray-600 italic mb-4">"As someone who grew up on farm-fresh milk, I can vouch for Dudh Diary's authenticity. Their products remind me of my childhood in the village. The ghee especially is top-notch."</p>
                    <h4 class="font-bold text-green-800">Mr. Patel</h4>
                    <p class="text-gray-500 text-sm">Retired Teacher</p>
                </div>
                
                <!-- Testimonial 3 -->
                <div class="testimonial-slide text-center">
                    <div class="flex justify-center mb-6">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/74d4bc58-906d-4ddc-b5c3-a9451b045e2c.png" alt="Young mother with baby choosing dairy products" class="rounded-full w-20 h-20 object-cover">
                    </div>
                    <p class="text-gray-600 italic mb-4">"With a growing toddler, I'm very particular about what goes into his food. Dudh Diary gives me peace of mind with their pure, additive-free products. The curd is my baby's favorite!"</p>
                    <h4 class="font-bold text-green-800">Priya Singh</h4>
                    <p class="text-gray-500 text-sm">Health-Conscious Mom</p>
                </div>
            </div>
            
            <div class="flex justify-center mt-8 space-x-2">
                <button onclick="showSlide(0)" class="w-3 h-3 rounded-full bg-green-700 focus:outline-none"></button>
                <button onclick="showSlide(1)" class="w-3 h-3 rounded-full bg-green-300 focus:outline-none"></button>
                <button onclick="showSlide(2)" class="w-3 h-3 rounded-full bg-green-300 focus:outline-none"></button>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-gray-50">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-green-800 mb-4">Get In Touch</h2>
                <p class="text-gray-600 max-w-3xl mx-auto">We'd love to hear from you. Reach out for inquiries, feedback or to start your dairy subscription.</p>
            </div>
            
            <div class="flex flex-col md:flex-row gap-10">
                <div class="md:w-1/2">
                    <form class="space-y-4">
                        <div>
                            <label for="name" class="block text-gray-700 mb-2">Full Name</label>
                            <input type="text" id="name" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-green-600" required>
                        </div>
                        <div>
                            <label for="email" class="block text-gray-700 mb-2">Email Address</label>
                            <input type="email" id="email" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-green-600" required>
                        </div>
                        <div>
                            <label for="phone" class="block text-gray-700 mb-2">Phone Number</label>
                            <input type="tel" id="phone" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-green-600">
                        </div>
                        <div>
                            <label for="message" class="block text-gray-700 mb-2">Your Message</label>
                            <textarea id="message" rows="4" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-green-600"></textarea>
                        </div>
                        <button type="submit" class="bg-green-700 hover:bg-green-600 text-white px-8 py-3 rounded-full font-bold transition duration-300 w-full">Send Message</button>
                    </form>
                </div>
                
                <div class="md:w-1/2">
                    <div class="bg-white p-8 rounded-lg shadow-md h-full">
                        <h3 class="text-xl font-bold text-green-800 mb-6">Contact Information</h3>
                        <div class="space-y-5">
                            <div class="flex items-start">
                                <div class="bg-green-100 p-3 rounded-full mr-4">
                                    <svg class="w-6 h-6 text-green-700" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"></path>
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"></path>
                                    </svg>
                                </div>
                                <div>
                                    <h4 class="font-bold text-gray-700">Our Location</h4>
                                    <p class="text-gray-600">123 Dairy Farm Road, Village Green, Mumbai, Maharashtra - 400001</p>
                                </div>
                            </div>
                            <div class="flex items-start">
                                <div class="bg-green-100 p-3 rounded-full mr-4">
                                    <svg class="w-6 h-6 text-green-700" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path>
                                    </svg>
                                </div>
                                <div>
                                    <h4 class="font-bold text-gray-700">Email Us</h4>
                                    <p class="text-gray-600">info@dudhdiary.com<br>orders@dudhdiary.com</p>
                                </div>
                            </div>
                            <div class="flex items-start">
                                <div class="bg-green-100 p-3 rounded-full mr-4">
                                    <svg class="w-6 h-6 text-green-700" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"></path>
                                    </svg>
                                </div>
                                <div>
                                    <h4 class="font-bold text-gray-700">Call Us</h4>
                                    <p class="text-gray-600">+91 9876543210<br>+91 1800-DUDH-MILK</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-green-800 text-white py-12">
        <div class="container mx-auto px-6">
            <div class="flex flex-col md:flex-row justify-between items-center">
                <div class="mb-8 md:mb-0">
                    <div class="flex items-center mb-4">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/56314d21-296b-4e8c-9629-5bb14990c887.png" alt="दूध logo - circular emblem with a milk jug and cow silhouette in white against dark green background" class="h-12 mr-3">
                        <span class="text-xl font-bold">दूध</span>
                    </div>
                    <p class="max-w-xs text-green-200">Pure, fresh dairy products from our family to yours. Farm to table freshness guaranteed.</p>
                </div>
                
                <div class="grid grid-cols-2 md:grid-cols-3 gap-10 md:gap-20">
                    <div>
                        <h3 class="font-bold text-lg mb-4">Quick Links</h3>
                        <ul class="space-y-2">
                            <li><a href="#home" class="text-green-200 hover:text-white">Home</a></li>
                            <li><a href="#about" class="text-green-200 hover:text-white">About Us</a></li>
                            <li><a href="#products" class="text-green-200 hover:text-white">Products</a></li>
                            <li><a href="#testimonials" class="text-green-200 hover:text-white">Testimonials</a></li>
                            <li><a href="#contact" class="text-green-200 hover:text-white">Contact</a></li>
                        </ul>
                    </div>
                    <div>
                        <h3 class="font-bold text-lg mb-4">Products</h3>
                        <ul class="space-y-2">
                            <li><a href="#" class="text-green-200 hover:text-white">Milk</a></li>
                            <li><a href="#" class="text-green-200 hover:text-white">Paneer</a></li>
                            <li><a href="#" class="text-green-200 hover:text-white">Ghee</a></li>
                            <li><a href="#" class="text-green-200 hover:text-white">Curd</a></li>
                            <li><a href="#" class="text-green-200 hover:text-white">Butter</a></li>
                        </ul>
                    </div>
                    <div>
                        <h3 class="font-bold text-lg mb-4">Connect With Us</h3>
                        <div class="flex space-x-4">
                            <a href="#" class="bg-green-700 hover:bg-green-600 p-3 rounded-full">
                                <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24">
                                    <path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"></path>
                                </svg>
                            </a>
                            <a href="#" class="bg-green-700 hover:bg-green-600 p-3 rounded-full">
                                <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24">
                                    <path d="M12.315 2c2.43 0 2.784.013 3.808.06 1.064.049 1.791.218 2.427.465a4.902 4.902 0 011.772 1.153 4.902 4.902 0 011.153 1.772c.247.636.416 1.363.465 2.427.048 1.067.06 1.407.06 4.123v.08c0 2.643-.012 2.987-.06 4.043-.049 1.064-.218 1.791-.465 2.427a4.902 4.902 0 01-1.153 1.772 4.902 4.902 0 01-1.772 1.153c-.636.247-1.363.416-2.427.465-1.067.048-1.407.06-4.123.06h-.08c-2.643 0-2.987-.012-4.043-.06-1.064-.049-1.791-.218-2.427-.465a4.902 4.902 0 01-1.772-1.153 4.902 4.902 0 01-1.153-1.772c-.247-.636-.416-1.363-.465-2.427-.047-1.024-.06-1.379-.06-3.808v-.63c0-2.43.013-2.784.06-3.808.049-1.064.218-1.791.465-2.427a4.902 4.902 0 011.153-1.772A4.902 4.902 0 015.45 2.525c.636-.247 1.363-.416 2.427-.465C8.901 2.013 9.256 2 11.685 2h.63zm-.081 1.802h-.468c-2.456 0-2.784.011-3.807.058-.975.045-1.504.207-1.857.344-.467.182-.8.398-1.15.748-.35.35-.566.683-.748 1.15-.137.353-.3.882-.344 1.857-.047 1.023-.058 1.351-.058 3.807v.468c0 2.456.011 2.784.058 3.807.045.975.207 1.504.344 1.857.182.466.399.8.748 1.15.35.35.683.566 1.15.748.353.137.882.3 1.857.344 1.054.048 1.37.058 4.041.058h.08c2.597 0 2.917-.01 3.96-.058.976-.045 1.505-.207 1.858-.344.466-.182.8-.398 1.15-.748.35-.35.566-.683.748-1.15.137-.353.3-.882.344-1.857.048-1.055.058-1.37.058-4.041v-.08c0-2.597-.01-2.917-.058-3.96-.045-.976-.207-1.505-.344-1.858a3.097 3.097 0 00-.748-1.15 3.098 3.098 0 00-1.15-.748c-.353-.137-.882-.3-1.857-.344-1.023-.047-1.351-.058-3.807-.058zM12 6.865a5.135 5.135 0 110 10.27 5.135 5.135 0 010-10.27zm0 1.802a3.333 3.333 0 100 6.666 3.333 3.333 0 000-6.666zm5.338-3.205a1.2 1.2 0 110 2.4 1.2 1.2 0 010-2.4z"></path>
                                </svg>
                            </a>
                            <a href="#" class="bg-green-700 hover:bg-green-600 p-3 rounded-full">
                                <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24">
                                    <path d="M8.29 20.251c7.547 0 11.675-6.253 11.675-11.675 0-.178 0-.355-.012-.53A8.348 8.348 0 0022 5.92a8.19 8.19 0 01-2.357.646 4.118 4.118 0 001.804-2.27 8.224 8.224 0 01-2.605.996 4.107 4.107 0 00-6.993 3.743 11.65 11.65 0 01-8.457-4.287 4.106 4.106 0 001.27 5.477A4.072 4.072 0 012.8 9.713v.052a4.105 4.105 0 003.292 4.022 4.095 4.095 0 01-1.853.07 4.108 4.108 0 003.834 2.85A8.233 8.233 0 012 18.407a11.616 11.616 0 006.29 1.84"></path>
                                </svg>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="border-t border-green-700 mt-12 pt-8 text-center text-green-200">
                <p>© 2023 दूध. All rights reserved.</p>
                <div class="mt-2">
                    <a href="#" class="text-green-200 hover:text-white mx-2">Privacy Policy</a>
                    <a href="#" class="text-green-200 hover:text-white mx-2">Terms of Service</a>
                    <a href="#" class="text-green-200 hover:text-white mx-2">Shipping Policy</a>
                </div>
            </div>
        </div>
    </footer>

    <!-- Back to Top Button -->
    <button onclick="topFunction()" id="backToTop" class="hidden fixed bottom-8 right-8 bg-green-700 text-white p-3 rounded-full shadow-lg hover:bg-green-600 focus:outline-none">
        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 10l7-7m0 0l7 7m-7-7v18"></path>
        </svg>
    </button>

    <script>
        // Testimonial Slider
        let currentSlide = 0;
        const slides = document.querySelectorAll('.testimonial-slide');
        
        function showSlide(n) {
            slides.forEach(slide => slide.classList.remove('active'));
            currentSlide = n;
            slides[n].classList.add('active');
            
            // Update indicator buttons
            const buttons = document.querySelectorAll('#testimonials button');
            buttons.forEach((btn, index) => {
                if(index === n) {
                    btn.classList.replace('bg-green-300', 'bg-green-700');
                } else {
                    btn.classList.replace('bg-green-700', 'bg-green-300');
                }
            });
        }
        
        // Auto slide change every 5 seconds
        setInterval(() => {
            currentSlide = (currentSlide + 1) % slides.length;
            showSlide(currentSlide);
        }, 5000);
        
        // Back to top button
        const backToTopBtn = document.getElementById('backToTop');
        
        window.onscroll = function() {
            if (document.body.scrollTop > 300 || document.documentElement.scrollTop > 300) {
                backToTopBtn.classList.remove('hidden');
            } else {
                backToTopBtn.classList.add('hidden');
            }
        };
        
        function topFunction() {
            window.scrollTo({top: 0, behavior: 'smooth'});
        }
        
        // Mobile menu toggle (can be expanded if needed)
        const mobileMenuBtn = document.querySelector('nav button');
        const mobileMenu = document.querySelector('nav .hidden.md\\:flex');
        
        mobileMenuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
            mobileMenu.classList.toggle('flex');
            mobileMenu.classList.toggle('flex-col');
            mobileMenu.classList.toggle('absolute');
            mobileMenu.classList.toggle('top-16');
            mobileMenu.classList.toggle('left-0');
            mobileMenu.classList.toggle('right-0');
            mobileMenu.classList.toggle('bg-white');
            mobileMenu.classList.toggle('p-4');
            mobileMenu.classList.toggle('shadow-md');
        });
    </script>
</body>
</html>
