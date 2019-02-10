---
title: dianthus alpinus
plant:
  genus: dianthus
  species: alpinus
---
<script>
var x = {{ page.plant | jsonify | remove: '<p>' | remove: '</p>' }}
document.write(x);
</script>
