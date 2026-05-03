<!DOCTYPE html><html lang="fr">

<head>

&#x20; <meta charset="UTF-8" />

&#x20; <meta name="viewport" content="width=device-width, initial-scale=1.0" />

&#x20; <title>N'guettia Service | Trouvez vos clients</title>

&#x20; <script src="https://cdn.tailwindcss.com"></script>

&#x20; <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" rel="stylesheet">

</head>

<body class="bg-gray-50 font-sans"><!-- NAVBAR --><nav class="bg-white shadow fixed w-full z-50">

&#x20; <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">

&#x20;   <h1 class="font-bold text-xl text-green-600">N'guettia Service</h1>

&#x20;   <a href="#devis" class="bg-green-600 text-white px-4 py-2 rounded-xl">Devis Gratuit</a>

&#x20; </div>

</nav><!-- HERO --><section class="h-screen flex items-center justify-center text-center bg-gradient-to-r from-green-600 to-green-400 text-white px-6">

&#x20; <div>

&#x20;   <h2 class="text-4xl md:text-5xl font-bold mb-4">Besoin d’un artisan fiable ?</h2>

&#x20;   <p class="mb-6 text-lg">Peinture • Électricité • Décoration rapide et professionnelle</p>

&#x20;   <a href="#devis" class="bg-white text-green-600 px-8 py-3 rounded-xl font-semibold shadow">Obtenir un devis gratuit</a>

&#x20; </div>

</section><!-- PREUVE SOCIALE --><section class="py-10 bg-white text-center">

&#x20; <h3 class="text-xl font-bold mb-4">+100 clients satisfaits en Côte d’Ivoire</h3>

&#x20; <p class="text-gray-600">Travaux réalisés avec qualité et respect des délais</p>

</section><!-- SERVICES --><section class="py-16 px-6 max-w-7xl mx-auto">

&#x20; <h2 class="text-3xl font-bold text-center mb-10">Nos Services</h2>

&#x20; <div class="grid md:grid-cols-3 gap-8"><div class="bg-white p-6 rounded-2xl shadow">

&#x20; <i class="fas fa-paint-roller text-green-600 text-3xl mb-4"></i>

&#x20; <h3 class="font-bold text-xl mb-2">Peinture</h3>

&#x20; <p>Maison, bureau, extérieur avec finition haut niveau</p>

</div>



<div class="bg-white p-6 rounded-2xl shadow">

&#x20; <i class="fas fa-bolt text-green-600 text-3xl mb-4"></i>

&#x20; <h3 class="font-bold text-xl mb-2">Électricité</h3>

&#x20; <p>Installation rapide et sécurisée</p>

</div>



<div class="bg-white p-6 rounded-2xl shadow">

&#x20; <i class="fas fa-couch text-green-600 text-3xl mb-4"></i>

&#x20; <h3 class="font-bold text-xl mb-2">Décoration</h3>

&#x20; <p>Design moderne et personnalisé</p>

</div>



&#x20; </div>

</section><!-- OFFRE --><section class="bg-green-600 text-white text-center py-12">

&#x20; <h2 class="text-3xl font-bold mb-4">🎯 Devis GRATUIT en moins de 10 minutes</h2>

&#x20; <p>Réponse rapide sur WhatsApp</p>

</section><!-- FORMULAIRE DE LEADS --><section id="devis" class="py-16 px-6 bg-white">

&#x20; <h2 class="text-3xl font-bold text-center mb-10">Demande de Devis</h2>

&#x20; <div class="max-w-2xl mx-auto"><form onsubmit="sendToWhatsApp(event)" class="grid gap-4">

&#x20; <input id="nom" type="text" placeholder="Nom" class="p-3 border rounded" required>

&#x20; <input id="tel" type="text" placeholder="Téléphone" class="p-3 border rounded" required>

&#x20; <select id="service" class="p-3 border rounded">

&#x20;   <option>Peinture</option>

&#x20;   <option>Électricité</option>

&#x20;   <option>Décoration</option>

&#x20; </select>

&#x20; <textarea id="message" placeholder="Décris ton besoin" class="p-3 border rounded" rows="4"></textarea>

&#x20; <button class="bg-green-600 text-white py-3 rounded-xl">Envoyer sur WhatsApp</button>

</form>



&#x20; </div>

</section><!-- WHATSAPP SCRIPT --><script>

function sendToWhatsApp(e) {

&#x20; e.preventDefault();

&#x20; let nom = document.getElementById('nom').value;

&#x20; let tel = document.getElementById('tel').value;

&#x20; let service = document.getElementById('service').value;

&#x20; let message = document.getElementById('message').value;



&#x20; let url = https://wa.me/2250779948903?text=Bonjour je m'appelle ${nom}, Téléphone: ${tel}, Service: ${service}, Besoin: ${message};

&#x20; window.open(url, '\_blank');

}

</script><!-- URGENCE --><section class="text-center py-10 bg-gray-100">

&#x20; <p class="text-lg font-semibold">⚡ Intervention rapide - Disponible immédiatement</p>

</section><!-- FOOTER --><footer class="bg-green-600 text-white text-center p-6">

&#x20; <p>© 2026 N'guettia Service - Tous droits réservés</p>

</footer></body>

* </html>

