

# Iaroslav Eliseev

<img src="./assets/my_photo.jpg" alt="My photo" width="150"/>


---

### Contact Information  
- **Email:** mr.ei@ya.ru
- **Discord:** [iaroslaveliseev_75117](https://discordapp.com/users/1366781004781719623)
- **GitHub:** [iaroslav-eliseev](https://github.com/iaroslav-eliseev)   

---

### About Me  
Aspiring Junior Frontend Developer with a strong passion for learning and improving skills in JavaScript, HTML, and CSS. Motivated to grow in a professional environment and contribute effectively to team projects. Quick learner, proactive, and eager to tackle new challenges in web development.

---

### Skills  
- **Languages:** JavaScript (ES6+), HTML5 (basic) , CSS3 (basic)  
- **Version Control:** Git, GitHub  
- **Tools:** VS Code, Chrome DevTools, npm, Webpack (basic)  
- **Methodologies:** BEM, Responsive Design, Agile (Scrum basics), Pixel Perfect

---

### Code Example  
Here is a solution to a Codewars challenge ("How good are you really?", 8 kyu):

```javascript

function betterThanAverage(classPoints, yourPoints) {
  
  let meanValue = yourPoints;
  classPoints.forEach((element) => {
    meanValue += element;
  });
  const average = meanValue / (classPoints.length + 1);
  
  if (yourPoints > average) {
    return true
  } else {
    return false
  };
};


