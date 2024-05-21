<!DOCTYPE html>
<html lang="pt">
<head>
<meta charset="UTF-8">
</head>
<body>

<h1>Instalação</h1>
<ul>
  <li><strong>Git</strong>
    <ul>
      <p>https://git-scm.com/</p>
    </ul>
  </li>
  
</ul>
  
<h1>Comandos Git</h1>

<h2>1. Configuração Básica e Gerenciamento de Repositório</h2>
<ul>
  <li><strong>Inicialização</strong>
    <ul>
      <li><code>git init</code> - Inicializa um novo repositório Git local.</li>
      <li><code>git clone</code> - Clona um repositório Git existente.</li>
    </ul>
  </li>
  <li><strong>Configuração</strong>
    <ul>
      <li><code>git config</code> - Configura opções de usuário, como email e nome do usuário.</li>
    </ul>
  </li>
</ul>

<h2>2. Manipulação Básica de Arquivos</h2>
<ul>
  <li><strong>Adicionar e Remover</strong>
    <ul>
      <li><code>git add</code> - Adiciona arquivos à área de staging.</li>
      <li><code>git rm</code> - Remove arquivos do diretório de trabalho e da área de staging.</li>
    </ul>
  </li>
  <li><strong>Status e Diferenças</strong>
    <ul>
      <li><code>git status</code> - Mostra o estado dos arquivos no diretório de trabalho.</li>
      <li><code>git diff</code> - Mostra as diferenças entre arquivos e commits.</li>
    </ul>
  </li>
</ul>

<h2>3. Commits e Alterações</h2>
<ul>
  <li><strong>Committing</strong>
    <ul>
      <li><code>git commit</code> - Grava alterações na base de dados do Git.</li>
    </ul>
  </li>
  <li><strong>Revertendo Mudanças</strong>
    <ul>
      <li><code>git revert</code> - Reverte mudanças de um commit anterior.</li>
      <li><code>git reset</code> - Reseta o HEAD para um estado anterior específico.</li>
      <li><code>git clean</code> - Remove arquivos não rastreados do diretório de trabalho.</li>
    </ul>
  </li>
</ul>

<h2>4. Branching e Merging</h2>
<ul>
  <li><strong>Gerenciamento de Branches</strong>
    <ul>
      <li><code>git branch</code> - Lista, cria ou deleta branches.</li>
    </ul>
  </li>
  <li><strong>Mudança de Branches</strong>
    <ul>
      <li><code>git checkout</code> - Troca de branch ou restaura arquivos do diretório de trabalho.</li>
    </ul>
  </li>
  <li><strong>Merging</strong>
    <ul>
      <li><code>git merge</code> - Junta duas ou mais histórias de desenvolvimento.</li>
    </ul>
  </li>
  <li><strong>Rebasing</strong>
    <ul>
      <li><code>git rebase</code> - Aplica mudanças de uma branch em outra.</li>
    </ul>
  </li>
</ul>

<h2>5. Trabalhando com Repositórios Remotos</h2>
<ul>
  <li><strong>Push e Pull</strong>
    <ul>
      <li><code>git push</code> - Envia alterações locais para o repositório remoto.</li>
      <li><code>git pull</code> - Atualiza o repositório local com as mudanças do repositório remoto.</li>
    </ul>
  </li>
  <li><strong>Gerenciamento de Remotos</strong>
    <ul>
      <li><code>git remote</code> - Gerencia conjuntos de rastreamento de repositórios remotos.</li>
    </ul>
  </li>
</ul>

<h2>6. Inspeção e Comparação</h2>
<ul>
  <li><strong>Logs</strong>
    <ul>
      <li><code>git log</code></li>
    </ul>                              
 </ul>

<h1>Exemplos</h1>

<h2>1. Configuração Básica e Gerenciamento de Repositório</h2>
<h3>Inicialização</h3>
<p><code>git init</code>: Cria um novo repositório local. Use git init no terminal dentro da pasta onde deseja iniciar o repositório.</p>
<p><code>git clone [url]</code>: Copia um repositório Git existente. Por exemplo, <code>git clone https://github.com/usuario/repositorio.git</code>.</p>

<h3>Configuração</h3>
<ul>
    <li><code>git config --global user.name "Seu Nome"</code>: Configura o nome que aparecerá nos seus commits.</li>
    <li><code>git config --global user.email "seuemail@exemplo.com"</code>: Configura o email para os seus commits.</li>
</ul>

<h2>2. Manipulação Básica de Arquivos</h2>
<h3>Adicionar e Remover</h3>
<ul>
    <li><code>git add arquivo.txt</code>: Adiciona um arquivo específico à área de staging.</li>
    <li><code>git rm arquivo.txt</code>: Remove um arquivo do diretório de trabalho e da área de staging.</li>
</ul>

<h3>Status e Diferenças</h3>
<ul>
    <li><code>git status</code>: Mostra o status atual do repositório, incluindo mudanças que não foram commitadas.</li>
    <li><code>git diff</code>: Mostra as diferenças de conteúdo entre a área de staging e os últimos commits.</li>
</ul>

<h2>3. Commits e Alterações</h2>
<h3>Committing</h3>
<p><code>git commit -m "Mensagem de commit"</code>: Faz um commit dos arquivos que estão na área de staging com uma mensagem explicando as mudanças.</p>

<h3>Revertendo Mudanças</h3>
<ul>
    <li><code>git revert [hash-do-commit]</code>: Reverte as mudanças introduzidas por um commit específico sem alterar o histórico.</li>
    <li><code>git reset --hard [hash-do-commit]</code>: Reseta o repositório para um commit específico, descartando todas as mudanças posteriores.</li>
    <li><code>git clean -f</code>: Remove arquivos não rastreados (que não estão no staging).</li>
</ul>

<h2>4. Branching e Merging</h2>
<h3>Gerenciamento de Branches</h3>
<ul>
    <li><code>git branch nova-branch</code>: Cria uma nova branch chamada nova-branch.</li>
    <li><code>git branch -d nome-da-branch</code>: Deleta a branch especificada.</li>
</ul>

<h3>Mudança de Branches</h3>
<ul>
    <li><code>git checkout nome-da-branch</code>: Muda para a branch especificada.</li>
</ul>

<h3>Merging</h3>
<ul>
    <li><code>git merge nome-da-branch</code>: Combina a branch especificada com a branch atual.</li>
</ul>

<h3>Rebasing</h3>
<ul>
    <li><code>git rebase nome-da-branch</code>: Aplica os commits de uma branch sobre outra.</li>
</ul>

<h2>5. Trabalhando com Repositórios Remotos</h2>
<h3>Push e Pull</h3>
<ul>
    <li><code>git push origin master</code>: Envia os commits da branch master para o repositório remoto origin.</li>
    <li><code>git pull origin master</code>: Atualiza sua branch local master com as mudanças do repositório remoto origin.</li>
</ul>

<h3>Gerenciamento de Remotos</h3>
<ul>
    <li><code>git remote add origin [url]</code>: Adiciona um novo repositório remoto chamado origin.</li>
    <li><code>git remote remove origin</code>: Remove o repositório remoto chamado origin.</li>
</ul>

<h2>6. Inspeção e Comparação</h2>
<h3>Logs</h3>
<ul>
    <li><code>git log</code>: Exibe o log de commits.</li>
    <li><code>git log --oneline</code>: Exibe o log de commits de forma resumida, em uma linha cada.</li>
</ul>

<h3>Blame</h3>
<ul>
    <li><code>git blame arquivo.txt</code>: Mostra quem modificou cada linha de um arquivo.</li>
</ul>

<h3>Stashing</h3>
<ul>
    <li><code>git stash</code>: Guarda as mudanças não commitadas temporariamente.</li>
    <li><code>git stash pop</code>: Aplica as mudanças guardadas pelo último git stash.</li>
</ul>

<h2>7. Comandos Avançados</h2>
<h3>Cherry-Picking</h3>
<ul>
    <li><code>git cherry-pick [hash-do-commit]</code>: Aplica o commit especificado na branch atual.</li>
</ul>

<h3>Submódulos</h3>
<ul>
    <li><code>git submodule add [url] [diretório]</code>: Adiciona um submódulo ao seu repositório.</li>
</ul>

<h3>Reflog</h3>
<ul>
    <li><code>git reflog</code>: Exibe um log de onde os ponteiros de branches estiveram recentemente, útil para recuperação de dados.</li>
</ul>

<p>Cada um desses comandos deve ser executado em um terminal ou linha de comando na pasta do seu projeto Git.</p>


<h1>Importância do Branching e Merging no Desenvolvimento de Software</h1>
<p>O branching e o merging são fundamentais no gerenciamento de versões em projetos de desenvolvimento de software, especialmente quando múltiplas pessoas estão trabalhando no mesmo projeto. Eles oferecem vários benefícios cruciais:</p>

<h2>Isolamento de Recursos</h2>
<p>O branching permite que diferentes recursos ou funcionalidades sejam desenvolvidos em paralelo, sem interferir um no trabalho do outro. Cada branch atua como um ambiente isolado, onde os desenvolvedores podem experimentar, desenvolver, testar e aperfeiçoar código sem afetar o código principal ou outras branches.</p>

<h2>Colaboração Melhorada</h2>
<p>Branching facilita a colaboração entre várias equipes trabalhando em diferentes aspectos de um projeto. Por exemplo, enquanto uma equipe pode trabalhar em novas funcionalidades em uma branch, outra pode focar em corrigir bugs em outra, otimizando a eficiência e a produtividade.</p>

<h2>Controle de Versão Estável</h2>
<p>O merging é usado para reintegrar o código desenvolvido em branches separadas de volta à branch principal (geralmente chamada de "master" ou "main"). Isso permite que as atualizações e melhorias sejam consolidadas de forma controlada e testada, mantendo a integridade do código principal estável.</p>

<h2>Redução de Conflitos</h2>
<p>Merging ajuda a gerenciar conflitos de código de maneira organizada. Quando múltiplas alterações são feitas no mesmo bloco de código por diferentes branches, o Git fornece ferramentas e processos (como merge conflicts) para ajudar os desenvolvedores a resolver essas discrepâncias manualmente, garantindo que o código final seja o mais otimizado e funcional possível.</p>

<h2>Histórico de Desenvolvimento Claro</h2>
<p>Usar branches e merges ajuda a manter um histórico de desenvolvimento claro e gerenciável. Isso permite que as equipes acompanhem mudanças específicas, entendam a evolução do projeto e revertam facilmente para versões anteriores se necessário.</p>

<p>Esses processos são essenciais para projetos grandes e complexos, pois permitem que as equipes trabalhem de maneira descentralizada enquanto mantêm um sistema centralizado de controle de versões, facilitando a gestão de código e diminuindo os riscos de erros em produção.</p>
