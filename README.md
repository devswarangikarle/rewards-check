# rewards-check
Newton School is hosting a programming competition with n participants. The organizer, Newton, plans to reward all participants with pens and notebooks. Newton has exactly m pens and k notebooks. Your task is to determine whether Newton can distribute the rewards to all participants.

n, m, k = map(int, input().split())

if m >= n and k >= n:
    print("YES")
else:
    print("NO")
