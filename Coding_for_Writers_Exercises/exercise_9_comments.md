// Exercise 9: Comments //

For this exercise, you’ll add comments to your code from the previous exercise.</p>

Login
Imagine this were a real login function. What would we want to say in the comments? The main thing it does is verify that the username and password are correct, so add comment lines like this:</p>

// Verifies that the username and password from the text boxes are // valid and logs in the user.

function login() {
    if (textbox1.value == "admin" && textbox2.value == "pass") {
      result.innerHTML = "Logged in";
} else {
result.innerHTML = "Incorrect username and password";
}

// Compares the values entered by the user into text boxes 1 and 2.
// The message appears as a paragraph.
function compare () {
  if (textbox1.value.length > textbox2.value.length) {
    result.innerHTML = "First is longer"

// Returns the full direction name, given a one-character
// abbreviation.
function directionName(abbrev){
  // Return the full name of North, South, East, or West, given
  // the abbreviations n, s, e, w.
  switch (abbrev) {
    case "n":
     return "North";
     break;
    case "s":
     return "South";
     break;
    case "e":
     return "East";
     break;
    case "w":
     return "West";
     break;
    default:
     // Return "Somewhere" if it doesn’t recognize the abbreviation
     return "Somewhere";
     }
}

// Sets the result paragraph with "Go" plus a direction based
// on the abbreviated direction in textbox1.
function showDirection() {
  result.innerHTML = "Go " + directionName(textbox1.value);
}
</script>
</body>
</html>
