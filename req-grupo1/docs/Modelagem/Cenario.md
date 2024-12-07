## Introdução

O presente documento foi elaborado como parte do projeto da disciplina de Requisitos de Software e tem como objetivo principal a definição detalhada dos cenários relacionados ao sistema do Bluesky. Os cenários são ferramentas essenciais no processo de análise e modelagem de requisitos, pois permitem compreender e descrever situações específicas que o sistema deve ser capaz de suportar. Cada cenário descrito contribui para a construção de uma visão abrangente das funcionalidades e interações esperadas.

## Objetivo

O objetivo deste documento é apresentar os cenários do sistema escolhido, Bluesky, descrevendo-os de forma clara e estruturada. Cada cenário abordará um contexto específico de uso do sistema, considerando os objetivos dos usuários, os atores envolvidos, os recursos necessários, os episódios que caracterizam o fluxo de interação, bem como as possíveis restrições e exceções que podem ocorrer. 

## Metodologia

A elaboração dos cenários foi realizada de forma colaborativa, com a contribuição de cada integrante do grupo. Cada membro foi responsável por desenvolver um cenário específico, utilizando o formato definido para garantir uniformidade e clareza.

O formato padrão de cada cenário inclui:
	1.	Título: Representa a situação ou funcionalidade abordada.
	2.	Objetivo: Descreve a finalidade do cenário, destacando o valor para os usuários ou stakeholders.
	3.	Contexto: Apresenta o ambiente e as condições iniciais do cenário.
	4.	Atores: Identifica os participantes do cenário, humanos ou sistemas.
	5.	Recursos: Lista os elementos necessários para a execução do cenário.
	6.	Episódios: Descreve o fluxo de eventos, dividindo o cenário em etapas claras.
	7.	Restrições: Aponta as limitações ou condições impostas ao cenário.
	8.	Exceções: Indica situações inesperadas que podem ocorrer e como serão tratadas.

Essa abordagem permite um levantamento detalhado das interações esperadas com o sistema, promovendo uma análise abrangente e uma melhor compreensão do escopo do projeto. Os cenários apresentados neste documento serão revisados e refinados conforme necessário, de acordo com o feedback recebido e a evolução do projeto. 

## Cenários
A tabela 1 descreve o integrante responsável por cada cenário realizado.

<center>
<font size="3"><b>Tabela 1:</b> Integrantes responsáveis por cada cenário</font>

|                Integrante                |                           Cenário                           |
| :--------------------------------------: | :---------------------------------------------------------: |
|   [Carla](https://github.com/ccarlaa)    |                              -                              |
| [Eduarda](https://github.com/erteduarda) | [Quantidade de visualizações em publicações](#visualizacao) |
|    [Davi](https://github.com/Jagaima)    |                        [Salvar um post](#salvos)                     |
|  [João Vitor](https://github.com/Joa0V)  |                              -                              |
| [Renata](https://github.com/Renatinha28) |              [Editar uma publicação](#edição)               |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

### CEN01 - Carla

<a id="visualizacao"></a>

### CEN02 - Quantidade de visualizações em publicações 
A tabela 3 descreve o cenário do requisito funcional não implementado: Quantidade de visualizações em publicações [RF29](https://requisitos-de-software.github.io/2024.2-Bluesky/PerfilUsuario/Tecnicas/Requisitosel/), que foi rastreada pela técnica de elicitação [IS27](https://requisitos-de-software.github.io/2024.2-Bluesky/PerfilUsuario/PerfilUser/) e foi realizado pela integrante [Eduarda](https://github.com/erteduarda).

<center>
<font size="3"><b>Tabela 3:</b> Cenário: Quantidade de visualizações em publicações </font>

|   Item    |                                                                                            Descrição                                                                                             |
| :-------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|  Título   |                                                                     Visualizar quantidade de visualizações de uma publicação                                                                     |
| Objetivo  |                                              Permitir que o usuário veja o número de vezes que sua publicação foi visualizada no aplicativo Bluesky                                              |
| Contexto  |                 Local: Tela do perfil do usuário ou publicação específica no Bluesky <br> Tempo: em tempo real <br> Pré-condição: O usuário ter publicações postadas no Bluesky                  |
|  Atores   |                                                                                       Usuários do Bluesky                                                                                        |
| Recursos  |                                                             Internet <br> Smartphone com o Bluesky instalado e com uma conta logada                                                              |
| Episódios | O usuário seleciona o ícone de perfil <br> O usuário localiza a publicação que deseja verificar <br> O número de visualizações aparece descretamente no cando inferior direito de uma publicação |
| Restrição |                                                          O número de visualizações está disponível apenas para as próprias publicações                                                           |
|  Exceção  |                                                                     Falta de conexão com a internet <br> Aplicativo offline                                                                      |

<font size="3"><b>Autor:</b> <a href="https://github.com/erteduarda">Eduarda Tavares</a></font> 
</center>

### CEN03 - Salvar POST

<a id="salvos"></a>

 tabela 4 descreve o cenário do requisito funcional não implementado: Itens Salvos [RF12](https://requisitos-de-software.github.io/2024.2-Bluesky/PerfilUsuario/Tecnicas/Requisitosel/) que foi rastreado pela elicitação [IS3](https://requisitos-de-software.github.io/2024.2-Bluesky/PerfilUsuario/Tecnicas/Introspeccao/) e [IS22](https://requisitos-de-software.github.io/2024.2-Bluesky/PerfilUsuario/Tecnicas/Introspeccao/)

#### Tabela: Cenário - Salvar um item em "Itens Salvos"

<center>
<font size="3"><b>Tabela 4:</b> Cenário: Salvar Post </font>

| **Item**   | **Descrição**                                                                                                                                                                                      |
|------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Título**  | Salvar um item em "Itens Salvos"                                                                                                                                                                  |
| **Objetivo** | Permitir que o usuário salve um item de interesse para acessá-lo posteriormente em sua lista de "Itens Salvos".                                                                                  |
| **Contexto** | Local: Tela do feed ou de publicação específica no Bluesky  <br> Tempo: Em tempo real  <br> Pré-condição: O usuário estar logado no aplicativo Bluesky.                                           |
| **Atores**   | Usuários do Bluesky                                                                                                                                                                              |
| **Recursos** | Internet <br> Smartphone com Bluesky instalado                                                                                                                                                   |
| **Episódios** | 1. O usuário navega no feed ou acessa uma publicação específica. <br> 2. O usuário identifica um item que deseja salvar. <br> 3. O usuário seleciona o ícone "Salvar" associado à publicação. <br> 4. O item é adicionado à lista de "Itens Salvos". <br> 5. O sistema exibe uma mensagem de confirmação ("Item salvo com sucesso"). |
| **Restrição** | Apenas itens públicos ou disponíveis ao usuário podem ser salvos.                                                                                                                               |
| **Exceção**  | Falta de conexão com a internet <br> Falha ao salvar o item devido a problemas técnicos (mensagem de erro exibida: "Erro ao salvar o item. Tente novamente").                                     |

<font size="3"><b>Autor:</b> <a href="https://github.com/Jagaima">Davi Nobre</a></font> 
</center>


### CEN04 - João Vitor

<a id="edição"></a>

### CEN05 - Fazer uma publicação
A tabela 6 descreve o cenário do requisito funcional não implementado: editar publicações já postadas (encontrado a partir da lista de requisitos elicitados [RF5](https://requisitos-de-software.github.io/2024.2-Bluesky/PerfilUsuario/Tecnicas/Requisitosel/), que foram rastreadas pelas técnicas de elicitação [OB5](https://requisitos-de-software.github.io/2024.2-Bluesky/PerfilUsuario/PerfilUser/) e [IS17](https://requisitos-de-software.github.io/2024.2-Bluesky/PerfilUsuario/Tecnicas/Introspeccao/)) e foi realizado pela integrante [Renata](https://github.com/Renatinha28).

<center>
<font size="3"><b>Tabela 6:</b> Cenário: editar uma publicação </font>

|   Item    |                                                                                                                          Descrição                                                                                                                           |
| :-------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|  Título   |                                                                                                                    Editar uma publicação                                                                                                                     |
| Objetivo  |                                                                                         Permitir que o usuário edite uma publicação já postada no aplicativo Bluesky                                                                                         |
| Contexto  |                                                    Local: Tela do perfil do usuário no Bluesku <br> Tempo: aproximadamente até 1 minuto <br> Pré-condição: O usuário ter a publicação postada no Bluesky                                                     |
|  Atores   |                                                                                                                     Usuários do Bluesky                                                                                                                      |
| Recursos  |                                                                               Internet <br> Smartphone com o Bluesky instalado e com uma conta logada <br> Publicação já feita                                                                               |
| Episódios | O usuário seleciona o ícone de perfil <br> O usuário seleciona sua publicação que  quer editar <br> O usuário seleciona o ícone de edição <br> O usuário faz as correções <br> O usuário clica no ícone de "Salvar edições" <br> O sistema registra a edição |
| Restrição |                                                                                                  O usuário só pode editar suas próprias publicações feitas                                                                                                   |
|  Exceção  |                                                                                                   Falta de conexão com a internet <br> Aplicatico offline                                                                                                    |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

## Bibliográfia
> 1. SERRANO, Milene. Requisitos – Aula 10. 2017. Apresentação de slides. Disponível em: https://aprender3.unb.br/pluginfile.php/2972470/mod_resource/content/1/Aula%2010.pdf. Último acesso em: 01 nov. 2024.

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
            <td>Criação do documento e cenário: publicação </td>
            <td><a href="https://github.com/Renatinha28">Renata Quadros</a></td>
            <td>06/12</td>
            <td><a href="https://github.com/erteduarda">Eduarda Tavares</a></td>
        </tr>
        <tr>
            <td>06/12</td>
            <td>1.1</td>
            <td>Criação do cenário: Quantidade de visualizações em publicações </td>
            <td><a href="https://github.com/erteduarda">Eduarda Tavares</a></td>
            <td></td>
            <td><a href="https://github.com/Jagaima">Davi NobreS</a></td>
        </tr>
        <tr>
            <td>06/12</td>
            <td>1.2</td>
            <td>Cenário: Salvar postagem </td>
            <td><a href="https://github.com/Jagaima">Davi Nobre</a></td>
            <td></td>
            <td><a href="https://github.com/"></a></td>
        </tr>
    </table>
</div>