# 2023-1 Open Source Software Lab 팀 프로젝트

![](https://cdn.pixabay.com/photo/2016/01/22/08/17/banner-1155437_1280.png)

### 영화 평점 관리 CRUD 프로그램 입니다.

## Getting Started
영화 제목, 감독, 장르, 평점, 배급사에 대한 정보를 담은 구조체입니다.
```~C
typedef struct {
  char* title
  char* director
  char* genre
  float rating
  char* distributor
} Movie;
```
### Function
```int selectMenu()``` : 영화 평점 관리 프로그램에 대한 기능 메뉴를 사용자에게 보여줍니다.

```void addMovie()``` : 영화 제목, 감독, 장르, 평점, 배급사 데이터를 추가합니다. 

```void readMovie()``` : 특정 영화 제목에 해당하는 데이터를 출력합니다. 

```void allReadMovie()``` : 전체 영화 데이터를 출력합니다. 

```void updateMovie()``` : 특정 영화 제목에 대한 데이터를 수정합니다.

```void deleteMovie()``` : 특정 영화 제목을 포함한 모든 데이터를 삭제합니다.

```void allDeleteMovie()``` : 전체 영화 데이터를 삭제합니다.

```void saveFile()``` : movie.txt에 현재까지 입력한 영화 데이터를 저장합니다.

```void readFile()``` : movie.txt에 저장되어 있는 영화 데이터를 출력합니다.

```void searchMovie()``` : 특정 영화 제목을 검색하면, 그 영화에 대한 정보가 출력됩니다.

## Tech Stack
<img src="https://img.shields.io/badge/c-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white"> <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">

## Authors
* [Kim-Hyun-Seung](https://github.com/Kim-Hyun-Seung) : 한동대학교 전산전자공학부 22000202 김현승
* [22000498](https://github.com/22000498) : 한동대학교 전산전자공학부 22000498 이건요

## License
