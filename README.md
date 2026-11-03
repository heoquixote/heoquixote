<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=24&duration=3000&pause=800&color=58A6FF&center=true&vCenter=true&width=640&lines=Hi%2C+I'm+Hote+%F0%9F%91%8B;Data+%C2%B7+BI+%C2%B7+AI+Workflow+Engineer;Tableau+Ambassador+%7C+n8n+Ambassador;Turning+data+into+next+actions." alt="Typing SVG" />

<p>
  <a href="https://www.data-learners.com/"><img src="https://img.shields.io/badge/data--learners.com-0D1117?style=for-the-badge&logo=googlechrome&logoColor=58A6FF" alt="Data Learners"></a>
  <a href="https://data-learners.wikidocs.net/"><img src="https://img.shields.io/badge/WikiDocs-0D1117?style=for-the-badge&logo=bookstack&logoColor=3FB950" alt="WikiDocs"></a>
  <a href="https://h-ote.tistory.com/"><img src="https://img.shields.io/badge/Blog-0D1117?style=for-the-badge&logo=tistory&logoColor=FF5A4A" alt="Blog"></a>
  <a href="https://www.linkedin.com/in/hote/"><img src="https://img.shields.io/badge/LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=0A66C2" alt="LinkedIn"></a>
  <a href="https://public.tableau.com/app/profile/hote/vizzes"><img src="https://img.shields.io/badge/Tableau_Public-0D1117?style=for-the-badge&logo=tableau&logoColor=E97627" alt="Tableau Public"></a>
  <a href="https://www.salesforce.com/trailblazer/hote"><img src="https://img.shields.io/badge/Trailblazer-0D1117?style=for-the-badge&logo=salesforce&logoColor=00A1E0" alt="Trailblazer"></a>
</p>

</div>

```python
from dataclasses import dataclass, field

@dataclass
class DataLearners:
    """배운 것을 실력으로, 실력을 결과로."""

    brand: str = "데이터러너즈 (Data Learners)"
    instructor: str = "허진성 (Hote)"
    site: str = "https://www.data-learners.com"
    mission: str = "SQL, Python, Tableau, 통계, AI 자동화를 실제 업무 문제와 프로젝트 중심으로"

    courses: dict = field(default_factory=lambda: {
        "SQL 데이터 분석": "Query to Insight",
        "Python 데이터 워크": "Code to Analysis",
        "Tableau 실무 시각화": "Data to Story",
        "n8n 데이터 워크플로우": "Work to Flow",
        "통계적 의사결정": "수치 → 판단",
        "머신러닝 실무 모델링": "데이터 → 예측",
    })

    learning_system: tuple = (
        "LBL · 01 개념과 원리",
        "LBL · 02 툴 사용법과 실습",
        "PBL · 03 프로젝트 기획과 수행",
        "PBL · 04 멘토링과 포트폴리오",
    )

    impact: dict = field(default_factory=lambda: {
        "누적 수강생": "1,000+",
        "기업·기관 교육": "50회+",
        "KDT 내일배움캠프 NPS": 93.5,
    })

    instructor_profile: list = field(default_factory=lambda: [
        "Tableau Ambassador 2026·2027",
        "n8n Ambassador 2026·2027",
        "ex) Salesforce Tableau Certified Instructor",
        "『태블로를 활용한 데이터 시각화』 저자",
    ])

    worked_with: list = field(default_factory=lambda: [
        "팀스파르타", "코드잇", "BDAI", "SeSAC", "국민대학교",
        "Trailhead Academy", "LG전자", "NHN", "CJ프레시웨이", "삼성화재",
    ])

    def contact(self) -> str:
        return "https://hote.app.n8n.cloud/form/edu-inquiry"
```

## 🛠️ Tech Stack

<p>
  <img src="https://skillicons.dev/icons?i=python,postgres,sklearn,pytorch&theme=dark" alt="Languages & ML" />
  <br/>
  <img src="https://skillicons.dev/icons?i=git,github,githubactions,vscode,notion,obsidian&theme=dark" alt="Tools" />
</p>

<p>
  <img src="https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white" alt="Tableau">
  <img src="https://img.shields.io/badge/Salesforce-00A1E0?style=flat-square&logo=salesforce&logoColor=white" alt="Salesforce">
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white" alt="n8n">
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="pandas">
  <img src="https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=111111" alt="DuckDB">
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter">
  <img src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="Claude">
  <img src="https://img.shields.io/badge/Codex-000000?style=flat-square&logo=openai&logoColor=white" alt="Codex">
</p>

## 🚀 Featured Projects

| Project | Description | Stack |
|:--|:--|:--|
| 🎓 [**data-learners.com**](https://github.com/heoquixote/heoquixote.github.io) | 실무 프로젝트 기반 데이터 교육 사이트 | `HTML` `GitHub Pages` |
| 🏭 [**predictive-maintenance-action-center**](https://github.com/heoquixote/predictive-maintenance-action-center) | 설비 센서 데이터를 경보·후속 조치로 연결하는 예지보전 분석 제품 | `JavaScript` `Analytics` |
| 📈 [**invest-dashboard**](https://github.com/heoquixote/invest-dashboard) | 투자 지표 탐색·모니터링 대시보드 | `JavaScript` `Dashboard` |
| 💬 [**n8n-chat-demo**](https://github.com/heoquixote/n8n-chat-demo) | n8n Chat Trigger + `@n8n/chat` 임베드 데모 | `n8n` `GitHub Pages` |
| ⏱️ [**pomo-timer**](https://github.com/heoquixote/pomo-timer) | 집중 시간을 요일×시각 히트맵으로 기록하는 macOS 메뉴바 뽀모도로 | `Swift` `macOS` |
| 📊 [**claude-usage-monitor**](https://github.com/heoquixote/claude-usage-monitor) | Claude 사용량 모니터링 도구 | `Python` |

## 📚 Open Books (WikiDocs)

| Book | Topic |
|:--|:--|
| [Data Visualization with Tableau](https://github.com/heoquixote/Data_Visualization_with_Tableau) | Tableau 차트·계산·대시보드 실무 |
| [tableau-book](https://github.com/heoquixote/tableau-book) | Tableau 실무 가이드 |
| [sql-basic](https://github.com/heoquixote/sql-basic) | SQL 기초부터 분석 쿼리까지 |
| [statistics-book](https://github.com/heoquixote/statistics-book) | 기술통계·가설검정·회귀·A/B 테스트 |
| [n8n-book](https://github.com/heoquixote/n8n-book) | n8n 기반 데이터 워크플로 구축 |
| [developing-with-Codex](https://github.com/heoquixote/developing-with-Codex) | Codex와 협업하는 개발 워크플로 |
| [engineer-quality-management](https://github.com/heoquixote/engineer-quality-management) | 품질경영 엔지니어링 |

## 📊 GitHub Stats

<div align="center">
  <img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=heoquixote&theme=github_dark" alt="Profile details" />
  <br/>
  <img height="180" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=heoquixote&theme=github_dark" alt="GitHub stats" />
  <img height="180" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=heoquixote&theme=github_dark" alt="Repos per language" />
  <br/>
  <img src="https://streak-stats.demolab.com?user=heoquixote&theme=github-dark-blue&hide_border=true" alt="GitHub streak" />
</div>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=heoquixote&style=flat-square&color=58A6FF&label=profile+views" alt="Profile views" />
</div>
