# MobileCarwashVanSale 
<div class="van-photos">
  <img src="van-photo1.jpg" alt="Mobile Carwash Van Front View">
  <img src="van-photo2.jpg" alt="Van Interior Setup">
</div>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>🚐💨 MOBILE CARWASH VAN FOR SALE! Your Business Dreams START HERE!</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial Black', Arial, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            overflow-x: hidden;
        }

        .hero-section {
            min-height: 100vh;
            background: linear-gradient(45deg, #FF6B6B, #4ECDC4, #45B7D1, #96CEB4);
            background-size: 400% 400%;
            animation: gradientShift 4s ease infinite;
            position: relative;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
            padding: 2rem;
        }

        @keyframes gradientShift {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        .hero-content {
            max-width: 1200px;
            z-index: 2;
        }

        .main-title {
            font-family: 'Impact', 'Arial Black', sans-serif;
            font-size: clamp(3rem, 8vw, 8rem);
            font-weight: 900;
            margin-bottom: 1rem;
            color: #FFD700;
            text-transform: uppercase;
            letter-spacing: 0.15em;
            animation: breakingNewsFlash 4s ease-in-out infinite;
            position: relative;
            overflow: hidden;
            background: linear-gradient(90deg, 
                transparent 0%, 
                #FFD700 25%, 
                #FFA500 50%, 
                #FF6347 75%, 
                transparent 100%
            );
            background-size: 200% 100%;
            -webkit-background-clip: text;
            background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        @keyframes breakingNewsFlash {
            0% { 
                transform: translateX(-100%);
                background-position: -200% 0;
            }
            25% {
                transform: translateX(0%);
                background-position: 0% 0;
            }
            75% {
                transform: translateX(0%);
                background-position: 200% 0;
            }
            100% {
                transform: translateX(100%);
                background-position: 400% 0;
            }
        }

        .subtitle {
            font-size: clamp(1.5rem, 4vw, 3rem);
            font-weight: bold;
            margin-bottom: 2rem;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
            animation: pulse 2s ease-in-out infinite;
        }

        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }

        .explosive-cta {
            background: linear-gradient(45deg, #FF1744, #FF5722);
            border: none;
            color: white;
            padding: 1.5rem 3rem;
            font-size: clamp(1.2rem, 3vw, 2rem);
            font-weight: 900;
            border-radius: 50px;
            cursor: pointer;
            transform: perspective(1px) translateZ(0);
            box-shadow: 0 8px 25px rgba(255, 23, 68, 0.4);
            transition: all 0.3s ease;
            text-transform: uppercase;
            letter-spacing: 0.1em;
            margin: 1rem;
            animation: glow 2s ease-in-out infinite alternate;
        }

        @keyframes glow {
            from { box-shadow: 0 8px 25px rgba(255, 23, 68, 0.4), 0 0 30px rgba(255, 23, 68, 0.2); }
            to { box-shadow: 0 12px 35px rgba(255, 23, 68, 0.8), 0 0 50px rgba(255, 23, 68, 0.5); }
        }

        .explosive-cta:hover {
            transform: translateY(-5px) scale(1.1);
            box-shadow: 0 15px 40px rgba(255, 23, 68, 0.7);
        }

        .features-section {
            background: linear-gradient(135deg, #1e3c72 0%, #2a5298 100%);
            padding: 4rem 2rem;
            color: white;
        }

        .features-container {
            max-width: 1200px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }

        .feature-card {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            padding: 2rem;
            text-align: center;
            border: 2px solid rgba(255, 255, 255, 0.2);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .feature-card:hover {
            transform: translateY(-10px) rotateY(5deg);
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.3);
        }

        .feature-icon {
            font-size: 4rem;
            margin-bottom: 1rem;
            animation: rotate 3s linear infinite;
        }

        @keyframes rotate {
            from { transform: rotate(0deg); }
            to { transform: rotate(360deg); }
        }

        .feature-title {
            font-size: 1.8rem;
            font-weight: 900;
            margin-bottom: 1rem;
            color: #FFD700;
            text-transform: uppercase;
        }

        .van-details {
            background: linear-gradient(45deg, #000000, #434343);
            color: white;
            padding: 4rem 2rem;
            position: relative;
            overflow: hidden;
        }

        .van-details::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><defs><pattern id="sparkle" patternUnits="userSpaceOnUse" width="100" height="100"><circle cx="20" cy="20" r="2" fill="%23FFD700" opacity="0.5"><animate attributeName="opacity" values="0.5;1;0.5" dur="2s" repeatCount="indefinite"/></circle><circle cx="80" cy="40" r="1.5" fill="%23FF6347" opacity="0.3"><animate attributeName="opacity" values="0.3;0.8;0.3" dur="1.5s" repeatCount="indefinite"/></circle><circle cx="40" cy="80" r="1" fill="%234ECDC4" opacity="0.4"><animate attributeName="opacity" values="0.4;0.9;0.4" dur="1.8s" repeatCount="indefinite"/></circle></pattern></defs><rect width="100%" height="100%" fill="url(%23sparkle)"/></svg>') repeat;
            opacity: 0.1;
            animation: sparkle 10s linear infinite;
        }

        @keyframes sparkle {
            0% { transform: translateX(0) translateY(0); }
            100% { transform: translateX(100px) translateY(100px); }
        }

        .details-grid {
            max-width: 1000px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            position: relative;
            z-index: 2;
        }

        .detail-item {
            background: linear-gradient(45deg, #FF6B6B, #4ECDC4);
            padding: 1.5rem;
            border-radius: 15px;
            text-align: center;
            font-weight: bold;
            transform: perspective(1px) translateZ(0);
            transition: all 0.3s ease;
            border: 3px solid transparent;
            background-clip: padding-box;
        }

        .detail-item:hover {
            transform: translateY(-8px) scale(1.05);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.4);
        }

        .detail-label {
            font-size: 1rem;
            opacity: 0.8;
            text-transform: uppercase;
            letter-spacing: 0.1em;
        }

        .detail-value {
            font-size: 1.5rem;
            font-weight: 900;
            margin-top: 0.5rem;
            color: white;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
        }

        .profit-section {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            padding: 4rem 2rem;
            color: white;
            text-align: center;
        }

        .profit-title {
            font-size: clamp(2rem, 5vw, 4rem);
            font-weight: 900;
            margin-bottom: 2rem;
            text-transform: uppercase;
            text-shadow: 3px 3px 6px rgba(0,0,0,0.5);
            animation: wiggle 0.5s ease-in-out infinite alternate;
        }

        @keyframes wiggle {
            0% { transform: rotate(-1deg); }
            100% { transform: rotate(1deg); }
        }

        .contact-section {
            background: linear-gradient(45deg, #FF1744, #FF5722, #FF9800);
            background-size: 200% 200%;
            animation: gradientShift 3s ease infinite;
            padding: 4rem 2rem;
            color: white;
            text-align: center;
        }

        .contact-info {
            max-width: 800px;
            margin: 0 auto;
            background: rgba(0, 0, 0, 0.3);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            padding: 3rem;
            border: 3px solid rgba(255, 255, 255, 0.3);
        }

        .contact-title {
            font-size: clamp(2rem, 4vw, 3rem);
            font-weight: 900;
            margin-bottom: 2rem;
            text-transform: uppercase;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.7);
        }

        .contact-item {
            font-size: 1.3rem;
            margin: 1rem 0;
            font-weight: bold;
            background: rgba(255, 255, 255, 0.1);
            padding: 1rem;
            border-radius: 10px;
            transition: all 0.3s ease;
        }

        .contact-item:hover {
            background: rgba(255, 255, 255, 0.2);
            transform: scale(1.05);
        }

        .hours {
            font-size: 1.1rem;
            background: linear-gradient(45deg, #4CAF50, #8BC34A);
            padding: 1rem;
            border-radius: 15px;
            margin-top: 2rem;
            font-weight: bold;
        }

        .floating-elements {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 1;
        }

        .floating-car {
            position: absolute;
            font-size: 2rem;
            animation: float 6s ease-in-out infinite;
            opacity: 0.3;
        }

        .floating-car:nth-child(1) {
            top: 10%;
            left: 10%;
            animation-delay: 0s;
        }

        .floating-car:nth-child(2) {
            top: 70%;
            right: 15%;
            animation-delay: 2s;
        }

        .floating-car:nth-child(3) {
            bottom: 20%;
            left: 20%;
            animation-delay: 4s;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0px) rotate(0deg); }
            50% { transform: translateY(-20px) rotate(5deg); }
        }

        @media (max-width: 768px) {
            .hero-section {
                padding: 1rem;
            }
            
            .details-grid {
                grid-template-columns: 1fr;
            }
            
            .features-container {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="floating-elements">
        <div class="floating-car">🚐</div>
        <div class="floating-car">✨</div>
        <div class="floating-car">💎</div>
    </div>

    <section class="hero-section">
        <div class="hero-content">
            <h1 class="main-title">🚐 MOBILE CARWASH VAN 🚐</h1>
            <h2 class="subtitle">🔥 FOR SALE! YOUR BUSINESS EMPIRE STARTS HERE! 🔥</h2>
            <div class="price-banner">
                <div class="price-text">ONLY $4,200!</div>
                <div class="price-subtext">💥 INCREDIBLE VALUE! 💥</div>
            </div>
            <p style="font-size: clamp(1rem, 2.5vw, 1.5rem); font-weight: bold; margin-bottom: 2rem;">
                TURN THIS INCREDIBLE GMC VAN INTO YOUR MONEY-MAKING MACHINE!
            </p>
            <button class="explosive-cta" onclick="document.querySelector('.contact-section').scrollIntoView({behavior: 'smooth'})">
                💰 CALL NOW & GET RICH! 💰
            </button>
            <button class="explosive-cta" onclick="document.querySelector('.van-details').scrollIntoView({behavior: 'smooth'})">
                🔥 SEE THE DETAILS! 🔥
            </button>
        </div>
    </section>

    <section class="features-section">
        <div class="features-container">
            <div class="feature-card">
                <div class="feature-icon">🚿</div>
                <h3 class="feature-title">Quick Exterior</h3>
                <p>Lightning-fast exterior cleaning that will have cars sparkling in minutes! Maximum efficiency = Maximum profit!</p>
            </div>
            <div class="feature-card">
                <div class="feature-icon">✨</div>
                <h3 class="feature-title">Full Detailing</h3>
                <p>Complete interior sanitizing and thorough cleaning for ultimate vehicle care. Premium service = Premium prices!</p>
            </div>
            <div class="feature-card">
                <div class="feature-icon">💼</div>
                <h3 class="feature-title">Ultimate Convenience</h3>
                <p>Bring the car wash to YOUR customers! No overhead costs, pure profit potential!</p>
            </div>
        </div>
    </section>

    <section class="van-details">
        <h2 style="text-align: center; font-size: clamp(2rem, 4vw, 3rem); font-weight: 900; margin-bottom: 3rem; text-transform: uppercase; color: #FFD700;">
            🎯 VAN SPECIFICATIONS - READY FOR SUCCESS! 🎯
        </h2>
        <div class="details-grid">
            <div class="detail-item" style="background: linear-gradient(45deg, #4CAF50, #8BC34A); grid-column: 1 / -1; font-size: 1.5rem;">
                <div class="detail-label">💰 PRICE 💰</div>
                <div class="detail-value" style="font-size: 2.5rem; color: white; text-shadow: 3px 3px 6px rgba(0,0,0,0.7);">$4,200 ONLY!</div>
            </div>
            <div class="detail-item">
                <div class="detail-label">Make</div>
                <div class="detail-value">GMC 🏆</div>
            </div>
            <div class="detail-item">
                <div class="detail-label">Vehicle Type</div>
                <div class="detail-value">Van 🚐</div>
            </div>
            <div class="detail-item">
                <div class="detail-label">Mileage</div>
                <div class="detail-value">150,000 ⚡</div>
            </div>
            <div class="detail-item">
                <div class="detail-label">Transmission</div>
                <div class="detail-value">Automatic 🔄</div>
            </div>
            <div class="detail-item">
                <div class="detail-label">Color</div>
                <div class="detail-value">White ⚪</div>
            </div>
            <div class="detail-item">
                <div class="detail-label">Fuel Type</div>
                <div class="detail-value">Gasoline ⛽</div>
            </div>
            <div class="detail-item">
                <div class="detail-label">Condition</div>
                <div class="detail-value">EXCELLENT! 🌟</div>
            </div>
            <div class="detail-item">
                <div class="detail-label">Location</div>
                <div class="detail-value">Melbourne, FL 🏖️</div>
            </div>
        </div>
    </section>

    <section class="profit-section">
        <h2 class="profit-title">💸 MOBILE CARWASH = BIG PROFITS! 💸</h2>
        <div style="max-width: 800px; margin: 0 auto; font-size: clamp(1rem, 2vw, 1.3rem); line-height: 1.6;">
            <div style="background: rgba(255, 255, 255, 0.1); padding: 2rem; border-radius: 20px; margin-bottom: 2rem; border: 3px solid #FFD700;">
                <div style="font-size: clamp(2rem, 4vw, 3rem); font-weight: 900; color: #FFD700; text-align: center; margin-bottom: 1rem;">
                    💰 FOR ONLY $4,200! 💰
                </div>
                <div style="font-size: clamp(1.2rem, 2.5vw, 1.5rem); font-weight: bold; text-align: center;">
                    This van will pay for itself in WEEKS! 🚀
                </div>
            </div>
            <p style="margin-bottom: 2rem; font-weight: bold;">
                🚀 Mobile carwash businesses are INCREDIBLY LUCRATIVE! 🚀
            </p>
            <p style="margin-bottom: 2rem;">
                Having a TOP-NOTCH, efficiently run, dependable mobile detailing vehicle is 
                <span style="color: #FFD700; font-weight: 900; font-size: 1.2em;">ABSOLUTELY CRITICAL</span> 
                for your success!
            </p>
            <p style="font-weight: bold; font-size: 1.2em; color: #4ECDC4;">
                This van is your ticket to financial freedom! 💰
            </p>
        </div>
    </section>

    <section class="contact-section">
        <div class="contact-info">
            <h2 class="contact-title">🔥 CONTACT MERHI TODAY! 🔥</h2>
            <p style="font-size: 1.2rem; margin-bottom: 2rem; font-weight: bold;">
                DON'T WAIT! This opportunity won't last long!
            </p>
            
            <div class="contact-item">
                📞 Phone: <strong>561-644-4594</strong>
            </div>
            <div class="contact-item">
                📱 Alternative: <strong>561-365-7062</strong>
            </div>
            <div class="contact-item">
                📧 Email: <strong>mandahomes1@gmail.com</strong>
            </div>
            
            <div class="hours">
                🕐 <strong>AVAILABLE 7 DAYS A WEEK!</strong><br>
                Monday - Sunday: 8AM to 10PM
            </div>
            
            <div style="margin-top: 2rem; font-size: 1.1rem; font-weight: bold;">
                ⚡ CALL NOW! Your business empire is waiting! ⚡
            </div>
        </div>
    </section>

    <script>
        // Add some dynamic sparkle effects
        function createSparkle() {
            const sparkle = document.createElement('div');
            sparkle.innerHTML = '✨';
            sparkle.style.position = 'fixed';
            sparkle.style.left = Math.random() * window.innerWidth + 'px';
            sparkle.style.top = Math.random() * window.innerHeight + 'px';
            sparkle.style.fontSize = (Math.random() * 20 + 10) + 'px';
            sparkle.style.pointerEvents = 'none';
            sparkle.style.zIndex = '1000';
            sparkle.style.opacity = '0.7';
            sparkle.style.animation = 'sparkleFloat 3s ease-out forwards';
            
            document.body.appendChild(sparkle);
            
            setTimeout(() => {
                sparkle.remove();
            }, 3000);
        }
        
        // Add CSS for sparkle animation
        const style = document.createElement('style');
        style.textContent = `
            @keyframes sparkleFloat {
                0% { transform: translateY(0px) rotate(0deg); opacity: 0.7; }
                100% { transform: translateY(-100px) rotate(360deg); opacity: 0; }
            }
        `;
        document.head.appendChild(style);
        
        // Create sparkles periodically
        setInterval(createSparkle, 2000);
        
        // Add click effects to buttons
        document.querySelectorAll('.explosive-cta').forEach(button => {
            button.addEventListener('click', function(e) {
                // Create explosion effect
                for (let i = 0; i < 5; i++) {
                    setTimeout(() => createSparkle(), i * 100);
                }
            });
        });
    </script>
</body>
</html>
