### **Lesson 11: Table Structure**

#### **Objective:**

Students will create a new project that displays user information in a structured table format. They will use the table-related HTML tags and concepts learned to display data collected from the registration form in Lesson 9, such as the user's name, gender, and country.

---

### **Step-by-Step Instructions**

1. **Set Up Your New Project:**

   - Create a new folder called `user-table-project` inside of your `unit02 - cw` folder.
   - Inside this folder, create a new HTML file named `index.html`.
   - Use the following starter HTML structure:

     ```html
     <!DOCTYPE html>
     <html lang="en">
       <head>
         <meta charset="UTF-8" />
         <meta
           name="viewport"
           content="width=device-width, initial-scale=1.0"
         />
         <title>User Information Table</title>
       </head>
       <body>
         <h2>User Information Table</h2>
       </body>
     </html>
     ```

2. **Create a Basic Table Structure:**

   - Below the `<h2>`inside the `<body>`, add the table structure with the `<table>` tag, including a `<thead>` for the table header and a `<tbody>` for the user data:
     ```html
     <table>
       <thead>
         <tr>
           <th>First Name</th>
           <th>Last Name</th>
           <th>Gender</th>
           <th>Country</th>
         </tr>
       </thead>
       <tbody></tbody>
     </table>
     ```

3. **Add Sample User Data to the Table:**

   - Populate the `<tbody>` with sample user data that includes the first name, last name, gender, and country:
     ```html
     <tbody>
       <tr>
         <td>John</td>
         <td>Doe</td>
         <td>Male</td>
         <td>United States</td>
       </tr>
     </tbody>
     ```
   - Come up with 2 more `<tr>` of sample user data that includes the first name, last name, gender, and country. At the end, you should that 3 sets of `<tr>`.

4. **Save and Preview Your Work:**
   - Save the `index.html` file.
   - Open the file in a browser and verify that the table displays correctly, with data properly formatted in rows and columns.

---

### **Assessment Criteria:**

1. **Correct Use of Table Tags:**

   - The table uses `<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, and `<td>` tags appropriately.

2. **Proper Data Display:**
   - The user information is displayed correctly in the table, with headers and corresponding data rows.
