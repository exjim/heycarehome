# Heycare Homepage

헤이케어 IR 자료를 바탕으로 제작한 정적 홈페이지 1차 시안입니다.

## Files

- `index.html`: 실제 홈페이지 구현 파일
- `wireframe.html`: 저충실도 와이어프레임
- `planning.md`: 홈페이지 구조와 기획 메모
- `assets/`: 홈페이지에 사용되는 이미지 에셋

## Local Preview

브라우저에서 `index.html`을 열면 바로 확인할 수 있습니다.

## GitHub Pages

GitHub 저장소 이름은 `heycarehome`을 사용합니다.

현재 연결 대상 저장소:

`https://github.com/exjim/heycarehome`

GitHub Pages 설정:

1. GitHub 저장소의 `Settings`로 이동
2. `Pages` 메뉴 선택
3. `Build and deployment`에서 `Deploy from a branch` 선택
4. Branch를 `main`, folder를 `/root`로 설정
5. `Custom domain`에 `www.heycare.co.kr` 입력
6. DNS 적용 후 `Enforce HTTPS` 활성화

## Gabia DNS

Gabia 도메인 관리에서 `www.heycare.co.kr`을 GitHub Pages에 연결합니다.

권장 DNS 레코드:

| Type | Host | Value |
| --- | --- | --- |
| CNAME | www | exjim.github.io |

루트 도메인 `heycare.co.kr`도 함께 연결하려면 Gabia에서 apex 도메인용 `A` 레코드를 GitHub Pages IP로 추가하면 됩니다. 다만 최종 접속 주소를 `www.heycare.co.kr`로 둘 경우, 우선 위 `www` CNAME 설정이 핵심입니다.
