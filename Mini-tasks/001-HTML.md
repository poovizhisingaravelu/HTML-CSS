# [Guvi Zen](https://www.guvi.io/zen/)

## HTML Task to know usage of basic tags.

1. Fix the bugs in below snippet

```HTML
    <html lang="en">
    <head>
        <title>Document guvi
        </title>
    </head>
        <body>
    <div>
        Lorem ipsum dolor sit amet consectetur adipisicing elit.
        </div>
            <div>
                Guvi Geek Network
            </div>
        </body>
    </html>
```
2. Try the below one

```HTML
<html lang="en">
    <head>
        <title>Document  guvi
            </title>
    </head>
        <body>
    <div>
        Lorem ipsum dolor sit amet consectetur adipisicing elit.
        </div>
            <div>
                Guvi Geek Network
            </div>
        </body>
    </html>
```

---

3. Design a contact us form with all fields as required.
<html>
    <head>
    
    </head>
    <body>
        <h1>contact form</h1>
        <label>enter your email</label>
        <input type="text">
        <br>
        <label>enter your phonenumber</label>
        <input type="text">
        <br>
        <label>enter your address</label>
        <input type="text">
        <br>
        <button>submit</button>
    </body>
</html>

---

4. Use certain HTML elements to display the following in a HTML page.

- Programming Language
  - JavaScript
    1. Angular
    2. React
    3. Vue.js
  - Python
    1. Django Framework
    2. Flask Framework
  - Java
    1. Spring
    2. Maven
    3. Hibernate
- Database
  - MySQL
  - MongoDB
  - Cansandra
  <html>
    <head>
        
    </head>
    <body>
        <ul >
            <li>Programming Language</li></ul>
                <ul style="list-style:circle;">
                   <li>JavaScript</li></ul>
                <ol type="a">
                    <li>Angular</li>
                        <li>React</li>
                        <li>Vue.js</li></ol>
                        <ul style="list-style:circle;">
                   <li>Python</li></ul>
                   <ol type="a">
                    <li>Django Framework</li>
                        <li>Flask Framework</li></ol>
                        <ul style="list-style:circle;">
                            <li>Java</li></ul>
                            <ol type="a">
                                <li>Spring</li>
                                    <li>Maven</li>
                                    <li>Hibernate</li></ol>
                                    <ul >
     <li>

     </li>Database</li></ul>
            <ul style="list-style:circle;">
               <li>MySQL</li>
               <li>MongoDB</li>
               <li>Cansandra</li>
    </ul>             
    </body>
</html>

---

5. Create an element that helps you to open the https://google.com in separate new tab.
<html>
    <head>
    
    </head>
    <body>
        <a href=" https://google.com">you want go to browser</a>
        </body>
</html>

---

6. In the form, add two radio buttons with grouping them for employee type(Salaried and own business)
<html>
    <head>EMPLOYESS DETAILS
    </head>
    <body>
        <p>employee type<mark>(Salaried and own business)</mark></p>
        <br>
        <input type="radio" />
        <label>Salaried</label>
        <br>
        <input type="radio" />
        <label>own business</label>
        <br>
        <button>submit</button>
    </body>
</html>

---

7. Design form shown in the link (http://evc-cit.info/cit040/formguide/card_0.png) 
<html>
    <head>
    
    </head>
    <body>
        <img src="https://www.allaboutgardening.com/wp-content/uploads/2022/01/Types-of-Flowers-in-Garden.jpg"/>
        </body>
</html>


---

8. Use the table tag to design given image [Click here](https://www.bapugraphics.com/assets/img/port_upload_dir/table-4.jpg).
<html>
    <head>
        <link rel="stylesheet"  href="list.css" />
    </head>
    <body>
        <p><b>Health Chart</b></p>
        <table width="80%">
            <tr>
              <th rowspan="2">State of health</th>
              
              <th  colspan="2">Fasting value</th>
              <th>After Eating</th>
            </tr>
                <th>minumum</th>
                <th>Maximum</th>
                <th>2 hours after eating</th>

            </tr>
            <tr>
              <td>Heathy</td>
              <td>70</td>
              <td>100</td>
              <td>less than 140</td>
            </tr>
              <tr>
              <td>pre-Diabetes</td>
              <td>101</td>
              <td>126</td>
              <td>140to200</td>
           
            </tr>
            <tr>
                <td>Diabetes</td>
                <td>more than 126</td>
                <td>N/A</td>
                <td>More than 200</td>
            </tr>
            
        </table>
    </body>
</html>
css---
p{
    text-align: center;
    
}
table,th,td{
    border: 1px solid black;
    border-collapse: collapse;
    padding: 10px;
   
}
table{
    margin-left: 70px;
    border-color: black;
}


---

9. Write HTML input tags snippet to show default values for all Form elements.
<html>
    <head>STUDENT DETAILS
    </head>
    <body>
        <p>WELCOME TO GUVI</p>
        <br>
        <label>NAME</label>
        <input type="text" />
        <br>
        <label>QUALIFIC</label>
        <input type="text" />
        <br>
        <label>phonenumber</label>
        <input type="text" />
        <br>
        <label>country</label>
        <input type="text" />
        <br>
        <label>SEX</label>
        <br>
        <input type="radio"/>
        <label>FEMALE</label>
        <br>
        <input type="radio"/>
        <label>MALE</label>
        <br>
        <label>DOB</label>
        <input type="datetime-local"/>
        <br>
        <button>submit</button>
    </body>
</html>

---

10. In your, HTML page add the below line and Highlight it without using any CSS.

- "HTML & CSS is awesome"
<head>STUDENT DETAILS
    </head>
    <body>
        <p>welcome to all<mark>HTML & CSS is awesome</mark></p>
        <p>WELCOME TO GUVI</p>
    </body>
</html>
---

11. Create an HTML page, which should contain all types of input elements.
<html>
    <head>STUDENT DETAILS
    </head>
    <body>
        <p>WELCOME TO GUVI</p>
        <br>
        <label>NAME</label>
        <input type="text" />
        <br>
        <label>QUALIFIC</label>
        <input type="text" />
        <br>
        <label>phonenumber</label>
        <input type="text" />
        <br>
        <label>country</label>
        <input type="text" />
        <br>
        <label>SEX</label>
        <br>
        <input type="radio"/>
        <label>FEMALE</label>
        <br>
        <input type="radio"/>
        <label>MALE</label>
        <br>
        <label>DOB</label>
        <input type="datetime-local"/>
        <br>
        <button>submit</button>
    </body>
</html>
