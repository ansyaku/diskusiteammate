Pertanyaan-Pertanyaan penting :
***

1. Bagaimana jika dalnis diberikan role manager reviewer sementara dalnis tetap menjadi project owner? <br>

2. Di ROWD ada opsi utk siapa mereviu, bagaimana jika disini diset reviuwernya siapa sampe level apa, biar daltu tidak perlu buat ribet?<br>

3. Manager reviewer tidak berhak memindahkan status ke dalam pengerjaan. Bisakah kita set agar :<br>
a. saat po udh geser ke dalam pengerjaan tdk bs ubah?<br>
b. terima saja yang penting ada history?<br>

4. Kenapa assignment di issue langsung ke reviewer, manager, dan klien pengawasan? Tidak ada pilihan untuk project owner, manager reviewer, dan anggota tim?

5. Proses reviu tindak lanjut yang dilakukan oleh auditor :
Yang bisa approve atau reject tindak lanjut adalah yang berperan sebagai manager pada project teammate+.

6. Issue kapan diselesaikan ? Belum ada ketentuan.

**Daftar User :**
***

**Auditor**
ass.technique2 -> owner (Pengendali Teknis)<br> 
ass.qualite		-> manager reviewer (Pengendali Mutu)<br> 
superviseur2	-> manager reviewer (Ketua Tim)<br> 
membre1 ->tester<br> Anggota Tim <br> 
membre2	->tester<br> Anggota Tim <br> 

**Klien Pengawasan :<br>**
utilisatrice (owner) <br>
directrice (final approver) <br>
observateur (observer) <br>

Cadangan :<br>
ass.technique1		manager<br>
superviseur1		manager<br>

Ketua tim dalam hal ini sebagai manager reviewer tidak dapat melakukan update profil & schedule.<br>
Schedule state: <br>
Owner -> Dalam pengerjaan, Selesai, Reviu - Telah diterima, Reviu - Telah diterima <br>
Ketua Tim -> Reviu - Telah diterima, Reviu - Telah diterima <br>

__Kontrol 1:__
Ketika kertas kerja sudah diubah statusnya menjadi selesai, maka ketua tim tidak dapat mengubah lagi prosedur, kecuali bila diubah state ke dalam pengerjaan.
Yang bisa menindaklanjuti respons adalah owner saja. Final approver dan approver tidak bisa.

__Response Tracking :__
Meminta tanggapan auditi atas temuan dan rekomendasi

**Pending :**
1. Bagaimana tatakelola untuk response tracking apakah harus di reviu terlebih dahulu ?<br>
2. Siapakah yang perlu mengubah status management response - tracking - pending <br>
Bisa response tracking tanpa kontak (risiko- auditor anggap udh response tp gak  masuk-masuk ke auditi karena memang gak ada auditinya)! <br>
Response tracking harus diganti terlebih dahulu menjadi dalam pengerjaan/_management response tracking-accepted_, agar bisa dirilis.

__Issue Tracking :__
1. Semua bisa issue tracking, tp kemarin yg disepakati Ketua Tim (minimal). 
2. Di owner diganti menjadi **TERIMPLEMENTASI**.
3. Ketika auditi sudah melakukan implementasi, auditi bisa kemblai mengedit sebelum diapprove atasan. 
4. Penuntasan bisa dilakukan dalnis atau daltu
5. Belum dimulai bisa dirilis
