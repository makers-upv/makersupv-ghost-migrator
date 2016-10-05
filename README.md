1. Download main table from Google Drive as TSV and save in `data/index.tsv`
2. Copy all images to `data/img`
3. `npm install`
4. `node run download` (takes a while)
5. Copy `config.example.json` to `config.json` and fill it out. (the bearer token has an expiration time, so do this last)
6. `node lib/index.js > migration.log` and sit for a while. `migration.log` will have all the info when it's finished.
7. Fix all the things broken for which a script written in an evening is insufficient