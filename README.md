# openCarry

## youtube.json 설명
**신중하게 수정할 것! 잘못 수정하면 앱에서 오류발생!**
```java
[
  {
    'lang':'ko',  /* 언어별 유튜브 리스트 */
    'list':
      [
        {
          'title':'당신을 위한 추천 레슨', /* 유튜브 목록 타이틀 */
          'playListId':'PL2KtS99uNp9V0MV2eJsDh_Yfmf5lscI-d',  /* 재생목록 ID */
          'channel':'' /* 채널 ID */
        },
        {
          'title':'박연습',
          'playListId':'PLVpetxH4Pz5tI7HDje4IVtRaZSwliogk_',
          'channel':'UC6sVX_-lnuq8LqsD7Lp4WMg'  /* 채널 ID 가 있으면 playListId 는 무시하고 채널의 모든 동영상을 view 많은 순으로 보여준다 */
        }
      ]
  },
  {
    'lang':'en',
    'list':
      [
        {
          'title':'당신을 위한 추천 레슨',
          'playListId':'PL2KtS99uNp9V0MV2eJsDh_Yfmf5lscI-d',
          'channel':''
        },
        {
          'title':'박연습',
          'playListId':'PLVpetxH4Pz5tI7HDje4IVtRaZSwliogk_',
          'channel':'UC6sVX_-lnuq8LqsD7Lp4WMg'
        }
      ]
  }
]
```
