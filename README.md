# Parcel

<br>

## setup
```
$ npm install -g parcel-bundler
$ npm init -y
```

## Publish structure
퍼블리싱 폴더 구조는 다음과 같이 구성된다.<br>
***** dist 폴더가 아닌 src 폴더에서 작업한다.

### Structure
```text
.
+-- dist                               퍼블리싱 UI 산출물 폴더  
|   +-- assets        
|   |   +-- fonts            
|   |   +-- images      
|   |   |   +-- webp         
|   |   +-- scss     
|   +-- pages   
|   |   +-- include 
|   |   +-- book_2depth 
|   |   +-- character_2depth 
|   |   +-- eggschool 
|   |   +-- hellocarrie 
|   |   +-- home 
|   |   +-- kindergarten_2depth 
|   |   +-- list-scroll 
|   |   +-- live_2depth 
|   |   +-- mymenu 
|   |   +-- nuri_2depth 
|   |   +-- papago 
|   |   +-- parents_2depth 
|   |   +-- popup 
|   |   +-- splash_loading 
|   |   +-- terms 
|   |   +-- tutorial 
|   |   +-- vod    
+-- src                                    퍼블리싱 개발 폴더
|   +-- assets               
|   |   +-- images  
|   |   |   +-- webp           
|   |   +-- scss     
|   +-- pages   
|   |   +-- include 
|   |   +-- book_2depth 
|   |   +-- character_2depth 
|   |   +-- eggschool 
|   |   +-- hellocarrie 
|   |   +-- home 
|   |   +-- kindergarten_2depth 
|   |   +-- list-scroll 
|   |   +-- live_2depth 
|   |   +-- mymenu 
|   |   +-- nuri_2depth 
|   |   +-- papago 
|   |   +-- parents_2depth 
|   |   +-- popup 
|   |   +-- splash_loading 
|   |   +-- terms 
|   |   +-- tutorial 
|   |   +-- vod                 
+-- gulpfile.js                             걸프테스크 관리
+-- index.html                              퍼블리싱 UI 산출물 및 디자인 연결 파일 
+-- package.json                            
+-- package-lock.json                       
```
<br>
