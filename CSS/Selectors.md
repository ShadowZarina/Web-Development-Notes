# CSS SELECTORS

### 1. **Type Selector**

- `A`
- Selects all elements of type A
    
    Example: `plate`
    

---

### 2. **Type Selector (Specific Element)**

- `A`
- Same as above, often repeated for different elements
    
    Example: `bento`
    

---

### 3. **Class Selector**

- `.classname`
- Selects elements with a class
    
    Example: `.small`
    

---

### 4. **ID Selector**

- `#id`
- Selects element with a specific ID
    
    Example: `#fancy`
    

---

### 5. **Descendant Combinator**

- `A B`
- Selects B inside A (at any depth)
    
    Example: `plate apple`
    

---

### 6. **Child Combinator**

- `A > B`
- Selects B that is a direct child of A
    
    Example: `bento > apple`
    

---

### 7. **Adjacent Sibling Combinator**

- `A + B`
- Selects B immediately after A
    
    Example: `plate + apple`
    

---

### 8. **General Sibling Combinator**

- `A ~ B`
- Selects all B siblings after A
    
    Example: `plate ~ apple`
    

---

### 9. **Universal Selector**

- 
- Selects all elements

---

### 10. **Combined Type + Class**

- `A.classname`
- Example: `apple.small`

---

### 11. **Multiple Class Selector**

- `.class1.class2`
- Elements with both classes

---

### 12. **Attribute Presence Selector**

- `[attribute]`
- Example: `[for]`

---

### 13. **Attribute Equals Selector**

- `[attribute="value"]`
- Example: `[for="Ethan"]`

---

### 14. **Attribute Starts With**

- `[attribute^="value"]`

---

### 15. **Attribute Ends With**

- `[attribute$="value"]`

---

### 16. **Attribute Contains**

- `[attribute*="value"]`

---

### 17. **First Child Pseudo-class**

- `:first-child`

---

### 18. **Last Child Pseudo-class**

- `:last-child`

---

### 19. **Nth Child**

- `:nth-child(n)`
- Examples:
    - `:nth-child(2)`
    - `:nth-child(odd)`
    - `:nth-child(even)`
    - `:nth-child(3n)`

---

### 20. **Nth Last Child**

- `:nth-last-child(n)`

---

### 21. **Only Child**

- `:only-child`

---

### 22. **First of Type**

- `:first-of-type`

---

### 23. **Last of Type**

- `:last-of-type`

---

### 24. **Nth of Type**

- `:nth-of-type(n)`

---

### 25. **Nth Last of Type**

- `:nth-last-of-type(n)`

---

### 26. **Only of Type**

- `:only-of-type`

---

### 27. **Empty**

- `:empty`

---

### 28. **Negation Pseudo-class**

- `:not(selector)`
- Example: `:not(.small)`
