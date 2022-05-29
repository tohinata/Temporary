## 에셋 파일 네이밍 규칙 정리


![image](https://user-images.githubusercontent.com/20883553/170869366-78f5c6e2-01c1-4db2-87e1-7a35855a3d34.png)


<br>

1. prefix
    1. asset type
        - 이 리소스는 무엇인가? 인 what에 해당
        - 아이콘(ic), 버튼(btn), 이미지(img), 로고(logo), 배경(bg), 비디오(vid)
    2. namespace
        - 앱에서 속한 위치인 where에 해당
        - Ex) 청박의 경우 intro, avatar, portal, badge 등의 화면
        
<br>

2. root
    1. asset name
        - 에셋의 고유 이름
        - 대표할만한 명사 또는 구체적이고 특징적인 묘사 또는 메타포
        
<br>

3. suffix    
    - prefix와 root 영역의 조합으로 만든 이름이 중복된게 있을 때 한정자를 추가하는 영역
    - 서비스에 맞게 suffix 를 정의하면 됨    

    <br>
    
    ![image](https://user-images.githubusercontent.com/20883553/170871432-d98ff243-a6c5-4bcf-ba1e-c7d2fa567ed6.png)
    
<br>

4. Ex) 트로핏 에셋 네이밍
    1. prefix(asset type) - root(asset name)
        - ![image](https://user-images.githubusercontent.com/20883553/170871618-e2ab2ce8-4fd2-4965-8538-45a5ea2a6653.png)
    
    2. prefix(namespace) - suffix or root(asset name) - suffix
        - ![image](https://user-images.githubusercontent.com/20883553/170871608-c48d537c-05bf-4400-8637-2cfb2141a148.png)

    3. prefix - root - suffix
        - ![image](https://user-images.githubusercontent.com/20883553/170871747-641033c7-61c4-4396-a515-0cdcbec0155d.png)

<br>

5. 생각해볼 규칙
    1. asset type 을 반드시 명시?
    2. 약자가 아닌 full name 을 사용? (icon - ic , button - btn /bn, ...)
    3. 이름 연결은 under-bar(_)? dash(-) ?


출처
- [아이콘에 제대로 된 이름 붙여주기](https://brunch.co.kr/@pizzakim/26)
- [추가 규칙](https://minnimalism.medium.com/%EC%95%84%EC%9D%B4%EC%BD%98%EC%97%90-%EC%A0%9C%EB%8C%80%EB%A1%9C-%EB%90%9C-%EC%9D%B4%EB%A6%84-%EB%B6%99%EC%97%AC%EC%A3%BC%EA%B8%B0-%EC%A0%81%EC%9A%A9%ED%95%98%EA%B8%B0-62a46936054e)
