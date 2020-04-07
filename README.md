# palavrasAPI
Uma API que fornece palavras no formato .json

## Uses

### Axios use
```
axios.get('https://lurkasf.github.io/palavrasAPI/PT-BR/words.json')
      .then(response => (YOUR_VAR = response.data.words),
            error => {this.console.error(error);})
```
