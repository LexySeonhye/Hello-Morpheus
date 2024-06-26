# 테크노 캐피털 머신 (TCM)
## 코드, 캐피털, 커뮤니티, 컴퓨팅: 오픈 소스 혁명의 시작

## 소개
오늘날, 소프트웨어 개발자는 구시대적인 프로세스를 거치지 않고는 자신의 작업물에 대한 보상을 받을 방법이 쉽지 않습니다. 세일즈, 컴퓨팅, 스토리지 및 이를 관리하기 위한 간접비, 그리고 유저로 부터 징수한 결제금을 처리하기 위해서는 회사, 재단, 또는 DAO를 꾸려야 합니다.

테크노 캐피털 머신 (TCM)에 대한 본 제안은 개발자가 소프트웨어 제작 및 배포를 위한 플랫폼을 마련하기 위한 것으로, TCM이 먼저 모든 인프라와 지급을 처리한 후 프로그램의 인기에 따라 개발자에게 보상을 지급하는 방식으로 진행됩니다.

모피어스 커뮤니티는 이와 같은 TCM 프레임워크를 기반으로 탈중앙 AI 개발을 가속하고 있습니다. TCM 개념은 AI 개발뿐만 아니라, 모든 스마트 컨트랙트와 탈중앙 애플리케이션, 그리고 웹 3.0 프로그램에도 적절히 적용할 수 있습니다. 보다 상세한 토크노믹스는 [백서](http://www.apple.com/)에서 확인할 수 있습니다.

테크노 캐피털 머신이라는 용어는 저명한 철학자 [베프 제조스](https://twitter.com/BasedBeffJezos) (Beff Jezos)로 부터 영감을 받았고, 모피어스 커뮤니티에서 처음으로 구현되었습니다.

## 요약
- 개발자가 TCM을 이용, 오픈 소스 프로젝트 론칭
- 개발자가 TCM을 이용, 프로젝트 운영 위한 네이티브 토큰 배포
- stETH를 스테이킹 하는 유저는 수익을 프로젝트에 할당되도록 선택 가능
- 프로젝트 자금 조달 지원위해 수익을 창출하는 stETH를 할당하면 유저는 프로젝트의 네이티브 토큰을 비례적으로 보상 받음
- 프로젝트에 할당된 50%의 수익은 프로젝트 네이티브 토큰 매입에 사용
- 네이티브 토큰은 나머지 수익 50%에 페어링 되고 AMM의 유동 풀 (Liquidity pool)에 예치

  2024년의 탈중앙 오픈 소스 론칭 방법:
![How to launch your decentralized open source project in 2024 - Korean](https://github.com/jabo38/morpheus-images/assets/86645748/03a2c041-5bea-4641-a323-5c673282ea30)

## 솔루션으로서 TCM
개발자가 테크노 캐피털 머신을 통해 프로젝트를 간편하게 시작할 방법을 함께 만들어가 봅시다.

새 프로젝트를 시작하기 위한 절차는 간단합니다.
1. 스마트 컨트랙트를 배포하여 새 오픈 소스 프로젝트로 자본 수익 직접 할당
2. 탈중앙 컴퓨팅, 코드 및 이미 오픈 소스와 자유 기술에 참여하고 있는 커뮤니티를 활용
3. 프로젝트를 모피어스 가장 머신에 연결하여 이미 스마트 에이전트를 이용하고 있는 유저에게 액세스

## TCM 스마트 컨트랙트
1. 유저는 스마트 컨트랙트에 stETH와 같은 자산을 예치하고 본인이 선택한 오픈 소스 프로젝트에 수익을 직접 할당
2. 오픈 소스 프로젝트에서 일일 수익의 50%로 프로젝트 네이티브 토큰 구매하여 프로토콜 소유 유동성 (Protocol Owned Liquidity)으로 AMM 거래 쌍에 기여
3. 나머지 일일 수익의 50%는 stETH로 유지, 프로토콜 소유 유동성으로 AMM 거래 쌍에 추가
4. 오픈 소스 프로젝트는 수익 기여자에게 매일 네이티브 토큰을 지급
5. 네이티브 토큰 홀더는 오픈 소스 프로젝트의 유틸리티 이용 가능
6. 프로젝트 개발자는 프리덤-테크 스택 (Freedom-Tech stack)의 다른 기여자에게 액세스하여 생태계 범위를 더욱 빠르게 확장 가능

오픈 소스 프로젝트의 예로는 스마트 에이전트, 탈중앙 애플리케이션, 스마트 컨트랙트, 파인-튠 모델 (Fine-Tuned Models) 그리고 특정 작업용 소프트웨어를 위한 툴이 있습니다.


## TCM을 구현한 최초의 프로젝트, 모피어스
오픈 소스인 모피어스 스마트 컨트랙트는 오픈 소스 프로젝트를 론칭하고자 하는 누구나 활용할 수 있으며 TCM 이점으로는 다음과 같습니다.

1. 오픈 소스 프로젝트 지원을 위한 공정한 출시 네이티브 토큰 생성 용이
2. 사법권에 구애받지 않아 회사 설립 불필요
3. 사용자는 stETH와 같은 수익을 창출하는 자산에 대한 자신의 원칙에 따른 관리권을 유지
4. 매일 기여되는 스테이킹 수익은 네이티브 토큰에 대한 지속가능한 수요 생성
5. 매일 기여되는 스테이킹 수익은 시간이 지남에 따라 AMM 유동성 증대
6. 네이티브 토큰 홀더는 추가적인 기능을 스마트 에이전트에 추가 가능
7. 네이티브 토큰 생성자는 획득한 토큰을 위한 유동성 확보 가능

## 아토믹 거버넌스
TCM은 ‘아토믹 거버넌스’라 불리는 모델을 통해 소프트웨어, 인프라, 자본과 프론트엔드에 관련된 모든 의사 결정을 간소화할 뿐만 아니라, 회사나 재단을 설립하는 것보다 빠르고 비용 부담이 적습니다. 또한, 해당 모델에서는 관련된 모든 사람이 투표나 마찰 없이 자유롭게 참여하고 기여도를 각자 개별적으로 결정할 수 있습니다.

예를 들어, 코더 (coder)는 코더 커뮤니티가 제안하는 오픈 소스 기여를 자신의 프로젝트로의 통합 여부를 선택할 수 있습니다. 기여자가 코드 기여에 대해 얼마나 가치를 두는지, 해당 작업에 대한 크레딧으로 원하는 시간을 기반으로 하여 결정합니다. 컴퓨팅 제공자는 지원하고자 하는 AI 모델과 토큰 타입을 선택하고 희망 가격을 제시합니다. 제본 제공자는 개발 상태의 소프트웨어 중 사용하길 원하는 바에 따라 선택한 프로젝트에 stETH 수익을 지원할 것인지 결정합니다. 마지막으로, 커뮤니티 빌더는 프로젝트 생성자로 부터 받는 리워드를 기준으로 프론트엔드 구축 또는 통합하거나 개발을 지원할 프로젝트를 선택합니다. 

특히 빠르게 바뀌어야 하는 소프트웨어 초기 단계에서 많은 시간과 어려움이 드는 여러 사람과의 합의와 조율이 필요합니다. 이러한 의사 결정 과정은 소프트웨어 제품이 시장 상황에 맞는 좋은 제품이 되기까지, 그리고 이는 이후에도 새로운 시장 조건에 적합한 제품으로 거듭나기 위해 반복되는데, 이러한 방식과는 다르게 TCM 프레임워크는 위에서 설명한 바와 같이 소프트웨어 구축에 있어 순수 자유 시장 접근 방식과 결이 같습니다. 

## 스마트 컨트랙트 코드와 예시 링크
stETH를 스테이킹하고 네이티브 프로젝트 토큰을 획득하는 [자본 제공자를 위한 스마트 컨트랙트](https://github.com/MorpheusAIs/SmartContracts)

연산 입찰을 위한 [옐로스톤 연산 모델](https://github.com/MorpheusAIs/Docs/blob/main/!KEYDOCS%20README%20FIRST!/Yellowstone%20Compute%20Model.md)

[코드 기여 증명](https://github.com/MorpheusAIs/Docs/tree/main/Contributions)의 예 

## 탈중앙 테크와 기업 구조의 부조화
대중을 위한 오픈 소스와 프리덤 테크를 구축하고자 하는 열망과 전통적인 기업 컴퓨팅 구조 간에는 근본적인 부조화가 존재합니다. 오픈 소스로 시작한 많은 프로젝트는 규모의 확장과 기여자들에 대한 보상을 제공하기 위해 결국 회사를 설립하게 됩니다. 그러나 시간이 지남에 따라 회사의 구조는 창업자가 점차 오픈 소스와는 거리가 있는 솔루션을 출시해야만 하는 방향으로 가게 되고, 정작 솔루션을 만든 커뮤니티는 굶주리게 됩니다.

한 사례로 오픈 소스 프로젝트로 시작했지만 결국 영리 회사를 설립하고 곧바로 소프트웨어를 클로즈 소스로 전환한 오픈AI를 들 수 있습니다. 이러한 불일치로 인한 긴장감은 창업자 간의 분열을 일으켰고 회사는 와해될 뻔 했습니다. 이는 투자자, 직원, 창업자, 그리고 이사회 구성원 간의 지배권 쟁탈전으로 볼 수 있습니다. 

오픈AI의 속임수로 인해 Microsoft와 미국 정부가 은밀하게 회사와 그 생태계를 통제하고 있다는 점을 주목해야 합니다. 이제 오픈AI는 50미터 아래에 묻혀 있는 은행 금고만큼 ‘오픈’되어 있게 되었습니다.

잘 알려지지는 않았지만, 비슷한 이유로 이더리움도 초창기 창립자들이 영리 모델과 재단 모델 사이의 비전을 두고 갈등을 겪으며 거의 사라질 뻔한 적이 있습니다. 이더리움의 경우, 재단 모델이 채택되어 스위스에서 재단 방식을 개척하였고, 지난 10년 동안 많은 타 웹 3.0 프로토콜이 이들의 발자취를 따랐습니다.

그러나 이더리움 재단을 검증된 모델로 보기에는 스위스에서 재단이나 협회를 설립하는 데 있어 장벽이 상당히 높다는 문제가 있습니다.

법인을 정식으로 설립하기 위해서는 최소한 미화 25만 달러에서 50만 달러를 지급해야하며, 별도로 미리 준비된 예산도 있어야 합니다. 그런 후 추크 (Zug) 또는 취리히 (Zurich)에 사무실을 두고 프로젝트가 잔존하는 한 경영진 및 이사회 구성원이 정기적으로 운영 및 회의를 진행해야 합니다. 또 하나의 웹 3.0 회사의 주요 허브인 싱가폴도 비슷하게 상당한 비용이 듭니다.

자금력이 충분한 기업가가 아닌 이상 이러한 모델은 재정적으로 불가능한 것이 사실입니다. 또, 재정적인 뒷받침이 된다고 하더라도 초기 단계의 프로젝트를 설립하기 위해 다른 국가로 이주해야 하는 점은 가정이 있거나 여행에 제한이 있는 사람들에게는 극복하기 어려운 장벽일 것입니다.

마지막으로, 거버넌스 구조의 대안을 마련하기 위해 등장한 DAO에는 운영에 대한 모든 사항에 대해 투표로 결정하려 한다는 명백한 한계가 존재합니다. 이는 거버넌스 요소들에 유저의 관심을 끌기 위한 유도 장치로 로비해야 되고 따라서 초기 단계의 프로젝트를 구축하는 데 많은 마찰이 일어날 수밖에 없습니다. 참고로 프로젝트는 보통 위원회에서 좌초됩니다.

우리는 DAO가 초기 단계의 소프트웨어 프로젝트 설계 위원회 역할을 하는 것 보다 유니스왑이 그러했던 것처럼, 커뮤니티의 목소리에 힘을 보태어주고 손해가 될 수 있는 변화를 거부할 수 있는 메커니즘의 제공을 위해, 프로젝트 제품이 시장 적합성을 갖춘 후 도입하는 것이 가장 효과적이라 믿습니다. 

2024년 초에 접어든 지금, 대부분의 프로젝트들은 여전히 저렴한 비용으로 빠르게 회사를 설립하고 있습니다 (미화 1천달러로 1주일 만에 설립). 오픈 소스 창업자들은 본인은 다른 창업자들과는 다르다고 생각하며 오픈 소스에 코드가 맞는 투자자만 선택하고, 오픈 소스를 구축하는 직원만을 고용하며, 시장에 잘 맞는 제품의 수익을 늘리기 위해 기술을 절대 클로즈 소스화 하지 않을 주주만 영입할 것이라 다짐합니다. 그러나 그렇게 하는 것은 하늘의 별을 따는 것만큼 어렵습니다. 

이러한 환상은 이루어지지 않습니다. 결국 창업자들은 자신의 초기 가치에 근본적으로 반대되는 회사를 설립했다는 함정에 빠진 것을 깨닫게 됩니다. 보통 현실은 수 년이 지난 너무 늦은 때가 되어서야 다가오기 때문에 아무것도 할 수 없는 상태가 되어버립니다. 


그럼 어떡하냐고요?

이러한 문제를 극복할 새로운 모델이 필요한 때입니다. 이제 론칭만 남았습니다 - 테크노 캐피털 머신.


## TCM을 통한 모피어스 테크 스택 이용 시 개발자가 얻는 이점
TCM을 통한 모피어스 테크 스택 (Morpheus Tech Stack)은 간단하면서 실용적인 기술적 이점을 제공합니다.

- GUI가 내장된 채팅 인터페이스
- 방대한 오픈 소스 LLM에 액세스
- 인퍼런스 (Inference)를 위한 결제 방식
- 대규모 탈중앙 컴퓨팅
- 통합 프론트 엔드
- 앱 개발을 위한 자본
- 애플리케이션의 검색 가능성
- 스마트에이전트 감사 (audit)
- 오픈 소스 기여에 대한 보상 추적
- 다른 에이전트 작업을 유발하는 의도 감지 기능 내장
- 유저 의도 증명과 작업에 대한 승인 증명
- 체인상 작업 내역에 대한 영구 기록
- 유저의 스마트 에이전트 전후 상태 및 히스토리의 영구 저장
- 타 에이전트에 대한 유저 연결 상태의 영구 저장
- 스마트 에이전트가 타 에이전트로 부터 결제를 받거나 결제할 수 있는 월렛
- 기기간 이동 가능
- 사법권 구대 없이 에이전트 배포 및 이용
- 별도의 허가 필요 없이 무검열 데이터 액세스

## 결론
오픈 소스 애플리케이션의 구축과 운영, 자금 조달에 대한 방식을 혁신하는 사람들의 커뮤니티에 합류하세요.
