# 파이썬을 이용한 웹 크롤링과 스크레이핑

『파이썬을 이용한 웹 크롤링과 스크레이핑』의 예제 파일입니다.

# Wiki Dataset Download

 *   https://archive.org/download/kowiki-20170801 
 1.   wget https://archive.org/download/kowiki-20170801/kowiki-20170801-pages-articles.xml.bz2 
 2.  bzcat kowiki-20170801-pages-articles.xml.bz2 
 3.  wget https://github.com/attardi/wikiextractor/blob/master/WikiExtractor.py
 4.  python WikiExtractor.py  --no-templates -o articles -b 100M  kowiki-20170801-pages-articles.xml
