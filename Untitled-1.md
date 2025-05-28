# Automasi IT: Google Workspace & Endpoint Security Scripts

Repositori ini berisi kumpulan script automasi (Bash dan PowerShell) yang dirancang untuk mempermudah tugas-tugas administrasi IT, khususnya yang berkaitan dengan Google Workspace dan keamanan endpoint.

Tujuan dari repositori ini adalah menyediakan alat bantu siap pakai untuk mengotomatisasi tugas-tugas berulang, meningkatkan efisiensi, dan membantu menjaga postur keamanan.


*   **Automasi Google Workspace:** Script untuk manajemen user, grup, lisensi, dan tugas-tugas administrasi Google Workspace lainnya.
*   **Keamanan Endpoint:** Script untuk memeriksa konfigurasi keamanan, menerapkan kebijakan, atau melakukan tindakan remediasi pada endpoint (Windows, Linux, macOS - tergantung script).
*   **Dukungan Multi-Platform:** Menyediakan script dalam Bash (umumnya untuk Linux/macOS/WSL) dan PowerShell (umumnya untuk Windows, tetapi juga tersedia di platform lain).

## Persyaratan

Persyaratan spesifik dapat bervariasi tergantung pada script yang Anda gunakan. Secara umum, Anda mungkin memerlukan:

*   Akses dan izin yang sesuai untuk lingkungan target (misalnya, akses API Google Workspace, hak administrator lokal pada endpoint).
*   Interpreter Bash atau PowerShell yang terinstal.
*   Dependensi tambahan yang mungkin diperlukan oleh script tertentu (misalnya, modul PowerShell, utilitas command-line).

## Cara Penggunaan

1.  **Clone Repositori:**
    ```bash
    git clone <URL_REPOSITORI_ANDA>
    ```
2.  **Navigasi:** Masuk ke direktori repositori yang baru di-clone.
3.  **Pilih Script:** Jelajahi direktori (`google-workspace/`, `endpoint-security/`, dll.) untuk menemukan script yang Anda butuhkan.
4.  **Baca Dokumentasi:** Setiap script idealnya memiliki komentar internal atau file README kecil yang menjelaskan fungsinya, parameter yang dibutuhkan, dan prasyarat. **Sangat disarankan untuk membaca dan memahami script sebelum menjalankannya.**
5.  **Jalankan Script:** Gunakan interpreter yang sesuai.
    *   Untuk script Bash:
        ```bash
        ./path/to/script.sh [parameter]
        ```
    *   Untuk script PowerShell:
        ```powershell
        powershell -ExecutionPolicy Bypass -File ./path/to/script.ps1 [parameter]
        ```
        *(Catatan: `-ExecutionPolicy Bypass` mungkin diperlukan di Windows tergantung konfigurasi sistem Anda. Gunakan dengan hati-hati.)*

## Struktur Repositori (Contoh)
