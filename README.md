# FullCycle - Git e Github - Padrões e técnicas avançadas


`apply`: O stash continua salvo e pode ser reutilizado depois.
`pop`: Aplica o conteúdo do stash e remove ele da pilha. Se algo der errado, pode perder o stash.

1. Para criar um stash:
git stash push -m "Descrição opcional"

2. Para visualizar stashes, o valor "0" é sempre o mais rescente:
git stash list

3. Aplicar um stash específico
git stash apply stash@{1}

ou aplicar e remover
git stash pop stash@{1}

4. Deletar um stash específico
git stash drop stash@{1}

5. Deletar todos 
Deletar stash clear

Stash de um ou mais arquivos específicos:
git stash push -m "Alterações em arquivos da home" index.html style.css script.js
git stash push -m "Stash só dos arquivos CSS e JS" *.css *.js



/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"