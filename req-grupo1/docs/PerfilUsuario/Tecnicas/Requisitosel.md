## Introdução
A engenharia de requisitos desempenha um papel crucial no sucesso de qualquer projeto de software, sendo responsável por identificar, documentar e gerenciar as necessidades e expectativas das partes interessadas. Este documento tem como finalidade consolidar todos os requisitos elicitados do Bluesky, utilizando um conjunto diversificado de técnicas de elicitação. 

## Objetivo 
O objetivo deste documento é apresentar os requisitos levantados através das técnicas de elicitação de requisitos, incluindo questionário, brainstorming, introspecção e observação. Essa compilação busca assegurar que todas as necessidades identificadas sejam documentadas de forma clara e organizada.

## Metodologia
Para alcançar os objetivos propostos, foram aplicadas as seguintes técnicas de elicitação de requisitos:
	1.	Questionário: Um conjunto de perguntas estruturadas foi enviado às partes interessadas para coletar informações detalhadas sobre suas expectativas e necessidades em relação ao sistema.

	2.	Brainstorming foi realizada uma reunião com stakeholders para estimular a geração de ideias e identificar novos requisitos em um ambiente colaborativo.

	3.	Introspecção: A análise individual foi realizada por membros da equipe para identificar requisitos com base em sua experiência e compreensão do domínio.

	4.	Observação: Foram realizadas sessões de acompanhamento das atividades reais do usuário, a fim de identificar requisitos implícitos e contextuais que poderiam não ser explicitados diretamente.

Os dados coletados foram analisados e organizados de forma estruturada neste documento, assegurando consistência, rastreabilidade e alinhamento com os objetivos do projeto.

## Requisitos Elicitados
As tabelas 1 e 2 descreve os requisitos elicitados, e sua legenda é:

- RFx: Requisito Funcional n°x
- RNFx: Requisito Não-Funcional nºx
- OBx: Requisito nºx elicitado pela observação.
- ISx: Requisito nºx elicitado pela introspecção.
- NISx: Requisito nºx elicitado pela introspecção (não funcionais). 
- QTx: Requisito nºx elicitado pelo questionário.
- BTx: Requisito nºx elicitado pelo Brainstorming.


<center><p><b>Tabela 1:</b> Requisitos funcionais</p></center>

| Tipo | Descrição | ID | 
| :-----: | :-------: | :------: | 
| RF1 | Deve ser possível realizar o login | OB1 e IS1 e IS10| 
| RF2 | Deve ser possível recuperar a senha no aplicativo | OB2 | 
| RF3 | Deve ser possível acessar novos conteúdos rapidamente na plataforma | OB3 | 
| RF4 | Deve ser possível realizar postagens na plataforma| OB4 | 
| RF5 | Deve ser possível ao usuário editar suas publicações já postadas | OB5 e IS17 | 
| RF6 | O sistema deve permitir que o usuário faça buscas por posts relacionados ao seu interesse, usando palavras-chave, hashtags ou filtros específicos. | OB6 e IS2 | 
| RF7 | Deve ser possível favoritar uma comunidade | OB7 | 
| RF8 | O usuário deve poder criar seus próprios posts ,e compartilhá-los com um feed específico ou a comunidade em geral. | OB8 e IS6 | 
| RF9 | Deve ser possível ver as mensagens com outros usuários | OB9 | 
| RF10 | Deve ser possível editar o conteúdo do perfil | OB10 e IS12 | 
| RF11 | O sistema deve notificar o usuário sobre novos posts com base nos interesses e feeds personalizados configurados. | OB12, IS7, BT3 | 
| RF12 | O usuário deve poder salvar Posts de interesse em uma seção dedicada para consulta futura. | IS3 e IS22 | 
| RF13 | O sistema deve disponibilizar uma seção onde o usuário possa visualizar e gerenciar todas os posts salvos, com opções de ordenação por data, e/ou hashtag | IS4 | 
| RF14 | O sistema deve permitir que o usuário crie ou use feeds (micro fóruns de posts) de terceiros personalizados com base em critérios como tipo de post, usuários ou hashtags relacionadas. | IS5 | 
| RF15 | Os usuários devem poder interagir com postagens por meio de comentários, curtidas e respostas. | IS8 e IS16 e QT2 | 
| RF16 | O sistema deve permitir a aplicação de filtros avançados, como autor do post, data de publicação ou popularidade, para melhorar a experiência de busca. | IS9 | 
| RF17 | O usuário deve ser capaz de fazer log-in/log-in automático em sua conta criada | IS11 | 
| RF18 | O usuário deve poder fixar uma publicação em seu perfil dando-a destaque em seu perfil	| IS13 | 
| RF19 | O usuário deve poder tornar sua conta privada, restringindo a interação de outros usuários ao permitir que apenas seguidores consigam interagir diretamente com ele | IS14 | 
| RF20 | Deve ser possível ao usuário fazer publicações contendo texto, imagens e vídeos | IS15 | 
| RF21 | Deve ser possível ao usuário visualizar dentro do aplicativo publicações de diferentes idiomas traduzidas para o idioma principal definido no aplicativo | IS18 | 
| RF22 | O usuário deve poder mandar mensagens diretas a outro usuário, caso se sigam mutualmente | IS19 | 
| RF23 | O usuário deve poder criar, ingressar, convidar e sair de grupos de mensagens diretas | IS20 | 
| RF24 | O usuário deve poder mandar mídias como vídeos e áudios nas mensagens privadas | IS21 | 
| RF25 | O usuário deve poder criar, modificar e excluir suas listas de perfis de interesse | IS23 | 
| RF26 | Caso não seja o criador da lista, o usuário deve poder inscrever-se/deixar de ser inscrito em listas de perfis de interesse para ter/deixar de ter acesso às publicações desses perfis por uma aba | IS24 |
| RF27 | O usuário deve poder criar, modificar e excluir suas listas de moderação | IS25 | 
| RF28 | Caso não seja o criador da lista, o usuário deve poder inscrever-se/deixar de ser inscrito em listas de moderação para não permitir/permitir a interação com os perfis contidos na lista | IS26 | 
| RF29 | O usuário deve poder visualizar a quantidade de vezes em que sua publicação foi visualizada | IS27 | 
| RF30 | O aplicativo deve permitir ao usuário a comunicação, entreterimento e informações atualizadas | QT1 | 
| RF31 | O aplicativo deve permitir linkar para outras pessoas sem o sufixo ".bsky.social" | QT3 | 
| RF32 | O aplicativo deve permitir Trending Topics | QT5 | 
| RF33 | O aplicativo deve permitir o sistema de tags fora do post | QT4 | 
| RF34 | O usuário deve poder criar comunidades ou grupos privados. | BT1 |
| RF35 | O usuário deve poder configurar a privacidade das postagens | BT2 |
| RF36 | O sistema deve enviar notificações sobre eventos em tempo real. | BT4 |
| RF37 | O usuário deve poder acessar métricas sobre o alcance de suas postagens | BT5 |


<p align="center"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></p> 



<center><p><b>Tabela 2:</b> Requisitos não funcionais</p></center>

| Tipo | Descrição | ID |
| :-----: | :-------: | :------: | 
| RNF1 | Deve ser possível personalizar o aplicativo (dark mode, idiomas…) | OB11 | 
| RNF2 | O sistema deve processar buscas e carregar feeds personalizados rapidamente, mesmo com grandes volumes de dados, garantin do uma experiência fluida para o usuário. | NIS1 BT7 | 
| RNF3 | O sistema deve ser capaz de crescer e suportar um número crescente de usuários e posts sem comprometer o desempenho. | NIS2, NIS13 e BT7 | 
| RNF4 | Todos os dados sensíveis, como informações de login e reviews salvas, devem ser protegidos por criptografia. O sistema deve implementar autenticação segura e proteger contra ataques como SQL injection e XSS. | NIS3 | 
| RNF5 | A interface do usuário deve ser intuitiva e fácil de usar, com opções bem definidas para buscar, salvar e visualizar postagens. O design deve ser centrado no usuário e acessível a diferentes perfis de idade. | NIS4 | 
| RNF6 | O sistema deve ter alta disponibilidade, operando continuamente com mínimas interrupções e implementando redundância de servidores para garantir estabilidade. | NIS5 | 
| RNF7 | O sistema deve ser compatível com dispositivos móveis modernos, oferecendo uma interface responsiva e acessível em diferentes tamanhos de tela. | NIS6 e BT9 | 
| RNF8 | O sistema deve permitir que o usuário personalize seus feeds e notificações facilmente, com opções para ajustar preferências de conteúdo e formato. | NIS7 | 
| RNF9 | O aplicativo deve ter um tempo de resposta para cada ação menor que 3 segundos | NIS9 | 
| RNF10 | O aplicativo deve ter interface intuitiva para usuários frequentes de redes sociais, levando até 15min para que se familiarizem com feeds, listas. | NIS10, BT10 | 
| RNF11 | O aplicativo deve prover ambientes saudáveis aos seus usuários, os protegendo de conteúdos nocivos |  NIS11 | 
| RNF12 | O aplicativo deve ser transparente quanto ao uso dos dados de seus usuários, independente de onde se encontra, o usuário deve estar a menos de 5 cliques dos Termos de Serviço e Política de Privacidade | NIS12 | 
| RNF13 | O aplicativo deve indicar ao usuário quando uma ação não pode ser concluída e o motivo para isso | NIS14 | 
| RNF14 | O aplicativo deve ter uma aparência agradavél ao usuário | QT6 | 
| RNF15 | A plataforma deve garantir transparência nos algoritmos de recomendação | QT6 |
| RNF16 | O sistema deve proteger os dados dos usuários de acordo com a LGPD. | BT8 |

<p align="center"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></p> 

## Bibliográfia 

> 1. Software Requirements. In: WIEGERS, Karl E.; BEATTY, Joy. Software Requirements. 3. ed. [S. l.]: Microsoft Press, 2013. cap. 16, p. 313-329. ISBN 0735679665.


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
            <td>Requisitos elicitados.</td>
            <td><a href="https://github.com/Renatinha28">Renata Quadros</a></td>
            <td>24/11</td>
            <td><a href="https://github.com/erteduarda">Eduarda</a></td>
        </tr>
    </table>
</div>