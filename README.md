# Dark-Light-Mode
This source code is based on javascript.

This is the Javascript source code:

<script>
    var content = document.getElementsByTagName("body")[0];
    var darkMode = document.getElementById("dark-change");
    darkMode.addEventListener('click',function() {
        darkMode.classList.toggle('active')
        content.classList.toggle('night')
    })
    
</script>

And also I had given the STYLE for the toggle:

    label.active::before{
        left: 24px;
        background: #fff;
    }
    body.night{
        background: #000;
        color: #fff;
    }
    
    If you had any doughts reffer the above codes.
    
    
    
    
    And also I had given the another method to create the dark-light-mode using javascript
    the source is given below:
    
    
 <button onclick="dark()"></button>

<script>
function dark() {
   var element = document.body;
   element.classList.toggle("dark-mode");
}
</script>

The above code is a button toggle is used to change the dark mode 
