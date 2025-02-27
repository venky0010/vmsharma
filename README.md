<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Venkatesh Mohan Sharma | Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            font-family: "Trebuchet MS", sans-serif;
        }
        h2 {
            font-family: "Arial Black", sans-serif;
        }
        .modal {
            transition: transform 0.3s ease-out, opacity 0.3s ease-out;
        }
    </style>
    <script>
        function showRecommendations() {
            document.getElementById('recommendationModal').classList.remove('hidden');
            document.getElementById('recommendationModal').classList.add('flex');
        }
        function closeRecommendations() {
            document.getElementById('recommendationModal').classList.add('hidden');
            document.getElementById('recommendationModal').classList.remove('flex');
        }
    </script>
</head>
<body class="bg-gray-900 text-white">
    <div class="flex flex-col md:flex-row h-auto md:h-screen">
        <!-- Left Sidebar -->
        <div class="w-full md:w-1/5 bg-gradient-to-b from-gray-700 to-black p-4 flex flex-col items-center text-center">
            <img src="myimage.jpeg" alt="Venkatesh Mohan Sharma" class="w-28 h-28 rounded-full border-4 border-gray-500">
            <h2 class="mt-3 text-base font-semibold">Venkatesh Mohan Sharma</h2>
            <p class="mt-1 text-gray-300 text-xs">Redmond, Washington</p>
            <div class="mt-3 flex flex-row justify-center space-x-3 items-center text-xs">
                <a href="https://www.linkedin.com/in/venkateshmsharma/" class="flex items-center space-x-1 text-blue-400 hover:text-blue-600">
                    <img src="linkedin.png" alt="LinkedIn" class="w-4 h-4">
                    <span>LinkedIn</span>
                </a>
                <a href="https://github.com/venky0010?tab=repositories" class="flex items-center space-x-1 text-gray-400 hover:text-gray-600">
                    <img src="github.png" alt="GitHub" class="w-4 h-4">
                    <span>GitHub</span>
                </a>
            </div>
            
            <!-- About Section -->
            <div class="mt-4 text-gray-300 text-xs w-full text-left">
                <p>Experienced Product Owner with expertise in product management, stakeholder management, process improvement, data analytics, and automation. Skilled in using experimentation, machine learning, and data modeling to create statistical solutions. Proven ability to drive data-driven decisions by automating processes, generating insightful reports, and optimizing workflows. Passionate about sports, especially Manchester United and the Houston Astros.</p>
            </div>
            
            <!-- Education Section -->
            <div class="mt-6 text-gray-300 text-xs w-full text-left">
                <h3 class="text-sm font-semibold text-white">Education</h3>
                <div class="flex items-center mt-3">
                    <img src="uh.png" alt="University of Houston" class="w-12 h-12 mr-2">
                    <div>
                        <p>University of Houston</p>
                        <p class="text-xs">Masters in Industrial Engineering</p>
                    </div>
                </div>
                <div class="flex items-center mt-3">
                    <img src="vtu.png" alt="VTU" class="w-12 h-12 mr-2">
                    <div>
                        <p>Visvesvaraya Technological University</p>
                        <p class="text-xs">Bachelors in Mechanical Engineering</p>
                    </div>
                </div>
            </div>
        </div>
        
        <!-- Right Side -->

        <div class="w-full md:w-4/5 flex flex-col p-6 bg-gradient-to-b from-gray-900 to-gray-700">
            <!-- Experiences Section -->
            <div class="w-full p-6 rounded-xl flex flex-col" style="min-height: 85vh;">
                <h3 class="text-lg font-semibold text-white mb-4">Experiences</h3>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-4 flex-grow">
                    <div class="flex items-center">
                        <img src="enpro.png" alt="EnPro" class="w-20 h-auto mr-3 object-contain">
                        <div>
                            <h4 class="text-sm font-semibold">EnPro Industries</h4>
                            <p class="italic text-xs text-gray-300">Product Owner Intern</p>
                            <p class="text-xs text-gray-200">Supervisor: <a href="abc" class="text-blue-400">Hao Dinh</a></p>
			    <p class="text-sm text-gray-200">Projects: Supply Chain optimization</p>
			    <p class="text-sm text-gray-200">Improvements/Savings: 1. Saved $270K per year  2. Saved 240+ manual hours annually</p>
			    <p class="text-sm text-gray-200">Skills/Tools: Automation Anywhere, Azure AI, Power Power App, Power Automate, Python, Power BI, SQL, Oracle, Netsuite, API Webservies, Postman, AWS Datahub, Redshift, JIRA, Smartsheet, Supply Chain Optimization, Procurement</p>
                        </div>
                    </div>
                    <div class="flex items-center">
                        <img src="garlock.png" alt="Garlock" class="w-20 h-auto mr-3 object-contain">
                        <div>
                            <h4 class="text-sm font-semibold">Garlock</h4>
                            <p class="italic text-xs text-gray-300">Industrial Engineering and Analytics Intern</p>
                            <p class="text-xs text-gray-400">Supervisor: <a href="bcd" class="text-blue-400">Aldo Ovalle</a></p>
			    <p class="text-sm text-gray-200">Projects: Continuous Improvement, Capacity Analysis and Analytics</p>
			    <p class="text-sm text-gray-200">Improvements/Savings: 1. Increased Production by 17%  2. Reduced variance by 12% acheiving production consistency</p>
			    <p class="text-sm text-gray-200">Skills/Tools: Lean Principles, Six Sigma, Python, PowerBI, Power Automate, Excel, t-test, beta distribution</p>
                        </div>
                    </div>
		   <div class="flex items-center">
                        <img src="asml.png" alt="ASML" class="w-20 h-auto mr-3 object-contain">
                        <div>
                            <h4 class="text-sm font-semibold">ASML</h4>
                            <p class="italic text-xs text-gray-300">Data Analytics Intern</p>
                            <p class="text-xs text-gray-400">Supervisor: <a href="bcd" class="text-blue-400">Dylan Holton</a></p>
			    <p class="text-sm text-gray-200">Projects: Analytics and Automation</p>
			    <p class="text-sm text-gray-200">Improvements/Savings: 1. Increase on time PM task completion rate by 80%  2. Improved process by 3-fold</p>
			    <p class="text-sm text-gray-200">Skills/Tools: Python, Power Automate, Spotfire, Chi-square test, t-test, correlation analysis</p>
                        </div>
                    </div>
                    <div class="flex items-center">
                        <img src="rbc.png" alt="Bosch" class="w-20 h-auto mr-3 object-contain">
                        <div>
                            <h4 class="text-sm font-semibold">Robert Bosch Centre for Data Science and AI</h4>
                            <p class="italic text-xs text-gray-300">Project Associate</p>
                            <p class="text-xs text-gray-400">Supervisor: <a href="https://doms.iitm.ac.in/index.php/nandan-s" class="text-blue-400">Nandan Sudarsanam</a></p>
			    <p class="text-sm text-gray-200">Projects: Forecasting, Data Anomaly Detection, Simulation, and Analytics</p>
			    <p class="text-sm text-gray-200">Improvements/Savings: 1. Replaced month long data reconciliation process by Knowledge Graph  2. Improved click thorugh rate by 5%</p>
			    <p class="text-sm text-gray-200">Skills/Tools: Python, Keras, PyTorch, Numpy, Pandas, Contextual Bandit Algorithm, CART, Clustering, ARIMA, Deep-AR, Chi-square Test for Independence, Normal Distribution, beta distribution</p>
                        </div>
                    </div>
		    <div class="flex items-center">
                        <img src="bauer.jpeg" alt="Bauer College" class="w-20 h-auto mr-3 object-contain">
                        <div>
                            <h4 class="text-sm font-semibold">Bauer College of Business, UH</h4>
                            <p class="italic text-xs text-gray-300">Instructional Assistant</p>
                            <p class="text-xs text-gray-400">Supervisor: <a href="https://www.bauer.uh.edu/search/directory/profile.asp?firstname=Ravi&lastname=Aron" class="text-blue-400">Ravi Aron</a></p>
			    <p class="text-sm text-gray-200">Projects: Experimental Design, Regression Analysis, Surveys, Market Research</p>
			    <p class="text-sm text-gray-200">Skills/Tools: Python, STATA, Excel, Factor Analysis, Regression, parametric and non parametric tests, VIF</p>
                        </div>
                    </div>
                    <div class="flex items-center">
                        <img src="doms.png" alt="Doms" class="w-20 h-auto mr-3 object-contain">
                        <div>
                            <h4 class="text-sm font-semibold">Indian Institute of Technology, Madras</h4>
                            <p class="italic text-xs text-gray-300">Data Science Intern</p>
                            <p class="text-xs text-gray-400">Supervisor: <a href="https://doms.iitm.ac.in/index.php/rrm" class="text-blue-400">Rahul Marathe</a></p>
			    <p class="text-sm text-gray-200">Projects: Regerssion Analysis and Fator Analysis</p>
			    <p class="text-sm text-gray-200">Skills/Tools: Python, SPSS-AMOS, Clutering, Regression, Unsupervised Learning</p>
                        </div>
                    </div>
                </div>
            </div>
            
            <!-- Bottom Section -->
            <div class="w-full grid grid-cols-3 gap-4 mt-4">
                <div class="bg-gray-800 p-4 text-center rounded-xl text-white font-semibold cursor-pointer" onclick="showRecommendations()">Recommendations</div>
                <div class="bg-gray-800 p-4 text-center rounded-xl text-white font-semibold">Certifications</div>
                <div class="bg-gray-800 p-4 text-center rounded-xl text-white font-semibold">Publication</div>
            </div>
        </div>
    </div>

    <!-- Recommendations Modal -->
    <div id="recommendationModal" class="hidden fixed inset-0 bg-black bg-opacity-75 justify-center items-center">
        <div class="bg-gray-900 p-6 rounded-lg w-3/4 grid grid-cols-2 gap-4">
            <img src="reco3.png" alt="Recommendation 3" class="rounded-lg">
            <img src="reco2.png" alt="Recommendation 2" class="rounded-lg">
            <img src="reco1.png" alt="Recommendation 1" class="rounded-lg">
            <img src="reco4.png" alt="Recommendation 4" class="rounded-lg">
            <button class="bg-red-500 px-4 py-2 rounded text-white col-span-2" onclick="closeRecommendations()">Close</button>
        </div>
    </div>
</body>
</html>
