# **Смещение покупки**

## Назначение: 

- Этот параметр позволяет вам регулировать цену покупки с помощью фиксированного смещения. Смещение покупки будет добавлено к выбранной цене покупки (может быть Ask, Bid или Mark. По умолчанию = Ask).

- Сделка будет изначально размещена по цене покупки, полученной в сигнале. Если она не будет выполнена в течение 5 секунд, то повторная попытка покупки будет совершена по цене покупки (может быть Ask, Bid или Mark. По умолчанию = Ask) плюс смещение (по умолчанию 0,05). 

## Пример:

- Сигнал покупки $100 с Bid на $99 и Ask на $101. Если первоначальный лимитный ордер на покупку не будет исполнен на $100, то повторная попытка будет совершена на $101 + 0,05 = $101,05.
