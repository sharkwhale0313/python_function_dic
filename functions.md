## 기본 함수

- ord(x) : to ascii (아스키코드)
- chr(x) : to charactor
- int(x) : to int (정수형), float to int 시에는 소수점 아래 삭제
- round(x) : 반올림( 0.5 이하는 내림, 0.5 초과는 올림 )
- str(x) : to string (문자열)
- list(x) : to list (리스트)
- len(li) : list length (길이, 사이즈, 문자열 길이)
- text.split(',') : text 를 ',' 기준으로 나눠서 list 형태로 리턴
- strip(str) : str의 앞,뒤 공백문자 제거. whitespace

> list 관련 함수

- list.index( value ) : 값을 이용하여 위치를 찾는 기능
- list.extend( [value1, value2] ) : 리스트 뒤에 값을 추가 (‘+’연산자 보다 성능이 좋음)
- list.insert( index, value ) : 원하는 위치에 값을 추가
- list.sort( ) : 값을 순서대로 정렬
- list.reverse( ) : 값을 역순으로 정렬
- " ".join(list) : "" 안에있는 문자를 사이에 끼워서 리스트 요소들을 str로 형변환

## import re

- findall(regex, string) : regex→정규표현식을 기준으로 문자열 쪼갬

## import numpy

- abs(x) : 절대값 절댓값
- sign(x) : 부호 ( 음수면 -1, 양수면 1, 0이면 0 return)
- asarray(rows,dtype='float32')
- matmul(x, weight) : 행렬 곱셈
- mean(x) : 평균
- prod(x) : 행렬 곱
- zeros

## import math
- ceil(x) : 천장함수. 소수점 올림
- floor(x) : 바닥함수. 소수점 내림

## import tensorflow

## import pandas

## import os

- os.path.join(path1, path2)
: path1 과 path2 를 합쳐줌. housing_path + 'housing.csv'
- path.isdir(dir_name)
: dir_name라는 directory가 존재하는지 반환
- path.abspath(file_name) : 절대경로 리턴
- path.realpath(file_name) : 상대경로 리턴
- getcwd() : 현재 폴더 경로 리턴
- path.dirname(file_name) : 파일의 폴더 경로 리턴
- makedirs('datasets/housing')
: datasets 아래에 housing이라는 diretory를 만듦
- mkdir(dir_name) : 현재 경로에 dir_name 이라는 directory 생성
- os.listdir(os.getcwd()) : 현재 폴더에 있는 파일 리스트 리턴
- os.chdir(path) : 작업 디렉토리 변경
