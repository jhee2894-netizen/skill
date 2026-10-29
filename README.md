# skill

jhee2894-netizen의 Claude 스킬 마켓플레이스.

## 스킬

| 스킬 | 설명 |
|------|------|
| `weekly-sales-report` | 구글 시트 '판매관리의 사본'으로 지난주(월~일) 주간 매출 리포트를 만들어 슬랙 채널 스레드에 올린다. Google Drive·Sheets, Slack 커넥터가 필요하다. |

## 설치

Claude Code:

```
/plugin marketplace add jhee2894-netizen/skill
/plugin install weekly-sales-report@jhee2894-skills
```

Claude 앱(claude.ai): [`dist/weekly-sales-report.skill`](dist/weekly-sales-report.skill)을 받아 설정 → 기능 → 스킬에서 업로드한다.
