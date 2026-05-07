---
navigation:
  title: Материалы для крафта нагрузки
  icon: appliedcreate:stress_processor
  parent: appliedcreate:index.md
  position: 70
item_ids:
  - appliedcreate:stress_circuit_board
  - appliedcreate:advanced_stress_circuit_board
  - appliedcreate:stress_processor
  - appliedcreate:advanced_stress_processor
  - appliedcreate:stress_storage_component_1k
  - appliedcreate:stress_storage_component_4k
  - appliedcreate:stress_storage_component_16k
  - appliedcreate:stress_storage_component_64k
  - appliedcreate:stress_storage_component_256k
  - appliedcreate:stress_storage_component_1m
  - appliedcreate:stress_storage_component_4m
  - appliedcreate:stress_storage_component_16m
  - appliedcreate:stress_storage_component_64m
  - appliedcreate:stress_storage_component_256m
  - appliedcreate:andesite_stress_cell_housing
  - appliedcreate:brass_stress_cell_housing
---

# Материалы для крафта нагрузки

Эти предметы используются для создания ячеек хранения нагрузки. Система повторяет стандартную цепочку крафта AE2, но использует материалы в стиле Create.

## Платы

Платы — основа для создания процессоров нагрузки. Их можно создать в прессовщике AE2 или с помощью резака плат.

<Row gap="20">
<Column>

<ItemImage id="appliedcreate:stress_circuit_board" scale="4" />

### <ItemLink id="appliedcreate:stress_circuit_board" />

Базовая плата для обработки нагрузки уровня андезита.

<RecipeFor id="appliedcreate:stress_circuit_board" />

</Column>
<Column>

<ItemImage id="appliedcreate:advanced_stress_circuit_board" scale="4" />

### <ItemLink id="appliedcreate:advanced_stress_circuit_board" />

Продвинутая плата для обработки нагрузки уровня латуни.

<RecipeFor id="appliedcreate:advanced_stress_circuit_board" />

</Column>
</Row>

## Процессоры

Процессоры собираются из плат в прессовщике AE2.

<Row gap="20">
<Column>

<ItemImage id="appliedcreate:stress_processor" scale="4" />

### <ItemLink id="appliedcreate:stress_processor" />

Используется в рецептах сборки хранения уровня андезита (1К–256К).

<RecipeFor id="appliedcreate:stress_processor" />

</Column>
<Column>

<ItemImage id="appliedcreate:advanced_stress_processor" scale="4" />

### <ItemLink id="appliedcreate:advanced_stress_processor" />

Используется в рецептах сборки хранения уровня латуни (1М–256М).

<RecipeFor id="appliedcreate:advanced_stress_processor" />

</Column>
</Row>

## Компоненты хранения

Компоненты хранения — основной элемент, определяющий ёмкость ячейки. Создаются по цепочке: каждый следующий уровень требует предыдущий.

### Уровень андезита (1К – 256К)

<RecipeFor id="appliedcreate:stress_storage_component_1k" />

### Уровень латуни (1М – 256М)

<RecipeFor id="appliedcreate:stress_storage_component_1m" />

## Корпуса ячеек

Корпуса используются вместе с компонентами хранения для создания готовых ячеек.

<Row gap="20">
<Column>

<ItemImage id="appliedcreate:andesite_stress_cell_housing" scale="4" />

### <ItemLink id="appliedcreate:andesite_stress_cell_housing" />

Используется с компонентами уровня андезита (1К–256К).

<RecipeFor id="appliedcreate:andesite_stress_cell_housing" />

</Column>
<Column>

<ItemImage id="appliedcreate:brass_stress_cell_housing" scale="4" />

### <ItemLink id="appliedcreate:brass_stress_cell_housing" />

Используется с компонентами уровня латуни (1М–256М).

<RecipeFor id="appliedcreate:brass_stress_cell_housing" />

</Column>
</Row>

## Цепочка крафта

Полный процесс создания ячеек хранения нагрузки:

1. **Платы** — создаются в прессовщике или резаке
2. **Процессоры** — плата + кремний + редстоун в прессовщике
3. **Компоненты хранения** — создаются из процессоров (каждый уровень требует предыдущий)
4. **Корпуса ячеек** — создайте нужный корпус
5. **Ячейки хранения** — объедините корпус и компонент = готовая ячейка  