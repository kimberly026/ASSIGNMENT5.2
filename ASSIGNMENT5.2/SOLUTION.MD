# Assignment 5.2 — CSS Selectors Practice

Aim: To understand and apply different CSS selectors, including element, class, ID, universal, grouping selectors, and the CSS cascade and specificity.


## 2. HTML file 

This webpage contains headings, paragraphs, cards, a special section, and examples for testing CSS selectors.


## 2. CSS file  CONFLICT IN style.css

The paragraph in the HTML has `class="conflict"`, so it appears red, even though the green `p` rule appears later in the stylesheet.

Why? The class selector `.conflict` has higher specificity than the element selector `p`.

Specificity, from higher to lower in this example:

1. ID selector — `#special-section`
2. Class selector — `.conflict`
3. Element selector — `p`
4. Universal selector — `*`

When selectors have equal specificity, the later applicable declaration generally wins, assuming the same origin, importance, and cascade layer.


## 7. WEBPAGE SCREEN SHOT
![alt text](<5.2 css selector-1.png>)


