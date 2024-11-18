## Introdução 

Nesta etapa iniciaremos uma das técnicas denominada introspecção. Na introspecção uma das pessoas do projeto encarregadas da construção da elicitação de requisitos vai realizar uma analise pessoal profunda sem Stackholders ou usuários para elicitar novos requisitos através de um exercício de imaginação de uma situação hipotética. 

## Metodologia 

O processo realizado pelo grupo para instrospecção foi divido em dois pensamentos, para os participantes do grupo [Davi Nobre](https://github.com/Jagaima) e [João Ribeiro](https://github.com/Joa0V). Quando o desenvolvimento individual for feito separaremos em requisitos não funcionais e funcionais (RNFx e RFx especificamente, onde x é o número de seu ID). As tabelas devem ser separadas entre esses requisitos e deve haver as respostas (se foram ou não implementados).

## Introspeção de Davi Nobre.

Para minha introspeção eu imaginei o seguinte cenário: Eu coordeno um clube do livro, gostaria de buscar posts relacionados a reviews de livro e poder salvar as reviews de livros que eu achar importante para visualizar no futuro. 



## Requisitos elicitados

### Requisitos Funcionais
    Tabela 1: Requisitos Funcionais. 
| **ID** | **Descrição** | **Autor da Elicitação** | **Implementado** |
|--------|---------------|-------------------------|------------------|
| **RF01** | O usuário deve ser capaz de se registrar ou fazer login na plataforma Bluesky para acessar suas funcionalidades. | Davi | SIM |
| **RF02** | O sistema deve permitir que o usuário faça buscas por posts relacionados ao seu interesse, usando palavras-chave, hashtags ou filtros específicos. | Davi | SIM |
| **RF03** | O usuário deve poder salvar Posts de interesse em uma seção dedicada para consulta futura. | Davi | NÃO |
| **RF04** | O sistema deve disponibilizar uma seção onde o usuário possa visualizar e gerenciar todas os posts salvos, com opções de ordenação por data, e/ou hashtag . | Davi | NÃO|
| **RF05** | O sistema deve permitir que o usuário crie ou use feeds (micro fóruns de posts) de terceiros personalizados com base em critérios como tipo de post, usuários ou hashtags relacionadas. | Davi | SIM|
| **RF06** | O usuário deve poder criar seus próprios posts ,e compartilhá-los com um feed específico ou a comunidade em geral. | Davi |SIM|
| **RF07** | O sistema deve notificar o usuário sobre novos posts com base nos interesses e feeds personalizados configurados. | Davi |NÃO|
| **RF08** | Os usuários devem poder interagir com postagens por meio de comentários, curtidas e respostas. | Davi |SIM|
| **RF09** | O sistema deve permitir a aplicação de filtros avançados, como autor do post, data de publicação ou popularidade, para melhorar a experiência de busca. | Davi | NÃO|

<p align="center">Autor: <a href="https://github.com/Jagaima">Davi Nobre</a></p> 

### Requisitos Não Funcionais

    Tabela 2: Requisitos Não Funcionais. 
| **ID** | **Descrição** | **Autor da Elicitação** | **Implementado** |
|--------|---------------|-------------------------|------------------|
| **RNF01** | O sistema deve processar buscas e carregar feeds personalizados rapidamente, mesmo com grandes volumes de dados, garantindo uma experiência fluida para o usuário. | Davi | SIM|
| **RNF02** | O sistema deve ser capaz de crescer e suportar um número crescente de usuários e posts sem comprometer o desempenho. | Davi | NÃO|
| **RNF03** | Todos os dados sensíveis, como informações de login e reviews salvas, devem ser protegidos por criptografia. O sistema deve implementar autenticação segura e proteger contra ataques como SQL injection e XSS. | Davi |SIM|
| **RNF04** | A interface do usuário deve ser intuitiva e fácil de usar, com opções bem definidas para buscar, salvar e visualizar postagens. O design deve ser centrado no usuário e acessível a diferentes perfis de idade. | Davi |SIM|
| **RNF05** | O sistema deve ter alta disponibilidade, operando continuamente com mínimas interrupções e implementando redundância de servidores para garantir estabilidade. | Davi | NÃO|
| **RNF06** | O sistema deve ser compatível com dispositivos móveis modernos, oferecendo uma interface responsiva e acessível em diferentes tamanhos de tela. | Davi |SIM|
| **RNF07** | O sistema deve permitir que o usuário personalize seus feeds e notificações facilmente, com opções para ajustar preferências de conteúdo e formato. | Davi | SIM|
| **RNF08** | O sistema deve garantir a privacidade do usuário, permitindo que ele controle quem pode ver suas atividades e reviews, com políticas claras sobre coleta e uso de dados. | Davi | SIM|

<p align="center">Autor: <a href="https://github.com/Jagaima">Davi Nobre</a></p> 


## Referência Bibliográfica

> SERRANO, Milene, SERRANO, Maurício. Requisitos (Aula 07): Elicitação, Modelagem e Análise. UnB Gama, Brasília, 2024. Disponível em <https://aprender3.unb.br/pluginfile.php/2972449/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf> </br>

## :round_pushpin: Histórico de Versão 
<div align="center">
    <table style="margin: auto;">
        <tr>
            <th>Data</th>
            <th>Versão</th>
            <th>Descrição</th>
            <th>Autor</th>
            <th>Data de Revisão</th>
            <th>Revisor</th>
        </tr>
        <tr>
            <td>17/11</td>
            <td>1.0</td>
            <td>Criação inicial do documento</td>
            <td><a href="https://github.com/Jagaima">Davi</a></td>
            <td></td>
            <td><a</a></td>
         </tr>  
        </table>
    </div>
