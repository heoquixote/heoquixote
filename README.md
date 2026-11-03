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
class Hote:
    name: str = "허진성 (Jinseong Heo)"
    location: str = "Seoul, KR 🇰🇷"
    roles: list = field(default_factory=lambda: [
        "Data Analyst", "BI Engineer", "AI Workflow Builder", "Data Educator",
    ])
    community: list = field(default_factory=lambda: [
        "Tableau Ambassador 2026·2027",
        "n8n Ambassador",
        "2× DataFam Rising Star",
    ])
    teaching: str = "1,000+ learners on Tableau, SQL, Python, ML, n8n"
    writing: list = field(default_factory=lambda: [
        "Data Visualization with Tableau (WikiDocs)",
        "ADsP 수험서 공동 집필 (시대에듀)",
    ])
    motto: str = "좋은 분석은 숫자에서 끝나지 않고, 다음 행동을 분명하게 만든다."

    def now(self) -> list[str]:
        return [
            "🏭 제조·품질 데이터 이상탐지 & 예지보전",
            "⚙️ n8n + LLM 기반 데이터 워크플로 자동화",
            "📚 실무형 데이터 교재와 강의 콘텐츠 제작",
        ]
```

## 🛠️ Tech Stack

<p>
  <img src="https://skillicons.dev/icons?i=python,postgres,sklearn,pytorch,js,html,css,swift&theme=dark" alt="Languages & ML" />
  <br/>
  <img src="https://skillicons.dev/icons?i=git,github,githubactions,vscode,notion,obsidian,vercel&theme=dark" alt="Tools" />
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
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=heoquixote&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=heoquixote&layout=compact&theme=github_dark&hide_border=true&langs_count=6" alt="Top languages" />
  <br/>
  <img src="https://streak-stats.demolab.com?user=heoquixote&theme=github-dark-blue&hide_border=true" alt="GitHub streak" />
</div>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=heoquixote&style=flat-square&color=58A6FF&label=profile+views" alt="Profile views" />
</div>
