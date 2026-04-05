# CSS GRIDS (from GRID GARDEN)

# CSS Grid Properties Used in CSS Grid Garden

## 🌱 `display`

```
display:grid;
```

Enables grid layout.

---

## 🌱 `grid-template-columns`

Defines column sizes.

### Possible values used:

```
grid-template-columns: 50%;
grid-template-columns: 100px 100px;
grid-template-columns: 1fr 1fr;
grid-template-columns:repeat(3, 1fr);
grid-template-columns: 20% 80%;
grid-template-columns: 100px 3em40%;
```

### Units used in the game:

- `px`
- `%`
- `em`
- `fr`
- `auto`

---

## 🌱 `grid-template-rows`

Same concept as columns.

```
grid-template-rows: 50px 50px;
grid-template-rows:repeat(4, 1fr);
grid-template-rows: 100pxauto;
```

---

## 🌱 `grid-column-start`

```
grid-column-start: 1;
grid-column-start: 3;
```

Accepts:

- Positive integers
- `span` keyword (later levels)

---

## 🌱 `grid-column-end`

```
grid-column-end: 3;
grid-column-end:span 2;
```

Accepts:

- Line number
- `span n`

---

## 🌱 `grid-row-start`

```
grid-row-start: 2;
```

---

## 🌱 `grid-row-end`

```
grid-row-end: 4;
grid-row-end:span 2;
```

---

## 🌱 Shorthand: `grid-column`

```
grid-column: 1 / 3;
grid-column: 2 /span 2;
```

Format:

```
grid-column:start /end;
```

---

## 🌱 Shorthand: `grid-row`

```
grid-row: 1 / 4;
grid-row: 3 /span 2;
```

---

## 🌱 Shorthand: `grid-area`

```
grid-area: 1 / 1 / 3 / 3;
```

Format:

```
grid-area:row-start /column-start /row-end /column-end;
```

---

## 🌱 `justify-items`

Controls horizontal alignment inside cells.

```
justify-items:start;
justify-items:end;
justify-items:center;
justify-items:stretch;
```

Possible values:

- `start`
- `end`
- `center`
- `stretch`

---

## 🌱 `align-items`

Controls vertical alignment inside cells.

```
align-items:start;
align-items:end;
align-items:center;
align-items:stretch;
```

---

## 🌱 `justify-content`

Aligns entire grid horizontally.

```
justify-content:start;
justify-content:end;
justify-content:center;
justify-content:stretch;
justify-content:space-between;
justify-content:space-around;
space-evenly;
```

---

## 🌱 `align-content`

Aligns entire grid vertically.

```
align-content:start;
align-content:end;
align-content:center;
align-content:stretch;
align-content:space-between;
align-content:space-around;
align-content:space-evenly;
```

---

## 🌱 `grid-template`

Shorthand used in later levels:

```
grid-template: 50px 50px / 1fr 1fr;
```

Format:

```
grid-template:rows /columns;
```

---

## 🌱 `repeat()`

Used inside template properties:

```
repeat(3,1fr)
repeat(2,50px100px)
```

---

# 3️⃣ Special Keywords Used

| Keyword | Meaning |
| --- | --- |
| `span` | Spans multiple tracks |
| `auto` | Automatic sizing |
| `fr` | Fraction of available space |
| `repeat()` | Repeats track patterns |
| `/` | Separates start & end lines |

---

# 4️⃣ Complete Property List in CSS Grid Garden

Here’s the full set of grid-related properties taught:

- `display`
- `grid-template-columns`
- `grid-template-rows`
- `grid-template`
- `grid-column-start`
- `grid-column-end`
- `grid-row-start`
- `grid-row-end`
- `grid-column`
- `grid-row`
- `grid-area`
- `justify-items`
- `align-items`
- `justify-content`
- `align-content`
