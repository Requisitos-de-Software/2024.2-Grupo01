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

Para confirmar que o usuário selecionado se enquadra no perfil traçado foi solicitado que o mesmo respondesse o formulário de perfil do usuário. As respostas estão disponibilizada na tabela 1 abaixo abaixo:

<center>
<font size="3"><b>Tabela 1:</b> Perfil do usuário observado.</font>
<table>
    <thead>
        <tr>
            <th>Pergunta</th>
            <th>Resposta</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Nome?</td>
            <td>Bruna de Araújo</td>
        </tr>
        <tr>
            <td>Qual sua idade?</td>
            <td>22 - 27</td>
        </tr>
        <tr>
            <td>Qual sua ocupação ou área de atuação?</td>
            <td>Estudante de Design</td>
        </tr>
        <tr>
            <td>Com que frequência você usa redes sociais?</td>
            <td>Alta</td>
        </tr>
        <tr>
            <td>Qual é seu nível de conforto ao utilizar tecnologias digitais?</td>
            <td>Alta</td>
        </tr>
        <tr>
            <td>Em uma escala de 1 a 5, o quanto você considera importante estar atualizado em relação a novas tecnologias?</td>
            <td>2/5</td>
        </tr>
        <tr>
            <td>Você costuma explorar todas as funcionalidades das redes sociais que usa, ou prefere um uso mais básico?</td>
            <td>Prefiro um uso mais básico</td>
        </tr>
        <tr>
            <td>Por que você utiliza redes sociais? (ex.: comunicação, entretenimento, trabalho, atualização de notícias)</td>
            <td>Comunicação, entretenimento e notícias</td>
        </tr>
        <tr>
            <td>O que você mais valoriza em uma rede social? (ex.: privacidade, liberdade de expressão, conteúdo interessante, conexão com amigos)</td>
            <td>Privacidade, conexão, conteúdo</td>
        </tr>
        <tr>
            <td>Quais são suas principais expectativas ao participar de uma nova rede social?</td>
            <td>Que haja moderação</td>
        </tr>
        <tr>
            <td>Com que frequência você compartilha conteúdo em redes sociais?</td>
            <td>Alta</td>
        </tr>
        <tr>
            <td>Em que situações você considera um conteúdo importante o suficiente para compartilhar com seus seguidores?</td>
            <td>Crimes de guerra</td>
        </tr>
        <tr>
            <td>Você prefere consumir conteúdo criado por amigos, empresas ou por perfis de entretenimento e notícias?</td>
            <td>Criado por amigos, empresas</td>
        </tr>
        <tr>
            <td>Qual o tipo de conteúdo você mais gosta de ver? (ex.: texto, vídeo, imagens)</td>
            <td>Imagem e vídeo</td>
        </tr>
        <tr>
            <td>Você possui rejeição ou aprovação a conteúdo gerado por IA?</td>
            <td>Rejeição</td>
        </tr>
        <tr>
            <td>Como você prefere interagir em redes sociais: comentando, curtindo ou compartilhando?</td>
            <td>Curtindo</td>
        </tr>
        <tr>
            <td>Você valoriza uma experiência de rede social mais personalizada ou prefere interações mais amplas e abertas?</td>
            <td>Personalizada</td>
        </tr>
        <tr>
            <td>Como você enxerga a questão da privacidade em redes sociais?</td>
            <td>4/5</td>
        </tr>
        <tr>
            <td>Quais são suas expectativas em relação ao controle do que é compartilhado sobre você?</td>
            <td>Não quero que sejam compartilhados nenhum conteúdo sobre mim sem minha prévia autorização</td>
        </tr>
        <tr>
            <td>Você utiliza redes sociais para fortalecer conexões pessoais ou para expandir sua rede profissional?</td>
            <td>Entretenimento</td>
        </tr>
        <tr>
            <td>Que tipo de feedback você espera receber nas suas postagens? (ex.: comentários, curtidas, novas conexões)</td>
            <td>Curtida</td>
        </tr>
        <tr>
            <td>Como você acredita que a Bluesky pode ajudar a alcançar seus objetivos pessoais e sociais?</td>
            <td>Fazendo amigos</td>
        </tr>
    </tbody>
</table>
<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Carla Clementino</a></font> 
</center>

Dessa forma, com base no perfil do usuário traçado para a plataforma podemos afirmar que a pessoa escolhida para realizar a observação se enquadra no perfil de usuários da plataforma.

### Entrevista 

<div style='display: flex; justify-content: center'>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/THP5Brfri_c" frameborder="0" allowfullscreen></iframe>
</div>

## Resultados

Com base na entrevista realizada a cima os seguintes requisitos, presentes na tabela 2 e 3, foram elicitados:
<center>
<font size="3"><b>Tabela 2:</b> Requisitos Funcinoais</font>
<table border="1" style="border-collapse: collapse; width: 100%;">
    <thead>
        <tr>
            <th>ID</th>
            <th>Descrição</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>RF01</td>
            <td>O sistema deve permitir que o usuário realize o login.</td>
        </tr>
        <tr>
            <td>RF02</td>
            <td>O sistema deve permitir que o usuário recupere a senha no aplicativo.</td>
        </tr>
        <tr>
            <td>RF03</td>
            <td>O sistema deve permitir acesso rápido a novos conteúdos.</td>
        </tr>
        <tr>
            <td>RF04</td>
            <td>O sistema deve permitir que o usuário realize postagens.</td>
        </tr>
        <tr>
            <td>RF05</td>
            <td>O sistema deve permitir que o usuário edite suas postagens.</td>
        </tr>
        <tr>
            <td>RF06</td>
            <td>O sistema deve permitir que o usuário pesquise comunidades.</td>
        </tr>
        <tr>
            <td>RF07</td>
            <td>O sistema deve permitir que o usuário favorite comunidades.</td>
        </tr>
        <tr>
            <td>RF08</td>
            <td>O sistema deve permitir que o usuário envie posts para outros usuários.</td>
        </tr>
        <tr>
            <td>RF09</td>
            <td>O sistema deve permitir que o usuário visualize mensagens com outros usuários.</td>
        </tr>
        <tr>
            <td>RF10</td>
            <td>O sistema deve permitir que o usuário edite o conteúdo do perfil.</td>
        </tr>
    </tbody>
</table>
<font size="3"><b>Autor:</b> <a href="https://github.com/ccarlaa">Carla Clementino</a></font> 
</center>

<center>
<font size="3"><b>Tabela 3:</b> Requisitos Não Funcinoais</font>
<table border="1" style="border-collapse: collapse; width: 100%;">
    <thead>
        <tr>
            <th>Identificação</th>
            <th>Descrição</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>RNF01</td>
            <td>O sistema deve permitir a personalização do aplicativo (modo escuro, idiomas, etc.).</td>
        </tr>
        <tr>
            <td>RNF02</td>
            <td>O sistema deve exibir notificações de forma eficiente.</td>
        </tr>
    </tbody>
</table>
<font size="3"><b>Autor:</b> <a href="https://github.com/ccarlaa">Carla Clementino</a></font> 
</center>

Além dos requisitos elicitados, foi possível realizar algumas observações: 

- O usuário teve dificuldades para redefinir a senha na plataforma. Entre os comentários feitos estão a demora para receber o código de redefinição de senha e não entender bem os feedbacks de erro da plataforma.
- Ao utilizar a plataforma, foram observados problemas de carregamento mesmo com a internet estável.
- Não foi observado a opção de editar um post.


## Referência Bibliográfica

> 1. REQUISTOS DE SOFTWARE. 2023.2-Skoob. Disponível em: https://github.com/Requisitos-de-Software/2023.2-Skoob. Acesso em: 17 nov. 2024.
> 2. REQUISTOS DE SOFTWARE. 2022.2-Grasshopper. Disponível em: https://github.com/Requisitos-de-Software/2022.2-Grasshopper. Acesso em: 17 nov. 2024.
> 3. Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1.

## :round_pushpin: Histórico de Versão 

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