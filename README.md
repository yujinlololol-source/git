# Yujin Portfolio Site

이유진의 포트폴리오 사이트 (PM · UX · AI+X 학습자)  
**이력서 + 자기소개 + 포트폴리오(케이스 스터디)**를 한눈에 볼 수 있도록 제작했습니다.  
[Behance 프로젝트 페이지](https://www.behance.net/gallery/222113957/-PM-UX-)의 무드를 참고하여 웹으로 재구성했습니다.

---

## 📂 폴더 구조
yujin_portfolio_site/
├─ index.html # 메인 (이력서 + 자기소개)
├─ portfolio.html # 포트폴리오 (케이스 스터디)
├─ css/
│ └─ case.css # 공통 스타일시트
├─ js/
│ └─ toc.js # 사이드바 TOC 하이라이트 스크립트
├─ assets/
│ ├─ images/ # 프로필/커버 이미지
│ └─ videos/ # 데모 영상
└─ docs/ # PDF, PPT, DOCX, XLSX 산출물


---

## 🚀 로컬 실행
압축 해제 후 `index.html`을 더블클릭하면 브라우저에서 바로 확인할 수 있습니다.  
영상/파일이 보안 정책 때문에 안 열리면, 터미널에서 다음을 실행하세요:

```bash
cd yujin_portfolio_site
python -m http.server 8000

