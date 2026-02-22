<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Open Source Notice - 펫플</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
            line-height: 1.6;
            color: #333;
            max-width: 800px;
            margin: 40px auto;
            padding: 0 20px;
            background-color: #f9f9f9;
        }
        .container {
            background-color: #fff;
            padding: 40px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
        }
        h1 {
            border-bottom: 2px solid #eee;
            padding-bottom: 10px;
            color: #2c3e50;
        }
        h2 {
            margin-top: 30px;
            color: #34495e;
            border-left: 4px solid #3498db;
            padding-left: 15px;
        }
        h3 {
            margin-top: 20px;
            color: #555;
        }
        .note {
            background-color: #e7f3fe;
            border-left: 6px solid #2196F3;
            margin-bottom: 15px;
            padding: 15px;
            font-size: 0.95em;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
            font-size: 0.9em;
        }
        th, td {
            text-align: left;
            padding: 12px;
            border-bottom: 1px solid #ddd;
        }
        th {
            background-color: #f8f9fa;
            font-weight: bold;
        }
        tr:hover {
            background-color: #f1f1f1;
        }
        .disclaimer {
            background-color: #fff3cd;
            border: 1px solid #ffeeba;
            padding: 20px;
            border-radius: 4px;
            font-size: 0.85em;
            color: #856404;
            margin-top: 30px;
        }
        footer {
            margin-top: 50px;
            text-align: center;
            font-size: 0.8em;
            color: #999;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>오픈소스 라이선스 고지 (Open Source Notice)</h1>
    <p>본 서비스(<strong>펫플</strong>)는 아래와 같은 오픈소스 소프트웨어를 사용하며, 각 소프트웨어의 저작권자 및 라이선스 규정을 준수합니다.</p>

    <hr>

    <h2>1. Android Application</h2>
    <div class="note">
        <strong>NOTE:</strong> 안드로이드 오픈소스 라이브러리 목록은 추후 추출하여 업데이트될 예정입니다.
    </div>
    <p style="color: #999;">- (추후 추가 예정)</p>

    <h2>2. Server Side Framework & Tools</h2>
    <p>서버 인프라 및 백엔드 구성에 사용된 주요 오픈소스 소프트웨어 목록입니다.</p>

    <table>
        <thead>
            <tr>
                <th>Software</th>
                <th>License</th>
                <th>Copyright</th>
                <th>Description</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><strong>Flask</strong></td>
                <td>BSD-3-Clause</td>
                <td>(c) 2010 Armin Ronacher & Pallets team</td>
                <td>Backend web application framework.</td>
            </tr>
            <tr>
                <td><strong>Nginx</strong></td>
                <td>BSD-2-Clause</td>
                <td>(c) 2002-2021 Igor Sysoev, Nginx, Inc.</td>
                <td>High-performance HTTP & reverse proxy server.</td>
            </tr>
            <tr>
                <td><strong>MariaDB Connector</strong></td>
                <td>LGPL-2.1</td>
                <td>(c) MariaDB Corporation Ab</td>
                <td>Python driver for connecting to MariaDB.</td>
            </tr>
            <tr>
                <td><strong>Certbot (EFF)</strong></td>
                <td>Apache-2.0</td>
                <td>(c) 2014 Electronic Frontier Foundation</td>
                <td>Tool for obtaining/renewing SSL certificates.</td>
            </tr>
        </tbody>
    </table>

    <h3>SSL/TLS Certificate</h3>
    <ul>
        <li>
            <strong>Let's Encrypt (CA)</strong>
            <ul>
                <li><strong>Description</strong>: SSL/TLS certificates provided by Internet Security Research Group (ISRG).</li>
                <li><strong>Notice</strong>: This service uses certificates issued by Let's Encrypt.</li>
            </tr>
        </ul>
    </li>

    <h2>3. General Disclaimer</h2>
    <div class="disclaimer">
        <p>본 소프트웨어는 저작권자 및 기여자들에 의해 <strong>"있는 그대로(AS IS)"</strong> 제공되며, 명시적 또는 묵시적인 보증을 포함하나 이에 국한되지 않는 모든 보증을 부인합니다. </p>
        <p>저작권자나 기여자는 어떠한 경우에도 본 소프트웨어의 사용으로 인해 발생하는 직접적, 간접적, 우발적, 특별한 손해(대체 재화나 서비스의 조달, 사용 손실, 데이터 신실, 이익 손실, 영업 중단 등)에 대해 책임을 지지 않습니다. 이는 계약상 책임, 엄격 책임 또는 불법 행위(과실 포함) 등 어떠한 책임 이론에 근거하더라도 마찬가지이며, 그러한 손해의 가능성을 사전에 알고 있었더라도 동일하게 적용됩니다. </p>
    </div>

    <footer>
        &copy; 2024 펫플. All rights reserved.
    </footer>
</div>

</body>
</html>
