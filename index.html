<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>صفحه شخصی - آفلاین</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background: #000;
            color: #fff;
            overflow-x: hidden;
            min-height: 100vh;
            position: relative;
        }

        #matrix {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
            opacity: 0.15;
            pointer-events: none;
        }

        .container {
            max-width: 400px;
            margin: 0 auto;
            padding: 20px;
            text-align: center;
            position: relative;
            z-index: 1;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
        }

        .profile-section {
            margin-bottom: 40px;
            position: relative;
        }

        .profile-image {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            margin: 0 auto 20px;
            position: relative;
            border: 3px solid rgba(255, 255, 255, 0.3);
            transition: all 0.3s ease;
            overflow: hidden;
            cursor: pointer;
        }

        .profile-image:hover {
            border-color: rgba(255, 255, 255, 0.6);
            transform: scale(1.05);
        }

        .profile-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            border-radius: 50%;
        }

        .edit-icon {
            position: absolute;
            bottom: 5px;
            right: 5px;
            background: rgba(255, 255, 255, 0.9);
            color: #000;
            border-radius: 50%;
            width: 30px;
            height: 30px;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: all 0.3s ease;
        }

        .edit-icon:hover {
            background: #fff;
            transform: scale(1.1);
        }

        #imageInput {
            display: none;
        }

        .profile-name {
            font-size: 24px;
            font-weight: bold;
            margin-bottom: 10px;
            direction: ltr;
            text-align: center;
            unicode-bidi: plaintext;
        }

        .profile-desc {
            font-size: 14px;
            color: rgba(255, 255, 255, 0.7);
            margin-bottom: 20px;
            direction: ltr;
            text-align: center;
            unicode-bidi: plaintext;
        }

        .menu-items {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        .menu-item {
            background: rgba(255, 255, 255, 0.1);
            border: 1px solid rgba(255, 255, 255, 0.2);
            border-radius: 15px;
            padding: 20px;
            cursor: pointer;
            transition: all 0.3s ease;
            backdrop-filter: blur(10px);
            position: relative;
            overflow: hidden;
        }

        .menu-item:hover {
            background: rgba(255, 255, 255, 0.2);
            border-color: rgba(255, 255, 255, 0.4);
            transform: translateY(-2px);
        }

        .menu-item h3 {
            font-size: 18px;
            font-weight: bold;
            direction: ltr;
            text-align: center;
            unicode-bidi: plaintext;
        }

        /* Modal Styles */
        .modal {
            display: none;
            position: fixed;
            z-index: 1000;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.9);
        }

        .modal-content {
            background: rgba(0, 0, 0, 0.95);
            border: 1px solid rgba(255, 255, 255, 0.2);
            border-radius: 20px;
            margin: 5% auto;
            padding: 30px;
            width: 90%;
            max-width: 600px;
            max-height: 80vh;
            overflow-y: auto;
            position: relative;
        }

        .close {
            color: rgba(255, 255, 255, 0.7);
            float: right;
            font-size: 28px;
            font-weight: bold;
            cursor: pointer;
            transition: color 0.3s ease;
        }

        .close:hover {
            color: #fff;
        }

        .modal h2 {
            margin-bottom: 20px;
            color: #fff;
            text-align: center;
            direction: ltr;
            unicode-bidi: plaintext;
        }

        .modal-body {
            color: rgba(255, 255, 255, 0.9);
            line-height: 1.6;
            direction: ltr;
            text-align: left;
            unicode-bidi: plaintext;
        }

        .modal-body p:lang(fa),
        .modal-body div:lang(fa) {
            direction: rtl;
            text-align: right;
        }

        .editable-title {
            outline: none;
            border: none;
            background: transparent;
            cursor: default;
            transition: all 0.3s ease;
        }

        .editable-title.edit-mode {
            cursor: text;
        }

        .editable-title.edit-mode:hover {
            background: rgba(255, 255, 255, 0.1);
            border-radius: 5px;
            padding: 2px 5px;
        }

        .editable-title.edit-mode:focus {
            background: rgba(255, 255, 255, 0.2);
            border-radius: 5px;
            padding: 2px 5px;
        }

        .admin-panel {
            position: fixed;
            top: 20px;
            left: 20px;
            background: rgba(0, 0, 0, 0.8);
            border: 1px solid rgba(255, 255, 255, 0.3);
            border-radius: 10px;
            padding: 15px;
            z-index: 999;
            display: none;
        }

        .admin-btn {
            background: rgba(255, 255, 255, 0.2);
            border: 1px solid rgba(255, 255, 255, 0.3);
            color: #fff;
            padding: 8px 15px;
            border-radius: 5px;
            cursor: pointer;
            margin: 5px;
            transition: all 0.3s ease;
            font-size: 12px;
        }

        .admin-btn:hover {
            background: rgba(255, 255, 255, 0.3);
        }

        .password-modal {
            display: none;
            position: fixed;
            z-index: 2000;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.9);
        }

        .password-content {
            background: rgba(0, 0, 0, 0.95);
            border: 1px solid rgba(255, 255, 255, 0.2);
            border-radius: 20px;
            margin: 20% auto;
            padding: 30px;
            width: 90%;
            max-width: 400px;
            text-align: center;
        }

        .password-input {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid rgba(255, 255, 255, 0.3);
            border-radius: 5px;
            background: rgba(255, 255, 255, 0.1);
            color: #fff;
            font-size: 16px;
            text-align: center;
        }

        .password-input::placeholder {
            color: rgba(255, 255, 255, 0.5);
        }

        .edit-indicator {
            position: fixed;
            top: 10px;
            right: 10px;
            background: rgba(0, 255, 0, 0.3);
            color: #fff;
            padding: 5px 10px;
            border-radius: 15px;
            font-size: 12px;
            display: none;
            z-index: 1000;
        }

        .save-status {
            position: fixed;
            top: 10px;
            left: 50%;
            transform: translateX(-50%);
            padding: 8px 16px;
            border-radius: 20px;
            font-size: 12px;
            z-index: 1001;
            display: none;
            transition: all 0.3s ease;
        }

        .save-status.saving {
            background: rgba(255, 165, 0, 0.8);
            color: #fff;
            display: block;
        }

        .save-status.saved {
            background: rgba(0, 255, 0, 0.8);
            color: #fff;
            display: block;
        }

        .save-status.error {
            background: rgba(255, 0, 0, 0.8);
            color: #fff;
            display: block;
        }

        /* Audio Player Styles */
        .audio-upload-area {
            border: 2px dashed rgba(255, 255, 255, 0.3);
            border-radius: 10px;
            padding: 20px;
            margin: 20px 0;
            text-align: center;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .audio-upload-area:hover {
            border-color: rgba(255, 255, 255, 0.5);
            background: rgba(255, 255, 255, 0.05);
        }

        .audio-upload-area.dragover {
            border-color: #fff;
            background: rgba(255, 255, 255, 0.1);
        }

        .playlist-container {
            max-height: 400px;
            overflow-y: auto;
            margin: 20px 0;
        }

        .audio-item {
            background: rgba(255, 255, 255, 0.1);
            border-radius: 10px;
            padding: 15px;
            margin: 10px 0;
            display: flex;
            align-items: center;
            justify-content: space-between;
            flex-wrap: wrap;
            gap: 10px;
        }

        .audio-info {
            flex: 1;
            min-width: 200px;
        }

        .audio-title {
            font-weight: bold;
            margin-bottom: 5px;
            direction: ltr;
            text-align: left;
            unicode-bidi: plaintext;
        }

        .audio-controls {
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .play-btn {
            background: rgba(255, 255, 255, 0.2);
            border: none;
            border-radius: 50%;
            width: 40px;
            height: 40px;
            color: #fff;
            cursor: pointer;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: all 0.3s ease;
        }

        .play-btn:hover {
            background: rgba(255, 255, 255, 0.3);
            transform: scale(1.1);
        }

        .delete-btn {
            background: rgba(255, 0, 0, 0.3);
            border: none;
            border-radius: 5px;
            color: #fff;
            padding: 5px 10px;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .delete-btn:hover {
            background: rgba(255, 0, 0, 0.5);
        }

        .audio-progress {
            width: 100%;
            height: 4px;
            background: rgba(255, 255, 255, 0.2);
            border-radius: 2px;
            margin: 5px 0;
            overflow: hidden;
        }

        .audio-progress-bar {
            height: 100%;
            background: #fff;
            width: 0%;
            transition: width 0.1s ease;
        }

        #audioInput {
            display: none;
        }
        
        @media (max-width: 480px) {
            .container {
                padding: 15px;
            }
            
            .profile-image {
                width: 100px;
                height: 100px;
            }
            
            .profile-name {
                font-size: 20px;
            }
            
            .menu-item {
                padding: 15px;
            }
            
            .modal-content {
                margin: 10% auto;
                padding: 20px;
                width: 95%;
            }
        }

        /* Link Styles */
        .modal-body a {
            color: #4fc3f7;
            text-decoration: underline;
            cursor: pointer;
            transition: color 0.3s ease;
        }

        .modal-body a:hover {
            color: #81d4fa;
        }

        /* Offline Status */
        .offline-status {
            position: fixed;
            bottom: 10px;
            right: 10px;
            background: rgba(0, 100, 0, 0.8);
            color: #fff;
            padding: 5px 10px;
            border-radius: 10px;
            font-size: 10px;
            z-index: 1000;
        }

        /* Import/Export File Input */
        .file-input {
            display: none;
        }
    </style>
</head>
<body>
    <div class="save-status" id="saveStatus">در حال ذخیره...</div>
    <div class="offline-status">🔒 نسخه آفلاین - بدون نیاز به اینترنت</div>
    <canvas id="matrix"></canvas>
    
    <!-- Admin Panel -->
    <div class="admin-panel" id="adminPanel">
        <button class="admin-btn" onclick="toggleEditMode()">حالت ویرایش</button>
        <button class="admin-btn" onclick="logout()">خروج</button>
        <button class="admin-btn" onclick="exportData()">خروجی داده‌ها</button>
        <button class="admin-btn" onclick="importData()">ورودی داده‌ها</button>
    </div>
    
    <!-- Edit Mode Indicator -->
    <div class="edit-indicator" id="editIndicator">حالت ویرایش فعال</div>
    
    <!-- Password Modal -->
    <div id="passwordModal" class="password-modal">
        <div class="password-content">
            <h2>ورود به پنل مدیریت</h2>
            <input type="password" id="passwordInput" class="password-input" placeholder="رمز عبور را وارد کنید">
            <br><br>
            <button class="admin-btn" onclick="checkPassword()">ورود</button>
            <button class="admin-btn" onclick="closePasswordModal()">انصراف</button>
        </div>
    </div>

    <!-- Hidden file inputs -->
    <input type="file" id="importInput" class="file-input" accept=".json">
    <input type="file" id="imageInput" class="file-input" accept="image/*">
    <input type="file" id="audioInput" class="file-input" accept="audio/*" multiple>
    
    <div class="container">
        <div class="profile-section">
            <div class="profile-image" id="profileImageContainer">
                <img id="profileImg" src="data:image/svg+xml,%3Csvg width='120' height='120' viewBox='0 0 120 120' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Crect width='120' height='120' fill='%23333'/%3E%3Ccircle cx='60' cy='40' r='15' fill='%23666'/%3E%3Cpath d='m35 80c0-15 10-25 25-25s25 10 25 25' fill='%23666'/%3E%3C/svg%3E" alt="Profile">
                <div class="edit-icon" id="editIcon" style="display: none;">✏️</div>
            </div>
            
            <div class="profile-name" id="profileName">Aeon</div>
            <div class="profile-desc" id="profileDesc">逐梦未来—智慧为刃˚.ᐟ.</div>
        </div>

        <div class="menu-items">
            <div class="menu-item" onclick="openModal('biography')">
                <h3 class="editable-title" data-type="biography">ABOUT ME</h3>
            </div>
            
            <div class="menu-item" onclick="openModal('tenrules')">
                <h3 class="editable-title" data-type="tenrules">Longevity Institutions</h3>
            </div>
            
            <div class="menu-item" onclick="openModal('playlist')">
                <h3 class="editable-title" data-type="playlist">PLAYLIST</h3>
            </div>
        </div>
    </div>

    <!-- Modal -->
    <div id="modal" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal()">&times;</span>
            <h2 id="modalTitle"></h2>
            <div class="modal-body" id="modalBody" contenteditable="false">
                <!-- محتوا اینجا نمایش داده می‌شود -->
            </div>
        </div>
    </div>

    <script>
        // App Configuration
        const STORAGE_KEY = 'personal_website_offline';
        const ADMIN_PASSWORD = "aeon2025";
        let isEditMode = false;
        
        // Default content data
        let contentData = {
            profileName: "Aeon",
            profileDesc: "逐梦未来—智慧为刃˚.ᐟ.",
            profileImage: "",
            contentData: {
                biography: {
                    title: "ABOUT ME",
                    content: "اینجا بیوگرافی خود را بنویسید..."
                },
                tenrules: {
                    title: "Longevity Institutions",
                    content: "اینجا محتوای خود را بنویسید..."
                },
                playlist: {
                    title: "PLAYLIST",
                    content: "آهنگ های خود را آپلود کنید...",
                    audioFiles: []
                }
            }
        };

        // Utility Functions
        function showSaveStatus(status, message) {
            const saveStatus = document.getElementById('saveStatus');
            saveStatus.className = `save-status ${status}`;
            saveStatus.textContent = message;
            saveStatus.style.display = 'block';
            
            if (status === 'saved') {
                setTimeout(() => saveStatus.style.display = 'none', 2000);
            } else if (status === 'error') {
                setTimeout(() => saveStatus.style.display = 'none', 3000);
            }
        }

        // Storage Functions
        function saveToStorage() {
            try {
                showSaveStatus('saving', 'در حال ذخیره...');
                localStorage.setItem(STORAGE_KEY, JSON.stringify(contentData));
                showSaveStatus('saved', 'ذخیره شد ✓');
            } catch (error) {
                console.error('Storage error:', error);
                showSaveStatus('error', 'خطا در ذخیره!');
                if (error.name === 'QuotaExceededError') {
                    alert('فضای ذخیره‌سازی پر شده است!');
                }
            }
        }

        function loadFromStorage() {
            try {
                const savedData = localStorage.getItem(STORAGE_KEY);
                if (savedData) {
                    const parsedData = JSON.parse(savedData);
                    contentData = {
                        ...contentData,
                        ...parsedData,
                        contentData: {
                            ...contentData.contentData,
                            ...parsedData.contentData
                        }
                    };
                }
                updateUI();
            } catch (error) {
                console.error('Load error:', error);
                updateUI();
            }
        }

        function updateUI() {
            document.getElementById('profileName').textContent = contentData.profileName;
            document.getElementById('profileDesc').textContent = contentData.profileDesc;
            
            if (contentData.profileImage) {
                document.getElementById('profileImg').src = contentData.profileImage;
            }
            
            document.querySelectorAll('.editable-title').forEach(title => {
                const type = title.dataset.type;
                if (contentData.contentData[type]?.title) {
                    title.textContent = contentData.contentData[type].title;
                }
            });
        }

        // Matrix Animation - Simplified
        function initMatrix() {
            const canvas = document.getElementById('matrix');
            const ctx = canvas.getContext('2d');
            
            canvas.width = window.innerWidth;
            canvas.height = window.innerHeight;

            const chars = "ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789@#$%^&*()";
            const fontSize = 10;
            const columns = Math.floor(canvas.width / fontSize);
            const drops = new Array(columns).fill(1);

            function draw() {
                ctx.fillStyle = 'rgba(0, 0, 0, 0.04)';
                ctx.fillRect(0, 0, canvas.width, canvas.height);
                
                ctx.fillStyle = '#fff';
                ctx.font = `${fontSize}px monospace`;
                
                drops.forEach((drop, i) => {
                    const char = chars[Math.floor(Math.random() * chars.length)];
                    ctx.fillText(char, i * fontSize, drop * fontSize);
                    
                    if (drop * fontSize > canvas.height && Math.random() > 0.975) {
                        drops[i] = 0;
                    }
                    drops[i]++;
                });
                
                requestAnimationFrame(draw);
            }
            
            draw();
        }

        // Admin Functions
        let clickCount = 0;
        document.getElementById('profileImageContainer').addEventListener('click', function() {
            if (!isEditMode) {
                clickCount++;
                setTimeout(() => {
                    if (clickCount === 2) {
                        showPasswordModal();
                    }
                    clickCount = 0;
                }, 400);
            } else {
                document.getElementById('imageInput').click();
            }
        });

        function showPasswordModal() {
            document.getElementById('passwordModal').style.display = 'block';
            document.getElementById('passwordInput').focus();
        }

        function closePasswordModal() {
            document.getElementById('passwordModal').style.display = 'none';
            document.getElementById('passwordInput').value = '';
        }

        function checkPassword() {
            const password = document.getElementById('passwordInput').value;
            if (password === ADMIN_PASSWORD) {
                isEditMode = true;
                enableEditMode();
                closePasswordModal();
                document.getElementById('adminPanel').style.display = 'block';
                document.getElementById('editIndicator').style.display = 'block';
            } else {
                alert('رمز عبور نادرست است!');
                document.getElementById('passwordInput').value = '';
            }
        }

        function enableEditMode() {
            document.getElementById('profileName').contentEditable = true;
            document.getElementById('profileDesc').contentEditable = true;
            document.getElementById('editIcon').style.display = 'flex';
            
            document.querySelectorAll('.editable-title').forEach(title => {
                title.contentEditable = true;
                title.classList.add('edit-mode');
            });
        }

        function disableEditMode() {
            document.getElementById('profileName').contentEditable = false;
            document.getElementById('profileDesc').contentEditable = false;
            document.getElementById('editIcon').style.display = 'none';
            
            document.querySelectorAll('.editable-title').forEach(title => {
                title.contentEditable = false;
                title.classList.remove('edit-mode');
            });
        }

        function toggleEditMode() {
            isEditMode = !isEditMode;
            if (isEditMode) {
                enableEditMode();
                document.getElementById('editIndicator').style.display = 'block';
            } else {
                disableEditMode();
                document.getElementById('editIndicator').style.display = 'none';
            }
        }

        function logout() {
            isEditMode = false;
            disableEditMode();
            document.getElementById('adminPanel').style.display = 'none';
            document.getElementById('editIndicator').style.display = 'none';
        }

        // Export/Import Functions
        function exportData() {
            try {
                const dataStr = JSON.stringify(contentData, null, 2);
                const dataBlob = new Blob([dataStr], {type: 'application/json'});
                const url = URL.createObjectURL(dataBlob);
                const link = document.createElement('a');
                link.href = url;
                link.download = `website_backup_${new Date().toISOString().split('T')[0]}.json`;
                link.click();
                URL.revokeObjectURL(url);
                alert('بک‌آپ با موفقیت ذخیره شد!');
            } catch (error) {
                alert('خطا در ذخیره بک‌آپ!');
            }
        }

        function importData() {
            document.getElementById('importInput').click();
        }

        // Modal Functions
        let currentModalType = '';

        function openModal(type) {
            currentModalType = type;
            const modal = document.getElementById('modal');
            const title = document.getElementById('modalTitle');
            const body = document.getElementById('modalBody');
            
            title.textContent = contentData.contentData[type].title;
            modal.style.display = 'block';
            
            if (type === 'playlist') {
                createPlaylistModal(body);
            } else {
                loadTextContent(type, body);
            }
        }

        function loadTextContent(type, body) {
            const data = contentData.contentData[type];
            let displayContent = (data.content || 'محتوایی وجود ندارد').replace(/\n/g, '<br>');
            
            if (!isEditMode) {
                displayContent = convertTextToLinks(displayContent);
            }
            
            body.innerHTML = displayContent;
            body.contentEditable = isEditMode;

            if (isEditMode) {
                let saveTimeout;
                body.oninput = function() {
                    clearTimeout(saveTimeout);
                    saveTimeout = setTimeout(() => {
                        const content = this.innerHTML.replace(/<br>/g, '\n').replace(/<div>/g, '\n').replace(/<\/div>/g, '');
                        contentData.contentData[type].content = content;
                        saveToStorage();
                    }, 500);
                };
            }
        }

        function convertTextToLinks(text) {
            return text.split('<br>').map(line => {
                const linkPattern = /^([^(]+)\s*\(((https?:\/\/[^\s)]+))\)$/;
                const match = line.match(linkPattern);
                if (match) {
                    const cleanText = match[1].trim();
                    const cleanUrl = match[2].trim();
                    return `<a href="${cleanUrl}" target="_blank">${cleanText}</a>`;
                }
                return line;
            }).join('<br>');
        }

        // Audio System
        function createPlaylistModal(body) {
            body.contentEditable = false;
            const uploadSection = isEditMode ? `
                <div class="audio-upload-area" onclick="document.getElementById('audioInput').click()">
                    <p>🎵 کلیک کنید یا فایل صوتی بکشید</p>
                    <p style="font-size: 12px; margin-top: 5px; opacity: 0.7;">MP3, WAV, M4A, OGG</p>
                    <p style="font-size: 10px; margin-top: 3px; opacity: 0.5;">حداکثر: 5MB</p>
                </div>
            ` : '';
            
            body.innerHTML = `
                ${uploadSection}
                <div class="playlist-container" id="playlistContainer">
                    ${renderPlaylist()}
                </div>
            `;

            if (isEditMode) {
                setupAudioEvents();
            }
        }

        function setupAudioEvents() {
            setTimeout(() => {
                const audioInput = document.getElementById('audioInput');
                const uploadArea = document.querySelector('.audio-upload-area');
                
                if (audioInput) {
                    audioInput.onchange = handleAudioUpload;
                }
                
                if (uploadArea) {
                    uploadArea.ondragover = e => e.preventDefault();
                    uploadArea.ondrop = handleAudioDrop;
                }
            }, 100);
        }

        function renderPlaylist() {
            const audioFiles = contentData.contentData.playlist.audioFiles || [];
            if (audioFiles.length === 0) {
                return '<p style="text-align: center; opacity: 0.7;">هنوز آهنگی آپلود نشده</p>';
            }

            return audioFiles.map((audio, index) => `
                <div class="audio-item">
                    <div class="audio-info">
                        <div class="audio-title">${audio.name}</div>
                        <div class="audio-progress">
                            <div class="audio-progress-bar" id="progress-${index}"></div>
                        </div>
                        <div style="font-size: 12px; opacity: 0.7;">${formatFileSize(audio.size)}</div>
                    </div>
                    <div class="audio-controls">
                        <button class="play-btn" onclick="toggleAudio(${index})" id="playBtn-${index}">▶</button>
                        ${isEditMode ? `<button class="delete-btn" onclick="deleteAudio(${index})">حذف</button>` : ''}
                    </div>
                </div>
            `).join('');
        }

        let currentAudio = null;
        let currentPlayButton = null;

        function toggleAudio(index) {
            const audioFiles = contentData.contentData.playlist.audioFiles || [];
            const audio = audioFiles[index];
            const playBtn = document.getElementById(`playBtn-${index}`);
            const progressBar = document.getElementById(`progress-${index}`);

            if (currentAudio && currentAudio.dataset.index == index) {
                if (currentAudio.paused) {
                    currentAudio.play().catch(() => {
                        alert('خطا در پخش آهنگ');
                        playBtn.textContent = '▶';
                    });
                    playBtn.textContent = '⏸';
                } else {
                    currentAudio.pause();
                    playBtn.textContent = '▶';
                }
                return;
            }

            if (currentAudio) {
                currentAudio.pause();
                currentAudio.currentTime = 0;
                currentAudio.src = '';
                if (currentPlayButton) {
                    currentPlayButton.textContent = '▶';
                }
            }

            currentAudio = new Audio();
            currentAudio.dataset.index = index;
            currentPlayButton = playBtn;

            currentAudio.onloadedmetadata = () => {
                currentAudio.play().catch(() => {
                    alert('خطا در پخش آهنگ');
                    playBtn.textContent = '▶';
                });
                playBtn.textContent = '⏸';
            };

            currentAudio.ontimeupdate = () => {
                if (currentAudio.duration) {
                    const progress = (currentAudio.currentTime / currentAudio.duration) * 100;
                    progressBar.style.width = progress + '%';
                }
            };

            currentAudio.onended = () => {
                playBtn.textContent = '▶';
                progressBar.style.width = '0%';
                currentAudio = null;
                currentPlayButton = null;
            };

            currentAudio.onpause = () => playBtn.textContent = '▶';
            currentAudio.onplay = () => playBtn.textContent = '⏸';

            currentAudio.src = audio.data;
        }

        function handleAudioUpload(event) {
            if (!isEditMode) return;
            
            const files = Array.from(event.target.files);
            
            files.forEach(file => {
                if (file.type.startsWith('audio/')) {
                    if (file.size > 5 * 1024 * 1024) {
                        alert(`فایل ${file.name} بیش از 5MB است.`);
                        return;
                    }
                    
                    const reader = new FileReader();
                    reader.onload = e => {
                        const audioData = {
                            name: file.name,
                            data: e.target.result,
                            size: file.size,
                            type: file.type,
                            id: Date.now() + '-' + Math.random().toString(36).substr(2, 9)
                        };
                        
                        if (!contentData.contentData.playlist.audioFiles) {
                            contentData.contentData.playlist.audioFiles = [];
                        }
                        
                        contentData.contentData.playlist.audioFiles.push(audioData);
                        updatePlaylist();
                        saveToStorage();
                    };
                    reader.readAsDataURL(file);
                } else {
                    alert(`فایل ${file.name} فرمت صوتی نیست.`);
                }
            });
            
            event.target.value = '';
        }

        function handleAudioDrop(e) {
            if (!isEditMode) return;
            
            e.preventDefault();
            const fakeEvent = {
                target: { files: e.dataTransfer.files, value: '' }
            };
            handleAudioUpload(fakeEvent);
        }

        function deleteAudio(index) {
            if (!isEditMode) return;
            
            if (confirm('آیا می‌خواهید این آهنگ را حذف کنید؟')) {
                if (currentAudio && currentAudio.dataset.index == index) {
                    currentAudio.pause();
                    currentAudio.src = '';
                    currentAudio = null;
                    currentPlayButton = null;
                }
                
                contentData.contentData.playlist.audioFiles.splice(index, 1);
                updatePlaylist();
                saveToStorage();
            }
        }

        function updatePlaylist() {
            const container = document.getElementById('playlistContainer');
            if (container) {
                container.innerHTML = renderPlaylist();
            }
        }

        function formatFileSize(bytes) {
            if (bytes === 0) return '0 Bytes';
            const k = 1024;
            const sizes = ['Bytes', 'KB', 'MB', 'GB'];
            const i = Math.floor(Math.log(bytes) / Math.log(k));
            return parseFloat((bytes / Math.pow(k, i)).toFixed(2)) + ' ' + sizes[i];
        }

        function closeModal() {
            document.getElementById('modal').style.display = 'none';
        }

        // Image Upload
        function compressImage(file, maxWidth = 400, quality = 0.8) {
            return new Promise((resolve) => {
                const canvas = document.createElement('canvas');
                const ctx = canvas.getContext('2d');
                const img = new Image();
                
                img.onload = () => {
                    const ratio = Math.min(maxWidth / img.width, maxWidth / img.height);
                    canvas.width = img.width * ratio;
                    canvas.height = img.height * ratio;
                    
                    ctx.drawImage(img, 0, 0, canvas.width, canvas.height);
                    resolve(canvas.toDataURL('image/jpeg', quality));
                };
                
                img.src = URL.createObjectURL(file);
            });
        }

        // Event Listeners
        document.getElementById('passwordInput').addEventListener('keypress', function(e) {
            if (e.key === 'Enter') {
                checkPassword();
            }
        });

        document.getElementById('profileName').addEventListener('blur', function() {
            if (isEditMode) {
                contentData.profileName = this.textContent;
                saveToStorage();
            }
        });

        document.getElementById('profileDesc').addEventListener('blur', function() {
            if (isEditMode) {
                contentData.profileDesc = this.textContent;
                saveToStorage();
            }
        });

        document.getElementById('imageInput').addEventListener('change', async function(e) {
            if (!isEditMode) return;
            
            const file = e.target.files[0];
            if (file) {
                try {
                    const compressedImage = await compressImage(file);
                    document.getElementById('profileImg').src = compressedImage;
                    contentData.profileImage = compressedImage;
                    saveToStorage();
                } catch (error) {
                    console.error('Image compression failed:', error);
                    const reader = new FileReader();
                    reader.onload = e => {
                        document.getElementById('profileImg').src = e.target.result;
                        contentData.profileImage = e.target.result;
                        saveToStorage();
                    };
                    reader.readAsDataURL(file);
                }
            }
        });

        document.getElementById('importInput').addEventListener('change', function(e) {
            const file = e.target.files[0];
            if (file) {
                const reader = new FileReader();
                reader.onload = e => {
                    try {
                        const importedData = JSON.parse(e.target.result);
                        
                        if (confirm('آیا مطمئن هستید داده‌های فعلی جایگزین شوند؟')) {
                            contentData = {
                                ...contentData,
                                ...importedData,
                                contentData: {
                                    ...contentData.contentData,
                                    ...importedData.contentData
                                }
                            };
                            
                            saveToStorage();
                            updateUI();
                            alert('داده‌ها با موفقیت وارد شدند!');
                        }
                    } catch (error) {
                        alert('فایل نامعتبر است!');
                    }
                };
                reader.readAsText(file);
            }
            e.target.value = '';
        });

        document.addEventListener('DOMContentLoaded', function() {
            document.querySelectorAll('.editable-title').forEach(title => {
                title.addEventListener('blur', function() {
                    if (isEditMode) {
                        const type = this.dataset.type;
                        contentData.contentData[type].title = this.textContent;
                        saveToStorage();
                    }
                });
                
                title.addEventListener('click', function(e) {
                    if (isEditMode) {
                        e.stopPropagation();
                    }
                });
            });
        });

        // Modal click outside to close
        window.addEventListener('click', function(event) {
            const modal = document.getElementById('modal');
            const passwordModal = document.getElementById('passwordModal');
            
            if (event.target === modal) {
                modal.style.display = 'none';
            }
            
            if (event.target === passwordModal) {
                closePasswordModal();
            }
        });

        // Window resize handler
        window.addEventListener('resize', () => {
            const canvas = document.getElementById('matrix');
            canvas.width = window.innerWidth;
            canvas.height = window.innerHeight;
        });

        // Make functions global for onclick handlers
        window.toggleEditMode = toggleEditMode;
        window.logout = logout;
        window.checkPassword = checkPassword;
        window.closePasswordModal = closePasswordModal;
        window.openModal = openModal;
        window.closeModal = closeModal;
        window.toggleAudio = toggleAudio;
        window.deleteAudio = deleteAudio;
        window.exportData = exportData;
        window.importData = importData;

        // Initialize app
        window.addEventListener('load', function() {
            initMatrix();
            loadFromStorage();
        });
    </script>
</body>
</html>
