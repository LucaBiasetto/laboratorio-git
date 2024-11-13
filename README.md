# Laboratorio su git

## Esercizio 1

- Clonate questo repository sul vostro computer usando `git clone`
- Ispezionate la storia delle modifiche con `git log`

## Esercizio 2

- Modificate o aggiungete un file qualsiasi e registrate i cambiamenti con `git add` e `git commit`

## Esercizio 3

- Spostatevi sul branch `esercizio-3` con il comando `git checkout esercizio-3`
- Ispezionate le differenze tra il branch `esercizio-3` e il branch `esercizio-3-bis` con il comando `git diff esercizio-3-bis`
- Fate il _merge_ dei due branch: `git merge esercizio-3-bis`.
  Ci sono conflitti? Ispezionate lo storico delle modifiche con `git log --all --oneline --graph`

## Esercizio 4

- Spostatevi sul branch `esercizio-4`
- Ispezionate le differenze tra il branch `esercizio-4` e `esercizio-4-bis`
- Fate il merge di `esercizio-4-bis` in `esercizio-4`, risolvendo eventuali conflitti. Ricordate di registrare la risoluzione dei conflitti con `git add` e di fare il commit
- Controllate che il comando `python esercizio4.py` venga eseguito con successo. L'output è come ve lo aspettate?

