n = int(input())
year = 2007
month = 2
day = 27

for i in range(n):
    userYear, userMonth, userDay = [int(i) for i in input().split()]

    if abs(userYear - year) > 18:
        print("Yes")
        continue
    elif abs(userYear - year) < 18:
        print("No")
        continue

    else:
        if userMonth < month:
            print("Yes")
            continue
        elif userMonth > month:
            print("No")
            continue
        else:
            if userDay <= day:
                print("Yes")
                continue
            elif userDay > day:
                print("No")
                continue
