# GitHub
 Comandos GitHub - Rocketseat | Curso Full Stack Developer
# Comandos Git Essenciais

## Sincronizando o Repositório

- `git pull`: Puxa e modifica o repositório remoto para o repositório local.
- `git push`: Envia as modificações feitas no repositório local para o repositório remoto.


 # Comandos Git Essenciais

## Sincronizando o Repositório

- `git pull`: Puxa e modifica o repositório remoto para o repositório local.
- `git push`: Envia as modificações feitas no repositório local para o repositório remoto.

## Processo de Commit

1. **Antes de enviar suas alterações:**
   - Faça um `git pull` para garantir que seu repositório local esteja atualizado com as últimas mudanças do repositório remoto.
   
2. **Verifique as modificações:**
   - Execute `git status` para visualizar os arquivos que foram modificados.

3. **Adicione as mudanças:**
   - Use `git add <arquivo>` para adicionar os arquivos modificados à área de stage.

4. **Comite as mudanças:**
   - Faça o commit das alterações com `git commit -m "mensagem do commit"`. A mensagem deve descrever brevemente as alterações feitas.

5. **Envie para o repositório remoto:**
   - Depois de comitar, use `git push` para enviar suas alterações para o repositório remoto.

# Comandos Git Adicionais

### Criando um Alias para Facilitar os Comandos
- `git config --global alias.s status` → Cria um atalho para `git status`, permitindo que você use `git s` em vez de `git status`.
