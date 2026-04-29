<div align="center">

<a href="#">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=32&pause=1000&color=00FFCC&center=true&vCenter=true&width=800&lines=System+Breach+Detected...;SQL+Injection+Vulnerability+Analysis;Executing+Prepared+Statements...;By+Rizky+Maulana" alt="Typing SVG" />
</a>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.gif" width="100%">

# 🛑 𝗖𝗬𝗕𝗘𝗥 𝗦𝗘𝗖𝗨𝗥𝗜𝗧𝗬 𝗥𝗘𝗦𝗘𝗔𝗥𝗖𝗛: 𝗦𝗤𝗟 𝗜𝗡𝗝𝗘𝗖𝗧𝗜𝗢𝗡 🛑

<p align="center">
  <kbd>Status: COMPLETED</kbd> • <kbd>Level: CRITICAL</kbd> • <kbd>Target: DATABASE AUTHENTICATION</kbd>
</p>

</div>

<br>

<table align="center" width="100%">
  <tr>
    <td width="50%" align="center">
      <h3>👨‍💻 IDENTITAS ENGINEER</h3>
      <code>NAMA  : Rizky Maulana</code><br>
      <code>NIM   : 312410430</code><br>
      <code>KELAS : I241C</code><br>
      <code>TUGAS : UTS Pemrograman Web</code>
    </td>
    <td width="50%" align="center">
      <h3>🛠️ TECH STACK DASHBOARD</h3>
      <img src="https://img.shields.io/badge/PHP_8.x-777BB4?style=for-the-badge&logo=php&logoColor=white" />
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" /><br>
      <img src="https://img.shields.io/badge/XAMPP-F37623?style=for-the-badge&logo=xampp&logoColor=white" />
      <img src="https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=white" />
    </td>
  </tr>
</table>

<br>

<div align="center">

## 📡 𝗣𝗨𝗕𝗟𝗜𝗞𝗔𝗦𝗜 𝗥𝗜𝗦𝗘𝗧 (𝗠𝗘𝗗𝗜𝗨𝗠)

Tugas eksklusif ini telah didokumentasikan dan dipublikasikan dalam bentuk artikel jurnal teknis di Medium. Klik *badge* di bawah ini untuk membaca analisis lengkap mengenai eksploitasi dan mitigasinya:

[![READ FULL ARTICLE ON MEDIUM](https://img.shields.io/badge/READ_FULL_ARTICLE_ON_MEDIUM-00FFCC?style=for-the-badge&logo=medium&logoColor=black&labelColor=black)]([LINK_MEDIUM_KAMU])

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.gif" width="80%">

</div>

## 🔬 𝗔𝗕𝗦𝗧𝗥𝗔𝗖𝗧 & 𝗦𝗬𝗦𝗧𝗘𝗠 𝗢𝗩𝗘𝗥𝗩𝗜𝗘𝗪

Repositori ini memuat *source code* dan dokumentasi dari pengujian penetrasi (Pen-Test) skala kecil pada sistem autentikasi web. Fokus utama dari riset ini adalah membuktikan betapa rentannya form login yang ditulis dengan `mysqli_query` murni tanpa filter, dan bagaimana sebuah karakter tunggal (`'`) dapat membobol akses *database*.

**Fase Operasi:**
1. 📂 **`vulnerable.php`** — Simulasi server dengan celah keamanan (*Zero-day concept*).
2. ⚔️ **`Payload Injection`** — Penetrasi menggunakan manipulasi *query* (`' OR '1'='1'#`).
3. 🛡️ **`secure.php`** — Penambalan celah (*Patching*) menggunakan arsitektur **Prepared Statements**.

---

## 📸 𝗦𝗬𝗦𝗧𝗘𝗠 𝗟𝗢𝗚𝗦 (𝗘𝗫𝗣𝗘𝗥𝗜𝗠𝗘𝗡𝗧 𝗣𝗥𝗢𝗢𝗙)

> *Klik pada setiap dropdown untuk melihat tangkapan layar dari hasil eksperimen.*

<details>
<summary><b>🟢 LOG 01: NORMAL AUTHENTICATION (SYSTEM STABLE)</b></summary>
<br>
Sistem berjalan normal ketika pengguna memasukkan kredensial yang valid. Tidak ada anomali yang terdeteksi.<br><br>

> *(Masukkan link gambar normal login kamu di bawah ini, timpa tulisan "LINK_GAMBAR")*
<img src="LINK_GAMBAR" alt="Normal Login" width="800" style="border: 2px solid #00FFCC; border-radius: 10px;">
</details>

<details>
<summary><b>🔴 LOG 02: SYSTEM BREACHED (SQL INJECTION SUCCESS)</b></summary>
<br>
<b>CRITICAL ALERT:</b> Autentikasi berhasil di-bypass menggunakan injeksi logika OR. Pelaku berhasil masuk tanpa password yang sah.<br><br>

> *(Masukkan link gambar saat login berhasil dibobol di bawah ini)*
<img src="LINK_GAMBAR" alt="Bypassed" width="800" style="border: 2px solid red; border-radius: 10px;">
</details>

<details>
<summary><b>🛡️ LOG 03: SYSTEM SECURED (ATTACK BLOCKED)</b></summary>
<br>
Sistem menolak serangan. Implementasi <i>Prepared Statements</i> berhasil mengonversi payload berbahaya menjadi string biasa.<br><br>

> *(Masukkan link gambar saat login gagal/aman di bawah ini)*
<img src="LINK_GAMBAR" alt="Secured" width="800" style="border: 2px solid #00FFCC; border-radius: 10px;">
</details>

<br>

<div align="center">
<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.gif" width="100%">

### *"A chain is only as strong as its weakest link. Secure your queries."*

<code>© 2026 Code & Security Research by Rizky Maulana</code>

</div>
