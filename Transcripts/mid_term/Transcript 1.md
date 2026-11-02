WEBVTT

1
00:07:57.020 --> 00:08:01.050
Faculty (Olympus): Hi, is anyone from the Great Learning Team

2
00:08:01.160 --> 00:08:03.999
Faculty (Olympus): Here, or any of the TAs for this course?

3
00:08:04.000 --> 00:08:04.940
Faculty (Olympus): Yes, yes, I am.

4
00:08:05.270 --> 00:08:09.800
Faculty (Olympus): Okay, alright, so you're able to see my video, orâ€¦

5
00:08:10.540 --> 00:08:11.719
Faculty (Olympus): Yes, I can.

6
00:08:11.720 --> 00:08:19.030
Faculty (Olympus): Okay, alright, let me also try and share my screen, andâ€¦ And my audio is clear?

7
00:08:19.480 --> 00:08:20.519
Faculty (Olympus): Yes, it is.

8
00:08:21.820 --> 00:08:24.630
Faculty (Olympus): Okay, what about the slides now?

9
00:08:29.870 --> 00:08:31.250
Faculty (Olympus): One second.

10
00:08:33.169 --> 00:08:34.909
Faculty (Olympus): So now I cannot see anything.

11
00:08:34.909 --> 00:08:36.859
Faculty (Olympus): Okay, one second,

12
00:08:45.199 --> 00:08:46.079
Faculty (Olympus): True.

13
00:08:46.419 --> 00:08:47.369
Faculty (Olympus): Yeah.

14
00:08:47.370 --> 00:08:48.420
Faculty (Olympus): you know, Sabh specifically.

15
00:08:49.290 --> 00:08:52.440
Faculty (Olympus): Okay, alright, okay, we'll start in a few minutes.

16
00:10:48.170 --> 00:10:56.170
Faculty (Olympus): Okay, good evening, everyone. We'll wait, for a couple more minutes while people join, and then we'll begin.

17
00:12:02.890 --> 00:12:10.749
Faculty (Olympus): Okay, let's, let's start. So, firstly, welcome, everyone, to

18
00:12:10.780 --> 00:12:27.329
Faculty (Olympus): the PGD program, and also the first lecture on, statistic, statistical foundations of machine learning. So, today is going to be an introductory lecture. I want to essentially cover,

19
00:12:27.330 --> 00:12:36.620
Faculty (Olympus): one, the logistics of the course, and secondly, I want to give you some flavor and some motivation for why

20
00:12:36.670 --> 00:12:44.509
Faculty (Olympus): one wants to study probability and how probability and statistical foundations are used in ML.

21
00:12:44.560 --> 00:12:59.299
Faculty (Olympus): And, from next lecture on, we'll really dive into the formal details, okay? So, let's begin. So, by the way, the way, we are going to structure, our lectures is that,

22
00:12:59.420 --> 00:13:13.340
Faculty (Olympus): We'll have a few breakpoints, okay? So, moreâ€¦ mostly, maybe 2 to 3 breakpoints, in between. I would urge that you hold on to your questions for those breakpoints.

23
00:13:13.450 --> 00:13:32.460
Faculty (Olympus): And the breakpoints will roughly be maybe, you know, every 20 minutes or so, or depending on what a suitable breakpoint is in between topics or something like that. That is the usual practice we are going to follow. And then I will have a sufficient amount at the end of the lecture

24
00:13:32.460 --> 00:13:38.049
Faculty (Olympus): For you to clear any remaining doubts, okay? So we'llâ€¦ we'll usually follow this practice.

25
00:13:38.960 --> 00:13:54.839
Faculty (Olympus): Okay, so let's start. So, firstly, my name is Nick Hill, and I'm one of the co-instructors of this course. The other instructor is Professor Manjunat. I'll be conducting the first half of the course, that is pre-med sim, and then the second half will be

26
00:13:54.960 --> 00:13:56.350
Faculty (Olympus): Prade of Samanjanat.

27
00:13:56.480 --> 00:13:57.230
Faculty (Olympus): Okay?

28
00:13:57.450 --> 00:14:12.140
Faculty (Olympus): Now, in terms of the evaluation of this course, I just want to clear that up immediately. We will have 3 main components. There will be some homeworks that will be

29
00:14:12.210 --> 00:14:24.120
Faculty (Olympus): Given to you every, maybe, maybe across the, across the entire, semester, it might be maybe 4 to 5 homeworks.

30
00:14:24.120 --> 00:14:32.529
Faculty (Olympus): Which, will haveâ€¦ usually these will be large practice sets, out of which only 4 or 5 you have to solve and submit.

31
00:14:32.730 --> 00:14:42.190
Faculty (Olympus): The remaining are essentially problems that are related to the content that we are doing, which will be solved in the TA sessions, okay?

32
00:14:42.190 --> 00:14:58.030
Faculty (Olympus): So, every Saturday, I think, you have your TA sessions, and the TA sessions will also be conducted inâ€¦ there will be two parallel streams in the TA session. One stream will be a little slower, they will go over every detail.

33
00:14:58.060 --> 00:15:15.599
Faculty (Olympus): And try to solve everything, really from first principles in a very detailed manner. The other one will be a little faster, which will try and cover maybe more problems, okay? So both of these streams will be running in parallel. You are free to choose whichever one you are more comfortable with.

34
00:15:15.600 --> 00:15:24.519
Faculty (Olympus): Of course, the videos of both of these will be available to you anytime, okay? So anyway, so the homework component accounts for 15% of the grade.

35
00:15:24.520 --> 00:15:35.439
Faculty (Olympus): We will have an online mid-sem, which will account for another 15, and the in-person Nsem will account for 70% of the grade. Okay, so this is, howâ€¦

36
00:15:37.030 --> 00:15:48.880
Faculty (Olympus): the marks will be structured, like you would have been told. You have to score a certain minimum level in the NSEMs for you to clear the course, which I think is 40%.

37
00:15:49.400 --> 00:15:50.130
Faculty (Olympus): Okay?

38
00:15:50.390 --> 00:15:55.720
Faculty (Olympus): So that'sâ€¦ that's mainly, for the evaluation.

39
00:15:55.990 --> 00:16:11.860
Faculty (Olympus): I will, at the end of the lecture, I will also provide you with a list of, references. In particular, I mean, there is a bunch of different books that one can look at. Probability is a veryâ€¦ and statistics are very, very widely studied topics.

40
00:16:11.860 --> 00:16:17.550
Faculty (Olympus): But there is one particular book which I'll recommend for a lot of the material that we cover.

41
00:16:17.650 --> 00:16:26.979
Faculty (Olympus): And if there is material which is outside, that book, then I'll suggest it as and when we go along, okay?

42
00:16:27.170 --> 00:16:34.729
Faculty (Olympus): Okay, so let's, let's maybe begin now. So, just to introduce,

43
00:16:35.140 --> 00:16:53.760
Faculty (Olympus): Probability and statistics, and why we have this as one of the foundational courses of this program on machine learning, is that probability and statistics are essentially the two pillars on which machine learning stands, and the third one may be being computation, which links

44
00:16:53.760 --> 00:17:09.220
Faculty (Olympus): these two together, and one way of thinking about where statistics and probability play a role is you can think of the statistics, okay, as essentially being a backward engine. So, what you generally observe

45
00:17:09.220 --> 00:17:21.730
Faculty (Olympus): in practice is data, right? Suppose you're running a firm which does credit analysis, you will be seeing a lot of transactions and data related to transactions.

46
00:17:21.730 --> 00:17:41.130
Faculty (Olympus): Or if your company, like, let's say you are an e-commerce company, and you're trying to get a sense of, you know, your user behavior, then you would have a lot of data about when users log in, how much time do they spend on a particular page, how often do they buy something.

47
00:17:41.130 --> 00:17:49.559
Faculty (Olympus): And so on. So, again, data related to user activity. So, what you usually see in practice isâ€¦ is data.

48
00:17:49.730 --> 00:18:03.450
Faculty (Olympus): You then look at this data, and statistics is one way of, essentially, given certain data, you want to come up with a model for how that data might have been generated.

49
00:18:03.470 --> 00:18:20.869
Faculty (Olympus): Okay? So that is what statistics usually will give you. For example, like, a very basic thing might be, if you are, again, for example, if you are a web app company who's tracking their user activity, you might be inâ€¦ you might look at the data and might be interested in theâ€¦

50
00:18:20.870 --> 00:18:25.580
Faculty (Olympus): Average or mean amount of time that a user spends

51
00:18:25.580 --> 00:18:29.779
Faculty (Olympus): On your, on your website.

52
00:18:29.790 --> 00:18:49.510
Faculty (Olympus): Or you might be interested in, given, let's say, a user spends 10 minutes on my app, how likely is the user to buy something from my website? So, each of this is like building a model for a user, okay? So, the statistics is like a backward engine. You look at the data, and then you try and come up with a model.

53
00:18:49.510 --> 00:18:58.659
Faculty (Olympus): On the other hand, probability kind of plays the opposite angle, which is the forward engine. So now that you have a model.

54
00:18:59.030 --> 00:19:09.420
Faculty (Olympus): You now want to use this model to make predictions, okay? You want to use this model for a user to predict future outcomes, which you haven't seen so far.

55
00:19:09.420 --> 00:19:22.890
Faculty (Olympus): Right? So, again, now, let's say, having seen, past data, maybe you feel that, okay, if a user spends 15 minutes on my website, they are very, very likely to buy something.

56
00:19:22.920 --> 00:19:37.119
Faculty (Olympus): Right? So now, I will use this kind of data to create a model for the likelihood of a user buying something from the website, given they have spent, let's say, X minutes on the website.

57
00:19:37.250 --> 00:19:55.709
Faculty (Olympus): And then use this to predict future outcomes. So when I see that a particular user is spending, let's say, 12 minutes, I now have a certain likelihood of how much this user isâ€¦ how likely is this user to buy something. I can use this kind of probabilistic information to maybe, you know.

58
00:19:55.890 --> 00:20:15.800
Faculty (Olympus): offer some discount to the user, or point them in the direction of something new that has come up, or give them newer recommendations, and so on. So all kinds of things can be built on top of it. So these are essentially the two modules, okay? One is statistics, which builds on top of data that you already have, so it uses that data to create a model.

59
00:20:15.940 --> 00:20:32.849
Faculty (Olympus): And then the probability side of things uses this model to predict future outcomes, okay? So these are kind of two phases of the coin, if you will, and what I want to do today is just to give you some sense ofâ€¦ we'll go through a few case studies.

60
00:20:32.850 --> 00:20:55.409
Faculty (Olympus): of possible applications of ideas, and a lot of what we cover might not be immediately familiar to you, but these are exactly the kind of concepts we will actually formally do through the course. So I just want to give you a sense of how some of these concepts are used in practice, or can be used in practice, and then we will

61
00:20:55.410 --> 00:20:58.250
Faculty (Olympus): See them again through the course, okay?

62
00:20:58.500 --> 00:21:09.700
Faculty (Olympus): Okay, so let's begin with, case study one. So, the first case study is about a fintech company. Let's say this company gives out loans.

63
00:21:09.920 --> 00:21:26.039
Faculty (Olympus): Okay, and the company, I mean, any such company will have to regularly make a classification decision, right? It has a user whose application has come in, and they have to decide whether or not to offer them a loan based on whatever information they might have.

64
00:21:26.040 --> 00:21:34.610
Faculty (Olympus): Okay, so let's say we have one such VinTech app, it needs to decide whether to give a particular user a daily 10,000 rupees loan or not.

65
00:21:35.010 --> 00:21:37.880
Faculty (Olympus): But the user does not have any credit history.

66
00:21:37.920 --> 00:21:50.140
Faculty (Olympus): So we essentially have to somehow decide, right, based on some information, we have to decide whether the user will be able to pay back this money if we loan it to the user or not.

67
00:21:50.140 --> 00:22:00.850
Faculty (Olympus): Right? So we have to decide something about, or predict, or estimate the liquidity of this user, daily liquidity of the user. Will the user have enough money

68
00:22:00.850 --> 00:22:12.289
Faculty (Olympus): to return back this loan or not? Or how likely is the user to default, right? So let's say we somehow gather 10 days of UPI transactions of this particular user.

69
00:22:12.310 --> 00:22:31.400
Faculty (Olympus): And let's say the raw data looks something like this. Okay, so for this user, there are 10 days, and on each of the days, this is the spend that the user has, right? So if the spend is low, then we can assume that the user has saved enough, and so is more likely to have enough money to return our loan.

70
00:22:31.400 --> 00:22:33.369
Faculty (Olympus): But if the user is spending too much.

71
00:22:33.370 --> 00:22:36.620
Faculty (Olympus): Then they're unlikely to have enough money left

72
00:22:36.620 --> 00:22:44.690
Faculty (Olympus): For them to return back our loan, right? That is kind of the broad idea. So let's say this is what we see.

73
00:22:44.690 --> 00:22:57.610
Faculty (Olympus): Now, more or less, you can see, theâ€¦ the value is, most days is maybe around 400, 450, but then there is this one Day 5, which is like a massive outlier.

74
00:22:57.890 --> 00:23:07.459
Faculty (Olympus): Right? So we have to kind of now come up with some way of accumulating all of this data into some reasonable statistic that we can use.

75
00:23:07.460 --> 00:23:20.190
Faculty (Olympus): Right? So what isâ€¦ what is a reasonable statistic to use? So one possible statistic is, of course, you have 10 days of data, you can think of the average spend of the user, and then use that as a statistic to make your decision.

76
00:23:20.190 --> 00:23:28.720
Faculty (Olympus): Right? So if I compute, like, the average of those 10 values, you can check that that turns out to be something like 1225.

77
00:23:28.860 --> 00:23:29.730
Faculty (Olympus): Right?

78
00:23:29.910 --> 00:23:43.310
Faculty (Olympus): So, what has happened is that that oneâ€¦ while on all other days the spend was roughly around $400, $500, that one outlier day has really stretched this out to 1,000, right?

79
00:23:43.570 --> 00:23:57.580
Faculty (Olympus): On the other hand, another possible statistic is a median. So in theâ€¦ in computing a median, what you do is you sort out the values in increasing or decreasing order, and then you take the middle point.

80
00:23:58.060 --> 00:24:15.989
Faculty (Olympus): Okay? So that is the median value. So again, these are the UPI spends, we have sorted them in increasing order, and then the median could be the average of the middle two values. Okay, so you can see that this, turns out to be 415,

81
00:24:15.990 --> 00:24:35.380
Faculty (Olympus): It'sâ€¦ maybe is a slightly better statistic than the mean, because the mean seems to be highly inflated by one outlier, whereas the median seems to be much more robust to outliers, right? So when I have some data, and I'm trying to, let's say, come up with a statistic to describe

82
00:24:35.410 --> 00:24:46.420
Faculty (Olympus): that data. Often, you will see that people use median instead of the mean as a compressed statistic, because the median turns out to be much more robust

83
00:24:46.500 --> 00:24:54.770
Faculty (Olympus): to noise, okay? So, when I say much more robust to noise, what do I mean? Can I quantify, this robustness

84
00:24:54.770 --> 00:24:59.889
Faculty (Olympus): to noise. So let's see a very simple example, okay? Let's say we have,

85
00:24:59.890 --> 00:25:16.779
Faculty (Olympus): a situation where there is, we are getting data, but 10% of the data is noise. Okay, so let's in fact take a very, very crude example, or a very stylized example. Let's say, we are looking at the spends, again, of a user.

86
00:25:16.780 --> 00:25:22.820
Faculty (Olympus): and withâ€¦ 90% chance, or 0.9 probability, the spend is going to be exactly 500.

87
00:25:23.140 --> 00:25:32.609
Faculty (Olympus): Okay, exactly 500 on each day. Thisâ€¦ there is 90% chance of that, but 10% chance of there being an outlier jump of 50,000.

88
00:25:32.630 --> 00:25:45.220
Faculty (Olympus): Okay, so like I said, I mean, I'm creating, like, a very stylized example just to illustrate a point. So, let's say the spend can be either 500, with probability 0.9,

89
00:25:45.390 --> 00:25:54.849
Faculty (Olympus): or 50,000 with probability 0.1. And let's see how these two statistics, the mean and the median, behave under such data.

90
00:25:55.290 --> 00:26:02.799
Faculty (Olympus): Okay? So what would happen to the mean? What would be the mean spend, or the average spend, under such data?

91
00:26:03.010 --> 00:26:16.940
Faculty (Olympus): So the mean would behave something like this, right? It'll be 0.9. With probability 0.9, the value is 500, and with probability 0.1, the value is 50,000, so this is the mean spend, or the expected

92
00:26:16.940 --> 00:26:24.499
Faculty (Olympus): Spend that you will see if you have this kind of data coming in, which turns out to be something like $5,450.

93
00:26:24.890 --> 00:26:26.950
Faculty (Olympus): Okay? So, very high value.

94
00:26:27.310 --> 00:26:41.480
Faculty (Olympus): On the other hand, like, and this is what is happening, which is that the mean, even though 90% of the time you're getting 500, this 10% of the time, because the value is very large, it is getting pulled in that direction.

95
00:26:42.180 --> 00:26:51.320
Faculty (Olympus): Okay? So it doesn'tâ€¦ it kind of fails to represent the majority behavior. It kind of is dragged by outliers very heavily.

96
00:26:52.010 --> 00:27:07.920
Faculty (Olympus): On the other hand, if I now want to, let's say, so for the median, like we said, what we do is we just, we just sort the values that we are going to get, right? So the two possible values in this case over 10 days is either 500 or 50,000.

97
00:27:08.420 --> 00:27:17.650
Faculty (Olympus): If the median has to switch to 50,000, then more than half of the values have to be 50,000. Only then will the median get pulled

98
00:27:17.730 --> 00:27:24.800
Faculty (Olympus): to 50,000 instead of 500, right? Because for the case of the median, recall that all we do is we kind of justâ€¦

99
00:27:24.860 --> 00:27:44.410
Faculty (Olympus): sort the values out, and then we take the middle point, right? So if the median has to go from 500 to 50,000, you have to have more than half of the values have to be outliers, right? So more than 6 out of the 10 days, we have to see 50,000. So what is the likelihood of seeing a data like that?

100
00:27:44.520 --> 00:27:55.269
Faculty (Olympus): So, we have 10 experiments, you can think of this as 10 experiments that we are doing, and the probability of seeing a 50,000 is 0.1.

101
00:27:55.370 --> 00:28:09.269
Faculty (Olympus): Right? Probability of seeing 500 is 0.9, and probability of seeing 50,000 is 0.1. So what isâ€¦ what is this, quantity telling us? This quantity

102
00:28:09.650 --> 00:28:15.090
Faculty (Olympus): Let's seeâ€¦ So, okay, if I look at this particular quantity.

103
00:28:15.200 --> 00:28:26.569
Faculty (Olympus): This is telling me what is theâ€¦ so this is looking at K possible 50,000, seeing K values of 50,000 amongst

104
00:28:26.900 --> 00:28:37.430
Faculty (Olympus): the 10 experiments that we are doing. So, 10 choose k illustrates out of 10 choosing K values, or K positions where you saw 50,000.

105
00:28:37.560 --> 00:28:50.720
Faculty (Olympus): 0.1 to the par K gives us what is the probability of actually seeing these 50,000 k times, and 0.9 to the par 10 minus K tells me what is the probability of seeing

106
00:28:50.980 --> 00:28:59.489
Faculty (Olympus): 510 minus k times, right? So k equals 6 means you are seeing 6

107
00:28:59.540 --> 00:29:10.610
Faculty (Olympus): days of $50,000 spent, and 4 days of, 500 spent. K equals 7 means you're seeing 7 days of $50,000 spent.

108
00:29:10.610 --> 00:29:30.559
Faculty (Olympus): and 3 days of 500 spend, and so on, right? So the probability that you'll see more than half outliers is given by this quantity, okay? So the exact expression, I don't want you to worry about it if you haven't seen this before, or you're not following it, because this is exactly the kind of thing we will do. We willâ€¦ we willâ€¦

109
00:29:30.610 --> 00:29:44.490
Faculty (Olympus): kind of formalize why this turns out to be the exact probability, but this is what we willâ€¦ you would want to compute. You want to computeâ€¦ for the median to become 50,000, you will have to have more than 6 outliers.

110
00:29:44.500 --> 00:29:56.229
Faculty (Olympus): Right? Now, you can do this computation, and you can do the calculation explicitly, and it'll turn out to be just 1.01%, not even 1%, 0.01%, right?

111
00:29:56.230 --> 00:30:05.039
Faculty (Olympus): So the probâ€¦ so while the mean, right, under this 10% of noise, the mean went off from 500 to around 5,000,

112
00:30:05.670 --> 00:30:09.369
Faculty (Olympus): You can see that for the median to shift from 500,

113
00:30:09.520 --> 00:30:12.859
Faculty (Olympus): Right? That probability is really, really low.

114
00:30:13.230 --> 00:30:18.430
Faculty (Olympus): It's 0.01%. So the median is really a very, very robust

115
00:30:18.490 --> 00:30:29.819
Faculty (Olympus): estimator, especially in the presence of noise or in the presence of outliers. Median is a very, very robust statistic and is used very often, as opposed to mean.

116
00:30:29.870 --> 00:30:42.859
Faculty (Olympus): Right? So if I have to give youâ€¦ if I'm looking at this user, and I have to just come up with one number, or one statistic to kind of, grade this user, or judge this user.

117
00:30:42.860 --> 00:30:50.689
Faculty (Olympus): then I shouldn't go with the mean spend, I should go with the median spend, because it is much, much more robust, it is much more representative

118
00:30:50.690 --> 00:30:52.640
Faculty (Olympus): Of what the underlying data is.

119
00:30:53.020 --> 00:30:53.880
Faculty (Olympus): Okay?

120
00:30:54.150 --> 00:31:12.250
Faculty (Olympus): how do we use this median, or how do we use any such statistic that we'll come to next? But maybe I'll take a short pause here, and if there are any questions, please raise your hand using Zoom, and then I can

121
00:31:12.320 --> 00:31:16.120
Faculty (Olympus): I can ask, or I can point, towards each of you.

122
00:31:36.810 --> 00:31:38.490
Faculty (Olympus): Okay, yeah, Rashmi, go ahead.

123
00:31:41.270 --> 00:31:47.289
Rashmi .: Professor, I was just, thinking about a very odd case, just like we were talking about loan scenario.

124
00:31:47.580 --> 00:32:02.020
Rashmi .: And you very well explained that, you know, how, median benefits over mean, if we take, you know, that as one of the formula or, you know, method to follow, generally, in this case. But I was thinking what, how about a very, you know.

125
00:32:02.090 --> 00:32:07.400
Rashmi .: A very odd and weird case where we're talking about loan scenario, and one person

126
00:32:07.400 --> 00:32:30.550
Rashmi .: Because probably he understands the mathematics behind the formula that, you know, the loan company's using, and he follows that formula that, you know, he would spend 29 days a consistent, lower, spend, but then on one day, he would, knowingly and willingly go, you know, behave as outlier. So, this, this looks like a breaching, you know, scenario.

127
00:32:30.550 --> 00:32:38.150
Rashmi .: he could benefit from this scenario. So how would such cases be handled by, you know, if we really take median as the way to go?

128
00:32:38.150 --> 00:32:52.270
Faculty (Olympus): Yeah, yeah, which is why, exactly why, if you see, none of the app companies release any information about how they make a decision, right? Because if they make that known, people will start gaming it immediately.

129
00:32:52.530 --> 00:33:05.619
Faculty (Olympus): Right? So, none of these decisions is ever made based on one parameter, right? I'm saying median spend as a parameter and taking decision based on median, but usually it'll never be one particular

130
00:33:05.620 --> 00:33:14.979
Faculty (Olympus): parameter that makes a decision about, one way or the other. It'll usually be a much, much larger vector of features. Maybe the median spend is one such feature.

131
00:33:15.040 --> 00:33:19.370
Faculty (Olympus): Which goes into making the decision, but it'll be many, many more things.

132
00:33:19.610 --> 00:33:38.840
Faculty (Olympus): So, for example, if maybe the user does something like this, and on one particular month, they manage to fool the company and, you know, do this, but the next moment, one of the features that will go is also how, like, you know, what the historical performance of this user has been.

133
00:33:38.850 --> 00:33:50.419
Faculty (Olympus): Or have they defaulted on other loans? All of these features also go into the algorithm that decides on this. It is never based on a single parameter.

134
00:33:50.570 --> 00:33:59.119
Faculty (Olympus): But you're absolutely right. If we release information about how the decision is being made, very often people will game it.

135
00:34:00.070 --> 00:34:01.200
Rashmi .: Thank you, Professor.

136
00:34:01.200 --> 00:34:03.200
Faculty (Olympus): Sure. Sanketh?

137
00:34:03.780 --> 00:34:06.410
Bipin Karyakarte .: Sorry, Nikhar, I'm not able to raise my hand.

138
00:34:06.810 --> 00:34:08.199
Faculty (Olympus): Okay,

139
00:34:08.580 --> 00:34:10.840
Bipin Karyakarte .: Sorry for butting in.

140
00:34:12.280 --> 00:34:12.920
Faculty (Olympus): Go ahead.

141
00:34:12.929 --> 00:34:32.539
Bipin Karyakarte .: Yeah, yeah. Can you go back to that previous slide where you gave that, this thing? Yeah, so the equation that you have there, right? Yeah. What I assume, and what I understood from your earlier talk is that right now, we should not worry about how we arrived at this equation, or how to read this equation, how to understand this equation, right?

142
00:34:32.540 --> 00:34:33.109
Faculty (Olympus): Yeah, yeah.

143
00:34:33.230 --> 00:34:37.050
Bipin Karyakarte .: That is what we will be covering in the next few days, or months, or.

144
00:34:37.050 --> 00:34:38.550
Faculty (Olympus): Yeah, yeah, yeah, yeah, yeah, absolutely.

145
00:34:38.550 --> 00:34:46.730
Bipin Karyakarte .: So right now, right now, we are just trying to understand the concept of mean, median, and how they affect, and, you know, that's at a very broad level, right?

146
00:34:46.730 --> 00:34:57.429
Faculty (Olympus): Yeah, yeah, yeah. So right now, all I want to kind of put forward is how statistics and probability play a role in decision-making

147
00:34:57.430 --> 00:35:12.809
Faculty (Olympus): Inâ€¦ in the real world. That's it. Any of these formulas, if you're not followingâ€¦ I mean, someâ€¦ yeah, some of you might have some background in probability, and mightâ€¦ it might seem familiar to you, but if it isâ€¦ it doesn't, it's absolutely okay. This is exactly the kind of things we willâ€¦ we will cover.

148
00:35:12.810 --> 00:35:15.330
Faculty (Olympus): And formalize in the coming month.

149
00:35:15.740 --> 00:35:16.649
Bipin Karyakarte .: Fine, thank you.

150
00:35:16.650 --> 00:35:19.250
Faculty (Olympus): Sure. Sanketh,

151
00:35:19.250 --> 00:35:21.020
sanket shah .: Yeah, yeah,

152
00:35:21.460 --> 00:35:37.329
sanket shah .: Hey, Nikhil, so I just wanted to have a deeper understanding about, if weâ€¦ if we have, like, different apps, like, you know, Flipkart, Amazon, etc, and if we have a user who is going to land for the first time.

153
00:35:37.650 --> 00:35:44.959
sanket shah .: So, on what basis, or what are the different kind of parameters?

154
00:35:45.140 --> 00:35:49.769
sanket shah .: To which, you areâ€¦ you are going to generally track.

155
00:35:49.780 --> 00:36:07.700
sanket shah .: Or what kind of, calculations, generally, like, are in your practicals areâ€¦ areâ€¦ are being expected so that, out of the 1 lakh product, which, are already, like, on those apps, and you are just trying to see.

156
00:36:09.560 --> 00:36:14.549
sanket shah .: According to, like, you know, your details. So, like,

157
00:36:14.930 --> 00:36:25.570
sanket shah .: what is the basis of, like, you know, once you see your applications You know, the,

158
00:36:27.170 --> 00:36:28.469
sanket shah .: Well, first of threeâ€¦

159
00:36:28.670 --> 00:36:43.109
Faculty (Olympus): Yeah, I mean, maybe this is a question which is better taken at the end, given it's not maybe directly relevant to what I'm talking about, and it'll require a little more discussion. So, yeah, let's maybe discuss this at the very end of the class.

160
00:36:43.110 --> 00:36:44.810
sanket shah .: Works, works for me, nobody's.

161
00:36:44.810 --> 00:36:46.440
Faculty (Olympus): Okay, Rigank?

162
00:36:47.720 --> 00:36:48.840
Mrigank Mahajan .: Yes.

163
00:36:49.000 --> 00:36:53.600
Mrigank Mahajan .: So, the question that I have here is that,

164
00:36:54.460 --> 00:37:05.560
Mrigank Mahajan .: this is what we're looking at loans, right, in particular, and we're looking at daily spend. Typically, what is going to happen is, on a fundamental level, a person

165
00:37:05.570 --> 00:37:16.890
Mrigank Mahajan .: would have weekdays, weekends, typically people go out shopping on weekends, right? In a month, there would be, say, one or two big purchases that would happen, right? Yeah. If weâ€¦

166
00:37:16.890 --> 00:37:34.190
Mrigank Mahajan .: take it as noise in this particular scenario. I understand the logic and the math behind it, but in this particular scenario, is itâ€¦ is it actually advisable to take it as noise? Because those two days would keep on repeatedly happening, month over month, andâ€¦ and

167
00:37:34.270 --> 00:37:37.990
Mrigank Mahajan .: basically, it's an 80-20 principle, right? Yeah, yeah.

168
00:37:37.990 --> 00:37:43.110
Faculty (Olympus): So, I mean, again, okay, I should say, I mean, I'm not advocating using this

169
00:37:43.200 --> 00:38:00.650
Faculty (Olympus): as a model, of course not. I mean, this is too simplistic to decide any of this, right? I'm just giving a sense of what one might do if they see data, what might be a useful statistic to decide anything. So, of course, yeah, you will have to take into account

170
00:38:00.650 --> 00:38:08.949
Faculty (Olympus): You know, weekday, weekend, do all of that kind of thing, maybe separate them out, have different models for weekdays, different models for weekends.

171
00:38:09.180 --> 00:38:28.159
Faculty (Olympus): Yeah, what happens in practice is going to be much, much more complicated than any of this. But if you look at any one such model, right, or if you look at any particular model, there will often be a statistic there which is representing them. It'll be maybe a combination of many different statistics.

172
00:38:28.160 --> 00:38:38.689
Faculty (Olympus): So this is in no way supposed to be, you know, how, things are actually decided in practice, okay? Or I'm not advocating using just the median spend as aâ€¦

173
00:38:38.690 --> 00:38:45.600
Faculty (Olympus): as, the basis of your decision, I'm just saying that whenever you have data and you're trying to summarize data.

174
00:38:45.670 --> 00:38:53.170
Faculty (Olympus): Mean is much more, let's say, susceptible to noise than the median. That's it.

175
00:38:53.170 --> 00:38:53.630
Mrigank Mahajan .: Correct.

176
00:38:53.630 --> 00:38:56.220
Faculty (Olympus): Nothing, nothingâ€¦ To be said here.

177
00:38:56.580 --> 00:38:57.250
Faculty (Olympus): Yeah.

178
00:38:57.920 --> 00:39:07.939
Saurabh Puranik .: Hello everyone, I'm, Saurabh Puranik. What I understand is that a clear difference between mean and median. Mean basically depends on the magnitude.

179
00:39:08.380 --> 00:39:11.820
Saurabh Puranik .: And, median is very much dependent on the frequency.

180
00:39:12.160 --> 00:39:29.320
Saurabh Puranik .: And the second thing is that, what example Mr. Mahajan has given, I think it depends on the number of population also, because he quoted that mostly in the weekends, we spend more. But, for example, if I take the data set of only 10 days.

181
00:39:29.410 --> 00:39:33.359
Saurabh Puranik .: then it could beâ€¦ I can figure it out, the outliers.

182
00:39:33.500 --> 00:39:40.279
Saurabh Puranik .: But if I take the complete 365-day data, then the outliers, that is the weekend data.

183
00:39:40.590 --> 00:39:51.690
Saurabh Puranik .: will be very much more. In that case, theâ€¦ what you can say, the curve could be a right skewed or left skewed, could not be a symmetrical.

184
00:39:51.690 --> 00:39:52.140
Faculty (Olympus): Sure.

185
00:39:52.140 --> 00:39:54.909
Saurabh Puranik .: So I think it also depends on the population.

186
00:39:55.770 --> 00:39:57.560
Faculty (Olympus): Yeah, yeah, so,

187
00:39:58.140 --> 00:40:10.330
Faculty (Olympus): Of course, I mean, all of this, yeah, you're rightly saying that mean is much more, affected by values, and median is much more affected by their frequency.

188
00:40:10.330 --> 00:40:12.540
Robin Rodrigues .: Perks of joining from home.

189
00:40:13.160 --> 00:40:21.920
Faculty (Olympus): Sorry, one second, let's, Iâ€¦ yeah, I mean, please wait for me to askâ€¦ Yeah, completely stop.

190
00:40:22.540 --> 00:40:25.239
Robin Rodrigues .: Looks like, it never rained.

191
00:40:26.600 --> 00:40:29.660
Faculty (Olympus): Okay, Ken, please,

192
00:40:29.660 --> 00:40:30.240
Robin Rodrigues .: Oh, okay.

193
00:40:30.660 --> 00:40:34.319
Robin Rodrigues .: Alan, any idea if Devin, Priyanka, anyone would be joining in?

194
00:40:35.320 --> 00:40:37.659
Charles Mutsu: Robin, your voice is audible.

195
00:40:38.350 --> 00:40:38.949
Charles Mutsu: How about you?

196
00:40:38.950 --> 00:40:39.300
Robin Rodrigues .: Megan?

197
00:40:39.300 --> 00:40:39.840
Charles Mutsu: Nope.

198
00:40:40.390 --> 00:40:41.030
Faculty (Olympus): Yeah.

199
00:40:41.080 --> 00:40:53.989
Faculty (Olympus): Okay, alright, so let me, again, go ahead. I see a lot of you have your, hands still raised, and, again, this is, we are going to come back.

200
00:40:53.990 --> 00:41:14.359
Faculty (Olympus): at the end, and I can resolve any doubts at that point, okay? So again, this is good practice going forward, like you would have seen. If we stop, then there are many, many questions, and that can sometimes break the flow, so what I'll usually do is I'll wait for 10 minutes, and whoever I can resolve in those 10 minutes.

201
00:41:14.360 --> 00:41:38.749
Faculty (Olympus): I will try and do that immediately, and for the others, we'll just wait at the end, and I'll give you time then, and we can resolve all kinds of optionsâ€¦ all kinds of questions then. Second request I have is, for questions which are, clearly or very, very closely related to the, to the material that I'm covering, please ask them, or at least prioritize them right after, in these between slots.

202
00:41:38.890 --> 00:41:53.119
Faculty (Olympus): For questions which are more general, which are very welcome, I mean, absolutely no problems with those, but questions which might be more broader in scope, again, I would request that you take those at the very end. So we'll do it, try and do it that way, okay?

203
00:41:53.210 --> 00:42:07.990
Faculty (Olympus): Okay, let's, let's go forward. So we have this, median value that we've gotten, right? So now Iâ€¦ I have some baseline for this user. I know that their median spend is $415, and,

204
00:42:08.460 --> 00:42:15.449
Faculty (Olympus): I've seen this over the past 10 days, and I'm confident that this is a good statistic for their spending behavior.

205
00:42:15.470 --> 00:42:28.959
Faculty (Olympus): Right? Now, but if I am a fintech company, Iâ€¦ I mean, I don't want to just know what their median spend is, right? I also want to know how likely they are to make a very large spend.

206
00:42:29.100 --> 00:42:33.490
Faculty (Olympus): Fine. In the past 10 days, they have made a median spend of around $400.

207
00:42:33.490 --> 00:42:36.509
Robin Rodrigues .: 15, but, I could hear you.

208
00:42:37.110 --> 00:42:51.019
Faculty (Olympus): But, how do I use that to decide whether or how likely is the user to make a very large spend in the future, right? So I have now some, data.

209
00:42:51.120 --> 00:43:03.180
Faculty (Olympus): And I haveâ€¦ I have a statistic based on data, but now I want to use this statistic to somehow predict the future. How likely is the user to make a spend of, say, 5,000 rupees in the future?

210
00:43:03.280 --> 00:43:15.240
Faculty (Olympus): Right? So how do I do that? To do that, I have to use the data or the statistic that I have created and come up with a probabilistic model for user spend.

211
00:43:15.240 --> 00:43:24.199
Faculty (Olympus): Okay, so in this particular case, again, this is just an example, this is not something I'm prescribing or suggesting, but suppose I come up with a model which says.

212
00:43:24.200 --> 00:43:28.989
Faculty (Olympus): The daily spend of a user, behaves something like this.

213
00:43:29.740 --> 00:43:38.120
Faculty (Olympus): It's an exponential distribution, okay? So the way this exponential distribution looks like is it's something like this.

214
00:43:38.120 --> 00:43:57.500
Faculty (Olympus): So, here, this is your X, which is your spend, and thisâ€¦ you can think of, this as your density value. So, the higher values, you can see it decays very, very rapidly. So, this is saying that the spend is more likely to be small than being very high, okay?

215
00:43:57.660 --> 00:44:08.850
Faculty (Olympus): So this isâ€¦ this is the family that we are going to work with. This is one model. So I am modeling a user, a daily spend of a user, as the exponential distribution.

216
00:44:08.850 --> 00:44:11.220
Robin Rodrigues .: I don't know, you set up the call, so you tell me.

217
00:44:12.360 --> 00:44:14.730
Faculty (Olympus): Soâ€¦

218
00:44:15.210 --> 00:44:27.699
Faculty (Olympus): Nowâ€¦ so this is, however, parameterized by this parameter lambda, right? This is parameterized by this parameter lambda, and I have to somehow specify this lambda to complete the model.

219
00:44:27.790 --> 00:44:44.990
Faculty (Olympus): Right? Now, how do I find this lambda? The only thing I have is that the median is 415, right? That is the only information I have. I have to somehow fit this data, which is the median being 415, to this probabilistic model.

220
00:44:45.290 --> 00:44:49.550
Robin Rodrigues .: Sorry, Paran, can you please repeat your question? I think I'm having some Zoom issues.

221
00:44:50.440 --> 00:44:55.140
Faculty (Olympus): So, let me maybe move them, okay.

222
00:44:56.480 --> 00:45:01.269
Faculty (Olympus): So I have to somehow fit, this,

223
00:45:01.330 --> 00:45:10.359
Faculty (Olympus): data that I have to the model family and figure out the right model family. So I have to figure out lambda for that. Now, the way I can do that is

224
00:45:10.400 --> 00:45:22.469
Faculty (Olympus): I know that the median of aâ€¦ of an exponential distribution with parameter lambda is exactly log 2 by lambda, okay? This isâ€¦ how do I get it? Again, this is something we will do inâ€¦

225
00:45:22.470 --> 00:45:34.290
Faculty (Olympus): You will understand it once we've gone through a few lectures on random variables and distributions, but for now, this is just some algebraic calculation that one can do

226
00:45:34.290 --> 00:45:48.100
Faculty (Olympus): Using the density, using the density expression. So I know that for an exponential distribution, the median value, or the value which kind of splits the probability half and half, is exactly log 2 by lambda.

227
00:45:48.140 --> 00:46:03.650
Faculty (Olympus): Okay, so now I'm going to use this relationship and the data that I have from history to find the value of lambda. So this is very easy in this particular case. I will just match these two together, and I now have a particular estimate of my lambda.

228
00:46:03.810 --> 00:46:10.550
Faculty (Olympus): Okay, so using this relationship, right, and the historical data, I now have a model

229
00:46:10.690 --> 00:46:26.140
Faculty (Olympus): for my daily spend of this particular user. So I am going to model the daily spend of this user as an exponential distributionâ€¦ distributed random variable with parameter lambda being equal to 0.00167.

230
00:46:26.200 --> 00:46:45.859
Faculty (Olympus): Okay? So, the choice of the exponential distribution was mine, right? I made this choice based on maybe some domain knowledge that I have, but I fit the data to this choice. The choice of lambda comes from the user, that is user-driven, and how the history ofâ€¦ what the history of user spend is, and so on.

231
00:46:46.040 --> 00:46:57.619
Faculty (Olympus): Okay? So now I have this probabilistic model. I'm now going to use this probabilistic model to compute the chance of this user making a very large spend. Okay?

232
00:46:57.740 --> 00:47:13.080
Faculty (Olympus): So let'sâ€¦ let's do that. So now, suppose my company decides that they will approve the loan if there is less than a 5% chance of the user spending more than 2,000 rupees in a day, right?

233
00:47:13.220 --> 00:47:17.240
Faculty (Olympus): So, I can now compute that because I have a probabilistic model.

234
00:47:17.840 --> 00:47:27.389
Faculty (Olympus): And the way to do that is, again, if this is not, something that you've seen before, that's absolutely okay. What you want to do is you want to compute this quantity.

235
00:47:27.540 --> 00:47:38.950
Faculty (Olympus): Right? You want to use your probabilistic model to compute this quantity, and if some of you might have seen a density function, then you can recognize that this is how you compute the probability of this event.

236
00:47:39.020 --> 00:47:48.239
Faculty (Olympus): And, if you do that integral, it turns out to be something like this, and you can work the numbers out. It turns out to look to be .035.

237
00:47:48.690 --> 00:48:04.750
Faculty (Olympus): Okay? What is 0.035? It is the probability that this particular user, right, whose spend I have modeled as an exponential random variable with a particular value of lambda, will, on a particular day, spend more than 2,000 rupees.

238
00:48:05.020 --> 00:48:05.860
Faculty (Olympus): Right?

239
00:48:05.930 --> 00:48:24.939
Faculty (Olympus): So, I will approve the loan if this value was less than 0.05, and I will disapprove the loan if the value is going to be larger than 5%. That is how, let's say, I decide whether to approve a loan or not, right? So, in this particular case, because the chance is

240
00:48:24.940 --> 00:48:31.969
Faculty (Olympus): around 3%, I willâ€¦ I will approve the loan, because it is below our 5% threshold.

241
00:48:32.150 --> 00:48:38.809
Faculty (Olympus): Right? So we will approve the loan in this particular case. Right? So what have we done? We first had a user.

242
00:48:38.960 --> 00:48:44.670
Faculty (Olympus): Who'sâ€¦ for whom we had some data, historical data about their daily spends.

243
00:48:44.780 --> 00:48:52.660
Faculty (Olympus): Alright? We used the statistic of median to model this user, or to just summarize the historical behavior of this user.

244
00:48:52.930 --> 00:49:01.230
Faculty (Olympus): Then we used that statistic to kind of fit an exponential model for the user's daily spend.

245
00:49:01.410 --> 00:49:06.769
Faculty (Olympus): Right? And we used the median value to fit the model to our data.

246
00:49:06.930 --> 00:49:18.910
Faculty (Olympus): And then we used that exponential model to come up with an estimate of the probability that this user in the future is going to make a very, big spend.

247
00:49:19.260 --> 00:49:20.200
Faculty (Olympus): Right?

248
00:49:20.390 --> 00:49:39.880
Faculty (Olympus): Okay? And because that value turns out to be less than 5%, we approve the loan. If this value had turned out to be larger than 5%, then we would have disapproved the loan. So, for example, this particular user had a median spend of, I think, around $415 or something like that.

249
00:49:39.880 --> 00:49:51.219
Faculty (Olympus): You can see that if the median spend was, let's say, higher, for example, if it was $700, maybe this value would have then jumped up to beyond 5%, and in that case, we would have disapproved the loan.

250
00:49:51.430 --> 00:49:52.260
Faculty (Olympus): Okay?

251
00:49:52.370 --> 00:50:07.420
Faculty (Olympus): So we are using both the statistics and the probabilistic modeling to together essentially predict the risk of this user, and because the risk is less than 5%, we decide we can go ahead and approve the loan.

252
00:50:07.490 --> 00:50:26.150
Faculty (Olympus): Okay? That's the idea. Okay, I will take a couple of quick questions. Again, please, keep these questions really tied to the material, and if you have more general questions, then we can take them up at the end. Okay?

253
00:50:26.570 --> 00:50:29.840
Faculty (Olympus): Yeah, Manu?

254
00:50:31.890 --> 00:50:45.680
Manu Verma .: Yeah, hi, good evening, Professor. So, I have two very basic questions. So if youâ€¦ on the first slide, I mean, if youâ€¦ where you were explaining the probability and statistic relationship, so is it possible to go on the first slide?

255
00:50:46.890 --> 00:50:51.990
Faculty (Olympus): Again, I don't want to go all the back there. Okay, no problem.

256
00:50:51.990 --> 00:51:02.960
Manu Verma .: I'll just mentionâ€¦ I'll mention it verbally. So there you mentionedâ€¦ there you wrote, like, a sort of a function like P. For statistics, you mentioned P, bracket, model, bar data.

257
00:51:02.960 --> 00:51:13.749
Manu Verma .: And for probability, you mentioned, P, bracket data bar model. Yeah. So, shouldn't it be other way around? Because for statistics, we have the data first, and then we create a model.

258
00:51:13.760 --> 00:51:14.280
Manu Verma .: Andâ€¦

259
00:51:14.280 --> 00:51:20.650
Faculty (Olympus): So, okay, so that, this notation of probability Awful.

260
00:51:21.780 --> 00:51:33.429
Faculty (Olympus): Thisâ€¦ this is the notation, right? The way to read this, and I should have done that, is what is theâ€¦ what we are doing here is a model. This bar stands for given.

261
00:51:33.570 --> 00:51:34.080
Faculty (Olympus): Okay.

262
00:51:34.080 --> 00:51:34.729
Manu Verma .: Okay, okay.

263
00:51:34.730 --> 00:51:45.669
Faculty (Olympus): So, again, when we deal with conditional probability, this will become clear. So thisâ€¦ the way to read this is model given data, and if it was data-model, then that is data given model.

264
00:51:45.670 --> 00:51:58.340
Manu Verma .: Got it, got it, sure. And my second question is, like, the lambda that we were just discussing. So I understand that for different scenarios and situations, the derivation of this lambda would be different.

265
00:51:58.340 --> 00:51:58.660
Faculty (Olympus): Yeah, yeah.

266
00:51:58.660 --> 00:52:08.669
Manu Verma .: have to basically find out the most optimized, way to define this, this, to define the lambda, right? And we'll be studying that in the later classes.

267
00:52:08.670 --> 00:52:11.240
Faculty (Olympus): Yeah, yeah, yeah, yeah, we'll be covering these things.

268
00:52:11.240 --> 00:52:12.660
Manu Verma .: Okay, sure. Thank you so much.

269
00:52:12.660 --> 00:52:14.270
Faculty (Olympus): Sure, Sameer?

270
00:52:14.780 --> 00:52:31.749
Sameer Sawant .: Yeah, quick question. So, does the fundamental machine learning says that there always has to be a statistical part to say there is a given data which helps you to predict the model, and then you use those models through probability and your lambda function.

271
00:52:31.840 --> 00:52:37.030
Sameer Sawant .: to predict the data of the future outcomes. Is that so in a very simple terms?

272
00:52:37.030 --> 00:52:52.270
Faculty (Olympus): I mean, so it's not a given, this is aâ€¦ again, this is a tool that we are using. We are assuming a generative model. We are assuming that there is some underlying probabilistic model which is generating this data, and we are trying to fit our data to the model.

273
00:52:52.270 --> 00:52:59.799
Faculty (Olympus): Okay? Whether there is, in fact, an underlying model which isâ€¦ or probabilistic model which is generating the data, no one knows.

274
00:52:59.800 --> 00:53:15.110
Faculty (Olympus): Right? We are just trying toâ€¦ this is one way of kind of making the problem possible to analyze, or to predict future outcomes. If we make no assumptions, then it is very difficult to predict anything.

275
00:53:15.120 --> 00:53:18.140
Faculty (Olympus): Right? So you make some assumption ofâ€¦

276
00:53:18.140 --> 00:53:22.100
Sameer Sawant .: Precursor, precursor in most of the scenarios is that what.

277
00:53:22.100 --> 00:53:35.569
Faculty (Olympus): I mean, we are trying to do both of these things together, in some sense. So, you will have a probabilistic model, and there will be some parameters associated with those models. Those are the parameters you want to really fit to the data.

278
00:53:35.650 --> 00:53:46.030
Faculty (Olympus): And then, in the statistical part, you will try and get good estimates of those particular parameters. So these two go hand in hand, it's not one or the other in order.

279
00:53:46.360 --> 00:53:47.130
Manu Verma .: than me.

280
00:53:47.130 --> 00:53:48.300
Faculty (Olympus): Okay, Vidya?

281
00:53:48.480 --> 00:53:51.140
Manu Verma .: Professor by T. Bob Menon.

282
00:53:51.140 --> 00:53:52.830
Vidya Gavel: Hi, can you hear me?

283
00:53:52.830 --> 00:53:53.470
Faculty (Olympus): Yeah.

284
00:53:53.970 --> 00:54:08.349
Vidya Gavel: I have a quick generic question regarding, the, statistical analysis and, basically machine learning model, right? So what we are talking about here, the model window.

285
00:54:08.350 --> 00:54:09.470
Faculty (Olympus): Okay, Vidyaâ€¦

286
00:54:09.470 --> 00:54:10.020
Vidya Gavel: Be a machine.

287
00:54:10.020 --> 00:54:26.260
Faculty (Olympus): you go ahead. If the question, like I said, if the question is really tied to the material, then I would say please go ahead and ask. But if it is more general, then I'm happy to take this question at the end. It'sâ€¦ so you make that decision.

288
00:54:26.450 --> 00:54:33.600
Vidya Gavel: Yeah, I mean, this is basically the model when we are talking about model. Are we talking about machine learning model, or just a statistical.

289
00:54:33.600 --> 00:54:39.179
Faculty (Olympus): So, here I'm talking about a probabilistic model. So, for example, a model like this.

290
00:54:39.870 --> 00:54:40.750
Vidya Gavel: Mhmh, okay?

291
00:54:40.750 --> 00:54:48.599
Faculty (Olympus): how I got this model, how I got that it is an exponential distribution, or how I should model this as an exponential distribution.

292
00:54:48.600 --> 00:55:06.639
Faculty (Olympus): This all comes from historical data, or domain knowledge, right? You might have seen in theâ€¦ in history, like, youâ€¦ peopleâ€¦ I mean, people who work with this will have some, usually, historical data, and they will look at how it behaves over time, and then would come up with a reasonable model for it.

293
00:55:06.750 --> 00:55:07.530
Faculty (Olympus): So that then you.

294
00:55:07.530 --> 00:55:07.860
Vidya Gavel: drink.

295
00:55:07.860 --> 00:55:09.340
Faculty (Olympus): parameters to it.

296
00:55:09.690 --> 00:55:13.250
Vidya Gavel: So we haven't reached, or we haveâ€¦ we are not talking aboutâ€¦ We are not talking about that.

297
00:55:13.250 --> 00:55:15.820
Faculty (Olympus): No, no, we're not talking about a machine learning model.

298
00:55:16.030 --> 00:55:18.989
Vidya Gavel: Okay, yeah, that's what I wanted to check. Thank you so much.

299
00:55:18.990 --> 00:55:23.339
Faculty (Olympus): Okay, maybe one last question, Naina?

300
00:55:27.170 --> 00:55:38.039
Naina Punjwani .: Professor, my question is more generic, I can wait. I wanted to understand the basics, books, to go through these concepts before we start the lecture, because.

301
00:55:38.040 --> 00:55:43.439
Faculty (Olympus): Then, yeah, yeah, we'll discuss this at the end, then. Yeah. Okay,

302
00:55:43.440 --> 00:55:44.960
Sriananth Haripanth .: Just one, oneâ€¦

303
00:55:44.960 --> 00:55:47.379
Vamsi Krishna Mutnuri .: Question, I'm not able to raise my hand.

304
00:55:47.510 --> 00:55:47.920
Faculty (Olympus): Sure.

305
00:55:47.920 --> 00:55:52.469
Sriananth Haripanth .: The question here from my side is that, first we did a data.

306
00:55:52.470 --> 00:56:10.509
Faculty (Olympus): Sorry, let's do this, one by one, and like I said, I mean, Iâ€¦ I don't want to devote too much time to questions in between, because it breaks the flow, but we will resolve your questions at the end. Maybe one last question isâ€¦

307
00:56:10.510 --> 00:56:24.360
Sriananth Haripanth .: Let me compute my question. So first, we did the data median, and then assumed the distribution. After that, we, we, can you explain what is this explosive estimation about?

308
00:56:26.010 --> 00:56:26.660
Sriananth Haripanth .: Fuck.

309
00:56:26.970 --> 00:56:30.699
Sriananth Haripanth .: Why did we go for the explicit estimation, by the way?

310
00:56:31.650 --> 00:56:34.110
Faculty (Olympus): Theâ€¦ what exclamation?

311
00:56:34.110 --> 00:56:34.720
Sriananth Haripanth .: Oops.

312
00:56:35.120 --> 00:56:37.250
Sriananth Haripanth .: the explicit estimation.

313
00:56:37.640 --> 00:56:39.240
Faculty (Olympus): Explicit estimation.

314
00:56:39.660 --> 00:56:40.639
Sriananth Haripanth .: Yeah, good.

315
00:56:41.730 --> 00:57:01.170
Faculty (Olympus): So, I mean, you have aâ€¦ what we have is, like, a genericâ€¦ it's like a family of distributions, right? We have the exponential distribution, but this is a family which is parameterized by lambda. Unless you know the value of lambda, you don't have a particular distribution. To specify the distribution, you need a value of lambda.

316
00:57:01.410 --> 00:57:06.219
Faculty (Olympus): So, we are using the median as a statistic to estimate that lambda.

317
00:57:08.000 --> 00:57:08.360
Sriananth Haripanth .: Understood.

318
00:57:08.360 --> 00:57:21.550
Faculty (Olympus): So, because for the exponential distribution, I have a clear expression for the median, I can use the empirical median and the median of the distribution, and match them together to get an estimate of lambda.

319
00:57:21.820 --> 00:57:35.150
Faculty (Olympus): Once I have lambda, then I have completely specified the probabilistic model. Without specifying the lambda, my probabilistic modeling is incomplete, right? What is theâ€¦ unless you know the value of lambda, you cannot do any calculations with this model.

320
00:57:36.650 --> 00:57:37.750
Faculty (Olympus): Okay?

321
00:57:38.380 --> 00:57:47.309
Faculty (Olympus): Okay, let's go ahead, like I said, for the others, we will, we will, take these questions at the end, so please hold on to those questions.

322
00:57:47.550 --> 00:57:54.499
Faculty (Olympus): Maybe I want to cover one, one more, application beforeâ€¦

323
00:57:54.770 --> 00:57:58.630
Faculty (Olympus): Stop today, okay, let meâ€¦

324
00:57:58.920 --> 00:58:06.680
Faculty (Olympus): Let me maybe skip this one. You will have access to the slides, so you can look at them later if you want.

325
00:58:06.850 --> 00:58:09.020
Faculty (Olympus): Let me do this one.

326
00:58:09.020 --> 00:58:27.609
Faculty (Olympus): Okay, so here is another case study. We usually, like I was saying, there are many, many different features that go into any machine learning model or any statistical model when you're trying to make a decision, right? So, for example, in the case of

327
00:58:27.720 --> 00:58:44.640
Faculty (Olympus): loan approval, like one of your colleagues suggested, if you only base it on median spend, anyone is going to be able to game it, right? So you usually will have many, many different features that together are used to make a decision.

328
00:58:44.640 --> 00:59:04.360
Faculty (Olympus): Now, what will happen often is that there are too many features, right? And then your model will become really, really complicated, and you can hardly do anything with it, and it becomes very hard, because you also have to estimate the parameters of that model, and so on. So you want to take, essentially, a subset of the most informative features, right?

329
00:59:04.360 --> 00:59:10.109
Faculty (Olympus): So, what are the features which are most likely to determine the outcome that you are interested in?

330
00:59:10.110 --> 00:59:27.230
Faculty (Olympus): Right? So, that is what one needs to do. So, one has to do some sort of feature selection. So, how do I do feature selection? If I am given a bunch of data, and I'm given all the features, how do I select the features which are most likely going to impact my outcome?

331
00:59:27.250 --> 00:59:35.130
Faculty (Olympus): So let's look thatâ€¦ look at that at a very, for a very specific, example. Let's say, I again have aâ€¦

332
00:59:35.330 --> 00:59:46.939
Faculty (Olympus): I'm an e-commerce company, right? And I'm noting down many, many features of the users. I'm tracking many features of the users who come and look at my app.

333
00:59:47.040 --> 00:59:59.590
Faculty (Olympus): And, for example, maybe two features that I look at are, one is the in-app session time, which is X, and the second is the user's brightness, screen brightness, when they are using my app.

334
00:59:59.600 --> 01:00:09.280
Faculty (Olympus): Okay, so I'm keeping track of these two features, and what I'm really interested in is maybe which of these features is more likely to impact

335
01:00:09.410 --> 01:00:12.950
Faculty (Olympus): The daily spend of this user on my app.

336
01:00:13.380 --> 01:00:28.069
Faculty (Olympus): Okay, so I only want to base it on one of these features. I don't want to carry both features forward. I want to select one of these features, and then decide that I'm going to use that particular feature to predict the daily spend. Okay, so how should I decide?

337
01:00:28.860 --> 01:00:42.749
Faculty (Olympus): whether X impacts Y more, or does Z impact Y more? Right? This is the main question that we are interested in. Which of these is more informative about my target variable, which is the daily spend of the user?

338
01:00:42.880 --> 01:00:52.099
Faculty (Olympus): Okay, so one way of doing that, and this is really a very, very popular method, is via correlation coefficients, and

339
01:00:52.100 --> 01:01:09.430
Faculty (Olympus): The statistical tool, is called Pearson's correlation coefficient. There are many different correlation coefficients, but the most popular one by far, is Pearson's correlation coefficient, which has this particular definition, okay? So let me maybe break down this definition. You have a bunch of data.

340
01:01:09.520 --> 01:01:14.460
Faculty (Olympus): Right? You have, data where you have X, maybe Y and Z.

341
01:01:15.070 --> 01:01:27.260
Faculty (Olympus): Right? Each of these is like a row. So every row corresponds to one user, and you have XI, Yi, ZI, right? So, this corresponds to one user.

342
01:01:27.460 --> 01:01:30.440
Faculty (Olympus): who spent Xi amount of time on the app.

343
01:01:31.440 --> 01:01:37.649
Faculty (Olympus): made a purchase of, size Yi, and had screen brightness ZI.

344
01:01:37.690 --> 01:01:47.950
Faculty (Olympus): Okay, so this is one row. Similarly, there will be many, many rows. Every row corresponds to one user. You aggregate this data into this correlation coefficient.

345
01:01:47.950 --> 01:01:58.379
Faculty (Olympus): Okay, so the correlation coefficientâ€¦ this is the correlation coefficient between X and Y. The way to compute it is you will go over all the rows.

346
01:01:58.400 --> 01:02:02.089
Faculty (Olympus): X bar is the mean value, or the average value of X.

347
01:02:02.150 --> 01:02:04.869
Faculty (Olympus): And Y bar is the average value of Y.

348
01:02:04.950 --> 01:02:07.489
Faculty (Olympus): And you compute this quantity, okay?

349
01:02:07.580 --> 01:02:22.229
Faculty (Olympus): Why this particular quantity? We will, in fact, look at this, and you will understand when we go over how this correlation coefficient comes about. At that point, it'll become clear why it is of this form. But right now, the main thing to note is that this isâ€¦ this measures

350
01:02:22.790 --> 01:02:28.649
Faculty (Olympus): correlation between variables. This value is always between minus 1 and 1,

351
01:02:28.970 --> 01:02:43.900
Faculty (Olympus): Okay? If it is close to 1, that means that X and Y grow together, which means when X is large, Y is also large. If it is minus 1, then that means they are negatively correlated, which means when X is large, Y is small.

352
01:02:44.220 --> 01:02:47.390
Faculty (Olympus): Okay? And if the value is close to zero.

353
01:02:47.440 --> 01:03:05.729
Faculty (Olympus): then that means that these two quantities are uncorrelated, meaning they don't have a lot of impact on each other, okay? So, by looking at the value of this correlation coefficient, you can judge whether these two parameters are positively correlated, or negatively correlated, or essentially uncorrelated, okay?

354
01:03:05.970 --> 01:03:17.549
Faculty (Olympus): So, for example, if I was doing it in this way, let's say I want to distinguish these meaningful relationships, the way to do that would be you center each variable by subtracting the mean.

355
01:03:17.550 --> 01:03:26.960
Faculty (Olympus): you multiply those values together, and then you normalize, right? So, for example, let's say the data was of this form, you haveâ€¦ you have polled, or you have tracked 5 users.

356
01:03:26.960 --> 01:03:29.270
Faculty (Olympus): And these are the X values

357
01:03:29.270 --> 01:03:32.380
Faculty (Olympus): Their, time that they spent on the app.

358
01:03:32.390 --> 01:03:37.810
Faculty (Olympus): This is the spends that each of these users had, and similarly, this is the brightness value.

359
01:03:38.020 --> 01:03:50.280
Faculty (Olympus): So you can compute these quantities, X minus X bar, Y minus Y bar. You take the product of those, and then you similarly take the product for Z and Y. These are the quantities that you get.

360
01:03:50.490 --> 01:04:04.510
Faculty (Olympus): And then you normalize. Okay, you normalize these sums, because if you notice, in the expression, you have this normalization factor of the variance in the denominator, so you normalize them, and if you normalize that.

361
01:04:04.600 --> 01:04:21.460
Faculty (Olympus): this is what you're going to get. So, if you look at the correlation, this, just this value of RXY, okay, all I have done is I have plugged in those numbers into the formula. If you compute that, you will see that the correlation for X and Y turns out to be 0.71.

362
01:04:21.590 --> 01:04:27.930
Faculty (Olympus): What is this telling me? This is telling me that the correlation that X

363
01:04:28.060 --> 01:04:31.550
Faculty (Olympus): So, X was the amount of time spent.

364
01:04:32.120 --> 01:04:32.980
Faculty (Olympus): Right?

365
01:04:33.360 --> 01:04:38.149
Faculty (Olympus): And Y is the spend? The spend amount. The amount spent.

366
01:04:38.970 --> 01:04:50.859
Faculty (Olympus): Right? So this is saying that there is a positive correlation, quite a good positive correlation between the time spent on the app and the amount of, actual money spent.

367
01:04:50.860 --> 01:05:01.140
Faculty (Olympus): There, right? So this is saying these two are positively correlated, which means if X becomes larger, which means you are spending more time on the app, your Y is also likely to

368
01:05:01.150 --> 01:05:02.130
Faculty (Olympus): Rise.

369
01:05:02.560 --> 01:05:20.449
Faculty (Olympus): Okay? So this is good. This is saying that this, in fact, does, it is a good indicator, time spent on the app is a good indicator of the amount of money that this user will probably spend. On the other hand, if you do the same calculation, right.

370
01:05:20.450 --> 01:05:26.509
Faculty (Olympus): So this is just reiterating what I just said. If I do the same calculation with screen brightness.

371
01:05:26.890 --> 01:05:35.209
Faculty (Olympus): Okay, again, all I'm going to do is I'm going to plug in the numbers into that formula. You will see that this turns out to be minus 0.03.

372
01:05:35.320 --> 01:05:54.960
Faculty (Olympus): So very, very close to zero. So what this is indicating is that there is no meaningful relationship or no correlation, essentially, between the screen brightness of the app while the user is using them, and the amount of money that the user spends, okay?

373
01:05:55.130 --> 01:06:04.699
Faculty (Olympus): Okay, so these are two different parameters with two different correlations, and clearly, in this case, you should be tracking the amount of time spent rather than the screen brightness.

374
01:06:04.740 --> 01:06:18.310
Faculty (Olympus): Right? Now, clearly, I mean, this is, like I said, I mean, this might seem silly to you, why would anyone think of screen brightness as being a predictor of the amount of money spent? I agree. I mean, this is just an example toâ€¦

375
01:06:18.370 --> 01:06:37.790
Faculty (Olympus): Kind of illustrate the point, but in general, you might have more, let's say, more confusing predictors, and you might have to decide to select some few of them. The way to do that is you kind of evaluate exactly these correlation coefficients, and then you select the ones which have the highest correlation coefficient.

376
01:06:37.830 --> 01:06:38.570
Faculty (Olympus): Okay

377
01:06:38.720 --> 01:06:58.040
Faculty (Olympus): So, that's the way to use these ideas. Or if you have two predictors which themselves have very high correlation amongst each other, then against it, it is not meaningful to select both of them, because they both are amongst themselves very, very correlated with each other, so there is no point selecting both of them. Instead, you select one of them.

378
01:06:58.150 --> 01:07:00.689
Faculty (Olympus): Right? So again, this is something that is used

379
01:07:00.880 --> 01:07:13.590
Faculty (Olympus): all the time for feature selection in machine learning. Usually, you will have hundreds and thousands of features, but you can only select a few of them because you want the model to still be explainable, you want the model to not become too large.

380
01:07:13.590 --> 01:07:21.729
Faculty (Olympus): So you will select a few of these, features, and the way toâ€¦ or one way to select these features is by computing these correlation coefficients.

381
01:07:21.810 --> 01:07:34.610
Faculty (Olympus): And, these correlation coefficients are essentially statistical quantities, and you use the ones which have either, you know, have high modulus, that is theâ€¦ those are the ones that you want to select.

382
01:07:34.910 --> 01:07:39.000
Faculty (Olympus): Okay? Okay, I will,

383
01:07:39.320 --> 01:07:45.569
Faculty (Olympus): Again, maybe, stop now, just to see if there are a few questions about exactly this

384
01:07:45.750 --> 01:07:55.180
Faculty (Olympus): example application, and then, we'll, we'll try and start concluding. Okay? Pradeep?

385
01:07:59.630 --> 01:08:01.070
Pradeep Kumar .: Yeah, hi, Professor.

386
01:08:01.210 --> 01:08:01.770
Faculty (Olympus): Yeah.

387
01:08:02.150 --> 01:08:09.970
Pradeep Kumar .: Yeah, so actually, I was having a question in the previous slide, but ohâ€¦ You know, previous.

388
01:08:09.970 --> 01:08:11.700
Faculty (Olympus): Meaning this example, or not this example?

389
01:08:11.700 --> 01:08:13.270
Pradeep Kumar .: the previous,

390
01:08:13.270 --> 01:08:13.860
Faculty (Olympus): Excuse me.

391
01:08:13.860 --> 01:08:14.210
Pradeep Kumar .: driving.

392
01:08:14.210 --> 01:08:16.580
Faculty (Olympus): So then weâ€¦ let's take this at the end.

393
01:08:16.580 --> 01:08:18.120
Pradeep Kumar .: Right, right, soâ€¦

394
01:08:18.120 --> 01:08:19.800
Souvik Brahmachari: Mishra, this is Souvik.

395
01:08:19.800 --> 01:08:20.300
Faculty (Olympus): Yeah.

396
01:08:20.300 --> 01:08:31.449
Souvik Brahmachari: So I couldn't raise my hand, so that's why. So, so I just missed that portion, like, if it is, near to the minus one, so in that.

397
01:08:31.450 --> 01:08:31.790
Faculty (Olympus): Yeah.

398
01:08:32.130 --> 01:08:33.380
Souvik Brahmachari: Whatâ€¦ what wouldâ€¦

399
01:08:33.380 --> 01:08:49.490
Faculty (Olympus): Soâ€¦ so ifâ€¦ so this, again, this correlation coefficient lands between minus 1 and 1. If it is 1, that means that X and Y grow together, meaning they are positively correlated. If X is large, Y is also large. They grow in the same direction.

400
01:08:49.520 --> 01:09:01.739
Faculty (Olympus): If X is small, Y is also small. If it's minus 1, then that means they have opposite behaviors, which means when X goes down, Y goes up. When Y goes down, X goes up. Okay, so they are negatively correlated then.

401
01:09:02.069 --> 01:09:03.470
Faculty (Olympus): That's what it means.

402
01:09:03.960 --> 01:09:05.130
Souvik Brahmachari: Okay, thank you.

403
01:09:05.130 --> 01:09:09.769
Faculty (Olympus): Okay? Savo Suresh,

404
01:09:10.100 --> 01:09:11.830
Savalo Suresh Naroji .: Yeah. Hey, hi.

405
01:09:11.830 --> 01:09:12.410
Faculty (Olympus): Hi.

406
01:09:12.410 --> 01:09:17.390
Savalo Suresh Naroji .: My question is regarding, like, are we allowed to use calculator to do something?

407
01:09:17.399 --> 01:09:20.749
Faculty (Olympus): So, again, Savo, maybe let's take this at the end.

408
01:09:21.300 --> 01:09:25.849
Savalo Suresh Naroji .: Okay, and I had another question, but it was for previous examples.

409
01:09:25.850 --> 01:09:28.969
Faculty (Olympus): So maybe we will come to it at the very end.

410
01:09:28.979 --> 01:09:30.369
Sriananth Haripanth .: Okay,

411
01:09:30.550 --> 01:09:49.220
Sriananth Haripanth .: My question is regarding this correlation. So, you mean to say this PSM correlation is something which that company decides whether they want to use this correlation, or use any other correlation, but it is specific to that, project, that kind of mechanism.

412
01:09:49.229 --> 01:10:03.109
Faculty (Olympus): Yeah, yeah, it's a metric which youâ€¦ which is available, and it's very popular. People use it all the time. There are other correlation coefficients also that people have come up with, but this is certainly one which is very popular.

413
01:10:04.570 --> 01:10:05.720
Manu Gupta .: True.

414
01:10:06.840 --> 01:10:08.669
Manu Gupta .: Sinha audio.

415
01:10:08.830 --> 01:10:09.560
Faculty (Olympus): Yeah.

416
01:10:09.750 --> 01:10:24.860
Manu Gupta .: So my concern is regarding PSN coordination. So, we here use to find the correlation between two numerical values, or I would say numerical columns. So, is it also applicable for the categorical variables?

417
01:10:26.140 --> 01:10:43.859
Faculty (Olympus): So, I mean, here, yeah, this is particularly defined when you have X and Ys, which are numerical, values. If it's categorical, you can either convert those into numerical values, for example, or there are other correlation coefficients that you can use there.

418
01:10:45.560 --> 01:10:46.140
Manu Gupta .: Thankâ€¦

419
01:10:47.420 --> 01:10:56.890
Faculty (Olympus): Okay, maybe, one last question before we kind of conclude, and then we will move ahead.

420
01:10:56.890 --> 01:10:58.380
Vamsi Krishna Mutnuri .: Can I?

421
01:10:59.380 --> 01:11:12.979
Faculty (Olympus): Sorry, who is this? Again, let's maybe, keep this, follow this, procedure that unless you're able to not raise your hand, which again, I would say, please try and fix that.

422
01:11:12.980 --> 01:11:19.539
Faculty (Olympus): let me maybe ask, otherwise there'll be a lot of collisions, so I don't want that.

423
01:11:19.750 --> 01:11:24.989
Faculty (Olympus): Yeah, I'll just pick, abhineet,

424
01:11:25.900 --> 01:11:30.540
Abhineet Bansal: Yeah, hi, sir. One quick question here. So, how do we know we've estimated the

425
01:11:30.870 --> 01:11:38.140
Abhineet Bansal: a good number of factors here. I mean, like, you estimated that X is a good factor for Y. How do we know there are many more?

426
01:11:38.960 --> 01:11:46.810
Faculty (Olympus): Yeah, of course, I mean, yeah, so, again, I mean, yeah, this is, yeah, it's not really,

427
01:11:46.810 --> 01:12:05.280
Faculty (Olympus): something for which I have a clear answer. You would wantâ€¦ what you would usually want isâ€¦ I mean, yeah, how you evaluate whether your model is good enough or not is like a separate thing, right? That is maybe more related to your ML course, rather than this particular course. There are several ways you will essentially

428
01:12:05.280 --> 01:12:15.220
Faculty (Olympus): maybe train your model using one feature, and then you will see how it, you will try and validate that model, you will see how it performs on test data. If it is not performing well.

429
01:12:15.220 --> 01:12:20.059
Faculty (Olympus): Then you will add more features and try and see whether that improves the performance of the model.

430
01:12:20.250 --> 01:12:20.889
Faculty (Olympus): That's the.

431
01:12:20.890 --> 01:12:25.169
Abhineet Bansal: And is there a way to identify more features? I don't know which features could influence.

432
01:12:25.170 --> 01:12:35.550
Faculty (Olympus): So again, feature engineering, that itself is, I mean, it's like a completely different field. What features to even include, or how to engineer features, it's like a completely different thing.

433
01:12:36.560 --> 01:12:37.380
Faculty (Olympus): Thank you.

434
01:12:38.210 --> 01:12:53.470
Faculty (Olympus): Okay, let's, maybe move on, and then, yeah, weâ€¦ I won't spend a lot of time on this now, and then we will conclude, and then I can take all the questions at the very end, okay? So, let's, let's maybe conclude.

435
01:12:53.620 --> 01:13:00.549
Faculty (Olympus): Okay, so the idea here, at least through these two examples, are what I wanted to

436
01:13:00.640 --> 01:13:17.130
Faculty (Olympus): point out is, in general, data science is about making decisions under uncertainty, and statistics and probability essentially help us with that, okay? These are essentially, formal ways of studying uncertainty and modeling uncertainty.

437
01:13:17.180 --> 01:13:33.879
Faculty (Olympus): Statistics helps us to summarize data and come up with, to identify, essentially, patterns in data, or get summary values which are robust to noise, and so on. So that is kind of the role of statistics.

438
01:13:34.100 --> 01:13:45.580
Faculty (Olympus): On the other hand, the rule of probability is now for us to provide a model for how the data was, in fact, generated, right? And then the reason that is useful is because once you have a model.

439
01:13:45.810 --> 01:14:05.219
Faculty (Olympus): then you can use this model to predict future values, and you can quantify risk, you can quantify behavior, and so on, right? So you can reason about future outcomes using a probabilistic model. So these two things kind of go hand in hand. You have a probabilistic model, which has maybe some features.

440
01:14:05.220 --> 01:14:11.659
Faculty (Olympus): You are going to use the data to estimate these features, that's essentially statistics, and this cycle kind of goes on.

441
01:14:11.880 --> 01:14:13.709
Faculty (Olympus): Okay? So theâ€¦

442
01:14:13.980 --> 01:14:28.809
Faculty (Olympus): better your data is, or the less noisy your data is, the better you will be able to estimate parameters, so better your probabilistic model will be, which means you will be able to make better predictions, and so on. Okay, so this is how the cycle kind of goes.

443
01:14:28.810 --> 01:14:34.619
Faculty (Olympus): And, the main idea of, or the main theme of this course is going to be toâ€¦

444
01:14:34.620 --> 01:14:38.119
Faculty (Olympus): Try and enable you to argue things formally.

445
01:14:38.120 --> 01:14:54.999
Faculty (Olympus): About these quantities, or reason things formally about these quantities. So we are going to go into the details, mathematical details, of how we define probability, how we define random variables, how we define distributions, and so on. All of that is essentially exactly the content of this course.

446
01:14:55.370 --> 01:14:56.210
Faculty (Olympus): Okay?

447
01:14:57.000 --> 01:15:08.729
Faculty (Olympus): Okay, I think I've, said all of this. So this is just a tentative, kind of, program that we have for the first half.

448
01:15:08.840 --> 01:15:28.189
Faculty (Olympus): of theâ€¦ of the course. Again, this is tentative. We might change this depending on how things are going. We'll begin with, just defining general probability space, and how to compute, probabilities, inâ€¦ in someâ€¦ using counting and sampling.

449
01:15:28.190 --> 01:15:39.739
Faculty (Olympus): We will then formally define the notion of random variables and distributions, densities, and so on. Some of these things you might have seen before, but we'll do this formally. We will then go to moments.

450
01:15:39.780 --> 01:15:45.060
Faculty (Olympus): Such as expectation, variance, covariance, correlation, and so on.

451
01:15:45.290 --> 01:15:54.410
Faculty (Olympus): And then, finally, the last part, is going to be about limit theorems and tail inequalities. Some of these things you might have heard about.

452
01:15:54.420 --> 01:16:05.819
Faculty (Olympus): But these turned out to be really, really important in performance analysis. And at the very end, depending on whether we have time limit remaining, we will do some amount of estimation.

453
01:16:05.830 --> 01:16:21.279
Faculty (Olympus): Okay? So this is the kind of plan for the first half of the course, and the second half of the course, like I said, Professor Manjunat will take, and he will cover more on applications of these ideas to estimation, hypothesis testing, regression, and so on.

454
01:16:21.370 --> 01:16:26.329
Faculty (Olympus): Okay? So that's the idea. In terms of references.

455
01:16:26.690 --> 01:16:35.609
Faculty (Olympus): The one that you will maybe find the easiest to follow, and also a lot of the initial material, at least you will definitely find.

456
01:16:35.610 --> 01:16:47.570
Faculty (Olympus): Here is this first book, which is called The First Course in Probability by Ross. You should be able to find an Indian edition for that, and I highly recommend that you get at least one book.

457
01:16:47.590 --> 01:17:07.430
Faculty (Olympus): This is one book where you will find a lot of the material. Maybe the exact, you know, material is not from here, the exact material may be from many different sources, but this is one source where you will definitely find those topics available, and you can use them to read, as well as solve practice problems, and so on.

458
01:17:07.430 --> 01:17:15.470
Faculty (Olympus): Okay? I have also suggested a few other references. These are essentially if you're interested in getting,

459
01:17:15.470 --> 01:17:21.349
Faculty (Olympus): Let's say more reading, or you want more references to look at a variety of

460
01:17:21.430 --> 01:17:40.270
Faculty (Olympus): perspectives, then you can also look at these three other references. The last one is, for some practice problems. It's a text which just has problems in probability, okay? We will also be sharing, like I said, we will also be sharing, practice sets as we go along, which will have aâ€¦

461
01:17:40.270 --> 01:17:44.130
Faculty (Olympus): Large number of, large number of questions with them.

462
01:17:44.130 --> 01:17:55.569
Faculty (Olympus): Okay? There are also some online resources that I have suggested, in case you are interested. This is not necessary, for you to look at, but in case you're interested, you can also look at these.

463
01:17:55.950 --> 01:17:56.670
Faculty (Olympus): Okay?

464
01:17:56.900 --> 01:18:10.460
Faculty (Olympus): Okay, so yeah, with that, I'm done with what I wanted to say for this, first lecture. I can now, take questions, and I can resolve any concerns, you might have. Okay?

465
01:18:10.570 --> 01:18:12.570
Faculty (Olympus): Okay, yeah, Pradeep?

466
01:18:18.080 --> 01:18:27.160
Pradeep Kumar .: Yeah, yeah. Hi, Professor. So, my question was, on theâ€¦ I'm pulling thatâ€¦

467
01:18:30.080 --> 01:18:34.860
Pradeep Kumar .: So, on the ex- on the explicit,

468
01:18:34.970 --> 01:18:39.890
Pradeep Kumar .: I believe the explicit, Yes.

469
01:18:40.710 --> 01:18:42.700
Pradeep Kumar .: I'm sorry, I just lost that.

470
01:18:47.190 --> 01:18:49.159
Bipin Karyakarte .: So, Professor, can I ask aâ€¦

471
01:18:49.160 --> 01:18:52.220
Ashwini Bende .: Explicit estimation, probably.

472
01:18:52.220 --> 01:19:03.510
Pradeep Kumar .: Right, yeah, yeah, yeah. So it's on the explicit, estimation. I was just curious, right, how we got that, value of 0.693.

473
01:19:03.850 --> 01:19:06.820
Faculty (Olympus): You mean log 2 by lambda for the median?

474
01:19:07.090 --> 01:19:07.680
Pradeep Kumar .: Right, right.

475
01:19:07.680 --> 01:19:20.080
Faculty (Olympus): Yeah, yeah, I mean, that is a calculation which weâ€¦ yeah, I mean, once youâ€¦ once we go over theâ€¦ howâ€¦ what a probability density is, what it means, how do we compute things, that'll be very, very clear.

476
01:19:20.300 --> 01:19:29.690
Faculty (Olympus): So, yeah, you don't have to worry about it right now, but yeah, once we've done, once we have covered density, etc, that'll be very easy to compute.

477
01:19:30.390 --> 01:19:48.589
Pradeep Kumar .: Okay, okay, one more thing, so, in Pearson correlation coefficient, so the numbers, right, the indicators you were using, so is there any unit also for that? Let's say, when we are talking about, screen time, I think those must beâ€¦

478
01:19:48.590 --> 01:19:55.100
Faculty (Olympus): Actually, one of the utilityâ€¦ I mean, one of the reasons this is very popular is this is a unitless quantity.

479
01:19:55.650 --> 01:20:04.520
Faculty (Olympus): Okay, so you can see that whatever these units of these Xi's and Yi's might be, they cancel out. So what you get is a unitless quantity.

480
01:20:06.260 --> 01:20:09.530
Pradeep Kumar .: Okay, okay. Yeah, yeah, that'sâ€¦ thank you for answering.

481
01:20:09.530 --> 01:20:11.540
Faculty (Olympus): Okay? Rahul?

482
01:20:15.000 --> 01:20:22.759
Rahul Joshi .: Yeah, my question is, the term feature which you used, so if one model is having, let's say, four attributes in that.

483
01:20:22.890 --> 01:20:26.140
Rahul Joshi .: Whether each attribute is referred as a feature.

484
01:20:26.540 --> 01:20:27.990
Faculty (Olympus): That's what I meant, yeah, yeah.

485
01:20:29.570 --> 01:20:31.790
Rahul Joshi .: And that is the standard term, right, for theâ€¦

486
01:20:31.790 --> 01:20:32.769
Faculty (Olympus): Yeah, yeah, yeah, sure.

487
01:20:32.770 --> 01:20:33.360
Rahul Joshi .: Okay.

488
01:20:34.650 --> 01:20:36.890
Faculty (Olympus): Okay? Niraj?

489
01:20:38.620 --> 01:20:40.080
Niraj Kumar Mishra .: Okay, thanks, Professor.

490
01:20:40.150 --> 01:20:56.479
Niraj Kumar Mishra .: So, my question is actually about data, right? So, in both the examples that you have explained, the key thing here is data, right? So, we have usable data for both the examples. What if I don't have usable data? We do have data, but the data is very raw in nature.

491
01:20:56.480 --> 01:21:06.700
Niraj Kumar Mishra .: So, will there be any lecture to, you know, guide us how to make the raw data in usable form, so that we can apply the aesthetics and probability?

492
01:21:07.430 --> 01:21:21.389
Faculty (Olympus): So, again, this is not, I wouldn't cover it. This might be part of some of your other courses on either programming for machine learning or the machine learning course, where they teach you about data cleaning.

493
01:21:21.740 --> 01:21:25.540
Faculty (Olympus): It wouldn't be part of this course, certainly.

494
01:21:26.330 --> 01:21:27.570
Niraj Kumar Mishra .: Okay, thanks.

495
01:21:27.570 --> 01:21:42.419
Faculty (Olympus): So, if at all we think that the data isâ€¦ has noise, then we will just model that as a certain noise value. We wouldn't, necessarilyâ€¦ yeah, I wouldn't give you any prescriptions on how to clean the data. That's maybe part of some other course.

496
01:21:43.000 --> 01:21:45.130
Faculty (Olympus): Okay? Okay. Okay, Naina?

497
01:21:48.270 --> 01:22:05.450
Naina Punjwani .: Professor, sorry, this might be a very basic question. I'mâ€¦ after 2 decades, I'm going to my 10th grade or something, I feel. Can you suggest a book whereâ€¦ which I can refer for, like, the basics, just the basics to understand the words? Because, it'sâ€¦

498
01:22:05.500 --> 01:22:18.839
Naina Punjwani .: You know, it's been difficult to understand the session, to be very frank. I didn't go through the PPT yesterday. So, the, you know, lambda and these words are, you know, difficult to recollect now.

499
01:22:19.140 --> 01:22:36.670
Faculty (Olympus): So, again, maybe I would say, don't, maybe, judge yourself too harshly based on this first lecture. This was not supposed to be, something which everyone will follow everything. I wanted.

500
01:22:36.670 --> 01:22:37.300
Naina Punjwani .: No, I heard that.

501
01:22:37.300 --> 01:22:37.660
Faculty (Olympus): Okay.

502
01:22:37.660 --> 01:23:00.769
Naina Punjwani .: these are formulas which we would have, you know, Bi-hearted at that, you know, maybe many years ago, but I just want to understand that first book which you have suggested in your PBT. Will that give me a clear concept of what is modulus, how do you calculate modulars, and so on? Because mean, median, and this is still fine, because,

503
01:23:01.040 --> 01:23:05.420
Naina Punjwani .: that I might be teaching my son also now, I think.

504
01:23:05.420 --> 01:23:11.910
Faculty (Olympus): Yeah, yeah, everything will beâ€¦ I mean, in theseâ€¦ in the book that I'm suggesting, everything will be defined very, very clearly. It's a mathematical.

505
01:23:11.910 --> 01:23:12.850
Naina Punjwani .: Thank you.

506
01:23:12.850 --> 01:23:13.320
Faculty (Olympus): So everythingâ€¦

507
01:23:13.320 --> 01:23:20.550
Bipin Karyakarte .: No, I thinkâ€¦ I think, I think, Nikhil, what she probably is asking is a book for basic calculus or something like that.

508
01:23:20.550 --> 01:23:30.900
Faculty (Olympus): So, if youâ€¦ yeah, ifâ€¦ I mean, yeah, so basic calculus or, basic math, yeah, I don't have something on the top of my head,

509
01:23:31.470 --> 01:23:40.570
Faculty (Olympus): Yeah, it's, something that you can look up for. So, essentially, I think at least, whatâ€¦

510
01:23:40.990 --> 01:23:46.719
Faculty (Olympus): One thing that'll be, in fact, very useful, or you will encounter this often, isâ€¦

511
01:23:46.800 --> 01:23:57.729
Faculty (Olympus): being able to integrate, being able to differentiate, take limits, maybe. So this is all, high school math, but like you were saying, it might have been a long time since you've seen that.

512
01:23:57.730 --> 01:24:08.959
Faculty (Olympus): I don't have a reference directly, at least right now. Maybe some of your colleagues can, help you with that, if they know. Otherwise, I can find out something and share it on the group.

513
01:24:10.100 --> 01:24:13.170
Naina Punjwani .: The first book will also not cover the concepts you're saying.

514
01:24:13.170 --> 01:24:13.859
Faculty (Olympus): I meanâ€¦

515
01:24:13.860 --> 01:24:14.980
Naina Punjwani .: calculus.

516
01:24:14.980 --> 01:24:27.169
Faculty (Olympus): They will allâ€¦ I mean, they won't, they will always take you through the, let's say, the derivation of how this is happening, but wouldn't necessarily, show you how to integrate a function.

517
01:24:27.270 --> 01:24:28.540
Faculty (Olympus): Because that is our purpose.

518
01:24:28.540 --> 01:24:30.370
Naina Punjwani .: Formulas there, right, for it.

519
01:24:31.150 --> 01:24:36.250
Faculty (Olympus): Yeah, yeah, yeah. Formulas, etc. will all be there. So, okay. Yeah, yeah, yeah.

520
01:24:36.350 --> 01:24:38.020
Faculty (Olympus): So I would say maybe have a look at it.

521
01:24:38.180 --> 01:24:43.370
Naina Punjwani .: Now, in the screen, I understand, is the correlation formula, right? Correct me if I'm wrong.

522
01:24:43.370 --> 01:24:48.720
Faculty (Olympus): Yeah, yeah, so it's a correlation coefficient. This is like a formula which is defined for correlation coefficient.

523
01:24:50.840 --> 01:24:51.390
Faculty (Olympus): Yeah.

524
01:24:51.390 --> 01:24:52.070
Naina Punjwani .: Okay.

525
01:24:52.310 --> 01:24:59.440
sanket shah .: Yeah, so just, oh, sorry to interrupt. So you, you canâ€¦

526
01:24:59.440 --> 01:25:03.730
Faculty (Olympus): Can we go in order, please? I'll come to everyone.

527
01:25:03.730 --> 01:25:15.489
sanket shah .: it will be actually helpful for her. So, like, I'm justâ€¦ I'm just trying to add a reference point for her, which would help her. So, you can,

528
01:25:15.890 --> 01:25:24.170
sanket shah .: open, 12 standard book, oftenâ€¦ Author, which is called asâ€¦

529
01:25:25.180 --> 01:25:31.540
sanket shah .: Rhish Karma, and, helpful, like, for differentiation integration.

530
01:25:32.760 --> 01:25:34.219
sanket shah .: Cool. Yeah.

531
01:25:34.350 --> 01:25:37.720
Bipin Karyakarte .: Can youâ€¦ can you put the name in the chat, Sanketh?

532
01:25:37.720 --> 01:25:40.270
sanket shah .: Sure, sure, sure. I'll put it. No worries.

533
01:25:42.440 --> 01:25:47.980
Faculty (Olympus): Okay, yeahâ€¦ Rahul?

534
01:25:49.160 --> 01:25:53.100
Rahul Bajaj: Hey, Professor, two quick questions. One was with theâ€¦

535
01:25:53.250 --> 01:25:57.730
Rahul Bajaj: this, correlation coefficient. You had mentioned that,

536
01:25:58.520 --> 01:26:03.500
Rahul Bajaj: Ideally, for a robust model, you should select those features which

537
01:26:03.650 --> 01:26:11.330
Rahul Bajaj: have the, like, the correlation coefficient as zero, so that then the model is more robust. Is that the correct understanding?

538
01:26:12.070 --> 01:26:25.439
Faculty (Olympus): No, so it depends on, okay, what I was saying was, if your target variable is Y, you want to select, select, essentially, features which have high correlation with Y.

539
01:26:27.000 --> 01:26:39.869
Faculty (Olympus): because you want that there should be dependence between X and Y, because you want to choose X as a predictor for Y, right? So if X and Y are uncorrelated, then X is not going to be a good predictor for Y.

540
01:26:40.480 --> 01:26:50.099
Faculty (Olympus): But, if you have, let's say, you have X1, X2, and X3, these are 3 possible predictors, you can only choose 2 out of them.

541
01:26:50.730 --> 01:26:56.200
Faculty (Olympus): Thenâ€¦ If X1 and X2 are themselves very, very highly correlated.

542
01:26:56.470 --> 01:27:01.880
Faculty (Olympus): Right? Think of X1 and X2 being as, very, veryâ€¦ almost equal to each other.

543
01:27:02.140 --> 01:27:07.140
Faculty (Olympus): Right? Or very, very tightly correlated, then selecting both of them is not useful.

544
01:27:07.940 --> 01:27:16.179
Faculty (Olympus): Right? Correct. Because they are essentially representing exactly the same information, so I can sparsify things, I can select one of the two.

545
01:27:16.240 --> 01:27:29.019
Faculty (Olympus): And then select maybe X3, which might beâ€¦ so amongst the predictors themselves, you want the correlation to not be too large, but from predictor to the target variable, you want the correlation to be large.

546
01:27:29.930 --> 01:27:32.259
Faculty (Olympus): Or the modulus of the correlation to be high.

547
01:27:32.770 --> 01:27:40.310
Rahul Bajaj: Borrowed. Okay. And the last, the last one was more general for the course, so in the, like, like, theâ€¦

548
01:27:40.420 --> 01:27:53.289
Rahul Bajaj: timetable, if you want to call it, that you're given for the 12 lectures. Yeah. Do you think it's advisable to, like, do a pre-read for each chapter, or you're gonna cover the basics for each chapter so that we don't need to, you know.

549
01:27:53.830 --> 01:28:01.399
Faculty (Olympus): I think it is useful, so I will usually share some form of my notes, beforehand.

550
01:28:01.670 --> 01:28:06.970
Faculty (Olympus): It'll be useful if you at least have a browse through through the notes so that you know what is going to be covered.

551
01:28:07.530 --> 01:28:10.710
Faculty (Olympus): But I will go over the material myself.

552
01:28:11.070 --> 01:28:12.400
Rahul Bajaj: Okay, thank you.

553
01:28:12.400 --> 01:28:13.020
Faculty (Olympus): Yeah.

554
01:28:13.600 --> 01:28:15.940
Faculty (Olympus): Okay, Vinay?

555
01:28:18.700 --> 01:28:20.450
vinay kaisar: Yeah. Am I audible?

556
01:28:20.450 --> 01:28:21.170
Faculty (Olympus): Yeah, yeah.

557
01:28:21.640 --> 01:28:37.620
vinay kaisar: I wasâ€¦ I was thinking, I had K-nearest, algorithm long back in my syllabus, so is this related? Because I seemâ€¦ because it seems the graph and all, are much related. So, can you give a brief on it?

558
01:28:37.930 --> 01:28:38.690
vinay kaisar: Thanks.

559
01:28:39.730 --> 01:28:54.339
Faculty (Olympus): So k nearest neighbors is, is, I mean, it's used in various different contexts, but it can be used for, supervised learning or unsupervised, learning when you are trying toâ€¦ for example, if you're trying to do some sort of.

560
01:28:54.380 --> 01:29:06.650
Faculty (Olympus): classification, then you mightâ€¦ and you have labels of your k-nearest neighbors, you might decide based on the labels of the k-nearest neighbors, what the label of a new test point is.

561
01:29:06.710 --> 01:29:17.749
Faculty (Olympus): Iâ€¦ it's aâ€¦ it's an ML algorithm for supervised or unsupervised learning. It's not directly related to anythingâ€¦ I mean, at least not directly related toâ€¦

562
01:29:17.870 --> 01:29:25.399
Faculty (Olympus): statistics and probability. One can use statistics and probability to study the performance of K-nearest neighbors.

563
01:29:25.810 --> 01:29:26.260
vinay kaisar: Okay.

564
01:29:26.260 --> 01:29:29.520
Faculty (Olympus): But, otherwise it's an algâ€¦ it's an ML algorithm.

565
01:29:31.480 --> 01:29:36.520
vinay kaisar: Cool, I'llâ€¦ I'll still get some, after the session. Thank you.

566
01:29:37.280 --> 01:29:38.869
Faculty (Olympus): Yeah, Bipin?

567
01:29:41.020 --> 01:29:45.440
Bipin Karyakarte .: Yeah, can you go to the page where you were showing the reference books?

568
01:29:45.650 --> 01:29:46.550
Faculty (Olympus): Sure, yeah.

569
01:29:53.300 --> 01:30:12.669
Bipin Karyakarte .: The next one. Okay, so now you have listed about 5 books and couple of online resources. Okay, definitely very difficult to go or, you know, keep all the 5 books, etc. So, if I ask you, like, which is the one book that I should go for, if at all I have to refer one book which will give me maximum.

570
01:30:12.670 --> 01:30:14.870
Faculty (Olympus): Yeah, that's the one in the boulder.

571
01:30:14.870 --> 01:30:17.360
Bipin Karyakarte .: Yeah, yeah, so that's the one in the bold, that is what.

572
01:30:17.360 --> 01:30:17.760
Faculty (Olympus): Yeah, yeah.

573
01:30:17.760 --> 01:30:22.700
Bipin Karyakarte .: should actually focus more on, and the other things I can always use, but this is the one, right?

574
01:30:22.700 --> 01:30:30.759
Faculty (Olympus): Yeah, so if there is material which is beyond this, then I will suggest specific references for those material.

575
01:30:30.880 --> 01:30:36.360
Faculty (Olympus): But in general, at least definitely in the first part of the course, the things that we cover are all going to be there.

576
01:30:36.680 --> 01:30:37.400
Bipin Karyakarte .: Okay.

577
01:30:37.400 --> 01:30:46.100
Faculty (Olympus): some form. I mean, they might not be exactly what I write, or what I do in class is not going to match exactly what is there, but you will always find those topics in that book.

578
01:30:46.250 --> 01:30:48.310
Bipin Karyakarte .: Absolutely fine. Thank you.

579
01:30:48.430 --> 01:30:50.130
Faculty (Olympus): Okay, Suyash?

580
01:30:54.520 --> 01:30:58.430
Sriananth Haripanth .: Yeah, Ashian. So, I'm assuming theâ€¦

581
01:30:58.430 --> 01:31:08.879
Faculty (Olympus): Sorry, can we please, again, let me follow what, the order in which I call, otherwise it becomes difficult. Is Suyash there?

582
01:31:14.410 --> 01:31:21.609
Faculty (Olympus): Okay, I can't hear you, Suresh, so please maybe try and fix your mic. In the meanwhile, Kedar.

583
01:31:23.540 --> 01:31:25.020
Kedar Digambar Gokhale .: Yes, Hopai Module.

584
01:31:25.020 --> 01:31:25.790
Faculty (Olympus): Yeah, yeah.

585
01:31:26.180 --> 01:31:34.539
Kedar Digambar Gokhale .: So this was about Pearson correlation, we talked about. Yeah. I believe the choice of, theâ€¦

586
01:31:34.620 --> 01:31:46.719
Kedar Digambar Gokhale .: choice of the factors or predictors will come from domain knowledge. But I was wondering how to deal with the predictors which might have some interdependence.

587
01:31:46.930 --> 01:31:59.979
Kedar Digambar Gokhale .: And then, do we haveâ€¦ is it, like, essential that the predictor has to be independent of each other, or if there are some underlying dependencies there, are we likely to get wrong predictions?

588
01:31:59.980 --> 01:32:07.740
Faculty (Olympus): So, again, that's what I was saying, if your predictors themselves are highly correlated with each other, then usually people remove one of them.

589
01:32:07.900 --> 01:32:23.019
Faculty (Olympus): So, that is also one way of, if you are, you know, if you areâ€¦ you don't want to choose predictors which are very, very tightly correlated with each other, because then they are essentially giving the same information, so it's, better to kind of eliminate one of them.

590
01:32:23.020 --> 01:32:28.010
Souvik Brahmachari: So, Marissa, I have a top-up question on topâ€¦ on that same question.

591
01:32:28.040 --> 01:32:43.310
Souvik Brahmachari: I'm so sorry. So, so ifâ€¦ if suppose that is, those two variables are notâ€¦ I mean, it's loosely correlated, not strongly, okay, but, still, it has a great influence on the main target variable, let's say.

592
01:32:43.690 --> 01:32:44.270
Faculty (Olympus): Going.

593
01:32:44.270 --> 01:32:54.380
Souvik Brahmachari: In that case, do we have to, you know, for each, each dependency, do we have to make independent, you know, Pearsonâ€¦

594
01:32:54.380 --> 01:33:18.829
Faculty (Olympus): No, no, I mean, see, all ofâ€¦ none of this is, is, written in stone. These are all, kind of, I would say, these are suggestive, so it depends. I mean, if your model can handle many, many features, then often you will take all of them, but then it might not perform the best when you take all the features, because you have a lot of correlation. So you try and removeâ€¦ you have some threshold for which

595
01:33:18.990 --> 01:33:35.870
Faculty (Olympus): Beyond which you remove and you select. I mean, all of this isâ€¦ it's really not aâ€¦ it's not science, it's an engineering thing about designing features. It's called feature engineering because it's not really an absolute science, it's more like an engineering thing. You try and get some sense of what might be good features and what are not.

596
01:33:36.200 --> 01:33:45.359
Faculty (Olympus): So, again, that's not really what we are going to cover in the course. Here, it's more to do with, I would say, the engineering behind machine learning.

597
01:33:46.210 --> 01:33:47.139
Kedar Digambar Gokhale .: Got it. Thank you, sir.

598
01:33:47.140 --> 01:33:47.670
Faculty (Olympus): Yeah.

599
01:33:48.200 --> 01:33:53.149
Faculty (Olympus): Okay, anuj Gupta?

600
01:33:54.720 --> 01:33:56.799
Anuj Gupta: Yeah, hi, Nikhil. Am I audible?

601
01:33:56.800 --> 01:33:57.649
Faculty (Olympus): Yeah, yeah, yeah.

602
01:33:57.650 --> 01:34:15.849
Anuj Gupta: Yeah, okay, Nikhil, I got first question answered is, like, around the book, actually, which you were suggesting it. I was just checking the contents, the contents looks good. Other thing I was asking is, Nikhil, so the next lecture which we'll be having with, I think, De Manjinas tomorrow, soâ€¦

603
01:34:15.850 --> 01:34:17.929
Faculty (Olympus): You have a lecture with him tomorrow?

604
01:34:17.930 --> 01:34:19.720
Anuj Gupta: I'm not sure, I mean, it's with usâ€¦

605
01:34:19.920 --> 01:34:22.480
Anuj Gupta: data science, right? I think it should be a.

606
01:34:24.110 --> 01:34:25.089
Faculty (Olympus): No, no, it's not okay.

607
01:34:25.090 --> 01:34:25.790
Bipin Karyakarte .: Yeah.

608
01:34:25.790 --> 01:34:29.209
Anuj Gupta: So, both of these lectures will go hand-by-hand, kind of.

609
01:34:29.210 --> 01:34:32.430
Faculty (Olympus): No, no, weâ€¦ no, no, it won't.

610
01:34:32.540 --> 01:34:42.569
Faculty (Olympus): Yeah, it notâ€¦ yeah, it really won't, youâ€¦ so it at least won't have happened temporarily, meaning it's not like the same topic is going to be covered in both spaces.

611
01:34:42.570 --> 01:34:56.459
Faculty (Olympus): Okay. You will see some of the same terms appearing in both courses, and we will kind of give maybe more foundational things, or how these estimators come about, and they will be teaching you more about how to implement them.

612
01:34:56.460 --> 01:35:00.179
Faculty (Olympus): And so on. But they won't happen side by side.

613
01:35:00.740 --> 01:35:11.469
Anuj Gupta: Okay, and the last thing, Nikh is, like, I mean, we are talking about these formulas and those things. I mean, I mean, I don't want to jump onto that, like, kind of thing, but these will be available in the Python APIs also, right?

614
01:35:11.470 --> 01:35:15.199
Faculty (Olympus): So, I mean, the ones thatâ€¦ this correlation, coefficient, etc, I'm sure these are all.

615
01:35:15.200 --> 01:35:15.540
Anuj Gupta: Yeah.

616
01:35:15.540 --> 01:35:16.379
Faculty (Olympus): invite an API.

617
01:35:16.750 --> 01:35:17.369
Faculty (Olympus): Yeah, yeah.

618
01:35:17.370 --> 01:35:20.060
Anuj Gupta: Oh, okay, okay, sure, Nitin, that was it.

619
01:35:20.230 --> 01:35:20.790
Faculty (Olympus): Okay.

620
01:35:21.000 --> 01:35:22.420
Faculty (Olympus): Okay, summer?

621
01:35:26.820 --> 01:35:28.860
Samar .: Nikh, am I audible?

622
01:35:28.860 --> 01:35:30.089
Faculty (Olympus): Yeah, yeah, yeah.

623
01:35:30.450 --> 01:35:40.889
Samar .: So, I have a question, like, since we talked about mean and median, and we kind of said, like, if there is a noisy data in the mean.

624
01:35:41.340 --> 01:35:54.020
Samar .: the mean could be skewed, or it could be impacted, right? Similarly, when we talk about these, problemâ€¦ probabilistic models, exponential distribution, correlation.

625
01:35:55.230 --> 01:36:00.950
Samar .: does these models also have kind of nuances like that? Like, if we have someâ€¦

626
01:36:01.330 --> 01:36:05.859
Samar .: Somethingâ€¦ some variable which impacts the outcome of these, andâ€¦

627
01:36:06.070 --> 01:36:21.409
Faculty (Olympus): Yeah, yeah, for example, I mean, this lambdaâ€¦ so our exponential model was parameterized by, lambda, right? So, if your lambda itself is erroneous, then it will certainly, impact, how the model performs.

628
01:36:21.410 --> 01:36:28.720
Faculty (Olympus): So, how good your estimate of lambda is also impacts, yourâ€¦ How good the model is.

629
01:36:30.610 --> 01:36:31.470
Samar .: Okay.

630
01:36:31.470 --> 01:36:31.790
Faculty (Olympus): Yeah.

631
01:36:31.790 --> 01:36:35.009
Samar .: So it's more related to the quality of the data, is that what.

632
01:36:35.010 --> 01:36:42.980
Faculty (Olympus): Yeah, it relates to the quality of the data, the quantity of the data. The more data you have, the better estimate of these parameters you can build.

633
01:36:43.090 --> 01:36:47.940
Faculty (Olympus): If you have very little data, then the parameter estimates will be very off.

634
01:36:48.140 --> 01:36:52.500
Faculty (Olympus): And so you will not be able to construct a good model It's go on.

635
01:36:53.200 --> 01:37:00.149
Samar .: Okay, and just maybe one last thing, like, when we talk about this correlation coefficient, if we have more than

636
01:37:00.290 --> 01:37:06.169
Samar .: two variables, can we fit into this same equation, orâ€¦

637
01:37:06.400 --> 01:37:06.674
Samar .: Oh.

638
01:37:06.950 --> 01:37:12.549
Faculty (Olympus): So, you usually compute these pairwise. That is how correlation coefficient is computed, yeah.

639
01:37:12.670 --> 01:37:14.029
Samar .: Okay, thank you, thanks a lot.

640
01:37:14.850 --> 01:37:16.260
Faculty (Olympus): Yeah, Charu?

641
01:37:19.270 --> 01:37:27.600
Charu .: Hey, hi, hi, Professor. Hello, everyone. I just wanted to check, is there any other book related to probability, related to machine learning and data science?

642
01:37:28.040 --> 01:37:34.990
Charu .: Resident-specific on a probability. I just want to read something related to machine learning and data science.

643
01:37:35.880 --> 01:37:47.850
Faculty (Olympus): So, I mean, there are, again, there are many, many books on machine learning and data science, but I would say maybe that is a question for someoneâ€¦ I mean, whichever faculty is teaching you machine learning.

644
01:37:48.340 --> 01:37:52.459
Charu .: No, no, no, I'm asking probability, probability for machine learning and data science.

645
01:37:52.850 --> 01:37:54.460
Charu .: Specific to machine learning.

646
01:37:56.410 --> 01:37:57.409
Charu .: I'm so sorry.

647
01:37:57.410 --> 01:38:06.660
Faculty (Olympus): Yeah, I mean, thereâ€¦ thereâ€¦ again, I have to, I don't, have an answer for you immediately. There are, again, many, many of the onesâ€¦ which one might beâ€¦

648
01:38:07.220 --> 01:38:11.000
Faculty (Olympus): the most suitable, I will have to think.

649
01:38:11.000 --> 01:38:12.700
Charu .: Naray, can you please let us know.

650
01:38:12.700 --> 01:38:13.690
Faculty (Olympus): Yeah, yeah, sure.

651
01:38:14.100 --> 01:38:15.229
Faculty (Olympus): Sure, sure, sure.

652
01:38:15.400 --> 01:38:16.160
Charu .: Thank you.

653
01:38:16.160 --> 01:38:16.850
Faculty (Olympus): Okay?

654
01:38:17.190 --> 01:38:19.020
Faculty (Olympus): Yashidish?

655
01:38:20.270 --> 01:38:36.900
Siddhesh Dinesh Kadam .: Yeah, just, two questions. First, the book which you've suggested, there are quite a few editions online, I just checked. Any particular one? I saw 10th edition, 9th edition, Global Edition, US edition, so anything which youâ€¦

656
01:38:36.900 --> 01:38:47.440
Faculty (Olympus): I mean, whichever is the latest edition should be okay, just thatâ€¦ by the way, I mean, Ross has written many different books, so just make sure that the title is a first course in probability.

657
01:38:48.060 --> 01:38:58.240
Faculty (Olympus): And there are usually not too many changes. It's a classical text, so there are not too many changes across editions, but yeah, it'll be useful if you get more,

658
01:38:58.820 --> 01:38:59.470
Siddhesh Dinesh Kadam .: and snagging.

659
01:38:59.470 --> 01:39:00.920
Faculty (Olympus): newer addition.

660
01:39:00.920 --> 01:39:13.929
Siddhesh Dinesh Kadam .: Thanks, thanks for that. Second question is, as a part of this course, are we, going to study about how is theâ€¦ as an example, how did the Pearson correlation formula come into existence?

661
01:39:13.930 --> 01:39:14.490
Faculty (Olympus): Yeah, yeah, yeah.

662
01:39:14.490 --> 01:39:17.550
Siddhesh Dinesh Kadam .: Like, if we assume E equal to MC squared own question.

663
01:39:17.740 --> 01:39:30.300
Faculty (Olympus): No, no, it'll be clear as to what thoseâ€¦ what these things encode, where did theâ€¦ where did that formula come from, or at least what are the components of that formula, what is it representing? All of that will be clear.

664
01:39:30.650 --> 01:39:31.969
Siddhesh Dinesh Kadam .: Okay, thanks.

665
01:39:32.330 --> 01:39:33.010
Faculty (Olympus): Sure.

666
01:39:33.290 --> 01:39:34.590
Faculty (Olympus): Yash?

667
01:39:38.820 --> 01:39:40.199
Yash Goyani .: Hi, good evening. Am I audible?

668
01:39:40.450 --> 01:39:41.320
Faculty (Olympus): Yeah, yeah.

669
01:39:41.720 --> 01:39:42.940
Yash Goyani .: Yeah,

670
01:39:43.100 --> 01:39:53.089
Yash Goyani .: Yeah, so, a quick question. You just have skipped, the second case, which seems very interesting, and it's a bit more complicated. Yeah.

671
01:39:53.260 --> 01:39:55.910
Yash Goyani .: So, will that be taken up,

672
01:39:55.910 --> 01:39:59.680
Faculty (Olympus): Yeah, yeah, we'll do that at some point later on, definitely.

673
01:39:59.680 --> 01:40:01.180
Yash Goyani .: Okay, fine. Thank you.

674
01:40:01.360 --> 01:40:02.340
Faculty (Olympus): Yeah, sure.

675
01:40:02.470 --> 01:40:04.659
Faculty (Olympus): Dr. Milind?

676
01:40:07.470 --> 01:40:10.220
Dr Milind Vaishnav .: Hi, can we know the homework, sir?

677
01:40:11.450 --> 01:40:13.969
Faculty (Olympus): sorry, what,

678
01:40:13.970 --> 01:40:17.690
Dr Milind Vaishnav .: You said there will be a homework to be given at the end of this session.

679
01:40:17.910 --> 01:40:32.920
Faculty (Olympus): Not at the end of this session. Once we've covered a little bit of material, then we will put up homeworks which have practice problems, and these homeworks willâ€¦ some of these questions you have to solve and submit, and some of them will be solved during the TA sessions.

680
01:40:33.170 --> 01:40:34.240
Dr Milind Vaishnav .: Okay, okay, thanks.

681
01:40:34.510 --> 01:40:35.230
Faculty (Olympus): Sure.

682
01:40:35.380 --> 01:40:36.680
Faculty (Olympus): Mahan?

683
01:40:40.340 --> 01:40:41.430
Mayank Johri .: broker, whoâ€¦

684
01:40:41.430 --> 01:40:42.279
Mayengbam Ronendro Singh .: Yes, yes.

685
01:40:43.340 --> 01:40:45.799
Mayengbam Ronendro Singh .: You're calling on my name, sorry,

686
01:40:46.460 --> 01:40:50.529
Mayengbam Ronendro Singh .: This is my, actually, house name, so my real name is, Ronendro, which is the second one.

687
01:40:50.530 --> 01:40:54.039
Faculty (Olympus): No, no, sorry, yeah, I was calling for Mayank, butâ€¦

688
01:40:54.040 --> 01:40:54.600
Mayengbam Ronendro Singh .: on.

689
01:40:54.600 --> 01:40:56.239
Faculty (Olympus): Go ahead.

690
01:40:56.240 --> 01:40:56.800
Mayank Johri .: Butâ€¦

691
01:40:59.200 --> 01:41:01.449
Faculty (Olympus): Either one is okay, Ron.

692
01:41:03.410 --> 01:41:06.009
Mayank Johri .: Okay, I'll go ahead. Raf, am I audible?

693
01:41:06.010 --> 01:41:06.830
Faculty (Olympus): Yeah, yeah, yeah.

694
01:41:07.330 --> 01:41:23.899
Mayank Johri .: Okay, so profâ€¦ basically, I have two follow-up questions. The data that you have shown for Pearson correlation coefficient looks like, to me, was a linear association. So what happens if the two variables have a non-relationâ€¦ a nonlinear relationship?

695
01:41:23.900 --> 01:41:24.220
Faculty (Olympus): Okay.

696
01:41:24.220 --> 01:41:35.250
Mayank Johri .: thing. So, should we still be choosing Pearson correlation coefficient model? And the second one is, how sensitive is the Pearson correlation to the outliers?

697
01:41:35.370 --> 01:41:36.310
Mayank Johri .: Soâ€¦

698
01:41:36.310 --> 01:41:45.519
Faculty (Olympus): Yeah, so, I mean, yeah, Pearson coefficient, or these correlation coefficients usually, only measure linear dependence.

699
01:41:45.980 --> 01:41:56.170
Faculty (Olympus): In the sense that, they will take plus 1 or minus 1 when the data is exactly linear, when the relationship is exactly linear.

700
01:41:56.460 --> 01:41:59.329
Faculty (Olympus): Ifâ€¦ for nonlinear,

701
01:41:59.480 --> 01:42:17.530
Faculty (Olympus): kind of dependencies, there are other correlation coefficients. You can also kind of model nonlinear dependencies byâ€¦ essentially, I mean, where you have X and Y, you can also think of X squared and Y, and then look at the dependence between X square and y, or calculate the correlation coefficient between X square and y.

702
01:42:17.730 --> 01:42:32.359
Faculty (Olympus): That is also one way of handling, things, but there areâ€¦ you are right that, the Pearson correlation coefficient does depend on, I mean, is trying to, estimate linear dependence. That is, definitely true.

703
01:42:32.830 --> 01:42:49.770
Faculty (Olympus): And in terms of outliers, yeah, I mean, it depends. It is something that is dealing with averaging and, also takes into account variance, so if you haveâ€¦ how good it is depends on the size of the data that you have.

704
01:42:49.820 --> 01:42:58.769
Faculty (Olympus): So if you have a good amount of data, then you will have a better estimate, and if you have smaller data, then you have a weaker estimate.

705
01:43:00.350 --> 01:43:01.610
Mayank Johri .: Okay, thank you.

706
01:43:02.790 --> 01:43:05.319
Faculty (Olympus): Okay, Apurv?

707
01:43:07.520 --> 01:43:09.549
Apurv Singh .: Right? So,

708
01:43:09.880 --> 01:43:17.270
Apurv Singh .: what I can see is that a lot of people in this class, they are, like, coming back to school and relearning a lot of things thatâ€¦

709
01:43:17.270 --> 01:43:18.020
Faculty (Olympus): Yay.

710
01:43:18.860 --> 01:43:27.649
Apurv Singh .: they had learned a very long time ago. My question is that, the first book that you've told us, or First Course in Probability.

711
01:43:27.750 --> 01:43:34.610
Apurv Singh .: It's got almost 900 pages. I'd just like to know where to start, and is there any section that is important?

712
01:43:34.610 --> 01:43:46.440
Faculty (Olympus): So, start from theâ€¦ yeah, yeah, so, I mean, right now, when youâ€¦ when youâ€¦ when I post the first set of notes, that'll give you a sense of where to begin, but you should begin from the beginning.

713
01:43:46.780 --> 01:43:53.030
Faculty (Olympus): Okay. I would say, if you're starting to read the book, just begin from the beginning, that's where we'll start from.

714
01:43:54.230 --> 01:43:54.630
Apurv Singh .: Sorry.

715
01:43:54.630 --> 01:43:56.800
Faculty (Olympus): We'll start from the basics of probability.

716
01:43:59.130 --> 01:44:04.110
Faculty (Olympus): Yeah, and when I post the notes, I will also mention what chapter, maybe, to look at.

717
01:44:04.810 --> 01:44:06.729
Apurv Singh .: Yeah, that's perfect, thanks.

718
01:44:06.730 --> 01:44:09.680
Faculty (Olympus): Okay. Sunil Ravut?

719
01:44:11.700 --> 01:44:12.790
Sunil Rawat .: Hey, hi, Professor.

720
01:44:12.790 --> 01:44:13.240
Faculty (Olympus): Bye.

721
01:44:13.240 --> 01:44:17.980
Sunil Rawat .: Thanks for suggesting books. Can you please go to the previous slide?

722
01:44:19.450 --> 01:44:19.980
Sunil Rawat .: Justâ€¦

723
01:44:19.980 --> 01:44:21.760
Faculty (Olympus): Yeah, sorry.

724
01:44:22.610 --> 01:44:28.980
Sunil Rawat .: Sorry, one, one before this. Where you mentioned about separating signals from randomness.

725
01:44:28.980 --> 01:44:30.320
Faculty (Olympus): Is this the one?

726
01:44:30.320 --> 01:44:30.980
Sunil Rawat .: Yes, yes.

727
01:44:30.980 --> 01:44:31.379
Faculty (Olympus): Yeah, yeah, yeah.

728
01:44:31.380 --> 01:44:35.859
Sunil Rawat .: Because this is the one here you mentioned about separating signals from randomness.

729
01:44:35.860 --> 01:44:36.380
Faculty (Olympus): Yo.

730
01:44:36.380 --> 01:44:41.989
Sunil Rawat .: So, is this something that we are going to cover as part of our future chapters or future.

731
01:44:41.990 --> 01:44:45.199
Faculty (Olympus): Yeah, yeah, we will talk about things of this nature.

732
01:44:45.200 --> 01:44:48.810
Sunil Rawat .: Okay, so it will also be covering identifying

733
01:44:48.930 --> 01:44:55.320
Sunil Rawat .: Features which are actual signals from the random signals that we have in the data center, right?

734
01:44:55.340 --> 01:45:05.459
Faculty (Olympus): Yeah, I mean, in some form, so I would say, yeah, maybe let'sâ€¦ let's see how things proceed, and then at some point, I think we will cover things of this nature.

735
01:45:05.600 --> 01:45:06.310
Sunil Rawat .: Okay, thank you.

736
01:45:06.310 --> 01:45:06.730
Faculty (Olympus): Yeah.

737
01:45:06.730 --> 01:45:07.950
Sunil Rawat .: Thanks for joining us.

738
01:45:07.950 --> 01:45:11.829
Faculty (Olympus): Sure. Yeah, Rahul?

739
01:45:12.580 --> 01:45:25.390
Rahul Joshi .: Hello, Professor. Just one question. So, statistics, topics, etc. make sense, like, we will be studying them. How much from the, calculus, like, we have to go deep into?

740
01:45:25.440 --> 01:45:32.880
Rahul Joshi .: For example, integration and the limit, and the triple integration, and all that. How muchâ€¦ because we have to prepare, we have not studied it for a long time.

741
01:45:32.880 --> 01:45:57.719
Faculty (Olympus): Yeah, yeah, so I mean, I would say that you should know how to do integration and differentiation and limits. I mean, yeah, I think it takes someâ€¦ you will have to recollect it a little bit, I agree, it'll require some preparation, but I think you will just enjoy things a little bit more. Things will be much more easier if those are things that you are

742
01:45:57.720 --> 01:45:58.610
Faculty (Olympus): prepared for.

743
01:45:58.620 --> 01:46:15.790
Faculty (Olympus): Otherwise, a lot of it might, seem like, you know, black magic. It's just happening, and I'm writing something, and it's turning out to be this, but if you know how to do those things, which Iâ€¦ I mean, it's just basic high school math, but I agree that it'll take some time to get back to that mode.

744
01:46:15.850 --> 01:46:20.510
Faculty (Olympus): But, I think it'll be useful if you know that.

745
01:46:20.510 --> 01:46:20.940
Rahul Joshi .: Levelâ€¦

746
01:46:20.940 --> 01:46:21.910
Faculty (Olympus): Basic things.

747
01:46:22.040 --> 01:46:24.620
Rahul Joshi .: Yeah, yeah, so maybe 12th Matt's book is a.

748
01:46:24.620 --> 01:46:26.239
Faculty (Olympus): Yeah, yeah, yeah, yeah, yeah.

749
01:46:26.240 --> 01:46:27.060
Rahul Joshi .: Okay, thank you.

750
01:46:27.060 --> 01:46:27.590
Faculty (Olympus): Yeah.

751
01:46:28.410 --> 01:46:31.299
Faculty (Olympus): Okay, Yavamsi Krishna?

752
01:46:36.300 --> 01:46:39.259
Vamsi Krishna Mutnuri .: Yes, thank you. Soâ€¦

753
01:46:39.900 --> 01:46:55.100
Vamsi Krishna Mutnuri .: My only question is that, since you will be taking almost the first half of this course, of this whole course, do you have any special recommendations for people coming from medical background, who do not have the 11th, 12th knowledge also of maths?

754
01:46:55.100 --> 01:47:00.740
Vamsi Krishna Mutnuri .: I agree that there is some basic preparation needed, for sure, but, do you,

755
01:47:00.740 --> 01:47:04.490
Vamsi Krishna Mutnuri .: I mean, do you have any special perspective for people from medical background?

756
01:47:05.090 --> 01:47:16.009
Faculty (Olympus): again, like I said, I mean, whatâ€¦ at least what we need isâ€¦ is, these basic things like, basic calculus. Thatâ€¦ that definitely, I think, is, required.

757
01:47:16.210 --> 01:47:23.530
Faculty (Olympus): And beingâ€¦ because this is a mathematical course, so really, I mean, I think it requires that level of mathematical,

758
01:47:24.150 --> 01:47:30.659
Faculty (Olympus): Yeah, you will have to perform mathematical computations, so I think it is important that you prepare yourself for it.

759
01:47:31.450 --> 01:47:38.100
Vamsi Krishna Mutnuri .: Understood. Thank you, and just whatâ€¦ an extension of that question is, I've just got a glimpse of the book which you recommended, the Ross Book of.

760
01:47:38.100 --> 01:47:38.630
Faculty (Olympus): Mhmh.

761
01:47:38.630 --> 01:47:47.710
Vamsi Krishna Mutnuri .: probability, and it started with permutations and combinations, and is that the same book, you know, you were recommending? Like, you know, is it the same,

762
01:47:47.890 --> 01:47:51.520
Vamsi Krishna Mutnuri .: The wayâ€¦ how to count the permutations and the combinations.

763
01:47:51.520 --> 01:48:04.569
Faculty (Olympus): I am guessing, I'm not exactly sure what the first chapter for that book is, I don't remember, but I canâ€¦ yeah, when I share my notes, I'll share what chapter I'm referring to.

764
01:48:04.770 --> 01:48:12.590
Faculty (Olympus): But if you search for, like, this particular book, then that should be the one, a first course in probability. It could be that that is the first chapter.

765
01:48:13.810 --> 01:48:15.630
Vamsi Krishna Mutnuri .: Understood. Thank you.

766
01:48:15.630 --> 01:48:17.220
Faculty (Olympus): Okay, Yashikar?

767
01:48:18.680 --> 01:48:19.830
Shikhar .: Hi, Professor.

768
01:48:19.830 --> 01:48:20.390
Faculty (Olympus): Yeah.

769
01:48:20.390 --> 01:48:33.220
Shikhar .: First of all, just let me know how to ask questions asynchronously offline, maybe, because this is a long queue, and it would be better if I can throw questions to you in any of the offline manner.

770
01:48:33.220 --> 01:48:43.329
Faculty (Olympus): Yeah, so I think there is some way Great Learning handles these through tickets. You can raise tickets and then send it. That is the way I think this, that's what I know of, at least.

771
01:48:43.330 --> 01:48:45.430
Shikhar .: The second question is very fundamental.

772
01:48:45.560 --> 01:48:50.989
Shikhar .: We'veâ€¦ we've been seeing logics, tests, and we wanted to find the models

773
01:48:51.190 --> 01:48:57.619
Shikhar .: to those tests, right? I just want to ask, what isâ€¦ what is the right definition of modeling itself? What is modeling?

774
01:48:58.720 --> 01:49:08.080
Faculty (Olympus): So, I mean, a model is like aâ€¦ I would say it's a way toâ€¦ So, Iâ€¦

775
01:49:08.880 --> 01:49:15.130
Faculty (Olympus): I would say it's like a way to fit what you are seeing, or represent what you are seeing.

776
01:49:15.560 --> 01:49:33.889
Faculty (Olympus): So when I say that, that I take the model of the daily spend as an exponential distribution, what that means is maybe, historically, I've seen a lot of data, and I've seen how thatâ€¦ how, you know, different spends, how frequently I see different spends, and then when Iâ€¦

777
01:49:33.890 --> 01:49:41.130
Faculty (Olympus): draw a curve around that historical data, I see something that looks like an exponential distribution, so I represent

778
01:49:41.130 --> 01:49:46.129
Faculty (Olympus): that as an exponential. So that is, like, a way to represent

779
01:49:46.210 --> 01:49:48.100
Faculty (Olympus): the reality, I would say.

780
01:49:48.760 --> 01:49:52.479
Shikhar .: So, the models will be always some formulas at the end.

781
01:49:52.830 --> 01:49:53.460
Shikhar .: Which one?

782
01:49:53.460 --> 01:50:00.640
Faculty (Olympus): I mean, so that is mathematical modeling. Mathematical modeling just means that you are writing a mathematical expression for that.

783
01:50:00.920 --> 01:50:03.510
Faculty (Olympus): That is what we willâ€¦ we will do in this course.

784
01:50:04.290 --> 01:50:05.120
Shikhar .: Thank you.

785
01:50:05.120 --> 01:50:06.740
Faculty (Olympus): Okay. Harshad?

786
01:50:14.210 --> 01:50:19.400
Faculty (Olympus): Okay, I can't, hear you, Harshad. Savo Suresh?

787
01:50:20.520 --> 01:50:21.369
Savalo Suresh Naroji .: Hey, hi.

788
01:50:21.500 --> 01:50:22.090
Faculty (Olympus): Alright.

789
01:50:22.250 --> 01:50:26.359
Savalo Suresh Naroji .: So, regarding the case one, can you go back to the one?

790
01:50:27.110 --> 01:50:28.440
Savalo Suresh Naroji .: First case?

791
01:50:32.610 --> 01:50:33.640
Faculty (Olympus): Ohâ€¦

792
01:50:43.330 --> 01:50:44.180
Faculty (Olympus): Okay?

793
01:50:44.590 --> 01:50:46.880
Savalo Suresh Naroji .: Soâ€¦ -Oh.

794
01:50:47.040 --> 01:50:53.229
Savalo Suresh Naroji .: go to theâ€¦ where we had, examples, right? Day spending, yeah.

795
01:50:53.340 --> 01:51:01.190
Savalo Suresh Naroji .: So, in this case, what we say is, like, there is just one outlier, right? Sure. Which isâ€¦

796
01:51:01.780 --> 01:51:14.560
Savalo Suresh Naroji .: which is, showing, average, like, a different from a mean, but then what if there are 4 different values in the same range? Yeah. So that willâ€¦

797
01:51:14.940 --> 01:51:29.089
Savalo Suresh Naroji .: give the average, like, push the average higher, right? But it is, like, out of 10 values, 4 values are the one which is higher, but median will be same, right, in that case, because medianâ€¦

798
01:51:29.090 --> 01:51:31.750
Faculty (Olympus): Canadianâ€¦ yeah, sure, yeah.

799
01:51:33.010 --> 01:51:37.039
Savalo Suresh Naroji .: always the middle value that we would take, soâ€¦

800
01:51:37.410 --> 01:51:48.120
Savalo Suresh Naroji .: In such case, when we say, like, medianâ€¦ median is the more robust value compared to the mean, that will not account right.

801
01:51:48.120 --> 01:51:59.300
Faculty (Olympus): I mean, that isâ€¦ thenâ€¦ thenâ€¦ so what we said was median is more robust to noise or outliers, but if you have 4 or 5 out of the 10 readings as being high, then these are no longer outliers, right?

802
01:51:59.420 --> 01:52:07.069
Faculty (Olympus): So, by definition, outliers are something which is, kind of, atypical. So, ifâ€¦

803
01:52:07.070 --> 01:52:12.650
Savalo Suresh Naroji .: How do you decide that? Like, we scan through all the values and take a residual?

804
01:52:12.650 --> 01:52:13.350
Faculty (Olympus): Yo.

805
01:52:13.350 --> 01:52:13.979
Savalo Suresh Naroji .: So you will kindâ€¦

806
01:52:13.980 --> 01:52:27.020
Faculty (Olympus): Kind ofâ€¦ generally, what you will do is you will plot this data, and you will see if there is, like, clear, you know, cluster of, cluster of data points together, and then a few which are outside.

807
01:52:27.020 --> 01:52:34.189
Faculty (Olympus): If that is the case, then the summary, you will take it as a median. If that is not really the case, then that is not a good summary either.

808
01:52:34.190 --> 01:52:36.369
Faculty (Olympus): Then you have to figure out some other way of doing it.

809
01:52:37.410 --> 01:52:48.299
Savalo Suresh Naroji .: Okay, yeah. Yeah. And regarding the homework part of it, when you say homework, it will be, like, handwritten homework that we have to do.

810
01:52:48.300 --> 01:52:49.040
Faculty (Olympus): Yeah, yeah, yeah.

811
01:52:49.040 --> 01:52:51.510
Savalo Suresh Naroji .: pictures and submit, orâ€¦ Yeah, yeah.

812
01:52:51.510 --> 01:52:54.979
Faculty (Olympus): No handwritten, and then pictures, or scan it, and submit.

813
01:52:55.410 --> 01:52:57.999
Savalo Suresh Naroji .: Okay, okay, yeah, that's it. Thanks.

814
01:52:58.000 --> 01:53:01.340
Faculty (Olympus): Okay. Yeah, Roshan.

815
01:53:02.210 --> 01:53:15.409
Roshan Mathane: Yeah, hi. So, in the example that you gave for the, Pearson coercion, coercion type, the range was between the minus 1 to 1. So, is this the standard range

816
01:53:15.550 --> 01:53:18.919
Roshan Mathane: Cross the other correlation types, orâ€¦

817
01:53:18.920 --> 01:53:26.770
Faculty (Olympus): No, I think this is for Pearson correlation coefficient. I don't recall what the range for other correlation coefficients are. It depends on that coefficient.

818
01:53:27.230 --> 01:53:29.990
Faculty (Olympus): I'm not sure if all of them are from minus 1 to 1.

819
01:53:30.830 --> 01:53:31.650
Roshan Mathane: Okay.

820
01:53:31.650 --> 01:53:32.270
Faculty (Olympus): Yeah.

821
01:53:33.720 --> 01:53:35.740
Faculty (Olympus): Okay? Yeahâ€¦

822
01:53:35.740 --> 01:53:43.320
Savalo Suresh Naroji .: Can I miss that, like, I had asked earlier one question regarding calculators are allowed. You said you'll answer later?

823
01:53:43.740 --> 01:53:48.929
Faculty (Olympus): Calculators, I mean, yeah, I think let's come to that when we are closer to the exam.

824
01:53:49.460 --> 01:53:50.110
Savalo Suresh Naroji .: Okay.

825
01:53:52.240 --> 01:53:55.109
Faculty (Olympus): Okay, Rahul,

826
01:53:55.110 --> 01:54:15.939
Rahul Joshi .: Yeah, thanks, Professoria. Quick question. So, whenever we are having a model, let's say 3 or 4 variables, and in any mathematical model, we expect that if it's a phi variable model, then 4 are known, and the fifth one you are predicting. In the real life, how reasonable it is to get the data for all the four variables consistently?

827
01:54:16.900 --> 01:54:35.029
Faculty (Olympus): So, it doesn't always happen, so you do a lot of cleaning of data. That also isâ€¦ wherever you have missing elements, you remove those rows, or you try and, kind of, you know, estimate those points, and then put estimates of, missing data. So, missing data is a big problem, and people deal with it.

828
01:54:35.130 --> 01:54:46.030
Faculty (Olympus): I mean, this is, again, more engineering than anything else. So, missing data is a problem, and people deal with it either by removing it, or by removing those rows. That's, like, all part of data cleaning.

829
01:54:48.530 --> 01:54:49.270
Faculty (Olympus): Okay. Yeah.

830
01:54:50.050 --> 01:55:00.249
Rahul Joshi .: And just one more, probably little open-ended question. See, generally, based on the domain knowledge, you have some assessment of the variables which drives the outcome.

831
01:55:00.250 --> 01:55:00.840
Faculty (Olympus): Sure.

832
01:55:00.840 --> 01:55:16.019
Rahul Joshi .: And sometimes you areâ€¦ you want to confirm those assessments, or sometimes it's the other way around. You don't know that, which variables are related. So, what is the rightâ€¦ I would say the very complicated models, what is the right trade-off between the two, actually?

833
01:55:16.720 --> 01:55:26.320
Faculty (Olympus): So, again, I mean, yeah, people do it in different ways. For example, one way of finding the right factors might be doing PCA of the data, and thenâ€¦

834
01:55:26.600 --> 01:55:32.119
Faculty (Olympus): Using the principal components as your features.

835
01:55:32.340 --> 01:55:46.749
Faculty (Olympus): Yeah, again, I mean, yeah, there areâ€¦ it'sâ€¦ it's just, yeah, there are many, many ways of doing it. I can't give you, like, a definite answer of whether this is the best or that is the best. There are many different ways in which, features areâ€¦

836
01:55:46.980 --> 01:55:50.609
Faculty (Olympus): Yeah, like I said, I mean, feature engineering itself is a big field.

837
01:55:50.780 --> 01:55:57.789
Faculty (Olympus): And, maybe this isâ€¦ these are topics that areâ€¦ that, your, programming for machine learning course will handle better.

838
01:55:58.160 --> 01:55:59.510
Rahul Joshi .: Okay, fine. Thank you so much.

839
01:56:00.200 --> 01:56:03.889
Faculty (Olympus): Okay, maybe the last two, Harshad,

840
01:56:04.530 --> 01:56:05.919
Harshad Dilip Behere .: Yeah, am I audible now, sir?

841
01:56:05.920 --> 01:56:06.839
Faculty (Olympus): Yeah, yeah, yeah.

842
01:56:06.840 --> 01:56:13.950
Harshad Dilip Behere .: Yeah, good evening, Professor. I was just trying to understand, as we were discussing about maybe with 12 standard integration and differential calculations, right?

843
01:56:13.950 --> 01:56:14.370
Faculty (Olympus): Yeah.

844
01:56:14.370 --> 01:56:19.979
Harshad Dilip Behere .: So, are we expected to do it in a handwritten way, or how it would be, actually, going forward?

845
01:56:19.980 --> 01:56:28.709
Faculty (Olympus): I would say you should know how to do differentiation and integration. Whether we allow calculators or not at the end, we'll see.

846
01:56:28.840 --> 01:56:34.270
Faculty (Olympus): But you should have a good sense of how to do at least basic differentiation and integration.

847
01:56:34.270 --> 01:56:39.300
Harshad Dilip Behere .: Okay, so it's like a typical notebook style, we have to start finding out answers there, okay.

848
01:56:39.300 --> 01:56:40.000
Faculty (Olympus): Yeah, yeah.

849
01:56:40.000 --> 01:56:41.089
Harshad Dilip Behere .: Thank you so much, Sam.

850
01:56:41.300 --> 01:56:46.210
Faculty (Olympus): Okay, yeah, one last, maybe, Prachiki Kumari,

851
01:56:47.260 --> 01:56:54.120
Lad Prachikumari Vijaykumar .: Yes, sir. So, I wanted to know that, during this course, Excel knowledge is required?

852
01:56:54.670 --> 01:56:55.440
Faculty (Olympus): Excel.

853
01:56:55.730 --> 01:56:56.330
Lad Prachikumari Vijaykumar .: Huh, yes.

854
01:56:56.330 --> 01:56:58.169
Faculty (Olympus): No, no, no, no. It's not me.

855
01:56:58.170 --> 01:57:00.639
Lad Prachikumari Vijaykumar .: Okay. Okay, fine. Thank you.

856
01:57:00.640 --> 01:57:01.300
Faculty (Olympus): Okay.

857
01:57:01.500 --> 01:57:07.289
Faculty (Olympus): Okay, no more questions, then we'llâ€¦ we'll end here.

858
01:57:07.290 --> 01:57:12.519
Mayengbam Ronendro Singh .: Yeah, Professor, I mean, I was trying to ask a question, but somehow, when I see, my hand got lowered anyway.

859
01:57:12.520 --> 01:57:13.599
Faculty (Olympus): Okay, okay, okay.

860
01:57:13.800 --> 01:57:16.280
Mayengbam Ronendro Singh .: So, my question was on theâ€¦

861
01:57:16.650 --> 01:57:23.809
Mayengbam Ronendro Singh .: correlation, because in the past, we have used other correlation, tools like, Spearman and Kendall.

862
01:57:23.810 --> 01:57:24.400
Faculty (Olympus): Sure, sure.

863
01:57:24.400 --> 01:57:31.689
Mayengbam Ronendro Singh .: But, in our course, we have only Pearson, which probably is considered not as good as Kendall or as.

864
01:57:32.170 --> 01:57:32.659
Faculty (Olympus): Yeah, yeah, yeah.

865
01:57:32.660 --> 01:57:35.350
Mayengbam Ronendro Singh .: Sure. So, could you please explain the reason for this one?

866
01:57:35.350 --> 01:57:45.150
Faculty (Olympus): No, no, I mean, yeah, this has nothing toâ€¦ yeah, please don't read anything into my choice of the correlation coefficient. This is just something that I would say is the most basic one.

867
01:57:45.300 --> 01:57:56.859
Faculty (Olympus): So I was just illustrating it using that. You're right, there are many different correlation coefficients, which some of the others might be more suited, suitable than this, and it depends on what kind of situation you are in.

868
01:57:56.990 --> 01:58:02.900
Faculty (Olympus): This was just to illustrate, how such correlation coefficients are used in practice.

869
01:58:03.080 --> 01:58:09.279
Faculty (Olympus): But, yeah, I'm not suggesting that this be the one that you use.

870
01:58:10.150 --> 01:58:11.340
Mayengbam Ronendro Singh .: Got it, Professor, thank you.

871
01:58:11.340 --> 01:58:12.230
Faculty (Olympus): Yeah, sure.

872
01:58:12.650 --> 01:58:19.630
Faculty (Olympus): Okay, alright, so we'll, meet, next time. Yeah, see you. Bye.

873
01:58:22.400 --> 01:58:23.199
vinay kaisar: Thank you.

874
01:58:23.200 --> 01:58:24.549
Samar .: Thank you, bye.

875
01:58:24.550 --> 01:58:25.070
Rosalin Biswal .: Thank you.

876
01:58:25.070 --> 01:58:26.859
Vidya Gavel: Thank you. Bye. Thank you so much.

877
01:58:27.330 --> 01:58:28.449
Mayank Johri .: Me too, bro.

