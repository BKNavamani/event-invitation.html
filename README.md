<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>Wedding Celebration</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body, html {
            height: 100%;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        /* Hero section with background image */
        .hero {
            background: url('https://images.unsplash.com/photo-1530026186672-33e53f5b6c1a?auto=format&fit=crop&w=1400&q=80') center center / cover no-repeat;
            height: 100vh;
            position: relative;
        }

        /* Overlay to darken background for better text contrast */
        .overlay {
            background: rgba(0, 0, 0, 0.5);
            height: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 2rem;
        }

        /* Content styling */
        .content {
            text-align: center;
            color: white;
            max-width: 600px;
        }

        h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
            letter-spacing: 1px;
        }

        .description {
            font-size: 1.2rem;
            margin-bottom: 1.5rem;
        }

        .details {
            font-size: 1.1rem;
            margin: 0.5rem 0;
        }

        /* RSVP Button */
        .rsvp-btn {
            display: inline-block;
            margin-top: 2rem;
            padding: 0.8rem 2rem;
            background: #ff6f61;
            color: white;
            text-decoration: none;
            font-size: 1.1rem;
            border-radius: 8px;
            transition: background 0.3s;
        }

        .rsvp-btn:hover {
            background: #ff3b2e;
        }

        /* Responsive adjustments */
        @media (max-width: 600px) {
            h1 {
                font-size: 2rem;
            }
            .description, .details {
                font-size: 1rem;
            }
        }
    </style>
</head>
<body>
    <div class="hero">
        <div class="overlay">
            <div class="content">
                <h1>Wedding Celebration</h1>
                <p class="description">Join us as we tie the knot and begin a new chapter of our lives together. Your presence will make it even more special.</p>
                
                <p class="details"><strong>Date:</strong> 25th December 2025</p>
                <p class="details"><strong>Time:</strong> 6:00 PM onwards</p>
                <p class="details"><strong>Venue:</strong> Grand Palace Hall, Chennai</p>
                
                <a href="#" class="rsvp-btn">RSVP Now</a>
            </div>
        </div>
    </div>
</body>
</html>
