```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <style type="text/css">
        * {
            margin: 0;
            padding: 0;
        }

        body {
            font-size: 12px;
        }

        table {
            border-collapse: collapse;
            border-spacing: 0;
        }
        .demo {
            margin: 100px;
            width: 470px;
            border: 1px solid #4b8df9;
            overflow: auto;
            min-height: 0.01%;
        }

        .demo table {
            table-layout: fixed;
            width: 140%;
            background-color: #fff;
            border: 1px solid #ddd;
            font-size: 13px;
        }

        .demo table th {
            padding: 8px 0;
            text-align: left;
            text-indent: 15px;
            border: 1px solid #ddd;
            border-top: none;
            border-bottom-width: 2px;
        }

        .demo table td {
            padding: 8px;
            border: 1px solid #ddd;
            text-overflow:ellipsis;
            word-break:keep-all;
            overflow:hidden;
            white-space: nowrap;
        }

        .demo table tbody tr:nth-of-type(odd) {
            background: #f9f9f9;
        }

        .demo .col2 {
            width: 80px;
        }

        .demo .col3 {
            width: 70px;
        }

        .demo .col4 {
            width: 60px;
        }

        .demo .col5 {
            width: 110px;
        }

        .demo .col6 {
            width: 70px;
        }

        .demo .col7 {
            width: 70px;
        }
    </style>
</head>
<body>

<div class="demo">
    <table>
        <thead>
        <tr>
            <th class="col1">产品名称</th>
            <th class="col2">基金代码</th>
            <th class="col3">产品类型</th>
            <th class="col4">净值</th>
            <th class="col5">购买期</th>
            <th class="col6">购买起点</th>
            <th class="col7">风险等级</th>
        </tr>
        </thead>
        <tbody>
        <tr>
            <td title="建信安心保本6号建信安心保本6号建信安心保本6号">建信安心保本6号建信安心保本6号建信安心保本6号</td>
            <td>002573</td>
            <td>股票型</td>
            <td>1.00</td>
            <td>20160405-0429</td>
            <td>10000</td>
            <td>高风险</td>
        </tr>
        <tr>
            <td>建信安心保本6号</td>
            <td>002573</td>
            <td>股票型</td>
            <td>1.00</td>
            <td>20160405-0429</td>
            <td>10000</td>
            <td>高风险</td>
        </tr>
        <tr>
            <td>建信安心保本6号</td>
            <td>002573</td>
            <td>股票型</td>
            <td>1.00</td>
            <td>20160405-0429</td>
            <td>10000</td>
            <td>高风险</td>
        </tr>
        </tbody>
    </table>
</div>
</body>
</html>
```
http://codepen.io/zplus/pen/WwgEGw
