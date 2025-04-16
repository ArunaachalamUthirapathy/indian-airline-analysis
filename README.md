
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Power BI Sales Dashboard – Arunaachalam</title>

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">

  <style>
    :root {
      --primary: #1d3557;
      --accent: #457b9d;
      --light: #f1faee;
      --bg: #f8f9fa;
      --text: #2d3142;
    }

    body {
      font-family: 'Inter', sans-serif;
      margin: 0;
      padding: 0;
      background: var(--bg);
      color: var(--text);
    }

    .banner {
      background: linear-gradient(135deg, #1d3557, #457b9d);
      color: white;
      padding: 40px 20px;
      text-align: center;
      box-shadow: 0 4px 20px rgba(0,0,0,0.1);
    }

    .banner h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
      animation: fadeInDown 1s ease-in-out;
    }

    .banner p {
      font-size: 1.1rem;
      color: #dceefb;
      animation: fadeInUp 1.2s ease-in-out;
    }

    .container {
      max-width: 900px;
      margin: 30px auto;
      padding: 20px;
      background: white;
      border-radius: 16px;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.06);
      animation: fadeIn 1.5s ease;
    }

    h2 {
      color: var(--primary);
      margin-top: 30px;
    }

    img {
      width: 100%;
      max-width: 850px;
      border-radius: 12px;
      margin: 15px 0;
      box-shadow: 0 4px 12px rgba(0,0,0,0.08);
      transition: transform 0.3s ease;
    }

    img:hover {
      transform: scale(1.01);
    }

    .download {
      margin-top: 20px;
      background: #eaf6ff;
      padding: 15px;
      border-left: 5px solid #1d3557;
      border-radius: 8px;
    }

    .download a {
      color: #1d3557;
      text-decoration: none;
      font-weight: 600;
      transition: all 0.3s ease;
    }

    .download a:hover {
      color: #457b9d;
      text-decoration: underline;
    }

    footer {
      margin-top: 40px;
      font-size: 0.95rem;
      text-align: center;
      color: #888;
    }

    hr {
      border: none;
      height: 2px;
      background: #eee;
      margin: 30px 0;
    }

    /* Animations */
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes fadeInDown {
      from { opacity: 0; transform: translateY(-20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes fadeInUp {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>

  <div class="banner">
    <h1>📊 Power BI Dashboard</h1>
    <p>Built using Power BI, Excel, and DAX /p>
  </div>

  <div class="container">
    <h2>🔍 Project Overview</h2>
    <p>This dashboard visualizes monthly sales data, highlights top-performing products, and shows trends across regions.</p>

    <h2>🖼️ Report Screenshots</h2>
    <img src="Airline_ind.png" alt="Dashboard Screenshot">

    <h2>📥 Download</h2>
    <div class="download">
      🔗 <a href="Airline.pbix" download>Download Power BI (.pbix) File</a>
    </div>

    <footer>
      <p>Made with 💙 by <strong>Arunaachalam</strong></p>
    </footer>
  </div>

</body>
</html>
