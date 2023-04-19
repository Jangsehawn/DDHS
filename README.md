# DDHS 논문을 구현한 코드입니다

## (Learning_From_Imbalanced_Data_With_Deep_Density_Hybrid_Sampling)

해당 방법론은 imbalanaced 문제에 data level로 접근하여 각 클래스 별로 분포가정을 통해 적합한 데이터를 만들어냅니다.

논문은 아래 링크에 공개가 되어있지만 코드는 구현되어 있지 않아 직접 구현해보았습니다

<논문 링크>

https://ieeexplore.ieee.org/document/9723474

<논문 리뷰 세미나>

http://dsba.korea.ac.kr/seminar/?mod=document&pageid=1&keyword=imbal&uid=2575

ddhs_v2 : large class, small class 에서 추출 비율을 하이퍼 파라미터로 받아 최적화 할 수 있도록 구현, 파리미터 별 디폴트 옵션 설정 
