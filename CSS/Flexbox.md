# FLEXBOX FLOGGY (FLEXBOX)

# 1. `display`

**Description:** Defines the layout model. Setting it to flex enables Flexbox for the container.

**Values used in Flexbox Froggy**

- `flex` — activates flex layout for the container.

**Example**

```
display:flex;
```

---

# 2. `justify-content`

**Description:** Aligns items **horizontally along the main axis** (left ↔ right in most cases).

**Values**

- `flex-start` — items align to the start (left).
- `flex-end` — items align to the end (right).
- `center` — items align in the center.
- `space-between` — items spread out with space between them.
- `space-around` — items have equal space around each item.

**Example**

```
justify-content:center;
```

---

# 3. `align-items`

**Description:** Aligns items **vertically along the cross axis** inside the container.

**Values**

- `flex-start` — items align to the top.
- `flex-end` — items align to the bottom.
- `center` — items align vertically in the middle.
- `baseline` — items align by their text baseline.
- `stretch` — items stretch to fill the container height.

**Example**

```
align-items:flex-end;
```

---

# 4. `flex-direction`

**Description:** Defines the **direction of the main axis**.

**Values**

- `row` — items arranged left → right.
- `row-reverse` — items arranged right → left.
- `column` — items arranged top → bottom.
- `column-reverse` — items arranged bottom → top.

**Example**

```
flex-direction:column;
```

---

# 5. `order`

**Description:** Changes the **display order of flex items** without changing HTML.

**Values**

- Any integer (`0`, `1`, `2`, etc.)
- Lower numbers appear first.

**Example**

```
order: 2;
```

---

# 6. `align-self`

**Description:** Overrides `align-items` **for a single flex item**.

**Values**

- `flex-start`
- `flex-end`
- `center`
- `baseline`
- `stretch`

**Example**

```
align-self:center;
```

---

# 7. `flex-wrap`

**Description:** Controls whether flex items **stay on one line or wrap to multiple lines**.

**Values**

- `nowrap` — all items stay on one line.
- `wrap` — items wrap to the next line.
- `wrap-reverse` — items wrap but in reverse direction.

**Example**

```
flex-wrap:wrap;
```

---

# 8. `flex-flow`

**Description:** **Shorthand** for `flex-direction` and `flex-wrap`.

**Values**

Combination of:

- direction (`row`, `column`, etc.)
- wrapping (`wrap`, `nowrap`, etc.)

**Example**

```
flex-flow:rowwrap;
```

---

# 9. `align-content`

**Description:** Aligns **multiple rows of flex items** when there is extra vertical space.

**Values**

- `flex-start`
- `flex-end`
- `center`
- `space-between`
- `space-around`
- `stretch`

**Example**

```
align-content:space-between;
```

---

✅ **Summary (All properties used in Flexbox Froggy):**

| Property | Purpose |
| --- | --- |
| `display` | Activates flex layout |
| `justify-content` | Horizontal alignment |
| `align-items` | Vertical alignment |
| `flex-direction` | Direction of items |
| `order` | Changes item order |
| `align-self` | Individual item alignment |
| `flex-wrap` | Controls wrapping |
| `flex-flow` | Shorthand for direction + wrap |
| `align-content` | Aligns multiple rows |


-------------------------------------------------------

# FLEXBOX ZOMBIES (FLEXBOX 2)

# Container (Parent) Properties

## 1. `display`

Defines a flex container.

- `flex`
- `inline-flex`

---

## 2. `flex-direction`

Controls the main axis direction.

- `row` (default)
- `row-reverse`
- `column`
- `column-reverse`

---

## 3. `justify-content`

Aligns items along the **main axis**.

- `flex-start`
- `flex-end`
- `center`
- `space-between`
- `space-around`
- `space-evenly`

---

## 4. `align-items`

Aligns items along the **cross axis**.

- `stretch` (default)
- `flex-start`
- `flex-end`
- `center`
- `baseline`

---

## 5. `align-content`

Aligns multiple rows (when wrapping).

- `stretch`
- `flex-start`
- `flex-end`
- `center`
- `space-between`
- `space-around`
- `space-evenly`

---

## 6. `flex-wrap`

Controls wrapping behavior.

- `nowrap` (default)
- `wrap`
- `wrap-reverse`

---

## 7. `flex-flow`

Shorthand for `flex-direction` + `flex-wrap`.

- Example values:
    - `row wrap`
    - `column nowrap`
    - `row-reverse wrap`

---

# Individual Item (Child) Properties

## 8. `order`

Controls item order.

- Any integer:
    - `0` (default)
    - `1`, `2`, `1`, etc.

---

## 9. `flex-grow`

Defines how much an item grows.

- Any number:
    - `0` (default)
    - `1`, `2`, etc.

---

## 10. `flex-shrink`

Defines how much an item shrinks.

- Any number:
    - `1` (default)
    - `0`, `2`, etc.

---

## 11. `flex-basis`

Initial size before space distribution.

- `auto`
- Length values:
    - `px`, `%`, `em`, etc.

---

## 12. `flex`

Shorthand for grow, shrink, basis.

- Common patterns:
    - `flex: 1`
    - `flex: 1 1 auto`
    - `flex: 0 1 auto`
    - `flex: none`

---

## 13. `align-self`

Overrides `align-items` for a single item.

- `auto`
- `flex-start`
- `flex-end`
- `center`
- `baseline`
- `stretch`

---

# Additional Concepts Used in the Game

## Axes

- **Main axis** → controlled by `flex-direction`
- **Cross axis** → perpendicular to main axis

---

## Spacing Tricks (commonly used in levels)

- `margin: auto`
- `margin-left: auto`
- `margin-right: auto`

---

## Common Defaults Highlighted

- `flex-direction: row`
- `flex-wrap: nowrap`
- `align-items: stretch`
- `flex-grow: 0`
- `flex-shrink: 1`

---

# Summary Cheat Sheet

| Property | Purpose |
| --- | --- |
| display | Enables flexbox |
| flex-direction | Main axis direction |
| justify-content | Main axis alignment |
| align-items | Cross axis alignment |
| flex-wrap | Wrapping behavior |
| order | Item order |
| flex | Size/grow/shrink shorthand |
| align-self | Per-item alignment override |
