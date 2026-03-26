<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>월영 흥신소 - 의뢰 전문 사무소</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- 로딩 화면 -->
    <div id="loading-screen" class="loading-screen">
        <div class="loading-content">
            <div class="loading-text">접속 중...</div>
            <div class="loading-dots">
                <span></span>
                <span></span>
                <span></span>
            </div>
        </div>
    </div>
    <!-- 네비게이션 -->
    <nav class="navbar">
        <div class="nav-container">
            <div class="logo">
                <span class="logo-text">월영</span>
                <span class="logo-subtitle">흥신소</span>
            </div>
            <ul class="nav-menu">
                <li><a href="#about" class="nav-link">소개</a></li>
                <li><a href="#services" class="nav-link">서비스</a></li>
                <li><a href="#contact" class="nav-link">의뢰</a></li>
            </ul>
        </div>
    </nav>

    <!-- 히어로 섹션 -->
    <section class="hero">
        <div class="hero-content">
            <h1 class="hero-title">월영 흥신소</h1>
            <div class="hero-divider"></div>
            <p class="hero-subtitle">돈만 있으면 무엇이든 해결해 드립니다.</p>
            <a href="#contact" class="hero-btn">의뢰하기</a>
        </div>
        <div class="hero-code">
            <pre><span class="code-comment">// System initialized</span>
<span class="code-keyword">const</span> <span class="code-var">truth</span> = <span class="code-string">"찾기"</span>;
<span class="code-keyword">const</span> <span class="code-var">trust</span> = <span class="code-string">"믿음"</span>;
<span class="code-keyword">function</span> <span class="code-var">investigate</span>() {
  <span class="code-keyword">return</span> truth + trust;
}</pre>
        </div>
    </section>

    <!-- 소개 섹션 -->
    <section class="about" id="about">
        <h2 class="section-title">소개</h2>
        <div class="about-content">
            <div class="about-card">
                <div class="card-icon">◆</div>
                <h3>신뢰성</h3>
                <p>10년 이상의 경험으로 축적된 전문 지식과 철저한 보안으로 당신의 비밀을 지킵니다.</p>
            </div>
            <div class="about-card">
                <div class="card-icon">◆</div>
                <h3>기밀성</h3>
                <p>모든 의뢰 사항과 조사 과정은 엄격한 비밀유지 원칙 하에 진행됩니다.</p>
            </div>
            <div class="about-card">
                <div class="card-icon">◆</div>
                <h3>정확성</h3>
                <p>철저한 조사와 검증을 통해 정확한 정보만을 제공합니다.</p>
            </div>
        </div>
        <div class="about-description">
            <h3>우리는 누구인가</h3>
            <p>월영 흥신소는 개인, 기업, 법인을 대상으로 한 전문적인 조사 및 문제 해결 서비스를 제공하는 기관입니다. 신원 확인부터 정보 수집 및 추적, 현장 정리까지 다양한 분야의 의뢰를 받고 있습니다. 최신 기술과 전문적인 팀으로 당신이 원하는 정보를 정확하게 찾아내겠습니다.</p>
        </div>
    </section>

    <!-- 서비스 섹션 -->
    <section class="services" id="services">
        <h2 class="section-title">서비스</h2>
        <div class="services-grid">
            <div class="service-item">
                <div class="service-number">01</div>
                <h3>신원 확인</h3>
                <p>개인의 신원, 배경, 신용 정보 등을 철저히 조사합니다.</p>
            </div>
            <div class="service-item">
                <div class="service-number">02</div>
                <h3>정보 수집 및 추적</h3>
                <p>대상의 위치 및 기록을 추적하여 필요한 정보를 수집합니다.</p>
            </div>
            <div class="service-item">
                <div class="service-number">03</div>
                <h3>현장 정리</h3>
                <p>사건 현장 조사 및 증거 수집을 통해 상황을 파악합니다.</p>
            </div>
            <div class="service-item">
                <div class="service-number">04</div>
                <h3>기타 의뢰</h3>
                <p>위에 해당하지 않는 모든 종류의 조사 및 문제 해결 의뢰를 받습니다.</p>
            </div>
        </div>
    </section>

    <!-- 의뢰 섹션 -->
    <section class="contact" id="contact">
        <h2 class="section-title">의뢰 양식</h2>
        <div class="contact-container">
            <form class="contact-form" id="inquiryForm">
                <div class="form-group">
                    <label for="name">이름 *</label>
                    <input type="text" id="name" name="name" required>
                </div>

                <div class="form-group">
                    <label for="email">이메일 *</label>
                    <input type="email" id="email" name="email" required>
                </div>

                <div class="form-group">
                    <label for="phone">연락처 *</label>
                    <input type="tel" id="phone" name="phone" required>
                </div>

                <div class="form-group">
                    <label for="message">의뢰 내용 *</label>
                    <textarea id="message" name="message" rows="8" required placeholder="상세한 의뢰 내용을 입력해주세요..."></textarea>
                </div>

                <div class="form-group checkbox">
                    <input type="checkbox" id="privacy" name="privacy" required>
                    <label for="privacy">개인정보 수집 및 이용 동의</label>
                </div>

                <button type="submit" class="submit-btn">의뢰 제출</button>
            </form>

            <div class="contact-info">
                <h3>문의 정보</h3>
                <div class="info-item">
                    <span class="info-label">전화</span>
                    <p>010-XXXX-XXXX</p>
                </div>
                <div class="info-item">
                    <span class="info-label">이메일</span>
                    <p>inquiry@wolyoung.kr</p>
                </div>
                <div class="info-item">
                    <span class="info-label">위치</span>
                    <p>서울특별시 중구 을지로 3가 117-12-1 광명빌딩 4층 404호</p>
                </div>
                <div class="info-item">
                    <span class="info-label">업무 시간</span>
                    <p>24/7 (24시간 의뢰 접수)</p>
                </div>
            </div>
        </div>
    </section>

    <!-- 푸터 -->
    <footer class="footer">
        <div class="footer-content">
            <p>&copy; 2026 월영 흥신소. All rights reserved. | 비밀유지 원칙을 준수합니다</p>
            <div class="footer-links">
                <a href="#privacy">개인정보처리방침</a>
                <a href="#terms">이용약관</a>
                <a href="#security">보안 정책</a>
            </div>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
