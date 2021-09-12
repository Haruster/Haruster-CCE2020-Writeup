- 오늘은 사이버 공격 방어 대회(CCE)2020의 포렌식 분야에서 출제된 문제인 Simple Carv를 풀어보겠습니다.

![](https://images.velog.io/images/dsph9245/post/6df725ce-c256-4332-99ae-eee88081e93d/1.PNG)

- 문제 사이트에 들어가면 히든 파일을 이미지 덤프에서 찾으라고 하네요.

- disk.7z파일을 다운로드 해줍니다.

![](https://images.velog.io/images/dsph9245/post/fbe48453-17a6-44af-914c-5710a37d0ebb/2.PNG)

- 압축 파일을 열어보면 disk.img라는 이름으로 디스크 이미지 파일이 들어있는 걸 볼 수 있습니다. 

![](https://images.velog.io/images/dsph9245/post/74d95b82-330c-44de-8283-f9582b35e66f/3.PNG)

- 해당 파일을 압축해제하고 FTK Imager라는 포렌식 툴로 분석을 시작해보겠습니다.

![](https://images.velog.io/images/dsph9245/post/a4bda0fa-61e0-47e5-ae70-45de96192021/4.PNG)

- File -> Add Evidence Item -> Image File에서 disk.img파일을 선택해줍니다.

![](https://images.velog.io/images/dsph9245/post/455bd638-8f44-40b9-9ffa-ae01fa666590/5.PNG)

- disk.img 파일을 열어줍니다.

![](https://images.velog.io/images/dsph9245/post/226abc5b-f0c5-433c-889a-ba015666a441/6.PNG)

- disk.img -> NONAME -> root 디렉터리를 보면 수상해보이는 파일인 secret.pdf파일이 있는 것을 볼 수 있습니다.

- 해당 파일을 우클릭한 다음 export를 해서 바탕화면에 저장을 해줍니다.
![](https://images.velog.io/images/dsph9245/post/4fa6ea98-e07a-4f94-a97e-948dab5b4210/7.PNG)

![](https://images.velog.io/images/dsph9245/post/6afc46a9-355e-4d99-b002-815073cdfb28/8.PNG)

- secret.pdf 파일을 열어보면 Flag가 나와있는 것을 볼 수 있습니다.

![](https://images.velog.io/images/dsph9245/post/51ffe0cf-1897-4a85-9bd3-dff828fb0918/11.PNG)

- 해당 플래그를 문제 서버에 제출해주면 정상적으로 solve가 되는 것을 볼 수 있습니다.

![](https://images.velog.io/images/dsph9245/post/f9029025-b2a1-405c-af43-ca3844aace59/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202021-09-13%20%E1%84%8B%E1%85%A9%E1%84%8C%E1%85%A5%E1%86%AB%204.09.52.png)
