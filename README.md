# Styled_Profile_Card
## Date: 08.08.2025

## Objective:
To practice HTML and CSS fundamentals by designing a visually appealing profile card that demonstrates the use of background color, typography, spacing, and layout alignment techniques.

## Tasks:
#### 1. Create the HTML Structure:
Use ```<!DOCTYPE html>, <html>, <head>, and <body>``` to define the structure.
Add a ```<title>``` like "My Profile Card".

#### 2. Add Content:
Include name, title (e.g., Developer, Student), and a short bio using semantic tags such as ```<h1>```, ```<h2>```, and ```<p>```.

#### 3. Add a Profile Image:
Use the ```<img>``` tag to include a profile picture with appropriate alt, width, and height attributes.

#### 4. Apply Background Color:
Use a CSS class to style the card with a background color.

#### 5. Style Typography:
Use CSS to apply different font families, sizes, and text colors for the name and bio.

#### 6. Add Spacing:
Apply margin and padding to improve spacing between elements using CSS.

#### 7. Center the Card:
Use flexbox or margin: auto to center the card vertically and horizontally on the page.

#### 8. Add Hover Effects:
Enhance interactivity with simple hover effects like border changes or background transition using CSS.

## HTML Code:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Profile</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <div class="profile-card">

    <header class="profile-header">
      <h1>Roshan R</h1>
      <h2>Student</h2>
      <h3>FullStack Developer</h3>
    </header>

    <hr>

    <section class="profile-section">
      <img src="Ghibli edit.jpg" alt="Profile picture of Roshan R" width="200" height="200" class="profile-image">
      <p class="bio">
        Hello! I'm a passionate learner exploring the world of web development. I enjoy solving algorithmic problems. My current focus is on building strong foundations in HTML, CSS, and JavaScript.
      </p>
    </section>

    <hr>

    <section class="profile-section">
      <h2>Interests</h2>
      <ul>
        <li>Full-Stack Web Development (HTML, CSS, JavaScript)</li>
        <li>Java Programming</li>
        <li>Data Analysis & Visualization</li>
      </ul>
    </section>

  </div>

</body>
</html>
```

## CSS Code:
```
body {
  background-color: rgb(239, 235, 235);
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  margin: 0;
  padding: 20px;
}

.profile-card {
  max-width: 800px;
  margin: auto;
  background-color: white;
  padding: 30px;
  border-radius: 12px;
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
}

.profile-header {
  text-align: center;
  margin-bottom: 20px;
}

.profile-header h1 {
  font-size: 48px;
  color: #333;
}

.profile-header h2 {
  font-size: 28px;
  color: #666;
  margin: 5px 0;
}

.profile-header h3 {
  font-size: 20px;
  color: #888;
  margin-top: 5px;
}

.profile-image {
  border-radius: 50%;
  display: block;
  margin: 0 auto 20px;
}

.bio {
  padding: 20px;
  line-height: 1.6;
  background-color: #d3e0b3;
  border-radius: 10px;
  font-size: 16px;
}

.profile-section {
  margin-top: 30px;
}

.profile-section h2 {
  color: #2c3e50;
  font-size: 24px;
  margin-bottom: 10px;
}

.profile-section ul {
  padding-left: 20px;
  line-height: 1.6;
}

hr {
  border: none;
  height: 1px;
  background-color: #ccc;
  margin: 30px 0;
}
```

## Output:
![Uploading Screenshot 2025-07-08 115256.png…]()

## Live WebPage:

## Result:
A visually appealing profile card that demonstrates the use of background color, typography, spacing, and layout alignment techniques is designed.
