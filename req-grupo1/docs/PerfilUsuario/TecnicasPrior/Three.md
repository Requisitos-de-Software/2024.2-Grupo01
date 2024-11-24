## Introdução 
A priorização de requisitos é uma etapa fundamental no processo de desenvolvimento de software, especialmente em projetos com recursos limitados de tempo, orçamento e equipe. Este documento utiliza a técnica Three Level Scale para priorizar requisitos de forma simples e eficiente, ajudando a equipe a determinar quais funcionalidades devem receber mais atenção. A abordagem organiza os requisitos em três níveis de prioridade, promovendo clareza e alinhamento com os objetivos do projeto e expectativas dos stakeholders.

## Objetivo
O objetivo deste documento é definir as prioridades dos requisitos do sistema do Bluesky utilizando a técnica Three Level Scale, classificando-os em:
	1.	Alta prioridade: Requisitos essenciais que precisam ser implementados para o funcionamento do sistema.
	2.	Média prioridade: Requisitos importantes, mas que podem ser adiados para versões futuras.
	3.	Baixa prioridade: Requisitos desejáveis ou opcionais, implementados apenas se houver recursos disponíveis.

## Metodologia
A metodologia utilizada para a priorização dos requisitos foi a Three Level Scale, priorizando os requisitos listados na técnica de elicitação de requisitos, classificando-os em:
	1.	Alta prioridade: Requisitos essenciais que precisam ser implementados para o funcionamento do sistema.
	2.	Média prioridade: Requisitos importantes, mas que podem ser adiados para versões futuras.
	3.	Baixa prioridade: Requisitos desejáveis ou opcionais, implementados apenas se houver recursos disponíveis.

Para a criação do documento, foi levado em consideração projetos anteriores, sendo eles o Bilheteria Digital<sup>[1](#ref1)</sup> e Lichess<sup>[2](#ref2)</sup>, além do livro Software Requirements<sup>[3](#ref3)</sup>.

## Participantes
Está técnica de priorização foi feita pela integrante do grupo [Renata Quadros](https://github.com/Renatinha28) que conduziu uma reunião com uma usuária do Bluesky, Luísa. A participante foi informada dos fins de pesquisa e concordou voluntariamente em participar com o uso das informações dadas na reunião. A reunião foi realizada no dia 24/11/2024 às 15:30 horas na plataforma Teams. O vídeo é disponibilizado logo a seguir:

<iframe width="560" height="315" src="" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Requisitos Priorizados
As tabelas 1 e 2 descreve os requisitos priorizados, e sua legenda é:

- RFx: Requisito Funcional n°x
- RNFx: Requisito Não-Funcional nºx
- OBx: Requisito nºx elicitado pela observação.
- ISx: Requisito nºx elicitado pela introspecção.
- NISx: Requisito nºx elicitado pela introspecção (não funcionais). 
- QTx: Requisito nºx elicitado pelo questionário.


<center><p><b>Tabela 1:</b> Requisitos funcionais</p></center>

| Tipo | Descrição | ID | Prioridade |
| :-----: | :-------: | :------: | :--------------: |
| RF1 | Deve ser possível realizar o login | OB1 e IS1 e IS10| Alta |
| RF2 | Deve ser possível recuperar a senha no aplicativo | OB2 | Alta |
| RF3 | Deve ser possível acessar novos conteúdos rapidamente na plataforma | OB3 | Média |
| RF4 | Deve ser possível realizar postagens na plataforma| OB4 | Baixa |
| RF5 | Deve ser possível ao usuário editar suas publicações já postadas | OB5 e IS17 | Média |
| RF6 | O sistema deve permitir que o usuário faça buscas por posts relacionados ao seu interesse, usando palavras-chave, hashtags ou filtros específicos. | OB6 e IS2 | Alta |
| RF7 | Deve ser possível favoritar uma comunidade | OB7 | Baixa |
| RF8 | O usuário deve poder criar seus próprios posts ,e compartilhá-los com um feed específico ou a comunidade em geral. | OB8 e IS6 | Média |
| RF9 | Deve ser possível ver as mensagens com outros usuários | OB9 | Média |
| RF10 | Deve ser possível editar o conteúdo do perfil | OB10 e IS12 | Alta |
| RF11 | O sistema deve notificar o usuário sobre novos posts com base nos interesses e feeds personalizados configurados. | OB12, IS7 e BT3 | Baixa |
| RF12 | O usuário deve poder salvar Posts de interesse em uma seção dedicada para consulta futura. | IS3 e IS22 | Média |
| RF13 | O sistema deve disponibilizar uma seção onde o usuário possa visualizar e gerenciar todas os posts salvos, com opções de ordenação por data, e/ou hashtag | IS4 | Média |
| RF14 | O sistema deve permitir que o usuário crie ou use feeds (micro fóruns de posts) de terceiros personalizados com base em critérios como tipo de post, usuários ou hashtags relacionadas. | IS5 | Média |
| RF15 | Os usuários devem poder interagir com postagens por meio de comentários, curtidas e respostas. | IS8 e IS16 e QT2 | Média |
| RF16 | O sistema deve permitir a aplicação de filtros avançados, como autor do post, data de publicação ou popularidade, para melhorar a experiência de busca. | IS9 | Alta |
| RF17 | O usuário deve ser capaz de fazer log-in/log-in automático em sua conta criada | IS11 | Alta |
| RF18 | O usuário deve poder fixar uma publicação em seu perfil dando-a destaque em seu perfil	| IS13 | Média |
| RF19 | O usuário deve poder tornar sua conta privada, restringindo a interação de outros usuários ao permitir que apenas seguidores consigam interagir diretamente com ele | IS14 | Alta |
| RF20 | Deve ser possível ao usuário fazer publicações contendo texto, imagens e vídeos | IS15 | Média |
| RF21 | Deve ser possível ao usuário visualizar dentro do aplicativo publicações de diferentes idiomas traduzidas para o idioma principal definido no aplicativo | IS18 | Alta |
| RF22 | O usuário deve poder mandar mensagens diretas a outro usuário, caso se sigam mutualmente | IS19 | Média |
| RF23 | O usuário deve poder criar, ingressar, convidar e sair de grupos de mensagens diretas | IS20 | Alta |
| RF24 | O usuário deve poder mandar mídias como vídeos e áudios nas mensagens privadas | IS21 | Média |
| RF25 | O usuário deve poder criar, modificar e excluir suas listas de perfis de interesse | IS23 | Alta |
| RF26 | Caso não seja o criador da lista, o usuário deve poder inscrever-se/deixar de ser inscrito em listas de perfis de interesse para ter/deixar de ter acesso às publicações desses perfis por uma aba | IS24 | Alta |
| RF27 | O usuário deve poder criar, modificar e excluir suas listas de moderação | IS25 | Média |
| RF28 | Caso não seja o criador da lista, o usuário deve poder inscrever-se/deixar de ser inscrito em listas de moderação para não permitir/permitir a interação com os perfis contidos na lista | IS26 | Alta |
| RF29 | O usuário deve poder visualizar a quantidade de vezes em que sua publicação foi visualizada | IS27 | Baixa |
| RF30 | O aplicativo deve permitir ao usuário a comunicação, entreterimento e informações atualizadas | QT1 | Alta |
| RF31 | O aplicativo deve permitir linkar para outras pessoas sem o sufixo ".bsky.social" | QT3 | Baixa |
| RF32 | O aplicativo deve permitir Trending Topics | QT5 | Média |
| RF33 | O aplicativo deve permitir o sistema de tags fora do post | QT4 | Baixa |
| RF34 | O usuário deve poder criar comunidades ou grupos privados. | BT1 | Baixa |
| RF35 | O usuário deve poder configurar a privacidade das postagens | BT2 | Alta |
| RF36 | O sistema deve enviar notificações sobre eventos em tempo real. | BT4 | Baixa |
| RF37 | O usuário deve poder acessar métricas sobre o alcance de suas postagens | BT5 | Média |

<p align="center"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></p> 



<center><p><b>Tabela 2:</b> Requisitos não funcionais</p></center>

| Tipo | Descrição | ID | Prioridade |
| :-----: | :-------: | :------: | :--------------: |
| RNF1 | Deve ser possível personalizar o aplicativo (dark mode, idiomas…) | OB11 | Baixa |
| RNF2 | O sistema deve processar buscas e carregar feeds personalizados rapidamente, mesmo com grandes volumes de dados, garantin do uma experiência fluida para o usuário. | NIS1 e BT7 | Alta |
| RNF3 | O sistema deve ser capaz de crescer e suportar um número crescente de usuários e posts sem comprometer o desempenho. | NIS2, NIS13 e BT7 | Alta |
| RNF4 | Todos os dados sensíveis, como informações de login e reviews salvas, devem ser protegidos por criptografia. O sistema deve implementar autenticação segura e proteger contra ataques como SQL injection e XSS. | NIS3 | Alta |
| RNF5 | A interface do usuário deve ser intuitiva e fácil de usar, com opções bem definidas para buscar, salvar e visualizar postagens. O design deve ser centrado no usuário e acessível a diferentes perfis de idade. | NIS4 | Média |
| RNF6 | O sistema deve ter alta disponibilidade, operando continuamente com mínimas interrupções e implementando redundância de servidores para garantir estabilidade. | NIS5 | Alta |
| RNF7 | O sistema deve ser compatível com dispositivos móveis modernos, oferecendo uma interface responsiva e acessível em diferentes tamanhos de tela. | NIS6, BT9 | Alta |
| RNF8 | O sistema deve permitir que o usuário personalize seus feeds e notificações facilmente, com opções para ajustar preferências de conteúdo e formato. | NIS7 | Média |
| RNF9 | O aplicativo deve ter um tempo de resposta para cada ação menor que 3 segundos | NIS9 | Alta |
| RNF10 | O aplicativo deve ter interface intuitiva para usuários frequentes de redes sociais, levando até 15min para que se familiarizem com feeds, listas. | NIS10, BT10 | Baixa |
| RNF11 | O aplicativo deve prover ambientes saudáveis aos seus usuários, os protegendo de conteúdos nocivos |  NIS11 | Média |
| RNF12 | O aplicativo deve ser transparente quanto ao uso dos dados de seus usuários, independente de onde se encontra, o usuário deve estar a menos de 5 cliques dos Termos de Serviço e Política de Privacidade | NIS12 | Alta |
| RNF13 | O aplicativo deve indicar ao usuário quando uma ação não pode ser concluída e o motivo para isso | NIS14 | Alta |
| RNF14 | O aplicativo deve ter uma aparência agradavél ao usuário | QT6 | Média | 
| RNF15 | A plataforma deve garantir transparência nos algoritmos de recomendação | QT6 | Média |
| RNF16 | O sistema deve proteger os dados dos usuários de acordo com a LGPD. | BT8 | Alta |

<p align="center"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></p> 

## Referências Bibliográficas 
> 1. <a id="ref1"></a> Bilheteria Digital, 2024. Disponível em:https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/. Acesso em 20, nov. 2024.

> 2. <a id="ref2"></a> Linchess, 2022. Disponível em: https://requisitos-de-software.github.io/2022.2-Lichess/. Acesso em: 20, nov. 2024.

> 3. <a id="ref3"></a> Software Requirements. In: WIEGERS, Karl E.; BEATTY, Joy. Software Requirements. 3. ed. [S. l.]: Microsoft Press, 2013. cap. 16, p. 313-329. ISBN 0735679665.


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
            <td>24/11</td>
            <td>1.0</td>
            <td>Adicionando priorização.</td>
            <td><a href="https://github.com/Renatinha28">Renata Quadros</a></td>
            <td>24/11</td>
            <td><a href="https://github.com/erteduarda">Eduarda</a></td>
        </tr>
    </table>
</div>