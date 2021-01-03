---
marp: true
theme: uncover
# size: 4:3  <!-- Uncomment and remove this comment to get traditional slides size -->
---

<!-- Customize Global theme -->
<style>
    h1 
    {
        color: darkOrange;
    }
    h2 
    {
        color: orange;
    }
    h3 
    {
        font-size: 40px;
    }
    p 
    {
        font-size: 30px;
    }
    li
    {
        font-size: 30px;
    }
    code
    {
        font-size: 20px;
    }
    table
    {
        font-size: 30px;
    }
    section
    {
        background: rgb(100,100,100);
        color: white;
    }
</style>

<!-- Scoped style for the First page-->
<style scoped>
    section 
    {
        background: rgb(20,20,20);
        color: orange;
    }
</style>

# Marp Slides Example

### An example of writing slides on Visual Studio Code using Marp

---

<!-- paginate: true -->

## How to

### Create some slides is really simple:

1. Install *Visual Studio Code* and the **Marp** extension using the *VS Marketplace* (Ctrl+Shift+X).
2. Create a *.md* file and add the following lines in the beginning:
    ```yaml
    ---
    marp: true
    theme: uncover
    ---
    ```
3. Write your presentation using **Markdown** syntax. 
---
4. Previsualize pressing *Ctrl+Shit+V*
5. Modify theme style using *HTML* and *CSS*:
    ```html
    <style>
        h1 
        {
            color: darkOrange;
        }
        h2 
        {
            color: orange;
            font-size: 30px;
        }
    </style>
    ```
6. Export to **PDF** pressing *F1* and selecting *Export slide deck*

---

## Full Mardown  compatible

Write tables and whatever using markdown syntax 

<!-- 
_header: This is a text in the local (_) header
-->

Name  | ID | Frame | Checked
------|----|:-----:|:--------:
Head  | 0 | Base   | True
Neck  | 1 | Base   | False
Spine | 5 | Base   | False
Base  | 8 | World  | True

<!-- 
_footer: This is a text in the local (_) footer 
-->

---

Images using also markdown syntax:
\
\
![logo](resources/marpit.png)
<style>
    img[alt=logo] { width: 650px; }
</style>  
\
\
Check its [website](https://marpit.marp.app/)

---

Maths Style Support:
\
\
$N_{avg}=\sum_n f(x,y)\cdot{\alpha}$