# Boas práticas em Commit

Os commits são registros das alterações realizadas no projeto.  
Uma boa prática é escrever mensagens curtas, objetivas e padronizadas, para facilitar a leitura do histórico e o entendimento do que foi feito pela equipe.

---

## Tipos mais usados

### `feat`
Usado quando o commit adiciona uma **nova funcionalidade** ou entrega um **novo requisito**.
**Exemplo:**
feat: cadastro de aluno

### `fix`
Usado quando o commit corrige um erro, **bug** ou **comportamento incorreto no sistema**.
**Exemplo:**
fix: corrige validação de email

### `refactor`
Usado quando o código é **reorganizado** ou **melhorado** sem mudar o comportamento da funcionalidade.
**Exemplo:**
refactor: organiza service de livros

### `Exemplo Completo de commit`

git commit -m "feat: Entrega Atv1.cs" -m"Atv1 lógica trocando nota númerica por mensão"

git commit -m "fix: Correção Atv1.cs" -m"Calculo média incorreto, inserindo prioridade nos cálculos"

git commit -m "refactor: Atv2.cs" -m"Atv2 aplicando funções para separar cálculos"