---
navigation:
  title: Ячейки хранения нагрузки
  icon: appliedcreate:stress_storage_cell_1k
  parent: appliedcreate:index.md
  position: 60
item_ids:
  - appliedcreate:stress_storage_cell_1k
  - appliedcreate:stress_storage_cell_4k
  - appliedcreate:stress_storage_cell_16k
  - appliedcreate:stress_storage_cell_64k
  - appliedcreate:stress_storage_cell_256k
  - appliedcreate:stress_storage_cell_1m
  - appliedcreate:stress_storage_cell_4m
  - appliedcreate:stress_storage_cell_16m
  - appliedcreate:stress_storage_cell_64m
  - appliedcreate:stress_storage_cell_256m
  - appliedcreate:creative_stress_cell
---

# Ячейки хранения нагрузки

<Row gap="20">
<Column>

<ItemImage id="appliedcreate:stress_storage_cell_1k" scale="4" />

Ячейки хранения нагрузки позволяют хранить значения вращательной нагрузки Create в вашей ME-сети, так же как ячейки хранения предметов или жидкости хранят предметы и жидкости. Поместите их в ME-драйвы, чтобы накапливать нагрузку для последующего использования с помощью <ItemLink id="appliedcreate:me_gearbox" />.

</Column>
</Row>

## Уровни ячеек

### Уровень андезита (1k – 256k)

Создаются с использованием <ItemLink id="appliedcreate:andesite_stress_cell_housing" /> и сборок хранения уровня андезита.

| Ячейка | Ёмкость | Потребление в простое |
|--------|---------|------------------------|
| <ItemLink id="appliedcreate:stress_storage_cell_1k" /> | 1 КБ | 0.5 AE/t |
| <ItemLink id="appliedcreate:stress_storage_cell_4k" /> | 4 КБ | 1.0 AE/t |
| <ItemLink id="appliedcreate:stress_storage_cell_16k" /> | 16 КБ | 1.5 AE/t |
| <ItemLink id="appliedcreate:stress_storage_cell_64k" /> | 64 КБ | 2.0 AE/t |
| <ItemLink id="appliedcreate:stress_storage_cell_256k" /> | 256 КБ | 2.5 AE/t |

### Уровень латуни (1M – 256M)

Создаются с использованием <ItemLink id="appliedcreate:brass_stress_cell_housing" /> и сборок хранения уровня латуни.

| Ячейка | Ёмкость | Потребление в простое |
|--------|---------|------------------------|
| <ItemLink id="appliedcreate:stress_storage_cell_1m" /> | 1 МБ | 3.0 AE/t |
| <ItemLink id="appliedcreate:stress_storage_cell_4m" /> | 4 МБ | 3.5 AE/t |
| <ItemLink id="appliedcreate:stress_storage_cell_16m" /> | 16 МБ | 4.0 AE/t |
| <ItemLink id="appliedcreate:stress_storage_cell_64m" /> | 64 МБ | 4.5 AE/t |
| <ItemLink id="appliedcreate:stress_storage_cell_256m" /> | 256 МБ | 5.0 AE/t |

### Креативная ячейка нагрузки

<ItemImage id="appliedcreate:creative_stress_cell" scale="2" />

<IncidentLink id="appliedcreate:creative_stress_cell" /> обеспечивает бесконечное хранение нагрузки в творческом режиме для тестирования.

## Крафт

Ячейки хранения нагрузки создаются путём объединения сборки хранения с соответствующим корпусом ячейки:

<RecipeFor id="appliedcreate:stress_storage_cell_1k" />

<RecipeFor id="appliedcreate:stress_storage_cell_1m" />

## Использование

1. Создайте ячейку хранения нагрузки нужного уровня
2. Поместите её в ME-драйв AE2
3. Используйте <ItemLink id="appliedcreate:me_gearbox" /> в режиме импорта для хранения нагрузки
4. Используйте <ItemLink id="appliedcreate:me_gearbox" /> в режиме экспорта для извлечения нагрузки и генерации вращения

## Советы

- Ячейки хранят только один тип данных: вращательную нагрузку (SU). В ME-терминале отображается количество хранимой нагрузки
- Более высокие уровни вмещают больше нагрузки, но потребляют больше энергии в простое
- Индикатор на ячейке показывает уровень заполнения (пусто, частично заполнено, заполнено)
- Ячейки нагрузки отображаются в ME-терминале вместе с предметами и жидкостями