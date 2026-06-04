# Tag 2 — 04.06.2026

## Was habe ich heute gelernt?
- git pull — Änderungen von GitHub auf den Rechner holen
- git checkout main — zwischen Branches wechseln
- Branches: Was ein "Fast-forward" bedeutet
- Neuen Branch anlegen und darauf arbeiten

## Welches Problem hatte ich?
Nach dem Pull Request war mein lokaler Branch noch auf dem alten Stand.
Git meldete: "Your branch is behind by 2 commits."

## Wie habe ich es gelöst?
Erst git checkout main, dann git pull — danach war alles synchron.

## Was nehme ich mit?
Git ist wie ein Speicherpunkt-System. Branches sind parallele Äste —
main bleibt immer sauber, ich experimentiere auf einem eigenen Ast.