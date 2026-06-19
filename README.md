
<!DOCTYPE html>
<html lang="pt-PT">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sensus OEE | Inteligência Industrial</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <style>
        body { background-color: #020617; color: #f1f5f9; scroll-behavior: smooth; }
        .gradient-text { background: linear-gradient(to right, #38bdf8, #818cf8); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
        .glass { background: rgba(15, 23, 42, 0.7); backdrop-filter: blur(10px); border: 1px solid rgba(255,255,255,0.1); }
        /* Animação suave para a engrenagem */
        .spin { animation: spin 10s linear infinite; }
        @keyframes spin { from { transform: rotate(0deg); } to { transform: rotate(360deg); } }
        /* Botão flutuante WhatsApp */
        .whatsapp-float { position: fixed; bottom: 30px; right: 30px; z-index: 100; }
    </style>
</head>
<body class="font-sans">

    <!-- Botão Flutuante WhatsApp -->
    <a href="https://wa.me/5524998453342?text=Olá!%20Gostaria%20de%20saber%20mais%20sobre%20o%20Sensus%20OEE." target="_blank" class="whatsapp-float bg-green-500 hover:bg-green-600 text-white w-16 h-16 rounded-full flex items-center justify-center shadow-lg transition-transform hover:scale-110">
        <i class="fab fa-whatsapp text-3xl"></i>
    </a>

    <!-- Navegação -->
    <nav class="sticky top-0 z-50 p-6 flex justify-between items-center glass border-b border-slate-800">
        <div class="text-2xl font-bold tracking-tighter text-white">SENSUS <span class="text-cyan-500">OEE</span></div>
        <div class="space-x-6">
            <a href="#inicio" class="text-slate-400 hover:text-cyan-400 transition">Início</a>
            <a href="#manifesto" class="text-slate-400 hover:text-cyan-400 transition">Manifesto</a>
        </div>
    </nav>

    <main class="max-w-4xl mx-auto p-6 space-y-24 mt-12">
        
        <!-- Hero -->
        <section id="inicio" class="text-center py-16">
            <!-- Logotipo em CSS: Engrenagem estilizada -->
            <div class="w-48 h-48 mx-auto mb-8 rounded-full border-4 border-cyan-500 shadow-[0_0_30px_rgba(6,182,212,0.3)] flex items-center justify-center bg-slate-900 spin">
                <i class="fa-solid fa-gear text-8xl text-cyan-500"></i>
            </div>
            
            <h1 class="text-5xl md:text-6xl font-bold mb-6 gradient-text">A Inteligência por trás da Eficiência</h1>
            <p class="text-xl text-slate-400 max-w-2xl mx-auto">Transformamos o caos do chão de fábrica em dados precisos para decisões estratégicas.</p>
        </section>

        <!-- Manifesto -->
        <section id="manifesto" class="glass p-12 rounded-3xl">
            <h2 class="text-3xl font-bold mb-8 text-white text-center">A Nossa Missão</h2>
            <p class="text-xl leading-relaxed text-slate-300 text-center italic mb-12">
                "Iluminar o chão de fábrica através da tecnologia, capacitando indústrias a atingirem a sua máxima performance."
            </p>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="p-6 bg-slate-900 rounded-2xl border border-slate-800">
                    <h3 class="font-bold text-cyan-400 mb-2">Transparência</h3>
                    <p class="text-sm text-slate-500">Dados reais e visíveis.</p>
                </div>
                <div class="p-6 bg-slate-900 rounded-2xl border border-slate-800">
                    <h3 class="font-bold text-cyan-400 mb-2">Performance</h3>
                    <p class="text-sm text-slate-500">Foco em resultados mensuráveis.</p>
                </div>
                <div class="p-6 bg-slate-900 rounded-2xl border border-slate-800">
                    <h3 class="font-bold text-cyan-400 mb-2">Simplicidade</h3>
                    <p class="text-sm text-slate-500">Tecnologia sem complexidade.</p>
                </div>
            </div>
        </section>
    </main>

    <footer class="py-12 text-center text-slate-600 border-t border-slate-800 mt-24">
        <p>Sensus OEE – Dados reais. Resultados visíveis.</p>
    </footer>
</body>
</html>
