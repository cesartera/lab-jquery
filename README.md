### Exercícios Eventos jQuery

Neste exercício você vai poder utilizar alguns dos eventos utilizados com maior frequência com jQuery:

- ready
- submit
- change
- click
- keypress

Você pode encontrar uma lista completa dos eventos de jQuery em: [http://api.jquery.com/category/events/](http://api.jquery.com/category/events/)

---

### Exercícios

**Instruções:**

Para cada exercício, crie uma pasta e dentro dela um arquivo `index.html` e um arquivo `app.js` 

Você pode também criar um arquivo `style.css`, caso queira estilizar sua pasta.

Para a entrega, você pode subir todas as pastas num único repositório do GitHub.

🔵 **Exercício 1 - Ready**

Adicione um h1 à página, com a mensagem: “Estou pronto!” e uma imagem do Bob Esponja, assim que a página carregar.

Tudo isso, claro, sem tocar no HTML.

![spongebob.gif](https://pa1.narvii.com/7206/34e4c594210d6b9f7792232d059d3eb687449339r1-260-200_hq.gif)

🔵 **Exercício 2 - Submit**

Neste exercício você precisa fazer sua página carregar um vídeo do YouTube.

Crie um formulário com os inputs:

- Nome do Vídeo - Deve receber o Nome que o usuário quiser dar para o vídeo
- Descrição - Deve receber uma descrição que o usuário quiser dar para o vídeo
- Link - Deve receber um link para um vídeo no YouTube.

Adicione também um botão do tipo submit ao formulário.

Ao preencher o formulário e clicar no botão “submit” o vídeo do YouTube deve aparecer embarcado na página, assim como o Nome e a Descrição.

**DICA:** Se precisar, pesquise no Google: “Como impedir que um botão envie um formulário automaticamente?”

🔵 **Exercício 3 - Change**

Crie um Array de objetos JavaScript que contenha uma lista de pelo menos 5 Alunos, com suas respectivas notas, de 0 a 10.

Exemplo:

```jsx

const alunos = [
	{nome: "César", nota: 7},
	{nome: "Rodrigo", nota: 9},
	{nome: "Carla", nota:8},
	{nome: "Ana", nota: 10},
	{nome: "José", nota: 8},
]
```

No HTML, adicione um input do tipo Select e faça das opções do Select os nomes dos alunos.

Quando o usuário mudar o nome do aluno no Select, o programa deve mostrar qual a nota do aluno selecionado.

**Bônus:** Exibir o Status de Aprovado ou Reprovado ou em recuperação.

🔵 **Exercício 4- Click**

Crie uma `ul`, que contenha em cada `li`, uma frase de uma música que você gosta.

Adicione pelo menos 10 frases.

Ao clicar em cada uma das frases, de forma individual, faça ela aparecer numa segunda lista, agora com uma cor diferente.

🔵 **Exercício 5- keypress**

O Desafio aqui é simples criar um Cronômetro.

Ao pressionar a tecla “Espaço” o cronometro deve iniciar

Ao pressionar a tecla “Espaço” novamente o cronômetro deve parar.

Você pode também adicionar o botão Zerar.

**Dica:** Pesquisar pelo método JavaScript `setInterval()`
