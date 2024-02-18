# PoABOT - Power of Algorithm

## 트레이딩뷰에서 전달되는 웹훅을 처리하는 봇입니다.

&nbsp;

- 지원 거래소
  - 업비트 KRW(원화) 마켓
  - 바이낸스 현물/선물 USDT,BUSD 마켓
  - 바이비트 현물/선물 USDT 마켓
  - 비트겟 현물/선물 USDT 마켓
  - 한국투자증권 한국/미국 주식 마켓

&nbsp;

# <주의>

_본 프로젝트는 개인적으로 개발한 프로젝트를 오픈소스로 공유한 것으로_

_발생하는 문제에 대한 모든 책임은 본인에게 있습니다._

# Dependency

> [fastapi](https://github.com/tiangolo/fastapi) , [ccxt](https://github.com/ccxt/ccxt) , [uvicorn](https://github.com/encode/uvicorn), [pocketbase](https://pocketbase.io/)

# Run

```
uvicorn main:app --reload --host 0.0.0.0
```

# PocketBase

<div class="alert m-t-10 m-b-xs">
  <div class="content">
    <ul>
      <li class="m-b-5">
        <a href="http://127.0.0.1:8090" target="_blank">
          <code>http://127.0.0.1:8090</code>
        </a>
        - if <code>pb_public</code> directory exists, serves the static content from it (html, css, images, etc.)
      </li>
      <li class="m-b-5">
        <a href="http://127.0.0.1:8090/_/" target="_blank">
          <code>http://127.0.0.1:8090/_/</code>
        </a>
        - Admin dashboard UI
      </li> 
      <li>
        <a href="http://127.0.0.1:8090/api/" target="_blank">
          <code>http://127.0.0.1:8090/api/</code>
        </a>
      - REST API
      </li>
    </ul>
  </div>
</div>