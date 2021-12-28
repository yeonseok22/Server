# changed
- 정리

|| Before | After |
|:--:|:---|:---|
|라즈베리파이 <-> 서버 | 서버 시작 -> ```Pi Server Thread``` 시작 -> ```Pi Read Thread``` 시작 | 서버 시작 후, ```Pi Server Thread```, ```Pi Read Thread```, ```Pi Send Thread``` 동시 시작|


1. 서버 Logic Process
  - Before
    - 서버 Logic Process
    ![image](https://user-images.githubusercontent.com/49339278/147593835-027ce177-8be3-4e03-a7e9-a2e5ce74198d.png)
    - 라즈베리파이 <-> 서버 Logic Process
    ![image](https://user-images.githubusercontent.com/49339278/147593913-95303eed-c240-45b4-838c-9b70e084bfd3.png)
    - 안드로이드 <-> 서버 Logic Process
    ![image](https://user-images.githubusercontent.com/49339278/147593937-18a24d95-05db-41e7-8bc3-0f6863fda6cd.png)
---
  - After
    - 서버 Logic Process
    ![image](https://user-images.githubusercontent.com/49339278/147593996-6af9575b-991f-43ed-bfee-1cb809f62b6e.png)
    - 라즈베리파이 <-> 서버 Logic Process
    - 안드로이드 <-> 서버 Logic Process