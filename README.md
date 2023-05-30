# Ex.08 Customer Registration Form
## AIM
  To write a program in JavaScript for creating a customer registration form for an agro-based company.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define different functions to register the customers based on their qualifications.

### STEP-3
  Using form elements to create the registration details of a customer.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
```
<!DOCTYPE html>
<head>
    <title>SAMPLE WEB PAGE</title>
</head>
<style>
    body
 {
        background-color: pink;
    }
</style>
<body>
    <h1>
        <caption>AGROTECH CUSTOMER REGISTRATION FORM</caption>
    </h1>
<hr color="blue">
   
    <h3>
        <form onsubmit="thank()">
            <br>
            NAME:
            <input type="text">
            <br>
            <br>
            E-MAIL:
            <input type="email">
            <br>
            <br>
            USERNAME:
            <input type="text">
            <br>
            <br>
            PASSWORD:
            <input type="password">
            <br>
            <br>   
            RE-TYPE PASSWORD:
            <input type="password">
            <br>
            <br>
            MOBILE NUMBER:
            <input type="tel">
            <br>
            <br>
            CROP:
            <select>
                <option>Maize</option>
                <option>Rice</option>
                <option>Wheat</option>
                <option>Corn</option>
            </select>
            <br>
            <br>
            FERTILIZER NEEDED:
            <input type="radio">Yes
            <input type="radio">No
            <br>
            <br>
            ADDRESS:
            <textarea rows="10" cols="30"></textarea>
            <br>
            <input type="submit" name="submit"><input type="button" value="Clear All" onclick="clearForm()">
        </form>
    </h3>
    <script type="text/javascript">
        function thank() {
            alert("THANKYOU FOR REGISTERING WITH US");
        }
    </script>
</body>
</html>



## OUTPUT
![WEB PG 01](https://github.com/JeevithaParthiban/EX08_Web-Design/assets/127817091/96a670c0-7436-4eca-8a2b-2dfa0aaabacd)
![WEB PG 02](https://github.com/JeevithaParthiban/EX08_Web-Design/assets/127817091/8a9dc665-4981-48ce-9baf-02c593ea65e0)


## RESULT
  Customer registration form using JavaScript is created successfully.
