# Roman Tyshchenko
#### Junior Frontend Developer
---
## <a id="title1">Contact information:</a>
Phone: +38 000 000 000 00  
E-mail: test1@gmail.com  
Telegram: @test2

---
## <a id="title1">About Myself:</a>
Having started my career as a layout designer in a local newspaper with minimum skills, I became profficient in printing design.  
My keen interest in printing technologies led me to working as a Prepress and DTP Engineer in the largest printing house in my city,
where I continued self-learning, examining the process of creating wine and food labels, magazines and other printed goods.  

Three years ago I’ve become passionate about retouching. I’ve mastered different retouching techniques,
learned to work with graphic tablet, become an advanced Photoshop user and found my first job as a retoucher.  

Remote work as a retoucher gives me extra free time, which I spend learning Frontend Development.
I’m interested in Web Development because this occupation provides endless possibilities for professional growth,
besides there’s a huge amount of free high quality resources for self-education and a large community of developers.  

I believe, that my ability to learn and to gain new skills will lead me through this path of becoming a proficient Frontend Developer.

---
## <a id="title1">Skills and Proficiency:</a>
- HTML5, CSS3
- JavaScript Basics
- Git, GitHub
- VS Code, IntelliJ IDEA
- Adobe Photoshop, Illustrator, InDesign
---
## <a id="title1">Code example:</a>
**Peak array index KATA from CODEWARS:** *Given an array of ints, return the index such that the sum of the elements to the right of that index equals the sum of the elements to the left of that index. If there is no such index, return -1. If there is more than one such index, return the left-most index.*
```javascript
function peak(arr) {

  for (let i = 1; i < arr.length - 1; i++) {
    let leftSum = arr.slice(0, i).reduce((accumulator, currentValue) => accumulator + currentValue);
    let rightSum = arr.slice(i + 1).reduce((accumulator, currentValue) => accumulator + currentValue);
    if (leftSum === rightSum) {
      return i;
    }
  }
  return -1;
}
```
---
## <a id="title1">Courses:</a>
- HTML and CSS Tutorials on the <a id="https://rs.school/js/">Курс «JavaScript/Front-end»</a> (completed)
- RS Schools Course «JavaScript/Front-end. Stage 0» (in progress)
---

## <a id="title1">Languages:</a>
- Ukrainian - Native
- Russian - Intermediate
- English - Intermediate
- Norwegian - B1