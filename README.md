### Langkah-langkah didalam membuat project existing dan not existing di github
1. Project Existing
2. Project non Existing 

1.Project Existing
* buat remote github sebagai tempat penyimpanan repository kita dengan command "git remote add origin git@github.com:wali91"
  * dengan SSH (origin sebagai remotenya)
* lakukan pengecekan status git yang ada di repository existing dengan command "git status"
  * ada 3 status pada git
    1.modified : kondisi dimana revisi/perubahan dilakukan perubahan namun belum ditandai atau disimpan di version control
    2.staged : kondisi dimana revisi sudah ditandai, tetapi belum disimpan di version control
    3.commit : kondisi dimana revisi sudah disimpan di version control
* lakukan pembuatan branch apabila ingin melakukan kolaborasi edit program dengan rekan kita 
  * command "git branch rafi" fungsi membuat branch adalah agar kode lama yang kita miliki tetap ada.
* pindahkan branch yang akan kita rubah/tambah 
  * command "git checkout rafi/nama branch"
* apabila terdapat pembaharuan/penambahan maka lakukan staged dengan lakukan add terlebuh dahulu kemudian commit 
  * command untuk add gunakan "git add -a -m  "keterangannya" untuk file yang statusnya modified
* setelah dilakukan perubahan maka lakukan push repository existing dengan 
  * command "git push nama origin git@github.com:wali91 / remote githubnya"
