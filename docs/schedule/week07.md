---
icon: lucide/play
title: Week 7
---

# Week 7 - Data about data

While we're not doing advanced stats in this class, we do need to know some things about how data works and how to visualize it. We'll cover the basics with a focus on how to use data in your project. We'll also take time to setup your domain and WordPress site. 

### Prep for Tuesday: 

* Read [Defining Data for Humanists](https://journalofdigitalhumanities.org/1-1/defining-data-for-humanists-by-trevor-owens/)
* Read [chapter 1](https://trinachi.github.io/data-design-builds/ch01.html) + [chapter 12](https://trinachi.github.io/data-design-builds/ch12.html). Browse the rest of book to get a sense of what it offers, what you might have learned in other classes, and what you might bookmark for help later. 

## Tuesday, October 20, 2026

* icebreaker
* lecture: how data works
* Lab: Turn your comment analysis into data
	* Work in the same groups as Thursday's comment analysis lab. Your starting material is your marked-up printout. You'll turn it into a small dataset in Google Sheets, then make charts that show something you noticed last week.
	* We're not doing statistics here. Counts, comparisons, and clear charts are enough. What we're practicing is the part that comes before the chart: deciding what counts as data. 
	* Research question: What does the data from your comment section show?
??? info
	
	* **Part 1: Make your dataset**
		* Start with a focus, not a spreadsheet. Look at your Week 6 discourse analysis and choose one thing you noticed that you could check with counts. For example: "most comments were jokes, not reactions to the post," or "the comments at the top of the feed were more negative than the ones at the bottom." 
		* Brainstorm everything you could record, then cut. Before you open Google Sheets, spend a few minutes listing every piece of information you could write down about each comment. Then decide which ones help you check your focus. Here are some places to start. They're possibilities, not requirements:
			* About the comment itself: the exact text, its position in the comment order, word count, whether it has emojis,date or time commented (if shown)
			* How people reacted to it: likes, number of replies, whether the creator liked it
			* Your interpretation: the category you gave it in Thursday's "Sort" step, tone (sincere, joking, sarcastic, unclear), who it's aimed at, whether it uses slang or algospeak, whether you'd need an in-joke to understand it, whether it agrees with the post
		* Choose at least 3 pieces of information to turn into columns on your spreadsheet. One column has to be an ID (C01, C02...) for each comment, and one should have the text of the comment. Everything else is your call. Your group should be able to answer these questions about your dataset:
			* Why is each column there? What does it help you check? 
			* What are the allowed values, and how did you decide? For example, for a column like "tone," what makes a comment sarcastic and not just joking?
			* Which of your columns are measurements, and which are interpretation? Word count is a measurement. Tone is an interpretation. Interpretation columns need the clearest rules, because two people can read the same comment differently
		* Set up the spreadsheet. Create three tabs: Data, Viz, and Notes. Your comment data will go into rows and columns in Data, the charts you make will go in Viz, and anything that would be helpful for you to have written down for your process (maybe your focus or any rules about, for example, what constitutes a joke vs pushback) will go in Notes.
			* Each comment has its own row. Each column is a variable about the comments. Fill in the first row with your column headers (eg: ID, comment text, etc.) No merged cells and no blank rows between entries (this is good practice for a clean dataset).
			* Enter all of your comments and their variables.
			* Leave out usernames. The commenters are ordinary people who posted without knowing their comments would end up in a class dataset. Thinking about that is part of research ethics: even when data is public, it’s good practice to collect only what you need.
		* Keep your data clean as you go
			* Keep labels consistent. Otherwise "Joke," "joke," and "jokes" become three different categories and your counts will be wrong.
			* Keep number columns as plain numbers. Only numbers, nothing like "N/A" or "lots." Leave a cell blank if you don't have the value. If a platform shows "1.2K likes," enter 1200.
			* Word count formula: `=IF(E2="","",COUNTA(SPLIT(E2," ")))` counts the words in cell E2. Change E2 to wherever your comment text is, and fill it down.
	* **Part 1: Make your dataset**
		* Make at least two charts that help you look into your focus. You choose the chart types. Use what we covered in lecture about what each type is good at showing.
		* How to choose: For each chart, decide what you want to show (a comparison, parts of a whole, how values are spread out, a relationship, or change over an order), which column or columns you need, and which chart type fits.
		* Match the chart to the data. A chart type can make the wrong point. A pie chart with ten slices or a line chart across unordered categories will mislead your reader.
		* Making a chart in Sheets
			* Select the column (or the rows of the column) you want to chart, including the header. To select two columns, click the first one, hold Cmd (Mac) or Ctrl (Windows), then click the second one.
			* Click Insert → Chart. Sheets will create a chart with a type of its own suggestion.
			* In the chart editor on the right, open the setup tab and use the chart type dropdown menu to choose your type. If the chart groups the wrong way (for example, one bar per tone instead of one bar per category), check switch rows/columns. If a header is being plotted as data, check use row 1 as headers. If Sheets draws one bar per comment instead of counting each label, check aggregate under the X-axis.
			* Open the customize tab. Under chart & axis titles, add a chart title and axis titles. Under series, you can change colors, add data labels so the numbers appear on the chart, or add a trendline to a scatter chart. 
			* Put the chart on the Viz tab. New charts appear on top of your data, so move each one when it looks right. Click the chart, click the three dots in its top right corner, and choose copy chart. Go to the Viz tab, click an empty cell, and paste. Then go back to the Data tab and delete the original chart. To edit a chart later, double-click it on the Summary tab.
		* Make each chart readable:
			* Write the title as a finding, not a label. "Most comments on the post were jokes" is a title. "Tone counts" isn't. You may need to make the chart first and then write the title.
			* Label both axes with what they measure.
	* **Part 3: Share and discuss as a class**
		* Reconvene as a class. Each group shows their Summary tab and takes about two minutes to share: what did your charts show, and how does that connect to last week's discourse analysis? Why did you choose the charts you did?

### Prep for Thursday: 

* Read [When the Designer Shows Up in the Design](https://www.propublica.org/article/when-the-designer-shows-up-in-the-design)
* Read [Why 'A Domain of One's Own' Matters (For the Future of Knowledge)](https://hackeducation.com/2017/04/04/domains)


## Thursday, October 22, 2026

* icebreaker
* Discussion
* Lab: domain + WordPress 
	* [Intro to WordPress](https://learn.wordpress.org/lesson/introduction-to-wordpress-2/)
	* There's now a page on the course website called [Domain](https://mackenziekbrooks.github.io/dci1001-f26/domain/) with more info.

## Week 7 homework

### Project Brainstorm

Time to start thinking seriously about your project for the rest of the term. 

1. First step, read the project description on the [Assignments page](https://mackenziekbrooks.github.io/dci1001-f26/assignments/#unit-2-project-research-project-prospectus). 

2. Then, revisit the [Week 5 slides](https://docs.google.com/presentation/d/1EoJ5RiTCyMOJJTPobBHX4vloOMz9cL8bowFV6ZWRPQI/edit?usp=sharing) with example projects. Follow the links to articles or websites and explore a bit. 

3. Paper brainstorming. Using the questions from the Week 5 slides, do some brainstorming on paper. You can make a grid with four quadrants to map the four sections of sections, or you can make a mind map with circles and lines. There is no right answer here, the purpose is to explore and brainstorm and make connections and spark ideas. 

	* Curiosity - What am I interested in? What is my major/minor or classes I have enjoyed? What is it about that subject that interests me? What am I interested in outside of school? 
	* Currency - What am I reading about in the news right now? What kind of news do I read and where does it come from? “News” can be broadly defined! 
	* Local - What’s going on around me? Campus/town/home/home on the internet? What phenomena or patterns can I observe? What are other students concerned with? 
	* Digital - What am I observing online right now? What changes have happened on a platform I spend time on? What apps do I use the most?

4. Maybe let that brainstorming sit for a day or two. Come back and make a list of three potential topics, subjects, and accompanying research questions. A topic is something like "Fandom Reactions to AI," the subject is "a particular forum, social media page, hashtag, etc" and the research questions could be, "of all the posts in this forum, how many are positive/negative? What are the major issues at play?"

5. Turn in the following: 

	* A photo of your brainstorming paper. 
	* Your answers to part #4. 
	* Post both things to a Wordpress post. Turn in the URL of your post on Canvas. Remember, it should be the published post URL, not the edit screen URL. 



