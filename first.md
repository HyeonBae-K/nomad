# Variable
1. 숫자
1.1 int(정수형)
1.2 float(실수형))
2. 문자열(String)
> "" or '' 로 둘러 싸여있어야함
3. boolean = True(1) or False(0)
4. None = 존재하지 않음 (java의 null과 비슷한 개념)
5. 변수 이름을 정할때는 '_'로 띄어쓰기를 한다.

# List
1. List = [] - mutable sequence(변경가능한 시퀀스)
> 한번에 많은 값을 저장하고 싶을때 활용. 많은 value를 열거
days ['mon', 'tue', 'wed','thur', 'fri']
print('mon' in days)  -> true
print(len(days)) -> 5
print(days) / days.append('sat') / print(days) -> sat추가된 리스트 출력
days.reverse() / print(days) -> 역방향 리스트 출력   

2. tuple = () - immutable sequence(변경불가능한 시퀀스)

3. dictionary = {key:value,}
> dict = {"name" = "hb", "age":25, "korean":True, "fav_food":['kimchi','sashimi']}
print(dict) -> dict 전체 출력
print(dict["name"]) -> hb 출력
dict["handsome"] = True -> dict에 추가

# def 사용자 정의 함수
```
def say_hello():
  print("hello")
```
> 들여쓰기로 함수의 body르 표시