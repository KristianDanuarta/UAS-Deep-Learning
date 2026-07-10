# Project Mini LM Colab Streamlit

Aplikasi web berbasis Streamlit dan PyTorch.

## Cara Menjalankan Aplikasi

Ikuti langkah-langkah di bawah ini menggunakan **PowerShell** atau **Command Prompt**:

### 1. Pindah ke Folder Proyek
```powershell
cd C:\streamlit_app

2. Buat Virtual Environment (.venv)
py -m venv .venv

3. Instal Dependensi (Library)
.venv\Scripts\python.exe -m pip install torch streamlit

4. Jalankan Aplikasi Streamlit
.venv\Scripts\python.exe -m streamlit run app.py --server.port 8502