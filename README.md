# cachgrind-result

Ir (Instruction Read):
프로그램이 실행될 때 읽힌 명령어의 횟수

I1mr (1st Level Instruction Cache Miss Read):
L1 캐시에 명령어가 없어서 메모리에서 읽어와야 할 때 발생하는 횟수

ILmr (Last Level Instruction Cache Miss Read):
L1 캐시 및 L2 캐시에서 명령어를 찾을 수 없어서 메모리에서 읽어와야 할 때 발생하는 횟수

Dr (Data Read):
데이터가 캐시로부터 읽힌 횟수

D1mr (1st Level Data Cache Miss Read):
L1 데이터 캐시에 데이터가 없어서 메모리에서 읽어와야 할 때 발생하는 횟수

DLmr (Last Level Data Cache Miss Read):
L1 데이터 캐시 및 L2 데이터 캐시에서 데이터를 찾을 수 없어서 메모리에서 읽어와야 할 때 발생하는 횟수

Dw (Data Write):
프로그램이 실행될 때 쓰여진 데이터의 수를 나타냅니다.
데이터가 캐시에 기록된 횟수를 추적합니다.

D1mw (1st Level Data Cache Miss Write):
L1 데이터 캐시에 공간이 부족해서 데이터를 메모리로 기록해야 할 때 발생하는 횟수

DLmw (Last Level Data Cache Miss Write):
L1 데이터 캐시 및 L2 데이터 캐시에서 공간이 부족해서 데이터를 메모리로 기록해야 할 때 발생하는 횟수
