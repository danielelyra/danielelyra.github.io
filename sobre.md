---
# title: Elements
feature_text: |
  ## Quem sou eu?
feature_image: "https://picsum.photos/2560/600?image=505"
excerpt: "Daniele Lyra é economista e cientista de dados"
aside: true
---
{% include figure.html image="/assets/images/me.jpeg" position="left" width="200" height="300" %}

<small> Olá! Fico feliz por você querer saber mais sobre mim e minha trajetória.</small>

<small> Sou uma economista apaixonada por números desde muito cedo, sempre adorei um desafio o que me levou a desenvolver a capacidade de criar possibilidades de escolhas mesmo quando não existem.</small>

<small>Ingressar numa faculdade pública era um dos meus sonhos, que consquistei ao ingressar e formar em Ciências Econômicas na federal fluminense a UFF, aproveitei muito essa fase e me apaixonei por Niterói mais conhecida como a cidade sorriso.</small>
        
 <small> Atuei em finanças por cerca de dez anos, nos mais diversos setores como energia, seguros, fintechs, indústria, etc. Aprendi muito na prática, buscando soluções para os desafios que surgiam e com profissionais excelentes que compartilharam suas experiências comigo.</small>

 <small> Depois de muito excel e sempre com um olhar no fututo, me deparei com novas tecnologias e ferramentas que poderia aprender para melhorar minhas habilidades de análise de dados. Em 2019, participei de um Bootcamp de ciência de dados e ali tive a certeza que era "minha praia" me empolguei em aprender algo novo a cada dia e decidi mudar de carreira. 
        
 <small> Desde então, eu me dedico a aprender e a melhorar meus conhecimentos na área. Em 2020, terminei o MBA de Bussiness Analytics e Big Data na FGV, aprendi a resolver problemas empresariais utilizando técnicas analíticas e com muito "mão na massa" praticando os métodos e criando soluções. Durante o curso, vi que precisava melhorar minhas habilidades em programação e meus conhecimentos de computação. Já tinha feito alguns cursos online, mas queria algo mais completo como uma graduação, passei no vestibular e no mesmo ano ingressei no curso de Ciência de Dados da UNIVESP e tem contribuído muito no meu aprendizado.</small>

 <small> Um dos meus hobbies é estudar e isso tem me ajudado muito nessa jornada. Sempre busco o conhecimento para evoluir como ser humano e aprender algo novo, como agora que me aventurei em aprender a tocar piano. Sei que aprendi muito nesse período de transição de carreira e tenho muito a aprender ainda, e é isso que me motiva todos os dias.</small>

 <small> Compartilho com vocês meus estudos, projetos, pensamentos, carreira e a vida em geral, espero que você aproveite o conteúdo e fique a vontade para me escrever um e-mail ou mandar mensagem nas redes sociais.</small>



<!-- # Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

<small>A small element</small>

[A link](https://david.darn.es "A link")

Lorem ipsum dolor sit amet, consectetur adip* isicing elit, sed do eiusmod *tempor incididunt ut labore et dolore magna aliqua.

Duis aute irure dolor in [A link](https://david.darn.es "A link") reprehenderit in voluptate velit esse cillum **bold text** dolore eu fugiat nulla pariatur. Excepteur span element sint occaecat cupidatat non proident, sunt _italicised text_ in culpa qui officia deserunt mollit anim id `some code` est laborum.

* An item
* An item
* An item
* An item
* An item

1. Item one
2. Item two
3. Item three
4. Item four
5. Item five

> A simple blockquote

Some HTML...

``` html
<blockquote cite="http://www.imdb.com/title/tt0284978/quotes/qt1375101">
  <p>You planning a vacation, Mr. Sullivan?</p>
  <footer>
    <a href="http://www.imdb.com/title/tt0284978/quotes/qt1375101">Sunways Security Guard</a>
  </footer>
</blockquote>
```

...CSS...

``` css
blockquote {
  text-align: center;
  font-weight: bold;
}
blockquote footer {
  font-size: .8rem;
}
```

...and JavaScript

``` js
const blockquote = document.querySelector("blockquote")
const bolden = (keyString, string) =>
  string.replace(new RegExp(keyString, 'g'), '<strong>'+keyString+'</strong>')

blockquote.innerHTML = bolden("Mr. Sullivan", blockquote.innerHTML)
```

`Single line of code`

## HTML Includes

### Contact form

{% include site-form.html %}

``` html
{% raw %}{% include site-form.html %}{% endraw %}
```

### Demo map embed

{% include map.html id="1UT-2Z-Vg_MG_TrS5X2p8SthsJhc" title="Coffee shop map" %}

``` html
{% raw %}{% include map.html id="XXXXXX" title="Coffee shop map" %}{% endraw %}
```

### Button include

{% include button.html text="A button" link="https://david.darn.es" %}

{% include button.html text="A button with icon" link="https://twitter.com/daviddarnes" icon="twitter" %}

``` html
{% raw %}{% include button.html text="A button" link="https://david.darn.es" %}
{% include button.html text="A button with icon" link="https://twitter.com/daviddarnes" icon="twitter" %}{% endraw %}
```

### Icon include

{% include icon.html id="twitter" title="twitter" %} [{% include icon.html id="linkedin" title="twitter" %}](https://www.linkedin.com/in/daviddarnes)

``` html
{% raw %}{% include icon.html id="twitter" title="twitter" %}
[{% include icon.html id="linkedin" title="twitter" %}](https://www.linkedin.com/in/daviddarnes){% endraw %}
```

### Video include

{% include video.html id="zrkcGL5H3MU" title="Siteleaf tutorial video" %}

``` html
{% raw %}{% include video.html id="zrkcGL5H3MU" title="Siteleaf tutorial video" %}{% endraw %}
```


### Image includes

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Image with caption" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Right aligned image" position="right" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Left aligned image" position="left" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/1600/800?image=894" alt="Image with just alt text" %}

``` html
{% raw %}{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Image with caption" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Right aligned image" position="right" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Left aligned image" position="left" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/1600/800?image=894" alt="Image with just alt text" %}{% endraw %}
``` -->
