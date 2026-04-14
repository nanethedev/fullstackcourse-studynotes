# Void Elements: hr e br


| Perguntas-chave | Notas principais |
|---|---|
| O que é um void element? | Elemento que não pode ter conteúdo, tem apenas uma tag única, sem abertura/fechamento separados |
| Como se escreve um void element? | `<hr />` ou `<br />` — a barra `/` fica antes do `>` |
| Qual a diferença entre `/tag` e `tag /`? | `/tag` = fechamento de elemento normal. `tag /` = void element (barra no final) |
| O que faz o `<hr />`? | Desenha uma linha horizontal na página para separar conteúdo |
| O que faz o `<br />`? | Quebra a linha dentro de um mesmo parágrafo, útil em poemas e endereços |
| Quando usar `<br />` vs `<p>`? | `<br />` = quebra de linha no mesmo parágrafo. `<p>` = parágrafo novo |
| A barra final é obrigatória? | Não, em HTML5 ambos são válidos, mas recomenda-se usar `<br />` para clareza |

---

## Termos-chave

| Termo | Definição |
|---|---|
| **Void element** | Elemento HTML sem conteúdo e sem tag de fechamento separada. Ex: `<br />`, `<hr />` |
| **`<hr />`** | Horizontal rule. Insere uma linha horizontal para separar seções de conteúdo |
| **`<br />`** | Break element. Quebra de linha dentro de um mesmo parágrafo |
| **Forward slash** | A barra `/` que aponta para a direita, usada em void elements e tags de fechamento |
| **Backslash** | A barra `\` que aponta para a esquerda, não usada em HTML |
| **HTML5** | Versão mais recente do HTML. Torna a barra final opcional em void elements |


---

## 🔁 Void vs. non-void element

```
NON-VOID:  <p> conteúdo </p>   ← tem abertura, conteúdo e fechamento
VOID:      <br />              ← tag única, sem conteúdo, barra no final
```

---

## Resumo

> Void elements são tags únicas sem conteúdo `<hr />` cria uma linha divisória e `<br />` quebra a linha dentro de um parágrafo. A diferença da barra é sutil: em tags de fechamento ela vem no início (`</p>`), em void elements vem no final (`<br />`). Use `<br />` só para casos como poemas e endereços, para novos parágrafos, sempre use `<p>`.

---

<details>
<summary>📝 Exercício: Void Elements</summary>

**Objetivo:** formatar o HTML abaixo para que fique igual a meta, com h1, endereço com quebras de linha, linha horizontal separadora e dois parágrafos.

```
William Blake

17 south molton street
London
W1K 5QT
UK

William Blake (28 November 1757 – 12 August 1827) was an English poet, painter, and printmaker. Largely unrecognised
during his life, Blake is now considered a seminal figure in the history of the poetry and visual art of the Romantic
Age. What he called his "prophetic works" were said by 20th-century critic Northrop Frye to form "what is in proportion
to its merits the least read body of poetry in the English language".[2] His visual artistry led 21st-century critic
Jonathan Jones to proclaim him "far and away the greatest artist Britain has ever produced".[3] In 2002, Blake was
placed at number 38 in the BBC's poll of the 100 Greatest Britons.[4] While he lived in London his entire life, except
for three years spent in Felpham,[5] he produced a diverse and symbolically rich collection of works, which embraced the
imagination as "the body of God"[6] or "human existence itself".[7]

Although Blake was considered mad by contemporaries for his idiosyncratic views, he is held in high regard by later
critics for his expressiveness and creativity, and for the philosophical and mystical undercurrents within his work. His
paintings and poetry have been characterised as part of the Romantic movement and as "Pre-Romantic".[8] In fact, he has
been said to be "a key early proponent of both Romanticism and Nationalism".[9] A committed Christian who was hostile to
the Church of England (indeed, to almost all forms of organised religion), Blake was influenced by the ideals and
ambitions of the French and American revolutions.[10][11] Though later he rejected many of these political beliefs, he
maintained an amiable relationship with the political activist Thomas Paine; he was also influenced by thinkers such as
Emanuel Swedenborg.[12] Despite these known influences, the singularity of Blake's work makes him difficult to classify.
The 19th-century scholar William Michael Rossetti characterised him as a "glorious luminary",[13] and "a man not
forestalled by predecessors, nor to be classed with contemporaries, nor to be replaced by known or readily surmisable
successors".[14]

```

</details>

<details>
<summary>✅ Solução</summary>

```html

<h1>William Blake</h1>

<p>
17 south molton street<br />
London<br />
W1K 5QT<br />
UK<br />
</p>

<hr />

<p>William Blake (28 November 1757 – 12 August 1827) was an English poet, painter, and printmaker. Largely unrecognised
during his life, Blake is now considered a seminal figure in the history of the poetry and visual art of the Romantic
Age. What he called his "prophetic works" were said by 20th-century critic Northrop Frye to form "what is in proportion
to its merits the least read body of poetry in the English language".[2] His visual artistry led 21st-century critic
Jonathan Jones to proclaim him "far and away the greatest artist Britain has ever produced".[3] In 2002, Blake was
placed at number 38 in the BBC's poll of the 100 Greatest Britons.[4] While he lived in London his entire life, except
for three years spent in Felpham,[5] he produced a diverse and symbolically rich collection of works, which embraced the
imagination as "the body of God"[6] or "human existence itself".[7]</p>

<p>Although Blake was considered mad by contemporaries for his idiosyncratic views, he is held in high regard by later
critics for his expressiveness and creativity, and for the philosophical and mystical undercurrents within his work. His
paintings and poetry have been characterised as part of the Romantic movement and as "Pre-Romantic".[8] In fact, he has
been said to be "a key early proponent of both Romanticism and Nationalism".[9] A committed Christian who was hostile to
the Church of England (indeed, to almost all forms of organised religion), Blake was influenced by the ideals and
ambitions of the French and American revolutions.[10][11] Though later he rejected many of these political beliefs, he
maintained an amiable relationship with the political activist Thomas Paine; he was also influenced by thinkers such as
Emanuel Swedenborg.[12] Despite these known influences, the singularity of Blake's work makes him difficult to classify.
The 19th-century scholar William Michael Rossetti characterised him as a "glorious luminary",[13] and "a man not
forestalled by predecessors, nor to be classed with contemporaries, nor to be replaced by known or readily surmisable
successors".[14]</p>
```

</details>


<summary>Meta do exercício: </summary>
<p align="center">
<img width="400" height="891" alt="image" src="https://github.com/user-attachments/assets/01eb9e06-15e0-48df-8c83-a8bd925f01e2" />
</p>


<p align="center"> 
<a href="https://github.com/nanethedev/fullstackcourse-studynotes/blob/main/section2/paragraphelement.md"> ⬅️ Aula anterior</a> · <a href="">➡️ Próxima aula</a></p>
