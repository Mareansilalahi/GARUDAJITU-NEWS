<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Portal Berita Terkini</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Arial, sans-serif;
        }
        
        header {
            background-color: #2c3e50;
            color: white;
            padding: 20px;
            text-align: center;
        }
        
        nav {
            background-color: #34495e;
            padding: 15px;
            position: sticky;
            top: 0;
        }
        
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: 500;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        /* Featured Thumbnail Besar */
        .featured-thumbnail {
            position: relative;
            margin: 25px 0;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.3);
        }
        
        .featured-thumbnail img {
            width: 100%;
            height: 500px;
            object-fit: cover;
            transition: transform 0.3s ease;
        }
        
        .featured-thumbnail:hover img {
            transform: scale(1.03);
        }
        
        .featured-content {
            position: absolute;
            bottom: 0;
            left: 0;
            right: 0;
            padding: 40px;
            background: linear-gradient(transparent, rgba(0,0,0,0.8));
            color: white;
        }
        
        .featured-content .category {
            background-color: #e74c3c;
            color: white;
            padding: 8px 15px;
            border-radius: 5px;
            display: inline-block;
            margin-bottom: 15px;
            font-size: 0.9em;
        }
        
        .featured-content h2 {
            font-size: 2.5em;
            margin-bottom: 15px;
            text-shadow: 2px 2px 5px rgba(0,0,0,0.5);
        }
        
        .featured-content p {
            font-size: 1.1em;
            line-height: 1.6;
            max-width: 800px;
        }
        
        .news-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 25px;
            margin-top: 40px;
        }
        
        .news-card {
            border: 1px solid #eee;
            border-radius: 10px;
            padding: 15px;
            transition: all 0.3s ease;
            background-color: white;
        }
        
        .news-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        
        .news-card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 5px;
            margin-bottom: 12px;
        }
        
        .category {
            color: #e74c3c;
            font-weight: bold;
            font-size: 0.85em;
            text-transform: uppercase;
            margin: 10px 0;
        }
        
        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 30px;
            margin-top: 50px;
        }
 
        @media (max-width: 768px) {
            .featured-content {
                padding: 20px;
            }
            
            .featured-content h2 {
                font-size: 1.8em;
            }
            
            .featured-thumbnail img {
                height: 350px;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>GARUDA JITU</h1>
        <p>Informasi Terkini dan Terpercaya</p>
    </header>
 
    <nav>
        <a href="#home">Home</a>
        <a href="#politik">Politik</a>
        <a href="#ekonomi">Ekonomi</a>
        <a href="#olahraga">Olahraga</a>
        <a href="#teknologi">Teknologi</a>
    </nav>
 
    <div class="container">
        <!-- Featured Thumbnail Besar -->
        <div class="featured-thumbnail">
            
                <div class="news-card">
                <img src="	https://files.catbox.moe/fhfi0q.jpg
" alt="Berita 4">                
		<div class="category">Teknologi</div>                
			<h3>Inovasi Gadget Terbaru</h3>                
		<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, voluptatum.</p>            
	</div>  
 
            <div class="news-card">
                <img src="	https://files.catbox.moe/fhfi0q.jpg
" alt="Berita 4">                
		<div class="category">Teknologi</div>                
			<h3>Inovasi Gadget Terbaru</h3>                
		<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, voluptatum.</p>            
	</div>  
 
            <div class="news-card">
                <img src="	https://files.catbox.moe/fhfi0q.jpg
" alt="Berita 4">                
		<div class="category">Teknologi</div>                
			<h3>Inovasi Gadget Terbaru</h3>                
		<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, voluptatum.</p>            
	</div>       
 	</div>    
	</div>     
	<footer>        
	<p>© 2024 News Portal - All rights reserved</p>    
	</footer>
	</body>
</html> 
