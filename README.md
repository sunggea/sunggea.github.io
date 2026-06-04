<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio | AI Engineering</title>
    <link rel="stylesheet" href="style.css">
    <!-- 폰트 및 아이콘 로드 -->
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@300;400;700&display=swap" rel="stylesheet">
    <script src="https://kit.fontawesome.com/your-fontawesome-key.js" crossorigin="anonymous"></script>
</head>
<body>

    <!-- 헤더 / 내비게이션 -->
    <header>
        <div class="container">
            <h1>Portfolio</h1>
            <nav>
                <ul>
                    <li><a href="#about">About Me</a></li>
                    <li><a href="#education">Education</a></li>
                    <li><a href="#skills">Skills</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#experience">Experience</a></li>
                    <li><a href="#cv">CV</a></li>
                    <li><a href="#contact">Contact</a></li>
                    <li><a href="#career">Career Goal</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <div class="container">
        <!-- 1. About Me -->
        <section id="about">
            <h2>1. 자기소개 / About Me</h2>
            <div class="card">
                <p>안녕하세요! 인공지능공학을 전공하며 Computer Vision, Natural Language Processing, Data Analysis에 관심이 많은 [이름]입니다. 향후 AI 서비스 개발자 또는 AI 연구자로 성장하는 것을 목표로 하고 있습니다. 현재는 대규모 데이터 처리와 효율적인 딥러닝 모델 경량화 기술을 깊이 있게 학습 중입니다.</p>
            </div>
        </section>

        <!-- 2. Education -->
        <section id="education">
            <h2>2. Education</h2>
            <div class="card">
                <h3>Chosun University (조선대학교)</h3>
                <p class="sub-text">Department of Artificial Intelligence Engineering (인공지능공학과)</p>
                <ul>
                    <li><strong>Year:</strong> 3rd year (3학년 재학 중)</li>
                    <li><strong>Period:</strong> 2024.03 - Present</li>
                    <li><strong>Relevant Coursework:</strong> Machine Learning, Deep Learning, Data Structures, Web Programming, Linear Algebra</li>
                    <li><strong>GPA:</strong> 4.1 / 4.5</li>
                </ul>
            </div>
        </section>

        <!-- 3. Skills -->
        <section id="skills">
            <h2>3. Skills</h2>
            <div class="card grid-2">
                <div>
                    <h3>Technical Stacks</h3>
                    <ul>
                        <li><strong>Programming:</strong> Python, JavaScript, C/C++</li>
                        <li><strong>AI / ML:</strong> PyTorch, TensorFlow, scikit-learn</li>
                        <li><strong>Web:</strong> HTML, CSS, React</li>
                        <li><strong>Tools:</strong> Git, GitHub, VS Code, Docker</li>
                        <li><strong>Database:</strong> MySQL, SQLite</li>
                    </ul>
                </div>
                <div>
                    <h3>Proficiency (숙련도)</h3>
                    <ul class="proficiency-list">
                        <li><strong>Python:</strong> <span class="badge intermediate">Intermediate</span></li>
                        <li><strong>PyTorch:</strong> <span class="badge basic">Basic</span></li>
                        <li><strong>Git:</strong> <span class="badge basic">Basic</span></li>
                        <li><strong>React:</strong> <span class="badge basic">Basic</span></li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- 4. Projects -->
        <section id="projects">
            <h2>4. Projects</h2>
            <div class="card">
                <h3>[프로젝트 제목: 예시 - 객체 탐지 기반 스마트 주차 관리 시스템]</h3>
                <ul>
                    <li><strong>Summary:</strong> CCTV 영상을 활용하여 실시간으로 주차 공간의 점유 상태를 파악하는 웹 서비스</li>
                    <li><strong>Period:</strong> 2026.03 - 2026.05 (3개월)</li>
                    <li><strong>Tech Stack:</strong> Python, PyTorch, YOLOv8, Flask, SQLite</li>
                    <li><strong>Role:</strong> 팀장 / YOLOv8 모델 학습 및 백엔드 API 개발</li>
                    <li><strong>Key Features:</strong> 
                        <ul>
                            <li>주차 구역 ROI 지정을 통한 실시간 차량 점유 상태 분류</li>
                            <li>Flask 서버를 활용한 실시간 점유 현황 웹 대시보드 시각화</li>
                        </ul>
                    </li>
                    <li><strong>Results:</strong> 실시간 탐지 정확도 mAP@0.5 기준 94.2% 달성</li>
                    <li><strong>GitHub:</strong> <a href="https://github.com/username/project-repo" target="_blank">Repository 링크</a></li>
                    <li><strong>Demo / Image:</strong> <a href="#" target="_blank">데모 영상 보기</a> 또는 <span class="text-muted">[이미지 준비 중]</span></li>
                </ul>
            </div>
        </section>

        <!-- 5. Experience -->
        <section id="experience">
            <h2>5. Experience</h2>
            <div class="card">
                <ul class="experience-list">
                    <li><strong>AI Lab Undergraduate Intern</strong> (인공지능 연구실 학부 인턴 | 2025.09 - 2026.02)</li>
                    <li><strong>Programming Club Member</strong> (교내 알고리즘 동아리 소속 | 2024.03 - Present)</li>
                    <li><strong>Capstone Design Team Project</strong> (캡스톤 디자인 팀 프로젝트 진행)</li>
                    <li><strong>AI Competition Participant</strong> (교외 AI 경진대회 참가 경력)</li>
                </ul>
            </div>
        </section>

        <!-- 6. CV / Resume PDF -->
        <section id="cv">
            <h2>6. CV / Resume PDF</h2>
            <div class="card text-center">
                <p class="warning-text">⚠️ 주의: 다운로드용 PDF에는 주민등록번호, 상세 주소 등 민감한 개인정보가 포함되어 있지 않습니다.</p>
                <a href="./resume.pdf" class="btn-download" download>📄 Download My Resume (PDF)</a>
            </div>
        </section>

        <!-- 7. Contact -->
        <section id="contact">
            <h2>7. Contact</h2>
            <div class="card">
                <ul>
                    <li><strong>Email:</strong> <a href="mailto:student@example.com">student@example.com</a></li>
                    <li><strong>GitHub:</strong> <a href="https://github.com/username" target="_blank">https://github.com/username</a></li>
                    <li><strong>LinkedIn:</strong> <a href="#" target="_blank">LinkedIn Profile (선택사항)</a></li>
                    <li><strong>Blog / Notion:</strong> <a href="#" target="_blank">Technical Blog (선택사항)</a></li>
                </ul>
            </div>
        </section>

        <!-- 8. Career Goal / Future Plan -->
        <section id="career">
            <h2>8. Career Goal / Future Plan</h2>
            <div class="card">
                <div class="grid-4">
                    <div class="goal-item">AI Developer</div>
                    <div class="goal-item">Data Scientist</div>
                    <div class="goal-item">Computer Vision Engineer</div>
                    <div class="goal-item">Graduate School / Research Track</div>
                </div>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2026 [Your Name]. Powered by GitHub Pages.</p>
    </footer>

</body>
</html>
