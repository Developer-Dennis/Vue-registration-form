<template>
    <h1>Patient Management - Add Patient</h1>
    <form action="">
      <div class="biodata">
        <h3>Bio Data</h3>
        <label>First Name:</label>
        <input type="text" name="firstname" required>
        <label>Middle Name:</label>
        <input type="text" name="middlename" required>
        <label>Last Name:</label>
        <input type="text" name="lastname" required>
        <label>DOB:</label>
        <input type="date" name="date" required>
        <label>Gender:</label>
        <select name="gender" id="gender" required>
          <option value="male">Male</option>
          <option value="female">Female</option>
        </select>
        <label>OP File No:</label>
        <input type="text" name="fileno" required>
        <label>IP File No:</label>
        <input type="text" name="fileno" required>
        <label>ID No:</label>
        <input type="text" name="fileno" required>
        <label>Confirm ID No:</label>
        <input type="text" name="fileno" required>
        <label>Employement:</label>
        <select name="employed" id="employement" required>
          <option value="employementtype">Employement Type</option>
          <option value="employed">Employed</option>
          <option value="selfemployed">Self Employed</option>
        </select>
        <label>Employer:</label>
        <input type="text" name="employer" required>
        <label>Occupation:</label>
        <input type="text" name="occupation" required>
        <label>Email:</label>
        <input type="email" name="email" required>
      </div>
      <div class="contactinfo">
        <h3>Contact Information</h3>
        <label>Cellphone:</label>
        <input type="number" name="phonenumber" required>
        <label>Cellphone:</label>
        <input type="number" name="phonenumber" required>
        <label> Other Cellphone:</label>
        <input type="number" name="phonenumber" required>
        <label>Current residence:</label>
        <input type="text" name="residence" required>

        <label>County:</label>
        <select name="county" id="county" required>
          <option value="selectcounty">Select county</option>
          <option value="Uasingishu">UASIN GISHU</option>
          <option value="nandi">NANDI</option>
          <option value="nakuru">NAKURU</option>
          <option value="kisii">KISII</option>
          <option value="nyamira">NYAMIRA</option>
          <option value="elgeyomarakwet">ELGEYO MARAKWET</option>
          <option value="westpokot">WEST POKOT</option>
          <option value="laikipia">LAIKIPIA</option>
          <option value="samburu">SAMBURU</option>
          <option value="turkana">TURKANA</option>
          <option value="nairobi">NAIROBI</option>
          <option value="mombasa">MOMBASA</option>
          <option value="kiambu">KIAMBU</option>
          <option value="nyandarua">NYANDARUA</option>
          <option value="muranga">MURANGA</option>
          <option value="narok">NAROK</option>
          <option value="kajiado">KAJIADO</option>
          <option value="makueni">MAKUENI</option>
          <option value="machakos">MACHAKOS</option>
          <option value="kitui">KITUI</option>
          <option value="taitataveta">TAITA TAVETA</option>
          <option value="kilifi">KILIFI</option>
          <option value="kericho">KERICHO</option>
          <option value="bomet">BOMET</option>
          <option value="kakamega">KAKAMEGA</option>
          <option value="vihiga">VIHIGA</option>
          <option value="baringo">BARINGO</option>
          <option value="bungoma">BUNGOMA</option>
          <option value="kwale">KWALE</option>
          <option value="lamu">LAMU</option>
          <option value="nyeri">NYERI</option>
          <option value="wajir">WAJIR</option>
          <option value="garisa">GARISA</option>
          <option value="kisumu">KISUMU</option>
          <option value="migori">MIGORI</option>
          <option value="siaya">SIAYA</option>
          <option value="busia">BUSIA</option>
          <option value="homabay">HOMA BAY</option>
          <option value="transnzoia">TRANS-NZOIA</option>
          <option value="kirinyaga">KIRINYAGA</option>
          <option value="embu">EMBU</option>
          <option value="isiolo">ISIOLO</option>
          <option value="mandera">MANDERA</option>
          <option value="tharkanithi">THARAKA NITHI</option>
          <option value="tanariver">TANA RIVER</option>
          <option value="marsabit">MARSABIT</option>
          <option value="meru">MERU</option>
        </select>


        <label>Location:</label>
        <select name="location" id="location" required>
          <option value="selectlocation">select location</option>
          <option value="racecourse">RACECOURSE</option>
          <option value="langas">LANGAS</option>
          <option value="kapseret">KAPSERET</option>
          <option value="ndalat">NDALAT</option>
          <option value="kesses">KESSES</option>
          <option value="ainabkoi">AINABKOI</option>
          <option value="moiben">MOIBEN</option>
          <option value="molo">MOLO</option>
          <option value="nakuru">NAKURU</option>
          <option value="soy">SOY</option>
          <option value="turbo">TURBO</option>
          <option value="matunda">MATUNDA</option>
          <option value="kapsabet">KAPSABET</option>
          <option value="moiben">MOIBEN</option>
        </select>


        <label>Sub Location:</label>
        <select name="sublocation" id="sublocation" required>
          <option value="sub location">sub location</option>
          <option value="racecourse">RACECOURSE</option>
          <option value="corner">CORNER</option>
          <option value="chinese">CHINESE</option>
        </select>
      </div>
      <div class="upload">
        <input type="file" id="myFile" name="filename">
      </div>
     <button>Save</button>
    </form>
</template>

<script>
export default {
  name: 'HomeView',
  components: {
  }
}
</script>
<style>

*{
  padding: 0px;
  margin: 0px;
}
  h1{
    background-color: grey;
    font-size: 18px;
  }
  .biodata{
    float: left;
    background-color: rgb(164, 164, 255);
  }
  .biodata h3{
    text-align: left;
  }
  .contactinfo{
    float: left;
  }
  .upload{
    float: right;
  }
</style>