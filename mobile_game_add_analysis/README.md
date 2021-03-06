# ?????? ??????? ??????? ? ????????? ????

## ????? ??????????

????????? ???? ???????????? ?? ?????? ???????. ???? ????????? ???????? ???????:
- int ? ????????????? ???????; 
- banner ? ?????????????? ??????, ????? ????? ?????? ???? ???? ??????; 
- rv ? ?????, ??????? ???? ??????? ?? ??????? ? ?? ???????? ???????? ??????? ??? ??. ???????. 

?????????? ? ?????? ?????? ???????????? ? ????????? ? ???????? ????? ?? ??????, ?????? ?????????? ???????, ????????? ???? ?? ??????? ??? ????? ? ??.

eCPM ? ????? ?? 1000 ??????? ???????.

## ?????? ????????????

???????? ???????????? ??????? ??????? ? ????? ?????? ??? ?????????? eCPM ? ??????????? ?? ????????? (??????) ?????, ?????? ?? ? ?????? ??????????.

???????? ?? ???????:
1. ??? ??????? ??????? ???????:
    - ????????? ????????????? ??????? eCPM-?? ??????
    - ?????????? ??????? eCPM-? ?? ???????, ??????? ??
    - ?????????? ????????? ?????? ?? ???????, ??????? ??
2. ?????? ?????????????? ?????????? ??? ?.1b. ???????? ??????? ? ??????? ???.
3. ??????? ?????????? ? ????? ?? ????????????.

?????????????? ??????:\
???????????:
- ????? ??????? ??????? ???????? ?????????? ? ?????? ?????
- ??????? ?? eCPM ?? ??????? ???
  
## ??????????????? ?????????? ? ????????

? ??????? "us events ad_revenue filtered 03.02-07.02.csv" ?????????? ?????????? ? ??????? ??????? ??? ?????? ???

- profile_id ? id ?????
- event_json ???????? ?????? ? ??????? ?????? ???????:
    - ad_type ? ?????? ??????? (int, banner ??? rv)
    - placement ? ?????/??? ??? ????? ??????? ? ????
    - view_index ? ????? ?????? ??????????? ??????? ??????? ??? ????? (??  ?????????????? ??? ????????)
    - revenue ? ????? ?? ??????????? ?????? ??????? (eCPM = revenue * 1000)
    - ads_ltv ? ??????????????? ????? ?? ???????, ????? ????? ???? revenue ?????
    - network_name ? ????????? ????, ?? ??????? ??? ?????
    
## ?????????? ? ???????? ???????

**Python Version:** 3.9.12\
**Packages:** pandas, numpy, scipy, statsmodels, matplotlib, seaborn, json


## ??????????

? ???? ?????? ???? ??????? ?????? ? ?????? ??????? ???? ????? ????????????? ????????? ????.

? ???????? ?????????? ??????????? ????? ??????? eCPM, ???????? ????????????? (????????) ? ??????? ?? ??? ??????? ?? ????? ???????.

??????? ????????, ??? ???? ???????? ????????? ????? ????????????? ????????? Samsung ? 76% ???? ????????? ??????????? ????? ?????????????.\
??????? ????? ????????????? ?????? ? ???? ? ????????? ? 92.4%, ?? ???????? ?????????? ?????? 7.6% ?????????.
?????????? ????? ???? ?? ?????? ??????????? ?????? ?? ? 44% ????????????? ????? ??. 

??????? ????? ????? ??????? eCPM ? ??????? ??. ???, ??? ???? ???? ????? ??????? ??????? eCPM ????????????? ??????? ???? ??? ??????????? ?????? ??.\
??????? ????? 11, 10 ? 9 ???????? ????? ?????, ?? ????? ? ???????????? ???????, ??? ?????? ?? ???? ??????? ????????????? ??????? ????? ??????? eCPM ??? ????????? ??????.

????? ??????? ????????, ??? ?????? ?? ???? ??????? ????? ?? ?????????? ???????, ??? ?????????? ????? 3% ????????????? ? ??? ?????? ????????? ??????? ??? ?????????? ?? ????? 2% ???????.\
???? ??????????? ???? ?????? ?? ??????? ?????????????? ?????? ?? ??????? ??????????, ??, ????????, ????? ????? ?????????? ?? ?????????.

??????????? ????????? ????? ????? ???????? ? ??????? eCPM. ???, ???????????? ????? ????? ??????? ??????? eCPm ?? ???? ???? ??????????, ?? ???? ?????? ???? ????? ??????? ?????????? ?????? ??????? ? ???? ?????? ? ????????? ?? ????? ?????????? ????????.

?????????? ?????????? ? ???????? ?? ??, ??? ???????? ????? ???????????? ???????? ???????? ??????? ???????????? ?? ????? ???? ? 95% ???? ????????? ???????, ??? ?????????? ???? 25.4% ???????.\
?????? ???? ????? ???????? ????????????? ???????, ??????? ????? ??????? eCPM ? 39 ??? ???? ??? ? ????????.\
???????? ?? ??, ??? ??? ??????? ?????????? ???? 4.4% ?? ???? ????????? ???????, ??? ???????? 57% ???????.

?????-??????? ???????? ????? ??????? ??????? eCPM, ?? ???????????? ?????. ??-?? ?????? ????? ??????????? ?? ??????? ???????? ????????????? ???????? ?????????? ??? ????????? eCPM ?? ???????.

?????? ?? ????????? ?????? ??? ????? ??????, ??? ??? ??????? ???????? ??????????, ????????? 17.6% ??????? ??? ???, ??? ????????? ????? ??????? ????? 1% (0.8%).\
????????, ????? ????? ???????????????????? ? ??????????? ????? ?????????? ?????-??????? ??????????????.\
???? ?????????? ????????? ???????? ??? ?????????? ????????:
- ????? ?????? ?????????? ?????-??????? ?????? ????????????? ??????? 
- ????? ????????? ?????? ?????????? ?? ???????? ?????-???????
????????.

?? ????????? ?????? ? ???? ????????? ???????????, ??? ? ?????-??????? ????? ???? ????????????? ????? ????? ??????? ????????. ??? ?????????? ???????????? ???????????? ?????-??????? ? ???????? ?? ?????????? ? ?? ??????? ?? ????? ?????????? ??????.