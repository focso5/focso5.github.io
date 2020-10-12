---
layout: post
title:  자바스크립트 언어 기본
date:   2020-10-12 14:23:20 +0300
description:  
permalink: /javaScript/2
img: post-js.png # Add image post (optional) 
tags: [javaScript, JavaScript 기초]
author: Adam Neilson # Add name author (optional)
--- 
JavaScript란?
프로그래밍적으로 웹브라우저를 제어하기위한 언어.
- 탈웹브라우저
    => 웹서버를 동작하기위한 도구로 사용(서버사이드스크립트)
    node.js(웹서버에서 사용하는 자바스크립트), php, java, python ...

언어란?
- 의사소통을 위한 약속

환경이란(웹브라우저, node.js, SpreadSheet)?
- 다양한 분야에서 자바스크립트가 사용되고있음.
- 언어를 사용하는 대상.
- 자바스크립트를 사용할때 사용환경에 맞는 문법을 사용해야 한다.

수학 관련 가테고리 
Math.pow() : 제곱
    => Math.pow(3,2)  // 3의 2승 = 9

Math.round() : 반올림
   => Math.round(10.6)  // 11

Math.ceil() : 소수점 버리고 올림
   => Math.ceil(10.2)  // 11

Math.floor() : 소수점 버림.
   => Math.floor(10.2)   // 10

Math.sqrt() : 제곱
   => Math.sqrt(9)  // 9의 제곱근은 3

Math.random() : 랜덤수
    => 100 * Math.random() // 100보다 작은 임의의 숫자를 출력

문자
    - escape 
        alert('egoing\ 's coding everybody');
        => 홑따옴표(')로 묶었는데 문자열에 홑따옴표가 또 들어갔을 경우 역슬래시(\)를 사용한다.
    - typeof
        typeof 1   // "number"
        typeof "1"  // "string"
        => 데이터 타입이 무엇인지 궁금할때
