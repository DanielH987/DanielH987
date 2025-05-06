# Hi there, I'm Daniel Hootini! 👋

## About Me

I'm currently pursuing a Bachelor's degree in Computer Science at Brigham Young University–Hawaii. I have a deep passion for technology, programming, and all things related to software engineering and automation. My journey in the tech world has been both diverse and enriching, allowing me to explore various facets of the field and develop a robust skill set.

## 🌐 Find Me Online

- **LinkedIn**: [Daniel Hootini](https://www.linkedin.com/in/daniel-hootini)
- **Portfolio**: [danielh987.github.io/portfolio](https://danielh987.github.io/portfolio)
- **Email**: [hootinid@gmail.com](mailto:hootinid@gmail.com)

## 🔧 Skills

- **Programming Languages**: Python
- **Web Development**: REST APIs, React
- **Cloud Technologies**: AWS (Machine Learning, Cloud Foundations, Data Engineering, Cloud Architecting)

## 🏆 Certifications

- **AWS Academy Graduate** - AWS Academy Machine Learning Foundations
- **AWS Academy Graduate** - AWS Academy Cloud Foundations
- **AWS Academy Graduate** - AWS Academy Data Engineering
- **AWS Academy Graduate** - AWS Academy Cloud Architecting

## 💼 Work Experience

- **Teacher Assistant, CS and IT** | Brigham Young University–Hawaii | Jan 2023 - Present
  - Facilitated learning by tutoring and grading computer science courses, contributing to an increase in student success rates.
  - Developed planning and entrepreneurial skills through team meetings and project reviews.

- **Mobile Developer Intern** | BYU-Hawaii Alumni Relations | Aug 2023 - Dec 2023
  - Led a project to develop a digital ID and benefits card for alumni, improving user accessibility and security.
  - Gained valuable experience in project management and team collaboration.

- **Developer** | Propellur | Dec 2021 - Dec 2022
  - Improved data processing efficiency and streamlined data entry processes, significantly boosting productivity and reducing error rates.

## 🎓 Education

- **Bachelor of Science in Computer Science** | Brigham Young University–Hawaii | Aug 2022 - Dec 2025

## 🌟 Projects

Discover more about the projects that fuel my passion for web development on my [portfolio](https://danielh987.github.io/portfolio/).

## 🌐 Languages

- English
- French
- Spanish

## ⚽ Hobbies

When I'm not coding, you can find me playing basketball, volleyball, or enjoying music on the piano.

## 📊 GitHub Stats

[![Daniel's GitHub stats](https://github-readme-stats.vercel.app/api?username=danielh987&show_icons=true&theme=shadow_blue)](https://github.com/danielh987)

## 🤝 Let's Connect!

Feel free to reach out to me via [LinkedIn](https://www.linkedin.com/in/daniel-hootini) or [email](mailto:hootinid@gmail.com) for any collaborations or just a friendly chat about technology and software development.

---

I hope you find my projects and contributions insightful and inspiring. Happy coding!  🚀 


<!-- index.html -->
<!DOCTYPE html>
<html>
  <head>
    <title>Simple Contact Form</title>
    <style>
      body {
        font-family: Arial, sans-serif;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        background-color: #f9f9f9;
      }

      .form-container {
        background-color: white;
        padding: 20px;
        border-radius: 10px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        width: 400px;
      }

      .form-container h2 {
        margin-top: 0;
        margin-bottom: 10px;
      }

      input[type="text"],
      input[type="email"] {
        width: 100%;
        padding: 10px;
        margin: 10px 0;
        border: 1px solid #ccc;
        box-sizing: border-box;
        border-radius: 5px;
      }

      button {
        width: 100%;
        background-color: #4caf50;
        color: white;
        padding: 10px;
        border: none;
        border-radius: 5px;
      }

      #message {
        margin-top: 15px;
      }
    </style>
  </head>
  <body>
    <div class="form-container">

      <h2>Contact Us</h2>
      <p>Please fill out the form below and we’ll get back to you soon.</p>

      <form id="contactForm">
      </form>

      <div id="message"></div>
      
    </div>

    <script>
      const form = document.getElementById("contactForm");
      const messageDiv = document.getElementById("message");

      form.addEventListener("submit", function (e) {
        e.preventDefault();
        messageDiv.textContent = "Form submitted successfully!";
      });
    </script>
  </body>
</html>
