<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Undangan Peringatan Maulid Nabi</title>
    <!-- Font Inter dari Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    
    <!-- Link Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Konfigurasi Tailwind untuk warna dan font -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        'primary': '#4a1e9e', // Ungu gelap
                        'secondary': '#fef3c7', // Kuning muda
                        'dark-bg': '#1f2937', // Abu gelap
                    }
                }
            }
        }
    </script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f3f4f6;
            background-image: linear-gradient(135deg, #f0fdf4 0%, #dcfce7 100%);
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 2rem;
        }
        .invitation-card {
            background-color: white;
            padding: 2.5rem;
            border-radius: 1.5rem;
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
            max-width: 600px;
            text-align: center;
            border: 2px solid #fef3c7;
        }
        .glow {
            text-shadow: 0 0 8px rgba(254, 243, 199, 0.8), 0 0 12px rgba(254, 243, 199, 0.6);
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .fade-in-element {
            animation: fadeIn 1s ease-out forwards;
        }
    </style>
</head>
<body>

    <!-- Kartu Undangan -->
    <div class="invitation-card space-y-6 fade-in-element">
        
        <!-- Judul -->
        <h1 class="text-3xl sm:text-4xl font-extrabold text-primary mb-2">
            Undangan <br> Peringatan Maulid Nabi Muhammad SAW
        </h1>
        
        <!-- Kata Pengantar -->
        <p class="text-gray-600 font-medium leading-relaxed">
            `Assalamu'alaikum Warahmatullahi Wabarakatuh.`
            <br><br>
            Dengan rahmat dan karunia Allah SWT, kami mengundang Sahabat IRMA sekalian untuk hadir dalam acara Peringatan Maulid Nabi Muhammad SAW. Mari bersama-sama menebar kebaikan dan meneladani akhlak mulia Rasulullah, demi kesejahteraan kita bersama di dunia dan akhirat.
        </p>
        
        <!-- Detail Acara -->
        <div class="bg-gray-50 p-6 rounded-xl border border-gray-200">
            <div class="flex flex-col sm:flex-row justify-around items-center space-y-4 sm:space-y-0 sm:space-x-4 text-center">
                <div class="flex-1">
                    <p class="text-lg font-bold text-gray-800">Hari & Tanggal:</p>
                    <p class="text-md text-gray-700">Sabtu, 6 September 2025</p>
                </div>
                <div class="flex-1">
                    <p class="text-lg font-bold text-gray-800">Waktu:</p>
                    <p class="text-md text-gray-700">Ba'da Isya - Selesai</p>
                </div>
            </div>
        </div>
        
        <!-- Dress Code -->
        <div class="space-y-4">
            <h2 class="text-2xl font-bold text-primary">Dress Code</h2>
            <div class="flex flex-col sm:flex-row justify-center items-center gap-4 text-left">
                <!-- Pakaian Laki-laki -->
                <div class="bg-white p-4 rounded-xl border-l-4 border-yellow-500 shadow-md flex-1">
                    <p class="text-lg font-semibold text-gray-800">Laki-laki:</p>
                    <p class="text-md text-gray-600">Baju putih, bawahan hitam</p>
                </div>
                <!-- Pakaian Perempuan -->
                <div class="bg-white p-4 rounded-xl border-l-4 border-yellow-500 shadow-md flex-1">
                    <p class="text-lg font-semibold text-gray-800">Perempuan:</p>
                    <p class="text-md text-gray-600">Gamis hitam, jilbab hitam</p>
                </div>
            </div>
        </div>
        
        <!-- Lokasi -->
        <div class="space-y-2 mt-6">
            <h2 class="text-2xl font-bold text-primary">Lokasi Acara</h2>
            <p class="text-lg font-semibold text-gray-800">Masjid Darul Iman Tarakan</p>
            <a href="https://maps.app.goo.gl/KTYSAr9hfhk4aVCBA?g_st=aw" target="_blank" class="inline-block bg-primary text-white font-bold py-3 px-6 rounded-full transition-transform transform hover:scale-105 shadow-lg">
                Lihat di Google Maps
            </a>
        </div>
        
        <!-- Kalimat Penutup -->
        <p class="mt-8 text-gray-600 italic">
            Atas kehadiran dan partisipasi Sahabat IRMA, kami ucapkan terima kasih.
            <br>
            `Wassalamu'alaikum Warahmatullahi Wabarakatuh.`
        </p>

    </div>

</body>
</html>
