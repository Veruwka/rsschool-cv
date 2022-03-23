# Vera Tiutiunnik     ![my_photo](https://github.com/Veruwka/rsschool-cv/blob/gh-pages/assets/images/myphoto.jpg "Hi! It's me")

> Hi! I am Vera and I have just started learning web development

> I like building websites and writing code. I really want to master new skills and become a good specialist

> I am glad when I succeed, because it is not easy to deal with everything at once. Hope I can do it!

## Skills

**HTML CSS JS GIT**

## Education

- 2005 - 2010 Training at SevNTU as a system engineer. Diploma of higher education.
- Completed the JS / Front-End Stage 0 online course at RSSchool
- Completed basic courses in HTML, CSS and JS at the HTML-Academy online school  
- Taking an English for IT course at lingualeo.com
- Studying at online school RSSchool in JavaScript/Front-end 2022Q1

## Languages

+ Russian - Native speaker
+ Ukrainian - Native speaker
+ English - A2 (Pre-Intermediate)

## Projects

*Photographer's portfolio https://rolling-scopes-school.github.io/veruwka-JSFEPRESCHOOL/portfolio/
*Game Tic-Tac-Toe https://rolling-scopes-school.github.io/veruwka-JSFEPRESCHOOL/tic-tac-toe/
*Audioplayer https://rolling-scopes-school.github.io/veruwka-JSFEPRESCHOOL/audioplayer/
*Random-jokes https://rolling-scopes-school.github.io/veruwka-JSFEPRESCHOOL/random-jokes/

## Code Examples

                ```async function getQuotes() {
                      const quotes = 'data.json';
                      const res = await fetch(quotes);
                      const data = await res.json();
                      console.log(data);
                      addText(data);
                  }
                  getQuotes();

                  function addText(array) {
                      let quote = document.querySelector('.quote');
                      let author = document.querySelector('.author');
                      let random = Math.floor(Math.random()*array.length)
                      quote.textContent = array[random].text;
                      author.textContent = array[random].author;
                      picture.classList.toggle('picture');    
                      picture.classList.toggle('picture-before');
                  }

                  button.addEventListener('click', getQuotes);
                  button.onclick = function f(){
                      picture.classList.remove('picture');
                  }```

## Contacts

> Email: revkaa@gmail.com
> Git-hub: https://github.com/Veruwka/
> Discord: VeraTiutiunnik#4076
> WhatsApp, Telegram, Viber: +8 (978) 827 60 10
