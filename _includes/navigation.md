<!-- _includes/navigation.html -->
<link rel="stylesheet" type="text/css" href="{{ site.baseurl }}/assets/css/custom.css">
<nav>
  <ul>
    <li><a href="{{ site.baseurl }}/" {% if page.url == "/" %}class="active"{% endif %}>Home</a></li>
    <li><a href="{{ site.baseurl }}/about" {% if page.url == "/about/" %}class="active"{% endif %}>About</a></li>
    <li><a href="{{ site.baseurl }}/llm/argumentevaluation" {% if page.url == "/llm/argumentevaluation/" %}class="active"{% endif %}>Argument Evaluation</a></li>
    <li><a href="{{ site.baseurl }}/llm/balanced_exposition" {% if page.url == "/llm/balanced_exposition/" %}class="active"{% endif %}>Balanced Exposition</a></li>
    <li><a href="{{ site.baseurl }}/llm/allegory" {% if page.url == "/llm/allegory/" %}class="active"{% endif %}>Allegorical Didactive Narrative Prompt</a></li>
    <li><a href="{{ site.baseurl }}/llm/extract_propositions" {% if page.url == "/llm/extract_propositions/" %}class="active"{% endif %}>Extract Logical Propositions From Source</a></li>
  </ul>
</nav>

extract_propositions
