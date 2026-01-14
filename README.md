# Himanshu Singh

**Web Developer | Frontend & JavaScript Specialist**

📍 India  
📧 sh707836@gmail.com  
🔗 Portfolio: https://mrhimanshu0207.github.io/Portfolio  
🔗 LinkedIn: https://linkedin.com/in/mrhimanshu0207  

---

## Summary

Web Developer with hands-on experience in **JavaScript, React, HTML, CSS, and Node.js**.  
Focused on building clean UI, responsive layouts, and real-world projects while learning full-stack development.

---

## Skills

- **Frontend:** HTML, CSS, JavaScript, React, Bootstrap
- **Backend:** Node.js, Firebase
- **Databases:** MongoDB, MySQL
- **Tools:** Git, GitHub, VS Code
- **Other:** UI/UX, Responsive Design

---

## Projects

**Resume Builder**  
Online resume builder with PDF export and themes  
🔗 https://mrhimanshu0207.github.io/Resume-Builder/

**File Sharing App**  
Secure file uploads and shareable links using Firebase  
🔗 https://mrhimanshu0207.github.io/File-Sharing-with-Link/

**Weather Forecast App**  
Real-time weather application using API  
🔗 https://mrhimanshu0207.github.io/Weather-Forecast-App/

**Portfolio Website**  
Personal portfolio showcasing projects and skills  
🔗 https://mrhimanshu0207.github.io/Portfolio/

---

## Learning & Goals

- Advanced React & JavaScript
- Full-Stack Development
- Open-Source Contribution
- UI/UX Best Practices

- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ mrhimanshu0207 }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:           A preset of color, one of [github, github-dark, github-light]
    #  - color_snake:       Color of the snake
    #  - color_dots:        Coma separated list of dots color.
    #                       The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                       Exactly 5 colors are expected.
    #  - color_background:  Color of the background (for gif only)
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9&color_background=#aaaaaa
