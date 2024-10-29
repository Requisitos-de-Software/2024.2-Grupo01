# Padrão de Uso do Git

## 1. Branch Principal
- **`beta`**: Ponto de partida para todas as branches de desenvolvimento.
- **`main`**: Branch de produção. Apenas uma pessoa autorizada fará o merge de `beta` para `main`.

## 2. Criação de Branches
- Para **novos desenvolvimentos**: `FT-[atividade]`, com o nome da atividade em camelCase. Exemplo: `FT-adicionarRichPicture`.
- Para **correções de erros**: `BUG-[correção]`, com o nome da correção em camelCase. Exemplo: `BUG-corrigirNavbar`.

#### Comandos:
```bash
git checkout beta

git pull origin beta  # Atualizar a beta antes de criar uma nova branch

git checkout -b FT-[atividade]  # Criar a nova branch
```

## 3. Fluxo de Trabalho
- Desenvolva na sua branch específica (FT-[atividade] ou BUG-[correção]).
- Faça commits pequenos e com mensagens claras.
#### Comandos
```bash
git add .

git commit -m "descrição"

git push origin [sua-branch]
```

### 4. Sincronização com beta (antes do merge)
- Antes de enviar sua branch para beta, faça um pull e atualize a beta com as mudanças mais recentes:
#### Comandos
```bash
git checkout beta

git pull origin beta

git merge [nome-da-sua-branch]  # Mesclar as mudanças mais recentes da sua branch na beta

# Resolva os conflitos caso exista

git commit origin beta

git push origin beta
```
