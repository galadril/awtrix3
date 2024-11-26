# API Documentation

Below is the SwaggerUI for the API:

<div id="swagger-ui"></div>

<script>
  // Load Swagger UI directly via Docsify plugin
  window.onload = function () {
    const ui = SwaggerUIBundle({
      url: "swagger/awtrix3.swagger.yml",
      dom_id: "#swagger-ui",
      deepLinking: true,
      presets: [SwaggerUIBundle.presets.apis, SwaggerUIStandalonePreset],
      layout: "StandaloneLayout",
      onComplete: function () {
        // Hide the SmartBear banner on completion
        document.querySelector('.swagger-ui .info').style.display = 'none';
      },
    });
  };
</script>
