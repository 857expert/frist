# frist
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>链接伪类选择器</title>
    <style>
        /* 未访问过的链接 */
        a:link {
            color: black;
            text-decoration: none;
        }

        /* 选择访问过的链接 */
        a:visited {
            color: coral;
        }

        /* 鼠标经过的链接 */
        a:hover {
            color: skyblue;
        }

        /* 没有弹起的链接 */
        a:active {
            color: orchid;
        }
    </style>
</head>

<body>
    <a href="#">佩奇</a>
    <a href="#">某某</a>
</body>

</html>
