<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LTMPS Infinite Linked Slider System</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: Arial, "Noto Sans TC", "Microsoft JhengHei", sans-serif;
            background-color: #f3f4f6;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }

        /* 輪播外框視窗 */
        .ltmps-slider-viewport {
            position: relative;
            width: 100%;
            max-width: 1000px;
            aspect-ratio: 1000 / 395; /* 嚴格鎖定學校 Banner 的標準 1000x395 比例 */
            overflow: hidden;
            box-shadow: 0 10px 25px rgba(0,0,0,0.15);
            background-color: #ffffff;
            border-radius: 4px;
        }

        /* 橫向滾動軌道 */
        .ltmps-slider-rail {
            display: flex;
            width: 100%;
            height: 100%;
        }

        /* 單張圖片連結外框 */
        .ltmps-slide-link {
            width: 100%;
            height: 100%;
            flex-shrink: 0;
            position: relative;
            display: block;
            text-decoration: none;
        }

        .ltmps-slide-link img {
            width: 100%;
            height: 100%;
            /* 關鍵修正：改為 fill 確保整張圖片邊緣與文字 100% 完整呈現，絕不被裁切 */
            object-fit: fill; 
            display: block;
        }

        /* 底部深青色標題列 */
        .ltmps-caption-bar {
            position: absolute;
            bottom: 0;
            left: 0;
            width: 100%;
            height: 46px;
            background-color: rgba(4, 67, 67, 0.85);
            display: flex;
            align-items: center;
            justify-content: center;
            color: #ffffff;
            font-size: 14px;
            font-weight: 500;
            letter-spacing: 0.5px;
            z-index: 5;
        }

        /* 左右切換箭頭 */
        .ltmps-arrow-btn {
            position: absolute;
            top: 50%;
            transform: translateY(-50%);
            background-color: rgba(255, 255, 255, 0.55);
            border: none;
            width: 36px;
            height: 36px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            z-index: 10;
            transition: background-color 0.2s, transform 0.2s;
            color: #333333;
            font-weight: bold;
            font-size: 16px;
        }

        .ltmps-arrow-btn:hover {
            background-color: rgba(255, 255, 255, 0.9);
            transform: translateY(-50%) scale(1.05);
        }

        .arrow-left { left: 15px; }
        .arrow-right { right: 15px; }

        /* 底部導航圓點面板 */
        .ltmps-indicator-panel {
            position: absolute;
            bottom: 12px;
            left: 50%;
            transform: translateX(-50%);
            display: flex;
            gap: 10px;
            z-index: 10;
        }

        .ltmps-dot-marker {
            width: 8px;
            height: 8px;
            border-radius: 50%;
            background-color: rgba(255, 255, 255, 0.35);
            border: 1px solid rgba(0, 0, 0, 0.1);
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .ltmps-dot-marker.is-active {
            background-color: #ffffff;
        }
    </style>
</head>
<body>

    <div class="ltmps-slider-viewport" id="sliderViewport">
        
        <!-- 左右手動控制按鈕 -->
        <button class="ltmps-arrow-btn arrow-left" id="prevBtn">&#10094;</button>
        <button class="ltmps-arrow-btn arrow-right" id="nextBtn">&#10095;</button>

        <!-- 自動產生的導航圓點 -->
        <div class="ltmps-indicator-panel" id="dotsContainer"></div>

        <!-- 輪播圖片軌道區 -->
        <div class="ltmps-slider-rail" id="sliderRail">
            
            <!-- Photo 1: 「第二屆隨身書好讀」選舉 (已套用您的完整 Google Sites 網址) -->
            <a href="https://sites.google.com/view/lhcc-edu-hk2026-2027/banner-slider/%E7%AC%AC%E4%BA%8C%E5%B1%86%E9%9A%A8%E8%BA%AB%E6%9B%B8%E5%A5%BD%E8%AE%80%E9%81%B8%E8%88%89?authuser=0" class="ltmps-slide-link">
                <img src="https://i.imgur.com/W2tSLBN.png" alt="「第二屆隨身書好讀」選舉">
                <div class="ltmps-caption-bar">「第二屆隨身書好讀」選舉</div>
            </a>

            <!-- Photo 2: 三十周年校慶徵文比賽結果公佈 (已套用您的完整 Google Sites 網址) -->
            <a href="https://sites.google.com/view/lhcc-edu-hk2026-2027/banner-slider/%E4%B8%89%E5%8D%81%E5%91%A8%E5%B9%B4%E6%A0%A1%E6%85%B6%E5%BE%B5%E6%96%87%E6%AF%94%E8%B3%BD%E7%B5%90%E6%9E%9C%E5%85%AC%E5%B8%83?authuser=0" class="ltmps-slide-link">
                <img src="https://i.imgur.com/xhVjWre.png" alt="三十周年校慶徵文比賽結果公佈">
                <div class="ltmps-caption-bar">三十周年校慶徵文比賽結果公佈</div>
            </a>

    <!-- Photo 3: 三十週年校慶親子短片拍攝比賽 (已套用您的完整 Google Sites 網址) -->
            <a href="https://sites.google.com/view/lhcc-edu-hk2026-2027/banner-slider/%E4%B8%89%E5%8D%81%E9%80%B1%E5%B9%B4%E6%A0%A1%E6%85%B6%E8%A6%AA%E5%AD%90%E7%9F%AD%E7%89%87%E6%8B%8D%E6%94%9D%E6%AF%94%E8%B3%BD?authuser=0" class="ltmps-slide-link">
                <img src="https://i.imgur.com/R2BUUoV.jpeg" alt="三十週年校慶親子短片拍攝比賽">
                <div class="ltmps-caption-bar">三十週年校慶親子短片拍攝比賽</div>
            </a>

    <!-- Photo 4: 藍循30周年校慶盆菜宴 (已套用您的完整 Google Sites 網址) -->
            <a href="https://sites.google.com/view/lhcc-edu-hk2026-2027/banner-slider/%E8%97%8D%E5%BE%AA30%E5%91%A8%E5%B9%B4%E6%A0%A1%E6%85%B6%E7%9B%86%E8%8F%9C%E5%AE%B4?authuser=0" class="ltmps-slide-link">
                <img src="https://i.imgur.com/KPaf6XM.jpeg” alt="藍循30周年校慶盆菜宴">
                <div class="ltmps-caption-bar">藍循30周年校慶盆菜宴</div>
            </a>

    <!-- Photo 5: L．T．M．P．S 生命素質 (已套用您的完整 Google Sites 網址) -->
            <a href="https://sites.google.com/view/lhcc-edu-hk2026-2027/banner-slider/ltmps-%E7%94%9F%E5%91%BD%E7%B4%A0%E8%B3%AA?authuser=0" class="ltmps-slide-link">
                <img src="https://i.imgur.com/rnOuSSD.jpeg" alt=" L．T．M．P．S 生命素質">
                <div class="ltmps-caption-bar"> L．T．M．P．S 生命素質</div>
            </a>
                         
            <!-- Photo 6: 三十周年校慶親子吉祥物設計比賽(已套用您的完整 Google Sites 網址) -->
            <a href="https://sites.google.com/view/lhcc-edu-hk2026-2027/banner-slider/%E4%B8%89%E5%8D%81%E9%80%B1%E5%B9%B4%E6%A0%A1%E6%85%B6%E5%90%89%E7%A5%A5%E7%89%A9%E8%A6%AA%E5%AD%90%E8%A8%AD%E8%A8%88%E6%AF%94%E8%B3%BD?authuser=0" class="ltmps-slide-link">
                <img src="https://i.imgur.com/I4zF7gX.jpeg" alt="三十周年校慶親子吉祥物設計比賽">
                <div class="ltmps-caption-bar">三十周年校慶親子吉祥物設計比賽</div>
            </a>


   <!-- Photo 7: 激情全運在藍循 (已套用您的完整 Google Sites 網址)-->
            <a href="https://sites.google.com/view/lhcc-edu-hk2026-2027/banner-slider/%E6%BF%80%E6%83%85%E5%85%A8%E9%81%8B%E5%9C%A8%E8%97%8D%E5%BE%AA?authuser=0" class="ltmps-slide-link">
                <img src="https://i.imgur.com/YvSOfV9.jpeg" alt="激情全運在藍循">
                <div class="ltmps-caption-bar">激情全運在藍循</div>
            </a>

    </div>

    <script>
        const rail = document.getElementById('sliderRail');
        const originalSlides = document.querySelectorAll('.ltmps-slide-link');
        const prevBtn = document.getElementById('prevBtn');
        const nextBtn = document.getElementById('nextBtn');
        const dotsContainer = document.getElementById('dotsContainer');

        let currentIndex = 0;
        const totalOriginalSlides = originalSlides.length;
        let slideInterval;
        const slideDuration = 5000; // 每張照片停留剛好 5 秒

        // 1. 建立無縫循環首尾複製節點
        const firstSlideClone = originalSlides[0].cloneNode(true);
        rail.appendChild(firstSlideClone);

        // 2. 動態畫出對應數量的導航點
        for (let i = 0; i < totalOriginalSlides; i++) {
            const dot = document.createElement('div');
            dot.classList.add('ltmps-dot-marker');
            if (i === 0) dot.classList.add('is-active');
            dot.addEventListener('click', () => jumpToSlide(i));
            dotsContainer.appendChild(dot);
        }
        const dots = document.querySelectorAll('.ltmps-dot-marker');

        // 3. 移動動畫引擎
        function updateSliderPosition(withTransition = true) {
            if (withTransition) {
                rail.style.transition = 'transform 0.6s cubic-bezier(0.25, 1, 0.5, 1)';
            } else {
                rail.style.transition = 'none';
            }
            rail.style.transform = `translateX(-${currentIndex * 100}%)`;
            updateDots();
        }

        function updateDots() {
            dots.forEach((dot, index) => {
                const visualIndex = currentIndex === totalOriginalSlides ? 0 : currentIndex;
                if (index === visualIndex) {
                    dot.classList.add('is-active');
                } else {
                    dot.classList.remove('is-active');
                }
            });
        }

        function nextSlide() {
            currentIndex++;
            updateSliderPosition(true);

            // 當滑動到最後一張的複製複本時，在動畫結束後「無感閃返」到真正的第一張
            if (currentIndex === totalOriginalSlides) {
                setTimeout(() => {
                    currentIndex = 0;
                    updateSliderPosition(false); 
                }, 600); // 這裡對齊 0.6 秒的過渡動畫時間
            }
        }

        function prevSlide() {
            if (currentIndex === 0) {
                currentIndex = totalOriginalSlides;
                updateSliderPosition(false);
                setTimeout(() => {
                    currentIndex = totalOriginalSlides - 1;
                    updateSliderPosition(true);
                }, 20);
            } else {
                currentIndex--;
                updateSliderPosition(true);
            }
        }

        function jumpToSlide(index) {
            currentIndex = index;
            updateSliderPosition(true);
            resetAutoplay();
        }

        // 4. 定時器核心控制
        function startAutoplay() {
            slideInterval = setInterval(nextSlide, slideDuration);
        }

        function resetAutoplay() {
            clearInterval(slideInterval);
            startAutoplay();
        }

        // 監聽點擊事件
        nextBtn.addEventListener('click', () => { nextSlide(); resetAutoplay(); });
        prevBtn.addEventListener('click', () => { prevSlide(); resetAutoplay(); });

        // 啟動自動輪播
        startAutoplay();
    </script>
</body>
</html>
