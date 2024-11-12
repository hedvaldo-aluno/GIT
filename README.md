1. **`git init`**  
   Inicializa um repositório Git em um diretório. Usado uma vez ao começar um novo projeto para criar o repositório local.
   - Exemplo:
     ```bash
     git init
     ```

2. **`git clone`**  
   Clona (copia) um repositório remoto para o ambiente local.
   - Exemplo:
     ```bash
     git clone https://github.com/usuario/repo.git
     ```

3. **`git add`**  
   Adiciona arquivos ao estágio (área de preparação) antes do commit. Usado para selecionar arquivos que serão incluídos no próximo commit.
   - Exemplo:
     ```bash
     git add arquivo.txt
     ```

4. **`git commit`**  
   Cria um ponto de salvamento com as mudanças da área de preparação. É essencial adicionar uma mensagem descritiva com `-m`.
   - Exemplo:
     ```bash
     git commit -m "Mensagem do commit"
     ```

5. **`git status`**  
   Mostra o status dos arquivos no repositório, indicando quais arquivos foram modificados, adicionados ou estão prontos para commit.
   - Exemplo:
     ```bash
     git status
     ```

6. **`git log`**  
   Exibe o histórico de commits do repositório, com detalhes como autor, data e mensagem do commit.
   - Exemplo:
     ```bash
     git log
     ```

7. **`git branch`**  
   Cria, lista ou exclui branches no repositório. Um branch permite que você trabalhe em uma linha separada de desenvolvimento.
   - Exemplo para criar um branch:
     ```bash
     git branch nome-do-branch
     ```

8. **`git checkout`**  
   Permite alternar entre branches ou restaurar arquivos do histórico de commits.
   - Exemplo para trocar de branch:
     ```bash
     git checkout nome-do-branch
     ```

9. **`git merge`**  
   Une as mudanças de um branch ao branch ativo. Normalmente usado para unir um branch de feature ao branch principal.
   - Exemplo:
     ```bash
     git merge nome-do-branch
     ```

10. **`git pull`**  
    Atualiza o repositório local com as últimas mudanças do repositório remoto.
    - Exemplo:
      ```bash
      git pull origin main
      ```

11. **`git push`**  
    Envia commits do repositório local para o repositório remoto.
    - Exemplo:
      ```bash
      git push origin main
      ```

12. **`git stash`**  
    Salva temporariamente as mudanças do seu ambiente de trabalho para você poder trabalhar em outra tarefa e depois restaurá-las.
    - Exemplo:
      ```bash
      git stash
      ```

13. **`git diff`**  
    Mostra as diferenças entre arquivos no repositório. Útil para ver o que foi modificado antes de um commit.
    - Exemplo:
      ```bash
      git diff
      ```
