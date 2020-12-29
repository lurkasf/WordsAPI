# WordsAPI
Uma API que fornece palavras no formato .json

O principal uso conhecido da API, atualmente é para o minigame [Anagrama](https://lurkasf.github.io/Anagrama), de mesma autoria.

## Uses

### With Axios
```
axios.get('https://lurkasf.github.io/WordsAPI/PT-BR/words.json')
      .then(response => (YOUR_VAR = response.data.words),
            error => {this.console.error(error);})
```
Remember to import axios

### With Fetch
```
fetch("https://lurkasf.github.io/WordsAPI/PT-BR/words.json")
.then(response => response.json())
.then(data => {
  this.palavras = data.words, this.console.log("API OK")
}).catch(err => {
  this.console.err(err)
})
```
