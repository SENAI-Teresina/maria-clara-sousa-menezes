```markdown
# Tutorial para subir os exercícios:

## Tutorial para Alunos que Já Tinham um Repositório Existente:

### Passo 1: Alterar o Remote do Repositório Existente

1. Abra o terminal (Linux/Mac) ou o Git Bash (Windows).
2. Navegue até o diretório do repositório existente.
3. Execute o seguinte comando para alterar o URL do remote para o novo repositório:

```bash
git remote set-url origin https://github.com/SENAI-Teresina/turma-senai-mobile.git
```

### Passo 2: Criar Diretório Pessoal e Pastas de Aula

1. Dentro do diretório do repositório existente, crie uma pasta com seu nome e sobrenome usando o seguinte comando (substitua "nome-sobrenome" pelo seu nome real):

```bash
mkdir nome-sobrenome
```

2. Navegue para o diretório recém-criado:

```bash
cd nome-sobrenome
```

3. Dentro do seu diretório pessoal, crie pastas para cada aula com as questões correspondentes. Por exemplo, se você está na aula 1, crie uma pasta chamada "aula1". Você pode usar o seguinte comando para criar a pasta:

```bash
mkdir aula1
```

### Passo 3: Adicionar e Enviar Alterações

1. Adicione as alterações ao índice de stage:

```bash
git add .
```

2. Faça um commit das alterações com uma mensagem descritiva:

```bash
git commit -m "Adicionando diretório pessoal e pastas de aula"
```

3. Envie as alterações para o novo repositório remoto:

```bash
git push origin master
```

---

## Tutorial para Alunos que Não Tinham um Repositório:

### Passo 1: Criar um Novo Repositório Local

1. Abra o terminal (Linux/Mac) ou o Git Bash (Windows).
2. Navegue até o diretório onde você deseja inicializar um novo repositório.
3. Execute o seguinte comando para iniciar um novo repositório:

```bash
git init
```

### Passo 2: Adicionar o Novo Remote

1. Execute o seguinte comando para adicionar o novo repositório remoto:

```bash
git remote add origin https://github.com/SENAI-Teresina/turma-senai-mobile.git
```

### Passo 3: Criar Diretório Pessoal e Pastas de Aula

1. Dentro do diretório recém-inicializado, crie uma pasta com seu nome e sobrenome usando o seguinte comando (substitua "nome-sobrenome" pelo seu nome real):

```bash
mkdir nome-sobrenome
```

2. Navegue para o diretório recém-criado:

```bash
cd nome-sobrenome
```

3. Dentro do seu diretório pessoal, crie pastas para cada aula com as questões correspondentes. Por exemplo, se você está na aula 1, crie uma pasta chamada "aula1". Você pode usar o seguinte comando para criar a pasta:

```bash
mkdir aula1
```

### Passo 4: Adicionar e Enviar Alterações

1. Adicione as alterações ao índice de stage:

```bash
git add .
```

2. Faça um commit das alterações com uma mensagem descritiva:

```bash
git commit -m "Adicionando diretório pessoal e pastas de aula"
```

3. Envie as alterações para o novo repositório remoto:

```bash
git push -u origin master
```

---

Esses tutoriais devem ajudar os alunos a criar um repositório, configurá-lo para apontar para o repositório fornecido e organizar suas pastas de acordo com as aulas. Se houver mais alguma dúvida ou precisar de mais assistência, sinta-se à vontade para perguntar!
```

Este é o texto completo em Markdown dos tutoriais para alunos que já tinham um repositório existente e para alunos que não tinham um repositório. Se precisar de mais alguma coisa, estou à disposição para ajudar!
