# FullCycle - Git e Github - Padrões e técnicas avançadas

Unstage file 
This moves the file back to the unstaged state but keeps the changes.
git restore --staged <file>
or the older command:
git reset <file>

Unstage all files
git restore --staged .
or 
git reset

teste1
teste2gig

Discard changes completely (Careful!)
If you want to unstage and revert changes (losing modifications):
git restore <file>      # New way
git checkout -- <file>  # Old way

praticando os comandos...˜`
mais uma alteração