WEBVTT

1
00:18:08.790 --> 00:18:09.580
Faculty (Olympus): Hello.

2
00:18:10.940 --> 00:18:13.479
Faculty (Olympus): Sir, in case you're saying anything, it's not audible.

3
00:20:39.320 --> 00:20:41.040
Faculty (Olympus): Okay, now can you hear?

4
00:20:41.570 --> 00:20:42.180
Faculty (Olympus): Yes, sir.

5
00:20:42.510 --> 00:20:46.789
Faculty (Olympus): Okay, come on, I thought that was working. Okay, fine.

6
00:20:53.150 --> 00:20:54.270
Faculty (Olympus): All right.

7
00:20:55.050 --> 00:20:57.690
Faculty (Olympus): Man, these things always make a mess.

8
00:20:58.040 --> 00:20:58.750
Faculty (Olympus): Mmm.

9
00:20:59.390 --> 00:21:00.890
Faculty (Olympus): Okay.

10
00:21:04.000 --> 00:21:08.180
Faculty (Olympus): Okay, the screen is also on, right? Okay, my video is not on.

11
00:21:09.090 --> 00:21:12.830
Naina Punjwani .: Yeah, Professor, we can see your screen and we can hear you.

12
00:21:12.830 --> 00:21:13.630
Faculty (Olympus): Okay.

13
00:21:14.990 --> 00:21:16.719
Faculty (Olympus): God bless technology.

14
00:21:19.770 --> 00:21:28.440
Faculty (Olympus): We canâ€¦ Okay, any questions fromâ€¦ Anybody has any questions from last week's discussion?

15
00:21:31.300 --> 00:21:33.850
Faculty (Olympus): Or rather, last class's discussion?

16
00:21:39.550 --> 00:21:42.129
Faculty (Olympus): Okay, perfect reception, huh?

17
00:21:42.670 --> 00:21:43.340
Faculty (Olympus): Okay.

18
00:21:47.710 --> 00:21:48.850
Faculty (Olympus): Correct.

19
00:24:45.770 --> 00:24:47.330
Faculty (Olympus): Okay.

20
00:24:55.080 --> 00:24:56.650
Faculty (Olympus): Okay.

21
00:25:02.140 --> 00:25:05.320
Faculty (Olympus): Okay, I think, we can get started.

22
00:25:05.660 --> 00:25:09.939
Faculty (Olympus): So good morning, everybody. This is the second lecture.

23
00:25:10.090 --> 00:25:27.630
Faculty (Olympus): In this part of the course, I'mâ€¦ yeah, so in the second half, where we talk more about statistics and how to use the probability theory that we developed earlier, in the first part of this course. And I'll give you three techniques, which I'm going to elaborate upon.

24
00:25:27.900 --> 00:25:41.990
Faculty (Olympus): Yeah, just to remind you, you know, these are things that I'll keep telling at frequent intervals. Please maintain a notebook, you know, please write down as Iâ€¦ as I say things, because that's the only way, and that's the easiest way to understand what is going on.

25
00:25:42.360 --> 00:26:00.270
Faculty (Olympus): Okay, and try to revise the material at the first opportunity. We understand that not everything that we say in a lecture is immediately comprehensible, and some of these things take time, and try to find time, and make the opportunity to You know, make the opportunity to revise it at the first opportunity.

26
00:26:00.650 --> 00:26:10.230
Faculty (Olympus): I keep reiterating, learning takes time, so these are concepts that you have not seen before, or most of you may not have seen large fractions of this, of this.

27
00:26:10.530 --> 00:26:16.089
Faculty (Olympus): of this kind of a material and this kind of a reasoning. I mean, the reasoning here is very different from your standard reasoning.

28
00:26:16.260 --> 00:26:26.709
Faculty (Olympus): So you need that extra time. I mean, and especially because you've unlearned many of the things that you've, you think you have intuitively understood or you have an intuitive sense of.

29
00:26:27.080 --> 00:26:32.330
Faculty (Olympus): So that transition takes time, so it's important that you spend time, you know, sort of.

30
00:26:32.440 --> 00:26:34.549
Faculty (Olympus): Doing something at the last minute, andâ€¦

31
00:26:35.060 --> 00:26:38.109
Faculty (Olympus): Thinking that you'll get it at the last minute is almostâ€¦

32
00:26:38.410 --> 00:26:52.439
Faculty (Olympus): I mean, reasonablyâ€¦ I'm reasonably sure with this much experience that it's hard. I'll reiterate that learning is hard on the brain and possibly on the body. You have to bear the pain and make the effort, and it'sâ€¦ the fun is afterwards, after you've figured out

33
00:26:52.690 --> 00:26:57.630
Faculty (Olympus): I'll keep reiterating exam efficiency is incidental and not the goal of the course.

34
00:26:57.970 --> 00:27:05.839
Faculty (Olympus): And yeah, so the course is demanding, but not cruel. I just, I'll keep reiterating this phrase at regular terms.

35
00:27:06.350 --> 00:27:12.920
Faculty (Olympus): Okay, so as we mentioned in the last class, so in this part, I'm going to give you three statistical concepts.

36
00:27:13.040 --> 00:27:23.550
Faculty (Olympus): One is what we call estimation, okay? This isâ€¦ you have seen examples of this estimation earlier, when we estimated the fraction of people voting for a certain

37
00:27:23.780 --> 00:27:39.020
Faculty (Olympus): Voting for a certain party, or a fraction ofâ€¦ or the number of people viewing a particular program, or, you know, some amount ofâ€¦ and potentially doing some kind of an estimation of what will happen.

38
00:27:39.020 --> 00:27:50.089
Faculty (Olympus): you know, whenâ€¦ under different examples, I mean, what will happen, for example, if the MDR kicks in, so we want to sort of make some guesses on what is going to happen and so on.

39
00:27:50.970 --> 00:27:56.200
Faculty (Olympus): Now, that gives me into the next sort of topic that we call hypothesis testing.

40
00:27:56.380 --> 00:28:03.489
Faculty (Olympus): This is an extremely important, you know, cultural shift, if you will, about how to look at things.

41
00:28:03.870 --> 00:28:23.450
Faculty (Olympus): Okay, so you have, for example, you want to introduce a newâ€¦ or let's take the MDR example, okay? So MDR is going to be introduced on the UPI starting October 15th. So around, let's say, December 15th, you have to look at the total number of transactions and make some conclusion.

42
00:28:23.500 --> 00:28:31.130
Faculty (Olympus): Okay, you want to guess. Sorry, look at the data, and you want to make a hypothesis, not a guess. You want to make a hypothesis thatâ€¦

43
00:28:31.670 --> 00:28:35.640
Faculty (Olympus): The MDR has affected or not affected.

44
00:28:35.910 --> 00:28:43.109
Faculty (Olympus): the nature of the transactions or the usage of UPI. That's the hypothesis. You can make one of the two.

45
00:28:43.290 --> 00:28:51.630
Faculty (Olympus): And typically, the default would be because of various things that you believe in, you say you will begin with the belief.

46
00:28:51.770 --> 00:29:10.170
Faculty (Olympus): that the MDR has not affected UPI transactions, okay? Not affected the profile of the UPI transactions. That's what we call the null hypothesis. Again, I'm going to make all of this formal when we come to that particular topic, so we formulate that hypothesis.

47
00:29:10.360 --> 00:29:20.809
Faculty (Olympus): And then we collect the statistical evidence to ask. Is there reason to disbelieve this hypothesis? Is there sufficient statistical reason to disbelieve this hypothesis?

48
00:29:20.930 --> 00:29:23.930
Faculty (Olympus): Okay, so null hypothesis is what you are going to go with.

49
00:29:24.080 --> 00:29:33.470
Faculty (Olympus): And you're collecting the evidence to say if you have enough evidence to say this hypothesis is wrong. I cannot go on with this hypothesis.

50
00:29:33.640 --> 00:29:41.860
Faculty (Olympus): Okay, so the onus of proof, or what we call the burden of proof, is to prove that the statistical evidence does not

51
00:29:42.130 --> 00:29:49.490
Faculty (Olympus): Allow me to go with this hypothesis. I'll come back to this, why that is indeed the case, the philosophical arguments, etc, on that later.

52
00:29:49.620 --> 00:29:58.159
Faculty (Olympus): Okay, that, you know, the same thing is done for drug testing, the same thing is done in digital communication. It's the same idea that keeps repeating, but in different forms.

53
00:29:58.640 --> 00:30:01.669
Faculty (Olympus): The third topic that I'm going to discuss is what we call regression.

54
00:30:02.500 --> 00:30:16.819
Faculty (Olympus): You have what we call an explanatory variable and a response variable. Okay, so you want to be able to look at if, for example, the explanatory variable could be some X and the response variable could be some Y.

55
00:30:16.920 --> 00:30:24.700
Faculty (Olympus): Okay, you want to be able to put develop some kind of a relationship, a functional relationship between X and Y.

56
00:30:25.070 --> 00:30:36.180
Faculty (Olympus): Okay, so you're collecting data, pairs of XY, which is essentially sort of the earliest form of learning. You collect data and learning is essentially a step.

57
00:30:36.360 --> 00:30:44.670
Faculty (Olympus): Spectacularly generalized version of this idea. It's significantly more complex, but the basic idea comes from regression.

58
00:30:44.770 --> 00:30:58.090
Faculty (Olympus): So I'm going to takeâ€¦ and basic idea comes from all of this, okay? So I'm going to take a particular explanatory variable, or a bunch of explanatory variables, and then there is the response variable. I willâ€¦ I will sort ofâ€¦

59
00:30:58.280 --> 00:31:08.179
Faculty (Olympus): Hypothesize a model between the two, and then estimate the parameters of that model. That's anotherâ€¦ that's a view that we will have about regression.

60
00:31:08.760 --> 00:31:09.640
Faculty (Olympus): Okay.

61
00:31:10.420 --> 00:31:23.389
Faculty (Olympus): Yeah, and estimation, so just to give you, I mean, just to sort of recap what I just told you, muchâ€¦ estimation is much like what we saw in the case studies, provide more detailed descriptions about a particular phenomena, okay, andâ€¦

62
00:31:23.940 --> 00:31:37.219
Faculty (Olympus): These things are essentially what we will callâ€¦ these terms will be made more precise as we go along. You're looking for the best point estimate using different criteria. Criteria here corresponds to what do you mean by the term best.

63
00:31:37.690 --> 00:31:53.609
Faculty (Olympus): Okay, so best different people can have different interpretations to the term best and we will define best what do we mean when we say best and then develop the best way to estimate the quantity of interest based on the data that you have collected.

64
00:31:54.150 --> 00:31:54.870
Faculty (Olympus): Okay.

65
00:31:55.440 --> 00:32:07.890
Faculty (Olympus): Yeah, so another model is what we will call confidence intervals. We will, you know, once we start estimation, you will understand what these things mean. And interval estimates, essentially, these things are similar to error bars.

66
00:32:20.420 --> 00:32:23.139
Faculty (Olympus): Oh, I think I'll write it here.

67
00:32:26.300 --> 00:32:29.100
Faculty (Olympus): Oh, sorry. Yeah, I think I didn't.

68
00:32:29.340 --> 00:32:30.950
Faculty (Olympus): Similar toâ€¦

69
00:32:34.070 --> 00:32:36.149
Faculty (Olympus): What we called error bars.

70
00:32:37.810 --> 00:32:41.780
Faculty (Olympus): Okay, so the bars that we saw in many of the data.

71
00:32:42.190 --> 00:32:52.210
Faculty (Olympus): The second topic, as we called, is hypothesis testing. We make a claim, we formulate a statistical experience on whether we want to accept or reject that particular claim.

72
00:32:52.230 --> 00:33:03.740
Faculty (Olympus): And then you say, look, and you're making a certain decision now. How sure are you that your decision is correct? Okay, this thing will keep coming up again and again. How sure are you about whatever it is that you're trying to say?

73
00:33:03.740 --> 00:33:16.780
Faculty (Olympus): Okay? So you will have to quantify that confidence that you have in either accepting the claim or rejecting the claim. What is itâ€¦ whatever it is that you do, you will have to provide some amount of confidence associated with that.

74
00:33:17.140 --> 00:33:31.730
Faculty (Olympus): Okay, so that's what we call hypothesis testing, and regression is to propose a relationship between a set of explanatory variables, an example could be X, and the response variables, for example, will be denoted by Y. Come up with a relationship then, and then

75
00:33:31.790 --> 00:33:37.419
Faculty (Olympus): Formulate, and then estimate the parameters, and then check whether that is indeed the case or not.

76
00:33:38.270 --> 00:33:39.000
Faculty (Olympus): Okay.

77
00:33:39.980 --> 00:33:49.059
Faculty (Olympus): In all of this, we are going to be using many of the things that we have studied so far. We are going to be using the notion of probability density function, and

78
00:33:49.840 --> 00:33:51.070
Faculty (Olympus): Okay, we're going to be.

79
00:33:51.970 --> 00:33:53.379
Faculty (Olympus): We're going to be usingâ€¦

80
00:33:55.720 --> 00:34:02.610
Faculty (Olympus): We are going to be using the notion of probability density function and probability mass function, the notion of independent variables.

81
00:34:02.860 --> 00:34:11.319
Faculty (Olympus): These are two things that you have not been taught yet. I'm going to describe both of these concepts, central limit theorem and law of large numbers now.

82
00:34:12.060 --> 00:34:12.719
Faculty (Olympus): Bit.

83
00:34:13.690 --> 00:34:18.170
Faculty (Olympus): And just to recap what you have learned so far, you have learned the notion of probability.

84
00:34:18.460 --> 00:34:22.170
Faculty (Olympus): What exactly does it mean to assign probabilities to events?

85
00:34:22.449 --> 00:34:30.100
Faculty (Olympus): Okay? You haveâ€¦ for that, for theâ€¦ for this idea of probability, we have discovered some formulas, okay? So if you are lookâ€¦

86
00:34:30.159 --> 00:34:43.829
Faculty (Olympus): You define the property of an event as a number between 0 and 1, we call it a measure. Okay, there is, again, a more formal theory associated with measures, we won't go into that. We define the notion ofâ€¦ I mean, from that, we can obtain formulas

87
00:34:43.860 --> 00:35:01.059
Faculty (Olympus): for, you know, compound events, whether twoâ€¦ I mean, if you're looking at the union of events, the intersection of events, and so on, and then we foundâ€¦ we developed some approximations. One is what is called the union bound, and the other is what isâ€¦ other set of

88
00:35:01.090 --> 00:35:06.269
Faculty (Olympus): These approximations is what we call the Bonferroni inequalities. These are something that has been taught to you before.

89
00:35:07.340 --> 00:35:20.599
Faculty (Olympus): And this is an extremely important concept. So, you're looking at the notion of conditional probability, and what exactly are the properties of this? The conditional probability here means that you have an event A, or you're looking at it

90
00:35:20.740 --> 00:35:22.900
Faculty (Olympus): Looking at a random variable X,

91
00:35:23.020 --> 00:35:40.580
Faculty (Olympus): Okay, and you are told that some other event or the value of another random variable Y is given to you, or an event B has happened. If you're talking in the language of events, you're told that this has happened, you want to be able to give me the probability of this.

92
00:35:41.370 --> 00:35:54.599
Faculty (Olympus): Okay? Soâ€¦ so this becomes a conditional probability. For example, if you're told, when you're tossing aâ€¦ when you're casting a die or rolling a die, if you're told that it's an even number, and you're looking at the probability that what hasâ€¦ what comes up.

93
00:35:54.650 --> 00:36:08.659
Faculty (Olympus): is a 3, obviously the probability will be 0. But if you don't give me that information, what we call the unconditional probability, will be different from the conditional probability. If I give you additional information about something, then

94
00:36:08.660 --> 00:36:15.180
Faculty (Olympus): The randomness or the randomness of the quantity of interest will change with information that you get.

95
00:36:15.280 --> 00:36:30.269
Faculty (Olympus): Okay? So, if you're looking at two variables together, for example, height and the weight, if I tell you the height of somebody, you should be able to give me a slightly more informed description of the weight of that person.

96
00:36:30.650 --> 00:36:40.600
Faculty (Olympus): Okay? So height of somebody who is 6 feet tall is veryâ€¦ I mean, the randomness in the height of somebody who is 6 feet tall will be very different from the randomness in the height of somebody who is

97
00:36:40.600 --> 00:36:50.859
Faculty (Olympus): Let's say four feet tall. Okay. The person may not it may not be an adult. It could still be a child. Okay. So so so so this notion of conditional probability is important.

98
00:36:50.860 --> 00:36:57.340
Faculty (Olympus): And based on that, we defined something called the chain rule, the law of total probability, and

99
00:36:57.340 --> 00:37:03.909
Faculty (Olympus): and build these rules, okay? So this is, again, something that we will use a little bit as we go forward.

100
00:37:05.090 --> 00:37:24.809
Faculty (Olympus): Events are independent if the informationâ€¦ the occurrence of one event has no bearing on the randomness of the other event. For example, then if you say, if you want to determine the probability of two events happening simultaneously, then the probability of both of them happening jointly is equal to the product of the individual probabilities.

101
00:37:25.190 --> 00:37:25.860
Faculty (Olympus): Okay.

102
00:37:26.680 --> 00:37:30.549
Faculty (Olympus): So this isâ€¦ Probably one of the simplest and easiest.

103
00:37:31.230 --> 00:37:45.719
Faculty (Olympus): things to understand. Okay, so you'reâ€¦ and this is something that you have done as, you know, this is sort of the introduction to probability for most of you who have encountered probability in a non-formalâ€¦ I mean, in a less formal setting.

104
00:37:45.870 --> 00:37:56.839
Faculty (Olympus): Okay, so you areâ€¦ you'reâ€¦ you're looking at, at counting, that means if you'reâ€¦ you're looking at aâ€¦ you can think about it asâ€¦ as a box withâ€¦ with balls of different numbers.

105
00:37:56.840 --> 00:38:02.840
Faculty (Olympus): Okay, and you're trying to pull out balls from this box. Okay, you pull out a ball.

106
00:38:02.840 --> 00:38:24.100
Faculty (Olympus): Orâ€¦ and either you put back the ball, or you don't put back the ball. That's one wayâ€¦ that's sort of two variations that you can have, with replacement or without replacement, with ordering or without ordering. You care for in what sequence you got a particular sequence of numbers, or you don't particularly care. For example, if there's a box with 10 numbers, I mean, 10â€¦ box with 10 balls numbered 1 through 10.

107
00:38:24.210 --> 00:38:43.199
Faculty (Olympus): Okay? In one case, you mightâ€¦ you'll pick up two balls without replacement, and don't care whether one and three came inâ€¦ don't care in what order you got one and three. All you want to know if youâ€¦ if youâ€¦ did you pull out a ball one and ball with number one and ball with number three? In the other case, you care. Did you get one

108
00:38:43.280 --> 00:38:48.260
Faculty (Olympus): You know, where these things come about depends on the experience and the experiment that you're conducting.

109
00:38:48.850 --> 00:38:49.540
Faculty (Olympus): Okay.

110
00:38:50.430 --> 00:39:03.869
Faculty (Olympus): So, from this, we went to random variables, and the key concept of cumulative distribution functions. You take the derivative of the cumulative distribution functions, you get

111
00:39:04.030 --> 00:39:05.980
Faculty (Olympus): Probability density function.

112
00:39:07.770 --> 00:39:08.440
Faculty (Olympus): Okay.

113
00:39:09.090 --> 00:39:20.089
Faculty (Olympus): Discrete random variables and the probability mass function of these has been studied. We also look at, yeah, so this is the probability density function. You can look at continuous random variables and define the probability density function.

114
00:39:22.030 --> 00:39:27.730
Faculty (Olympus): Now, these are the key properties that many of us are familiar with in a different context.

115
00:39:27.960 --> 00:39:33.130
Faculty (Olympus): We are looking at expectation in some sense, some notion of centrality.

116
00:39:38.690 --> 00:39:40.720
Faculty (Olympus): Centrality of.

117
00:39:41.530 --> 00:39:44.349
Faculty (Olympus): The of of of the distribution.

118
00:39:48.760 --> 00:39:51.180
Faculty (Olympus): This tree view, okay?

119
00:39:51.730 --> 00:39:53.100
Faculty (Olympus): Distribution.

120
00:39:53.540 --> 00:40:00.499
Faculty (Olympus): This variance describes The variation around expectation.

121
00:40:06.150 --> 00:40:07.550
Faculty (Olympus): Around the mean.

122
00:40:08.850 --> 00:40:21.810
Faculty (Olympus): So just to remind you, what is the variance? The formula for the definition of the variance is you take the realization of a random variable, you take the difference between what you got.

123
00:40:22.280 --> 00:40:24.680
Faculty (Olympus): And the average value.

124
00:40:25.240 --> 00:40:26.000
Faculty (Olympus): Okay?

125
00:40:26.120 --> 00:40:29.170
Faculty (Olympus): You take the square of that. That is the square of the error.

126
00:40:29.990 --> 00:40:33.159
Faculty (Olympus): This is a random quantity. Every time you get some number.

127
00:40:33.780 --> 00:40:50.320
Faculty (Olympus): I mean, every time you realize a random variable, you will have a random quantity. You take its difference of the quantity that you get from the mean value of that random variable, or the average value. So this is what we callâ€¦ you can think about it as an error, or the variation.

128
00:40:50.440 --> 00:41:00.579
Faculty (Olympus): Or the difference between the mean and this. You take the square of that. So you're only interested in the magnitude of the difference rather than the sign.

129
00:41:00.790 --> 00:41:09.120
Faculty (Olympus): And that's, of course, a random quantity, and now you take the expectation of that quantity. So you're looking for, in this case, what is the average

130
00:41:09.810 --> 00:41:11.390
Faculty (Olympus): Mean square error.

131
00:41:19.140 --> 00:41:19.920
Faculty (Olympus): Okay.

132
00:41:20.030 --> 00:41:23.190
Faculty (Olympus): So the smaller the mean square error.

133
00:41:23.320 --> 00:41:30.979
Faculty (Olympus): The more likely that the value of the random variable is closer to mu, closer to its mean, closer to its average.

134
00:41:31.090 --> 00:41:32.930
Faculty (Olympus): The larger this value.

135
00:41:33.100 --> 00:41:43.780
Faculty (Olympus): Which means that there are large number of possibilities, or there are large deviations from the mean are likely to happen.

136
00:41:44.430 --> 00:41:53.230
Faculty (Olympus): Okay? So, small variance means that most of the distribution, the most of the values that you're going to get are close to the mean. Large means they'll be distributed away from the mean.

137
00:41:53.630 --> 00:41:54.350
Faculty (Olympus): Okay.

138
00:41:56.220 --> 00:42:12.019
Faculty (Olympus): Now, if instead of looking at one, you look at multiple vectors together, okay, so multiple random variables together, you can call that as a random vector, and now you're looking at joint behavior of these different random variables. Joint cumulative distribution function.

139
00:42:12.020 --> 00:42:20.969
Faculty (Olympus): It could be events, sorry, it could be independent, each of these random variables could be independent, so we could define the notion of independence of random variables.

140
00:42:21.910 --> 00:42:35.459
Faculty (Olympus): So, these could be continuous, in which caseâ€¦ sorry, these could be discrete first, and in which case we define the joint and conditional property mass function, or they could be continuous, in which case we define property density functions.

141
00:42:36.840 --> 00:42:37.520
Faculty (Olympus): Okay.

142
00:42:37.700 --> 00:42:50.990
Faculty (Olympus): Now, this is also important. What is theâ€¦ how do theâ€¦ if there are two random variables that I'm looking at together, how do they vary, okay? For example, does a large height or a high value of the height correspond to a high value of the

143
00:42:50.990 --> 00:43:08.619
Faculty (Olympus): of the weight, okay? Or is itâ€¦ or do they go in opposite directions, okay? For example, if you have done academically well, if you haveâ€¦ if you're the topper of your class, is it more likely that you're going to make more money 15 years down the line, or is it negatively correlated? The lower you're in the class.

144
00:43:08.620 --> 00:43:26.129
Faculty (Olympus): the higher is the amount of money that you can make. That's another way of lookingâ€¦ another kind of a question that you're looking at. Another sort of obvious examples. Covariance means how do two random variables vary together, okay? Does giving informationâ€¦ does having information about one of them tell you anything about the other random variable?

145
00:43:28.000 --> 00:43:40.249
Faculty (Olympus): Yeah. So much of this material is covered in this book, and I really want you to have this book with you, and sort of go back and read from that book, because that's really the best source of this material.

146
00:43:41.260 --> 00:43:55.610
Faculty (Olympus): Okay? Any questions on this? Any questions on whatever we have covered so far? Any of the concepts, if they are not clear, I'll just quickly run you through, because I will need each of these concepts to be clearly understood when I develop the material soon.

147
00:43:55.870 --> 00:44:01.190
Faculty (Olympus): There was the material for estimation and and and and hypothesis testing and

148
00:44:01.350 --> 00:44:03.719
Faculty (Olympus): And regression. Any questions on any of this?

149
00:44:05.930 --> 00:44:07.180
Faculty (Olympus): Okay, Rahul.

150
00:44:09.220 --> 00:44:23.049
Rahul Shrikrishna Joshi .: Morning, Professor. My question is, in all these models, I think there is a general perception or general expectation that there will be some mean, and how much you vary from the mean. The lower the variance, better, something like that.

151
00:44:23.050 --> 00:44:25.570
Faculty (Olympus): No, no, no, don't even bring the world better.

152
00:44:25.710 --> 00:44:27.460
Faculty (Olympus): Okay, just a description.

153
00:44:27.460 --> 00:44:28.500
Rahul Shrikrishna Joshi .: It's a description, yeah, okay.

154
00:44:28.500 --> 00:44:28.940
Faculty (Olympus): the.

155
00:44:28.940 --> 00:44:29.380
Rahul Shrikrishna Joshi .: machinist.

156
00:44:29.380 --> 00:44:37.190
Faculty (Olympus): So don't call, yeah, it's important not to be judgmental about what is better, what is not better, and so on. Don't get into that kind of a thinking.

157
00:44:37.640 --> 00:44:39.360
Faculty (Olympus): Okay, it's there, that's it.

158
00:44:39.840 --> 00:44:49.389
Rahul Shrikrishna Joshi .: Okay, so my question is, is it the only way to explain the data? Why there cannot be a variable which is absolutely random, like, where you cannot have any trends?

159
00:44:49.390 --> 00:44:51.660
Faculty (Olympus): What does it mean to say absolutely random?

160
00:44:52.090 --> 00:44:52.620
Rahul Shrikrishna Joshi .: You can.

161
00:44:52.620 --> 00:44:58.039
Faculty (Olympus): If you know nothing about it, hang on, hang on. If you don't know nothing about it, you can't say anything about it.

162
00:44:59.720 --> 00:45:00.940
Rahul Shrikrishna Joshi .: That is also true on VAR.

163
00:45:00.940 --> 00:45:13.249
Faculty (Olympus): So you have to know something. If you are calling some data as random, you have to have a way of describing the randomness. Only then can you do something with it.

164
00:45:14.730 --> 00:45:21.019
Faculty (Olympus): If there is nothing that you can say, there is nothing that you can say. You don't deal with it, right?

165
00:45:21.200 --> 00:45:22.490
Faculty (Olympus): You can't handle it.

166
00:45:24.970 --> 00:45:25.620
Rahul Shrikrishna Joshi .: Yeah.

167
00:45:25.620 --> 00:45:32.079
Faculty (Olympus): Describing the nature of the randomness gives you an ability to

168
00:45:32.260 --> 00:45:36.840
Faculty (Olympus): Understand and get a hold of what is what is happening.

169
00:45:37.730 --> 00:45:42.730
Faculty (Olympus): Okay, if you are unable to describe, then there is no, I mean, there is nothing to do, you know, let it go.

170
00:45:43.110 --> 00:45:47.009
Faculty (Olympus): Right? Yeah, that's a beautiful thing, David. Good question. Gaurav.

171
00:45:50.890 --> 00:45:57.900
Gaurav Singh .: Professor, in the, in the last, part, previous part of this, the same course.

172
00:45:58.010 --> 00:46:11.069
Gaurav Singh .: Basically, the main problem I felt I was having was counting is a little difficult to do. For example, you were talking about.

173
00:46:11.070 --> 00:46:20.009
Faculty (Olympus): Yeah, okay, so, okay, if you'reâ€¦ yeah, so I will not be revisiting any of those, if that's your question. Those things, you take it up in the TA sessions.

174
00:46:20.470 --> 00:46:21.140
Gaurav Singh .: Okay.

175
00:46:21.140 --> 00:46:32.210
Faculty (Olympus): Okay? Yeah. If you have difficulty about specific topics, the best place to get them resolvedâ€¦ I mean, topics that have already been covered. Yeah. The best place to get them resolved is in the TA sessions.

176
00:46:32.660 --> 00:46:33.260
Gaurav Singh .: Correct.

177
00:46:33.260 --> 00:46:33.859
Faculty (Olympus): Okay, so maybe.

178
00:46:33.860 --> 00:46:41.080
Gaurav Singh .: I wanted suggestion from you like the practice is the only way or

179
00:46:41.080 --> 00:46:44.959
Faculty (Olympus): Of course, there is no shortcut. Please don't ask me for shortcuts. I don't know any.

180
00:46:44.960 --> 00:46:45.280
Gaurav Singh .: Hmm.

181
00:46:45.280 --> 00:46:49.239
Faculty (Olympus): I work hard, so I want you to work hard. Naina, sorry.

182
00:46:49.710 --> 00:46:50.730
Gaurav Singh .: Sure. Yeah.

183
00:46:50.730 --> 00:46:51.060
Naina Punjwani .: Apurv.

184
00:46:51.060 --> 00:46:51.710
Faculty (Olympus): Later.

185
00:46:51.710 --> 00:47:05.710
Naina Punjwani .: Yeah, Professor. So I want to understand the difference between. So like we learned binomial, we learned multinomial when there are multiple variables. So multinomial is multiple variables. So.

186
00:47:05.710 --> 00:47:13.100
Naina Punjwani .: what would be the difference between the vector and the variable? How, how would you differentiate,

187
00:47:13.100 --> 00:47:20.110
Faculty (Olympus): Vector is multiple variables. You go back to your vector calculus, or vector, whatever vectors you have studied.

188
00:47:20.310 --> 00:47:26.310
Faculty (Olympus): Okay, vector means you collect multiple variables together. You look at them together rather than individually.

189
00:47:26.310 --> 00:47:28.270
Naina Punjwani .: So it can be more than 2 as well.

190
00:47:28.270 --> 00:47:29.939
Faculty (Olympus): Of course, of course, of course, in fact.

191
00:47:29.940 --> 00:47:31.269
Naina Punjwani .: Because the formulas.

192
00:47:31.270 --> 00:47:34.299
Faculty (Olympus): You will be dealing with thousands of them in learning.

193
00:47:35.840 --> 00:47:36.180
Naina Punjwani .: Okay.

194
00:47:36.180 --> 00:47:41.329
Faculty (Olympus): Typically, you'll be, I mean, any learning algorithm will, you know, for example, when you talk about features.

195
00:47:41.610 --> 00:47:47.880
Faculty (Olympus): Okay, what is a feature? It's just a variable. If you are looking at a set of features, it's a vector of features.

196
00:47:49.450 --> 00:47:54.470
Naina Punjwani .: Okay, so because when we learned we learned only two variables.

197
00:47:54.470 --> 00:47:58.799
Faculty (Olympus): Yeah, I mean, if I show you 1000 on the first day.

198
00:47:58.800 --> 00:47:59.170
Naina Punjwani .: Neat.

199
00:47:59.170 --> 00:48:03.079
Faculty (Olympus): You're going to run away, right? So.

200
00:48:03.560 --> 00:48:03.930
Naina Punjwani .: can.

201
00:48:03.930 --> 00:48:13.860
Faculty (Olympus): Okay? Yeah, no, I mean, that's a valid point. The point I'm making is, in a course, we teach you something that's easy to comprehend in this lecture.

202
00:48:14.160 --> 00:48:22.910
Faculty (Olympus): Okay, the complexities have to be absorbed and sort ofâ€¦ you have to learn how to handle the, sort of, the generalization, the extension, etc, etc.

203
00:48:23.360 --> 00:48:30.159
Faculty (Olympus): Okay, we'll tell you that this is the idea, and now you have to take it forward. That's typically how most teaching is done.

204
00:48:30.740 --> 00:48:33.000
Faculty (Olympus): All right. Any other questions.

205
00:48:33.460 --> 00:48:36.320
Faculty (Olympus): Okay, very good. So, let's move on.

206
00:48:36.810 --> 00:48:47.719
Faculty (Olympus): Okay, just again, I think I'll, you know, I was debating whether I should have this or not. Yeah, just toâ€¦ I just recap again, so probability theory is an abstract standalone theory.

207
00:48:47.870 --> 00:48:53.130
Faculty (Olympus): Okay, it is developed using the three axioms that we have studied when we began the course.

208
00:48:53.600 --> 00:49:03.200
Faculty (Olympus): Okay, it's just abstract on its own, and it provides some kind of a consistent framework. I mean, all of those theories are required because you have to be consistent.

209
00:49:03.200 --> 00:49:14.780
Faculty (Olympus): You have to be able to draw some amount of understanding from it and not have alternate, I mean, you know, you should not, the theory should allow you to be consistent.

210
00:49:15.000 --> 00:49:20.639
Faculty (Olympus): Okay, and that consistency is about the beliefs about events of interest for you.

211
00:49:20.950 --> 00:49:28.200
Faculty (Olympus): Okay, there are different events of interest, and, you know, what is your belief about something that will happen? I'll give you a quick example soon.

212
00:49:28.780 --> 00:49:33.269
Faculty (Olympus): And much of thisâ€¦ this theory is developed from real life.

213
00:49:33.660 --> 00:49:35.090
Faculty (Olympus): But it is standalone.

214
00:49:35.480 --> 00:49:36.420
Faculty (Olympus): Okay.

215
00:49:36.650 --> 00:49:41.040
Faculty (Olympus): It is this, it is, it is inspired, the theory is inspired by real life.

216
00:49:41.300 --> 00:49:47.149
Faculty (Olympus): But the theory itself stands on its own. It doesn't require real life.

217
00:49:47.260 --> 00:49:48.110
Faculty (Olympus): Okay.

218
00:49:48.400 --> 00:49:59.160
Faculty (Olympus): Andâ€¦ but, of course, because it's inspired from real life, and because there is an objective of using that theory to develop some concepts and understanding of real life, we will connect them back.

219
00:49:59.390 --> 00:50:06.170
Faculty (Olympus): First, develop the theory of probability, and then use it to understand and describe phenomena using statistics.

220
00:50:06.510 --> 00:50:15.799
Faculty (Olympus): Okay, so one way of understanding this theory, or sorry, this connection between the theory and real life, is this notion of law of large numbers.

221
00:50:16.240 --> 00:50:19.020
Faculty (Olympus): Okay, that's something that I'm going to describe to you soon.

222
00:50:20.200 --> 00:50:31.820
Faculty (Olympus): Okay, and there is the notion of a frequentist, frequentist view, so let's just, for the time being, park this thought. I'll come back to this again when I give you the law of large numbers.

223
00:50:32.320 --> 00:50:33.630
Faculty (Olympus): Okay.

224
00:50:33.930 --> 00:50:41.699
Faculty (Olympus): Now, let me just describe to you how the lawâ€¦ what exactly is the law of large. There's a formal proof for this, and there are different

225
00:50:41.910 --> 00:50:55.580
Faculty (Olympus): You know, different proofs and different versions and different, what shall I say? I mean, there are, yeah, there are different ways of describing what I'm going to give you here. I'm not going to give you any proof. I'm going to give you the final result.

226
00:50:55.790 --> 00:50:56.620
Faculty (Olympus): Okay?

227
00:50:56.880 --> 00:51:03.640
Faculty (Olympus): So the way to think about it is, okay, so this should be Xi. Yeah, so let's assume that Xi.

228
00:51:03.750 --> 00:51:04.990
Faculty (Olympus): X1.

229
00:51:05.260 --> 00:51:16.080
Faculty (Olympus): Okay, is a random variable whose mean, okay, mean, expectation, average, all of that is some mu, and which has a variance of sigma square.

230
00:51:17.400 --> 00:51:23.630
Faculty (Olympus): Okay. Then you take this random variable and make copies of this, statistical copies of this.

231
00:51:23.760 --> 00:51:35.099
Faculty (Olympus): Okay? So, the way toâ€¦ the best way to think about it is picking people from the street. You want to measure the height of a person. I'm going to keep that example all the time. You want to measure the height of a population.

232
00:51:35.440 --> 00:51:37.900
Faculty (Olympus): Okay, so height is your random variable.

233
00:51:38.390 --> 00:51:41.919
Faculty (Olympus): And you're picking random people from the street.

234
00:51:42.050 --> 00:51:58.930
Faculty (Olympus): Okay? So each of them, before you know what the statisticâ€¦ what their height is, there is a statistâ€¦ there's a randomness to that height that theyâ€¦ before you've seen the person, you picked up the person, whatever, okay? So there's a randomness to that. That randomness is what we call

235
00:51:58.930 --> 00:52:11.090
Faculty (Olympus): the PDF, or the randomness is described using the probability density function of the height, which in turn will give us the mean, which in turn will also give us the variance of the height in that population.

236
00:52:11.640 --> 00:52:25.609
Faculty (Olympus): Okay? So different people will have different values of that, or you can think about it as you're getting differentâ€¦ I want to give you this term here. You're going to getâ€¦ so when I say Xi.

237
00:52:26.560 --> 00:52:29.530
Faculty (Olympus): What I mean here is statistical copies.

238
00:52:33.410 --> 00:52:43.330
Faculty (Olympus): Okay? These are not copies, these are statistical copies. That means the randomness in all of them areâ€¦ have the same characteristic. That's what it means.

239
00:52:43.670 --> 00:52:45.819
Faculty (Olympus): Okay, now you takeâ€¦

240
00:52:46.130 --> 00:52:54.330
Faculty (Olympus): take them, and sum up the heights, or sum up the values of Xi. So this SN is what we call the sample sum.

241
00:52:54.800 --> 00:52:57.520
Faculty (Olympus): Okay? So this is the sample sum.

242
00:52:57.730 --> 00:53:05.340
Faculty (Olympus): And MN, you take the sample sum and divide it by the total number of samples here, so this is what we'll call the sample mean.

243
00:53:06.360 --> 00:53:10.909
Faculty (Olympus): Okay, so SN is the sample sum, MN is the sample mean.

244
00:53:13.170 --> 00:53:19.500
Faculty (Olympus): Now, it is important to distinguish this importantâ€¦ this is an important fact to understand.

245
00:53:19.810 --> 00:53:22.399
Faculty (Olympus): If two people are conducting this experiment.

246
00:53:22.690 --> 00:53:26.959
Faculty (Olympus): The values of SN and MN they will see will be very different.

247
00:53:27.830 --> 00:53:38.440
Faculty (Olympus): Okay, it will be different. Let's not even worry about very. Okay, they'll be different. Which means, the way to, again, think about it is that these two quantities are random variables.

248
00:53:46.300 --> 00:53:47.700
Faculty (Olympus): Random variables.

249
00:53:51.820 --> 00:53:52.740
Faculty (Olympus): Okay.

250
00:53:53.160 --> 00:53:53.940
Faculty (Olympus): Yeah.

251
00:53:54.510 --> 00:54:01.710
Faculty (Olympus): And, yeah, different realizations of N samples will result in different MN. That's the first thing to understand.

252
00:54:04.010 --> 00:54:09.989
Faculty (Olympus): And the natural question is to ask, what happens to MN as N becomes large?

253
00:54:11.270 --> 00:54:14.620
Faculty (Olympus): What happens to the sample mean as n becomes large?

254
00:54:14.730 --> 00:54:19.750
Faculty (Olympus): So can anybody give me an intuitive answer to that question without going into the next slide?

255
00:54:20.460 --> 00:54:23.549
Siddharth Digambar Kulkarni .: It becomes equal to mu, which tends to mu.

256
00:54:23.550 --> 00:54:24.520
Ashish Kumar .: the.

257
00:54:24.520 --> 00:54:31.280
Faculty (Olympus): Okay, please raise your hand and I'll call up. Please don't speak up without that. Please mute yourself. Okay, Gaurav.

258
00:54:31.880 --> 00:54:34.839
Gaurav Singh .: Yeah, it will, tend towards Mu.

259
00:54:34.840 --> 00:54:39.209
Faculty (Olympus): Okay, so what you're saying is MN tend towards mu.

260
00:54:40.270 --> 00:54:43.130
Faculty (Olympus): Okay, Vamsi, you want to say something else to this?

261
00:54:43.130 --> 00:54:45.399
Vamsi Krishna Mutnuri .: Yeah, same thing, sir, same thing.

262
00:54:45.400 --> 00:54:48.920
Faculty (Olympus): Okay, okay. Anybody wants to give me something more than this?

263
00:54:50.360 --> 00:54:53.690
Faculty (Olympus): Okay, okay, now what does tend to mean?

264
00:54:54.550 --> 00:54:57.160
Faculty (Olympus): Remember, this is a random quantity.

265
00:54:58.110 --> 00:55:00.089
Samar Jain .: It will tend to the mean of popular.

266
00:55:00.090 --> 00:55:05.249
Faculty (Olympus): What does Bendende do mean? See, in your standard.

267
00:55:05.410 --> 00:55:06.590
Faculty (Olympus): Calculus.

268
00:55:07.410 --> 00:55:13.440
Faculty (Olympus): If I'm saying something is tending to something, what it means is that if you are looking at a sequence.

269
00:55:13.570 --> 00:55:19.350
Faculty (Olympus): Okay, say for example, if this was not a random quantity, MN is a sequence of numbers.

270
00:55:19.700 --> 00:55:24.969
Faculty (Olympus): Okay? MN is a sequence of numbers. Mu is theâ€¦ you're claiming that MN tends to mu.

271
00:55:25.120 --> 00:55:27.629
Faculty (Olympus): Assume now that MN is not random.

272
00:55:28.110 --> 00:55:36.400
Faculty (Olympus): Okay, MN is random, so that complicates the problem. Assume that MN is not random. What it means in calculus is that as N becomes large.

273
00:55:38.110 --> 00:55:45.330
Faculty (Olympus): There will be a point in that sequence where all the MNs will be within some epsilon of mu.

274
00:55:46.160 --> 00:55:54.340
Faculty (Olympus): And that point depends on the epsilon that you choose. If you want to make it very, very close, you'll have to find a larger N.

275
00:55:54.890 --> 00:56:05.779
Faculty (Olympus): Okay? So you will always find an N beyond which all the M's are veryâ€¦ are within a specified boundary of mu.

276
00:56:06.560 --> 00:56:09.210
Faculty (Olympus): That's what it means in the deterministic world.

277
00:56:09.700 --> 00:56:12.560
Faculty (Olympus): Okay, what does it mean in the probabilistic world?

278
00:56:13.590 --> 00:56:27.460
Faculty (Olympus): Okay? Now, it means it has multiâ€¦ it has several potential interpretations. And I'm going to give you only one interpretation, okay? Which isâ€¦ which gives you the intuition to this. Yeah, so many of you said this, it becomes closer toâ€¦

279
00:56:29.370 --> 00:56:37.779
Faculty (Olympus): It becomes closer toâ€¦ closer to mu, but the question is, what does it mean to say it is closer to mu? That has to beâ€¦ has to be taken up.

280
00:56:38.650 --> 00:56:39.530
Faculty (Olympus): Okay.

281
00:56:40.220 --> 00:56:40.960
Faculty (Olympus): Peek.

282
00:56:44.090 --> 00:56:54.680
Faculty (Olympus): Okay, what this intuitively means is that the variance of MNâ€¦ see, remember I introduced the term variance. What is the variance? Variance is the expectation of

283
00:56:54.890 --> 00:56:58.560
Faculty (Olympus): The difference between the random values and the mean.

284
00:56:58.720 --> 00:57:08.440
Faculty (Olympus): Okay, you take the square of that, and you take the expectation of that particular quantity. Remember that the variance here is expectation of X minus mu.

285
00:57:08.870 --> 00:57:10.010
Faculty (Olympus): Whole square.

286
00:57:12.270 --> 00:57:20.199
Faculty (Olympus): This is the so-called difference from the mean, or if you want to think about it as some kind of an error with respect to the mean.

287
00:57:21.440 --> 00:57:29.800
Faculty (Olympus): Okay, so this quantity starts becoming smaller and smaller as N becomes large, okay? I can actually prove it to you.

288
00:57:30.030 --> 00:57:32.769
Faculty (Olympus): Okay, how do I prove this?

289
00:57:33.600 --> 00:57:34.949
Faculty (Olympus): What is SN?

290
00:57:36.190 --> 00:57:38.570
Faculty (Olympus): Ascend this Sigma Xi.

291
00:57:39.630 --> 00:57:40.600
Faculty (Olympus): Okay.

292
00:57:41.030 --> 00:57:44.970
Faculty (Olympus): What isâ€¦ Variants of SN.

293
00:57:50.600 --> 00:57:52.410
Faculty (Olympus): XI are independent.

294
00:57:52.840 --> 00:57:57.040
Faculty (Olympus): Okay, I'm taking the sum of n random variables.

295
00:57:57.790 --> 00:58:05.480
Faculty (Olympus): So, the variance of the sum of n independent random variables is equal to Sigma.

296
00:58:09.490 --> 00:58:10.520
Faculty (Olympus): I squared.

297
00:58:11.080 --> 00:58:17.929
Faculty (Olympus): We know that sigma i is sigma for all the i, so this essentially is n sigma squared.

298
00:58:19.310 --> 00:58:21.120
Faculty (Olympus): This is something that you're familiar with.

299
00:58:22.370 --> 00:58:25.350
Faculty (Olympus): Okay? Now, what is MN?

300
00:58:27.380 --> 00:58:28.980
Faculty (Olympus): It's SN by N.

301
00:58:30.460 --> 00:58:33.920
Faculty (Olympus): Okay, what is variance of MN?

302
00:58:38.390 --> 00:58:40.500
Faculty (Olympus): Variance of MN is.

303
00:58:41.130 --> 00:58:46.040
Faculty (Olympus): Variance of SN, variance ofâ€¦ let me first write down the formula.

304
00:58:46.350 --> 00:58:50.059
Faculty (Olympus): Variance of this quantity, because it's a definition, MN is equal to SN by N.

305
00:58:50.560 --> 00:58:55.880
Faculty (Olympus): Which in turn is equal to 1 over N square variance of SN.

306
00:58:57.750 --> 00:59:13.590
Faculty (Olympus): Something you know, right? So if you are scaling a random variable, the variance of that scales as A square. Scaling a random variable by A, that means you're expanding it by A. The variance of that scales as A square.

307
00:59:13.870 --> 00:59:19.800
Faculty (Olympus): So if you are scaling a random variable SN by N, It scales as 1 over N squared.

308
00:59:20.790 --> 00:59:30.349
Faculty (Olympus): Okay? So this means thatâ€¦ The variance of MN, so this quantity, is basically sigma squared by N.

309
00:59:32.420 --> 00:59:36.739
Faculty (Olympus): Okay, what happens as n becomes large? Because sigma squared is a constant.

310
00:59:36.940 --> 00:59:41.649
Faculty (Olympus): This quantity starts going down, and then in the limit, it is equal to zero.

311
00:59:41.820 --> 00:59:46.199
Faculty (Olympus): When it is equal to zero in the limit, this means that this value is a constant.

312
00:59:46.340 --> 00:59:49.919
Faculty (Olympus): It'll take on the value ofâ€¦ of its meal.

313
00:59:50.440 --> 00:59:52.419
Faculty (Olympus): Okay, that's one way to think about it.

314
00:59:52.760 --> 00:59:56.509
Faculty (Olympus): Okay, any questions on this argument, on this derivation?

315
00:59:59.970 --> 01:00:00.870
Faculty (Olympus): Very good.

316
01:00:01.870 --> 01:00:02.939
Rahul Shrikrishna Joshi .: Sorry, sir, just one question.

317
01:00:02.940 --> 01:00:03.260
Faculty (Olympus): should.

318
01:00:03.260 --> 01:00:11.849
Rahul Shrikrishna Joshi .: Yeah. Can you, can you, can you go back to the previous, where you had written that? Yeah, yeah. So here, how the N sigma square has been derived?

319
01:00:12.280 --> 01:00:15.289
Faculty (Olympus): Which step was what? This, this, this step?

320
01:00:15.530 --> 01:00:16.130
Rahul Shrikrishna Joshi .: Yeah, yeah, that'd be.

321
01:00:16.130 --> 01:00:17.320
Faculty (Olympus): You agree with this?

322
01:00:18.330 --> 01:00:19.060
Faculty (Olympus): Sigma.

323
01:00:19.060 --> 01:00:22.309
Rahul Shrikrishna Joshi .: So that isâ€¦ that is individual difference square sum, right?

324
01:00:22.310 --> 01:00:31.350
Faculty (Olympus): Variance of a random variable which is derived from the sum of independent random variables is equal to the sum of the variances.

325
01:00:31.350 --> 01:00:31.880
Rahul Shrikrishna Joshi .: Yep.

326
01:00:32.170 --> 01:00:35.289
Faculty (Olympus): Variance of sum is equal to sum of variances if.

327
01:00:35.570 --> 01:00:46.419
Faculty (Olympus): If they are independent. Not if they are not independent, only if they are independent. So if you agree, going from here to here, then this, because all the I's areâ€¦ all the Sigma I is the same.

328
01:00:47.450 --> 01:00:49.269
Faculty (Olympus): It's a statistical copy.

329
01:00:50.540 --> 01:00:53.189
Faculty (Olympus): Remember, I said statistical copy somewhere here.

330
01:00:53.950 --> 01:00:54.820
Faculty (Olympus): This one.

331
01:00:56.530 --> 01:00:58.459
Rahul Shrikrishna Joshi .: But why is the Sigma I will be same?

332
01:00:59.000 --> 01:01:00.680
Faculty (Olympus): Because that's the assumption.

333
01:01:02.230 --> 01:01:07.220
Faculty (Olympus): I assume they're all statistical copies, meaning Xi have all the same distribution.

334
01:01:08.590 --> 01:01:09.799
Faculty (Olympus): That's an assumption.

335
01:01:11.870 --> 01:01:13.280
Faculty (Olympus): Did I not say that here?

336
01:01:15.230 --> 01:01:17.789
Faculty (Olympus): Of it, yeah, of this random variable.

337
01:01:20.640 --> 01:01:25.220
Faculty (Olympus): Okay, okay, I'll explicitly say this, so what we say is xi.

338
01:01:25.340 --> 01:01:28.580
Faculty (Olympus): Râ€¦ Identically.

339
01:01:31.120 --> 01:01:32.630
Faculty (Olympus): Independent.

340
01:01:34.300 --> 01:01:42.499
Faculty (Olympus): Identical. Okay. We call them IIDs. So let me figure out how to say it here.

341
01:01:43.320 --> 01:01:50.910
Faculty (Olympus): Okay, so the wayâ€¦ the language I used here was that Xi are copies, statistical copies of this random variable.

342
01:01:53.990 --> 01:02:03.310
Faculty (Olympus): Okay? When I say statistical copies, that's what I mean. I mean that they all have the same distribution. If they have the same distribution, they have the same mean, and the same variance.

343
01:02:06.010 --> 01:02:06.750
Rahul Shrikrishna Joshi .: Okay, yep.

344
01:02:08.640 --> 01:02:13.579
Rahul Shrikrishna Joshi .: So here, sir, just one more question. So here, the analogy is, like, whenever you give the example of height.

345
01:02:13.770 --> 01:02:14.140
Faculty (Olympus): Jitra.

346
01:02:14.140 --> 01:02:18.230
Rahul Shrikrishna Joshi .: We are measuring randomly individual person site selected randomly or.

347
01:02:18.230 --> 01:02:22.369
Faculty (Olympus): No, the way to think about it, yeah, the way to think about it is take the same population.

348
01:02:22.860 --> 01:02:24.709
Faculty (Olympus): Okay, there are two of you doing it.

349
01:02:25.660 --> 01:02:32.470
Faculty (Olympus): Okay, sorry, but let's take one of you doing it, if I'm doing it first, okay? If you're doing it, then you pick somebody.

350
01:02:33.100 --> 01:02:45.600
Faculty (Olympus): The distribution of that, before you actually do the measurement, the randomness of the height of that person, and the randomness of the height of the second person that you pick, assuming you pick them randomly from the population, is the same.

351
01:02:49.040 --> 01:02:49.800
Rahul Shrikrishna Joshi .: Andâ€¦

352
01:02:50.270 --> 01:02:52.340
Faculty (Olympus): I mean, that's the that's the assumption.

353
01:02:52.340 --> 01:02:52.680
Rahul Shrikrishna Joshi .: Alright.

354
01:02:52.680 --> 01:02:59.740
Faculty (Olympus): If I don't pick it randomly, if I pick a brother, there will be similar height. You're not supposed to pick the brother.

355
01:03:00.850 --> 01:03:03.119
Faculty (Olympus): You have to pick some random person from the street.

356
01:03:04.510 --> 01:03:08.220
Faculty (Olympus): Okay, that's, that's, so we assume that the randomness.

357
01:03:08.380 --> 01:03:12.119
Faculty (Olympus): isâ€¦ is the same. The randomness is the same, not the value.

358
01:03:12.510 --> 01:03:14.520
Faculty (Olympus): Yep. The randomness is the same.

359
01:03:16.380 --> 01:03:17.320
Rahul Shrikrishna Joshi .: Okay, yep.

360
01:03:17.320 --> 01:03:18.480
Faculty (Olympus): Yeah, that's it.

361
01:03:20.930 --> 01:03:23.639
Faculty (Olympus): Okay, I'll take this after the lecture if.

362
01:03:23.640 --> 01:03:24.000
Rahul Shrikrishna Joshi .: Right.

363
01:03:24.000 --> 01:03:25.340
Faculty (Olympus): Okay, yeah.

364
01:03:25.340 --> 01:03:25.859
Rahul Shrikrishna Joshi .: Yeah, that's fine.

365
01:03:25.860 --> 01:03:26.600
Faculty (Olympus): Yeah, yeah.

366
01:03:27.170 --> 01:03:28.410
Faculty (Olympus): Okay, yeah.

367
01:03:28.510 --> 01:03:47.789
Faculty (Olympus): So this implies, yeah, so essentially what I just said was that as n becomes large, the variance of Mn getsâ€¦ becomes closer andâ€¦ I mean, is equal to sigma squared by n, which means that this quantity goes to 0, which means that the variation of Mn around its mean, that goes to Mu.

368
01:03:48.630 --> 01:03:58.049
Faculty (Olympus): Because it is not, you know, the values that MN can take around mu become smaller and smaller. I mean, the difference

369
01:03:58.200 --> 01:04:07.220
Faculty (Olympus): between the values that MN takes and mu will become smaller and smaller. Variance equal to zero means it's constant, okay? So that's what that is.

370
01:04:08.020 --> 01:04:18.669
Faculty (Olympus): Okay? Which essentially means it's more likely to be close to mu, okay? And it's exactly mu only in the limit. I mean, that's a mathematical concept. If you don't understand it, don't worry about it.

371
01:04:18.670 --> 01:04:28.310
Faculty (Olympus): The way to think about it is as N becomes large, MN is more likely to be close to mu. That's the way to think about it. Again, you can make that more precise later.

372
01:04:30.030 --> 01:04:37.800
Faculty (Olympus): Okay? So this is what is called the law of large numbers. Essentially, what we say is that MN byâ€¦ sorry, MN

373
01:04:38.770 --> 01:04:43.759
Faculty (Olympus): goes to Mu is essentially the Law of large numbers.

374
01:04:44.190 --> 01:04:48.419
Faculty (Olympus): LLN, LLN, not LLM, ok, it's N.

375
01:04:50.950 --> 01:04:52.470
Faculty (Olympus): Yeah, any questions on that?

376
01:04:54.940 --> 01:05:01.460
Gaurav Singh .: Professor, why MN will not become near to zero?

377
01:05:02.150 --> 01:05:05.490
Faculty (Olympus): What are you doing? What are you doing with MN? What is MN?

378
01:05:05.770 --> 01:05:08.849
Gaurav Singh .: MN is SN divided by N. So for largeâ€¦

379
01:05:08.850 --> 01:05:10.439
Faculty (Olympus): Huh, why should it be zero?

380
01:05:10.630 --> 01:05:11.349
Gaurav Singh .: Because for lastâ€¦

381
01:05:11.350 --> 01:05:14.520
Faculty (Olympus): Take the height example. Why would the height become zero?

382
01:05:16.330 --> 01:05:17.940
Gaurav Singh .: Okay.

383
01:05:18.780 --> 01:05:23.730
Faculty (Olympus): What the averageâ€¦ so what is essentiallyâ€¦ what is MN in that example? It is the average height.

384
01:05:24.690 --> 01:05:27.009
Faculty (Olympus): Right, the average height will not become zero.

385
01:05:27.940 --> 01:05:33.999
Gaurav Singh .: But here also N tending towards large number. So SN divided by N.

386
01:05:34.000 --> 01:05:36.859
Faculty (Olympus): No, Asend. Asend is the sum.

387
01:05:37.690 --> 01:05:41.649
Gaurav Singh .: Oh, as the N will increase, SN will also increase. I got it.

388
01:05:41.650 --> 01:05:43.140
Faculty (Olympus): Of course.

389
01:05:43.260 --> 01:05:44.540
Faculty (Olympus): Of course, okay?

390
01:05:45.240 --> 01:05:48.179
Faculty (Olympus): Yeah, as n becomes large, as n goes to infinity.

391
01:05:48.650 --> 01:05:50.830
Faculty (Olympus): SN by N becomes.

392
01:05:51.070 --> 01:05:52.490
Gaurav Singh .: Got got yeah yeah.

393
01:05:52.490 --> 01:05:54.679
Faculty (Olympus): Okay, I'll take two more questions Vamsi.

394
01:05:55.470 --> 01:06:03.080
Vamsi Krishna Mutnuri .: Yes, sir. Sir, LLN is law of large numbers. You said, like, for example, in medical reports and all, we have normal distribution based on bell curves.

395
01:06:03.080 --> 01:06:06.679
Faculty (Olympus): I'm not going to do that.

396
01:06:06.780 --> 01:06:08.020
Faculty (Olympus): Normal Agyare.

397
01:06:08.960 --> 01:06:15.529
Faculty (Olympus): Okay? Kaur is the next question. We'll come to that. Just hold on to that question. If you're discussing Norman, we'll come to that in the next question.

398
01:06:15.900 --> 01:06:18.359
Faculty (Olympus): Okay? I'll come to that. Abhishek?

399
01:06:19.080 --> 01:06:29.160
Abhishek Raghuvanshi .: Yeah, Professor, is it fair to understand it this way that as n becomes very large, the sample sort of becomes the population itself and it tends toâ€¦

400
01:06:29.160 --> 01:06:38.129
Faculty (Olympus): Yeah, that's one way to think about it. But you don't have to make it very large to get it very close to mu is also a fact, which I'm going to describe in a bit.

401
01:06:38.710 --> 01:06:42.460
Faculty (Olympus): Okay. Yeah. So Rahul, I'll take, I'll park your question and we'll take it.

402
01:06:42.460 --> 01:06:44.339
Rahul Shrikrishna Joshi .: No, no, sir, my different questions, sorry, sir, sorry.

403
01:06:44.340 --> 01:06:46.519
Faculty (Olympus): No, yeah, I think let's move on, otherwise we'll get stuck.

404
01:06:46.520 --> 01:06:48.190
Rahul Shrikrishna Joshi .: Okay, okay, that's fine.

405
01:06:48.190 --> 01:06:49.110
Faculty (Olympus): Yeah, yeah.

406
01:06:49.220 --> 01:06:55.849
Faculty (Olympus): So, you know, I won't take all the questions whenever I stop. I'll take only a small number, otherwise we'll get stuck in this.

407
01:06:56.020 --> 01:06:57.150
Faculty (Olympus): Okay, yeah.

408
01:06:58.240 --> 01:07:03.000
Faculty (Olympus): Yeah, so the next way of thinking about it is a little different now.

409
01:07:03.320 --> 01:07:05.379
Faculty (Olympus): Okay, so we take this SN.

410
01:07:06.280 --> 01:07:15.160
Faculty (Olympus): Okay, now if I subtract n mu from it, mind you that Expectation of SN.

411
01:07:15.390 --> 01:07:20.669
Faculty (Olympus): is equal to N mu. Okay, so, okay, just so that you get the idea here.

412
01:07:23.990 --> 01:07:25.410
Faculty (Olympus): Say.

413
01:07:29.650 --> 01:07:31.929
Faculty (Olympus): Okay, which is equal to N mu.

414
01:07:32.520 --> 01:07:37.979
Faculty (Olympus): Because, you know, just toâ€¦ just to go back, all the XIs have the same distribution.

415
01:07:38.250 --> 01:07:46.739
Faculty (Olympus): Okay? So, the expected value of the sum is N mu. Now, if I do SN minus N mu.

416
01:07:46.910 --> 01:07:53.810
Faculty (Olympus): And if I take the expectation of that, this will be expectation of SN minus expectation of N mu.

417
01:07:54.450 --> 01:07:58.490
Faculty (Olympus): which means, and the expectation of this is enemy, as I said earlier. So this would be 0.

418
01:07:58.630 --> 01:08:06.350
Faculty (Olympus): Okay, so if I take SN and subtract the mean from it, that gives me a zero mean quantity.

419
01:08:07.530 --> 01:08:08.460
Faculty (Olympus): Okay.

420
01:08:08.630 --> 01:08:13.350
Faculty (Olympus): And, if I takeâ€¦ And this is something that I derived earlier.

421
01:08:14.350 --> 01:08:17.589
Faculty (Olympus): The variance of SN is N sigma squared, okay?

422
01:08:17.890 --> 01:08:22.570
Faculty (Olympus): Nowâ€¦ Let usâ€¦ let us do the following.

423
01:08:24.160 --> 01:08:32.410
Faculty (Olympus): So, what isâ€¦ The variance ofâ€¦ Asem

424
01:08:33.290 --> 01:08:38.179
Faculty (Olympus): by N sigma by root N sigma.

425
01:08:39.870 --> 01:08:40.580
Faculty (Olympus): Okay.

426
01:08:40.729 --> 01:08:48.760
Faculty (Olympus): This, by definition, byâ€¦ from our earlier derivation from the previous part, would be variance of SN

427
01:08:48.890 --> 01:09:02.139
Faculty (Olympus): divided by the square ofâ€¦ so 1 over this is your A. Okay, so this is yourâ€¦ 1 over root n sigma is the A, so this will be multiplied by A square, which would be n sigma squared.

428
01:09:03.520 --> 01:09:07.170
Faculty (Olympus): Okay? Soâ€¦ and this is equal to 1.

429
01:09:09.180 --> 01:09:12.249
Faculty (Olympus): Okay, so if I take a.

430
01:09:12.350 --> 01:09:14.540
Faculty (Olympus): If I take this quantity.

431
01:09:15.020 --> 01:09:24.510
Faculty (Olympus): and scale it by root n sigma, that means I divide it by root n sigma, then the variance of that scaled quantity is 1.

432
01:09:25.830 --> 01:09:26.819
Faculty (Olympus): Okay.

433
01:09:28.100 --> 01:09:31.870
Faculty (Olympus): So what I'm now saying is the following. If I take a SEN

434
01:09:33.340 --> 01:09:37.409
Faculty (Olympus): And subtract N mu from it. This gives me 0 mean.

435
01:09:38.149 --> 01:09:43.789
Faculty (Olympus): If I subtract a constant from a random variable, the variance does not change. You can check that out.

436
01:09:44.189 --> 01:09:51.069
Faculty (Olympus): Okay? When you subtract, what happens is that the random variables, the random variables values.

437
01:09:51.240 --> 01:09:54.489
Faculty (Olympus): Just shifts, the density function just shifts.

438
01:09:54.720 --> 01:09:58.220
Faculty (Olympus): So, the distribution, the shape does not change.

439
01:09:58.560 --> 01:10:03.890
Faculty (Olympus): Okay, so this gives me a 0 mean. and if I divide it by this quantity.

440
01:10:04.060 --> 01:10:06.870
Faculty (Olympus): S root N times Sigma.

441
01:10:07.230 --> 01:10:13.240
Faculty (Olympus): Okay, this makes it zero mean. This scaling makes it unit variance.

442
01:10:13.560 --> 01:10:15.830
Faculty (Olympus): Okay, so this quantity.

443
01:10:17.160 --> 01:10:22.540
Faculty (Olympus): Okay, so this what we are doing here is we are calling we are calling this a shifting quantity.

444
01:10:23.390 --> 01:10:27.600
Faculty (Olympus): You're shifting the meanâ€¦ shifting the random variable by N mu.

445
01:10:28.060 --> 01:10:30.840
Faculty (Olympus): And what you're doing here is what we call scaling.

446
01:10:33.460 --> 01:10:37.889
Faculty (Olympus): Okay, you're, you're, you're, you're, you're just multiplying it by some constant.

447
01:10:38.710 --> 01:10:47.270
Faculty (Olympus): Each of the N's, you're multiplying it by some constant. So, every one of these has a zero mean, because you have subtracted the mean from it.

448
01:10:47.560 --> 01:10:55.759
Faculty (Olympus): And because you have divided it by its standard deviation, this will haveâ€¦ this quantity is zero mean.

449
01:10:57.000 --> 01:10:58.520
Faculty (Olympus): unit variance.

450
01:11:02.910 --> 01:11:05.949
Faculty (Olympus): Variance is one, the mean is zero.

451
01:11:06.280 --> 01:11:08.120
Faculty (Olympus): Okay? Any questions on that?

452
01:11:09.190 --> 01:11:15.159
Faculty (Olympus): This is something that's simple algebra, if you just go back andâ€¦ go back and apply the formulas from your first step.

453
01:11:15.750 --> 01:11:18.660
Abhineet Bansal .: So, not able to understand, how is it equal to 1?

454
01:11:19.070 --> 01:11:22.500
Faculty (Olympus): bought Okay, this part? Yeah.

455
01:11:22.710 --> 01:11:23.450
Abhineet Bansal .: Yes, sir.

456
01:11:24.310 --> 01:11:25.880
Faculty (Olympus): Let me show this again.

457
01:11:26.280 --> 01:11:28.340
Faculty (Olympus): Take a random variable X.

458
01:11:29.880 --> 01:11:34.180
Faculty (Olympus): Okay, let's assume that variance of X is Sigma Square.

459
01:11:35.330 --> 01:11:36.250
Faculty (Olympus): Okay.

460
01:11:37.080 --> 01:11:39.000
Faculty (Olympus): What is variance of AX?

461
01:11:41.590 --> 01:11:42.949
Faculty (Olympus): What happened here?

462
01:11:44.540 --> 01:11:46.229
Faculty (Olympus): What is variance of AX?

463
01:11:47.020 --> 01:11:49.350
Abhineet Bansal .: So A square into variance of X.

464
01:11:49.350 --> 01:11:50.219
Faculty (Olympus): Got it.

465
01:11:53.440 --> 01:11:54.320
Faculty (Olympus): Right.

466
01:11:57.290 --> 01:12:03.679
Faculty (Olympus): What is variance of SN divided by root and sigma? Call 1 over root and sigma as A.

467
01:12:06.010 --> 01:12:07.570
Faculty (Olympus): A Sen is my ex.

468
01:12:08.160 --> 01:12:11.220
Abhineet Bansal .: So 1 by N comes outside and then variance of S.

469
01:12:11.220 --> 01:12:13.660
Faculty (Olympus): by root n sigma comes outside.

470
01:12:14.240 --> 01:12:16.410
Faculty (Olympus): That becomes, and you take the square of that.

471
01:12:16.790 --> 01:12:18.170
Faculty (Olympus): that's n sigma square.

472
01:12:18.740 --> 01:12:20.439
Abhineet Bansal .: Correct. How does it become one?

473
01:12:20.440 --> 01:12:21.640
Faculty (Olympus): Variants of SN.

474
01:12:24.950 --> 01:12:26.510
Abhineet Bansal .: Variants of Asem.

475
01:12:26.510 --> 01:12:28.310
Faculty (Olympus): We have done that before, right, somewhere here.

476
01:12:28.310 --> 01:12:29.490
Gaurav Singh .: Math Club again.

477
01:12:29.490 --> 01:12:31.339
Faculty (Olympus): Sigma no N sigma squared.

478
01:12:31.340 --> 01:12:32.480
Gaurav Singh .: And, andâ€¦

479
01:12:32.770 --> 01:12:34.079
Abhineet Bansal .: Yes, n sigma squared.

480
01:12:35.060 --> 01:12:37.060
Faculty (Olympus): Notebook Rakhna Likna.

481
01:12:37.450 --> 01:12:38.490
Faculty (Olympus): Okay.

482
01:12:38.770 --> 01:12:41.430
Faculty (Olympus): That I can go back and point you to that point.

483
01:12:41.980 --> 01:12:46.819
Faculty (Olympus): Okay, soâ€¦ so variance of this is N sigma square, this is N sigma square, that's one.

484
01:12:48.890 --> 01:12:49.720
Abhineet Bansal .: Oh.

485
01:12:50.100 --> 01:12:52.320
Faculty (Olympus): Okay!

486
01:12:52.430 --> 01:12:54.800
Faculty (Olympus): Notebook, notebook, okay?

487
01:12:57.000 --> 01:12:58.990
Faculty (Olympus): Sorry.

488
01:12:59.570 --> 01:13:14.120
Faculty (Olympus): Okay, so when I define this quantity, I just showed you that this has a zero mean, and, yeah, so this has a zero mean and unit variance, okay? So this is ZN isâ€¦

489
01:13:15.340 --> 01:13:16.709
Faculty (Olympus): Zero mean?

490
01:13:17.700 --> 01:13:20.680
Faculty (Olympus): Andâ€¦ unit variance.

491
01:13:22.050 --> 01:13:22.840
Faculty (Olympus): He.

492
01:13:23.430 --> 01:13:24.290
Faculty (Olympus): Okay.

493
01:13:26.160 --> 01:13:30.470
Rahul Shrikrishna Joshi .: Why it is called zero mean the numerator itself will be zero, right?

494
01:13:30.470 --> 01:13:32.810
Faculty (Olympus): No, it would be expected, no.

495
01:13:33.180 --> 01:13:34.990
Faculty (Olympus): Numerator will not be zero.

496
01:13:35.090 --> 01:13:36.500
Faculty (Olympus): This is random.

497
01:13:38.920 --> 01:13:40.229
Rahul Shrikrishna Joshi .: More the bigger value.

498
01:13:40.230 --> 01:13:41.959
Faculty (Olympus): No, no, wait, wait, do you understand?

499
01:13:42.330 --> 01:13:43.740
Faculty (Olympus): This is 0.

500
01:13:45.640 --> 01:13:46.040
Rahul Shrikrishna Joshi .: Yep.

501
01:13:46.040 --> 01:13:48.210
Faculty (Olympus): Sin minus n mu is not zero.

502
01:13:49.790 --> 01:13:50.900
Rahul Shrikrishna Joshi .: Okay, got it, yeah.

503
01:13:51.590 --> 01:13:59.000
Faculty (Olympus): Okay? Don't forget, don't confuse expectations to the random values, okay?

504
01:13:59.560 --> 01:14:00.890
Faculty (Olympus): Okay, yeah.

505
01:14:01.100 --> 01:14:19.679
Faculty (Olympus): You know, thoseâ€¦ yeah, so thoseâ€¦ you know, the language is important, so just do pick up on the language ofâ€¦ of theâ€¦ ofâ€¦ of discourse here. It's important to get thatâ€¦ get thoseâ€¦ get those words, okay? Yeah. Any questions on this? So, so that this ZN is a zero mean unit variance random variable.

506
01:14:20.860 --> 01:14:22.419
Faculty (Olympus): For all values of N.

507
01:14:25.040 --> 01:14:25.920
Faculty (Olympus): Okay.

508
01:14:26.260 --> 01:14:33.949
Faculty (Olympus): So let me repeat this again. So I'm saying here that ZN isâ€¦ Zero mean?

509
01:14:34.880 --> 01:14:45.310
Faculty (Olympus): Unit variance, unitâ€¦ variance RV, random variable, for all N. This, this here means for all N.

510
01:14:47.630 --> 01:15:04.330
Faculty (Olympus): Okay? For every value of n, the numerator isâ€¦ the expectation of this quantity is 0, because SN minus N mu is 0. Expectation of SN minus N mu is 0. Expectation of SN minus N mu is 0. When you scale it by root n sigma.

511
01:15:04.480 --> 01:15:07.739
Faculty (Olympus): Okay? It makes the variance 1.

512
01:15:09.070 --> 01:15:09.670
Faculty (Olympus): Okay?

513
01:15:10.630 --> 01:15:13.029
Abhineet Bansal .: What is ZN called, sir? What is the term for it?

514
01:15:13.030 --> 01:15:15.760
Faculty (Olympus): I've just defined it some number. Doesn't matter.

515
01:15:16.150 --> 01:15:18.070
Faculty (Olympus): Just some, just some quantity.

516
01:15:18.910 --> 01:15:22.219
Faculty (Olympus): Just someâ€¦ just a name. I just give it a name called Zede.

517
01:15:22.760 --> 01:15:23.630
Faculty (Olympus): Together!

518
01:15:23.750 --> 01:15:27.009
Faculty (Olympus): Okay, so now the theorem is.

519
01:15:27.450 --> 01:15:34.900
Faculty (Olympus): As ZN becomes large, Okay, ZN tends to the unit normal.

520
01:15:38.540 --> 01:15:39.750
Faculty (Olympus): In the limit.

521
01:15:41.160 --> 01:15:49.169
Faculty (Olympus): Meaning that the random variable, if I were to look at the probability of Zn being less than small z.

522
01:15:49.300 --> 01:15:56.370
Faculty (Olympus): It is the probability of the unit normal random variable being less than or equal to small set.

523
01:15:57.040 --> 01:16:01.329
Faculty (Olympus): Okay? So intuitively, what this means is that probâ€¦

524
01:16:07.050 --> 01:16:09.060
Faculty (Olympus): Probably a.

525
01:16:12.360 --> 01:16:14.080
Faculty (Olympus): AI Jadav Yadav.

526
01:16:17.740 --> 01:16:19.120
Faculty (Olympus): Well.

527
01:16:21.990 --> 01:16:30.159
Faculty (Olympus): probability of ZN Being less than or equal to smalls small Z.

528
01:16:31.020 --> 01:16:34.689
Faculty (Olympus): Gets close to probability of.

529
01:16:36.330 --> 01:16:38.920
Faculty (Olympus): P R O B.

530
01:16:39.680 --> 01:16:41.650
Faculty (Olympus): Of unit.

531
01:16:43.530 --> 01:16:44.840
Faculty (Olympus): Normal.

532
01:16:46.640 --> 01:16:48.629
Faculty (Olympus): Taking on a value.

533
01:16:48.870 --> 01:16:50.120
Faculty (Olympus): Letâ€¦ sorry.

534
01:16:51.100 --> 01:16:52.419
Faculty (Olympus): Less than Z.

535
01:16:53.280 --> 01:16:59.740
Faculty (Olympus): Okay, so mind you that probability that Zn is less than or equal to small z is a number, which is a function of z, of course.

536
01:16:59.990 --> 01:17:07.629
Faculty (Olympus): Okay? So as you make N larger and larger, for every value of Z, Okay, this.

537
01:17:08.270 --> 01:17:10.750
Faculty (Olympus): This limiting behavior is shown.

538
01:17:12.130 --> 01:17:17.880
Faculty (Olympus): Okay, so this is a very powerful result. Now, somebody had a question about normal distribution.

539
01:17:18.090 --> 01:17:24.169
Faculty (Olympus): This is exactly what is exploited in all the estimation things that we will be talking about.

540
01:17:24.760 --> 01:17:28.390
Faculty (Olympus): Okay, much of the exclamation things that we'll be talking about, just one second, okay?

541
01:17:28.510 --> 01:17:31.479
Faculty (Olympus): So this isâ€¦ this is what is called the central limit theorem.

542
01:17:32.150 --> 01:17:39.439
Faculty (Olympus): Okay, as N becomes large, ZN approaches the unit normal random variable. Now, anybody has a question?

543
01:17:41.300 --> 01:17:45.340
Abhineet Bansal .: So this small Z is the value of Z for a smaller N.

544
01:17:46.100 --> 01:17:49.060
Faculty (Olympus): No. Okay. The way to think about it is.

545
01:17:49.330 --> 01:17:53.239
Faculty (Olympus): Capital Z is some, some quantity, ok, some random variable.

546
01:17:54.710 --> 01:17:57.230
Faculty (Olympus): Come on, I don't know what I should do toâ€¦

547
01:17:57.930 --> 01:18:03.970
Faculty (Olympus): Okay, there has to be some snap to grid, which I didn't want it to do, and I don't want to start correcting that now.

548
01:18:03.970 --> 01:18:07.410
Faculty (Olympus): Suhas here, on the toolbar on your left.

549
01:18:07.410 --> 01:18:07.880
Faculty (Olympus): No, I don't.

550
01:18:07.880 --> 01:18:08.810
Faculty (Olympus): I don't I don't.

551
01:18:08.810 --> 01:18:10.989
Faculty (Olympus): I don't want to change anything.

552
01:18:10.990 --> 01:18:14.570
Faculty (Olympus): Just deselect the very last icon, like, on the left.

553
01:18:14.850 --> 01:18:16.820
Faculty (Olympus): The very last one.

554
01:18:17.210 --> 01:18:18.540
Faculty (Olympus): Oh, that one, okay.

555
01:18:18.720 --> 01:18:19.270
Faculty (Olympus): Yep.

556
01:18:20.670 --> 01:18:22.050
Faculty (Olympus): Okay, that's it.

557
01:18:22.050 --> 01:18:25.100
Faculty (Olympus): Yeah, that's the one. Okay, sorry. Yeah, yeah, I forgot that.

558
01:18:25.390 --> 01:18:31.890
Faculty (Olympus): Yeah, I don't like changing something in the class. Okay, so yeah, where am I?

559
01:18:32.300 --> 01:18:33.020
Abhineet Bansal .: Small z.

560
01:18:33.020 --> 01:18:37.209
Faculty (Olympus): Small Z, yes, small Z.

561
01:18:38.850 --> 01:18:43.469
Faculty (Olympus): Probability of Zn is a Zn is a random variable.

562
01:18:43.630 --> 01:18:44.600
Faculty (Olympus): Okay.

563
01:18:45.460 --> 01:18:55.039
Faculty (Olympus): What is the probability that it is less than or equal to some Z? What is the Zâ€¦ small Z could take on a value, 0.3, 0.5, minus 8, whatever.

564
01:18:57.140 --> 01:18:58.040
Faculty (Olympus): Okay.

565
01:18:59.440 --> 01:19:01.100
Abhineet Bansal .: Between minus 1 to 1.

566
01:19:01.100 --> 01:19:01.950
Faculty (Olympus): No.

567
01:19:02.210 --> 01:19:04.720
Faculty (Olympus): Z is minus infinity to plus infinity.

568
01:19:05.250 --> 01:19:15.030
Faculty (Olympus): I have noâ€¦ I did not put any restrictions on the values of X, hence I did not put any restrictions on the values of X.

569
01:19:15.380 --> 01:19:24.480
Faculty (Olympus): Sorry, of Z. Sorry, let me repeat. I did not put any restrictions on the values of X, hence I don't have to have any restrictions on the values of Z.

570
01:19:26.830 --> 01:19:32.349
Abhineet Bansal .: Can you rewrite that last theorem, sir, conclusion which you wrote, probability of Zn is less than Z?

571
01:19:33.590 --> 01:19:38.139
Faculty (Olympus): Okay, so, okay, so this is an arbitrary random variable.

572
01:19:38.640 --> 01:19:45.410
Faculty (Olympus): Okay? What I'm saying is this quantity, as N becomes large, okay, becomesâ€¦

573
01:19:45.510 --> 01:19:51.150
Faculty (Olympus): Closer and closer to probability of the normal RV.

574
01:19:51.590 --> 01:19:55.250
Faculty (Olympus): Being less than or equal to small set is also less.

575
01:20:00.450 --> 01:20:03.470
Faculty (Olympus): Okay, so this is what this is what we call limiting.

576
01:20:03.470 --> 01:20:05.849
Siddharth Digambar Kulkarni .: Of the original random variable, right?

577
01:20:05.850 --> 01:20:06.320
Faculty (Olympus): Sorry.

578
01:20:06.320 --> 01:20:07.080
Siddharth Digambar Kulkarni .: Soâ€¦

579
01:20:09.200 --> 01:20:10.159
Faculty (Olympus): Say that again.

580
01:20:10.940 --> 01:20:13.950
Siddharth Digambar Kulkarni .: This is irrespective of the original randomâ€¦ Correct.

581
01:20:13.950 --> 01:20:22.329
Faculty (Olympus): This is irrespective of the original random variable. There are some minor restrictions. We'll take them off for the, you know, we'll just ignore them for the sake of practicality.

582
01:20:22.330 --> 01:20:27.059
Siddharth Digambar Kulkarni .: But sir, how big the end should be so that it becomes a random? How big.

583
01:20:27.060 --> 01:20:32.650
Faculty (Olympus): That depends on the problem. So let's not get into those discussions. Okay, we'll come to that in examples and so on.

584
01:20:33.120 --> 01:20:33.690
Siddharth Digambar Kulkarni .: Okay.

585
01:20:33.690 --> 01:20:39.130
Faculty (Olympus): I mean, valid question, but let us defer the discussion when we see real stuff.

586
01:20:39.680 --> 01:20:40.510
Faculty (Olympus): Take care.

587
01:20:40.660 --> 01:20:43.230
Faculty (Olympus): Okay, one last question, Naina.

588
01:20:44.670 --> 01:20:58.339
Naina Punjwani .: Professor, will a graph plotting, if you can show a graph plot plotting for this, it might help, to understand the concept more clearer. I'm not sure if you can do that.

589
01:20:58.340 --> 01:21:05.919
Faculty (Olympus): No, I can't do that immediately. So here is a simple exercise. Go and do that with uniform random variables.

590
01:21:06.910 --> 01:21:18.060
Faculty (Olympus): go to, you know, you've been taught how to write programs, okay? You can quicklyâ€¦ and I think I can ask the TAs to do that. Suhas, please note that for the TA session.

591
01:21:18.200 --> 01:21:23.869
Faculty (Olympus): Okay, so what you can do is do the following, okay? So let X be uniform.

592
01:21:24.540 --> 01:21:28.229
Faculty (Olympus): Okay, X be uniform in, let's say, 0 to 1.

593
01:21:29.930 --> 01:21:35.189
Faculty (Olympus): Okay? Then you construct MN, exactlyâ€¦ not MN, sorry, ZN, as I just said.

594
01:21:40.050 --> 01:21:44.159
Faculty (Olympus): Okay, you construct ZN is equal to

595
01:21:45.530 --> 01:21:54.359
Faculty (Olympus): Okay, Xi. Sudden is equal to whatever I just said, sigma, sorry, sigma Xi minus.

596
01:21:54.540 --> 01:22:07.320
Faculty (Olympus): N into 0.5 divided by whatever is the mean of this, root n times the variance, the standard deviation of uniform random variable between 0 and 1.

597
01:22:07.600 --> 01:22:14.090
Faculty (Olympus): Okay? You construct that, and you just start plotting the density of

598
01:22:14.270 --> 01:22:19.279
Faculty (Olympus): of ZN. You will quickly see that it will become closer and closer to normal.

599
01:22:21.560 --> 01:22:29.399
Faculty (Olympus): Okay? So, Swash, can youâ€¦ can you sort of make that a demo in the TA issue? Okay? Yeah.

600
01:22:30.950 --> 01:22:31.800
Faculty (Olympus): Okay.

601
01:22:32.280 --> 01:22:36.629
Faculty (Olympus): All right? So, yeah, so that's thisâ€¦ that's what is called the central limit theorem.

602
01:22:36.860 --> 01:22:42.510
Faculty (Olympus): So, there are many such theorems that describe what happens in the aggregate.

603
01:22:42.850 --> 01:22:48.940
Faculty (Olympus): Okay, so, you know, if you take a particular, if you pull out a particular person from the street.

604
01:22:49.070 --> 01:22:57.899
Faculty (Olympus): The height of that person, you know, varies. It could be anywhere from, let's say, four and a half, five feet, all the way to maybe six and a half, seven feet.

605
01:22:58.210 --> 01:23:01.569
Faculty (Olympus): Okay, basketball players do have those kinds of heights.

606
01:23:01.880 --> 01:23:12.790
Faculty (Olympus): Okay? Now, soâ€¦ but on the other hand, if you start taking some samples and looking them up in the aggregate, collecting them together, collect, you know, computing the sum of it.

607
01:23:12.790 --> 01:23:23.820
Faculty (Olympus): They will start behaving very differently. They'll do what are essentially what we call behaviors in the aggregate. And that's easier to understand than describe individuals.

608
01:23:23.820 --> 01:23:35.570
Faculty (Olympus): I mean, there's less randomness in this, in the aggregate than in the individual ones. Okay. So these limit theorems capture what happens when you start aggregating random variables.

609
01:23:37.070 --> 01:23:44.730
Faculty (Olympus): Okay? So the law of large number tells us that the sample average gets close to the true average, which you never know.

610
01:23:44.970 --> 01:23:47.110
Faculty (Olympus): Okay, it only gets close to that.

611
01:23:47.320 --> 01:23:49.700
Faculty (Olympus): And the central limit theorem tells us.

612
01:23:50.010 --> 01:23:57.510
Faculty (Olympus): The randomness in that getting close to the true value. How random is it? What is the variance of it?

613
01:23:57.640 --> 01:24:01.359
Faculty (Olympus): If you scale it carefully, you'll be able to get that number.

614
01:24:02.950 --> 01:24:03.730
Faculty (Olympus): Okay.

615
01:24:03.830 --> 01:24:15.690
Faculty (Olympus): So itâ€¦ so this, essentially, this, this, this and this together motivates all the mechanisms that we have to, you know, to understand how to estimate

616
01:24:15.690 --> 01:24:26.239
Faculty (Olympus): you know, I mean, how to report the outcomes of polling, you know, polling that we conduct, you know, how to develop, for example, premiums of.

617
01:24:26.260 --> 01:24:31.000
Faculty (Olympus): For premiums for for for for insurance.

618
01:24:31.280 --> 01:24:50.799
Faculty (Olympus): Okay? Yeah, you know, maybe I can just showâ€¦ we'll probably give you a problem that you can think about with respect to insurance and so on, and also for doing simulations and a whole bunch of everything else. I mean, central limit theorem and the law of large numbers is used extensively in everything that we do that involves randomness.

619
01:24:51.360 --> 01:24:52.060
Faculty (Olympus): Okay.

620
01:24:53.200 --> 01:24:53.950
Faculty (Olympus): Yeah.

621
01:24:54.330 --> 01:25:05.100
Faculty (Olympus): And why is CLT important? CLT is important because it justifies the use of everywhere we go, we just say Gaussian distribution, or many of you call it the normal distribution.

622
01:25:06.000 --> 01:25:13.240
Faculty (Olympus): Okay, so the language that I'm going to use is that Gaussian means Okay.

623
01:25:13.350 --> 01:25:16.230
Faculty (Olympus): Some mean and some variance.

624
01:25:16.750 --> 01:25:26.529
Faculty (Olympus): Normal, when I say, especially, I'll usually use the word unit normal. Unit normal means Gaussian with zero mean.

625
01:25:28.250 --> 01:25:30.730
Faculty (Olympus): and unit variance. That's what I think.

626
01:25:31.240 --> 01:25:33.589
Faculty (Olympus): Okay, that's the language I'm going to use. Okay.

627
01:25:35.220 --> 01:25:41.340
Faculty (Olympus): Any questions on this? I'm going to now sort of spend a little bit more time trying to understand the Gaussian distribution.

628
01:25:43.750 --> 01:25:46.120
Faculty (Olympus): Gaurav.

629
01:25:46.350 --> 01:26:01.240
Gaurav Singh .: Yeah, one question, like, when we talked about LAR, you know, when we, find out the normalâ€¦ unit normal random variable for, it will tend towards unit normal random variable when the N becomes large.

630
01:26:01.240 --> 01:26:01.800
Faculty (Olympus): Mmm.

631
01:26:01.800 --> 01:26:05.450
Gaurav Singh .: It will be all kind of distribution of the random variable, right?

632
01:26:05.450 --> 01:26:13.619
Faculty (Olympus): All things that we will be concerned about. There are corner cases which we are not going to discuss. Everything that is practical for us.

633
01:26:14.030 --> 01:26:18.060
Faculty (Olympus): Will follow the will will tend to become normal correct.

634
01:26:18.060 --> 01:26:19.380
Gaurav Singh .: Understood. Okay.

635
01:26:19.640 --> 01:26:20.330
Faculty (Olympus): Very good.

636
01:26:20.490 --> 01:26:21.800
Faculty (Olympus): Shraddha.

637
01:26:22.410 --> 01:26:23.400
Faculty (Olympus): Hello.

638
01:26:23.400 --> 01:26:24.000
Shraddha Aniruddha Mitragotri .: Yeah.

639
01:26:24.000 --> 01:26:24.390
Faculty (Olympus): Yeah.

640
01:26:24.390 --> 01:26:33.369
Shraddha Aniruddha Mitragotri .: We have been talking about sample and then large numbers. Will we be touching on the definition of large? What does large mean for that?

641
01:26:33.370 --> 01:26:38.799
Faculty (Olympus): When we talk about limit theorems, we only talk about the limiting value.

642
01:26:39.090 --> 01:26:43.280
Faculty (Olympus): What happens in the limit? It's a mathematical construct at this time.

643
01:26:43.380 --> 01:26:48.070
Faculty (Olympus): Why do we talk about Mathematâ€¦ why do we talk about limiting behavior? Because

644
01:26:48.350 --> 01:26:53.470
Faculty (Olympus): Because that's easy to prove, okay? So that's too easy to sort of understand.

645
01:26:53.720 --> 01:26:58.240
Faculty (Olympus): Now, how to convert it into practical depends on the practical problem.

646
01:26:59.640 --> 01:27:11.169
Faculty (Olympus): And whatâ€¦ there is aâ€¦ there are theories associated with what Nâ€¦ what happens when N is finite, large N, and so on. But the problem with that is that those becomes too complicated.

647
01:27:11.670 --> 01:27:16.269
Faculty (Olympus): Okay, those expressions, those derivations are too messy. We won't do all of that.

648
01:27:16.760 --> 01:27:24.800
Faculty (Olympus): What is a good end is basically coming from experience and looking at the problem. And youâ€¦ and, you know, for mostâ€¦

649
01:27:25.540 --> 01:27:34.910
Faculty (Olympus): I mean, just crudely, and don'tâ€¦ don't quote me on this anywhere else, approximately 100â€¦ anywhere from 50 to 100 typically is goodâ€¦ is large enough.

650
01:27:36.200 --> 01:27:43.530
Faculty (Olympus): Okay, so when you are looking at ZN, when N is about 50 to 100, you can approximate it as a Gaussian distribution, as a unit normal.

651
01:27:44.420 --> 01:27:45.360
Faculty (Olympus): Okay.

652
01:27:46.090 --> 01:27:46.929
Shraddha Aniruddha Mitragotri .: Thank you, sir.

653
01:27:46.930 --> 01:27:52.500
Faculty (Olympus): Yeah, yeah, okay. Okay, okay, so now I wanna give you, okay.

654
01:27:53.020 --> 01:27:55.619
Faculty (Olympus): Did I do it here? Yeah, why not?

655
01:27:56.680 --> 01:27:59.369
Faculty (Olympus): Just one second. I was supposed to.

656
01:28:00.270 --> 01:28:05.800
Faculty (Olympus): Yeah, okay, so let meâ€¦ let me give you one of my favorite,

657
01:28:06.040 --> 01:28:12.719
Faculty (Olympus): Whatever, you know, favorite goofs from goofs or whatever it is that you want to think about.

658
01:28:16.060 --> 01:28:27.550
Faculty (Olympus): Okay, so this was a, you know, most of you probably, some of you are probably familiar with what happened about 8, 10 years ago. Okay, there was, in the US, the elections, Hillary Clinton.

659
01:28:27.550 --> 01:28:31.509
Faculty (Olympus): You know, and Donald Trump was supposed to be fighting this election.

660
01:28:31.510 --> 01:28:51.089
Faculty (Olympus): And before the election results were announced, I don't know if I have the date here. No, I don't. Okay, this is before the election of the, before the day of the election. So this was the news item. Okay, Hillary Clinton has an 85% chance to win. Of course, she famously lost the election.

661
01:28:51.600 --> 01:29:03.479
Faculty (Olympus): Okay, so the immediate question is, did the polls do anything wrong? I mean, this is somethingâ€¦ a question like this has been asked before, and how did this number come about in the New York Times was this.

662
01:29:04.490 --> 01:29:23.419
Faculty (Olympus): Okay? So, they looked atâ€¦ there are a large number of these organizations that keeps, you know, tracking the polls. Among these, you know, the one that is probably statistically most sophisticated is this fellow, 538. Okay, and occasionally, even this one is something that I haveâ€¦

663
01:29:23.660 --> 01:29:37.270
Faculty (Olympus): I have, I have liked and the other, yeah, Real Clear Politics and 538 are two reasonable, you know, reasonably, reasonably sophisticated. The others are, I mean, to varying degrees of sophistication, the others are reasonable.

664
01:29:37.770 --> 01:29:53.870
Faculty (Olympus): Okay, now what they said here was that what they put out here is this is the amount of what they call the popular vote. If they count on the average American, so they'll ask about, I think in this case, about 300 or 500 Americans.

665
01:29:54.680 --> 01:30:11.780
Faculty (Olympus): 300 potential voters, they will make some randomâ€¦ they'll make some of these choices using a suitable kind of randomness, and call them and ask them who they'll vote for. And it turns out that all of these polls, if you look at it.

666
01:30:12.490 --> 01:30:19.320
Faculty (Olympus): Most of them gave a larger amount of votes to Hillary Clinton as opposed to Donald Trump.

667
01:30:19.560 --> 01:30:21.530
Faculty (Olympus): Okay, nowâ€¦

668
01:30:22.080 --> 01:30:29.060
Faculty (Olympus): They're all, you know, if you just think about, if you just look at these numbers, they're very, very close, okay, they're within about 2-3% of each other.

669
01:30:29.430 --> 01:30:35.409
Faculty (Olympus): Based on this statement, New York Times made this claim that Hillary Clinton has an 85% chance to win.

670
01:30:35.650 --> 01:30:38.560
Faculty (Olympus): So the question that I'm going to ask is, was this wrong?

671
01:30:38.930 --> 01:30:45.110
Faculty (Olympus): Okay, so this is, mind you, these are estimates of Vote share.

672
01:30:50.630 --> 01:30:51.440
Faculty (Olympus): Okay.

673
01:30:51.670 --> 01:30:57.820
Faculty (Olympus): This is the prediction from New York Times, based on all of that.

674
01:30:58.060 --> 01:31:00.550
Faculty (Olympus): Okay, and then you compare this with the result.

675
01:31:00.870 --> 01:31:04.559
Faculty (Olympus): So, anybody wants to take a crack at, you know.

676
01:31:05.030 --> 01:31:07.149
Faculty (Olympus): Saying New York Times messed this up.

677
01:31:07.950 --> 01:31:09.490
Faculty (Olympus): Or didn't mess it up.

678
01:31:10.270 --> 01:31:10.760
Abhineet Bansal .: Dieselâ€¦

679
01:31:10.760 --> 01:31:13.219
Faculty (Olympus): I mean, these areâ€¦ Go ahead, go ahead.

680
01:31:13.220 --> 01:31:20.240
Abhineet Bansal .: These are vote shares across the entire country, so maybe they have a higher vote share within a certain region, which contributes to.

681
01:31:20.240 --> 01:31:21.269
Faculty (Olympus): I think the.

682
01:31:21.270 --> 01:31:22.060
Abhineet Bansal .: Total share.

683
01:31:22.060 --> 01:31:33.680
Faculty (Olympus): A good point, but I think the way they did this randomness was, I mean, the way they distributed the the whatever the polling was determined, you know, that they took that into account.

684
01:31:34.790 --> 01:31:38.229
Faculty (Olympus): Took that into account. From my end, I mean, of course, you know, as I said, yeah.

685
01:31:38.560 --> 01:31:47.139
Faculty (Olympus): I mean, that's a very valid, whatever, immediate criticism, but to the best of my understanding, that was addressed. Okay? Yeah.

686
01:31:47.340 --> 01:31:48.920
Faculty (Olympus): Rahul?

687
01:31:49.560 --> 01:31:56.460
Rahul Shrikrishna Joshi .: Sir, the true population at the state level, was it a sample at the state level was considered because they have a.

688
01:31:56.460 --> 01:32:06.410
Faculty (Olympus): As I said, so there are some, I mean, I don't know all the details of all of these, there are so many of them. There are, I mean, we just want to get a ballpark idea of what, what, what, how toâ€¦

689
01:32:06.700 --> 01:32:14.859
Faculty (Olympus): how to think about what we are seeing, okay? That's basically all. So let's not worry too much about whether they wereâ€¦ assume that they were doing the right thing.

690
01:32:15.480 --> 01:32:23.290
Faculty (Olympus): For the time being, just assume they were doing the right thing. You know, it's too messy toâ€¦ to do, you know, to go into all the details. Okay? Sanket.

691
01:32:23.730 --> 01:32:28.700
Sanketh Chiplunkar .: Sir, looking at the chart, I'm quite worried. Why didâ€¦ why New York Times did not say it's 100%?

692
01:32:30.580 --> 01:32:36.050
Faculty (Olympus): Okay, good question. If I were to ask you about something, would you say 100% Yay Yoga?

693
01:32:36.990 --> 01:32:38.870
Sanketh Chiplunkar .: I guess so, looking at the chart.

694
01:32:38.870 --> 01:32:40.509
Faculty (Olympus): Looking at which one?

695
01:32:41.100 --> 01:32:43.200
Sanketh Chiplunkar .: The one that's shown in the slide now.

696
01:32:43.200 --> 01:32:46.900
Faculty (Olympus): Don't forget that associated with each of these numbers is an error bar.

697
01:32:47.650 --> 01:32:49.370
Faculty (Olympus): We showed about errors before.

698
01:32:49.740 --> 01:32:50.790
Sanketh Chiplunkar .: Oh, yes, okay.

699
01:32:50.790 --> 01:32:52.710
Faculty (Olympus): Okay, yeah, Shravan.

700
01:32:56.680 --> 01:33:01.359
Shravan Kumar Ganpur .: So, what I think, Samin, the other way around, it should not have been published.

701
01:33:02.160 --> 01:33:03.370
Shravan Kumar Ganpur .: What?

702
01:33:03.370 --> 01:33:04.180
Faculty (Olympus): What what what?

703
01:33:04.980 --> 01:33:07.170
Shravan Kumar Ganpur .: I should not have been published to one of them.

704
01:33:07.170 --> 01:33:07.809
Faculty (Olympus): So you mean.

705
01:33:07.810 --> 01:33:08.500
Shravan Kumar Ganpur .: audience.

706
01:33:08.500 --> 01:33:12.550
Faculty (Olympus): You mean that they wouldn't have done this 85%, they shouldn't have done this 85% thing?

707
01:33:12.790 --> 01:33:17.170
Shravan Kumar Ganpur .: No, they should not have published it something like to change the audiences.

708
01:33:17.170 --> 01:33:32.120
Faculty (Olympus): No, no, no, that's notâ€¦ no, no, no, wait, wait, wait. You're getting into a different kind of an argument. The philosophical argument about the correctness of these areâ€¦ let's not get into that, okay? In the US, you are allowed toâ€¦ you know, publish the results of polls.

709
01:33:32.120 --> 01:33:37.580
Faculty (Olympus): Even as the election is going on. So let's not get into the that becomes too philosophical.

710
01:33:37.600 --> 01:33:40.059
Faculty (Olympus): Okay, the questionâ€¦ let's stay statistical.

711
01:33:40.560 --> 01:33:48.449
Faculty (Olympus): I'm not interested in the politics of this one, okay? I'm interested in treating it as a statistical outcome, okay? What do I do?

712
01:33:48.680 --> 01:33:51.740
Faculty (Olympus): Okay, who was this? This was Kapil, is it?

713
01:33:52.890 --> 01:33:57.009
Kapil Shailesh Inamdar .: Sir, I had a question, no, no. He was another guy.

714
01:33:57.140 --> 01:34:02.800
Kapil Shailesh Inamdar .: I had a question, what exactly doesâ€¦ Percent to win means because.

715
01:34:02.800 --> 01:34:04.359
Faculty (Olympus): That's the question that I'm asking you.

716
01:34:04.360 --> 01:34:04.870
Kapil Shailesh Inamdar .: the.

717
01:34:04.870 --> 01:34:05.550
Faculty (Olympus): So.

718
01:34:05.550 --> 01:34:07.459
Kapil Shailesh Inamdar .: Say like one person said.

719
01:34:07.460 --> 01:34:15.069
Faculty (Olympus): Hang on, hang on, hang on, hang on. I'll explain that first. I'll explain that first. If X is a random variable, which will take on a value 1,

720
01:34:15.290 --> 01:34:20.639
Faculty (Olympus): If Hillary Clinton wins and zero if Hillary Clinton loses. Treat it that way.

721
01:34:21.020 --> 01:34:22.040
Faculty (Olympus): Okay.

722
01:34:22.320 --> 01:34:24.920
Faculty (Olympus): And the probability of a 1 isâ€¦

723
01:34:25.030 --> 01:34:31.250
Faculty (Olympus): 0.85, and probability of a 0 is 0.15, is what New York Times is telling you here.

724
01:34:32.970 --> 01:34:37.469
Faculty (Olympus): That's the way to interpret this statement. Okay, Kapil, did that is that clear?

725
01:34:38.450 --> 01:34:39.190
Kapil Shailesh Inamdar .: Yeah.

726
01:34:39.190 --> 01:34:39.610
Faculty (Olympus): Okay?

727
01:34:39.610 --> 01:34:52.059
Kapil Shailesh Inamdar .: So that means they have taken this 0.45, like 40 average I I think is 45 and then they have made many possible iterations of that in the geometry.

728
01:34:52.060 --> 01:34:55.599
Faculty (Olympus): No, no, no, no. We don't know how they converted this into that.

729
01:34:55.710 --> 01:35:02.599
Faculty (Olympus): Okay, that formula is not given to us, but what this table is showing you isâ€¦

730
01:35:02.670 --> 01:35:20.910
Faculty (Olympus): what is the fraction of votes estimated by each of these organizations? Each of these organizations, okay? Each of these organizations, what is, according to their polling, what is the estimate of the number of votes, what the fraction of votes that Hillary Clinton is going to get, and what is the fraction of votes that Trump is going to get?

731
01:35:21.400 --> 01:35:23.610
Faculty (Olympus): That is what is being said here.

732
01:35:23.810 --> 01:35:33.319
Faculty (Olympus): Okay, so if this is indeed exactly what happens, then Hillary Clinton will win. If this is indeed what happens, Hillary Clinton will win.

733
01:35:33.730 --> 01:35:36.769
Faculty (Olympus): But associated with these numbers, there's an error bar.

734
01:35:38.120 --> 01:35:40.350
Faculty (Olympus): Okay, that's something that I mentioned earlier.

735
01:35:41.140 --> 01:35:42.040
Faculty (Olympus): Okay.

736
01:35:42.500 --> 01:35:44.119
Faculty (Olympus): Yeah. Aseem?

737
01:35:44.730 --> 01:35:50.929
Aseem Gupta: So you said that this is representative of popular vote, right? But the popular vote doesn't determineâ€¦

738
01:35:50.930 --> 01:35:57.769
Faculty (Olympus): We discussed that. Let's assume there's a clean way to translate popular vote into the victory in the electoral college.

739
01:35:58.240 --> 01:36:06.479
Faculty (Olympus): Let's assume that, okay? Yeah, so I'm going to go with new faces that I see there, people who have not asked the question before. So, Pradeep.

740
01:36:10.670 --> 01:36:11.590
Pradeep Kumar .: Oh, yeah.

741
01:36:12.260 --> 01:36:19.759
Pradeep Kumar .: So, I mean, clearly from the stats and And, and then you like.

742
01:36:19.760 --> 01:36:25.099
Faculty (Olympus): I'm not monitoring the chat, so yeah, so that the chat is the chat. Quickly.

743
01:36:25.620 --> 01:36:27.520
Pradeep Kumar .: Such places,

744
01:36:27.700 --> 01:36:35.150
Pradeep Kumar .: They have not accounted all, all the, you know, like, the poll was run maybe on a smaller sample, right?

745
01:36:36.350 --> 01:36:40.709
Faculty (Olympus): The only, I have a limited question. Was this wrong?

746
01:36:41.180 --> 01:36:42.870
Pradeep Kumar .: Yeah, I mean, yeah, thank you.

747
01:36:43.050 --> 01:36:45.920
Faculty (Olympus): It's a limited question, yes or no, that's all.

748
01:36:47.640 --> 01:36:51.559
Faculty (Olympus): And then, if you want, you can expand on why you think it's right or wrong.

749
01:36:52.020 --> 01:36:53.710
Pradeep Kumar .: I said yes.

750
01:36:56.870 --> 01:37:01.259
Faculty (Olympus): Okay, let's move. Let me just ask one more person, Rahul Bajaj.

751
01:37:01.480 --> 01:37:03.850
Faculty (Olympus): I am going to go to the school.

752
01:37:04.010 --> 01:37:04.740
Rahul D Bajaj .: Ha ha.

753
01:37:05.070 --> 01:37:09.840
Rahul D Bajaj .: Sir, is it that the error, confidence.

754
01:37:09.840 --> 01:37:10.299
Faculty (Olympus): Huh.

755
01:37:10.300 --> 01:37:14.820
Rahul D Bajaj .: Is that the reason why they have, like, assigned a 15% chance.

756
01:37:14.820 --> 01:37:15.300
Faculty (Olympus): Yeah.

757
01:37:15.300 --> 01:37:17.389
Rahul D Bajaj .: For Donald Trump to win.

758
01:37:17.390 --> 01:37:18.300
Faculty (Olympus): Okay.

759
01:37:18.300 --> 01:37:18.870
Rahul D Bajaj .: technical.

760
01:37:18.870 --> 01:37:22.869
Faculty (Olympus): You sort of, you're somewhere, you're getting close to what actually happened.

761
01:37:23.050 --> 01:37:23.780
Faculty (Olympus): Okay.

762
01:37:24.010 --> 01:37:30.989
Faculty (Olympus): As you forget, okay, I think now let me just stop the questions on this. Let me tell you exactly how to interpret such a statement.

763
01:37:32.490 --> 01:37:39.220
Faculty (Olympus): Mind you, this is, you'll eventually get only one sample, okay? Hillary Clinton either wins or doesn't win.

764
01:37:39.630 --> 01:37:49.260
Faculty (Olympus): What it is saying is, assume that it's a coin that you're tossing, which will come up heads with probability 0.85, and tails with probability 0.15.

765
01:37:49.710 --> 01:37:50.480
Faculty (Olympus): Okay.

766
01:37:50.760 --> 01:37:53.429
Faculty (Olympus): Now, if you toss that coin.

767
01:37:53.790 --> 01:38:01.299
Faculty (Olympus): And intuitively, okay, this is not correct, I mean, only according to law of large numbers is this correct. If you toss this coin 100 times.

768
01:38:01.510 --> 01:38:07.950
Faculty (Olympus): 15 of those will give Donald Trump a win, and 85 of those will give Hillary Clinton a win.

769
01:38:08.560 --> 01:38:11.319
Faculty (Olympus): So, one way to think about this is that

770
01:38:12.580 --> 01:38:15.560
Faculty (Olympus): It is one of those 15 that actually happened.

771
01:38:16.210 --> 01:38:17.220
Faculty (Olympus): Okay?

772
01:38:17.340 --> 01:38:19.390
Faculty (Olympus): I cannot say this was wrong.

773
01:38:19.900 --> 01:38:26.829
Faculty (Olympus): This wasâ€¦ I can only prove that this is wrong if I had a large number of such elections.

774
01:38:27.110 --> 01:38:31.229
Faculty (Olympus): Okay? In identical circumstances. I don't have that luxury.

775
01:38:31.490 --> 01:38:50.560
Faculty (Olympus): Okay, so one way to think about it is, based on what I see, what is the belief? What is my belief about X being equal to 1? What is my belief about X is equal to 0? X equal to 1 here corresponds to Hillary Clinton winning, and the other. So the correct answer here is that.

776
01:38:51.440 --> 01:38:52.380
Faculty (Olympus): Okay.

777
01:38:52.590 --> 01:39:01.689
Faculty (Olympus): The correct answer, or the way to think about this here, is that, no, it was not wrong, okay? It gave its belief derived from

778
01:39:01.690 --> 01:39:20.320
Faculty (Olympus): those resultsâ€¦ those polls that it had, and how did it come about? Potentially, the way to think about it is, each of those had anâ€¦ why did they not say 100%? That was a question that was asked by somebody. The reason they did not askâ€¦ the reason it was not 100% is that associated with every number, there was an error margin.

779
01:39:20.330 --> 01:39:34.420
Faculty (Olympus): Okay? Thereâ€¦ you could say, for example, if I were to look at this number, okay, that around 47.4â€¦ 47.2, the actual votes that Hillary Clinton will get could be, okay.

780
01:39:35.580 --> 01:39:40.709
Faculty (Olympus): Could be, I'm just putting, you know, two numbers here, between 42 and 52.

781
01:39:41.090 --> 01:39:47.689
Faculty (Olympus): And what Donald Trump would get could be between, let us say, 38 and 48.

782
01:39:48.950 --> 01:40:08.910
Faculty (Olympus): Okay? It is possible that Hillary Clinton's was more like here, and so what they are saying is, with a very high probability, this is the range with which the number of votes here would be, and this is the range for which the number ofâ€¦ The actual number could be anywhere in that interval. More to the left for Hillary and more to the right for Trump. It could have been that.

783
01:40:09.150 --> 01:40:21.139
Faculty (Olympus): Okay? So, because of thatâ€¦ that kind of a possibility, they have reduced the number from 85 to 15. Exactly how did they come about that, etc? We'll not get into the details of this.

784
01:40:21.280 --> 01:40:27.570
Faculty (Olympus): The only limited point that I want to make here is that when you see a result like this.

785
01:40:27.780 --> 01:40:42.360
Faculty (Olympus): And the outcome, I mean, when you make aâ€¦ when you see a statement like this, and the outcome is not what you think the outcome is being projected here, be careful in jumping to the conclusion that this was wrong.

786
01:40:42.680 --> 01:40:46.390
Faculty (Olympus): Okay, they did not, they did not, they potentially did not make a mistake.

787
01:40:46.870 --> 01:41:01.249
Faculty (Olympus): They just had a belief that if there are 100 such instances, I mean, intuitively, if there are 100 such instances, 85 of them Hillary will win, 55 of 15 of them Trump would win.

788
01:41:01.390 --> 01:41:04.380
Faculty (Olympus): The outcome just happened to be one of those 15.

789
01:41:05.860 --> 01:41:13.939
Faculty (Olympus): I think I won't take any more questions on this. I'll, you know, all of the questions, please lower your hand, we'll take them at the end of the lecture, okay?

790
01:41:16.140 --> 01:41:16.870
Faculty (Olympus): Yeah.

791
01:41:17.610 --> 01:41:20.280
Faculty (Olympus): Now I want to spend some time on the Gaussian distribution.

792
01:41:21.810 --> 01:41:22.730
Faculty (Olympus): Okay.

793
01:41:23.740 --> 01:41:33.940
Faculty (Olympus): So, so again, you know, I could haveâ€¦ Z could be X, it doesn't matter. So, this is the probability density function of the Gaussian.

794
01:41:48.510 --> 01:41:49.260
Faculty (Olympus): Okay.

795
01:41:50.810 --> 01:41:52.229
Faculty (Olympus): So let's call it S.

796
01:41:55.330 --> 01:41:58.069
Faculty (Olympus): Sigma one is greater than Sigma two.

797
01:41:58.550 --> 01:42:02.719
Faculty (Olympus): Okay, so assume that this is symmetric and this is the best that I can draw.

798
01:42:03.320 --> 01:42:05.720
Faculty (Olympus): The way to think about this is.

799
01:42:06.510 --> 01:42:13.580
Faculty (Olympus): thatâ€¦ Okay, so now if Iâ€¦ so this is theâ€¦ so theâ€¦ the density function is centered at mu.

800
01:42:14.050 --> 01:42:18.820
Faculty (Olympus): Okay, that's something that will come out if you analyze this, the nature of this equation.

801
01:42:19.540 --> 01:42:20.290
Faculty (Olympus): Okay.

802
01:42:20.870 --> 01:42:34.660
Faculty (Olympus): So what it means is that, okay, the wayâ€¦ the couple of things that I want to show you here is that as Mâ€¦ as Sigma becomes larger and larger, okay, the density spreads out more and more.

803
01:42:34.770 --> 01:42:44.440
Faculty (Olympus): Which means that as sigma is large, these values, for example, if you look at theâ€¦ if you look at the value here, okay, at some distance fromâ€¦ from mu.

804
01:42:45.780 --> 01:42:53.499
Faculty (Olympus): Okay, this particular, so this is one version of Z, this is a second version of Z. Okay, I'm sorry, this is the first version, this is the second version.

805
01:42:54.030 --> 01:43:07.870
Faculty (Olympus): Okay, so this one, if Z had a sigma of this, then the values that Z can take around here isâ€¦ has a much lower probability than the values than

806
01:43:08.730 --> 01:43:19.150
Faculty (Olympus): then the values that the Z will take, values in this region, will have a lower probability with this kind of a random variable than with this kind of random variable.

807
01:43:20.220 --> 01:43:21.050
Faculty (Olympus): Okay.

808
01:43:21.640 --> 01:43:41.520
Faculty (Olympus): Sorry, the other way around. We'll have a lower probability with this kind of a random variable than with this kind of a random variable. What it means is thatâ€¦ so if youâ€¦ if the distribution is narrow around the mean, it means that most of the values of the random variable will be closer to the mean and not far away from the mean, okay? When you're doing Z minus mu.

809
01:43:41.950 --> 01:43:47.679
Faculty (Olympus): You're essentially moving this in the direction, okay? If this is positive, you're essentially moving it here.

810
01:43:47.920 --> 01:43:58.109
Faculty (Olympus): And if you're doing a scaling, you're essentially compressingâ€¦ you're essentially compressing theâ€¦ compressing the axis to make it like the unit knot. That's the viewâ€¦ that's the view to take.

811
01:43:59.980 --> 01:44:00.730
Faculty (Olympus): Okay.

812
01:44:00.840 --> 01:44:11.460
Faculty (Olympus): Yeah, so this is theâ€¦ this is exactly what I'm just saying. So thisâ€¦ this corresponds to, if you subtract the mean, it becomes a zero mean, you know, and if you scale it by sigma, it becomes a unit variance.

813
01:44:12.490 --> 01:44:20.479
Faculty (Olympus): This is something that, you know, we have said this in different forms before, so we'll have that. So this isâ€¦ first thing is to understand that this isâ€¦

814
01:44:20.810 --> 01:44:22.400
Faculty (Olympus): This is the density.

815
01:44:22.970 --> 01:44:28.599
Faculty (Olympus): And this, this density function is important because of the CLT.

816
01:44:29.850 --> 01:44:31.480
Faculty (Olympus): Makes this important.

817
01:44:32.940 --> 01:44:35.569
Faculty (Olympus): Okay, not just important, it's very important.

818
01:44:39.520 --> 01:44:40.200
Faculty (Olympus): Okay.

819
01:44:40.450 --> 01:44:55.810
Faculty (Olympus): So multivariate Gaussian has a nice structure, so the advantages of Gaussian are manyfold, okay? You might have been introduced to multivariate Gaussian, it has a nice structure, we'll worry about them later. And if you're looking at, you know, if you're doing some linear transformation of Gaussian random variables.

820
01:44:55.840 --> 01:45:03.360
Faculty (Olympus): You know, the results are also Gaussian random variables. That sort of keeps it in the family, if you will.

821
01:45:04.050 --> 01:45:14.909
Faculty (Olympus): Okay, and our uncorrelatedâ€¦ okay. So typically, zero correlation in general, zero correlation does not mean

822
01:45:15.630 --> 01:45:21.489
Faculty (Olympus): Not necessarily, meanâ€¦ Does not imply independence.

823
01:45:24.970 --> 01:45:30.780
Faculty (Olympus): Okay, this is true, independence implies zero correlation in general, okay, generally.

824
01:45:33.370 --> 01:45:36.409
Faculty (Olympus): Okay, zero correlation does not mean independence.

825
01:45:36.680 --> 01:45:39.330
Faculty (Olympus): But in the case of Gaussian.

826
01:45:40.110 --> 01:45:43.069
Faculty (Olympus): In the case of Gaussian, it actually means.

827
01:45:43.400 --> 01:45:52.190
Faculty (Olympus): Zero correlation means independence, okay? That can also be derived by looking at the expression and then separating out the density function, the densities.

828
01:45:52.770 --> 01:45:57.290
Faculty (Olympus): And the conditional expectation, that means if you're looking at X1 and X2,

829
01:45:57.640 --> 01:46:12.009
Faculty (Olympus): as a vector, if I tell you X2 is equal to X, okay, so if I want to find out what is the expectation of X given X2 is equal to small x, this will be a linear function of X and mu1.

830
01:46:13.300 --> 01:46:24.109
Faculty (Olympus): Okay? So things become easy to handle with Gaussian in many, many ways, and it is justified because of the central limit theorem. So that's sort of the beauty, and the centrality of

831
01:46:24.350 --> 01:46:29.880
Faculty (Olympus): of Gaussian to most of the discussion that we are going to be having in thisâ€¦ in the rest of this course.

832
01:46:30.990 --> 01:46:31.760
Faculty (Olympus): Okay.

833
01:46:32.050 --> 01:46:38.070
Faculty (Olympus): Yeah. So I'll give you one more estimation problem, and then maybe we'll stop, and stop for questions.

834
01:46:39.670 --> 01:46:55.870
Faculty (Olympus): Okay, so let's assumeâ€¦ let's take the following problem, okay? I guess with vibe coding, programming is probably not that big a deal anymore, but once up not very long ago, I mean, literally 5-6 years ago, this is a huge deal, okay? You get a program, and you want to debug it, especially when you have a large program.

835
01:46:56.180 --> 01:47:08.859
Faculty (Olympus): Okay, debugging means that you have toâ€¦ you have toâ€¦ you have to find out all the places where this program is going to make an error. I'm not talking ofâ€¦ we are talking about logical errors and not syntactic errors, okay?

836
01:47:09.440 --> 01:47:10.420
Faculty (Olympus): Now.

837
01:47:11.110 --> 01:47:14.099
Faculty (Olympus): So let's assume that you get a program.

838
01:47:14.420 --> 01:47:25.249
Faculty (Olympus): And itâ€¦ let's assume that it contains some number of bugs in it, okay? So let me call that number N, okay? So this is a random number, unknown.

839
01:47:26.260 --> 01:47:27.650
Faculty (Olympus): Okay, unknown.

840
01:47:28.440 --> 01:47:31.249
Faculty (Olympus): And we'll assume it is random.

841
01:47:33.540 --> 01:47:39.840
Faculty (Olympus): Depending on the coder, you know, or the coding team, there's some distribution associated with this N.

842
01:47:40.360 --> 01:47:43.310
Faculty (Olympus): Okay, some kind of a randomness associated with this N.

843
01:47:45.000 --> 01:47:53.490
Faculty (Olympus): Okay, now, one of the ways in which this used to be done was that, okay, there are N unknown bugs, okay? I'll reiterate.

844
01:47:54.330 --> 01:47:55.970
Faculty (Olympus): and unknown bugs.

845
01:47:58.500 --> 01:48:01.740
Faculty (Olympus): And then you deliberately introduce N1.

846
01:48:02.120 --> 01:48:05.159
Faculty (Olympus): And known and known bugs.

847
01:48:08.520 --> 01:48:13.459
Faculty (Olympus): Okay, so the typically way this was done was that there is a coding team.

848
01:48:13.560 --> 01:48:16.049
Faculty (Olympus): That wants to find out how many bucks there were.

849
01:48:16.470 --> 01:48:22.090
Faculty (Olympus): And that coding team, before it gets into production, will hand it over to a debugging and testing team.

850
01:48:22.530 --> 01:48:26.380
Faculty (Olympus): And before they hand out, they put these N known bugs.

851
01:48:27.550 --> 01:48:32.179
Faculty (Olympus): Okay, they know that these bugs are there, so that they can take it out later before it goes into production.

852
01:48:32.810 --> 01:48:36.300
Faculty (Olympus): And then they ask the debugging team to find out all the bugs there are.

853
01:48:37.340 --> 01:48:43.790
Faculty (Olympus): Okay? So what will happen typically is that the debugger debugging team.

854
01:48:45.810 --> 01:48:49.899
Faculty (Olympus): Will discover a total of let us say.

855
01:48:50.370 --> 01:48:51.660
Faculty (Olympus): M bugs.

856
01:48:54.350 --> 01:48:56.379
Faculty (Olympus): Okay, M would be.

857
01:48:56.490 --> 01:48:59.470
Faculty (Olympus): Some number, okay, M would be some number.

858
01:48:59.770 --> 01:49:02.039
Faculty (Olympus): Let's assume of this M.

859
01:49:02.290 --> 01:49:05.199
Faculty (Olympus): There are N1 from this set.

860
01:49:07.660 --> 01:49:12.460
Faculty (Olympus): Okay, and M minus 1 from this unknown set.

861
01:49:14.040 --> 01:49:26.109
Faculty (Olympus): Okay? So if they discover all the N1, if N1 is equal to small n, if the small N1 is equal to small n, then you can reasonably assume that they have probably found most of the bugs.

862
01:49:26.420 --> 01:49:29.170
Faculty (Olympus): If this number is small compared to this.

863
01:49:29.610 --> 01:49:36.790
Faculty (Olympus): Okay? Then I'll have to be a lot more worried that there are bugs that were not caught.

864
01:49:37.290 --> 01:49:42.469
Faculty (Olympus): Okay, so I have to be able to estimate the value of unknown bugs.

865
01:49:43.080 --> 01:49:52.890
Faculty (Olympus): Atâ€¦ by doing this insertion of N, and by the discovery of these N1 and M minus N1 bugs.

866
01:49:53.780 --> 01:49:59.389
Faculty (Olympus): Okay? So I'm trying toâ€¦ what I'm trying to do here is to guess how many bucks there are

867
01:49:59.790 --> 01:50:07.590
Faculty (Olympus): Before I gave it to the debug teams, or now I can go back and debug them all over again. Of those N, these many were caught.

868
01:50:08.020 --> 01:50:18.010
Faculty (Olympus): Okay? Of course, these will also be removed, okay? Then you go back, introduce these bugs all over again, keep doing this process till you're more and more confident that you've taken out all the bugs.

869
01:50:18.330 --> 01:50:23.169
Faculty (Olympus): Okay, so what I'm asking for is some kind of an estimation problem associated with this.

870
01:50:23.820 --> 01:50:25.430
Faculty (Olympus): Okay, any questions on this.

871
01:50:27.770 --> 01:50:30.459
Faculty (Olympus): Now, an identical problem.

872
01:50:30.780 --> 01:50:40.580
Faculty (Olympus): Identical problem is if I want to estimate the amount of fish in a lake, okay? There is Powai Lake right across the IIT campus. I want to estimate how many fish there are.

873
01:50:40.920 --> 01:50:48.360
Faculty (Olympus): What is the trick to do? I catch a small number of fish, let's say small N, the same problem, it's identical problem.

874
01:50:48.580 --> 01:50:50.929
Faculty (Olympus): Okay, I catch small end fish.

875
01:50:51.680 --> 01:50:53.100
Faculty (Olympus): Mark them.

876
01:50:53.210 --> 01:50:54.930
Faculty (Olympus): Put them back into the pond.

877
01:50:56.180 --> 01:51:00.449
Faculty (Olympus): Okay, then I go out after some time, I catch M fish.

878
01:51:00.710 --> 01:51:10.010
Faculty (Olympus): Out of these M, N1 are the fish that I had marked earlier. And from that, I can estimate the N. The problem is identical. The context is different.

879
01:51:11.220 --> 01:51:14.410
Faculty (Olympus): Okay, so here is that problem.

880
01:51:15.980 --> 01:51:20.259
Faculty (Olympus): Okay, there is another way of looking at this problem.

881
01:51:20.430 --> 01:51:26.220
Faculty (Olympus): Another way of looking at this problem is you have some n-dimensional object, some object.

882
01:51:26.680 --> 01:51:30.650
Faculty (Olympus): Okay, you want to be able to estimate its volume.

883
01:51:31.470 --> 01:51:48.440
Faculty (Olympus): You don't know. I mean, it's some object with a complex, you know, in someâ€¦ No, and this N is not necessarily that. I mean, these two do not have to be there. So, I want to be able to estimate the value ofâ€¦ sorry, the volume of some n-dimensional solid.

884
01:51:52.270 --> 01:51:58.600
Faculty (Olympus): One of the ways of doing that is to take this n-dimensional solid, embed it into an n-dimensional cube.

885
01:52:00.020 --> 01:52:08.930
Faculty (Olympus): And then throw random points into the cube, and find out if each of these random points is inside this object or outside this object. From that, you can estimate the number.

886
01:52:09.060 --> 01:52:18.070
Faculty (Olympus): So the same idea of doing some kind of an estimation is coming from a large number ofâ€¦ a large class of problems. Okay?

887
01:52:18.530 --> 01:52:27.229
Faculty (Olympus): Now, I think I probably am running out of time to get to the actual estimation. This we will start discussing in the next class.

888
01:52:28.130 --> 01:52:37.689
Faculty (Olympus): So I'm going to stop here and take any questions that anybody might have, okay? Any questions on anything that I've covered or in the previous lecture, I'll stay back and answer them.

889
01:52:38.640 --> 01:52:40.810
Faculty (Olympus): Abhijit Abhinit, sorry.

890
01:52:41.110 --> 01:52:41.950
Abhineet Bansal .: certain

891
01:52:42.420 --> 01:52:50.410
Abhineet Bansal .: The last issue that you discussed about estimation, can we have a practical problem on this? Or are we going to discuss that in the next lecture?

892
01:52:50.610 --> 01:52:56.290
Faculty (Olympus): I'm going to discuss the algorithms and the theory of it, and at the end of it, you will see a practical problem, correct?

893
01:52:56.740 --> 01:52:58.500
Abhineet Bansal .: Got it, sir. And in the hilarityâ€¦

894
01:52:58.500 --> 01:53:02.720
Faculty (Olympus): I mean, I'llâ€¦ the practical problem that I'll talk about will be given out as

895
01:53:02.830 --> 01:53:10.129
Faculty (Olympus): A self-learning exercise and not connected or anything. Yes, I'll give you that. Practical meaning not ultra practical.

896
01:53:10.240 --> 01:53:13.210
Faculty (Olympus): You know, practical, practical.

897
01:53:13.210 --> 01:53:13.770
Abhineet Bansal .: application.

898
01:53:13.770 --> 01:53:17.050
Faculty (Olympus): To the to this to to the point that you can do it. Yeah.

899
01:53:17.050 --> 01:53:27.649
Abhineet Bansal .: Got it, sir. And in the Hillary Clinton example, sir, you said we discussed that 85% was chances of Hillary and 15% was the other guy. My question was that even.

900
01:53:27.650 --> 01:53:31.009
Faculty (Olympus): You're not allowed to say the other guy, man. You have to pay suitable respects to the man, okay?

901
01:53:31.010 --> 01:53:31.980
Abhineet Bansal .: Hmm.

902
01:53:31.980 --> 01:53:33.449
Faculty (Olympus): You hard soon, okay, huh.

903
01:53:33.450 --> 01:53:44.680
Abhineet Bansal .: Not in theâ€¦ he's not in the call. Okay. So, sir, would it be the same way saying that even somebody is saying with a 99% confidence we cannot rely on his answer?

904
01:53:45.870 --> 01:53:46.260
Faculty (Olympus): Yeah.

905
01:53:46.260 --> 01:53:48.160
Abhineet Bansal .: Because he still left 1%.

906
01:53:48.160 --> 01:53:49.030
Faculty (Olympus): Yeah.

907
01:53:49.030 --> 01:53:49.730
Abhineet Bansal .: Option there.

908
01:53:49.730 --> 01:53:53.060
Faculty (Olympus): Similarly, correct, correct, except that you are more sure that you can't rely.

909
01:53:55.740 --> 01:54:07.620
Faculty (Olympus): 85 or 1999, so in one case, you're saying that I'm 85, there's a 15% chance, and the other saying you have 1% chance of the answer being right.

910
01:54:08.330 --> 01:54:09.580
Abhineet Bansal .: So if somebody says there's a 99â€¦

911
01:54:09.580 --> 01:54:10.350
Faculty (Olympus): 10% chance.

912
01:54:10.350 --> 01:54:13.229
Abhineet Bansal .: market will go up. I still have to fear about that.

913
01:54:13.230 --> 01:54:17.679
Faculty (Olympus): More likely that it is significantly more likely that it'll go up rather than go down, correct?

914
01:54:18.860 --> 01:54:25.810
Faculty (Olympus): See, there's no, I mean, there are no statistical guarantees there, okay? Because ultimately, you're testing out a prediction.

915
01:54:25.930 --> 01:54:36.440
Faculty (Olympus): From one event, just one sample after that. So whether the prediction was right or wrong, you don't know. You're only going to give credibility to the prediction based on past performance.

916
01:54:37.890 --> 01:54:38.480
Abhineet Bansal .: Got it, sir.

917
01:54:38.480 --> 01:54:50.629
Faculty (Olympus): Okay, exactly how to convert past predictions and the outcome that youâ€¦ that they were predicting, and then converting into some kind of a reputation score is a much more complex exercise.

918
01:54:52.170 --> 01:54:59.870
Faculty (Olympus): Okay, that's that's much more complex. So you have to be careful. I mean, ultimately you'll have some horsenski, you know, how much to trust somebody's number.

919
01:55:01.260 --> 01:55:02.050
Abhineet Bansal .: Autotune.

920
01:55:02.290 --> 01:55:04.030
Faculty (Olympus): Yeah, yeah, okay?

921
01:55:04.180 --> 01:55:05.120
Faculty (Olympus): Rahul.

922
01:55:05.830 --> 01:55:09.929
Rahul Shrikrishna Joshi .: Sir, in the previous slide where you'd calculated Z,

923
01:55:12.910 --> 01:55:17.730
Rahul Shrikrishna Joshi .: This one? Another one. Yeah, this one, yeah. What is the uppercase Z means exactly?

924
01:55:18.920 --> 01:55:20.679
Faculty (Olympus): This is a random variable.

925
01:55:20.790 --> 01:55:23.690
Faculty (Olympus): This is the value that the random variable can take.

926
01:55:24.190 --> 01:55:29.120
Faculty (Olympus): When I pick somebody, okay, that when I pick somebody to measure the height.

927
01:55:29.250 --> 01:55:31.860
Faculty (Olympus): What is the value that this height can take?

928
01:55:32.740 --> 01:55:36.799
Faculty (Olympus): What is the value that this height will take? That's a random, random quantity.

929
01:55:37.480 --> 01:55:40.690
Faculty (Olympus): Now I can ask, what is the probability of the height?

930
01:55:40.890 --> 01:55:45.839
Faculty (Olympus): Okay, is less than, let's say, 160 centimeters.

931
01:55:46.640 --> 01:55:48.160
Faculty (Olympus): This is your small set.

932
01:55:51.150 --> 01:55:51.810
Rahul Shrikrishna Joshi .: Okay.

933
01:55:51.810 --> 01:55:53.249
Faculty (Olympus): Before you measure.

934
01:55:53.370 --> 01:55:56.919
Faculty (Olympus): After you measure, you know the value. That's what is called a realization.

935
01:55:57.740 --> 01:55:58.780
Rahul Shrikrishna Joshi .: Okay, got it, yeah.

936
01:55:58.780 --> 01:55:59.990
Faculty (Olympus): Okay, yeah, yeah.

937
01:55:59.990 --> 01:56:00.660
Rahul Shrikrishna Joshi .: Thank you.

938
01:56:00.660 --> 01:56:02.040
Faculty (Olympus): Okay, Abhishek.

939
01:56:05.700 --> 01:56:09.629
Abhishek Raghuvanshi .: Yeah, Professor, so in that Hillary example,

940
01:56:09.630 --> 01:56:10.180
Faculty (Olympus): Hello?

941
01:56:10.480 --> 01:56:17.000
Abhishek Raghuvanshi .: The random variable, if it was a difference in the votes, would it have improved theâ€¦

942
01:56:17.000 --> 01:56:17.440
Faculty (Olympus): No.

943
01:56:17.440 --> 01:56:18.410
Abhishek Raghuvanshi .: confidence interval.

944
01:56:18.410 --> 01:56:28.220
Faculty (Olympus): The only thing that I would have said, okay, if you are looking at it, okay, see, this is a different kind of a question than what is going on here.

945
01:56:30.050 --> 01:56:35.700
Faculty (Olympus): Okay, here what is being asked is that X is the fraction of votes that Hillary is going to get.

946
01:56:35.810 --> 01:56:52.109
Faculty (Olympus): Okay? Y is the fraction of votes that this guy is going to get. What was the term used? The other guy is going to get. Okay? The only constraint, if you're talking about it in terms of fraction, you're saying that X plus Y is less than 1, and X comma Y is greater than or equal to 0.

947
01:56:52.740 --> 01:56:56.550
Faculty (Olympus): You're looking at a pair of random variables with that kind of a property.

948
01:56:57.520 --> 01:57:03.869
Faculty (Olympus): Okay, so all you are going to say in the second part is that if this is X and this is Y,

949
01:57:04.050 --> 01:57:11.170
Faculty (Olympus): Okay? You are going to give me distributions of where in this box, in fact, in this box.

950
01:57:11.610 --> 01:57:14.340
Faculty (Olympus): These 2 people are going to these 2 votes are going to lie.

951
01:57:15.400 --> 01:57:17.969
Faculty (Olympus): Wherein and the probability of this.

952
01:57:18.220 --> 01:57:30.260
Faculty (Olympus): theseâ€¦ the vote share, X and Y, lying inâ€¦ in that plane corresponding to X plus Y is equal to 1. X plus Y has to be less than 1, right? So, the X and Y together will be in this region.

953
01:57:30.630 --> 01:57:35.669
Faculty (Olympus): What is the probability it will be in this region? What is the probability? It's what people are trying to estimate.

954
01:57:36.050 --> 01:57:43.270
Faculty (Olympus): Okay? What each of these is trying to say. Okay, let me take this particular example, okay? Let me take this particular example.

955
01:57:43.790 --> 01:57:45.730
Faculty (Olympus): What it is saying is the following.

956
01:57:46.150 --> 01:57:47.260
Faculty (Olympus): Okay.

957
01:57:48.810 --> 01:57:49.790
Faculty (Olympus): That.

958
01:57:51.160 --> 01:57:57.270
Faculty (Olympus): If I takeâ€¦ assume that this is 38 to 42, assume that this is some 42 to 52.

959
01:57:58.230 --> 01:58:00.719
Faculty (Olympus): Okay? So assume that this is that box.

960
01:58:01.320 --> 01:58:17.599
Faculty (Olympus): That means X and Y together are between 42 and 52, and 38 and 48 forâ€¦ 38 and 42 for one, 42 to 52 for the other. The probability that X and Y together are in this box is 0.95. That's one way to think about it.

961
01:58:18.900 --> 01:58:19.590
Abhishek Raghuvanshi .: Okay.

962
01:58:19.590 --> 01:58:31.169
Faculty (Olympus): Okay? X and Y together are inside that box is 0.95. I mean, if you want to find out what the second-dimensionalâ€¦ I mean, what the three-dimensional picture is, then you have to give me the density of

963
01:58:31.480 --> 01:58:33.969
Faculty (Olympus): Of this in this three-dimensional space.

964
01:58:36.260 --> 01:58:36.970
Abhishek Raghuvanshi .: Okay.

965
01:58:36.970 --> 01:58:37.890
Faculty (Olympus): Okay, yeah.

966
01:58:39.130 --> 01:58:40.760
Faculty (Olympus): Anybody else have a question?

967
01:58:48.070 --> 01:58:48.990
Faculty (Olympus): Okay.

968
01:58:49.890 --> 01:58:51.280
Faculty (Olympus): Yeah, Gaurav.

969
01:58:51.600 --> 01:58:58.060
Gaurav Singh .: Yeah, soâ€¦ In, for example, in the bug example, or, fish exampleâ€¦

970
01:58:58.060 --> 01:58:59.159
Faculty (Olympus): In the what example?

971
01:58:59.370 --> 01:59:01.540
Gaurav Singh .: The bug, the buggingâ€¦

972
01:59:01.540 --> 01:59:02.510
Faculty (Olympus): Example, huh, huh, huh.

973
01:59:02.610 --> 01:59:09.480
Gaurav Singh .: Yeah. So, you said that if a debugging team has Picked up M Bucks.

974
01:59:09.810 --> 01:59:13.200
Gaurav Singh .: Out of that, that N one bucks.

975
01:59:13.520 --> 01:59:16.439
Gaurav Singh .: They found out of the known bugs.

976
01:59:16.470 --> 01:59:21.139
Gaurav Singh .: Right? So, M minus N1 will be unknown bugs.

977
01:59:21.140 --> 01:59:27.429
Gaurav Singh .: So this is a directly a ratio problem that, hey, there was, and

978
01:59:27.430 --> 01:59:43.910
Gaurav Singh .: known bugs we have kept there, and out of that, N1 known bugs debugging team has identified, so I will scale my unknown bugs also in the same ratio. So it's just a ratio problem, like, what is the, you know, ratio?

979
01:59:43.910 --> 01:59:44.360
Faculty (Olympus): that.

980
01:59:44.360 --> 01:59:48.849
Gaurav Singh .: Variable and probability, thing coming here.

981
01:59:48.850 --> 01:59:56.080
Faculty (Olympus): Right. So what do you have to. Okay, so let me. Let me throw the book at you. Okay. Just. Just bear with me.

982
01:59:56.490 --> 01:59:59.020
Faculty (Olympus): Okay, bear with me about.

983
01:59:59.350 --> 02:00:00.740
Faculty (Olympus): Why this?

984
02:00:01.470 --> 02:00:05.380
Faculty (Olympus): Why, what you said is not going to be a good idea.

985
02:00:05.850 --> 02:00:06.710
Faculty (Olympus): Okay.

986
02:00:08.050 --> 02:00:10.209
Faculty (Olympus): So the way I'm going to think about it is this.

987
02:00:11.790 --> 02:00:14.500
Faculty (Olympus): N, okay, is a random variable.

988
02:00:15.730 --> 02:00:19.380
Faculty (Olympus): N has, okay, what this means is N has a certain distribution.

989
02:00:20.240 --> 02:00:20.780
Gaurav Singh .: Yeah.

990
02:00:20.780 --> 02:00:30.020
Faculty (Olympus): Okay, so let me assume that N is because you're familiar with this. Let me assume that it is Poisson with some mean lambda.

991
02:00:32.040 --> 02:00:32.750
Faculty (Olympus): Okay?

992
02:00:33.400 --> 02:00:37.670
Faculty (Olympus): Nowâ€¦ M is the discovered bug.

993
02:00:39.060 --> 02:00:39.770
Gaurav Singh .: Yeah.

994
02:00:40.850 --> 02:00:41.600
Faculty (Olympus): Okay?

995
02:00:42.440 --> 02:00:44.550
Faculty (Olympus): What I'm going to have is M.

996
02:00:44.980 --> 02:00:46.470
Faculty (Olympus): Is also.

997
02:00:47.060 --> 02:00:47.970
Faculty (Olympus): Okay.

998
02:00:48.320 --> 02:00:49.560
Faculty (Olympus): Bison?

999
02:00:51.330 --> 02:00:52.230
Faculty (Olympus): Okay.

1000
02:00:54.370 --> 02:00:59.539
Faculty (Olympus): Don't worry if you don't fully understand what I'm trying to say, but I'll come to this, okay? And I'll explain a little bit more.

1001
02:00:59.640 --> 02:01:02.209
Faculty (Olympus): Let me assume that this is now.

1002
02:01:02.310 --> 02:01:09.220
Faculty (Olympus): a function lambda one of M, Smarted.

1003
02:01:13.390 --> 02:01:15.180
Faculty (Olympus): What I'm going to discover.

1004
02:01:15.950 --> 02:01:18.680
Faculty (Olympus): It's also a random quantity in general.

1005
02:01:18.930 --> 02:01:20.450
Faculty (Olympus): Think about it this way.

1006
02:01:20.910 --> 02:01:25.109
Faculty (Olympus): I don't know anything about N, so I have to have some belief, Kitna Hai.

1007
02:01:26.530 --> 02:01:30.049
Faculty (Olympus): For every possible value of N, I should have some belief.

1008
02:01:31.780 --> 02:01:32.800
Faculty (Olympus): Is that okay?

1009
02:01:33.000 --> 02:01:33.320
Gaurav Singh .: Yeah.

1010
02:01:33.320 --> 02:01:36.820
Faculty (Olympus): That's what now I'm trying to parse out what I'm trying to, what I wrote down there.

1011
02:01:37.180 --> 02:01:38.609
Faculty (Olympus): I have to have some belief.

1012
02:01:40.130 --> 02:01:42.950
Faculty (Olympus): That belief is captured in this poison.

1013
02:01:45.280 --> 02:01:47.140
Faculty (Olympus): Okay, with with rate lambda.

1014
02:01:47.480 --> 02:01:48.820
Faculty (Olympus): So I'm going to say.

1015
02:01:49.370 --> 02:01:58.439
Faculty (Olympus): The probability that Nâ€¦ okay, it is likely that N is equal to 0 is, E power minus lambda.

1016
02:01:59.720 --> 02:02:07.620
Faculty (Olympus): The probability that N is equal to 1 is E powerâ€¦ that's also E power minus lambda, right? Yeah, yeah.

1017
02:02:08.940 --> 02:02:11.019
Faculty (Olympus): No lambda e power minus lambda.

1018
02:02:13.500 --> 02:02:16.320
Faculty (Olympus): Okay, let's assume somehow I know lambda.

1019
02:02:16.660 --> 02:02:18.410
Faculty (Olympus): Based on my experience.

1020
02:02:18.720 --> 02:02:19.400
Gaurav Singh .: Yeah.

1021
02:02:19.950 --> 02:02:26.090
Faculty (Olympus): Okay, so now what happens is Iâ€¦ and I also know that if Sorry, this should be N.

1022
02:02:28.540 --> 02:02:32.840
Faculty (Olympus): Okay? That if Iâ€¦ the Devâ€¦ I also know something about the debugging team.

1023
02:02:33.500 --> 02:02:34.860
Faculty (Olympus): How good are they?

1024
02:02:36.370 --> 02:02:37.310
Faculty (Olympus): Okay.

1025
02:02:37.470 --> 02:02:42.849
Faculty (Olympus): So I'll have some notion ofâ€¦ Okitna Pakkarniye, Bobiranda mein.

1026
02:02:43.610 --> 02:02:44.160
Gaurav Singh .: Hmm.

1027
02:02:44.160 --> 02:02:53.639
Faculty (Olympus): And then, but I also know that, let me just make it even simpler. Let me not make it so complicated. Let me make it much simpler.

1028
02:02:57.010 --> 02:02:57.900
Faculty (Olympus): 8.

1029
02:03:00.140 --> 02:03:02.930
Faculty (Olympus): Let's assume this is Poisson.

1030
02:03:05.020 --> 02:03:10.320
Faculty (Olympus): With some lambda 1 multiplied by small n plus small n.

1031
02:03:12.420 --> 02:03:13.320
Faculty (Olympus): I'm not.

1032
02:03:14.470 --> 02:03:19.269
Faculty (Olympus): Just, you know, every bug is being caught with some probability. Roughly, that's what I'm trying to say.

1033
02:03:20.310 --> 02:03:20.880
Gaurav Singh .: Okay.

1034
02:03:20.880 --> 02:03:25.900
Faculty (Olympus): Okay. Again, you know, so this is, this is, you know, crudely, this is what I'm trying to do.

1035
02:03:27.820 --> 02:03:30.890
Faculty (Olympus): Nowâ€¦ What you are going to get.

1036
02:03:31.750 --> 02:03:34.719
Faculty (Olympus): Is I want to estimate N.

1037
02:03:34.970 --> 02:03:39.729
Gaurav Singh .: Sorry to interrupt you, sir. Capital N is the unknown.

1038
02:03:39.730 --> 02:03:41.090
Faculty (Olympus): No, correct, correct.

1039
02:03:41.090 --> 02:03:43.150
Gaurav Singh .: Correct, correct, correct.

1040
02:03:43.310 --> 02:03:44.630
Faculty (Olympus): Correct, correct.

1041
02:03:44.850 --> 02:03:48.270
Faculty (Olympus): Okay, what you are trying to do is to ask N.

1042
02:03:48.630 --> 02:03:58.909
Faculty (Olympus): given M is equal to whatever is the number that you got. I'm treating, in the first instance, in this formulation, the symbol here, this M corresponds to a random variable.

1043
02:03:59.020 --> 02:04:00.749
Faculty (Olympus): But I'm now going to askâ€¦

1044
02:04:01.560 --> 02:04:06.810
Faculty (Olympus): What is this? I've toldâ€¦ I mean, M is Jord Nikla, Uzkov is Marembalo.

1045
02:04:06.810 --> 02:04:07.810
Gaurav Singh .: Understood.

1046
02:04:07.810 --> 02:04:08.520
Faculty (Olympus): Okay.

1047
02:04:08.640 --> 02:04:15.909
Faculty (Olympus): Which I'm going to ask, give me the probability distribution of, or rather the PMF.

1048
02:04:16.240 --> 02:04:18.120
Faculty (Olympus): The conditional PMF of this.

1049
02:04:19.930 --> 02:04:20.990
Gaurav Singh .: Okay, okay.

1050
02:04:20.990 --> 02:04:26.480
Faculty (Olympus): Okay, see, if what you're doing is not unreasonable, But it is naive.

1051
02:04:27.420 --> 02:04:28.120
Gaurav Singh .: Hmm.

1052
02:04:28.120 --> 02:04:29.660
Faculty (Olympus): You're scaling up Nebula.

1053
02:04:30.050 --> 02:04:30.510
Gaurav Singh .: This.

1054
02:04:30.510 --> 02:04:32.550
Faculty (Olympus): It is not unreasonable, but it's naive.

1055
02:04:33.080 --> 02:04:34.190
Gaurav Singh .: Yes, nice.

1056
02:04:34.190 --> 02:04:36.110
Faculty (Olympus): It's a simple way of doing it.

1057
02:04:36.620 --> 02:04:37.220
Gaurav Singh .: and.

1058
02:04:37.220 --> 02:04:40.349
Faculty (Olympus): Okay, if I make some assumptions.

1059
02:04:41.050 --> 02:04:41.900
Gaurav Singh .: Correct.

1060
02:04:41.900 --> 02:04:47.180
Faculty (Olympus): You need to be able to justify.

1061
02:04:47.390 --> 02:04:48.090
Gaurav Singh .: Hmm.

1062
02:04:48.090 --> 02:04:57.680
Faculty (Olympus): And the other important thing is you can never say with 100% surety that N is equal to whatever is the scale quantity that you came up with. I can never say that.

1063
02:04:58.060 --> 02:04:58.830
Gaurav Singh .: Hmm.

1064
02:04:58.830 --> 02:05:10.110
Faculty (Olympus): Okay, so once, so now you go back to your, go back to that situation where you're going to say, I have so many bugs left.

1065
02:05:10.350 --> 02:05:13.939
Faculty (Olympus): Once you take out those bugs, how sure are you that it's a bug-free air?

1066
02:05:15.320 --> 02:05:16.030
Gaurav Singh .: Yeah.

1067
02:05:16.200 --> 02:05:17.310
Faculty (Olympus): You're not very sure.

1068
02:05:17.750 --> 02:05:18.210
Gaurav Singh .: Correct.

1069
02:05:18.210 --> 02:05:20.439
Faculty (Olympus): You cannot be sure, you should not be sure.

1070
02:05:20.440 --> 02:05:21.340
Gaurav Singh .: Hmm.

1071
02:05:21.340 --> 02:05:24.819
Faculty (Olympus): So now what you have to do, you have to go back and give me this.

1072
02:05:25.090 --> 02:05:29.650
Faculty (Olympus): A analysis with some background will tell you how sure are you that you're bug-free.

1073
02:05:30.150 --> 02:05:33.500
Gaurav Singh .: Understood, understood. What is the chance ofâ€¦

1074
02:05:33.500 --> 02:05:35.540
Faculty (Olympus): Correct. This isâ€¦

1075
02:05:35.540 --> 02:05:37.000
Gaurav Singh .: What is the percentage ofâ€¦ Yeah.

1076
02:05:37.000 --> 02:05:46.509
Faculty (Olympus): Yeah, what areâ€¦ how shouldâ€¦ I mean, just think about it this way. How sure am I that it is bug-free, after I've discovered, let's say, the other bugs?

1077
02:05:47.110 --> 02:05:47.810
Gaurav Singh .: Understood.

1078
02:05:48.030 --> 02:05:48.560
Gaurav Singh .: Understood.

1079
02:05:48.560 --> 02:05:49.440
Faculty (Olympus): Okay, yeah.

1080
02:05:51.070 --> 02:05:51.909
Gaurav Singh .: Thank you, Professor.

1081
02:05:51.910 --> 02:05:52.930
Faculty (Olympus): Yeah, sure, sure.

1082
02:05:53.080 --> 02:05:54.819
Faculty (Olympus): Any other questions, Sanket?

1083
02:05:55.080 --> 02:06:02.619
Sanketh Chiplunkar .: So yes, so in the same polling example, there were multiple polling agencies. Everybody went wrong. I'm sure you will not say that.

1084
02:06:02.620 --> 02:06:05.120
Faculty (Olympus): Somebody went wrong. How do you know they went wrong?

1085
02:06:05.120 --> 02:06:07.970
Sanketh Chiplunkar .: But what might be the reason thatâ€¦

1086
02:06:07.970 --> 02:06:12.920
Faculty (Olympus): That's exactly what I'm trying to tell you. They did notâ€¦ They did not go wrong.

1087
02:06:14.710 --> 02:06:20.140
Faculty (Olympus): Okay, that did not go wrong. The claim that New York Times said was that

1088
02:06:20.820 --> 02:06:25.489
Faculty (Olympus): X equal to 1 in this particular example, wherever that was.

1089
02:06:27.460 --> 02:06:28.270
Faculty (Olympus): Yeah.

1090
02:06:28.510 --> 02:06:31.290
Faculty (Olympus): All it said is that X is equal to 1.

1091
02:06:33.350 --> 02:06:38.780
Faculty (Olympus): has probability 0.85â€¦ sorry.

1092
02:06:41.160 --> 02:06:45.039
Faculty (Olympus): And x is equal to 0 has probability.

1093
02:06:46.630 --> 02:06:50.020
Faculty (Olympus): 0.15. This is all that New York Times said.

1094
02:06:50.610 --> 02:06:59.060
Faculty (Olympus): Yes. How did they base this? They based this on the claim that I said here. Each of these people, you know, in fact, what is hidden here.

1095
02:06:59.190 --> 02:07:06.250
Faculty (Olympus): Is that the actual value that they are saying is between 42 and 52 for this fellow.

1096
02:07:06.560 --> 02:07:19.129
Faculty (Olympus): For this fellow, it is saying it isâ€¦ this is also between 42 and 52. This is roughly between whatever, whatever the other numbers are. I mean, each of them has a different, you know, a different confidence interval and a band.

1097
02:07:21.150 --> 02:07:28.019
Faculty (Olympus): Okay, so it is, I just sort of made up those two numbers. I mean, that number is not brought out here, okay?

1098
02:07:29.860 --> 02:07:31.599
Faculty (Olympus): The number is not brought out here.

1099
02:07:32.030 --> 02:07:32.770
Sanketh Chiplunkar .: Yes, yes, yes.

1100
02:07:32.770 --> 02:07:39.630
Faculty (Olympus): Okay, yeah. So, you know, the actual number you're saying is in that range, actual values that they're going to get is in that range.

1101
02:07:39.910 --> 02:07:45.880
Faculty (Olympus): Okay, soâ€¦ Okay, any other questions?

1102
02:07:47.140 --> 02:07:54.560
Rahul Shrikrishna Joshi .: Sir, just one thing. In this type of a situation where the binary outcome is going to be there, either candidate A will win eventually, or B,

1103
02:07:54.700 --> 02:08:06.110
Rahul Shrikrishna Joshi .: Obviously, there is going to be some lag between the analysis time and actual polling time, right? So, obviously, there will be some variation going to happen, depending on the last-minute issues and all that, isn't it?

1104
02:08:06.110 --> 02:08:06.710
Faculty (Olympus): Tanya?

1105
02:08:07.680 --> 02:08:09.050
Faculty (Olympus): Okay, yeah, sure.

1106
02:08:09.890 --> 02:08:13.450
Faculty (Olympus): Sure. The idea here is not toâ€¦

1107
02:08:13.630 --> 02:08:25.930
Faculty (Olympus): not to look atâ€¦ I mean, the idea of the discussion is not to look at how valid the polls are. The idea is that assuming everything is perfect with respect to polling.

1108
02:08:26.160 --> 02:08:27.840
Faculty (Olympus): How do I interpret that?

1109
02:08:28.050 --> 02:08:28.830
Rahul Shrikrishna Joshi .: Oh, got it.

1110
02:08:28.830 --> 02:08:43.609
Faculty (Olympus): That's our goal is not, you know, I don't care, you know, what happened, you know. I'm looking at it from trying to draw statistics lessons from that, nothing more than that.

1111
02:08:43.610 --> 02:08:44.350
Rahul Shrikrishna Joshi .: Yeah, yeah, got it.

1112
02:08:44.350 --> 02:08:55.440
Faculty (Olympus): I'm not a pollster, I don't want to worry about it, and so on. So that's not the objective. I mean, 100 things can go wrong. I mean, there areâ€¦ there's huge criticism and critique that one can do about everything.

1113
02:08:55.870 --> 02:08:59.480
Faculty (Olympus): Okay, the, the, you're, I mean, we're focusing on something very simple.

1114
02:08:59.580 --> 02:09:03.300
Faculty (Olympus): How do I interpret what is being said? Assuming everything else is perfect.

1115
02:09:04.460 --> 02:09:05.150
Rahul Shrikrishna Joshi .: Yep.

1116
02:09:05.150 --> 02:09:06.320
Faculty (Olympus): Okay? Yeah.

1117
02:09:06.450 --> 02:09:10.099
Siddharth Digambar Kulkarni .: So, each of these agencies should have given a range, right? That's what you're.

1118
02:09:10.100 --> 02:09:21.199
Faculty (Olympus): No, they don't. See, the range is not pointed out here. I mean, the range comes about through what we call the confidence interval. I'll come back to this again.

1119
02:09:22.800 --> 02:09:24.289
Faculty (Olympus): I'll come back to this again.

1120
02:09:26.550 --> 02:09:27.450
Faculty (Olympus): Okay.

1121
02:09:28.180 --> 02:09:28.889
Faculty (Olympus): Got it.

1122
02:09:30.020 --> 02:09:31.379
Faculty (Olympus): Any other questions?

1123
02:09:34.660 --> 02:09:41.129
Naina Punjwani .: Sir, in this scenario, it could be that the votes have moved to the other two participants also, right? Because the.

1124
02:09:41.530 --> 02:09:48.769
Faculty (Olympus): A whole lot of things could have happened. These are people who are poor could also have lied.

1125
02:09:50.240 --> 02:09:50.810
Naina Punjwani .: Okay.

1126
02:09:50.810 --> 02:10:03.050
Faculty (Olympus): I mean, I'll reiterate, you know, the objective here is not to discuss the correctness of the polling process, the validity, etc. I just want to understand what is the statistical, I mean, how do I interpret this?

1127
02:10:03.500 --> 02:10:09.519
Faculty (Olympus): What is the correct way to think about it from the point of view of status? That's all that I'm trying to do.

1128
02:10:09.760 --> 02:10:10.530
Faculty (Olympus): The wholeâ€¦

1129
02:10:10.530 --> 02:10:11.130
Naina Punjwani .: Okay.

1130
02:10:11.550 --> 02:10:16.699
Faculty (Olympus): If you allow me a four-letter word, a whole lot of SHIT could have happened.

1131
02:10:17.990 --> 02:10:18.880
Faculty (Olympus): Okay.

1132
02:10:19.110 --> 02:10:21.160
Naina Punjwani .: No, because there are no actuals in.

1133
02:10:21.160 --> 02:10:40.960
Faculty (Olympus): Absolutely not, absolutely not. We don't know anything, right? I mean, we have to assume a certain amount of correctness, etc, etc, okay? So, certain amount of sophistication. See, there was a time, for example, when even India Today would report a poll by, you know, motorcycle, motorcycle, whatever.

1134
02:10:41.360 --> 02:10:47.499
Faculty (Olympus): Okay, they would ask 100 people and say that that is my whatever, that is my opinion. Wrong.

1135
02:10:48.010 --> 02:10:49.280
Naina Punjwani .: The sample size could also.

1136
02:10:49.280 --> 02:10:53.209
Faculty (Olympus): Yeah, yeah, yeah. The sample itself is horribly wrong.

1137
02:10:53.800 --> 02:10:56.750
Faculty (Olympus): I mean, I'm talking of, you know, whatever, 30, 40 years ago.

1138
02:10:57.280 --> 02:11:10.680
Faculty (Olympus): Things have evolved in India also substantially, but in India it's much harder to predict because our variances are large. Our variations in the population are significantly higher. So it's not just a fault of the polling agencies. It's a lot harder to do here.

1139
02:11:11.860 --> 02:11:22.699
Faculty (Olympus): In many of these, for example, the way in which this is done is in most of the counties, the vote share has remained roughly the same for a long, long time. It's only a small number of counties whereâ€¦ which determine

1140
02:11:22.810 --> 02:11:24.910
Faculty (Olympus): How the how the election flips.

1141
02:11:25.530 --> 02:11:28.530
Faculty (Olympus): Okay, India Basani over there. So both must kill it.

1142
02:11:30.560 --> 02:11:48.469
Faculty (Olympus): Anyway. Yeah, so let's not get into the correctness of the polling process and all. Just focus on the statistical lessons and the statistical interpretation of these charts using statistics. That's all. Don't worry, don't go back and forth on anything else, because that's just going to clutter the whole thing up.

1143
02:11:51.670 --> 02:11:54.089
Faculty (Olympus): Okay, any other questions?

1144
02:11:59.740 --> 02:12:00.820
Faculty (Olympus): All right.

1145
02:12:01.450 --> 02:12:03.220
Faculty (Olympus): Okay, folks, thank you very much.

1146
02:12:05.070 --> 02:12:06.160
Gaurav Singh .: Thank you, Professor.

1147
02:12:06.160 --> 02:12:07.110
Faculty (Olympus): Thank you.

1148
02:12:07.110 --> 02:12:08.149
Charles Ravi Kiran Mutsu .: Thank you, Rupa.

1149
02:12:08.150 --> 02:12:08.860
Faculty (Olympus): thinkingâ€¦

1150
02:12:08.860 --> 02:12:09.840
Satish Narayan Dwivedi .: Thank you, Professor.

1151
02:12:09.840 --> 02:12:10.999
vinay kaisar: Thank you, Professor.

1152
02:12:11.120 --> 02:12:11.959
Amlan Sarkar .: Thank you, sir.

1153
02:12:11.960 --> 02:12:12.860
Vidya Gavel .: Thank you.

1154
02:12:15.680 --> 02:12:16.209
Piyush Rustagi .: Okay, okay.

1155
02:12:16.210 --> 02:12:16.620
Faculty (Olympus): Thank you.

1156
02:12:16.620 --> 02:12:17.310
Pradeep Kumar .: Thank you.

1157
02:12:18.270 --> 02:12:19.060
Dinesh Devnath Yadav .: Thank you, sir.

