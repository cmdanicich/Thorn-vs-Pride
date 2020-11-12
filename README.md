# Thorn-vs-Pride

## Dataset share

### Dataset Source: Twitter
This dataset utilizes data scraped from twitter.com using the Twitter API to gather the followers of two accounts; the @ThornsFC and @ORLPride. This data comes in the form of two text files including user handle, name, location, followers count, friend count, and bio description. I love soccer and this was a great way to analyze two rival teams with small enough followings that my computer didn’t explode. 

### Dataset Description:
The first text file, ThornsFC_followers.txt, contains 122 tab-delimited rows that includes basic account information as mentioned above. The second file, ORLPride_followers.txt, contains 116 rows of the same nature. 

### Descriptive Statistics:
Before starting on the descriptive stats, I split on whitespace, shifted to lowercase, and removed all stop-words from both .txt files. 

THORNSFC
-	Tokens: 661
-	Unique Tokens: 571
-	Average Token Length: 6.29
-	Lexical Diversity: .864
-	Top 10 Tokens: (sports, like, soccer, high, zambia, love, good, football, twitter, meowbertsenpai)

ORLPRIDE
-	Tokens: 723
-	Unique Tokens: 596
-	Average Token Length: 6.24
-	Lexical Diversity: .824
-	Top 10 Tokens: (usa, soccer, high, de, sports, love, fl, class, chelsea, ecnl) 

### Interesting Questions: 
1.	Where are followers located? Same city as team? Same state? Same region?
2.	Are more tweets tweeted on game days?

### Next Steps: 
I think the first question could be a little more interesting – where are followers located. You could follow this up by seeing if more Pride followers are location in Orlando or FL in general and same with the Portland Thorns. To do this, instead of using a followers list, I would scrape either the hashtag #orlpride or #thornsfc. Once collected and written to a text file I would use pandas to graph common locations of users tweeting the hashtag.

