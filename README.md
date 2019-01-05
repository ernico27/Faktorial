# Faktorial

    #include<iostream>
    using namespace std;
    int main()
    {
    int b,c;
    cout << "\t\t ================== \n";
    cout << "\t\t Program Faktorial \n";
    cout << "\t\t ================== \n";
    cout << "\t\t Masukkan bilangan yang ingin di faktorkan : "; cin >> b;
    c=b;
    for(int i=1;i<=b;i++){
        cout << i;
        if(i==b){
            cout << " = ";
        }else{
        cout << "*";}
    }
    for(int i=1;b>i;){
        b=b-1;
        c=c*b;
    }
    cout << c;
    return 0;
    }

## Hasilnya

![img](https://github.com/ernico27/Faktorial/blob/master/faktorial.png?raw=true)
