"masjid raya depok"
import_andorid
import_size 
import_website

{
("address =  Jl. Flamboyan No.4, Cinere, Kec. Cinere, Kota Depok, Jawa Barat 16514")
enum
("number address = 16514")
}
bool 
(" 1 + 0 = 1")
date ("9-4-2026")
time("17:00")
null for apilcation

#include <iostream>
#include <string>
#include <vector>

using namespace std;

class BangunanMasjid {
public:
    string nama;
    int kapasitas;
    int jumlahKubah;

    void tampilkanInfo() {
        cout << "=== Profil Masjid ===" << endl;
        cout << "Nama      : " << nama << endl;
        cout << "Kapasitas : " << kapasitas << " Jamaah" << endl;
        cout << "Kubah     : " << jumlahKubah << endl;
        cout << "----------------------" << endl;
    }
};

int main() {
    BangunanMasjid masjidDepok;
    masjidDepok.nama = "Masjid Raya Depok";
    masjidDepok.kapasitas = 1000;
    masjidDepok.jumlahKubah = 1;

    masjidDepok.tampilkanInfo();

    return 0;
}
xml
<?xml version="1.0" encoding="UTF-8"?>
<masjid_raya>
    <nama>Masjid Raya Depok</nama>
    <lokasi>
        <jalan>Jl. Margonda Raya</jalan>
        <kota>Depok</kota>
        <provinsi>Jawa Barat</provinsi>
        <negara>Indonesia</negara>
    </lokasi>
    <arsitektur>
        <gaya>Modern Islami</gaya>
        <jumlah_kubah>1</jumlah_kubah>
        <jumlah_menara>1</jumlah_menara>
        <kapasitas unit="jamaah">1000</kapasitas>
    </arsitektur>
    <fasilitas>
        <item>Area Parkir Luas</item>
        <item>Ruang Serbaguna</item>
        <item>Perpustakaan Digital</item>
        <item>Taman Hijau</item>
    </fasilitas>
</masjid_raya>

<?xml version="1.0" encoding="UTF-8"?>
<kml xmlns="http://www.opengis.net/kml/2.2">
  <Placemark>
    <name>Masjid Raya Depok</name>
    <description>Masjid ikonik di pusat Kota Depok.</description>
    <Point>
      <coordinates>106.8234,-6.3919,0</coordinates>
    </Point>
  </Placemark>
  
</kml>
