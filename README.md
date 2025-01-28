1)HTML Dosyasının Oluşturulması: Yeni bir HTML dosyası oluşturun ve dosyayı sinif_tablosu.html olarak kaydedin.
2)Temel HTML Yapısı: HTML dosyasının temel yapısını oluşturun. <html>, <head>, <body>, <title> ve <style> etiketlerini doğru bir şekilde kullanın.
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>HTML Title Örneği</title>
    </head>
    <body>
    3)Sayfa Başlığı: Sayfanın başlığı olarak "Sınıf Tablosu" ifadesini kullanın ve <h1> etiketi ile sayfa başlığını belirleyin.
    <h1>Sınıf Tablosu</h1>
    4)Tablonun Oluşturulması: <table> etiketi ile bir tablo oluşturun. Tabloya başlık (header) satırı ekleyin ve dört sütun başlığı tanımlayın: "Öğrenci Numarası", "Adı", "Soyadı" ve "Notu".
<table>
                <tr>
            <table style="width:100%; border: 2px solid black;">
            <tr>
                <th>Öğrenci Numarası</th>
                <th>Adı</th>
                <th>Soyadı</th>
                <th>Notu</th>
                <th>Doğum Tarihi</th>    
            </tr>
            5)Öğrenci Bilgileri: Tabloya en az 5 öğrenci ekleyin. Her öğrenci için "Öğrenci Numarası", "Adı", "Soyadı" ve "Notu" bilgilerini doldurun.
            <tr>
                <td>07071907</td>
                <td>Cemre</td>
                <td>Sönmez</td>
                <td>100</td>
                <td>22.05.2001</td>
            </tr>
            <tr>
                <td>85769405</td>
                <td>Kaan</td>
                <td>Sönmez</td>
                <td>90</td>
                <td>30.03.2004</td>
             </tr>
             <tr>
                <td>85940244</td>
                <td>Denizhan</td>
                <td>Sönmez</td>
                <td>85</td>
                <td>21.01.2001</td>
             </tr>
             <tr>
                <td>53728956</td>
                <td>Aybüke</td>
                <td>Sönmez</td>
                <td>88</td>
                <td>03.07.2001</td>
             </tr>
             <tr>
                <td>83987267</td>
                <td>Büşra</td>
                <td>Sönmez</td>
                <td>92</td>
                <td>27.04.2000</td>
             </tr>
             <tr>
                <td>90879650</td>
                <td>Parla</td>
                <td>Sönmez</td>
                <td>83</td>
                <td>03.02.2000</td>
             </tr>
             <tr>
                <td>33768969</td>
                <td>Işık</td>
                <td>Sönmez</td>
                <td>70</td>
                <td>12.06.1999</td>
             </tr>
             <tr>
                <td>56271873</td>
                <td>Nagehan</td>
                <td>Sönmez</td>
                <td>78</td>
                <td>17.07.1999</td>
             </tr>
             6)Tablo Stilinin Belirlenmesi: Tabloya bazı temel stiller uygulayın:
Tablonun genişliğini yüzde 100 yapın.
Hücrelerin (th, td) kenarlıklarını belirleyin ve padding (iç boşluk) ekleyin.
Tablo başlık satırının (th) arka plan rengini belirleyin.
<style>
            /* th için arka plan rengi,padding,border,text-allignment belirleme */
            th {
                background-color: #2dd6d9;
                padding: 17px;
                border: 2px solid black;
                text-align: center;
            }
            /* td için padding,border,text-allignment belirleme */
            td {
                padding: 17px;
                border: 2px solid black;
                text-align: center;
            }
             </style>
        <table>
                <tr>
            <table style="width:100%; border: 2px solid black;">
            7) 7 ve 8. soruda istenenler 4 ve 5. soruda ekli durumdadır.
