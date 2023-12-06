#include <stdio.h>

int main() {
    int toplam = 0;

    // 1 ile 50 arasındaki tek sayıları topla
    for (int i = 1; i <= 50; i += 2) {
        toplam += i;
    }

    // Toplamı ekrana yazdır
    printf("1 ile 50 arasindaki tek sayilarin toplami: %d\n", toplam);

    return 0;
}
