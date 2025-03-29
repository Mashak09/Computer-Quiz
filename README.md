print('Nando Computer Quiz'l Nindo Swagatha!')

playing = input('Nikk kaliko manas unda? (yes/no) ')

if playing.lower() != 'yes':  
    quit()

print('Let's kalika!')
score = 0

answer = input('Nindo abbare per endro? ')
if answer.lower() == 'farooq':
    print('Sari')
    score += 1
else:
    print('Thappu')

answer = input('Nindo ummaro per endro? ')
if answer.lower() == 'zubaida':
    print('Sari')
    score += 1
else:
    print('Thappu')

answer = input('Nindo sister ro per endro? ')
if answer.lower() == 'mariyam':  
    print('Sari')
    score += 1
else:
    print('Thappu')

print('You got ' + str(score) + ' questions correct.')
print('You got ' + str(round((score / 3) * 100, 2)) + '% score.')

