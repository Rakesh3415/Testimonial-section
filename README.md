<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Testimonials</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f8f4fc;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        .container {
            width: 90%;
            max-width: 800px;
            margin: auto;
            padding: 20px;
        }
        h1 {
            color: #4b136f;
            font-size: 24px;
        }
        p {
            color: #555;
        }
        .ratings {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 10px;
        }
        .rating-box {
            background: #fff;
            padding: 10px;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            flex: 1;
            min-width: 200px;
        }
        .stars {
            color: #ffcc00;
            font-size: 20px;
        }
        .testimonials {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 10px;
        }
        .testimonial {
            background: #6b2477;
            color: #fff;
            padding: 15px;
            border-radius: 10px;
            flex: 1;
            min-width: 250px;
            max-width: 350px;
            text-align: left;
        }
        .testimonial img {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            margin-right: 10px;
            vertical-align: middle;
        }
        .testimonial h4 {
            margin: 0;
            display: inline-block;
            font-size: 16px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>10,000+ of our users love our products.</h1>
        <p>We only provide great products combined with excellent customer service. See what our satisfied customers are saying about our services.</p>
        
        <div class="ratings">
            <div class="rating-box">
                <div class="stars">★★★★★</div>
                <p>Rated 5 Stars in Reviews</p>
            </div>
            <div class="rating-box">
                <div class="stars">★★★★★</div>
                <p>Rated 5 Stars in Report Guru</p>
            </div>
            <div class="rating-box">
                <div class="stars">★★★★★</div>
                <p>Rated 5 Stars in BestTech</p>
            </div>
        </div>
        
        <div class="testimonials">
            <div class="testimonial">
                <img src="C:\Users\nkhld\OneDrive\Desktop\testimonial\images\image-colton.jpg" alt="User">
                <h4>Colton Smith</h4>
                <p>Verified Buyer</p>
                <p>“ We needed the same printed design as the one we had ordered a week prior. Not only did they find the original order, but we also received it in time. Excellent! ”</p>
            </div>
            
            <div class="testimonial">
                <img src="C:\Users\nkhld\OneDrive\Desktop\testimonial\images\image-irene.jpg" alt="User">
                <h4>Irene Roberts</h4>
                <p>Verified Buyer</p>
                <p>“ Customer service is always excellent and very quick turn around. Completely delighted with the simplicity of the purchase and the speed of delivery. ”</p>
            </div>
            
            <div class="testimonial">
                <img src="C:\Users\nkhld\OneDrive\Desktop\testimonial\images\image-anne.jpg" alt="User">
                <h4>Anne Wallace</h4>
                <p>Verified Buyer</p>
                <p>“ Put an order with this company and can only praise them for the very high standard. Will definitely use them again and recommend them to everyone! ”</p>
            </div>
        </div>
    </div>
</body>
</html>
