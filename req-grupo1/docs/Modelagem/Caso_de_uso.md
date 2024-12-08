## Introdução
O Caso de Uso é um artefato essencial na Engenharia de Requisitos, utilizado para capturar e descrever as interações entre os usuários (ou atores) e o sistema em desenvolvimento. Ele é uma ferramenta poderosa para compreender e documentar como o sistema deve atender a uma funcionalidade específica, descrevendo cenários de uso de maneira estruturada. Por sua clareza e capacidade de representar situações reais, o Caso de Uso se tornou um recurso indispensável em projetos de software, promovendo o alinhamento entre as expectativas dos stakeholders e o desenvolvimento técnico.

## Objetivo
O objetivo do Caso de Uso é garantir que os requisitos do sistema sejam representados de maneira detalhada, considerando os fluxos principais, alternativos e de exceção. Esse artefato busca fornecer uma visão centrada no usuário, descrevendo as ações realizadas pelos atores e as respostas esperadas do sistema. Dessa forma, ele assegura que o sistema desenvolvido atenda às necessidades dos usuários, sirva como referência para as equipes de desenvolvimento e testes, e facilite a rastreabilidade dos requisitos ao longo do ciclo de vida do projeto.

## Metodologia
A construção de um Caso de Uso segue uma metodologia estruturada que envolve as seguintes etapas:

 **1. Identificação do Caso de Uso:**
Definir uma funcionalidade específica do sistema que será descrita, determinando quais atores interagem com o sistema.

 **2. Descrição dos Atores e Pré-condições:**
Identificar os usuários ou sistemas externos que interagem com a funcionalidade e listar as condições que devem ser atendidas antes do início do caso.

 **3. Modelagem dos Fluxos:**
Elaborar o fluxo básico, descrevendo as etapas principais que representam o sucesso da interação, e os fluxos alternativos, que cobrem variações no processo. Além disso, mapear possíveis fluxos de exceção, que tratam falhas ou problemas durante a execução.

 **4. Definição de Pós-condições:**
Especificar os resultados esperados após a execução bem-sucedida ou falha do caso de uso.

 **5. Validação e Revisão:**
Apresentar o Caso de Uso aos stakeholders e realizar revisões para garantir que ele esteja completo, claro e alinhado às expectativas do projeto.

Essa metodologia assegura que os Casos de Uso sejam desenvolvidos de forma consistente, garantindo sua aplicabilidade em todas as etapas do ciclo de desenvolvimento do software.
## Diagrama de Casos de Uso

A figura 1 representa o diagrama de casos de uso do Bluesky com as  funcionalidades trabalhadas.
<center><p><b>Figura 1:</b> Diagrama de Caso de Uso </p></center>

<figure markdown="span">
  ![nome_da_imagem](../assets/images/diagramacasodeuso.png){ width="700" align="center" }
  <figcaption><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></figcaption>
</figure>

## Especialização dos casos de uso

A tabela 1 mostra as especializações realizadas e o integrante responsável por cada uma.

<center>
<font size="3"><b>Tabela 1:</b> Integrantes responsáveis por cada especialização</font>

|                Integrante                |                Especialização do Caso de Uso                 |
| :--------------------------------------: | :----------------------------------------------------------: |
|   [Carla](https://github.com/ccarlaa)    |   [Visualização de Trending Topics](#visualizacao0)                              |
| [Eduarda](https://github.com/erteduarda) | [Quantidade de visualizações em publicações](#visualizacao1) |
|  [João Vitor](https://github.com/Joa0V)  |         [Criar grupo de mensagem direta](#grupo1)            |
|  [Davi](https://github.com/Jagaima)      |                  [Salvar Post](#salvos1)                     |
| [Renata](https://github.com/Renatinha28) |              [Editar uma publicação](#edição1)               |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

<a id="visualizacao0"></a>
### UC01 - Visualização de Trending Topics


A tabela abaixo descreve a especificação do caso de uso **"Visualização de Trending Topics"**.  Foi feito pela integrante [Carla](https://github.com/ccarlaa).

<center>
<font size="3"><b>Tabela 2:</b> Visualização de Trending Topics</font>

| **UC01**                     | **Descrição**                                                                 |
|-------------------------------|-------------------------------------------------------------------------------|
| **Data da criação**          | 08/12                                                                          |
| **Rastreabilidade**          | [RF32](../PerfilUsuario/Tecnicas/Requisitosel.md/#requisitos-elicitados)<br>[QT5](https://requisitos-de-software.github.io/2024.2-Bluesky/PerfilUsuario/Tecnicas/Questionario/)                                                                     |
| **Atores**                   | Usuários do Bluesky                                                            |
| **Ação**                     | O usuário visualiza os trending topics da rede social                         |
| **Pré-condições**            | O usuário deve estar logado no Bluesky                                         |
| **Fluxo básico**             | 1. O usuário efetua o login no Bluesky<br>2. O usuário acessa a seção de trending topics<br>3. Os trending topics são exibidos na interface            |
| **Fluxos alternativos**      | 1. O usuário efetua o login no Bluesky<br>2. O usuário busca os trending topics em uma categoria específica<br>3. Os trending topics dessa categoria são exibidos  |
| **Fluxo de exceção**         | 1. O usuário efetua o login no Bluesky<br>2. O sistema não consegue carregar os trending topics devido a uma falha (por exemplo, falta de conexão)<br>3. O sistema exibe uma mensagem de erro informando o problema<br>4. O usuário pode tentar novamente após restabelecer a conexão |
| **Pós-condições**            | O usuário visualiza os trending topics disponíveis no Bluesky                 |
| **Autor**                    | [Carla Clementino](https://github.com/ccarlaa)                                                                     |

<font size="3"><b>Autor:</b> <a href="https://github.com/ccarlaa">Carla Clementino</a></font> 
</center>

<a id="visualizacao1"></a>

### UC02 - Quantidade de visualizações em publicações
A tabela 3 descreve a especificação do caso de uso "Quantidade de visualizações em publicações". Foi feito pela integrante [Eduarda](https://github.com/erteduarda).

<center>
<font size="3"><b>Tabela 3:</b> Especialização: quantidade de visualizações em publicações </font>

|        UC02         |                                                                                                                                                                        Descrição                                                                                                                                                                        |
| :-----------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|   Data da criação   |                                                                                                                                                                          06/12                                                                                                                                                                          |
|   Rastreabilidade   |                                                                           [RF5](https://requisitos-de-software.github.io/2024.2-Bluesky/PerfilUsuario/Tecnicas/Requisitosel/) <br> [IS27](https://requisitos-de-software.github.io/2024.2-Bluesky/PerfilUsuario/PerfilUser/)                                                                            |
|       Atores        |                                                                                                                                                                   Usuários do Bluesky                                                                                                                                                                   |
|        Ação         |                                                                                                                                       O usuário visualiza a quantidade de vezes que uma publicação sua foi vista                                                                                                                                        |
|    Pré-condições    |                                                                                                                                                   Possuir pelo menos uma publicação feita no Bluesky                                                                                                                                                    |
|    Fluxo básico     |                                                                        O usuário efetua o login no Bluesky <br> O usuário entra em seu perfil pessoal <br> O usuário localiza uma publicação no perfil <br> O número de visualizações é exibido ao lado ou abaixo da publicação                                                                         |
| Fluxos alternativos |                                                                                        O usuário efetua o login no Bluesky <br> O usuário acessa uma publicação específica diretamente <br> O número de visualizações é exibido ao lado ou abaixo da publicação                                                                                         |
|  Fluxo de exceção   | O usuário efetua o login no Bluesky <br> O usuário tenta acessar seu perfil ou uma publicação <br> O sistema não consegue carregar o número de visualizações devido a uma falha (por exemplo, falta de conexão) <br> O sistema exibe uma mensagem de erro informando o problema <br> O usuário pode tentar novamente quando a conexão for restabelecida |
|    Pós-condições    |                                                                                                                            O usuário visualiza o número de visualizações da publicação no perfil ou na página da publicação                                                                                                                             |

<font size="3"><b>Autor:</b> <a href="https://github.com/erteduarda">Eduarda Tavares</a></font> 
</center>
<a id="salvos1"></a>

### UC03 - Salvar Post

A tabela 4 descreve a especificação do caso de uso "Salvar Post". Foi feito pelo integrante [Davi](https://github.com/Jagaima).

<center>
<font size="3"><b>Tabela 4:</b> Salvar Post </font>

| **UC03**           | **Descrição**                                                                                                                                                                                                                                     |
|---------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Data da criação** | 06/12                                                                                                                                                                                                                                           |
| **Rastreabilidade** | [RF6](https://requisitos-de-software.github.io/2024.2-Bluesky/PerfilUsuario/Tecnicas/Requisitosel/), [IS28](https://requisitos-de-software.github.io/2024.2-Bluesky/PerfilUsuario/PerfilUser/)                                                   |
| **Atores**          | Usuários do Bluesky                                                                                                                                                                                                                              |
| **Ação**            | O usuário salva uma publicação em sua lista de "Itens Salvos" para acesso futuro                                                                                                                                                                 |
| **Pré-condições**   | O usuário deve estar logado no Bluesky e visualizar uma publicação válida                                                                                                                                                                        |
| **Fluxo básico**    | 1. O usuário efetua login no Bluesky. <br> 2. O usuário localiza uma publicação no feed ou perfil. <br> 3. O sistema exibe a opção de "Salvar". <br> 4. O usuário clica na opção de "Salvar". <br> 5. O sistema adiciona a publicação à lista de "Itens Salvos". <br> 6. O sistema exibe confirmação da operação. |
| **Fluxos alternativos** | 1. O usuário efetua login no Bluesky. <br> 2. O usuário acessa diretamente uma publicação específica. <br> 3. O sistema exibe a opção de "Salvar". <br> 4. O usuário clica na opção de "Salvar". <br> 5. O sistema adiciona a publicação à lista de "Itens Salvos". <br> 6. O sistema exibe uma confirmação da operação. |
| **Fluxo de exceção** | 1. O usuário clica em "Salvar" em uma publicação. <br> 2. O sistema tenta processar a operação, mas ocorre uma falha (por exemplo, falta de conexão). <br> 3. O sistema exibe uma mensagem de erro informando o problema. <br> 4. O sistema não adiciona a publicação à lista de "Itens Salvos". |
| **Pós-condições**   | O item é adicionado com sucesso à lista de "Itens Salvos" do usuário, disponível para consulta futura       

<font size="3"><b>Autor:</b> <a href="https://github.com/Jagaima">Davi Nobre</a></font> 
</center>

<a id="grupo1"></a>

### UC04 - Criar grupo de mensagem direta

<center>
<font size="3"><b>Tabela 5:</b> Especialização: Criar grupo de mensagem direta </font>

| UC04                | Descrição                                                                                                                                                                         |
| :------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Data da criação**     | 07/12                                                                                                                                                                             |
 **Rastreabilidade**      | [RF23](../PerfilUsuario/Tecnicas/Requisitosel.md/#requisitos-elicitados) <br> [IS20](../PerfilUsuario/Tecnicas/Introspeccao.md/#requisitos-funcionais-1)                     |                            
| **Atores**              | Usuário comum do Bluesky                                                                                                                                                          |
| **Ação**                | O usuário cria um novo grupo de mensagem direta                                                                                                                                   |
| **Pré-condições**       | O usuário já deve ter efetuado o log-in no sistema                                                                                                                                |
| **Fluxo básico**        | 1. O usuário clica no botão 'Chat' na barra lateral<br>2. O sistema apresenta a página de Chats<br>3. O usuário clica no botão 'Novo chat'<br>4. O sistema apresenta as opções 'Chat' e 'Chat em grupo'<br>5. O usuário seleciona a opção 'Chat em grupo'<br>6. O sistema apresenta um pop-up para inserção do nome do grupo<br>7. O usuário define o nome do grupo de mensagem direta<br>8. O sistema apresenta um pop-up com uma lista de perfis para seleção dos  participantes do grupo<br>9. O usuário clica no botão 'Adicionar' relativo aos perfis que participarão do grupo<br>10. O sistema apresenta uma mensagem a cada adição<br>11. O usuário clica no botão 'Salvar'<br>12. O usuário finaliza a criação do grupo de mensagem |
| **Fluxos alternativos** | No passo "8. O sistema apresenta um pop-up para seleção dos perfis que participarão do grupo", caso o usuário não<br> seja seguido mutualmente por outro usuário:<br>	1.1 O sistema apresenta uma mensagem indicando a falta de seguidores mútuos<br>	1.2 O usuário clica no botão 'Perfil' na barra lateral<br>	1.3 O sistema apresenta a página do perfil do usuário<br>	1.4 O usuário clica no botão 'seguidores'<br>	1.5 O sistema apresenta a página com uma lista de seguidores do perfil do usuário<br>	1.6 O usuário clica no botão 'Seguir de volta' nos perfis de seu interesse para integrar o grupo de mensagem direta<br>	1.7 Retorno ao passo 1<br><br>No passo "9. O usuário clica no botão 'Adicionar' relativo aos perfis que participarão do grupo", que se quer a <br>participação no grupo esteja configurado para não ser adicionado diretamente nos grupos de mensagem direta:<br>	2.1 O usuário clica no botão 'Solicitar' relativo aos perfis que se quer a participarão do grupo<br>	2.2 O sistema apresenta uma mensagem a cada solicitação<br>	2.3 Retorno ao passo 9 |
| **Fluxo de Exceção**    | No passo "7. O usuário define o nome do grupo de mensagem direta", caso o nome definido não seja válido:<br>	3.1 O sistema apresenta uma mensagem indicando que o nome inserido não é válido<br>	3.2 Retorno ao passo 6<br><br>No passo "11. O usuário clica no botão 'Salvar'", caso o usuário não tenha nem adicionado nem solicitado<br> participação de ao menos um perfil:<br>	4.1 O sistema apresenta uma mensagem indicando a necessidade da adição ou solicitação de ao menos um perfil<br>	4.2 Retorno ao passo 8 |
| **Pós-condições**       | Um novo grupo de mensagem direta é apresentado na página de Chats<br>Novas notificações podem ser recebidas referentes ao grupo de mensagem direta criado                                                                                                                                                                                                    |

<font size="3"><b>Autor:</b> <a href="https://github.com/Joa0V">João Ribeiro</a></font> 
</center>

<a id="edição1"></a>

### UC05 - Editar publicação

A tabela 6 descreve a especificação do caso de uso "editar". Foi feito pela integrante [Renata](https://github.com/Renatinha28).

<center>
<font size="3"><b>Tabela 6:</b> Especialização: editar uma publicação </font>

|        UC05         |                                                                                                                                                                                                                                                                    Descrição                                                                                                                                                                                                                                                                     |
| :-----------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|   Data da criação   |                                                                                                                                                                                                                                                                      01/12                                                                                                                                                                                                                                                                       | 2024 |
|   Restreabilidade   |                                                                                                                   [RF5](https://requisitos-de-software.github.io/2024.2-Bluesky/PerfilUsuario/Tecnicas/Requisitosel/) <br> [OB5](https://requisitos-de-software.github.io/2024.2-Bluesky/PerfilUsuario/PerfilUser/) <br> [IS17](https://requisitos-de-software.github.io/2024.2-Bluesky/PerfilUsuario/Tecnicas/Introspeccao/)                                                                                                                    |
|       Atores        |                                                                                                                                                                                                                                                               Usuários do Bluesky                                                                                                                                                                                                                                                                |
|        Ação         |                                                                                                                                                                                                                                O usuário vai selecionar a opção de edição e vai editar uma publicação já postada                                                                                                                                                                                                                                 |
|    Pré-condições    |                                                                                                                                                                                                                                                            Possuir uma postagem feita                                                                                                                                                                                                                                                            |
|    Fluxo básico     |                                                                                                                                               O usuário efetua o login no Bluesky <br> O usuário entra em seu perfil pessoal <br> O usuário clica no ícone "..." em alguma postagem <br> O usuário clica na opção de "Editar" <br> O usuário edita a publicação <br> O usuário salva a edição <br>                                                                                                                                               |
| Fluxos alternativos |                                                                                                                                              O usuário efetua o login no Bluesky <br> O usuário entra em seu perfil pessoal <br> O usuário clica no ícone "..." em alguma postagem <br> O usuário clica na opção de "Editar" <br> O usuário edita a publicação <br> O usuário cancela a edição <br>                                                                                                                                              |
|  Fluxo de exceção   | O usuário efetua o login no Bluesky <br> O usuário entra em seu perfil pessoal <br> O usuário clica no ícone "..." em alguma postagem <br> O usuário clica na opção de "Editar" <br> O usuário edita a publicação <br> O usuário clica em "salvar edição" <br> O sistema tenta processar a edição mas ocorre uma falha(por exemplo, falha de conexão) <br> O sistema exibe uma mensagem de erro indicando o problema <br> O sistema armazena temporariamente a edição, caso o usuário deseje continuar a edição após a correção do problema <br> |
|    Pós-condições    |                                                                                                                                                                                                                                              O usuário tem salvo em seu perfil a publicação editada                                                                                                                                                                                                                                              |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

## Bibliográfia
> 1. Lucidchart. Diagrama de Caso de Uso UML. Disponível em: <https://www.lucidchart.com/pages/pt/diagrama-de-caso-de-uso-uml>. Acesso em: 01 nov. 2024.

> 2. Milene Serrano e Maurício Serrano. Requisitos - Aula 13. 2017. Disponível em: https://aprender3.unb.br/pluginfile.php/2972480/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf. Acesso em: 01 nov. 2024.

> 3. SOMMERVILLE, Ian. Software Engineering. 10th Edition, Pearson, 2015.

> 4. LARMAN, Craig. Applying UML and Patterns: An Introduction to Object-Oriented Analysis and Design and Iterative Development. Prentice Hall, 2004.

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
            <td>01/12</td>
            <td>1.0</td>
            <td>Criação do documento e especialização: editar publicação </td>
            <td><a href="https://github.com/Renatinha28">Renata Quadros</a></td>
            <td>06/12</td>
            <td><a href="https://github.com/erteduarda">Eduarda Tavares</a></td>
        </tr>
        <tr>
            <td>06/12</td>
            <td>1.1</td>
            <td>Ajuste do documento e especialização: quantidade de visualizações em publicações </td>
            <td><a href="https://github.com/erteduarda">Eduarda Tavares</a></td>
            <td>07/12</td>
            <td><a href="https://github.com/Jagaima">Davi Nobre</a></td>
        </tr>
        <tr>
            <td>06/12</td>
            <td>1.2</td>
            <td>caso de uso: Salvar postagem </td>
            <td><a href="https://github.com/Jagaima">Davi Nobre</a></td>
            <td>07/12</td>
            <td><a href="https://github.com/Joa0V">João Ribeiro</a></td>
        </tr>
                <tr>
            <td>07/12</td>
            <td>1.3</td>
            <td>Caso de uso: Criar grupo de mensagem direta</td>
            <td><a href="https://github.com/Joa0V">João Ribeiro</a></td>
            <td>08/12</td>
            <td><a href="https://github.com/Renatinha28">Renata Quadros</a></td>
        </tr>
        <tr>
            <td>08/12</td>
            <td>1.4</td>
            <td>Cenário: Trending Topics. </td>
            <td><a href="https://github.com/ccarlaa">Carla Clementino</a></td>
            <td>08/12</td>
            <td><a href="https://github.com/">
            </a></td>
    </table>
</div>