# Pepson API for Developers
<!-- The text field -->
<input type="text" value="pip install pepson-api" id="myInput">

<!-- The button used to copy the text -->
<button onclick="myFunction()">Copy</button>
<!-- The JavaScript Source to Copy Code-->
<script>
function myFunction() {
  /* Get the text field */
  var copyText = document.getElementById("myInput");

  /* Select the text field */
  copyText.select();
  copyText.setSelectionRange(0, 99999); /* For mobile devices */

   /* Copy the text inside the text field */
  navigator.clipboard.writeText(copyText.value);

  /* Alert the copied text */
  alert("Copied the text: " + copyText.value);
}
</script>

# What Is Pepson API?
Pepson API is a Powerfull API to Connect your Project with Pepson
Pepson API is free, open source, integrates easly, ease to use and more
# Then How Do I Create a Web App
type this piece of code: pepson.create "app" type="web" name="name"

# How I Create a OAuth App?
type this piece of code: pepson.create "oauth" type="auth" name="name"
