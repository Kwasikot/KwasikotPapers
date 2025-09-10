🏛️ Пример Technetic Graph (уровень Римской империи)
Узлы (Nodes)

R1: Mining & Quarrying (добыча руды, камня, мрамора)

R2: Smelting & Forging (железо, бронза, сталь низкого качества)

R3: Pottery & Glassmaking

R4: Concrete & Hydraulic Cement

R5: Aqueducts & Water Management

R6: Roads & Bridges (Stone, Concrete)

R7: Architecture & Engineering (форумы, амфитеатры, купола)

R8: Sailing Ships & Navigation

R9: Agriculture (Irrigation, Crop Rotation, Olive & Vine Cultivation)

R10: Literacy & Record-Keeping (Scrolls, Codices)

R11: Administration & Law (юридический кодекс, налоги)

R12: Military Logistics (легионы, форты, оружие)

Рёбра (Dependencies)

R1 → R2 (без добычи нет металлов)

R2 + R3 → R7 (металлы + стекло/керамика → здания, техника)

R2 + R4 → R6 (металл + бетон → дороги и мосты)

R4 → R5 → R9 (бетон → акведуки → сельское хозяйство)

R6 + R7 → R11 (дороги + архитектура = расширение управления и права)

R10 → R11 (письменность = законы и бюрократия)

R6 + R8 → Trade Expansion (дороги + корабли = экономика)

R11 + R12 → Empire Stability (администрирование + армия = контроль территории)

Визуально (ASCII):
[R1: Mining] → [R2: Smelting] → [R12: Military]
        ↓             ↓
   [R3: Pottery]   [R4: Concrete] → [R5: Aqueducts] → [R9: Agriculture]
        ↓                ↓                ↓
      [R7: Engineering]   → [R6: Roads] → [Trade Expansion]
                ↓                  ↓
            [R10: Literacy] → [R11: Law/Admin] 
                       ↓
                 [Empire Stability]

Особенности:

Базовые материалы (R1–R3) обеспечивают инфраструктуру.

Строительство (R4–R7) создаёт города и дороги.

Сельское хозяйство + торговля (R5, R9, R8) дают устойчивое снабжение.

Социальные технологии (R10, R11) позволяют координировать миллионы людей.

Армия (R12) замыкает цикл, поддерживая экспансию и стабильность.

💡 Такой Technetic Graph показывает, что Римская империя = синергия материальных технологий (бетон, дороги, металл) и социальных технологий (закон, администрация).