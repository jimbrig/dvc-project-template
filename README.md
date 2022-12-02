# Data Version Control (DVC) Template Repository

> This repo serves as a template laying out the structure for a data related project that implements data-version-control via DVC.

*See the [CHANGELOG](CHANGELOG.md) for detailed changes over time*

```powershell
+---.dvc
|   +---cache
|   \---tmp
|       +---hashes
|       |   \---local
|       \---links
+---bin
+---config
+---data
|   +---curated
|   +---metadata
|   +---processed
|   \---raw
+---dev
|   +---dbt
|   +---bash
|   +---R
|   +---python
|   \---pwsh
+---docs
|   +---assets
|   +---dbdocs
|   +---mkdocs
|   |   +---docs
|   |   \---site
|   \---schemaspy
|       +---java
|       \---output
+---infra
+---lib
+---src
|   +---API
|   +---Database
|   +---ExcelApp
|   \---WebApp
\---tests

```
