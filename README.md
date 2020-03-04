#include <stdio.h>
#include <stdlib.h>

int main()
{
    /*int a, b;
    scanf("%d", &a);
    scanf("%d", &b);

    if(abs(a)>abs(b))
        printf("%d",a);
    else
        printf("%d%",b);*/

   /* int figura;
    printf("Podaj figure: 1-trojkat, 2-kwadrat, 3-prostokat");
    scanf("%d", &figura);
    int wys,podst;
    if(figura == 1)
    {
        printf("Podaj wysokosc");
        scanf("%d", &wys);
        printf("Podaj podstawe");
        scanf("%d", &podst);
        printf("Pole to:");
        printf("%d",(wys*podst)/2);
    }
    else if(figura == 2)
    {
        printf("Podaj bok");
        scanf("%d", &wys);
        printf("Pole to:");
        printf("%d", wys*wys);
    }
    else if(figura == 3)
    {
        printf("Podaj pierwszy bok");
        scanf("%d", &wys);
        printf("Podaj drugi bok");
        scanf("%d", &podst);
        printf("Pole to:");
        printf("%d",wys*podst);
    }*/


    /*float a,b,c,d,e,f;*/


    /*if(w!=0)
    {
        printf("1 rozw: x=%f, y=%f",wx/w,wy/w);
    }
    else
    {
        if(xw==0 && wy==0)
        {
            printf("Nieskonczenie wiele rozw");
        else
        {
            printf("Brak rozw");
        }
    }*/

    /*int n, m;
    scanf("%d", &n);
    scanf("%d", &m);
    for(int i = n; i < m; i+=n)
    {
        printf("%d\n", i);
    }*/

    /*int n, m, k;
    scanf("%d", &m);
    scanf("%d", &n);
    scanf("%d", &k);
    for(int i = n; (i > m) && (i < k); i+=n)
    {
        printf("%d\n", i);
    }*/

    /*int n;
    int suma=0;
    int wynik=0 ;
    scanf("%d", &n);
    for(int i = 0; i<=n; i++)
    {
        wynik = i*i;
        suma = suma + wynik;
    }
    printf("%d", suma+1);*/

    /*int n,m;
    int suma=1;
    int wynik ;
    scanf("%d", &n);
    scanf("%d", &m);
    for(int i = n; i<=m; i++)
    {
        wynik = i;
        suma = suma * wynik;
    }
    printf("%d", suma);*/

    int n, m;
    int dzielnik = 1;
    scanf("%d", &n);
    scanf("%d", &m);
    for(int i = 1; i < n; i++)
    {
        if((n%i==0)&&(m%i==0))
            dzielnik = i;
    }
    printf("%d", dzielnik);

    return 0;

}

