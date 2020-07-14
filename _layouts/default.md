<!DOCTYPE html>
<html lang="{{ page.lang | default: site.lang | default: "en" }}">
  {%- include head.md -%}
  <body>
    <main>
      <div class="content-wrapper">{{ content }}<hr /></div>
      
      <div class="footer">
      {%- include footer.md -%}
    </div>
    </main>
    
  </body>
</html>
