<h4>
  Subject : Hextroadinary
  <br>
  Type : Cryptography
  <br>
  DIfficulty : Easy
</h4>
<hr>
<p>
  Meet ROXy, a coder obsessed with being exclusively the worlds best hacker. She specializes in short cryptic hard to decipher secret codes. The below hex values for example, she did something with them to generate a secret code, can you figure out what? Your answer should start with 0x.
  <br><b>0xc4115 0x4cf8</b>
</p>
<p>Pada challenge ini, clue dapat dilihat pada kata ROXy, yang merupakan plesetan untuk kata XOR, yaitu operasi logika untuk membandingkan 2 nilai biner. Lalu perhatikan pada akhir kalimat, terdapat kalimat "Your answer should start with 0x.
0x merupakan notasi awal dari hexadecimal, karena itulah kita diberikan 2 buah kode hexadecimal.</p>
<p>Setelah membaca clue tersebut, saya pun menggunakan perintah pada bahasa pemograman python untuk melakukan operasi XOR, yaitu :
<br> print(hex(0xc4115 ^ 0x4cf8))
<br>dimana fungsi dari hex() disini untuk mengubah format hasil dari XOR kedalam kode hexadecimal.</p>
<p>Flag : <b>0xc0ded</b></p>
