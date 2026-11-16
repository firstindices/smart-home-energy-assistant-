src/: your real code, split by feature, so adding EV charging or heat pumps later is just a new subfolder.
data/: keep it out of Git if files are large (add it to .gitignore).
tests/: recruiters notice this, and it’s cheap to add.
docs/: put your README images here and link them with ![Demo](docs/demo.gif).