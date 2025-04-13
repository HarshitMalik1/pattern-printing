#include <iostream>
using namespace std;

int main(){
    int n;
    cin>>n;

    int mid = n / 2 + 1;

    for (int i = 1; i <= n; i++) {
        for (int j = 1; j <= n; j++) {
            bool isTop = (i == 1 && j > 1);
            bool isBottom = (i == n && j < n);
            bool isLeft = (j == 1);
            bool isMidRow = (i == mid && j != 2);
            bool isRightBottom = (j == n && i >= mid && (i != n || i==n));
            if (isTop || isBottom || isLeft || isMidRow || isRightBottom)
                cout << "* ";
            else
                cout << "  ";
        }
        cout << endl;
    }

    return 0;
}
