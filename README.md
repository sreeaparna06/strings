<!DOCTYPE html>
<html>
<body>
<script>
  function alpha(str) {
    var arr = str.split(""); 
    res = arr.sort().join(""); 
    return res; 
  }
  str =prompt("enter any string")
  document.write(alpha(str));
</script>
</body>
</html>
