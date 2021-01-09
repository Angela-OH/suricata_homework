# 20200107
suricata_rule_homework

## Assignment
* test.rules 파일에 20개의 사이트를 탐지하는 룰을 만든다.
* 이후 fast.log를 확인하면서 20개의 사이트가 제대로 탐지되는지 확인을 해 본다.
* 가급적이면 평문 통신(HTTP)이 이루어 지는 사이트 뿐만 아니라 TLS 통신(HTTPS)을 하는 사이트에 대한 탐지를 구현해 본다.

## Suricata Rule
* 평문 통신(HTTP)는 80번, TLS 통신(HTTPS)는 443번 포트를 사용
* `naver.com`, `wikipedia.org`, `github.com`, `facebook.com`, `namu.wiki`, `youtube.com`, `paypal.com`은 <br>기존의 수업시간에 했던 방식으로는 제대로 탐지가 되지 않았음

## reference
* https://suricata.readthedocs.io/en/suricata-4.1.4/rules/intro.html
* https://redmine.openinfosecfoundation.org/projects/suricata/wiki/Protocol_Anomalies_Detection
