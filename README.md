# R-for-Data-Science
R for Data


참조 사이트
https://kuduz.tistory.com/1077

참조 코드 
1. R 설치
2. 콘솔 상에서 install.packages('ggplot2')
3. library('ggplot2')
4. ggplot(data=mtcars, aes(x=disp, y=mpg)) + geom_point(aes(size=hp, color=wt))


출처: https://kuduz.tistory.com/1077 [kini'n creations]


예시 화면
library('ggplot2') 실행 후
> ggplot(data=economics, aes(x=date, y=unemploy)) + geom_bar(stat='identity', color='#FFAA00', lwd=1) + geom_hline(yintercept=mean(economics$unemploy), linetype='dashed')

* 모든 것은 R Console 상에서 




