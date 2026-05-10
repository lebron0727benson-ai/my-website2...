# my-website2...
<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI 影像辨識技術探索 | 高三專題</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f4;
            color: #333;
        }
        .container {
            max-width: 1200px;
            margin: auto;
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        h1, h2 {
            color: #2c3e50;
        }
        img, video, iframe {
            max-width: 100%;
            border-radius: 8px;
            margin: 10px 0;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 12px;
            text-align: left;
        }
        th {
            background-color: #3498db;
            color: white;
        }
        .gallery {
            display: flex;
            gap: 15px;
            flex-wrap: wrap;
            margin: 20px 0;
        }
        .gallery img {
            width: 200px;
            height: auto;
            box-shadow: 2px 2px 5px rgba(0,0,0,0.2);
        }
        hr {
            margin: 30px 0;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>📷 探索 AI 影像辨識技術</h1>
            <p><strong>發表時間：</strong> 2026年5月10日 | <strong>作者：</strong> 高三數據分析師</p>
            <p>人工智慧在電腦視覺領域的突破，讓機器能夠「看懂」世界。從人臉解鎖到自動駕駛，影像辨識已深入生活。本網站將展示 AI 如何辨識物體、人臉與動作，並透過下方表格和範例，讓你了解這項技術的核心數據與實際應用。</p>
        </header>

        <hr>

        <h2>📊 常見 AI 影像辨識模型效能比較</h2>
        <table>
            <thead>
                <tr>
                    <th>模型名稱</th>
                    <th>發表年份</th>
                    <th>Top-1 準確率 (ImageNet)</th>
                    <th>主要特點</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>ResNet-50</td>
                    <td>2015</td>
                    <td>76.5%</td>
                    <td>殘差網路，解決梯度消失問題</td>
                </tr>
                <tr>
                    <td>EfficientNet-B0</td>
                    <td>2019</td>
                    <td>77.1%</td>
                    <td>模型縮放方法，參數更少效率高</td>
                </tr>
                <tr>
                    <td>Vision Transformer (ViT)</td>
                    <td>2020</td>
                    <td>85.6%</td>
                    <td>將 Transformer 應用於影像分類</td>
                </tr>
                <tr>
                    <td>ConvNeXt</td>
                    <td>2022</td>
                    <td>86.8%</td>
                    <td>現代化卷積網路，媲美 Transformer</td>
                </tr>
            </tbody>
        </table>

        <hr>

        <h2>🖼️ AI 視覺應用案例</h2>
        <div class="gallery">
            <img src="https://picsum.photos/id/1/300/200" alt="AI 辨識風景中的物體" title="物體辨識：湖泊與山脈">
            <img src="https://picsum.photos/id/26/300/200" alt="AI 人臉偵測與標記" title="人臉偵測技術">
            <img src="https://picsum.photos/id/42/300/200" alt="AI 分析圖片中的動作" title="動作分析：彈鋼琴">
        </div>
        <p><small>※ 以上示範圖片來自 picsum 範例圖庫，實際應用中 AI 可自動標記物體、人臉及動作。</small></p>

        <hr>

        <h2>🎬 原生影片範例：AI 追蹤移動物體</h2>
        <video width="640" height="360" controls>
            <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
            您的瀏覽器不支援 video 標籤。
        </video>
        <p>這是一個使用 HTML5 <strong>&lt;video&gt;</strong> 標籤嵌入的 MP4 影片，展示類似 AI 電腦視覺追蹤移動路徑的示意畫面。</p>

        <hr>

        <h2>📺 YouTube 教學：什麼是影像辨識？</h2>
        <iframe width="800" height="450" src="https://www.youtube.com/embed/2ePf9rue1Ao" 
                title="YouTube video player" frameborder="0" 
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
                referrerpolicy="strict-origin-when-cross-origin" 
                allowfullscreen>
        </iframe>
        <p>上方嵌入了一支來自 YouTube 的解說影片，詳細介紹卷積神經網路 (CNN) 如何辨識影像中的特徵。</p>

        <hr>

        <footer>
            <p><strong>📌 網站目標：</strong> 本網站為高三電腦科專題設計，所有多媒體元素（表格、圖片、影片、iframe）均符合爬蟲實戰教材範例。</p>
            <p>&copy; 2026 數據分析師專題 - AI 影像辨識探索</p>
        </footer>
    </div>
</body>
</html>
