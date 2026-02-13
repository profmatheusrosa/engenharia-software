# Cheatsheet: Git Essencial

## Configuração Inicial
```bash
git config --global user.name "Seu Nome"
git config --global user.email "seu@email.com"
```

## Iniciando e Clonando
```bash
git init                # Inicia um repositório na pasta atual
git clone [URL]         # Clona um repositório remoto
```

## Fluxo Básico
```bash
git status              # Mostra o estado dos arquivos
git add [arquivo]       # Adiciona arquivo ao stage
git add .               # Adiciona tudo ao stage
git commit -m "msg"     # Salva o snapshot com mensagem
```

## Branches
```bash
git branch              # Lista branches
git branch [nome]       # Cria nova branch
git checkout [nome]     # Muda para a branch
git checkout -b [nome]  # Cria e muda para a branch (atalho)
git merge [branch]      # Funde a branch especificada na atual
```

## Remoto
```bash
git remote add origin [URL] # Conecta ao remoto
git push origin [branch]    # Envia alterações
git pull                    # Baixa e funde alterações
git fetch                   # Baixa alterações sem fundir
```

## Desfazendo Coisas
```bash
git checkout -- [arquivo] # Desfaz alterações locais (antes do stage)
git reset HEAD [arquivo]  # Tira do stage
git revert [commit]       # Cria um commit inverso (seguro)
git reset --hard [commit] # Volta no tempo (perigoso, apaga histórico futuro)
```

## Log
```bash
git log                   # Histórico simples
git log --oneline --graph # Árvore visual no terminal
```
