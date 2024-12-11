# 등산경로를 NFT로 만들어서 참여자들에게 보내주기!

이 프로젝트는 등산하는 동안 스마트 디바이스를 통해 수집한 GPS 좌표, 해발고도, 시간 등의 데이터를 활용하여 등산 이동경로를 추출하고, 이를 SUI 블록체인에 손쉽게 저장하는 방법을 정리하였다. 블록체인에 NFT 형태로 저장되어 함께 참여한 누구에게든 기념품, 인증서의 의미로 보낼 수 있다. 블록체인의 장점을 적극 활용하여 움직임(MOVE) 데이터를 안전한 동시에 최대한의 신뢰성을 확보하면서 저장할 수 있게 되는 것이다.


##기능
- 등산 데이터 수집: Garmin 스마트 위치에서 등산 데이터(GPX 파일)를 가져옴. 이 데이터에는 좌표(위도, 경도), 고도, 타임스탬프가 포함됨
- SUI 블록체인 통합: 수집된 등산 데이터를 SUI 블록체인에 안전하게 저장
- 웹 서비스: 블록체인에 등산 데이터를 쉽게 업로드하고, 조회할 수 있는 서비스


##기술 스택
- SUI 블록체인: 안정성이 확보된 SUI 블록체인을 이용하여 필요한 등산 데이터를 저장할 수 있으며, 궁극적으로는 가장 저렴한 수준의 비용으로 실시간 트래킹까지 제공할 수 있게 됨
- Rust 프로그래밍 언어: Rust를 기반으로 만들어진 SUI 블록체인과 가장 호환성이 높음. Solana, Near protocol, Polkadot 등이 Rust를 기반으로 만들어진 블록체인이라 확장성을 확보할 수 있음.


##환경 설정 및 소프트웨어 설치:
- Frondend: **Vite** (https://vite.dev/guide/)
- Backend: **Rust** (https://www.rust-lang.org/tools/install)
- Smart Contract: **Sui** (https://docs.sui.io/guides/developer/getting-started/sui-install)
