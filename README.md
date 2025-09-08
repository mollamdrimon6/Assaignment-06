# ASSIGNMENT-006
# Green Earth


#

---
🌴 API Endpoints
---
1. Get 🌴All Plants
```bash
https://openapi.programming-hero.com/api/plants
```

2. Get 🌴All categories <br/>
```bash
https://openapi.programming-hero.com/api/categories
```


3. Get 🌴plants by categories <br/>
```bash
https://openapi.programming-hero.com/api/category/${id}
```

```bash
https://openapi.programming-hero.com/api/category/1
```

4. Get 🌴Plants Detail <br/>

```bash
https://openapi.programming-hero.com/api/plant/${id}
```

```bash
https://openapi.programming-hero.com/api/plant/1
```
---




## ✅ Main Requirements 

#### 1) Navbar

- Website **logo/name** on the **left**  
- **Menu items** in the **center** 
- **Plant a Tree button** on the **right** 

#### 2) Banner 
- A **background image**  
- A **title** and **subtitle**  
- A **centered button**  

#### 3) About Campaign
- **Section heading**  
- **Image on the left**, **text on the right**  

#### 4) Our Impact Section 
- Show **3 cards** with campaign **statistics**  

#### 5) Plant a Tree Today Section & Footer
- **Form**: Name, Email, Number of Trees  
- **Footer** with copyright info 

#### 6) Responsiveness 
- Website must be **mobile responsive**  

---
#### 7) Create a README file to answer the following question-


1) Difference between var, let, and const

var

Function-scoped (accessible throughout the function where declared).

Can be redeclared and updated.

Hoisted (moved to the top) but initialized as undefined.

let

Block-scoped (only accessible inside {}).

Can be updated but not redeclared within the same scope.

Hoisted but not initialized, so accessing before declaration causes ReferenceError.

const

Block-scoped like let.

Must be initialized at the time of declaration.

Cannot be reassigned, but if it’s an object/array, the contents can still be modified.

 In short: Use let for values that change, const for values that don’t, and avoid var in modern JS.

2) Difference between map(), forEach(), and filter()

map()

Returns a new array with transformed values.

Doesn’t change the original array.

Example: nums.map(x => x * 2) → returns doubled array.

forEach()

Loops through elements but does not return anything (always undefined).

Used mainly for side effects (logging, updating external variables).

filter()

Returns a new array with elements that match a condition.

Example: nums.filter(x => x > 5) → returns only values greater than 5.

 In short:

map() → transform items

forEach() → just loop

filter() → select items

3) Arrow Functions in ES6

A shorter way to write functions:

const add = (a, b) => a + b;


Key differences from regular functions:

No own this → They inherit this from surrounding scope (lexical this).

Cannot be used as constructors (new won’t work).

Cleaner and more concise syntax.

 Use arrow functions for callbacks, array methods, and when you need lexical this.

4) Destructuring Assignment in ES6

Allows extracting values from arrays or objects into variables easily.

Array destructuring:

const [a, b] = [10, 20];  
console.log(a); // 10


Object destructuring:

const {name, age} = {name: "Rimon", age: 22};  
console.log(name); // "Rimon"


 Makes code cleaner, avoids repetitive property access, and supports default values.

5) Template Literals in ES6

Introduced backticks ` for strings.

Support string interpolation with ${}.

Support multi-line strings without \n.

Example:

const name = "Rimon";
console.log(`Hello, ${name}! Welcome to ES6.`);


 Difference from string concatenation:

Old way: "Hello, " + name + "!" → messy.

New way: `Hello, ${name}!` → cleaner, readable, and allows multi-line formatting.
## ⚙️ Functionalities 

1) Category Loading 
Load Tree Categories dynamically on the left side.

2) Category Click → Tree Data 
On clicking a category: load trees of that category.

Display in a 3-column card layout.

3) Card Contents 
 Each card includes:

        - Image

        -  Name

        - Short description

        - Category

        - Price

        - Add to Cart button

4) Modal on Card Click 
Clicking a tree name on a card opens a modal with full tree details.


##  🧪 Challenges 


    1) Add to Cart 
    Clicking Add to Cart: - Adds the tree to Cart List
                          - Shows tree name 

    2) Total Calculation 
    Calculate total price of trees in cart.

    3) Remove from Cart 
    Clicking ❌ removes tree and deducts price from total.

    4) Loading Spinner
    Show spinner while data is loading.

    5) Active Button State 
    Highlight active category button when selected.



🧰 Technology Stack:
        
        HTML

        CSS ( Tailwind )

        JavaScript (Vanilla only, no frameworks)

📌 Rules
✅ At least 5 meaningful commits

❌ No dummy text or Lorem Ipsum — must use relevant content





## 🔗 Submission
- **Live Link :**
- **GitHub Private Repository:** 

