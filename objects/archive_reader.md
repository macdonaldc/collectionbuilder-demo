{% assign archive_id = page.object_location | split: '/' | last %}
<!--<div class="ratio ratio-4x3">-->
<div>
    <iframe src="https://archive.org/embed/{{ archive_id }}" frameborder="0" webkitallowfullscreen="true" mozallowfullscreen="true" allowfullscreen></iframe>
</div>

