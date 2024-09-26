# EX01 Developing a Simple Webserver
## Date:26.09.2024.

## AIM:
To develop a simple webserver to display the configuration details of my laptop.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Serving the HTML pages.

### Step 5:
Testing the webserver.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Laptop Configuration</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 50px;
            background-color: #f4f4f4;
        }

        h2,h3 {
            text-align: center;
            color: #333;
        }

        table {
            width: 60%;
            margin: 0 auto;
            border-collapse: collapse;
            background-color: white;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }

        th, td {
            padding: 12px 15px;
            text-align: left;
            border: 1px solid #ccc;
        }

        th {
            background-color: #fcffff;
            color: rgb(95, 21, 21);
        }

        tr:nth-child(even) {
            background-color: #f2f2f2;
        }

        tr:hover {
            background-color: #ddd;
        }

        td {
            color: #555;
        }
    </style>
</head>
<body>

    <h2>Laptop Configuration</h2>
    <h3>RUDESH KANNA R (24900303)</h3>


    <table>
        <tr>
            <th>Component</th>
            <th>Specification</th>
        </tr>
        <tr>
            <td>Processor</td>
            <td>12th Gen Intel Core i5-1235U processor</td>
        </tr>
        <tr>
            <td>RAM</td>
            <td>8 GB DDR4</td>
        </tr>
        <tr>
            <td>Storage</td>
            <td>512 GB SSD</td>
        </tr>
        <tr>
            <td>Graphics</td>
            <td>NVIDIA GeForce GTX 1650</td>
        </tr>
        <tr>
            <td>Display</td>
            <td>15.6" FHD (1920x1080) IPS</td>
        </tr>
        <tr>
            <td>Battery</td>
            <td> 65Wh</td>
        </tr>
        <tr>
            <td>Operating System</td>
            <td>Windows 11</td>
        </tr>
    </table>

</body>
</html>


```
## OUTPUT:
![image](https://github.com/user-attachments/assets/d7bb8077-2892-4dfe-8f13-81d21173cc97)


## RESULT:
The program for implementing simple webserver is executed successfully.
