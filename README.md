<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>页面跳转中</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            background: #f5f5f5;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            font-family: -apple-system, "PingFang SC", "Microsoft YaHei", sans-serif;
            padding: 20px;
        }
        .card {
            background: white;
            border-radius: 16px;
            box-shadow: 0 4px 20px rgba(0,0,0,0.08);
            padding: 40px 24px;
            text-align: center;
            max-width: 320px;
            width: 100%;
        }
        .icon {
            font-size: 48px;
            margin-bottom: 16px;
        }
        h2 {
            font-size: 20px;
            color: #333;
            margin-bottom: 8px;
        }
        p {
            font-size: 15px;
            color: #666;
            margin-bottom: 28px;
            line-height: 1.5;
        }
        .btn {
            display: block;
            width: 100%;
            padding: 14px 0;
            background: #07c160;
            color: white;
            font-size: 17px;
            font-weight: 600;
            border: none;
            border-radius: 12px;
            cursor: pointer;
            text-decoration: none;
            transition: background 0.2s;
        }
        .btn:active {
            background: #06ad56;
        }
        .hint {
            margin-top: 16px;
            font-size: 13px;
            color: #999;
        }
    </style>
</head>
<body>
    <div class="card">
        <div class="icon">🔗</div>
        <h2>即将打开目标页面</h2>
        <p>请点击下方按钮继续访问<br>如无法打开，可点击右上角<br>「在浏览器中打开」</p>
        <a class="btn" onclick="redirectTo()">点击进入目标页面</a>
        <div class="hint">为确保流畅访问，请允许跳转</div>
    </div>

    <script>
        function redirectTo() {
            // 目标链接，请替换成你需要的地址
            window.location.href = "https://frost888.iosifk.top";
        }
    </script>
</body>
</html>
