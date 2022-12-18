# rsshool-cv-html
<!doctype html>
<html lang="ru">
<head>
  <meta charset="utf-8">
  <meta http-equiv="x-ua-compatible" content="ie=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Rsschool-cv-html</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cabin:wght@400;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="./css/reset.css">
  <link rel="stylesheet" href="./css/style.css">
</head>

<body>
  <div class="container-centered">
    <div class="two-columns">
      <div class="left-column">
        <header>
          <img src=".https://rs.school/images/rs_school_js.svg" alt="Логотип" width="204" height="204">
          <h1>Алина Ярмолик</h1>
          <h2>Ученик rsshool/stage0</h2>
        </header>
        <main>
          <section class="contacts">
            <h3>Контакты</h3>
            <ul>
              <li>
                <img src="./icons/phone.svg" alt="Phone Icon" width="30" height="30">
                <p>+375299991946</p>
              </li>
              <li>
                <img src="./icons/email.svg" alt="Email Icon" width="30" height="30">
                <p>alinayarmolik@gmail.com</p>
              </li>
              <li>
                <img src="./icons/telegram.svg" alt="Telegram Icon" width="30" height="30">
                <p>@alinayarmolik</p>
              </li>
              <li>
                <img src="./icons/behance.svg" alt="Behance Icon" width="30" height="30">
                <a href="https://www.behance.net/ankavolosh1156">Behance</a>
              </li>
              <li>
                <img src="./icons/linkedin.svg" alt="LinkedIn Icon" width="30" height="30">
                <a href="https://www.linkedin.com/in/anna-voloshina-259aa6154/">LinkedIn</a>
              </li>
            </ul>
          </section>
          <section class="skills">
            <h3>Skills</h3>
            <ul>
              <li>HTML5, CSS3</li>
            </ul>
          </section>
          <section class="languages">
            <h3>Языки</h3>
            <ul>
              <li>
                <p class="language-name">Англиский</p>
                <p>Upper-intermediate</p>
              </li>
              <li>
                <p class="language-name">Русский</p>
                <p>Native</p>
              </li>
              <li>
                <p class="language-name">Украинский</p>
                <p>Intermediate</p>
              </li>
              <li>
                <p class="language-name">Велорусский</p>
                <p>Basic</p>
              </li>
            </ul>
          </section>
        </main>
      </div>
      <aside class="right-column">
        <section class="about-myself">
          <div class="sub-header">
            <img src="./icons/myself.svg" alt="About Myself Icon" width="30" height="30">
            <h3>About Myself</h3>
          </div>
          <p>Мне 16,учюсь в 10 классе,изучаю физику и математику,саморазвиваюсь и пробую себя в разных облостях</p>
          <p>Я не знаю что тут написать по этому напишу про мою собаку.Ее завут Молли и она живет у меня уже 6 лет</p>
          <p>так нальем еще немного воды,поэтому расскажу о моем хобби.Я увлекаюсь вязанием и вяжу маленькие миленькие игрушки и вещи.</p>
          <p>И на этом мои мысли закончились,спасибо тебе мой читатель</p>
        </section>
        <section class="education">
          <div class="sub-header">
            <img src="./icons/education.svg" alt="Education Icon" width="30" height="30">
            <h3>Education</h3>
          </div>
          <p><strong>Я пока только обучаюсь всему</strong></p>
          <p>Electronic Engineering Faculty</p>
          <p>Years:2006-2022</p>
          <p>Specialization: у меня нет специализации</p>
        </section>
        <section class="courses">
          <div class="sub-header">
            <img src="./icons/courses.svg" alt="Courses" width="30" height="30">
            <h3>Courses</h3>
          </div>
          <ul>
            <li>HTML and CSS 50/50</li>
          </ul>
          <img class="score-img" src="./images/w3schools-score_small.jpg" alt="W3schools Score" width="500">
        </section>
        <section class="code-example">
          <div class="sub-header">
            <img src="./icons/code.svg" alt="Code Icon" width="30" height="30">
            <h3>Code example</h3>
          </div>
          <p><strong>Peak array index KATA from CODEWARS:</strong> Given an array of ints, return the index such that
            the sum of the elements to the right of that index equals the sum of the elements to the
            left of that index. If there is no such index, return -1. If there is more than one such index, return the
            left-most index. Ну а вообще я это немного скопировала,и пример этого кода был в оброзце</p>
          <pre>
            <code>
function peak(arr) {

  for (let i = 1; i &lt; arr.length - 1; i++) {
    let leftSum = arr.slice(0, i).reduce((accumulator, currentValue) => accumulator + currentValue);
    let rightSum = arr.slice(i + 1).reduce((accumulator, currentValue) => accumulator + currentValue);

    if (leftSum === rightSum) return i;
  }
  return -1;
}</code>
          </pre>
        </section>
      </aside>
    </div>
    <footer>
      <a class="my-github" href="https://github.com/AnnaVoloshina">
        <img class="github-icon" src="./icons/github.svg" alt="Github Icon" width="26" height="26">
        <p>Visit my GitHub</p>
      </a>
      <p>© 2021</p>
      <a href="https://rs.school/js/">
        <img src="./icons/rsschool.svg" alt="Rsschool Icon" width="73" height="26">
      </a>
    </footer>
  </div>
</body>

</html>
