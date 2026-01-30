# 📜 Software Copyrights

<style>
.awards-container {
    max-width: 1400px;
    margin: 30px auto;
}
.section-title {
    font-size: 24px;
    font-weight: bold;
    color: #333;
    margin: 30px 0 20px 0;
    padding-bottom: 10px;
    border-bottom: 3px solid #667eea;
}

.awards-grid {
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    gap: 20px;
    padding: 20px 0;
}

.award-card {
    background: white;
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    transition: all 0.3s ease;
    cursor: pointer;
}

.award-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 16px rgba(0,0,0,0.2);
}

.award-image-container {
    width: 100%;
    height: 200px;
    overflow: hidden;
    position: relative;
}

.award-image {
    width: 100%;
    height: 100%;
    object-fit: cover;
    display: block;
    transition: transform 0.3s ease;
}

.award-card:hover .award-image {
    transform: scale(1.15);
}

.award-info {
    padding: 12px;
}

.award-title {
    font-size: 13px;
    line-height: 1.5;
    color: #333;
    margin-bottom: 6px;
    min-height: 40px;
}

.award-date {
    font-size: 11px;
    color: #888;
    font-weight: 500;
}

/* 灯箱样式 */
.lightbox {
    display: none;
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.9);
    z-index: 9999;
    justify-content: center;
    align-items: center;
    animation: fadeIn 0.3s ease;
}

.lightbox.active {
    display: flex;
}

@keyframes fadeIn {
    from {
        opacity: 0;
    }
    to {
        opacity: 1;
    }
}

.lightbox-content {
    position: relative;
    max-width: 90%;
    max-height: 90%;
    animation: zoomIn 0.3s ease;
}

@keyframes zoomIn {
    from {
        transform: scale(0.8);
        opacity: 0;
    }
    to {
        transform: scale(1);
        opacity: 1;
    }
}

.lightbox-image {
    max-width: 100%;
    max-height: 90vh;
    object-fit: contain;
    border-radius: 8px;
    box-shadow: 0 0 50px rgba(255, 255, 255, 0.1);
}

.lightbox-close {
    position: absolute;
    top: -40px;
    right: 0;
    color: white;
    font-size: 36px;
    font-weight: bold;
    cursor: pointer;
    background: none;
    border: none;
    padding: 0;
    width: 40px;
    height: 40px;
    line-height: 40px;
    text-align: center;
    transition: transform 0.2s ease;
}

.lightbox-close:hover {
    transform: scale(1.2);
}

.lightbox-nav {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    color: white;
    font-size: 48px;
    font-weight: bold;
    cursor: pointer;
    background: rgba(255, 255, 255, 0.1);
    border: none;
    padding: 20px;
    width: 60px;
    height: 60px;
    line-height: 20px;
    text-align: center;
    border-radius: 50%;
    transition: all 0.3s ease;
    user-select: none;
}

.lightbox-nav:hover {
    background: rgba(255, 255, 255, 0.2);
    transform: translateY(-50%) scale(1.1);
}

.lightbox-prev {
    left: 20px;
}

.lightbox-next {
    right: 20px;
}

.lightbox-caption {
    position: absolute;
    bottom: -60px;
    left: 0;
    right: 0;
    color: white;
    text-align: center;
    font-size: 16px;
    padding: 10px;
}

@media (max-width: 1200px) {
    .awards-grid {
        grid-template-columns: repeat(4, 1fr);
        gap: 15px;
    }
}

@media (max-width: 900px) {
    .awards-grid {
        grid-template-columns: repeat(3, 1fr);
        gap: 15px;
    }
}

@media (max-width: 600px) {
    .awards-grid {
        grid-template-columns: repeat(2, 1fr);
        gap: 12px;
    }
    
    .award-image-container {
        height: 150px;
    }
    
    .lightbox-nav {
        font-size: 32px;
        padding: 10px;
        width: 45px;
        height: 45px;
    }
    
    .lightbox-prev {
        left: 10px;
    }
    
    .lightbox-next {
        right: 10px;
    }
}
</style>

<div class="awards-container">

<div class="awards-grid">

<div class="award-card" onclick="openLightbox('images/Copyright/Copyright.jpg', '狼口博弈', '2025年')">
    <div class="award-image-container">
        <img class="award-image" src="images/Copyright/Copyright.png" alt="软著1">
    </div>
    <div class="award-info">
        <div class="award-title">狼口博弈</div>
        <div class="award-date">2025年</div>
    </div>
</div>
</div>

</div>

# 🥇 Honors

<div class="awards-container">

<div class="section-title" style="font-size: 16px;">
  🏆 National Level Awards (8)
</div>


<div class="awards-grid">

<div class="award-card" onclick="openLightbox('images/Award/Guo_1.png', '国家级奖项', '2025年')">
    <div class="award-image-container">
        <img class="award-image" src="images/Award/Guo_1.png" alt="国奖1">
    </div>
    <div class="award-info">
        <div class="award-title">国家级奖项</div>
        <div class="award-date">2025年</div>
    </div>
</div>

<div class="award-card" onclick="openLightbox('images/Award/Guo_2.png', '国家级奖项', '2025年')">
    <div class="award-image-container">
        <img class="award-image" src="images/Award/Guo_2.png" alt="国奖2">
    </div>
    <div class="award-info">
        <div class="award-title">国家级奖项</div>
        <div class="award-date">2025年</div>
    </div>
</div>

<div class="award-card" onclick="openLightbox('images/Award/Guo_3.png', '国家级奖项', '2025年')">
    <div class="award-image-container">
        <img class="award-image" src="images/Award/Guo_3.png" alt="国奖3">
    </div>
    <div class="award-info">
        <div class="award-title">国家级奖项</div>
        <div class="award-date">2025年</div>
    </div>
</div>

<div class="award-card" onclick="openLightbox('images/Award/Guo_4.png', '国家级奖项', '2025年')">
    <div class="award-image-container">
        <img class="award-image" src="images/Award/Guo_4.png" alt="国奖4">
    </div>
    <div class="award-info">
        <div class="award-title">国家级奖项</div>
        <div class="award-date">2025年</div>
    </div>
</div>

<div class="award-card" onclick="openLightbox('images/Award/Guo_5.png', '国家级奖项', '2025年')">
    <div class="award-image-container">
        <img class="award-image" src="images/Award/Guo_5.png" alt="国奖5">
    </div>
    <div class="award-info">
        <div class="award-title">国家级奖项</div>
        <div class="award-date">2025年</div>
    </div>
</div>

<div class="award-card" onclick="openLightbox('images/Award/Guo_6.png', '国家级奖项', '2025年')">
    <div class="award-image-container">
        <img class="award-image" src="images/Award/Guo_6.png" alt="国奖6">
    </div>
    <div class="award-info">
        <div class="award-title">国家级奖项</div>
        <div class="award-date">2025年</div>
    </div>
</div>

<div class="award-card" onclick="openLightbox('images/Award/Guo_7.jpg', '国家级奖项', '2025年')">
    <div class="award-image-container">
        <img class="award-image" src="images/Award/Guo_7.jpg" alt="国奖7">
    </div>
    <div class="award-info">
        <div class="award-title">国家级奖项</div>
        <div class="award-date">2025年</div>
    </div>
</div>

<div class="award-card" onclick="openLightbox('images/Award/Guo_8.jpg', '国家级奖项', '2024年')">
    <div class="award-image-container">
        <img class="award-image" src="images/Award/Guo_8.jpg" alt="国奖8">
    </div>
    <div class="award-info">
        <div class="award-title">国家级奖项</div>
        <div class="award-date">2024年</div>
    </div>
</div>

</div>

<div class="section-title" style="font-size: 16px;">
  🎖️ Provincial Level Awards (15)
</div>

<div class="awards-grid">

<div class="award-card" onclick="openLightbox('images/Award/Sheng_1.png', '省部级奖项', '2025年')">
    <div class="award-image-container">
        <img class="award-image" src="images/Award/Sheng_1.png" alt="省奖1">
    </div>
    <div class="award-info">
        <div class="award-title">省部级奖项</div>
        <div class="award-date">2025年</div>
    </div>
</div>

<div class="award-card" onclick="openLightbox('images/Award/Sheng_2.png', '省部级奖项', '2025年')">
    <div class="award-image-container">
        <img class="award-image" src="images/Award/Sheng_2.png" alt="省奖2">
    </div>
    <div class="award-info">
        <div class="award-title">省部级奖项</div>
        <div class="award-date">2025年</div>
    </div>
</div>

<div class="award-card" onclick="openLightbox('images/Award/Sheng_3.png', '省部级奖项', '2025年')">
    <div class="award-image-container">
        <img class="award-image" src="images/Award/Sheng_3.png" alt="省奖3">
    </div>
    <div class="award-info">
        <div class="award-title">省部级奖项</div>
        <div class="award-date">2025年</div>
    </div>
</div>

<div class="award-card" onclick="openLightbox('images/Award/Sheng_4.png', '省部级奖项', '2025年')">
    <div class="award-image-container">
        <img class="award-image" src="images/Award/Sheng_4.png" alt="省奖4">
    </div>
    <div class="award-info">
        <div class="award-title">省部级奖项</div>
        <div class="award-date">2025年</div>
    </div>
</div>

<div class="award-card" onclick="openLightbox('images/Award/Sheng_5.png', '省部级奖项', '2025年')">
    <div class="award-image-container">
        <img class="award-image" src="images/Award/Sheng_5.png" alt="省奖5">
    </div>
    <div class="award-info">
        <div class="award-title">省部级奖项</div>
        <div class="award-date">2025年</div>
    </div>
</div>

<div class="award-card" onclick="openLightbox('images/Award/Sheng_6.png', '省部级奖项', '2024年')">
    <div class="award-image-container">
        <img class="award-image" src="images/Award/Sheng_6.png" alt="省奖6">
    </div>
    <div class="award-info">
        <div class="award-title">省部级奖项</div>
        <div class="award-date">2024年</div>
    </div>
</div>

<div class="award-card" onclick="openLightbox('images/Award/Sheng_7.png', '省部级奖项', '2025年')">
    <div class="award-image-container">
        <img class="award-image" src="images/Award/Sheng_7.png" alt="省奖7">
    </div>
    <div class="award-info">
        <div class="award-title">省部级奖项</div>
        <div class="award-date">2025年</div>
    </div>
</div>

<div class="award-card" onclick="openLightbox('images/Award/Sheng_8.png', '省部级奖项', '2025年')">
    <div class="award-image-container">
        <img class="award-image" src="images/Award/Sheng_8.png" alt="省奖8">
    </div>
    <div class="award-info">
        <div class="award-title">省部级奖项</div>
        <div class="award-date">2025年</div>
    </div>
</div>

<div class="award-card" onclick="openLightbox('images/Award/Sheng_9.jpg', '省部级奖项', '2025年')">
    <div class="award-image-container">
        <img class="award-image" src="images/Award/Sheng_9.jpg" alt="省奖9">
    </div>
    <div class="award-info">
        <div class="award-title">省部级奖项</div>
        <div class="award-date">2025年</div>
    </div>
</div>

<div class="award-card" onclick="openLightbox('images/Award/Sheng_10.png', '省部级奖项', '2025年')">
    <div class="award-image-container">
        <img class="award-image" src="images/Award/Sheng_10.png" alt="省奖10">
    </div>
    <div class="award-info">
        <div class="award-title">省部级奖项</div>
        <div class="award-date">2025年</div>
    </div>
</div>

<div class="award-card" onclick="openLightbox('images/Award/Sheng_11.png', '省部级奖项', '2025年')">
    <div class="award-image-container">
        <img class="award-image" src="images/Award/Sheng_11.png" alt="省奖11">
    </div>
    <div class="award-info">
        <div class="award-title">省部级奖项</div>
        <div class="award-date">2025年</div>
    </div>
</div>

<div class="award-card" onclick="openLightbox('images/Award/Sheng_12.jpg', '省部级奖项', '2025年')">
    <div class="award-image-container">
        <img class="award-image" src="images/Award/Sheng_12.jpg" alt="省奖12">
    </div>
    <div class="award-info">
        <div class="award-title">省部级奖项</div>
        <div class="award-date">2025年</div>
    </div>
</div>

<div class="award-card" onclick="openLightbox('images/Award/Sheng_13.jpg', '省部级奖项', '2025年')">
    <div class="award-image-container">
        <img class="award-image" src="images/Award/Sheng_13.jpg" alt="省奖13">
    </div>
    <div class="award-info">
        <div class="award-title">省部级奖项</div>
        <div class="award-date">2025年</div>
    </div>
</div>

<div class="award-card" onclick="openLightbox('images/Award/Sheng_14.jpg', '省部级奖项', '2025年')">
    <div class="award-image-container">
        <img class="award-image" src="images/Award/Sheng_14.jpg" alt="省奖14">
    </div>
    <div class="award-info">
        <div class="award-title">省部级奖项</div>
        <div class="award-date">2025年</div>
    </div>
</div>

<div class="award-card" onclick="openLightbox('images/Award/Sheng_15.jpg', '省部级奖项', '2025年')">
    <div class="award-image-container">
        <img class="award-image" src="images/Award/Sheng_15.jpg" alt="省奖15">
    </div>
    <div class="award-info">
        <div class="award-title">省部级奖项</div>
        <div class="award-date">2025年</div>
    </div>
</div>

</div>

</div>

<!-- 灯箱 -->
<div id="lightbox" class="lightbox" onclick="closeLightbox(event)">
    <div class="lightbox-content">
        <button class="lightbox-close" onclick="closeLightbox(event)">&times;</button>
        <button class="lightbox-nav lightbox-prev" onclick="navigateImage(event, -1)">‹</button>
        <img id="lightbox-image" class="lightbox-image" src="" alt="">
        <button class="lightbox-nav lightbox-next" onclick="navigateImage(event, 1)">›</button>
        <div class="lightbox-caption" id="lightbox-caption"></div>
    </div>
</div>

<script>
let currentImageIndex = 0;
let allImages = [];

// 收集所有图片信息
function collectAllImages() {
    allImages = [];
    const cards = document.querySelectorAll('.award-card');
    cards.forEach(card => {
        const img = card.querySelector('.award-image');
        const title = card.querySelector('.award-title').textContent;
        const date = card.querySelector('.award-date').textContent;
        allImages.push({
            src: img.src,
            title: title,
            date: date
        });
    });
}

// 打开灯箱
function openLightbox(imageSrc, title, date) {
    collectAllImages();
    currentImageIndex = allImages.findIndex(img => img.src.includes(imageSrc));
    
    const lightbox = document.getElementById('lightbox');
    const lightboxImage = document.getElementById('lightbox-image');
    const lightboxCaption = document.getElementById('lightbox-caption');
    
    lightboxImage.src = imageSrc;
    lightboxCaption.textContent = `${title} - ${date}`;
    lightbox.classList.add('active');
    
    // 防止背景滚动
    document.body.style.overflow = 'hidden';
}

// 关闭灯箱
function closeLightbox(event) {
    if (event.target.id === 'lightbox' || event.target.classList.contains('lightbox-close')) {
        const lightbox = document.getElementById('lightbox');
        lightbox.classList.remove('active');
        document.body.style.overflow = 'auto';
    }
}

// 导航到上一张/下一张图片
function navigateImage(event, direction) {
    event.stopPropagation();
    currentImageIndex += direction;
    
    if (currentImageIndex < 0) {
        currentImageIndex = allImages.length - 1;
    } else if (currentImageIndex >= allImages.length) {
        currentImageIndex = 0;
    }
    
    const currentImage = allImages[currentImageIndex];
    const lightboxImage = document.getElementById('lightbox-image');
    const lightboxCaption = document.getElementById('lightbox-caption');
    
    lightboxImage.src = currentImage.src;
    lightboxCaption.textContent = `${currentImage.title} - ${currentImage.date}`;
}

// 键盘导航
document.addEventListener('keydown', function(event) {
    const lightbox = document.getElementById('lightbox');
    if (lightbox.classList.contains('active')) {
        if (event.key === 'Escape') {
            lightbox.classList.remove('active');
            document.body.style.overflow = 'auto';
        } else if (event.key === 'ArrowLeft') {
            navigateImage(event, -1);
        } else if (event.key === 'ArrowRight') {
            navigateImage(event, 1);
        }
    }
});
</script>
