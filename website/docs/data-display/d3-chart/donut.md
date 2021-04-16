---
title: Donut chart
---

@## Donut

- Круговой график отображается с помощью компонента `Donut`.
- `Pie` — отдельный сектор.
- `Label` — подпись внутри графика.

@example donut

@## Semi-Donut

Для построения половинчатого графика нужно указать значение `halfsize` и уменьшить высоту в два раза.

@example semi-donut

@## Edge cases

- Если какие-либо данные отсутствуют, то они не отображаются на графике
- Если известно только одно значение, то для отображения его маленьким сектором необходимо указать также процент/значение неизвестных данных

@example semi-donut-with-one-data

- Если данных нет, то отображается пустой график серого цвета

@example donut-without-data