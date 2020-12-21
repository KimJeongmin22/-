# 디즈니 실사영화 분석: 뮬란의 몰락

#### 전공: 중국언어문화전공
#### 학번: 201801040 
#### 이름: 김정민

<img width="800" src="https://user-images.githubusercontent.com/74295599/102784841-46883900-43e0-11eb-9c66-e313c1821de8.jpg">

----------------------------------------------------------------------------------------------
### 배경
디즈니 실사 영화 <뮬란>은 중화권 최고 스타 '유역비'와 미국 대표 컨텐츠 회사 '디즈니'의 만남으로 많은 영화인을 설레게 했다. 디즈니 제작진은 역사상 최고 제작비 3억 달러를 바탕으로 중국의 신장 지역에 3주 동안 거주하며 영화에 심혈을 기울였다. 그러나 개봉 후 <뮬란>은 작품성과 기획력 부분에서도 부정적 평가를 받으며 디즈니 실사 영화 사상 최악의 혹평을 받았다.  

----------------------------------------------------------------------------------------------
### 목적
디즈니 역대 실사 영화 <알라딘> <미녀와 야수> <정글북> <라이언킹> <이상한 나라의 앨리스>의 분석을 통해 부정적 평가를 극복하기 위한 디즈니의 매력 요소를 찾고, <뮬란>의 흥행 실패 요인을 파악한다. 

----------------------------------------------------------------------------------------------
### 대상 데이터 (네이버 영화 평점 및 리뷰)
* 기간: 영화 개봉일 ~ 2020년 11월 17일 

- 알라딘 (2019.05.23 / 평점 9.42 / 1,272만명) - 수집 데이터: 27,100개
- 미녀와 야수 (2017.03.16 / 평점 8.99 / 515만명) - 수집 데이터: 17,800개
- 라이온킹 (2019.07.17 / 평점 8.64 / 474만명) - 수집 데이터: 9,200개
- 정글북 (2016.06.09 / 평점 8.57 / 253만명) -수집 데이터: 7,700개
- 이상한 나라의 앨리스 (2010.03.04 / 평점 7.55 / 214만명) - 수집 데이터: 5,800개
- 뮬란 (2020.09.17 / 평점 8.12 / 23만명) - 수집 데이터: 4,500개

----------------------------------------------------------------------------------------------
### 방법
네이버 영화 평점 리뷰로 수집한 데이터의 언어 분석(형태소 분석, KoNLPy) 수행

----------------------------------------------------------------------------------------------

### 해석
#### Ⅰ. 디즈니 실사 영화의 부정적 평가
<div>
<img width="600" src="https://user-images.githubusercontent.com/74295599/102784542-e5f8fc00-43df-11eb-85ad-e672b546cccf.png">
<img width="600" src="https://user-images.githubusercontent.com/74295599/102784521-e1344800-43df-11eb-8d20-99d005cb6f42.png">
<img width="600" src="https://user-images.githubusercontent.com/74295599/102784582-f5784500-43df-11eb-9e26-363f775a8645.png">
<img width="600" src="https://user-images.githubusercontent.com/74295599/102784591-f8733580-43df-11eb-8131-02bc362932d1.png">
<img width="600" src="https://user-images.githubusercontent.com/74295599/102784566-eee9cd80-43df-11eb-86ea-5eac99c5437d.png">
<div>
(순서대로 <알라딘> <미녀와 야수> <정글북> <라이언킹> <이상한 나라의 앨리스> 형용사, 상위 200개 분석)

디즈니 실사 영화의 형용사 분석 결과 부정적 어감을 지닌 어휘들은 '재미없다', '뻔하다', '유치하다', '진부하다'는 내용이 대부분이며, 높은 평점을 준 관람객들도 '뻔하고 유치하다'는 의견을 제시했다. 관람객들이 이미 영화의 줄거리를 알고 있는 상태에서 디즈니는 영화의 내용을 어떻게 풀어낼 것인지 보다 구체적인 형태소 분석으로 알아보고자 한다.

----------------------------------------------------------------------------------------------

#### Ⅱ. 영화의 흥행요인
#### (1) 캐릭터
<div>
<img width="600" src="https://user-images.githubusercontent.com/74295599/102784523-e1ccde80-43df-11eb-8464-8e39df01b6fd.png">
<img width="600" src="https://user-images.githubusercontent.com/74295599/102784532-e2fe0b80-43df-11eb-9e88-220228d4dc65.png">
<div>
(<알라딘> 명사 228개 분석)

<알라딘>은 램프와 양탄자를 비롯한 모든 역할이 평균 0.05%(상위 3%)이상 언급되었다. 특히 악당 역할(술탄, 악당, 자파, 악역)은 6점 이상 평점을 준 관람객들에게서 빠지지 않고 언급되었다.
<div>
<img width="600" src="https://user-images.githubusercontent.com/74295599/102784544-e6919280-43df-11eb-9674-2bcb3d635e9a.png">
<img width="600" src="https://user-images.githubusercontent.com/74295599/102784546-e72a2900-43df-11eb-8704-cf0e9f46dc3a.png">
<img width="600" src="https://user-images.githubusercontent.com/74295599/102784550-e85b5600-43df-11eb-900a-a009442d190e.png">
<div>   
(<이상한 나라의 앨리스> 명사 299개 분석)

<이상한 나라의 앨리스> 역시 대부분의 캐릭터(앨리스, 여왕, 모자장수, 거울)가 높은 평점을 준 관람객들의 압도적인 언급을 보였고, 악역(여왕)은 주인공 앨리스를 제외하고 모든 평점에서 언급된 유일한 캐릭터이다.

#### ∴ 디즈니는 악역마저 미워할 수 없는 다채로운 캐릭터를 만들었다.

#### (2) 스토리

<div>
<img width="150" src="https://user-images.githubusercontent.com/74295599/102784570-f01afa80-43df-11eb-8541-c70dcf73ead9.png">
<img width="150" src="https://user-images.githubusercontent.com/74295599/102784575-f1e4be00-43df-11eb-8dbb-3ea5a2eab1be.png">
        
<img width="150" src="https://user-images.githubusercontent.com/74295599/102784505-da0d3a00-43df-11eb-8c00-17dd7c38de91.png">
<img width="150" src="https://user-images.githubusercontent.com/74295599/102784584-f6a97200-43df-11eb-8bcd-3d353d35d841.png">
<div>
(<정글북> 명사 1,392개 / <라이언킹> 명사 956개 분석)

<정글북>과 <라이언킹>은 감정을 나타내는 단어(눈물, 감동, 사랑, 공감)가 유독 많이 언급되고, 어린 시절의 향수를 자극(추억, 향수, 새록새록, 옛날)하는 단어들이 자주 등장한다.

#### ∴ 호불호가 갈릴 수 있는 자연을 배경으로 한 작품은 감정을 자극하는 이야기에 초점을 맞추었다.

#### (3) 음악
<div>
<img width="600" src="https://user-images.githubusercontent.com/74295599/102784560-ec877380-43df-11eb-8fa9-54344bd1abfd.png">
<img width="600" src="https://user-images.githubusercontent.com/74295599/102784578-f3ae8180-43df-11eb-9f08-4d95e25b974a.png">
<img width="600" src="https://user-images.githubusercontent.com/74295599/102784589-f7da9f00-43df-11eb-8477-5d0bb7168d66.png">
<img width="600" src="https://user-images.githubusercontent.com/74295599/102784538-e4c7cf00-43df-11eb-8006-47f9fb4f2cc0.png">
<img width="600" src="https://user-images.githubusercontent.com/74295599/102784600-fc06bc80-43df-11eb-87f5-7a3d2238ff34.png">
<div>
(순서대로 <이상한 나라의 앨리스> <정글북> <라이언킹> <알라딘> <미녀와 야수> 명사 분석)

디즈니 실사 영화는 모두 노래에 대한 언급이 빠지지 않았으며, '편곡'의 언급을 통해 기존 고전 애니메이션 음악이 재해석되었음을 알 수 있다.

----------------------------------------------------------------------------------------------
#### Ⅲ. <뮬란>과의 비교

(1) 공통점
<img width="150" src="https://user-images.githubusercontent.com/74295599/102784596-fad58f80-43df-11eb-861b-adc645533243.png">
(<뮬란> 명사 2,488개 분석)

기존 실사 영화들처럼 뮬란 또한 노래의 편곡이 사용되었고 동양의 분위기에 맞게 '경음악'이 사용되었다. 그러나 다른 작품들처럼 노래에 대한 언급이 크게 나타나지 않았다. 

(2) 차이점
<div>
<img width="600" src="https://user-images.githubusercontent.com/74295599/102784592-f90bcc00-43df-11eb-9f5d-f7607dafa107.png">
<img width="600" src="https://user-images.githubusercontent.com/74295599/102784594-f9a46280-43df-11eb-89fb-cf90ae491dfa.png">
<div>
(<뮬란> 명사 분석)

명사 분석 결과 역시 주요 등장인물의 언급이 가장 많이 나타났으나, 등장인물의 언급이 낮은 평점의 관람객들에게 더 많이 언급되어 캐릭터에 대한 호감도는 낮았다. 영화에는 등장하지 않는 원작 속 배역(무슈, 용, 귀뚜라미)과 영화에만 등장하는 마녀가 저평점 관람객들에게 많이 언급되어 기존 캐릭터 부재와 등장인물의 변화가 부정적인 영향을 미쳤음을 알 수 있다. 배역의 언급을 제외하고는 '액션'이 가장 높게 언급되어 기존 디즈니 실사 영화에서는 생소한 어휘가 등장했다. <뮬란>의 전투씬은 고평점 관람객들에게는 '액션'으로 저평점 관람객들에게는 '무협'이란 단어로 지칭되었는데, 이는 보는 이에 따라 디즈니 영화보다는 중국의 무협 영화라는 명칭을 얻게 되는 원인이 되었다. 

<img width="400" src="https://user-images.githubusercontent.com/74295599/102784597-fb6e2600-43df-11eb-8bc7-84cbc4e85e83.png">
(<뮬란> 형용사 분석)
형용사 분석 결과, 영화에 대한 평가보다는 배우 '유역비'의 외모와 관련된 어휘가 더 눈에 띄었다. 이는 관람객들을 영화에 온전히 몰입시키지 못한 결과라 할 수 있다.  

----------------------------------------------------------------------------------------------
#### Ⅳ. 결론

기존 디즈니 실사 영화는 3가지 방면(캐릭터, 스토리, 음악)에서 단조로운 영화 흐름에 매력 요소를 더하였다. <뮬란> 또한 세가지 방면에서 차별화를 주었지만 캐릭터의 변화와 액션 추가라는 파격적인 요소가 오히려 독이 되었다.  
