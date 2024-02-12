## try
### trying images
- here is an image attached
---

💡
![beautifull_tree](ritik1.jpg)
<<<<<<< HEAD

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Interactive Select</title>
</head>
<body>

<select id="selectOptions" onchange="displaySelectedOption()">
  <option value="option1">Option 1</option>
  <option value="option2">Option 2</option>
  <option value="option3">Option 3</option>
</select>

<p id="selectedOption">Selected Option will appear here</p>
<p id="displaySelectedOption">Selected Option: </p> <!-- New paragraph element -->

<script>
function displaySelectedOption() {
  var selectElement = document.getElementById("selectOptions");
  var selectedOption = selectElement.options[selectElement.selectedIndex].text;
  document.getElementById("selectedOption").innerText = "Selected Option: " + selectedOption;
  document.getElementById("displaySelectedOption").innerText = "Selected Option: " + selectedOption; // Update the content of the new paragraph
}
</script>

</body>
</html>
=======
