# itda-work

> 대한민국 직장인이 AI를 진짜 업무 파트너로 쓸 수 있도록,
> 사람과 AI 도구를 잇는 인프라와 오픈소스를 만드는 조직입니다.

보고서 작성, 법령 검색, 문서 처리 같은 실무 도구가 Claude·Cowork에 안전하게 연결되고
운영될 수 있는 바탕을 Django 위에 세웁니다.

## 주요 프로젝트

| 프로젝트 | 설명 |
|---------|------|
| [itda-hub](https://github.com/itda-work/itda-hub) | 도구를 골라 도구함에 담고 한 번의 로그인으로 Claude·Cowork에 연결하는 오픈소스 MCP 허브 |
| [channels-nats](https://github.com/itda-work/channels-nats) | Django Channels용 NATS 채널 레이어. Redis 대신 Go 바이너리 하나로, Windows 친화적 |
| [django-wireview](https://github.com/itda-work/django-wireview) | Django Channels 기반 실시간 서버 렌더링 UI 라이브러리. Phoenix LiveView에 해당 |

## 기술 스택

- **Backend**: Python, Django, Django Channels
- **AI 연결**: MCP, fastmcp, OAuth 2.1
- **Infra**: NATS, Go

## 연락처

- GitHub: [@itda-work](https://github.com/itda-work)
