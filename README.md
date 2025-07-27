# codeforce
t = int(input())
for _ in range(t):
    n = int(input())
    b = list(map(int, input().split()))
    possible = True
    for i in range(1, n):
        if b[i] < b[i-1]:
            possible = False
            break
    print("YES" if possible else "NO")
tell what is wrong with code
