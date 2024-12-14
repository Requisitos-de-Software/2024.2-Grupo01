## Introdução
As histórias de usuário são fundamentais no desenvolvimento ágil de software, especialmente em abordagens como o Scrum, pois auxiliam na captura de necessidades do usuário de forma simples e objetiva. Elas descrevem, sob a perspectiva do usuário final, o que é esperado do sistema, proporcionando um entendimento compartilhado entre as partes interessadas no projeto. Além disso, permitem um alinhamento claro dos objetivos do produto, ajudando a equipe de desenvolvimento a priorizar funcionalidades que gerem maior valor ao usuário. Este documento apresenta as histórias de usuário do aplicativo Bluesky, criadas a partir de uma análise criteriosa dos requisitos e baseadas nas necessidades identificadas durante o processo de elicitação.

## Objetivo
O principal objetivo deste artefato é documentar as histórias de usuário do aplicativo Bluesky, garantindo que:

1. As necessidades e expectativas dos usuários sejam compreendidas e traduzidas em funcionalidades claras e acionáveis.

2. O desenvolvimento seja orientado pela perspectiva do usuário, mantendo o foco na entrega de valor.

3. As funcionalidades sejam priorizadas de acordo com a relevância para os usuários finais e os objetivos do projeto.

4. A comunicação entre a equipe de desenvolvimento e os stakeholders seja clara e eficiente, reduzindo ambiguidades e alinhando expectativas.

Em última análise, este artefato busca assegurar que o Bluesky atenda de forma eficaz às demandas dos usuários, promovendo uma experiência satisfatória e funcional.

## Metodologia
Para a construção das histórias de usuário do aplicativo Bluesky, foi seguido um processo estruturado em três etapas principais:

1.	Elicitação de Requisitos: Aplicamos técnicas de brainstorming, observação, introspecção e questionários para identificar as necessidades dos usuários e requisitos funcionais e não funcionais do aplicativo. As informações coletadas foram organizadas e analisadas para garantir uma compreensão abrangente do contexto do sistema.

2.	Rastreabilidade e Priorização: Os requisitos identificados foram rastreados e associados a funcionalidades específicas, assegurando que nenhum aspecto importante fosse negligenciado. Para priorizar as funcionalidades, utilizamos técnicas como Three Level Scale, First Things Firts e $100.

3.	Elaboração das Histórias de Usuário: As histórias foram redigidas utilizando um formato padrão (como usuário, eu quero… para que…), acompanhadas de critérios de aceitação claros para cada funcionalidade; As histórias foram validadas com base no feedback de stakeholders e ajustadas conforme necessário para refletir com precisão as expectativas dos usuários.

## Participantes
Cada história de usuário foi validada com o PO. Com o objetivo de organização, a tabela 1 mostra a história de usuário, o integrante responsável por tal, Product Owner e usuário participantes. Todos os requisitos elicitados estão presentes no artefato [Requisitos Elicitados](../../PerfilUsuario/Tecnicas/Requisitosel.md/#requisitos-elicitados). 


<center>
<font size="3"><b>Tabela 1:</b> Desenvolvedor e PO</font>

| História de Usuario | Desenvolvedor | Product Owner | Usuário |
|:-------------------:|:-------------:|:-------------:|:--------:|
| US01 até US07  | [Renata](https://github.com/Renatinha28) | - | - |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

## Histórias de Usuário

A tabela 2 mostra o modelo seguido para cada história de usuário realizada.

<center>
<font size="3"><b>Tabela 2:</b>Modelo para História de Usuário</font>

| Item | Descrição |
|:----:|:---------:|
| USx(número de identificação) | USx |
| Tema | Título |
| Descrição | Eu, como [tipo de usuário], desejo [ação desejada] para [objetivo] |
| Critérios de Aceitação | - [Critério 1] <br> - [Critério 2] <br> ... |
| Prioridade PO | Alta, Média, Baixa |
| Prioridade Usuário | Alta, Média, Baixa |
| Status | Se a história foi Validada ou não pelo usuário |
| Rastreabilidade | Código do requisito |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

### Histórias de Usuário : requisitos elicitados 1 até 7

As tabelas 3 até 9 descrevem as histórias de usuário realizadas pela integrante [Renata Quadros](https://github.com/Renatinha28)

<center>
<font size="3"><b>Tabela 3:</b>História de Usuário: Login</font>

| Item | Descrição |
|:----:|:---------:|
| USx(número de identificação) | US01 |
| Tema | Fazer login |
| Descrição | Eu, como usuário interessado em utilizar o Bluesky, desejo realizar o login para acessar o aplicativo |
| Critérios de Aceitação | - O sistema deve permitir o login automatico caso o usuário tenha salvo <br> - O sistema deve redirecionar para tela inicial do app após a confirmação do login <br> - O sistema deve permitir o acesso apenas se o usuário e a senha estiverem corretos |
| Prioridade PO | Alta |
| Prioridade Usuário | Alta |
| Status | Validada |
| Rastreabilidade | [OB1](../../PerfilUsuario/Tecnicas/Observacao.md), [IS1](../../PerfilUsuario/Tecnicas/Introspeccao.md), [IS10](../../PerfilUsuario/Tecnicas/Introspeccao.md) |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

<center>
<font size="3"><b>Tabela 4:</b>História de Usuário: Recuperar senha</font>

| Item | Descrição |
|:----:|:---------:|
| USx(número de identificação) | US02 |
| Tema | Recuperar senha |
| Descrição | Eu, como usuário, desejo recuperar minha senha para acessar o aplicativo Bluesky |
| Critérios de Aceitação |  - O sistema deve exibir um botão "Esqueci minha senha" na tela de login <br> - O usuário deve receber um e-mail com um link de redefinição de senha no e-mail cadastrado na conta <br> - O link enviado deve expirar após 10 minutos|
| Prioridade PO | Alta |
| Prioridade Usuário | Alta |
| Status | Validada |
| Rastreabilidade | [OB2](../../PerfilUsuario/Tecnicas/Observacao.md) |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

<center>
<font size="3"><b>Tabela 5:</b>História de Usuário: Acessar novos conteúdos</font>

| Item | Descrição |
|:----:|:---------:|
| USx(número de identificação) | US03 |
| Tema | Acessar novos conteúdos rapidamente |
| Descrição | Eu, como usuário do Bluesky, desejo acessar novos conteúdos rapidamente para ficar atualizado |
| Critérios de Aceitação | - O sistema deve atualizar o feed automaticamente ao abrir o aplicativo <br> - O usuário deve ter a opção de atualizar o feed manualmente  |
| Prioridade PO | Média |
| Prioridade Usuário | Média |
| Status | Validada |
| Rastreabilidade | [OB3](../../PerfilUsuario/Tecnicas/Observacao.md) |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

<center>
<font size="3"><b>Tabela 6:</b>História de Usuário: realizar postagens</font>

| Item | Descrição |
|:----:|:---------:|
| USx(número de identificação) | US04 |
| Tema | Realizar postagens |
| Descrição | Eu, como usuário do Bluesky, desejo fazer postagens para compartilhar informações com outros usuários do Bluesky |
| Critérios de Aceitação | - O sistema deve permitir a criação de postagens com texto e imagens <br> - O botão "publicar" só deve ser habilitado após o preenchimento do campo de texto ou adição de imagem |
| Prioridade PO | Alta |
| Prioridade Usuário | Alta |
| Status | Validada |
| Rastreabilidade | [OB4](../../PerfilUsuario/Tecnicas/Observacao.md) |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

<center>
<font size="3"><b>Tabela 7:</b>História de Usuário: Editar publicações </font>

| Item | Descrição |
|:----:|:---------:|
| USx(número de identificação) | US05 |
| Tema | Editar postagens |
| Descrição | Eu, como usuário do Bluesky, desejo editar postagens para corrigir erros |
| Critérios de Aceitação | O sistema deve permitir edições de postagens já publicadas <br> - O sistema deve exibir uma mensagem de confirmação após a confirmação da edição |
| Prioridade PO | Alta |
| Prioridade Usuário | Alta |
| Status | Validada|
| Rastreabilidade | [OB5](../../PerfilUsuario/Tecnicas/Observacao.md) e [IS17](../../PerfilUsuario/Tecnicas/Introspeccao.md) |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

<center>
<font size="3"><b>Tabela 8:</b>História de Usuário: Buscar por posts com palavras-chaves </font>

| Item | Descrição |
|:----:|:---------:|
| USx(número de identificação) | US6 |
| Tema |  Busca com palavras-chaves |
| Descrição | Eu, como usuário do Bluesky, desejo realizar buscas com palavras-chaves para encontrar conteúdos com facilidade |
| Critérios de Aceitação | - O sistema deve permitir ao usuário interir palavras chaves na barra de busca <br> - Os resultados da busca devem ser exibidos ordenados por relevância |
| Prioridade PO | Média |
| Prioridade Usuário | Média |
| Status | Validada |
| Rastreabilidade | [OB6](../../PerfilUsuario/Tecnicas/Observacao.md) e [IS2](../../PerfilUsuario/Tecnicas/Introspeccao.md) |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

<center>
<font size="3"><b>Tabela 9:</b>História de Usuário: Favoritar posts ou comunidades </font>

| Item | Descrição |
|:----:|:---------:|
| USx(número de identificação) | US7 |
| Tema | Favoritar posts |
| Descrição | Eu, como usuário do Bluesky, desejo favoritar posts para voltar a encontra-los quando quiser |
| Critérios de Aceitação |  - O sistema deve permitir ao usuário favoritar posts por meio de um ícone <br> - Os itens favoritados devem ser salvos na aba de "Favoritos" |
| Prioridade PO | Média |
| Prioridade Usuário | Média |
| Status | Validada |
| Rastreabilidade | [OB7](../../PerfilUsuario/Tecnicas/Observacao.md) |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

#### Gravação com o PO

#### Gravação com o Usuário

## Bibliografia

> 1. DIOGO. Guia definitivo para Histórias de Usuário - Product Management. YouTube, 11 jul. 2022. Disponível em: https://www.youtube.com/watch?v=pLJ3LxR292w.

> 2. 2023.2 Economia DF. Econimia DF, 2023. Disponível em: https://requisitos-de-software.github.io/2023.2-Economia-DF/. Acesso em: 15, nov. 2024.

> 3. Meu INSS, 2024.1. Disponível em: https://vitorfleonardo.github.io/2024.1-Meu-INSS/. Acesso em 16, nov. 2024.

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
            <td>Criação do documento e histórias de usuário de 1 até 7 </td>
            <td><a href="https://github.com/Renatinha28">Renata Quadros</a></td>
            <td>15/12</td>
            <td><a href="https://github.com/erteduarda">Eduarda Tavares</a></td>
        </tr>
    </table>
</div>