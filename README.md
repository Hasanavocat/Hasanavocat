- 👋 Hi, I’m @Hasanavocat
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Hasanavocat/Hasanavocat is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>مدونتي الشعرية</title>
    <style>
        body {
            background-color: #f0fff0; /* لون أخضر فاتح جداً */
            font-family: Arial, sans-serif;
            color: #333;
            direction: rtl;
            text-align: right;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #a8d5ba; /* لون أخضر بدرجة أغمق قليلاً للرأس */
            padding: 20px;
            text-align: center;
        }
        h1 {
            margin: 0;
        }
        .content {
            padding: 20px;
        }
        .poem-section {
            margin-bottom: 40px;
        }
        h2 {
            color: #4a7c59; /* لون أغمق للعناوين */
        }
        .comment-section {
            margin-top: 40px;
        }
        input[type="text"], textarea {
            width: 100%;
            padding: 10px;
            margin: 5px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        input[type="submit"] {
            background-color: #4a7c59;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        input[type="submit"]:hover {
            background-color: #3a6246;
        }
    </style>
</head>
<body>

<header>
    <h1>مدونتي الشعرية</h1>
</header>

<div class="content">
    <!-- قسم الأشعار -->
    <div class="poem-section" id="love">
        <h2>أشعار الحب</h2>
        <p>...أدخل أشعار الحب هنا...</p>
    </div>

    <div class="poem-section" id="nature">
        <h2>أشعار الطبيعة</h2>
        <p>...أدخل أشعار الطبيعة هنا...</p>
    </div>

    <div class="poem-section" id="philosophy">
        <h2>أشعار الفلسفة</h2>
        <p>...أدخل أشعار الفلسفة هنا...</p>
    </div>

    <!-- قسم التعليقات -->
    <div class="comment-section">
        <h2>اترك تعليقك</h2>
        <form action="#" method="post">
            <label for="name">اسمك:</label>
            <input type="text" id="name" name="name" required>

            <label for="comment">تعليقك:</label>
            <textarea id="comment" name="comment" rows="4" required></textarea>

            <input type="submit" value="إرسال التعليق">
        </form>
    </div>
</div>

</body>
</html>
