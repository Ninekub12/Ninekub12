ได้เลย! นี่คือตัวอย่างโค้ด HTML และ JavaScript ที่แสดงการแจ้งเตือนเมื่อผู้ใช้กดปุ่ม:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Notification Example</title>
    <script>
        function showAlert() {
            alert("คุณได้กดปุ่มแล้ว!");
        }
    </script>
</head>
<body>
    <button onclick="showAlert()">กดปุ่มนี้</button>
</body>
</html>
```

ในโค้ดนี้:

1. สร้างปุ่มใน HTML ด้วย `<button>`
2. เมื่อคลิกปุ่ม จะเรียกใช้ฟังก์ชัน `showAlert()` ซึ่งแสดงการแจ้งเตือนด้วยคำสั่ง `alert()`

เพียงเท่านี้เมื่อคุณกดปุ่มก็จะมีข้อความแจ้งเตือนปรากฏขึ้น! ลองนำไปใช้ในโปรเจกต์ของคุณดูนะ.

อยากทำอะไรเพิ่มเติมอีกไหม?
