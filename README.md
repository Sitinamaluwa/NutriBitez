# NutriBitez
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Premium Protein Bars</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <style>
        /* Custom styles for animations */
        .icon {
            transition: transform 0.3s;
        }
        .icon:hover {
            transform: scale(1.1);
        }
    </style>
</head>
<body class="bg-gray-100">

    <!-- Hero Section -->
    <section class="bg-gradient-to-r from-blue-500 to-purple-600 text-white py-20">
        <div class="container mx-auto text-center">
            <h1 class="text-5xl font-bold mb-4">Fuel Your Fitness Journey</h1>
            <p class="text-lg mb-8">Discover our premium protein bars designed for every goal.</p>
            <a href="#products" class="bg-white text-blue-500 px-6 py-3 rounded-full font-semibold">Shop Now</a>
        </div>
    </section>

    <!-- Product Showcase Grid -->
    <section id="products" class="py-20">
        <div class="container mx-auto text-center">
            <h2 class="text-3xl font-bold mb-10">Our Products</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-10">
                <div class="bg-white p-6 rounded-lg shadow-lg">
                    <h3 class="text-xl font-semibold">High-Calorie Bulking Bars</h3>
                    <p class="mt-2">Perfect for muscle gain and energy.</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-lg">
                    <h3 class="text-xl font-semibold">Low-Calorie Cutting Bars</h3>
                    <p class="mt-2">Ideal for weight loss without sacrificing taste.</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-lg">
                    <h3 class="text-xl font-semibold">Protein-Rich Snack Bars</h3>
                    <p class="mt-2">Great for on-the-go nutrition.</p>
                </div>
                <!-- Add more products as needed -->
            </div>
        </div>
    </section>

    <!-- Nutrition Benefits Section -->
    <section class="py-20 bg-gray-200">
        <div class="container mx-auto text-center">
            <h2 class="text-3xl font-bold mb-10">Nutrition Benefits</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-10">
                <div class="flex flex-col items-center">
                    <div class="icon text-4xl mb-4">💪</div>
                    <h3 class="font-semibold">Muscle Gain</h3>
                </div>
                <div class="flex flex-col items-center">
                    <div class="icon text-4xl mb-4">🔥</div>
                    <h3 class="font-semibold">Fat Loss</h3>
                </div>
                <div class="flex flex-col items-center">
                    <div class="icon text-4xl mb-4">⚡</div>
                    <h3 class="font-semibold">Energy Boost</h3>
                </div>
                <div class="flex flex-col items-center">
                    <div class="icon text-4xl mb-4">❤️</div>
                    <h3 class="font-semibold">Heart Health</h3>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-10 bg-gray-800 text-white text-center">
        <p>&copy; 2023 Premium Protein Bars. All rights reserved.</p>
    </footer>

</body>
</html>
