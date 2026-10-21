# glose-updates

Mises à jour de Glose, une extension Firefox privée. Firefox lit
[`updates.json`](updates.json) chaque jour (adresse `update_url` du manifeste) et
installe la version la plus récente qu'il annonce.

Chaque `.xpi` est signé par Mozilla : Firefox refuse un fichier non signé, ou
signé pour un autre identifiant que `glose@nopitch.github.io`. Ce dépôt ne
contient que les paquets ; on y publie avec `bun scripts/publish-update.js`
depuis le dépôt de Glose, jamais à la main.
