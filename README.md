<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive Dashboard Boilerplate </title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100">
    <!-- header -->
<div class="flex-1 flex flex-col">
    <nav class="bg-white p-4 shadow flex justify-between">
            <div>  <h2 class="mx-[-3px] text-xl font-bold">Dashboard</h2> </div>  
            <div class="space-x-4">
            <a href="#" class="text-gray-600 hover:text-gray-900">Profile</a>
            <a href="#" class="text-gray-600 hover:text-gray-900">Settings</a>
            <a href="#" class="text-gray-600 hover:text-gray-900">Logout</a>
        </div>
    </nav>
<div class="flex h-screen">
    <div class="w-64 bg-gray-800 text-white p-5 space-y-5">    
        <nav class="">
            <ul class="space-y-4">
                <li><a href="#" class="mx-[-10px] block px-3 py-2 hover:bg-gray-700 rounded">Dashboard</a></li>
                <li><a href="#" class="mx-[-10px] block px-3 py-2 hover:bg-gray-700 rounded">Users</a></li>
                <li><a href="#" class="mx-[-10px] block px-3 py-2 hover:bg-gray-700 rounded">Reports</a></li>
                <li><a href="#" class="mx-[-10px] block px-3 py-2 hover:bg-gray-700 rounded">Settings</a></li>
            </ul>
        </nav>
    </div>
        <!-- Main -->
            <main class="flex-1 p-6">
                <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                    <div class="bg-white p-6 rounded-lg shadow">
                        <h3 class="text-lg font-bold">Card Title 1</h3>
                        <p class="text-gray-600 mt-2">Content for card 1.</p>
                    </div>
                    <div class="bg-white p-6 rounded-lg shadow">
                        <h3 class="text-lg font-bold">Card Title 2</h3>
                        <p class="text-gray-600 mt-2">Content for card 2.</p>
                    </div>
                    <div class="bg-white p-6 rounded-lg shadow">
                        <h3 class="text-lg font-bold">Card Title 3</h3>
                        <p class="text-gray-600 mt-2">Content for card 3.</p>
                    </div>
                </div>
            </main>
        </div>
    </div>
    <!-- Footer -->
    <footer class="text-center text-gray-500 text-sm py-4">

<hr><br> © 2025 Your Company. All rights reserved.
    </footer>

</body>
</html>
