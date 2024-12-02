| **Selector**              | **Syntax**              | **Description**                                                             |
| ------------------------- | ----------------------- | --------------------------------------------------------------------------- |
| **Universal Selector**    | `*`                     | Selects all elements.                                                       |
| **Type Selector**         | `element`               | Selects all elements of a specific type (e.g., `h1`, `p`, `div`).           |
| **Class Selector**        | `.classname`            | Selects all elements with a specific class.                                 |
| **ID Selector**           | `#id`                   | Selects a specific element by its unique ID.                                |
| **Attribute Selector**    | `[attribute="value"]`   | Selects elements with specific attributes.                                  |
| **Descendant Selector**   | `ancestor descendant`   | Selects elements inside another element (any level).                        |
| **Child Selector**        | `parent > child`        | Selects direct child elements.                                              |
| **Adjacent Sibling**      | `element + sibling`     | Selects an element that directly follows another element.                   |
| **General Sibling**       | `element ~ siblings`    | Selects all siblings of an element that follow it.                          |
| **Grouping Selectors**    | `selector1, selector2`  | Applies the same styles to multiple selectors.                              |
| **Chaining Selectors**    | `selector1.selector2`   | Combines selectors for more precise targeting.                              |
| **Pseudo-class**          | `selector:pseudo-class` | Selects elements in a specific state (e.g., `:hover`, `:focus`).            |
| **Pseudo-element**        | `selector::pseudo`      | Selects specific parts of an element (e.g., `::before`, `::first-line`).    |
| **Attribute Starts With** | `[attribute^="value"]`  | Selects elements where the attribute value starts with the specified value. |
| **Attribute Ends With**   | `[attribute$="value"]`  | Selects elements where the attribute value ends with the specified value.   |
| **Attribute Contains**    | `[attribute*="value"]`  | Selects elements where the attribute value contains the specified value.    |
