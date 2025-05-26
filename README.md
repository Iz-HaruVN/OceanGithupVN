**New year-New world**
``` cpp
std::string gt="Hello,new world!";
printf ("%s\n",gt.c_str());
```
[![stalk counter](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Flqdoj.edu.vn%2Fuser%2FSBD_01_Lam&countColor=%232ccce4)](https://visitorbadge.io/status?path=https%3A%2F%2Flqdoj.edu.vn%2Fuser%2FSBD_01_Lam)
*Life is suffering...,and suffering is C++*
??? "about me:"
    *********************************
    * Ngày bước chân vào con đường tà đạo: 5/1/2023.
    * "Thành thạo" c++, powerpoint, capcut, alight motion,...
    * *Người chơi **[Blue][1] Archive** bình tĩnh nhất...*
    * *Don't be sad that it's **over**, be happy because it **happened**.*
    * *I never quit **minecraft**, I just take a really long break from it.*
    **links:**
    > [minecraft][2] (Ai generate)
    > [facebook][3]
    > [CSL::OJ][4]
    > [GitHup][5] (chưa bt dùng🐳)
    > [tapy.me][6]
   
!!! note "CSES - Weird Algorithm"
    [link bài:][8]
    Đây có thể gọi là **800đ** free
    **Thuật toán**:
    >nếu ```x%2!=0``` thì: ```x=3x+1```
    >ngược lại: ```x/=2```
    ??? note "Code c++"
        ``` cpp
        #include <bits/stdc++.h>
        #define fi first
        #define se second
        typedef long long ll;
        using namespace std;
        ll n;
        signed main()
        {
            scanf("%lld", &n);
            while(n > 1){
                printf("%lld ", n);
                if(n&1) n = 3*n+1;
                else    n >>= 1;
            }
            printf("1\n");
        }
        ```
    Tôi sẽ tìm và cập nhật các bài *"điểm free"* sau
> Reached **30.000** points in 25/11/2024
> **200th** problem was solved in 27/11/2024
> *just don't learn cpp, trust me!*


  


  [1]: https://bluearchive.nexon.com/home
  [2]: https://oasis.decart.ai/starting-point
  [3]: https://www.facebook.com/profile.php?id=61567310324386
  [4]: http://csloj.ddns.net/user/5948
  [5]: https://github.com/OceanGithupVN
  [6]: https://tapy.me/oceanmcvnoffical
  [8]: https://lqdoj.edu.vn/problem/cses1068
