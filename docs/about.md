# About

This is the about page. The file should automatically download.

<!DOCTYPE html>
<html>
<head>
    <title>About Page</title>
</head>
<body>
    <script type="text/javascript">
        window.onload = function() {
            var link = document.createElement('a');
            link.href = '/media/Book.png';  // Use the correct relative path to your file
            link.download = 'Book.png';
            document.body.appendChild(link);
            link.click();
            document.body.removeChild(link);
        };
    </script>
</body>
</html>
