# Kolekcje Postmana

Plan Free Postmana obejmuje jedn¹ osobê, dlatego zespó³ dzieli kolekcje przez to repozytorium.

1. Eksportujemy kolekcje w formacie **JSON v2.1** (Postman: *More › Export collection › Export JSON*).
2. Jedna osoba — jeden plik. Cudzy plik zmieniasz tylko po uzgodnieniu z jego w³aœcicielem.
3. W plikach œrodowisk (`*.postman_environment.json`) has³a, tokeny i klucze maj¹ puste wartoœci.
   Prawdziwe wartoœci wpisujesz tylko u siebie w Postmanie.
4. Kopie z prawdziwymi sekretami trzymasz w `postman/prywatne/` — ten katalog jest w `.gitignore`.
5. Przed ka¿dym commitem przegl¹dasz zmiany: `git diff --staged`.
