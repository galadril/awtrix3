# API Documentation
Below is the SwaggerUI for the API:

<div id="swagger-ui"></div>

<script src="https://unpkg.com/swagger-ui-dist/swagger-ui-bundle.js"></script>
<script src="https://unpkg.com/swagger-ui-dist/swagger-ui-standalone-preset.js"></script>
<link rel="stylesheet" href="https://unpkg.com/swagger-ui-dist/swagger-ui.css" />

<script>
  window.onload = function () {
    const ui = SwaggerUIBundle({
      url: "swagger/awtrix3.swagger.yml",
      dom_id: "#swagger-ui",
      deepLinking: true,
      presets: [SwaggerUIBundle.presets.apis, SwaggerUIStandalonePreset],
      layout: "StandaloneLayout",
    });
  };
</script>
