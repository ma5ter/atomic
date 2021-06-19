# atomic
Этот файл для того, кто будет смотреть мое решение тестового задания

1. Благодарнось
  Когда я увидел задание, я толком не понял даже, чего от меня хотят. Начал гуглить, изучать разные реализации стеков, что такое атомики, с чем их едят, и примерно понял в чем, состоит смысл задания. В процессе я очень увлекся задачей и мне понравилось ею заниматься. Узнал много нового и полезного, я теперь как человек с молотком, который во всем видит гвозди, рыскаю по своим проектам и думаю, куда бы атомики применить=) Спасибо вам за такую интересную задачу.

2. Описание
  Так как с атомиками я столкнулся впервые, взял за основу самый простой вариант реализации стека на массиве. Сделал простые потоконебезопасные функции для стека (файл stk_utils.c), написал несколько тестов, которые демонстрируют проблему при записи и чтении несколькими потоками, и написал функции с использованием атомиков(файл stk_utils_atomic.c). Во все функции добавил приостановки работы потока для проявления потоконебезопасности. Постарался сделать поясняющие комментарии в коде.

