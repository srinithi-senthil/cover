# Ex.06 Book Front Cover Page Design
## Date:12-12-2025

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
<style>
.book-cover {
  width: 600px;
  height: 900px;
  border: 4px solid PINK;
  display: flex;
  flex-direction: column;
  background: linear-gradient(180deg, orange, gold);
}

.top {
  flex: 2;
  padding: 30px;
  background: linear-gradient(180deg, #ff6600, #ffcc00);
  color: white;
}

.top h4 {
  margin: 0;
  font-size: 18px;
}

.title {
  margin-top: 40px;
  font-size: 42px;
  font-weight: bold;
  text-transform: uppercase;
}

.subtitle {
  margin-top: 20px;
  font-size: 22px;
}

.bottom {
  flex: 1;
  background: linear-gradient(180deg, gold, orange);
  padding: 20px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  color: white;
}

.bottom-left {
  max-width: 70%;
}

.special {
  font-weight: bold;
  font-size: 20px;
}

.author {
  margin-top: 15px;
  font-size: 18px;
}

.bottom-right img {
  width: 100px;
  height: 120px;
  object-fit: cover;
  border: 2px solid white;
}
</style>

<div class="book-cover">
  <div class="top">
    <h4>DEPARTMENT OF CSE</h4>
    <div class="title">PROJECT BOOK</div>
    <div class="subtitle">Web Development</div>
  </div>

  <div class="bottom">
    <div class="bottom-left">
      <div class="special">SPECIAL EDITION</div>
      <div class="author">Ms. Srinithi.S</div>
    </div>

    <div class="bottom-right">
      <img src="srinithi profil photo.jpg" alt="Author photo">
    </div>
  </div>
</div>
```

## OUTPUT:
![alt text](<Screenshot 2025-12-12 185012.png>)
## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
