1. Definire email
    git config --global user.email "enricomaria.pavan@protonmail.com"
    
2. Definire nome
    git config --global user.name "iqwoo"
    
3. Aggiungere il credential helper
    git config --global credential.helper
    
4. Configurare il credential helper
    git credential-store --file ~/Development/.git-credentials store
    protocol=https
    host=github.com
    username=iqwoo
    password=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
    
5. Clonare il repository
    git clone https://github.com/iqwoo/nome_del_repository.git
    
6. Aggiungere tutto
    git add *
    
7. Commit (nel repo locale)
    git commit -m "Descrizione del commit"
    
8. git push origin nome_del_branch
    

