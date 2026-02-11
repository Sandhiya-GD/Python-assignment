# Python-assignment
Python assignment 
# Python Data Collection Tool

## 📌 Overview

This project is a Python-based data collection tool developed as part of a technical assignment.

It collects public data from:

- A website using HTML scraping  
  👉 https://quotes.toscrape.com

- A public API using REST calls  
  👉 https://api.github.com/search/repositories

The collected data is normalized and exported into a single structured JSON file.

The implementation focuses on reliability, error handling, logging, and production-ready practices.

---

## ⚙️ Features

- Website scraping with pagination
- GitHub API consumption with pagination
- Configurable User-Agent header
- Optional GitHub API authentication
- Rate limit handling
- Structured logging
- Graceful failure handling
- Google Colab compatible
- Single JSON output

---

## 🛠️ Installation

### Prerequisites
- google colab
- pip

### Install Dependencies

```bash
pip install requests beautifulsoup4








{
    "quotes": [
        {
            "text": "“The world as we have created it is a process of our thinking. It cannot be changed without changing our thinking.”",
            "author": "Albert Einstein",
            "author_url": "https://quotes.toscrape.com/author/Albert-Einstein"
        },
        {
            "text": "“It is our choices, Harry, that show what we truly are, far more than our abilities.”",
            "author": "J.K. Rowling",
            "author_url": "https://quotes.toscrape.com/author/J-K-Rowling"
        },
        {
            "text": "“There are only two ways to live your life. One is as though nothing is a miracle. The other is as though everything is a miracle.”",
            "author": "Albert Einstein",
            "author_url": "https://quotes.toscrape.com/author/Albert-Einstein"
        },
        {
            "text": "“The person, be it gentleman or lady, who has not pleasure in a good novel, must be intolerably stupid.”",
            "author": "Jane Austen",
            "author_url": "https://quotes.toscrape.com/author/Jane-Austen"
        },
        {
            "text": "“Imperfection is beauty, madness is genius and it's better to be absolutely ridiculous than absolutely boring.”",
            "author": "Marilyn Monroe",
            "author_url": "https://quotes.toscrape.com/author/Marilyn-Monroe"
        },
        {
            "text": "“Try not to become a man of success. Rather become a man of value.”",
            "author": "Albert Einstein",
            "author_url": "https://quotes.toscrape.com/author/Albert-Einstein"
        },
        {
            "text": "“It is better to be hated for what you are than to be loved for what you are not.”",
            "author": "André Gide",
            "author_url": "https://quotes.toscrape.com/author/Andre-Gide"
        },
        {
            "text": "“I have not failed. I've just found 10,000 ways that won't work.”",
            "author": "Thomas A. Edison",
            "author_url": "https://quotes.toscrape.com/author/Thomas-A-Edison"
        },
        {
            "text": "“A woman is like a tea bag; you never know how strong it is until it's in hot water.”",
            "author": "Eleanor Roosevelt",
            "author_url": "https://quotes.toscrape.com/author/Eleanor-Roosevelt"
        },
        {
            "text": "“A day without sunshine is like, you know, night.”",
            "author": "Steve Martin",
            "author_url": "https://quotes.toscrape.com/author/Steve-Martin"
        },
        {
            "text": "“This life is what you make it. No matter what, you're going to mess up sometimes, it's a universal truth. But the good part is you get to decide how you're going to mess it up. Girls will be your friends - they'll act like it anyway. But just remember, some come, some go. The ones that stay with you through everything - they're your true best friends. Don't let go of them. Also remember, sisters make the best friends in the world. As for lovers, well, they'll come and go too. And baby, I hate to say it, most of them - actually pretty much all of them are going to break your heart, but you can't give up because if you give up, you'll never find your soulmate. You'll never find that half who makes you whole and that goes for everything. Just because you fail once, doesn't mean you're gonna fail at everything. Keep trying, hold on, and always, always, always believe in yourself, because if you don't, then who will, sweetie? So keep your head high, keep your chin up, and most importantly, keep smiling, because life's a beautiful thing and there's so much to smile about.”",
            "author": "Marilyn Monroe",
            "author_url": "https://quotes.toscrape.com/author/Marilyn-Monroe"
        },
        {
            "text": "“It takes a great deal of bravery to stand up to our enemies, but just as much to stand up to our friends.”",
            "author": "J.K. Rowling",
            "author_url": "https://quotes.toscrape.com/author/J-K-Rowling"
        },
        {
            "text": "“If you can't explain it to a six year old, you don't understand it yourself.”",
            "author": "Albert Einstein",
            "author_url": "https://quotes.toscrape.com/author/Albert-Einstein"
        },
        {
            "text": "“You may not be her first, her last, or her only. She loved before she may love again. But if she loves you now, what else matters? She's not perfect—you aren't either, and the two of you may never be perfect together but if she can make you laugh, cause you to think twice, and admit to being human and making mistakes, hold onto her and give her the most you can. She may not be thinking about you every second of the day, but she will give you a part of her that she knows you can break—her heart. So don't hurt her, don't change her, don't analyze and don't expect more than she can give. Smile when she makes you happy, let her know when she makes you mad, and miss her when she's not there.”",
            "author": "Bob Marley",
            "author_url": "https://quotes.toscrape.com/author/Bob-Marley"
        },
        {
            "text": "“I like nonsense, it wakes up the brain cells. Fantasy is a necessary ingredient in living.”",
            "author": "Dr. Seuss",
            "author_url": "https://quotes.toscrape.com/author/Dr-Seuss"
        },
        {
            "text": "“I may not have gone where I intended to go, but I think I have ended up where I needed to be.”",
            "author": "Douglas Adams",
            "author_url": "https://quotes.toscrape.com/author/Douglas-Adams"
        },
        {
            "text": "“The opposite of love is not hate, it's indifference. The opposite of art is not ugliness, it's indifference. The opposite of faith is not heresy, it's indifference. And the opposite of life is not death, it's indifference.”",
            "author": "Elie Wiesel",
            "author_url": "https://quotes.toscrape.com/author/Elie-Wiesel"
        },
        {
            "text": "“It is not a lack of love, but a lack of friendship that makes unhappy marriages.”",
            "author": "Friedrich Nietzsche",
            "author_url": "https://quotes.toscrape.com/author/Friedrich-Nietzsche"
        },
        {
            "text": "“Good friends, good books, and a sleepy conscience: this is the ideal life.”",
            "author": "Mark Twain",
            "author_url": "https://quotes.toscrape.com/author/Mark-Twain"
        },
        {
            "text": "“Life is what happens to us while we are making other plans.”",
            "author": "Allen Saunders",
            "author_url": "https://quotes.toscrape.com/author/Allen-Saunders"
        },
        {
            "text": "“I love you without knowing how, or when, or from where. I love you simply, without problems or pride: I love you in this way because I do not know any other way of loving but this, in which there is no I or you, so intimate that your hand upon my chest is my hand, so intimate that when I fall asleep your eyes close.”",
            "author": "Pablo Neruda",
            "author_url": "https://quotes.toscrape.com/author/Pablo-Neruda"
        },
        {
            "text": "“For every minute you are angry you lose sixty seconds of happiness.”",
            "author": "Ralph Waldo Emerson",
            "author_url": "https://quotes.toscrape.com/author/Ralph-Waldo-Emerson"
        },
        {
            "text": "“If you judge people, you have no time to love them.”",
            "author": "Mother Teresa",
            "author_url": "https://quotes.toscrape.com/author/Mother-Teresa"
        },
        {
            "text": "“Anyone who thinks sitting in church can make you a Christian must also think that sitting in a garage can make you a car.”",
            "author": "Garrison Keillor",
            "author_url": "https://quotes.toscrape.com/author/Garrison-Keillor"
        },
        {
            "text": "“Beauty is in the eye of the beholder and it may be necessary from time to time to give a stupid or misinformed beholder a black eye.”",
            "author": "Jim Henson",
            "author_url": "https://quotes.toscrape.com/author/Jim-Henson"
        },
        {
            "text": "“Today you are You, that is truer than true. There is no one alive who is Youer than You.”",
            "author": "Dr. Seuss",
            "author_url": "https://quotes.toscrape.com/author/Dr-Seuss"
        },
        {
            "text": "“If you want your children to be intelligent, read them fairy tales. If you want them to be more intelligent, read them more fairy tales.”",
            "author": "Albert Einstein",
            "author_url": "https://quotes.toscrape.com/author/Albert-Einstein"
        },
        {
            "text": "“It is impossible to live without failing at something, unless you live so cautiously that you might as well not have lived at all - in which case, you fail by default.”",
            "author": "J.K. Rowling",
            "author_url": "https://quotes.toscrape.com/author/J-K-Rowling"
        },
        {
            "text": "“Logic will get you from A to Z; imagination will get you everywhere.”",
            "author": "Albert Einstein",
            "author_url": "https://quotes.toscrape.com/author/Albert-Einstein"
        },
        {
            "text": "“One good thing about music, when it hits you, you feel no pain.”",
            "author": "Bob Marley",
            "author_url": "https://quotes.toscrape.com/author/Bob-Marley"
        },
        {
            "text": "“The more that you read, the more things you will know. The more that you learn, the more places you'll go.”",
            "author": "Dr. Seuss",
            "author_url": "https://quotes.toscrape.com/author/Dr-Seuss"
        },
        {
            "text": "“Of course it is happening inside your head, Harry, but why on earth should that mean that it is not real?”",
            "author": "J.K. Rowling",
            "author_url": "https://quotes.toscrape.com/author/J-K-Rowling"
        },
        {
            "text": "“The truth is, everyone is going to hurt you. You just got to find the ones worth suffering for.”",
            "author": "Bob Marley",
            "author_url": "https://quotes.toscrape.com/author/Bob-Marley"
        },
        {
            "text": "“Not all of us can do great things. But we can do small things with great love.”",
            "author": "Mother Teresa",
            "author_url": "https://quotes.toscrape.com/author/Mother-Teresa"
        },
        {
            "text": "“To the well-organized mind, death is but the next great adventure.”",
            "author": "J.K. Rowling",
            "author_url": "https://quotes.toscrape.com/author/J-K-Rowling"
        },
        {
            "text": "“All you need is love. But a little chocolate now and then doesn't hurt.”",
            "author": "Charles M. Schulz",
            "author_url": "https://quotes.toscrape.com/author/Charles-M-Schulz"
        },
        {
            "text": "“We read to know we're not alone.”",
            "author": "William Nicholson",
            "author_url": "https://quotes.toscrape.com/author/William-Nicholson"
        },
        {
            "text": "“Any fool can know. The point is to understand.”",
            "author": "Albert Einstein",
            "author_url": "https://quotes.toscrape.com/author/Albert-Einstein"
        },
        {
            "text": "“I have always imagined that Paradise will be a kind of library.”",
            "author": "Jorge Luis Borges",
            "author_url": "https://quotes.toscrape.com/author/Jorge-Luis-Borges"
        },
        {
            "text": "“It is never too late to be what you might have been.”",
            "author": "George Eliot",
            "author_url": "https://quotes.toscrape.com/author/George-Eliot"
        },
        {
            "text": "“A reader lives a thousand lives before he dies, said Jojen. The man who never reads lives only one.”",
            "author": "George R.R. Martin",
            "author_url": "https://quotes.toscrape.com/author/George-R-R-Martin"
        },
        {
            "text": "“You can never get a cup of tea large enough or a book long enough to suit me.”",
            "author": "C.S. Lewis",
            "author_url": "https://quotes.toscrape.com/author/C-S-Lewis"
        },
        {
            "text": "“You believe lies so you eventually learn to trust no one but yourself.”",
            "author": "Marilyn Monroe",
            "author_url": "https://quotes.toscrape.com/author/Marilyn-Monroe"
        },
        {
            "text": "“If you can make a woman laugh, you can make her do anything.”",
            "author": "Marilyn Monroe",
            "author_url": "https://quotes.toscrape.com/author/Marilyn-Monroe"
        },
        {
            "text": "“Life is like riding a bicycle. To keep your balance, you must keep moving.”",
            "author": "Albert Einstein",
            "author_url": "https://quotes.toscrape.com/author/Albert-Einstein"
        },
        {
            "text": "“The real lover is the man who can thrill you by kissing your forehead or smiling into your eyes or just staring into space.”",
            "author": "Marilyn Monroe",
            "author_url": "https://quotes.toscrape.com/author/Marilyn-Monroe"
        },
        {
            "text": "“A wise girl kisses but doesn't love, listens but doesn't believe, and leaves before she is left.”",
            "author": "Marilyn Monroe",
            "author_url": "https://quotes.toscrape.com/author/Marilyn-Monroe"
        },
        {
            "text": "“Only in the darkness can you see the stars.”",
            "author": "Martin Luther King Jr.",
            "author_url": "https://quotes.toscrape.com/author/Martin-Luther-King-Jr"
        },
        {
            "text": "“It matters not what someone is born, but what they grow to be.”",
            "author": "J.K. Rowling",
            "author_url": "https://quotes.toscrape.com/author/J-K-Rowling"
        },
        {
            "text": "“Love does not begin and end the way we seem to think it does. Love is a battle, love is a war; love is a growing up.”",
            "author": "James Baldwin",
            "author_url": "https://quotes.toscrape.com/author/James-Baldwin"
        },
        {
            "text": "“There is nothing I would not do for those who are really my friends. I have no notion of loving people by halves, it is not my nature.”",
            "author": "Jane Austen",
            "author_url": "https://quotes.toscrape.com/author/Jane-Austen"
        },
        {
            "text": "“Do one thing every day that scares you.”",
            "author": "Eleanor Roosevelt",
            "author_url": "https://quotes.toscrape.com/author/Eleanor-Roosevelt"
        },
        {
            "text": "“I am good, but not an angel. I do sin, but I am not the devil. I am just a small girl in a big world trying to find someone to love.”",
            "author": "Marilyn Monroe",
            "author_url": "https://quotes.toscrape.com/author/Marilyn-Monroe"
        },
        {
            "text": "“If I were not a physicist, I would probably be a musician. I often think in music. I live my daydreams in music. I see my life in terms of music.”",
            "author": "Albert Einstein",
            "author_url": "https://quotes.toscrape.com/author/Albert-Einstein"
        },
        {
            "text": "“If you only read the books that everyone else is reading, you can only think what everyone else is thinking.”",
            "author": "Haruki Murakami",
            "author_url": "https://quotes.toscrape.com/author/Haruki-Murakami"
        },
        {
            "text": "“The difference between genius and stupidity is: genius has its limits.”",
            "author": "Alexandre Dumas fils",
            "author_url": "https://quotes.toscrape.com/author/Alexandre-Dumas-fils"
        },
        {
            "text": "“He's like a drug for you, Bella.”",
            "author": "Stephenie Meyer",
            "author_url": "https://quotes.toscrape.com/author/Stephenie-Meyer"
        },
        {
            "text": "“There is no friend as loyal as a book.”",
            "author": "Ernest Hemingway",
            "author_url": "https://quotes.toscrape.com/author/Ernest-Hemingway"
        },
        {
            "text": "“When one door of happiness closes, another opens; but often we look so long at the closed door that we do not see the one which has been opened for us.”",
            "author": "Helen Keller",
            "author_url": "https://quotes.toscrape.com/author/Helen-Keller"
        },
        {
            "text": "“Life isn't about finding yourself. Life is about creating yourself.”",
            "author": "George Bernard Shaw",
            "author_url": "https://quotes.toscrape.com/author/George-Bernard-Shaw"
        },
        {
            "text": "“That's the problem with drinking, I thought, as I poured myself a drink. If something bad happens you drink in an attempt to forget; if something good happens you drink in order to celebrate; and if nothing happens you drink to make something happen.”",
            "author": "Charles Bukowski",
            "author_url": "https://quotes.toscrape.com/author/Charles-Bukowski"
        },
        {
            "text": "“You don’t forget the face of the person who was your last hope.”",
            "author": "Suzanne Collins",
            "author_url": "https://quotes.toscrape.com/author/Suzanne-Collins"
        },
        {
            "text": "“Remember, we're madly in love, so it's all right to kiss me anytime you feel like it.”",
            "author": "Suzanne Collins",
            "author_url": "https://quotes.toscrape.com/author/Suzanne-Collins"
        },
        {
            "text": "“To love at all is to be vulnerable. Love anything and your heart will be wrung and possibly broken. If you want to make sure of keeping it intact you must give it to no one, not even an animal. Wrap it carefully round with hobbies and little luxuries; avoid all entanglements. Lock it up safe in the casket or coffin of your selfishness. But in that casket, safe, dark, motionless, airless, it will change. It will not be broken; it will become unbreakable, impenetrable, irredeemable. To love is to be vulnerable.”",
            "author": "C.S. Lewis",
            "author_url": "https://quotes.toscrape.com/author/C-S-Lewis"
        },
        {
            "text": "“Not all those who wander are lost.”",
            "author": "J.R.R. Tolkien",
            "author_url": "https://quotes.toscrape.com/author/J-R-R-Tolkien"
        },
        {
            "text": "“Do not pity the dead, Harry. Pity the living, and, above all those who live without love.”",
            "author": "J.K. Rowling",
            "author_url": "https://quotes.toscrape.com/author/J-K-Rowling"
        },
        {
            "text": "“There is nothing to writing. All you do is sit down at a typewriter and bleed.”",
            "author": "Ernest Hemingway",
            "author_url": "https://quotes.toscrape.com/author/Ernest-Hemingway"
        },
        {
            "text": "“Finish each day and be done with it. You have done what you could. Some blunders and absurdities no doubt crept in; forget them as soon as you can. Tomorrow is a new day. You shall begin it serenely and with too high a spirit to be encumbered with your old nonsense.”",
            "author": "Ralph Waldo Emerson",
            "author_url": "https://quotes.toscrape.com/author/Ralph-Waldo-Emerson"
        },
        {
            "text": "“I have never let my schooling interfere with my education.”",
            "author": "Mark Twain",
            "author_url": "https://quotes.toscrape.com/author/Mark-Twain"
        },
        {
            "text": "“I have heard there are troubles of more than one kind. Some come from ahead and some come from behind. But I've bought a big bat. I'm all ready you see. Now my troubles are going to have troubles with me!”",
            "author": "Dr. Seuss",
            "author_url": "https://quotes.toscrape.com/author/Dr-Seuss"
        },
        {
            "text": "“If I had a flower for every time I thought of you...I could walk through my garden forever.”",
            "author": "Alfred Tennyson",
            "author_url": "https://quotes.toscrape.com/author/Alfred-Tennyson"
        },
        {
            "text": "“Some people never go crazy. What truly horrible lives they must lead.”",
            "author": "Charles Bukowski",
            "author_url": "https://quotes.toscrape.com/author/Charles-Bukowski"
        },
        {
            "text": "“The trouble with having an open mind, of course, is that people will insist on coming along and trying to put things in it.”",
            "author": "Terry Pratchett",
            "author_url": "https://quotes.toscrape.com/author/Terry-Pratchett"
        },
        {
            "text": "“Think left and think right and think low and think high. Oh, the thinks you can think up if only you try!”",
            "author": "Dr. Seuss",
            "author_url": "https://quotes.toscrape.com/author/Dr-Seuss"
        },
        {
            "text": "“What really knocks me out is a book that, when you're all done reading it, you wish the author that wrote it was a terrific friend of yours and you could call him up on the phone whenever you felt like it. That doesn't happen much, though.”",
            "author": "J.D. Salinger",
            "author_url": "https://quotes.toscrape.com/author/J-D-Salinger"
        },
        {
            "text": "“The reason I talk to myself is because I’m the only one whose answers I accept.”",
            "author": "George Carlin",
            "author_url": "https://quotes.toscrape.com/author/George-Carlin"
        },
        {
            "text": "“You may say I'm a dreamer, but I'm not the only one. I hope someday you'll join us. And the world will live as one.”",
            "author": "John Lennon",
            "author_url": "https://quotes.toscrape.com/author/John-Lennon"
        },
        {
            "text": "“I am free of all prejudice. I hate everyone equally. ”",
            "author": "W.C. Fields",
            "author_url": "https://quotes.toscrape.com/author/W-C-Fields"
        },
        {
            "text": "“The question isn't who is going to let me; it's who is going to stop me.”",
            "author": "Ayn Rand",
            "author_url": "https://quotes.toscrape.com/author/Ayn-Rand"
        },
        {
            "text": "“′Classic′ - a book which people praise and don't read.”",
            "author": "Mark Twain",
            "author_url": "https://quotes.toscrape.com/author/Mark-Twain"
        },
        {
            "text": "“Anyone who has never made a mistake has never tried anything new.”",
            "author": "Albert Einstein",
            "author_url": "https://quotes.toscrape.com/author/Albert-Einstein"
        },
        {
            "text": "“A lady's imagination is very rapid; it jumps from admiration to love, from love to matrimony in a moment.”",
            "author": "Jane Austen",
            "author_url": "https://quotes.toscrape.com/author/Jane-Austen"
        },
        {
            "text": "“Remember, if the time should come when you have to make a choice between what is right and what is easy, remember what happened to a boy who was good, and kind, and brave, because he strayed across the path of Lord Voldemort. Remember Cedric Diggory.”",
            "author": "J.K. Rowling",
            "author_url": "https://quotes.toscrape.com/author/J-K-Rowling"
        },
        {
            "text": "“I declare after all there is no enjoyment like reading! How much sooner one tires of any thing than of a book! -- When I have a house of my own, I shall be miserable if I have not an excellent library.”",
            "author": "Jane Austen",
            "author_url": "https://quotes.toscrape.com/author/Jane-Austen"
        },
        {
            "text": "“There are few people whom I really love, and still fewer of whom I think well. The more I see of the world, the more am I dissatisfied with it; and every day confirms my belief of the inconsistency of all human characters, and of the little dependence that can be placed on the appearance of merit or sense.”",
            "author": "Jane Austen",
            "author_url": "https://quotes.toscrape.com/author/Jane-Austen"
        },
        {
            "text": "“Some day you will be old enough to start reading fairy tales again.”",
            "author": "C.S. Lewis",
            "author_url": "https://quotes.toscrape.com/author/C-S-Lewis"
        },
        {
            "text": "“We are not necessarily doubting that God will do the best for us; we are wondering how painful the best will turn out to be.”",
            "author": "C.S. Lewis",
            "author_url": "https://quotes.toscrape.com/author/C-S-Lewis"
        },
        {
            "text": "“The fear of death follows from the fear of life. A man who lives fully is prepared to die at any time.”",
            "author": "Mark Twain",
            "author_url": "https://quotes.toscrape.com/author/Mark-Twain"
        },
        {
            "text": "“A lie can travel half way around the world while the truth is putting on its shoes.”",
            "author": "Mark Twain",
            "author_url": "https://quotes.toscrape.com/author/Mark-Twain"
        },
        {
            "text": "“I believe in Christianity as I believe that the sun has risen: not only because I see it, but because by it I see everything else.”",
            "author": "C.S. Lewis",
            "author_url": "https://quotes.toscrape.com/author/C-S-Lewis"
        },
        {
            "text": "“The truth.\" Dumbledore sighed. \"It is a beautiful and terrible thing, and should therefore be treated with great caution.”",
            "author": "J.K. Rowling",
            "author_url": "https://quotes.toscrape.com/author/J-K-Rowling"
        },
        {
            "text": "“I'm the one that's got to die when it's time for me to die, so let me live my life the way I want to.”",
            "author": "Jimi Hendrix",
            "author_url": "https://quotes.toscrape.com/author/Jimi-Hendrix"
        },
        {
            "text": "“To die will be an awfully big adventure.”",
            "author": "J.M. Barrie",
            "author_url": "https://quotes.toscrape.com/author/J-M-Barrie"
        },
        {
            "text": "“It takes courage to grow up and become who you really are.”",
            "author": "E.E. Cummings",
            "author_url": "https://quotes.toscrape.com/author/E-E-Cummings"
        },
        {
            "text": "“But better to get hurt by the truth than comforted with a lie.”",
            "author": "Khaled Hosseini",
            "author_url": "https://quotes.toscrape.com/author/Khaled-Hosseini"
        },
        {
            "text": "“You never really understand a person until you consider things from his point of view... Until you climb inside of his skin and walk around in it.”",
            "author": "Harper Lee",
            "author_url": "https://quotes.toscrape.com/author/Harper-Lee"
        },
        {
            "text": "“You have to write the book that wants to be written. And if the book will be too difficult for grown-ups, then you write it for children.”",
            "author": "Madeleine L'Engle",
            "author_url": "https://quotes.toscrape.com/author/Madeleine-LEngle"
        },
        {
            "text": "“Never tell the truth to people who are not worthy of it.”",
            "author": "Mark Twain",
            "author_url": "https://quotes.toscrape.com/author/Mark-Twain"
        },
        {
            "text": "“A person's a person, no matter how small.”",
            "author": "Dr. Seuss",
            "author_url": "https://quotes.toscrape.com/author/Dr-Seuss"
        },
        {
            "text": "“... a mind needs books as a sword needs a whetstone, if it is to keep its edge.”",
            "author": "George R.R. Martin",
            "author_url": "https://quotes.toscrape.com/author/George-R-R-Martin"
        }
    ],
    "github_repos": [
        {
            "name": "public-apis",
            "owner": "public-apis",
            "stars": 397741,
            "url": "https://github.com/public-apis/public-apis"
        },
        {
            "name": "free-programming-books",
            "owner": "EbookFoundation",
            "stars": 382445,
            "url": "https://github.com/EbookFoundation/free-programming-books"
        },
        {
            "name": "system-design-primer",
            "owner": "donnemartin",
            "stars": 335006,
            "url": "https://github.com/donnemartin/system-design-primer"
        },
        {
            "name": "awesome-python",
            "owner": "vinta",
            "stars": 282323,
            "url": "https://github.com/vinta/awesome-python"
        },
        {
            "name": "Python",
            "owner": "TheAlgorithms",
            "stars": 217609,
            "url": "https://github.com/TheAlgorithms/Python"
        },
        {
            "name": "AutoGPT",
            "owner": "Significant-Gravitas",
            "stars": 181782,
            "url": "https://github.com/Significant-Gravitas/AutoGPT"
        },
        {
            "name": "stable-diffusion-webui",
            "owner": "AUTOMATIC1111",
            "stars": 160507,
            "url": "https://github.com/AUTOMATIC1111/stable-diffusion-webui"
        },
        {
            "name": "transformers",
            "owner": "huggingface",
            "stars": 156343,
            "url": "https://github.com/huggingface/transformers"
        },
        {
            "name": "yt-dlp",
            "owner": "yt-dlp",
            "stars": 146661,
            "url": "https://github.com/yt-dlp/yt-dlp"
        },
        {
            "name": "langflow",
            "owner": "langflow-ai",
            "stars": 144723,
            "url": "https://github.com/langflow-ai/langflow"
        },
        {
            "name": "HelloGitHub",
            "owner": "521xueweihan",
            "stars": 142744,
            "url": "https://github.com/521xueweihan/HelloGitHub"
        },
        {
            "name": "youtube-dl",
            "owner": "ytdl-org",
            "stars": 139647,
            "url": "https://github.com/ytdl-org/youtube-dl"
        },
        {
            "name": "langchain",
            "owner": "langchain-ai",
            "stars": 126449,
            "url": "https://github.com/langchain-ai/langchain"
        },
        {
            "name": "open-webui",
            "owner": "open-webui",
            "stars": 123550,
            "url": "https://github.com/open-webui/open-webui"
        },
        {
            "name": "ComfyUI",
            "owner": "Comfy-Org",
            "stars": 102958,
            "url": "https://github.com/Comfy-Org/ComfyUI"
        },
        {
            "name": "DeepSeek-V3",
            "owner": "deepseek-ai",
            "stars": 101537,
            "url": "https://github.com/deepseek-ai/DeepSeek-V3"
        },
        {
            "name": "pytorch",
            "owner": "pytorch",
            "stars": 97316,
            "url": "https://github.com/pytorch/pytorch"
        },
        {
            "name": "thefuck",
            "owner": "nvbn",
            "stars": 95447,
            "url": "https://github.com/nvbn/thefuck"
        },
        {
            "name": "fastapi",
            "owner": "fastapi",
            "stars": 94995,
            "url": "https://github.com/fastapi/fastapi"
        },
        {
            "name": "whisper",
            "owner": "openai",
            "stars": 94453,
            "url": "https://github.com/openai/whisper"
        },
        {
            "name": "awesome-llm-apps",
            "owner": "Shubhamsaboo",
            "stars": 93737,
            "url": "https://github.com/Shubhamsaboo/awesome-llm-apps"
        },
        {
            "name": "django",
            "owner": "django",
            "stars": 86732,
            "url": "https://github.com/django/django"
        },
        {
            "name": "markitdown",
            "owner": "microsoft",
            "stars": 86715,
            "url": "https://github.com/microsoft/markitdown"
        },
        {
            "name": "core",
            "owner": "home-assistant",
            "stars": 84751,
            "url": "https://github.com/home-assistant/core"
        },
        {
            "name": "manim",
            "owner": "3b1b",
            "stars": 84407,
            "url": "https://github.com/3b1b/manim"
        },
        {
            "name": "devops-exercises",
            "owner": "bregman-arie",
            "stars": 80945,
            "url": "https://github.com/bregman-arie/devops-exercises"
        },
        {
            "name": "Deep-Live-Cam",
            "owner": "hacksider",
            "stars": 79397,
            "url": "https://github.com/hacksider/Deep-Live-Cam"
        },
        {
            "name": "funNLP",
            "owner": "fighting41love",
            "stars": 78919,
            "url": "https://github.com/fighting41love/funNLP"
        },
        {
            "name": "browser-use",
            "owner": "browser-use",
            "stars": 78171,
            "url": "https://github.com/browser-use/browser-use"
        },
        {
            "name": "models",
            "owner": "tensorflow",
            "stars": 77696,
            "url": "https://github.com/tensorflow/models"
        },
        {
            "name": "d2l-zh",
            "owner": "d2l-ai",
            "stars": 75572,
            "url": "https://github.com/d2l-ai/d2l-zh"
        },
        {
            "name": "PayloadsAllTheThings",
            "owner": "swisskyrepo",
            "stars": 75095,
            "url": "https://github.com/swisskyrepo/PayloadsAllTheThings"
        },
        {
            "name": "ragflow",
            "owner": "infiniflow",
            "stars": 73128,
            "url": "https://github.com/infiniflow/ragflow"
        },
        {
            "name": "sherlock",
            "owner": "sherlock-project",
            "stars": 72625,
            "url": "https://github.com/sherlock-project/sherlock"
        },
        {
            "name": "awesome-machine-learning",
            "owner": "josephmisiti",
            "stars": 71630,
            "url": "https://github.com/josephmisiti/awesome-machine-learning"
        },
        {
            "name": "cpython",
            "owner": "python",
            "stars": 71452,
            "url": "https://github.com/python/cpython"
        },
        {
            "name": "flask",
            "owner": "pallets",
            "stars": 71148,
            "url": "https://github.com/pallets/flask"
        },
        {
            "name": "PaddleOCR",
            "owner": "PaddlePaddle",
            "stars": 70602,
            "url": "https://github.com/PaddlePaddle/PaddleOCR"
        },
        {
            "name": "gpt_academic",
            "owner": "binary-husky",
            "stars": 70109,
            "url": "https://github.com/binary-husky/gpt_academic"
        },
        {
            "name": "vllm",
            "owner": "vllm-project",
            "stars": 70027,
            "url": "https://github.com/vllm-project/vllm"
        },
        {
            "name": "spec-kit",
            "owner": "github",
            "stars": 68904,
            "url": "https://github.com/github/spec-kit"
        },
        {
            "name": "ansible",
            "owner": "ansible",
            "stars": 67961,
            "url": "https://github.com/ansible/ansible"
        },
        {
            "name": "OpenHands",
            "owner": "OpenHands",
            "stars": 67738,
            "url": "https://github.com/OpenHands/OpenHands"
        },
        {
            "name": "skills",
            "owner": "anthropics",
            "stars": 67647,
            "url": "https://github.com/anthropics/skills"
        },
        {
            "name": "LlamaFactory",
            "owner": "hiyouga",
            "stars": 67154,
            "url": "https://github.com/hiyouga/LlamaFactory"
        },
        {
            "name": "gpt4free",
            "owner": "xtekky",
            "stars": 65725,
            "url": "https://github.com/xtekky/gpt4free"
        },
        {
            "name": "annotated_deep_learning_paper_implementations",
            "owner": "labmlai",
            "stars": 65718,
            "url": "https://github.com/labmlai/annotated_deep_learning_paper_implementations"
        },
        {
            "name": "scikit-learn",
            "owner": "scikit-learn",
            "stars": 64981,
            "url": "https://github.com/scikit-learn/scikit-learn"
        },
        {
            "name": "localstack",
            "owner": "localstack",
            "stars": 64339,
            "url": "https://github.com/localstack/localstack"
        },
        {
            "name": "MetaGPT",
            "owner": "FoundationAgents",
            "stars": 64110,
            "url": "https://github.com/FoundationAgents/MetaGPT"
        },
        {
            "name": "keras",
            "owner": "keras-team",
            "stars": 63764,
            "url": "https://github.com/keras-team/keras"
        },
        {
            "name": "open-interpreter",
            "owner": "openinterpreter",
            "stars": 62109,
            "url": "https://github.com/openinterpreter/open-interpreter"
        },
        {
            "name": "openpilot",
            "owner": "commaai",
            "stars": 60057,
            "url": "https://github.com/commaai/openpilot"
        },
        {
            "name": "OpenBB",
            "owner": "OpenBB-finance",
            "stars": 60056,
            "url": "https://github.com/OpenBB-finance/OpenBB"
        },
        {
            "name": "crawl4ai",
            "owner": "unclecode",
            "stars": 59734,
            "url": "https://github.com/unclecode/crawl4ai"
        },
        {
            "name": "scrapy",
            "owner": "scrapy",
            "stars": 59701,
            "url": "https://github.com/scrapy/scrapy"
        },
        {
            "name": "Real-Time-Voice-Cloning",
            "owner": "CorentinJ",
            "stars": 59331,
            "url": "https://github.com/CorentinJ/Real-Time-Voice-Cloning"
        },
        {
            "name": "pathway",
            "owner": "pathwaycom",
            "stars": 59314,
            "url": "https://github.com/pathwaycom/pathway"
        },
        {
            "name": "llama",
            "owner": "meta-llama",
            "stars": 59137,
            "url": "https://github.com/meta-llama/llama"
        },
        {
            "name": "30-Days-Of-Python",
            "owner": "Asabeneh",
            "stars": 57627,
            "url": "https://github.com/Asabeneh/30-Days-Of-Python"
        },
        {
            "name": "private-gpt",
            "owner": "zylon-ai",
            "stars": 57108,
            "url": "https://github.com/zylon-ai/private-gpt"
        },
        {
            "name": "yolov5",
            "owner": "ultralytics",
            "stars": 56808,
            "url": "https://github.com/ultralytics/yolov5"
        },
        {
            "name": "you-get",
            "owner": "soimort",
            "stars": 56732,
            "url": "https://github.com/soimort/you-get"
        },
        {
            "name": "face_recognition",
            "owner": "ageitgey",
            "stars": 56112,
            "url": "https://github.com/ageitgey/face_recognition"
        },
        {
            "name": "rich",
            "owner": "Textualize",
            "stars": 55440,
            "url": "https://github.com/Textualize/rich"
        },
        {
            "name": "gpt-engineer",
            "owner": "AntonOsika",
            "stars": 55214,
            "url": "https://github.com/AntonOsika/gpt-engineer"
        },
        {
            "name": "faceswap",
            "owner": "deepfakes",
            "stars": 54963,
            "url": "https://github.com/deepfakes/faceswap"
        },
        {
            "name": "hackingtool",
            "owner": "Z4nzu",
            "stars": 54941,
            "url": "https://github.com/Z4nzu/hackingtool"
        },
        {
            "name": "GPT-SoVITS",
            "owner": "RVC-Boss",
            "stars": 54913,
            "url": "https://github.com/RVC-Boss/GPT-SoVITS"
        },
        {
            "name": "autogen",
            "owner": "microsoft",
            "stars": 54468,
            "url": "https://github.com/microsoft/autogen"
        },
        {
            "name": "OpenManus",
            "owner": "FoundationAgents",
            "stars": 54415,
            "url": "https://github.com/FoundationAgents/OpenManus"
        },
        {
            "name": "MinerU",
            "owner": "opendatalab",
            "stars": 54208,
            "url": "https://github.com/opendatalab/MinerU"
        },
        {
            "name": "requests",
            "owner": "psf",
            "stars": 53728,
            "url": "https://github.com/psf/requests"
        },
        {
            "name": "ultralytics",
            "owner": "ultralytics",
            "stars": 53165,
            "url": "https://github.com/ultralytics/ultralytics"
        },
        {
            "name": "nanoGPT",
            "owner": "karpathy",
            "stars": 52878,
            "url": "https://github.com/karpathy/nanoGPT"
        },
        {
            "name": "docling",
            "owner": "docling-project",
            "stars": 52684,
            "url": "https://github.com/docling-project/docling"
        },
        {
            "name": "unsloth",
            "owner": "unslothai",
            "stars": 51852,
            "url": "https://github.com/unslothai/unsloth"
        },
        {
            "name": "grok-1",
            "owner": "xai-org",
            "stars": 51483,
            "url": "https://github.com/xai-org/grok-1"
        },
        {
            "name": "n8n-workflows",
            "owner": "Zie619",
            "stars": 51204,
            "url": "https://github.com/Zie619/n8n-workflows"
        },
        {
            "name": "professional-programming",
            "owner": "charlax",
            "stars": 50356,
            "url": "https://github.com/charlax/professional-programming"
        },
        {
            "name": "MoneyPrinterTurbo",
            "owner": "harry0703",
            "stars": 49470,
            "url": "https://github.com/harry0703/MoneyPrinterTurbo"
        },
        {
            "name": "odoo",
            "owner": "odoo",
            "stars": 48948,
            "url": "https://github.com/odoo/odoo"
        },
        {
            "name": "pandas",
            "owner": "pandas-dev",
            "stars": 47852,
            "url": "https://github.com/pandas-dev/pandas"
        },
        {
            "name": "Fooocus",
            "owner": "lllyasviel",
            "stars": 47689,
            "url": "https://github.com/lllyasviel/Fooocus"
        },
        {
            "name": "big-list-of-naughty-strings",
            "owner": "minimaxir",
            "stars": 47584,
            "url": "https://github.com/minimaxir/big-list-of-naughty-strings"
        },
        {
            "name": "mem0",
            "owner": "mem0ai",
            "stars": 47088,
            "url": "https://github.com/mem0ai/mem0"
        },
        {
            "name": "llama_index",
            "owner": "run-llama",
            "stars": 46928,
            "url": "https://github.com/run-llama/llama_index"
        },
        {
            "name": "freqtrade",
            "owner": "freqtrade",
            "stars": 46675,
            "url": "https://github.com/freqtrade/freqtrade"
        },
        {
            "name": "TrendRadar",
            "owner": "sansan0",
            "stars": 46076,
            "url": "https://github.com/sansan0/TrendRadar"
        },
        {
            "name": "text-generation-webui",
            "owner": "oobabooga",
            "stars": 46035,
            "url": "https://github.com/oobabooga/text-generation-webui"
        },
        {
            "name": "ai-hedge-fund",
            "owner": "virattt",
            "stars": 45725,
            "url": "https://github.com/virattt/ai-hedge-fund"
        },
        {
            "name": "TTS",
            "owner": "coqui-ai",
            "stars": 44516,
            "url": "https://github.com/coqui-ai/TTS"
        },
        {
            "name": "airflow",
            "owner": "apache",
            "stars": 44224,
            "url": "https://github.com/apache/airflow"
        },
        {
            "name": "crewAI",
            "owner": "crewAIInc",
            "stars": 43956,
            "url": "https://github.com/crewAIInc/crewAI"
        },
        {
            "name": "MediaCrawler",
            "owner": "NanmiCoder",
            "stars": 43823,
            "url": "https://github.com/NanmiCoder/MediaCrawler"
        },
        {
            "name": "streamlit",
            "owner": "streamlit",
            "stars": 43442,
            "url": "https://github.com/streamlit/streamlit"
        },
        {
            "name": "Summer2026-Internships",
            "owner": "SimplifyJobs",
            "stars": 43359,
            "url": "https://github.com/SimplifyJobs/Summer2026-Internships"
        },
        {
            "name": "sentry",
            "owner": "getsentry",
            "stars": 43134,
            "url": "https://github.com/getsentry/sentry"
        },
        {
            "name": "nanochat",
            "owner": "karpathy",
            "stars": 42856,
            "url": "https://github.com/karpathy/nanochat"
        },
        {
            "name": "python-patterns",
            "owner": "faif",
            "stars": 42745,
            "url": "https://github.com/faif/python-patterns"
        },
        {
            "name": "copyparty",
            "owner": "9001",
            "stars": 42312,
            "url": "https://github.com/9001/copyparty"
        },
        {
            "name": "mitmproxy",
            "owner": "mitmproxy",
            "stars": 42255,
            "url": "https://github.com/mitmproxy/mitmproxy"
        },
        {
            "name": "ailearning",
            "owner": "apachecn",
            "stars": 42029,
            "url": "https://github.com/apachecn/ailearning"
        },
        {
            "name": "Umi-OCR",
            "owner": "hiroi-sora",
            "stars": 42028,
            "url": "https://github.com/hiroi-sora/Umi-OCR"
        },
        {
            "name": "diagrams",
            "owner": "mingrammer",
            "stars": 42007,
            "url": "https://github.com/mingrammer/diagrams"
        },
        {
            "name": "gradio",
            "owner": "gradio-app",
            "stars": 41661,
            "url": "https://github.com/gradio-app/gradio"
        },
        {
            "name": "DeepSpeed",
            "owner": "deepspeedai",
            "stars": 41595,
            "url": "https://github.com/deepspeedai/DeepSpeed"
        },
        {
            "name": "black",
            "owner": "psf",
            "stars": 41376,
            "url": "https://github.com/psf/black"
        },
        {
            "name": "ColossalAI",
            "owner": "hpcaitech",
            "stars": 41347,
            "url": "https://github.com/hpcaitech/ColossalAI"
        },
        {
            "name": "exo",
            "owner": "exo-explore",
            "stars": 41347,
            "url": "https://github.com/exo-explore/exo"
        },
        {
            "name": "chatgpt-on-wechat",
            "owner": "zhayujie",
            "stars": 41230,
            "url": "https://github.com/zhayujie/chatgpt-on-wechat"
        },
        {
            "name": "ChatGLM-6B",
            "owner": "zai-org",
            "stars": 41226,
            "url": "https://github.com/zai-org/ChatGLM-6B"
        },
        {
            "name": "ray",
            "owner": "ray-project",
            "stars": 41219,
            "url": "https://github.com/ray-project/ray"
        },
        {
            "name": "ccxt",
            "owner": "ccxt",
            "stars": 40892,
            "url": "https://github.com/ccxt/ccxt"
        },
        {
            "name": "cheat.sh",
            "owner": "chubin",
            "stars": 40889,
            "url": "https://github.com/chubin/cheat.sh"
        },
        {
            "name": "aider",
            "owner": "Aider-AI",
            "stars": 40509,
            "url": "https://github.com/Aider-AI/aider"
        },
        {
            "name": "bert",
            "owner": "google-research",
            "stars": 39849,
            "url": "https://github.com/google-research/bert"
        },
        {
            "name": "Deep-Learning-Papers-Reading-Roadmap",
            "owner": "floodsung",
            "stars": 39478,
            "url": "https://github.com/floodsung/Deep-Learning-Papers-Reading-Roadmap"
        },
        {
            "name": "FastChat",
            "owner": "lm-sys",
            "stars": 39404,
            "url": "https://github.com/lm-sys/FastChat"
        },
        {
            "name": "minimind",
            "owner": "jingyaogong",
            "stars": 39303,
            "url": "https://github.com/jingyaogong/minimind"
        },
        {
            "name": "quivr",
            "owner": "QuivrHQ",
            "stars": 38925,
            "url": "https://github.com/QuivrHQ/quivr"
        },
        {
            "name": "ChatTTS",
            "owner": "2noise",
            "stars": 38698,
            "url": "https://github.com/2noise/ChatTTS"
        },
        {
            "name": "mindsdb",
            "owner": "mindsdb",
            "stars": 38440,
            "url": "https://github.com/mindsdb/mindsdb"
        },
        {
            "name": "python-cheatsheet",
            "owner": "gto76",
            "stars": 38216,
            "url": "https://github.com/gto76/python-cheatsheet"
        },
        {
            "name": "agno",
            "owner": "agno-agi",
            "stars": 37772,
            "url": "https://github.com/agno-agi/agno"
        },
        {
            "name": "cli",
            "owner": "httpie",
            "stars": 37527,
            "url": "https://github.com/httpie/cli"
        },
        {
            "name": "Open-Assistant",
            "owner": "LAION-AI",
            "stars": 37457,
            "url": "https://github.com/LAION-AI/Open-Assistant"
        },
        {
            "name": "GFPGAN",
            "owner": "TencentARC",
            "stars": 37385,
            "url": "https://github.com/TencentARC/GFPGAN"
        },
        {
            "name": "Langchain-Chatchat",
            "owner": "chatchat-space",
            "stars": 37285,
            "url": "https://github.com/chatchat-space/Langchain-Chatchat"
        },
        {
            "name": "qlib",
            "owner": "microsoft",
            "stars": 37243,
            "url": "https://github.com/microsoft/qlib"
        },
        {
            "name": "interview_internal_reference",
            "owner": "0voice",
            "stars": 37173,
            "url": "https://github.com/0voice/interview_internal_reference"
        },
        {
            "name": "gym",
            "owner": "openai",
            "stars": 37032,
            "url": "https://github.com/openai/gym"
        },
        {
            "name": "wtfpython",
            "owner": "satwikkansal",
            "stars": 36895,
            "url": "https://github.com/satwikkansal/wtfpython"
        },
        {
            "name": "MockingBird",
            "owner": "babysor",
            "stars": 36880,
            "url": "https://github.com/babysor/MockingBird"
        },
        {
            "name": "manim",
            "owner": "ManimCommunity",
            "stars": 36727,
            "url": "https://github.com/ManimCommunity/manim"
        },
        {
            "name": "sqlmap",
            "owner": "sqlmapproject",
            "stars": 36574,
            "url": "https://github.com/sqlmapproject/sqlmap"
        },
        {
            "name": "paperless-ngx",
            "owner": "paperless-ngx",
            "stars": 36485,
            "url": "https://github.com/paperless-ngx/paperless-ngx"
        },
        {
            "name": "supervision",
            "owner": "roboflow",
            "stars": 36479,
            "url": "https://github.com/roboflow/supervision"
        },
        {
            "name": "vnpy",
            "owner": "vnpy",
            "stars": 36367,
            "url": "https://github.com/vnpy/vnpy"
        },
        {
            "name": "pytorch-image-models",
            "owner": "huggingface",
            "stars": 36351,
            "url": "https://github.com/huggingface/pytorch-image-models"
        },
        {
            "name": "HanLP",
            "owner": "hankcs",
            "stars": 36128,
            "url": "https://github.com/hankcs/HanLP"
        },
        {
            "name": "GPT_API_free",
            "owner": "chatanywhere",
            "stars": 36006,
            "url": "https://github.com/chatanywhere/GPT_API_free"
        },
        {
            "name": "DragGAN",
            "owner": "XingangPan",
            "stars": 35976,
            "url": "https://github.com/XingangPan/DragGAN"
        },
        {
            "name": "OpenVoice",
            "owner": "myshell-ai",
            "stars": 35924,
            "url": "https://github.com/myshell-ai/OpenVoice"
        },
        {
            "name": "litellm",
            "owner": "BerriAI",
            "stars": 35729,
            "url": "https://github.com/BerriAI/litellm"
        },
        {
            "name": "BettaFish",
            "owner": "666ghj",
            "stars": 35464,
            "url": "https://github.com/666ghj/BettaFish"
        },
        {
            "name": "jax",
            "owner": "jax-ml",
            "stars": 34838,
            "url": "https://github.com/jax-ml/jax"
        },
        {
            "name": "jieba",
            "owner": "fxsjy",
            "stars": 34755,
            "url": "https://github.com/fxsjy/jieba"
        },
        {
            "name": "Python",
            "owner": "geekcomputers",
            "stars": 34722,
            "url": "https://github.com/geekcomputers/Python"
        },
        {
            "name": "Retrieval-based-Voice-Conversion-WebUI",
            "owner": "RVC-Project",
            "stars": 34379,
            "url": "https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebUI"
        },
        {
            "name": "Hello-Python",
            "owner": "mouredev",
            "stars": 34354,
            "url": "https://github.com/mouredev/Hello-Python"
        },
        {
            "name": "Real-ESRGAN",
            "owner": "xinntao",
            "stars": 34316,
            "url": "https://github.com/xinntao/Real-ESRGAN"
        },
        {
            "name": "TaskMatrix",
            "owner": "chenfei-wu",
            "stars": 34275,
            "url": "https://github.com/chenfei-wu/TaskMatrix"
        },
        {
            "name": "textual",
            "owner": "Textualize",
            "stars": 34207,
            "url": "https://github.com/Textualize/textual"
        },
        {
            "name": "poetry",
            "owner": "python-poetry",
            "stars": 34199,
            "url": "https://github.com/python-poetry/poetry"
        },
        {
            "name": "12306",
            "owner": "testerSunshine",
            "stars": 34187,
            "url": "https://github.com/testerSunshine/12306"
        },
        {
            "name": "detectron2",
            "owner": "facebookresearch",
            "stars": 34062,
            "url": "https://github.com/facebookresearch/detectron2"
        },
        {
            "name": "gpt-pilot",
            "owner": "Pythagora-io",
            "stars": 33767,
            "url": "https://github.com/Pythagora-io/gpt-pilot"
        },
        {
            "name": "awesome-claude-skills",
            "owner": "ComposioHQ",
            "stars": 33720,
            "url": "https://github.com/ComposioHQ/awesome-claude-skills"
        },
        {
            "name": "ControlNet",
            "owner": "lllyasviel",
            "stars": 33634,
            "url": "https://github.com/lllyasviel/ControlNet"
        },
        {
            "name": "shadowsocks",
            "owner": "shadowsocks",
            "stars": 33634,
            "url": "https://github.com/shadowsocks/shadowsocks"
        },
        {
            "name": "XX-Net",
            "owner": "XX-net",
            "stars": 33427,
            "url": "https://github.com/XX-net/XX-Net"
        },
        {
            "name": "spaCy",
            "owner": "explosion",
            "stars": 33185,
            "url": "https://github.com/explosion/spaCy"
        },
        {
            "name": "certbot",
            "owner": "certbot",
            "stars": 32823,
            "url": "https://github.com/certbot/certbot"
        },
        {
            "name": "diffusers",
            "owner": "huggingface",
            "stars": 32744,
            "url": "https://github.com/huggingface/diffusers"
        },
        {
            "name": "OCRmyPDF",
            "owner": "ocrmypdf",
            "stars": 32577,
            "url": "https://github.com/ocrmypdf/OCRmyPDF"
        },
        {
            "name": "khoj",
            "owner": "khoj-ai",
            "stars": 32479,
            "url": "https://github.com/khoj-ai/khoj"
        },
        {
            "name": "mmdetection",
            "owner": "open-mmlab",
            "stars": 32396,
            "url": "https://github.com/open-mmlab/mmdetection"
        },
        {
            "name": "pytorch-tutorial",
            "owner": "yunjey",
            "stars": 32176,
            "url": "https://github.com/yunjey/pytorch-tutorial"
        },
        {
            "name": "linux-insides",
            "owner": "0xAX",
            "stars": 32164,
            "url": "https://github.com/0xAX/linux-insides"
        },
        {
            "name": "fairseq",
            "owner": "facebookresearch",
            "stars": 32152,
            "url": "https://github.com/facebookresearch/fairseq"
        },
        {
            "name": "dspy",
            "owner": "stanfordnlp",
            "stars": 32127,
            "url": "https://github.com/stanfordnlp/dspy"
        },
        {
            "name": "PDFMathTranslate",
            "owner": "PDFMathTranslate",
            "stars": 31756,
            "url": "https://github.com/PDFMathTranslate/PDFMathTranslate"
        },
        {
            "name": "erpnext",
            "owner": "frappe",
            "stars": 31682,
            "url": "https://github.com/frappe/erpnext"
        },
        {
            "name": "glances",
            "owner": "nicolargo",
            "stars": 31626,
            "url": "https://github.com/nicolargo/glances"
        },
        {
            "name": "marker",
            "owner": "datalab-to",
            "stars": 31582,
            "url": "https://github.com/datalab-to/marker"
        },
        {
            "name": "numpy",
            "owner": "numpy",
            "stars": 31415,
            "url": "https://github.com/numpy/numpy"
        },
        {
            "name": "tinygrad",
            "owner": "tinygrad",
            "stars": 31345,
            "url": "https://github.com/tinygrad/tinygrad"
        },
        {
            "name": "CheatSheetSeries",
            "owner": "OWASP",
            "stars": 31334,
            "url": "https://github.com/OWASP/CheatSheetSeries"
        },
        {
            "name": "posthog",
            "owner": "PostHog",
            "stars": 31203,
            "url": "https://github.com/PostHog/posthog"
        },
        {
            "name": "kitty",
            "owner": "kovidgoyal",
            "stars": 31193,
            "url": "https://github.com/kovidgoyal/kitty"
        },
        {
            "name": "interactive-coding-challenges",
            "owner": "donnemartin",
            "stars": 31161,
            "url": "https://github.com/donnemartin/interactive-coding-challenges"
        },
        {
            "name": "tqdm",
            "owner": "tqdm",
            "stars": 30951,
            "url": "https://github.com/tqdm/tqdm"
        },
        {
            "name": "graphrag",
            "owner": "microsoft",
            "stars": 30892,
            "url": "https://github.com/microsoft/graphrag"
        },
        {
            "name": "pytorch-lightning",
            "owner": "Lightning-AI",
            "stars": 30828,
            "url": "https://github.com/Lightning-AI/pytorch-lightning"
        },
        {
            "name": "ChatDev",
            "owner": "OpenBMB",
            "stars": 30814,
            "url": "https://github.com/OpenBMB/ChatDev"
        },
        {
            "name": "ML-From-Scratch",
            "owner": "eriklindernoren",
            "stars": 30716,
            "url": "https://github.com/eriklindernoren/ML-From-Scratch"
        },
        {
            "name": "roop",
            "owner": "s0md3v",
            "stars": 30511,
            "url": "https://github.com/s0md3v/roop"
        },
        {
            "name": "DeepFaceLive",
            "owner": "iperov",
            "stars": 30504,
            "url": "https://github.com/iperov/DeepFaceLive"
        },
        {
            "name": "ui-ux-pro-max-skill",
            "owner": "nextlevelbuilder",
            "stars": 30444,
            "url": "https://github.com/nextlevelbuilder/ui-ux-pro-max-skill"
        },
        {
            "name": "algo",
            "owner": "trailofbits",
            "stars": 30332,
            "url": "https://github.com/trailofbits/algo"
        },
        {
            "name": "stanford_alpaca",
            "owner": "tatsu-lab",
            "stars": 30269,
            "url": "https://github.com/tatsu-lab/stanford_alpaca"
        },
        {
            "name": "changedetection.io",
            "owner": "dgtlmoon",
            "stars": 30188,
            "url": "https://github.com/dgtlmoon/changedetection.io"
        },
        {
            "name": "openai-python",
            "owner": "openai",
            "stars": 29888,
            "url": "https://github.com/openai/openai-python"
        },
        {
            "name": "django-rest-framework",
            "owner": "encode",
            "stars": 29869,
            "url": "https://github.com/encode/django-rest-framework"
        },
        {
            "name": "jumpserver",
            "owner": "jumpserver",
            "stars": 29847,
            "url": "https://github.com/jumpserver/jumpserver"
        },
        {
            "name": "hosts",
            "owner": "StevenBlack",
            "stars": 29814,
            "url": "https://github.com/StevenBlack/hosts"
        },
        {
            "name": "TradingAgents",
            "owner": "TauricResearch",
            "stars": 29749,
            "url": "https://github.com/TauricResearch/TradingAgents"
        },
        {
            "name": "Jobs_Applier_AI_Agent_AIHawk",
            "owner": "feder-cr",
            "stars": 29344,
            "url": "https://github.com/feder-cr/Jobs_Applier_AI_Agent_AIHawk"
        },
        {
            "name": "llama3",
            "owner": "meta-llama",
            "stars": 29240,
            "url": "https://github.com/meta-llama/llama3"
        },
        {
            "name": "langextract",
            "owner": "google",
            "stars": 29166,
            "url": "https://github.com/google/langextract"
        },
        {
            "name": "EasyOCR",
            "owner": "JaidedAI",
            "stars": 28938,
            "url": "https://github.com/JaidedAI/EasyOCR"
        },
        {
            "name": "data-science-ipython-notebooks",
            "owner": "donnemartin",
            "stars": 28861,
            "url": "https://github.com/donnemartin/data-science-ipython-notebooks"
        },
        {
            "name": "python-telegram-bot",
            "owner": "python-telegram-bot",
            "stars": 28783,
            "url": "https://github.com/python-telegram-bot/python-telegram-bot"
        },
        {
            "name": "wttr.in",
            "owner": "chubin",
            "stars": 28749,
            "url": "https://github.com/chubin/wttr.in"
        },
        {
            "name": "linkedin-skill-assessments-quizzes",
            "owner": "Ebazhanov",
            "stars": 28663,
            "url": "https://github.com/Ebazhanov/linkedin-skill-assessments-quizzes"
        },
        {
            "name": "PythonRobotics",
            "owner": "AtsushiSakai",
            "stars": 28616,
            "url": "https://github.com/AtsushiSakai/PythonRobotics"
        },
        {
            "name": "Open-Sora",
            "owner": "hpcaitech",
            "stars": 28521,
            "url": "https://github.com/hpcaitech/Open-Sora"
        },
        {
            "name": "BitNet",
            "owner": "microsoft",
            "stars": 28364,
            "url": "https://github.com/microsoft/BitNet"
        },
        {
            "name": "agents",
            "owner": "wshobson",
            "stars": 28355,
            "url": "https://github.com/wshobson/agents"
        },
        {
            "name": "LightRAG",
            "owner": "HKUDS",
            "stars": 28234,
            "url": "https://github.com/HKUDS/LightRAG"
        },
        {
            "name": "redash",
            "owner": "getredash",
            "stars": 28216,
            "url": "https://github.com/getredash/redash"
        },
        {
            "name": "d2l-en",
            "owner": "d2l-ai",
            "stars": 28138,
            "url": "https://github.com/d2l-ai/d2l-en"
        },
        {
            "name": "Genesis",
            "owner": "Genesis-Embodied-AI",
            "stars": 28119,
            "url": "https://github.com/Genesis-Embodied-AI/Genesis"
        },
        {
            "name": "python-fire",
            "owner": "google",
            "stars": 28105,
            "url": "https://github.com/google/python-fire"
        },
        {
            "name": "reflex",
            "owner": "reflex-dev",
            "stars": 28089,
            "url": "https://github.com/reflex-dev/reflex"
        },
        {
            "name": "spleeter",
            "owner": "deezer",
            "stars": 28031,
            "url": "https://github.com/deezer/spleeter"
        },
        {
            "name": "celery",
            "owner": "celery",
            "stars": 27998,
            "url": "https://github.com/celery/celery"
        },
        {
            "name": "so-vits-svc",
            "owner": "svc-develop-team",
            "stars": 27992,
            "url": "https://github.com/svc-develop-team/so-vits-svc"
        },
        {
            "name": "ChatGPT",
            "owner": "acheong08",
            "stars": 27982,
            "url": "https://github.com/acheong08/ChatGPT"
        },
        {
            "name": "storm",
            "owner": "stanford-oval",
            "stars": 27896,
            "url": "https://github.com/stanford-oval/storm"
        },
        {
            "name": "insightface",
            "owner": "deepinsight",
            "stars": 27844,
            "url": "https://github.com/deepinsight/insightface"
        },
        {
            "name": "GitHub520",
            "owner": "521xueweihan",
            "stars": 27832,
            "url": "https://github.com/521xueweihan/GitHub520"
        },
        {
            "name": "cascadia-code",
            "owner": "microsoft",
            "stars": 27510,
            "url": "https://github.com/microsoft/cascadia-code"
        },
        {
            "name": "locust",
            "owner": "locustio",
            "stars": 27481,
            "url": "https://github.com/locustio/locust"
        },
        {
            "name": "Hitomi-Downloader",
            "owner": "KurtBestor",
            "stars": 27428,
            "url": "https://github.com/KurtBestor/Hitomi-Downloader"
        },
        {
            "name": "generative-models",
            "owner": "Stability-AI",
            "stars": 26910,
            "url": "https://github.com/Stability-AI/generative-models"
        },
        {
            "name": "mihomo",
            "owner": "MetaCubeX",
            "stars": 26823,
            "url": "https://github.com/MetaCubeX/mihomo"
        },
        {
            "name": "ArchiveBox",
            "owner": "ArchiveBox",
            "stars": 26822,
            "url": "https://github.com/ArchiveBox/ArchiveBox"
        },
        {
            "name": "pydantic",
            "owner": "pydantic",
            "stars": 26762,
            "url": "https://github.com/pydantic/pydantic"
        },
        {
            "name": "facefusion",
            "owner": "facefusion",
            "stars": 26737,
            "url": "https://github.com/facefusion/facefusion"
        },
        {
            "name": "ItChat",
            "owner": "littlecodersh",
            "stars": 26706,
            "url": "https://github.com/littlecodersh/ItChat"
        },
        {
            "name": "Qwen3",
            "owner": "QwenLM",
            "stars": 26549,
            "url": "https://github.com/QwenLM/Qwen3"
        },
        {
            "name": "Detectron",
            "owner": "facebookresearch",
            "stars": 26410,
            "url": "https://github.com/facebookresearch/Detectron"
        },
        {
            "name": "YouCompleteMe",
            "owner": "ycm-core",
            "stars": 26343,
            "url": "https://github.com/ycm-core/YouCompleteMe"
        },
        {
            "name": "deep-learning-for-image-processing",
            "owner": "WZMIAOMIAO",
            "stars": 26073,
            "url": "https://github.com/WZMIAOMIAO/deep-learning-for-image-processing"
        },
        {
            "name": "mkdocs-material",
            "owner": "squidfunk",
            "stars": 26011,
            "url": "https://github.com/squidfunk/mkdocs-material"
        },
        {
            "name": "open-r1",
            "owner": "huggingface",
            "stars": 25876,
            "url": "https://github.com/huggingface/open-r1"
        },
        {
            "name": "MiniGPT-4",
            "owner": "Vision-CAIR",
            "stars": 25761,
            "url": "https://github.com/Vision-CAIR/MiniGPT-4"
        },
        {
            "name": "ungoogled-chromium",
            "owner": "ungoogled-software",
            "stars": 25720,
            "url": "https://github.com/ungoogled-software/ungoogled-chromium"
        },
        {
            "name": "Mask_RCNN",
            "owner": "matterport",
            "stars": 25519,
            "url": "https://github.com/matterport/Mask_RCNN"
        },
        {
            "name": "smolagents",
            "owner": "huggingface",
            "stars": 25395,
            "url": "https://github.com/huggingface/smolagents"
        },
        {
            "name": "gpt-researcher",
            "owner": "assafelovic",
            "stars": 25284,
            "url": "https://github.com/assafelovic/gpt-researcher"
        },
        {
            "name": "flux",
            "owner": "black-forest-labs",
            "stars": 25209,
            "url": "https://github.com/black-forest-labs/flux"
        },
        {
            "name": "pipenv",
            "owner": "pypa",
            "stars": 25109,
            "url": "https://github.com/pypa/pipenv"
        },
        {
            "name": "kotaemon",
            "owner": "Cinnamon",
            "stars": 25019,
            "url": "https://github.com/Cinnamon/kotaemon"
        },
        {
            "name": "vit-pytorch",
            "owner": "lucidrains",
            "stars": 24990,
            "url": "https://github.com/lucidrains/vit-pytorch"
        },
        {
            "name": "algorithms",
            "owner": "keon",
            "stars": 24974,
            "url": "https://github.com/keon/algorithms"
        },
        {
            "name": "agenticSeek",
            "owner": "Fosowl",
            "stars": 24956,
            "url": "https://github.com/Fosowl/agenticSeek"
        },
        {
            "name": "pytorch-CycleGAN-and-pix2pix",
            "owner": "junyanz",
            "stars": 24940,
            "url": "https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix"
        },
        {
            "name": "fish-speech",
            "owner": "fishaudio",
            "stars": 24868,
            "url": "https://github.com/fishaudio/fish-speech"
        },
        {
            "name": "searxng",
            "owner": "searxng",
            "stars": 24867,
            "url": "https://github.com/searxng/searxng"
        },
        {
            "name": "labelImg",
            "owner": "HumanSignal",
            "stars": 24781,
            "url": "https://github.com/HumanSignal/labelImg"
        },
        {
            "name": "cookiecutter",
            "owner": "cookiecutter",
            "stars": 24656,
            "url": "https://github.com/cookiecutter/cookiecutter"
        },
        {
            "name": "gpt-2",
            "owner": "openai",
            "stars": 24608,
            "url": "https://github.com/openai/gpt-2"
        },
        {
            "name": "zulip",
            "owner": "zulip",
            "stars": 24590,
            "url": "https://github.com/zulip/zulip"
        },
        {
            "name": "langgraph",
            "owner": "langchain-ai",
            "stars": 24580,
            "url": "https://github.com/langchain-ai/langgraph"
        },
        {
            "name": "JARVIS",
            "owner": "microsoft",
            "stars": 24547,
            "url": "https://github.com/microsoft/JARVIS"
        },
        {
            "name": "dash",
            "owner": "plotly",
            "stars": 24463,
            "url": "https://github.com/plotly/dash"
        },
        {
            "name": "LLaVA",
            "owner": "haotian-liu",
            "stars": 24440,
            "url": "https://github.com/haotian-liu/LLaVA"
        },
        {
            "name": "mlflow",
            "owner": "mlflow",
            "stars": 24083,
            "url": "https://github.com/mlflow/mlflow"
        },
        {
            "name": "calibre",
            "owner": "kovidgoyal",
            "stars": 24071,
            "url": "https://github.com/kovidgoyal/calibre"
        },
        {
            "name": "spotify-downloader",
            "owner": "spotDL",
            "stars": 23884,
            "url": "https://github.com/spotDL/spotify-downloader"
        },
        {
            "name": "examples",
            "owner": "pytorch",
            "stars": 23739,
            "url": "https://github.com/pytorch/examples"
        },
        {
            "name": "maple-font",
            "owner": "subframe7536",
            "stars": 23702,
            "url": "https://github.com/subframe7536/maple-font"
        },
        {
            "name": "MiniCPM-o",
            "owner": "OpenBMB",
            "stars": 23673,
            "url": "https://github.com/OpenBMB/MiniCPM-o"
        },
        {
            "name": "loguru",
            "owner": "Delgan",
            "stars": 23579,
            "url": "https://github.com/Delgan/loguru"
        },
        {
            "name": "ultimatevocalremovergui",
            "owner": "Anjok07",
            "stars": 23527,
            "url": "https://github.com/Anjok07/ultimatevocalremovergui"
        },
        {
            "name": "minGPT",
            "owner": "karpathy",
            "stars": 23507,
            "url": "https://github.com/karpathy/minGPT"
        },
        {
            "name": "sglang",
            "owner": "sgl-project",
            "stars": 23494,
            "url": "https://github.com/sgl-project/sglang"
        },
        {
            "name": "pytorch_geometric",
            "owner": "pyg-team",
            "stars": 23468,
            "url": "https://github.com/pyg-team/pytorch_geometric"
        },
        {
            "name": "awesome-claude-code",
            "owner": "hesreallyhim",
            "stars": 23382,
            "url": "https://github.com/hesreallyhim/awesome-claude-code"
        },
        {
            "name": "Open-AutoGLM",
            "owner": "zai-org",
            "stars": 23318,
            "url": "https://github.com/zai-org/Open-AutoGLM"
        },
        {
            "name": "algo",
            "owner": "wangzheng0822",
            "stars": 23200,
            "url": "https://github.com/wangzheng0822/algo"
        },
        {
            "name": "pandas-ai",
            "owner": "sinaptik-ai",
            "stars": 23161,
            "url": "https://github.com/sinaptik-ai/pandas-ai"
        },
        {
            "name": "proxy_pool",
            "owner": "jhao104",
            "stars": 23142,
            "url": "https://github.com/jhao104/proxy_pool"
        },
        {
            "name": "VibeVoice",
            "owner": "microsoft",
            "stars": 23125,
            "url": "https://github.com/microsoft/VibeVoice"
        },
        {
            "name": "NLP-progress",
            "owner": "sebastianruder",
            "stars": 22979,
            "url": "https://github.com/sebastianruder/NLP-progress"
        },
        {
            "name": "DeepSeek-Coder",
            "owner": "deepseek-ai",
            "stars": 22770,
            "url": "https://github.com/deepseek-ai/DeepSeek-Coder"
        },
        {
            "name": "fastmcp",
            "owner": "jlowin",
            "stars": 22761,
            "url": "https://github.com/jlowin/fastmcp"
        },
        {
            "name": "chinese-independent-blogs",
            "owner": "timqian",
            "stars": 22759,
            "url": "https://github.com/timqian/chinese-independent-blogs"
        },
        {
            "name": "IOPaint",
            "owner": "Sanster",
            "stars": 22717,
            "url": "https://github.com/Sanster/IOPaint"
        },
        {
            "name": "graphiti",
            "owner": "getzep",
            "stars": 22692,
            "url": "https://github.com/getzep/graphiti"
        },
        {
            "name": "vanna",
            "owner": "vanna-ai",
            "stars": 22644,
            "url": "https://github.com/vanna-ai/vanna"
        },
        {
            "name": "ddia",
            "owner": "Vonng",
            "stars": 22595,
            "url": "https://github.com/Vonng/ddia"
        },
        {
            "name": "saleor",
            "owner": "saleor",
            "stars": 22589,
            "url": "https://github.com/saleor/saleor"
        },
        {
            "name": "Scrapegraph-ai",
            "owner": "ScrapeGraphAI",
            "stars": 22585,
            "url": "https://github.com/ScrapeGraphAI/Scrapegraph-ai"
        },
        {
            "name": "chatterbox",
            "owner": "resemble-ai",
            "stars": 22542,
            "url": "https://github.com/resemble-ai/chatterbox"
        },
        {
            "name": "DeepSeek-OCR",
            "owner": "deepseek-ai",
            "stars": 22448,
            "url": "https://github.com/deepseek-ai/DeepSeek-OCR"
        },
        {
            "name": "tornado",
            "owner": "tornadoweb",
            "stars": 22445,
            "url": "https://github.com/tornadoweb/tornado"
        },
        {
            "name": "iptv-api",
            "owner": "Guovin",
            "stars": 22354,
            "url": "https://github.com/Guovin/iptv-api"
        },
        {
            "name": "matplotlib",
            "owner": "matplotlib",
            "stars": 22322,
            "url": "https://github.com/matplotlib/matplotlib"
        },
        {
            "name": "magic-wormhole",
            "owner": "magic-wormhole",
            "stars": 22321,
            "url": "https://github.com/magic-wormhole/magic-wormhole"
        },
        {
            "name": "flash-attention",
            "owner": "Dao-AILab",
            "stars": 22193,
            "url": "https://github.com/Dao-AILab/flash-attention"
        },
        {
            "name": "deepface",
            "owner": "serengil",
            "stars": 22183,
            "url": "https://github.com/serengil/deepface"
        },
        {
            "name": "localGPT",
            "owner": "PromtEngineer",
            "stars": 22180,
            "url": "https://github.com/PromtEngineer/localGPT"
        },
        {
            "name": "babyagi",
            "owner": "yoheinakajima",
            "stars": 22137,
            "url": "https://github.com/yoheinakajima/babyagi"
        },
        {
            "name": "Gooey",
            "owner": "chriskiehl",
            "stars": 22044,
            "url": "https://github.com/chriskiehl/Gooey"
        },
        {
            "name": "mlc-llm",
            "owner": "mlc-ai",
            "stars": 22023,
            "url": "https://github.com/mlc-ai/mlc-llm"
        },
        {
            "name": "unilm",
            "owner": "microsoft",
            "stars": 22019,
            "url": "https://github.com/microsoft/unilm"
        }
    ],
    "meta": {
        "run_time": "2026-02-11T06:41:36.849484+00:00",
        "total_quotes": 100,
        "total_repos": 300,
        "failures": 0
    }
}
