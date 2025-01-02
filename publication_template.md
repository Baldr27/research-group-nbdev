# Publication Template
Shane McIntosh, Filipe R. Cogo

<div class="publication" data-tags="{{ tags | join(', ') }}">

<h3>

<a href="{{ publication_url }}">{{ title }}</a>
</h3>

<strong>Authors</strong>: {{ authors | join(“,”) }} </br>
<strong>Venue</strong>: {{ venue }} </br> <strong>Preprint</strong>:
[PDF](%7B%7B%20preprint%20%7D%7D) </br> <strong>Related Tags</strong>:
{{ tags | map(tag =\> “<a href='#' class='tag-filter'>” + tag + “</a>”)
| join(“,”) }}

</div>
