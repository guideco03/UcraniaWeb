# UcraniaWomen - Tela de Login para refugiadas
<p> Como dito nas aulas de UX Design, nós, programadores, precisávamos desenvolver um site que fosse "fácil e responsivo" para ajudar as mulheres que estão em situação de guerra na ucrânia a encontrarem um lar. Dito isso, desenvolvi uma tela de Login simples e ágil, para que elas não encontrem dificuladade na hora de acessar sua conta.<p>
Explicação do Código JavaScript: primeiro passo foi recuperar os valores do input com a variável "let", com document.getElementById e document.querySelector.
Feito isso, desenvolvi um validador para o e-mail e a senha; O campo e-mail, por exemplo, precisa ser preenchido seguindo o formato nome@email.com,
sendo que se o usuário não digitar o "@", algum nome antes ou depois do "@", e o ".com" no final, o campo não será preenchido. Na senha, o usuário precisa digitar
no mínimo 6 dígitos, incluindo pelo menos um número e um caractere especial como "@, %, $, etc". Para isso, criei a função nas linhas 44 e 50 utilizando
expressões regulares (peguei no site do mozila). Todas as vezes em que os requisitos não são atendidos, uma mensagem aparece para o usuário, ensinando a ele a forma correta de preencher o campo. <p>
OBS: Os campos nulos não são preenchidos. 
