# Jap
This is a self-teaching tool for people who want to learn Japanese. I am thinking of something like what I used to get in primary school:
  
  The teacher will read the word every time you learn some new ones, and you have to write them down. Then you will be graded based on how many you got correct. This step is just to help you memorise the words, how to write them down and how to pronounce them. As for how to use the words correctly, I think I will put it in the second phase.

The application, hopefully, will be an executable programme on windows first and transfer to android afterwards. I am still in the designing phase.

On a second thought, I decided to build it as a web application first. With angular as front end and java as back end. I would use Spring and Hibernate to help me build it. The front end part will come out first, with no back end logic attached to it (just fixed string values or dummy data to show the UI/UX).

Functional requirement will come later, and will be updated as the development is in progress. That's all.

Functional Requirements

Update Dec 21, 2018

  There are two types of Japanese syllabaries, Hiragana (平仮名, ひらがな) and Katakana(片仮名, かたかな, カタカナ). There is also kanji (Chinese characters, what is used in day to day life), romaji (or romanji, basics for Japanese input in computers, also what I will use on the app). I will do Hiragana first.
    
<h3>[One]</h3>
    
   1>. The webpage will display a Hiragana symbol, the user will type the romaji and type Enter (or click) to submit the answer. If the answer is correct, it will be displayed in Green; if the answer is wrong, it will be displayed in Red and the correct one will appear in Green.
      
   2>. The webpage will display a Hiragana symbol, and several (very likely three) romaji choices for users to select. After the user clicks an option, the right answer will be displayed in Green and the wrong answer will be displayed in Red.
      
   3>. The webpage will display a Japanese word in Hiragana, the user will type the romaji and type Enter (or click) to submit the answer. If the answer is correct, it will be displayed in Green; if the answer is wrong, it will be displayed in Red and the correct one will appear in Green.
      
   4>. The webpage will display a Japanese word in Hiragana, and several (very likely three) romaji choices for users to select. After the user clicks an option, the right answer will be displayed in Green and the wrong answer will be displayed in Red.
    
<h3>[Two]</h3>
      
   1>. The app will keep track of the Hiragana symbols and Japanese words that the user answered wrongly. There will be a Review Your Mistakes function.
   
   2>. There will be three types of mistakes
      a. mistakes that appear only once.
      b. mistakes that appear two or three times
      c. mistakes that appear more than three times.
      
   3>. The app will make all the mistakes will appear twice. If the p
