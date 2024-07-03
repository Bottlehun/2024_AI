## 1. 학습목표

<img src="https://github.com/Bottlehun/2024_AI/assets/95833863/70d0faba-cb18-4076-b525-047e1f1f8352.png">

* ### 1.1 XHTML 설정
    ```html
    <!-- 학습목표 -->
            <div class="cont-header">
                <div class="chapter-num n01" title="01" alt="01"></div>
                <div class="chapter-title-wrap">
                    <div class="chapter-title">컴퓨팅 시스템의 구성</div>
                    <div class="chapter-gole">
                        <p>우리 주변의 컴퓨팅 시스템을 탐색할 수 있다.</p>
                        <p>컴퓨팅 시스템의 구성요소를 파악할 수 있다.</p>
                    </div>
                </div>
                <div class="chap-intro-ani">
                    <div class="robot-ani" title=""></div>
                    <button class="gole-open-btn" data-option='{"type":"button", "target":"think_1"}'></button>
                </div>
            </div>
    <!-- 학습목표 -->
    ```


***

## 2. 물음표 클릭 박스

<img src="https://user-images.githubusercontent.com/95833863/178181513-31562573-9d14-4df0-8949-276fb91ecf2b.jpg">

* ### 2.1 XHTML 설정
    ```html
    <span class="question-box"><strong>입력 장치</strong></span>
    ```
    
***

## 3. 주석 클릭 팝업

<img src="https://user-images.githubusercontent.com/95833863/178181513-31562573-9d14-4df0-8949-276fb91ecf2b.jpg">

* ### 2.1 XHTML 설정
    ```html
    <!-- 루비(주석) 버튼 -->
    <ruby class="mini-popup-btn" data-option='{"id":"footnote_1"}'>시<rt>*</rt>스템</ruby></strong></span>
    <!-- 루비(주석) 버튼 -->

    <!-- 루비 미니 팝업-->
        <div class="mini-popup modal" id="footnote_1">
            <div class="close-btn"></div>
            <div class="mini-title">시스템</div>
            <div class="mini-cont">
                <p>여러 부분이 서로 맞물려 작동하거나 하나로 연결되어 목표를 달성하도록 설계한 것을 말한다.</p>
                <div class="mini-exam">예문</div>
                <div class="mini-exam-cont">
                    <p class="exam-txt">모바일 결제 <span>시스템</span>은 스마트폰, 스마트워치 등 모바일 기기를 통해 온, 오프라인에서 결제할 수 있도록 만든 방식이다.</p>
                    <img class="exam-img" src="./images/img_0101.png" alt="위두랑-게시판" />
                </div>
            </div>
        </div>
    <!-- 루비 미니 팝업-->
    ```

* ### 6.2 CSS 설정
    ```CSS
    #footnote_1 {
        top: 558px;
        left: 1033px;
        width: 510px;
    }
    ```


    |Option|설명|
    |---|---|
    |**id**|클릭 대상 팝업의 id와 동일하게 설정|
    |**show:'all' (default)**|클릭 팝업이 여러개 일 경우 모두 다 열어줌|
    |**show:'one'**|클릭 팝업이 여러개 일 경우 다른 팝업을 열면 이전 팝업이 닫힘. 'mini-popup-group' 클래스가 감싸진 범위에서만 작동, 생략시 페이지 전체 범위에서 작동.|
    |**class="mini-popup"**|기본 주석 팝업으로 사용|
    |**class="mini-popup blue"**|헤드 & 테두리 컬러가 남색 팝업으로 사용|
    |**class="mini-popup sky"**|헤드 & 테두리 컬러가 회색 팝업으로 사용|
    
    
***



















