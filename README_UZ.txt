TOURISM WORKFORCE PLATFORM — YANGILANGAN VERSIYA

Ishga tushirish:
1. ZIP faylni oching.
2. Tourism_Workforce_Platform_Final_Update papkasidagi index.html faylini brauzerda oching yoki VS Code Live Server bilan ishga tushiring.
3. KIRISH tugmasini bosing.

Kirish ma’lumotlari (login maydoniga 8 raqamli loginni kiriting):

TALABA — 10 ta hisob:
10293847 / St2026#a1
10293848 / St2026#b2
10293849 / St2026#c3
10293850 / St2026#d4
10293851 / St2026#e5
10293852 / St2026#f6
10293853 / St2026#g7
10293854 / St2026#h8
10293855 / St2026#k9
10293856 / St2026#m0

TASHKILOT / ISH BERUVCHI — 10 ta hisob:
20384751 / Org99#x1
20384752 / Org99#x2
20384753 / Org99#x3
20384754 / Org99#x4
20384755 / Org99#x5
20384756 / Org99#x6
20384757 / Org99#x7
20384758 / Org99#x8
20384759 / Org99#x9
20384760 / Org99#x10

UNIVERSITET — 10 ta hisob:
30475861 / Univ77*a
30475862 / Univ77*b
30475863 / Univ77*c
30475864 / Univ77*d
30475865 / Univ77*e
30475866 / Univ77*f
30475867 / Univ77*g
30475868 / Univ77*h
30475869 / Univ77*j
30475870 / Univ77*k

SUPER ADMIN (BOSH ADMINISTRATOR) — Tizimni to‘liq boshqarish:
admin / Admin2026#  (yoki login: 99999999 / parol: Admin2026#)

Rollar:
- Talaba: o‘z profilini, universitetini, ish tajribasini, rasmini, sertifikatlarini, kurs va dars natijalarini to‘ldiradi.
- Universitet: o‘z profilini yaratadi, rasmiy email va logotipini saqlaydi, e’lon joylaydi va boshqa universitetlarning profillari/e’lonlarini ko‘radi; talabalar profil va natijalarini faqat ko‘rish rejimida ko‘radi. Ish e’lonlariga ariza yubora olmaydi.
- Tashkilot / ish beruvchi: tashkilot profilini (nomi, emaili, rasmi) saqlaydi; ish yoki amaliyot e’lonlarini joylaydi, ko‘radi/o‘chiradi va talabalar bilan email orqali bog‘lanishi mumkin. Kabinetda boshqa tashkilotlarning e’lonlari ko‘rsatilmaydi.
- “Connect / Universitetlar” bo‘limida faqat profil yaratgan universitetlar va ularning e’lonlari ko‘rsatiladi; qidiruv va joylashuv filtrlari olib tashlangan.

Email va fayllar:
- Aloqa formasida CV va boshqa fayllarni biriktirish mumkin.
- Profil rasmi va sertifikat/fayllar emailga yuborilmaydi; ular faqat shu login profilida saqlanadi.
- Ishga ariza tegishli tashkilot emailiga, amaliyot joyi so‘rovi tanlangan tashkilot emailiga, tashkilotning talaba bilan xabari talabaning profilida ko‘rsatilgan emailga yuborishga urinadi.
- Birinchi yuborishda FormSubmit emailingizni tasdiqlashni so‘rashi mumkin.
- Fayl hajmi va email xizmatining cheklovlari sabab ayrim katta fayllar yuborilmasligi mumkin.

Saqlash va xavfsizlik bo‘yicha muhim ma’lumot:
- Profil, fayllar va kurs natijalari hozircha ayni brauzerning localStorage xotirasida saqlanadi. Brauzer ma’lumotlari o‘chirib yuborilsa yoki boshqa qurilmadan kirilsa, ular avtomatik ko‘chmaydi.
- Universitet va ish beruvchi ko‘radigan foydalanuvchi ma’lumotlari ham shu brauzer xotirasi bilan cheklangan. Demak, profillar turli kompyuter yoki telefonlarda avtomatik ko‘rinmaydi. Barcha foydalanuvchilar o‘rtasida umumiy saqlash uchun server, ma’lumotlar bazasi va haqiqiy autentifikatsiya kerak.
- Login va parol frontend kodida turibdi; bu ishlab chiqarishdagi xavfsiz autentifikatsiya o‘rnini bosa olmaydi. Saytni ommaga ishga tushirishdan oldin server tomonida xavfsiz login tizimini joriy qilish zarur.
- Kursni yakunlash uchun barcha nazariy darslarni tugatish kerak. Shundan so‘ng “Kursning nazariy qismini yakunlash” tugmasi chiqadi; bosilganda kurs nomi va yakunlangan sana talaba profilida saqlanadi.

AMALIYOT VAQTI:
- AM: 00:00–11:59 — yarim tundan tushgacha.
- PM: 12:00–23:59 — tushdan yarim tungacha.
- Vaqt tanlagich 24 soatlik ko‘rinishda bo‘lsa, 19:00 — kechki 7 degani.
- Amaliyot sahifasida har bir “Start Practice” topshirig‘i uchun 3 ta vaziyat, savollar va namunaviy javoblar mavjud; vaziyatlar o‘zbek, ingliz, rus va turk tillarida ko‘rsatiladi.
- Bosh sahifada hamma foydalanuvchi e’lonlarni faqat ko‘radi. “Ish e’lonlari” sahifasida ariza yuborish tugmasi faqat talaba login-paroli bilan kirganda ko‘rinadi; ariza tashkilot emailiga yuborishga topshiriladi.
- Tashkilot profilini saqlash orqali amaliyot joylari ro‘yxatiga qo‘shiladi. Ish e’lonlari va tashkilotlar uchun demo nomlar/namunaviy e’lonlar olib tashlangan.


YANGILANISH V8 (2026-10-12)
- Tashkilot profil rasmi uchun 30 MB gacha JPG/PNG/WEBP manba fayli qabul qilinadi va brauzer xotirasiga moslab avtomatik siqiladi. Tanlangan rasm saqlashdan oldin ko‘rinadi.
- Tashkilot profilini saqlashda rasm va e’lonlardagi nusxalar hajmi kamaytirilgan, xotira cheklovi bo‘lsa rasm e’lon ma’lumotlaridan alohida kichiklashtiriladi.
- Talaba barcha nazariy darslarni tugatganda “Amaliyot muddatini belgilashga o‘tish” tugmasi ko‘rinadi va amaliyot sanasi/vaqti bo‘limiga olib boradi.
- Amaliyot joyi ro‘yxatida faqat stajirovka/amaliyot e’loni joylagan tashkilotlar chiqadi; tanlanganda tashkilot logotipi, nomi, manzili, emaili va e’lon nomi ko‘rsatiladi. So‘rov tashkilot profilida kiritilgan email manziliga yuborishga topshiriladi.
- Talaba kabinetidagi “Professional Profile” bo‘limi “Talaba profili” deb ko‘rsatiladi; “Universitet profili” faqat universitet loginida qoladi.

V9 — TASHKILOT PROFIL RASMI SAQLASH TUZATISHI
- Tashkilot rasmi 30 MB gacha fayldan olinadi, so‘ng avtomatik ravishda juda kichik JPEG ko‘rinishiga siqiladi.
- Profil rasmi endi har bir ish e’loniga alohida ko‘chirib yozilmaydi; bitta tashkilot profilida saqlanadi va e’lonlarda shu yerdan ko‘rsatiladi.
- Eski versiyalarda ish e’lonlari ichida takror saqlangan rasmlar avtomatik tozalanadi, brauzer xotirasidagi joy tejaladi.

YANGILANISH V10 (2026-10-12)
- Tashkilot logotipi endi IndexedDB brauzer bazasiga ham saqlanadi; bu rasmni localStorage hajmiga bog‘lab qo‘ymaydi.
- Profil rasmi oldingidan ancha kichik JPEG ko‘rinishiga siqiladi, shuning uchun profil ma’lumotlariga kamroq joy kerak bo‘ladi.
- Saqlashdan oldin eski ish/amaliyot e’lonlaridagi takroriy rasm nusxalari tozalanadi. E’lonlar va talaba kurs natijalari ataylab o‘chirilmaydi.
- Agar localStorage xotirasi juda to‘la bo‘lsa, sayt avval tashkilotning matnli ma’lumotlarini saqlashga urinadi va rasmni alohida bazadan ko‘rsatadi.
- Tashkilot logotipi brauzer xotirasida saqlanadi; bu hali turli qurilmalar orasida umumiy server saqlashi degani emas.


YANGILANISH V11 (2026-10-12)
- Barcha kurs nazariy darslari tugatilgach “Kursning nazariy qismini yakunlash” tugmasi chiqadi.
- Tugma bosilganda kurs nomi, yakunlangan sana va natija talaba profiliga qo‘shiladi. Bu ma’lumot universitet va ish beruvchi kabinetlaridagi talaba profili ko‘rinishida ham chiqadi.
- Tashkilot va universitet logotiplari IndexedDB alohida xotirasida saqlanadi; katta rasm ma’lumotlari localStorage ichiga qayta-qayta yozilmaydi. Universitet rasmi uchun ham avtomatik kichraytirish va oldindan ko‘rish qo‘shildi.
- Eslatma: sayt hozircha serverga ulanmagan. “Hammaga ko‘rinish” ayni brauzer xotirasidan foydalanuvchi profillar orasida ishlaydi; turli qurilmalar va internetdagi barcha foydalanuvchilar uchun umumiy ko‘rinish server va ma’lumotlar bazasini talab qiladi.


YANGILANISH V12 (2026-10-12)
- Universitet kabinetida avval joylangan e’lonlar uchun “Tahrirlash” tugmasi qo‘shildi. Sarlavha, tavsif va muddatni o‘zgartirib, o‘sha e’lonni yangilash mumkin.
- Tashkilot kabinetida avval joylangan ish/amaliyot e’lonlari uchun “Tahrirlash” tugmasi qo‘shildi. Lavozim, turi, ish shakli, sektor, tajriba darajasi, muddat va tavsifni o‘zgartirib saqlash mumkin.
- Tahrirlashda yangi e’lon nusxasi yaratilmaydi: mavjud e’lonning ID raqami saqlanadi va umumiy e’lonlar ro‘yxati yangilanadi.
- “Tahrirlashni bekor qilish” tugmasi qo‘shildi.


V14 YANGILANISHLARI
- Universitet kabinetidagi “Talabalar natijalari” bo‘limida faqat universitet profilidagi nomga mos universitetni talaba profilida ko‘rsatgan talabalar chiqadi. TSUE va Toshkent davlat iqtisodiyot universiteti nomlari bitta universitet sifatida moslashtiriladi.
- CONTACT / ALOQA formasi xabar va biriktirilgan PDF faylni fxzm916@gmail.com manziliga yuborishga sozlangan. FormSubmit xizmatida ushbu email birinchi marta tasdiqlanishi mumkin.
- Tashkilot boshqa foydalanuvchiga email yuborganda xabarda tizim profilidagi tashkilot nomi ko‘rsatiladi.
- Talaba, universitet va tashkilot profillarida yuklangan profil rasmini olib tashlash tugmasi mavjud.
- Til almashtirilganda tarjimasi topilmagan matn avvalgi tilda qolib ketmasdan asl matnga qaytadi; mavjud tarjimalar tanlangan tilga o‘tkaziladi.

ESLATMA: loyiha hozircha statik brauzer sayti. Talabalar profillari va natijalari bitta brauzerning localStorage xotirasidan olinadi; boshqa qurilmalardagi foydalanuvchilar ma’lumotlarini umumiy ko‘rish uchun server va markaziy ma’lumotlar bazasi kerak.


V15 YANGILANISHLARI (2026-10-12)
- Aloqa formasi xabar va PDF fayllarni fxzm916@gmail.com manziliga yuborish uchun AJAX/multipart yuborish oqimiga o‘tkazildi; yuborish holati haqida xabar beradi. FormSubmit birinchi marta tasdiqlash talab qilishi mumkin.
- Tashkilot kabinetidagi “Kelgan arizalar” ichida “Profil / Skill Passport” tugmasi orqali nomzodning emaili, universiteti, mutaxassisligi, tillari, skills, ish tajribasi, kurslari va yuklangan fayllarini ko‘rish qo‘shildi.
- “Talabaga email yuborish” tugmasi xabarni talabaning Skill Passport profilida saqlangan emailiga yo‘naltiradi; tashkilot profilidagi email javob uchun reply-to sifatida biriktiriladi va tashkilot nomi xabarda ko‘rsatiladi.
- Talaba arizasidagi email Skill Passport profilidan olinadi va o‘zgartirib yuborishning oldi olinadi.
- Sertifikat/fayllar localStorage o‘rniga IndexedDB brauzer bazasida saqlanadi; eski fayllar imkon bo‘lsa avtomatik ko‘chiriladi. Yuklangan faylni o‘chirish, tanlangan faylni bekor qilish hamda profil rasmini olib tashlash/bekor qilish boshqaruvlari qo‘shildi.
- Cheklov: IndexedDB faqat shu brauzer/qurilmada saqlaydi. Turli foydalanuvchilar va qurilmalar o‘rtasida doimiy umumiy saqlash uchun server/backend va markaziy ma’lumotlar bazasi kerak. Email yetkazilishi FormSubmit tasdiqlashiga ham bog‘liq.


V16 YANGILANISHLARI (SUPER ADMIN & LMS DARSLAR BOSHQARUVI):
- Til almashtirgich (Language Switcher) to‘liq sinxronlashtirildi: O‘zbek, English, Русский va Türkçe tillari tanlanganda yuqori menyudagi barcha havolalar (Bosh sahifa, Ish e’lonlari, Qo‘llanmalar, Aloqa) hamda kirish tugmalari (KIRISH / LOGIN / ВХОД / GİRİŞ va KABINETGA KIRISH ↗) to‘liq tanlangan tilda ko‘rsatiladi.
- Super Admin paneliga to‘liq LMS darslar boshqaruvi qo‘shildi:
  1. Har bir kurs kartasida "🎬 Darslar & Video" tugmasi orqali istalgan kurs darslarini boshqarish mumkin.
  2. Dars videolari (YouTube havola): Super Admin har bir darsga alohida YouTube to‘liq video havolasini kiritishi yoki o‘zgartirishi mumkin.
  3. Dars mavzulari va matnlari: Dars sarlavhasi (mavzu nomi) va dars konspekti/matnini admin panel orqali mustaqil yozish va saqlash imkoniyati yaratildi.
  4. Dars qo‘llanmalari (PDF): Kursning umumiy PDF qo‘llanmasi va har bir darsning alohida PDF materiali havolasini admin paneldan sozlash mumkin.
  5. Kiritilgan barcha o‘zgarishlar darhol saytda, kurs tafsilotlari va dars pleyerida aks etadi.
