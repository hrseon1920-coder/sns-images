# sns-images

인스타그램 발행용 **이미지 보관 저장소**입니다.
사람이 보는 홈페이지가 아니라, 카드 이미지의 공개 https 주소를 만들어 주는 창고입니다.

- 이미지 위치: `public/cards/<logNo>/01.jpg` ...
- 공개 주소:   `https://<버셀주소>/cards/<logNo>/01.jpg`

엔진(`C:\sns-auto\tistory`)이 이 폴더에 카드 이미지를 복사한 뒤 git push 하면
Vercel이 자동 배포하여 인스타그램이 읽을 수 있는 주소가 됩니다.
