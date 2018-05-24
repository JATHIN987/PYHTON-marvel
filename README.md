# PYHTON-marvel
import random

items = ['IRON_MAN', 'SCARLET_WITCH', 'HULK', 'LOKI', 'THOR', 'GAMORA','DOCTOR_STRANGE', 'CAPTAIN_AMERICA']
items1=items
IRON_MAN1=7
SCARLET_WITCH1=6
HULK1=9
LOKI1=8
THOR1=8
GAMORA1=7
DOCTOR_STRANGE1=6
CAPTAIN_AMERICA1=8

def shuffle(items1):
    random.shuffle(items1)
    character1=items1.pop()
    random.shuffle(items1)
    character2=items1.pop()
    print('CHARACTER1={0}\nCHARACTER2={1}'.format(character1,character2))

items = ['IRON_MAN', 'SCARLET_WITCH', 'HULK', 'LOKI', 'THOR', 'GAMORA','DOCTOR_STRANGE', 'CAPTAIN_AMERICA']
print('THE AVAILABLE CHARACTERS IN THE GAME ARE')
print(items)
print('The  assumed ratings of the superheroes are')
print('IRON_MAN1=7\nSCARLET_WITCH1=6\nHULK1=9\nLOKI1=8\nTHOR1=8\nGAMORA1=7\nDOCTOR_STRANGE1=6\nCAPTAIN_AMERICA1=8')
shuffle(items1)
print('NOW SELECT CHARACTER3 AND CHARACTER4')
i=int(input('Enter the serial number of the CHARACTER3 :'))
j=int(input('Enter the serial number of the CHARACTER4 :'))
c1=int(input('Enter the rating of CHARACTER1 :'))
c2=int(input('Enter the rating of CHARACTER2 :'))
character3=items[i]
if character3== 'IRON_MAN':
    c3=IRON_MAN1
elif character3== 'SCARLET_WITCH':
    c3=SCARLET_WITCH1
elif character3== 'HULK':
    c3=HULK1
elif character3== 'LOKI':
    c3=LOKI1
elif character3== 'THOR':
    c3=THOR1
elif character3== 'GAMORA':
    c3=GAMORA1
elif character3== 'DOCTOR_STRANGE':
    c3=DOCTOR_STRANGE1
elif character3=='CAPTAIN_AMERICA':
    c3=CAPTAIN_AMERICA1

character4=items[j]
if character4== 'IRON_MAN':
    c4=IRON_MAN1
elif character4== 'SCARLET_WITCH':
    c4=SCARLET_WITCH1
elif character4== 'HULK':
    c4=HULK1
elif character4== 'LOKI':
    c4=LOKI1
elif character4== 'THOR':
    c4=THOR1
elif character4== 'GAMORA':
    c4=GAMORA1
elif character4== 'DOCTOR_STRANGE':
    c4=DOCTOR_STRANGE1
elif character4=='CAPTAIN_AMERICA':
    c4=CAPTAIN_AMERICA1
totalscore=c1+c2+c3+c4
print('THE TOTAL RATING OF THE TEAM YOU HAVE SELECTED IS :',totalscore)


