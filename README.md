# SITE
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Luan dos Santos Ayres Carvalho</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #f5f5f5;
            color: #333;
            line-height: 1.6;
        }
        
        header {
            background: linear-gradient(135deg, #4568DC, #B06AB3);
            color: white;
            text-align: center;
            padding: 3rem 1rem;
            position: relative;
            overflow: hidden;
        }
        
        header::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 100%;
            height: 50px;
            background: linear-gradient(to bottom right, transparent 49%, white 50%);
        }
        
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 2rem;
            background-color: white;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
            margin-top: -20px;
            position: relative;
            z-index: 1;
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }
        
        .subtitle {
            font-size: 1.2rem;
            opacity: 0.8;
            margin-bottom: 1rem;
        }
        
        .profile {
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
        }
        
        .profile-image {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            background-color: #ddd;
            margin-bottom: 1rem;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 3rem;
            color: #555;
            border: 5px solid white;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
        }
        
        section {
            margin: 2rem 0;
        }
        
        h2 {
            color: #4568DC;
            margin-bottom: 1rem;
            padding-bottom: 0.5rem;
            border-bottom: 2px solid #f0f0f0;
        }
        
        .info-list {
            list-style: none;
        }
        
        .info-list li {
            margin-bottom: 1rem;
            padding-left: 1.5rem;
            position: relative;
        }
        
        .info-list li::before {
            content: '•';
            color: #B06AB3;
            font-size: 1.5rem;
            position: absolute;
            left: 0;
            top: -5px;
        }
        
        .interests {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 1rem;
        }
        
        .interest-tag {
            background-color: #f0f0f0;
            color: #4568DC;
            padding: 0.5rem 1rem;
            border-radius: 20px;
            font-size: 0.9rem;
            display: inline-block;
        }
        
        .footer {
            text-align: center;
            padding: 2rem;
            background-color: #333;
            color: white;
            margin-top: 2rem;
            border-radius: 0 0 10px 10px;
        }
        
        .contact-section {
            display: flex;
            justify-content: center;
            gap: 2rem;
            margin-top: 1rem;
        }
        
        .contact-item {
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
