# examen
examen primer periodo

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio (master)
$ git clone https://github.com/JDiego24/examen.git
Cloning into 'examen'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Casa/
        Certificado Vacuna.pdf
        Killing Floor 2.url
        Prueba/
        Roblox Player.lnk
        Roblox Studio.lnk
        Visual Studio Code.lnk
        desktop.ini
        examen/

nothing added to commit but untracked files present (use "git add" to track)

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio (master)
$ cd examen

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (main)
$ git branch produccion

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (main)
$ git branch ventas

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (main)
$ git branch recurso_humano

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (main)
$ git branch
* main
  produccion
  recurso_humano
  ventas

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (main)
$ git -m commit "agregando ramas"
unknown option: -m
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--config-env=<name>=<envvar>] <command> [<args>]

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (main)
$ git commit -m "agregando ramas"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (main)
$ git push
Everything up-to-date

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (main)
$ git checkout produccion
Switched to branch 'produccion'

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (produccion)
$ git status
On branch produccion
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        materia prima.txt
        produccionfinal.txt
        producto.jpg

nothing added to commit but untracked files present (use "git add" to track)

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (produccion)
$ git add .

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (produccion)
$ git push -u origin produccion
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'produccion' on GitHub by visiting:
remote:      https://github.com/JDiego24/examen/pull/new/produccion
remote:
To https://github.com/JDiego24/examen.git
 * [new branch]      produccion -> produccion
branch 'produccion' set up to track 'origin/produccion'.

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (produccion)
$ git checkout ventas
Switched to branch 'ventas'
A       materia prima.txt
A       produccionfinal.txt
A       producto.jpg

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (ventas)
$ git status
On branch ventas
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   materia prima.txt
        new file:   produccionfinal.txt
        new file:   producto.jpg

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Empleados.txt
        tiendas.txt


bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (ventas)
$ git add . tiendas.txt

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (ventas)
$ git commit -m "Agregando tiendas a ventas"
[ventas 8249247] Agregando tiendas a ventas
 5 files changed, 8 insertions(+)
 create mode 100644 Empleados.txt
 create mode 100644 materia prima.txt
 create mode 100644 produccionfinal.txt
 create mode 100644 producto.jpg
 create mode 100644 tiendas.txt

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (ventas)
$ git push -u origin ventas
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 12 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 112.87 KiB | 10.26 MiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'ventas' on GitHub by visiting:
remote:      https://github.com/JDiego24/examen/pull/new/ventas
remote:
To https://github.com/JDiego24/examen.git
 * [new branch]      ventas -> ventas
branch 'ventas' set up to track 'origin/ventas'.

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (ventas)
$ git checkout recurso_humano
Switched to branch 'recurso_humano'

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (recurso_humano)
$ git status
On branch recurso_humano
nothing to commit, working tree clean

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (recurso_humano)
$ git push -u origin recurso_humano
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'recurso_humano' on GitHub by visiting:
remote:      https://github.com/JDiego24/examen/pull/new/recurso_humano
remote:
To https://github.com/JDiego24/examen.git
 * [new branch]      recurso_humano -> recurso_humano
branch 'recurso_humano' set up to track 'origin/recurso_humano'.

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (recurso_humano)
$ git checkout recurso_humano
Already on 'recurso_humano'
Your branch is up to date with 'origin/recurso_humano'.

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (recurso_humano)
$ git status
On branch recurso_humano
Your branch is up to date with 'origin/recurso_humano'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Empleados.txt
        materia prima.txt
        produccionfinal.txt
        producto.jpg
        tiendas.txt

nothing added to commit but untracked files present (use "git add" to track)

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (recurso_humano)
$ git add Empleados.txt
warning: in the working copy of 'Empleados.txt', LF will be replaced by CRLF the next time Git touches it

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (recurso_humano)
$ git status
On branch recurso_humano
Your branch is up to date with 'origin/recurso_humano'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Empleados.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        materia prima.txt
        produccionfinal.txt
        producto.jpg
        tiendas.txt


bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (recurso_humano)
$ git push -u origin recurso_humano
Everything up-to-date
branch 'recurso_humano' set up to track 'origin/recurso_humano'.

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (recurso_humano)
$ git checkout produccion
Switched to branch 'produccion'
A       Empleados.txt
Your branch is up to date with 'origin/produccion'.

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (produccion)
$ git status
On branch produccion
Your branch is up to date with 'origin/produccion'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Empleados.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        materia prima.txt
        produccionfinal.txt
        producto.jpg
        tiendas.txt


bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (produccion)
$ git add materia prima.txt
fatal: pathspec 'materia' did not match any files

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (produccion)
$ git add ^C

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (produccion)
$ git add .
warning: in the working copy of 'tiendas.txt', LF will be replaced by CRLF the next time Git touches it

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (produccion)
$ git status
On branch produccion
Your branch is up to date with 'origin/produccion'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Empleados.txt
        new file:   materia prima.txt
        new file:   produccionfinal.txt
        new file:   producto.jpg
        new file:   tiendas.txt


bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (produccion)
$ git commit -m "Agregando productos a produccion"
[produccion 6f547cf] Agregando productos a produccion
 5 files changed, 8 insertions(+)
 create mode 100644 Empleados.txt
 create mode 100644 materia prima.txt
 create mode 100644 produccionfinal.txt
 create mode 100644 producto.jpg
 create mode 100644 tiendas.txt

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (produccion)
$ git push -u origin produccion
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 12 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 112.87 KiB | 8.68 MiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/JDiego24/examen.git
   076c3c1..6f547cf  produccion -> produccion
branch 'produccion' set up to track 'origin/produccion'.

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (produccion)
$ dir
Empleados.txt  materia\ prima.txt   producto.jpg
README.md      produccionfinal.txt  tiendas.txt

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (produccion)
$ git rm Empleados.txt
rm 'Empleados.txt'

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (produccion)
$ dir
README.md  materia\ prima.txt  produccionfinal.txt  producto.jpg  tiendas.txt

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (produccion)
$ git rm tiendas.txt
rm 'tiendas.txt'

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (produccion)
$ git commit -m "volviendo a agregar productos a productos"
[produccion fa54640] volviendo a agregar productos a productos
 2 files changed, 8 deletions(-)
 delete mode 100644 Empleados.txt
 delete mode 100644 tiendas.txt

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (produccion)
$ git push -u origin produccion
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 240 bytes | 240.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/JDiego24/examen.git
   6f547cf..fa54640  produccion -> produccion
branch 'produccion' set up to track 'origin/produccion'.

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (produccion)
$ git checkout ventas
Switched to branch 'ventas'
Your branch is up to date with 'origin/ventas'.

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (ventas)
$ dir
Empleados.txt  materia\ prima.txt   producto.jpg
README.md      produccionfinal.txt  tiendas.txt

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (ventas)
$ git rm empleados.txt
fatal: pathspec 'empleados.txt' did not match any files

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (ventas)
$ git rm Empleados.txt
rm 'Empleados.txt'

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (ventas)
$ git rm producto.jpg
rm 'producto.jpg'

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (ventas)
$ dir
README.md  materia\ prima.txt  produccionfinal.txt  tiendas.txt

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (ventas)
$ git rm materia\ prima.txt
rm 'materia prima.txt'

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (ventas)
$ git rm produccionfinal.txt
rm 'produccionfinal.txt'

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (ventas)
$ dir
README.md  tiendas.txt

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (ventas)
$ git status
On branch ventas
Your branch is up to date with 'origin/ventas'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        deleted:    Empleados.txt
        deleted:    materia prima.txt
        deleted:    produccionfinal.txt
        deleted:    producto.jpg


bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (ventas)
$ git commit -m "Agregando la tienda a la venta"
[ventas 97a619f] Agregando la tienda a la venta
 4 files changed, 5 deletions(-)
 delete mode 100644 Empleados.txt
 delete mode 100644 materia prima.txt
 delete mode 100644 produccionfinal.txt
 delete mode 100644 producto.jpg

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (ventas)
$ git push -u origin ventas
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 284 bytes | 142.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/JDiego24/examen.git
   8249247..97a619f  ventas -> ventas
branch 'ventas' set up to track 'origin/ventas'.

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (ventas)
$ git checkout recurso_humano
Switched to branch 'recurso_humano'
Your branch is up to date with 'origin/recurso_humano'.

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (recurso_humano)
$ git checkout produccion
Switched to branch 'produccion'
Your branch is up to date with 'origin/produccion'.

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (produccion)
$ git checkout recurso_humano
Switched to branch 'recurso_humano'
Your branch is up to date with 'origin/recurso_humano'.

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (recurso_humano)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (main)
$ git merge produccion
Updating 076c3c1..fa54640
Fast-forward
 materia prima.txt   |   0
 produccionfinal.txt |   0
 producto.jpg        | Bin 0 -> 115604 bytes
 3 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 materia prima.txt
 create mode 100644 produccionfinal.txt
 create mode 100644 producto.jpg

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (main)
$ git commit -m "Mezclando main y produccion"
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (main)
$ git push
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/JDiego24/examen.git
   076c3c1..fa54640  main -> main

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (main)
$ git checkout main
Already on 'main'
Your branch is up to date with 'origin/main'.

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (main)
$ git checkout produccion
Switched to branch 'produccion'
Your branch is up to date with 'origin/produccion'.

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (produccion)
$ git checkout ventas
Switched to branch 'ventas'
Your branch is up to date with 'origin/ventas'.

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (ventas)
$ git checkout recurso_humano
Switched to branch 'recurso_humano'
Your branch is up to date with 'origin/recurso_humano'.

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (recurso_humano)
$ dir
README.md

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (recurso_humano)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (main)
$ git merge recurso_humano
Already up to date.

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (main)
$ git tag version1 -m "Esta es la primer version"

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (main)
$ git push tag version1
fatal: 'tag' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (main)
$ git tag
version1

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (main)
$ git tag version1.1 -m "Esta es la nueva version"

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (main)
$ git tag
version1
version1.1

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (main)
$ git checkout ventas
Switched to branch 'ventas'
Your branch is up to date with 'origin/ventas'.

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (ventas)
$ git dif tiendas.txt
git: 'dif' is not a git command. See 'git --help'.

The most similar commands are
        diff
        config
        difftool
        init

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (ventas)
$ git diff tiendas.txt
diff --git a/tiendas.txt b/tiendas.txt
index dae43b7..0fc0bf2 100644
--- a/tiendas.txt
+++ b/tiendas.txt
@@ -1,3 +1,5 @@
 Tienda solecito
 Tienda mi vaquita
-Tienda la esquina
\ No newline at end of file
+Tienda la esquina
+Tienda la cuarta
+Tienda la quinta
\ No newline at end of file

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (ventas)
$ git checkout recurso_humano
error: Your local changes to the following files would be overwritten by checkout:
        tiendas.txt
Please commit your changes or stash them before you switch branches.
Aborting

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (ventas)
$ git commit -m "Modificando las tienditas"
On branch ventas
Your branch is up to date with 'origin/ventas'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   tiendas.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Empleados.txt
        empleados_f/

no changes added to commit (use "git add" and/or "git commit -a")

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (ventas)
$ git status
On branch ventas
Your branch is up to date with 'origin/ventas'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   tiendas.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Empleados.txt
        empleados_f/

no changes added to commit (use "git add" and/or "git commit -a")

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (ventas)
$ git add .
warning: in the working copy of 'Empleados.txt', LF will be replaced by CRLF the next time Git touches it

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (ventas)
$ dir
Empleados.txt  README.md  empleados_f  tiendas.txt

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (ventas)
$ git rm Empleados.txt
error: the following file has changes staged in the index:
    Empleados.txt
(use --cached to keep the file, or -f to force removal)

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (ventas)
$ git rm -f Empleados.txt
rm 'Empleados.txt'

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (ventas)
$ git rm -f empleados_f
fatal: not removing 'empleados_f' recursively without -r

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (ventas)
$ git rm -f empleados_f -r
rm 'empleados_f/e1.jpg'
rm 'empleados_f/e2.jpg'
rm 'empleados_f/e3.jpg'
rm 'empleados_f/e4.jpg'
rm 'empleados_f/e5.png'

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (ventas)
$ git commit -m "Auxilio voy a explotar"
[ventas e514d1e] Auxilio voy a explotar
 1 file changed, 3 insertions(+), 1 deletion(-)

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (ventas)
$ git push -u origin ventas
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 342 bytes | 14.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/JDiego24/examen.git
   97a619f..e514d1e  ventas -> ventas
branch 'ventas' set up to track 'origin/ventas'.

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (ventas)
$ git checkout recurso_humano
Switched to branch 'recurso_humano'
Your branch is up to date with 'origin/recurso_humano'.

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (recurso_humano)
$ dir
README.md

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (recurso_humano)
$ git push --tag version1
fatal: 'version1' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (recurso_humano)
$ git push --version1.1
error: unknown option `version1.1'
usage: git push [<options>] [<repository> [<refspec>...]]

    -v, --verbose         be more verbose
    -q, --quiet           be more quiet
    --repo <repository>   repository
    --all                 push all refs
    --mirror              mirror all refs
    -d, --delete          delete refs
    --tags                push tags (can't be used with --all or --mirror)
    -n, --dry-run         dry run
    --porcelain           machine-readable output
    -f, --force           force updates
    --force-with-lease[=<refname>:<expect>]
                          require old value of ref to be at this value
    --force-if-includes   require remote updates to be integrated locally
    --recurse-submodules (check|on-demand|no)
                          control recursive pushing of submodules
    --thin                use thin pack
    --receive-pack <receive-pack>
                          receive pack program
    --exec <receive-pack>
                          receive pack program
    -u, --set-upstream    set upstream for git pull/status
    --progress            force progress reporting
    --prune               prune locally removed refs
    --no-verify           bypass pre-push hook
    --follow-tags         push missing but relevant tags
    --signed[=(yes|no|if-asked)]
                          GPG sign the push
    --atomic              request atomic transaction on remote side
    -o, --push-option <server-specific>
                          option to transmit
    -4, --ipv4            use IPv4 addresses only
    -6, --ipv6            use IPv6 addresses only


bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (recurso_humano)
$ git push origin version1
Enumerating objects: 1, done.
Counting objects: 100% (1/1), done.
Writing objects: 100% (1/1), 176 bytes | 88.00 KiB/s, done.
Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/JDiego24/examen.git
 * [new tag]         version1 -> version1

bring@DiegoPc MINGW64 ~/OneDrive/Escritorio/examen (recurso_humano)
$ git push origin version1.1
Enumerating objects: 1, done.
Counting objects: 100% (1/1), done.
Writing objects: 100% (1/1), 177 bytes | 177.00 KiB/s, done.
Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/JDiego24/examen.git
 * [new tag]         version1.1 -> version1.1
