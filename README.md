# ʹ��Bootstrap������ǰ��С��Ŀ

### ����:����һ����׼��bootstrapҳ��:

```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0,user-scalable=no">
    <title>title</title>
    <!-- ����bootstrao������ʽ -->
    <link href="https://cdn.bootcdn.net/ajax/libs/twitter-bootstrap/4.5.0/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
	....
    <!-- ����bootstrap��js�ļ� -->
    <script src="https://cdn.bootcdn.net/ajax/libs/jquery/3.5.1/jquery.slim.min.js"></script>
    <script src="https://cdn.bootcdn.net/ajax/libs/twitter-bootstrap/4.5.0/js/bootstrap.bundle.min.js"></script>
    <script>
        // ����������ʾ
        $(function () {
            $('[data-toggle="popover"]').popover()
        })
        // ������ʾ��
        $(function () {
            $('[data-toggle="tooltip"]').tooltip()
        })
    </script>
</body>
</html>
```
### �����˽�:

�����˽�bootstrap������Բ鿴���� -- [bootstrap����](getbootstrap.com)



