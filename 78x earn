<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My WhatsApp Channel<https://whatsapp.com/channel/0029Vb6CssVHFxP5RzPd9l2P>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }
        
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            text-align: center;
        }
        
        header {
            background-color: #25D366;
            color: white;
            padding: 20px 0;
            border-radius: 10px 10px 0 0;
            margin-bottom: 30px;
        }
        
        h1 {
            margin: 0;
            font-size: 2.5em;
        }
        
        .logo {
            width: 100px;
            height: 100px;
            margin-bottom: 20px;
        }
        
        .channel-link {
            background-color: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin-bottom: 30px;
        }
        
        .whatsapp-btn {
            display: inline-block;
            background-color: #25D366;
            color: white;
            text-decoration: none;
            padding: 15px 30px;
            border-radius: 50px;
            font-weight: bold;
            font-size: 1.2em;
            margin: 20px 0;
            transition: all 0.3s ease;
        }
        
        .whatsapp-btn:hover {
            background-color: #128C7E;
            transform: translateY(-3px);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
        }
        
        .whatsapp-btn i {
            margin-right: 10px;
        }
        
        .link-input {
            margin: 30px 0;
        }
        
        input[type="text"] {
            width: 70%;
            padding: 12px 20px;
            border: 2px solid #ddd;
            border-radius: 50px;
            font-size: 1em;
            outline: none;
            transition: border 0.3s;
        }
        
        input[type="text"]:focus {
            border-color: #25D366;
        }
        
        button {
            background-color: #25D366;
            color: white;
            border: none;
            padding: 12px 25px;
            border-radius: 50px;
            cursor: pointer;
            font-size: 1em;
            margin-left: 10px;
            transition: background-color 0.3s;
        }
        
        button:hover {
            background-color: #128C7E;
        }
        
        footer {
            margin-top: 50px;
            color: #777;
            font-size: 0.9em;
        }
        
        @media (max-width: 600px) {
            .container {
                padding: 10px;
            }
            
            input[type="text"] {
                width: 100%;
                margin-bottom: 10px;
            }
            
            button {
                width: 100%;
                margin-left: 0;
            }
        }
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <div class="container">
        <header>
            <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp Logo" class="logo">
            <h1>My WhatsApp Channel</h1>
            <p>Stay updated with our latest content</p>
        </header>
        
        <div class="channel-link">
            <h2>Join Our Channel</h2>
            <p>Click the button below to join our WhatsApp channel and get updates directly on WhatsApp.</p>
            
            <!-- Replace this with your actual WhatsApp channel link -->
            <a href="https://whatsapp.com/channel/your-channel-id" class="whatsapp-btn" id="channelLink">
                <i class="fab fa-whatsapp"></i> Join Now
            </a>
            
            <div class="link-input">
                <h3>Add Your Own WhatsApp Channel Link</h3>
                <input type="text" id="whatsappLink" placeholder="Paste your WhatsApp channel link here">
                <button onclick="updateLink()">Update Link</button>
            </div>
        </div>
        
        <footer>
            <p>© 2023 My WhatsApp Channel. All rights reserved.</p>
        </footer>
    </div>
    
    <script>
        // Function to update the WhatsApp channel link
        function updateLink() {
            const newLink = document.getElementById('whatsappLink').value;
            
            if (newLink) {
                // Validate it's a WhatsApp link (basic validation)
                if (newLink.includes('whatsapp.com/channel/')) {
                    document.getElementById('channelLink').href = newLink;
                    // Save to localStorage so it persists on refresh
                    localStorage.setItem('whatsappChannelLink', newLink);
                    alert('Link updated successfully!');
                } else {
                    alert('Please enter a valid WhatsApp channel link');
                }
            } else {
                alert('Please enter a link');
            }
        }
        
        // Optional: Load a saved link from localStorage
        window.onload = function() {
            const savedLink = localStorage.getItem('whatsappChannelLink');
            if (savedLink) {
                document.getElementById('whatsappLink').value = savedLink;
                document.getElementById('channelLink').href = savedLink;
            }
        };
    </script>
</body>
</html>
