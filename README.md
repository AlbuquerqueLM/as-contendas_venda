# Projeto Portfólio: Página de Venda do Livro *As Contendas*

Desenvolvi esse projeto com o intuito de fazer uma simulação de uma construção real de uma página de vendas para um livro físico, nesse caso, um publicado de minha própria autoria. 
A obra se chama "As Contendas - O Esquadrão do Centro da Praça" reconhecido pela academia brasileira de letras pelo ISBN - 9786501444628
Eu utilizei esta aplicação como uma forma de demonstrar minhas habilidades técnicas na criação de interfaces web e integração com serviços externos, mesmo sem conhecimentos iniciais em back-end.



##  Tecnologias e Conceitos que Visei:

### HTML
- Uso de formulários com campos validados
- Agrupamento de dados com `<fieldset>` e `<legend>`
- Formulário adaptado para versões de produto diferentes (unitário e luxo, com questões de precificação e frete)

### CSS
- Estilização responsiva e moderna usando variáveis CSS (`:root`)
- Efeitos visuais como `hover`, `fadeIn`, `transform`, `scale` - mostrando serem bastante eficazes para a polidez do projeto.
- Separação entre layout principal (`styles.css`) e formulário (`form.css`) - Dentro de uma pasta apenas para CSS.

### JavaScript
- Cálculo dinâmico de preço
- Atualização visual com base na seleção do produto (Tópico que abordarei com mais ênfase nas próximas versões desse mesmo projeto)
- Condicional para abrir um dos 4 links de pagamento diferentes com base no valor total (Todos reverberando uma situação de compra, por ser um qr code para pix na minha conta pessoal)
- Exibição de mensagem de confirmação
- Integração com [EmailJS](https://emailjs.com) para envio de pedidos diretamente ao autor. (Um desafio gigantesco, principalmente para fazer com que os formulários e os 'ids' estivessem corretamente preenchidos)

---

## Simulação de Situação Real

Este projeto foi construído como se fosse um desafio profissional verdadeiro:  
> E sou um autor independente que deseja vender meu próprio livro físico e preciso de uma página funcional, elegante e que colete pedidos de forma automática. Acredito que **esse** tenha sido o começo de todo um site sobre meu próprio trabalho como artista.

---

##  Scripts e Integrações

- **EmailJS:** envia todas as informações do formulário para o meu e-mail.  (testado e operante)
- **Abertura de links de pagamento:** cada valor de pedido (R$ 140, 150, 175, 185) aciona um link de pagamento diferente via Nubank. (testado e operante)
- **Validação dos campos:** feita com HTML5 e reforçada por JavaScript. (testado e operante)
- **Infobox pós-envio:** feedback visual informando que o cliente receberá e-mail com código de rastreio após o pagamento. (testado e operante, embora o email de volta para o cliente tenha que ser feito de forma humana, acredito que em versões futuras eu consiga automatizar isso também)

---

## Organização de Códigos

Prezei por um código polido e organizado, embora tenha sido complicado manter essa metodologia e por diversas vezes me perdi no meio de tantas linhas. Por fim, revisei observando apenas a disposição do que foi digitado e colocando harmonicamente dentro do vscode.

---

##  Conclusão

Foi completamente exaustivo, extremamente difícil e trabalhoso.
Esse projeto exigiu uma dedicação e paciência que eu não pensei que tivesse ter, me custou muitas horas de estudos, pesquisas, tentativas e erros. 
Entender algumas tecnologias como o EmailJS foi custoso, validar os campos e conseguir fazer integrações puxou muito do meu trabalho. 

De qualquer forma, de todos os projetos que eu já desenvolvi, mesmo que não tivessem subido para o GitHub, creio que esse tenha sido o mais recompensador, principalmente pois tenho intuitos reais de utiliza-lo profissionalmente, uma criação minha para vender um trabalho que é meu. 

---

##  Autor

L. M. Albuquerque — Escritor e Desenvolvedor em Formação  
[Email de contato](mailto:drive.sidequest@gmail.com)

---

##  RESULTADO FINAL

Páginas hospedadas no GitHub Pages para visualização:
[Clique Aqui para Acessar a Página Online](https://albuquerquelm.github.io/as-contendas_venda/)

