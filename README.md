<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>The Jewellery Bazaar India</title>
    <style>
        :root {
            --primary: #4b1f1f;
            --accent: #b8860b;
            --bg: #faf7f2;
            --text: #2d2d2d;
            --white: #ffffff;
        }
        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            margin: 0;
            background: var(--bg);
            color: var(--text);
            line-height: 1.6;
        }
        header {
            background: var(--primary);
            color: var(--white);
            text-align: center;
            padding: 40px 20px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
        }
        .logo {
            width: 160px;
            height: 160px;
            object-fit: contain;
            border-radius: 50%;
            margin-bottom: 15px;
            box-shadow: 0 6px 15px rgba(0,0,0,0.2);
            background-color: #fff;
        }
        header h1 {
            margin: 10px 0 5px 0;
            font-size: 2.2rem;
        }
        header p {
            font-style: italic;
            margin: 5px 0 0;
            opacity: 0.9;
            font-size: 1.1rem;
        }
        .hero {
            padding: 50px 20px;
            text-align: center;
            max-width: 800px;
            margin: 0 auto;
        }
        .hero h2 {
            font-size: 2.2rem;
            color: var(--primary);
            margin-bottom: 10px;
        }
        .hero p {
            font-size: 1.2rem;
            color: #666;
            margin-bottom: 25px;
        }
        .btn-container {
            display: flex;
            justify-content: center;
            gap: 15px;
            flex-wrap: wrap;
        }
        .btn {
            display: inline-flex;
            align-items: center;
            background: var(--accent);
            color: var(--white);
            padding: 14px 28px;
            text-decoration: none;
            border-radius: 30px;
            font-weight: bold;
            transition: all 0.3s ease;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }
        .btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 6px 12px rgba(0,0,0,0.15);
            background: #a3760a;
        }
        .btn-wa {
            background: #25D366;
        }
        .btn-wa:hover {
            background: #20ba5a;
        }
