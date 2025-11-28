
# word-macro
Macro Microsoft Word untuk memudahkan membuat laporan and such...

- [x] Automatic Heading 1-3 Position and Format ✅ 2025-11-17
	- [x] Fix jika style heading sudah ada maka PASS ✅ 2025-11-22
- [x] If Content Rumusan masalah ketik otomatis.... bruhh (Buat Placeholder untuk mengetik dimananya...) ✅ 2025-11-13
- [x] Isi konten misal isi dari sebuah headings kan jadi hX normal, nah shorcut untuk shortcut perheading tsb! ✅ 2025-11-12
- [x] **Automatic Page Numbering with Header & Footer Format based on First Page^60efa9 ✅ 2025-11-22
	- [x] Just make it works, Can insert page number automatically using shortcut ✅ 2025-11-14
		although its lttle clunky
	- [x] Automatic Restart at 1 ketika di BAB I ✅ 2025-11-14
		also a bit clunky
	- [x] Separate the Romans Numeral with Latin Numeral based on Current Section ✅ 2025-11-20
		~~kayanya based on Section, kan udah pasti tuh bab segini section berapa? tinggal primary dan secodary thingy~~ Based on curent Section di Selection Cursor.
	- [x] Combinin the automatic restart at **BAB 1** into the page number shortcut ✅ 2025-11-22
	- [ ] ~~**TEMPORARY** Shortcut untuk otomatis First Page header~~
		Not Needed
	It Should Work Now, I Hope
- [x] Automatic Section Next Page Break when ✅ 2025-11-25
	  ~~TIS IS NEXT~~
	  ~~When Typing Heading 1 Content then activating the shortcut, the selection will move to the front of the text then inserting Section Break Next Page~~
	  ~~Its actually a pretty bad idea and works problematically~~
	  Wait ill have different implementation, because its actually needed!
	  Buat menjadi shortcut?? jadi search trough every heading 1, if found then move cursor to the previous page really edge, add section break, if section > 1 ofc ^730c46
- [x] Automatic Table of Content!! Based on our my own *good* format rather than default word!! ✅ 2025-11-28
- [ ] Buat Universal Frame, whatchacalit table of Figures yes
	- [ ] Photo frame complete with with the description 
	- [ ] Table frame complete with the description 
- [ ] Setup AutoExec jadinya tidak broken ketika dibuka kembali
	- [ ] Buat seperti metadata? kalo filenya ini pernah dibuka dan diedit menggunakan macros nya
	Wait AutoExec gimana??,  i forgor problemnya apa
- [x] Makes it so that it works for other people!! **.DOTM** APPARANTLY ✅ 2025-11-22
	Haven't tried for other people but it should work
- [x] Buat Daftar Nama mudah, style Butun! also alamat butun ✅ 2025-11-13
	Pretty Useless Though...
- [ ] Buat Dokumentasi Cara Penggunaan Macro ini
- [ ] very optional, I dont think ill need this...
	- [ ] make undo button works after macroing
	- [ ] Shortcut increase paragraph indent incase tabs doesnt work
- [ ] Bug Testing
- [ ] Post IG!! Anjayy
- [ ] ???
- [ ] Profit...!!! 

---

### List Shortcut

- ALT + F  :  Format Margins, Heading, Numbering
- ALT + 1  :  Heading 1
- ALT + 2  :  Heading 2
- ALT + 3  :  Heading 3
- ALT + SHIFT + 2  :  Heading 2 Normal (Paragraf di dalam Heading 2)
- ALT + SHIFT + 3  :  Heading 3 Normal (Paragraf di dalam Heading 3)
- ALT + E  :  Lembar Halaman
- ALT + R  :  Reset Halaman Romawi ke Angka Numerik Arab (1, 2, 3), Beserta Heading 1
- ALT + R  :  Reset Heading 1
- ALT + Q  :  Section Break (Next Page)
- ALT + B   :  Section Break Fix


---

### Use Case

Laporan Sudah Jadi -- Sisa Halaman dan Daftar Isi
1. ALT+F : Format
2. ALT+E : Angka Halaman
3. ALT+R : Reset Romawi (Letakkan Kursor di lembar yang ingin di Reset ---> **BAB 1**)
4. ALT+T : Buat Daftar Isi Otomatis (Letakkan Kursor di garis kosong di lembar DAFTAR ISI)

Laporan Setengah Jadi -- Margin Heading Format & Numbering


Laporan Belum Jadi Sama Sekali -- No Progress


---