### Overview

vue-swipe is a touch slider for vue.js.

forked from [ElemeFE/vue-swipe](https://github.com/ElemeFE/vue-swipe)

* support ssr
* fix defaultIndex
* support mouse event
* ...

### Install

```bash
$ npm install vue-slidex
```

## Import using module
import { Swipe, SwipeItem } from 'vue-slidex';
```

### Usage

```HTML
<swipe class="my-swipe" :auto="3000" :defaultIndex="2">
  <swipe-item class="slide1"></swipe-item>
  <swipe-item class="slide2"></swipe-item>
  <swipe-item class="slide3"></swipe-item>
</swipe>
```

```CSS
.my-swipe {
        height: 200px;
        color: #fff;
        font-size: 30px;
        text-align: center;
        margin-bottom: 20px;
        width: 100%;
    }
    .mint-swipe-items-wrap
        overflow: hidden;
        position: relative;
        height: 200px
    .slide1 {
        background-color: #0089dc;
        color: #fff;
    }

    .slide2 {
        background-color: #ffd705;
        color: #000;
    }

    .slide3 {
        background-color: #ff2d4b;
        color: #fff;
    }
    .mint-swipe-item
        height 200px
        display inline-block
        width 100%
    .mint-swipe
        height 200px
    .slide
        display block
        z-index -1
    .mint-swipe-items-wrap > div
        display block
    .slide.is-active
        height 100%
        width 90%
        z-index 100
        margin-left 5%
        border-radius 10px
    .slide.before-active
        transform translateX(-10%)
        height 80%
        margin-top 5%
        z-index -100
    .slide.after-active
        transform translateX(90%)
        height 80%
        margin-top 5%
        z-index -100
```
