# GriefCube.me
GriefCube
О сервереПравилаКомандаДонат
Grief Cube
Анархия. Гриф. Хаос. Выживает сильнейший. Никаких правил — только кубический мир без границ.
play.griefcube.ruнажми, чтобы скопироватьОнлайн: 247 игроков
 Начать играть
Почему Grief Cube?

Есть Приваты 
🔥
Ивенты каждый месяц
Захват крепостей, гонки, дуэли на выживание. Призы — ценные ресурсы.
⚡
Мощный хостинг
Никаких лагов. 1.26.2, поддержка 500+ игроков одновременно.
🎁
Кейсы и награды
Ежедневные бонусы, кейсы за игру, редкие скины и предметы.
Правила сервера
Запрещены читы и сторонние программы. Использование X-Ray, Killaura и т.п. — бан навсегда.
Запрещены дюпы и багоюз. Использование багов — блокировка аккаунта.
Запрещены атаки на сервер. DDoS, крашеры и эксплойты караются вечным баном.
Реклама запрещена. Ссылки на другие серверы в чате — мут 7 дней.
Оскорбления по признакам (раса, религия, нация) — бан 30 дней.
Гриф разрешён. Всё, что построено в открытом мире — может быть разрушено.
Администрация решает спорные ситуации. Решения админов не обсуждаются.
Наша команда
👑
MrModed
Основатель
🛡️
Qwejoke,MatBobrik228
Главные админы
⚙️
Moder415
Тех. специалист
🎮
Anton_2015
Модератор
Донат привилегии
<div class="donate-card">
  <h3>VIP</h3>
  <div class="price">199 <span>₽</span></div>
  <ul>
    <li>Префикс [VIP]</li>
    <li>Цветной ник в чате</li>
    <li>2 доп. дома</li>
    <li>Доступ к /fly в лобби</li>
  </ul>
  <a href="#" class="btn btn-outline">Купить</a>
</div>

<div class="donate-card popular">
  <h3>PREMIUM</h3>
  <div class="price">499 <span>₽</span></div>
  <ul>
    <li>Префикс [PREMIUM]</li>
    <li>5 доп. домов</li>
    <li>Кит раз в 24 часа</li>
    <li>Доступ к /craft и /ec</li>
    <li>Цветные сообщения</li>
  </ul>
  <a href="#" class="btn">Купить</a>
</div>

<div class="donate-card">
  <h3>LEGEND</h3>
  <div class="price">999 <span>₽</span></div>
  <ul>
    <li>Префикс [LEGEND]</li>
    <li>10 доп. домов</li>
    <li>Кит раз в 12 часов</li>
    <li>Доступ к /heal и /feed</li>
    <li>Свой цвет ника</li>
    <li>Приоритет входа</li>
  </ul>
  <a href="#" class="btn btn-outline">Купить</a>
</div>

GriefCube
© 2025 Grief Cube. Все права защищены. Minecraft — торговая марка Mojang AB.
Связь: Discord · Telegram · VK
IP скопирован: griefcube.progamer.me
  // Копирование IP
  function copyIP() {
    navigator.clipboard.writeText('play.griefcube.ru').then(() => {
      const toast = document.getElementById('toast');
      toast.classList.add('show');
      setTimeout(() => toast.classList.remove('show'), 2500);
    });
  }

  // Анимация появления секций
  const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
      if (entry.isIntersecting) entry.target.classList.add('visible');
    });
  }, { threshold: 0.15 });

  document.querySelectorAll('.fade-in').forEach(el => observer.observe(el));

  // Плавная прокрутка
  document.querySelectorAll('a[href^="#"]').forEach(link => {
    link.addEventListener('click', e => {
      const target = document.querySelector(link.getAttribute('href'));
      if (target) {
        e.preventDefault();
        target.scrollIntoView({ behavior: 'smooth' });
      }
    });
  });

  // Имитация онлайна
  const onlineEl = document.getElementById('online-count');
  setInterval(() => {
    const base = 247;
    const change = Math.floor(Math.random() * 21) - 10;
    onlineEl.textContent = base + change;
  }, 3000);
