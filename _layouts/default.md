<!DOCTYPE html>
<html lang="{{ page.lang | default: site.lang | default: "en" }}">

  {% include head.html %}

  <body>

    {% include header.html %}

    <main class="container-fluid" aria-label="Content">
      <div class="row">
        {% include sidebar.html %}

        <div class="post col-lg-8 col-md-8 col-sm-6">
          {{ content }}
        </div>
      </div>
      
    </main>

    {% include footer.html %}

  </body>

</html>
