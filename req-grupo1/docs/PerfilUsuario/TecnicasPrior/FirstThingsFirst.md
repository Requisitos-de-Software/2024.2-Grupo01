
## Introdução

A priorização de requisitos de software é uma prática fundamental para garantir o sucesso de projetos de desenvolvimento de software, uma vez que permite estabelecer uma ordem de importância para os requisitos, facilitando a alocação de recursos. Com a técnica First-Things-First buscamos definir a ordenação dos requisitos com base tanto em seus benefícios, quanto em seus custos e riscos. Essa definição das prioridades ajuda a atender às necessidades mais críticas do cliente e a maximizar o valor do produto final, mesmo com restrições.

## Objetivo

Com a First-Things-First procuramos ordenar o conjunto de requisitos elicitados de forma a priorizar aqueles que gerem maior impacto positivo no valor do produto para, assim, apoiar decisões e melhorar a alocação de recursos com o fim na satisfação das necessidades do usuário. Tudo isso considerando tanto a perspectiva do cliente, quanto a da equipe de desenvolvimento enquanto construindo uma visualização estruturada em planilha ao equilibrar prós e contras, assinalar riscos técnicos e alinhar requisitos às regras de negócio.

## Metodologia

Essa técnica envolveu o desempenho de três papéis durantes as reuniões: o mediador, responsável por apresentar os requisitos elicitados, o usuário, responsável pela classificação dos requisitos em seus benefícios e penalidades de não implementação e o desenvolvedor, responsável pela classificação dos requisitos em seus custos e riscos de implementação. Foram realizadas duas reuniões para realização dessa técnica:

- Uma entre usuário e mediador na data de 23/11/2024 às 20:20, em que [Davi Nobre](https://github.com/Jagaima) atuou como mediador. [Link para vídeo da reunião com usuário](https://youtu.be/5yrODj8tqH0).
- Uma entre desenvolvedor e mediador na data de 23/11/2024 às 20:40, em que [João Ribeiro](https://github.com/Joa0V) atuou como mediador e [Davi Nobre](https://github.com/Jagaima) como desenvolvedor. [Link para vídeo da reunião com desenvolvedor]()

A técnica foi concretizada da seguinte forma:

1. Os requisitos elicitados foram listados em uma planilha e estabelecidos os pesos relativos para os cálculos:
    - Peso relativo para benefício: 2
	- Peso relativo para penalidade: 2
	- Peso relativo para custo: 1
	- Peso relativo para risco: 1
2. Em cada requisito, o usuário estimou seu benefício relativo em uma escala de 1 a 9, com 1 representando pouco benefício e 9 alto benefício.
3. Para cada requisito, o usuário estimou o impacto negativo que o negócio sofreria com sua não implementação em uma escala de 1 a 9, com 1 representando baixo impacto e 9 alto impacto
4. O valor total foi calculado da seguinte forma:  <p align="center" style="font-size: 18px;">`valor total = (benefício * peso) + (penalidade * peso)`</p>
5. Para cada requisito, o desenvolvedor estimou o custo relativo de sua implementação em uma escala de 1 a 9, com 1 representando baixo custo e 9 alto custo.
6. Para cada requisito, o desenvolvedor estimou o grau relativo de risco de sua implementação em uma escala de 1 a 9, com 1 sendo baixo risco e 9 alto risco.
7. A prioridade de cada requisito foi calculada da seguinte forma:
<br><p align="center" style="font-size: 18px;">`prioridade = valor(%)/(custo(%) * peso do custo + risco(%) * peso do risco)`</p>
8. Por fim, foi feita uma tabela de requisitos em ordem decrescente de prioridade.

## Resultado da Priorização

Na tabela 1 estão os resultados da priorização dos requisitos funcionais por meio da técnica First-Things-First, já na tabela 2 estão os resultados da priorização dos requisitos não-funcionais com a mesma técnica em ambas os requisitos estão ordenados de maneira decrescente com base em sua prioridade. Ainda, nas tabelas 3 e 4 tem-se a identificação e a descrição de cada requisito funcional e não-funcional respectivamente.

<center><p><b>Tabela 1:</b> Requisitos Funcionais Priorizados</p></center>

| **Requisito** | **Benefício Relativo** | **Penalidade Relativa** | **Valor total** | **Valor (%)** | **Custo Relativo** | **Custo(%)** | **Risco Relativo** | **Risco(%)** | **Prioridade** |
| ------------- | ---------------------- | ----------------------- | --------------- | ------------- | ---------------- | ------------ | ------------------ | ------------ | :------------: |
| RF17          | 9                      | 9                       | 36              | 4,62          | 1                | 0,95         | 1                  | 1,52         |      1,87      |
| RF10          | 9                      | 9                       | 36              | 4,62          | 2                | 1,90         | 1                  | 1,52         |      1,35      |
| RF6           | 9                      | 9                       | 36              | 4,62          | 3                | 2,86         | 1                  | 1,52         |      1,06      |
| RF15          | 9                      | 8                       | 34              | 4,36          | 3                | 2,86         | 1                  | 1,52         |      1,00      |
| RF13          | 9                      | 7                       | 32              | 4,10          | 3                | 2,86         | 1                  | 1,52         |      0,94      |
| RF27          | 7                      | 5                       | 24              | 3,08          | 2                | 1,90         | 1                  | 1,52         |      0,90      |
| RF28          | 8                      | 9                       | 34              | 4,36          | 2                | 1,90         | 2                  | 3,03         |      0,88      |
| RF18          | 8                      | 3                       | 22              | 2,82          | 2                | 1,90         | 1                  | 1,52         |      0,82      |
| RF12          | 5                      | 5                       | 20              | 2,56          | 2                | 1,90         | 1                  | 1,52         |      0,75      |
| RF5           | 9                      | 5                       | 28              | 3,59          | 2                | 1,90         | 2                  | 3,03         |      0,73      |
| RF26          | 6                      | 8                       | 28              | 3,59          | 2                | 1,90         | 2                  | 3,03         |      0,73      |
| RF33          | 5                      | 5                       | 20              | 2,56          | 3                | 2,86         | 1                  | 1,52         |      0,59      |
| RF25          | 7                      | 5                       | 24              | 3,08          | 4                | 3,81         | 1                  | 1,52         |      0,58      |
| RF4           | 6                      | 5                       | 22              | 2,82          | 2                | 1,90         | 2                  | 3,03         |      0,57      |
| RF19          | 9                      | 7                       | 32              | 4,10          | 3                | 2,86         | 3                  | 4,55         |      0,55      |
| RF16          | 9                      | 7                       | 32              | 4,10          | 5                | 4,76         | 2                  | 3,03         |      0,53      |
| RF20          | 9                      | 9                       | 36              | 4,62          | 6                | 5,71         | 2                  | 3,03         |      0,53      |
| RF1           | 9                      | 8                       | 34              | 4,36          | 4                | 3,81         | 3                  | 4,55         |      0,52      |
| RF7           | 3                      | 5                       | 16              | 2,05          | 3                | 2,86         | 1                  | 1,52         |      0,47      |
| RF22          | 9                      | 3                       | 24              | 3,08          | 4                | 3,81         | 2                  | 3,03         |      0,45      |
| RF21          | 6                      | 6                       | 24              | 3,08          | 6                | 5,71         | 1                  | 1,52         |      0,43      |
| RF31          | 9                      | 9                       | 36              | 4,62          | 5                | 4,76%        | 5                  | 7,58%        |      0,37      |
| RF14          | 4                      | 7                       | 22              | 2,82          | 4                | 3,81         | 3                  | 4,55         |      0,34      |
| RF2           | 8                      | 9                       | 34              | 4,36          | 5                | 4,76         | 6                  | 9,09         |      0,31      |
| RF30          | 9                      | 8                       | 34              | 4,36          | 5                | 4,76         | 8                  | 12,12        |      0,26      |
| RF32          | 3                      | 5                       | 16              | 2,05          | 6                | 5,71%        | 2                  | 3,03         |      0,23      |
| RF23          | 1                      | 6                       | 14              | 1,79          | 4                | 3,81         | 3                  | 4,55         |      0,21      |
| RF24          | 5                      | 4                       | 18              | 2,31          | 6                | 5,71%        | 4                  | 6,06         |      0,20      |
| RF11          | 1                      | 1                       | 4               | 0,51          | 4                | 3,81         | 2                  | 3,03         |      0,07      |

<p align="center"><b>Autores:</b> <a href="https://github.com/Joa0V">João Ribeiro </a> e <a href="https://github.com/Jagaima">Davi nobre</a></p>

<center><p><b>Tabela 2:</b> Requisitos Não-Funcionais Priorizados</p></center>

| **Requisito** | **Benefício Relativo** | **Penalidade Relativa** | **Valor total** | **Valor (%)** | *Custo Relativo* | **Custo(%)** | **Risco Relativo** | **Risco(%)** | **Prioridade** |
| ------------- | ---------------------- | ----------------------- | --------------- | ------------- | ---------------- | ------------ | ------------------ | ------------ | :------------- |
| RNF1          | 9                      | 9                       | 36              | 8,96          | 1                | 2,27         | 1                  | 2,00         | 2,10           |
| RNF13         | 9                      | 9                       | 36              | 8,96          | 1                | 2,27         | 1                  | 2,00         | 2,10           |
| RNF14         | 9                      | 9                       | 36              | 8,96          | 1                | 2,27         | 1                  | 2,00         | 2,10           |
| RNF8          | 7                      | 8                       | 30              | 7,46          | 2                | 4,55         | 1                  | 2,00         | 1,14           |
| RNF7          | 9                      | 8                       | 34              | 8,46          | 3                | 6,82         | 1                  | 2,00         | 0,96           |
| RNF10         | 9                      | 9                       | 36              | 8,96          | 4                | 9,09         | 2                  | 4,00         | 0,68           |
| RNF11         | 7                      | 7                       | 28              | 6,97          | 2                | 4,55         | 3                  | 6,00         | 0,66           |
| RNF9          | 8                      | 9                       | 34              | 8,46          | 4                | 9,09         | 5                  | 10,00        | 0,44           |
| RNF4          | 9                      | 9                       | 36              | 8,96          | 5                | 11,36        | 9                  | 18,00        | 0,30           |
| RNF12         | 8                      | 5                       | 26              | 6,47          | 3                | 6,82         | 9                  | 18,00        | 0,26           |
| RNF2          | 9                      | 9                       | 36              | 8,96          | 9                | 20,45        | 8                  | 16,00        | 0,25           |

<p align="center"><b>Autores:</b> <a href="https://github.com/Joa0V">João Ribeiro </a> e <a href="https://github.com/Jagaima">Davi nobre</a></p>

<p align="center"><b>Tabela 3:</b> Requisitos funcionais</p>


| Tipo | Descrição | ID |
| :-----: | :-------: | :------: |
| RF1 | Deve ser possível realizar o login | [OB1](../Tecnicas/Observacao.md/#resultados) e [IS1](../Tecnicas/Introspeccao.md) e [IS10](../Tecnicas/Introspeccao.md)|
| RF2 | Deve ser possível recuperar a senha no aplicativo | [OB2](../Tecnicas/Observacao.md/#resultados) |
| RF3 | Deve ser possível acessar novos conteúdos rapidamente na plataforma | [OB3](../Tecnicas/Observacao.md/#resultados) |
| RF4 | Deve ser possível realizar postagens na plataforma| [OB4](../Tecnicas/Observacao.md/#resultados) |
| RF5 | Deve ser possível ao usuário editar suas publicações já postadas | [OB5](../Tecnicas/Observacao.md/#resultados) e [IS17](../Tecnicas/Introspeccao.md) |
| RF6 | O sistema deve permitir que o usuário faça buscas por posts relacionados ao seu interesse, usando palavras-chave, hashtags ou filtros específicos. | [OB6](../Tecnicas/Observacao.md/#resultados) e [IS2](../Tecnicas/Introspeccao.md) |
| RF7 | Deve ser possível favoritar uma comunidade | [OB7](../Tecnicas/Observacao.md/#resultados) |
| RF8 | O usuário deve poder criar seus próprios posts, e compartilhá-los com um feed específico ou a comunidade em geral. | [OB8](../Tecnicas/Observacao.md/#resultados) e [IS6](../Tecnicas/Introspeccao.md) |
| RF9 | Deve ser possível ver as mensagens com outros usuários | [OB9](../Tecnicas/Observacao.md/#resultados) |
| RF10 | Deve ser possível editar o conteúdo do perfil | [OB10](../Tecnicas/Observacao.md/#resultados) e [IS12](../Tecnicas/Introspeccao.md) |
| RF11 | O sistema deve notificar o usuário sobre novos posts com base nos interesses e feeds personalizados configurados. | [OB12](../Tecnicas/Observacao.md/#resultados) e [IS7](../Tecnicas/Introspeccao.md) |
| RF12 | O usuário deve poder salvar Posts de interesse em uma seção dedicada para consulta futura. | [IS3](../Tecnicas/Introspeccao.md) e [IS22](../Tecnicas/Introspeccao.md) |
| RF13 | O sistema deve disponibilizar uma seção onde o usuário possa visualizar e gerenciar todos os posts salvos, com opções de ordenação por data, e/ou hashtag | [IS4](../Tecnicas/Introspeccao.md) |
| RF14 | O sistema deve permitir que o usuário crie ou use feeds (micro fóruns de posts) de terceiros personalizados com base em critérios como tipo de post, usuários ou hashtags relacionadas. | [IS5](../Tecnicas/Introspeccao.md) |
| RF15 | Os usuários devem poder interagir com postagens por meio de comentários, curtidas e respostas. | [IS8](../Tecnicas/Introspeccao.md) e [IS16](../Tecnicas/Introspeccao.md) e [QT2](../Tecnicas/Questionario.md/#requisitos-elicitados) |
| RF16 | O sistema deve permitir a aplicação de filtros avançados, como autor do post, data de publicação ou popularidade, para melhorar a experiência de busca. | [IS9](../Tecnicas/Introspeccao.md) |
| RF17 | O usuário deve ser capaz de fazer log-in/log-in automático em sua conta criada | [IS11](../Tecnicas/Introspeccao.md) |
| RF18 | O usuário deve poder fixar uma publicação em seu perfil dando-a destaque em seu perfil	| [IS13](../Tecnicas/Introspeccao.md) |
| RF19 | O usuário deve poder tornar sua conta privada, restringindo a interação de outros usuários ao permitir que apenas seguidores consigam interagir diretamente com ele | [IS14](../Tecnicas/Introspeccao.md) |
| RF20 | Deve ser possível ao usuário fazer publicações contendo texto, imagens e vídeos | [IS15](../Tecnicas/Introspeccao.md) |
| RF21 | Deve ser possível ao usuário visualizar dentro do aplicativo publicações de diferentes idiomas traduzidas para o idioma principal definido no aplicativo | [IS18](../Tecnicas/Introspeccao.md) |
| RF22 | O usuário deve poder mandar mensagens diretas a outro usuário, caso se sigam mutualmente | [IS19](../Tecnicas/Introspeccao.md) |
| RF23 | O usuário deve poder criar, ingressar, convidar e sair de grupos de mensagens diretas | [IS20](../Tecnicas/Introspeccao.md) |
| RF24 | O usuário deve poder mandar mídias como vídeos e áudios nas mensagens privadas | [IS21](../Tecnicas/Introspeccao.md) |
| RF25 | O usuário deve poder criar, modificar e excluir suas listas de perfis de interesse | [IS23](../Tecnicas/Introspeccao.md) |
| RF26 | Caso não seja o criador da lista, o usuário deve poder inscrever-se/deixar de ser inscrito em listas de perfis de interesse para ter/deixar de ter acesso às publicações desses perfis por uma aba | [IS24](../Tecnicas/Introspeccao.md) |
| RF27 | O usuário deve poder criar, modificar e excluir suas listas de moderação | [IS25](../Tecnicas/Introspeccao.md) |
| RF28 | Caso não seja o criador da lista, o usuário deve poder inscrever-se/deixar de ser inscrito em listas de moderação para não permitir/permitir a interação com os perfis contidos na lista | [IS26](../Tecnicas/Introspeccao.md) |
| RF29 | O usuário deve poder visualizar a quantidade de vezes em que sua publicação foi visualizada | [IS27](../Tecnicas/Introspeccao.md) |
| RF30 | O aplicativo deve permitir ao usuário a comunicação, entreterimento e informações atualizadas | [QT1](../Tecnicas/Questionario.md/#requisitos-elicitados) |
| RF31 | O aplicativo deve permitir linkar para outras pessoas sem o sufixo ".bsky.social" | [QT3](../Tecnicas/Questionario.md/#requisitos-elicitados) |
| RF32 | O aplicativo deve permitir Trending Topics | [QT5](../Tecnicas/Questionario.md/#requisitos-elicitados) |
| RF33 | O aplicativo deve permitir o sistema de tags fora do post | [QT4](../Tecnicas/Questionario.md/#requisitos-elicitados) |


<p align="center"><b>Autores:</b> <a href="https://github.com/Joa0V">João Ribeiro </a> e <a href="https://github.com/Jagaima">Davi nobre</a></p>


<p align="center"><b>Tabela 4:</b> Requisitos não-funcionais</p>


| Tipo | Descrição | ID |
| :-----: | :-------: | :------: |
| RNF1 | Deve ser possível personalizar o aplicativo (dark mode, idiomas…) | [OB11](../Tecnicas/Observacao.md/#resultados) |
| RNF2 | O sistema deve processar buscas e carregar feeds personalizados rapidamente, mesmo com grandes volumes de dados, garantindo uma experiência fluida para o usuário. | [NIS1](../Tecnicas/Introspeccao.md) |
| RNF3 | O sistema deve ser capaz de crescer e suportar um número crescente de usuários e posts sem comprometer o desempenho. | [NIS2](../Tecnicas/Introspeccao.md) e [NIS13](../Tecnicas/Introspeccao.md) |
| RNF4 | Todos os dados sensíveis, como informações de login e reviews salvas, devem ser protegidos por criptografia. O sistema deve implementar autenticação segura e proteger contra ataques como SQL injection e XSS. | [NIS3](../Tecnicas/Introspeccao.md) |
| RNF5 | A interface do usuário deve ser intuitiva e fácil de usar, com opções bem definidas para buscar, salvar e visualizar postagens. O design deve ser centrado no usuário e acessível a diferentes perfis de idade. | [NIS4](../Tecnicas/Introspeccao.md) |
| RNF6 | O sistema deve ter alta disponibilidade, operando continuamente com mínimas interrupções e implementando redundância de servidores para garantir estabilidade. | [NIS5](../Tecnicas/Introspeccao.md) |
| RNF7 | O sistema deve ser compatível com dispositivos móveis modernos, oferecendo uma interface responsiva e acessível em diferentes tamanhos de tela. | [NIS6](../Tecnicas/Introspeccao.md) |
| RNF8 | O sistema deve permitir que o usuário personalize seus feeds e notificações facilmente, com opções para ajustar preferências de conteúdo e formato. | [NIS7](../Tecnicas/Introspeccao.md) |
| RNF9 | O sistema deve garantir a privacidade do usuário, permitindo que ele controle quem pode ver suas atividades e reviews, com políticas claras sobre coleta e uso de dados. | [NIS8](../Tecnicas/Introspeccao.md) |
| RNF10 | O aplicativo deve ter um tempo de resposta para cada ação menor que 3 segundos | [NIS9](../Tecnicas/Introspeccao.md) |
| RNF11 | O aplicativo deve ter interface intuitiva para usuários frequentes de redes sociais, levando até 15min para que se familiarizem com feeds, listas. | [NIS10](../Tecnicas/Introspeccao.md) |
| RNF12 | O aplicativo deve prover ambientes saudáveis aos seus usuários, os protegendo de conteúdos nocivos |  [NIS11](../Tecnicas/Introspeccao.md) |
| RNF13 | O aplicativo deve ser transparente quanto ao uso dos dados de seus usuários, independente de onde se encontra, o usuário deve estar a menos de 5 cliques dos Termos de Serviço e Política de Privacidade | [NIS12](../Tecnicas/Introspeccao.md) |
| RNF14 | O aplicativo deve indicar ao usuário quando uma ação não pode ser concluída e o motivo para isso | [NIS14](../Tecnicas/Introspeccao.md) |
| RNF15 | O aplicativo deve ter uma aparência agradavél ao usuário | [QT6](../Tecnicas/Questionario.md/#requisitos-elicitados) | 


<p align="center"><b>Autores:</b> <a href="https://github.com/Joa0V">João Ribeiro </a> e <a href="https://github.com/Jagaima">Davi nobre</a></p>

## Bibliografia

> 1. KARL WIEGERS. Medium, 2024. First Things First: Prioritizing Requirements (or anything else). Disponível em: https://medium.com/analysts-corner/first-things-first-prioritizing-requirements-or-anything-else-d43aa7bad4b1. Acesso em: 23/11/2024
> 2. FIRST things first: Setting requirement priorities. In: WIEGERS, Karl E.; BEATTY, Joy. Software Requirements. 3. ed. S. l.: Microsoft Press, 2013. cap. 16, p. 313-329. ISBN 0735679665.

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
            <td>23/11</td>
            <td>1.0</td>
            <td>Criação do documento </td>
            <td><a href="https://github.com/Joa0V">João Ribeiro</a></td>
            <td></td>
            <td><a href="https://github.com/"></a></td>
        </tr>
    </table>
</div>