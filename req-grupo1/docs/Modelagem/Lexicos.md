## Introdução
O Léxico é uma ferramenta utilizada para descrever os termos específicos de uma linguagem por meio de explicações detalhadas. Na Engenharia de Requisitos, seu principal propósito é identificar palavras ou expressões que sejam relevantes ao contexto social do estudo. Cada termo registrado no léxico possui uma noção, que explica o que o termo representa, e um impacto, que descreve o efeito concreto ou as consequências que ocorrem quando o termo é colocado em prática.

## Objetivo
O objetivo da aplicação do método léxico é identificar e documentar de forma clara e consistente os termos e conceitos relevantes ao contexto de um sistema, facilitando o entendimento compartilhado entre os stakeholders e contribuindo para a definição precisa dos requisitos. Essa abordagem permite reduzir ambiguidades, alinhar expectativas e garantir que o vocabulário específico do domínio seja compreendido e utilizado corretamente durante todo o ciclo de desenvolvimento.

## Metodologia 
A metodologia para aplicação do método léxico começa com a identificação dos termos relevantes ao contexto do sistema, utilizando fontes como entrevistas com stakeholders, análise de documentos de domínio, cenários de uso e observações práticas. Em seguida, os termos são classificados com base em sua função no sistema, como verbos, substantivos ou estados. Cada termo identificado é descrito detalhadamente, incluindo uma noção, que define seu significado ou representação, e um impacto, que especifica os efeitos ou consequências associados a ele no sistema. O léxico elaborado é validado junto aos stakeholders, incorporando feedbacks para garantir que os termos sejam claros e adequados ao domínio do projeto. Durante todo o ciclo de vida do desenvolvimento, o léxico é revisado e atualizado conforme necessário, acompanhando mudanças no escopo ou requisitos. Por fim, o léxico é integrado a outras atividades, como a definição de casos de uso, especificações de requisitos e testes, servindo como uma base semântica para alinhar a comunicação entre equipes e reduzir ambiguidades. A tabela 1 serve de orientação para como os léxicos serão organizados.

<center>
<font size="3"><b>Tabela 1:</b> Modelo dos léxicos </font>

|Título|Classificação|Impacto|Noção|Dicionário|Autor| Restreabilidade | Cenário |
|:----:|:------------:|:-----:|:----:|:------:|:----:|:----:|:------:|
|Nome do léxico| Objeto/Estado/Verbo | Descrição do efeito/ocorrência/uso | Descrição de um símbolo | Sinônimo | Integrante responsável | Técnica de elicitação utilizada para identificar o requisito | Cenário utilizado para criação do léxico |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

## Léxicos 
A tabela 2 descreve a funcionalidade do léxico e o integrante responsável pela construção. Cada léxico feito foi realizado através dos cenários feitos anteriormente.

<center>
<font size="3"><b>Tabela 2:</b> Integrantes responsáveis por cada funcionalidade do léxico</font>

|                Integrante                |                   Léxico                   |
| :--------------------------------------: | :----------------------------------------: |
|   [Carla](https://github.com/ccarlaa)    |                     L01 -                      |
| [Eduarda](https://github.com/erteduarda) | L02 - Quantidade de visualizações em publicações |
|  [João Vitor](https://github.com/Joa0V)  |               L03 - Mensagem direta              |
|  [Davi](https://github.com/Jagaima)      |                 L04 - Salvar Post                |
| [Renata](https://github.com/Renatinha28) |           L05 - Editar uma publicação            |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

## Objetos
Léxico de objetos engloba as palavras que representam coisas, seres ou entidades. Os objetos podem ser concretos, como “mesa” ou “cachorro”, ou abstratos, como “amor” ou “liberdade”. A tabela 3 descreve os léxicos do tipo objeto identificados através dos cenários realizados.

<center>
<font size="3"><b>Tabela 3:</b> Léxicos : Objeto </font>

|Título|Classificação|Impacto|Noção|Dicionário|Autor| Restreabilidade | Cenário |
|:----:|:------------:|:-----:|:----:|:------:|:----:|:-----:|:-----:|
| L05 - Usuário | Objeto | O usuário pode editar suas publicações | O “usuário” é um sujeito que interage com a plataforma e com as publicações. Ele é o ente que realiza a ação de editar, mas o termo em si não expressa uma ação nem um estado, apenas um ser que utiliza o serviço. | Utilizador/Desfrutador | [Renata Quadros](https://github.com/Renatinha28)| [RF5](https://requisitos-de-software.github.io/2024.2-Bluesky/PerfilUsuario/Tecnicas/Requisitosel/) <br> [OB5](https://requisitos-de-software.github.io/2024.2-Bluesky/PerfilUsuario/PerfilUser/) <br> [IS17](https://requisitos-de-software.github.io/2024.2-Bluesky/PerfilUsuario/Tecnicas/Introspeccao/) |                [Editar publicação](../Modelagem/Cenario.md#edição)                 |    
| L05 - Publicação | Objeto | O usuário pode visualizar, editar e interagir com publicações | A “publicação” é o conteúdo criado ou compartilhado por um usuário, como textos, imagens ou vídeos | Postagem/Divulgação | [Renata Quadros](https://github.com/Renatinha28) | [RF5](https://requisitos-de-software.github.io/2024.2-Bluesky/PerfilUsuario/Tecnicas/Requisitosel/) <br> [OB5](https://requisitos-de-software.github.io/2024.2-Bluesky/PerfilUsuario/PerfilUser/) <br> [IS17](https://requisitos-de-software.github.io/2024.2-Bluesky/PerfilUsuario/Tecnicas/Introspeccao/) |                [Editar publicação](../Modelagem/Cenario.md#edição)                 |    
| L03 - Mensagem direta | Objeto | Mensagens diretas podem ser iniciadas ou silenciadas. Há também a possibilidade de sair da conversa | Comunicação entre usuários realizada por trocas de mensagens privadas, ou seja, em um canal de comunicação que apenas os integrantes de tal canal tem acesso. | Chat, conversa | [João Ribeiro]() |  [RF23](../PerfilUsuario/Tecnicas/Requisitosel.md/#requisitos-elicitados)<br>[IS20](../PerfilUsuario/Tecnicas/Introspeccao.md/#reqfunc2) | [Iniciar um grupo de mensagens diretas](../Modelagem/Cenario.md/#grupo) | 
| L01 - Trending Topics   | Objeto            | Os usuários podem visualizar os tópicos mais comentados, facilitando o acompanhamento de tendências em tempo real | Os "Trending Topics" representam os assuntos mais comentados ou populares na plataforma Bluesky durante um período de tempo. Eles ajudam os usuários a se manterem informados sobre temas em alta. | Tópicos em alta<br>Assuntos populares |  [Carla Clementino](https://github.com/ccarlaa)  | [RF32](../PerfilUsuario/Tecnicas/Requisitosel.md/#requisitos-elicitados)<br>[QT5](https://requisitos-de-software.github.io/2024.2-Bluesky/PerfilUsuario/Tecnicas/Questionario/) | [Trending Topics](../Modelagem/Cenario.md#trending)  |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

## Estados
Léxico de estados refere-se ao conjunto de palavras que expressam condições ou estados do sujeito, ao contrário de ações ou mudanças. Os verbos de estado descrevem o estado em que algo ou alguém se encontra, como sentimentos, características ou situações permanentes. A tabela 4 descrevem os léxicos encontrados do tipo estado

<center>
<font size="3"><b>Tabela 4:</b> Léxicos : Estado </font>

|Título|Classificação|Impacto|Noção|Dicionário|Autor|
|:----:|:------------:|:-----:|:----:|:------:|:----:|


<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

## Verbos

Os léxicos do tipo verbo são palavras que indicam ações ou processos. No léxico de verbos, estão presentes todos os verbos, que podem variar em tempos, modos e pessoas. A tabela 5 descreve os léxicos identificados do tipo verbo.

<center>
<font size="3"><b>Tabela 3:</b> Léxicos : Verbo </font>

|Título|Classificação|Impacto|Noção|Dicionário|Autor| Restreabilidade | Cenário |
|:----:|:------------:|:-----:|:----:|:------:|:----:|:----:|:-----:|
| L05 - Editar publicação | Verbo | Garante a atualidade e a correção das publicações | Ação que permite ao usuário modificar o conteúdo ou atributos de uma publicação previamente criada. <br> O usuário está interessado em editar uma publicação <br> O usuário edita sua publicação conforme deseja <br> O usuário confirma as edições e a publicação é mostrada no perfil conforme a edição | Edição, Correção, Ajustes em publicações | [Renata Quadros](https://github.com/Renatinha28) | [RF5](https://requisitos-de-software.github.io/2024.2-Bluesky/PerfilUsuario/Tecnicas/Requisitosel/) <br> [OB5](https://requisitos-de-software.github.io/2024.2-Bluesky/PerfilUsuario/PerfilUser/) <br> [IS17](https://requisitos-de-software.github.io/2024.2-Bluesky/PerfilUsuario/Tecnicas/Introspeccao/) |                [Editar publicação](../Modelagem/Cenario.md#edição)                 |     
| L02 - Visualizar o número de vezes que uma publicação foi vista | Verbo | Garante a transparência e acompanhamento do desempenho das publicações | Ação que permite ao usuário visualizar o número de vezes que uma publicação foi vista. <br> O usuário está interessado em verificar o alcance de sua publicação <br> O sistema exibe o contador de visualizações ao lado da publicação <br> O usuário pode acompanhar as visualizações em tempo real | Visualização, Contador de visualizações, Alcance de publicação | [Eduarda Tavares](https://github.com/erteduarda) | [RF5](https://requisitos-de-software.github.io/2024.2-Bluesky/PerfilUsuario/Tecnicas/Requisitosel/) <br> [IS27](https://requisitos-de-software.github.io/2024.2-Bluesky/PerfilUsuario/PerfilUser/)                                                  | [Quantidade de visualizações em publicações](../Modelagem/Cenario.md#visualizacao) |
| L04 - Salvar um post | Verbo | Permite ao usuário armazenar itens de interesse para acesso futuro, aumentando a conveniência e retenção. | Ação que permite ao usuário adicionar uma publicação à sua lista de itens salvos. <br> O usuário acessa a publicação ou o feed. <br> O sistema exibe a opção de salvar o item. <br> Ao salvar, o item é adicionado à lista de "Itens Salvos". <br> Uma mensagem confirma a operação. | Salvar, Publicação, Lista de Itens Salvos, Mensagem de Confirmação | [Davi Nobre](https://github.com/Jagaima) | [IS3](https://requisitos-de-software.github.io/2024.2-Bluesky/PerfilUsuario/Tecnicas/Introspeccao/) e [IS22](https://requisitos-de-software.github.io/2024.2-Bluesky/PerfilUsuario/Tecnicas/Introspeccao/)    |                                         [Salvar Post](../Modelagem/Cenario.md#salvos)                                     |  
| L01 - Visualizar Trending Topics   | Verbo             | Facilita o acompanhamento de tendências e assuntos populares em tempo real            | Ação que permite ao usuário acessar e observar os assuntos mais comentados ou populares no momento, baseando-se nas interações gerais da comunidade.      | Ver tópicos, Acompanhar tendências | [Carla Clementino](https://github.com/ccarlaa)  | [RF32](../PerfilUsuario/Tecnicas/Requisitosel.md/#requisitos-elicitados)<br>[QT5](https://requisitos-de-software.github.io/2024.2-Bluesky/PerfilUsuario/Tecnicas/Questionario/) | [Trending Topics](../Modelagem/Cenario.md#trending)      |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>


## Bibliográfia
> 1. SERRANO, Milene. Requisitos – Aula 10. 2017. Apresentação de slides. Disponível em: https://aprender3.unb.br/pluginfile.php/2972470/mod_resource/content/1/Aula%2010.pdf. Último acesso em: 01 dez. 2024.
> 2. 2023.2 Economia DF. Econimia DF, 2023. Disponível em: https://requisitos-de-software.github.io/2023.2-Economia-DF/. Acesso em: 01 dez. 2024.
> 3. Bilheteria Digital, 2023. Disponível em:https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/. Acesso em: 01 dez. 2024.
> 4. LEITE, Julio Cesar Sampaio do Prado; PAES, Luiz Antonio P. Linguistic Instruments in Requirements Engineering. 1993.
> 5. SOMMERVILLE, Ian; SAWYER, Pete. Requirements Engineering: A Good Practice Guide. 1999. Disponível em: https://www.pearson.com/us/higher-education/product/Sommerville-Requirements-Engineering-A-Good-Practice-Guide/9780201360467.html. Último acesso em: 06 dez. 2024.


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
            <td>Criação do documento e léxico: publicação </td>
            <td><a href="https://github.com/Renatinha28">Renata Quadros</a></td>
            <td>06/12</td>
            <td><a href="https://github.com/erteduarda">Eduarda Tavares</a></td>
        </tr>
        <tr>
            <td>06/12</td>
            <td>1.1</td>
            <td>Ajuste do documento e léxico: publicação </td>
            <td><a href="https://github.com/erteduarda">Eduarda Tavares</a></td>
            <td>07/12</td>
            <td><a href="https://github.com/Jagaima">Davi Nobre</a></td>
        </tr>
        <tr>
            <td>06/12</td>
            <td>1.2</td>
            <td>Léxico: Salvar postagem </td>
            <td><a href="https://github.com/Jagaima">Davi Nobre</a></td>
            <td>07/12</td>
            <td><a href="https://github.com/Joa0V">João Ribeiro</a></td>
        </tr>
        <tr>
            <td>07/12</td>
            <td>1.3</td>
            <td>Léxico: Mensagem direta</td>
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
            <td><a href="https://github.com/Renatinha28">Renata Quadros</a></td>
            </a></td>
        </tr>
    </table>
</div>