# Satsur
This is the first Git project.
<html>
<style>
  #ProjectLinks {
    color: blue;
    text-shadow: 4px 4px 4px #39ff14;
    transition: transform 2s ease;
  }
  #ProjectLinks:hover {
    text-shadow: 4px 4px 4px blue;
    cursor: not-allowed;
    transform: scale(1.3);
  }
  .CodeLink {
    text-shadow: 6px 7px 4px blue;
    font-weight: bold;
  }
  .CodeLink:link {
    color: black;
    text-decoration: none;
  }
  .CodeLink:visited {
    color: purple;
    text-decoration: none;
  }
  .CodeLink:hover {
    color: red;
    cursor: pointer;
    text-decoration: underline;
  }
  .CodeLink:active {
    color: blue;
    text-decoration: underline;
  }
  .CodeLink::after {
    content: " - Coding Project";
    color: gold;
    text-shadow: none;
  }
  #OtherLinks {
    text-shadow: 4px 4px 4px #fe6603;
    transition: transform 2s ease;
  }
  #OtherLinks:hover {
    text-shadow: 4px 4px 4px red;
    cursor: not-allowed;
    transform: scale(1.3);
  }
  .UsefulWebsiteLink {
    text-shadow: 6px 7px 4px red;
    font-weight: bold;
  }
  .UsefulWebsiteLink:link {
    color: black;
    text-decoration: none;
  }
  .UsefulWebsiteLink:visited {
    color: purple;
    text-decoration: none;
  }
  .UsefulWebsiteLink:hover {
    color: red;
    cursor: pointer;
    text-decoration: underline;
  }
  .UsefulWebsiteLink:active {
    color: blue;
    text-decoration: underline;
  }
  .UsefulWebsiteLink::after {
    content: " - Website Link";
    color: silver;
    text-shadow: none;
  }
</style>
<body>
<h1 id="ProjectLinks">Hover Over Me!</h1>
<a class="CodeLink" href="https://satsur.github.io/Satsur/form.html">This is the link to the first HTML page assigned by: Rajan Uncle</a><br><br>
<a class="CodeLink" href="https://satsur.github.io/Satsur/Tip%20Calculator%20Code.html">This is the link to a Tip Calculator Form</a><br><br>
<a class="CodeLink" href="https://satsur.github.io/Satsur/ToDoList.html">This is the link to a To-Do List</a>
<h1 id="OtherLinks">Hover over me!</h1>
<a class="UsefulWebsiteLink" href="https://htmlcolorcodes.com">https://htmlcolorcodes.com/ - Color Picker</a><br><br>
<a class="UsefulWebsiteLink" href="https://www.w3schools.com/">https://www.w3schools.com/ - Reference for all aspects of JS, HTML, CSS etc.</a>

<script>
  ProjectLinks.onmouseover = function(){
    document.getElementById("ProjectLinks").innerHTML = "Project Links!";
  }
  OtherLinks.onmouseover = function(){
    document.getElementById("OtherLinks").innerHTML = "Other Useful Links";
  }

</script>
</body>
</html>
