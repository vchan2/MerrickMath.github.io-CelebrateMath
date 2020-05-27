# Part I



Onward: <input id='password' type='text'  />
<a href="https://MerrickMath.github.io/part2.html" onclick="javascript:return validatePass()">  Click here to submit  </a>
<script>
function validatePass(){
    if(document.getElementById('password').value == '38'){
        return true;
    }else{
        alert('wrong password!!');
        return false;
    }
}
</script>


