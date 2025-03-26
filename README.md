<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Surprise Ulang Tahun!</title>
    <script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.0.1"></script>
</head>
<body>
    <h1>Selamat Ulang Tahun!</h1>
    <p>Klik tombol di bawah untuk kejutan 🎉</p>
    <button onclick="showSurprise()">Klik di sini</button>

    <script>
        function showSurprise() {
            confetti();
            alert("Semoga harimu menyenangkan! 🎂");
        }
    </script>
</body>
</html>
