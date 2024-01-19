<!DOCTYPE html>
<html>
<head>
    <title>Redirect</title>
    <script>
        window.onload = function() {
            var url = 'google.com';
            var base64url = btoa(url);
            window.location = atob(base64url);
        }
    </script>
</head>
<body>
</body>
</html>
