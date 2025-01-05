<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Office of the Building Official</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            height: 100vh;
            background-color: #f5f5f5;
        }
        nav {
            width: 250px;
            background-color: #001f3f;
            color: white;
            display: flex;
            flex-direction: column;
            padding-top: 1rem;
            box-shadow: 2px 0 5px rgba(0, 0, 0, 0.1);
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 1rem;
            border-bottom: 1px solid #003366;
            transition: background-color 0.3s, color 0.3s;
        }
        nav a:hover {
            background-color: #003366;
            color: #f5f5f5;
        }
        .container {
            flex: 1;
            display: flex;
            flex-direction: column;
            padding: 1rem;
        }
        .video-section {
            text-align: center;
            margin-bottom: 2rem;
        }
        .video-section iframe {
            width: 80%;
            height: 315px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .sections {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
        }
        .section {
            flex: 1 1 calc(50% - 1rem);
            background: white;
            padding: 1rem;
            border-radius: 5px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .section h2 {
            border-bottom: 2px solid #001f3f;
            padding-bottom: 0.5rem;
            margin-bottom: 1rem;
        }
        .btn {
            display: inline-block;
            margin: 0.5rem 0;
            padding: 0.7rem 1rem;
            background-color: #001f3f;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        .btn:hover {
            background-color: #003366;
        }
    </style>
</head>
<body>
    <nav>
        <a href="#zoning">Land Classification</a>
        <a href="#building-permits">Building Online Application</a>
        <a href="#occupancy">Occupancy Online Application</a>
        <a href="#downloads">Permit Templates</a>
        <a href="#education">Educational Videos</a>
        <a href="#certification">Request for Certification</a>
    </nav>

    <div class="container">
        <div class="video-section">
            <h2>Educational Videos</h2>
            <iframe src="https://www.youtube.com/embed/example" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>

        <div class="sections">
            <div id="zoning" class="section">
                <h2>Zoning Rules</h2>
                <p>Search zoning rules by entering your address or area below:</p>
                <input type="text" placeholder="Enter address or area" style="width: 100%; padding: 0.5rem; margin: 0.5rem 0;">
                <a href="#" class="btn">Search</a>
            </div>

            <div id="building-permits" class="section">
                <h2>Building Permits</h2>
                <p>Learn about building permit application requirements and start your application online.</p>
                <a href="#" class="btn">Learn More</a>
                <a href="#" class="btn">Apply Now</a>
            </div>

            <div id="occupancy" class="section">
                <h2>Occupancy Requirements</h2>
                <p>Check the requirements to obtain an occupancy permit and validate compliance.</p>
                <a href="#" class="btn">Check Requirements</a>
            </div>

            <div id="downloads" class="section">
                <h2>Permit Templates</h2>
                <p>Download application templates for various permits.</p>
                <a href="#" class="btn">Download Templates</a>
            </div>

            <div id="certification" class="section">
                <h2>Request for Certification</h2>
                <p>Submit a request to obtain official certifications for zoning, building compliance, or occupancy.</p>
                <a href="#" class="btn">Submit Request</a>
            </div>
        </div>
    </div>
</body>
</html>
