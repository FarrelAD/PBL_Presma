Ini merupakan eksperimen end-to-end (E2E) testing yang dilakukan menggunakan Python Playwright pada proyek Laravel.

# Bagaimana cara menjalankan test-nya ?

1. Instal dependensi
    
    Jika anda menggunakan `uv` package manager, anda bisa menggunakan perintah berikut untuk proses instalasinya:

    ```bash
    uv init
    uv venv
    .venv\Scripts\activate
    uv sync
    ```

    Jika anda tidak memiliki `uv`, maka anda bisa menginstal dependensi secara manual dengan cara berikut:

    ```bash
    python -m venv .venv
    .venv\Scripts\activate
    pip install -r requirements.txt
    ```

2. Install browser playwright

    Playwright memerlukan browser yang diinstal terlebih dahulu agar dapat menjalankan pengujian secara otomatis. Jalankan perintah berikut:

    ```python
    playwright install
    ```

3. Jalankan e2e testing

    Gunakan perintah berikut untuk menjalankan pengujian:

    ```python
    pytest main.py
    ```

