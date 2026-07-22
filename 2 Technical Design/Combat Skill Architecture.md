Характеристики навыков: 
- Количество ударов (в зависимости от анимации навыка). Не вструктуру а в аним нотиафаях монтажа
- Процент урона
- Накладывает/не накладывает статус
- Шанс статуса при наличии
- Контроль навыка (стан, опрокидывание и т.д.)
- Суперармор
- Блокирование
- Неуязвимость к урону
- Расход магической энергии
- Расход выносливости
- Эффект навыка (бафф/дебафф)
- Длительность навыка (баффов/дебаффов)
- Время перезарядки
- Количество целей (от 1 до 5) (или если цель это сам игрок)
- Радиус действия
- Комбинация

BPC_Skills
BPC_SkillsSword > Array (Skills) & S_WeaponMaster
Array (Skills) > Sruct
Struct > S_SkillInfo

S_WeaponMastery (Level / Current Exp / Damage Multiply)

1. Index
2. Name
3. Description
4. Icon
5. Montage
6. Damage
7. Cooldown
8. Radius 
9. Mana Cost
10. Stamina Consume
11. Max Targets
12. Superarmor
13. Block
14. Invincible
15. Level
16. Points to Lvl Up
17. Type (Attack / Heal / Buff / Other)
18. Status Type
19. Status Chance
20. Duration Effect 
21. Positive Effects
22. Negative Effects
23. WeaponType
24. Key Combination Default
25. Ban

Struct: "S_Skill" (Index, Level;  Key Combination; Data Asset > Data Table; Ban;)
Data Asset: (IDSkillAsset, Name; Icon; Montage; Weapon Type; Status Type; Invincible; Superarmor; Block; AoE; Sequence; Description)
Data Table (Damage; Cooldawn;  Points to Lvl Up; PositiveEffects; NegativeEffects; Status Chance, Radius, Targets, Mana Cost, Stamina Consume, Duration)

