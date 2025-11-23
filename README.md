# New York Times Home Page Clone

A simple clone of the New York Times home page layout, created as a Lab Task/Assignment. This project focuses on learning the basics of HTML structure and CSS Flexbox layouts.

## 🛠️ Technologies Used

* **HTML5:** For the structural content.
* **CSS3:** For styling, colors, and layout (Flexbox).
* **No external frameworks** (Pure HTML/CSS).

## 💻 How to Run

1.  Clone or download this repository to your computer.
2.  Make sure the image file (`31uk-riot-wfqm-videoSixteenByNineJumbo1600-v3.jpg`) is in the same folder as `index.html`.
3.  Double-click `index.html` to open it in your web browser.

## 📸 Screenshots

![Project Screenshot](homepage_screenshot.jpg)

## 💻 Source Code

### 1. HTML Code (`index.html`)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The New York Times</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1>The New York Times</h1>
    <ul>
        <li>U.S.</li>
        <li>World</li>
        <li>Business</li>
        <li>Arts</li>
        <li>LifeStyle</li>
        <li>Opinion</li>
        <li>Audio</li>
        <li>Games</li>
        <li>Cooking</li>
        <li>Wirecutter</li>
        <li>The Athletic</li>
    </ul>
    <div class="parent">
        <div class="left">
            <div class="a">
                <p style="color: red; font-family: sans-serif; font-size: 12px;"><b>Live</b> 2m ago</p>
                <h2><a href="[https://www.nytimes.com/live/2025/10/12/world/israel-gaza-hostages-trump](https://www.nytimes.com/live/2025/10/12/world/israel-gaza-hostages-trump)">Trump flies to Israel As Region Awaits Hostage-Prisoner Swap</a></h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Saepe dolor nam ipsum itaque in voluptatem reiciendis modi molestias ipsam nulla beatae maiores.</p>
            </div>
            <hr style="margin: 30px 0; opacity: 0.3;"> 
            <div class="b">
                <p style="font-size: 12px; font-weight: bold;">Analysis</p>
                <h2><a href="#">Wealthy Americans Are Spending. People With Less Are Struggling.</a></h2>
                <p>Data show a resilient economy. But that largely reflects spending by the rich, while others pull back.</p>
            </div>
        </div>
        <div class="right">
            <img src="31uk-riot-wfqm-videoSixteenByNineJumbo1600-v3.jpg" alt="image">
            <p style="font-size: 12px; color: gray; text-align: right;">Police officers at the scene.</p>
        </div>
        <div class="sidebar">
            <div class="box large-box">
                WIDGET PLACEHOLDER
            </div>
            <div class="ad-row">
                <div class="box small-box">AD SLOT 1</div>
                <div class="box small-box">AD SLOT 2</div>
            </div>
        </div>
    </div>
</body>
</html>
```

### 2. CSS Code (`styles.css`)

```css
body {
    font-family: Georgia, serif;
    margin: 20px;
    box-sizing: border-box;
}

a {
    color: black;  
    text-decoration: none;
}

h1 {
    text-align: center;
    font-size: 50px;
    margin-bottom: 10px;
}

ul {
    text-align: center;
    list-style: none;
    padding: 10px;
    border-top: 1px solid black;
    border-bottom: 1px double black; 
    font-family: Arial, sans-serif;
    font-size: 12px;
}

li {
    padding: 10px;
    display: inline-block;
}

.parent {
    margin-top: 30px;
    display: flex;
    justify-content: space-between; 
    gap: 20px; 
}

.left {
    width: 30%; 
    border-right: 1px solid #ddd; 
    padding-right: 20px; 
}

.right {
    width: 40%; 
}

img {
    width: 100%;  
    height: auto; 
}

.sidebar {
    width: 25%;
    border-left: 1px solid #ddd;
    padding-left: 20px;
    display: flex;
    flex-direction: column; 
    gap: 20px; 
}

.box {
    border: 1px solid #999;
    background-color: #f9f9f9;
    border-radius: 8px;
    color: #555;
    font-family: Arial, sans-serif;
    font-size: 11px;
    display: flex;           
    align-items: center;     
    justify-content: center; 
}

.large-box {
    width: 100%;
    height: 150px; 
}

.ad-row {
    display: flex;
    justify-content: space-between;
    width: 100%;
}

.small-box {
    width: 48%;
    height: 150px;
}
```

## 👤 Author

* **[Md Sabbir Hossain]** - *Initial work for Lab Task*
