# FDA 21 CFR 101.9 Nutrition Facts Deterministic Rounding Reference

Concise engineering reference for deterministic Nutrition Facts rounding per 21 CFR 101.9 and 2020 Reference Daily Values (adults and children >= 4 years).

## 1. Calories (`21 CFR 101.9(c)(1)`)

| Raw Calories per Serving | Displayed Value |
| :--- | :--- |
| `<= 5` | `0` |
| `> 5` and `<= 50` | Nearest `5` kcal |
| `> 50` | Nearest `10` kcal |

## 2. Total Fat, Saturated Fat, Trans Fat (`21 CFR 101.9(c)(2)`)

| Raw Grams per Serving | Displayed Value |
| :--- | :--- |
| `< 0.5 g` | `0g` |
| `0.5 g` to `< 5 g` | Nearest `0.5g` |
| `>= 5 g` | Nearest `1g` |

## 3. Cholesterol (`21 CFR 101.9(c)(3)`)

| Raw mg per Serving | Displayed Value |
| :--- | :--- |
| `< 2 mg` | `0mg` |
| `2 mg` to `5 mg` | `Less than 5mg` |
| `> 5 mg` | Nearest `5mg` |

## 4. Sodium, Potassium & Calcium (`21 CFR 101.9(c)(4)/(8)`)

| Raw mg per Serving | Displayed Value |
| :--- | :--- |
| `< 5 mg` | `0mg` |
| `5 mg` to `140 mg` | Nearest `5mg` |
| `> 140 mg` | Nearest `10mg` |

## 5. Total Carbohydrate, Dietary Fiber, Total/Added Sugars, Protein

| Raw Grams per Serving | Displayed Value |
| :--- | :--- |
| `< 0.5 g` | `0g` |
| `0.5 g` to `< 1 g` | `<1g` |
| `>= 1 g` | Nearest `1g` |

## 6. Micronutrients & Daily Values (FDA 2020)

- **Daily Values**: Total Fat `78g`, Sat Fat `20g`, Cholesterol `300mg`, Sodium `2300mg`, Total Carb `275g`, Dietary Fiber `28g`, Added Sugars `50g`, Protein `50g`, Vitamin D `20mcg`, Calcium `1300mg`, Iron `18mg`, Potassium `4700mg`.
- **Micronutrient %DV Steps (`21 CFR 101.9(c)(8)(iii)`)**: `< 1% -> 0%`, `<= 10% -> nearest 2%`, `<= 50% -> nearest 5%`, `> 50% -> nearest 10%`.

Interactive no-signup calculator & vector SVG/PDF generator: [CottageFoodTools FDA Nutrition Generator](https://cottagefoodtools.com/nutrition-label-generator)
