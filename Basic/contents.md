# Web Desigining using react JS

- HTML
  - Version - Doctype
  - Head
    - title
    - link(favicon,css(tomorrow))
    - meta
    - script
  - Body
    - Block-level elements
      - Headings(h1-h6)
      - paragraph
      - Ordered list and list items(ul,ol,dl)
      - Division
      - Table,tr,caption
      - Options is block level
      - form
      - semantic elements(Having specific meaning for the element = Division(div)+special meaning)
        - Header
        - Footer
        - Nav
        - Main
        - Section
        - Article
        - Aside
    - Inline elements
      - All form controls
        - Input types
        - Select is Inline
        - styling elements
        - span
        - images
        - Navigation
          - In- bound(Navigating within documents)
          - Out - bound(navigating between the documents)
          - mailto(specifying emails)
          - tel(specifying mobile numbers)
- CSS
  - systax
  - Kinds
    - Inline
    - Internal
    - External
  - selectors
    - element selector
      - defined with the tagname  
        `body{ background: red; }`
    - Id selector
      - `#idname{ background: red;}`
    - class selector
      - `.classname{ background: red;}`
    - Universal selector
      - `*{ background: red;}`
- Bootstrap
- Java Script
- React JS
- Redux

# Day 3(05th March 2021)

- Media Queries and Flex box(responsove designing)

## Flexbox

- padding property
  - padding(top,right,bottom,left) --> Order
- Flex Properties
  - display
    - flex should be given if we use flex properties
  - Flex direction
    - row
    - row reverse
    - column
    - column reverse
  - Justify Content
    - flex-start
    - flex-end
    - center
    - space-between
    - space-around
  - flex-wrap
    - wrap (applys only when the viewport is there)
    - nowrap
    - wrap-reverse

## Day 4(08th Mar 2021)

- Java Script
  - Brendon Eich (livescript) -- 1994
  - LiveScript converted to JavaScript in 1995
  - ECMA(European Computer Manufactures Association) -- Tied up with this and started releasing updates
    - ES-6 (Basics) working with any kind of library and advanced frameworks
    - ES11 - In 2020
- Data Types
  - var(declaring a variable)
    - var a = 10
  - number
  - boolean
  - string
  - undefined
  - not defined
  - object
  - null
  - function
    ```javascript
    function name() {
      return;
    }
    ```
- Output Statements
  - Console
    - Console doesn't have any return statements or return types. So that undefined
    - console.log('msg')
    - console.warn()
    - console.error()
    - console.assert(condition,data)
      - returns a value based on condition
    - console.info('msg')
    - console.count()
    - console.clear()
  - Pop-ups
    - Alert
      ```javascript
      alert("alert msg");
      ```
    - Prompt(string type data)
      ```javascript
      prompt("prompting for a value");
      ```
    - Confirm
  - Conversion statements
    - number
      - parseInt
      - parseFloat
    - toString
      - string
    - boolean(true or false result will be number)
      - true(1)
      - false(0)
    - null -- zero(0)
    - empty string -- zero(0)
    - undefined -- NaN(Not a Number) for all formats except string
