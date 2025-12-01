# Relatório Final - Página Colaborativa de Receitas

## Integrantes do Grupo
- Nome do projeto: ReceitasGit--JoaoVitor-MiguelSequeira-JoaoPiteira
- Integrantes: Joao Vitor , Miguel Sequeira , Joao Piteira
- Repositório: https://github.com/JoviNatalli/ReceitasGit--JoaoVitor-MiguelSequeira-JoaoPiteira
  
## Branches Criadas
- As branches foram criadas para indicar receitas de pratos , cada branch tem como função suportar a receita do prato.
- Todos os merges foram feitos via Pull Request (PR). Cada PR passou por revisão de pelo menos um integrante do grupo antes de ser aprovado e deslocado para a main.

## Histórico de Commits
- <img width="1293" height="883" alt="Captura de Tela 2025-12-01 às 01 04 30" src="https://github.com/user-attachments/assets/da3e3948-7dd1-438c-afe5-fb5744cf8875" />


- (https://github.com/JoviNatalli/ReceitasGit--JoaoVitor-MiguelSequeira-JoaoPiteira/graphs/contributors)
- (link para o grafico das contribuições)

## Issues Criadas

- <img width="1201" height="585" alt="Captura de Tela 2025-12-01 às 01 06 37" src="https://github.com/user-attachments/assets/8d12be48-36b6-478d-8f93-34bc876d4305" />

## Pull Requests
Cada PR foi criado a partir de uma branch de receitas e revisado por outro integrante antes do merge.
Após aprovação, o merge foi feito na branch main utilizando a opção “Merge pull request” do GitHub.
PRs incluíam descrição detalhada das alterações e referência às issues correspondentes.

<img width="1440" height="900" alt="Captura de ecrã 2025-12-01, às 1 11 04 AM" src="https://github.com/user-attachments/assets/a5ac97ad-d9c9-4339-8ab2-1e384a8b9656" />


## Conflitos e Resoluções
1. Origem do Conflito Durante o processo de Pull Request, foram detetados conflitos de fusão (merge conflicts) nos ficheiros do projeto. Esta situação ocorreu porque houve alterações concorrentes nas mesmas linhas de código (neste caso, nas receitas) em dois branches distintos:

    O branch de destino (main) sofreu atualizações (commits) no mesmo trecho do ficheiro enquanto o branch de funcionalidade (feature) estava a ser desenvolvido.

    Devido a esta divergência paralela, o algoritmo de merge automático do Git não conseguiu determinar qual a versão prevalente.

2. Metodologia de Resolução A resolução foi efetuada diretamente na interface do GitHub através dos seguintes passos:

    Identificação: Localização dos blocos de código em conflito, delimitados pelos marcadores de versão (<<<<<<<, =======, >>>>>>>).

    Seleção: Análise das divergências e decisão manual pela versão correta a manter (a nova implementação da funcionalidade).

    Limpeza: Remoção do código obsoleto e dos marcadores de conflito gerados pelo Git.

    Consolidação: Realização do commit de resolução (merge commit), permitindo a finalização e integração do Pull Request sem erros.
   
## Dificuldades Enfrentadas
Aprender a organizar branches de forma eficiente.
Ajustar o layout para que todas as receitas ficassem padronizadas.
Resolver conflitos no Git sem perder alterações importantes.

## Principais Comandos Git Utilizados
git clone <repo> → Clonar o repositório.

git checkout -b <branch> → Criar e mudar para uma nova branch.

git add . → Adicionar alterações ao stage.

git commit -m "mensagem" → Salvar alterações com mensagem clara.

git push origin <branch> → Enviar alterações para o GitHub.

git merge <branch> → Mesclar alterações de outra branch.

git pull → Atualizar a branch local com alterações da remota.

## Conclusão

O grupo aprendeu a trabalhar colaborativamente em um repositório GitHub, organizando branches, resolvendo conflitos e revisando PRs. Além disso, melhoramos nossas habilidades em padronizar conteúdo e documentação, criando uma página de receitas clara e funcional. A experiência reforçou a importância de comunicação, organização e boas práticas de versionamento.
