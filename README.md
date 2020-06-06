  
<!DOCTYPE html>
<html>
<head>
  <title>Topic 3</title>
  <link rel="stylesheet" type="text/css" href="assets/css/bootstrap.css">
  <link rel="stylesheet" type="text/css" href="assets/css/bootstrap2.css">
  <link rel="icon" href="assets/img/icon.png">
  <script>
        /*
            function coba(){
                document.getElementById("inputEmail").addEventListener("keyup", function(event){
                    event.preventDefault();
                    if(event.keyCode === 13){
                        document.getElementById("inputpass").focus();
                    }
                });
            }
        */
            function alertsalahlogin() {
                // body...
            }
            window.setTimeout(function () {
                $(".alert").fadeTo(400,0).slideUp(400,function () {
                    $(this).remove();
                });
            }, 4000);
            function showModalku() {
                $(document).ready(function () {
                    $('#ModalKu').modal('show')
                });
            }
        </script>
  <style type="text/css">
    body{
      background-image: url(https://i.imgur.com/rG2uegc.jpg);
    }
  </style>
</head>
<body>
  <form>
    <div class="vid-container">
    <div class="inner-container">
      <div align="center" class="alert alert-primary alert-dismissible fade show" role="alert">
        ~ Selamat Datang ~
      </div>
      <div class="box">
        <center><img src="assets/img/icon.png" width="80" height="80"></center>
        <h1>Silahkan Masuk</h1>
        <p>Selamat Belajar</p>
        <input type="text" placeholder="Username"/>
        <input type="text" placeholder="Password"/>
        <button class="btn btn-primary btn-block" type="button">Login</button>
        <p>Bukan anggota ? <span>Mendaftar</span></p>
        <!--<button class="btn btn-primary btn-block" type="button" data-toggle="modal" data-target="#ModalKu">
          Show Modal Madul
        </button>-->
        <button onclick="showModalku();" class="btn btn-primary btn-block" type="button" data-toggle="modal">
          Show Modal dengan JS
        </button>
      </div>
    </div>
  </div>
  </form>
  <div class="modal fade" id="ModalKu" tabindex="-1" role="dialog" aria-labelledby="DialogModalLabel" aria-hidden="true">
            <div class="modal-dialog" role="document">
                <div class="modal-content">
                    <div class="modal-header">
                        <h5 class="modal-title" id="ModalLabel01">
                            Username atau Password Salah
                        </h5>
                        <button class="close" type="button" data-dismiss="modal" arial-label="close">
                            <span aria-hidden="true">&times;</span>
                        </button>
                    </div>
                    <div class="modal-body">
                        <p>
                            Klik Mendaftar untuk mendapatkan user dan password
                        </p>
                    </div>
                    <div class="modal-footer">
                        <button class="btn btn-secondary" type="button" data-dismiss="modal">
                            TUTUP
                        </button>
                    </div>
                </div>
            </div>
        </div>
  <script src="assets/js/jquery.min.js"></script>
  <script src="assets/js/popper.min.js"></script>
  <script src="assets/js/bootstrap.min.js"></script>
</body>
</html>
Penjelasan
2	 <html>	Tag pembuka untuk membuat dokumen HTML
3	 <head>	Informasi meta tentang dokumen
4	 <title>	Membuat judul halaman yang nantinya akan ditampilkan di browser
5	 <body>	Tempat dibuatnya semua konten website menggunakan HTML
6.    style	 Atribut untuk elemen styling pada HTML
7. <link> digunakan untuk membuat "hubungan" antara halaman HTML dengan file lain.
8. <div> untuk mengovirmasikan link
9. <heading> untuk mebuat font paragraf
10.<p> untuk mebuat Baris baru
11.<form> tempat penginputan data sebelum diproses oleh sistem.
12.<script> Menunjukkan asynchronously yang berarti tidak serempak. 
13.<buton> untuk mebuat tombol
