# Satsur
This is the first Git project.
<html>
<style>
  #ProjectLinks {
    color: blue;
    text-shadow: 4px 4px 4px #39ff14;
  }
  #ProjectLinks:hover {
    text-shadow: 4px 4px 4px  #fe6603;
    cursor: not-allowed;

  }
  .CodeLink:link {
    font-weight: bold;
    color: black;
  }
  .CodeLink:visited {
    font-weight: bold;
    color: purple;
  }
  .CodeLink:hover {
    font-weigt: bold;
    color: red;
    cursor: pointer;
  }
  .CodeLink:active {
    font-weight: bold;
    color: blue
  }
  #OtherLinks {
    text-shadow: 4px 4px 4px #fe6603;
  }
  #OtherLinks:hover {
    text-shadow: 4px 4px 4px #39ff14;
    cursor: not-allowed;
  }
</style>
<body>
<h1 id="ProjectLinks">Hover Over Me!</h1>
<a class="CodeLink" href="https://satsur.github.io/Satsur/form.html">This is the link to the first HTML page assigned by: Rajan Uncle</a><br><br>
<a class="CodeLink" href="https://satsur.github.io/Satsur/Tip%20Calculator%20Code.html">This is the link to a Tip Calculator Form</a><br><br>
<a class="CodeLink" href="https://satsur.github.io/Satsur/ToDoList.html">This is the link to a To-Do List</a>
<h1 id="OtherLinks">Hover over me and press enter!</h1>

<script>
  ProjectLinks.onmouseover = function(){
    document.getElementById("ProjectLinks").innerHTML = "Project Links!";
  }
  OtherLinks.onmouseover = function(){
    OtherLinks.onkeypress = function(e){
      if(e.which == 13) {
        document.getElementById("OtherLinks").innerHTML = "Other Useful Links!"
      }
    }
  }

</script>
</body>
</html>
