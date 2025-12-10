---
layout: post
title: "첫 번째 블로그 포스트"
date: 2025-12-10 15:00:00 +0900
categories: [blog, example]
tags: [jekyll, markdown, tutorial]
author: "호형"
---

# 블로그 포스트 예시

이 글은 Jekyll 블로그 포스트의 **Markdown 예시**입니다.  
파일명은 `2025-12-10-my-post.md`로 저장되어 `_posts` 폴더에 위치합니다.

## 📌 주요 특징
- **Front Matter**: 레이아웃, 제목, 날짜, 카테고리, 태그 지정
- **Markdown 문법**: 제목, 리스트, 코드 블록, 이미지 등 활용 가능

## 📊 리스트 예시
- Jekyll은 정적 사이트 생성기
- Markdown을 HTML로 변환
- 블로그 포스트 자동 생성

## 🔗 링크
[홈으로 돌아가기](/)

## 🖼️ 이미지
![샘플 이미지](/assets/images/sample.jpg)


### ✅ 정리
이 포스트는 Jekyll 빌드 시 `/blog/example/2025/12/10/my-post.html` 같은 경로로 생성됩니다.

# Python 코드 하이라이팅 예시

이 포스트는 Jekyll 블로그에서 **Python 코드 블록**을 하이라이팅하는 방법을 보여줍니다.

👉 Jekyll이 빌드할 때 Rouge가 자동으로 Python 코드 하이라이팅 적용


### 2. Liquid 태그 방식

{% highlight ruby %}
def hello(name)
  puts "Hello, #{name}!"
end
{% endhighlight %}


## 📌 코드 블록 (fenced code block)
```python
def greet(name):
    print(f"Hello, {name}!")

greet("호형")


```markdown
CoinMarketCap

글로벌 암호화폐 시세 집계 플랫폼

BTC/USDT 거래쌍의 가격, 거래량, 시가총액, 변동률 제공

CoinGecko

실시간 암호화폐 가격 및 차트 제공

BTC/USDT 환율을 다양한 거래소 기준으로 집계

TradingView

전문 차트 플랫폼

BTC/USDT 캔들 차트, 기술적 지표, 거래소별 데이터 시각화 가능

Binance, Coinbase, Kraken 등 거래소 API

실제 거래소에서 발생하는 BTC/USDT 거래 데이터를 실시간 반영

가장 직접적이고 신뢰성 높은 데이터 소스