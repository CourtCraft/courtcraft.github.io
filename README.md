<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mental Match Play Checklist Infographic</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        .chart-container {
            position: relative;
            margin: auto;
            height: 300px;
            width: 100%;
            max-width: 600px;
        }
        @media (min-width: 768px) {
            .chart-container {
                height: 350px;
            }
        }
        .flowchart-step {
            clip-path: polygon(0 0, 85% 0, 100% 50%, 85% 100%, 0 100%);
        }
    </style>
</head>
<body class="bg-slate-100 text-slate-800">

    <div class="container mx-auto p-4 md:p-8">

        <header class="mb-12">
            <!-- Logo Section -->
            <div class="text-left mb-6 flex items-center">
                <img src=https://lh3.googleusercontent.com/pw/AP1GczM4vz_H4wgz-bp1h8stBhljj1QbtsGPJdiSzg1wJE1SwpLPuEKpKvoeuc9BJRroBVQzoGSwUq2mBKz7aQH115jPsW4kifLPvmqxotU08m_0MO1BWD9p5x0xa6-86RFfe66Cn2u0yTrwhgnTtwC69nY=w1279-h1279-s-no?authuser=0 alt="Your Company Logo" class="h-16 w-auto rounded-lg ml-4 mr-2">
                <span class="text-2xl font-bold text-slate-900">Court Craft</span>
            </div>
            <h1 class="text-4xl md:text-6xl font-bold text-slate-900 mb-4 text-center">The Unseen Advantage</h1>
            <p class="text-lg md:text-xl text-slate-600 max-w-3xl mx-auto text-center">Mastering the mental game is just as crucial as perfecting your strokes. Here's a breakdown of the mental match play checklist to keep you calm and confident under pressure.</p>
        </header>

        <main class="space-y-12">

            <section id="pre-match">
                <div class="bg-white rounded-lg shadow-lg p-6 md:p-8 transform hover:scale-105 transition-transform duration-300">
                    <h2 class="text-3xl font-bold text-center mb-6 text-teal-600">🚀 Pre-Match Prep: Set the Stage for Success</h2>
                    <p class="text-center text-slate-600 mb-8">Confidence isn't found, it's built. Your mental preparation starts long before the first serve. These steps are your foundation for a strong and resilient mindset on the court.</p>
                    <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6 text-center">
                        <div class="bg-teal-50 p-4 rounded-lg">
                            <div class="text-4xl mb-2">🧠</div>
                            <h3 class="font-semibold text-lg text-teal-800">Visualize Victory</h3>
                            <p class="text-sm text-slate-600">See yourself executing key shots and overcoming challenges.</p>
                        </div>
                        <div class="bg-teal-50 p-4 rounded-lg">
                            <div class="text-4xl mb-2">🎯</div>
                            <h3 class="font-semibold text-lg text-teal-800">Define Your Focus</h3>
                            <p class="text-sm text-slate-600">Choose 1-2 process goals, like "good footwork" or "deep serves".</p>
                        </div>
                        <div class="bg-teal-50 p-4 rounded-lg">
                             <div class="text-4xl mb-2">💬</div>
                            <h3 class="font-semibold text-lg text-teal-800">Positive Self-Talk</h3>
                            <p class="text-sm text-slate-600">Prepare go-to phrases like "Next point!" for tough moments.</p>
                        </div>
                        <div class="bg-teal-50 p-4 rounded-lg">
                            <div class="text-4xl mb-2">👟</div>
                            <h3 class="font-semibold text-lg text-teal-800">Warm-Up with Purpose</h3>
                            <p class="text-sm text-slate-600">Focus on rhythm and feel to sync your body and mind.</p>
                        </div>
                    </div>
                </div>
            </section>

            <section id="during-match">
                <div class="bg-white rounded-lg shadow-lg p-6 md:p-8 transform hover:scale-105 transition-transform duration-300">
                    <h2 class="text-3xl font-bold text-center mb-6 text-amber-600">🏃‍♀️ During the Match: Master the Moment</h2>
                    <p class="text-center text-slate-600 mb-8">The match is a series of moments. Winning the mental battle means winning these small windows of opportunity. Here's how to stay in control when the pressure mounts.</p>
                    <div class="grid md:grid-cols-2 gap-8 items-center">
                        <div>
                            <h3 class="text-xl font-bold mb-4 text-amber-800">The 5-Second Reset Rule</h3>
                            <p class="text-slate-600 mb-4">Between every point, you have a crucial window to reset. This disciplined routine prevents emotions from spiraling and keeps you focused on the present.</p>
                             <div class="chart-container">
                                <canvas id="resetChart"></canvas>
                            </div>
                        </div>
                        <div>
                           <div class="space-y-4">
                               <div class="bg-amber-50 p-4 rounded-lg flex items-center">
                                   <div class="text-2xl mr-4">👀</div>
                                   <div>
                                       <h4 class="font-semibold text-amber-800">Focus on the Ball</h4>
                                       <p class="text-sm text-slate-600">Your primary job is to watch the ball, not the outcome.</p>
                                   </div>
                               </div>
                               <div class="bg-amber-50 p-4 rounded-lg flex items-center">
                                   <div class="text-2xl mr-4">⚙️</div>
                                   <div>
                                       <h4 class="font-semibold text-amber-800">Control the Controllables</h4>
                                       <p class="text-sm text-slate-600">Focus on your effort, attitude, and shot choice.</p>
                                   </div>
                               </div>
                                <div class="bg-amber-50 p-4 rounded-lg flex items-center">
                                   <div class="text-2xl mr-4">🚶‍♀️</div>
                                   <div>
                                       <h4 class="font-semibold text-amber-800">Body Language Boost</h4>
                                       <p class="text-sm text-slate-600">Stand tall and act confident to influence your mindset.</p>
                                   </div>
                               </div>
                               <div class="bg-amber-50 p-4 rounded-lg flex items-center">
                                   <div class="text-2xl mr-4">💡</div>
                                   <div>
                                       <h4 class="font-semibold text-amber-800">Problem-Solve, Don't Panic</h4>
                                       <p class="text-sm text-slate-600">If a tactic fails, mentally adjust. What can you try next?</p>
                                   </div>
                               </div>
                           </div>
                        </div>
                    </div>
                </div>
            </section>
            
            <section id="after-match">
                <div class="bg-white rounded-lg shadow-lg p-6 md:p-8 transform hover:scale-105 transition-transform duration-300">
                    <h2 class="text-3xl font-bold text-center mb-6 text-sky-600">✅ After the Match: Learn & Grow</h2>
                    <p class="text-center text-slate-600 mb-8">The match ends, but the learning doesn't. How you process the result, win or lose, determines your long-term growth as a player. This is where champions are forged.</p>
                    <div class="space-y-6">
                        <h3 class="text-xl font-bold text-sky-800 text-center">Your Post-Match Growth Process</h3>
                        <div class="flex flex-col md:flex-row items-center justify-center space-y-4 md:space-y-0 md:space-x-4">
                            <div class="flowchart-step bg-sky-100 p-4 text-sky-800 w-full md:w-1/4 text-center">
                                <div class="font-bold text-lg">1. Review</div>
                                <p class="text-sm">Did you stick to your pre-match focus points?</p>
                            </div>
                             <div class="hidden md:block text-2xl text-sky-400">&rarr;</div>
                            <div class="flowchart-step bg-sky-200 p-4 text-sky-800 w-full md:w-1/4 text-center">
                               <div class="font-bold text-lg">2. Celebrate</div>
                                <p class="text-sm">Acknowledge small wins, like a great save or a brave shot.</p>
                            </div>
                             <div class="hidden md:block text-2xl text-sky-400">&rarr;</div>
                            <div class="flowchart-step bg-sky-300 p-4 text-sky-800 w-full md:w-1/4 text-center">
                                <div class="font-bold text-lg">3. Analyze</div>
                                <p class="text-sm">What did you learn? No self-criticism, only analysis.</p>
                            </div>
                             <div class="hidden md:block text-2xl text-sky-400">&rarr;</div>
                             <div class="flowchart-step bg-sky-400 p-4 text-white w-full md:w-1/4 text-center">
                               <div class="font-bold text-lg">4. Recharge</div>
                               <p class="text-sm">Reflect on positive takeaways and rest for the next challenge.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
        </main>

        <footer class="text-center mt-12">
            <p class="text-lg font-bold text-slate-900">Confidence is built one point, one breath, one positive thought at a time. 🎾✨</p>
        </footer>

    </div>

    <script>
        function wrapText(label) {
            const words = label.split(' ');
            let line = '';
            const lines = [];
            const maxLength = 16;
            words.forEach((word, i) => {
                const testLine = line + word + ' ';
                if (testLine.length > maxLength && i > 0) {
                    lines.push(line.trim());
                    line = word + ' ';
                } else {
                    line = testLine;
                }
            });
            lines.push(line.trim());
            return lines;
        }

        const tooltipTitleCallback = (tooltipItems) => {
            const item = tooltipItems[0];
            let label = item.chart.data.labels[item.dataIndex];
            if (Array.isArray(label)) {
                return label.join(' ');
            } else {
                return label;
            }
        };

        const ctx = document.getElementById('resetChart').getContext('2d');
        new Chart(ctx, {
            type: 'doughnut',
            data: {
                labels: ['Acknowledge (20%)', 'Release (20%)', 'Plan (40%)', 'Commit (20%)'],
                datasets: [{
                    label: '5-Second Reset',
                    data: [20, 20, 40, 20],
                    backgroundColor: [
                        '#fbbf24', // amber-400
                        '#fcd34d', // amber-300
                        '#f59e0b', // amber-500
                        '#fde68a'  // amber-200
                    ],
                    borderColor: '#ffffff',
                    borderWidth: 3
                }]
            },
            options: {
                responsive: true,
                maintainAspectRatio: false,
                plugins: {
                    legend: {
                        position: 'top',
                    },
                    tooltip: {
                        callbacks: {
                            title: tooltipTitleCallback
                        }
                    },
                    title: {
                        display: true,
                        text: 'Breakdown of the Between-Point Reset'
                    }
                }
            }
        });
    </script>
</body>
</html>
