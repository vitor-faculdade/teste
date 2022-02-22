<link rel="stylesheet" href="https://unpkg.com/swagger-ui-dist@4.5.0/swagger-ui.css" />

<div id="swagger-ui"></div>

<script src="https://unpkg.com/swagger-ui-dist@4.5.0/swagger-ui-bundle.js" crossorigin></script>
<script src="https://unpkg.com/swagger-ui-dist@4.5.0/swagger-ui-standalone-preset.js" crossorigin></script>
<script>
  window.onload = () => {
    window.ui = SwaggerUIBundle({
      url: 'https://raw.githubusercontent.com/vitor-faculdade/teste/main/teste.yaml',
      dom_id: '#swagger-ui',
      // presets: [
      //   SwaggerUIBundle.presets.apis,
      //   SwaggerUIStandalonePreset
      // ],
      // layout: "StandaloneLayout",
    });
  };
  console.log('teste');
</script>