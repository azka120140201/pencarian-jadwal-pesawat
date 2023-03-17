# pencarian-jadwal-pesawat
![image](https://user-images.githubusercontent.com/101125177/225956595-a8379c34-9a84-46f1-bb9f-9f9faec80021.png)
![image](https://user-images.githubusercontent.com/101125177/225956664-2dd67cb7-01a2-4886-ac62-e0cb6a892cb7.png)

data class Jadwal(val jadwal_id: Int, val bandara_kode_keberangkatan: String, val bandara_kode_tujuan: String, val maskapai_id: Int)
data class Maskapai(val maskapai_id: Int, val maskapai_nama: String, val maskapai_logo: String)
data class Bandara(val bandara_kode: String, val bandara_nama: String)
