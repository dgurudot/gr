# **재진입 횟수**

## 목적: 

- 이 설정을 사용하면 최종적으로 시장 주문을 하기 전에 오프셋으로 제한 주문을 재시도하는 횟수를 조정할 수 있습니다.

## 예:

- 재시도 횟수가 1이면 신호는 먼저 신호에서 수신한 가격으로 주문을 채우려고 시도합니다. 
- 채워지지 않으면 재시도는 1회만 수행되며(재시도 횟수 설정에 따라 변경 가능) 매수의 경우 매도에 오프셋을 더한 매수를 사용하거나 매도의 경우 오프셋을 뺀 매수를 사용합니다. 
- 재시도 횟수가 소진되면 시장 주문이 실행됩니다.
