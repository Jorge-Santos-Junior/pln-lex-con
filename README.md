# 📖 Guia de Início Rápido do Estudante

Bem-vindo ao repositório do projeto **PLN-LEX-CON**!

Siga este passo a passo para configurar o seu ambiente local e começar a trabalhar na branch da sua respectiva turma.

## 🛠️ Passo 1: Preparar o Diretório Local

Antes de baixar o projeto, crie uma pasta no seu computador para organizar os arquivos do projeto.

1. Abra o terminal no seu computador.

2. Crie uma nova pasta chamada `pln-lex-con` e acesse-a:

```
# Cria a pasta do projeto
mkdir pln-lex-con

# Navegue até a pasta do projeto
cd pln-lex-con

```

## 📥 Passo 2: Clonar o Repositório

Com a pasta `pln-lex-con` aberta no terminal, clone o repositório oficial do GitHub:

```
# Clona o repositório dentro da pasta atual
git clone https://github.com/Jorge-Santos-Junior/pln-lex-con.git .

```

*(Nota: O ponto `.` ao final garante que o projeto seja descompactado diretamente dentro da pasta `pln-lex-con`).*

## 🔀 Passo 3: Entrar na Branch da Sua Turma

Cada turma possui um espaço de trabalho próprio e isolado no Git. Alterne para a branch correspondente ao seu ano:

* **1º Ano (Motor Simbólico):**

  ```
  git checkout turma-1ano
  
  ```

* **2º Ano (Paradigma Estatístico):**

  ```
  git checkout turma-2ano
  
  ```

* **3º Ano (Paradigma Neural / RAG):**

  ```
  git checkout turma-3ano
  
  ```

* **4º Ano (Integração e Avaliação):**

  ```
  git checkout turma-4ano
  
  ```

## 🚀 Passo 4: Fluxo Diário de Trabalho

Após realizar suas alterações ou criar novos scripts nas pastas destinadas à sua turma, envie suas contribuições para o GitHub:

```
# 1. Adicione os arquivos alterados
git add .

# 2. Registre o commit com uma mensagem descritiva
git commit -m "feat(modulo): descreva brevemente a alteração realizada"

# 3. Envie para o GitHub na branch da sua turma
git push origin turma-Xano

```

*(Substitua `turma-Xano` pelo nome exato da branch da sua turma, ex: `turma-1ano`).*
