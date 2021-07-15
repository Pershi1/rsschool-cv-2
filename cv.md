# Andrey Serikov

# Contacts

- Tel: **+375293850999**
- E-mail: **AS.Korag@protonmail.com**
- Telegram: **@ubyrfehxbu_f**
- Discord: **AS.Korag(@ASKorag)** (rs-school server)
- VK: [AS.Korag](https://vk.com/as.korag)

# About Me

Brief personal information: 26 years old, higher education, married, have a son. My aim is to do what I love and become a professional at it. My strengths:

1. Fast learning
2. Dislike for low-quality work
3. Hard work
4. Curiosity
5. Honesty
6. No bad habits

# My skills

### Main skills

- JS + TS
- HTML (Pug)
- CSS (SASS)
- Git
- Webpack
- React (Redux)

### Additional skills

- Linux

# Sample code

```{javascript}
const check = (str, bracketsConfig) => {
  const newStr = str
  const escapedChars = '[()|'
  let isIdentity
  do {
    isIdentity = false
    for (paar of bracketsConfig) {
      const stringForRegExp = paar
        .map(char =>
          escapedChars.includes(char) === true ? `\\${char}` : char
        )
        .join('')
      const regExp = new RegExp(stringForRegExp, 'g')
      if (regExp.test(newStr)) {
        isIdentity = true
        newStr = newStr.replace(regExp, '')
      }
    }
  } while (isIdentity)
  return newStr.length === 0
}
```

# Work experience

😢

# Education

1. [The Modern JavaScript Tutorial](https://learn.javascript.ru/)
2. [\<VM\>](https://www.youtube.com/channel/UCg8ss4xW9jASrqWGP30jXiw)
3. [IT-KAMASUTRA](https://www.youtube.com/channel/UCTW0FUhT0m-Bqg2trTbSs0g)
4. [webDev](https://www.youtube.com/channel/UCE9ODjNIkOHrnSdkYWLfYhg)
5. [Front-end Science c Сергеем Пузанковым](https://www.youtube.com/channel/UCmI5YBB9KJ0xLtFtgBX8rfw)

# English level

At the moment my level is A2, but I'm constantly learning and I'm not going to stop until I can speak fluently.