## Introdução
Este documento tem como finalidade apresentar uma análise comparativa de cinco aplicativos, cada um escolhido e avaliado pelos membros do grupo, visando selecionar o mais adequado para um projeto detalhado de requisitos. Diante do avanço tecnológico e da importância crescente dos aplicativos no atendimento a diversas necessidades do público, essa seleção buscará identificar o app que mais se destaca em aspectos como funcionalidade, usabilidade, acessibilidade, impacto, além de não poderter sido avaliado por semestres anteriores.

## Objetivo
O objetivo deste documento é documentar as avaliações individuais dos aplicativos escolhidos pelos membros do grupo, a fim de determinar o aplicativo que melhor atende aos critérios estabelecidos para um estudo aprofundado de requisitos. A escolha do melhor app permitirá que o grupo realize uma análise mais detalhada dos requisitos funcionais e não funcionais, oferecendo uma base sólida para o desenvolvimento de uma solução robusta e eficaz.

## Metodologia
Para garantir uma avaliação justa e objetiva, adotamos uma metodologia que contempla os seguintes passos:

- **Seleção individual de aplicativos:** Cada membro do grupo escolheu um aplicativo para avaliação, considerando fatores como relevância, base de usuários, variedade de funcionalidades e acessibilidade.
    - **Rich Picture:** Representação visual que integra diferentes aspectos e perspectivas do aplicativo escolhido, permitindo uma visão ampla e não estruturada das funcionalidades, interações e desafios. Essa representação facilita o entendimento do contexto, possibilita identificar pontos de melhoria e auxilia na comunicação entre os envolvidos na análise.
- **Análise comparativa:** A partir das avaliações individuais, faremos uma comparação detalhada dos pontos fortes e fracos de cada app.
- **Seleção final:** Com base na análise comparativa, escolheremos o aplicativo que mais se destaca nos critérios estabelecidos, tornando-o o candidato ideal para o estudo de requisitos.

Todos os Rich Pictures foram feitos contendo os elementos principais, de acordo com "Introducing Rich Pictures - Rich Picture Drawing Guidelines", como mostra a figura 1.

<div style="text-align: center;">
    <h2>Figura 1: Elementos - Rich Picture</h2>
</div>
<figure>
    <img src="../../assets/images/RP0.png"  style="width: 70%; height: auto; object-fit: cover;">
    <figcaption>Fonte: Introducing Rich Pictures - Rich Picture Drawing Guidelines  </figcaption>
</figure>

## Tabela de apps avaliados
A Tabela 1 indica todos os aplicativos avaliados pelo grupo, indicando o caminho de cada descrição da avaliação neste documento, além do membro do grupo responsável pela avaliação.

<div style="text-align: center;">
    <p>Tabela 1: Apps avaliados</p>

    <table style="margin: 0 auto;">
        <tr>
            <th>App avaliado</th>
            <th>Integrante responsável</th>
        </tr>
        <tr>
            <td><a href="#meu-sus-digital">Meu SUS Digital</a></td>
            <td><a href="https://github.com/Renatinha28">Renata Quadros</a></td>
        </tr>
        <tr>
            <td><a href="#app-2">GitHub Mobile</a></td>
            <td><a href="https://github.com/ccarlaa">Carla Clementino</a></td>
        </tr>
        <tr>
            <td><a href="#fab">Força áerea brasileira</a></td>
            <td><a href="https://github.com/Jagaima">Davi Nobre</a></td>
        </tr>
        <tr>
            <td><a href="#carteira-de-trabalho-digital">Carteira de Trabalho Digital</a></td>
            <td><a href="https://github.com/erteduarda">Eduarda</a></td>
        </tr>
        <tr>
            <td><a href="#bluesky">BlueSky</a></td>
            <td><a href="https://github.com/Joa0V">João Ribeiro</a></td>
        </tr>
    </table>

    <p>Autor: <a href="https://github.com/Renatinha28">Renata Quadros</a></p>
</div>

## Meu SUS Digital
O Sistema Único de Saúde (SUS) é o sistema público de saúde brasileiro, criado para garantir acesso universal e gratuito aos serviços de saúde. Com o avanço da tecnologia, o SUS lançou o aplicativo Meu SUS Digital, que centraliza diversos serviços, como agendamentos e histórico de vacinas, em uma plataforma prática e acessível. Este app facilita o acesso dos cidadãos aos serviços de saúde, sendo um exemplo de inovação no setor público. Para o projeto de Requisitos, a integrante [Renata Quadros]() escolheu o Meu SUS Digital para avaliar e algumas das justificativas são:

- Familiaridade e acessibilidade: Aplicativo projetado para ser intuitivo e fácil de usar, acessível para pessoas com diferentes níveis de experiência com tecnologia.
-	Base de usuários ampla: Usado por uma grande e diversificada base de usuários que utilizam os serviços do Sistema Único de Saúde (SUS), o que permite uma análise com grande impacto e relevância.
-	Variedade de funcionalidades: Oferece múltiplos serviços como agendamento de consultas, histórico de vacinas, resultados de exames, localização de unidades de saúde, entre outros, possibilitando um estudo abrangente de requisitos.
-	Relevância na atualidade: Com a digitalização dos serviços de saúde e a demanda por soluções mais acessíveis, a análise do Meu SUS Digital se torna importante para entender requisitos de sistemas que impactam diretamente a população.
-	Contribuição prática para formação: Permite uma experiência de aprendizado alinhada com demandas reais, preparando para projetos de grande uso e importância social.

### Rich Picture - Meu SUS Digital
Foi feito para o Meu SUS Digital uma representação, mostrado na Figura 2, em Rich Picture, que ajuda a ilustrar de forma visual e simplificada os processos e interações envolvidos. Através dessa abordagem visual, é possível visualizar melhor o funcionamento do sistema e facilitar a comunicação entre diferentes membros da equipe ou stakeholders que talvez não estejam familiarizados com os detalhes técnicos do projeto.

<div style="text-align: center;">
    <h2>Figura 2: Rich Picture: Meu SUS Digital</h2>
</div>
<figure>
    <img src="../../assets/images/rp-renata.png" style="width: 70%; height: auto; object-fit: cover;">
    <figcaption>Autor: Renata Quadros</figcaption>
</figure>
### Descrição dos Componentes

1. Usuário:
    - Representados pelos desenhos de pessoas, o usuário tem acesso a algumas funcionalidades como adicionar medicamentos, adicionar alergia, consultar vacinas, entre outros. Além disso, temos dois tipos de usuários: um representando o usuário que está fora do SUS e outro o que está no SUS. Este último irá passar informações para a funcionária (também representada por um desenho de pessoa), que terá acesso restrito a algumas funcionalidades, como registrar exames e agendamentos, além de também ter acesso a funcionalidades que o usuário possui, como vacinas, medicamentos e alergias.
2. Funcionalidades Principais:
     - Medicamentos : Permite ao usuário adicionar e visualizar medicamentos passados por médicos, além de permitir a funcionária visualizar todos os medicamentos adicionados.
    - Alergias : Permite ao usuário adicionar e visualizar alergias, além de permitir a funcionária visualizar todos as alergias adicionadas.
    - Rede de saúde : Permite ao usuário visualizar as redes de saúde mais próxima da sua localização atual.
    - Vacinas : Permite a funcionária registrar vacinas do usuário e a visualização para o usuário.
    - Agendamentos : Permite a funcionária registrar os agendamentos do usuário e a visualização para o usuário. 
    - Exames : Permite a funcionária registrar os exames do usuário e a visualização para o usuário. 
3. Adicionais:
    -  Os balões desenhados indicam possiveís pensamentos dos usuários, facilitando a compreensão.
    - Os nomes de cada ator são descritos logo abaixo do desenho de cada um.
    - Algumas descrições são utilizadas no fluxo (setas) para facilitar o entendimento


## BlueSky
A BlueSky é uma plataforma de rede social que surgiu como uma alternativa às redes sociais tradicionais com uma abordagem descentralizada. Assim, sua proposta é promover a expressão de seus usuários de acordo com suas próprias regras, sem estar a mercê das decisões de uma grande corporação. Dentre os pontos positivos para a escolha do BlueSky para o projeto da disciplina Requisitos de Software estão:

- Relevância: redes socias tem grande relevância na sociedade atual com inegável impacto na maneira como o ser humano se relaciona com o próximo.
- Gama de funcionalidades: a BlueSky aprensenta grande variedade de ações para seus usuários como postar textos, imagens e vídeos, troca de mensagens, personalizar feed, editar perfil e preferências, entre outros.
- Caracteríscas interessantes: a escolha de descentralização direcionou à utilização de um protocolo que permite a comunicação direta entre BlueSky e demais platafomas que o implementam e a maior participação de sua comunidade na moderação da plataforma.
- Crescente comunidade: a plataforma que já possui uma grande comunidade continua a receber novos usuários com a procura por alternativas às redes sociais já existentes.

### Rich Picture - Bluesky

O rich picture da figura 3 ilustra os processos e interações do sistema da Bluesky

<div style="text-align: center;">
    <h2>Figura 3: Rich Picture: Bluesky</h2>
</div>
<figure>
    <img src="../../assets/images/rp-bluesky.png"  style="width: 70%; height: auto; object-fit: cover;">
    <figcaption>Autor: João Vitor</figcaption>
</figure>

#### Descrição dos componentes

1. Usuário:
    - Um usuário da Bluesky pode interagir com outros usuários do sistema por meio de publicações e mensagens diretas, além de gerenciar sua própria conta.

2. Funcionalidades Principais:

    - Publicar: um usuário pode compartilhar pequenos textos, fotos e vídeos.
    - Explorar publicações: um usuário pode explorar as publicações de outros usuários e interagir com elas, sendo possível curtir, comentar ou compartilha-las.
    - Seguir: um usuário pode seguir uma conta e torna-la mais evidente em seu feed.
    - Enviar mensagens: um usuário pode enviar mensagens privadas a contas de outros usuários.
    - Configurar conta: um usuário pode gerenciar sua conta, bem como configurar opções de exibição de conteúdo e privacidade.

3. Adicionais:

    - Um usuário moderador tem a capacidade de classificar contas por meio de rótulos com base em suas ações no sistema. Além disso, é possível que um moderador bloqueie uma conta, caso a mesma infrinja os termos de uso.

## Carteira de Trabalho Digital
A Carteira de Trabalho Digital é um aplicativo desenvolvido pelo governo brasileiro para simplificar o acesso e gestão das informações trabalhistas dos cidadãos. Entre os benefícios de escolher a Carteira de Trabalho Digital para o projeto da disciplina de Requisitos de Software, destacam-se:

- Relevância: O app digitaliza um documento essencial para o trabalhador brasileiro, com impacto direto na formalização e histórico profissional.
- Gama de funcionalidades: A plataforma permite acesso ao histórico de empregos, visualização de contratos, consulta de dados trabalhistas, aviso de férias e direitos, além de integração com outros serviços.
- Facilidade e conveniência: A digitalização elimina a necessidade do documento físico, facilitando o acesso rápido às informações trabalhistas.
- Atualização: Informações sobre novos vínculos empregatícios e direitos trabalhistas são atualizadas de forma automática, permitindo que o trabalhador acompanhe suas relações de trabalho de maneira prática e eficiente.
- Popularidade crescente: Cada vez mais trabalhadores aderem à plataforma devido à praticidade e confiança, fortalecendo a comunidade de usuários e incentivando melhorias contínuas no aplicativo.

### Rich Picture - Carteira de Trabalho Digital
O Rich Picture mostrado na figura 4 representa o fluxo de informações e os principais componentes do sistema no aplicativo da
Carteira de Trabalho Digital, destacando as interações dos usuários com as funcionalidades oferecidas pelo
app.

<div style="text-align: center;">
    <h2>Figura 4: Rich Picture: Carteira de Trabalho Digital</h2>
</div>
<figure>
    <img src="../../assets/images/rp.png"  style="width: 70%; height: auto; object-fit: cover;">
    <figcaption>Autor: Eduarda </figcaption>
</figure>

#### Descrição dos Componentes
1. Usuário:
    - Representado pelo ícone de uma pessoa, o usuário tem acesso a várias funcionalidades do aplicativo, como
cadastro, consulta e compartilhamento de informações.
2. Funcionalidades Principais:
    - Relatório de Contratos: Permite aos usuários visualizar e acessar relatórios de contratos de trabalho. Essa funcionalidade se conecta diretamente com o dashboard, onde as informações são agregadas e analisadas.
    - Cadastro no Banco de Vagas: Usuários podem cadastrar-se em um banco de vagas, utilizando formulários que coletam e organizam suas informações para oportunidades de emprego.
    - Consulta Abono Salarial: A função de consulta permite que o usuário verifique seu status em relação
ao abono salarial, possivelmente acessando informações sobre elegibilidade e valores disponíveis.
    - Compartilhar Carteira de Trabalho: Permite ao usuário compartilhar informações de sua carteira de
trabalho de forma digital, conectando-se diretamente com a internet para enviar dados.
3. Formulários e Pesquisa:
    - O app usa formulários para coletar dados dos usuários para o banco de vagas, e uma função de pesquisa
para facilitar a consulta de informações sobre abono salarial, de forma ágil e intuitiva.

## Força áerea brasileira
Força áerea brasileira é uma organização militar brasileira que tem com o intuito manter a segurança áerea nacional. Sua comunicação principal com a população e a mídia se dá através de seu site e de deu app que será avaliado aqui. entre os pontos positivos para a escolha do app da FAB para o projeto da disciplina Requisitos de Software estão os seguintes:

- Relevância: O app é uma fonte de informações primordial para o meio jornalistico, pois é aqui que os mesmos disponibilizam suas notícias para todos os veículos de mídia. 
- Base de usuários ampla: O app possui funções tanto para usuários que compõe o corpo militar (como informações monetárias) até para civis, com direcionamento ao alistamento e uma rádio da própria FAB.
- Funcionalidades: O app possui diversas funcionalidades (algumas não funcionando) que podem ter seus requisitos validados ou o estudo de novos requisitos em cima de funções pré existentes 
- Contribuição acadêmica: Por se tratar de um software governamental aparentemente com baixa manutenção mas de uma base aceitavel de uso, se torna ideal em seu estágio atual sua pesquisa. 

### Rich Picture - Força áerea brasileira
A figura 5 mostra o Rich Picture que representa o fluxo de informações e os principais elementos do sistema na Força Aérea Brasileira. Destacando suas interações com o usuário e demais papeis que representam um todo de funcionalidades do app. 

<div style="text-align: center;">
    <h2>Figura 5: Rich Picture: Força áerea brasileira</h2>
</div>
<figure>
    <img src="../../assets/images/img4.jpg"  style="width: 70%; height: auto; object-fit: cover;">
    <figcaption>Autor: Davi </figcaption>
</figure>

### Descrição dos Componentes

1. Usuário:
    - Representados por ícones de pessoas, os usuários possuem acesso a diversas funcionalidades relacionadas à Força Aérea Brasileira (FAB). Eles podem realizar ações como pesquisar notícias, consultar localização de bases e realizar o alistamento. Há diferentes tipos de usuários, incluindo jornalistas, que podem publicar dados e noticiar acontecimentos. Esses usuários interagem com o sistema e têm diferentes níveis de acesso às informações e funções, com algumas funcionalidades exclusivas para setores internos da FAB.
2. Funcionalidades Principais:
    - Base de Notícias: Centraliza as informações e anúncios da FAB, transmitindo dados importantes e atualizações para os usuários. Jornalistas e outros usuários podem pesquisar notícias e compartilhar informações com o público.
    - Base de Dados de Locais da FAB: Permite aos usuários acessar informações sobre localizações e instalações da FAB. Facilita a pesquisa por localização e ajuda a direcionar as ações e informações relevantes.
    - Publicação de Dados: Usuários autorizados, como jornalistas, podem publicar dados e comunicar feitos da FAB ao público, como datas de alistamento e eventos significativos.
    Alistamento: Permite aos usuários realizar o processo de alistamento, que é enviado para a base de dados da FAB e fica acessível para setores internos.
    - Envio de Dados e Avaliações: O sistema permite o envio de datas importantes para avaliações e ações dentro da FAB, assegurando que o fluxo de informações chegue aos departamentos adequados.
3. Adicionais:
    -  As formas ovais representam funções sendo exceutadas. 
    - Os nomes de cada ator são descritos na área de legenda das imagens
    - Algumas descrições são utilizadas no fluxo (setas) para facilitar o entendimento


## Github Mobile

<p>O aplicativo escolhido para a atividade de confecção de uma Rich Picture foi o GitHub Mobile. A escolha se deu pelo fato de o aplicativo ser um projeto open source, o que facilita o acesso às informações sobre sua estrutura e funcionalidades. Além disso, o grupo teria fácil acesso a diversos usuários da plataforma, tornando a coleta de dados mais viável e enriquecedora. Outro fator relevante é o grande interesse dos participantes, dado o uso frequente do GitHub em atividades acadêmicas ao longo do curso.</p> <p>Considerando um trabalho sobre requisitos de software, a análise do GitHub Mobile se torna particularmente relevante pelos seguintes pontos:</p> <ul> <li><strong>Relevância das funcionalidades:</strong> O GitHub Mobile oferece funcionalidades essenciais para o gerenciamento de projetos de desenvolvimento, como controle de versões, gerenciamento de repositórios e comunicação entre colaboradores. A análise dessas funcionalidades permite entender como o software atende às necessidades de seus usuários e como requisitos adicionais ou melhorias podem ser identificados.</li> <li><strong>Facilidade de uso e experiência do usuário (UX):</strong> O app precisa garantir uma interface intuitiva e uma navegação eficiente. A coleta de requisitos sobre a usabilidade e a experiência do usuário pode fornecer informações sobre a eficácia das funcionalidades do app e como elas podem ser aprimoradas, considerando a fluidez das interações e a facilidade de execução das tarefas.</li> <li><strong>Desempenho e confiabilidade:</strong> O GitHub Mobile deve ser capaz de realizar operações rápidas e sem falhas, especialmente considerando a base de usuários ativa. O desempenho do aplicativo é um requisito crítico que impacta diretamente a satisfação do usuário e deve ser analisado em termos de tempo de resposta e estabilidade.</li> <li><strong>Requisitos de segurança:</strong> Como o GitHub Mobile lida com repositórios de código e dados sensíveis, a segurança é um requisito fundamental. A análise de como o aplicativo gerencia a autenticação, criptografia de dados e permissões de acesso é crucial para garantir que os usuários estejam protegidos enquanto utilizam o serviço.</li> <li><strong>Compatibilidade com diferentes dispositivos:</strong> O GitHub Mobile precisa ser compatível com uma variedade de dispositivos móveis e versões de sistemas operacionais. O estudo da compatibilidade e dos requisitos para garantir uma experiência consistente em diferentes plataformas é importante para avaliar a cobertura de usuários do aplicativo e identificar possíveis falhas de implementação em dispositivos específicos.</li> </ul>
A figura 6 e 7 representa o Rich Picture realizado.

<div style="text-align: center;">
    <h2>Figura 6: Rich Picture: Github Mobile</h2>
</div>
<figure>
    <img src="../../assets/images/carla_rich_picture.jpg"  style="width: 70%; height: auto; object-fit: cover;">
    <figcaption>Autor: Carla A. C. Ribeiro </figcaption>
</figure>

<div style="text-align: center;">
    <h2>Figura 7: Legenda Github Mobile </h2>
</div>
<figure>
    <img src="../../assets/images/rich_description.jpg"  style="width: 70%; height: auto; object-fit: cover;">
    <figcaption>Autor: Carla A. C. Ribeiro </figcaption>
</figure>



### Descrição dos Componentes

1. Usuário
Representados por ícones de usuários, os usuários do GitHub Mobile têm acesso a diversas funcionalidades essenciais para o gerenciamento e colaboração em projetos de software. Eles podem realizar ações como logar na plataforma, hospedar seus próprios projetos, visualizar outros projetos, contribuir com código e melhorias, debater sobre questões e ideias relacionadas aos projetos, além de acompanhar e ver diferentes versões de um repositório. 

2. Funcionalidades Principais: 

<p>O GitHub Mobile oferece diversas funcionalidades que permitem aos usuários interagir de forma eficiente com seus projetos e colaborar com outros desenvolvedores. Entre as funcionalidades disponíveis, destacam-se:</p> <ul> <li><strong>Login:</strong> Permite aos usuários fazerem login na plataforma, garantindo acesso seguro e personalizado às suas informações e projetos.</li> <li><strong>Hospedagem de Projetos:</strong> Usuários podem hospedar seus próprios projetos, facilitando o compartilhamento e gerenciamento de código-fonte com colaboradores e a comunidade.</li> <li><strong>Visualizar Projetos:</strong> Os usuários podem explorar outros projetos hospedados na plataforma, contribuindo para a comunidade e aprendendo com diferentes abordagens e soluções de software.</li> <li><strong>Contribuição:</strong> Permite que os usuários contribuam com código ou melhorias para projetos de outros desenvolvedores, por meio de pull requests e submissões de alterações.</li> <li><strong>Debate:</strong> O GitHub Mobile possibilita a interação entre desenvolvedores por meio de discussões em issues, onde é possível debater ideias, tirar dúvidas e colaborar nas decisões de projeto.</li> <li><strong>Visualizar Versões:</strong> Usuários podem acessar e comparar diferentes versões de um projeto, analisando histórico de mudanças, correções de bugs e novas funcionalidades implementadas.</li> </ul>


## Referência Bibliográfica / Bibliografia
> [Plano de ensino](https://aprender3.unb.br/pluginfile.php/2972367/mod_resource/content/52/Plano_de_Ensino%20RE%20022024%20Turma%2002%20v1.pdf)
<a id="c1"></a>

> Monk, A., & Howells, K. (n.d.). Introducing Rich Pictures: Rich Picture Drawing Guidelines.

> 1. Meu SUS Digital. SUS, 2024. Dispinível em: https://meususdigital.saude.gov.br/login. Acesso em: 06 nov 2024.



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
            <td>28/10</td>
            <td>1.0</td>
            <td>Criação do documento e add Meu SUS digital </td>
            <td><a href="https://github.com/Renatinha28">Renata Quadros</a></td>
            <td>03/11</td>
            <td><a href="https://github.com/Jagaima">Davi Nobre</a></td>
        </tr>
        <tr>
            <td>29/10</td>
            <td>1.1</td>
            <td>Criação do documento e add Carteira de Trabalho Digital</td>
            <td><a href="https://github.com/erteduarda">Eduarda Tavares</a></td>
            <td>03/11</td>
            <td><a href="https://github.com/Renatinha28">Renata Quadros</a></td>
            <td><a href=""></a></td>
        </tr>
        <tr>
            <td>29/10</td>
            <td>1.2</td>
            <td>Adição do Bluesky</td>
            <td><a href="https://github.com/Joa0V">João Ribeiro</a></td>
            <td>03/11</td>
            <td><a href="https://github.com/Jagaima">Davi Nobre</a></td>
        </tr>
        <tr>
            <td>03/11</td>
            <td>1.3</td>
            <td>Adição da FAB</td>
            <td><a href="https://github.com/Jagaima">Davi Nobre</a></td>
            <td>06/11</td>
            <td><a href="https://github.com/Renatinha28">Renata Quadros</a></td>
            <td><a href=""></a></td>>
        </tr>
        <tr>
            <td>05/11</td>
            <td>1.4</td>
            <td>Adição do Github Mobile</td>
            <td><a href="https://github.com/Jagaima">Carla Clementino</a></td>
            <td>06/11</td>
            <td><a href="https://github.com/Renatinha28">João Ribeiro</a></td>
            <td><a href=""></a></td>>
        </tr>
        <tr>
            <td>15/11</td>
            <td>1.5</td>
            <td>Correções pós apresentação</td>
            <td><a href="https://github.com/Renatinha28">Renata Quadros</a></td>
            <td>15/11</td>
            <td><a href="https://github.com/Renatinha28">João Ribeiro</a></td>
            <td><a href=""></a></td>>
        </tr>
    </table>
</div>