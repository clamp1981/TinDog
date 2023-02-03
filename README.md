# BootStrap

BootStrap을 이용하여 TinDog 이라는 가상 사이트를 생성해 보기 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)


## Overview

### Screenshot

![my-privew](https://user-images.githubusercontent.com/14327580/216262354-ced24d9f-9c74-4f0b-bfb8-3beadfd632e7.png)


### Links

- Live Site URL: [TinDog]()

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- BootStrap 


### What I learned

```html
<!-- ***************  BootStrap 설정 시작******************** -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-GLhlTQ8iRABdZLl6O3oVMWSktQOp6b7In1Zl3/Jr59b6EGGoI1aFkw7cmDA6j6gD" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-w76AqPfDkMBDXo30jS1Sgez6pr3x5MlQ1ZAGC+nuZB+EYdgRZgiwxhTBTkF7CXvN"
        crossorigin="anonymous"></script>
<!-- ***************  BootStrap 끝 ******************** -->

<!-- Nav Bar 사용 -->
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
            <div class="container-fluid">
                <a class="navbar-brand" href="#">Navbar</a>
                <!-- ***************  화면이 작아지면 토글 버튼 생성******************** -->
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
                    aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <!-- ***************  상단 메뉴 ******************** -->
                    <!-- ms-auto : 우측으로 메뉴를 정렬  -->
                    <ul class="navbar-nav ms-auto">
                        <li class="nav-item">
                            <a class="nav-link" href="#">Contact</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Pricing</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Download</a>
                        </li>
    
                    </ul>
                </div>
                
            </div>
        </nav>

```
