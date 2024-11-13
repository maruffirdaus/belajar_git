# Belajar Git

## init

- > git init

    Menginisiasi sebuah Git repository.

## clone

- > git clone \<url repository\>

    Men-download repository pada url tertentu.

## add

- > git add \<nama file\>

    Menambahkan file tertentu ke dalam index.

- > git add .

    Menambahkan semua file ke dalam index.

## status

- > git status

    Menampilkan status dari repository yang sedang dikerjakan.

## branch

- > git branch

    Menampilkan branch yang sedang aktif dan daftar seluruh branch.

- > git branch -m \<nama branch\>

    Mengganti nama branch yang sedang aktif.

## checkout

- > git checkout \<nama branch\>

    Mengganti branch yang sedang aktif ke branch lain.

- > git checkout -b \<nama branch\>

    Membuat branch baru dan menjadikannya sebagai branch aktif.

## commit

- > git commit -m "\<pesan\>"

    Merekam perubahan ke dalam repository dengan pesan tertentu.

## log

- > git log

    Menampilkan daftar commit yang telah dilakukan.

## reset

- > git reset --hard \<commit hash\>

    Mengembalikan repository ke kondisi suatu commit tertentu.

## revert

- > git revert \<commit hash\>

    Mengembalikan repository ke kondisi suatu commit tertentu dan merekamnya.

## push

- > git push

    Meng-update remote repository dengan local repository pada branch yang sedang aktif.

- > git push -f

    Meng-update remote repository dengan local repository pada branch yang sedang aktif dengan mengabaikan peringatan yang ada (**tidak disarankan**).

- > git push -u origin \<nama branch\>

    Meng-update remote repository dengan local repository pada branch tertentu.

## pull

- > git pull

    Meng-update local repository dengan remote repository.