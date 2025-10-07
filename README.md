# Ex09 Event Registration Web Application
## Date:07/10/25

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>DRESTIN'25</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <div class="container">

    <!-- Screen 1: Branding -->
    <section class="screen branding">
      <h1>Saveetha Engineering College</h1>
      <h2>DRESTIN'25</h2>
      <a href="#register" class="btn">REGISTER</a>
    </section>

    <!-- Screen 2: Registration Form -->
    <section class="screen registration" id="register">
      <h2>REGISTER</h2>
      <form>
        <label>Name:</label>
        <input type="text" name="name" required />
        <label>Dept:</label>
        <input type="text" name="dept" required />
        <label>Contact No:</label>
        <input type="tel" name="contact" required />
        <label>Event:</label>
        <input type="text" name="event" required />
        <button type="submit" class="btn">Submit</button>
      </form>
    </section>

    <!-- Screen 3: Events List -->
    <section class="screen events">
      <h2>EVENTS</h2>
      <ul>
        <li>POOKOLAM</li>
        <li>VADAM VALI</li>
        <li>CHENDA MELAM</li>
        <li>CULTURAL EVENTS</li>
        <li>DJ</li>
      </ul>
    </section>

    <!-- Screen 4: Contact Info -->
    <section class="screen contact">
      <h2>CONTACT US</h2>
      <p>📞 Ph: 8797657878</p>
      <p>📍 Venue: SEC Campus</p>
      <p>📅 Date: 22/10/25</p>
      <p>⏰ Time: 1–3 P.M.</p>
    </section>

  </div>
</body>
</html>
```
```
/* styles.css */
body {
  font-family: 'Segoe UI', sans-serif;
  background-color: #f4f4f4;
  margin: 0;
  padding: 0;
}

.container {
  max-width: 400px;
  margin: 20px auto;
  padding: 10px;
}

.screen {
  background-color: #fff;
  border-radius: 12px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  padding: 20px;
  margin-bottom: 20px;
}

.branding h1 {
  font-size: 1.2rem;
  color: #555;
}

.branding h2 {
  font-size: 2rem;
  color: #0077cc;
  margin: 10px 0;
}

.btn {
  display: inline-block;
  padding: 10px 20px;
  background-color: #0077cc;
  color: white;
  text-decoration: none;
  border-radius: 8px;
  margin-top: 10px;
}

.registration form {
  display: flex;
  flex-direction: column;
}

.registration label {
  margin-top: 10px;
  font-weight: bold;
}

.registration input {
  padding: 8px;
  margin-top: 5px;
  border: 1px solid #ccc;
  border-radius: 6px;
}

.events ul {
  list-style: none;
  padding: 0;
}

.events li {
  background-color: #e0f7fa;
  margin: 8px 0;
  padding: 10px;
  border-radius: 6px;
}

.contact p {
  margin: 10px 0;
  font-size: 1rem;
}

```

## OUTPUT:
![alt text](<Screenshot (36).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
