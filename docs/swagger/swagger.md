# API Documentation
Below is the SwaggerUI for the API:

<div id="swagger-ui"></div>

<script>
  // Load Swagger UI directly via Docsify plugin
  window.onload = function () {
    const ui = SwaggerUIBundle({
      url: "swagger/awtrix3.swagger.yml", // Replace with your Swagger file URL
      dom_id: "#swagger-ui",
      deepLinking: true,
      presets: [SwaggerUIBundle.presets.apis, SwaggerUIStandalonePreset],
      layout: "StandaloneLayout",
    });
  };
</script>
