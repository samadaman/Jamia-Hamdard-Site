# Jamia Hamdard Homepage (Practice Session)

### 🌐 Project Overview
<i> This project is a practice session focused on creating a homepage for Jamia Hamdard University. The main objective is to utilize CSS 'Float' for layout design and include a marquee paragraph to enhance the visual appeal. </i>

### ✨ Features
###### <i> • CSS Float: Efficiently used for layout and positioning. </i>
###### <i> • Marquee Paragraph: Adds dynamic scrolling text to the page. </i>
###### <i> • Responsive Design: Optimized for various screen sizes. </i>
###### <i> • Clean and Structured Code: Ensures easy readability and maintenance. </i>
### 🔧 Technologies Used
###### <i> • HTML: Provides the structure for the web pages. </i>
###### <i> • CSS: Styles the HTML elements, with a focus on using 'Float' for layout. </i>

### 💡 Usage
<i> Explore the homepage layout created using CSS 'Float'. Notice the marquee paragraph for an engaging scrolling text effect. </i>

### ✍️ Sample Code
html
Copy code
<div class="marquee">
  <p>Welcome to Jamia Hamdard University - Excellence in Education and Research!</p>
</div>

<div class="container">
  <div class="left-column">
    <!-- Content for the left column -->
  </div>
  <div class="right-column">
    <!-- Content for the right column -->
  </div>
</div>
css
Copy code
.marquee p {
  width: 100%;
  overflow: hidden;
  white-space: nowrap;
  box-sizing: border-box;
  animation: marquee 15s linear infinite;
}

@keyframes marquee {
  0% { transform: translate(100%, 0); }
  100% { transform: translate(-100%, 0); }
}

.container {
  overflow: hidden;
}

.left-column {
  float: left;
  width: 50%;
  /* Additional styling */
}

.right-column {
  float: right;
  width: 50%;
  /* Additional styling */
}

### 🤝 Contributing
<i> Contributions are welcome! Here's how: </i>

### Fork the repository.
Create a new branch `git checkout -b feature-improvement.`
Make your changes.
Commit your changes `git commit -am 'Add new feature'`.
Push to the branch `git push origin feature-improvement`.
Create a new Pull Request.
