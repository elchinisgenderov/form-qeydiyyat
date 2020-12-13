# form-qeydiyyat
<!DOCTYPE html>
<html>
    <head>
        <title>Ders 4</title>
        <meta name="keywords" content="">
        <meta name="description" content="">
        <link rel="stylesheet" href="css/style.css">
    </head>
    <body>
        <!-- =============================== -->
        <!-- ============Form============ -->
        <!-- =============================== -->
        <div class="container">
            <h2>Registration Form</h2>
            <form action="#" method="POST">
            
        <!-- =============================== -->
        <!-- ============hEAD DIV============ -->
        <!-- =============================== -->
              <div class="box_1">
                    <!-- ============Ad============ -->
                 <div class="group">
                    <label for="fname">First Name</label>
                    <input type="text" name="" placeholder="Adini yazin">
                 </div>
                 
                 <!-- ============Soyad============ -->
                 <div class="group">
                     <label for="lname">Last Nmae</label>
                     <input type="text" name="" placeholder="Soyadinizi yazin">
                 </div>
                 
                 <!-- ============Ad gunu============ -->
                 <div class="group">
                    <label for="brithday">Brithday</label>
                    <input type="month" name="" value="">
                </div>
                
                <!-- ============Cins============ -->
                <div class="group">
                    <label for="gender">Gender</label>
                    <br>
                    <label for="male" >Male</label>
                    <input type="radio" name="" class="radio">
                    <label for="famale">Famale</label>
                    <input type="radio" name="" class="radio">
                </div>
                <br>
                <!-- ============Mail============ -->
                <div class="group">
                    <label for="mail">Email</label>
                    <input type="email" name="" placeholder="Emailinizi yazin">
                </div>
                <br>
                <!-- ============Phone============ -->
                <div class="group">
                    <label for="phone">Phone</label>
                    <input type="nubmer" name="" placeholder="Nomrenizi yazin">
                </div>
                <br>
              </div>

              <!-- =============================== -->
              <!-- ============footer DIV============ -->
              <!-- =============================== -->

              <div class="">
                  <!-- ============Select============ -->
                  <div class="">
                    <span>Subject</span>
                     <select autofocus>
                         <option value="">Subject1</option>
                         <option value="">Subject2</option>
                         <option value="">Subject3</option>
                     </select>
                  </div>
                  <br>
                  <!-- ============Submit============ -->
                  <div class="">
                      <input type="submit" value="Qeydiyyatdan kec">
                  </div>
              </div>
            </form>
        </div>
    </body>
</html>
