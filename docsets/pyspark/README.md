pyspark Docset
==============

* Author: Rahul Iyer (https://twitter.com/rahuliyer95) - versions: 3.4.0
* Author: Tomas Kunka (https://twitter.com/TomasKunka) - versions: 3.0.0, 2.4.0
* Author: Ronert Obst (https://twitter.com/ronert_obst) - versions: 2.1.0, 1.6.1, 1.5.1
* Instructions
  * Clone the Apache Spark repo
  * Modify `spark/python/docs/conf.py` and add `html_theme_options = {"nosidebar": "true"}` under `html_theme = 'nature'`
  * Run `make html`
    * Optionally `export SPHINXOPTS="-j auto --keep-going"`
  * Then run doc2dash
