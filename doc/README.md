# jangyonggi0421.github.io

<script src="https://cdn.jsdelivr.net/npm/marked/marked.min.js"></script>

<div id="content"></div>

<script>
fetch("https://example.com/file.md")
  .then(r => r.text())
  .then(md => {
    document.getElementById("content").innerHTML = marked.parse(md);
  });
</script>