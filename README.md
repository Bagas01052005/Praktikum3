# Praktikum3

# Kelas Pegawai

class Pegawai {

    private String nama;
    private double gajiPokok;

    // Setter dan Getter untuk nama
    public void setNama(String nama) {
        this.nama = nama;
    }

    public String getNama() {
        return nama;
    }

    // Setter dan Getter untuk gajiPokok
    public void setGajiPokok(double gajiPokok) {
        this.gajiPokok = gajiPokok;
    }

    public double getGajiPokok() {
        return gajiPokok;
    }

    // Metode untuk mencetak informasi pegawai
    public void cetakInfo() {
        System.out.println("Nama: " + nama);
        System.out.println("Gaji Pokok: " + gajiPokok);
    }
}

# Kelas Manager yang merupakan subclass dari Pegawai

class Manager extends Pegawai {

    private double tunjangan;

    // Setter dan Getter untuk tunjangan
    public void setTunjangan(double tunjangan) {
        this.tunjangan = tunjangan;
    }

    public double getTunjangan() {
        return tunjangan;
    }

    // Metode untuk mencetak tunjangan
    public void cetakTunjangan() {
        System.out.println("Tunjangan: " + tunjangan);
    }
}

# Kelas Programmer yang merupakan subclass dari Pegawai

class Programmer extends Pegawai {
    private double bonus;

    // Setter dan Getter untuk bonus
    public void setBonus(double bonus) {
        this.bonus = bonus;
    }

    public double getBonus() {
        return bonus;
    }

    // Metode untuk mencetak bonus
    public void cetakBonus() {
        System.out.println("Bonus: " + bonus);
    }
}
