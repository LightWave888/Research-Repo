### Python

*_What is Python?_*

Python is coding language that is very widly used, as it is easy (so they say!) to learn.  It's name Python is related to Monthy Python!  I love it that the coding community have agret sense of humour and like to have fun with things!

A quick search on seek and most of the software and web development jobs are asking for Python coding experience.

*_Coding_*
I'm still getting the hang of learning Python.  I am enjoying doing the Koans, i feel like it's helping me to unerstand a bit more although some of it is still very confusing.  
I had a lot of trouble with getting VS Code to work, i had set it up wrong, Pinal helped me to get it set up properly so i can actually run codes without any issue now.

I've mainly been practising with print, int, if, elif, else functions and just getting the hang of these.  After doing some Koans i've also learnt len. I have a long way to go and i feel like at times I am really struggling with focus and brainfog - I will look at a bunch of code and it just looks so mind boggling.  I know it's always the hardest when you start learning something new so i know it'll all click for me soon.  It definitly does challenge your own self belief, I have thought a few times 'maybe i'm not smart enough', 'maybe i'm not sharp enough', 'why are't I getting this?',  'why isnt this easier?', 'Maybe i've chosen the wrong thing to study', 'Maybe i should just got back to hospo fulltime'.   

*_Resources that are helping me_*
I've found some great resources to use and practise Python with.
-W3Schools a very helpful and has a lot of info and tutorials
-https://www.dataquest.io/blog/python-projects-for-beginners has a lot if links to various projects and activites.  I am yet to explore a lot of them but i will be doing some of these too
-koans, trying to work out some of these really gets me thinking and every mistake i make and incorrect answer helps me to learn. 

I've been mindful of Roman saying to be careful about Turtorial hell,  I think for me the combo of Romans teaching and extra turtorials are helping me a lot.  I only really learn by doing, so just watching someone do it or watching a video without actually following along in real time is very hard for me.  If i do something I am more likely to retain it.

For the exercise of calculating a dogs age I found this code
h_age = int(input("Input a dog's age in human years: "))

if h_age < 0:
	print("Age must be positive number.")
	exit()
elif h_age <= 2:
	d_age = h_age * 10.5
else:
	d_age = 21 + (h_age - 2)*4

print("The dog's age in dog's years is", d_age)

this codde works well, but i feel it could be simpler.  I'm not sure why it needs the if question, but I assume when writing code we need to assume people might not think logically so perhaps someone would put something less than 1.  It's interesting to start to think about the potential users and what they may input and what output we would want for that.

One of the Koans codes i found fun was 
def test_accessing_list_elements(self):
        noms = ['peanut', 'butter', 'and', 'jelly']

        self.assertEqual('peanut', noms[0])
        self.assertEqual('jelly', noms[3])
        self.assertEqual('jelly', noms[-1])
        self.assertEqual('butter', noms[-3])
        
It's kind of strange that the numbering system is different to our normal numbering system, but it's quite fun at the same time.  I keep trying to relate computer language and coding languages to our english language but it just doesnt always work like that.  I remembered about when I studied spanish in school and how even the sentence structure is totally different to english, I think letting go of what I know of my language will help more and more to understand code.  I can see why kids can pick it up pretty fast as they arent so set in their ways with their language and it's structure.

## Pygame
 This is some coding I've been learning to create a game in pygame.  This is the beginiings of a snake game and am just learning what parts of the code represent. 
 I can easily change the colours, and the sizing with this.  The code also tells us to keep running unless the user says QUIT and then it is to exit.  I'm enjoying playing around with pygame and will be doing more on this for fun too!


size = width, height = 640, 480
pink = 255, 192, 203
yellow = 255, 255, 0

screen = pygame.display.set_mode(size)

while 1:
    for event in pygame.event.get():
        if event.type == pygame.QUIT: sys.exit()
        
    screen.fill(pink)
    
    pygame.draw.rect(screen, yellow, (100, 100, 10, 10))
    pygame.display.flip()
    
   
