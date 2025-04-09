<!DOCTYPE html>
<html lang="zh">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>富国岛3天旅游规划表</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            width: 210mm;
            height: 297mm;
            padding: 10mm;
            box-sizing: border-box;
        }
        .container {
            display: grid;
            grid-template-columns: 1fr;
            grid-gap: 10mm;
        }
        .section {
            border: 1px solid #ccc;
            padding: 5mm;
        }
        h1, h2, h3 {
            margin: 0;
            padding: 0;
        }
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid #ccc;
            padding: 5px;
            text-align: left;
        }
        .print-button {
            margin-top: 10mm;
            text-align: center;
        }
        @media print {
            .print-button {
                display: none;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- 行程标题区 -->
        <div class="section">
            <h1>富国岛3天旅游规划</h1>
            <p>日期：2023年10月1日 - 2023年10月3日</p>
            <p>天气：晴，28°C/22°C</p>
        </div>

        <!-- 行程概览区 -->
        <div class="section">
            <h2>行程概览</h2>
            <ul>
                <li>第一天：富国国家公园、富国监狱博物馆、胡椒农场</li>
                <li>第二天：长滩、浮潜或潜水、海鲜晚餐</li>
                <li>第三天：珍珠岛游乐园、购物、放松</li>
            </ul>
        </div>

        <!-- 详细时间表区 -->
        <div class="section">
            <h2>详细时间表</h2>
            <table>
                <tr>
                    <th>时间</th>
                    <th>活动</th>
                    <th>地点</th>
                    <th>详情</th>
                </tr>
                <tr>
                    <td>09:00-11:00</td>
                    <td>游览富国国家公园</td>
                    <td>富国岛</td>
                    <td>门票：免费</td>
                </tr>
                <tr>
                    <td>11:30-13:00</td>
                    <td>参观富国监狱博物馆</td>
                    <td>富国岛</td>
                    <td>门票：20,000 VND</td>
                </tr>
                <!-- 继续添加其他活动 -->
            </table>
        </div>

        <!-- 交通信息区 -->
        <div class="section">
            <h2>交通信息</h2>
            <p>主要交通方式：摩托车、出租车</p>
            <p>预计交通时间：市区到富国国家公园约30分钟</p>
        </div>

        <!-- 住宿与餐饮区 -->
        <div class="section">
            <h2>住宿与餐饮</h2>
            <p>酒店：富国岛海滩度假村</p>
            <p>推荐餐厅：富国岛海鲜餐厅</p>
        </div>

        <!-- 实用信息区 -->
        <div class="section">
            <h2>实用信息</h2>
            <p>紧急联系电话：+84 123 456 789</p>
            <p>注意事项：注意防晒，保管好个人物品</p>
        </div>

        <!-- 打印按钮 -->
        <div class="print-button">
            <button onclick="window.print()">打印规划表</button>
        </div>
    </div>
</body>
</html>
