# form_pendaftaran_rial
implementasi formulir pendaftaran online yang akan digunakan oleh pengguna dengan usia > 40 tahun. Buatlah desain form dengan field isian: Nama, Tanggal Lahir, Jenis Kelamin, Alamat, Daftar Riwayat Pekerjaan.

String form_pendaftaran = "", usia_lanjut;
if (rblaki.isSelected()) {
     form_pendaftaran = "usia lebih dari sama dengan 40 tahu";
} else if (rbperempuan.isSelected()) {
     form_pendaftaran = "usia kurang dari 40 tahun";
}
usia_lanjut = formdaftar.getSelectedItem().toString();

txtarea.setText("Nama\t: " + txtnama.getText()
        + "\n Tanggal Lahir\t: " + txttanggallahir.getText()
        + "\n Jenis Kelamin\t: " + form_pendaftaran
        + "\n Alamat\t: " +txtalamat .getText());
        + "\n Daftar Riwayat Pekerjaan \t: " + riwayat_pekerjaan
