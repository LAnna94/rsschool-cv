<div style="text-align: center;">

# Hanna Lakhmotka

</div>

## Junior Frontend Developer
### +1 (224)2584925 | annalahmotko@gmail.com | [LinkidIn](https://www.linkedin.com/in/anna-lahmotko/) | [GitHub](https://github.com/LAnna94)

----

## Summary
Junior Frontend Developer with a background in PPC, where I gained technical experience through site audits and configuring web analytics that required code work. My interest in web development led me to complete courses at Yandex Practicum and RS School, where I built a solid foundation and a portfolio of projects. While I continue expanding my skills in this dynamic field, I am eager to apply my knowledge to real-world projects and deliver high-quality, user-centered solutions.

----

## Skills
* JavaScript             
* HTML5
* CSS3 (Bootstrap, SASS, BEM)
* React
* Node.js
* Git, GitHub
* Figma, Adobe Photoshop
* MongoDB
* Express.js
* VS Code
* Postman
* TypeScript

----

## Code examples
**The Hashtag Generator from CODEWARS:** *The marketing team is spending way too much time typing in hashtags. Let's help them with our own Hashtag Generator! It must start with a hashtag (#). All words must have their first letter capitalized. If the final result is longer than 140 chars it must return false. If the input or the result is an empty string it must return false.*

```

function generateHashtag (str) {
  if (str === "") {
    return false
  } 

  let arr = str.split(" ").filter(item => item !== "");

  if (arr.length === 0) {
    return false
  }
    
  let newArr = arr.map((item) => {
    let lettersArr = item[0].toUpperCase() + item.slice(1);
    return lettersArr
  })

  let hashtag = `#${newArr.join('')}`

    if (hashtag.length > 140) {
  return false
}

  return hashtag
}

```

----

## Work Experience
### Yandex Practicum (courses)
Some projects completed during training (all work is reviewed by mentors and goes through code review.):

1. **Project: "How to Learn"**

Functionality: Single-page informational website

Technologies: HTML, CSS, BEM

Project link: https://github.com/LAnna94/how-to-learn


2. **Project: "Russian Travel"**

Functionality: Single-page website, adapted for common screen resolutions

Technologies: HTML, CSS, responsive design, Grid Layout, Flexbox, BEM

Project link: https://github.com/LAnna94/russian-travel


3. **Project: Mesto**

Functionality: Add/remove cards, edit profile information, "Like" feature with like counter, API and server integration

Technologies: HTML, CSS, React.js, Webpack, Node.js, JavaScript, BEM, responsive design

Project link: https://github.com/LAnna94/mesto-react


### MegaSiteGroup
PPC Specialist

Full cycle of work on digital advertiSsing campaigns: initial account setup and in-depth keyword research to ongoing optimization and performance analysis, site audits, and development of recommendations to improve User Experience.
Collaborated closely with the project manager.

Tools and applications: Google Tag Manager, Google Analytics, Photoshop, HTML, CSS.

----

## Education
**Bachelor Degree in Information & Communications Technology, BSU (2016)**

**Yandex Practicum (2022)**

----

## Languages
* Russian (Native)
* English (B2)