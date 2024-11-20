## Introdução

O desenvolvimento de sistemas de software requer a identificação clara e precisa de requisitos. Para tanto, o processo de elicitação é fundamental, permitindo o levantamento de necessidades e expectativas dos usuários e stakeholders. Este trabalho tem como foco o aplicativo BlueSky, uma rede social social de microblogue descentralizada.
Entre os métodos disponíveis para elicitação de requisitos, optamos pelo método de observação devido à sua capacidade de capturar comportamentos e interações dos usuários no ambiente real, permitindo identificar requisitos explícitos e implícitos que influenciam a experiência do usuário.

## Objetivo

Este estudo tem como objetivo identificar requisitos funcionais e não funcionais para o aplicativo BlueSky a partir da análise de interações dos usuários. A observação será utilizada para compreender como os usuários utilizam o aplicativo, quais funcionalidades são mais valorizadas e quais dificuldades ou limitações enfrentam.

## Metodologia 

A metodologia de observação para elicitação de requisitos consiste em analisar como usuários realizam suas atividades no ambiente real de trabalho, identificando necessidades e problemas de forma prática. Essa abordagem permite coletar informações implícitas, que nem sempre são verbalizadas, e compreender melhor o contexto de uso do sistema a ser desenvolvido.

## Execução

A observação será conduzida de forma direta, com foco nas interações dos usuários ao utilizarem o aplicativo BlueSky.

**Observação direta**: A equipe de análise acompanhará os usuários em tempo real enquanto utilizam o aplicativo.


### Perfil do Usuária Observado:

Para confirmar que o usuário selecionado se enquadra no perfil traçado foi solicitado que o mesmo respondesse o formulário de perfil do usuário. As respostas estão disponibilizada na tabela () abaixo abaixo:

| Pergunta | Resposta |
|---------------|---------------|
| Nome ? | Bruna de Araújo |
| Qual sua idade ? | 22 - 27 |
| Qual sua ocupação ou área de atuação? |   Estudante de Design |
| Com que frequência você usa redes sociais? |  Alta  |
| Qual é seu nível de conforto ao utilizar tecnologias digitais? |  Alta  |
| Em uma escala de 1 a 5, o quanto você considera importante estar atualizado em relação a novas tecnologias? |  2/5  |
| Você costuma explorar todas as funcionalidades das redes sociais que usa, ou prefere um uso mais básico? |  Prefiro um uso mais básico  |
| Por que você utiliza redes sociais? (ex.: comunicação, entretenimento, trabalho, atualização de notícias) |  Comunicação, entendimento e notícias  |
| O que você mais valoriza em uma rede social? (ex.: privacidade, liberdade de expressão, conteúdo interessante, conexão com amigos) |  Privacidade, conexão, conteúdo   |
| Quais são suas principais expectativas ao participar de uma nova rede social? |  Que haja moderação    |
| Com que frequência você compartilha conteúdo em redes sociais? |  Alta  |
| Em que situações você considera um conteúdo importante o suficiente para compartilhar com seus seguidores? |  Crimes de guerra  |
| Você prefere consumir conteúdo criado por amigos, empresas ou por perfis de entretenimento e notícias? |  Criado por amigos , empresas  |
| Qual o tipo de conteúdo você mais gosta de ver? (ex.: texto, vídeo, imagens) |  Imagem e vídeo   |
| Você possui rejeição ou aprovação a conteúdo gerado por IA? |  Rejeição  |
| Como você prefere interagir em redes sociais: comentando, curtindo ou compartilhando? |  Curtindo  |
| Você valoriza uma experiência de rede social mais personalizada ou prefere interações mais amplas e abertas? |  Personalizada  |
| Como você enxerga a questão da privacidade em redes sociais? |  4/5  |
| Quais são suas expectativas em relação ao controle do que é compartilhado sobre você? |  Não quero que sejam compartilhado nenhum conteúdo sobre mim sem minha prévia autorização   |
| Você utiliza redes sociais para fortalecer conexões pessoais ou para expandir sua rede profissional? |  Entrenimento  |
| Que tipo de feedback você espera receber nas suas postagens? (ex.: comentários, curtidas, novas conexões) |  Curtida  |
| Como você acredita que a Bluesky pode ajudar a alcançar seus objetivos pessoais e sociais? |  Fazendo amigos  |

<p align="center">Tabela 1: Perfil do usuário observado. Autor: <a href="https://github.com/Renatinha28">Carla Clementino</a>.</p> 

Dessa forma, com base no perfil do usuário traçado para a plataforma podemos afirmar que a pessoa escolhida para realizar a observação se enquadra no perfil de usuários da plataforma.

### Entrevista 

<div style='display: flex; justify-content: center'>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/THP5Brfri_c" frameborder="0" allowfullscreen></iframe>
</div>

## Resultados

Com base na entrevista realizada a cima os seguintes requisitos, presentes na tabela 2, foram elicitados:

| **Identificação** | **Descrição**                                         |
|-------------------|-----------------------------------------------------|
| OB01             | Deve ser possível realizar o login                   |
| OB02             | Deve ser possível recuperar a senha no aplicativo    |
| OB03             | Deve ser possível acessar novos conteúdos rapidamente na plataforma |
| OB04             | Deve ser possível realizar postagens na plataforma   |
| OB05             | Deve ser possível editar um post da plataforma       |
| OB06             | Deve ser possível pesquisar uma comunidade           |
| OB07             | Deve ser possível favoritar uma comunidade           |
| OB08             | Deve ser possível enviar um post para outro usuário  |
| OB09             | Deve ser possível ver as mensagens com outros usuários |
| OB10             | Deve ser possível editar o conteúdo do perfil        |
| OB11             | Deve ser possível personalizar o aplicativo (dark mode, idiomas…) |
| OB12             | Deve ser possível ver as notificações                |

<p align="center">Tabela 2: Requisitos Elicitados. Autor: <a href="https://github.com/Renatinha28">Carla Clementino</a>.</p> 

Além dos requisitos elicitados, foi possível realizar algumas observações: 

- O usuário teve dificuldades para redefinir a senha na plataforma. Entre os comentários feitos estão a demora para receber o código de redefinição de senha e não entender bem os feedbacks de erro da plataforma.
- Ao utilizar a plataforma, foram observados problemas de carregamento mesmo com a internet estável.
- Não foi observado a opção de editar um post.


## Referência Bibliográfica

> 1. REQUISTOS DE SOFTWARE. 2023.2-Skoob. Disponível em: https://github.com/Requisitos-de-Software/2023.2-Skoob. Acesso em: 17 nov. 2024.
> 2. REQUISTOS DE SOFTWARE. 2022.2-Grasshopper. Disponível em: https://github.com/Requisitos-de-Software/2022.2-Grasshopper. Acesso em: 17 nov. 2024.
> 3. Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1.

## Histórico de Versão 

<div align="center">
    <table>
        <tr>
            <th>Data</th>
            <th>Versão</th>
            <th>Descrição</th>
            <th>Autor</th>
            <th>Data da Revisão</th>
            <th>Revisor</th>
        </tr>
        <tr>
            <td>17/11</td>
            <td>1.0</td>
            <td>Criação do documento</td>
            <td><a href="https://github.com/ccarlaa">Carla Clementino</a></td>
            <td>20/11</td>
            <td><a href="https://github.com/Renatinha28">Renata Quadros</a></td>
        </tr>
    </table>
</div>