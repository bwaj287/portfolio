# portfolio
A curated portfolio of data visualization projects exploring urban policy, historical data redesigns, and demographic analysis. Built with HTML/CSS for MBAI 5400G.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Xinyu Wang | Data Visualization Portfolio</title>
    <style>
        /* --- RESET & BASIC STYLES (Rubric: Sans-serif fonts) --- */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
            background-color: #fdfbf7; /* Rubric: Unsaturated, warm off-white */
            color: #333;
            line-height: 1.6;
            padding: 20px;
        }

        /* --- LAYOUT (Rubric: Simple Grid) --- */
        .container {
            max-width: 1100px;
            margin: 0 auto;
        }

        header {
            padding: 60px 0 40px;
            border-bottom: 2px solid #eee;
            margin-bottom: 40px;
        }

        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            color: #2c3e50;
        }

        .subtitle {
            font-size: 1.2rem;
            color: #7f8c8d;
            max-width: 600px;
        }

        /* --- PROJECT GRID --- */
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 40px;
        }

        .card {
            background: white;
            border: 1px solid #eee;
            border-radius: 8px;
            overflow: hidden;
            transition: transform 0.2s;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
        }

        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 15px rgba(0,0,0,0.1);
        }

        .card-img {
            width: 100%;
            height: 250px;
            object-fit: cover; /* Keeps images neat in the grid */
            object-position: top;
            border-bottom: 1px solid #eee;
        }

        .card-content {
            padding: 25px;
        }

        .tag {
            font-size: 0.75rem;
            text-transform: uppercase;
            letter-spacing: 1px;
            color: #e67e22; /* Muted accent color */
            font-weight: bold;
            margin-bottom: 10px;
            display: block;
        }

        h3 {
            margin-bottom: 15px;
            font-size: 1.4rem;
        }

        p {
            font-size: 0.95rem;
            color: #555;
            margin-bottom: 15px;
        }

        /* --- FOOTER --- */
        footer {
            margin-top: 80px;
            padding-top: 40px;
            border-top: 2px solid #eee;
            text-align: center;
            font-size: 0.9rem;
            color: #888;
        }

        a {
            color: #2c3e50;
            text-decoration: underline;
        }
    </style>
</head>
<body>

<div class="container">
    
    <header>
        <h1>Xinyu Wang</h1>
        <p class="subtitle">Exploring the intersection of urban policy, history, and human stories through data visualization.</p>
    </header>

    <div class="grid">

        <article class="card">
            <img src="work1.png" alt="Storyboard of Toronto Commuters" class="card-img">
            <div class="card-content">
                <span class="tag">Scrollytelling & Storyboard</span>
                <h3>The Great Re-Commute</h3>
                <p>
                    <strong>The Challenge:</strong> Post-pandemic Toronto faces a clash between Return-to-Office mandates and Work-from-Home preferences. Abstract stats about "occupancy rates" often ignore the human cost.
                </p>
                <p>
                    <strong>The Solution:</strong> I created a narrative storyboard following three distinct characters—Amy (the hybrid parent), Raj (the business owner), and Leonard (the relocated worker). [cite_start]This approach transforms dry policy data into an interconnected ecosystem of urban tension. [cite: 148, 153]
                </p>
            </div>
        </article>

        <article class="card">
            <img src="work2.png" alt="Minard Map Redesign" class="card-img">
            <div class="card-content">
                <span class="tag">Historical Data Analysis</span>
                <h3>Deconstructing the Grande Armée</h3>
                <p>
                    <strong>The Challenge:</strong> Minard’s famous 1869 map portrays Napoleon’s army as a single "monolith" marching to tragedy. [cite_start]This simplifies the reality that different regiments had vastly different outcomes. [cite: 9, 10]
                </p>
                <p>
                    [cite_start]<strong>The Insight:</strong> By disaggregating the data into three troops, this comparative redesign reveals that while the central force was decimated, the northern flanking regiments actually returned largely intact. [cite: 20]
                </p>
            </div>
        </article>

        <article class="card">
            <img src="work3.jpg" alt="Canada Immigration Infographic" class="card-img">
            <div class="card-content">
                <span class="tag">Infographic Design</span>
                <h3>Are We Ready for New Faces?</h3>
                <p>
                    <strong>The Context:</strong> With 6 of the top 10 source countries for Canadian immigration now in Asia, diversity is higher than ever. However, integration success varies wildly.
                </p>
                <p>
                    <strong>The Insight:</strong> This visualization highlights a critical gap: Newcomers from Asia (46%) report the highest difficulty making ends meet. The design argues for targeted settlement services rather than broad "welcoming" policies.
                </p>
            </div>
        </article>

    </div>

    <footer>
        <p>&copy; 2025 Xinyu Wang. Built for MBAI 5400G.</p>
    </footer>

</div>

</body>
</html>
