---
layout: default
title: Dainis Silamikelis - Software Architect
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dainis Silamikelis - Software Architect</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">
    <header class="bg-gradient-to-r from-blue-800 to-purple-800 text-white py-20 text-center">
        <h1 class="text-5xl font-bold">Dainis Silamikelis</h1>
        <p class="text-2xl mt-4">Software Architect | Cloud Enthusiast | Team Leader</p>
        <p class="mt-4">Riga, Latvia | <a href="mailto:dainis.silamikelis@gmail.com" class="text-blue-300 underline">dainis.silamikelis@gmail.com</a></p>
        <div class="mt-6 flex justify-center gap-4">
            <a href="https://linkedin.com/in/dainis-silamikelis" target="_blank" class="bg-white text-blue-800 py-2 px-4 rounded shadow hover:bg-gray-200">LinkedIn</a>
            <a href="https://github.com/dainissilamikelis" target="_blank" class="bg-white text-blue-800 py-2 px-4 rounded shadow hover:bg-gray-200">GitHub</a>
        </div>
    </header>

    <main class="container mx-auto px-6 py-12">
        <section id="about" class="mb-16">
            <h2 class="text-3xl font-bold text-center mb-6">About Me</h2>
            <p class="text-lg text-center">Passionate developer and leader with over 8 years of IT experience, including 5+ years leading teams. Adept at creating scalable, efficient solutions and high-performing teams. Enthusiastic about cloud services, education, and modern technology trends. Chess player and miniature painter in my free time.</p>
        </section>

        <section id="skills" class="mb-16">
            <h2 class="text-3xl font-bold text-center mb-6">Skills</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <div class="p-6 bg-white rounded shadow">
                    <h3 class="font-semibold text-lg">Cloud & Infrastructure</h3>
                    <p>AWS, Infrastructure as Code (Terraform), Serverless Architecture</p>
                </div>
                <div class="p-6 bg-white rounded shadow">
                    <h3 class="font-semibold text-lg">Programming</h3>
                    <p>JavaScript, Python, OOP, UI/UX Design</p>
                </div>
                <div class="p-6 bg-white rounded shadow">
                    <h3 class="font-semibold text-lg">Leadership</h3>
                    <p>Team Management, Agile Development, Communication</p>
                </div>
            </div>
        </section>

        <section id="experience" class="mb-16">
            <h2 class="text-3xl font-bold text-center mb-6">Professional Experience</h2>
            <div class="space-y-8">
                <div class="p-6 bg-white rounded shadow">
                    <h3 class="text-xl font-semibold">Software Development Manager & Architect</h3>
                    <p class="text-gray-600">SIA 1NCE | January 2024 - Present</p>
                    <ul class="list-disc list-inside mt-2">
                        <li>Oversaw products such as Web-Probes, Jira Integration, and Performance Page Overview.</li>
                        <li>Improved operational success and delivered value for managed projects.</li>
                    </ul>
                </div>
                <div class="p-6 bg-white rounded shadow">
                    <h3 class="text-xl font-semibold">Team Lead & Senior Software Engineer</h3>
                    <p class="text-gray-600">SIA 1NCE | April 2022 - January 2024</p>
                    <ul class="list-disc list-inside mt-2">
                        <li>Developed tools like Web Probes and Jira Integration.</li>
                        <li>Built and trained teams for front-end and integration tasks.</li>
                    </ul>
                </div>
                <div class="p-6 bg-white rounded shadow">
                    <h3 class="text-xl font-semibold">Tech Lead</h3>
                    <p class="text-gray-600">SIA VISASIESPEJAS | October 2019 - October 2020</p>
                    <ul class="list-disc list-inside mt-2">
                        <li>Rebuilt architecture using modern JavaScript approaches and AWS.</li>
                        <li>Worked on DevOps, full-stack development, and NoSQL migrations.</li>
                    </ul>
                </div>
            </div>
        </section>

        <section id="education" class="mb-16">
            <h2 class="text-3xl font-bold text-center mb-6">Education</h2>
            <ul class="space-y-6">
                <li class="p-6 bg-white rounded shadow">
                    <h3 class="font-semibold">Master's in Computer Science</h3>
                    <p>University of Latvia, 2018-2022</p>
                </li>
                <li class="p-6 bg-white rounded shadow">
                    <h3 class="font-semibold">Bachelor's in Physics</h3>
                    <p>University of Latvia, 2013-2015</p>
                </li>
            </ul>
        </section>

        <section id="certifications" class="mb-16">
            <h2 class="text-3xl font-bold text-center mb-6">Certifications</h2>
            <ul class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <li class="p-6 bg-white rounded shadow">AWS Certified Cloud Practitioner (2021 - 2024)</li>
                <li class="p-6 bg-white rounded shadow">ICAgile Certified Professional</li>
                <li class="p-6 bg-white rounded shadow">Advanced React (FrontCon, 2020)</li>
            </ul>
        </section>

        <section id="contact" class="text-center">
            <h2 class="text-3xl font-bold mb-6">Contact</h2>
            <div class="inline-flex space-x-4">
                <a href="mailto:dainis.silamikelis@gmail.com" class="bg-blue-600 hover:bg-blue-700 text-white py-2 px-6 rounded">Email Me</a>
                <a href="https://linkedin.com/in/dainis-silamikelis" target="_blank" class="bg-gray-600 hover:bg-gray-700 text-white py-2 px-6 rounded">LinkedIn</a>
                <a href="https://github.com/dainissilamikelis" target="_blank" class="bg-black hover:bg-gray-800 text-white py-2 px-6 rounded">GitHub</a>
            </div>
        </section>
    </main>

    <footer class="bg-gray-900 text-white text-center py-4">
        <p>© {{ "now" | date: "%Y" }} Dainis Silamikelis. All rights reserved.</p>
    </footer>
</body>
</html>
