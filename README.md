### Hi there 👋

*teste*
**teste**
__teste__
___teste___

- lista1
- lista2
    - sublista

1. lista ordenada 1
2. lista ordenada 2
    1. sublista ordenada

[exemplo imagem via link](https://conteudo.imguol.com.br/c/entretenimento/70/2016/04/22/21abr2016---ate-a-nasa-divulgou-uma-foto-da-nebulosa-do-caranguejo-remanescente-de-supernova-vista-do-telescopio-do-observatorio-espacial-herschel-alguem-pode-ver-prince-tocando-sua-guitarra-1461328809241_v2_900x506.jpg)

### imagem embeded
![exemplo imagem embeded](https://conteudo.imguol.com.br/c/entretenimento/70/2016/04/22/21abr2016---ate-a-nasa-divulgou-uma-foto-da-nebulosa-do-caranguejo-remanescente-de-supernova-vista-do-telescopio-do-observatorio-espacial-herschel-alguem-pode-ver-prince-tocando-sua-guitarra-1461328809241_v2_900x506.jpg)

### exemplo de código em bloco
```
const mode = document.querySelector('body');
const switcher = document.getElementById('flexSwitchCheckDefault');
const navbarBackGround = document.querySelector('[data-navbar]');

switcher.addEventListener('click', () => {
    const check = switcher.checked ? 'dark' : 'light';
    if (check === 'light') {
        navbarBackGround.classList.toggle('bg-light');
        navbarBackGround.classList.toggle('bg-dark');
    }else if (check === 'dark') {
        navbarBackGround.classList.toggle('bg-dark');
        navbarBackGround.classList.toggle('bg-light');
    }
    mode.setAttribute('data-bs-theme', check);
})

```

> exemplo de citacao
---
### exemplo de tabela

| cabecalho 1 | cabecalho 2 |
|-------------|-------------|
|   texto 1   |    texto 2  |


<!--
**tarciosilva/tarciosilva** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
