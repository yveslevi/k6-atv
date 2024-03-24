# Atividade de implementação do k6 - Semana 7

Esse repositório será utilizado como uma documentação individual a partir do teste que está no repositório original do grupo.

Para fazer o teste você mesmo, poderá acessar o repositório do grupo 3 e ir em:

```
./2024-T0003-ES09-G03/codigo/backend/src/scripts/loads/answerdReport
```

Depois de ter o projeto configurado na sua máquina, poderá rodar: 

```
k6 run ./case_1.js
```

Abaixo você consegue ver o teste de carga feito para 10 VU's em 5 minutos (300s)

![image](https://github.com/yveslevi/k6-atv/assets/98428867/7217ebce-c5b0-4dc2-96e0-fc6ba40946c3)


Explicando a tecnologia:

O k6 é uma biblioteca open-source que faz o teste de performance da sua aplicação de forma fácil, ou seja, com pouco código e apenas uma linha de comando você consegue testar a disponibilidade, velocidade, além de outros parâmetros da sua aplicação. Diferente de outras ferramentas de teste de carga que podem ser complexas e difíceis de usar, o k6 distingue-se pela sua simplicidade, eficiência e por ser uma ferramenta projetada com uma abordagem "como código", o que significa que você usa código JavaScript para escrever seus testes de carga, tornando-o uma ferramenta poderosa e flexível.

Conceitos aprendidos:

Seguindo o turtorial eu aprendi bem como funciona o framework e sua estrutura de escrita, com imports, adição de virtual users, inserção de parâmetros, inserção da rota que quer testar e o teste como um todo, podendo colocar um sleep para a inserção de VU's não ser constante. 

Além disso, algumas especifidades, como métodos da biblioteca foram bem fixados por mim.
