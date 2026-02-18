<table style="border: none; border-collapse: collapse; width: 100%;">
  <tr>
    <td width="30%" align="center" style="border: none;">
      <img src="[프로필_사진.jpg]" width="180" height="180" style="border-radius: 50%; object-fit: cover;" alt="Profile">
    </td>
    <td width="70%" style="border: none; padding-left: 20px;">
      <h1 style="margin: 0; font-size: 28px;">Minwoo Park</h1>
      <p style="color: #555; margin-bottom: 10px; font-weight: bold;">Hardware-Native AI Engineer</p>
      
      <p style="font-size: 14px; color: #333; line-height: 1.6;">
        <b>"Physical Hardware + AI Software Integration"</b><br>
        Field Service Engineer 출신으로 하드웨어와 소프트웨어의 접점을 깊이 이해합니다.<br>
        제한된 리소스 환경에서의 <b>최적화</b>와 <b>안정적인 파이프라인 구축</b>에 집중합니다.
      </p>

      <p>
        <a href="mailto:minwoo990210@gmail.com">
          <img src="https://img.shields.io/badge/minwoo990210@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white"/>
        </a>
        <a href="https://github.com/minwoooooooo">
          <img src="https://img.shields.io/badge/github.com/minwoooooooo-181717?style=flat-square&logo=github&logoColor=white"/>
        </a>
      </p>
    </td>
  </tr>
</table>

<br>

<h3>Technical Skills</h3>
<div align="left">

<b>AI & Vision</b><br>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"> <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white"> <img src="https://img.shields.io/badge/YOLOv8-00FFFF?style=flat-square&logo=yolo&logoColor=black"> <img src="https://img.shields.io/badge/Detectron2-000000?style=flat-square&logo=meta&logoColor=white"> <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white">

<br>

<b>Backend & Infrastructure</b><br>
<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white"> <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"> <img src="https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white"> <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black">

<br>

<b>Collaboration & Tools</b><br>
<img src="https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white"> <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white">

</div>

<br>
<hr>

<h3>Project 1. AI Traffic Law Violation Automatic Reporting System</h3>
<p style="color: #666; font-size: 14px; margin-top: -10px;"><i>Role: Project Manager (PM) & AI Model Developer | Team of 5</i></p>

<img src="[교통프로젝트_GIF_파일명.gif]" width="100%" style="border-radius: 8px; border: 1px solid #ddd; margin-bottom: 15px;">

<h4>1. Overview</h4>
<p>
  교통법규 위반(신호위반, 중앙선 침범, 꼬리물기 등) 차량을 실시간으로 탐지하고, 위반 증거 영상을 생성하여 '안전신문고' 양식에 맞춰 자동 신고하는 무인 단속 시스템입니다.
</p>

<h4>2. Tech Stack</h4>
<ul>
  <li><b>H/W:</b> Raspberry Pi 5 (Edge), Desktop PC (Server)</li>
  <li><b>AI Model:</b> YOLOv8 (Object Detection), Detectron2 (Lane Segmentation)</li>
  <li><b>Backend:</b> FastAPI, Docker, MariaDB</li>
  <li><b>Language:</b> Python 3.11</li>
</ul>

<h4>3. Key Contributions</h4>
<ul>
  [cite_start]<li><b>Edge-Server Distributed Architecture:</b> 라즈베리파이의 발열 및 연산 한계를 극복하기 위해, 영상 수집은 Edge에서 담당하고 AI 추론은 고성능 Server에서 처리하는 분산 구조 설계 [cite: 1]</li>
  [cite_start]<li><b>Advanced Vision Pipeline:</b> YOLOv8로 차량을 탐지하고, Detectron2로 차선을 인식한 뒤 투영 변환(Perspective Transform)을 적용하여 위반 차량을 정밀 판별 [cite: 1]</li>
  <li><b>Robust Data Processing:</b> AI-Hub 기반 300GB 주행 데이터 학습 및 Docker 컨테이너 환경 구축을 통한 배포 일관성 확보</li>
  <li><b>Agile Management:</b> Jira를 활용한 스프린트 단위 일정 관리 및 이슈 트래킹 주도</li>
</ul>

<p>
  👉 <a href="https://github.com/minwoooooooo/FinalProject_Aiplatform"><b>[GitHub] AI Model Repository</b></a> &nbsp;|&nbsp; 
  👉 <a href="https://github.com/minwoooooooo/FinalProject_webApplication"><b>[GitHub] Web Application Repository</b></a>
</p>
<p>
  💾 <a href="1조_최종보고.pdf"><b>Download Presentation (PDF)</b></a>
</p>

<br>
<hr>

<h3>Project 2. AI-based VGA Price Analysis & Prediction</h3>
<p style="color: #666; font-size: 14px; margin-top: -10px;"><i>Role: Solo Developer (Full-Stack)</i></p>

<img src="[VGA프로젝트_GIF_파일명.gif]" width="100%" style="border-radius: 8px; border: 1px solid #ddd; margin-bottom: 15px;">

<h4>1. Overview</h4>
<p>
  다나와(Danawa) 등 주요 사이트의 그래픽카드 시세 데이터를 수집 및 분석하여, 향후 가격 변동 추이를 예측하고 최적의 구매 시기를 제안하는 시계열 분석 솔루션입니다.
</p>

<h4>2. Tech Stack</h4>
<ul>
  <li><b>Language:</b> Python, Java</li>
  <li><b>AI Model:</b> TensorFlow/Keras (LSTM, CNN-LSTM), Scikit-learn (RandomForest, XGBoost)</li>
  <li><b>Data Processing:</b> Pandas, Selenium (Crawling)</li>
  <li><b>Visualization:</b> Streamlit</li>
</ul>

<h4>3. Key Contributions</h4>
<ul>
  [cite_start]<li><b>End-to-End Pipeline:</b> 데이터 크롤링부터 전처리(이상치 제거), 모델 학습, 시각화 서비스까지 전 과정 단독 개발 [cite: 2]</li>
  [cite_start]<li><b>Model Optimization:</b> LSTM, CNN-LSTM, GRU 등 다양한 시계열 모델 성능을 비교 분석하여 최적의 예측 모델(LSTM) 선정 및 튜닝 [cite: 2]</li>
  [cite_start]<li><b>Interactive Dashboard:</b> Streamlit을 활용하여 사용자가 모델별 예측 결과와 성능 지표(RMSE)를 직관적으로 비교할 수 있는 대시보드 구현 [cite: 2]</li>
</ul>

<p>
  👉 <a href="https://github.com/minwoooooooo/vga-price-forecaster"><b>[GitHub] Project Repository</b></a>
</p>
<p>
  💾 <a href="AI 기반 VGA 분석 예측 시스템.hwp"><b>Download Documentation (HWP)</b></a>
</p>

<br>
<hr>

<h3>Experience</h3>

<p><b>Koh Young Technology (고영테크놀러지)</b> <br> 
<i>Field Service Engineer | 2023.02 ~ 2024.06</i></p>
<ul>
  <li>SPI/AOI 정밀 3D 검사 장비 셋업 및 제조 환경별 S/W 파라미터 최적화</li>
  <li>고객사 기술 이슈 트러블슈팅 및 본사 개발팀(Vision/SW)과 협업하여 업데이트 배포 검증</li>
  <li>스마트팩토리 구축을 위한 장비-서버 간 통신 프로토콜 분석 및 데이터 연동 지원</li>
</ul>

<br>
