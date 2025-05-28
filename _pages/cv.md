---
permalink: /cv/
---
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Redirecting to CV...</title>
    <script type="text/javascript">
        // 获取当前路径并构建正确的 PDF 路径
        var pathArray = window.location.pathname.split('/');
        var baseIndex = pathArray.indexOf('dudusama');
        if (baseIndex !== -1) {
            var basePath = pathArray.slice(0, baseIndex + 1).join('/');
            window.location.href = basePath + '/files/cv.pdf';
        } else {
            window.location.href = '/files/cv.pdf';
        }
    </script>
</head>
<body>
    <p>Loading CV...</p>
</body>
</html>
