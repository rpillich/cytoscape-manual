# cytoscape-manual
Markdown version of Cytoscape manual

Kozo's instructions:

1. I exported http://wiki.cytoscape.org/Cytoscape_3/UserManual to a
docbook xml. (https://github.com/kozo2/cytoscape3-usermanual/blob/master/UserManual.xml)

2. I converted UserManual.xml to UserManual.md
(https://github.com/kozo2/cytoscape3-usermanual/blob/master/UserManual.md)
with ```pandoc -f docbook -t markdown -s UserManual.xml -o UserManual.md```

3. I separated UserManual.md per chapter manually.
(https://github.com/kozo2/cytoscape3-usermanual/tree/master/docs)

4. I built and deployed 3. with mkdocs and readthedocs.
 
Additionally:

1. Create a new project in ReadTheManual, and create a WebHook from GitHub to ReadTheDocs via http://docs.readthedocs.org/en/latest/webhooks.html

1. Text is processed by Sphinx, which is documented here: http://www.sphinx-doc.org/en/stable/contents.html