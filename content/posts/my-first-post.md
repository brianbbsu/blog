---
title: "這是一個測試用的文章"
date: 2019-02-27
tags: 
  - Test
categories:
  - 廢文
slug: hello-world
---

這是一篇用來測試部落格系統的文章。

This is an article to test the blog system.

# This is a Test

## First, let's test some English

So I'm just typing some random stuff.

![avatar](https://brian.su/avatar.jpg)

## 第二，來測試一下中文吧

希望這段中文能夠被好好的顯示出來，不會爛掉

## Third, let's test some markdown stuff

- Test 1
- Test 2
- 測試 3
- $X^2$
- this is inline `for(int i = 0;i < n;i ++)` code
- $$x = {-b \pm \sqrt{b^2-4ac} \over 2a}$$
- list
  - list 2
  - list 3

| 1 | 2 | 3 |
|---|---|---|
|123|456|789|

## 第三，來測試點程式吧

``` cpp
#include<bits/stdc++.h>
using namespace std;

int main(){
    cout<<"123"<<endl;
    return 0;
}
```

``` bash
set -e
echo test | grep "t"
```

``` python
x = input()
print(int(x) * 2)
```

``` text
this is just some text
test123 test456
```

``` cpp
//{
#include<bits/stdc++.h>
using namespace std;
typedef long long ll;
typedef double lf;
typedef pair<ll,ll> ii;
#define REP(i,n) for(ll i=0;i<n;i++)
#define REP1(i,n) for(ll i=1;i<=n;i++)
#define FILL(i,n) memset(i,n,sizeof i)
#define X first
#define Y second
#define SZ(_a) (int)_a.size()
#define ALL(_a) _a.begin(),_a.end()
#define pb push_back
#ifdef brian
#define debug(...) do{\
    fprintf(stderr,"%s - %d (%s) = ",__PRETTY_FUNCTION__,__LINE__,#__VA_ARGS__);\
    _do(__VA_ARGS__);\
}while(0)
template<typename T>void _do(T &&_x){cerr<<_x<<endl;}
template<typename T,typename ...S> void _do(T &&_x,S &&..._t){cerr<<_x<<" ,";_do(_t...);}
template<typename _a,typename _b> ostream& operator << (ostream &_s,const pair<_a,_b> &_p){return _s<<"("<<_p.X<<","<<_p.Y<<")";}
template<typename It> ostream& _OUTC(ostream &_s,It _ita,It _itb)
{
    _s<<"{";
    for(It _it=_ita;_it!=_itb;_it++)
    {
        _s<<(_it==_ita?"":",")<<*_it;
    }
    _s<<"}";
    return _s;
}
template<typename _a> ostream &operator << (ostream &_s,vector<_a> &_c){return _OUTC(_s,ALL(_c));}
template<typename _a> ostream &operator << (ostream &_s,set<_a> &_c){return _OUTC(_s,ALL(_c));}
template<typename _a,typename _b> ostream &operator << (ostream &_s,map<_a,_b> &_c){return _OUTC(_s,ALL(_c));}
template<typename _t> void pary(_t _a,_t _b){_OUTC(cerr,_a,_b);cerr<<endl;}
#define IOS()
#else
#define debug(...)
#define pary(...)
#define endl '\n'
#define IOS() ios_base::sync_with_stdio(0);cin.tie(0);
#endif // brian
//}


const ll MAXn=1e5+5,MAXlg=__lg(MAXn)+2;
const ll MOD=1000000007;
const ll INF=ll(1e15);

int main()
{
    IOS();

}
```