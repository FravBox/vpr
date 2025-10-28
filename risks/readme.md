# Photosensitive Risk Categories

Remember: Your source can have these naturally! Your video can be a risk without adding any effects!

TODO: Do we need to explain that "risk categories" are "triggers" ?

{% for risks in site.risks %}
  <h2>{{ risks.name }} (**{{ risks.shortcode }}**)</h2>
  <p>{{ risks.content | markdownify }}</p>
{% endfor %}