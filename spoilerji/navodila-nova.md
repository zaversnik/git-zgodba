inhibit-stiridva

# Nadaljnja navodila

1. Sedaj imate lokalno kopijo repozitorija.
2. Poženite skripto, da boste lahko preigrali zgodbo:
   v ukazno vrstico napišete `./hook-install.sh` in stisnite vnašalko.
3. Uredite to datoteko (`navodila.md`) tako, da bo v njej nekje
   zapisan odgovor na življenje, vesolje in sploh vse (t.j. `42`).
4. Z `git status` preverite, da ste res spremenili vsebino datoteke.
5. Git-u povejte, da ste spremenili datoteko: `git add navodila.md`.
6. Poglejte, kaj ko se je spremenil repozitorij: `git status`.
   Zeleno obarvana imena so spremembe, za katere git ve, rdeča pa tiste spremembe,
   za katere git še ne ve. Sedaj napišite `git commit -m "Moj prvi commit"` in
   s tem povejte git-u, naj spremembe shrani v repozitorij.
7. Glejte ukazno vrstico za nadaljnja navodila.
   Če se ob ukazu `git commit` ni izpisalo nič drugega kot običajno, ste izpustili 2. korak: poženite skripto in `git commit` ponovite.
8. Shranite svoje delo na github z naslednjimi ukazi:
   - `git add navodila.md zelena.txt rumena.txt`
   - `git commit -m "Tik pred shranjevanjem na strežnik"`
   - `git push origin master`
9. Počakajte kakšno minuto, nato si na GitHubu oglejte svojo kopijo repozitorija.
    Ali so se v datoteki `navodila.md` pojavila dodatna navodila?
    Če se tudi po nekaj minutah ne pojavijo, preverite, ali ste v 2. koraku navodil v `README.md` vklopili _Actions_.
