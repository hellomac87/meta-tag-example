# basic meta tag for seo

SEO(검색엔진 최적화) 에 관련된 메타태그

1. description 웹 어플리케이션 설명에 관한 내용
2. keywords 웹 어플리케이션을 나타내는 keywords 에 관한 내용
3. author 웹 어플리케이션 작성자에 관한 내용

예시) 업비트

```html
<meta
  name="description"
  content="비트코인, 이더리움, 비트코인캐시, 리플, 라이트코인, 대시, 네오 등 100여 가지의 알트코인을 편리하고 안전하게 거래 #업비트 #모든 고객 거래 가능"
/>
<meta
  name="keywords"
  content="web, software, mobile, app, upbit, 업빗, 업비트"
/>
<meta name="author" content="두나무" />
```

# meta tag for facebook opengraph

페이스북, 메신저(kakao, slack 등) 링크공유 와 관련된 메타태그.

링크 공유시 설정해놓은 메타태그의 내용, 이미지가 나타남.

이미지는 최소 600px 이상의 너비를 사용해야함

예시) 업비트

```html
<meta property="og:url" content="https://upbit.com/signin" />
<meta
  property="og:site_name"
  content="업비트 - 가장 신뢰받는 암호화폐 거래소"
/>
<meta property="og:title" content="업비트" />
<meta
  property="og:image"
  content="https://static.upbit.com/upbit-pc/seo/upbit_facebook.png"
/>
<meta property="og:image:width" content="1200" />
<meta property="og:image:height" content="627" />
<meta
  property="og:description"
  content="비트코인, 이더리움, 비트코인캐시, 리플, 라이트코인, 대시, 네오 등 100여 가지의 알트코인을 편리하고 안전하게 거래 #업비트 #모든 고객 거래 가능"
/>
<meta property="og:locale" content="ko_kr" />
<meta property="og:type" content="website" />
```

# meta tag for twitter

예시) gdac

```html
<meta property="twitter:card" content="summary" />
<meta property="twitter:url" content="https://www.gdac.com/" />
<meta property="twitter:title" content="GDAC(지닥) - 블록체인 금융 플랫폼" />
<meta
  property="twitter:description"
  content="거래소 토큰을 통해 사용자 기여도 기반의 생태계를 지향합니다."
/>
<meta
  property="twitter:image"
  content="https://www.gdac.com/gdac-og-tag_twitter.png"
/>
```
