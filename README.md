# Embedded-Study

Bit 연산
unsigned short 2Byte를 받으면
그 중 1의 갯수를 출력하는 코드
4Byte
32비트니까 8번 돌자

count = count 
+bit_count_map_(n)[(u32Input>>(8*i))&0x??]
n이 4이면 F
n이 8이면 FF
n이 16이면 FFFF
n이 32면 FFFFFFFF
