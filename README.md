# Hunny-project-1
<!DOCTYPE html><html lang="lo">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Lao Vacation | ທ່ຽວລາວແບບຄົນລາວ</title>
  <style>
    body { font-family: sans-serif; margin: 0; background: #f9f9f9; color: #333; }
    header { background: #00695c; color: white; padding: 1.5rem; text-align: center; }
    nav { background: #004d40; padding: 1rem; display: flex; justify-content: center; flex-wrap: wrap; }
    nav a { color: white; margin: 0 1rem; text-decoration: none; font-weight: bold; }
    section { padding: 2rem; max-width: 1000px; margin: auto; }
    footer { background: #004d40; color: white; text-align: center; padding: 1rem; margin-top: 2rem; }
    .spotlight { background: white; padding: 1.5rem; margin-bottom: 1.5rem; border-radius: 10px; box-shadow: 0 0 10px rgba(0,0,0,0.05); }
    h2 { color: #00796b; }
    .lang-switch { text-align: center; margin-top: 1rem; }
    .lang-switch button { margin: 0 5px; padding: 5px 10px; background: #00796b; color: white; border: none; cursor: pointer; border-radius: 5px; }
  </style>
  <script>
    function switchLang(lang) {
      document.querySelectorAll('[data-lang]').forEach(el => {
        el.style.display = el.dataset.lang === lang ? 'block' : 'none';
      });
    }
    window.onload = () => switchLang('lo');
  </script>
</head>
<body>
  <header>
    <h1>🌏 Lao Vacation | ທ່ຽວລາວແບບຄົນລາວ</h1>
    <p>ຄູ່ມືທ່ຽວໂດຍຄົນລາວ ເພື່ອຄົນທົ່ວໂລກ</p>
    <div class="lang-switch">
      <button onclick="switchLang('lo')">ພາສາລາວ</button>
      <button onclick="switchLang('th')">ไทย</button>
      <button onclick="switchLang('en')">English</button>
    </div>
  </header>
  <nav>
    <a href="#places">ແຫຼ່ງທ່ຽວ</a>
    <a href="#food">ອາຫານ</a>
    <a href="#culture">ວັດທະນະທຳ</a>
    <a href="#plan">ວາງແຜນ</a>
    <a href="#contact">ຕິດຕໍ່</a>
  </nav>  <section id="places">
    <div class="spotlight">
      <h2>🏞️ <span data-lang="lo">ແຫຼ່ງທ່ຽວຍອດນິຍົມ</span><span data-lang="th">สถานที่ท่องเที่ยวยอดนิยม</span><span data-lang="en">Top Tourist Destinations</span></h2>
      <ul>
        <li data-lang="all">ຫຼວງພະບາງ / Luang Prabang – UNESCO World Heritage</li>
        <li data-lang="all">ວັງວຽງ / Vang Vieng – Nature & Adventure</li>
        <li data-lang="all">ຈໍາປາສັກ / Champasak – Wat Phou & Southern Laos</li>
        <li data-lang="all">ວຽງຈັນ / Vientiane – Capital Culture</li>
      </ul>
    </div>
  </section>  <section id="food">
    <div class="spotlight">
      <h2>🍲 <span data-lang="lo">ອາຫານລາວທີ່ຕ້ອງລອງ</span><span data-lang="th">อาหารลาวที่ต้องลอง</span><span data-lang="en">Must-Try Lao Dishes</span></h2>
      <p data-lang="lo">ລາບ, ເຂົ້າໜຽວ, ໄກ່ຢ່າງ, ຊຸບໜໍໄມ້, ເຂົ້າຈີ່ ແລະ ອື່ນໆ</p>
      <p data-lang="th">ลาบ, ข้าวเหนียว, ไก่ย่าง, ซุปหน่อไม้, ข้าวจี่ ฯลฯ</p>
      <p data-lang="en">Larb, sticky rice, grilled chicken, bamboo soup, baguette sandwiches and more!</p>
    </div>
  </section>  <section id="culture">
    <div class="spotlight">
      <h2>📜 <span data-lang="lo">ວັດທະນະທຳ ແລະ ປະເພນີ</span><span data-lang="th">วัฒนธรรมและประเพณี</span><span data-lang="en">Culture and Traditions</span></h2>
      <p data-lang="lo">ຮຽນຮູ້ກ່ຽວກັບ ພາສາ ສາສະໜາ ແລະ ບຸນປີໃໝ່ລາວ ແລະ ບຸນບັ້ງໄຟ</p>
      <p data-lang="th">เรียนรู้เกี่ยวกับภาษา ศาสนา มารยาท และเทศกาลสำคัญ เช่น ปีใหม่ลาว บุญบั้งไฟ</p>
      <p data-lang="en">Explore the Lao language, religion, etiquette, and major festivals like Lao New Year and Rocket Festival</p>
    </div>
  </section>  <section id="plan">
    <div class="spotlight">
      <h2>🛫 <span data-lang="lo">ການວາງແຜນການເດີນທາງ</span><span data-lang="th">วางแผนการเดินทาง</span><span data-lang="en">Travel Planning</span></h2>
      <p data-lang="lo">ແນະນຳວິທີເດີນທາງ ດ້ວຍ ລົດ ເຮືອ ຫຼື ລົດໄຟ ຈາກຈີນ ແລະ ທີ່ພັກແນະນຳ</p>
      <p data-lang="th">แนะนำการเดินทางด้วยรถ เรือ หรือรถไฟจากจีน การเตรียมงบประมาณ และที่พักแนะนำ</p>
      <p data-lang="en">Tips for traveling by bus, boat or train from China, budget planning, and recommended stays</p>
    </div>
  </section>  <section id="contact">
    <div class="spotlight">
      <h2>📞 <span data-lang="lo">ຕິດຕໍ່ເຮົາ</span><span data-lang="th">ติดต่อเรา</span><span data-lang="en">Contact Us</span></h2>
      <ul>
        <li data-lang="all">Facebook: fb.com/laovacation</li>
        <li data-lang="all">Email: laovacation@gmail.com</li>
        <li data-lang="all">WhatsApp: +856-20-xxxx-xxxx</li>
      </ul>
    </div>
  </section>  <footer>
    <p>&copy; 2025 Lao Vacation | Made with ❤️ in Laos</p>
  </footer>
</body>
</html>
