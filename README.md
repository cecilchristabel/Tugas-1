# Tugas-1
## Connect git ke github ##
Bash
> git config --global user.name "cecilchristabel"
> git config --global user.email "cecilia.cs0908@gmail.com"
> ssh-keygen -t ed25519 -C "cecilia.cs0908@gmail.com"
  SSH key tersimpan di C:\Users\<username>\.ssh\id_ed25519.pub

GitHub
> klik profile picture > settings
> SSH and GPG keys > New SSH key
> paste semua isi file id_ed25519.pub ke bagian Key > Add SSH key

Check di bash
> ssh -T git@github.com
> ketik yes


## WORKFLOW ##
> buat repository di Github
> Clone repository : git clone git@github.com:cecilchristabel/Tugas-1.git
> pull : git pull origin main
> Buka folder repository di Visual studio code dan buat file baru
> menambahkan file ke staging area: git add filename atau git add
> commit : git commit -m "message"
> push : git push origin main 
