Отчёт о тестировании Money Transfer

Краткое описание
07.07.20г. было проведено тестирование приложения Money Transfer.
При пополнении банковского счета VIP-клиента, баланс счета должен увеличиваться.
Результат - увеличенная сумма счета.

Описание тестов
Проводилось позитивное, функциональное тестирование.
В Java было создано приложение, позволяющее воспроизвести ситуацию пополнения баланса.
В качестве тестовых данных использовались входные данные
https://github.com/netology-code/javaqa-homeworks/tree/master/programming

В результате тестирования
тест показал отрицательную сумму на балансе, после пополнения
создан баг-репорт https://github.com/Stor-Nat/homework3-2.1/issues/1

Тестирование производилось в следующем окружении:
OC - macOS Catalina, версия 10.15.5, 64-бит разрядность
Java - openjdk version "11.0.7"
