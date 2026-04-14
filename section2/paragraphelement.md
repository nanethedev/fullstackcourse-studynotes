<p align="center">
  <img src="https://64.media.tumblr.com/73f34eb6543708c5b237fd739b389a55/a76707adad47a36a-a6/s540x810/d5ca09678f2f10b2fa2f553a2c28a650fe3732b4.png" alt="paragraph" width="220">
</p>

<h1 align="center">O Elemento Paragraph/Parágrafo</h1>

---

| Perguntas-chave | Notas principais |
|---|---|
| Por que usar a tag `<p>`? | Sem ela, todo o texto vira uma linha só. A tag separa visualmente os parágrafos |
| Qual a estrutura da tag? | `<p>` conteúdo `</p>`, igual ao heading |
| Por que é importante pra acessibilidade? | Leitores de tela usam a tag `<p>` pra permitir que usuários cegos pulem entre parágrafos |
| O que é Lorem Ipsum? | Texto placeholder em latim usado pra simular conteúdo real sem precisar escrever |
| De onde vem o Lorem Ipsum? | Da literatura clássica latina de Cícero, usado na indústria gráfica desde os anos 1500 |
| Onde gerar Lorem Ipsum? | lipsum.com, ou versões divertidas: baconipsum.com, broipsum.com |

---

## Sem vs. com a tag `<p>`

```
SEM <p>:  Parágrafo 1 Parágrafo 2 Parágrafo 3  ← tudo numa linha só

COM <p>:  Parágrafo 1
          Parágrafo 2                            ← separados corretamente
          Parágrafo 3
```

---

## Resumo

> A tag `<p>` é essencial para separar texto em parágrafos distintos, sem ela, todo o conteúdo se junta em uma única linha. Além do visual, ela é fundamental para acessibilidade, permitindo que leitores de tela naveguem entre parágrafos. O Lorem Ipsum é o texto placeholder padrão do mercado, usado desde os anos 1500 para simular conteúdo real em layouts.

---

<details>
<summary>📝 Exercício — Paragraph Element</summary>

**Objetivo:** formatar os três blocos de texto abaixo usando a tag `<p>` para que apareçam como parágrafos separados no navegador.

```html

First paragraph. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna
aliqua. Arcu cursus vitae congue mauris. In nisl nisi scelerisque eu ultrices vitae auctor eu augue. Nisi est sit amet
facilisis magna. Diam sit amet nisl suscipit adipiscing bibendum est ultricies integer. Quis ipsum suspendisse ultrices
gravida dictum fusce ut. Euismod elementum nisi quis eleifend. Habitant morbi tristique senectus et. Amet nisl suscipit
adipiscing bibendum est ultricies integer. Viverra orci sagittis eu volutpat odio facilisis mauris sit. Nisi quis
eleifend quam adipiscing. Neque convallis a cras semper auctor neque vitae. Magna fermentum iaculis eu non. Vivamus arcu
felis bibendum ut tristique et. Justo nec ultrices dui sapien eget mi. In vitae turpis massa sed elementum tempus. Eu
facilisis sed odio morbi quis commodo. Sagittis aliquam malesuada bibendum arcu vitae elementum curabitur vitae.

Second paragraph. Suscipit adipiscing bibendum est ultricies. Tortor aliquam nulla facilisi cras fermentum. Eget aliquet nibh praesent
tristique magna. In hac habitasse platea dictumst vestibulum. Ornare quam viverra orci sagittis eu. Sit amet est
placerat in. Proin fermentum leo vel orci porta non pulvinar neque laoreet. Turpis in eu mi bibendum neque egestas
congue. Enim eu turpis egestas pretium aenean pharetra magna ac placerat. Ultrices sagittis orci a scelerisque purus
semper eget duis at. Egestas egestas fringilla phasellus faucibus scelerisque eleifend donec pretium. Condimentum
lacinia quis vel eros donec ac odio.

Third paragraph. Nisl purus in mollis nunc sed id semper risus. Ipsum a arcu cursus vitae congue mauris rhoncus aenean. Ridiculus mus
mauris vitae ultricies leo integer malesuada nunc. In tellus integer feugiat scelerisque. Lectus mauris ultrices eros in
cursus turpis massa. Sollicitudin ac orci phasellus egestas. Massa massa ultricies mi quis hendrerit dolor. Quam
elementum pulvinar etiam non quam lacus suspendisse faucibus interdum. Iaculis nunc sed augue lacus viverra. Id ornare
arcu odio ut sem nulla pharetra. Amet luctus venenatis lectus magna fringilla urna porttitor. Eu nisl nunc mi ipsum
faucibus vitae aliquet nec ullamcorper. Nunc mattis enim ut tellus elementum sagittis. Mauris augue neque gravida in
fermentum et sollicitudin. Pellentesque habitant morbi tristique senectus. Tristique senectus et netus et. Turpis
egestas sed tempus urna et pharetra pharetra. Feugiat vivamus at augue eget arcu dictum varius duis at. Lacus sed
viverra tellus in hac habitasse platea dictumst vestibulum. Nisl condimentum id venenatis a condimentum vitae sapien.
```

</details>

<details>
<summary>✅ Solução</summary>

```html
<p>First paragraph. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna
aliqua. Arcu cursus vitae congue mauris. In nisl nisi scelerisque eu ultrices vitae auctor eu augue. Nisi est sit amet
facilisis magna. Diam sit amet nisl suscipit adipiscing bibendum est ultricies integer. Quis ipsum suspendisse ultrices
gravida dictum fusce ut. Euismod elementum nisi quis eleifend. Habitant morbi tristique senectus et. Amet nisl suscipit
adipiscing bibendum est ultricies integer. Viverra orci sagittis eu volutpat odio facilisis mauris sit. Nisi quis
eleifend quam adipiscing. Neque convallis a cras semper auctor neque vitae. Magna fermentum iaculis eu non. Vivamus arcu
felis bibendum ut tristique et. Justo nec ultrices dui sapien eget mi. In vitae turpis massa sed elementum tempus. Eu
facilisis sed odio morbi quis commodo. Sagittis aliquam malesuada bibendum arcu vitae elementum curabitur vitae.</p>

<p>Second paragraph. Suscipit adipiscing bibendum est ultricies. Tortor aliquam nulla facilisi cras fermentum. Eget aliquet nibh praesent
tristique magna. In hac habitasse platea dictumst vestibulum. Ornare quam viverra orci sagittis eu. Sit amet est
placerat in. Proin fermentum leo vel orci porta non pulvinar neque laoreet. Turpis in eu mi bibendum neque egestas
congue. Enim eu turpis egestas pretium aenean pharetra magna ac placerat. Ultrices sagittis orci a scelerisque purus
semper eget duis at. Egestas egestas fringilla phasellus faucibus scelerisque eleifend donec pretium. Condimentum
lacinia quis vel eros donec ac odio.</p>

<p>Third paragraph. Nisl purus in mollis nunc sed id semper risus. Ipsum a arcu cursus vitae congue mauris rhoncus aenean. Ridiculus mus
mauris vitae ultricies leo integer malesuada nunc. In tellus integer feugiat scelerisque. Lectus mauris ultrices eros in
cursus turpis massa. Sollicitudin ac orci phasellus egestas. Massa massa ultricies mi quis hendrerit dolor. Quam
elementum pulvinar etiam non quam lacus suspendisse faucibus interdum. Iaculis nunc sed augue lacus viverra. Id ornare
arcu odio ut sem nulla pharetra. Amet luctus venenatis lectus magna fringilla urna porttitor. Eu nisl nunc mi ipsum
faucibus vitae aliquet nec ullamcorper. Nunc mattis enim ut tellus elementum sagittis. Mauris augue neque gravida in
fermentum et sollicitudin. Pellentesque habitant morbi tristique senectus. Tristique senectus et netus et. Turpis
egestas sed tempus urna et pharetra pharetra. Feugiat vivamus at augue eget arcu dictum varius duis at. Lacus sed
viverra tellus in hac habitasse platea dictumst vestibulum. Nisl condimentum id venenatis a condimentum vitae sapien.</p>
```

</details>


<summary>Meta do exercício: </summary>
<p align="center">
<img width="400" height="891" alt="image" src="https://github.com/user-attachments/assets/46dcfd94-453c-4db0-813f-8f87901448d3" />
</p>



<p align="center"> 
<a href="https://github.com/nanethedev/fullstackcourse-studynotes/blob/main/section2/headingelement.md"> ⬅️ Aula anterior</a> · <a href="">➡️ Próxima aula</a></p>
