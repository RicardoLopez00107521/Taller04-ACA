# Uso básico de FutbolNow

=== "Noticias"

    ```js
    fetch('/api/news')
      .then(res => res.json())
      .then(data => render(data));
    ```

=== "Resultados"

    ```js
    fetch('/api/live')
      .then(res => res.json())
      .then(show => updateUI(show));
    ```

[Volver al inicio](../index.md)
