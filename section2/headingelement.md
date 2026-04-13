<p align="center">
  <img src="https://blob.gifcities.org/gifcities/SAYHC3FAWPOGKWZNXHZK2Y66YBF7XIME.gif" alt="html" width="220">
</p>


<h1 align="center">Tag Heading</h1>

| Perguntas-chave | Notas principais |
|---|---|
| O que é uma tag? | Qualquer coisa dentro de `< >`. Ex: `<h1>` é a tag de abertura, `</h1>` é a de fechamento |
| O que é um elemento? | O conjunto completo: tag de abertura + conteúdo + tag de fechamento |
| Qual a diferença entre tag e elemento? | Tag = só a marcação. Elemento = tag + conteúdo |
| Quantos níveis de heading existem? | 6 de `h1` (maior) até `h6` (menor). Não existe `h7` |
| Posso ter mais de um `h1`? | Não. Boa prática: apenas um `h1` por página |
| Posso pular de `h1` para `h3`? | Não. Sempre seguir a hierarquia em ordem |
| O que é o forward slash `/`? | É o que diferencia a tag de fechamento (`</h1>`) da de abertura (`<h1>`) |

---

## Estrutura de uma tag heading

```
<h1>Título principal</h1>
  ↑               ↑
tag de          tag de
abertura       fechamento
```

---

## Resumo

> Um elemento HTML é formado por uma tag de abertura, o conteúdo e uma tag de fechamento. Os headings vão de h1 a h6 e seguem uma hierarquia como o sumário de um livro. H1 é o título principal e só deve aparecer uma vez por página. Nunca pule níveis: se tem h3, deve ter h2 antes.

---

<p align="center">
<img width="720" height="1228" alt="image" src="https://github.com/user-attachments/assets/e49b69dd-f042-4be0-9ae8-63bdc1c6da92" />
</p>

<details>
<summary>📝 Exercício — Heading Element</summary>

**Objetivo:** formatar o conteúdo abaixo usando as tags h1 até h4, seguindo a hierarquia correta.

```html
Book
Chapter 1
Section 1
Section 2
Chapter 2
Section 1
Diagram 1
Chapter 3
Section 1
Section 2
```

</details>

<details>
<summary>✅ Solução</summary>

```html
<h1>Book</h1>
  <h2>Chapter 1</h2>
    <h3>Section 1</h3>
    <h3>Section 2</h3>
  <h2>Chapter 2</h2>
    <h3>Section 1</h3>
      <h4>Diagram 1</h4>
  <h2>Chapter 3</h2>
    <h3>Section 1</h3>
    <h3>Section 2</h3>
```

</details>

<summary>Meta do exercício: </summary>
<p align="center">
<img width="400" height="891" alt="image" src="https://github.com/user-attachments/assets/1cae6939-6758-4a75-abcc-b9d461a139ed" />
</p>


<p align="center"> 
<a href="https://github.com/nanethedev/fullstackcourse-studynotes/blob/main/section2/whatishtml.md"> ⬅️ Aula anterior</a> · <a href="">➡️ Próxima aula</a></p>
