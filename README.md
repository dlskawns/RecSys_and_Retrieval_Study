# 추천시스템, 검색모델 관련 구현을 위한 Repository입니다.

## 이론을 공부해보고, 이를 코드로 구현해봅니다.


기본적인 추천 시스템 종류 컨텐츠 기반추천(CB), 협업 필터링(CF)

컨텐츠 기반 추천시스템(Content Based)
협업 필터링(CF, Collaborative Filtering)
* 메모리 기반 (Memory Based)
    * 유저 기반 (User Based)
    * 아이템 기반 (Item Based)
    
    
* 모델 기반 (Machine Learning)
    * 잠재요인 기반(Latent factor Based)
    	* SVD(Singular Vector Decomposition)
    	* MF(Matrix Factorization)
    	* AutoEncoder(Latent Feature)
    	* SVM(Support Vector Machine) - 한마디로 선형 결정 경계를 찾는 모델 
        
        
    * 기타 분류/회귀 기반
  
        
    * 딥러닝 기반(Deep Learning Based)
    	* NCF(Neural Collaborative Filtering)
        * DCN(Deep Cross Network)
        * Wide & Deep
    	* DeepFM(Deep Fatorization Machine)
