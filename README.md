# BLUR-sastab

<!DOCTYPE html>
Bu qator HTML hujjati ekanini bildiradi. Brauzerga bu fayl HTML5 formatida yozilganini aytadi.

html

<html>
 Hujjatning asosiy boshlanish tegi. Barcha HTML tarkibi shu teg ichida bo‘ladi.

html

<head>
 Hujjatning bosh qismi. Bu qismda skriptlar, stillar, sarlavha (title) va boshqa texnik ma’lumotlar joylashadi.

html

    <script>
 Bu teg ichida JavaScript kodi yoziladi.

javascript

        function meningFunksiyam() {
 meningFunksiyam nomli funksiya e’lon qilinyapti. Bu funksiya tugma bosilganda bajariladi.

javascript

          document.getElementById("id").innerHTML = "Ma'lumot almashtirildi";
 HTML hujjatidagi id="id" bo‘lgan element topiladi va uning ichidagi matn "Ma'lumot almashtirildi" ga almashtiriladi.

javascript

        }
 Funksiya tugaganini bildiradi.

javascript

        function meningFunksiyam1() {
 Yangi funksiya (meningFunksiyam1) e’lon qilinyapti.

javascript

          document.getElementById("id").innerHTML = "Hello world";
 id="id" elementining ichidagi matn yana "Hello world" holatiga qaytariladi.

javascript

        }
 Funksiya tugashi.

javascript

        function meningFunksiyam2() {
 Uchinchi funksiya (meningFunksiyam2) e’lon qilinyapti.

javascript

          document.getElementById("id").innerHTML = "";
 id="id" elementining ichidagi matn bo‘sh qilinadi (ya’ni o‘chiriladi).

javascript

        }
 Funksiya tugashi.

html

        </script>
 JavaScript kodi tugadi.

html

</head>
 Hujjatning bosh qismi tugadi.

html

<body>
 Hujjatning ko‘rinadigan qismi (saytda foydalanuvchi ko‘radi) shu teg ichida joylashadi.

html

<h2 id="id">Hello world</h2>
 Bu sarlavha (<h2>) bo‘lib, id="id" deb nomlangan. JavaScript orqali shu element ustida o‘zgarishlar qilinadi. Dastlabki matn — “Hello world”.

html

<button type="button" onclick="meningFunksiyam()">Almashtirish knopkasi</button>
 Tugma yaratilgan. Bosilganda meningFunksiyam() funksiyasi chaqiriladi — ya’ni matn “Ma’lumot almashtirildi” deb o‘zgaradi.

html

<button type="button" onclick="meningFunksiyam1()">Ortga qaytarish</button>
 Bu tugma bosilganda meningFunksiyam1() funksiyasi ishlaydi — matn “Hello world” holatiga qaytadi.

html

<button type="button" onclick="meningFunksiyam2()">ochirish </button>
 Bu tugma bosilganda meningFunksiyam2() funksiyasi ishlaydi — matn to‘liq o‘chiriladi.

html

</body>
 Hujjatning ko‘rinadigan qismi tugadi.

html

</html>
 HTML hujjatining yakuni.

             Qisqacha natija:
Bu kodda uchta tugma bor:

“Almashtirish knopkasi” – matnni “Ma’lumot almashtirildi” ga o‘zgartiradi.

“Ortga qaytarish” – matnni “Hello world” holatiga qaytaradi.

“ochirish” – matnni butunlay o‘chiradi.
