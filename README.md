<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Capitol Parking Solutions</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-100">
    <!-- Header -->
    <header class="bg-blue-700 text-white py-4">
        <div class="container mx-auto flex justify-between items-center px-4">
            <h1 class="text-2xl font-bold">Capitol Parking Solutions</h1>
            <nav>
                <ul class="flex space-x-4">
                    <li><a href="#services" class="hover:underline">Services</a></li>
                    <li><a href="#contact" class="hover:underline">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="bg-cover bg-center h-64" style="background-color: #1E3A8A;">
        <div class="bg-black bg-opacity-50 h-full flex items-center justify-center">
            <h2 class="text-white text-4xl font-bold">Your Rest, Our Priority</h2>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-12">
        <div class="container mx-auto px-4">
            <h3 class="text-2xl font-bold text-center mb-6">Our Amenities</h3>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-white shadow-lg rounded-lg p-6 text-center">
                    <h4 class="font-bold text-xl mb-4">24/7 Security Cameras</h4>
                    <p>Ensuring safety around the clock.</p>
                </div>
                <div class="bg-white shadow-lg rounded-lg p-6 text-center">
                    <h4 class="font-bold text-xl mb-4">All-Night Lighting</h4>
                    <p>Bright and secure lighting for peace of mind.</p>
                </div>
                <div class="bg-white shadow-lg rounded-lg p-6 text-center">
                    <h4 class="font-bold text-xl mb-4">Numbered Parking Spaces</h4>
                    <p>Clearly assigned spots for easy access.</p>
                </div>
                <div class="bg-white shadow-lg rounded-lg p-6 text-center">
                    <h4 class="font-bold text-xl mb-4">High-Speed Internet</h4>
                    <p>Stay connected while you rest.</p>
                </div>
                <div class="bg-white shadow-lg rounded-lg p-6 text-center">
                    <h4 class="font-bold text-xl mb-4">Disposal Services</h4>
                    <p>Convenient waste management facilities.</p>
                </div>
                <div class="bg-white shadow-lg rounded-lg p-6 text-center">
                    <h4 class="font-bold text-xl mb-4">Controlled Access</h4>
                    <p>Entry restricted to clients for added security.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-12">
        <div class="container mx-auto px-4">
            <h3 class="text-2xl font-bold text-center mb-6">Contact Us</h3>
            <div class="text-center mb-6">
                <p class="text-lg">Capitol Ave. 99301, Pasco, Washington</p>
                <p class="text-lg">Phone: (509) 539 4632</p>
                <p class="text-lg">Email: <a href="mailto:arycoria@live.com" class="text-blue-500 hover:underline">arycoria@live.com</a></p>
            </div>
            <form class="max-w-lg mx-auto bg-white shadow-lg rounded-lg p-6">
                <div class="mb-4">
                    <label for="name" class="block text-gray-700 font-bold mb-2">Name</label>
                    <input type="text" id="name" class="w-full border-gray-300 rounded-lg shadow-sm">
                </div>
                <div class="mb-4">
                    <label for="email" class="block text-gray-700 font-bold mb-2">Email</label>
                    <input type="email" id="email" class="w-full border-gray-300 rounded-lg shadow-sm">
                </div>
                <div class="mb-4">
                    <label for="message" class="block text-gray-700 font-bold mb-2">Message</label>
                    <textarea id="message" class="w-full border-gray-300 rounded-lg shadow-sm"></textarea>
                </div>
                <button type="submit" class="bg-blue-700 text-white py-2 px-4 rounded-lg hover:bg-blue-800">Send</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-blue-700 text-white py-4">
        <div class="container mx-auto text-center">
            <p>&copy; 2025 Capitol Parking Solutions. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
