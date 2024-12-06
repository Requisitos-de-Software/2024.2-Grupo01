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

## Especialização dos casos de uso

A tabela 1 mostra as especializações realizadas e o integrante responsável por cada uma.

<center>
<font size="3"><b>Tabela 1:</b> Integrantes responsáveis por cada especialização</font>

|                Integrante                |                Especialização do Caso de Uso                 |
| :--------------------------------------: | :----------------------------------------------------------: |
|   [Carla](https://github.com/ccarlaa)    |                              -                               |
| [Eduarda](https://github.com/erteduarda) | [Quantidade de visualizações em publicações](#visualizacao1) |
|    [Davi](https://github.com/Jagaima)    |                              -                               |
|  [João Vitor](https://github.com/Joa0V)  |                              -                               |
| [Renata](https://github.com/Renatinha28) |              [Editar uma publicação](#edição1)               |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

### UC01

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

### UC03

### UC04

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
            <td></td>
            <td><a href="https://github.com/"></a></td>

        </tr>
    </table>
</div>