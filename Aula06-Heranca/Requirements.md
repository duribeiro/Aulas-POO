# Projeto Universidade - Tarefas

## Prática sobre Herança

- [/] Criar o projeto Universidade
- [/] Criar a classe **Pessoa** com os seguintes requisitos:
  - [/] Atributo: `nome`
  - [/] Atributo: `cpf`
  - [/] Método: `exibirDados()`
- [/] Criar interface **Autenticavel** com os seguintes métodos:
  - [/] `autenticar()`
  - [/] `mudarSenha()`
- [ ] Criar a classe **Aluno** (filha de `Pessoa`) com os seguintes requisitos:
  - [ ] Atributo: `matricula`
  - [ ] Método: `autenticar()` (deve verificar se o parâmetro senha possui mais de 8 caracteres e exibir o resultado)
    - *Dica:* `String senha = "qwert12345"; int tamanho = senha.length();`
- [ ] Criar a classe **Professor** (filha de `Pessoa`) com os seguintes requisitos:
  - [ ] Atributo: `departamento`
  - [ ] Método: `autenticar()` (deve exibir a mensagem: "Acesso de professor concedido")
- [ ] Criar a classe **Monitor** (filha de `Aluno`) com os seguintes requisitos:
  - [ ] Atributo: `disciplina`
- [ ] Criar uma instância de **Monitor** e utilizar o método `autenticar()` para ver quantos caracteres tem a senha
- [ ] Criar uma instância de **Professor** e utilizar:
  - [ ] Método `exibirDados()` para ver as informações do Professor
  - [ ] Método `autenticar()`
