<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Project Romeo // Mahal - Phase 5</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,600;1,600&family=Inter:wght@300;400;500&family=Dancing+Script:wght@500;600;700&family=Orbitron:wght@400;600;700&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    
    <style>
        :root {
            --primary: #8b5cf6;
            --primary-glow: rgba(139, 92, 246, 0.5);
            --accent: #3b82f6;
            --accent-glow: rgba(59, 130, 246, 0.5);
            --bg-dark: #090a16;
            --bg-card: rgba(255, 255, 255, 0.05);
            --border-glass: rgba(255, 255, 255, 0.12);
            --text-main: #f8fafc;
            --text-muted: #94a3b8;
            --gold: #38bdf8;
            --parchment: #fafafa;
            --crimson: #4c1d95;
            --error-red: #f43f5e;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Inter', sans-serif;
            background: radial-gradient(circle at 50% 0%, #2e1065 0%, #0f172a 60%, #070a17 100%);
            background-attachment: fixed;
            color: var(--text-main);
            min-height: 100vh;
            overflow-x: hidden;
            position: relative;
        }

        /* Ambient Stars / Particles */
        .firefly {
            position: fixed;
            width: 3px;
            height: 3px;
            background: #cbd5e1;
            border-radius: 50%;
            pointer-events: none;
            box-shadow: 0 0 10px 2px var(--accent);
            opacity: 0.6;
            z-index: 1;
        }

        @keyframes float {
            0% { transform: translate(0, 0) scale(1); opacity: 0; }
            20% { opacity: 0.8; }
            80% { opacity: 0.8; }
            100% { transform: translate(calc(-60px + 120px * var(--dir-x)), calc(-60px + 120px * var(--dir-y))) scale(0.4); opacity: 0; }
        }

        /* Glassmorphism Panel */
        .glass-panel {
            background: var(--bg-card);
            backdrop-filter: blur(18px);
            -webkit-backdrop-filter: blur(18px);
            border: 1px solid var(--border-glass);
            border-radius: 24px;
            box-shadow: 0 12px 40px rgba(0, 0, 0, 0.5);
        }

        /* ----- LOGIN PAGE ----- */
        #landing-page {
            position: fixed; 
            top: 0; left: 0; 
            width: 100vw; height: 100vh;
            display: flex; 
            justify-content: center; 
            align-items: center;
            z-index: 4000;
            padding: 20px;
            background: radial-gradient(circle at center, rgba(30, 27, 75, 0.9) 0%, rgba(7, 10, 23, 0.98) 100%);
        }

        .login-card {
            padding: 3.5rem 2.5rem;
            text-align: center;
            max-width: 420px;
            width: 100%;
            position: relative;
            box-shadow: 0 20px 50px rgba(0,0,0,0.6), 0 0 30px rgba(139, 92, 246, 0.15);
            transition: transform 0.3s ease;
        }

        .login-card.shake {
            animation: shake 0.4s ease-in-out;
        }

        @keyframes shake {
            0%, 100% { transform: translateX(0); }
            20%, 60% { transform: translateX(-10px); }
            40%, 80% { transform: translateX(10px); }
        }

        .lock-icon-wrapper {
            width: 70px;
            height: 70px;
            margin: 0 auto 1.5rem;
            background: linear-gradient(135deg, rgba(139, 92, 246, 0.2), rgba(59, 130, 246, 0.2));
            border: 1px solid rgba(139, 92, 246, 0.4);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.8rem;
            color: #a7f3d0;
            box-shadow: 0 0 20px var(--primary-glow);
        }

        .login-card h2 {
            font-family: 'Playfair Display', serif;
            font-size: 2.2rem;
            margin-bottom: 6px;
            background: linear-gradient(to right, #ffffff, #c084fc, #60a5fa);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .status-text {
            font-size: 0.72rem;
            color: var(--gold);
            letter-spacing: 3px;
            margin-bottom: 2rem;
            font-family: 'Orbitron', sans-serif;
            text-transform: uppercase;
        }

        .input-group {
            position: relative;
            margin-bottom: 1rem;
        }

        .pin-input {
            width: 100%;
            padding: 1.1rem 1rem;
            background: rgba(3, 7, 18, 0.7);
            border: 1px solid var(--border-glass);
            border-radius: 14px;
            color: #fff;
            text-align: center;
            letter-spacing: 12px;
            font-size: 1.6rem;
            outline: none;
            transition: all 0.3s ease;
            font-family: 'Orbitron', monospace;
        }

        .pin-input:focus {
            border-color: var(--primary);
            box-shadow: 0 0 20px var(--primary-glow);
            background: rgba(3, 7, 18, 0.9);
        }

        .error-message {
            min-height: 20px;
            font-size: 0.8rem;
            color: var(--error-red);
            margin-bottom: 1rem;
            font-family: 'Inter', sans-serif;
            letter-spacing: 1px;
            opacity: 0;
            transition: opacity 0.3s ease;
        }

        .error-message.visible {
            opacity: 1;
        }

        .btn-glow {
            width: 100%;
            padding: 1.1rem;
            border: none;
            border-radius: 14px;
            background: linear-gradient(135deg, var(--primary), var(--accent));
            color: white;
            font-family: 'Poppins', sans-serif;
            font-weight: 600;
            font-size: 0.95rem;
            cursor: pointer;
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
            text-transform: uppercase;
            letter-spacing: 2px;
            box-shadow: 0 4px 15px var(--primary-glow);
        }

        .btn-glow:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 25px var(--primary-glow);
        }

        /* ----- Intro Sequence ----- */
        #intro-sequence {
            position: fixed; top: 0; left: 0; width: 100%; height: 100%;
            background: #030712; z-index: 5000; display: none;
            justify-content: center; align-items: center; text-align: center;
        }
        
        .intro-text {
            font-family: 'Orbitron', sans-serif;
            font-size: 1.1rem;
            color: var(--gold);
            letter-spacing: 4px;
            animation: pulse 1.5s infinite;
        }

        /* ----- Main Page / Dashboard ----- */
        #main-page {
            display: none;
            padding: 4rem 1.5rem;
            opacity: 0;
            transition: opacity 1.2s ease;
            position: relative;
            z-index: 10;
            max-width: 920px;
            margin: 0 auto;
        }

        .header-section {
            text-align: center;
            margin-bottom: 3.5rem;
        }

        .sync-text {
            color: var(--gold);
            font-family: 'Orbitron', sans-serif;
            font-size: 0.8rem;
            letter-spacing: 3px;
            margin-bottom: 1rem;
        }

        .main-title {
            font-family: 'Playfair Display', serif;
            font-size: 3rem;
            font-style: italic;
            margin-bottom: 2rem;
            text-shadow: 0 4px 20px rgba(0,0,0,0.6);
            background: linear-gradient(to right, #ffffff, #c084fc, #93c5fd);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        /* Timer */
        .timer-container {
            display: flex;
            justify-content: center;
            gap: 1.2rem;
            flex-wrap: wrap;
        }

        .timer-unit {
            background: rgba(59, 130, 246, 0.08);
            padding: 1.2rem 1rem;
            border-radius: 18px;
            min-width: 85px;
            text-align: center;
            border: 1px solid rgba(59, 130, 246, 0.25);
            backdrop-filter: blur(8px);
        }

        .timer-unit span {
            display: block;
            font-size: 2.2rem;
            color: #fff;
            font-family: 'Orbitron', sans-serif;
            font-weight: 700;
            text-shadow: 0 0 12px var(--accent-glow);
        }

        .timer-unit label {
            font-size: 0.65rem;
            color: var(--text-muted);
            letter-spacing: 2px;
            margin-top: 6px;
            display: block;
        }

        /* Gift Grid */
        .gift-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 1.2rem;
            margin-top: 3.5rem;
        }

        .menu-btn {
            background: var(--bg-card);
            border: 1px solid var(--border-glass);
            color: white;
            padding: 1.5rem 1.8rem;
            border-radius: 18px;
            cursor: pointer;
            display: flex;
            justify-content: space-between;
            align-items: center;
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
            font-family: 'Poppins', sans-serif;
            text-align: left;
            position: relative;
            overflow: hidden;
        }

        .menu-btn::before {
            content: '';
            position: absolute;
            top: 0; left: 0; width: 4px; height: 100%;
            background: linear-gradient(180deg, var(--primary), var(--accent));
            transform: scaleY(0);
            transition: transform 0.3s ease;
        }

        .menu-btn:hover {
            background: rgba(139, 92, 246, 0.12);
            border-color: rgba(139, 92, 246, 0.4);
            transform: translateY(-3px);
            box-shadow: 0 12px 25px rgba(0,0,0,0.4);
        }

        .menu-btn:hover::before {
            transform: scaleY(1);
        }

        .menu-btn span:first-child {
            font-size: 1.05rem;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .badge-new {
            background: linear-gradient(135deg, var(--primary), var(--accent));
            color: white;
            padding: 4px 10px;
            border-radius: 20px;
            font-size: 0.65rem;
            font-weight: 600;
            letter-spacing: 1px;
            box-shadow: 0 0 10px var(--accent-glow);
        }

        /* ----- Views / Letters ----- */
        .gift-view {
            display: none;
            max-width: 820px;
            margin: 0 auto;
            animation: fadeIn 0.6s ease;
        }

        .back-btn {
            background: transparent;
            border: 1px solid var(--border-glass);
            color: var(--text-muted);
            padding: 10px 25px;
            border-radius: 30px;
            cursor: pointer;
            margin-bottom: 2rem;
            font-size: 0.9rem;
            transition: 0.3s;
            display: inline-flex;
            align-items: center;
            gap: 8px;
        }

        .back-btn:hover {
            background: rgba(255,255,255,0.1);
            color: white;
        }

        /* Wax Seal */
        .seal-wrapper {
            text-align: center;
            cursor: pointer;
            padding: 90px 0;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .wax-seal {
            width: 105px;
            height: 105px;
            background: linear-gradient(135deg, #5b21b6, #1e1b4b);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 3rem;
            color: white;
            box-shadow: 0 10px 30px rgba(91, 33, 182, 0.5), inset 0 0 12px rgba(0,0,0,0.6);
            border: 3px solid #3b0764;
            transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            position: relative;
        }

        .wax-seal::after {
            content: '♥';
        }

        .seal-wrapper:hover .wax-seal {
            transform: scale(1.15) rotate(12deg);
            box-shadow: 0 15px 40px rgba(139, 92, 246, 0.6);
        }

        .seal-hint {
            font-family: 'Dancing Script', cursive;
            font-size: 1.6rem;
            color: var(--gold);
            margin-top: 25px;
            opacity: 0.9;
        }

        /* Letter Styling */
        .paper-letter {
            display: none;
            background: var(--parchment);
            color: #1e293b;
            padding: 4rem 3.5rem;
            border-radius: 6px;
            line-height: 1.8;
            box-shadow: 0 30px 60px rgba(0,0,0,0.7);
            transform-origin: top;
            animation: unfold 1.2s cubic-bezier(0.23, 1, 0.32, 1);
            position: relative;
        }

        .letter-greeting {
            font-family: 'Dancing Script', cursive;
            font-size: 3rem;
            color: var(--crimson);
            margin-bottom: 2rem;
        }

        .letter-body {
            font-size: 1.1rem;
            white-space: pre-wrap;
            text-align: justify;
            font-family: 'Inter', sans-serif;
            font-weight: 400;
        }

        .letter-signoff {
            margin-top: 3rem;
            font-family: 'Dancing Script', cursive;
            font-size: 2.2rem;
            text-align: right;
            color: var(--crimson);
            line-height: 1.2;
        }

        .bouquet-action {
            text-align: center;
            border-top: 1px dashed rgba(0,0,0,0.2);
            padding-top: 2rem;
            margin-top: 3rem;
        }

        .btn-bouquet {
            display: inline-block;
            padding: 1.1rem 2.2rem;
            background: linear-gradient(135deg, #7b2cbf, #2563eb);
            color: white;
            text-decoration: none;
            border-radius: 50px;
            font-weight: 600;
            font-family: 'Poppins', sans-serif;
            transition: all 0.3s ease;
            box-shadow: 0 10px 25px rgba(37, 99, 235, 0.4);
        }

        .btn-bouquet:hover {
            transform: translateY(-3px) scale(1.04);
            box-shadow: 0 15px 35px rgba(58, 134, 255, 0.6);
        }

        /* Q&A / Interview Styling */
        .qa-block {
            margin-bottom: 2rem;
            padding: 1.6rem;
            background: rgba(0,0,0,0.3);
            border-radius: 14px;
            border-left: 3px solid var(--accent);
        }

        .qa-q {
            color: var(--gold);
            font-family: 'Poppins', sans-serif;
            font-weight: 600;
            font-size: 1.1rem;
            margin-bottom: 0.8rem;
        }

        .qa-a {
            color: var(--text-muted);
            line-height: 1.7;
        }

        /* Keyframe Animations */
        @keyframes unfold { 
            0% { transform: rotateX(-90deg); opacity: 0; } 
            100% { transform: rotateX(0deg); opacity: 1; } 
        }
        @keyframes fadeIn { 
            from { opacity: 0; transform: translateY(10px); } 
            to { opacity: 1; transform: translateY(0); } 
        }
        @keyframes pulse { 
            0%, 100% { opacity: 0.4; } 
            50% { opacity: 1; text-shadow: 0 0 10px var(--gold); } 
        }

        /* Responsive Breakpoints */
        @media (max-width: 768px) {
            .main-title { font-size: 2.2rem; }
            .paper-letter { padding: 2.5rem 1.5rem; }
            .timer-unit { min-width: 70px; padding: 0.8rem; }
            .timer-unit span { font-size: 1.6rem; }
            .login-card { padding: 2.5rem 1.5rem; }
        }
    </style>
</head>
<body>

    <!-- Particle Starfield -->
    <div id="fireflies-container"></div>

    <!-- 1. LOGIN PAGE -->
    <div id="landing-page">
        <div class="glass-panel login-card" id="login-card">
            <div class="lock-icon-wrapper">🔒</div>
            <h2>Project Romeo</h2>
            <p class="status-text">PHASE 5 ACCESS PORTAL</p>
            
            <div class="input-group">
                <input type="password" id="pin" class="pin-input" maxlength="6" placeholder="••••••" inputmode="numeric" onkeyup="handlePinInput(event)">
            </div>
            
            <div id="error-msg" class="error-message">Incorrect PIN code. Try again.</div>

            <button class="btn-glow" onclick="startIntroSequence()">Unlock Memories</button>
        </div>
    </div>

    <!-- 2. INTRO SEQUENCE -->
    <div id="intro-sequence">
        <p class="intro-text" id="intro-msg">INITIALIZING SYSTEM...</p>
    </div>

    <!-- 3. MAIN DASHBOARD -->
    <div id="main-page">
        <div id="home-view">
            <div class="header-section">
                <div class="sync-text" id="live-clock">SYNCING...</div>
                <h1 class="main-title">Happy 5th Monthsary, Mahal</h1>
                
                <div class="timer-container">
                    <div class="timer-unit"><span id="days">0</span><label>DAYS</label></div>
                    <div class="timer-unit"><span id="hours">0</span><label>HOURS</label></div>
                    <div class="timer-unit"><span id="mins">0</span><label>MINS</label></div>
                    <div class="timer-unit"><span id="secs">0</span><label>SECS</label></div>
                </div>
            </div>

            <div class="gift-grid">
                <!-- 5th Monthsary Additions -->
                <button class="menu-btn" onclick="showView('fifth-month-view')">
                    <span style="font-weight: 600;">✨ 5th Monthsary Letter</span>
                    <span class="badge-new">NEW</span>
                </button>

                <button class="menu-btn" onclick="showView('vault-view')">
                    <span style="font-weight: 600;">📁 Memory Vault</span>
                    <span class="badge-new">NEW</span>
                </button>

                <!-- Our Playlist with NEW badge -->
                <button class="menu-btn" onclick="showView('music-view')">
                    <span style="font-weight: 600;">🎵 Our Playlist</span>
                    <span class="badge-new">NEW</span>
                </button>

                <!-- Previous Archives -->
                <button class="menu-btn" onclick="showView('fourth-month-view')">
                    <span>📜 4th Monthsary Archive</span>
                    <span>→</span>
                </button>
                <button class="menu-btn" onclick="showView('third-month-view')">
                    <span>📜 3rd Monthsary Archive</span>
                    <span>→</span>
                </button>
                <button class="menu-btn" onclick="showView('letter-view')">
                    <span>💌 2nd Monthsary Archive</span>
                    <span>→</span>
                </button>
                <button class="menu-btn" onclick="showView('archive-view')">
                    <span>💖 1st Monthsary Archive</span>
                    <span>→</span>
                </button>
                <button class="menu-btn" onclick="showView('bday-view')">
                    <span>🎂 17th Birthday Message</span>
                    <span>→</span>
                </button>
                <button class="menu-btn" onclick="showView('interview-view')">
                    <span>🎤 Project: Romeo Log</span>
                    <span>→</span>
                </button>
            </div>
        </div>

        <!-- 5th Monthsary Personal Letter -->
        <div id="fifth-month-view" class="gift-view">
            <button class="back-btn" onclick="goHome()">← Return to Dashboard</button>
            <div id="seal-wrapper-5" class="seal-wrapper" onclick="openPaper('main-letter-5', 'seal-wrapper-5')">
                <div class="wax-seal"></div>
                <p class="seal-hint">Tap the heart seal to open your 5th Monthsary letter...</p>
            </div>
            <div id="main-letter-5" class="paper-letter">
                <h2 class="letter-greeting">My Dearest Mahal,</h2>
                <div class="letter-body">Happy 5th Monthsary, mahal ko! 💖

Limang buwan na tayong magkasama, at sa bawat araw na lumilipas, lalong lumalalim ang pagmamahal at pagpapasalamat ko sa’yo. Maraming salamat sa patuloy na pag-unawa, pagmamahal, at sa pagiging tahanan ng puso ko.

Kahit ano man ang dumating na pagsubok o mga araw na napapagod tayo, gusto kong malaman mo na palagi kong pipiliin na hawakan ang kamay mo. Ikaw ang aking pahinga at paboritong bahagi ng bawat araw ko.

Pangako ko sa'yo na patuloy akong magiging mas mabuting partner para sa'yo. Nandidito lang ako para suportahan ka sa lahat ng mga pangarap mo. Mahal na mahal kita, kahapon, ngayon, at sa lahat ng susunod pang mga buwan at taon.

Happy 5th Monthsary ulit, mahal ko! Mwahhh! 💜✨</div>
                <p class="letter-signoff">Nagmamahal nang buong puso,<br>Romeo</p>
            </div>
        </div>

        <!-- Memory Vault View -->
        <div id="vault-view" class="gift-view">
            <button class="back-btn" onclick="goHome()">← Return to Dashboard</button>
            <div class="glass-panel" style="padding: 3.5rem 2rem; text-align: center;">
                <h2 style="font-family: 'Playfair Display'; font-size: 2.3rem; margin-bottom: 12px; color: var(--text-main);">📁 Memory Vault</h2>
                <p style="color: var(--gold); font-family: 'Orbitron'; margin-bottom: 25px; letter-spacing: 2px; font-size: 0.85rem;">SECURE DRIVE REPOSITORY</p>
                <p style="font-size: 1.05rem; line-height: 1.8; margin-bottom: 35px; color: var(--text-muted); max-width: 600px; margin-left: auto; margin-right: auto;">
                    A dedicated secure folder storing all our treasured pictures, videos, voice clips, and unforgettable moments captured through time.
                </p>
                <div style="background: rgba(139, 92, 246, 0.06); border: 1px dashed rgba(139, 92, 246, 0.4); padding: 35px 20px; border-radius: 18px;">
                    <a href="https://drive.google.com/drive/folders/1lW-jAXDJUVxLwaSjJ3H8B657pTWDxD1P?usp=sharing" target="_blank" class="btn-bouquet" style="background: linear-gradient(135deg, #3b82f6, #8b5cf6);">
                        🔗 Open Memory Vault Drive
                    </a>
                </div>
            </div>
        </div>

        <!-- 4th Monthsary View -->
        <div id="fourth-month-view" class="gift-view">
            <button class="back-btn" onclick="goHome()">← Return to Dashboard</button>
            <div id="seal-wrapper-4" class="seal-wrapper" onclick="openPaper('main-letter-4', 'seal-wrapper-4')">
                <div class="wax-seal"></div>
                <p class="seal-hint">Tap the heart to open your 4th Monthsary letter...</p>
            </div>
            <div id="main-letter-4" class="paper-letter">
                <h2 class="letter-greeting">My Dearest Mahal,</h2>
                <div class="letter-body">Hii po, mahal ko. 

Thank you po sa lahat ng ginagawa mo para sa akin. Sobrang thankful po ako kasi kahit zero days pa lang ako noon, pinili mo pa rin ako. Alam ko pong maraming iba diyan na baka mas okay, mas deserving, o mas kayang ibigay ang gusto mo, pero ako pa rin ang pinili mo. Hanggang ngayon, hindi pa rin po ako makapaniwala na naging tayo, at araw-araw nagpapasalamat po ako dahil nandiyan ka.

Thank you rin po sa pagtrato mo sa akin nang tama, sa pagiging patient mo, sa pag-intindi sa akin, at sa pagmamahal na binibigay mo. Ang saya-saya po ng puso ko kapag ikaw ang kausap ko, at kahit simpleng oras lang na kasama kita, sapat na iyon para mapasaya ako.

Gusto ko lang pong sabihin na sana huwag mo akong pagsawaan. Hayaan mo lang po akong mahalin ka araw-araw, lambingin ka palagi, at iparamdam sa'yo kung gaano ka kahalaga sa akin. Pangako ko po na patuloy akong mag-i-improve para maging partner na deserve mo. Hindi man ako perfect, hindi po mapapagod ang puso kong piliin ka sa bawat araw.

Thank you po kasi ikaw ang naging tahanan ng puso ko. Ikaw ang favorite person ko, ang pahinga ko, at ang taong gusto kong makasama sa lahat ng bagay. Sana marami pa tayong monthsary na sabay nating ipagdiwang hanggang sa maging years na.

Happy 4th monthsary po ulit, mahal ko. Super miss na miss na po kita. Gusto na po kitang mayakap nang mahigpit at hindi na bumitaw. Lagi mong tatandaan na nandito lang po ako, palagi. Mahal na mahal po kita, higit pa sa kaya kong ipaliwanag. Mwahhh.</div>
                <p class="letter-signoff">Nagmamahal nang buong puso,<br>Romeo</p>
                <div class="bouquet-action">
                    <a href="https://digibouquet.vercel.app/bouquet/50768206-3d81-4042-be0c-9d12b903f61b" target="_blank" class="btn-bouquet">💐 Open 4th Monthsary Bouquet</a>
                </div>
            </div>
        </div>

        <!-- 3rd Monthsary View -->
        <div id="third-month-view" class="gift-view">
            <button class="back-btn" onclick="goHome()">← Return to Dashboard</button>
            <div id="seal-wrapper-3" class="seal-wrapper" onclick="openPaper('main-letter-3', 'seal-wrapper-3')">
                <div class="wax-seal"></div>
                <p class="seal-hint">Tap the heart to open your 3rd Monthsary letter...</p>
            </div>
            <div id="main-letter-3" class="paper-letter">
                <h2 class="letter-greeting">My Dearest Mahal,</h2>
                <div class="letter-body">Hello mahal team bahay nanaman po noh? Well okay lang po yun, naiintindihan ko naman po lalo na para kay Tita. 💜

At this moment magka-call po tayo habang nag-CCP ka nga po. HAHAHA. Habang kausap kita medyo naiiyak po ako kasi nawala yung bracelet na binigay mo. To be honest mahal, sobrang grateful po ako na dumating ka sa buhay ko. Kahit feeling ko minsan wala pa akong masyadong naaabot sa ngayon, pinili mo pa rin ako. Sobrang swerte ko po na ikaw ang naging mahal ko. 🥺💜

Happy 3rd Monthsary po asawa kooooo. 🎉💜 Tatlong buwan na tayong magkasama at bawat araw na kasama kita ay isa sa mga pinakamasayang parte ng buhay ko. Salamat sa lahat ng pagmamahal, pag intindi, pag aalaga at sa pagiging ikaw. Hindi mo lang pinapasaya ang araw ko, pinapagaan mo rin ang lahat ng nararamdaman ko.

Alam ko po na nasa bagong school ka na ngayon. Hindi na kita nakikita tulad ng dati kaya minsan nalulungkot po ako. Naiisip ko kung nakakain ka ba nang maayos, kung napapagod ka ba sa school, kung okay ka ba araw araw at kung may nag aalaga ba sa iyo kapag hindi ka okay. Pero mahal huwag ka pong mag alala. Kahit malayo ako at hindi kita nakikita palagi, hahanap at hahanap po ako ng paraan para maalagaan ka sa abot ng makakaya ko. 💜

Palagi mong tandaan na sobrang proud po ako sa iyo. Proud ako sa lahat ng ginagawa mo, sa lahat ng efforts mo at sa bawat laban na hinaharap mo araw araw. Kahit gaano kahirap ang araw mo nandito lang po ako para makinig, umintindi at samahan ka.

Mahal gusto ko ring malaman mo na hindi mo kailangang maging perfect para mahalin kita. Kapag masaya ka mamahalin kita. Kapag malungkot ka mamahalin kita. Kapag pagod ka mamahalin kita. Kapag may problema ka mamahalin kita. Sa lahat ng pagkakataon at sa lahat ng version mo, ikaw pa rin ang pipiliin ko. 💜

Kapag napapagod ka, nalulungkot ka o nag ooverthink ka, sana maalala mo na hindi ka nag iisa. Nandito lang po ang asawa mo na handang makinig sa lahat ng kwento mo, sa lahat ng problema mo at sa lahat ng pangarap mo. Gusto kong makita kang masaya, ligtas at mas laron umuunlad sa buhay.

Please take care of yourself for me mahal. Kumain ka sa tamang oras, uminom ng maraming tubig, magpahinga kapag pagod at huwag masyadong magpupuyat. Kahit hindi ako nasa tabi mo araw araw, dala dala mo po lagi ang pagmamahal ko saan ka man magpunta. 🥺💜

Thank you for staying. Thank you for choosing me every day. Thank you for loving me. Kahit anong mangyari, nandito lang po ako para sa iyo. Hindi man ako perpekto pero sisikapin kong maging taong masasandalan mo sa tuwa, lungkot at lahat ng bagay na pagdadaanan mo.

Happy 3rd Monthsary asawa koooo. 💜🥺

Mahal na mahal po kita. Lagi mong tandaan na may isang taong naniniwala sa iyo, proud sa iyo at handang piliin ka araw araw. Ikaw ang isa sa pinakamagandang nangyari sa buhay ko at sobrang nagpapasalamat ako na ikaw ang kasama ko ngayon.

I love you so much asawa ko. Ngayon, bukas at sa mga susunod pang buwan at taon. Mwahhhh. 💜😘✨</div>
                <p class="letter-signoff">Nagmamahal nang buong puso,<br>Romeo</p>
                <div class="bouquet-action">
                    <a href="https://digibouquet.vercel.app/bouquet/e30cde7d-ed70-4474-a4a3-3d5a462ada76" target="_blank" class="btn-bouquet">💐 Open 3rd Monthsary Bouquet</a>
                </div>
            </div>
        </div>

        <!-- 2nd Monthsary View -->
        <div id="letter-view" class="gift-view">
            <button class="back-btn" onclick="goHome()">← Return to Dashboard</button>
            <div id="seal-wrapper-2" class="seal-wrapper" onclick="openPaper('main-letter-2', 'seal-wrapper-2')">
                <div class="wax-seal"></div>
                <p class="seal-hint">Tap the heart to read my promise...</p>
            </div>
            <div id="main-letter-2" class="paper-letter">
                <h2 class="letter-greeting">My Dearest Mahal,</h2>
                <div class="letter-body">Happy 2nd Monthsary, my wife!!

Hello po mahal... gusto ko lang sabihin sa’yo na ginagawa ko po lahat ito habang nagma makeup ka po, may 10 bago pa man dumating ang ating 2nd Monthsary. To be honest, mahal... naiiyak ako habang nakikita kitang nag aayos, habang pinagmamasdan kita. Iiyak ako hindi dahil malungkot, kundi dahil sobrang pasasalamat at pagmamahal ang nararamdaman ko kasi mayroon na akong Asawa na napakaganda, hindi lang sa panlabas kundi pati sa puso, napaka unawa, napakabuti, at napakabait sa alkali. Bawat galaw mo, bawat ngiti mo, bawat pagsisikap mo, lahat ‘yan ay nagpapatunay sa akin kung gaano ako ka swerte at napili ng tadhana na ikaw ang ibigay sa kiwi.

Alam mo naman po na wala naman akong kayang ibigay o ibahagi sa ngayon kundi ang pagmamahal ko lang sa’yo, kaya ito lang ang nagawa ko para sa’yo. Alam ko rin po... alam kong nagtatampo ka na minsan kasi hindi na kita nabibigyan ng sapat na oras gaya ng dati. Naiindihan ko kung bakit, at humihingi ako ng paumanhin kung nakakapagparamdam ako na parang hindi ka mahalaga o parang napapabayaan kita. Pasensya na po kung minsan ay abala ako o maraming ginagawa, at pakiramdam mo ay napapanghinaan ka ng loob dahil wala ako sa tabi mo o hindi tayo nakakapag usap nang matagal. Huwag po sana kayong mag isip na nababawasan ang pagmamahal ko, hinding hindi po mangyayari ‘yan.

At alam ko rin na hindi lang ito ang dahilan kung bakit minsan ay malungkot o mabigat ang loob mo... Alam ko ang pinagdadaanan mo sa pamilya niyo. Nakikita ko kung gaano kabigat ang mga pasanin na dinadala mo araw araw, kung paano mong pilit na lumalakas kahit na ang sakit na sa loob mo. Gusto kong malaman mo na nakikita kita, naririnig kita, at nararamdaman ko ang bawat lungkot at pagod na nararamdaman mo. Ligtas ka sa piling ko, palagi.

Ito ang pinaka sigurado at tapat kong pangako sa’yo: hindi kita iiwan, mahal. Ngayon, bukas, at sa habang panahon. Hahawakan kita nang mahigpit sa bawat mahirap na usapan, sa bawat gabing umiiyak ka, sa bawat araw na pagod ka, at sa bawat sandaling pakiramdam mo ay susuko ka na. Hindi ka lang basta girlfriend para sa akin, ikaw ang kapareha ko, ang matalik kong kaibigan, ang kapayapaan ko, at ang taong gusto kong makasama habang buhay.

Happy 2nd Monthsary, mahal ko. Nandito lang ako, palagi at habang buhay.</div>
                <p class="letter-signoff">Nagmamahal nang buong puso,<br>Romeo</p>
                <div class="bouquet-action">
                    <a href="https://digibouquet.net/create-bouquet?b=JTdCJTIyZiUyMiUzQSU1QiUyMm9yY2hpZCUyMiUyQyUyMmNhbWVsbGlhJTIyJTJDJTIyZGFpc3klMjIlMkMlMjJsb3R1cyUyMiUtQyUyMnR1bGlwJTIyJTJDJTIycGVvbnklMjIlMkMlMjJyb3NlJTIyJTJDJTIybGlseSUyMiU1RCUyQyUyMmSelection%202" target="_blank" class="btn-bouquet">💐 Open 2nd Monthsary Bouquet</a>
                </div>
            </div>
        </div>

        <!-- 1st Monthsary View -->
        <div id="archive-view" class="gift-view">
            <button class="back-btn" onclick="goHome()">← Return</button>
            <div class="glass-panel" style="padding: 3rem; text-align: center;">
                <h2 style="font-family: 'Playfair Display'; font-size: 2rem; margin-bottom: 10px;">The First Milestone</h2>
                <p style="color: var(--gold); font-family: 'Orbitron'; margin-bottom: 25px; letter-spacing: 2px;">April 14, 2026</p>
                <p style="font-size: 1.15rem; font-style: italic; margin-bottom: 35px; color: var(--text-muted);">
                    "Salamat sa pagtitiwala sa akin, sa pagbukas ng iyong puso, at sa pagiging ikaw mismo."
                </p>
                <div style="background: rgba(139, 92, 246, 0.05); border: 1px dashed rgba(139, 92, 246, 0.4); padding: 30px; border-radius: 15px;">
                    <a href="https://digibouquet.vercel.app/bouquet/0382aca8-4b69-486e-b6c6-7f02b69eb11a" target="_blank" class="btn-bouquet">🌸 Open Your 1st Bouquet</a>
                </div>
            </div>
        </div>

        <!-- Birthday Message -->
        <div id="bday-view" class="gift-view">
            <button class="back-btn" onclick="goHome()">← Return</button>
            <div class="paper-letter" style="display: block; background: rgba(255, 255, 255, 0.05); color: #fff; border: 1px solid var(--gold); backdrop-filter: blur(10px);">
                <h3 style="font-family: 'Dancing Script'; font-size: 2.8rem; margin-bottom: 2rem; color: var(--gold); text-align: center;">Happy 17th Birthday, mahal ko.</h3>
                <div style="opacity: 0.95; line-height: 1.8; font-size: 1.05rem; white-space: pre-wrap; font-weight: 300;">This is from someone unexpected… someone who didn’t plan to walk into your life, but somehow found a place in it anyway. And even if I came quietly and without warning, please know I’m here with genuine intentions and a heart that cares deeply for you.

On your special day, I just want to remind you that you are seen, appreciated, and loved in ways you may not always realize. I know life hasn’t always been easy, and there are moments when you carry things silently, but you don’t have to face everything alone. I’m here, not just for the happy moments, but also for the days when things feel heavy.

You deserve a kind of love that feels safe, steady, and reassuring. The kind that doesn’t confuse you, doesn’t leave you questioning your worth, and doesn’t disappear when things get hard. I may have come into your life unexpectedly, but my presence is something I choose every day.

And because you’re that special to me, I made something just for you, a website created with all my thoughts and feelings, hoping it can show even a small part of how much you mean to me.

I hope this year brings you peace in your heart, clarity in your mind, and warmth in your soul. And in all the uncertainty life brings, I hope you feel one thing clearly, I’m here for you, mahal ko.

Happy Birthday again. You mean more than you think. 💜💙</div>
            </div>
        </div>

        <!-- Playlist View -->
        <div id="music-view" class="gift-view">
            <button class="back-btn" onclick="goHome()">← Return</button>
            <div class="glass-panel" style="padding: 2.5rem 1.8rem; text-align: center;">
                <h2 style="font-family: 'Playfair Display'; font-size: 2.2rem; margin-bottom: 8px; color: var(--text-main);">🎵 Our Playlist</h2>
                <p style="color: var(--gold); font-family: 'Orbitron'; margin-bottom: 30px; letter-spacing: 2px; font-size: 0.8rem;">THE SOUNDTRACK OF US</p>
                
                <!-- 1. Background Theme Song -->
                <div style="margin-bottom: 2.2rem; background: rgba(59, 130, 246, 0.08); padding: 1.2rem; border-radius: 18px; border: 1px solid rgba(59, 130, 246, 0.25);">
                    <p style="font-family: 'Orbitron', sans-serif; font-size: 0.75rem; color: var(--gold); letter-spacing: 2px; margin-bottom: 12px; text-transform: uppercase; font-weight: 600;">✨ Background / Theme Song</p>
                    <iframe style="border-radius:14px; box-shadow: 0 8px 25px rgba(0,0,0,0.5);" src="https://open.spotify.com/embed/track/4FdQYoWFym37QDQ2GkEHi1?utm_source=generator&theme=0" width="100%" height="152" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
                </div>

                <!-- 2. Main Song -->
                <div style="margin-bottom: 2.2rem; background: rgba(139, 92, 246, 0.08); padding: 1.2rem; border-radius: 18px; border: 1px solid rgba(139, 92, 246, 0.3);">
                    <p style="font-family: 'Orbitron', sans-serif; font-size: 0.75rem; color: #c084fc; letter-spacing: 2px; margin-bottom: 12px; text-transform: uppercase; font-weight: 600;">🌟 Main Song</p>
                    <iframe style="border-radius:14px; box-shadow: 0 8px 25px rgba(0,0,0,0.5);" src="https://open.spotify.com/embed/track/4WgViu9gw3qYOr3iF9OuLG?utm_source=generator&theme=0" width="100%" height="152" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
                </div>

                <!-- 3. Additional Songs & Original Track -->
                <div style="display: flex; flex-direction: column; gap: 1.5rem;">
                    <p style="font-family: 'Orbitron', sans-serif; font-size: 0.75rem; color: var(--text-muted); letter-spacing: 2px; margin-top: 0.5rem; text-transform: uppercase; font-weight: 600;">💬 Special Tracks</p>
                    
                    <!-- Original Song -->
                    <iframe style="border-radius:14px; box-shadow: 0 6px 18px rgba(0,0,0,0.4);" src="https://open.spotify.com/embed/track/0xJ4Qk9lIisIjOrI8bLkNP?utm_source=generator&theme=0" width="100%" height="152" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>

                    <iframe style="border-radius:14px; box-shadow: 0 6px 18px rgba(0,0,0,0.4);" src="https://open.spotify.com/embed/track/0JzwzRDkwZr8s1WRfNgUqA?utm_source=generator&theme=0" width="100%" height="152" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
                    
                    <iframe style="border-radius:14px; box-shadow: 0 6px 18px rgba(0,0,0,0.4);" src="https://open.spotify.com/embed/track/7aW2GrNlteWTwQZxX6LNjT?utm_source=generator&theme=0" width="100%" height="152" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
                    
                    <iframe style="border-radius:14px; box-shadow: 0 6px 18px rgba(0,0,0,0.4);" src="https://open.spotify.com/embed/track/13QQ8OerNguc4eR4qtd6SQ?utm_source=generator&theme=0" width="100%" height="152" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
                </div>

                <p style="font-family: 'Dancing Script', cursive; font-size: 1.6rem; color: var(--gold); margin-top: 35px; line-height: 1.6;">
                    "Pinipili kita, makasama sa pagtanda.<br>
                    Araw-araw walang iba, sa piling mo payapa na."
                </p>
            </div>
        </div>

        <!-- Romeo Log View -->
        <div id="interview-view" class="gift-view">
            <button class="back-btn" onclick="goHome()">← Return</button>
            <div class="glass-panel" style="padding: 3rem 2rem;">
                <h2 style="font-family: 'Playfair Display'; color: var(--text-main); text-align: center; margin-bottom: 2.5rem; font-size: 2.2rem;">Project Active: Romeo</h2>
                
                <div class="qa-block">
                    <p class="qa-q">Q: What is the purpose of this project?</p>
                    <p class="qa-a">To create a digital sanctuary. This isn't just a website; it’s a living archive for someone who made an unexpected but beautiful impact on my life. It exists to hold the things that matter—our songs, our photos, and the words I sometimes find hard to say out loud.</p>
                </div>

                <div class="qa-block">
                    <p class="qa-q">Q: Why did you choose this format?</p>
                    <p class="qa-a">Memories fade in phone galleries and chat logs. I wanted something intentional. "Project Active: Romeo" is about staying present—constantly building a space that reminds her she is seen and valued every time she logs in.</p>
                </div>

                <div class="qa-block">
                    <p class="qa-q">Q: Who is this truly for?</p>
                    <p class="qa-a" style="font-style: italic;">It is for her. Entirely. Every line of code, every color choice, and every hidden detail was designed with her smile in mind. It’s a reminder that even in a digital world, my intentions for her are real and permanent.</p>
                </div>

                <p style="text-align: center; color: var(--gold); font-family: 'Orbitron'; font-size: 0.9rem; margin-top: 3rem; letter-spacing: 3px;">
                    STATUS: ACTIVE (PHASE 5)
                </p>
            </div>
        </div>
    </div>

    <script>
        const PIN = "031426";
        const targetDate = new Date("2026-08-14T00:00:00").getTime();

        // Pin typing listener
        function handlePinInput(event) {
            const input = document.getElementById('pin');
            const error = document.getElementById('error-msg');
            
            error.classList.remove('visible');
            
            if (event.key === 'Enter') {
                startIntroSequence();
            } else if (input.value.length === 6) {
                startIntroSequence();
            }
        }

        // Security / Login logic
        function startIntroSequence() {
            const pinInput = document.getElementById('pin');
            const card = document.getElementById('login-card');
            const errorMsg = document.getElementById('error-msg');

            if (pinInput.value === PIN) {
                errorMsg.classList.remove('visible');
                document.getElementById('landing-page').style.display = 'none';
                
                const intro = document.getElementById('intro-sequence');
                const msg = document.getElementById('intro-msg');
                intro.style.display = 'flex';

                const lines = [
                    "INITIALIZING SYSTEM...",
                    "LOADING MEMORIES FOR MAHAL...",
                    "SYNCING HEARTBEATS...",
                    "PROJECT ROMEO: PHASE 5 ACTIVE"
                ];
                
                let i = 0;
                const interval = setInterval(() => {
                    msg.innerText = lines[i];
                    i++;
                    if (i >= lines.length) {
                        clearInterval(interval);
                        setTimeout(() => {
                            intro.style.opacity = '0';
                            intro.style.transition = 'opacity 1s ease';
                            setTimeout(() => {
                                intro.style.display = 'none';
                                document.getElementById('main-page').style.display = 'block';
                                setTimeout(() => document.getElementById('main-page').style.opacity = '1', 50);
                                initApp();
                            }, 1000);
                        }, 1200);
                    }
                }, 1100);
            } else { 
                card.classList.remove('shake');
                void card.offsetWidth;
                card.classList.add('shake');
                
                errorMsg.innerText = "Incorrect PIN code. Please try again.";
                errorMsg.classList.add('visible');
                
                pinInput.value = "";
                pinInput.focus();
            }
        }

        // Navigation
        function showView(id) {
            document.getElementById('home-view').style.display = 'none';
            document.getElementById(id).style.display = 'block';
            window.scrollTo({ top: 0, behavior: 'smooth' });
        }

        function goHome() {
            document.querySelectorAll('.gift-view').forEach(v => v.style.display = 'none');
            document.getElementById('home-view').style.display = 'block';
            
            const letters = ['main-letter-5', 'main-letter-4', 'main-letter-3', 'main-letter-2'];
            const seals = ['seal-wrapper-5', 'seal-wrapper-4', 'seal-wrapper-3', 'seal-wrapper-2'];
            
            letters.forEach(id => {
                if(document.getElementById(id)) document.getElementById(id).style.display = 'none';
            });
            seals.forEach(id => {
                if(document.getElementById(id)) document.getElementById(id).style.display = 'flex';
            });
            
            window.scrollTo({ top: 0, behavior: 'smooth' });
        }

        // Letter Opening Logic
        function openPaper(letterId, sealId) {
            document.getElementById(sealId).style.display = 'none';
            document.getElementById(letterId).style.display = 'block';
        }

        // Core App Logic (Timers & Effects)
        function initApp() {
            setInterval(() => {
                const now = new Date().getTime();
                const diff = targetDate - now;
                const opt = { timeZone: 'Asia/Manila', hour: '2-digit', minute: '2-digit', second: '2-digit', hour12: true };
                document.getElementById('live-clock').innerText = "STATION_TAYABAS // " + new Intl.DateTimeFormat('en-US', opt).format(new Date());

                if (diff > 0) {
                    document.getElementById('days').innerText = Math.floor(diff / (1000 * 60 * 60 * 24));
                    document.getElementById('hours').innerText = Math.floor((diff % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
                    document.getElementById('mins').innerText = Math.floor((diff % (1000 * 60 * 60)) / (1000 * 60));
                    document.getElementById('secs').innerText = Math.floor((diff % (1000 * 60)) / 1000);
                } else {
                    document.querySelectorAll('.timer-unit span').forEach(el => el.innerText = "0");
                }
            }, 1000);

            // Ambient Sky Particles
            const container = document.getElementById('fireflies-container');
            container.innerHTML = "";
            for (let i = 0; i < 45; i++) {
                let f = document.createElement('div');
                f.className = 'firefly';
                f.style.left = Math.random() * 100 + 'vw';
                f.style.top = Math.random() * 100 + 'vh';
                
                f.style.setProperty('--dir-x', Math.random());
                f.style.setProperty('--dir-y', Math.random());
                
                f.style.animation = `float ${10 + Math.random() * 15}s infinite linear`;
                f.style.animationDelay = `-${Math.random() * 10}s`;
                container.appendChild(f);
            }
        }

        window.onload = function() {
            const container = document.getElementById('fireflies-container');
            for (let i = 0; i < 35; i++) {
                let f = document.createElement('div');
                f.className = 'firefly';
                f.style.left = Math.random() * 100 + 'vw';
                f.style.top = Math.random() * 100 + 'vh';
                f.style.setProperty('--dir-x', Math.random());
                f.style.setProperty('--dir-y', Math.random());
                f.style.animation = `float ${10 + Math.random() * 15}s infinite linear`;
                f.style.animationDelay = `-${Math.random() * 10}s`;
                container.appendChild(f);
            }
        };
    </script>
</body>
</html>
