<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no, viewport-fit=cover">
    <title>Make Money & Traffic</title>

    <!-- PWA Meta Tags -->
    <meta name="theme-color" content="#6A11CB"/>
    <link id="manifest-link" rel="manifest">
    <meta name="mobile-web-app-capable" content="yes">
    <meta name="apple-mobile-web-app-capable" content="yes">
    <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
    <link rel="apple-touch-icon" href="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAMAAAADACAYAAABS3GwHAAAAAXNSR0IArs4c6QAAAl1JREFUeF7t0AEJAAAMAsHZv/RyPNwSyBIg1AAQEAABYDYgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAB46gAb5CBvQy9s7wAAAABJRU5ErkJggg==">

    <!-- Fonts & Icons -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Teko:wght@700&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <style>
        :root {
            --primary-color: #6A11CB; --primary-dark-color: #2575FC;
            --secondary-color: #FFFFFF;
            --text-color: #212121; --text-light-color: #555;
            --border-color: rgba(255, 255, 255, 0.4);
            --success-color: #4CAF50; --error-color: #E53935; --warning-color: #FFA000;
            --gold-gradient: linear-gradient(145deg, #FFDF00, #F7B500, #D4AF37);
            
            /* Social & Payment Colors */
            --color-youtube: #FF0000; --color-facebook: #1877F2; --color-tiktok: #010101; --color-instagram: #E4405F;
            --color-pi: #F39E1A; 
            --color-cih: #ED1C24;
            --color-paypal: #0070BA;
            --color-payeer: #26a69a;
            --color-usdt: #26A17B;
            --color-binance-pay: #F0B90B;
            --color-wise: #9FE870;
            --color-skrill: #8F227D;
            --color-perfect-money: #D82823;
            --color-bitcoin: #F7931A;

            --safe-area-inset-bottom: env(safe-area-inset-bottom, 20px);
        }
        * { margin: 0; padding: 0; box-sizing: border-box; -webkit-tap-highlight-color: transparent; }
        html, body { height: 100%; width: 100%; overflow: hidden; font-family: 'Inter', 'Cairo', sans-serif; color: var(--text-color); transition: background 0.8s ease-in-out; }
        
        /* Default Gradients */
        body.gradient-home { background: linear-gradient(135deg, #6A11CB 0%, #2575FC 100%); }
        body.gradient-history { background: linear-gradient(135deg, #00c6ff 0%, #0072ff 100%); }
        body.gradient-deposit { background: linear-gradient(135deg, #f7971e 0%, #ffd200 100%); }
        body.gradient-withdraw { background: linear-gradient(135deg, #11998e 0%, #38ef7d 100%); }
        body.gradient-profile { background: linear-gradient(135deg, #ec008c 0%, #fc6767 100%); }
        body.gradient-store { background: linear-gradient(135deg, #8E2DE2, #4A00E0); }

        /* Custom background for Auth page */
        body.page-auth {
            background: linear-gradient(135deg, #74b9ff, #0984e3);
        }
        
        #app-container { position: relative; width: 100%; height: 100%; overflow: hidden; }
        .page { position: absolute; top: 0; left: 0; width: 100%; height: 100%; padding: 20px 20px calc(80px + var(--safe-area-inset-bottom)) 20px; overflow-y: auto; background-color: transparent; transform: translateX(100%); transition: transform 0.4s cubic-bezier(0.25, 0.46, 0.45, 0.94), opacity 0.5s ease; opacity: 0; }
        .page.active { transform: translateX(0); opacity: 1; z-index: 5; }
        .page.no-transform { transform: none; }
        
        /* Splash Screen */
        #splash-page { color: var(--secondary-color); display: flex; flex-direction: column; justify-content: center; align-items: center; z-index: 100; background-image: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), url('data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAkGBxISEhUSEhIVFRUVFRUVFRUVFRUVFRUVFRUWFhUVFRUYHSggGBolHRUVITEhJSkrLi4uFx8zODMtNygtLisBCgoKDg0OGxAQGy0lICUtLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLf/AABEIALcBEwMBIgACEQEDEQH/xAAcAAACAwEBAQEAAAAAAAAAAAADBAIFBgcBAAj/xABAEAACAQIEAwUFBgQGAQUBAAABAhEAAwQSITEFQVEGEyJhcYEykaEUscHR8CNSYnKC4RQzQ5Ky8RY0U2Oi0uL/xAAaAQEAAwEBAQAAAAAAAAAAAAABAAIDBAUG/8QALBEAAgIBAwQCAgIBBQAAAAAAAAECEQMSITEEE0FRIgVhcYGRobHwFDLR4f/aAAwDAQACEQMRAD8A8/uLqPjQcQpXcUzG6Jmq72m60LRTXvB1GqN2D6mgW5o50EigItrE351UuYm5bJUkx1o2JtA6d6jY7DDK2UanQelBjJd2C22KkG5bYaiNqFexGZ9JgdaI+HuE91yOhoBw2Jt6G246aEUBt90NtdJ/xVnD4bETmNt56mDQ7N2+0F1I/mFMMJxG6i5YUDyFAkQreGu/Yf/8TQL9i99h/8AxNHu8TvnpUD8UXPT3oGTKAt3l3Vv8pqw+Gv2yVNu4pHQwRUXD4h0ZSrEHeCOlX7/ABm6/wARJ8yaDKPBTF0g6qR5ijjiTjYn2NVLjiZNCs1BSH7cSxO6z4gR9KjXOM2H1e1PuKgY1Cg1YI54/hTo9oj/ACmoN7jlljsf4qgDShVqBks/j1o3Fw/xFf/lUPE8dY/CtqvmTJ+lUQKKBk25xG627geQgfSoN26zGSSfMyaFSFagZClKEUq0DIUqQpCgYlSFIUAStUKBCpA0KhQFpBSFKtQMSaQpChQMSKRoUKoGFIUjQpUAkUaVKgEaFLQoECtCtUKBghSNClQCEUhSNClQCRSNClQCEUhStCtQMpWlUqUB//Z'); background-size: cover; background-position: center center; overflow: hidden; transition: opacity 0.6s ease-out; }
        #icon-rain-container { position: absolute; top: 0; left: 0; width: 100%; height: 100%; pointer-events: none; }
        .falling-icon { position: absolute; top: -15%; color: rgba(255, 255, 255, 0.3); user-select: none; animation: fall linear infinite; }
        @keyframes fall { to { transform: translateY(115vh) rotate(60deg); opacity: 0; } }
        #splash-title-container { position: relative; text-align: center; z-index: 10; }
        .splash-title { font-family: 'Teko', sans-serif; font-size: 4rem; font-weight: 700; line-height: 1; text-transform: uppercase; background: var(--gold-gradient); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text; text-fill-color: transparent; text-shadow: 2px 2px 8px rgba(0,0,0,0.5); margin: 0; }
        .splash-subtitle { display: block; font-size: 2.5rem; letter-spacing: 1px; }
        #loader-percentage { position: absolute; bottom: 15%; font-size: 2rem; font-weight: 700; color: rgba(255, 255, 255, 0.9); text-shadow: 1px 1px 4px rgba(0,0,0,0.5); z-index: 10; }
        
        /* Notification System */
        #notification-container { position: fixed; top: 20px; left: 50%; transform: translateX(-50%); z-index: 2000; width: 90%; max-width: 500px; }
        .notification { padding: 15px 20px; border-radius: 12px; color: white; margin-bottom: 10px; box-shadow: 0 5px 15px rgba(0,0,0,0.2); display: flex; align-items: center; opacity: 0; transform: translateY(-20px); transition: opacity 0.3s ease, transform 0.3s ease; }
        .notification.show { opacity: 1; transform: translateY(0); }
        .notification i { margin-right: 12px; font-size: 20px; }
        .notification.success { background-color: var(--success-color); }
        .notification.error { background-color: var(--error-color); }
        .notification.info { background-color: var(--primary-dark-color); }
        
        .card { background: rgba(255, 255, 255, 0.5); -webkit-backdrop-filter: blur(12px); backdrop-filter: blur(12px); border-radius: 20px; padding: 20px; box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.2); border: 1px solid var(--border-color); margin-bottom: 20px; }
        .btn { display: flex; align-items: center; justify-content: center; width: 100%; padding: 15px; border: none; border-radius: 12px; font-size: 16px; font-weight: 700; cursor: pointer; transition: all 0.2s; }
        .btn-primary { background: linear-gradient(to right, #6A11CB, #2575FC); color: var(--secondary-color); box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2); }
        .btn:disabled { background: var(--text-light-color); cursor: not-allowed; box-shadow: none; }
        
        h1.page-title { font-size: 30px; margin-bottom: 25px; font-weight: 700; display: flex; align-items: center; color: var(--secondary-color); text-shadow: 0 2px 4px rgba(0,0,0,0.2); }
        .back-btn { font-size: 24px; color: var(--secondary-color); text-decoration: none; z-index: 10; margin-right: 15px; }
        h2.section-title { font-size: 22px; font-weight: 700; margin-bottom: 15px; color: var(--secondary-color); text-align: center; text-shadow: 0 2px 4px rgba(0,0,0,0.2); }
        body.rtl h2.section-title { text-align: center; }

        .form-group { margin-bottom: 15px; }
        .form-group label { display: block; margin-bottom: 8px; font-weight: 600; color: var(--text-color); font-size: 14px; }
        .form-group input, .form-group select, .form-group textarea { width: 100%; padding: 14px; border: 1px solid #ddd; border-radius: 10px; font-size: 16px; background-color: #fff; font-family: 'Inter', 'Cairo', sans-serif; }
        .form-group textarea { resize: vertical; min-height: 80px; }
        
        p.link { color: var(--primary-color); text-align: center; margin-top: 15px; cursor: pointer; }
        p.link strong { text-decoration: underline; }

        #forgot-message { color: var(--error-color); text-align: center; font-weight: 600; margin-bottom: 15px; min-height: 20px; }

        /* Auth Page "About" Section */
        #auth-about-section {
            margin-top: 25px;
            padding: 25px;
            background: rgba(0, 0, 0, 0.2);
            border-radius: 20px;
            color: var(--secondary-color);
            border: 1px solid rgba(255, 255, 255, 0.2);
            text-shadow: 1px 1px 3px rgba(0,0,0,0.3);
        }
        #auth-about-section h2 {
            font-family: 'Cairo', sans-serif;
            font-size: 24px;
            font-weight: 700;
            text-align: center;
            margin-bottom: 15px;
        }
        #auth-about-section p {
            font-family: 'Cairo', sans-serif;
            font-size: 15px;
            line-height: 1.7;
            margin-bottom: 20px;
        }
        #auth-about-section ul {
            list-style: none;
            padding: 0;
        }
        #auth-about-section li {
            font-family: 'Cairo', sans-serif;
            display: flex;
            align-items: center;
            margin-bottom: 12px;
            font-size: 14px;
        }
        #auth-about-section li i {
            font-size: 16px;
            background: var(--gold-gradient);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            width: 20px;
        }
        .auth-promo-text {
            font-family: 'Cairo', sans-serif;
            font-size: 16px !important;
            line-height: 1.7;
            font-weight: 600;
            text-align: center;
            margin-top: 20px;
            padding: 10px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 10px;
        }
        /* LTR styling */
        body:not(.rtl) #auth-about-section p:not(.auth-promo-text) { text-align: left; }
        body:not(.rtl) #auth-about-section ul { text-align: left; }
        body:not(.rtl) #auth-about-section li { justify-content: flex-start; }
        body:not(.rtl) #auth-about-section li i { margin-right: 12px; }
        /* RTL styling */
        body.rtl #auth-about-section p:not(.auth-promo-text) { text-align: right; }
        body.rtl #auth-about-section ul { text-align: right; }
        body.rtl #auth-about-section li { justify-content: flex-end; }
        body.rtl #auth-about-section li i { margin-left: 12px; }

        /* Online Users Card Styles */
        .online-users-card { text-align: center; padding: 12px; margin-bottom: 20px; background: rgba(0, 0, 0, 0.2); color: var(--secondary-color); font-weight: 600; border: 1px solid rgba(255, 255, 255, 0.2); }
        .online-users-card i { margin-right: 8px; color: var(--success-color); }
        #online-users-count { font-weight: 700; display: inline-block; min-width: 30px; }

        /* News Ticker Styles */
        #news-ticker-container { width: 100%; background-color: rgba(0, 0, 0, 0.3); border-radius: 12px; overflow: hidden; padding: 10px 0; margin-bottom: 20px; white-space: nowrap; box-shadow: 0 4px 10px rgba(0,0,0,0.1); }
        .news-ticker-content { display: inline-block; padding-left: 100%; animation: scroll-left 40s linear infinite; }
        .news-ticker-content span { display: inline-block; color: var(--secondary-color); font-size: 14px; font-weight: 500; margin: 0 25px; }
        .news-ticker-content span i { margin-right: 8px; opacity: 0.8; }
        @keyframes scroll-left { 0% { transform: translateX(0%); } 100% { transform: translateX(-100%); } }

        /* How It Works / Features Preview Styles */
        .how-it-works-steps, .features-preview { display: flex; justify-content: space-around; text-align: center; margin-top: 20px; }
        .step, .feature-item { flex: 1; padding: 10px; }
        .step-icon, .feature-icon { font-size: 32px; color: var(--primary-color); margin-bottom: 10px; width: 60px; height: 60px; line-height: 60px; border-radius: 50%; background: rgba(255,255,255,0.2); }
        .step h4, .feature-item h4 { font-size: 16px; margin-bottom: 5px; color: var(--text-color); }
        .step p, .feature-item p { font-size: 12px; color: var(--text-light-color); line-height: 1.4; }
        #register-form .features-preview { color: var(--text-color); }
        #register-form .feature-icon { color: white; background: var(--primary-color); }

        /* Ad Grid Layout Styles */
        .ad-list-container { display: grid; grid-template-columns: repeat(auto-fit, minmax(160px, 1fr)); gap: 15px; padding: 0; list-style: none; }
        .ad-list-item { background: rgba(255, 255, 255, 0.25); -webkit-backdrop-filter: blur(10px); backdrop-filter: blur(10px); border: 2px solid rgba(255, 255, 255, 0.4); border-radius: 20px; padding: 15px; text-align: center; color: var(--secondary-color); display: flex; flex-direction: column; align-items: center; justify-content: space-between; transition: transform 0.2s, box-shadow 0.2s; min-height: 220px; }
        .ad-list-item:hover { transform: translateY(-5px); box-shadow: 0 10px 20px rgba(0,0,0,0.2); }
        .ad-icon-container { font-size: 40px; margin-bottom: 15px; }
        .ad-icon-container .fa-youtube { color: var(--color-youtube); }
        .ad-icon-container .fa-facebook { color: var(--color-facebook); }
        .ad-icon-container .fa-tiktok { color: var(--color-tiktok); }
        .ad-icon-container .fa-instagram { color: var(--color-instagram); }
        .ad-info p { font-size: 14px; font-weight: 600; margin: 0; }
        .ad-info .task-target { font-size: 11px; font-weight: 400; opacity: 0.8; margin-top: 5px; word-break: break-all; }
        .ad-action-btn { width: 100%; margin-top: auto; padding: 10px; font-size: 14px; border-radius: 10px; }
        .ad-action-btn.watch-btn { background-color: var(--primary-color); color: white; }
        .ad-action-btn.task-btn { background-color: var(--success-color); color: white; }
        .ad-action-btn:disabled { background-color: var(--text-light-color); }

        /* Profile Page Styles */
        #profile-header { text-align: center; margin-bottom: 25px; }
        #profile-picture-container { position: relative; width: 120px; height: 120px; margin: 0 auto 15px auto; }
        #profile-picture { width: 100%; height: 100%; border-radius: 50%; object-fit: cover; border: 4px solid var(--secondary-color); box-shadow: 0 4px 15px rgba(0,0,0,0.2); }
        #profile-picture-upload-label { position: absolute; bottom: 0; right: 0; width: 36px; height: 36px; background: var(--primary-color); color: white; border-radius: 50%; display: flex; align-items: center; justify-content: center; cursor: pointer; border: 2px solid white; box-shadow: 0 2px 5px rgba(0,0,0,0.3); }
        #profile-picture-upload { display: none; }

        #profile-identity { display: flex; align-items: center; justify-content: center; gap: 10px; margin-bottom: 5px; flex-wrap: wrap; }
        #profile-name-display { color: var(--secondary-color); text-shadow: 0 2px 4px rgba(0,0,0,0.3); font-size: 28px; font-weight: 700; margin: 0; }
        #profile-badge-container { display: flex; align-items: center; gap: 8px; }
        .profile-badge { display: inline-flex; align-items: center; padding: 4px 10px; border-radius: 16px; font-size: 12px; font-weight: 700; text-transform: uppercase; letter-spacing: 0.5px; }
        .profile-badge i { margin-right: 5px; font-size: 13px; }
        body.rtl .profile-badge i { margin-right: 0; margin-left: 5px; }
        .verified-badge { background-color: #1DA1F2; color: white; box-shadow: 0 2px 4px rgba(29, 161, 242, 0.4); }
        .publisher-badge { background: var(--gold-gradient); color: black; box-shadow: 0 2px 5px rgba(0,0,0,0.3); }

        #profile-balance-display { color: var(--secondary-color); text-shadow: 0 2px 4px rgba(0,0,0,0.3); }
        #profile-balance-display p { font-size: 16px; font-weight: 500; margin: 0; }
        #profile-balance-display h2 { font-size: 32px; font-weight: 700; margin: 0; }
        #kyc-status { font-weight: 700; }
        .status-verified { color: var(--success-color); }
        .status-pending { color: var(--warning-color); }
        .status-not-verified { color: var(--error-color); }

        /* Deposit Page Styles */
        #cih-screenshot-upload { display: none; }
        #screenshot-filename { font-size: 12px; color: var(--text-light-color); text-align: center; margin-top: 10px; }
        .btn-secondary { background: rgba(255,255,255,0.7); color: var(--text-color); }
        
        #deposit-timer-display {
            margin-top: 20px;
            text-align: center;
            font-size: 16px;
            font-weight: 600;
            color: var(--text-color);
            background-color: rgba(255, 255, 255, 0.15);
            padding: 10px;
            border-radius: 10px;
            border: 1px solid rgba(255,255,255,0.4);
        }
        #deposit-timer-display i { margin-right: 8px; }
        body.rtl #deposit-timer-display i { margin-right: 0; margin-left: 8px; }

        /* Professional Payment Method Styles */
        .methods-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(120px, 1fr)); gap: 15px; margin-bottom: 25px; }
        .method-card { background: rgba(255, 255, 255, 0.25); -webkit-backdrop-filter: blur(10px); backdrop-filter: blur(10px); border: 2px solid rgba(255, 255, 255, 0.4); border-radius: 15px; padding: 20px 15px; display: flex; flex-direction: column; align-items: center; justify-content: center; text-align: center; color: var(--secondary-color); text-shadow: 0 1px 3px rgba(0,0,0,0.2); cursor: pointer; transition: transform 0.3s ease, box-shadow 0.3s ease, border-color 0.3s ease, background 0.3s ease; position: relative; }
        .method-card:hover { transform: translateY(-5px); box-shadow: 0 12px 24px rgba(0, 0, 0, 0.2); }
        .method-card.active { border-color: var(--success-color); box-shadow: 0 8px 16px rgba(0,0,0,0.25); transform: translateY(-5px); }
        .method-card.active::after { content: '\f00c'; font-family: 'Font Awesome 6 Free'; font-weight: 900; position: absolute; top: 10px; right: 10px; width: 24px; height: 24px; background-color: var(--success-color); color: white; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-size: 14px; }
        .method-card i { font-size: 36px; margin-bottom: 12px; color: var(--secondary-color); transition: color 0.3s ease; }
        .method-card span { font-weight: 600; font-size: 14px; }
        
        /* Platform-specific coloring */
        .method-card.cih:hover, .method-card.cih.active { border-color: var(--color-cih); }
        .method-card.cih.active { background: linear-gradient(145deg, var(--color-cih), #a11319); }
        .method-card.paypal:hover, .method-card.paypal.active { border-color: var(--color-paypal); }
        .method-card.paypal.active { background: linear-gradient(145deg, var(--color-paypal), #005ea6); }
        .method-card.payeer:hover, .method-card.payeer.active { border-color: var(--color-payeer); }
        .method-card.payeer.active { background: linear-gradient(145deg, var(--color-payeer), #1c8b7f); }
        .method-card.usdt:hover, .method-card.usdt.active { border-color: var(--color-usdt); }
        .method-card.usdt.active { background: linear-gradient(145deg, var(--color-usdt), #1a7e5f); }
        .method-card.binance-pay:hover, .method-card.binance-pay.active { border-color: var(--color-binance-pay); }
        .method-card.binance-pay.active { background: linear-gradient(145deg, var(--color-binance-pay), #d8a40a); color: var(--text-color); }
        .method-card.binance-pay.active i, .method-card.binance-pay.active span { color: var(--text-color); text-shadow: none; }
        .method-card.wise:hover, .method-card.wise.active { border-color: var(--color-wise); }
        .method-card.wise.active { background: linear-gradient(145deg, var(--color-wise), #87c75b); color: var(--text-color); }
        .method-card.wise.active i, .method-card.wise.active span { color: var(--text-color); text-shadow: none; }
        .method-card.skrill:hover, .method-card.skrill.active { border-color: var(--color-skrill); }
        .method-card.skrill.active { background: linear-gradient(145deg, var(--color-skrill), #6c1a5d); }
        .method-card.perfect-money:hover, .method-card.perfect-money.active { border-color: var(--color-perfect-money); }
        .method-card.perfect-money.active { background: linear-gradient(145deg, var(--color-perfect-money), #a51f1a); }
        .method-card.bitcoin:hover, .method-card.bitcoin.active { border-color: var(--color-bitcoin); }
        .method-card.bitcoin.active { background: linear-gradient(145deg, var(--color-bitcoin), #d47e16); }
        .method-card.pi-network:hover, .method-card.pi-network.active { border-color: var(--primary-color); }
        .method-card.pi-network.active { background: linear-gradient(145deg, var(--primary-color), #4d0b9a); }
        .method-card.pi-network i { color: var(--color-pi); }
        .method-card.pi-network.active i { color: white; }
        
        #qr-code-img { border: 5px solid white; border-radius: 10px; box-shadow: 0 4px 10px rgba(0,0,0,0.2); }

        /* Packages Page Styles */
        .package-card { 
            padding: 0; 
            overflow: hidden; 
            position: relative; 
            border: 1px solid rgba(0,0,0,0.1);
            background-blend-mode: screen;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .package-card:hover { transform: translateY(-5px); box-shadow: 0 12px 28px rgba(0,0,0,0.15); }
        .package-hero-icon-container { padding: 30px 20px; text-align: center; margin: 0; border-bottom: 1px solid rgba(0,0,0,0.1); background: transparent; }
        .package-hero-icon-container i { font-size: 64px; text-shadow: 0 2px 8px rgba(0,0,0,0.15); position: relative; z-index: 1; }
        
        .package-card[data-package="youtube"] { background-color: #fff0f0; background-image: radial-gradient(circle at 10% 20%, rgba(255, 255, 255, 0.7) 0%, transparent 45%), radial-gradient(circle at 80% 90%, rgba(255, 0, 0, 0.18) 0%, transparent 50%); }
        .package-card[data-package="youtube"] .package-hero-icon-container i { color: var(--color-youtube); }
        .package-card[data-package="facebook"] { background-color: #eff5ff; background-image: radial-gradient(circle at 90% 15%, rgba(255, 255, 255, 0.7) 0%, transparent 45%), radial-gradient(circle at 20% 80%, rgba(24, 119, 242, 0.2) 0%, transparent 50%); }
        .package-card[data-package="facebook"] .package-hero-icon-container i { color: var(--color-facebook); }
        .package-card[data-package="tiktok"] { background-color: #f7f7f7; background-image: radial-gradient(circle at 15% 85%, rgba(255, 255, 255, 0.7) 0%, transparent 45%), radial-gradient(circle at 85% 20%, rgba(0, 0, 0, 0.12) 0%, transparent 50%); }
        .package-card[data-package="tiktok"] .package-hero-icon-container i { color: var(--color-tiktok); }
        .package-card[data-package="instagram"] { background-color: #fff0f5; background-image: radial-gradient(circle at 10% 90%, rgba(255, 223, 0, 0.2) 0%, transparent 50%), radial-gradient(circle at 90% 30%, rgba(228, 64, 95, 0.2) 0%, transparent 50%), radial-gradient(circle at 50% 50%, rgba(255, 255, 255, 0.6) 0%, transparent 45%); }
        .package-card[data-package="instagram"] .package-hero-icon-container i { background: radial-gradient(circle at 30% 107%, #fdf497 0%, #fdf497 5%, #fd5949 45%, #d6249f 60%, #285AEB 90%); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }

        .package-card .friday-deal-banner { position: absolute; top: 15px; left: -40px; transform: rotate(-45deg); width: 150px; background: var(--gold-gradient); color: black; text-align: center; padding: 5px 0; font-weight: 700; font-size: 14px; text-transform: uppercase; z-index: 2; box-shadow: 0 2px 5px rgba(0,0,0,0.3); }
        .package-card-header { padding: 20px 20px 15px 20px; text-align: center; }
        .package-card-header h2 { margin: 0; color: var(--text-color); }
        .package-card-body { padding: 20px; }
        .price-container { text-align: center; margin-bottom: 20px; }
        .original-price { font-size: 16px; text-decoration: line-through; color: var(--text-light-color); }
        .final-price { font-size: 32px; font-weight: 700; color: var(--text-color); }
        .discount-badge { background-color: var(--error-color); color: white; padding: 4px 8px; border-radius: 8px; font-size: 12px; font-weight: bold; margin-left: 10px;}
        
        .package-features-list { list-style: none; padding: 0; margin: 0 0 20px 0; text-align: left; }
        body.rtl .package-features-list { text-align: right; }
        .package-features-list li { display: flex; align-items: center; margin-bottom: 10px; font-size: 14px; color: var(--text-color); }
        .package-features-list i { color: var(--success-color); margin-right: 12px; width: 20px; text-align: center; }
        body.rtl .package-features-list i { margin-right: 0; margin-left: 12px; }
        .feature-quantity { margin-left: auto; font-weight: 700; background-color: rgba(0,0,0,0.08); padding: 3px 8px; border-radius: 8px; font-size: 13px; }
        body.rtl .feature-quantity { margin-left: 0; margin-right: auto; }

        .monetization-requirements { margin: 20px 0; padding: 15px; background-color: rgba(0,0,0,0.05); border-radius: 12px; border-top: 2px solid rgba(0,0,0,0.1); }
        .monetization-requirements h4 { font-size: 16px; font-weight: 700; text-align: center; margin-bottom: 12px; color: var(--text-color); }
        .monetization-requirements ul { list-style: none; padding: 0; margin: 0; }
        .monetization-requirements li { display: flex; align-items: center; font-size: 14px; color: var(--text-light-color); margin-bottom: 8px; }
        .monetization-requirements li:last-child { margin-bottom: 0; }
        .monetization-requirements li i { color: var(--primary-color); margin-right: 10px; width: 22px; text-align: center; }
        body.rtl .monetization-requirements li i { margin-right: 0; margin-left: 10px; }
        .monetization-requirements li span { font-weight: 600; }

        .package-progress-container, .package-complete-message { display: none; margin-top: 15px; }
        .package-progress-container h4 { text-align: center; font-size: 16px; margin-bottom: 15px; font-weight: 600; color: var(--text-color); }
        .progress-item { margin-bottom: 12px; }
        .progress-item-label { display: flex; justify-content: space-between; font-size: 12px; font-weight: 500; margin-bottom: 5px; color: var(--text-light-color); }
        .progress-bar-bg { background-color: rgba(0,0,0,0.1); border-radius: 8px; height: 10px; overflow: hidden; }
        .progress-bar-fill { background: var(--primary-color); height: 100%; border-radius: 8px; width: 0%; transition: width 0.5s ease-out; }
        .package-complete-message { text-align: center; padding: 20px; background-color: rgba(76, 175, 80, 0.1); border: 2px solid var(--success-color); border-radius: 12px; }
        .package-complete-message i { font-size: 40px; color: var(--success-color); margin-bottom: 10px; }
        .package-complete-message h4 { font-size: 18px; color: var(--success-color); margin-bottom: 5px; }
        .package-complete-message p { font-size: 14px; color: var(--text-light-color); }
        .package-complete-message .btn { margin-top: 20px; }

        /* Modal Styles */
        .modal-overlay { position: fixed; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0,0,0,0.6); backdrop-filter: blur(5px); display: none; justify-content: center; align-items: center; z-index: 1000; padding: 20px 0; }
        .modal-content { background: white; padding: 0; border-radius: 20px; width: 90%; max-width: 450px; box-shadow: 0 10px 40px rgba(0,0,0,0.3); display: flex; flex-direction: column; max-height: 90vh; overflow: hidden; }
        .modal-header { display: flex; justify-content: space-between; align-items: center; padding: 15px 25px; border-bottom: 1px solid #eee; flex-shrink: 0; }
        .modal-body { overflow-y: auto; padding: 25px; }
        .modal-header h2 { margin: 0; font-size: 22px; color: var(--text-color); }
        .modal-close-btn { background: none; border: none; font-size: 24px; cursor: pointer; color: var(--text-light-color); }

        #kyc-modal .modal-content { max-width: 400px; text-align: center; }
        .kyc-step { display: none; }
        .kyc-step.active { display: block; }
        .kyc-step h3 { font-size: 20px; margin-bottom: 10px; color: var(--text-color); }
        .kyc-step p { font-size: 14px; color: var(--text-light-color); margin-bottom: 25px; line-height: 1.5; }
        .kyc-step-icon { font-size: 60px; margin-bottom: 20px; color: var(--primary-color); }
        .kyc-upload-box { border: 2px dashed #ddd; border-radius: 12px; padding: 20px; margin-bottom: 20px; cursor: pointer; transition: background-color 0.2s; }
        .kyc-upload-box:hover { background-color: rgba(0,0,0,0.05); }
        .kyc-upload-box i { font-size: 32px; color: var(--text-light-color); margin-bottom: 10px; }
        .kyc-upload-box span { font-weight: 600; display: block; color: var(--text-color); }
        .kyc-upload-box input[type="file"] { display: none; }
        .kyc-image-preview { width: 100%; max-height: 150px; border-radius: 8px; object-fit: contain; margin-bottom: 15px; border: 1px solid #ddd; }
        .kyc-loader { border: 4px solid #f3f3f3; border-top: 4px solid var(--primary-color); border-radius: 50%; width: 50px; height: 50px; animation: spin 1s linear infinite; margin: 20px auto; }
        @keyframes spin { 0% { transform: rotate(0deg); } 100% { transform: rotate(360deg); } }

        .fab { position: fixed; width: 60px; height: 60px; border-radius: 50%; display: none; align-items: center; justify-content: center; color: white; font-size: 24px; box-shadow: 0 4px 15px rgba(0,0,0,0.3); cursor: pointer; z-index: 999; transition: transform 0.2s ease-in-out; }
        .fab:hover { transform: scale(1.1); }
        .fab-unread-count { position: absolute; top: -2px; right: -2px; background-color: var(--error-color); color: white; width: 22px; height: 22px; border-radius: 50%; display: flex; align-items: center; justify-content: center; border: 2px solid white; font-size: 12px; font-weight: bold; }
        #chat-fab { bottom: calc(80px + var(--safe-area-inset-bottom)); right: 20px; background: linear-gradient(45deg, var(--primary-color), var(--primary-dark-color)); }
        #support-fab { bottom: calc(80px + var(--safe-area-inset-bottom)); right: 20px; background: linear-gradient(45deg, #28a745, #218838); }
        body.rtl #support-fab { right: auto; left: 20px; }
        body:not(.page-profile) #support-fab { display: none !important; }

        .chat-modal-class .modal-content { width: 95%; max-width: 800px; height: 80vh; max-height: 600px; padding: 0; }
        .chat-header-class { padding: 15px 20px; border-bottom: 1px solid #eee; }
        .chat-messages-container-class { flex-grow: 1; overflow-y: auto; padding: 15px; background-color: #f9f9f9; }
        .chat-message { display: flex; margin-bottom: 15px; max-width: 80%; }
        .chat-message.current-user { margin-left: auto; flex-direction: row-reverse; }
        .chat-avatar { width: 40px; height: 40px; border-radius: 50%; object-fit: cover; flex-shrink: 0; margin: 0 10px; }
        .message-bubble { padding: 10px 15px; border-radius: 18px; position: relative; }
        .chat-message:not(.current-user) .message-bubble { background-color: #e5e5ea; color: black; border-bottom-left-radius: 4px; }
        .chat-message.current-user .message-bubble { background-color: var(--primary-dark-color); color: white; border-bottom-right-radius: 4px; }
        .message-sender-info { display: flex; align-items: center; gap: 5px; margin-bottom: 5px; font-size: 13px; font-weight: 600; }
        .chat-message.current-user .message-sender-info { justify-content: flex-end; }
        .chat-message:not(.current-user) .message-sender-info { color: #333; }
        .chat-message.current-user .message-sender-info { color: #ddd; }
        .chat-badge { font-size: 11px; padding: 1px 6px; }
        .message-text { word-wrap: break-word; font-size: 15px; line-height: 1.4; }
        .message-time { font-size: 11px; color: #999; margin-top: 5px; }
        .chat-message.current-user .message-time { text-align: right; }
        .chat-input-form-class { display: flex; padding: 15px; border-top: 1px solid #eee; gap: 10px; flex-shrink: 0; }
        .chat-input-class { flex-grow: 1; padding: 12px; border: 1px solid #ccc; border-radius: 20px; font-size: 15px; resize: none; }
        .chat-send-btn-class { width: 45px; height: 45px; padding: 0; border-radius: 50%; font-size: 18px; flex-shrink: 0; }

        .bottom-nav { background: rgba(255, 255, 255, 0.6); -webkit-backdrop-filter: blur(15px); backdrop-filter: blur(15px); position: fixed; bottom: 0; left: 0; right: 0; height: calc(60px + var(--safe-area-inset-bottom)); display: flex; justify-content: space-around; align-items: flex-start; padding-top: 10px; border-top: 1px solid rgba(255, 255, 255, 0.3); z-index: 50; }
        .nav-item { display: flex; flex-direction: column; align-items: center; text-decoration: none; color: var(--text-light-color); font-size: 12px; flex: 1; font-weight: 600; }
        .nav-item.active { color: var(--primary-color); }
        .nav-item i { font-size: 20px; margin-bottom: 4px; }
        #bottom-nav-container { display: none; }

        .language-selector { position: absolute; top: 22px; right: 20px; z-index: 20; }
        .language-globe-btn { color: var(--secondary-color); font-size: 24px; cursor: pointer; text-shadow: 0 2px 4px rgba(0,0,0,0.2); }
        .language-dropdown { display: none; position: absolute; right: 0; top: 100%; margin-top: 10px; background: rgba(255, 255, 255, 0.9); backdrop-filter: blur(10px); border-radius: 8px; box-shadow: 0 4px 15px rgba(0,0,0,0.2); overflow: hidden; list-style: none; padding: 0; width: 120px; }
        .language-dropdown.show { display: block; }
        .language-dropdown li a { display: block; padding: 10px 15px; text-decoration: none; color: var(--text-color); font-weight: 500; transition: background-color 0.2s; }
        .language-dropdown li a:hover { background-color: rgba(0,0,0,0.1); }
        
        .referral-card-professional { padding: 0; overflow: hidden; }
        .ref-header { padding: 15px 20px; background: rgba(0,0,0,0.1); text-align: center; border-bottom: 1px solid rgba(0,0,0,0.05); }
        .ref-header h3 { font-size: 20px; font-weight: 700; color: var(--text-color); margin: 0; }
        .ref-header p { font-size: 14px; color: var(--text-light-color); margin-top: 4px; line-height: 1.4;}
        .ref-body { display: flex; gap: 20px; padding: 20px; align-items: flex-start; }
        .ref-qr-code { flex-shrink: 0; }
        .ref-qr-code img { border-radius: 12px; display: block; border: 4px solid white; box-shadow: 0 2px 8px rgba(0,0,0,0.15); }
        .ref-details { flex-grow: 1; display: flex; flex-direction: column; gap: 15px; }
        .ref-stats { display: flex; justify-content: space-around; background-color: rgba(255,255,255,0.2); border-radius: 10px; padding: 10px; }
        .ref-stat-item { text-align: center; flex: 1; padding: 0 5px; }
        .ref-stat-item:first-child { border-right: 1px solid rgba(0,0,0,0.1); }
        body.rtl .ref-stat-item:first-child { border-right: none; border-left: 1px solid rgba(0,0,0,0.1); }
        .ref-stat-item span { display: block; font-size: 12px; font-weight: 500; color: var(--text-light-color); }
        .ref-stat-item strong { display: block; font-size: 18px; font-weight: 700; color: var(--text-color); }
        .ref-link-group label { margin-bottom: 5px; font-size: 12px; font-weight: 600; }
        .ref-link-input { width: 100%; border: 1px solid var(--border-color); background: rgba(255,255,255,0.7); padding: 10px; border-radius: 8px; font-size: 13px; overflow-x: auto; white-space: nowrap; }
        .ref-actions { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; }
        .ref-actions .btn { padding: 12px; font-size: 14px; }
        .ref-actions .btn i { margin-right: 8px; }
        @media (max-width: 480px) { .ref-body { flex-direction: column; align-items: center; } .ref-details { width: 100%; } }
        
        .app-store-section { background: rgba(0, 0, 0, 0.2); -webkit-backdrop-filter: blur(10px); backdrop-filter: blur(10px); border-radius: 20px; padding: 20px; border: 1px solid rgba(255, 255, 255, 0.2); margin-top: 10px; text-align: center; }
        .app-store-section h4 { font-size: 16px; margin-bottom: 15px; font-weight: 600; color: var(--secondary-color); }
        .app-store-buttons { display: flex; flex-wrap: wrap; justify-content: center; align-items: center; gap: 15px; }
        .app-store-btn { display: flex; align-items: center; padding: 8px 16px; border-radius: 8px; text-decoration: none; transition: transform 0.2s ease, box-shadow 0.2s ease; cursor: pointer; }
        .app-store-btn:hover { transform: translateY(-3px); box-shadow: 0 6px 12px rgba(0,0,0,0.2); }
        .app-store-btn.google-play { background-color: #000000; color: #FFFFFF; border: 1px solid #4d4d4d; }
        .app-store-btn.app-store { background-color: #000000; color: #FFFFFF; border: 1px solid #4d4d4d; }
        .app-store-btn svg { width: 24px; height: 24px; margin-right: 10px; }
        body.rtl .app-store-btn svg { margin-right: 0; margin-left: 10px; }
        .app-store-btn .btn-text { text-align: left; }
        body.rtl .app-store-btn .btn-text { text-align: right; }
        .btn-text span:first-child { font-size: 10px; display: block; line-height: 1; opacity: 0.8; }
        .btn-text span:last-child { font-size: 16px; display: block; font-weight: 600; line-height: 1.2; }
        
        .page-footer { text-align: center; padding: 15px 0 0 0; font-size: 12px; color: rgba(255, 255, 255, 0.7); text-shadow: 1px 1px 2px rgba(0,0,0,0.2); }
        .page:not(#dashboard-page):not(#profile-page) .app-store-section,
        .page:not(#dashboard-page):not(#profile-page) .page-footer { display: none; }
        
        body.rtl { direction: rtl; text-align: right; }
        body.rtl h1.page-title, body.rtl .card h3, body.rtl .ref-header h3 { text-align: right; }
        body.rtl .back-btn { margin-right: 0; margin-left: 15px; }
        body.rtl .page-title .back-btn i { transform: scaleX(-1); }
        body.rtl .btn i, body.rtl .notification i, body.rtl .ref-actions .btn i { margin-right: 0; margin-left: 8px; }
        body.rtl .btn-secondary i { margin-left: 0; margin-right: 8px; }
        body.rtl .language-selector { right: auto; left: 20px; }
        body.rtl .language-dropdown { right: auto; left: 0; }
        body.rtl .modal-header h2 { text-align: right; }
        body.rtl .form-group label, body.rtl p.link, body.rtl .reach-display, body.rtl .terms-agreement label, body.rtl .ref-link-group label { text-align: right; }
        body.rtl .modal-close-btn { order: -1; }
        body.rtl .modal-header { justify-content: space-between; }
        body.rtl #profile-picture-upload-label { right: auto; left: 0; }
        body.rtl .method-card.active::after { right: auto; left: 10px; }
        body.rtl .news-ticker-content span i { margin-right: 0; margin-left: 8px; }
        .reach-display { margin-top: 15px; text-align: center; font-weight: 600; color: var(--text-color); }
        .terms-agreement { margin-top: 15px; display: flex; align-items: center; }
        .terms-agreement input { width: auto; margin-right: 10px; }
        body.rtl .terms-agreement input { margin-right: 0; margin-left: 10px; }
        .specific-ad-fields { border-left: 3px solid var(--primary-color); padding-left: 15px; margin-top: 15px; }
        body.rtl .specific-ad-fields { border-left: 0; border-right: 3px solid var(--primary-color); padding-left: 0; padding-right: 15px; }

        .store-entry-card { display: flex; align-items: center; gap: 20px; text-decoration: none; color: var(--text-color); padding: 25px; transition: transform 0.2s ease, box-shadow 0.2s ease; }
        .store-entry-card:hover { transform: translateY(-5px); box-shadow: 0 12px 24px rgba(0,0,0,0.15); }
        .store-entry-icon { font-size: 36px; color: white; background: var(--primary-color); width: 70px; height: 70px; border-radius: 18px; display: flex; align-items: center; justify-content: center; flex-shrink: 0; }
        .store-entry-text h3 { font-size: 20px; font-weight: 700; margin: 0 0 5px 0; }
        .store-entry-text p { font-size: 14px; color: var(--text-light-color); line-height: 1.4; margin: 0; }
        .store-entry-cta { margin-left: auto; font-size: 24px; color: var(--primary-color); }
        body.rtl .store-entry-cta { margin-left: 0; margin-right: auto; transform: scaleX(-1); }

        .store-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(160px, 1fr)); gap: 20px; margin-top: 10px; }
        .product-card { background: rgba(0, 0, 0, 0.15); border: 1px solid rgba(255, 255, 255, 0.1); border-radius: 20px; padding: 15px; display: flex; flex-direction: column; text-decoration: none; color: var(--secondary-color); transition: transform 0.3s ease, box-shadow 0.3s ease; backdrop-filter: blur(8px); position: relative; overflow: hidden; }
        .product-card:hover { transform: translateY(-8px); box-shadow: 0 12px 25px rgba(0, 0, 0, 0.25); }
        .product-logo { width: 100%; height: 80px; margin-bottom: 15px; display: flex; align-items: center; justify-content: center; border-radius: 12px; padding: 10px; background-size: cover; background-position: center; }
        .product-logo svg, .product-logo i, .product-logo img { width: 100%; height: auto; max-height: 50px; filter: drop-shadow(0 2px 4px rgba(0,0,0,0.4)); }
        .product-logo.netflix-logo { background-image: linear-gradient(to top, #000000 0%, #e50914 100%); }
        .product-logo.spotify-logo { background-image: linear-gradient(120deg, #1db954 0%, #191414 100%); }
        .product-logo.canva-logo { background-image: linear-gradient(45deg, #3c46a8 0%, #00c4cc 100%); }
        .product-logo.premium-logo { background: var(--gold-gradient); }
        .product-logo.premium-logo i { color: black; font-size: 40px; }
        .product-logo.user-product-logo { background-color: rgba(255,255,255,0.1); }
        .product-logo.user-product-logo img { object-fit: cover; width: 100%; height: 100%; border-radius: 8px; filter: none; }
        .product-info { text-align: center; margin-bottom: 15px; flex-grow: 1; }
        .product-name { font-size: 15px; font-weight: 600; display: block; line-height: 1.3; }
        .product-seller { font-size: 11px; font-weight: 500; color: var(--secondary-color); opacity: 0.7; margin-top: 4px; }
        .product-price { font-size: 18px; font-weight: 700; margin-top: 8px; display: block; color: #a8ff78; text-shadow: 0 1px 3px rgba(0,0,0,0.4); }
        .product-price small { font-size: 12px; font-weight: 400; opacity: 0.8; }
        .buy-now-btn { width: 100%; padding: 10px; font-size: 14px; border-radius: 10px; background: rgba(255, 255, 255, 0.9); color: var(--text-color); border: none; font-weight: 700; margin-top: auto; }
        .buy-now-btn i { margin-right: 8px; }
        body.rtl .buy-now-btn i { margin-right: 0; margin-left: 8px; }

        #my-products-list { list-style: none; padding: 0; }
        .my-product-item { display: flex; align-items: center; gap: 15px; padding: 15px; background: rgba(0,0,0,0.1); border-radius: 12px; margin-bottom: 10px; color: var(--secondary-color); }
        .my-product-item img { width: 50px; height: 50px; border-radius: 8px; object-fit: cover; flex-shrink: 0; }
        .my-product-details { flex-grow: 1; }
        .my-product-details h4 { margin: 0 0 5px; font-size: 16px; }
        .my-product-details p { margin: 0; font-size: 14px; opacity: 0.8; }
        .my-product-price { font-size: 16px; font-weight: 700; }
        #profile-actions-container { display: flex; flex-direction: column; gap: 15px; margin-bottom: 20px; }

    </style>
</head>
<body class="gradient-home">
    <div id="notification-container"></div>

    <div id="app-container">
        <!-- Translation Selector -->
        <div class="language-selector">
            <i class="fas fa-globe language-globe-btn"></i>
            <ul class="language-dropdown">
                <li><a href="#" data-lang="en">English</a></li>
                <li><a href="#" data-lang="ar">العربية</a></li>
            </ul>
        </div>
        
        <!-- Splash Screen -->
        <div id="splash-page" class="page active no-transform">
            <div id="icon-rain-container"></div>
            <div id="splash-title-container">
                <h1 class="splash-title" data-translate-key="app_title_full">
                    Make Money
                    <span class="splash-subtitle">& Traffic</span>
                </h1>
            </div>
            <div id="loader-percentage">0%</div>
        </div>

        <!-- Auth Page -->
        <div id="auth-page" class="page">
            <h1 class="page-title" style="justify-content: center; color: var(--secondary-color);" data-translate-key="app_title_full">Make Money & Traffic</h1>
            
            <div id="login-form-container" class="card">
                <form id="login-form">
                    <div class="form-group"><label for="login-email" data-translate-key="email">Email</label><input type="email" id="login-email" required></div>
                    <div class="form-group"><label for="login-password" data-translate-key="password">Password</label><input type="password" id="login-password" required></div>
                    <button type="submit" class="btn btn-primary" data-translate-key="login">Login</button>
                </form>
                <p class="link" id="show-forgot-password" data-translate-key="forgot_password_q">Forgot Password?</p>
                <p class="link" id="show-register" style="margin-top:20px;" data-translate-key="no_account_q">Don't have an account? <strong data-translate-key="register">Register</strong></p>
            </div>

            <div id="register-form" style="display:none;" class="card">
                <div class="features-preview">
                    <div class="feature-item">
                        <div class="feature-icon"><i class="fas fa-play-circle"></i></div>
                        <h4 data-translate-key="watch_earn">Watch & Earn</h4>
                        <p data-translate-key="watch_earn_desc">Get paid for watching videos and completing simple tasks.</p>
                    </div>
                    <div class="feature-item">
                        <div class="feature-icon"><i class="fas fa-wallet"></i></div>
                        <h4 data-translate-key="easy_payouts">Easy Payouts</h4>
                        <p data-translate-key="easy_payouts_desc">Withdraw your earnings through multiple payment methods.</p>
                    </div>
                    <div class="feature-item">
                        <div class="feature-icon"><i class="fas fa-rocket"></i></div>
                        <h4 data-translate-key="grow">Grow</h4>
                        <p data-translate-key="grow_desc">Promote your own content to a real audience.</p>
                    </div>
                </div>
                <hr style="border-top:1px solid rgba(255,255,255,0.4); margin: 25px 0;">
                <form id="register-form-actual">
                    <div class="form-group"><label for="register-name" data-translate-key="full_name">Full Name</label><input type="text" id="register-name" required></div>
                    <div class="form-group"><label for="register-email" data-translate-key="email">Email</label><input type="email" id="register-email" required></div>
                    <div class="form-group"><label for="register-password" data-translate-key="password">Password</label><input type="password" id="register-password" required></div>
                    <div class="form-group"><label for="register-confirm-password" data-translate-key="confirm_password">Confirm Password</label><input type="password" id="register-confirm-password" required></div>
                    <button type="submit" class="btn btn-primary" data-translate-key="register">Register</button>
                </form>
                <p class="link" id="show-login" data-translate-key="have_account_q">Already have an account? <strong data-translate-key="login">Login</strong></p>
            </div>
            
            <div id="auth-about-section">
                <h2 data-translate-key="auth_about_title"></h2>
                <p data-translate-key="auth_about_desc1"></p>
                <p data-translate-key="auth_about_desc2"></p>
                <ul>
                    <li><i class="fas fa-user-plus"></i><span data-translate-key="auth_about_li1"></span></li>
                    <li><i class="fas fa-coins"></i><span data-translate-key="auth_about_li2"></span></li>
                    <li><i class="fas fa-wallet"></i><span data-translate-key="auth_about_li3"></span></li>
                    <li><i class="fas fa-rocket"></i><span data-translate-key="auth_about_li4"></span></li>
                    <li><i class="fas fa-users"></i><span data-translate-key="auth_about_li5"></span></li>
                </ul>
                <p class="auth-promo-text" data-translate-key="auth_about_promo_line"></p>
                <p style="text-align: center; margin-top: 20px; margin-bottom: 0;" data-translate-key="auth_about_footer"></p>
            </div>

        </div>

        <!-- Forgot Password Page -->
        <div id="forgot-password-page" class="page">
            <h1 class="page-title"><a href="#" class="back-btn" data-target="auth-page"><i class="fas fa-arrow-left"></i></a><span data-translate-key="reset_password">Reset Password</span></h1>
            <div class="card">
                <p id="forgot-message"></p>
                <form id="forgot-step-1-form">
                    <p style="text-align: center; margin-bottom: 20px;" data-translate-key="forgot_intro">Enter your account's email address and we will help you reset your password.</p>
                    <div class="form-group"><label for="forgot-email" data-translate-key="email_address">Email Address</label><input type="email" id="forgot-email" required></div>
                    <button type="submit" class="btn btn-primary" data-translate-key="next">Next</button>
                </form>
                <form id="forgot-step-2-form" style="display: none;"><p style="text-align: center; margin-bottom: 20px;" data-translate-key="forgot_verify_intro">To verify your identity, please enter your date of birth.</p><div class="form-group"><label for="forgot-dob" data-translate-key="date_of_birth">Date of Birth</label><input type="date" id="forgot-dob" required></div><button type="submit" class="btn btn-primary" data-translate-key="verify">Verify</button></form>
                <form id="forgot-step-3-form" style="display: none;"><p style="text-align: center; margin-bottom: 20px;" data-translate-key="forgot_new_pass_intro">Verification successful. Please enter your new password.</p><div class="form-group"><label for="forgot-new-password" data-translate-key="new_password">New Password</label><input type="password" id="forgot-new-password" required></div><div class="form-group"><label for="forgot-confirm-password" data-translate-key="confirm_new_password">Confirm New Password</label><input type="password" id="forgot-confirm-password" required></div><button type="submit" class="btn btn-primary" data-translate-key="reset_password">Reset Password</button></form>
            </div>
        </div>


        <!-- Dashboard Page -->
        <div id="dashboard-page" class="page">
            <h1 class="page-title" id="welcome-message">Welcome!</h1>
            
            <div id="news-ticker-container"><div class="news-ticker-content"></div></div>
            <div class="card online-users-card"><p><i class="fas fa-users"></i> <span data-translate-key="online_users">Online Users:</span> <span id="online-users-count">...</span></p></div>
            <div class="card balance-card"><p data-translate-key="current_balance">Current Balance</p><h2 id="balance-display" style="font-size: 48px;">$0.00</h2></div>
            
            <div class="card">
                <h3 style="font-size: 20px; text-align: center; margin-bottom: 10px; font-weight: 600;" data-translate-key="how_it_works">How It Works</h3>
                <div class="how-it-works-steps">
                    <div class="step"><div class="step-icon"><i class="fas fa-eye"></i></div><h4 data-translate-key="watch_ads">Watch Ads</h4><p data-translate-key="watch_ads_desc">Explore videos and tasks.</p></div>
                    <div class="step"><div class="step-icon"><i class="fas fa-coins"></i></div><h4 data-translate-key="earn_cash">Earn Cash</h4><p data-translate-key="earn_cash_desc">Get rewards for your time.</p></div>
                    <div class="step"><div class="step-icon"><i class="fas fa-hand-holding-usd"></i></div><h4 data-translate-key="withdraw_money">Withdraw</h4><p data-translate-key="withdraw_money_desc">Easily cash out your earnings.</p></div>
                </div>
            </div>

            <div class="card">
                <h3 style="font-size: 20px; text-align: center; margin-bottom: 20px; font-weight: 600;" data-translate-key="start_earning">Start Earning</h3>
                <div id="quick-access-grid" style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 15px;">
                    <a href="#" class="icon-item video" data-target="ad-list-page-1" style="display: flex; flex-direction: column; align-items: center; justify-content: center; padding: 15px 10px; border-radius: 18px; text-decoration: none; text-align: center; cursor: pointer; color: var(--secondary-color); transition: transform 0.15s ease-out, box-shadow 0.15s ease-out; background: linear-gradient(135deg, #ff758c, #ff7eb3); box-shadow: 0 4px 15px rgba(255, 117, 140, 0.5);"><i class="fas fa-video" style="font-size: 32px; margin-bottom: 8px; text-shadow: 0 2px 5px rgba(0,0,0,0.3);"></i><span data-translate-key="video_ads">Video Ads</span></a>
                    <a href="#" class="icon-item banner" data-target="ad-list-page-2" style="display: flex; flex-direction: column; align-items: center; justify-content: center; padding: 15px 10px; border-radius: 18px; text-decoration: none; text-align: center; cursor: pointer; color: var(--secondary-color); transition: transform 0.15s ease-out, box-shadow 0.15s ease-out; background: linear-gradient(135deg, #72afd3, #37ecba); box-shadow: 0 4px 15px rgba(114, 175, 211, 0.5);"><i class="fas fa-image" style="font-size: 32px; margin-bottom: 8px; text-shadow: 0 2px 5px rgba(0,0,0,0.3);"></i><span data-translate-key="banner_ads">Banner Ads</span></a>
                    <a href="#" class="icon-item task" data-target="ad-list-page-3" style="display: flex; flex-direction: column; align-items: center; justify-content: center; padding: 15px 10px; border-radius: 18px; text-decoration: none; text-align: center; cursor: pointer; color: var(--secondary-color); transition: transform 0.15s ease-out, box-shadow 0.15s ease-out; background: linear-gradient(135deg, #a8ff78, #78ffd6); box-shadow: 0 4px 15px rgba(168, 255, 120, 0.5);"><i class="fas fa-tasks" style="font-size: 32px; margin-bottom: 8px; text-shadow: 0 2px 5px rgba(0,0,0,0.3);"></i><span data-translate-key="tasks">Tasks</span></a>
                </div>
            </div>
            
            <a href="#" class="card store-entry-card" data-target="store-page">
                <div class="store-entry-icon">
                    <i class="fas fa-shopping-bag"></i>
                </div>
                <div class="store-entry-text">
                    <h3 data-translate-key="digital_store_entry_title">Digital Store</h3>
                    <p data-translate-key="digital_store_entry_desc">Use your balance for Netflix, Spotify & more.</p>
                </div>
                <div class="store-entry-cta">
                    <i class="fas fa-arrow-right"></i>
                </div>
            </a>

            <div class="card referral-card-professional">
                <div class="ref-header">
                    <h3 data-translate-key="refer_earn_title">Invite Friends, Earn Rewards</h3>
                    <p data-translate-key="refer_desc">Share your link to earn $0.05 for each new user + 3% of their task earnings!</p>
                </div>
                <div class="ref-body">
                    <div class="ref-qr-code">
                        <img id="referral-qr-img" src="" alt="Referral QR Code" width="100" height="100">
                    </div>
                    <div class="ref-details">
                        <div class="ref-stats">
                            <div class="ref-stat-item">
                                <span data-translate-key="referred_users">Referred Users</span>
                                <strong id="referred-users-count">0</strong>
                            </div>
                            <div class="ref-stat-item">
                                <span data-translate-key="referral_earnings">Referral Earnings</span>
                                <strong id="referral-earnings-total">$0.00</strong>
                            </div>
                        </div>
                        <div class="ref-link-group">
                            <label data-translate-key="your_ref_link">Your Referral Link</label>
                            <input type="text" id="referral-link-display" class="ref-link-input" readonly>
                        </div>
                        <div class="ref-actions">
                            <button id="copy-referral-link-btn" class="btn btn-secondary"><i class="fas fa-copy"></i><span data-translate-key="copy">Copy</span></button>
                            <button id="share-referral-link-btn" class="btn btn-primary"><i class="fas fa-share-alt"></i><span data-translate-key="share">Share</span></button>
                        </div>
                    </div>
                </div>
            </div>

            <div class="card">
                <button id="dashboard-packages-btn" class="btn btn-primary" style="background: var(--gold-gradient); color: black;"><i class="fas fa-rocket" style="margin-right: 8px;"></i> <span data-translate-key="creator_packages">Creator Growth Packages</span></button>
            </div>
            
            <div class="app-store-section">
                <h4>Soon on App Stores</h4>
                <div class="app-store-buttons">
                    <a href="#" class="app-store-btn app-store">
                        <svg viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M20.25 15.2C20.25 14.025 20.6 12.925 21.3 12.025C22.025 11.1 22.925 10.5 24.1 10.275C24 9.3 23.6 8.425 22.95 7.725C22.3 7.025 21.45 6.6 20.5 6.475C19.025 6.175 17.55 6.95 16.65 6.95C15.75 6.95 14.475 6.2 12.95 6.25C11.375 6.275 9.9 7.025 8.95 8.125C7.25 10.025 6.625 12.8 7.925 15.65C8.725 17.275 9.9 18.3 11.25 18.3C12.575 18.275 13.25 17.575 14.65 17.575C16.05 17.575 16.675 18.3 18.1 18.275C19.5 18.275 20.25 17.275 21.1 15.8C21.325 15.425 21.5 15.025 21.6 14.625L17.725 14.725C16.675 14.825 15.825 14.125 15.6 13.075C15.5 12.025 16.275 11.125 17.375 11.025L21.725 10.65C21.75 10.975 21.75 11.325 21.75 11.675C21.75 12.85 21.3 13.975 20.5 14.85" fill="white"></path><path d="M16 4.5C17.25 4.5 18.225 3.55 18.25 2.325C18.25 1.1 17.275 0.125 16.025 0.125C14.775 0.125 13.825 1.075 13.8 2.3C13.8 3.525 14.75 4.5 16 4.5Z" fill="white"></path></svg>
                        <div class="btn-text"><span>Download on the</span><span>App Store</span></div>
                    </a>
                    <a href="#" class="app-store-btn google-play">
                        <svg viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M22.9375 11.0625L6.5625 26.625L13.8125 19.3125L22.9375 11.0625Z" fill="#FFD966"></path><path d="M25.6875 13.625L23 11L13.8125 19.3125L16.5 22L25.6875 13.625Z" fill="#F4B183"></path><path d="M5.3125 2.875L6.5625 26.625L25.6875 13.625L5.3125 2.875Z" fill="#86E5FB"></path><path d="M5.3125 2.875L13.8125 19.3125L6.5625 26.625L5.3125 2.875Z" fill="#A9D08E"></path></svg>
                        <div class="btn-text"><span>GET IT ON</span><span>Google Play</span></div>
                    </a>
                </div>
            </div>
            
            <footer class="page-footer">
                <p>© 2025 Make Money & Traffic. All Rights Reserved.</p>
            </footer>
        </div>

        <!-- Digital Store Page -->
        <div id="store-page" class="page">
            <h1 class="page-title"><a href="#" class="back-btn" data-target="dashboard-page"><i class="fas fa-arrow-left"></i></a><span data-translate-key="digital_store_title">Digital Services Store</span></h1>
            
            <p style="text-align: center; margin-bottom: 25px; font-size:14px; color: var(--secondary-color); text-shadow: 1px 1px 2px rgba(0,0,0,0.2);" data-translate-key="digital_store_subtitle">Get your favorite subscriptions using your balance.</p>

            <div id="digital-services-section">
                <h2 class="section-title" data-translate-key="digital_services">Digital Services</h2>
                <div id="digital-store-grid" class="store-grid">
                    <!-- Digital products will be populated by JS -->
                </div>
            </div>

            <div id="community-marketplace-section" style="margin-top: 40px;">
                <h2 class="section-title" data-translate-key="community_marketplace">Community Marketplace</h2>
                <div id="community-store-grid" class="store-grid">
                    <!-- User-created products will be populated by JS -->
                </div>
            </div>
        </div>
        
        <!-- My Store Page (for Sellers) -->
        <div id="my-store-page" class="page">
            <h1 class="page-title"><a href="#" class="back-btn" data-target="profile-page"><i class="fas fa-arrow-left"></i></a><span data-translate-key="my_store">My Store</span></h1>
            <div class="card">
                <h3 data-translate-key="store_details">Store Details</h3>
                <form id="my-store-form">
                    <div class="form-group">
                        <label for="my-store-name" data-translate-key="store_name">Store Name</label>
                        <input type="text" id="my-store-name" required>
                    </div>
                    <div class="form-group">
                        <label for="my-store-description" data-translate-key="store_description">Store Description</label>
                        <textarea id="my-store-description"></textarea>
                    </div>
                    <button type="submit" class="btn btn-primary" data-translate-key="save_store_details">Save Store Details</button>
                </form>
            </div>
            <div class="card">
                <div style="display:flex; justify-content: space-between; align-items: center; margin-bottom: 20px;">
                    <h3 style="margin:0;" data-translate-key="my_products">My Products</h3>
                    <button id="add-product-btn" class="btn btn-primary" style="width: auto; padding: 10px 15px;"><i class="fas fa-plus" style="margin-right: 8px;"></i> <span data-translate-key="add_product">Add Product</span></button>
                </div>
                <ul id="my-products-list">
                    <!-- Seller's products will be populated by JS -->
                </ul>
            </div>
        </div>


        <!-- Ad List Pages -->
        <div id="ad-list-page-1" class="page"><h1 class="page-title"><a href="#" class="back-btn" data-target="dashboard-page"><i class="fas fa-arrow-left"></i></a><span data-translate-key="video_ads">Video Ads</span></h1><ul id="ad-list-1" class="ad-list-container"></ul></div>
        <div id="ad-list-page-2" class="page"><h1 class="page-title"><a href="#" class="back-btn" data-target="dashboard-page"><i class="fas fa-arrow-left"></i></a><span data-translate-key="banner_ads">Banner Ads</span></h1><ul id="ad-list-2" class="ad-list-container"></ul></div>
        <div id="ad-list-page-3" class="page"><h1 class="page-title"><a href="#" class="back-btn" data-target="dashboard-page"><i class="fas fa-arrow-left"></i></a><span data-translate-key="tasks">Interactive Tasks</span></h1><ul id="ad-list-3" class="ad-list-container"></ul></div>

        <!-- Watch Ad Page -->
        <div id="watch-ad-page" class="page"><h1 class="page-title"><a href="#" id="watch-ad-back-btn" class="back-btn" data-target=""><i class="fas fa-arrow-left"></i></a><span data-translate-key="watch_earn_title">Watch & Earn</span></h1><div id="ad-container" class="card"><i class="fas fa-play-circle" style="font-size: 48px; color: var(--primary-color);"></i><p style="margin-top:15px; color: var(--text-color);" data-translate-key="ad_loading">Your ad is loading...</p></div><div id="timer-display" style="font-size: 24px; font-weight: 600; text-align: center; margin-bottom: 25px; color: var(--text-color);"><p><span data-translate-key="time_remaining">Time remaining:</span> <span id="countdown">30</span>s</p></div><button id="claim-reward-btn" class="btn btn-primary" style="display:none;" data-translate-key="claim_reward">Claim Reward</button></div>

        <!-- History Page -->
        <div id="history-page" class="page"><h1 class="page-title" data-translate-key="history">History</h1><ul id="history-list" style="padding:0;"></ul><p id="no-history-message" class="no-history" style="display:none; text-align:center; color: #fff; text-shadow: 1px 1px 2px #000;" data-translate-key="no_history">No transactions yet.</p></div>

        <!-- Deposit Page -->
        <div id="deposit-page" class="page">
            <h1 class="page-title" data-translate-key="deposit_funds">Deposit Funds</h1>
            <div class="card">
                <h3 style="font-size:18px; margin-bottom: 15px; text-align: center;" data-translate-key="select_method">1. Select Deposit Method</h3>
                <div id="deposit-methods-grid" class="methods-grid">
                    <div class="method-card cih" data-method="cih"><i class="fas fa-university"></i><span>CIH Bank</span></div>
                    <div class="method-card paypal" data-method="paypal"><i class="fab fa-paypal"></i><span>PayPal</span></div>
                    <div class="method-card payeer" data-method="payeer"><i class="fas fa-credit-card"></i><span>Payeer</span></div>
                    <div class="method-card usdt" data-method="usdt-trc20"><i class="fas fa-coins"></i><span>USDT TRC20</span></div>
                    <div class="method-card usdt" data-method="usdt-bep20"><i class="fas fa-coins"></i><span>USDT BEP20</span></div>
                    <div class="method-card binance-pay" data-method="binance-pay"><i class="fas fa-wallet"></i><span>Binance Pay</span></div>
                    <div class="method-card wise" data-method="wise"><i class="fas fa-money-bill-transfer"></i><span>Wise</span></div>
                    <div class="method-card skrill" data-method="skrill"><i class="fab fa-skrill"></i><span>Skrill</span></div>
                    <div class="method-card perfect-money" data-method="perfect-money"><i class="fas fa-star"></i><span>Perfect Money</span></div>
                    <div class="method-card bitcoin" data-method="bitcoin"><i class="fab fa-bitcoin"></i><span>Bitcoin</span></div>
                    <div class="method-card pi-network" data-method="pi-network"><i class="fas fa-pi"></i><span>Pi Network</span></div>
                </div>
                <div id="payment-details-form" style="display:none;">
                    <hr style="border-top:1px solid rgba(255,255,255,0.4); margin: 25px 0;">
                    <h3 style="font-size:18px; margin-bottom: 15px; text-align: center;" data-translate-key="enter_details">2. Enter Details</h3>
                    <form id="deposit-form">
                        <div class="form-group"><label for="deposit-amount" data-translate-key="amount_usd">Amount (USD)</label><input type="number" id="deposit-amount" step="0.01" min="10" data-translate-placeholder-key="min_deposit" placeholder="Minimum $10.00" required></div>
                        <p id="deposit-instructions" style="color: var(--text-color); background-color: rgba(255, 255, 255, 0.5); padding: 10px; border-radius: 8px; margin-bottom: 20px; display:none; white-space: pre-wrap; word-wrap: break-word;"></p>
                        <div id="qr-code-container" style="display:none; text-align:center; margin: 20px 0;"><img id="qr-code-img" src="" alt="Scan QR Code to Pay"></div>
                        <div id="cih-screenshot-upload-group" class="form-group" style="display:none;"><label for="cih-screenshot-upload" class="btn btn-secondary"><i class="fas fa-camera" style="margin-right: 8px;"></i>Upload Transfer Screenshot</label><input type="file" id="cih-screenshot-upload" accept="image/*" style="display: none;"><p id="screenshot-filename"></p></div>
                        <button type="submit" id="confirm-deposit-btn" class="btn btn-primary" data-translate-key="confirm_deposit">Confirm Deposit</button>
                    </form>
                    <div id="deposit-timer-display" style="display: none;">
                        <i class="fas fa-hourglass-half"></i> <span data-translate-key="session_expires_in">Session expires in:</span> <span id="deposit-countdown">60:00</span>
                    </div>
                </div>
            </div>
        </div>

        <!-- Withdraw Page -->
        <div id="withdraw-page" class="page">
            <h1 class="page-title" data-translate-key="withdraw_funds">Withdraw Funds</h1>
            <div class="card">
                <h3 style="font-size:18px; margin-bottom: 15px; text-align: center;" data-translate-key="select_method">1. Select Withdrawal Method</h3>
                <div id="withdraw-methods-grid" class="methods-grid">
                    <div class="method-card cih" data-method="cih"><i class="fas fa-university"></i><span>CIH Bank</span></div>
                    <div class="method-card paypal" data-method="paypal"><i class="fab fa-paypal"></i><span>PayPal</span></div>
                    <div class="method-card payeer" data-method="payeer"><i class="fas fa-credit-card"></i><span>Payeer</span></div>
                    <div class="method-card usdt" data-method="usdt-trc20"><i class="fas fa-coins"></i><span>USDT TRC20</span></div>
                    <div class="method-card usdt" data-method="usdt-bep20"><i class="fas fa-coins"></i><span>USDT BEP20</span></div>
                    <div class="method-card binance-pay" data-method="binance-pay"><i class="fas fa-wallet"></i><span>Binance Pay</span></div>
                    <div class="method-card wise" data-method="wise"><i class="fas fa-money-bill-transfer"></i><span>Wise</span></div>
                    <div class="method-card skrill" data-method="skrill"><i class="fab fa-skrill"></i><span>Skrill</span></div>
                    <div class="method-card perfect-money" data-method="perfect-money"><i class="fas fa-star"></i><span>Perfect Money</span></div>
                    <div class="method-card bitcoin" data-method="bitcoin"><i class="fab fa-bitcoin"></i><span>Bitcoin</span></div>
                    <div class="method-card pi-network" data-method="pi-network"><i class="fas fa-pi"></i><span>Pi Network</span></div>
                </div>
                <div id="withdrawal-details-form" style="display:none;"><hr style="border-top:1px solid rgba(255,255,255,0.4); margin: 25px 0;"><h3 style="font-size:18px; margin-bottom: 15px; text-align: center;" data-translate-key="enter_details_amount">2. Enter Details & Amount</h3><form id="withdraw-form"><div id="cih-fields" class="specific-fields"><div class="form-group"><label for="cih-name">Full Name</label><input type="text" id="cih-name"></div><div class="form-group"><label for="cih-account">Account Number (RIB)</label><input type="text" id="cih-account" placeholder="24 digits"></div></div><div id="paypal-fields" class="specific-fields"><div class="form-group"><label for="paypal-email">PayPal Email</label><input type="email" id="paypal-email"></div></div><div id="payeer-fields" class="specific-fields"><div class="form-group"><label for="payeer-account">Payeer Account</label><input type="text" id="payeer-account" placeholder="P12345678"></div></div><div id="usdt-trc20-fields" class="specific-fields"><div class="form-group"><label for="usdt-trc20-address">USDT Address (TRC20)</label><input type="text" id="usdt-trc20-address"></div></div><div id="usdt-bep20-fields" class="specific-fields"><div class="form-group"><label for="usdt-bep20-address">USDT Address (BEP20)</label><input type="text" id="usdt-bep20-address"></div></div><div id="binance-pay-fields" class="specific-fields"><div class="form-group"><label for="binance-pay-id">Binance Pay ID</label><input type="text" id="binance-pay-id"></div></div><div id="wise-fields" class="specific-fields"><div class="form-group"><label for="wise-email">Wise Email</label><input type="email" id="wise-email"></div></div><div id="skrill-fields" class="specific-fields"><div class="form-group"><label for="skrill-email">Skrill Email</label><input type="email" id="skrill-email"></div></div><div id="perfect-money-fields" class="specific-fields"><div class="form-group"><label for="pm-account">Perfect Money Account</label><input type="text" id="pm-account" placeholder="U12345678"></div></div><div id="bitcoin-fields" class="specific-fields"><div class="form-group"><label for="btc-address">Bitcoin (BTC) Address</label><input type="text" id="btc-address"></div></div><div id="pi-network-fields" class="specific-fields"><div class="form-group"><label for="pi-address">Pi Wallet Address</label><input type="text" id="pi-address"></div></div><div class="form-group"><label for="withdraw-amount" data-translate-key="amount_usd">Amount (USD)</label><input type="number" id="withdraw-amount" step="0.01" min="5" data-translate-placeholder-key="min_withdraw" placeholder="Minimum $5.00" required></div><button type="submit" class="btn btn-primary" data-translate-key="request_withdrawal">Request Withdrawal</button></form></div>
            </div>
        </div>

        <!-- Profile Page -->
        <div id="profile-page" class="page">
            <h1 class="page-title" style="padding-bottom: 0; margin-bottom: 0;" data-translate-key="my_profile">My Profile</h1>
            
            <div id="profile-header">
                <div id="profile-picture-container">
                    <img id="profile-picture" src="" alt="Profile Picture">
                    <label for="profile-picture-upload" id="profile-picture-upload-label"><i class="fas fa-camera"></i></label>
                    <input type="file" id="profile-picture-upload" accept="image/*" style="display: none;">
                </div>
                <div id="profile-identity">
                    <h2 id="profile-name-display"></h2>
                    <span id="profile-badge-container"></span>
                </div>
                <div id="profile-balance-display">
                    <p data-translate-key="account_balance">Account Balance</p>
                    <h2 id="profile-balance-value">$0.00</h2>
                </div>
            </div>
            
            <div id="profile-actions-container">
                <button id="become-seller-btn" class="btn btn-secondary" style="display: none;"><i class="fas fa-store" style="margin-right: 8px;"></i> <span data-translate-key="become_a_seller">Become a Seller</span></button>
                <button id="go-to-my-store-btn" class="btn btn-primary" style="display: none;"><i class="fas fa-store-alt" style="margin-right: 8px;"></i> <span data-translate-key="manage_my_store">Manage My Store</span></button>
                <button id="profile-packages-btn" class="btn btn-primary" style="background: var(--gold-gradient); color: black;"><i class="fas fa-rocket" style="margin-right: 8px;"></i> <span data-translate-key="creator_packages">Creator Growth Packages</span></button>
                <a href="#" id="show-publishers-link" class="btn btn-secondary"><span data-translate-key="publisher_q">Are you a Publisher? Advertise with Us</span> <i class="fas fa-arrow-right"></i></a>
            </div>

            <div class="card">
                <form id="profile-form">
                    <div class="form-group"><label for="profile-name" data-translate-key="full_name">Full Name</label><input type="text" id="profile-name" required></div>
                    <div class="form-group"><label for="profile-email" data-translate-key="email">Email</label><input type="email" id="profile-email" disabled></div>
                    <div class="form-group"><label for="profile-phone" data-translate-key="phone_number">Phone Number</label><input type="tel" id="profile-phone"></div>
                    <div class="form-group"><label for="profile-dob" data-translate-key="date_of_birth">Date of Birth</label><input type="date" id="profile-dob"></div>
                    <div class="form-group"><label for="profile-gender" data-translate-key="gender">Gender</label><select id="profile-gender"><option value="" data-translate-key="select_gender">-- Select --</option><option value="male" data-translate-key="male">Male</option><option value="female" data-translate-key="female">Female</option></select></div>
                    <div class="form-group"><label for="profile-address" data-translate-key="address">Address</label><textarea id="profile-address"></textarea></div>
                    <hr style="border-top:1px solid rgba(255,255,255,0.4); margin: 25px 0;">
                    <h3 style="font-size: 18px; margin-bottom: 15px;" data-translate-key="change_password">Change Password</h3>
                    <div class="form-group"><label for="profile-old-password" data-translate-key="old_password">Old Password</label><input type="password" id="profile-old-password" data-translate-placeholder-key="old_pass_placeholder" placeholder="Enter old password to change"></div>
                    <div class="form-group"><label for="profile-new-password" data-translate-key="new_password">New Password</label><input type="password" id="profile-new-password" data-translate-placeholder-key="new_pass_placeholder" placeholder="Leave blank to keep current"></div>
                    <button type="submit" class="btn btn-primary" data-translate-key="save_changes">Save Changes</button>
                </form>
            </div>
            
            <button id="logout-btn" class="btn" style="background-color: var(--error-color); color:white; margin-top:20px;" data-translate-key="logout">Logout</button>
            
            <div class="app-store-section">
                <h4>Coming Soon</h4>
                <div class="app-store-buttons">
                    <a href="#" class="app-store-btn app-store">
                        <svg viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M20.25 15.2C20.25 14.025 20.6 12.925 21.3 12.025C22.025 11.1 22.925 10.5 24.1 10.275C24 9.3 23.6 8.425 22.95 7.725C22.3 7.025 21.45 6.6 20.5 6.475C19.025 6.175 17.55 6.95 16.65 6.95C15.75 6.95 14.475 6.2 12.95 6.25C11.375 6.275 9.9 7.025 8.95 8.125C7.25 10.025 6.625 12.8 7.925 15.65C8.725 17.275 9.9 18.3 11.25 18.3C12.575 18.275 13.25 17.575 14.65 17.575C16.05 17.575 16.675 18.3 18.1 18.275C19.5 18.275 20.25 17.275 21.1 15.8C21.325 15.425 21.5 15.025 21.6 14.625L17.725 14.725C16.675 14.825 15.825 14.125 15.6 13.075C15.5 12.025 16.275 11.125 17.375 11.025L21.725 10.65C21.75 10.975 21.75 11.325 21.75 11.675C21.75 12.85 21.3 13.975 20.5 14.85" fill="white"></path><path d="M16 4.5C17.25 4.5 18.225 3.55 18.25 2.325C18.25 1.1 17.275 0.125 16.025 0.125C14.775 0.125 13.825 1.075 13.8 2.3C13.8 3.525 14.75 4.5 16 4.5Z" fill="white"></path></svg>
                        <div class="btn-text"><span>Download on the</span><span>App Store</span></div>
                    </a>
                    <a href="#" class="app-store-btn google-play">
                        <svg viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M22.9375 11.0625L6.5625 26.625L13.8125 19.3125L22.9375 11.0625Z" fill="#FFD966"></path><path d="M25.6875 13.625L23 11L13.8125 19.3125L16.5 22L25.6875 13.625Z" fill="#F4B183"></path><path d="M5.3125 2.875L6.5625 26.625L25.6875 13.625L5.3125 2.875Z" fill="#86E5FB"></path><path d="M5.3125 2.875L13.8125 19.3125L6.5625 26.625L5.3125 2.875Z" fill="#A9D08E"></path></svg>
                        <div class="btn-text"><span>GET IT ON</span><span>Google Play</span></div>
                    </a>
                </div>
            </div>

            <footer class="page-footer">
                <p>© 2025 Make Money & Traffic. All Rights Reserved.</p>
            </footer>
        </div>
        
        <!-- Creator Packages Page -->
        <div id="packages-page" class="page">
            <h1 class="page-title"><a href="#" class="back-btn" data-target="profile-page"><i class="fas fa-arrow-left"></i></a><span data-translate-key="creator_packages">Creator Packages</span></h1>
            
            <div class="card package-card" data-package="youtube">
                <div class="friday-deal-banner">🎉 Friday Deal!</div>
                <div class="package-hero-icon-container"><i class="fab fa-youtube"></i></div>
                <div class="package-card-header"><h2 data-translate-key="youtube_growth">YouTube Growth</h2></div>
                <div class="package-card-body">
                    <div class="package-buy-view">
                        <ul class="package-features-list">
                            <li><i class="fas fa-check-circle"></i><span data-translate-key="pkg_auth_eng">Authentic Engagement</span><span class="feature-quantity" data-translate-key="pkg_real_users">Real Users</span></li>
                            <li><i class="fas fa-eye"></i><span data-translate-key="pkg_views">Real Views</span><span class="feature-quantity">~45,000</span></li>
                            <li><i class="fas fa-thumbs-up"></i><span data-translate-key="pkg_likes">Post Likes</span><span class="feature-quantity">~2,000</span></li>
                            <li><i class="fas fa-user-plus"></i><span data-translate-key="pkg_subs">Subscribers</span><span class="feature-quantity">~1,000</span></li>
                            <li><i class="fas fa-comment"></i><span data-translate-key="pkg_comments">Comments</span><span class="feature-quantity">~500</span></li>
                        </ul>
                        <div class="monetization-requirements">
                            <h4 data-translate-key="monetization_req_title">Monetization Requirements</h4>
                            <ul>
                                <li><i class="fas fa-user-friends"></i> <span data-translate-key="youtube_req_1">1,000 Subscribers</span></li>
                                <li><i class="fas fa-clock"></i> <span data-translate-key="youtube_req_2">4,000 Watch Hours</span></li>
                            </ul>
                        </div>
                        <div class="price-container"><span class="original-price">$100.00</span><span class="final-price">$100.00</span><span class="discount-badge"></span></div>
                        <button class="btn btn-primary buy-package-btn" data-translate-key="buy_package">Buy Package</button>
                    </div>
                    <div class="package-progress-container"></div>
                    <div class="package-complete-message"></div>
                </div>
            </div>

            <div class="card package-card" data-package="facebook">
                <div class="friday-deal-banner">🎉 Friday Deal!</div>
                <div class="package-hero-icon-container"><i class="fab fa-facebook"></i></div>
                <div class="package-card-header"><h2 data-translate-key="facebook_expansion">Facebook Expansion</h2></div>
                <div class="package-card-body">
                    <div class="package-buy-view">
                        <ul class="package-features-list">
                            <li><i class="fas fa-check-circle"></i><span data-translate-key="pkg_community_bld">Community Building</span><span class="feature-quantity" data-translate-key="pkg_real_users">Real Users</span></li>
                            <li><i class="fas fa-user-plus"></i><span data-translate-key="pkg_followers">Followers</span><span class="feature-quantity">~10,000</span></li>
                            <li><i class="fas fa-thumbs-up"></i><span data-translate-key="pkg_page_likes">Page/Post Likes</span><span class="feature-quantity">~80,000</span></li>
                            <li><i class="fas fa-comment"></i><span data-translate-key="pkg_comments">Comments</span><span class="feature-quantity">~5,000</span></li>
                        </ul>
                        <div class="monetization-requirements">
                            <h4 data-translate-key="monetization_req_title">Monetization Requirements</h4>
                            <ul>
                                <li><i class="fas fa-user-friends"></i> <span data-translate-key="facebook_req_1">10,000 Followers</span></li>
                                <li><i class="fas fa-play-circle"></i> <span data-translate-key="facebook_req_2">600k Watch Minutes</span></li>
                            </ul>
                        </div>
                        <div class="price-container"><span class="original-price">$100.00</span><span class="final-price">$100.00</span><span class="discount-badge"></span></div>
                        <button class="btn btn-primary buy-package-btn" data-translate-key="buy_package">Buy Package</button>
                    </div>
                    <div class="package-progress-container"></div>
                    <div class="package-complete-message"></div>
                </div>
            </div>
            
            <div class="card package-card" data-package="tiktok">
                <div class="friday-deal-banner">🎉 Friday Deal!</div>
                <div class="package-hero-icon-container"><i class="fab fa-tiktok"></i></div>
                <div class="package-card-header"><h2 data-translate-key="tiktok_boost">TikTok Viral Boost</h2></div>
                <div class="package-card-body">
                    <div class="package-buy-view">
                         <ul class="package-features-list">
                            <li><i class="fas fa-check-circle"></i><span data-translate-key="pkg_viral_pot">Viral Potential</span><span class="feature-quantity" data-translate-key="pkg_real_users">Real Users</span></li>
                            <li><i class="fas fa-user-plus"></i><span data-translate-key="pkg_followers">Followers</span><span class="feature-quantity">~10,000</span></li>
                            <li><i class="fas fa-heart"></i><span data-translate-key="pkg_video_likes">Video Likes</span><span class="feature-quantity">~80,000</span></li>
                             <li><i class="fas fa-share"></i><span data-translate-key="pkg_shares_comments">Shares & Comments</span><span class="feature-quantity">~5,000</span></li>
                        </ul>
                        <div class="monetization-requirements">
                            <h4 data-translate-key="monetization_req_title">Monetization Requirements</h4>
                            <ul>
                                <li><i class="fas fa-user-friends"></i> <span data-translate-key="tiktok_req_1">10,000 Followers</span></li>
                                <li><i class="fas fa-eye"></i> <span data-translate-key="tiktok_req_2">100k Views (30 days)</span></li>
                            </ul>
                        </div>
                        <div class="price-container"><span class="original-price">$100.00</span><span class="final-price">$100.00</span><span class="discount-badge"></span></div>
                        <button class="btn btn-primary buy-package-btn" data-translate-key="buy_package">Buy Package</button>
                    </div>
                    <div class="package-progress-container"></div>
                    <div class="package-complete-message"></div>
                </div>
            </div>

            <div class="card package-card" data-package="instagram">
                <div class="friday-deal-banner">🎉 Friday Deal!</div>
                <div class="package-hero-icon-container"><i class="fab fa-instagram"></i></div>
                <div class="package-card-header"><h2 data-translate-key="instagram_push">Instagram Profile Push</h2></div>
                <div class="package-card-body">
                    <div class="package-buy-view">
                         <ul class="package-features-list">
                            <li><i class="fas fa-check-circle"></i><span data-translate-key="pkg_profile_growth">Profile Growth</span><span class="feature-quantity" data-translate-key="pkg_real_users">Real Users</span></li>
                            <li><i class="fas fa-user-plus"></i><span data-translate-key="pkg_followers">Followers</span><span class="feature-quantity">~10,000</span></li>
                            <li><i class="fas fa-heart"></i><span data-translate-key="pkg_likes">Post Likes</span><span class="feature-quantity">~80,000</span></li>
                             <li><i class="fas fa-comment"></i><span data-translate-key="pkg_comments">Comments</span><span class="feature-quantity">~5,000</span></li>
                        </ul>
                        <div class="monetization-requirements">
                            <h4 data-translate-key="monetization_req_title">Monetization Requirements</h4>
                            <ul>
                                <li><i class="fas fa-user-friends"></i> <span data-translate-key="instagram_req_1">10,000 Followers</span></li>
                                <li><i class="fas fa-chart-line"></i> <span data-translate-key="instagram_req_2">Active Engagement</span></li>
                            </ul>
                        </div>
                        <div class="price-container"><span class="original-price">$100.00</span><span class="final-price">$100.00</span><span class="discount-badge"></span></div>
                        <button class="btn btn-primary buy-package-btn" data-translate-key="buy_package">Buy Package</button>
                    </div>
                    <div class="package-progress-container"></div>
                    <div class="package-complete-message"></div>
                </div>
            </div>
        </div>

        <!-- Publishers Page -->
        <div id="publishers-page" class="page">
            <h1 class="page-title"><a href="#" class="back-btn" data-target="profile-page"><i class="fas fa-arrow-left"></i></a><span data-translate-key="advertise_with_us">Advertise With Us</span></h1>
            <div class="card">
                <h3 style="text-align: center; margin-bottom: 15px;" data-translate-key="create_campaign_title">Create Your Ad Campaign</h3>
                <p style="text-align: center; line-height: 1.6; margin-bottom: 20px;" data-translate-key="create_campaign_desc">
                    Reach a broad and engaged audience by creating your own ad campaigns. You can launch targeted video ads, banner ads, or interactive tasks to drive traffic and engagement. Start now for as little as $1.00!
                </p>
                <div style="margin-top: 20px;">
                    <button id="go-to-create-ad-btn" class="btn btn-primary">
                        <i class="fas fa-plus" style="margin-right:8px;"></i> 
                        <span data-translate-key="create_campaign_now">Create Campaign Now</span>
                    </button>
                </div>
            </div>
            <div class="card">
                <h3 style="text-align: center; margin-bottom: 15px;" data-translate-key="creator_packages_title">All-in-One Growth Packages</h3>
                <p style="text-align: center; line-height: 1.6; margin-bottom: 20px;" data-translate-key="creator_packages_desc">
                    If you're looking to meet monetization requirements on platforms like YouTube or Facebook, our comprehensive growth packages are the perfect solution. We handle the complexity, you get the results.
                </p>
                <div style="margin-top: 20px;">
                    <button class="btn btn-secondary" id="publishers-view-packages-btn">
                        <i class="fas fa-rocket" style="margin-right:8px;"></i> 
                        <span data-translate-key="view_growth_packages">View Growth Packages</span>
                    </button>
                </div>
            </div>
        </div>

        <!-- Create Ad Page -->
        <div id="create-ad-page" class="page">
            <h1 class="page-title"><a href="#" class="back-btn" data-target="publishers-page"><i class="fas fa-arrow-left"></i></a><span data-translate-key="create_ad_campaign_title">Create Ad Campaign</span></h1>
            <div class="card">
                <form id="create-ad-form">
                    <div class="form-group">
                        <label for="ad-type-select" data-translate-key="ad_type">Ad Type</label>
                        <select id="ad-type-select" required>
                            <option value="" data-translate-key="select_one">-- Select --</option>
                            <option value="video" data-translate-key="video_ad">Video Ad</option>
                            <option value="banner" data-translate-key="banner_ad">Banner Ad</option>
                            <option value="task" data-translate-key="interactive_task">Interactive Task</option>
                        </select>
                    </div>
                    <div id="video-ad-fields" class="specific-ad-fields" style="display:none;">
                        <div class="form-group"><label for="video-title" data-translate-key="video_title_url">Video Title / URL</label><input type="text" id="video-title"></div>
                    </div>
                    <div id="banner-ad-fields" class="specific-ad-fields" style="display:none;">
                        <div class="form-group"><label for="banner-title" data-translate-key="banner_title">Banner Title</label><input type="text" id="banner-title"></div>
                    </div>
                    <div id="task-ad-fields" class="specific-ad-fields" style="display:none;">
                        <div class="form-group">
                            <label for="task-platform" data-translate-key="platform">Platform</label>
                            <select id="task-platform">
                                <option value="YouTube">YouTube</option><option value="Facebook">Facebook</option>
                                <option value="TikTok">TikTok</option><option value="Instagram">Instagram</option>
                            </select>
                        </div>
                        <div class="form-group"><label for="task-target" data-translate-key="target_url">Target URL</label><input type="text" id="task-target"></div>
                        <div class="form-group">
                            <label for="task-action" data-translate-key="action">Action</label>
                            <select id="task-action">
                                <option value="Subscribe">Subscribe</option><option value="Follow">Follow</option>
                                <option value="Like">Like</option><option value="Comment">Comment</option>
                            </select>
                        </div>
                    </div>
                    <hr style="border-top:1px solid rgba(255,255,255,0.4); margin: 25px 0;">
                    <div class="form-group"><label for="campaign-budget" data-translate-key="campaign_budget">Campaign Budget ($)</label><input type="number" id="campaign-budget" min="1" step="0.5" placeholder="Minimum $1.00" required></div>
                    <div class="form-group"><label for="reward-per-action" data-translate-key="reward_per_action">Reward per Interaction ($)</label><input type="number" id="reward-per-action" min="0.001" step="0.001" placeholder="e.g., 0.01" required></div>
                    <div class="reach-display" data-translate-key="estimated_reach">Estimated Reach: <span id="estimated-reach">---</span> users</div>
                    <div class="terms-agreement"><input type="checkbox" id="terms-checkbox"><label for="terms-checkbox" data-translate-key="terms_agreement">I agree to the terms and take responsibility for the content.</label></div>
                    <button type="submit" id="create-ad-submit-btn" class="btn btn-primary" disabled data-translate-key="create_publish_campaign">Create & Publish Campaign</button>
                </form>
            </div>
        </div>
    </div>
    
    <div id="chat-fab" class="fab">
        <i class="fas fa-comments"></i>
        <span id="chat-unread-count" class="fab-unread-count" style="display: none;">0</span>
    </div>
    <div id="support-fab" class="fab">
        <i class="fas fa-headset"></i>
        <span id="support-unread-count" class="fab-unread-count" style="display: none;">0</span>
    </div>

    <!-- Modals -->
    <div id="package-modal" class="modal-overlay">
        <div class="modal-content">
            <div class="modal-header">
                <h2 id="modal-title"></h2>
                <button class="modal-close-btn">×</button>
            </div>
            <div class="modal-body">
                <form id="package-purchase-form">
                    <div class="form-group">
                        <label id="package-url-page-label" for="package-url-page">Channel/Page URL</label>
                        <input type="url" id="package-url-page" required>
                    </div>
                    <div class="form-group">
                        <label for="package-url-video1">Video URL 1</label>
                        <input type="url" id="package-url-video1" placeholder="https://..." required>
                    </div>
                     <div class="form-group">
                        <label for="package-url-video2">Video URL 2</label>
                        <input type="url" id="package-url-video2" placeholder="https://..." required>
                    </div>
                     <div class="form-group">
                        <label for="package-url-video3">Video URL 3</label>
                        <input type="url" id="package-url-video3" placeholder="https://..." required>
                    </div>
                    <p style="font-size: 14px; color: var(--text-light-color); margin-top: -5px; margin-bottom: 20px;" data-translate-key="pkg_purchase_desc">Your campaign will be automatically optimized with a mix of interactions to ensure natural growth.</p>
                    <button type="submit" id="confirm-package-purchase-btn" class="btn btn-primary" data-translate-key="confirm_pkg_purchase">Confirm & Start Campaign</button>
                </form>
            </div>
        </div>
    </div>

    <div id="add-product-modal" class="modal-overlay">
        <div class="modal-content">
            <div class="modal-header">
                <h2 data-translate-key="add_new_product">Add New Product</h2>
                <button class="modal-close-btn">×</button>
            </div>
            <div class="modal-body">
                <form id="add-product-form">
                    <div class="form-group">
                        <label for="product-name-input" data-translate-key="product_name">Product Name</label>
                        <input type="text" id="product-name-input" required>
                    </div>
                    <div class="form-group">
                        <label for="product-description-input" data-translate-key="product_description">Product Description</label>
                        <textarea id="product-description-input" required></textarea>
                    </div>
                    <div class="form-group">
                        <label for="product-price-input" data-translate-key="product_price">Price (USD)</label>
                        <input type="number" id="product-price-input" step="0.01" min="0.5" required>
                    </div>
                    <div class="form-group">
                        <label for="product-image-url-input" data-translate-key="product_image_url">Image URL</label>
                        <input type="url" id="product-image-url-input" placeholder="https://example.com/image.png" required>
                    </div>
                    <button type="submit" class="btn btn-primary" data-translate-key="add_product">Add Product</button>
                </form>
            </div>
        </div>
    </div>
    
    <div id="kyc-modal" class="modal-overlay">
        <div class="modal-content">
            <div class="modal-header">
                <h2 id="kyc-modal-title" data-translate-key="kyc_verification">KYC Verification</h2>
                <button id="kyc-modal-close-btn" class="modal-close-btn">×</button>
            </div>
            <div class="modal-body">
                <div id="kyc-step-intro" class="kyc-step active">
                    <i class="fas fa-shield-alt kyc-step-icon"></i>
                    <h3 data-translate-key="kyc_secure_process">Secure Verification Process</h3>
                    <p data-translate-key="kyc_intro_desc">To ensure the security of our community, we need to verify your identity. Please have your official ID card ready.</p>
                    <button id="kyc-begin-btn" class="btn btn-primary" data-translate-key="kyc_begin_verification">Begin Verification</button>
                </div>
                <div id="kyc-step-front" class="kyc-step">
                    <h3 data-translate-key="kyc_step_1">Step 1: Front of ID</h3>
                    <p data-translate-key="kyc_front_desc">Please upload a clear image of the front of your ID card.</p>
                    <label for="kyc-id-front-upload" class="kyc-upload-box">
                        <img id="id-front-preview" class="kyc-image-preview" style="display:none;">
                        <i class="fas fa-id-card"></i>
                        <span data-translate-key="kyc_click_to_upload">Click to Upload</span>
                    </label>
                    <input type="file" id="kyc-id-front-upload" accept="image/*">
                    <button id="kyc-next-btn" class="btn btn-primary" disabled data-translate-key="next">Next</button>
                </div>
                <div id="kyc-step-back" class="kyc-step">
                    <h3 data-translate-key="kyc_step_2">Step 2: Back of ID</h3>
                    <p data-translate-key="kyc_back_desc">Now, please upload a clear image of the back of your ID card.</p>
                    <label for="kyc-id-back-upload" class="kyc-upload-box">
                        <img id="id-back-preview" class="kyc-image-preview" style="display:none;">
                        <i class="fas fa-id-card-alt"></i>
                        <span data-translate-key="kyc_click_to_upload">Click to Upload</span>
                    </label>
                    <input type="file" id="kyc-id-back-upload" accept="image/*">
                    <button id="kyc-submit-btn" class="btn btn-primary" disabled data-translate-key="submit_for_review">Submit for Review</button>
                </div>
                <div id="kyc-step-pending" class="kyc-step">
                    <div class="kyc-loader"></div>
                    <h3 data-translate-key="kyc_processing">Processing Verification</h3>
                    <p data-translate-key="kyc_pending_desc">Your documents have been submitted and are under review. This may take a few moments.</p>
                </div>
                <div id="kyc-step-verified" class="kyc-step">
                    <i class="fas fa-check-circle kyc-step-icon" style="color: var(--success-color);"></i>
                    <h3 data-translate-key="kyc_verified_title">Verification Complete!</h3>
                    <p data-translate-key="kyc_verified_desc">Your account is now fully verified. Thank you for your cooperation.</p>
                    <button id="kyc-done-btn" class="btn btn-primary" data-translate-key="done">Done</button>
                </div>
            </div>
        </div>
    </div>

    <div id="chat-modal" class="modal-overlay chat-modal-class">
        <div class="modal-content">
            <div class="modal-header chat-header-class">
                <h2 data-translate-key="chat_title">Global Chat</h2>
                <button id="chat-modal-close-btn" class="modal-close-btn">×</button>
            </div>
            <div id="chat-messages-container" class="chat-messages-container-class"></div>
            <form id="chat-input-form" class="chat-input-form-class">
                <input type="text" id="chat-input" class="chat-input-class" placeholder="Type a message..." autocomplete="off">
                <button type="submit" id="chat-send-btn" class="btn btn-primary chat-send-btn-class"><i class="fas fa-paper-plane"></i></button>
            </form>
        </div>
    </div>

    <div id="support-chat-modal" class="modal-overlay chat-modal-class">
        <div class="modal-content">
            <div class="modal-header chat-header-class">
                <h2 data-translate-key="support_chat_title">Support Chat</h2>
                <button id="support-chat-modal-close-btn" class="modal-close-btn">×</button>
            </div>
            <div id="support-chat-messages-container" class="chat-messages-container-class"></div>
            <form id="support-chat-input-form" class="chat-input-form-class">
                <input type="text" id="support-chat-input" class="chat-input-class" placeholder="Ask for help..." autocomplete="off">
                <button type="submit" id="support-chat-send-btn" class="btn btn-primary chat-send-btn-class"><i class="fas fa-paper-plane"></i></button>
            </form>
        </div>
    </div>

    <div id="bottom-nav-container"><nav class="bottom-nav"><a href="#" class="nav-item active" data-page="dashboard-page"><i class="fas fa-home"></i><span data-translate-key="home">Home</span></a><a href="#" class="nav-item" data-page="history-page"><i class="fas fa-history"></i><span data-translate-key="history">History</span></a><a href="#" class="nav-item" data-page="deposit-page"><i class="fas fa-plus-circle"></i><span data-translate-key="deposit">Deposit</span></a><a href="#" class="nav-item" data-page="withdraw-page"><i class="fas fa-wallet"></i><span data-translate-key="withdraw">Withdraw</span></a><a href="#" class="nav-item" data-page="profile-page"><i class="fas fa-user-circle"></i><span data-translate-key="profile">Profile</span></a></nav></div>
<script>
    // This is a self-executing function to encapsulate the logic and avoid polluting the global scope.
    (function() {
        // This programmatic PWA setup allows the entire app to be self-contained in one HTML file.
        const manifest = { "name": "Make Money & Traffic", "short_name": "Make Money", "start_url": ".", "display": "standalone", "background_color": "#121212", "theme_color": "#F7B500", "description": "Earn money by watching ads and completing tasks.", "icons": [{ "src": "data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAMAAAADACAYAAABS3GwHAAAAAXNSR0IArs4c6QAAAl1JREFUeF7t0AEJAAAMAsHZv/RyPNwSyBIg1AAQEAABYDYgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAAIgwGwgAEEAAhAQAAGgBpsEAB46gAb5CBvQy9s7wAAAABJRU5ErkJggg==", "sizes": "192x192", "type": "image/png", "purpose": "any maskable" }] };
        const manifestBlob = new Blob([JSON.stringify(manifest)], {type: 'application/json'});
        const manifestURL = URL.createObjectURL(manifestBlob);
        document.getElementById('manifest-link').setAttribute('href', manifestURL);
        const swContent = `const CACHE_NAME = 'makemoney-cache-v1'; const urlsToCache = ['/']; self.addEventListener('install', e => e.waitUntil(caches.open(CACHE_NAME).then(c => c.addAll(urlsToCache)))); self.addEventListener('fetch', e => e.respondWith(caches.match(e.request).then(r => r || fetch(e.request)))); self.addEventListener('activate', e => { const cacheWhitelist = [CACHE_NAME]; e.waitUntil(caches.keys().then(names => Promise.all(names.map(name => { if (cacheWhitelist.indexOf(name) === -1) return caches.delete(name); })))); });`;
        const swBlob = new Blob([swContent], {type: 'application/javascript'});
        const swURL = URL.createObjectURL(swBlob);
        if ('serviceWorker' in navigator) { navigator.serviceWorker.register(swURL).then(() => console.log('SW registered.')).catch(err => console.error('SW reg failed:', err)); }
    })();

    document.addEventListener('DOMContentLoaded', () => {

        // =================================================================
        // 1. STATE MANAGEMENT & CORE DATA
        // =================================================================
        window.campaignSimulators = {}; // To manage campaign progress intervals
        window.depositTimer = null; // To manage the deposit session timer

        const defaultProfilePicture = "data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0iI2NjYyI+PHBhdGggZD0iTTEyIDJDNi44OCAyIDIgNi40OCAyIDEyczQuNDggMTAgMTAgMTAgMTAtNC40OCAxMC0xMFMxNy41MiAyIDEyIDJ6bTAgM2MxLjg4IDAgMy40MiAxLjU0IDMuNDIgMy40MnMtMS41NCAzLjQyLTMuNDIgMy40MlM4LjU4IDEwLjMgOC41OCA4LjQyIDExLjA4IDUgMTIgNXptMCAxNC4yYy0yLjUgMC00LjcxLTEuMjgtNi0zLjIyLjAzLTEuOTkgNC0zLjA4IDYtMy4wOHM1Ljk3IDEuMDkgNiAzLjA4Yy0xLjI5IDEuOTQtMy41IDMuMjItNiAzLjIyeiIvPjwvc3ZnPg==";
        const SUPPORT_AGENT = {
            name: "Support Team",
            avatar: "data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0iIzI4YTc0NSI+PHBhdGggZD0iTTIwLjQ5IDE3LjM4Yy0uODItMi4xOS0xLjQ2LTQuMDgtMi4xNy01LjYyLS40My0uOTMtLjc4LTEuODMtMS4xMy0yLjU5LS4zMy0uNzEtLjM1LTEuMy4xLTEuODguNDUtLjU4IDEuMTItMS4wMyAxLjYxLTEuNjIuNDgtLjU4LjYyLTEuNDIuMjYtMi4xNmwtLjI0LS41Yy0uMzYtLjc0LTEuMi0xLjEtMS45NC0uNzQtLjU4LjI4LTEuMDIuNTEtMS41LjguNDEuODMuNTMgMS44My4yNSAyLjc5LS4yMy43OS0uNzIgMS40Ny0xLjMxIDEuODgtMS43OCAxLjIzLTQuOTUtMy4yOC0zLjU1LTYuNDYgMS4wNS0yLjM5IDMuNDgtMy45MSA2LjA0LTMuOTFoLjA3Yy44OCAwIDEuNzEuMjcgMi40NC43NS43My40NyAxLjI4IDEuMTcgMS41MyAyLjA1LjM0IDEuMTgtLjEyIDIuNDQtLjg3IDMuNDMtLjU4Ljc3LTEuMjggMS40LTEuODggMi4xMy0uMzguNDYtLjM1IDEuMDguMDggMS41Mi45My45MyAxLjc2IDIuMDEgMi40MSA0LjEzLjA0LjEzLjA3LjI3LjA5LjQxLjA2LjQxLjE3IDEuMTQtMS4xNCAxLjIxLS4yMy4wMS0uNjQtLjE0LS44NC0uMjF6TTkuMDcgMTguMDdjLTQuNDEtLjMzLTQuNTgtNS40My0xLjlkLTYuMTYuNDYtLjEzIDEuMDItLjE2IDEuNDItLjQxLjM0LS4yMS40OC0uNjIuNDgtMS4wMyAwLS40OC0uNDUtMS4yMy0uNzgtMS43My0uNDItLjYyLS40Ny0xLjQ3LS4xMi0yLjE4LjM3LS43NSAxLjEyLTEuMjIgMS45MS0uOTkuNTguMTggMS4wMS40NyAxLjQ3LjguMjQuMTcuNDIuMzUuNTguNTUgMS4xMyAxLjM4IDEuNyAyLjk2IDEuNjggNC42MS0uMDIgMS44NC0uNzMgMy41LTEuODcgNC43My0uMzkuNDItLjg1Ljc0LTEuMzcgMS0uMy4xNS0uNjMuMi0uOTYuMi0uNSAwLTEtLjI2LTEuMy0uNjF6Ii8+PC9zdmc+"
        };

        const appState = { 
            currentUserEmail: null, 
            users: [], 
            userData: {}, 
            userStores: {}, // <-- NEW: For user-created stores
            ads: { video: [], banner: [], task: [] }, 
            chatMessages: [],
            recoveryEmail: null,
            lastDailyReset: null
        };
        
        const defaultUserData = { 
            balance: 0, history: [], completedTasks: [], profilePicture: defaultProfilePicture, 
            phone: '', dob: '', gender: '', address: '', 
            kycStatus: 'not_verified', kycData: {}, 
            referralEarnings: 0, referredUsersCount: 0, 
            isPublisher: false,
            hasStore: false, // <-- NEW: To track if a user is a seller
            supportChat: [], 
            hasUnreadSupportMessage: false,
            activeCampaigns: {}
        };
        
        const packageRequirements = {
             youtube: { 'Subscribers': 1000, 'Watch Hours': 4000, 'Likes': 2000 },
             facebook: { 'Followers': 10000, 'Watch Minutes': 600000, 'Likes': 80000 },
             tiktok: { 'Followers': 10000, 'Views (30d)': 100000, 'Likes': 80000 },
             instagram: { 'Followers': 10000, 'Likes': 80000, 'Comments': 5000 }
        };

        const saveState = () => { try { localStorage.setItem('makemoney_appState', JSON.stringify(appState)); } catch (e) { console.error("Failed to save state:", e); showNotification("Could not save data.", 'error'); } };
        const loadState = () => { 
            try { 
                const savedState = JSON.parse(localStorage.getItem('makemoney_appState')); 
                if (savedState) { 
                    Object.assign(appState, savedState); 
                }
            } catch (e) { 
                console.error("Failed to load state, starting fresh:", e);
            } 
        };
        
        // =================================================================
        // 2. TRANSLATION & NOTIFICATION SYSTEM
        // =================================================================
        
        const translations = {
            en: {
                app_title_full: "Make Money & Traffic", email: "Email", password: "Password", login: "Login", register: "Register",
                forgot_password_q: "Forgot Password?", no_account_q: "Don't have an account? <strong>Register</strong>", have_account_q: "Already have an account? <strong>Login</strong>",
                home: "Home", history: "History", deposit: "Deposit", withdraw: "Withdraw", profile: "Profile", save_changes: "Save Changes", logout: "Logout",
                next: "Next", verify: "Verify", back: "Back", watch_earn: "Watch & Earn", watch_earn_desc: "Get paid for watching videos and completing simple tasks.",
                easy_payouts: "Easy Payouts", easy_payouts_desc: "Withdraw your earnings through multiple payment methods.", grow: "Grow", grow_desc: "Promote your own content to a real audience.",
                full_name: "Full Name", confirm_password: "Confirm Password", reset_password: "Reset Password", forgot_intro: "Enter your account's email address and we will help you reset your password.",
                email_address: "Email Address", forgot_verify_intro: "To verify your identity, please enter your date of birth.", date_of_birth: "Date of Birth",
                forgot_new_pass_intro: "Verification successful. Please enter your new password.", new_password: "New Password", confirm_new_password: "Confirm New Password",
                welcome: "Welcome", online_users: "Online Users:", current_balance: "Current Balance", how_it_works: "How It Works", watch_ads: "Watch Ads",
                watch_ads_desc: "Explore videos and tasks.", earn_cash: "Earn Cash", earn_cash_desc: "Get rewards for your time.", withdraw_money: "Withdraw",
                withdraw_money_desc: "Easily cash out your earnings.", start_earning: "Start Earning", video_ads: "Video Ads", banner_ads: "Banner Ads",
                tasks: "Interactive Tasks", creator_packages: "Creator Growth Packages", watch_earn_title: "Watch & Earn", ad_loading: "Your ad is loading...",
                time_remaining: "Time remaining:", claim_reward: "Claim Reward", no_history: "No transactions yet.", deposit_funds: "Deposit Funds",
                withdraw_funds: "Withdraw Funds", select_method: "1. Select Method", enter_details: "2. Enter Details", enter_details_amount: "2. Enter Details & Amount",
                amount_usd: "Amount (USD)", min_deposit: "Minimum ${amount}", min_withdraw: "Minimum $5.00", confirm_deposit: "Confirm Deposit", request_withdrawal: "Request Withdrawal",
                my_profile: "My Profile", account_balance: "Account Balance", phone_number: "Phone Number", gender: "Gender", select_gender: "-- Select --",
                male: "Male", female: "Female", address: "Address", change_password: "Change Password", old_password: "Old Password",
                old_pass_placeholder: "Enter old password to change", new_pass_placeholder: "Leave blank to keep current", kyc_verification: "KYC Verification",
                kyc_status: "Status:", kyc_not_verified: "Not Verified", kyc_pending: "Pending", kyc_verified: "Verified", start_verification: "Start Verification",
                publisher_q: "Are you a Publisher? Advertise with Us", 
                advertise_with_us: "Advertise With Us", create_campaign_title: "Create Your Ad Campaign", create_campaign_desc: "Reach a broad and engaged audience by creating your own ad campaigns. You can launch targeted video ads, banner ads, or interactive tasks to drive traffic and engagement. Start now for as little as $1.00!",
                create_campaign_now: "Create Campaign Now", creator_packages_title: "All-in-One Growth Packages", creator_packages_desc: "If you're looking to meet monetization requirements on platforms like YouTube or Facebook, our comprehensive growth packages are the perfect solution. We handle the complexity, you get the results.",
                view_growth_packages: "View Growth Packages", create_ad_campaign_title: "Create Ad Campaign", ad_type: "Ad Type", select_one: "-- Select --", video_ad: "Video Ad", banner_ad: "Banner Ad", interactive_task: "Interactive Task",
                video_title_url: "Video Title / URL", banner_title: "Banner Title", platform: "Platform", target_url: "Target URL", action: "Action", campaign_budget: "Campaign Budget ($)", reward_per_action: "Reward per Interaction ($)",
                estimated_reach: "Estimated Reach:", terms_agreement: "I agree to the terms and take responsibility for the content.", create_publish_campaign: "Create & Publish Campaign",
                youtube_growth: "YouTube Growth", facebook_expansion: "Facebook Expansion", tiktok_boost: "TikTok Viral Boost", instagram_push: "Instagram Profile Push",
                buy_package: "Buy Package", alert_pass_nomatch: "Passwords do not match.",
                alert_email_exists: "An account with this email already exists.", alert_invalid_creds: "Invalid email or password.",
                alert_earned_reward: "You've earned ${amount}!", alert_insufficient_balance: "Insufficient balance. Please deposit funds first.",
                history_watched_ad: "Watched Ad", history_task_completed: "Task: {taskTitle}", history_deposit: "Deposit via {method}",
                history_withdrawal: "Withdrawal Request ({method})", history_referral_bonus: "Referral Bonus",
                history_task_commission: "Task Commission ({amount}) from {user}",
                refer_earn_title: "Invite Friends, Earn Rewards", refer_desc: "Share your link to earn $0.05 for each new user + 3% of their task earnings!", your_ref_link: "Your Referral Link",
                copy: "Copy", share: "Share", referred_users: "Referred Users", referral_earnings: "Referral Earnings",
                alert_link_copied: "Referral link copied to clipboard!",
                monetization_req_title: "Monetization Requirements",
                youtube_req_1: "1,000 Subscribers", youtube_req_2: "4,000 Watch Hours",
                facebook_req_1: "10,000 Followers", facebook_req_2: "600k Watch Minutes",
                tiktok_req_1: "10,000 Followers", tiktok_req_2: "100k Views (30 days)",
                instagram_req_1: "10,000 Followers", instagram_req_2: "Active Engagement",
                pkg_purchase_desc: "Your campaign will be automatically optimized with a mix of interactions to ensure natural growth.", confirm_pkg_purchase: "Confirm & Start Campaign",
                pkg_auth_eng: "Authentic Engagement", pkg_real_users: "Real Users", pkg_views: "Real Views", pkg_likes: "Post Likes", pkg_subs: "Subscribers", pkg_comments: "Comments",
                pkg_community_bld: "Community Building", pkg_followers: "Followers", pkg_page_likes: "Page/Post Likes", pkg_viral_pot: "Viral Potential", pkg_video_likes: "Video Likes", pkg_shares_comments: "Shares & Comments", pkg_profile_growth: "Profile Growth",
                daily_reset_notification: "Today's opportunities have been refreshed!",
                kyc_secure_process: "Secure Verification Process", kyc_intro_desc: "To ensure the security of our community, we need to verify your identity. Please have your official ID card ready.", kyc_begin_verification: "Begin Verification", kyc_step_1: "Step 1: Front of ID", kyc_front_desc: "Please upload a clear image of the front of your ID card.", kyc_click_to_upload: "Click to Upload", kyc_step_2: "Step 2: Back of ID", kyc_back_desc: "Now, please upload a clear image of the back of your ID card.", submit_for_review: "Submit for Review", kyc_processing: "Processing Verification", kyc_pending_desc: "Your documents have been submitted and are under review. This may take a few moments.", kyc_verified_title: "Verification Complete!", kyc_verified_desc: "Your account is now fully verified. Thank you for your cooperation.", done: "Done",
                kyc_withdrawal_required: "For security, identity verification is required to withdraw funds.",
                badge_verified: "Verified", badge_publisher: "Publisher",
                chat_title: "Global Chat", support_chat_title: "Support Chat",
                auth_about_title: "Make Money & Traffic",
                auth_about_desc1: "Looking for a guaranteed way to earn online? 💸 Are you a creator struggling to reach your audience and meet monetization requirements? Our app is the perfect solution for you!",
                auth_about_desc2: "Learn how you can:",
                auth_about_li1: "Register easily and get started in seconds",
                auth_about_li2: "Earn money by watching ads and completing tasks",
                auth_about_li3: "Withdraw your earnings via secure, multiple methods",
                auth_about_li4: "Buy professional growth packages for your channels",
                auth_about_li5: "Increase your earnings by inviting friends",
                auth_about_promo_line: "You can deposit just $1 to start your advertising campaign and make your content go viral!",
                auth_about_footer: "Don't waste any more time! Join our community today and start achieving your financial and creative goals.",
                pkg_campaign_progress: "Campaign in Progress",
                pkg_campaign_complete_title: "Campaign Complete!",
                pkg_campaign_complete_desc: "Congratulations! You've met the requirements for this package.",
                start_new_campaign: "Start a New Campaign?",
                session_expires_in: "Session expires in:",
                deposit_session_expired: "Deposit session expired. Please select a method again.",
                digital_store_title: "Digital Services Store",
                digital_store_subtitle: "Get your favorite subscriptions using your balance.",
                buy_now: "Buy Now",
                digital_store_entry_title: "Digital Store",
                digital_store_entry_desc: "Use your balance for Netflix, Spotify & more.",
                // NEW TRANSLATIONS FOR USER STORES
                digital_services: "Digital Services", community_marketplace: "Community Marketplace",
                my_store: "My Store", store_details: "Store Details", store_name: "Store Name",
                store_description: "Store Description", save_store_details: "Save Store Details",
                my_products: "My Products", add_product: "Add Product", add_new_product: "Add New Product",
                product_name: "Product Name", product_description: "Product Description", product_price: "Price (USD)",
                product_image_url: "Image URL", become_a_seller: "Become a Seller", manage_my_store: "Manage My Store",
                store_created_success: "Your store has been created! You can now add products.",
                store_updated_success: "Store details updated successfully.",
                product_added_success: "Product added successfully.",
                no_community_products: "No products from the community yet. Be the first to sell!",
            },
            ar: {
                app_title_full: "كسب المال والزيارات", email: "البريد الإلكتروني", password: "كلمة المرور", login: "تسجيل الدخول", register: "تسجيل جديد",
                forgot_password_q: "هل نسيت كلمة المرور؟", no_account_q: "ليس لديك حساب؟ <strong data-translate-key='register'>تسجيل جديد</strong>", have_account_q: "لديك حساب بالفعل؟ <strong data-translate-key='login'>تسجيل الدخول</strong>",
                home: "الرئيسية", history: "السجل", deposit: "إيداع", withdraw: "سحب", profile: "ملفي الشخصي", save_changes: "حفظ التغييرات", logout: "تسجيل الخروج",
                next: "التالي", verify: "تحقق", back: "رجوع", watch_earn: "شاهد واكسب", watch_earn_desc: "احصل على أموال مقابل مشاهدة الفيديوهات وإكمال المهام البسيطة.",
                easy_payouts: "دفعات سهلة", easy_payouts_desc: "اسحب أرباحك عبر طرق دفع متعددة.", grow: "طوّر محتواك", grow_desc: "روّج للمحتوى الخاص بك لجمهور حقيقي.",
                full_name: "الاسم الكامل", confirm_password: "تأكيد كلمة المرور", reset_password: "إعادة تعيين كلمة المرور", forgot_intro: "أدخل البريد الإلكتروني لحسابك وسنساعدك في إعادة تعيين كلمة المرور.",
                email_address: "عنوان البريد الإلكتروني", forgot_verify_intro: "للتحقق من هويتك، يرجى إدخال تاريخ ميلادك.", date_of_birth: "تاريخ الميلاد",
                forgot_new_pass_intro: "تم التحقق بنجاح. يرجى إدخال كلمة المرور الجديدة.", new_password: "كلمة المرور الجديدة", confirm_new_password: "تأكيد كلمة المرور الجديدة",
                welcome: "أهلاً بك", online_users: "المتصلون الآن:", current_balance: "الرصيد الحالي", how_it_works: "كيف يعمل", watch_ads: "شاهد الإعلانات",
                watch_ads_desc: "تصفح الفيديوهات والمهام.", earn_cash: "اكسب المال", earn_cash_desc: "احصل على مكافآت مقابل وقتك.", withdraw_money: "اسحب أرباحك",
                withdraw_money_desc: "اسحب أرباحك بسهولة.", start_earning: "ابدأ الكسب", video_ads: "إعلانات الفيديو", banner_ads: "إعلانات البانر",
                tasks: "مهام تفاعلية", creator_packages: "باقات نمو المبدعين", watch_earn_title: "شاهد واكسب", ad_loading: "جاري تحميل إعلانك...",
                time_remaining: "الوقت المتبقي:", claim_reward: "اطلب المكافأة", no_history: "لا توجد معاملات بعد.", deposit_funds: "إيداع الأموال",
                withdraw_funds: "سحب الأموال", select_method: "1. اختر طريقة", enter_details: "2. أدخل التفاصيل", enter_details_amount: "2. أدخل التفاصيل والمبلغ",
                amount_usd: "المبلغ (بالدولار الأمريكي)", min_deposit: "الحد الأدنى للإيداع ${amount}",
                min_withdraw: "الحد الأدنى للسحب 5.00$",
                confirm_deposit: "تأكيد الإيداع", request_withdrawal: "طلب سحب", my_profile: "ملفي الشخصي", account_balance: "رصيد الحساب",
                phone_number: "رقم الهاتف", gender: "الجنس", select_gender: "-- اختر --", male: "ذكر", female: "أنثى", address: "العنوان",
                change_password: "تغيير كلمة المرور", old_password: "كلمة المرور القديمة", old_pass_placeholder: "أدخل كلمة المرور القديمة للتغيير",
                new_pass_placeholder: "اتركه فارغًا للإبقاء على الحالية", kyc_verification: "توثيق الهوية (KYC)", kyc_status: "الحالة:",
                kyc_not_verified: "غير موثق", kyc_pending: "قيد المراجعة", kyc_verified: "موثق", start_verification: "بدء التوثيق",
                publisher_q: "هل أنت ناشر؟ أعلن معنا",
                advertise_with_us: "أعلن معنا", create_campaign_title: "أنشئ حملتك الإعلانية", create_campaign_desc: "صل إلى جمهور واسع ومتفاعل عبر إنشاء حملاتك الإعلانية الخاصة. يمكنك إطلاق إعلانات فيديو مستهدفة، أو بانرات، أو مهام تفاعلية لزيادة الزيارات والتفاعل. ابدأ الآن بمبلغ 1.00$ فقط!",
                create_campaign_now: "أنشئ حملة الآن", creator_packages_title: "باقات النمو المتكاملة", creator_packages_desc: "إذا كنت تسعى لتحقيق شروط الربح على منصات مثل يوتيوب أو فيسبوك، فإن باقات النمو الشاملة لدينا هي الحل الأمثل. نحن نتولى التعقيدات، وأنت تحصل على النتائج.",
                view_growth_packages: "عرض باقات النمو", create_ad_campaign_title: "إنشاء حملة إعلانية", ad_type: "نوع الإعلان", select_one: "-- اختر --", video_ad: "إعلان فيديو", banner_ad: "إعلان بانر", interactive_task: "مهمة تفاعلية",
                video_title_url: "عنوان/رابط الفيديو", banner_title: "عنوان البانر", platform: "المنصة", target_url: "الرابط المستهدف", action: "الإجراء", campaign_budget: "ميزانية الحملة ($)", reward_per_action: "المكافأة لكل تفاعل ($)",
                estimated_reach: "الوصول المقدر:", terms_agreement: "أوافق على الشروط وأتحمل مسؤولية المحتوى.", create_publish_campaign: "إنشاء ونشر الحملة",
                youtube_growth: "باقة نمو يوتيوب", facebook_expansion: "باقة نمو فيسبوك", tiktok_boost: "باقة دعم تيك توك", instagram_push: "باقة دعم انستغرام",
                buy_package: "شراء الباقة", alert_pass_nomatch: "كلمات المرور غير متطابقة.",
                alert_email_exists: "يوجد حساب مسجل بهذا البريد الإلكتروني بالفعل.", alert_invalid_creds: "البريد الإلكتروني أو كلمة المرور غير صحيحة.",
                alert_earned_reward: "لقد ربحت ${amount}!", alert_insufficient_balance: "رصيد غير كافٍ. يرجى إيداع الأموال أولاً.",
                history_watched_ad: "مشاهدة إعلان", history_task_completed: "مهمة: {taskTitle}", history_deposit: "إيداع عبر {method}",
                history_withdrawal: "طلب سحب ({method})", history_referral_bonus: "مكافأة إحالة",
                history_task_commission: "عمولة مهمة ({amount}) من {user}",
                refer_earn_title: "ادعُ الأصدقاء، اكسب المكافآت", refer_desc: "شارك رابطك لتربح 0.05$ عن كل مستخدم جديد + 3% من أرباح مهامهم!", your_ref_link: "رابط الإحالة الخاص بك",
                copy: "نسخ", share: "مشاركة", referred_users: "المستخدمون المحالون", referral_earnings: "أرباح الإحالة",
                alert_link_copied: "تم نسخ رابط الإحالة إلى الحافظة!",
                monetization_req_title: "شروط تحقيق الربح",
                youtube_req_1: "1,000 مشترك", youtube_req_2: "4,000 ساعة مشاهدة",
                facebook_req_1: "10,000 متابع", facebook_req_2: "600 ألف دقيقة مشاهدة",
                tiktok_req_1: "10,000 متابع", tiktok_req_2: "100 ألف مشاهدة (آخر 30 يومًا)",
                instagram_req_1: "10,000 متابع", instagram_req_2: "تفاعل نشط",
                pkg_purchase_desc: "سيتم تحسين حملتك تلقائيًا بمزيج من التفاعلات لضمان نمو طبيعي.", confirm_pkg_purchase: "تأكيد وبدء الحملة",
                pkg_auth_eng: "تفاعل حقيقي", pkg_real_users: "مستخدمون حقيقيون", pkg_views: "مشاهدات حقيقية", pkg_likes: "إعجابات للمنشور", pkg_subs: "مشتركون", pkg_comments: "تعليقات",
                pkg_community_bld: "بناء مجتمع", pkg_followers: "متابعون", pkg_page_likes: "إعجابات للصفحة/المنشور", pkg_viral_pot: "إمكانية الانتشار", pkg_video_likes: "إعجابات للفيديو", pkg_shares_comments: "مشاركات وتعليقات", pkg_profile_growth: "نمو الملف الشخصي",
                daily_reset_notification: "تم تحديث فرص اليوم!",
                kyc_secure_process: "عملية تحقق آمنة", kyc_intro_desc: "لضمان أمان مجتمعنا، نحتاج إلى التحقق من هويتك. يرجى تجهيز بطاقة الهوية الرسمية الخاصة بك.", kyc_begin_verification: "بدء التحقق", kyc_step_1: "الخطوة 1: الوجه الأمامي للهوية", kyc_front_desc: "يرجى تحميل صورة واضحة للوجه الأمامي لبطاقة هويتك.", kyc_click_to_upload: "انقر للتحميل", kyc_step_2: "الخطوة 2: الوجه الخلفي للهوية", kyc_back_desc: "الآن، يرجى تحميل صورة واضحة للوجه الخلفي لبطاقة هويتك.", submit_for_review: "إرسال للمراجعة", kyc_processing: "جاري معالجة التحقق", kyc_pending_desc: "تم استلام مستنداتك وهي قيد المراجعة الآن. قد يستغرق هذا بضع لحظات.", kyc_verified_title: "اكتمل التحقق!", kyc_verified_desc: "لقد تم توثيق حسابك بالكامل الآن. شكراً لتعاونك.", done: "تم",
                kyc_withdrawal_required: "لأسباب أمنية، يجب توثيق الهوية لتتمكن من سحب الأموال.",
                badge_verified: "موثق", badge_publisher: "ناشر",
                chat_title: "الدردشة العامة", support_chat_title: "دردشة الدعم",
                auth_about_title: "Make Money & Traffic",
                auth_about_desc1: "هل تبحث عن طريقة مضمونة لكسب المال من الإنترنت؟ 💸 هل أنت صانع محتوى وتكافح للوصول إلى جمهورك وتحقيق شروط الربح؟ تطبيقنا هو الحل الأمثل لك!",
                auth_about_desc2: "تعرف على كيف يمكنك:",
                auth_about_li1: "التسجيل بسهولة والبدء في ثوانٍ",
                auth_about_li2: "كسب المال من خلال مشاهدة الإعلانات وإكمال المهام",
                auth_about_li3: "سحب أرباحك عبر طرق دفع آمنة ومتعددة",
                auth_about_li4: "شراء باقات نمو احترافية لقنواتك وحساباتك",
                auth_about_li5: "زيادة أرباحك عبر دعوة أصدقائك",
                auth_about_promo_line: "يمكنك إيداع (1$) و بدء حملتك الاعلانية و جعل محتواك اكثر إنتشارا",
                auth_about_footer: "لا تضيع المزيد من الوقت! انضم إلى مجتمعنا اليوم وابدأ في تحقيق أهدافك المالية والإبداعية.",
                pkg_campaign_progress: "الحملة قيد التنفيذ",
                pkg_campaign_complete_title: "اكتملت الحملة!",
                pkg_campaign_complete_desc: "تهانينا! لقد حققت متطلبات هذه الباقة بنجاح.",
                start_new_campaign: "هل تود بدء حملة جديدة؟",
                session_expires_in: "تنتهي الجلسة خلال:",
                deposit_session_expired: "انتهت جلسة الإيداع. يرجى اختيار طريقة الدفع مرة أخرى.",
                digital_store_title: "متجر الخدمات الرقمية",
                digital_store_subtitle: "احصل على اشتراكاتك المفضلة باستخدام رصيدك.",
                buy_now: "اشتر الآن",
                digital_store_entry_title: "المتجر الرقمي",
                digital_store_entry_desc: "استخدم رصيدك للحصول على Netflix و Spotify والمزيد.",
                // NEW TRANSLATIONS FOR USER STORES (AR)
                digital_services: "الخدمات الرقمية", community_marketplace: "سوق المجتمع",
                my_store: "متجري", store_details: "تفاصيل المتجر", store_name: "اسم المتجر",
                store_description: "وصف المتجر", save_store_details: "حفظ تفاصيل المتجر",
                my_products: "منتجاتي", add_product: "إضافة منتج", add_new_product: "إضافة منتج جديد",
                product_name: "اسم المنتج", product_description: "وصف المنتج", product_price: "السعر (بالدولار)",
                product_image_url: "رابط الصورة", become_a_seller: "كن بائعًا", manage_my_store: "إدارة متجري",
                store_created_success: "تم إنشاء متجرك بنجاح! يمكنك الآن إضافة منتجاتك.",
                store_updated_success: "تم تحديث تفاصيل المتجر بنجاح.",
                product_added_success: "تمت إضافة المنتج بنجاح.",
                no_community_products: "لا توجد منتجات من المجتمع بعد. كن أول من يبيع!",
            }
        };
        
        let currentLanguage = localStorage.getItem('app_language') || 'en';
        
        const t = (key, replacements = {}) => { let text = (translations[currentLanguage] && translations[currentLanguage][key]) || translations['en'][key] || key; Object.entries(replacements).forEach(([p, v]) => { text = text.replace(new RegExp(`\\{\\s*${p}\\s*\\}|\\$\\s*\\{\\s*${p}\\s*\\}`, 'g'), v); }); return text; };
        const showNotification = (message, type = 'info') => { const c = document.getElementById('notification-container'); const n = document.createElement('div'); n.className = `notification ${type}`; const i = type === 'success' ? 'fa-check-circle' : type === 'error' ? 'fa-exclamation-circle' : 'fa-info-circle'; n.innerHTML = `<i class="fas ${i}"></i><span>${message}</span>`; c.appendChild(n); setTimeout(() => n.classList.add('show'), 10); setTimeout(() => { n.classList.remove('show'); n.addEventListener('transitionend', () => n.remove()); }, 4000); };
        
        // =================================================================
        // 3. UI & DOM MANIPULATION
        // =================================================================
        
        const allElements = {};
        
        const populateDomElements = () => {
            const ids = [
                'app-container', 'notification-container', 'splash-page', 'loader-percentage', 'icon-rain-container', 'auth-page',
                'login-form-container', 'login-form', 'register-form', 'register-form-actual', 'forgot-password-page', 'forgot-step-1-form',
                'forgot-step-2-form', 'forgot-step-3-form', 'forgot-message', 'dashboard-page', 'welcome-message', 'news-ticker-container',
                'online-users-count', 'balance-display', 'quick-access-grid', 'ad-list-page-1', 'ad-list-1', 'ad-list-page-2', 'ad-list-2',
                'ad-list-page-3', 'ad-list-3', 'watch-ad-page', 'watch-ad-back-btn', 'ad-container', 'timer-display', 'countdown',
                'claim-reward-btn', 'history-page', 'history-list', 'no-history-message', 'deposit-page', 'deposit-methods-grid',
                'payment-details-form', 'deposit-form', 'deposit-amount', 'deposit-instructions', 'qr-code-container', 'qr-code-img',
                'cih-screenshot-upload-group', 'cih-screenshot-upload', 'screenshot-filename', 'confirm-deposit-btn', 'withdraw-page',
                'withdraw-methods-grid', 'withdrawal-details-form', 'withdraw-form', 'withdraw-amount', 'profile-page', 'profile-header',
                'profile-picture-container', 'profile-picture', 'profile-picture-upload-label', 'profile-picture-upload', 'profile-balance-display',
                'profile-balance-value', 'profile-form', 'profile-name', 'profile-email', 'profile-phone', 'profile-dob', 'profile-gender',
                'profile-address', 'profile-old-password', 'profile-new-password', 'profile-packages-btn',
                'show-publishers-link', 'logout-btn', 'packages-page', 'publishers-page', 'go-to-create-ad-btn', 'create-ad-page',
                'create-ad-form', 'ad-type-select', 'video-ad-fields', 'video-title', 'banner-ad-fields', 'banner-title', 'task-ad-fields',
                'task-platform', 'task-target', 'task-action', 'campaign-budget', 'reward-per-action', 'reach-display', 'estimated-reach',
                'terms-checkbox', 'create-ad-submit-btn', 'package-modal', 'modal-title', 'package-purchase-form', 
                'package-url-page', 'package-url-page-label', 'package-url-video1', 'package-url-video2', 'package-url-video3',
                'confirm-package-purchase-btn', 'bottom-nav-container', 'show-forgot-password', 'show-register', 'show-login',
                'dashboard-packages-btn', 'referral-qr-img', 'referral-link-display', 'copy-referral-link-btn', 'share-referral-link-btn',
                'referred-users-count', 'referral-earnings-total',
                'kyc-modal', 'kyc-modal-title', 'kyc-modal-close-btn', 'kyc-step-intro', 'kyc-begin-btn', 
                'kyc-step-front', 'kyc-id-front-upload', 'id-front-preview', 'kyc-next-btn',
                'kyc-step-back', 'kyc-id-back-upload', 'id-back-preview', 'kyc-submit-btn',
                'kyc-step-pending', 'kyc-step-verified', 'kyc-done-btn',
                'profile-name-display', 'profile-badge-container',
                'chat-fab', 'chat-unread-count', 'chat-modal', 'chat-modal-close-btn', 'chat-messages-container', 
                'chat-input-form', 'chat-input', 'chat-send-btn',
                'support-fab', 'support-unread-count', 'support-chat-modal', 'support-chat-modal-close-btn', 
                'support-chat-messages-container', 'support-chat-input-form', 'support-chat-input', 'support-chat-send-btn',
                'publishers-view-packages-btn', 'deposit-timer-display', 'deposit-countdown', 'store-page',
                'digital-store-grid', 'community-store-grid',
                // NEW ELEMENTS FOR USER STORES
                'my-store-page', 'my-store-form', 'my-store-name', 'my-store-description', 'add-product-btn', 'my-products-list',
                'add-product-modal', 'add-product-form',
                'become-seller-btn', 'go-to-my-store-btn'
            ];
            ids.forEach(id => { const el = document.getElementById(id); if(el) allElements[id.replace(/-(\w)/g, (m, p1) => p1.toUpperCase())] = el; });
            
            allElements.pages = document.querySelectorAll('.page');
            allElements.navItems = document.querySelectorAll('.nav-item');
            allElements.specificWithdrawFields = document.querySelectorAll('#withdraw-page .specific-fields');
            allElements.specificAdFields = document.querySelectorAll('.specific-ad-fields');
            allElements.packageModalCloseBtn = document.querySelector('#package-modal .modal-close-btn');
            allElements.addProductModalCloseBtn = document.querySelector('#add-product-modal .modal-close-btn');
            allElements.langGlobeBtn = document.querySelector('.language-globe-btn');
            allElements.langDropdown = document.querySelector('.language-dropdown');
            allElements.newsTickerContent = document.querySelector('.news-ticker-content');
            allElements.kycSteps = document.querySelectorAll('.kyc-step');
        };

        const applyTranslations = () => {
            if (!currentLanguage) return;
            document.documentElement.lang = currentLanguage;
            document.body.classList.toggle('rtl', currentLanguage === 'ar');
            document.body.dir = currentLanguage === 'ar' ? 'rtl' : 'ltr';

            document.querySelectorAll('[data-translate-key]').forEach(element => {
                const key = element.dataset.translateKey;
                const translation = t(key);
                if (translation.includes('<') && translation.includes('>')) {
                    element.innerHTML = translation;
                } else {
                    element.textContent = translation;
                }
            });

            document.querySelectorAll('[data-translate-placeholder-key]').forEach(el => { 
                const key = el.dataset.translatePlaceholderKey;
                let amount = '';
                if (key === 'min_deposit') {
                    amount = `$${parseFloat(el.min || 10).toFixed(2)}`;
                } else if (key === 'min_withdraw') {
                    amount = `$${parseFloat(el.min || 5).toFixed(2)}`;
                }
                el.placeholder = t(key, { amount: amount });
            });
        };

        const showPage = (pageId) => {
            if (window.depositTimer && pageId !== 'deposit-page') {
                clearInterval(window.depositTimer);
                window.depositTimer = null;
            }

            allElements.pages.forEach(p => p.classList.remove('active'));
            const targetPage = document.getElementById(pageId);
            if (targetPage) {
                targetPage.classList.add('active');
                let bodyClasses = document.body.className.split(' ').filter(c => !c.startsWith('page-'));
                document.body.className = bodyClasses.join(' ');
                document.body.classList.add(`page-${pageId.replace(/-page$/, '')}`);
            }

            const gradientMap = { 'dashboard-page': 'gradient-home', 'history-page': 'gradient-history', 'deposit-page': 'gradient-deposit', 'withdraw-page': 'gradient-withdraw', 'profile-page': 'gradient-profile', 'packages-page': 'gradient-profile', 'publishers-page': 'gradient-profile', 'create-ad-page': 'gradient-profile', 'store-page': 'gradient-store', 'my-store-page': 'gradient-store' };
            const pageGroup = pageId.startsWith('ad-list-') || pageId === 'watch-ad-page' ? 'dashboard-page' : pageId;
            let bodyClasses = document.body.className.split(' ').filter(c => !c.startsWith('gradient-'));
            document.body.className = bodyClasses.join(' ');
            
            if (pageId === 'auth-page' || pageId === 'forgot-password-page') {
                document.body.classList.add('page-auth');
            } else if (gradientMap[pageGroup]) {
                document.body.classList.add(gradientMap[pageGroup]);
            }

            if (currentLanguage === 'ar') document.body.classList.add('rtl');
            
            const mainNavPages = ['dashboard-page', 'history-page', 'deposit-page', 'withdraw-page', 'profile-page'];
            const isMainNavPage = mainNavPages.includes(pageGroup);
            allElements.bottomNavContainer.style.display = isMainNavPage ? 'flex' : 'none';
            if(isMainNavPage) allElements.navItems.forEach(item => item.classList.toggle('active', item.dataset.page === pageGroup));
            
            allElements.chatFab.style.display = pageId === 'dashboard-page' ? 'flex' : 'none';
            allElements.supportFab.style.display = pageId === 'profile-page' ? 'flex' : 'none';

            if (pageId !== 'deposit-page') resetDepositPage();
            if (pageId !== 'withdraw-page') resetWithdrawPage();
            if (pageId !== 'forgot-password-page') resetForgotPasswordPage();

            switch (pageId) {
                case 'dashboard-page': updateDashboardUI(); break;
                case 'history-page': updateHistoryUI(); break;
                case 'profile-page': updateProfileUI(); break;
                case 'packages-page': setupPackagesPage(); break;
                case 'store-page': updateStorePage(); break;
                case 'my-store-page': updateMyStorePage(); break;
                case 'ad-list-page-1': populateAdList(allElements.adList1, appState.ads.video, 'ad'); break;
                case 'ad-list-page-2': populateAdList(allElements.adList2, appState.ads.banner, 'ad'); break;
                case 'ad-list-page-3': populateAdList(allElements.adList3, appState.ads.task, 'task'); break;
            }
            applyTranslations(); 
        };

        const updateDashboardUI = () => {
            const user = getCurrentUser();
            if (!user) return;
            const userData = appState.userData[user.email] || defaultUserData;
            
            allElements.welcomeMessage.textContent = `${t('welcome')}, ${user.name}!`;
            allElements.balanceDisplay.textContent = `$${(userData.balance || 0).toFixed(2)}`;
            
            if(user.referralCode) {
                const refLink = `${window.location.origin}${window.location.pathname}?ref=${user.referralCode}`;
                allElements.referralLinkDisplay.value = refLink;
                allElements.referralQrImg.src = `https://api.qrserver.com/v1/create-qr-code/?size=100x100&data=${encodeURIComponent(refLink)}&bgcolor=FFFFFF&color=212121&qzone=1`;
                allElements.referredUsersCount.textContent = userData.referredUsersCount || 0;
                allElements.referralEarningsTotal.textContent = `$${(userData.referralEarnings || 0).toFixed(2)}`;
            }
        };
        
        const updateHistoryUI = () => {
            const user = getCurrentUser();
            if (!user) return;
            const userHistory = appState.userData[user.email]?.history || [];
            allElements.historyList.innerHTML = '';
            allElements.noHistoryMessage.style.display = userHistory.length === 0 ? 'block' : 'none';
            
            userHistory.slice().reverse().forEach(item => {
                const li = document.createElement('li');
                const isDebit = item.reward < 0;
                let details;
                
                switch(item.type) {
                    case 'Watched Ad': details = t('history_watched_ad'); break;
                    case 'Deposit': details = t('history_deposit', { method: item.method }); break;
                    case 'Withdrawal Request': details = t('history_withdrawal', { method: item.method }); break;
                    case 'Referral Bonus': details = t('history_referral_bonus'); break;
                    case 'Task Commission': details = t('history_task_commission', { amount: '3%', user: item.from }); break;
                    default:
                        if (item.type.startsWith('Task:')) details = t('history_task_completed', { taskTitle: item.type.replace('Task: ', '') });
                        else if (item.type.includes('Package') || item.type.includes('Campaign') || item.type.includes('KYC') || item.type.includes('Publisher') || item.type.startsWith('Purchased:') || item.type.startsWith('Sale:')) details = item.type;
                        else details = item.type;
                }

                li.innerHTML = `<div class="card" style="margin-bottom: 10px;"><div style="display:flex; justify-content: space-between; align-items: center;"><div><p style="font-weight:600;">${details}</p><p style="font-size:12px;color:var(--text-light-color);">${new Date(item.date).toLocaleString()}</p></div><span style="font-size: 1.1em; font-weight:700; color: ${isDebit ? 'var(--error-color)' : 'var(--success-color)'};">${isDebit ? '' : '+'}$${Math.abs(item.reward).toFixed(2)}</span></div></div>`;
                allElements.historyList.appendChild(li);
            });
        };
        
        const updateProfileUI = () => {
            const user = getCurrentUser();
            if (!user) return;
            const data = appState.userData[user.email] || {};

            allElements.profileName.value = user.name || '';
            allElements.profileEmail.value = user.email || '';
            allElements.profilePhone.value = data.phone || '';
            allElements.profileDob.value = data.dob || '';
            allElements.profileGender.value = data.gender || '';
            allElements.profileAddress.value = data.address || '';
            allElements.profilePicture.src = data.profilePicture || defaultProfilePicture;
            
            allElements.profileNameDisplay.textContent = user.name || 'User';
            allElements.profileBalanceValue.textContent = `$${(data.balance || 0).toFixed(2)}`;
            
            allElements.profileBadgeContainer.innerHTML = '';
            
            if (data.isPublisher) {
                const publisherBadge = `<span class="profile-badge publisher-badge"><i class="fas fa-rocket"></i>${t('badge_publisher')}</span>`;
                allElements.profileBadgeContainer.innerHTML += publisherBadge;
            }
            if (data.kycStatus === 'verified') {
                const verifiedBadge = `<span class="profile-badge verified-badge"><i class="fas fa-check-circle"></i>${t('badge_verified')}</span>`;
                allElements.profileBadgeContainer.innerHTML += verifiedBadge;
            }

            // NEW: Logic for showing seller buttons
            if (data.hasStore) {
                allElements.becomeSellerBtn.style.display = 'none';
                allElements.goToMyStoreBtn.style.display = 'flex';
            } else {
                allElements.becomeSellerBtn.style.display = 'flex';
                allElements.goToMyStoreBtn.style.display = 'none';
            }

            if (data.hasUnreadSupportMessage) {
                allElements.supportUnreadCount.style.display = 'flex';
                allElements.supportUnreadCount.textContent = '1';
            } else {
                allElements.supportUnreadCount.style.display = 'none';
            }

            allElements.profileOldPassword.value = '';
            allElements.profileNewPassword.value = '';
        };

        const populateAdList = (listElement, adData, adType) => {
            const user = getCurrentUser();
            if (!user) { listElement.innerHTML = `<p style="color:white; text-align:center; grid-column: 1 / -1;">Please log in to see tasks.</p>`; return; }
            const userData = appState.userData[user.email];
            if (!userData) return;

            listElement.innerHTML = '';
            if (adData.length === 0) { listElement.innerHTML = `<p style="color:white; text-align:center; grid-column: 1 / -1;">No ads available right now.</p>`; return; }

            adData.forEach(ad => {
                const li = document.createElement('li');
                li.className = 'ad-list-item';
                const isCompleted = userData.completedTasks?.includes(ad.id);
                const rewardText = `+$${ad.reward.toFixed(3)}`;
                
                let iconClass = 'fas'; 
                if(['youtube', 'facebook', 'tiktok', 'instagram'].includes(ad.platform?.toLowerCase())) {
                    iconClass = 'fab';
                }
                
                let iconHtml = `<i class="${iconClass} ${ad.icon}"></i>`;
                let mainContent = ad.type === 'ad' ? `<p>${ad.title}</p>` : `<p>${ad.platform}: ${ad.action}</p><p class="task-target">${ad.target}</p>`;
                let buttonHtml = ad.type === 'ad' ? `<button class="btn ad-action-btn watch-btn" data-id="${ad.id}" data-reward="${ad.reward}">Earn ${rewardText}</button>`
                                                : `<button class="btn ad-action-btn task-btn" data-id="${ad.id}" data-reward="${ad.reward}" data-title="${ad.platform}: ${ad.action}" ${isCompleted ? 'disabled' : ''}>${isCompleted ? 'Done' : `Do (${rewardText})`}</button>`;
                
                li.innerHTML = `<div class="ad-icon-container">${iconHtml}</div><div class="ad-info">${mainContent}</div>${buttonHtml}`;
                listElement.appendChild(li);
            });
        };

        const resetDepositPage = () => { if (window.depositTimer) { clearInterval(window.depositTimer); window.depositTimer = null; } if (allElements.paymentDetailsForm) { allElements.paymentDetailsForm.style.display = 'none'; document.querySelectorAll('#deposit-methods-grid .method-card').forEach(c => c.classList.remove('active')); allElements.depositForm.reset(); allElements.cihScreenshotUploadGroup.style.display = 'none'; allElements.screenshotFilename.textContent = ''; allElements.confirmDepositBtn.disabled = false; allElements.qrCodeContainer.style.display = 'none'; allElements.depositTimerDisplay.style.display = 'none'; } };
        const resetWithdrawPage = () => { if (allElements.withdrawalDetailsForm) { allElements.withdrawalDetailsForm.style.display = 'none'; document.querySelectorAll('#withdraw-methods-grid .method-card').forEach(c => c.classList.remove('active')); allElements.withdrawForm.reset(); allElements.specificWithdrawFields.forEach(f => f.style.display = 'none'); } };
        const resetForgotPasswordPage = () => { if (allElements.forgotStep1Form) { allElements.forgotStep1Form.style.display = 'block'; allElements.forgotStep2Form.style.display = 'none'; allElements.forgotStep3Form.style.display = 'none'; allElements.forgotMessage.textContent = ''; allElements.forgotStep1Form.reset(); allElements.forgotStep2Form.reset(); allElements.forgotStep3Form.reset(); appState.recoveryEmail = null; } };
        
        // =================================================================
        // 4. CORE APP LOGIC & HELPERS
        // =================================================================
        const getCurrentUser = () => appState.users.find(u => u.email === appState.currentUserEmail);
        const setLanguage = (lang) => { currentLanguage = lang; localStorage.setItem('app_language', lang); if(allElements.langDropdown) allElements.langDropdown.classList.remove('show'); applyTranslations(); };
        const startAdTimer = (adId, reward, fromPageId) => { showPage('watch-ad-page'); allElements.watchAdBackBtn.dataset.target = fromPageId; clearInterval(window.adTimer); allElements.claimRewardBtn.style.display = 'none'; allElements.claimRewardBtn.dataset.reward = reward; allElements.claimRewardBtn.dataset.id = adId; allElements.timerDisplay.querySelector('p').innerHTML = `${t('time_remaining')} <span id="countdown">30</span>s`; let countdown = 30; window.adTimer = setInterval(() => { countdown--; const countdownEl = document.getElementById('countdown'); if (countdownEl) countdownEl.textContent = countdown; if (countdown <= 0) { clearInterval(window.adTimer); allElements.timerDisplay.querySelector('p').textContent = 'Ad finished!'; allElements.claimRewardBtn.style.display = 'flex'; } }, 1000); };
        
        const openPackageModal = (packageName, price) => { window.currentPackageData = { name: packageName, price: price }; const labelTextMap = { youtube: "YouTube Channel URL", facebook: "Facebook Page URL", tiktok: "TikTok Profile URL", instagram: "Instagram Profile URL" }; const placeholderTextMap = { youtube: "https://youtube.com/channel/...", facebook: "https://facebook.com/yourpage...", tiktok: "https://tiktok.com/@yourprofile...", instagram: "https://instagram.com/yourprofile..." }; allElements.packageUrlPage.placeholder = placeholderTextMap[packageName] || "https://..."; allElements.packageUrlPageLabel.textContent = labelTextMap[packageName] || "Main Page/Channel URL"; allElements.modalTitle.textContent = `Setup ${packageName.charAt(0).toUpperCase() + packageName.slice(1)} Campaign`; allElements.packageModal.style.display = 'flex'; };
        const closePackageModal = () => { allElements.packageModal.style.display = 'none'; allElements.packagePurchaseForm.reset(); };
        const processReferralCommission = (referredUser, taskReward) => { if (!referredUser || !referredUser.referredBy) return; const referrer = appState.users.find(u => u.referralCode === referredUser.referredBy); if (!referrer || !appState.userData[referrer.email]) return; const referrerData = appState.userData[referrer.email]; const commission = taskReward * 0.03; referrerData.balance += commission; referrerData.referralEarnings = (referrerData.referralEarnings || 0) + commission; referrerData.history.push({ type: 'Task Commission', reward: commission, date: new Date().toISOString(), from: referredUser.name }); };
        const runDailyChecks = () => { const today = new Date().toISOString().split('T')[0]; if (appState.lastDailyReset === today) { return; } Object.keys(appState.userData).forEach(email => { appState.userData[email].completedTasks = []; }); appState.lastDailyReset = today; saveState(); if (appState.currentUserEmail) { showNotification(t('daily_reset_notification'), 'success'); } };

        // --- KYC Modal Logic ---
        const showKycStep = (stepId) => { allElements.kycSteps.forEach(step => step.classList.remove('active')); document.getElementById(stepId).classList.add('active'); };
        const openKycModal = () => { const user = getCurrentUser(); if (!user) return; const userData = appState.userData[user.email]; resetKycModal(); if (userData.kycStatus === 'verified') { showKycStep('kyc-step-verified'); } else if (userData.kycStatus === 'pending') { showKycStep('kyc-step-pending'); } else { showKycStep('kyc-step-intro'); } allElements.kycModal.style.display = 'flex'; };
        const closeKycModal = () => { allElements.kycModal.style.display = 'none'; };
        const resetKycModal = () => { allElements.idFrontPreview.style.display = 'none'; allElements.idBackPreview.style.display = 'none'; allElements.idFrontPreview.src = ''; allElements.idBackPreview.src = ''; allElements.kycIdFrontUpload.value = ''; allElements.kycIdBackUpload.value = ''; allElements.kycNextBtn.disabled = true; allElements.kycSubmitBtn.disabled = true; };
        const handleKycFileUpload = (event, previewElement, nextButton) => { const file = event.target.files[0]; if (file) { const reader = new FileReader(); reader.onload = (e) => { previewElement.src = e.target.result; previewElement.style.display = 'block'; nextButton.disabled = false; }; reader.readAsDataURL(file); } };

        // --- Global Chat Logic ---
        const openChatModal = () => { updateChatUI(); allElements.chatModal.style.display = 'flex'; allElements.chatMessagesContainer.scrollTop = allElements.chatMessagesContainer.scrollHeight; };
        const closeChatModal = () => { allElements.chatModal.style.display = 'none'; };
        const updateChatUI = () => {
            const container = allElements.chatMessagesContainer; container.innerHTML = ''; const currentUser = getCurrentUser(); if (!currentUser) return;
            appState.chatMessages.forEach(msg => {
                const isCurrentUser = msg.sender === currentUser.name; const messageEl = document.createElement('div'); messageEl.className = `chat-message ${isCurrentUser ? 'current-user' : ''}`;
                let badgesHtml = '';
                if (msg.isPublisher) { badgesHtml += `<span class="profile-badge publisher-badge chat-badge"><i class="fas fa-rocket"></i></span>`; }
                if (msg.isVerified) { badgesHtml += `<span class="profile-badge verified-badge chat-badge"><i class="fas fa-check-circle"></i></span>`; }
                messageEl.innerHTML = `<img src="${msg.avatar}" alt="${msg.sender}" class="chat-avatar"><div class="message-content"><div class="message-sender-info"><span>${msg.sender}</span>${badgesHtml}</div><div class="message-bubble"><p class="message-text">${msg.text.replace(/</g, "&lt;").replace(/>/g, "&gt;")}</p><div class="message-time">${new Date(msg.time).toLocaleTimeString([], { hour: '2-digit', minute: '2-digit' })}</div></div></div>`;
                container.appendChild(messageEl);
            });
            container.scrollTop = container.scrollHeight;
        };
        const handleSendMessage = (e) => {
            e.preventDefault(); const input = allElements.chatInput; const text = input.value.trim(); if (!text) return;
            const currentUser = getCurrentUser(); const currentUserData = appState.userData[currentUser.email]; if (!currentUser) return;
            const newMessage = { sender: currentUser.name, text: text, time: new Date().toISOString(), avatar: currentUserData.profilePicture || defaultProfilePicture, isVerified: currentUserData.kycStatus === 'verified', isPublisher: currentUserData.isPublisher };
            appState.chatMessages.push(newMessage); saveState(); updateChatUI(); input.value = ''; input.focus();
        };

        // --- Support Chat Logic ---
        const openSupportChatModal = () => { const user = getCurrentUser(); if(!user) return; const userData = appState.userData[user.email]; userData.hasUnreadSupportMessage = false; saveState(); updateProfileUI(); updateSupportChatUI(); allElements.supportChatModal.style.display = 'flex'; allElements.supportChatMessagesContainer.scrollTop = allElements.supportChatMessagesContainer.scrollHeight; };
        const closeSupportChatModal = () => { allElements.supportChatModal.style.display = 'none'; };
        const updateSupportChatUI = () => {
            const container = allElements.supportChatMessagesContainer; container.innerHTML = ''; const currentUser = getCurrentUser(); if (!currentUser) return;
            const chatHistory = appState.userData[currentUser.email]?.supportChat || [];
            chatHistory.forEach(msg => {
                const isCurrentUser = msg.sender !== SUPPORT_AGENT.name; const messageEl = document.createElement('div'); messageEl.className = `chat-message ${isCurrentUser ? 'current-user' : ''}`;
                messageEl.innerHTML = `<img src="${isCurrentUser ? (appState.userData[currentUser.email].profilePicture || defaultProfilePicture) : SUPPORT_AGENT.avatar}" class="chat-avatar"><div class="message-content"><div class="message-sender-info">${isCurrentUser ? currentUser.name : SUPPORT_AGENT.name}</div><div class="message-bubble"><p class="message-text">${msg.text.replace(/</g, "&lt;").replace(/>/g, "&gt;")}</p><div class="message-time">${new Date(msg.time).toLocaleTimeString([], { hour: '2-digit', minute: '2-digit' })}</div></div></div>`;
                container.appendChild(messageEl);
            });
            container.scrollTop = container.scrollHeight;
        };
        const handleSendSupportMessage = (e) => { e.preventDefault(); const input = allElements.supportChatInput; const text = input.value.trim(); if (!text) return; const currentUser = getCurrentUser(); if (!currentUser) return; const userData = appState.userData[currentUser.email]; const userMessage = { sender: currentUser.name, text: text, time: new Date().toISOString() }; if (!userData.supportChat) userData.supportChat = []; userData.supportChat.push(userMessage); updateSupportChatUI(); input.value = ''; input.focus(); setTimeout(() => { const autoReply = { sender: SUPPORT_AGENT.name, text: "Your message has been received. Our team will get back to you shortly.", time: new Date().toISOString() }; userData.supportChat.push(autoReply); saveState(); updateSupportChatUI(); }, 1000); saveState(); };

        // =================================================================
        // 5. EVENT LISTENERS & HANDLERS
        // =================================================================

        const setupEventListeners = () => {
            allElements.showRegister.addEventListener('click', (e) => { e.preventDefault(); allElements.loginFormContainer.style.display = 'none'; allElements.registerForm.style.display = 'block'; });
            allElements.showLogin.addEventListener('click', (e) => { e.preventDefault(); allElements.registerForm.style.display = 'none'; allElements.loginFormContainer.style.display = 'block'; });
            allElements.showForgotPassword.addEventListener('click', (e) => { e.preventDefault(); showPage('forgot-password-page'); });
            allElements.loginForm.addEventListener('submit', handleLogin);
            allElements.registerFormActual.addEventListener('submit', handleRegister);
            allElements.forgotStep1Form.addEventListener('submit', handleForgotStep1);
            allElements.forgotStep2Form.addEventListener('submit', handleForgotStep2);
            allElements.forgotStep3Form.addEventListener('submit', handleForgotStep3);
            allElements.navItems.forEach(item => item.addEventListener('click', e => { e.preventDefault(); showPage(item.dataset.page); }));
            document.body.addEventListener('click', e => { 
                const backBtn = e.target.closest('.back-btn'); 
                if (backBtn && backBtn.dataset.target) { e.preventDefault(); showPage(backBtn.dataset.target); }
                const storeCard = e.target.closest('.store-entry-card');
                if (storeCard && storeCard.dataset.target) { e.preventDefault(); showPage(storeCard.dataset.target); }
            });
            allElements.quickAccessGrid.addEventListener('click', e => { const targetItem = e.target.closest('.icon-item'); if (targetItem) { e.preventDefault(); showPage(targetItem.dataset.target); } });
            document.querySelectorAll('.ad-list-container').forEach(container => container.addEventListener('click', handleAdClick));
            allElements.claimRewardBtn.addEventListener('click', handleClaimReward);
            allElements.logoutBtn.addEventListener('click', handleLogout);
            allElements.profileForm.addEventListener('submit', handleProfileUpdate);
            allElements.profilePictureUpload.addEventListener('change', handleProfilePictureChange);
            allElements.dashboardPackagesBtn.addEventListener('click', () => showPage('packages-page'));
            allElements.profilePackagesBtn.addEventListener('click', () => showPage('packages-page'));
            allElements.publishersViewPackagesBtn.addEventListener('click', () => showPage('packages-page'));
            allElements.showPublishersLink.addEventListener('click', (e) => { e.preventDefault(); showPage('publishers-page'); });
            allElements.goToCreateAdBtn.addEventListener('click', () => showPage('create-ad-page'));
            allElements.createAdForm.addEventListener('submit', handleCreateAd);
            allElements.adTypeSelect.addEventListener('change', () => { const selectedType = allElements.adTypeSelect.value; allElements.specificAdFields.forEach(f => { f.style.display = 'none'; f.querySelectorAll('input,select').forEach(i => i.required = false); }); if (selectedType) { const target = document.getElementById(`${selectedType}-ad-fields`); if(target) { target.style.display = 'block'; target.querySelectorAll('input,select').forEach(i => i.required = true); } } });
            ['input', 'change'].forEach(evt => { allElements.campaignBudget.addEventListener(evt, updateReach); allElements.rewardPerAction.addEventListener(evt, updateReach); });
            allElements.termsCheckbox.addEventListener('change', () => { allElements.createAdSubmitBtn.disabled = !allElements.termsCheckbox.checked; });
            allElements.depositMethodsGrid.addEventListener('click', handleDepositMethodSelect);
            allElements.depositForm.addEventListener('submit', handleDepositSubmit);
            allElements.cihScreenshotUpload.addEventListener('change', (e) => { const file = e.target.files[0]; if(file) allElements.screenshotFilename.textContent = `Selected: ${file.name}`; allElements.confirmDepositBtn.disabled = !file; });
            allElements.withdrawMethodsGrid.addEventListener('click', handleWithdrawMethodSelect);
            allElements.withdrawForm.addEventListener('submit', handleWithdrawSubmit);
            document.getElementById('packages-page').addEventListener('click', (e) => { 
                if(e.target.classList.contains('buy-package-btn')) { 
                    const card = e.target.closest('.package-card'); 
                    openPackageModal(card.dataset.package, parseFloat(card.dataset.price)); 
                }
                if(e.target.classList.contains('restart-campaign-btn')) {
                    handleRestartCampaign(e.target.dataset.package);
                }
            });
            allElements.packageModalCloseBtn.addEventListener('click', closePackageModal);
            allElements.packagePurchaseForm.addEventListener('submit', handlePackagePurchase);
            allElements.langGlobeBtn.addEventListener('click', e => { e.stopPropagation(); allElements.langDropdown.classList.toggle('show'); });
            document.addEventListener('click', () => allElements.langDropdown.classList.remove('show'));
            allElements.langDropdown.addEventListener('click', e => { e.preventDefault(); e.stopPropagation(); const lang = e.target.dataset.lang; if (lang && lang !== currentLanguage) setLanguage(lang); });
            allElements.copyReferralLinkBtn.addEventListener('click', handleCopyReferralLink);
            allElements.shareReferralLinkBtn.addEventListener('click', handleShareReferralLink);

            allElements.kycModalCloseBtn.addEventListener('click', closeKycModal);
            allElements.kycBeginBtn.addEventListener('click', () => showKycStep('kyc-step-front'));
            allElements.kycIdFrontUpload.addEventListener('change', (e) => handleKycFileUpload(e, allElements.idFrontPreview, allElements.kycNextBtn));
            allElements.kycNextBtn.addEventListener('click', () => showKycStep('kyc-step-back'));
            allElements.kycIdBackUpload.addEventListener('change', (e) => handleKycFileUpload(e, allElements.idBackPreview, allElements.kycSubmitBtn));
            allElements.kycSubmitBtn.addEventListener('click', handleKycSubmit);
            allElements.kycDoneBtn.addEventListener('click', closeKycModal);

            allElements.chatFab.addEventListener('click', openChatModal);
            allElements.chatModalCloseBtn.addEventListener('click', closeChatModal);
            allElements.chatInputForm.addEventListener('submit', handleSendMessage);
            
            allElements.supportFab.addEventListener('click', openSupportChatModal);
            allElements.supportChatModalCloseBtn.addEventListener('click', closeSupportChatModal);
            allElements.supportChatInputForm.addEventListener('submit', handleSendSupportMessage);
            
            // Event listener for the main store page (delegated)
            if (allElements.storePage) {
                allElements.storePage.addEventListener('click', handleStorePurchase);
            }

            // NEW EVENT LISTENERS for USER STORES
            allElements.becomeSellerBtn.addEventListener('click', handleBecomeSeller);
            allElements.goToMyStoreBtn.addEventListener('click', () => showPage('my-store-page'));
            allElements.myStoreForm.addEventListener('submit', handleUpdateStoreDetails);
            allElements.addProductBtn.addEventListener('click', () => allElements.addProductModal.style.display = 'flex');
            allElements.addProductModalCloseBtn.addEventListener('click', () => allElements.addProductModal.style.display = 'none');
            allElements.addProductForm.addEventListener('submit', handleAddProduct);
        };

        function handleStorePurchase(e) {
            const buyBtn = e.target.closest('.buy-now-btn');
            if (buyBtn) {
                e.preventDefault();
                const productCard = buyBtn.closest('.product-card');
                const productId = productCard.dataset.productId;
                const productPrice = parseFloat(productCard.dataset.price);
                const isUserProduct = productCard.dataset.isUserProduct === 'true';

                const user = getCurrentUser();
                if (!user) {
                    showNotification("Please log in to make a purchase.", 'error');
                    return;
                }
                
                const productName = productCard.querySelector('.product-name').textContent;
                const sellerEmail = productCard.dataset.sellerEmail;
                if(isUserProduct && user.email === sellerEmail) {
                    showNotification("You cannot purchase your own product.", 'error');
                    return;
                }

                const userData = appState.userData[user.email];
                if (userData.balance < productPrice) {
                    showNotification(t('alert_insufficient_balance'), 'error');
                    showPage('deposit-page');
                    return;
                }

                // Deduct balance and record transaction
                userData.balance -= productPrice;
                userData.history.push({
                    type: `Purchased: ${productName}`,
                    reward: -productPrice,
                    date: new Date().toISOString()
                });

                // If it's a user product, credit the seller (minus a commission)
                if (isUserProduct) {
                    const sellerData = appState.userData[sellerEmail];
                    if (sellerData) {
                        const commission = 0.10; // 10% commission
                        const earnings = productPrice * (1 - commission);
                        sellerData.balance += earnings;
                        sellerData.history.push({
                           type: `Sale: ${productName}`,
                           reward: earnings,
                           date: new Date().toISOString()
                        });
                    }
                }

                saveState();
                updateDashboardUI(); // Refresh balance display

                showNotification(`Successfully purchased for $${productPrice.toFixed(2)}!`, 'success');
            }
        }
        
        function handleLogin(e) { e.preventDefault(); const email = allElements.loginForm.querySelector('#login-email').value.toLowerCase(); const password = allElements.loginForm.querySelector('#login-password').value; const user = appState.users.find(u => u.email === email && u.password === password); if (user) { appState.currentUserEmail = email; if (!appState.userData[email]) { appState.userData[email] = JSON.parse(JSON.stringify(defaultUserData)); } if(!appState.userStores[email] && appState.userData[email].hasStore) { appState.userStores[email] = { storeName: `${user.name}'s Store`, storeDescription: '', products: [] }; } runDailyChecks(); startActiveCampaignSimulations(email); saveState(); showPage('dashboard-page'); allElements.loginForm.reset(); } else { showNotification(t('alert_invalid_creds'), 'error'); } }
        function handleRegister(e) { e.preventDefault(); const name = allElements.registerFormActual.querySelector('#register-name').value; const email = allElements.registerFormActual.querySelector('#register-email').value.toLowerCase(); const password = allElements.registerFormActual.querySelector('#register-password').value; if (password !== allElements.registerFormActual.querySelector('#register-confirm-password').value) { showNotification(t('alert_pass_nomatch'), 'error'); return; } if (appState.users.some(u => u.email === email)) { showNotification(t('alert_email_exists'), 'error'); return; } const referralCode = name.replace(/\s+/g, '').toLowerCase() + Math.floor(Math.random() * 900 + 100); const newUser = { name, email, password, referralCode }; const urlParams = new URLSearchParams(window.location.search); const refCode = urlParams.get('ref'); if (refCode) { const referrer = appState.users.find(u => u.referralCode === refCode); if (referrer && appState.userData[referrer.email]) { newUser.referredBy = refCode; const referralBonus = 0.05; const referrerData = appState.userData[referrer.email]; referrerData.balance += referralBonus; referrerData.referralEarnings = (referrerData.referralEarnings || 0) + referralBonus; referrerData.referredUsersCount = (referrerData.referredUsersCount || 0) + 1; referrerData.history.push({ type: 'Referral Bonus', reward: referralBonus, date: new Date().toISOString() }); } } appState.users.push(newUser); appState.userData[email] = JSON.parse(JSON.stringify(defaultUserData)); const welcomeMessage = { sender: SUPPORT_AGENT.name, text: "Welcome to Make Money & Traffic! If you need any help, just ask here.", time: new Date().toISOString() }; appState.userData[email].supportChat.push(welcomeMessage); appState.currentUserEmail = email; saveState(); showPage('dashboard-page'); allElements.registerFormActual.reset(); if (refCode) { history.replaceState(null, '', window.location.pathname); } }
        function handleLogout() { appState.currentUserEmail = null; Object.values(window.campaignSimulators).forEach(clearInterval); window.campaignSimulators = {}; saveState(); showPage('auth-page'); }
        function handleForgotStep1(e) { e.preventDefault(); const email = document.getElementById('forgot-email').value.toLowerCase(); const userExists = appState.users.some(u => u.email === email); if (userExists && appState.userData[email]?.dob) { appState.recoveryEmail = email; allElements.forgotStep1Form.style.display = 'none'; allElements.forgotStep2Form.style.display = 'block'; allElements.forgotMessage.textContent = ''; } else { allElements.forgotMessage.textContent = userExists ? 'Date of Birth not set. Cannot recover.' : 'No account found with that email.'; } }
        function handleForgotStep2(e) { e.preventDefault(); const dob = document.getElementById('forgot-dob').value; if (appState.recoveryEmail && appState.userData[appState.recoveryEmail]?.dob === dob) { allElements.forgotStep2Form.style.display = 'none'; allElements.forgotStep3Form.style.display = 'block'; allElements.forgotMessage.textContent = ''; } else { allElements.forgotMessage.textContent = 'Incorrect date of birth.'; } }
        function handleForgotStep3(e) { e.preventDefault(); const newPassword = document.getElementById('forgot-new-password').value; if (newPassword !== document.getElementById('forgot-confirm-password').value) { allElements.forgotMessage.textContent = t('alert_pass_nomatch'); return; } const userIndex = appState.users.findIndex(u => u.email === appState.recoveryEmail); if (userIndex !== -1) { appState.users[userIndex].password = newPassword; saveState(); showNotification('Password reset successfully!', 'success'); showPage('auth-page'); } else { allElements.forgotMessage.textContent = 'An unexpected error occurred.'; } }
        function handleAdClick(e) { const targetBtn = e.target.closest('.ad-action-btn'); if (!targetBtn || targetBtn.disabled) return; const user = getCurrentUser(); if (!user) { showNotification("Session expired. Please log in.", 'error'); showPage('auth-page'); return; } const userData = appState.userData[user.email]; const adId = targetBtn.dataset.id; if (userData.completedTasks.includes(adId)) { showNotification("You have already completed this task today.", "info"); return; } const fromPageId = targetBtn.closest('.page').id; if (targetBtn.classList.contains('watch-btn')) { startAdTimer(adId, targetBtn.dataset.reward, fromPageId); } else if (targetBtn.classList.contains('task-btn')) { const taskId = targetBtn.dataset.id; const taskState = targetBtn.dataset.taskState; if (taskState === 'pending') { const reward = parseFloat(targetBtn.dataset.reward); userData.balance += reward; userData.history.push({ type: `Task: ${targetBtn.dataset.title}`, reward: reward, date: new Date().toISOString() }); userData.completedTasks.push(taskId); processReferralCommission(user, reward); saveState(); showNotification(t('alert_earned_reward', { amount: `$${reward.toFixed(3)}` }), 'success'); showPage(fromPageId); } else { const ad = appState.ads.task.find(a => a.id === taskId); if (ad && ad.target) { window.open(ad.target.startsWith('http') ? ad.target : `https://${ad.target}`, '_blank'); targetBtn.dataset.taskState = 'pending'; targetBtn.innerHTML = `<i class="fas fa-check"></i> Verify Completion`; targetBtn.style.backgroundColor = 'var(--warning-color)'; showNotification("Complete the task in the new tab, then return and click 'Verify Completion'.", 'info'); } else { showNotification("Task target URL not found.", 'error'); } } } }
        function handleClaimReward() { const user = getCurrentUser(); if (!user) return; const reward = parseFloat(allElements.claimRewardBtn.dataset.reward); const adId = allElements.claimRewardBtn.dataset.id; const fromPageId = allElements.watchAdBackBtn.dataset.target; appState.userData[user.email].balance += reward; appState.userData[user.email].history.push({ type: 'Watched Ad', reward: reward, date: new Date().toISOString() }); if(adId) appState.userData[user.email].completedTasks.push(adId); processReferralCommission(user, reward); saveState(); showNotification(t('alert_earned_reward', { amount: `$${reward.toFixed(3)}` }), 'success'); showPage(fromPageId || 'dashboard-page'); }
        function handleProfileUpdate(e) { e.preventDefault(); const user = getCurrentUser(); if (!user) return; const userIndex = appState.users.findIndex(u => u.email === user.email); if (userIndex === -1) return; const oldPass = allElements.profileOldPassword.value, newPass = allElements.profileNewPassword.value; if (newPass) { if (!oldPass || oldPass !== user.password) { showNotification('Old password does not match.', 'error'); return; } appState.users[userIndex].password = newPass; } appState.users[userIndex].name = allElements.profileName.value; appState.userData[user.email].phone = allElements.profilePhone.value; appState.userData[user.email].dob = allElements.profileDob.value; appState.userData[user.email].gender = allElements.profileGender.value; appState.userData[user.email].address = allElements.profileAddress.value; saveState(); showNotification('Profile updated successfully!', 'success'); updateProfileUI(); }
        function handleProfilePictureChange(e) { const user = getCurrentUser(); if (!user) return; const file = e.target.files[0]; if (file) { const reader = new FileReader(); reader.onload = (event) => { allElements.profilePicture.src = event.target.result; appState.userData[user.email].profilePicture = event.target.result; saveState(); }; reader.readAsDataURL(file); } }
        
        function handleKycSubmit() { const user = getCurrentUser(); if (!user) return; const userData = appState.userData[user.email]; userData.kycData = { idFront: allElements.idFrontPreview.src, idBack: allElements.idBackPreview.src }; userData.kycStatus = 'pending'; userData.history.push({ type: 'KYC Submission', reward: 0, date: new Date().toISOString() }); saveState(); updateProfileUI(); showKycStep('kyc-step-pending'); setTimeout(() => { if (getCurrentUser() && appState.userData[user.email].kycStatus === 'pending') { appState.userData[user.email].kycStatus = 'verified'; saveState(); updateProfileUI(); if(allElements.kycModal.style.display === 'flex') { showKycStep('kyc-step-verified'); } showNotification('Your KYC has been successfully verified!', 'success'); } }, 5000); }

        function updateReach() { const budget = parseFloat(allElements.campaignBudget.value); const reward = parseFloat(allElements.rewardPerAction.value); const profitMargin = 0.40; const distributableBudget = budget * (1 - profitMargin); allElements.estimatedReach.textContent = (budget > 0 && reward > 0) ? Math.floor(distributableBudget / reward) : '---'; }
        function handleCreateAd(e) { e.preventDefault(); const user = getCurrentUser(); if (!user) return; const budget = parseFloat(allElements.campaignBudget.value), reward = parseFloat(allElements.rewardPerAction.value), adType = allElements.adTypeSelect.value; if (!allElements.termsCheckbox.checked) { showNotification('You must agree to the terms.', 'error'); return; } if (budget < 1 || reward < 0.001) { showNotification('Budget must be at least $1 and reward must be at least $0.001.', 'error'); return; } if (appState.userData[user.email].balance < budget) { showNotification(t('alert_insufficient_balance'), 'error'); return; } appState.userData[user.email].balance -= budget; appState.userData[user.email].history.push({ type: `Ad Campaign (${adType})`, reward: -budget, date: new Date().toISOString() }); if (!appState.userData[user.email].isPublisher) { appState.userData[user.email].isPublisher = true; appState.userData[user.email].history.push({ type: 'Publisher Status Unlocked', reward: 0, date: new Date().toISOString() }); } const profitMargin = 0.40; const distributableBudget = budget * (1 - profitMargin); const reach = Math.floor(distributableBudget / reward); for (let i = 0; i < reach; i++) { const newAd = { id: `${adType}_${Date.now()}_${i}`, reward }; if (adType === 'video') { Object.assign(newAd, { type: 'ad', title: `${allElements.videoTitle.value}`, icon: 'fa-play-circle' }); appState.ads.video.unshift(newAd); } else if (adType === 'banner') { Object.assign(newAd, { type: 'ad', title: `${allElements.bannerTitle.value}`, icon: 'fa-image' }); appState.ads.banner.unshift(newAd); } else if (adType === 'task') { const platform = allElements.taskPlatform.value; Object.assign(newAd, { type: 'task', platform, target: allElements.taskTarget.value, action: allElements.taskAction.value, icon: `fa-${platform.toLowerCase()}` }); appState.ads.task.unshift(newAd); } } saveState(); showNotification('Your ad campaign has been created!', 'success'); showPage('dashboard-page'); }
        
        function handleDepositMethodSelect(e) { const card = e.target.closest('.method-card'); if (!card) return; if (window.depositTimer) { clearInterval(window.depositTimer); } window.selectedDepositMethod = card.dataset.method; document.querySelectorAll('#deposit-methods-grid .method-card').forEach(c => c.classList.remove('active')); card.classList.add('active'); allElements.paymentDetailsForm.style.display = 'block'; const minDeposits = { 'cih': 1, 'binance-pay': 1, 'paypal': 1, 'payeer': 1 }; const minAmount = minDeposits[window.selectedDepositMethod] || 10; allElements.depositAmount.min = minAmount; allElements.depositAmount.placeholder = t('min_deposit', { amount: `$${minAmount.toFixed(2)}` }); const methodMap = { cih: "Titulaire: Make Money & traffic\nRIB: 230 480 4344228211021600 14", bitcoin: 'bc1qnnq0l4h20pzdgwh6jc9rk79g96lmwcymqwzn5y', 'usdt-trc20': 'TNf6J3YPgARUQdWWPaZmL6zk4c7o3yyuKC', 'usdt-bep20': '0x23C9c91e334a095563c927E205531D4E38e8FAc0', 'pi-network': 'GDPK5CKSH4265J4AL75CASKNUVHZWLSOKH42DKAGW47PUSI3HGNMECVZ', paypal: "payment@example.com", payeer: 'P12345678', 'binance-pay': 'Pay ID: 987654321', wise: 'wise@example.com', skrill: 'skrill@example.com', 'perfect-money': 'U1234567' }; const address = methodMap[window.selectedDepositMethod] || "Details for " + window.selectedDepositMethod; allElements.depositInstructions.textContent = `Please transfer to:\n${address}`; allElements.depositInstructions.style.display = 'block'; allElements.cihScreenshotUploadGroup.style.display = window.selectedDepositMethod === 'cih' ? 'block' : 'none'; allElements.confirmDepositBtn.disabled = window.selectedDepositMethod === 'cih'; allElements.qrCodeContainer.style.display = ['bitcoin', 'usdt-trc20', 'usdt-bep20', 'pi-network'].includes(window.selectedDepositMethod) ? 'block' : 'none'; if(allElements.qrCodeContainer.style.display === 'block') allElements.qrCodeImg.src = `https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=${encodeURIComponent(address)}`; const endTime = Date.now() + 60 * 60 * 1000; allElements.depositTimerDisplay.style.display = 'block'; window.depositTimer = setInterval(() => { const remaining = Math.round((endTime - Date.now()) / 1000); if (remaining <= 0) { clearInterval(window.depositTimer); window.depositTimer = null; showNotification(t('deposit_session_expired'), 'info'); showPage('dashboard-page'); } else { const minutes = Math.floor(remaining / 60); const seconds = remaining % 60; allElements.depositCountdown.textContent = `${String(minutes).padStart(2, '0')}:${String(seconds).padStart(2, '0')}`; } }, 1000); }
        function handleDepositSubmit(e) { e.preventDefault(); if (window.depositTimer) { clearInterval(window.depositTimer); window.depositTimer = null; } const user = getCurrentUser(); if (!user) return; const amount = parseFloat(allElements.depositAmount.value); const minAmount = parseFloat(allElements.depositAmount.min); if (amount < minAmount) { showNotification(`Minimum deposit for this method is $${minAmount.toFixed(2)}`, 'error'); return; } if (window.selectedDepositMethod === 'cih' && !allElements.cihScreenshotUpload.files[0]) { showNotification('Please upload a screenshot for CIH deposits.', 'error'); return; } appState.userData[user.email].balance += amount; appState.userData[user.email].history.push({ type: `Deposit`, method: window.selectedDepositMethod, reward: amount, date: new Date().toISOString() }); saveState(); showNotification(`$${amount.toFixed(2)} deposit request received. It will be reviewed shortly.`, 'success'); resetDepositPage(); showPage('dashboard-page'); }
        function handleWithdrawMethodSelect(e) { const card = e.target.closest('.method-card'); if (!card) return; window.selectedWithdrawalMethod = card.dataset.method; document.querySelectorAll('#withdraw-methods-grid .method-card').forEach(c => c.classList.remove('active')); card.classList.add('active'); allElements.withdrawalDetailsForm.style.display = 'block'; allElements.specificWithdrawFields.forEach(field => { const isTarget = field.id === `${window.selectedWithdrawalMethod}-fields`; field.style.display = isTarget ? 'block' : 'none'; field.querySelectorAll('input, select').forEach(i => i.required = isTarget); }); }
        function handleWithdrawSubmit(e) { e.preventDefault(); const user = getCurrentUser(); if (!user) return; const userData = appState.userData[user.email]; if (userData.kycStatus !== 'verified') { showNotification(t('kyc_withdrawal_required'), 'info'); openKycModal(); return; } const amount = parseFloat(allElements.withdrawAmount.value); const userBalance = userData.balance || 0; if (amount < 5) { showNotification('Minimum withdrawal is $5.00', 'error'); return; } if (amount > userBalance) { showNotification('Insufficient balance.', 'error'); return; } userData.balance -= amount; userData.history.push({ type: 'Withdrawal Request', method: window.selectedWithdrawalMethod, reward: -amount, date: new Date().toISOString() }); saveState(); showNotification(`Withdrawal request for $${amount.toFixed(2)} submitted.`, 'success'); resetWithdrawPage(); showPage('dashboard-page'); }
        function handlePackagePurchase(e) { e.preventDefault(); const user = getCurrentUser(); if (!user) return; const { name, price } = window.currentPackageData; const userData = appState.userData[user.email]; const userBalance = userData?.balance || 0; if (userBalance < price) { showNotification(t('alert_insufficient_balance'), 'error'); closePackageModal(); showPage('deposit-page'); return; } const pageUrl = allElements.packageUrlPage.value; const videoUrls = [ allElements.packageUrlVideo1.value, allElements.packageUrlVideo2.value, allElements.packageUrlVideo3.value, ].filter(url => url.trim() !== ''); if (videoUrls.length < 3) { showNotification('Please provide all three video URLs.', 'error'); return; } userData.balance -= price; userData.history.push({ type: `Purchased ${name.charAt(0).toUpperCase() + name.slice(1)} Package`, reward: -price, date: new Date().toISOString() }); if (!userData.isPublisher) { userData.isPublisher = true; userData.history.push({ type: 'Publisher Status Unlocked', reward: 0, date: new Date().toISOString() }); } if (!userData.activeCampaigns) userData.activeCampaigns = {}; userData.activeCampaigns[name] = { packageName: name, isActive: true, isComplete: false, startDate: new Date().toISOString(), requirements: { ...packageRequirements[name] }, progress: Object.keys(packageRequirements[name]).reduce((acc, key) => ({...acc, [key]: 0}), {}) }; startCampaignSimulation(user.email, name); saveState(); showNotification(`${name.charAt(0).toUpperCase() + name.slice(1)} campaign started!`, 'success'); closePackageModal(); setupPackagesPage(); }
        function handleRestartCampaign(packageName) { const user = getCurrentUser(); if (!user || !appState.userData[user.email] || !appState.userData[user.email].activeCampaigns[packageName]) return; delete appState.userData[user.email].activeCampaigns[packageName]; saveState(); setupPackagesPage(); showNotification(`The ${packageName} package is now available for purchase again.`, 'success'); }
        function handleCopyReferralLink() { const link = allElements.referralLinkDisplay.value; if (navigator.clipboard && window.isSecureContext) { navigator.clipboard.writeText(link).then(() => showNotification(t('alert_link_copied'), 'success')); } else { allElements.referralLinkDisplay.select(); document.execCommand('copy'); showNotification(t('alert_link_copied'), 'success'); } }
        function handleShareReferralLink() { const user = getCurrentUser(); if (!user) return; const refLink = allElements.referralLinkDisplay.value; if (navigator.share) { navigator.share({ title: t('refer_earn_title'), text: t('refer_desc'), url: refLink, }).catch(console.error); } else { handleCopyReferralLink(); showNotification('Share not supported, link copied instead.', 'info'); } }

        // --- NEW: USER STORE HANDLERS ---
        function handleBecomeSeller() {
            const user = getCurrentUser(); if (!user) return;
            const userData = appState.userData[user.email];
            userData.hasStore = true;
            appState.userStores[user.email] = {
                storeName: `${user.name}'s Store`,
                storeDescription: 'Welcome to my new store!',
                products: []
            };
            saveState();
            showNotification(t('store_created_success'), 'success');
            showPage('my-store-page');
        }

        function handleUpdateStoreDetails(e) {
            e.preventDefault();
            const user = getCurrentUser(); if (!user) return;
            const userStore = appState.userStores[user.email];
            if (!userStore) return;
            userStore.storeName = allElements.myStoreName.value;
            userStore.storeDescription = allElements.myStoreDescription.value;
            saveState();
            showNotification(t('store_updated_success'), 'success');
        }

        function handleAddProduct(e) {
            e.preventDefault();
            const user = getCurrentUser(); if (!user) return;
            const userStore = appState.userStores[user.email];
            if (!userStore) return;

            const newProduct = {
                id: `prod_${Date.now()}`,
                name: document.getElementById('product-name-input').value,
                description: document.getElementById('product-description-input').value,
                price: parseFloat(document.getElementById('product-price-input').value),
                imageUrl: document.getElementById('product-image-url-input').value,
                sellerEmail: user.email,
                sellerName: user.name
            };

            userStore.products.push(newProduct);
            saveState();
            showNotification(t('product_added_success'), 'success');
            allElements.addProductModal.style.display = 'none';
            allElements.addProductForm.reset();
            updateMyStorePage();
        }

        // =================================================================
        // 6. CAMPAIGN SIMULATION LOGIC
        // =================================================================
        function startCampaignSimulation(userEmail, packageName) {
            const user = appState.users.find(u => u.email === userEmail);
            if (!user || !appState.userData[userEmail] || window.campaignSimulators[packageName]) return;

            const campaign = appState.userData[userEmail].activeCampaigns[packageName];
            if (!campaign || campaign.isComplete) return;

            const intervalId = setInterval(() => {
                const currentCampaign = appState.userData[userEmail].activeCampaigns[packageName];
                if (!currentCampaign || currentCampaign.isComplete) {
                    clearInterval(intervalId);
                    delete window.campaignSimulators[packageName];
                    return;
                }

                let isStillRunning = false;
                Object.keys(currentCampaign.requirements).forEach(key => {
                    const requirement = currentCampaign.requirements[key];
                    const currentProgress = currentCampaign.progress[key];

                    if (currentProgress < requirement) {
                        isStillRunning = true;
                        const increment = Math.ceil(requirement / (Math.random() * 200 + 100));
                        currentCampaign.progress[key] = Math.min(requirement, currentProgress + increment);
                    }
                });

                if (!isStillRunning) {
                    currentCampaign.isComplete = true;
                    clearInterval(intervalId);
                    delete window.campaignSimulators[packageName];
                }
                
                saveState();
                if (document.getElementById('packages-page').classList.contains('active')) {
                    setupPackagesPage();
                }

            }, 2000 + Math.random() * 1000); 

            window.campaignSimulators[packageName] = intervalId;
        }

        function startActiveCampaignSimulations(userEmail) {
            const userData = appState.userData[userEmail];
            if (userData && userData.activeCampaigns) {
                Object.keys(userData.activeCampaigns).forEach(packageName => {
                    if (!userData.activeCampaigns[packageName].isComplete) {
                        startCampaignSimulation(userEmail, packageName);
                    }
                });
            }
        }
        
        // =================================================================
        // 7. PAGE SETUP & INITIALIZATION
        // =================================================================
        function setupPackagesPage() {
            const user = getCurrentUser(); if (!user) return; const userData = appState.userData[user.email]; const activeCampaigns = userData.activeCampaigns || {};
            document.querySelectorAll('.package-card').forEach(card => {
                const packageName = card.dataset.package; const campaign = activeCampaigns[packageName];
                const buyView = card.querySelector('.package-buy-view'); const progressView = card.querySelector('.package-progress-container'); const completeView = card.querySelector('.package-complete-message');
                buyView.style.display = 'none'; progressView.style.display = 'none'; completeView.style.display = 'none';
                if (campaign) {
                    if (campaign.isComplete) {
                        completeView.innerHTML = `<i class="fas fa-check-circle"></i><h4 data-translate-key="pkg_campaign_complete_title">${t('pkg_campaign_complete_title')}</h4><p data-translate-key="pkg_campaign_complete_desc">${t('pkg_campaign_complete_desc')}</p><button class="btn btn-secondary restart-campaign-btn" data-package="${packageName}" data-translate-key="start_new_campaign">${t('start_new_campaign')}</button>`;
                        completeView.style.display = 'block';
                    } else {
                        let progressHTML = `<h4 data-translate-key="pkg_campaign_progress">${t('pkg_campaign_progress')}</h4>`;
                        Object.entries(campaign.requirements).forEach(([key, value]) => {
                            const current = campaign.progress[key]; const percentage = (current / value) * 100;
                            progressHTML += `<div class="progress-item"><div class="progress-item-label"><span>${key}</span><span>${current.toLocaleString()} / ${value.toLocaleString()}</span></div><div class="progress-bar-bg"><div class="progress-bar-fill" style="width: ${percentage}%;"></div></div></div>`;
                        });
                        progressView.innerHTML = progressHTML; progressView.style.display = 'block';
                    }
                } else {
                    const isFriday = new Date().getDay() === 5; const originalPriceEl = card.querySelector('.original-price'); const finalPriceEl = card.querySelector('.final-price'); const discountBadgeEl = card.querySelector('.discount-badge'); const banner = card.querySelector('.friday-deal-banner'); let price = 100;
                    if (isFriday) { const discount = Math.floor(Math.random() * 26) + 5; price = 100 * (1 - discount / 100); banner.style.display = 'block'; originalPriceEl.style.display = 'inline'; discountBadgeEl.textContent = `${discount}% OFF`; discountBadgeEl.style.display = 'inline-block'; } else { banner.style.display = 'none'; originalPriceEl.style.display = 'none'; discountBadgeEl.style.display = 'none'; }
                    finalPriceEl.textContent = `$${price.toFixed(2)}`; card.dataset.price = price; buyView.style.display = 'block';
                }
            });
            applyTranslations();
        }

        // --- NEW: STORE PAGE SETUP ---
        function updateStorePage() {
            const digitalGrid = allElements.digitalStoreGrid;
            const communityGrid = allElements.communityStoreGrid;
            digitalGrid.innerHTML = '';
            communityGrid.innerHTML = '';

            const digitalProducts = [
                { id: 'netflix1m', name: 'Netflix Premium (1 Month)', price: 9.99, brand: 'netflix' },
                { id: 'spotify1m', name: 'Spotify Premium (1 Month)', price: 5.99, brand: 'spotify' },
                { id: 'canva1y', name: 'Canva Pro (1 Year)', price: 49.99, brand: 'canva' },
                { id: 'premium1y', name: 'App Premium (1 Year)', price: 29.99, brand: 'premium' },
            ];
            
            digitalProducts.forEach(product => {
                let logoHtml = '';
                switch (product.brand) {
                    case 'netflix': logoHtml = `<svg viewBox="0 0 113.3 306" xml:space="preserve" fill="#E50914"><path d="M113.3 306V0h-32.2v136.2L32.2 0H0v306h32.2V169.8l48.9 136.2h32.2z"/></svg>`; break;
                    case 'spotify': logoHtml = `<svg viewBox="0 0 24 24" fill-rule="evenodd" clip-rule="evenodd" fill="#1DB954"><path d="M12 0c-6.627 0-12 5.373-12 12s5.373 12 12 12 12-5.373 12-12-5.373-12-12-12zm-3.374 17.84c-.183.296-.58.395-.875.212-.293-.183-.396-.58-.212-.874.578-1.004 1.25-1.74 2.15-2.27.9-.53 2.05-.76 3.2-.67.33.01.6.28.6.61s-.27.6-.6.6c-1.02-.08-1.95.12-2.7.54-.75.42-1.32 1.05-1.813 1.882zm.893-2.348c-.21.353-.664.47-1.016.26-.354-.21-.47-.664-.26-1.016.7-1.156 1.582-1.894 2.658-2.327.9-.36 2.1-.42 3.25-.21.39.07.65.45.58.84-.07.39-.45.65-.84.58-1.02-.18-1.97-.12-2.73.21-.9.42-1.65 1.05-2.242 2.009zm.06-2.583c-.258.42-.71.554-1.13.3-.42-.258-.554-.71-.3-1.13.82-1.34 1.88-2.256 3.16-2.7.9-.32 2.2-.35 3.4-.07.46.1.75.53.65.99-.1.46-.53.75-.99.65-1.05-.24-2.1-.21-2.9.12-.95.42-1.88 1.17-2.54 2.84z"/></svg>`; break;
                    case 'canva': logoHtml = `<svg viewBox="0 0 24 24" fill="#00c4cc"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm3.32 12.38c-.14.44-.45.6-.45.6s-.31.16-.45-.28c-.14-.44.17-.99.45-1.28.28-.28.7-.28.84.14.14.43-.12.82-.39 1.12zm-3.18-5.32c-.44 0-.7.31-.7.7s.26.7.7.7.7-.31.7-.7-.26-.7-.7-.7zm-1.88 5.46c-.14.44-.45.6-.45.6s-.31.16-.45-.28c-.14-.44.17-.99.45-1.28.28-.28.7-.28.84.14.14.43-.12.82-.39 1.12zM12 20c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8z" opacity=".3"></path><path d="M12 4c-4.41 0-8 3.59-8 8s3.59 8 8 8 8-3.59 8 8-3.59-8-8-8zm0 14c-3.31 0-6-2.69-6-6s2.69-6 6-6 6 2.69 6 6-2.69 6-6 6zm-1.74-6.54c.28-.28.7-.28.84.14.14.43-.12.82-.39 1.12-.14.16-.45.28-.45.28s-.31.16-.45-.28c-.14-.44.17-.99.45-1.28zm1.74-2.46c.39 0 .7.31.7.7s-.31.7-.7.7-.7-.31-.7-.7.31-.7.7.7zm3.32 4.08c.28-.28.7-.28.84.14.14.43-.12.82-.39 1.12-.14.16-.45.28-.45.28s-.31.16-.45-.28c-.14-.44.17-.99.45-1.28z"></path></svg>`; break;
                    case 'premium': logoHtml = `<i class="fas fa-star"></i>`; break;
                }
                const card = `<a href="#" class="product-card" data-product-id="${product.id}" data-price="${product.price}">
                                <div class="product-logo ${product.brand}-logo">${logoHtml}</div>
                                <div class="product-info">
                                    <span class="product-name">${product.name}</span>
                                    <span class="product-price">$${product.price.toFixed(2)}</span>
                                </div>
                                <button class="btn buy-now-btn"><i class="fas fa-shopping-cart"></i> <span data-translate-key="buy_now">Buy Now</span></button>
                            </a>`;
                digitalGrid.innerHTML += card;
            });

            const allUserProducts = Object.values(appState.userStores).flatMap(store => store.products);
            if (allUserProducts.length === 0) {
                communityGrid.innerHTML = `<p style="color:white; text-align:center; grid-column: 1 / -1;" data-translate-key="no_community_products">${t('no_community_products')}</p>`;
            } else {
                 allUserProducts.forEach(product => {
                    const card = `<a href="#" class="product-card" data-is-user-product="true" data-seller-email="${product.sellerEmail}" data-product-id="${product.id}" data-price="${product.price}">
                                    <div class="product-logo user-product-logo">
                                        <img src="${product.imageUrl}" alt="${product.name}" onerror="this.src='data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0iI2RkZCI+PHBhdGggZD0iTTE5IDV2MTRINVY1aDE0bTAtMkgrM3YxOGgxOHYtOGwtMy0yaC0zbDItNGgtMnoiLz48L3N2Zz4=';">
                                    </div>
                                    <div class="product-info">
                                        <span class="product-name">${product.name}</span>
                                        <span class="product-seller">by ${product.sellerName}</span>
                                        <span class="product-price">$${product.price.toFixed(2)}</span>
                                    </div>
                                    <button class="btn buy-now-btn"><i class="fas fa-shopping-cart"></i> <span data-translate-key="buy_now">Buy Now</span></button>
                                </a>`;
                    communityGrid.innerHTML += card;
                });
            }
            applyTranslations();
        }

        // --- NEW: MY STORE PAGE SETUP ---
        function updateMyStorePage() {
            const user = getCurrentUser(); if (!user) return;
            const userStore = appState.userStores[user.email];
            if (!userStore) { showPage('profile-page'); return; }

            allElements.myStoreName.value = userStore.storeName;
            allElements.myStoreDescription.value = userStore.storeDescription;
            
            const productList = allElements.myProductsList;
            productList.innerHTML = '';
            if (userStore.products.length === 0) {
                productList.innerHTML = `<p style="text-align:center; color: var(--secondary-color); opacity: 0.8;">You haven't added any products yet.</p>`;
            } else {
                userStore.products.forEach(product => {
                    const li = document.createElement('li');
                    li.className = 'my-product-item';
                    li.innerHTML = `
                        <img src="${product.imageUrl}" alt="${product.name}" onerror="this.src='data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0iI2RkZCI+PHBhdGggZD0iTTE5IDV2MTRINVY1aDE0bTAtMkgrM3YxOGgxOHYtOGwtMy0yaC0zbDItNGgtMnoiLz48L3N2Zz4=';">
                        <div class="my-product-details">
                            <h4>${product.name}</h4>
                            <p>${product.description.substring(0, 50)}...</p>
                        </div>
                        <strong class="my-product-price">$${product.price.toFixed(2)}</strong>
                    `;
                    productList.appendChild(li);
                });
            }
        }
        
        const initApp = () => {
            populateDomElements();
            runDailyChecks(); 
            setLanguage(currentLanguage);

            const newsItems = []; 
            if (allElements.newsTickerContent) allElements.newsTickerContent.innerHTML = newsItems.map(item => `<span><i class="fas fa-bullhorn"></i>${item}</span>`).join('').repeat(2);
            (function createFallingIcons() { const c = allElements.iconRainContainer; if (!c) return; const i = ['fa-youtube', 'fa-facebook', 'fa-tiktok', 'fa-instagram']; for (let n = 0; n < 30; n++) { const e = document.createElement('i'); e.classList.add('fab', i[Math.floor(Math.random() * i.length)], 'falling-icon'); e.style.left = `${Math.random()*100}vw`; e.style.fontSize = `${Math.random()*24+12}px`; e.style.animationDuration = `${Math.random()*3+2}s`; e.style.animationDelay = `${Math.random()*3}s`; c.appendChild(e); } })();
            (function startPercentageLoader() { const e = allElements.loaderPercentage; if (!e) return; let t = 0; const n = setInterval(() => { t++; e.textContent = `${t}%`; if (t >= 100) clearInterval(n); }, 25); })();
            
            setupEventListeners();
            
            let simulatedOnlineUsers = Math.floor(Math.random() * 201) + 80;
            const updateOnlineUsers = () => { if (allElements.onlineUsersCount) { simulatedOnlineUsers += Math.floor(Math.random() * 7) - 3; simulatedOnlineUsers = Math.max(50, Math.min(400, simulatedOnlineUsers)); allElements.onlineUsersCount.textContent = simulatedOnlineUsers; }};
            setInterval(updateOnlineUsers, 3500);
            updateOnlineUsers();
            
            setTimeout(() => {
                const urlParams = new URLSearchParams(window.location.search);
                const refCode = urlParams.get('ref');
                const user = getCurrentUser();

                if (user) {
                    startActiveCampaignSimulations(user.email);
                    showPage('dashboard-page');
                } else {
                    showPage('auth-page');
                    if(refCode) allElements.showRegister.click();
                }
                allElements.splashPage.style.opacity = 0;
                allElements.splashPage.addEventListener('transitionend', () => allElements.splashPage.style.display = 'none');
            }, 3000);
        };
        
        loadState();
        initApp();
    });
    </script>
</body>
</html>
