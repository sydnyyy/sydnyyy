## 🚀 Performance & Architecture Highlights
- [**WebSocket 연결 관리**](https://github.com/sydnyyy/Gameet-BE?tab=readme-ov-file#websocket-%EC%A4%91%EB%B3%B5-%EC%97%B0%EA%B2%B0) - 중복 연결 차단
- [**Singe-Flight 패턴 기반 OPEN API 호출 설계**](https://github.com/sydnyyy/Exchange-Rate-API?tab=readme-ov-file#%ED%99%98%EC%9C%A8-open-api-%EC%8B%A4%EC%8B%9C%EA%B0%84-%ED%98%B8%EC%B6%9C-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8) - 동시 호출 1회로 제한
- [**Kafka 스트림즈 윈도우 집계 결과 컨트롤 & Topology 설계**](https://medium.com/@asdny1234/kafka-streams%EC%9D%98-window-results-%EC%BB%A8%ED%8A%B8%EB%A1%A4%ED%95%98%EA%B8%B0-3c20c360cf02) - DB I/O 최소화 및 중간 결과 억제
- [**Bloom Filter 적용**](https://medium.com/@asdny1234/bloom-filter%EB%A1%9C-db-%EB%B6%80%ED%95%98-%EA%B0%90%EC%86%8C-%EC%84%B1%EB%8A%A5-61-%EA%B0%9C%EC%84%A0-e46e8ce62d6d) - 처리 속도 **154ms → 59ms** 개선 & False Positive 최소화
- [**KStream-KTable Join 적용 실패 사례**](https://medium.com/@asdny1234/kstream-ktable-join-%EC%A0%81%EC%9A%A9-%EC%8B%A4%ED%8C%A8%EA%B8%B0-f7b8bfa11e42) - 처리 속도 **10.2s → 1.7s** 개선했으나, DB 영속화 지연 문제 발생
- [**Exponential Backoff and Jitter 적용**](https://medium.com/@asdny1234/resilience4j-retry-circuitbreaker-%EC%A0%81%EC%9A%A9%ED%95%98%EA%B8%B0-a60d06a46c54) - 재시도 요청 분산으로 서버 부하 완화

<br>

![GitHub Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=sydnyyy&theme=github)