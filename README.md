# CheckBox-Image-Change


### Input - [CheckBox]
```
<!-- CSS -->
<style>
.checkboxImg{display:inline-block; width:30px; height:30px; 
             background-image:url('https://icon-icons.com/icons2/472/PNG/48/unchecked_checkbox-48_44481.png'); 
             background-repeat:no-repeat; background-size:cover; background-position:0 0; cursor:pointer;}
input[type="checkbox"]{display:none;}
input[type="checkbox"]:checked+.checkboxImg{background-image:url('https://icon-icons.com/icons2/472/PNG/48/checked_checkbox-48_44484.png'); }
</style>


<!-- HTML -->
<input type="checkbox" name="chk">
<div class="checkboxImg" onclick="this.previousElementSibling.checked ^= 1;"></div>
```

_ _ _
### Input - [Radio]
```
<!-- CSS -->
<style>
.radioImg{display:inline-block; width:30px; height:30px; 
          background-image:url('https://image.flaticon.com/icons/svg/149/149148.svg'); 
          background-repeat:no-repeat; background-size:cover; background-position:0 0;  cursor:pointer;} 
input[type="radio"]{display:none;} 
input[type="radio"]:checked+.radioImg{background-image:url('https://image.flaticon.com/icons/svg/148/148767.svg'); }
</style>

<!-- HTML --> 
<input type="radio" name="rdo" checked>
<div class="radioImg" onclick="this.previousElementSibling.checked |= 1"></div>
<input type="radio" name="rdo">
<div class="radioImg" onclick="this.previousElementSibling.checked |= 1"></div>
<input type="radio" name="rdo">
<div class="radioImg" onclick="this.previousElementSibling.checked |= 1"></div>

```
