# Teste Técnico - Programação

A cada ciclo de atividades temos que dividir as equipes de maneira otimizada, de forma que cada aluno preferencialmente não trabalhe com um colega que já trabalhou em ciclos anteriores. As equipes podem ter uma quantidade variada de membros. A cada ciclo, essa quantidade de membros pode mudar.

- **Exemplo**
    
    Nos ciclos passados, ocorreram várias equipes. Dentre elas:
    
    1. Laura, Pedro, João.
    2. Vinicius, Carlos, Maria.
    3. Leonardo, Ana, Daniela.
    4. Eduardo, Henrique, Yago.
    
    No próximo ciclo:
    
    - Laura não pode fazer equipe com Pedro, e vice-versa.
    - Laura não pode fazer equipe com João, e vice-versa.
    - Pedro não pode fazer equipe com João, e vice-versa.
    - Assim por diante…
    
    Supondo que o próximo ciclo seja de equipes de 4 membros:
    
    - Um exemplo de equipe ideal é: Laura, Carlos, Daniela, Eduardo. Nenhum desses alunos fez trabalho com os outros membros da equipe antes.
    - Um exemplo de equipe que queremos evitar é: Pedro, Vinicius, Yago e Maria. Pois Vinicius e Maria já trabalharam juntos antes.

### Seu objetivo

Para tornar o tempo de planejamento dos mentores mais produtivo e evitar ter que passar horas achando as combinações perfeitas de cada equipe, te contratamos para otimizar o processo de divisão de equipes para cada ciclo! Depois da sua proposta de solução, temos a esperança de criar o máximo de equipes ideais possíveis em todos os ciclos de atividades ao longo da jornada de aprendizado dos alunos.

- **Dados**
    
    Esses são os dados da turma, estamos nos preparando para o terceiro ciclo que será feito em duplas, com pair programming.
    
    ```jsx
    {
        "ciclo1" : [
            [
                "Laura", 
                "Pedro", 
                "João",
                "Vinicius"
            ],
            [
                "Carlos", 
                "Maria",
                "Leonardo", 
                "Ana"
            ],
            [
                "Daniela",
                "Marcos",
                "Wesley",
                "Luiza"
            ],
            [
                "Daiane",
                "Felipe",
                "Teodoro",
                "Helena"
            ],
            [
                "Natalia",
                "Beatriz",
                "Eduardo",
                "Caio"
            ]
        ],
        "ciclo2" : [
            [
                "Teodoro",
                "Daiane",
                "Luiza"
            ],
            [
                "Carlos",
                "João",
                "Helena"
            ],
            [
                "Daniela",
                "Pedro",
                "Caio"
            ],
            [
                "Leonardo",
                "Maria",
                "Laura"
            ],
            [
                "Beatriz",
                "Marcos",
                "Vinicius"
            ],
            [
                "Natalia",
                "Felipe",
                "Eduardo"
            ],
            [
                "Ana",
                "Wesley"
            ]
        ]
    }
    ```
    

### Requisitos

A solução deve:

- ser um programa ou a modelagem de um programa, em qualquer linguagem;
- resolver pelo menos parcialmente a demanda;
- estar documentada.

Como esses requisitos serão cumpridos, você que decide. Você não precisa se prender a nenhuma solução que já exista.
[Documentação](https://github.com/jbrun0r/Test-Tecnico-Apple-Academy/wiki/Documenta%C3%A7%C3%A3o) 

