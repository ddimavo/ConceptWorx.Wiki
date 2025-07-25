---
label: TEST
order: 500
icon: sparkles-fill
tags: [Enchantments]
---

<style>
  .enchants-container {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    max-width: 1200px;
    margin: 0 auto;
    color: #333;
  }
  
  .header {
    background: linear-gradient(135deg, #6e48aa 0%, #9d50bb 100%);
    color: white;
    padding: 1.5rem;
    border-radius: 8px;
    margin-bottom: 2rem;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  }
  
  .header h1 {
    margin: 0;
    font-size: 2.2rem;
  }
  
  .category {
    margin-bottom: 3rem;
    background: white;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 2px 10px rgba(0,0,0,0.08);
  }
  
  .category-header {
    background: linear-gradient(135deg, #4776E6 0%, #8E54E9 100%);
    color: white;
    padding: 0.8rem 1.5rem;
    font-size: 1.5rem;
    display: flex;
    align-items: center;
    gap: 10px;
  }
  
  table {
    width: 100%;
    border-collapse: collapse;
    font-size: 0.95rem;
  }
  
  th {
    background-color: #f5f7fa;
    text-align: left;
    padding: 12px 15px;
    font-weight: 600;
    color: #4a5568;
    border-bottom: 2px solid #e2e8f0;
  }
  
  td {
    padding: 12px 15px;
    border-bottom: 1px solid #edf2f7;
    vertical-align: top;
  }
  
  tr:hover {
    background-color: #f8fafc;
  }
  
  .item-icon {
    width: 24px;
    height: 24px;
    vertical-align: middle;
    margin: 0 2px;
  }
  
  .notes {
    background-color: #f0f9ff;
    border-left: 4px solid #3b82f6;
    padding: 1rem;
    margin: 1rem 0;
    border-radius: 0 4px 4px 0;
  }
  
  .notes-title {
    font-weight: bold;
    color: #1e40af;
    margin-bottom: 0.5rem;
  }
  
  .warning {
    background-color: #fff7ed;
    border-left: 4px solid #f97316;
    padding: 1rem;
    margin: 1rem 0;
    border-radius: 0 4px 4px 0;
  }
  
  .warning-title {
    font-weight: bold;
    color: #9a3412;
    margin-bottom: 0.5rem;
  }
  
  .tip {
    background-color: #f0fdf4;
    border-left: 4px solid #22c55e;
    padding: 1rem;
    margin: 1rem 0;
    border-radius: 0 4px 4px 0;
  }
  
  .tip-title {
    font-weight: bold;
    color: #166534;
    margin-bottom: 0.5rem;
  }
  
  .highlight {
    background-color: #fef3c7;
    padding: 2px 4px;
    border-radius: 4px;
  }
  
  @media (max-width: 768px) {
    table {
      display: block;
      overflow-x: auto;
    }
  }
</style>

<div class="enchants-container">
  <div class="header">
    <h1>✨ ExcellentEnchants: Новые зачарования и их подробное описание</h1>
  </div>

  <!-- Armor Enchantments -->
  <div class="category">
    <div class="category-header">🛡️ Зачарования для брони</div>
<table>
  <thead>
    <tr>
      <th>Название (Оригинал)</th>
      <th>Эффект</th>
      <th>Несовместимо с</th>
      <th>Макс. уровень</th>
      <th style="text-align: center;">Основные предметы</th>
      <th style="text-align: center;">Дополнительные предметы</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Холодная Сталь</strong> (Cold Steel)</td>
      <td>Накладывает на атакующего эффект <strong>Усталости</strong> (Mining Fatigue)</td>
      <td></td>
      <td>III</td>
      <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Chestplate.webp" alt="Chestplate"></td>
      <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Elytra.webp" alt="Elytra"></td>
    </tr>
    <tr>
      <td><strong>Плащ Тьмы</strong> (Darkness Cloak)</td>
      <td>Накладывает на атакующего эффект <strong>Тьмы</strong> (Darkness)</td>
      <td></td>
      <td>III</td>
      <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Chestplate.webp" alt="Chestplate"></td>
      <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Elytra.webp" alt="Elytra"></td>
    </tr>
    <tr>
      <td><strong>Защита от Стихий</strong> (Elemental Protection)</td>
      <td>Снижает урон от зелий и стихийных атак (огонь, лава и т.д.)</td>
      <td></td>
      <td>IV</td>
      <td style="text-align: center; vertical-align: middle;">
        <img class="item-icon" src="../static/excellentenchants/Helmet.webp" alt="Helmet">
        <img class="item-icon" src="../static/excellentenchants/Chestplate.webp" alt="Chestplate">
        <img class="item-icon" src="../static/excellentenchants/Leggings.webp" alt="Leggings">
        <img class="item-icon" src="../static/excellentenchants/Boots.webp" alt="Boots">
      </td>
      <td style="text-align: center; vertical-align: middle;"></td>
    </tr>
    <tr>
      <td><strong>Огненный Щит</strong> (Fire Shield)</td>
      <td><strong>Поджигает</strong> атакующего</td>
      <td></td>
      <td>IV</td>
      <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Chestplate.webp" alt="Chestplate"></td>
      <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Elytra.webp" alt="Elytra"></td>
    </tr>
    <tr>
      <td><strong>Огненный Шаг</strong> (Flame Walker)</td>
      <td>Позволяет ходить по лаве, иммунитет к урону от магмы</td>
      <td>(Frost Walker)</td>
      <td>II</td>
      <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Boots.webp" alt="Boots"></td>
      <td style="text-align: center; vertical-align: middle;"></td>
    </tr>
    <tr>
      <td><strong>Закалка</strong> (Hardened)</td>
      <td>Даёт эффект <strong>Сопротивления</strong> (Resistance) при получении урона</td>
      <td></td>
      <td>II</td>
      <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Chestplate.webp" alt="Chestplate"></td>
      <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Elytra.webp" alt="Elytra"></td>
    </tr>
    <tr>
      <td><strong>Ледяной Щит</strong> (Ice Shield)</td>
      <td><strong>Замораживает</strong> и <strong>замедляет</strong> (Slowness) атакующего</td>
      <td></td>
      <td>III</td>
      <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Chestplate.webp" alt="Chestplate"></td>
      <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Elytra.webp" alt="Elytra"></td>
    </tr>
    <tr>
      <td><strong>Прыгучесть</strong> (Jumping)</td>
      <td>Даёт эффект <strong>Прыгучести</strong> (Jump Boost)</td>
      <td></td>
      <td>II</td>
      <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Boots.webp" alt="Boots"></td>
      <td style="text-align: center; vertical-align: middle;"></td>
    </tr>
    <tr>
      <td><strong>Камикадзе</strong> (Kamikadze)</td>
      <td>Создаёт взрыв при смерти</td>
      <td></td>
      <td>III</td>
      <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Chestplate.webp" alt="Chestplate"></td>
      <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Elytra.webp" alt="Elytra"></td>
    </tr>
    <tr>
      <td><strong>Ночное Зрение</strong> (Night Vision)</td>
      <td>Даёт эффект <strong>Ночного зрения</strong> (Night Vision)</td>
      <td></td>
      <td>I</td>
      <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Helmet.webp" alt="Helmet"></td>
      <td style="text-align: center; vertical-align: middle;"></td>
    </tr>
    <tr>
      <td><strong>Отскок</strong> (Rebound)</td>
      <td>Эффект приземления на <strong>слизневый блок</strong> (Slime Block)</td>
      <td>Невесомость (Feather Falling)</td>
      <td>I</td>
      <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Boots.webp" alt="Boots"></td>
      <td style="text-align: center; vertical-align: middle;"></td>
    </tr>
    <tr>
      <td><strong>Регенерация</strong> (Regrowth)</td>
      <td>Восстанавливает определённое количество сердец со временем</td>
      <td></td>
      <td>IV</td>
      <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Chestplate.webp" alt="Chestplate"></td>
      <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Elytra.webp" alt="Elytra"></td>
    </tr>
    <tr>
      <td><strong>Насыщение</strong> (Saturation)</td>
      <td>Восстанавливает определённое количество сытости со временем</td>
      <td></td>
      <td>II</td>
      <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Helmet.webp" alt="Helmet"></td>
      <td style="text-align: center; vertical-align: middle;"></td>
    </tr>
    <tr>
      <td><strong>Скорость</strong> (Speed)</td>
      <td>Даёт эффект <strong>Скорости</strong> (Speed)</td>
      <td></td>
      <td>II</td>
      <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Boots.webp" alt="Boots"></td>
      <td style="text-align: center; vertical-align: middle;"></td>
    </tr>
    <tr>
      <td><strong>Устойчивость</strong> (Stopping Force)</td>
      <td>Уменьшает <strong>отбрасывание</strong> (Knockback) при получении урона</td>
      <td></td>
      <td>III</td>
      <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Leggings.webp" alt="Leggings"></td>
      <td style="text-align: center; vertical-align: middle;"></td>
    </tr>
    <tr>
      <td><strong>Подводное Дыхание</strong> (Water Breathing)</td>
      <td>Даёт эффект <strong>Подводного дыхания</strong> (Water Breathing)</td>
      <td></td>
      <td>I</td>
      <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Helmet.webp" alt="Helmet"></td>
      <td style="text-align: center; vertical-align: middle;"></td>
    </tr>
  </tbody>
</table>
  </div>

  <!-- Bow Enchantments -->
<div class="category">
  <div class="category-header">🏹 Зачарования для лука</div>
  <table>
    <thead>
      <tr>
        <th>Название (Оригинал)</th>
        <th>Эффект</th>
        <th>Несовместимо с</th>
        <th>Макс. уровень</th>
        <th style="text-align: center;">Основной предмет</th>
        <th style="text-align: center;">Дополнительный предмет</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><strong>Бомбардир</strong> (Bomber)</td>
        <td>Выстреливает <strong>TNT</strong> вместо стрел</td>
        <td>Зачарования, изменяющие снаряд; Нестрельные зачарования</td>
        <td>III</td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Bow.webp" alt="Bow"></td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Crossbow.webp" alt="Crossbow"></td>
      </tr>
      <tr>
        <td><strong>Сбивающие стрелы</strong> (Confusing Arrows)</td>
        <td>Накладывает эффект <strong>Тошноты</strong> при попадании</td>
        <td>Нестрельные зачарования</td>
        <td>III</td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Bow.webp" alt="Bow"></td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Crossbow.webp" alt="Crossbow"></td>
      </tr>
      <tr>
        <td><strong>Тёмные стрелы</strong> (Darkness Arrows)</td>
        <td>Накладывает эффект <strong>Тьмы</strong> при попадании</td>
        <td>Нестрельные зачарования</td>
        <td>III</td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Bow.webp" alt="Bow"></td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Crossbow.webp" alt="Crossbow"></td>
      </tr>
      <tr>
        <td><strong>Драконьи стрелы</strong> (Dragonfire Arrows)</td>
        <td>Накладывает <strong>Драконье дыхание</strong> при попадании</td>
        <td>Нестрельные зачарования</td>
        <td>III</td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Bow.webp" alt="Bow"></td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Crossbow.webp" alt="Crossbow"></td>
      </tr>
      <tr>
        <td><strong>Электрические стрелы</strong> (Electrified Arrows)</td>
        <td>Призывает <strong>молнию</strong> в место попадания</td>
        <td>Нестрельные зачарования</td>
        <td>III</td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Bow.webp" alt="Bow"></td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Crossbow.webp" alt="Crossbow"></td>
      </tr>
      <tr>
        <td><strong>Эндер-лук</strong> (Ender Bow)</td>
        <td>Выстреливает <strong>жемчуг Эндера</strong> вместо стрел</td>
        <td>Зачарования, изменяющие снаряд; Нестрельные зачарования</td>
        <td>I</td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Bow.webp" alt="Bow"></td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Crossbow.webp" alt="Crossbow"></td>
      </tr>
      <tr>
        <td><strong>Взрывные стрелы</strong> (Explosive Arrows)</td>
        <td>Стрелы <strong>взрываются</strong> при попадании</td>
        <td>Нестрельные зачарования</td>
        <td>III</td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Bow.webp" alt="Bow"></td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Crossbow.webp" alt="Crossbow"></td>
      </tr>
      <tr>
        <td><strong>Факел</strong> (Flare)</td>
        <td>Устанавливает <strong>факел</strong> в месте падения стрелы</td>
        <td>Нестрельные зачарования</td>
        <td>I</td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Bow.webp" alt="Bow"></td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Crossbow.webp" alt="Crossbow"></td>
      </tr>
      <tr>
        <td><strong>Призрак</strong> (Ghost)</td>
        <td>Выстреливает <strong>огненный шар</strong> вместо стрел</td>
        <td>Зачарования, изменяющие снаряд; Нестрельные зачарования</td>
        <td>I</td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Bow.webp" alt="Bow"></td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Crossbow.webp" alt="Crossbow"></td>
      </tr>
      <tr>
        <td><strong>Парящие стрелы</strong> (Hover)</td>
        <td>Накладывает эффект <strong>Левитации</strong> при попадании</td>
        <td>Нестрельные зачарования</td>
        <td>III</td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Bow.webp" alt="Bow"></td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Crossbow.webp" alt="Crossbow"></td>
      </tr>
      <tr>
        <td><strong>Затяжные стрелы</strong> (Lingering)</td>
        <td>Создает <strong>долговременное облако</strong> эффекта при попадании</td>
        <td>Нестрельные зачарования</td>
        <td>III</td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Bow.webp" alt="Bow"></td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Crossbow.webp" alt="Crossbow"></td>
      </tr>
      <tr>
        <td><strong>Ядовитые стрелы</strong> (Poisoned Arrows)</td>
        <td>Накладывает эффект <strong>Отравления</strong> при попадании</td>
        <td>Нестрельные зачарования</td>
        <td>III</td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Bow.webp" alt="Bow"></td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Crossbow.webp" alt="Crossbow"></td>
      </tr>
      <tr>
        <td><strong>Снайпер</strong> (Sniper)</td>
        <td><strong>Увеличивает скорость снаряда</strong></td>
        <td></td>
        <td>II</td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Bow.webp" alt="Bow"></td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Crossbow.webp" alt="Crossbow"></td>
      </tr>
      <tr>
        <td><strong>Вампирские стрелы</strong> (Vampiric Arrows)</td>
        <td><strong>Восстанавливает здоровье</strong> при попадании</td>
        <td>Нестрельные зачарования</td>
        <td>III</td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Bow.webp" alt="Bow"></td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Crossbow.webp" alt="Crossbow"></td>
      </tr>
      <tr>
        <td><strong>Увядающие стрелы</strong> (Withered Arrows)</td>
        <td>Накладывает эффект <strong>Увядания</strong> при попадании</td>
        <td>Нестрельные зачарования</td>
        <td>III</td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Bow.webp" alt="Bow"></td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Crossbow.webp" alt="Crossbow"></td>
      </tr>
    </tbody>
  </table>

  <div class="notes">
    <div class="notes-title"><strong>Примечания</strong></div>
    <ul>
      <li><strong>Зачарования, изменяющие снаряд</strong> (Bomber, Ender Bow, Ghost) несовместимы друг с другом</li>
      <li><strong>Нестрельные зачарования</strong> - зачарования, не предназначенные для лука/стрел</li>
    </ul>
  </div>

  <div class="warning">
    <div class="warning-title"><strong>Важно</strong></div>
    <ul>
      <li>Зачарования из группы "изменяющие снаряд" можно наносить только по одному на лук</li>
      <li>"Снайпер" совместим со всеми типами зачарований</li>
      <li>Максимальный уровень влияет на силу/длительность эффекта</li>
    </ul>
  </div>
</div>

  <!-- Tool Enchantments -->
<div class="category">
  <div class="category-header">⛏️ Зачарования для инструментов</div>
  <table>
    <thead>
      <tr>
        <th>Название (Оригинал)</th>
        <th>Эффект</th>
        <th>Несовместимо с</th>
        <th>Макс. уровень</th>
        <th style="text-align: center;">Основной предмет</th>
        <th style="text-align: center;">Дополнительный предмет</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><strong>Взрывная добыча</strong> (Blast Mining)</td>
        <td>Добывает блоки <strong>взрывами</strong></td>
        <td>Туннель (Tunnel), Добыча жилы (Veinminer)</td>
        <td>V</td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Pickaxe.webp" alt="Pickaxe"></td>
        <td style="text-align: center; vertical-align: middle;"></td>
      </tr>
      <tr>
        <td><strong>Стеклолом</strong> (Glass Breaker)</td>
        <td>Мгновенно разбивает <strong>стекло</strong></td>
        <td></td>
        <td>I</td>
        <td style="text-align: center; vertical-align: middle;">
          <img class="item-icon" src="../static/excellentenchants/Pickaxe.webp" alt="Pickaxe">
          <img class="item-icon" src="../static/excellentenchants/Axe.webp" alt="Axe">
          <img class="item-icon" src="../static/excellentenchants/Shovel.webp" alt="Shovel">
        </td>
        <td style="text-align: center; vertical-align: middle;">
          <img class="item-icon" src="../static/excellentenchants/Hoe.webp" alt="Hoe">
          <img class="item-icon" src="../static/excellentenchants/Shears.webp" alt="Shears">
        </td>
      </tr>
      <tr>
        <td><strong>Ускорение</strong> (Haste)</td>
        <td>Даёт эффект <strong>Ускорения</strong> при добыче</td>
        <td></td>
        <td>III</td>
        <td style="text-align: center; vertical-align: middle;">
          <img class="item-icon" src="../static/excellentenchants/Pickaxe.webp" alt="Pickaxe">
          <img class="item-icon" src="../static/excellentenchants/Axe.webp" alt="Axe">
          <img class="item-icon" src="../static/excellentenchants/Shovel.webp" alt="Shovel">
        </td>
        <td style="text-align: center; vertical-align: middle;">
          <img class="item-icon" src="../static/excellentenchants/Hoe.webp" alt="Hoe">
          <img class="item-icon" src="../static/excellentenchants/Shears.webp" alt="Shears">
        </td>
      </tr>
      <tr>
        <td><strong>Удачливый шахтёр</strong> (Lucky Miner)</td>
        <td>Увеличивает <strong>опыт</strong> с добытых блоков</td>
        <td></td>
        <td>III</td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Pickaxe.webp" alt="Pickaxe"></td>
        <td style="text-align: center; vertical-align: middle;"></td>
      </tr>
      <tr>
        <td><strong>Пересадчик</strong> (Replanter)</td>
        <td>Автоматически <strong>пересаживает</strong> урожай</td>
        <td></td>
        <td>I</td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Hoe.webp" alt="Hoe"></td>
        <td style="text-align: center; vertical-align: middle;"></td>
      </tr>
      <tr>
        <td><strong>Шёлковый сундук</strong> (Silk Chest)</td>
        <td><strong>Сундуки</strong> выпадают с содержимым</td>
        <td></td>
        <td>I</td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Axe.webp" alt="Axe"></td>
        <td style="text-align: center; vertical-align: middle;">
          <img class="item-icon" src="../static/excellentenchants/Pickaxe.webp" alt="Pickaxe">
          <img class="item-icon" src="../static/excellentenchants/Shovel.webp" alt="Shovel">
          <img class="item-icon" src="../static/excellentenchants/Hoe.webp" alt="Hoe">
        </td>
      </tr>
      <tr>
        <td><strong>Шёлковый спаунер</strong> (Silk Spawner)</td>
        <td>Шанс получить <strong>спаунер мобов</strong></td>
        <td>Плавильщик (Smelter)</td>
        <td>I</td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Pickaxe.webp" alt="Pickaxe"></td>
        <td style="text-align: center; vertical-align: middle;"></td>
      </tr>
      <tr>
        <td><strong>Плавильщик</strong> (Smelter)</td>
        <td><strong>Переплавляет</strong> добытые ресурсы</td>
        <td>Шёлковое касание (Silk Touch), Шёлковый спаунер (Silk Spawner)</td>
        <td>V</td>
        <td style="text-align: center; vertical-align: middle;">
          <img class="item-icon" src="../static/excellentenchants/Pickaxe.webp" alt="Pickaxe">
          <img class="item-icon" src="../static/excellentenchants/Axe.webp" alt="Axe">
          <img class="item-icon" src="../static/excellentenchants/Shovel.webp" alt="Shovel">
        </td>
        <td style="text-align: center; vertical-align: middle;">
          <img class="item-icon" src="../static/excellentenchants/Hoe.webp" alt="Hoe">
          <img class="item-icon" src="../static/excellentenchants/Shears.webp" alt="Shears">
        </td>
      </tr>
      <tr>
        <td><strong>Телекинез</strong> (Telekinesis)</td>
        <td><strong>Лут</strong> попадает прямо в инвентарь</td>
        <td></td>
        <td>I</td>
        <td style="text-align: center; vertical-align: middle;">
          <img class="item-icon" src="../static/excellentenchants/Pickaxe.webp" alt="Pickaxe">
          <img class="item-icon" src="../static/excellentenchants/Axe.webp" alt="Axe">
          <img class="item-icon" src="../static/excellentenchants/Shovel.webp" alt="Shovel">
          <img class="item-icon" src="../static/excellentenchants/Hoe.webp" alt="Hoe">
        </td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Shears.webp" alt="Shears"></td>
      </tr>
      <tr>
        <td><strong>Лесоруб</strong> (Treefeller)</td>
        <td>Вырубает <strong>целое дерево</strong></td>
        <td></td>
        <td>I</td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Axe.webp" alt="Axe"></td>
        <td style="text-align: center; vertical-align: middle;"></td>
      </tr>
      <tr>
        <td><strong>Туннель</strong> (Tunnel)</td>
        <td>Добывает блоки в области <strong>1×2/2×2/3×3</strong></td>
        <td>Добыча жилы (Veinminer), Взрывная добыча (Blast Mining)</td>
        <td>III</td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Pickaxe.webp" alt="Pickaxe"></td>
        <td style="text-align: center; vertical-align: middle;">
          <img class="item-icon" src="../static/excellentenchants/Axe.webp" alt="Axe">
          <img class="item-icon" src="../static/excellentenchants/Shovel.webp" alt="Shovel">
          <img class="item-icon" src="../static/excellentenchants/Hoe.webp" alt="Hoe">
        </td>
      </tr>
      <tr>
        <td><strong>Добыча жилы</strong> (Veinminer)</td>
        <td>Добывает <strong>всю рудную жилу</strong> сразу</td>
        <td>Туннель (Tunnel), Взрывная добыча (Blast Mining)</td>
        <td>III</td>
        <td style="text-align: center; vertical-align: middle;"><img class="item-icon" src="../static/excellentenchants/Pickaxe.webp" alt="Pickaxe"></td>
        <td style="text-align: center; vertical-align: middle;"></td>
      </tr>
    </tbody>
  </table>

  <div class="tip">
    <div class="tip-title">Стратегии использования</div>
    <div class="notes-title"><strong>Комбинируйте зачарования</strong>:</div>
    <ul>
      <li>Пересадчик + Телекинез = Автоферма</li>
      <li>Ускорение + Удачливый шахтёр = Быстрая прокачка</li>
      <li>Шёлковый сундук + Телекинез = Безопасный перенос лут-сундуков</li>
    </ul>
    

<div class="warning-title"><strong>Осторожно с несовместимостью</strong>:</div>
    <ul>
      <li>Взрывная добыча уничтожает лут (не сочетать с Телекинезом)</li>
      <li>Плавильщик несовместим с Шёлковым касанием</li>
      <li>Туннель и Добыча жилы - взаимоисключающие</li>
    </ul>
    
<div class="notes-title"><strong>Специализация инструментов</strong>:</div>
    <ul>
      <li>Кирка: Добыча жилы + Удачливый шахтёр</li>
      <li>Топор: Лесоруб + Телекинез</li>
      <li>Мотыга: Пересадчик + Ускорение</li>
      <li>Ножницы: Шёлковый спаунер + Стеклолом</li>
    </ul>
  </div>

  <div class="warning">
    <div class="warning-title">Совет</div>
    <p>Создайте отдельные инструменты для разных задач - это повысит эффективность добычи в 3 раза!</p>
  </div>
</div>
</div>