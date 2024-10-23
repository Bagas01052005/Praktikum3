# Praktikum3

# Kelas Pegawai

class Pegawai {

    private String nama;
    private double gajiPokok;

    public void setNama(String nama) {
        this.nama = nama;
    }

    public String getNama() {
        return nama;
    }

    public void setGajiPokok(double gajiPokok) {
        this.gajiPokok = gajiPokok;
    }

    public double getGajiPokok() {
        return gajiPokok;
    }

    public void cetakInfo() {
        System.out.println("Nama: " + nama);
        System.out.println("Gaji Pokok: " + gajiPokok);
    }
}

# Kelas Manager yang merupakan subclass dari Pegawai

class Manager extends Pegawai {

    private double tunjangan
    
    public void setTunjangan(double tunjangan) {
        this.tunjangan = tunjangan;
    }

    public double getTunjangan() {
        return tunjangan;
    }

    
    public void cetakTunjangan() {
        System.out.println("Tunjangan: " + tunjangan);
    }
}

# Kelas Programmer yang merupakan subclass dari Pegawai

class Programmer extends Pegawai {
    private double bonus;

    
    public void setBonus(double bonus) {
        this.bonus = bonus;
    }

    public double getBonus() {
        return bonus;
    }

    
    public void cetakBonus() {
        System.out.println("Bonus: " + bonus);
    }
}
