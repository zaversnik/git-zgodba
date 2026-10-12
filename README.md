# Navodila

Dobrodošli! Ta repozitorij vsebuje interaktivno zgodbo, skozi katero boste spoznali osnove Gita.

Za igranje potrebujete uporabniški račun na GitHubu, na svojem računalniku pa nameščen Git in nastavljen ključ SSH (oboje ste uredili v 1. nalogi na vajah).

## 1. Naredite svojo kopijo tega repozitorija

- Zgoraj desno, v vrstici z imenom repozitorija (`git-zgodba`), poiščite gumb _Fork_.
- Kliknite ga in na strani, ki se odpre, spodaj še _Create fork_.
  Pristali boste na **svoji** kopiji tega repozitorija, ki ima ista navodila; nadaljujte na njej.

## 2. Pripravite svoj repozitorij

GitHub na kopiranih repozitorijih avtomatsko izklopi robotsko pomoč, ki jo uporabimo v zgodbi.
Da jo ponovno vklopite, pojdite na zavihek *Actions* zgoraj in stisnite zelen gumb z napisom *I understand my workflows, go ahead and enable them*.
Nato se vrnite na zavihek *Code* in nadaljujte.

## 3. Klonirajte repozitorij na svoj računalnik

Na **svoji** kopiji repozitorija kliknite zeleni gumb _Code_, izberite _Local_ in _SSH_ ter kopirajte naslov (kot v 1. nalogi na vajah). Videti je takole:

```
git clone git@github.com:⟨uporabnisko-ime⟩/git-zgodba.git
```

V ukazno vrstico v VSCode (v imeniku `rp`) napišite `git clone`, prilepite naslov in stisnite vnašalko.

Sledite navodilom v datoteki `navodila.md`:
- v ukazni vrstici se premaknite v repozitorij: `cd git-zgodba` in
- izpišite vsebino datoteke z navodili: `cat navodila.md`.

Datoteka `navodila.md` je napisana v jeziku Markdown, zato je koda označena z obrnjenimi apostrofi: `` ` ``.
To pomeni, da če so v datoteki navodila
```shell
Poženite program `nano` takole: `nano datoteka.txt`
```
v ukazno vrstico napišete `nano datoteka.txt`, ne pa `` `nano datoteka.txt` ``.


## Zahvala

Prvo verzijo te igre je pripravil [Patrik Žnidaršič](https://github.com/k3ap).
