# CoinScope

바이낸스 USDT 마켓 전체 코인을 실시간으로 불러와 기술적 지표(RSI, MACD, Stoch RSI, 볼린저밴드, EMA, 지지/저항, 추세선)와 시장 심리 지표로 매수·매도 구간을 제안하고, 보유 코인의 손익과 탈출 플랜을 계산하는 단일 HTML 웹앱입니다.

## 실행
- `index.html`을 브라우저로 열면 바로 동작합니다 (빌드 불필요).
- GitHub Pages: 저장소 Settings → Pages → Branch `main` / root 선택.

## 기능
- 1분~월봉 + 년봉(월봉 집계) 차트, WebSocket 실시간 갱신
- 지표 기반 종합 점수(-100~+100), 매수 관심 구간·손절·1/2차 목표가
- 멀티 타임프레임 신호표와 자동 분석 코멘트
- 보유 코인(KRW/USDT) 손익, 본전 필요 상승률, 4시간·일봉 기반 탈출 플랜, 가격 알림
- 공포탐욕지수, BTC 도미넌스, 시가총액, 환율, BTC 장세

## 데이터 출처
Binance 공개 시세 API, alternative.me, CoinGecko, open.er-api.com (API 키 불필요)

## 면책
신호는 규칙 기반 계산 결과로 투자 권유가 아니며, 미래 가격을 보장하지 않습니다.
