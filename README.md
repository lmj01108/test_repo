# test_repo
for testing

def maximum(a,b,c):
	if a>b:
		if a>c:
			return a
		else:
			return c
	else:
		if b>c:
			return b
		else:
			return c
	
a,b,c = input().split()#스페이스기준으로 문자열을 찢어서 각 요소의 리스트를 만들 수 있음
a,b,c = int(a), int(b), int(c)

# call the maximum function to find the maximum number among a,b,c
# and, print that maximum
print(maximum(a,b,c))

# 급하게 추가적으로 수정해야할 내용이 생각나서 다시 중복으로 pull request요청
