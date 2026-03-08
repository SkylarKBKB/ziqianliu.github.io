<!DOCTYPE html>
<html lang="zh">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Publications Example</title>
  
  <!-- Bootstrap CDN（原本的 col-sm-3 / col-sm-9 依賴它） -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  
  <style>
    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
      max-width: 1000px;
      margin: 0 auto;
      padding: 40px 20px;
      line-height: 1.5;
    }
    
    h2 {
      margin: 2px 0 -15px;
      font-size: 1.8rem;
    }
    
    /* 讓整個 publications 區塊更緊湊 */
    .publications {
      margin: 1.2em 0 2em 0;
    }
    
    .publications .bibliography {
      margin: 0.4em 0 1em 0;
      padding-left: 1.4em;
      list-style-position: outside;
    }
    
    /* 每篇 paper 的間距 — 核心調整 */
    .publications .bibliography li {
      margin-bottom: 0.55em;   /* 可改成 0.4em ~ 0.7em 來微調鬆緊 */
      padding-bottom: 0;
    }
    
    .publications .pub-row {
      margin-bottom: 0.3em;
      padding: 0.35em 0;
    }
    
    .publications .col-sm-3.abbr {
      padding-bottom: 0;
    }
    
    .publications .col-sm-9 {
      padding-top: 0.1em;
      padding-bottom: 0.2em;
    }
    
    .teaser {
      width: 120px;
      height: auto;
      margin-bottom: 0.4em;
    }
    
    .title {
      font-weight: 600;
      margin-bottom: 0.25em;
    }
    
    .title a {
      color: #0066cc;
      text-decoration: none;
    }
    
    .title a:hover {
      text-decoration: underline;
    }
    
    .author {
      margin-bottom: 0.18em;
      color: #444;
    }
    
    .periodical {
      margin-bottom: 0.35em;
      color: #555;
    }
    
    .links a.btn {
      margin-right: 0.4em;
      margin-bottom: 0.3em;
      background: #f0f0f0;
      border: none;
      color: #333;
    }
    
    .badge {
      position: absolute;
      bottom: 8px;
      right: 8px;
      font-size: 0.75em;
      background: #e74d3c;
    }
  </style>
</head>
<body>

<h2 id="publications">Other Publications</h2>

<div class="publications">
  <ol class="bibliography">

    <!-- 第一篇範例 -->
    <li>
      <div class="pub-row">
        <div class="col-sm-3 abbr" style="position: relative; padding-right: 15px; padding-left: 15px;">
          <!-- 如果有圖片就放這裡，沒有就留空 -->
          <img src="https://via.placeholder.com/120x80?text=Paper+1" class="teaser img-fluid z-depth-1" alt="teaser">
          <abbr class="badge">ICML'24</abbr>
        </div>
        <div class="col-sm-9" style="position: relative; padding-right: 15px; padding-left: 20px;">
          <div class="title"><a href="#">Towards Better Understanding of Emergent Communication</a></div>
          <div class="author">ZI QIAN, John Doe, Jane Smith</div>
          <div class="periodical"><em>International Conference on Machine Learning (ICML)</em></div>
          <div class="links">
            <a href="#" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">PDF</a>
            <a href="#" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Code</a>
            <a href="#" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Project Page</a>
          </div>
        </div>
      </div>
    </li>

    <!-- 第二篇範例 -->
    <li>
      <div class="pub-row">
        <div class="col-sm-3 abbr" style="position: relative; padding-right: 15px; padding-left: 15px;">
          <img src="https://via.placeholder.com/120x80?text=Paper+2" class="teaser img-fluid z-depth-1" alt="teaser">
          <abbr class="badge">NeurIPS'23</abbr>
        </div>
        <div class="col-sm-9" style="position: relative; padding-right: 15px; padding-left: 20px;">
          <div class="title"><a href="#">Efficient Diffusion Models via Knowledge Distillation</a></div>
          <div class="author">ZI QIAN, Alice Wang, Bob Lee et al.</div>
          <div class="periodical"><em>Conference on Neural Information Processing Systems (NeurIPS)</em></div>
          <div class="links">
            <a href="#" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">PDF</a>
            <strong><i style="color:#e74d3c">Spotlight</i></strong>
          </div>
        </div>
      </div>
    </li>

    <!-- 你可以繼續加更多 <li> ... </li> -->

  </ol>
</div>

</body>
</html>
