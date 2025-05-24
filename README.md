# mini-projek-
  #include <stdio.h>

int main () {
    int i;
    int jawaban1, jawaban2, jawaban3, jawaban4, jawaban5, jawaban6, jawaban7, jawaban8, jawaban9, jawaban10;
    int point[10] = {0};  
    int total = 0;

    printf("welcome to the game\n\n");
    printf("> press 7 to start the game\n");
    printf("> press 0 to quit the game\n");

    scanf("%d", &i);

    if(i==7)
    {
        printf("the game has start\n\n");
    }
    else if(i==0)
    {
        printf("the game has end\n\n");
        return 0;
    }
    else
    {
        printf("invalid\n\n");
        return 0;
    }

    // Soal 1
    printf("A. Perintah if digunakan untuk?\n\n");
    printf("1) Menyimpan data\n");
    printf("2) Membuat pengulangan\n");
    printf("3) Mengecek kondisi\n");
    printf("4) Menampilkan output\n");

    printf("enter your answer : ");
    scanf("%d", &jawaban1);

    if(jawaban1==3)
    {
        printf("correct answer\n");
        point[0] = 5;
    }
    else
    {
        printf("wrong answer\n");
    }
    printf("you have score %d point\n", point[0]);

    // Soal 2
    printf("B. Komentar dalam kode digunakan untuk?\n\n");
    printf("1) Menjalankan perintah\n");
    printf("2) Menyimpan hasil program\n");
    printf("3) Memberi penjelasan kode\n");
    printf("4) Menambah error\n");

    printf("enter your answer : ");
    scanf("%d", &jawaban2);

    if(jawaban2==3)
    {
        printf("correct answer\n");
        point[1] = 5;
    }
    else
    {
        printf("wrong answer\n");
    }
    printf("you have score %d point\n", point[1]);

    // Soal 3
    printf("C. Yang termasuk tipe data adalah?\n\n");
    printf("1) for, while, do\n");
    printf("2) int, float, char\n");
    printf("3) scanf, printf, gets\n");
    printf("4) main, void, return\n");

    printf("enter your answer : ");
    scanf("%d", &jawaban3);

    if(jawaban3==2)
    {
        printf("correct answer\n");
        point[2] = 5;
    }
    else
    {
        printf("wrong answer\n");
    }
    printf("you have score %d point\n", point[2]);

    // Soal 4
    printf("D. Apa fungsi dari perulangan (loop)\n\n");
    printf("1) Menyimpan data\n");
    printf("2) Membandingkan dua nilai\n");
    printf("3) Menjalankan kode berulang kali\n");
    printf("4) Menghentikan program\n");

    printf("enter your answer : ");
    scanf("%d", &jawaban4);

    if(jawaban4==3)
    {
        printf("correct answer\n");
        point[3] = 5;
    }
    else
    {
        printf("wrong answer\n");
    }
    printf("you have score %d point\n", point[3]);

    // Soal 5
    printf("E. Apa itu variabel dalam pemrograman?\n\n");
    printf("1) Tempat untuk mencetak data\n");
    printf("2) Tempat untuk menyimpan data\n");
    printf("3) Perintah untuk mengulang kode\n");
    printf("4) Tipe data angka\n");

    printf("enter your answer : ");
    scanf("%d", &jawaban5);

    if(jawaban5==2)
    {
        printf("correct answer\n");
        point[4] = 5;
    }
    else
    {
        printf("wrong answer\n");
    }
    printf("you have score %d point\n", point[4]);

    // Soal 6
    printf("F. Apa itu sintaks dalam pemrograman?\n\n");
    printf("1) Alur program\n");
    printf("2) Aturan penulisan kode\n");
    printf("3) Nama variabel\n");
    printf("4) Jenis fungsi\n");

    printf("enter your answer : ");
    scanf("%d", &jawaban6);

    if(jawaban6==2)
    {
        printf("correct answer\n");
        point[5] = 5;
    }
    else
    {
        printf("wrong answer\n");
    }
    printf("you have score %d point\n", point[5]);

    // Soal 7
    printf("G. Apa itu bug dalam pemrograman?\n\n");
    printf("1) Jenis data\n");
    printf("2) Kesalahan dalam kode\n");
    printf("3) Operator logika\n");
    printf("4) Nama fungsi\n");

    printf("enter your answer : ");
    scanf("%d", &jawaban7);

    if(jawaban7==2)
    {
        printf("correct answer\n");
        point[6] = 5;
    }
    else
    {
        printf("wrong answer\n");
    }
    printf("you have score %d point\n", point[6]);

    // Soal 8
    printf("H. Fungsi printf dalam bahasa C digunakan untuk?\n\n");
    printf("1) Mengulang perintah\n");
    printf("2) Menginput data\n");
    printf("3) Menampilkan output\n");
    printf("4) Menyimpan data\n");

    printf("enter your answer : ");
    scanf("%d", &jawaban8);

    if(jawaban8==3)
    {
        printf("correct answer\n");
        point[7] = 5;
    }
    else
    {
        printf("wrong answer\n");
    }
    printf("you have score %d point\n", point[7]);

    // Soal 9
    printf("I. Apa hasil dari 5 > 3 dalam bahasa pemrograman?\n\n");
    printf("1) false\n");
    printf("2) eror\n");
    printf("3) true\n");
    printf("4) 53\n");

    printf("enter your answer : ");
    scanf("%d", &jawaban9);

    if(jawaban9==3)
    {
        printf("correct answer\n");
        point[8] = 5;
    }
    else
    {
        printf("wrong answer\n");
    }
    printf("you have score %d point\n", point[8]);

    // Soal 10
    printf("J. Perintah while digunakan untuk?\n\n");
    printf("1) Menginput data\n");
    printf("2) Menyimpan nilai\n");
    printf("3) Menampilkan hasil\n");
    printf("4) Melakukan perulangan selama kondisi\n");

    printf("enter your answer : ");
    scanf("%d", &jawaban10);

    if(jawaban10==4)
    {
        printf("correct answer\n");
        point[9] = 5;
    }
    else
    {
        printf("wrong answer\n");
    }
    printf("you have score %d point\n", point[9]);

    // Hitung total
    for(int j = 0; j < 10; j++) {
        total += point[j];
    }

    printf("\n=================================\n");
    printf("Total poin yang kamu dapatkan: %d dari 50\n", total);
    printf("=================================\n");

    return 0;
}
