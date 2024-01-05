# QuizEffect

### 퀴즈 디자인
```js
 <main id="main">
        <div class="quiz__wrap">
            <div class="quiz">
                <div class="quiz__header">
                    <span class="quiz__date"></span>  // 시험년도
                    <span class="quiz__type"></span>  // 시험과목  
                </div>
                <div class="quiz__main">
                    <div class="quiz__question">
                       <em></em>.  // 문제번호
                       <span></span> // 문제내용
                    </div>

                    <div class="quiz__animation">   // 퀴즈 애니메이션 
                        <div class="wrapper">
                            <div class="card-container">
                                <div class="dog">
                                    <div class="head">
                                        <div class="ears"></div>
                                        <div class="face"></div>
                                        <div class="eyes">
                                            <div class="teardrop"></div>
                                        </div>
                                        <div class="nose"></div>
                                        <div class="mouth">
                                            <div class="tongue"></div>
                                        </div>
                                        <div class="chin"></div>
                                    </div>
                                    <div class="body">
                                        <div class="tail"></div>
                                        <div class="legs"></div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="quiz__input">
                        <input type="text" placeholder="정답을 입력해주세요!">  // 정답 입력 
                    </div>
                    <div class="quiz__answer"></div> // 정답
                    <div class="quiz__desc"></div>  // 정답에 대한 해설
                </div>
                <div class="quiz__footer">
                    <button class="quiz__confirm">정답 확인하기</button> // 정답 확인하기 버튼
                </div>
            </div>
        </div>
    </main>
    <!-- //main -->
```