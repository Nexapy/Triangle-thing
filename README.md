#Triangle-thing

def triangle(f):
    i = f
    if f > 1 and f < 39:
        print(' '*i+' ','/\\')
        for cf in range(f):
            print(' '*i,'/','__'*cf,'\\')
            i = i-1
    else:
        print('Error. the number is either too big or either too small.')
for i in range(100):
    fl = int(input('Floors? #'))
    triangle(fl)
    print('')
    print('')
