# Réponses — chasse au trésor

<!-- Format imposé, une réponse par ligne :
Q01: <réponse>
commande: <commande(s) utilisée(s)>
-->

Q01: 32
commande: git rev-list --count depart

Q02: Sarah Benali
commande: git blame src/format.js

Q03: de5637a7c2ec4e7458525081fd1d1e9b237f0708
commande: git bisect start HEAD v0.2.0   git bisect run node scripts/controle-alertes.js

Q04: sk_live_01de6ba0c9f4d846
commande: git log -p -S "API_KEY"

Q05: 11544ab934db75adbe18115b8c463b52bdb4296a
commande: git log -p -S "API_KEY"

Q06: 17
commande: git rev-list --count v0.2.0..v1.0.0

Q07: essai-perf
commande: git for-each-ref --format '%(refname:short) : %(objecttype)' refs/tags

Q08: origin/feature/export-csv
commande: git log --graph --oneline --all --decorate

Q09: src/utils.js
commande: git log --follow --name-status src/outils.js

Q10: Nathan Robin
commande: git shortlog -sn depart

Q11: 2026-03-24
commande: git log -1 --format=%ai v1.0.0

Q12: bannière de démarrage
commande: git log --grep="Revert" --oneline

Q13: de5637a
commande: git log --merges --grep="fix/valeur-totale" --oneline

Q14: 16
commande: git diff --numstat v0.1.0 v1.0.0 -- src/stock.js 

Q15: 6d6b9207651255c22dd0f084b0cf793faed17f31
commande: git log -S "TODO: gérer les quantités négatives"
