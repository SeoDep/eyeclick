<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page Relevance Analysis - Business Model</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Montserrat', sans-serif;
            background-color: #f8f9fa;
        }
        /* Custom colors */
        .bg-custom-purple { background-color: #8d5fa7; }
        .text-custom-purple { color: #8d5fa7; }
        .border-custom-purple { border-color: #8d5fa7; }
        .bg-custom-gray { background-color: #cbcfd6; }

        .card {
            background-color: white;
            border-radius: 12px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.05);
            transition: all 0.3s ease-in-out;
            border: 1px solid #e9ecef;
            height: 100%;
            display: flex;
            flex-direction: column;
        }
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.08);
        }
        .card-header {
            padding: 1rem 1.5rem;
            border-bottom: 1px solid #e9ecef;
            border-top-left-radius: 12px;
            border-top-right-radius: 12px;
        }
        .card-body {
            padding: 1.5rem;
            flex-grow: 1;
        }
        .card-body ul {
            list-style: none;
            padding: 0;
        }
        .card-body li {
            padding: 0.75rem 0;
            border-bottom: 1px solid #f1f3f5;
            color: #495057;
        }
        .card-body li:last-child {
            border-bottom: none;
        }
        .level-icon {
            width: 24px;
            height: 24px;
            border-radius: 50%;
            display: inline-block;
            margin-right: 12px;
        }
    </style>
</head>
<body class="flex items-center justify-center min-h-screen p-4 sm:p-6 md:p-8">

    <div class="w-full max-w-6xl mx-auto">
        <div class="text-center mb-12">
            <h1 class="text-4xl font-bold text-gray-800">Strategic Page Hierarchy</h1>
        </div>

        <!-- Grid Container -->
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">

            <!-- Level 1: Core Pages -->
            <div class="card border-custom-purple border-2">
                <div class="card-header bg-custom-purple">
                    <h2 class="text-xl font-semibold text-white flex items-center">
                        <span class="level-icon bg-white/50"></span>
                        Level 1: Core Pages
                    </h2>
                </div>
                <div class="card-body">
                    <p class="text-gray-600 mb-4">The most strategic pages with the highest relevance and conversion potential for the business.</p>
                    <p class="text-sm text-gray-500 italic mb-3">Examples include:</p>
                    <ul>
                        <li class="font-semibold text-custom-purple">Entertainment</li>
                        <li class="font-semibold text-custom-purple">Education</li>
                        <li class="font-semibold text-custom-purple">Senior Care</li>
                    </ul>
                </div>
            </div>

            <!-- Level 2: Secondary Pages -->
            <div class="card">
                <div class="card-header bg-custom-gray">
                    <h2 class="text-xl font-semibold text-gray-800 flex items-center">
                        <span class="level-icon bg-white/50"></span>
                        Level 2: Secondary Pages
                    </h2>
                </div>
                <div class="card-body">
                    <p class="text-gray-600 mb-4">High-value sub-segments designed to capture more targeted (long-tail) traffic.</p>
                    <p class="text-sm text-gray-500 italic mb-3">Examples include:</p>
                    <ul>
                        <li>Church Entertainment</li>
                        <li>Hospital Waiting Rooms</li>
                        <li>Dementia Interactive Games</li>
                    </ul>
                </div>
            </div>

            <!-- Level 3: Supporting Pages -->
            <div class="card">
                <div class="card-header bg-gray-100">
                    <h2 class="text-xl font-semibold text-gray-700 flex items-center">
                        <span class="level-icon bg-gray-300"></span>
                        Level 3: Supporting Pages
                    </h2>
                </div>
                <div class="card-body">
                    <p class="text-gray-600 mb-4">General pages for broad discovery and targeting keywords with mixed search intent.</p>
                    <p class="text-sm text-gray-500 italic mb-3">Examples include:</p>
                    <ul>
                        <li>Educational games</li>
                        <li>Future school</li>
                        <li>Games to prevent dementia</li>
                    </ul>
                </div>
            </div>

        </div>
    </div>

</body>
</html>
