# -print ('입력')
# n, m = list(map(int, input('작업 수 / 작업 번호  : ').split()))
# priority = list(map(int,input('작업 우선순위 : ').split()))

# arrangement = list(range(len(priority)))
# arrangement[m] = 'goal'

# progress_time = 0

# while True:
#        if priority[0] == max(priority):
#           progress_time += 1
#            if arrangement[0] == 'goal':
#                print('출력')
#                print(progress_time,'분')
#                break
#            else:
#                priority.pop(0)
#                arrangement.pop(0)
                
#        else:
#             priority.append(priority.pop(0))
#             arrangement.append(arrangement.pop(0))
