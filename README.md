# 첫번째 프로젝트 : README.md를 위한 마크업 정리
## Usage of MARKDOWN 

|No|Items|Description|
|--|--|--|
| 1 | 글자크기 Heading | 6단계   |
| 2 | 강조 |  |
| 3 |  |  |
| 4 |  |  |

# Ⅰ. 제목(Header)
> # 제목 1: # 제목 1
>> ## 제목 2:  ## 제목 2
>>> ### 제목 3: ### 제목 3
>>>> #### 제목 4: #### 제목 4
>>>>> ##### 제목 5: ##### 제목 5
>>>>>> ###### 제목 6: ###### 제목 6

# Ⅱ. 강조(Emphasis)
### 1. 이텔릭
  1) *이텔렉체* : * 한개 별표(asterisks) *
  2) _이텔릭체_ : _ 한개 언더바(underscore) _
### 2. 두껍게 
  1) <strong>두껍게</strong> : < strong> 두껍게 < /strong>
  2) <b>두껍게</b> : < b> 두껍게 < /b>
  3) **두껍게** : ** 두개 별표(asterisks) **
  4) __두껍게__ :  __ 두개 언더바 (underscore) __
### 3. 두꺼운 이텔릭체
  1) **_두꺼운 이텔릭체_** :  ** _ 두꺼운 이텔릭체 _ **
  2)  ___두꺼운 이텔릭체___ : __ _ 두꺼운 이텔릭체 _ __
### 4. 취소선
  1) <del>취소선</del> :  < del>취소선< /del>
  2)  ~~취소선~~ : ~~ 두개 물결표시 ~~
  3)   취소선~ : ~ 한개 물결표시 ~
### 5. 첨자(위첨자/아래첨자)
  1) <sup>위첨자</sup>Letter : < sup>위첨자< /sup>
  2) <sub>아래첨자</sub>Letter : < sub>아래첨자< /sub>
### 6. 단락구분 (아래위 여백이 커짐 다름)
  1) <p>단락구분: < p> 단락구분 < /p> </p> 
  2) _<em>이건또</em>_

# Ⅲ. 목록
### 1) 순서없는 목록 < ul>< li>< /li>< /ul>
  <ul>
    <li>첫번째</li>
    <li>두번째</li>
    <li>세번째</li>
  </ul>

```
<ul>
  <li>첫번째</li>
  <li>두번째</li>
  <li>세번째</li>
</ul>
```
  
### 2) 순서있는 목록 < ol>< li></li> li>< /ol>
  <ol>
    <li>첫번째</li>
    <li>두번째</li>
    <li>세번째</li>
  </ol>
  
```
<ol>
  <li>첫번째</li>
  <li>두번째</li>
  <li>세번째</li>
</ol>
```
# 4. 링크
### 1) 링크연결
<em>마크다운 설명이 잘 정리된 git은 <a href="https://gist.github.com/ihoneymon/652be052a0727ad59601" title="gist.github.com">여기</a>를 참조.</em>

```
<em>마크다운 설명이 잘 정리된 git은 <a href="https://gist.github.com/ihoneymon/652be052a0727ad59601" title="gist.github.com">여기</a>를 참조.</em>
```
# 5. 코드블럭
### 1). 코드블럭
```
#a. 코드블럭 : ``` 코드블럭 ```
```

<pre><code>#b. 코드블럭: < pre>< code> 코드블럭 2 < /code>< /pre> </code></pre>

