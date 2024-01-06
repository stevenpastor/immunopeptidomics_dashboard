# Immunopeptidomics Dashboard

---

## DESCRIPTION

* Flask, Postgres app producing useful visualizations and tables to summarize and allow further analyses of multi-omics immunopeptidomics results

## INSTALLATION

* Rename .env.prod-sample to .env.prod and .env.prod.db-sample to .env.prod.db.

* Build images and run containers:

```
docker-compose -f docker-compose.prod.yml up -d --build
```

* In browser, go to: http://localhost:1337

* If you need to change anything, you must re-build the image.

