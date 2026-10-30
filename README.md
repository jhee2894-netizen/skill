# skill

jhee2894-netizen의 Claude 스킬 마켓플레이스.

## 스킬

| 스킬 | 설명 |
|------|------|
| `weekly-sales-report` | 구글 시트 '판매관리의 사본'으로 지난주(월~일) 주간 매출 리포트를 만들어 슬랙 채널 스레드에 올린다. Google Drive·Sheets, Slack 커넥터가 필요하다. |
| `card-news-generator-v2` | 주제와 배경색(선택: 배경 이미지 폴더)을 받아 600x600 인스타그램형 카드뉴스 시리즈를 만든다. 원작: [bear2u/my-skills](https://github.com/bear2u/my-skills) (MIT License), 수정 없이 수록. |

## 설치

Claude Code:

```
/plugin marketplace add jhee2894-netizen/skill
/plugin install weekly-sales-report@jhee2894-skills
/plugin install card-news-generator-v2@jhee2894-skills
```

Claude 앱(claude.ai): `dist/` 폴더의 `.skill` 파일([`weekly-sales-report.skill`](dist/weekly-sales-report.skill), [`card-news-generator-v2.skill`](dist/card-news-generator-v2.skill))을 받아 설정 → 기능 → 스킬에서 업로드한다.

## 라이선스

`card-news-generator-v2`는 bear2u의 원작으로 MIT License를 따른다.
