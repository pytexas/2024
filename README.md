# PyTexas Conference Website

## Development
1. Create a virtual environment
    ```
    python -m venv venv
    ```
2. Activate virtual environment
    ```
    source venv/bin/activate
    ```
3. Pip install mkdocs material
    ```
    pip install mkdocs-material
    ```
4. Run dev server
    ```
    mkdocs serve
    ```

## Adding Announcement Banners
1. Add the following lines and update the text to `overrides/main.html`
```html
{% block announce %}
    <p>Attend the <a href="https://conference.pytexas.org">PyTexas 2024 Conference</a> April 19 - 21, 2024</p>
{% endblock %}
```
