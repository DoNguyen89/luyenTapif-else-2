Viết chương trình kiểm tra đăng nhập hệ thống của người dùng theo yêu cầu sau

Yêu cầu người dùng nhập tên từ bàn phím. 

    Nếu tên nhập vào là Admin thì yêu cầu nhập mật khẩu.
        Nếu mật khẩu là TheMaster thì in ra chuỗi Welcome.
        Nếu mật khẩu nhập vào là null in ra chuỗi Canceled.
        Còn lại in ra chuỗi Wrong password. 
    Nếu tên nhập vào là null in ra chuỗi canceld.
    Còn lại in ra chuỗi “I don’t know you"



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>luyenTapifelse_2</title>
</head>
<body>
    <script>
        var userName = prompt("Who's there?", ' ');
        if (userName == 'Admin') {
            var passWord = prompt("Password?", '');
            if (passWord == 'TheMaster') {
                alert('Welcome');
            }
            else if (passWord == 'null') {
                alert('Canceled');
            }
            else
                alert('Wrong password');
        }
         else if ( userName == 'null') {
                alert('canceled');
            }
         else
             alert("i don't know you");

    </script>
</body>
</html>
