# Analiza danych Titanic
<a href="titanic.ipynb" class="md-button md-button--primary">Pobierz Notebook</a>
<a href="titanic.pdf" class="md-button md-button--primary">Pobierz Raport</a>
<a href="titanic_presentation.pdf" download class="md-button md-button--primary">Pobierz prezentację</a>

<iframe
    id="content"
    src="titanic.html"
    width="100%"
    style="border:1px solid black;overflow:hidden;"
></iframe>
<script>
function resizeIframeToFitContent(iframe) {
    iframe.style.height = (iframe.contentWindow.document.documentElement.scrollHeight + 50) + "px";
    iframe.contentDocument.body.style["overflow"] = 'hidden';
}
window.addEventListener('load', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
});
window.addEventListener('resize', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
});
</script>