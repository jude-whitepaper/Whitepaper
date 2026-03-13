<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PM Portfolio | Profile</title>
    <style>
        :root {
            --primary-color: #2563eb;
            --text-dark: #1f2937;
            --text-gray: #4b5563;
            --bg-light: #f9fafb;
        }
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
            line-height: 1.7;
            color: var(--text-dark);
            margin: 0;
            background-color: var(--bg-light);
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 40px 20px;
        }
        header {
            border-bottom: 2px solid var(--primary-color);
            padding-bottom: 20px;
            margin-bottom: 40px;
        }
        h1 { font-size: 2.5rem; margin-bottom: 10px; }
        .quote {
            font-size: 1.2rem;
            color: var(--primary-color);
            font-weight: 600;
            margin-bottom: 20px;
        }
        section {
            background: white;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
            margin-bottom: 30px;
        }
        h2 {
            font-size: 1.5rem;
            border-left: 4px solid var(--primary-color);
            padding-left: 15px;
            margin-bottom: 20px;
        }
        ul { padding-left: 20px; }
        li { margin-bottom: 12px; color: var(--text-gray); }
        p { color: var(--text-gray); margin-bottom: 15px; }
        .highlight { font-weight: bold; color: var(--text-dark); }
        
        @media (max-width: 600px) {
            h1 { font-size: 1.8rem; }
            section { padding: 20px; }
        }
    </style>
</head>
<body>

<div class="container">
    <header>
        <h1>Product Manager</h1>
        <p class="quote">“고객 가치와 비즈니스 성장을 연결하는 프로덕트 매니저입니다.”</p>
    </header>

    <section>
        <h2>Core Competencies</h2>
        <ul>
            <li><span class="highlight">요구사항 및 우선순위:</span> 효율적인 제품 개발 주도 및 전략적 로드맵 설정</li>
            <li><span class="highlight">사용자 중심 설계:</span> UI/UX 정책 수립 및 고객 지향적 서비스 구현</li>
            <li><span class="highlight">이해관계자 조율:</span> 원활한 소통을 통한 요구사항 최적화 및 협업</li>
            <li><span class="highlight">팀 리딩 & Agile:</span> Scrum 방법론 기반의 팀 리빌딩 및 리소스 관리</li>
            <li><span class="highlight">도메인 확장성:</span> 계정, 결제, CS, 백오피스 등 광범위한 비즈니스 경험</li>
        </ul>
    </section>

    <section>
        <h2>Experience & Strengths</h2>
        
        <div style="margin-bottom: 25px;">
            <p class="highlight">🤝 커뮤니케이션 및 기술적 이해</p>
            <p>다양한 직군의 팀을 이끌며 서비스 정책 수립부터 아키텍처 의사결정 참여까지 폭넓은 경험을 쌓았습니다. 특히 기술 부채 관리와 개선 계획 수립을 통해 안정성과 성능을 동시에 향상시키는 전략적 사고에 능숙합니다.</p>
        </div>

        <div>
            <p class="highlight">📈 팀 리딩과 성과 관리</p>
            <p>10년 이상의 팀장 경력을 바탕으로 조직의 목표를 수립하고 성과를 모니터링합니다. 구성원들이 공동의 목표를 향해 책임감을 느끼고 협력할 수 있는 환경을 조성하는 데 강점이 있습니다.</p>
        </div>
    </section>
</div>

</body>
</html>
