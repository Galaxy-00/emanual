{% capture dxl_led_policy %}  
**주의** :  
(장치의 상태(조건)에 따른 LED의 동작입니다.)

| 상태                | LED 동작      |
|:-------------------:|:-------------:|
| 부팅                | 1회 점멸      |

{% endcapture %}
<div class="notice--warning">{{ dxl_led_policy | markdownify }}</div>