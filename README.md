# horoscope-
An application to check the horoscope of a person through zodiac signs
print(''' 
1) Aries
2) Taurus
3) Gemini
4) Cancer
5) Leo
6) Virgo
7) Libra
8) Scorpio
9) Sagittarius
10) Capricorn
11) Aquarius
12) Pisces
''')     
z = int(input('Choose your zodiac sign according the numbers mentioned'))

if z == 1:
    print('''You might not get the things done that you want to do today, Aries, but don't sweat it. Go easy on yourself if you still have a few unchecked things on the list tonight. People may pop out of nowhere and demand your attention for much of the time. Listen, be present, and try not to think of the things that aren't getting done. Focus on those things that are getting done.Revive your love. Make this the year your love grows with a psychic love reading.''')
elif z == 2:
        print('''Today is a fantastic day, Taurus, so make the most of it. If you're emotionally and mentally prepared to go on a new, exciting life journey, the opportunity will present itself. The energy will be fast and furious. You can work harmoniously with electrical gadgets and new technologies. Break free of the mundane and seek less conventional ways of living.  ''')
elif z==3:
        print(''' You'll be tested today, Gemini, so brace yourself for the unexpected. A large piece of your life is coming into question at this time, and you're being forced to face the music. Is this something that really rings true with your inner being? If it is, you should be able to deal with this challenge. If you're struggling, perhaps you should take this as a sign that you need a major life change. ''')
elif z==4:
        print('''You have lots of energy at your disposal today, Cancer, but it's erratic and powerful. You have the stamina to make major changes, and the opportunity to break free from any restrictions that hold you back. Embrace the new, fresh aspects of your life that ring true to your freedom-loving nature. Give your soul room to breathe as you take a long walk in nature this afternoon. ''')
elif z==5:
        print(''' It's time to take a bold step forward, Leo. Have confidence in yourself and all the careful planning you've been painstakingly doing for the past few months. Realize that much of this hard work is paying off, but only if you're willing to take the next step. The opportunity is there. All you need to do is jump on it. Act out of faith and confidence instead of fear and restriction. ''')
elif z==6:
         print('''You can't ask for a better day, Virgo. Positive energy is coming your way. You should look for the opportunities that are right in front of you. You may be going through some significant upheaval right now. Clear away all the things that have limited you in the past. The future is wide open. Empower yourself to make the changes necessary to build your life way you want it to be. ''')
elif z==7:
         print('''  Be on your toes today, Libra, and expect the unexpected. People may be acting out in rash, outlandish ways, so go with the flow. As usual, you have a tremendous ability to roll with the punches and still come out unscathed. Just take care that someone else isn't grabbing the reins. Stay laid-back while maintaining control of your actions. ''')
elif z==8:
     print('''If you've put in your time and done your homework, this day can prove very rewarding, Scorpio. Watch out for incredible opportunities hiding nearby. You have a great deal of physical energy today, although you may find it erratic and a bit out of control. Break free of anything that seems to be binding you. Shed the chains and live the way you want to live ''')
elif z==9:
        print(''' You may find people very stubborn today, so take care, Sagittarius. Arguments can explode out of nowhere, so have your helmet ready. Think before you act and don't feel pressured to get involved in something that makes you feel uncomfortable. Remember that it's OK to just walk away. No one will win the boxing match, so don't even get in the ring. ''')
elif z==10:
         print(''' Initiate a major change in your life, Capricorn. Break free of the humdrum and launch into something exciting. Take part in an online class that expands your mind. Consider yoga, tarot, or any form of martial arts. You have a tremendous amount of energy today. It will help you maintain confidence and endurance as you do the groundwork to put this new life-enhancing endeavor in motion.''')
elif z==11:
        print('''Walk on the sunny side of the street. This is a time for you to consciously be positive about your career situation and where you are going. Find a way to flip your mind from a negative perspective to an uplifting one. Your attitude is everything.  ''')
elif z==12:
          print('''Support from friends is outstanding. Lean on your friends at this time. Asking for help and support is a sign of strength, and not a sign of weakness. Don't be afraid to ask others for ideas and alternative perspectives. They are there to help you. ''')
else:
    print("wrong choice")
