'''
eu sou iniciante, comecei programar há algumas semanas e não copiei nada de ninguém, talvez tenha maneiras mais faceis, desculpe se estiver ruim
I'm a beginner, I started programming a few weeks ago and I didn't copy anything from anyone, maybe I have easier ways, sorry if it's bad
'''
import playsound

from tkinter import messagebox

messagebox.showinfo('Musicas UU','Olá, Bem vindo ao meu sei lá o que de musica')   #Isso vai escrever a mensagem de alerta
escolher = (int(input('Para ver as Bandas digite 1: ')))

if escolher == 1:
    print("")
    print('1- Iron Maiden')
    print("")
    print('2- Guns N Roses')
    print('')
    print('3- Metallica')
    print("")


banda = int(input('Digite o número da banda: '))

if banda == 1:
    print('')
    print('1- Wasting Love')
    print('2- The Number Of The Beast')
    print('3- Wasted Years')
    print('4- The Trooper')
    print('5- Fear of the Dark')
    print('')
    musica_iron = int(input("Digite o número da musica: "))

if banda==1 and musica_iron ==1:    #se a banda for igual e 1 E a musica_iron for igual a 1, toque wasting love
    playsound.playsound('wastinglove.mp3')  #essa é a musica que você copiou e colou
    messagebox.showinfo("Rock N'Roll", "Otima escolha, Aumente som") #essa é uma caixa de mensagem que vai aparecer
if banda==1 and musica_iron ==2:
    messagebox.showinfo("Rock N'Roll", "Otima escolha, Aumente som")
    playsound.playsound('thenumber.mp3')
if banda==1 and musica_iron ==3:
    messagebox.showinfo("Rock N'Roll", "Otima escolha, Aumente som")
    playsound.playsound('wastedyears.mp3')
if banda==1 and musica_iron ==4:
    messagebox.showinfo("Rock N'Roll", "Otima escolha, Aumente som")
    playsound.playsound('trooper.mp3')
if banda==1 and musica_iron ==5:
    messagebox.showinfo("Rock N'Roll", "Otima escolha, Aumente som")
    playsound.playsound('fearofthedark.mp3')

if banda == 2:
    print('')
    print('1- Sweet Child of Mine')
    print('2- November Rain')
    print('3- Welcome To The Jungle')
    print('')
    musica_guns = int(input("Digite o número da musica: "))

if banda ==2 and musica_guns ==1: #Tudo se repette, mas dessa vez com a banda =2 e a musica_guns = 1
    messagebox.showinfo("Rock N'Roll", "Otima escolha, Aumente som")
    playsound.playsound("sweetchild.mp3")
if banda ==2 and musica_guns ==2:
    messagebox.showinfo("Rock N'Roll", "Otima escolha, Aumente som")
    playsound.playsound("novemberrain.mp3")
if banda ==2 and musica_guns ==3:
    messagebox.showinfo("Rock N'Roll", "Otima escolha, Aumente som")
    playsound.playsound("welcometo.mp3")

if banda ==3:
    print('')
    print('1- Nothing Else Matters')
    print('2- For Whom the Bell Tolls')
    print('3- Master of Puppets')
    print('')
    musica_metallica = int(input('Digite o número da musica: '))

if banda ==3 and musica_metallica ==1: #mesma coisa
    messagebox.showinfo("Rock N'Roll", "Otima escolha, Aumente som")
    playsound.playsound('nothingelse.mp3')
if banda ==3 and musica_metallica ==2:
    messagebox.showinfo("Rock N'Roll", "Otima escolha, Aumente som")
    playsound.playsound('forwhom.mp3')
    messagebox.showinfo("Rock N'Roll", "Otima escolha, Aumente som")
if banda ==3 and musica_metallica ==3:
    messagebox.showinfo("Rock N'Roll", "Otima escolha, Aumente som")
    playsound.playsound('masterofpuppets.mp3')

''''
VOCÊ TEM QUE IR NA SUA MUSICA .MP3 CLICAR EM COPIAR E DEPOIS COLAR NO MESMO LUGAR QUE ESTA SALVO ESSE CODIGOS


YOU HAVE TO GO IN YOUR MUSIC .MP3 CLICK TO COPY AND THEN PASTE IN THE SAME PLACE THAT IS SAVED THAT CODES


'''
