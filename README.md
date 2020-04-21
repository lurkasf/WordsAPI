# palavrasAPI
Uma API que fornece palavras no formato .json

## Uses

### Axios use
```
axios.get('https://lurkasf.github.io/palavrasAPI/PT-BR/words.json')
      .then(response => (YOUR_VAR = response.data.words),
            error => {this.console.error(error);})
```
Remember to import axios

### Fetch use
```
fetch("https://lurkasf.github.io/palavrasAPI/PT-BR/words.json")
.then(response => response.json())
.then(data => {
  this.palavras = data.words, this.console.log("API OK")
}).catch(err => {
  this.console.err(err)
})
```
