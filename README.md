print("How long should your Countdown work:")
time = int(input())
Time = [1]



for seconds in range(0, int(time), 1):
    while Time[time - (time - seconds)] < time:
        Time.append((time + 1) - (time - seconds))
        print((time + 1) - (time - seconds))
