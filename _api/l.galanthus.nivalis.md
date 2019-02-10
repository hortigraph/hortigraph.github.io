---
plant:
  genus: galanthus
  species: nivalis
---
{{ page.plant | jsonify | remove: '<p>' | remove: '</p>' | strip_html }}
