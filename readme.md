# 파이썬을 이용한 웹 크롤링과 스크레이핑

『파이썬을 이용한 웹 크롤링과 스크레이핑』의 예제 파일입니다.

# Wiki Dataset Download

 *   https://archive.org/download/kowiki-20170801 
 1.   wget https://archive.org/download/kowiki-20170801/kowiki-20170801-pages-articles.xml.bz2 
 2.  bzcat kowiki-20170801-pages-articles.xml.bz2 
 3.  위키 추출기 :   https://github.com/attardi/wikiextractor    
   3.1  wget https://github.com/attardi/wikiextractor/blob/master/WikiExtractor.py        
   3.2  python WikiExtractor.py  --no-templates -o articles -b 100M  kowiki-20170801-pages-articles.xml
 4.  pip install konlpy 
 5.  pip install jpype1 
 6.  python chapter_5/word_frequency.py

#  API 로 데이터 수집하고 활용하기 
 1. 트위터에서 데이터 수집하기 
 
 2. 유튜브에서 동영상 정보 수집하기 
 
 
 3. 시계열 데이터 수집하고 활용하기 
 
 4. Open Data 수집과 활용 : PDF , Linked Open  Data 
 
 5. 웹페이지 자동 조작 
   5.1 Selenium 과 PhantomJS 설치   
     - pip install selenum==3.0    
     - wget https://bitbucket.org/ariya/phantomjs/downloads/phantomjs-1.9.8-linux-x86_64.tar.bz2   
     
     - sudo apt-get install -y fonts-nanum* 
     
   5.2 RSS 피드 생성하기   
     - pip install feedgenerator 
   
   
   
 
 
 
 
