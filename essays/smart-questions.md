---
layout: essay
type: essay
title: "Smart Questions, Good Answers"
# All dates must be YYYY-MM-DD format!
date: 2022-09-08
published: true
labels:
  - Questions
  - Answers
  - StackOverflow
---

<p>
  insert text here
<a href='https://stackoverflow.com/questions/62046304/i-am-trying-to-move-my-character-but-instead-of-that-the-player-wont-move'>testing<a>
  insert text here
  </p>
  <h2> "There is no such thing as a stupid question" They Said...</h2>

Growing up, I've often heard people, especially teachers, encourage others to ask questions if they are confused.  I've heard the notion that "there is no such thing as a dumb question" tossed around quite often.  However, is that *really* true or are people who use that phrase (especially teachers) merely sugarcoating reality?  If StackOverflow has taught me anything, it is definitely the latter.  
  
  
  
  ## The foolproof way to get ignored.

While there are decent questions that benefit everyone, there are those one can ask to create an entirely different effect. In the following example, a user asks how he would, in short, create a desktop application with Facebook.
<a href='https://meta.stackoverflow.com/questions/400643/what-should-i-do-if-i-am-post-banned-but-i-can-not-modify-any-of-my-bad-question'>Not-so-good-question</a> asked by Hydro on StackOverflow
```So. I am trying to move my character. I wrote it just like in a tutorial. It didn't work so I tried to fix it but just 
ruined other things. Can someone please tell me what the problem is? It would be also nice if someone would tell me how 
to resize the objects, buttons, etc when I maximize my Pygame Window? I don't know what the errors mean. Can someone 
please try this code on their own and then tell me what they mean and what to do? Here is the code:```

A simple “yes” would have answered the question, but we know that’s not the sort of answer he or she is looking for. Fortunately, someone kindly responded with a link to Facebook’s developer website. The asker should have done more research on his or her potential project. Then further down the road, he or she could have asked more specific and detailed questions that wouldn’t require a thousand-paged response for a sufficient answer.

## What’s a smart question?


  
  <a href='https://stackoverflow.com/questions/11227809/why-is-processing-a-sorted-array-faster-than-processing-an-unsorted-array>An example of a good question</a> asked by GManNickG




```
A: datetime and the datetime.timedelta classes are your friend.

1. find today
2. use that to find the first day of this month.
3. use timedelta to backup a single day, to the last day of the previous month.
4. print the YYYYMM string you're looking for.

Like this:

 >>> import datetime
 >>> today = datetime.date.today()
 >>> first = datetime.date(day=1, month=today.month, year=today.year)
 >>> lastMonth = first - datetime.timedelta(days=1)
 >>> print lastMonth.strftime("%Y%m")
 201202
 >>>

```
 
The asker received six possible answers, and he or she was successful in inciting discussion from multiple users. The answers themselves were clear and were devoid of the rumored sarcasm and hostility of “hackers.” Since I myself have referenced this page and found it useful, I can confidently say that it is a good question.



## Conclusion

When we rely on others’ generosity and expertise to provide answers to our questions, it should hold that the question we ask should be one that leads to efficient and effective help that not only benefits us, but also the people we ask and others who might ask the same question in the future. Thus, if you have a question… make it a smart one! Asking questions may not always get you the best answer, but asking them in a way that will make others want to answer them will increase the success of finding a good solution and make it a positive experience on all sides.
