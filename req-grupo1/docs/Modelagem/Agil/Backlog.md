## Introdução
A metodologia ágil é amplamente utilizada no desenvolvimento de software para promover flexibilidade, eficiência e colaboração entre equipes. Dentro dessa abordagem, o backlog desempenha um papel central, organizando e priorizando requisitos, funcionalidades e tarefas de forma iterativa e incremental. No contexto do aplicativo Bluesky, o backlog foi estruturado para dividir os requisitos elicitados em temas, épicos e histórias de usuário, permitindo uma gestão clara e eficiente. Essa estrutura não apenas facilita a priorização e o acompanhamento das atividades, mas também garante alinhamento com as necessidades do cliente, entregando valor continuamente ao longo do desenvolvimento.

## Objetivo 
O objetivo deste backlog é organizar e priorizar os requisitos do aplicativo Bluesky de forma lógica e eficiente, agrupando funcionalidades relacionadas em temas e épicos. Através dessa estruturação, buscamos atender às expectativas dos usuários, oferecendo um sistema robusto e funcional, alinhado às melhores práticas de usabilidade, segurança e desempenho.

## Metodologia
A construção do backlog seguiu uma abordagem iterativa baseada nos requisitos elicitados. Foram identificados grandes agrupamentos de funcionalidades (temas), que foram divididos em épicos. Cada épico representa um conjunto de objetivos relacionados, os quais foram desmembrados em histórias de usuário para detalhar as funcionalidades específicas. Esse processo permite uma visão holística do projeto, além de possibilitar a priorização e execução incremental das tarefas. A organização final priorizou as funcionalidades mais críticas, garantindo que os entregáveis iniciais tenham maior impacto para os usuários.

## Temas 
Os requisitos elicitados foram agrupados em temas principais:

T01 - Autenticação e Configurações de Usuário

T02 - Publicações e Interações


## Épicos e Histórias de Usuário

<!-- AUTENTICACAO E CONFIGURACOES DE USUARIO -->

**ÉPICO 1.1**: Autenticação e Configurações de Usuário

US01: Eu, como usuário, desejo realizar o login no aplicativo Bluesky para acessar minha conta. (RF1)

US17: Eu, como usuário, desejo fazer log-in automático em minha conta criada agilizar o início do uso do sistema em cada sessão de uso. ([RF17](http://127.0.0.1:8000/PerfilUsuario/Tecnicas/Requisitosel/), [IS11](http://127.0.0.1:8000/PerfilUsuario/Tecnicas/Introspeccao/))

**ÉPICO 1.2**: Autenticação e Configurações de Usuário

US02: Eu, como usuário, desejo recuperar minha senha para acessar o aplicativo Bluesky em caso de esquecimento. (RF2)

**ÉPICO 1.3** : Deve ser possível editar o conteúdo do perfil

US10: Eu, como usuário, desejo editar meu perfil para mudar a aparência da minha página principal(OB10, IS12).


<!-- PUBLICACOES E INTERACOES  -->

**ÉPICO 2.1**: Publicações e Interações

US03: Eu, como usuário, desejo acessar novos conteúdos rapidamente para estar atualizado com as últimas informações da plataforma. (RF3)

**ÉPICO 2.2**: Publicações e Interações

US04: Eu, como usuário, desejo realizar postagens na plataforma para compartilhar informações e ideias com outros usuários. (RF4)

US20: Eu, como usuário, desejo fazer publicações contendo texto, imagens e vídeos para melhor me comunicar por meio dos posts. ([RF20](http://127.0.0.1:8000/PerfilUsuario/Tecnicas/Requisitosel/), [IS15](http://127.0.0.1:8000/PerfilUsuario/Tecnicas/Introspeccao/))

**ÉPICO 2.3**: Publicações e Interações

US05: Eu, como usuário, desejo editar minhas publicações já postadas para corrigir erros ou atualizar o conteúdo. (RF5)

**ÉPICO 2.4**: Publicações e Interações


US06: Eu, como usuário, desejo buscar posts relacionados ao meu interesse utilizando palavras-chave, hashtags ou filtros específicos, para encontrar conteúdos relevantes. (RF6)

US16: Eu, como usuário, desejo pesquisar publicações com filtros como autor do post, data de publicação ou popularidade, para melhorar minha experiência de busca. ([RF16](http://127.0.0.1:8000/PerfilUsuario/Tecnicas/Requisitosel/), [IS9](http://127.0.0.1:8000/PerfilUsuario/Tecnicas/Introspeccao/))

**ÉPICO 2.5**: Publicações e Interações

US07: Eu, como usuário, desejo favoritar comunidades para acessar rapidamente os conteúdos de maior interesse. (RF7)

**ÉPICO 2.6**: Criar post e compartilha-los num feed.

US8:Eu, como usuário comum do app, desejo criar uma publicação para que seja vista em um feed específico (OB8 e IS6)

**ÉPICO 2.7**: Deve ser possível ver as mensagens com outros usuários

US09: Eu, como usuário, desejo ver minhas mensagens com outro usuário para recordar um fato que foi conversado. (OB9)

US22: Eu, como usuário, desejo mandar mensagens diretas a outro usuário, caso nos sigamos mutualmente para poder me comunicar de forma privada. [RF22](http://127.0.0.1:8000/PerfilUsuario/Tecnicas/Requisitosel/), [IS19](http://127.0.0.1:8000/PerfilUsuario/Tecnicas/Introspeccao/)

**ÉPICO 2.8**: O sistema deve notificar o usuário sobre novos posts com base nos interesses e feeds personalizados configurados.

US11: Eu, como usuário, desejo receber notificações de posts relacionados ao que gosto para conhecer novas contas a seguir e ficar atualizado. (OB12, IS7 e BT3)

**ÉPICO 2.9**:O usuário deve poder salvar Posts de interesse em uma seção dedicada para consulta futura

US12: Eu, como usuário, desejo salvar posts relacionados ao que gosto para os rever quando quiser facilmente e manter nota de postagens importantes (IS3 e IS22)

**ÉPICO 2.10**: O sistema deve disponibilizar uma seção onde o usuário possa visualizar e gerenciar todas os posts salvos, com opções de ordenação por data, e/ou hashtag.

US13: Eu, como usuário, desejo gerênciar meus posts salvos relacionados ao que gosto para me organizar com o que ainda preciso ou não.(IS4)

**ÉPICO 2.11**: O sistema deve permitir que o usuário crie ou use feeds (micro fóruns de posts) de terceiros personalizados com base em critérios como tipo de post, usuários ou hashtags relacionadas.

US14: Eu, como usuário, desejo participar ou criar um feed para ter um espaço sobre um tipo de conteúdo que me relaciono. (IS5)

**ÉPICO 2.12**: O sistema deve permitir que o usuário crie ou use feeds (micro fóruns de posts) de terceiros personalizados com base em critérios como tipo de post, usuários ou hashtags relacionadas.

US14: Eu, como usuário, desejo participar ou criar um feed para ter um espaço sobre um tipo de conteúdo que me relaciono. (IS5)

<!-- Carla -->

**ÉPICO 2.13**: Publicações e Interações

US24: Eu, como usuário, desejo enviar vídeos e áudios em mensagens privadas para compartilhar conteúdos de forma mais completa e interativa. (IS21)
  
**ÉPICO 2.14**: Publicações e Interações

US25: Eu, como usuário, desejo criar, modificar e excluir minhas listas de perfis de interesse para organizar melhor minhas conexões e interações. (IS23)

**ÉPICO 2.15**: Publicações e Interações

US26: Eu, como usuário, desejo inscrever-me ou deixar de ser inscrito em listas de perfis de interesse para ter ou deixar de ter acesso às publicações desses perfis por meio de uma aba. (IS24)

**ÉPICO 2.16**: Publicações e Interações

US27: Eu, como usuário, desejo criar, modificar e excluir minhas listas de moderação para gerenciar melhor os perfis e conteúdos que preciso monitorar. (IS25)

**ÉPICO 2.17**: Publicações e Interações

US28: Eu, como usuário, desejo inscrever-me ou deixar de ser inscrito em listas de moderação para permitir ou não a interação com os perfis contidos na lista. (IS26)

**ÉPICO 2.18**: Publicações e Interações

US29: Eu, como usuário, desejo visualizar a quantidade de vezes em que minha publicação foi visualizada para entender o engajamento com o meu conteúdo. (IS27)

**ÉPICO 2.19**: Publicações e Interações   

US30: Eu, como usuário, desejo que o aplicativo me permita comunicação, entretenimento e informações atualizadas, para que eu possa me manter informado e engajado com o conteúdo.. (QT1)

**ÉPICO 2.20**

US15: Eu, como usuário, desejo interagir com postagens por meio de comentários, curtidas e respostas para me expressar sobre uma publicação. ([RF15](http://127.0.0.1:8000/PerfilUsuario/Tecnicas/Requisitosel/) [IS8](http://127.0.0.1:8000/PerfilUsuario/Tecnicas/Introspeccao/) e [IS16](http://127.0.0.1:8000/PerfilUsuario/Tecnicas/Introspeccao/) e [QT2](http://127.0.0.1:8000/PerfilUsuario/Tecnicas/Questionario/))

**ÉPICO 2.21**

US18: Eu, como usuário, desejo fixar uma publicação em seu perfil para dar destaque a publicação importante em meu perfil. ([RF18](http://127.0.0.1:8000/PerfilUsuario/Tecnicas/Requisitosel/), [IS13](http://127.0.0.1:8000/PerfilUsuario/Tecnicas/Introspeccao/))

**ÉPICO 2.22**

US19: Eu, como usuário, desejo tornar minha conta privada para permitir que apenas seguidores consigam interagir diretamente comigo. ([RF19](http://127.0.0.1:8000/PerfilUsuario/Tecnicas/Requisitosel/), [IS14](http://127.0.0.1:8000/PerfilUsuario/Tecnicas/Introspeccao/))

**ÉPICO 2.23**
US21: Eu, como usuário, desejo visualizar publicações de diferentes idiomas traduzidas para meu idioma principal dentro do aplicativo para compreender usuários que falam diferentes línguas. ([RF21](http://127.0.0.1:8000/PerfilUsuario/Tecnicas/Requisitosel/), [IS18](http://127.0.0.1:8000/PerfilUsuario/Tecnicas/Introspeccao/))

**ÉPICO 2.24**
US23: Eu, como usuário, desejo participar de grupos de mensagens privadas para poder me comunicar de forma privada com um grupo restrito de outros usuários. ([RF23](http://127.0.0.1:8000/PerfilUsuario/Tecnicas/Requisitosel/), [IS20](http://127.0.0.1:8000/PerfilUsuario/Tecnicas/Introspeccao/))

<!--  -->

## Tabela com todos os épicos
A tabela 1 organiza todos os épicos 

<center>
<font size="3"><b>Tabela 1:</b> Backlog </font>

| Tema | Épico | História de Usuário | Prioridade | Rastreabilidade |
|:----:|:-----:|:------------------:|:----------:|:------:|
| T01 - Autenticação e Configurações de Usuário | Épico 1.1 | [US01](../../Modelagem/Agil/historia.md/#US01) | Alta | [OB1](../../PerfilUsuario/Tecnicas/Observacao.md), [IS1](../../PerfilUsuario/Tecnicas/Introspeccao.md), [IS10](../../PerfilUsuario/Tecnicas/Introspeccao.md) |
| T01 - Autenticação e Configurações de Usuário | Épico 1.2 | [US02]() | Alta |  [OB2](../../PerfilUsuario/Tecnicas/Observacao.md) |
| T02 - Publicações e Interações | Épico 2.1 | [US03](../../Modelagem/Agil/historia.md/#US03) | Média | [OB3](../../PerfilUsuario/Tecnicas/Observacao.md) |
| T02 - Publicações e Interações | Épico 2.2 | [US04](../../Modelagem/Agil/historia.md/#US04) | Alta | [OB4](../../PerfilUsuario/Tecnicas/Observacao.md) |
| T02 - Publicações e Interações | Épico 2.3 | [US05](../../Modelagem/Agil/historia.md/#US05) | Alta | [OB5](../../PerfilUsuario/Tecnicas/Observacao.md), [IS17](../../PerfilUsuario/Tecnicas/Introspeccao.md) |
| T02 - Publicações e Interações | Épico 2.4 | [US06](../../Modelagem/Agil/historia.md/#US06) | Média | [OB6](../../PerfilUsuario/Tecnicas/Observacao.md), [IS2](../../PerfilUsuario/Tecnicas/Introspeccao.md) |
| T02 - Publicações e Interações | Épico 2.5 | [US07](../../Modelagem/Agil/historia.md/#US07) | Média | [OB7](../../PerfilUsuario/Tecnicas/Observacao.md) |
| T02 - Publicações e Interações | Épico 2.6 | [US08](../../Modelagem/Agil/historia.md/#US08) | Alta | [OB8](../../PerfilUsuario/Tecnicas/Observacao.md), [IS6](../../PerfilUsuario/Tecnicas/Introspeccao.md) |
| T02 - Publicações e Interações | Épico 2.7 | [US09](../../Modelagem/Agil/historia.md/#US09) | Alta | [OB9](../../PerfilUsuario/Tecnicas/Observacao.md) |
| T01 - Autenticação e Configurações de Usuário | Épico 1.3 | [US10](../../Modelagem/Agil/historia.md/#US10) | Alta | [OB10](../../PerfilUsuario/Tecnicas/Observacao.md), [IS12](../../PerfilUsuario/Tecnicas/Introspeccao.md) |
| T02 - Publicações e Interações | Épico 2.8 | [US11](../../Modelagem/Agil/historia.md/#US11) | Baixa | [OB12](../../PerfilUsuario/Tecnicas/Observacao.md), [IS7](../../PerfilUsuario/Tecnicas/Introspeccao.md), [BT3](../../PerfilUsuario/Tecnicas/Benchmarking.md) |
| T02 - Publicações e Interações | Épico 2.9 | [US12](../../Modelagem/Agil/historia.md/#US12) | Alta | [IS3](../../PerfilUsuario/Tecnicas/Introspeccao.md), [IS22](../../PerfilUsuario/Tecnicas/Introspeccao.md) |
| T02 - Publicações e Interações | Épico 2.10 | [US13](../../Modelagem/Agil/historia.md/#US13) | Média | [IS4](../../PerfilUsuario/Tecnicas/Introspeccao.md) |
| T02 - Publicações e Interações | Épico 2.11 | [US14](../../Modelagem/Agil/historia.md/#US14) | Média | [IS5](../../PerfilUsuario/Tecnicas/Introspeccao.md) |
| T02 - Publicações e Interações                  | Épico 2.20 | [US15](../../Modelagem/Agil/historia.md/#US15) | Alta       | [IS8](http://127.0.0.1:8000/PerfilUsuario/Tecnicas/Introspeccao/), [IS16](http://127.0.0.1:8000/PerfilUsuario/Tecnicas/Introspeccao/),  [QT2](http://127.0.0.1:8000/PerfilUsuario/Tecnicas/Questionario/) |
| T02 - Publicações e Interações                  | Épico 2.4  | [US16](../../Modelagem/Agil/historia.md/#US16) | Alta       | [IS9](http://127.0.0.1:8000/PerfilUsuario/Tecnicas/Introspeccao/)|
| T01 - Autenticação e Configurações de Usuário\| | Épico 1.1  | [US17](../../Modelagem/Agil/historia.md/#US17) | Alta       | [IS11](http://127.0.0.1:8000/PerfilUsuario/Tecnicas/Introspeccao/)|
| T02 - Publicações e Interações                  | Épico 2.21 | [US18](../../Modelagem/Agil/historia.md/#US18) | Média      | [IS13](http://127.0.0.1:8000/PerfilUsuario/Tecnicas/Introspeccao/)|
| T02 - Publicações e Interações                  | Épico 2.22 | [US19](../../Modelagem/Agil/historia.md/#US19) | Alta       | [IS14](http://127.0.0.1:8000/PerfilUsuario/Tecnicas/Introspeccao/)|
| T02 - Publicações e Interações                  | Épico 2.2  | [US20](../../Modelagem/Agil/historia.md/#US20) | Alta       | [IS15](http://127.0.0.1:8000/PerfilUsuario/Tecnicas/Introspeccao/)|
| T02 - Publicações e Interações                  | Épico 2.23 | [US21](../../Modelagem/Agil/historia.md/#US21) | Alta       | [IS18](http://127.0.0.1:8000/PerfilUsuario/Tecnicas/Introspeccao/)|
| T02 - Publicações e Interações                  | Épico 2.7  | [US22](../../Modelagem/Agil/historia.md/#US22) | Média      | [IS19](http://127.0.0.1:8000/PerfilUsuario/Tecnicas/Introspeccao/)|
| T02 - Publicações e Interações                  | Épico 2.24 | [US23](../../Modelagem/Agil/historia.md/#US23) | Média      | [IS20](http://127.0.0.1:8000/PerfilUsuario/Tecnicas/Introspeccao/)|
| T02 - Publicações e Interações | Épico 2.13 | [US24](../../Modelagem/Agil/historia.md/#US24) | Média | [IS21](../../PerfilUsuario/Tecnicas/Introspeccao.md) |
| T02 - Publicações e Interações | Épico 2.14 | [US25](../../Modelagem/Agil/historia.md/#US25) | Alta | [IS23](../../PerfilUsuario/Tecnicas/Introspeccao.md) |
| T02 - Publicações e Interações | Épico 2.15 | [US26](../../Modelagem/Agil/historia.md/#US26) | Alta | [IS24](../../PerfilUsuario/Tecnicas/Introspeccao.md) |
| T02 - Publicações e Interações | Épico 2.16 | [US27](../../Modelagem/Agil/historia.md/#US27) | Média | [IS25](../../PerfilUsuario/Tecnicas/Introspeccao.md) |
| T02 - Publicações e Interações | Épico 2.17 | [US28](../../Modelagem/Agil/historia.md/#US28) | Alta | [IS26](../../PerfilUsuario/Tecnicas/Introspeccao.md) |
| T02 - Publicações e Interações | Épico 2.18 | [US29](../../Modelagem/Agil/historia.md/#US29) | Baixa | [IS27](../../PerfilUsuario/Tecnicas/Introspeccao.md) |
| T02 - Publicações e Interações | Épico 2.19 | [US30](../../Modelagem/Agil/historia.md/#US30) | Alta | [QT1](../../PerfilUsuario/Tecnicas/Qualidade.md) |


<font size="3"><b>Autores:</b><a href="https://github.com/Renatinha28">Renata Quadros</a>; <a href="https://github.com/Jagaima">Davi Nobre</a>; <a href="https://github.com/ccarlaa">Carla Clementino</a>; <a href="https://github.com/Joa0V">João Ribeiro</a></font> 
</center>

## Bibliografia

> 1. 2023.2 Economia DF. Econimia DF, 2023. Disponível em: https://requisitos-de-software.github.io/2023.2-Economia-DF/. Acesso em: 15, nov. 2024.

> 2. Meu INSS, 2024.1. Disponível em: https://vitorfleonardo.github.io/2024.1-Meu-INSS/. Acesso em 16, nov. 2024.

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
            <td>14/12</td>
            <td>1.0</td>
            <td>Criação do documento e add backlogs </td>
            <td><a href="https://github.com/Renatinha28">Renata Quadros</a></td>
            <td>15/12</td>
            <td><a href="https://github.com/erteduarda">Eduarda Tavares</a></td>
        </tr>
        <tr>
            <td>14/12</td>
            <td>1.1</td>
            <td>Adição de mais 7 backlogs </td>
            <td><a href="https://github.com/Jagaima">Davi Nobre</a></td>
            <td>15/12</td>
            <td><a href="https://github.com/Renatinha28">Renata Quadros</a></td>
        </tr>
        <tr>
            <td>16/12</td>
            <td>1.2</td>
            <td>Adição dos backlogs dos requisitos de 24 ate 30 </td>
            <td><a href="https://github.com/ccarlaa">Carla Clementino</a></td>
            <td>16/12</td>
            <td><a href="https://github.com//Jagaima">Davi Nobre</a></td>
        </tr>
        <tr>
            <td>16/12</td>
            <td>1.3</td>
            <td>Adição dos itens de backlog das US de 15 a 23 </td>
            <td><a href="https://github.com/Joa0V">João Ribeiro</a></td>
            <td>17/12</td>
            <td><a href="https://github.com/Renatinha28">Renata Quadros</a></td>
        </tr>
        </tr>
    </table>
</div>