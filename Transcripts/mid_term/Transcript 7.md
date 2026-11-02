WEBVTT

1
00:04:55.460 --> 00:05:01.770
Faculty (Olympus): Rupal, can you please confirm if you can see my screen and also hear me properly?

2
00:05:01.770 --> 00:05:03.010
Rupal Makhijani: Yes, sir, yes.

3
00:05:03.010 --> 00:05:04.719
Faculty (Olympus): Okay, alright, okay, thank you.

4
00:05:05.320 --> 00:05:06.959
Faculty (Olympus): We'll start in a few minutes.

5
00:05:47.590 --> 00:05:53.060
Faculty (Olympus): In the meantime, yeah, if there are any questions, please feel free to ask them around.

6
00:07:01.580 --> 00:07:02.290
Matin Khan .: Amazing.

7
00:07:22.750 --> 00:07:23.540
Anita Menon .: Professor.

8
00:07:23.790 --> 00:07:32.780
Anita Menon .: After we, submit our assignments, will we get our corrected or checked copies back, so that we know where we did wrong, or what our assumptions went wrong?

9
00:07:32.780 --> 00:07:49.840
Faculty (Olympus): Yeah, yeah, yeah. They'll be corrected, and yeah, you will see in the scanned copies, I think there'll be some sort of annotation there to, exactly tell you, what the mistakes were. Also, there will be, solutions provided,

10
00:07:50.090 --> 00:07:55.439
Faculty (Olympus): As well, at least reference solutions provided for all the questions, that were there in the homework.

11
00:07:56.470 --> 00:07:57.200
Anita Menon .: Thank you.

12
00:10:33.370 --> 00:10:43.769
Faculty (Olympus): Okay, let's begin. So the plan, for today is I will do a couple of quick, examples on,

13
00:10:44.040 --> 00:10:58.920
Faculty (Olympus): discrete random variables, and PMF justâ€¦ just to maybe revise some things that we did last time, and then we'll move to the case of continuous random variables, okay? So, last time, we saw the notion of

14
00:10:59.300 --> 00:11:02.460
Faculty (Olympus): discreteâ€¦ random variables.

15
00:11:02.780 --> 00:11:09.880
Faculty (Olympus): Right, and we saw that these discrete random variables essentially have support which is countable.

16
00:11:11.500 --> 00:11:20.690
Faculty (Olympus): Right? And they can be described via the notion of a probability mass function, which essentially tells me

17
00:11:20.910 --> 00:11:23.370
Faculty (Olympus): What the probability

18
00:11:23.650 --> 00:11:37.599
Faculty (Olympus): of X taking each of these values in the support is, right? So ifâ€¦ for every value of k which is in the support, it tells me exactly what the probability corresponding

19
00:11:37.710 --> 00:11:40.069
Faculty (Olympus): To that value isâ€¦

20
00:11:40.250 --> 00:11:59.610
Faculty (Olympus): Right? So let's look at an example, and then we also saw a bunch of examples of common discrete random variables. We saw that you can move from the probability mass function to the CDF and back, right? The CDF of any such discrete random variable will usually look somethingâ€¦

21
00:11:59.760 --> 00:12:17.010
Faculty (Olympus): like this. So CDF corresponds to the probability of X being less than equal to X, so it's a function from the reals to 0â€¦ to the interval 0, 1. So the CDF for any such discrete random variable will essentially look

22
00:12:17.080 --> 00:12:22.539
Faculty (Olympus): Usually something like this. It'll be maybe zero till some point, then there'll be a jump.

23
00:12:22.730 --> 00:12:26.910
Faculty (Olympus): Then maybe it'll remain at that point for some time. Again, a jump.

24
00:12:26.970 --> 00:12:41.599
Faculty (Olympus): And something like this, right? It'll look something like this, and finally it'll converge to 1, and the size of the jumps exactly tell usâ€¦ so, for example, if there was a jump at this position XI, then this tells me the probability

25
00:12:41.600 --> 00:12:51.269
Faculty (Olympus): of X taking the value Xi. The size of the jump, essentially, corresponds to the probability, or the value of the PMF at that point.

26
00:12:51.700 --> 00:12:52.400
Faculty (Olympus): Right?

27
00:12:52.720 --> 00:12:59.159
Faculty (Olympus): Okay, so let's, let's consider an example.

28
00:12:59.600 --> 00:13:06.440
Faculty (Olympus): So, let's say we have, an election coming up, Okay, there is an electionâ€¦

29
00:13:06.650 --> 00:13:09.740
Faculty (Olympus): And let's say there are just two candidates.

30
00:13:12.480 --> 00:13:16.029
Faculty (Olympus): Mitsâ€¦ A and B.

31
00:13:16.240 --> 00:13:26.590
Faculty (Olympus): And suppose, the, underlying population is such that there is 60%

32
00:13:26.940 --> 00:13:32.329
Faculty (Olympus): support. So, 60% of the population supports A, 40%

33
00:13:32.730 --> 00:13:50.799
Faculty (Olympus): supports B, okay? Let's say this is the ground truth. Of course, no one knows this beforehand, before the election. And let's say there is a polling company. So the way these polls work, these are regular polls that happen before any election, right? The way they work is that a polling company will sample

34
00:13:51.350 --> 00:13:54.170
Faculty (Olympus): Some subset of the population.

35
00:13:55.660 --> 00:14:07.860
Faculty (Olympus): And they will ask them who they support, or they will gather their voting preferences. And, let's say, amongst this, subset, let's say X,

36
00:14:08.020 --> 00:14:12.000
Faculty (Olympus): Is the numberâ€¦ that support A.

37
00:14:14.270 --> 00:14:14.950
Faculty (Olympus): Okay.

38
00:14:15.150 --> 00:14:17.960
Faculty (Olympus): So let's say the subset sizeâ€¦

39
00:14:19.560 --> 00:14:25.080
Faculty (Olympus): the subset of population that is, pooled, let's call that N.

40
00:14:25.370 --> 00:14:35.670
Faculty (Olympus): Okay, so X is, like, theâ€¦ amongst the N, how many support, A. And, we willâ€¦ the poll, just choosesâ€¦

41
00:14:36.260 --> 00:14:45.619
Faculty (Olympus): the majorityâ€¦ Opinionâ€¦ Or the majority candidate, As the predicted winner.

42
00:14:45.850 --> 00:14:46.570
Faculty (Olympus): Right?

43
00:14:47.780 --> 00:14:56.959
Faculty (Olympus): This is all actually quite close to how things are, are actually done in practice as well.

44
00:14:56.990 --> 00:15:07.899
Faculty (Olympus): So, suppose, you know, you have someâ€¦ like I said, 60% is the underlying, population, so one way of thinking about it might be.

45
00:15:08.060 --> 00:15:21.229
Faculty (Olympus): that, let's say N is 5, so you are polling 5 people, right? And, each person, we can think of them as, supporting, or each,

46
00:15:22.090 --> 00:15:23.329
Faculty (Olympus): Let me write this.

47
00:15:23.710 --> 00:15:33.900
Faculty (Olympus): If I think ofâ€¦ Soâ€¦ Eachâ€¦ Randomly selected individual.

48
00:15:34.600 --> 00:15:43.500
Faculty (Olympus): Let's seeâ€¦ Supportsâ€¦ Candidateâ€¦ E.

49
00:15:43.800 --> 00:15:48.830
Faculty (Olympus): with probability Pâ€¦ equals 0.6.

50
00:15:48.940 --> 00:15:55.340
Faculty (Olympus): Right? 60% of the population we, we've assumed, supports

51
00:15:55.520 --> 00:16:10.109
Faculty (Olympus): candidate A. So if you select randomlyâ€¦ select one such individual randomly, the probability or the chance that they support Candidate A is essentially 0.6, right? So now I am randomly selecting 5 people.

52
00:16:10.280 --> 00:16:29.579
Faculty (Olympus): Right? And each of them, we're assuming that for each of them, the probability that they support candidate A is 0.6, the probability that they support candidate B is 0.4, and the decision is independent for each of these guys, right? And we want to find, okay, what is the probability

53
00:16:29.610 --> 00:16:33.370
Faculty (Olympus): That the poolâ€¦ predicts incorrectly.

54
00:16:36.010 --> 00:16:38.280
Faculty (Olympus): incorrectly predicts.

55
00:16:38.580 --> 00:16:39.400
Faculty (Olympus): Right?

56
00:16:39.650 --> 00:16:51.249
Faculty (Olympus): Now, the true winner, of course, on election day is going to be Candidate A. Right? When will the poll predict incorrectly? The poll will predict incorrectly if amongst the 5 people

57
00:16:51.500 --> 00:16:59.770
Faculty (Olympus): it happened by chance that the number that support A is not the majority, right? Which means that

58
00:17:00.160 --> 00:17:05.190
Faculty (Olympus): the number that supports A, which is X, is less than equal to 2.

59
00:17:05.510 --> 00:17:10.510
Faculty (Olympus): Right? If that happens, then the poll is going to predict candidate B as the winner.

60
00:17:10.950 --> 00:17:11.780
Faculty (Olympus): Right?

61
00:17:12.060 --> 00:17:22.659
Faculty (Olympus): And, then it is going to incorrectly predict. Now, there is, of course, some chance that this is going to happen, because we are not going and polling every single individual in the population, we are selecting just 5 people

62
00:17:22.670 --> 00:17:35.309
Faculty (Olympus): Randomly, and each of them is, has some likelihood of supporting candidate A, some likelihood of supporting candidate B. We are asking what is the probability that X is less than equal to 2.

63
00:17:35.750 --> 00:17:40.909
Faculty (Olympus): Right? So firstly, think about what kind of a random variable is X.

64
00:17:41.360 --> 00:17:53.819
Faculty (Olympus): Right? If you have N, people who we are polling, each person isâ€¦ has probability P of supporting candidate A. Right?

65
00:17:54.850 --> 00:17:55.420
Gaurav Singh .: I don't know.

66
00:17:55.420 --> 00:18:04.370
Faculty (Olympus): what would X, look like, right? So, you can think of X as essentiallyâ€¦ Like a sum.

67
00:18:05.010 --> 00:18:09.859
Faculty (Olympus): over the 5 candidates, or over the n candidates, And,

68
00:18:10.900 --> 00:18:23.509
Faculty (Olympus): youâ€¦ soâ€¦ sorry, not the end candidates, the N people who you are polling, and you get a 1 if, the Ayeth individual

69
00:18:23.700 --> 00:18:27.939
Faculty (Olympus): supports A, and you get a 0 otherwise.

70
00:18:28.190 --> 00:18:30.690
Faculty (Olympus): Right? So it's like a sum of nâ€¦

71
00:18:30.890 --> 00:18:46.490
Faculty (Olympus): indicator random variables, or a sum of n Bernoulli random variables. So, you can think of this as a binomial random variable, where you are doing n experiments, and the success of each experiment is P, and you're asking how many

72
00:18:46.610 --> 00:18:50.719
Faculty (Olympus): successes did you actually get? So we are mapping the notion of experiment

73
00:18:51.050 --> 00:18:57.510
Faculty (Olympus): To, essentially, the number of people who are getting sampled, and then every person

74
00:18:57.750 --> 00:19:04.820
Faculty (Olympus): when they support A, we are mapping that to being a success, then X essentially becomes the number of successes that you see

75
00:19:04.930 --> 00:19:16.599
Faculty (Olympus): in N experiments, right? So it's going to be a binomial random variable, and we are essentiallyâ€¦ what is this quantity? This is essentially the CDF of X evaluated at point 2.

76
00:19:16.910 --> 00:19:22.549
Faculty (Olympus): Right? And we can evaluate this explicitly, so this probability that X is less than or equal to 2

77
00:19:22.960 --> 00:19:29.279
Faculty (Olympus): It's going to beâ€¦ You are going to sum over all values that X can take.

78
00:19:29.380 --> 00:19:40.019
Faculty (Olympus): from 0 to 2, the probability that X is equal to K. Now, what is the probability of X equal to K for a binomial random variable? It is n choose k

79
00:19:40.720 --> 00:19:45.739
Faculty (Olympus): P to the K, 1 minus P to the power n minus k.

80
00:19:45.910 --> 00:19:49.549
Faculty (Olympus): This goes from k equals 0 to 2, right?

81
00:19:49.730 --> 00:19:52.490
Faculty (Olympus): N here is 5.

82
00:19:52.620 --> 00:20:08.190
Faculty (Olympus): P here is 0.6. So we can plug it into this formula, we'll get some number, it turns out this number is going to be roughly 0.3 something, okay? If you compute this for this particular, numbers, this is what you're going to get.

83
00:20:08.670 --> 00:20:20.070
Faculty (Olympus): So what this is saying is that if you poll 5 people, okay, there is almost 1 third chance that the poll will actually incorrectly predict, candidate B

84
00:20:20.180 --> 00:20:21.319
Faculty (Olympus): To be the winner.

85
00:20:21.470 --> 00:20:34.650
Faculty (Olympus): Right? Again, this is maybe not surprising. We are polling too few people, so there is a big enough chance that you actuallyâ€¦ the majority turns out to be the losing candidate. Suppose

86
00:20:34.850 --> 00:20:42.250
Faculty (Olympus): If the solution for that, of course, is to poll more people. So, suppose we increase this. See, suppose we go to n equals 20.

87
00:20:42.370 --> 00:20:48.830
Faculty (Olympus): And now, the probability that the poll predicts incorrectly is the probability that the number of candidates

88
00:20:48.960 --> 00:20:56.629
Faculty (Olympus): or sorry, the number of people who supportâ€¦ the number of sampled people who support candidate A is less than equal to 10.

89
00:20:56.940 --> 00:20:57.710
Faculty (Olympus): Right?

90
00:20:57.960 --> 00:21:02.370
Faculty (Olympus): If that happens, then again, you mightâ€¦ you will predict, incorrectly.

91
00:21:03.210 --> 00:21:09.970
Faculty (Olympus): one can, again, exactly do the same calculation, right? Now, all you're doing is you're going from k equals 0 to

92
00:21:10.190 --> 00:21:12.930
Faculty (Olympus): 10, and now you are doingâ€¦

93
00:21:12.930 --> 00:21:18.250
Rahul Joshi .: Professor White10, it should beâ€¦ 60% of 20, right? Which is 12.

94
00:21:18.250 --> 00:21:29.929
Faculty (Olympus): No, 60% is not something we are aware of, right? The polling company, all it is doing is that it is looking at the majority winner, and they are selecting that to be the winner.

95
00:21:30.110 --> 00:21:31.360
Faculty (Olympus): Whoever is in majority.

96
00:21:31.360 --> 00:21:33.370
Siddharth Digambar Kulkarni .: But 10 is also a tie, right?

97
00:21:33.440 --> 00:21:35.930
Faculty (Olympus): 10 is a tie, sure, yeah, yeah, so maybe, okay.

98
00:21:35.930 --> 00:21:37.379
Siddharth Digambar Kulkarni .: And 11 is rented.

99
00:21:37.380 --> 00:21:50.820
Faculty (Olympus): Sure, so let's maybeâ€¦ at a time, maybe the polling company doesn't make a judgment at all, but yeah, sure, we canâ€¦ or we can just keep this as N equals 21, and

100
00:21:51.190 --> 00:21:56.520
Faculty (Olympus): If X is less than equal to 10, then you definitely lose, right?

101
00:21:57.360 --> 00:21:58.190
Faculty (Olympus): That's aâ€¦

102
00:21:58.190 --> 00:22:01.409
Lad Prachikumari Vijaykumar .: Sir, quickly, please explain Part A.

103
00:22:02.250 --> 00:22:06.749
Faculty (Olympus): Part A. Okay, so, yeah, so what we are saying is we are essentially polling

104
00:22:06.880 --> 00:22:13.580
Faculty (Olympus): people, we're pulling some subset of people, and every person has some probability of

105
00:22:13.990 --> 00:22:19.969
Faculty (Olympus): selecting candidate A, or supporting candidate A.

106
00:22:20.170 --> 00:22:33.979
Faculty (Olympus): And the poll, essentially, is going to look at the majority of the opinion that is held across the sampled people, and whoever has the majority opinion, they are going to go ahead with that as the predicted winner.

107
00:22:34.110 --> 00:22:38.409
Faculty (Olympus): So we are asking what is the probability that the poll incorrectly predicts

108
00:22:38.530 --> 00:22:47.840
Faculty (Olympus): candidate B to be the winner, which means that the number of people who support candidate A is less than half of the number of people who were actually polled.

109
00:22:48.080 --> 00:22:50.600
Faculty (Olympus): Right? There is some probability of that happening.

110
00:22:50.770 --> 00:22:59.119
Faculty (Olympus): It turns out that this X is a binomial random variable, so this is just finding out the CDF of that binomial random variable at a certain point.

111
00:22:59.470 --> 00:23:06.160
Faculty (Olympus): So now we areâ€¦ we got that for n equals 5, that value is roughly 0.3, right?

112
00:23:06.490 --> 00:23:15.790
Faculty (Olympus): So, the solution to that is you poll more people. Now, if you poll, for example, 21 people instead of 5 people, your probability becomes

113
00:23:16.250 --> 00:23:22.029
Faculty (Olympus): X, or the number of people being less, thatâ€¦ who support, who turn out to support

114
00:23:22.130 --> 00:23:27.169
Faculty (Olympus): or the number of sampled people who turn out to support candidate A being less than equal to 10,

115
00:23:27.340 --> 00:23:39.089
Faculty (Olympus): So again, we canâ€¦ we can compute that quantity. All that is changing is this N is now going to become 21, so it's going to be 21 choose k, 0.6 to the power k.

116
00:23:39.310 --> 00:23:44.619
Faculty (Olympus): 1 minus B, which is 1 minus 0.6, 0.4,

117
00:23:44.790 --> 00:23:47.040
Faculty (Olympus): to the power 21 minus k.

118
00:23:47.970 --> 00:23:53.739
Faculty (Olympus): So again, you're going to have, some calculation. If you do this calculation, this

119
00:23:53.950 --> 00:24:10.169
Faculty (Olympus): number will roughly turn out to be around, I think.25, maybe, something like that. Okay, so it is going to go down. If you sample even more people, so if you go to, let's say 100 folks, andâ€¦ or, okay, just to be precise, maybe let's do 100 and.

120
00:24:10.170 --> 00:24:14.430
Siddharth Digambar Kulkarni .: Even, even, even is, even a tie is not the right result, right?

121
00:24:14.620 --> 00:24:15.319
Siddharth Digambar Kulkarni .: You wannaâ€¦

122
00:24:15.320 --> 00:24:21.719
Faculty (Olympus): Yeah, so we are taking, we are notâ€¦ we are looking at N being odd, so you'll never have a tie.

123
00:24:22.620 --> 00:24:24.169
Siddharth Digambar Kulkarni .: Even if it is evenâ€¦

124
00:24:24.170 --> 00:24:31.879
Faculty (Olympus): Even if it was a tie, so then it depends on how the polling company decides, right? What happens when they get a tie.

125
00:24:33.180 --> 00:24:35.990
Siddharth Digambar Kulkarni .: It is not the right result, right? Tie is not the right result.

126
00:24:35.990 --> 00:24:42.229
Faculty (Olympus): It's not a right result, yeah. So maybe the predictionâ€¦ yeah, it depends what we count as an error, right? Maybe ifâ€¦

127
00:24:42.410 --> 00:24:54.060
Faculty (Olympus): If it is a tie, and we areâ€¦ we just don't comment, thenâ€¦ then we are not really in error. But maybe the polling company then does not make anyâ€¦ any prediction at all.

128
00:24:54.400 --> 00:25:03.500
Faculty (Olympus): Okay? But it depends, yeah, it depends on what event we are looking at. So again, for example, if you poll 101 people, then the probability of

129
00:25:03.690 --> 00:25:16.460
Faculty (Olympus): you predicting incorrectly is that the number of sampled folks who support candidate A is less than equal to 50. You do the same calculation, this roughly becomes around .03.

130
00:25:16.700 --> 00:25:27.529
Faculty (Olympus): Okay, so now, with sampling 100 folks, your probability of making an incorrect judgment is already down to, about 3%.

131
00:25:27.630 --> 00:25:42.799
Faculty (Olympus): Okay, so essentially, this gives you a handle on how to select the sampling size, right? This is one of the key questions in polling or sampling. How many people should I actually sample to get a reasonable,

132
00:25:43.100 --> 00:25:47.269
Faculty (Olympus): Reasonable probability of correct prediction.

133
00:25:47.470 --> 00:25:59.920
Faculty (Olympus): And, this is, I mean, this is, of course, simplistic, but this is the kind of tool that you would use to, bound your probability of making incorrect judgments or incorrect predictions.

134
00:26:00.870 --> 00:26:13.949
Faculty (Olympus): Okay, so yeah, thisâ€¦ all of this is just based on a binomial distribution, which is a discrete, random variable. It has its own PMF, it has its own CDF, all of these events.

135
00:26:13.970 --> 00:26:22.090
Faculty (Olympus): in fact, are just the CDF values evaluated at specific points, right? This is the CDF of a binomial

136
00:26:22.250 --> 00:26:27.739
Faculty (Olympus): 101.6 random variable evaluated at the point 50.

137
00:26:27.990 --> 00:26:43.030
Faculty (Olympus): this is the binomial of, or the CDF of value of a binomial 21,6 evaluated at x equals 10, right? So the CDF just immediately, I mean, plays,

138
00:26:43.270 --> 00:26:48.189
Faculty (Olympus): critical role in computing these quantities. It is, in fact, the right quantity to look at.

139
00:26:48.820 --> 00:26:56.770
Faculty (Olympus): Okay, let meâ€¦ let me take a couple of quick questions, and thenâ€¦ then I'll, move on.

140
00:26:57.940 --> 00:27:03.029
Faculty (Olympus): Ohâ€¦ Okay, Gaurav?

141
00:27:04.040 --> 00:27:08.719
Gaurav Singh .: Yeah, professors, like, when you were taking n equals to even numbers,

142
00:27:09.160 --> 00:27:18.339
Gaurav Singh .: for example, 20, then X less than equals to 9 was a good, I mean, right estimation of incorrectlyâ€¦ I mean.

143
00:27:18.490 --> 00:27:22.850
Gaurav Singh .: choosing the sample which will not make A to win, right?

144
00:27:22.850 --> 00:27:29.690
Faculty (Olympus): Yeah, yeah, so, I mean, I think it depends on how we define error. If we say that, you know.

145
00:27:29.800 --> 00:27:44.740
Faculty (Olympus): unless you predict A to be the right answer, meaning even if you tell me that I don't know if I consider that as an unacceptable outcome, then you will have to include X less than equal to 10 also in that

146
00:27:44.910 --> 00:27:47.550
Faculty (Olympus): But if you are only worried about

147
00:27:47.680 --> 00:27:51.539
Faculty (Olympus): incorrectly predicting, meaning you are okay with saying, I don't know.

148
00:27:51.760 --> 00:28:02.109
Faculty (Olympus): then you're right, X less than equal to 9 would have been the right choice for an error. So it depends on what I define as the event that Iâ€¦ whose probability I'm actually computing.

149
00:28:03.240 --> 00:28:10.649
Gaurav Singh .: But ifâ€¦ even ifâ€¦ if I chose, in case of N equals to 20, X less than equals to 10.

150
00:28:10.650 --> 00:28:11.190
Faculty (Olympus): Yo?

151
00:28:11.530 --> 00:28:13.879
Gaurav Singh .: Because my,

152
00:28:14.800 --> 00:28:25.039
Gaurav Singh .: A's probability itself is 0.6, right? So, including that 10 also will be giving me favorable outcomes.

153
00:28:25.040 --> 00:28:37.339
Faculty (Olympus): No, no, but I mean, the polling company does not know that, that 60% of the people areâ€¦ no one knows, right? This is just the underlying population, how it is going to behave on election day.

154
00:28:37.680 --> 00:28:46.720
Faculty (Olympus): The polling company, all it is doing is, it is going to look at the majority winner, meaning whoever has more votes, and they are going to predict that as the winner.

155
00:28:47.710 --> 00:28:54.889
Gaurav Singh .: But when we say 0.6 or 0.4, that means polling companies have some kind of hint about the probability, right?

156
00:28:54.890 --> 00:28:55.709
Faculty (Olympus): No, no, this isâ€¦

157
00:28:55.710 --> 00:28:56.340
Gaurav Singh .: 18.6.

158
00:28:56.340 --> 00:29:01.660
Faculty (Olympus): Yeah, yeah, yeah. So, I mean, this is the probability ofâ€¦ we are just computing the probability ofâ€¦

159
00:29:01.800 --> 00:29:18.800
Faculty (Olympus): the polling company making an error. You're right that, you know, how will I actually use this? If you're asking me, how will I actually use this? Because I don't know. Yeah, yeah, yeah. So then, then it's alsoâ€¦ it's like a combination of an estimation problem with

160
00:29:18.890 --> 00:29:36.059
Faculty (Olympus): such computations. We will probablyâ€¦ I don't know, yeah, whether we'll get to such things, but you have a fair point. I mean, how do I actually even compute this quantity? If I was deciding my sampling size based on this formula, how would I actually do that?

161
00:29:36.060 --> 00:29:37.770
Gaurav Singh .: occupied, who don't know theâ€¦

162
00:29:37.770 --> 00:29:38.499
Faculty (Olympus): If I don't know.

163
00:29:38.650 --> 00:29:39.240
Gaurav Singh .: Huh.

164
00:29:39.240 --> 00:29:51.989
Faculty (Olympus): I agree. So, I mean, usually you are right, what the polling company will do is probably then use some kind of estimation, meaning actually then try and sample some people, some population, try and get an estimate of what

165
00:29:52.180 --> 00:30:00.140
Faculty (Olympus): this quantity is come up with confidence intervals, and so on. So we will come to some of that as well, yeah, at some point, I think.

166
00:30:00.480 --> 00:30:08.270
Gaurav Singh .: one more point, like, usually in elections, like, there are multiple parties involved, no? Not A, B, there'll be A, B, C, D, E, F, right?

167
00:30:08.270 --> 00:30:08.860
Faculty (Olympus): Soâ€¦

168
00:30:08.860 --> 00:30:15.000
Gaurav Singh .: So, I mean, in that case, whether the varun would be the right Choice, or what.

169
00:30:15.000 --> 00:30:29.630
Faculty (Olympus): No, no, then, I mean, yeah, then maybe, it's, then, okay, you can think of, essentially, in that case, it might be something which is called the multinomial distribution,

170
00:30:30.130 --> 00:30:39.739
Faculty (Olympus): Whereâ€¦ which exactly mimics, this kind of a situation, where you have, n differentâ€¦ you have a total population size of N,

171
00:30:39.900 --> 00:30:48.709
Faculty (Olympus): But there are, now, say, M categories instead of just two categories. And, that's called a multinomial distribution.

172
00:30:48.970 --> 00:30:49.600
Gaurav Singh .: Got it.

173
00:30:49.600 --> 00:30:57.079
Siddharth Digambar Kulkarni .: Or we can say A wins or he loses. We can have two events, whether a particular person wins or he loses.

174
00:30:57.470 --> 00:31:07.570
Faculty (Olympus): Yeah, but then, I mean, describingâ€¦ so, it depends on how your election runs, right? If your election requires, so, is the winnerâ€¦

175
00:31:07.790 --> 00:31:13.919
Faculty (Olympus): Someone who wins 50% of the votes, or is the winner someone who wins the largest number of votes?

176
00:31:14.460 --> 00:31:23.080
Faculty (Olympus): If it is, you know, if it is a fixed threshold that you have to win 50% of the votes, then I agree, then you can think individually about each of them.

177
00:31:23.470 --> 00:31:25.469
Siddharth Digambar Kulkarni .: It may not be more than 50%.

178
00:31:25.470 --> 00:31:35.509
Faculty (Olympus): But it won't be, right? If you are running an election the way it runs here, then we haveâ€¦ then we have something else.

179
00:31:35.820 --> 00:31:36.580
Faculty (Olympus): Okay?

180
00:31:36.580 --> 00:31:37.859
Gaurav Singh .: Thank you, thank you.

181
00:31:37.990 --> 00:31:39.350
Faculty (Olympus): Harshad?

182
00:31:39.600 --> 00:31:52.219
Harshad Dilip Behere .: Yeah, good afternoon, Professor. Can we scroll up a little bit? Sorry, I joined a little late, so I'm trying to understand that the probability of 0.6 is the probability where, choosing incorrect candidate, right?

183
00:31:52.220 --> 00:32:11.309
Faculty (Olympus): No, no, that is the probability that you would support candidate A. So, 60% of the underlying population is supporting candidate A. So, if I pick, let's say, the way we are modeling things, if I pick a random individual, with probability 0.6, they support A. With probability 0.4, they support B.

184
00:32:12.130 --> 00:32:17.750
Harshad Dilip Behere .: Okay. I was also trying to understand, when we have an even number, why we say it will be a tie?

185
00:32:18.340 --> 00:32:26.290
Faculty (Olympus): Because, I mean, if 10 and 10, so if there are 20 people, 10 of them support A, 10 of them support B, then there is no real winner, right?

186
00:32:26.990 --> 00:32:29.680
Faculty (Olympus): So, we are saying there is a tie.

187
00:32:30.080 --> 00:32:33.060
Harshad Dilip Behere .: Yeah, but we say 0.6 already support A, right? Soâ€¦

188
00:32:33.060 --> 00:32:37.689
Faculty (Olympus): No, no, so that's the overall population, but in my sampled set.

189
00:32:37.850 --> 00:32:50.880
Faculty (Olympus): It can always happen, right? Because I'm only sampling a subset of the population. If I sample everyone, then yes, then there is no tie, then there are 60% of the people are actually supporting A, 40% are supporting B, but I'm only sampling 5 people.

190
00:32:51.340 --> 00:32:58.039
Faculty (Olympus): or if I'm sampling 6 people, it could very well happen that 3 of them support A, 3 of them support B.

191
00:32:58.540 --> 00:33:04.230
Harshad Dilip Behere .: Okay, and we use binomial here because we have eitherâ€¦ I mean, it's kind of a true and false here, right?

192
00:33:04.230 --> 00:33:15.889
Faculty (Olympus): Yeah, yeah, yeah. So we are thinking of, like, yeah, two possibilities for each of these N experiments, and we are computing, like, the number of successes, in some sense, of how many we see in the N.

193
00:33:16.160 --> 00:33:18.610
Harshad Dilip Behere .: Thank you, Professor. Thank you, Sina.

194
00:33:18.610 --> 00:33:20.650
Faculty (Olympus): Okay, Pinaki?

195
00:33:20.820 --> 00:33:29.169
Pinaki Ghosh .: Yeah, good afternoon, Professor. Just to reconfirm my understanding, though. Now, in case, here we have two candidates, we are assuming that there are two candidates, and therefore we areâ€¦

196
00:33:29.170 --> 00:33:41.449
Pinaki Ghosh .: Based on the sample size, we are trying to kind of, that X value is less than equal to middle value plus 1, just to avoid that. In case we have multiple candidates, like 10 candidates.

197
00:33:41.450 --> 00:33:47.369
Pinaki Ghosh .: So, in that case, binomial, as you said, will not be the right answer, right? What would the X value are, then, in that case?

198
00:33:47.370 --> 00:34:05.080
Faculty (Olympus): Yeah, yeah, no, so it depends what kind of election we are running, or what is the rule for a winner, how does the polling company actually doâ€¦ so you mightâ€¦ one possibility there, like I said, is what is called a multinomial distribution, which is essentiallyâ€¦ it's a generalization of the binomial distribution.

199
00:34:05.080 --> 00:34:12.040
Faculty (Olympus): Where now you have N people, but they are now divided into M classes, or supporting M different candidates.

200
00:34:12.040 --> 00:34:17.450
Faculty (Olympus): And then you might be interested in, amongst those M which is the highest

201
00:34:17.590 --> 00:34:20.409
Faculty (Olympus): Amongst the M numbers that were assigned.

202
00:34:20.690 --> 00:34:28.949
Faculty (Olympus): Alright, so what is the mode? And then you will select based on whichever is the highest value, and there'll be some probability associated with that.

203
00:34:29.730 --> 00:34:31.279
Pinaki Ghosh .: Okay. Yeah. Thanks, Chris.

204
00:34:31.710 --> 00:34:33.000
Faculty (Olympus): Okay, Shirley?

205
00:34:33.570 --> 00:34:40.629
Shirley Menezes .: So, will there be the element of independence in this case? Because, I think.

206
00:34:40.639 --> 00:34:51.289
Faculty (Olympus): Yeah, yeah. So we are, we are, we are, assuming that each selected, individual, independently decides whether to support candidate A or support candidate B.

207
00:34:51.710 --> 00:34:53.040
Shirley Menezes .: Okay, okay, makes sense.

208
00:34:53.520 --> 00:34:55.989
Faculty (Olympus): Okay? Yeah, Vidya?

209
00:34:59.260 --> 00:35:13.920
Vidya Gavel .: Hi, Professor. So, my question is regarding the B, where we have sample size 21. How did the 0.25 came in? Because when I calculate, I see a different 0.17 or something.

210
00:35:14.210 --> 00:35:32.440
Faculty (Olympus): Oh, is it? Okay, no, no, I might have written this incorrectly. I had, I think, computed it for 20, maybe with 21, it turns out to be different. Could be. This number, I'm notâ€¦ I'm not very sure about. What I know is that this formula is fine, so as long as this is what is being computed.

211
00:35:32.440 --> 00:35:37.509
Vidya Gavel .: Yeah, yeah, this isâ€¦ this formula is fine, yeah. When I calculate this, then I getâ€¦ Could be, could be, yeah.

212
00:35:37.510 --> 00:35:39.840
Faculty (Olympus): could be that this is not exactly 0.25.

213
00:35:39.840 --> 00:35:41.949
Vidya Gavel .: Sure, yeah, thanks, thanks for answering.

214
00:35:41.950 --> 00:35:42.620
Faculty (Olympus): Okay?

215
00:35:42.820 --> 00:35:43.970
Faculty (Olympus): Rahul?

216
00:35:44.400 --> 00:36:01.089
Rahul Joshi .: Sorry, just to confirm the understanding, sir, so whenever thisâ€¦ let's presuming that this 0.25 is the correct answer, so what we are saying is that whenever we will poll 21 people, there is a 25% or 0.25, chance that the poll will give B as a winner, right?

217
00:36:01.090 --> 00:36:01.819
Faculty (Olympus): Yeah, yeah.

218
00:36:02.360 --> 00:36:03.359
Rahul Joshi .: That isâ€¦ that is understood.

219
00:36:03.360 --> 00:36:04.939
Faculty (Olympus): That is the understanding, yeah.

220
00:36:04.940 --> 00:36:06.380
Rahul Joshi .: Okay, thank you, yeah.

221
00:36:06.380 --> 00:36:09.070
Faculty (Olympus): Okay, Praji Kumari?

222
00:36:09.500 --> 00:36:13.880
Lad Prachikumari Vijaykumar .: Sir, is it possible to solve this problem using Bardnoli?

223
00:36:15.410 --> 00:36:34.800
Faculty (Olympus): I mean, not directly, because we are not talking about just a 0, 1, but a binomial distribution is essentially like a sum of n Bernoulli random variables, okay? So you can think of a binomial distributed random variable X as, like, a sum of

224
00:36:36.000 --> 00:36:42.599
Faculty (Olympus): Nâ€¦ Bernoulli random variables, where each of these Xi's is Bernoulli P.

225
00:36:42.800 --> 00:36:55.670
Faculty (Olympus): Right? Each of these Xi's, they can take either value 1, or they can take value 0. The probability of being 1 is P, the probability of being 0 is 1 minus P. Right? And then we areâ€¦

226
00:36:55.820 --> 00:37:08.700
Faculty (Olympus): So, whenever Xi is 1, it contributes 1 to the sum. Whenever Xi is 0, it contributes nothing to the sum. So, the summation of Xi is exactly the number of 1s you see when you do end such experiments.

227
00:37:09.240 --> 00:37:09.750
Lad Prachikumari Vijaykumar .: Oh my goodness.

228
00:37:09.750 --> 00:37:15.180
Faculty (Olympus): think of this as, like, yeah, a sum of n, Bernoulli random variables as well.

229
00:37:15.820 --> 00:37:23.670
Lad Prachikumari Vijaykumar .: Okay, because I'm confused about, like, we have a problem statement and what concept we can apply, so that's why, like.

230
00:37:23.670 --> 00:37:26.270
Faculty (Olympus): Yeah, Bernali is only 0, 1.

231
00:37:26.410 --> 00:37:33.830
Faculty (Olympus): Ifâ€¦ if it is not something that is directly getting modeled as 0,1, then we have to move to something else.

232
00:37:34.270 --> 00:37:42.760
Faculty (Olympus): Right? Here, it'sâ€¦ it's the number of candidates supporting a certain candidate, is not either 0 or 1, so it cannot be Bernali.

233
00:37:44.380 --> 00:37:45.040
Lad Prachikumari Vijaykumar .: It hooked.

234
00:37:45.040 --> 00:37:45.370
Faculty (Olympus): Yep.

235
00:37:45.370 --> 00:37:46.679
Lad Prachikumari Vijaykumar .: Okay, thank you.

236
00:37:46.680 --> 00:37:52.430
Faculty (Olympus): Okay, okay, let's, let's move on,

237
00:37:52.690 --> 00:38:07.109
Faculty (Olympus): Okay, let me maybe do one more example of discrete random variables, and then we'll move further to continuous. Okay, so this is an example of a recommendation system.

238
00:38:10.330 --> 00:38:15.350
Faculty (Olympus): Okay, soâ€¦ You can think of your,

239
00:38:16.180 --> 00:38:28.029
Faculty (Olympus): Google News, or Google Search, or you can think of YouTube recommending videos to you, and so on. So, let's say what happens is that I pose, as a user, I pose a certain query.

240
00:38:28.280 --> 00:38:30.890
Faculty (Olympus): Okay? To the system.

241
00:38:31.400 --> 00:38:37.820
Faculty (Olympus): Andâ€¦ What the system does is that it gives me an ordered list.

242
00:38:38.610 --> 00:38:41.840
Faculty (Olympus): And it shows me, 5.

243
00:38:43.910 --> 00:38:46.809
Faculty (Olympus): Items, okay? Let's call themâ€¦

244
00:38:46.980 --> 00:38:55.979
Faculty (Olympus): Maybe thisâ€¦ so this is item 1, this is item 2, item 3, 4, 5, and then it shows me a sixth

245
00:38:56.180 --> 00:38:59.630
Faculty (Olympus): Element at bottom, which just is aâ€¦

246
00:38:59.750 --> 00:39:02.959
Faculty (Olympus): Link, which says, show me more.

247
00:39:03.010 --> 00:39:15.289
Faculty (Olympus): Okay, so if the 5â€¦ so the way this works is that it is an ordered list of 5 different things. So, for example, if it was a YouTube query, about something, suppose I was searching for,

248
00:39:15.290 --> 00:39:21.449
Faculty (Olympus): arsenal highlights, and then it'll give me 5 different links.

249
00:39:21.450 --> 00:39:37.280
Faculty (Olympus): Okay, these are supposed to be ordered, right? Maybe the first link is the most relevant according to YouTube, the second one is the second most relevant, third is the third most relevant, and so on. So it shows me five such items, and the way I go through these items is I go through them

250
00:39:37.410 --> 00:39:46.740
Faculty (Olympus): from the first. If I like the first, I click the first. If I don't like the first, I might look at the second one. If I like the second one, I click the second one.

251
00:39:46.860 --> 00:39:57.260
Faculty (Olympus): If I don't like 1 or 2, then I look at 3, and I might click 3, and so on, right? And at the end, if I don't like any of these 5, then I might just ask.

252
00:39:57.260 --> 00:40:07.440
Faculty (Olympus): YouTube to show me more links. Okay, so there are 6 possibilities for, how the user behaves, when they are showed such an ordered list.

253
00:40:07.630 --> 00:40:09.740
Faculty (Olympus): Now, suppose,

254
00:40:09.870 --> 00:40:20.119
Faculty (Olympus): Now, of course, YouTube has tons of data. They might have looked at how likely people are to click their first link, how likely people are to click the second link, and so on.

255
00:40:20.500 --> 00:40:31.900
Faculty (Olympus): Right? So, suppose we define Xâ€¦ to beâ€¦ the position of user click.

256
00:40:32.810 --> 00:40:41.559
Faculty (Olympus): Right? So then X can take 6 different values, right? User can click at position 1, or it can click at position 2,

257
00:40:41.910 --> 00:40:45.750
Faculty (Olympus): 3â€¦ forâ€¦ 5â€¦

258
00:40:46.060 --> 00:41:00.670
Faculty (Olympus): And maybe they are not satisfied with any of the links, so they might click on position 6. Okay? So suppose YouTube did this experiment, and they found, okay, 30% of the users actually like the first link itself, and they click it.

259
00:41:00.950 --> 00:41:05.870
Faculty (Olympus): Maybe a quarter, like, don't like the first one, but like the second one.

260
00:41:06.350 --> 00:41:11.049
Faculty (Olympus): 0.15 is here, 0.1 here.

261
00:41:11.120 --> 00:41:26.810
Faculty (Olympus): 05 clicked the fifth link, so very few people actually like the fifth link, so maybe by the fifth link, things are reallyâ€¦ the recommendation is not really very relevant. And then 15% of the people don't like any of the links, and just ask for more.

262
00:41:27.030 --> 00:41:39.580
Faculty (Olympus): Okay, so if we sum these up, they should sum up to 1. Is that happening here? So, 0.3 plus 0.4, 0.7, 0.8, yeah, point. So, the wholeâ€¦ this is, a valid

263
00:41:39.730 --> 00:41:43.700
Faculty (Olympus): probability mass function for this random variable X.

264
00:41:43.940 --> 00:41:45.920
Faculty (Olympus): Right, this is my PMF.

265
00:41:46.070 --> 00:41:59.410
Faculty (Olympus): for X. This describes my PMF, right? X is a value which can take either 1, 2, 3, 4, 5, or 6, and these are the probability values, or the PMF associated with this X.

266
00:41:59.850 --> 00:42:18.890
Faculty (Olympus): Right? Now, what kind of things might, YouTube be interested in? YouTube might be interested in, okay, what is the probability that, youâ€¦ so they mightâ€¦ they will, of course, be interested in, the quality of service, so what YouTube usually will want is that the user clicks one of the higher

267
00:42:18.890 --> 00:42:29.560
Faculty (Olympus): links, right? Because if they are clicking the first or the second link, that means the recommendation system is working well, right? So maybe they are interested in finding the probability of X being

268
00:42:29.560 --> 00:42:40.409
Faculty (Olympus): Less than equal to 3. So, how manyâ€¦ what fraction of users actually find the relevant link in the top 3 recommendations, right? So, this is exactly

269
00:42:40.410 --> 00:42:44.950
Faculty (Olympus): the CDF value of X, evaluated at 3.

270
00:42:45.060 --> 00:42:54.110
Faculty (Olympus): And this can be computed byâ€¦ so this is summing up, essentially, the PMF values corresponding to

271
00:42:54.590 --> 00:42:57.479
Faculty (Olympus): all values of i less than equal to 3.

272
00:42:57.620 --> 00:43:00.950
Faculty (Olympus): So this is I equals 1 to 3.

273
00:43:01.110 --> 00:43:10.380
Faculty (Olympus): Which is, in this particular case, it's going to be 0.3â€¦ plus 0.25â€¦ plus 0.15,

274
00:43:10.530 --> 00:43:19.689
Faculty (Olympus): So, that's 0.7. So, 70% of the users find their relevant, a relevant answer in the first 3

275
00:43:19.850 --> 00:43:26.879
Faculty (Olympus): choices that are presented to, to them, right? Similarly, they might be interested in

276
00:43:27.210 --> 00:43:35.140
Faculty (Olympus): Finding how many users actually are left unsatisfied. So what is the probability that X is greater than 4?

277
00:43:35.300 --> 00:43:51.329
Faculty (Olympus): Right? What is the probability that X is either 5 or 6? So the users are either finding something at the very last point, or they're not finding anything, right? And they're just going, and asking for more recommendations to be shown to them.

278
00:43:51.480 --> 00:44:00.149
Faculty (Olympus): Right? So, this will be, again, this will be probability of X being 5 plus the probability of X

279
00:44:00.350 --> 00:44:15.290
Faculty (Olympus): being 6, right? You can also think of this as 1 minus the probability of X less than equal to 3, right? Which is 1 minus FX evaluated at 3.

280
00:44:15.470 --> 00:44:22.960
Faculty (Olympus): Right? So if you sum up these values, X equals 5 and X equals 6, that corresponds to this

281
00:44:23.470 --> 00:44:29.590
Faculty (Olympus): plus this, is that,

282
00:44:29.590 --> 00:44:33.639
Siddharth Digambar Kulkarni .: less than, or, you're right. Correct.

283
00:44:33.640 --> 00:44:35.459
Faculty (Olympus): Okay, I made an error here.

284
00:44:35.640 --> 00:44:39.639
Faculty (Olympus): Yeah, okay, good. At least some people are awake.

285
00:44:39.810 --> 00:44:55.340
Faculty (Olympus): Very good, so this is FX at 4. You're right. So this is FX evaluated at 4. Here, X equals 5 is, is it .05? Yeah, so this is .05 plus 0.15

286
00:44:55.510 --> 00:44:57.059
Faculty (Olympus): So.2.

287
00:44:57.860 --> 00:45:03.959
Faculty (Olympus): Okay? So this, so FX at 4 must be 0.8, right?

288
00:45:04.350 --> 00:45:11.119
Faculty (Olympus): So, this tells me, okay, what fraction of users actually don't find anything

289
00:45:11.350 --> 00:45:21.559
Faculty (Olympus): useful in the first 4 links. They have to either look at the very last link, or they have to ask for more options. So that, again, isâ€¦ this is the quantity which is maybeâ€¦

290
00:45:21.740 --> 00:45:37.940
Faculty (Olympus): maybe suggests that, okay, this isâ€¦ there is a significant portion of people who are not finding things, relevant things in the top part of the recommendation list, so I have to improve my recommendation system. There is something wrong going on here, okay?

291
00:45:38.380 --> 00:45:46.439
Faculty (Olympus): So again, yeah, this is an, again, an example of a discrete random variable, which is directly related to recommendation systems.

292
00:45:48.460 --> 00:46:03.330
Faculty (Olympus): And, again, its PMF tells us something about the probability of positions of user click, and its CDF value is related to the quality of my recommendation system.

293
00:46:03.510 --> 00:46:04.340
Faculty (Olympus): Okay?

294
00:46:04.700 --> 00:46:13.410
Faculty (Olympus): Okay, yeah, maybe, maybe a couple of quick questions, and thenâ€¦ then we'll move on to, continuous random variables. Jagaurav?

295
00:46:14.280 --> 00:46:31.560
Gaurav Singh .: So, Professor, like, when we are selecting that PX less than equals to 3 forâ€¦ my recommendation is right, rightly givingâ€¦ more likely to giving right and, recommendations, then we should choose, X greater than 3, no? Like, as a complement of that.

296
00:46:32.590 --> 00:46:39.030
Faculty (Olympus): No, X less than equal to 3 meansâ€¦ so X is the position of user click, so X smaller is good.

297
00:46:39.540 --> 00:46:43.250
Faculty (Olympus): So, if I click on the first position, That's high.

298
00:46:43.250 --> 00:46:48.860
Gaurav Singh .: Talking about the, like, the second option, like, when the recommendation engine is not givingâ€¦

299
00:46:48.860 --> 00:46:55.180
Faculty (Olympus): Yeah, yeah, so it depends, right? Yeah, yeah, so, I mean, it depends on how I'm defining badâ€¦

300
00:46:55.200 --> 00:47:06.969
Faculty (Olympus): recommendation system. I am defining bad recommendation system as someone who either gives me the last link or asking for more. You might have your own definition.

301
00:47:06.970 --> 00:47:15.370
Faculty (Olympus): So this might be, like, a very, very good recommendation engine. Maybe an okay recommendation engine is one.

302
00:47:15.380 --> 00:47:18.250
Faculty (Olympus): Which looks at where,

303
00:47:18.310 --> 00:47:27.980
Faculty (Olympus): you know, you are at least giving me something in the top 5. So, it depends on what your event is. We are just looking at two different events, which are not complement of each other.

304
00:47:27.980 --> 00:47:28.490
Gaurav Singh .: No kidding.

305
00:47:28.490 --> 00:47:34.499
Faculty (Olympus): it depends on what your criteria is, right? Someone might have a very strict criteria saying, I want

306
00:47:34.660 --> 00:47:52.259
Faculty (Olympus): you know, most people, or 90% of the people, I want them to beâ€¦ to click either the first or the second link. Maybe that is your, kind of criteria that you are looking for. In which case, then, you will look at probability of X less than equal to 2. So, it depends on what your criteria is.

307
00:47:52.800 --> 00:47:53.640
Gaurav Singh .: Okay.

308
00:47:53.640 --> 00:47:54.170
Faculty (Olympus): Yep.

309
00:47:54.940 --> 00:47:56.290
Faculty (Olympus): Manu?

310
00:47:59.330 --> 00:48:01.060
Manu Gupta .: Good afternoon, Professor.

311
00:48:01.060 --> 00:48:01.720
Faculty (Olympus): Thank you.

312
00:48:01.720 --> 00:48:05.610
Manu Gupta .: My concerns regarding previous oneâ€¦

313
00:48:05.840 --> 00:48:10.090
Manu Gupta .: In the previous, we are, problemâ€¦

314
00:48:10.090 --> 00:48:14.499
Faculty (Olympus): Can we then do it at the end? You mean the candidate one?

315
00:48:15.580 --> 00:48:22.670
Faculty (Olympus): Yeah, so then let's do it at the end. I don't want to go back, again to that example, but we'llâ€¦ we canâ€¦ we can resolve that at the end.

316
00:48:23.620 --> 00:48:25.570
Faculty (Olympus): Okay. Alright, Sajith?

317
00:48:28.800 --> 00:48:34.740
Sajith K N .: It's, not a binomial, right? What is this method called?

318
00:48:35.120 --> 00:48:36.000
Sajith K N .: We just,

319
00:48:36.000 --> 00:48:38.799
Faculty (Olympus): This distribution is not aâ€¦

320
00:48:39.190 --> 00:48:44.170
Faculty (Olympus): One of the families that we have discussed, this is just an arbitrary probability mass function.

321
00:48:45.360 --> 00:48:46.070
Sajith K N .: Oh, boy.

322
00:48:46.070 --> 00:48:49.640
Faculty (Olympus): Yeah, there's no name for it, doesn't belong to some particular family.

323
00:48:50.840 --> 00:48:51.350
Sajith K N .: Okay.

324
00:48:51.810 --> 00:48:52.600
Faculty (Olympus): Okay?

325
00:48:53.690 --> 00:49:01.410
Faculty (Olympus): Okay, so that's it for discrete, random variables. Let's move on.

326
00:49:01.680 --> 00:49:04.120
Faculty (Olympus): 2â€¦ Continuous.

327
00:49:07.160 --> 00:49:08.719
Faculty (Olympus): Random variables.

328
00:49:12.880 --> 00:49:13.650
Faculty (Olympus): Okay?

329
00:49:14.690 --> 00:49:24.420
Faculty (Olympus): Okay, so, a random variableâ€¦ Isâ€¦ Saidâ€¦ to be continuous.

330
00:49:30.080 --> 00:49:37.469
Faculty (Olympus): Ifâ€¦ there existsâ€¦ A non-negative function.

331
00:49:38.620 --> 00:49:44.129
Faculty (Olympus): Maybe, okay, I don't know whether this is known to you, so let me write this. There existsâ€¦

332
00:49:45.240 --> 00:49:46.760
Faculty (Olympus): there existsâ€¦

333
00:49:47.510 --> 00:49:55.010
Faculty (Olympus): By the way, the notation sometimes used for this is opposite E. Okay, there exists a non-negative function.

334
00:49:55.340 --> 00:49:56.530
Faculty (Olympus): FX.

335
00:49:57.080 --> 00:50:04.400
Faculty (Olympus): Which, takes values in the real line and gives Something between 0 to infinity.

336
00:50:04.550 --> 00:50:11.390
Faculty (Olympus): Such thatâ€¦ the CDF of this random variable, right? Every random variable is associated with a CDF.

337
00:50:11.570 --> 00:50:21.469
Faculty (Olympus): The CDF can be expressed, okay? The CDF can be expressed as an integral from minus infinity to X of this

338
00:50:22.000 --> 00:50:24.119
Faculty (Olympus): particular function.

339
00:50:27.110 --> 00:50:29.120
Faculty (Olympus): Okay, and this has to be true.

340
00:50:29.350 --> 00:50:32.420
Faculty (Olympus): for all X.

341
00:50:33.210 --> 00:50:52.480
Faculty (Olympus): in R. So for all values of X, I should be able to describe my CDF, which is just the probability of X being less than equal to X. This is the definition of my CDF. I should be able to describe that CDF as an integral of this form.

342
00:50:52.720 --> 00:51:06.890
Faculty (Olympus): where FX is a non-negative function. If I'm able to do that, then the random variable is set to be a continuous random variable, and this non-negative function is said to be the probability

343
00:51:07.180 --> 00:51:10.490
Faculty (Olympus): Density function of the random variable.

344
00:51:10.830 --> 00:51:13.250
Faculty (Olympus): In short, the PDF.

345
00:51:13.960 --> 00:51:16.230
Faculty (Olympus): Okay? In short, the PDF.

346
00:51:17.470 --> 00:51:22.090
Faculty (Olympus): Okay, so this is the definition of a continuous random variable. Now.

347
00:51:22.860 --> 00:51:28.660
Faculty (Olympus): With this definition, there are a few implications of this definition.

348
00:51:29.190 --> 00:51:34.999
Faculty (Olympus): The first one is that because FX can be written in form of this integral.

349
00:51:35.540 --> 00:51:43.770
Faculty (Olympus): it is always continuous. So the CDF for a continuous random variable is itself Continuous.

350
00:51:45.270 --> 00:51:56.340
Faculty (Olympus): Okay? What this means is that, it is continuous, and also it isâ€¦ and alsoâ€¦ differentiable Almost everywhere.

351
00:51:57.860 --> 00:52:00.589
Faculty (Olympus): Okay, so this is almostâ€¦

352
00:52:01.250 --> 00:52:13.190
Faculty (Olympus): everywhere, you canâ€¦ I mean, yeah, you can ignore the almost everywhere for now if you want, but the key thing to keep in mind is that this is itself a continuous function, which means

353
00:52:13.190 --> 00:52:21.749
Faculty (Olympus): that the CDF will always be something that looks maybe something like this, okay? It will never have jumps

354
00:52:21.970 --> 00:52:26.610
Faculty (Olympus): Like the way we had for discrete random variables, where we had these jumps.

355
00:52:26.630 --> 00:52:34.230
Faculty (Olympus): Right? You will never have these kind of jumps for a continuous random variable, because a continuous random variable's CDF

356
00:52:34.230 --> 00:52:46.750
Faculty (Olympus): can always be written in this integral form, and this integral form assures that as X changeâ€¦ if X changes a tiny bit, you cannot have these arbitrary jumps, okay? That is just not allowed.

357
00:52:46.800 --> 00:52:51.749
Faculty (Olympus): So, for a continuous random variable, the CDF will always be continuous.

358
00:52:51.820 --> 00:52:55.379
Faculty (Olympus): Okay? That is one thing, that is one implication.

359
00:52:56.250 --> 00:53:07.980
Faculty (Olympus): The second implication is thatâ€¦ What do we know about the limit of the CDF, as X becomes large.

360
00:53:08.370 --> 00:53:11.430
Faculty (Olympus): Right? So, again, this is the limit

361
00:53:11.520 --> 00:53:30.269
Faculty (Olympus): as X tends to infinity of the probability of X being less than equal to X. We know that as small x becomes larger and large, this probability is going to converge to 1, right? The CDF always, as you go towards the right, it converges to 1. So I know that this quantity

362
00:53:30.490 --> 00:53:43.359
Faculty (Olympus): is, going to be equal to 1. Now, the CDF is being written in terms of an integral of this form, right? What will happen if you take this X to infinity?

363
00:53:43.490 --> 00:53:50.760
Faculty (Olympus): So this, what the implication is, that if I integrate this density function.

364
00:53:51.250 --> 00:53:55.389
Faculty (Olympus): over the entire real line, I will always get 1.

365
00:53:55.830 --> 00:54:08.579
Faculty (Olympus): Okay? So, a valid PDF will always have an integral over the real line, which amounts to 1. So, if you integrate this density out over the entire real line, you are going to get 1.

366
00:54:08.930 --> 00:54:09.780
Faculty (Olympus): Okay?

367
00:54:10.320 --> 00:54:21.709
Faculty (Olympus): Okay, very good. Now, the third thing was, what about the probability of, let's say, A less than X less than equal to B?

368
00:54:22.650 --> 00:54:30.590
Faculty (Olympus): This, we have seen, is the same as FX of B minus FX of A.

369
00:54:31.040 --> 00:54:31.960
Faculty (Olympus): Right?

370
00:54:32.210 --> 00:54:43.610
Faculty (Olympus): Now, for a continuous random variable, this is integrating minus infinity to B, of FXZDZ minus

371
00:54:43.940 --> 00:55:00.910
Faculty (Olympus): minus infinity to A of FXZDZ, right? So you are integrating out from minus infinity to B, and then subtracting the integral from minus infinity to A. So this is just equal to the integral from A to B,

372
00:55:01.350 --> 00:55:04.340
Faculty (Olympus): of FXZ Decent.

373
00:55:04.750 --> 00:55:11.780
Faculty (Olympus): Okay? So, the probability of X belonging to any interval Okay?

374
00:55:12.250 --> 00:55:19.330
Faculty (Olympus): Can be represented asâ€¦ An integral of the density in the corresponding interval.

375
00:55:21.200 --> 00:55:25.000
Faculty (Olympus): Okay? In the integral of the density in the corresponding interval.

376
00:55:25.480 --> 00:55:26.510
Faculty (Olympus): Nowâ€¦

377
00:55:26.650 --> 00:55:35.600
Faculty (Olympus): So, we can compute such probabilities using integrals of this density. So, the thing to keep in mind is that unlike

378
00:55:36.100 --> 00:55:40.820
Faculty (Olympus): discrete random variables where the PMF value correspond to true probabilities.

379
00:55:41.020 --> 00:55:51.500
Faculty (Olympus): The density actually does not correspond to a probability, so the density is not limited to be between 0 to 1. Density can actually have higher values as well. It need not be between 0 to 1.

380
00:55:51.730 --> 00:55:53.989
Soumen Deb .: Excuse me, sir. Excuse me.

381
00:55:54.320 --> 00:55:56.040
Faculty (Olympus): Sorry. Soâ€¦

382
00:55:56.040 --> 00:55:58.499
Soumen Deb .: So here it is A. Can I completeâ€¦

383
00:55:58.500 --> 00:56:08.440
Faculty (Olympus): Please, let me just complete, and then I'll stop, and then you can ask me the questions. Okay, I'll just take a moment more. Let me complete, and then we can do questions.

384
00:56:10.250 --> 00:56:29.310
Faculty (Olympus): So, yeah, so, probabilities don't correspond to the density. Integral of the density corresponds to probability, okay? So the density itself might beâ€¦ might have values beyond 1, but the density, when integrated over some interval, will always be values between 0 to 1.

385
00:56:29.710 --> 00:56:30.530
Faculty (Olympus): Okay?

386
00:56:30.660 --> 00:56:35.190
Faculty (Olympus): One lastâ€¦ Property.

387
00:56:35.830 --> 00:56:41.669
Faculty (Olympus): Okay? Which is, again, if I look at the probability of

388
00:56:41.830 --> 00:56:45.410
Faculty (Olympus): X taking a certain value A.

389
00:56:45.600 --> 00:56:46.390
Faculty (Olympus): Right?

390
00:56:46.580 --> 00:57:01.159
Faculty (Olympus): In the case of PMF, this could have been something which is some number between 0 to 1, but in the case of a continuous random variable, the probability of X taking a particular value A is always 0.

391
00:57:01.790 --> 00:57:06.029
Faculty (Olympus): Okay? Again, one way to see that is, you can think of this

392
00:57:06.640 --> 00:57:11.570
Faculty (Olympus): Quantity as being, let's say, the probability of

393
00:57:11.780 --> 00:57:18.230
Faculty (Olympus): X belonging to being greater than A minus some very small, tiny delta.

394
00:57:18.520 --> 00:57:24.200
Faculty (Olympus): and X being less than equal to A. Right? So, you can think of this as

395
00:57:24.730 --> 00:57:30.069
Faculty (Olympus): Let's say this is X, and this is X minus delta, and delta is very, very small.

396
00:57:30.200 --> 00:57:33.360
Faculty (Olympus): Okay? Very, very small. You take delta to go to zero.

397
00:57:33.640 --> 00:57:44.460
Faculty (Olympus): And you're asking what is the probability that X belongs very, very close to A, right? What will this integral be? So this will be, like, the integral from A minus delta

398
00:57:45.490 --> 00:58:01.610
Faculty (Olympus): to A of this density function, because it's a continuous random variable. Now, because delta is very, very tiny, this quantity, the density will roughly remain the same in this very tiny interval, so you can think of this as delta times

399
00:58:02.100 --> 00:58:03.860
Faculty (Olympus): FX A.

400
00:58:04.210 --> 00:58:10.409
Faculty (Olympus): But delta is going to 0, so this quantity is also going to go to 0, as delta goes to 0.

401
00:58:10.770 --> 00:58:17.140
Faculty (Olympus): Okay? So the probability that X takes any particular value any A.

402
00:58:17.310 --> 00:58:18.390
Faculty (Olympus): is zero.

403
00:58:18.580 --> 00:58:26.850
Faculty (Olympus): Okay, if you ask me what is the probability that X is either A or B, of course that is also 0, because it's just summing 0 plus 0.

404
00:58:27.130 --> 00:58:35.639
Faculty (Olympus): Right? So, that is also something that is very much a property of continuous

405
00:58:35.800 --> 00:58:45.119
Faculty (Olympus): distributions, okay? So, for continuous random variables, This is the probability

406
00:58:45.360 --> 00:59:01.820
Faculty (Olympus): that, of, X belonging to some interval, and that can be computed using integral of the density in the particular region, but the probability that X takes a particular value is just 0, okay?

407
00:59:02.090 --> 00:59:13.089
Faculty (Olympus): Okay, so now, now we can take, some questions, and but this is what a continuous, random variable is. Okay, yeah, Gaurav?

408
00:59:15.280 --> 00:59:18.820
Gaurav Singh .: Yeah, Professor, so, since we said that,

409
00:59:18.980 --> 00:59:29.729
Gaurav Singh .: as a definition itself, non-negative function, right? Yeah. So, while we are integrating from minus infinite to X instead, we could have integrated from 0 to X, right?

410
00:59:29.730 --> 00:59:36.090
Faculty (Olympus): No, no. So, non-negative function doesn't mean that the argument that I give is non-negative.

411
00:59:36.250 --> 00:59:39.669
Faculty (Olympus): The value that the function takes is non-negative.

412
00:59:40.300 --> 00:59:44.649
Gaurav Singh .: Okay, okay, Z isâ€¦ Z is non, can be negative.

413
00:59:44.650 --> 00:59:48.460
Faculty (Olympus): Z can be negative, but FX of Z will always be non-negative.

414
00:59:48.680 --> 00:59:53.570
Gaurav Singh .: non-negative. And second thing, like, the pro- property dens,

415
00:59:53.990 --> 00:59:58.539
Gaurav Singh .: probability distribution function, I think you said, that,

416
00:59:58.540 --> 00:59:59.840
Faculty (Olympus): Probability density from.

417
00:59:59.840 --> 01:00:00.470
Gaurav Singh .: Interesting.

418
01:00:00.470 --> 01:00:03.020
Faculty (Olympus): FX is probability density function.

419
01:00:03.020 --> 01:00:08.909
Gaurav Singh .: Yes, thatâ€¦ that will be greater than 1. Iâ€¦ I mean, canâ€¦

420
01:00:09.070 --> 01:00:20.129
Faculty (Olympus): That can be greater than 1. We will see, when we do some examples, we'll see that that value can, in fact, be larger than 1 as well, okay? But when I integrate that function over the

421
01:00:20.270 --> 01:00:21.810
Faculty (Olympus): Entire real line.

422
01:00:21.980 --> 01:00:22.780
Faculty (Olympus): Right?

423
01:00:22.890 --> 01:00:25.340
Faculty (Olympus): That will always be one.

424
01:00:26.110 --> 01:00:35.000
Faculty (Olympus): Which means thatâ€¦ what does integral, right, what does it mean, right? If I takeâ€¦ if I have some density of this kind, right? Suppose this isâ€¦

425
01:00:35.270 --> 01:00:36.360
Faculty (Olympus): FX.

426
01:00:36.540 --> 01:00:44.440
Faculty (Olympus): Right? It's a non-negative function. What does its integral over the entire real line mean? That means the area that is under this curve.

427
01:00:44.770 --> 01:00:45.450
Gaurav Singh .: Yes.

428
01:00:45.590 --> 01:00:47.699
Faculty (Olympus): Okay, so the area is 1.

429
01:00:48.180 --> 01:00:48.710
Gaurav Singh .: Yes.

430
01:00:48.710 --> 01:00:52.769
Faculty (Olympus): But a particular value here might be larger than 1.

431
01:00:53.790 --> 01:00:54.230
Gaurav Singh .: Mhmhm.

432
01:00:54.230 --> 01:00:55.290
Faculty (Olympus): That can happen.

433
01:00:55.490 --> 01:00:59.879
Faculty (Olympus): So this value, for example, could be something which is greater than 1.

434
01:00:59.990 --> 01:01:09.469
Faculty (Olympus): But if I compute the entire area, then that is something that is always equal to 1, and the probability of, let's say, X being

435
01:01:09.610 --> 01:01:19.690
Faculty (Olympus): lying inâ€¦ between A to B essentially corresponds to the area of theâ€¦ under the curve in this corresponding interval.

436
01:01:21.240 --> 01:01:34.669
Gaurav Singh .: But, say, like, probability mass function, for example, number of occurrences of a thing divided by total sample size is a kind of probability mass function, right, at a given.

437
01:01:35.270 --> 01:01:44.979
Faculty (Olympus): Probablyâ€¦ that'sâ€¦ so that is a discrete random variable. Probability mass function is for discrete random variables. They are inherently different from continuous random variables.

438
01:01:45.010 --> 01:01:45.969
Gaurav Singh .: Huh, soâ€¦

439
01:01:45.970 --> 01:01:50.610
Faculty (Olympus): So, you are thinkingâ€¦ so think of containers random variables. You should think ofâ€¦

440
01:01:50.720 --> 01:01:55.230
Faculty (Olympus): Quantities whichâ€¦ which do not have a finite support.

441
01:01:55.650 --> 01:01:58.359
Faculty (Olympus): For example, it might be over the reels.

442
01:01:59.350 --> 01:02:00.070
Gaurav Singh .: Hmm.

443
01:02:00.070 --> 01:02:09.610
Faculty (Olympus): Right? So it is not something that has a finite support. That is the type of quantity you should be thinking about when you're thinking about continuous random variables. For example.

444
01:02:10.030 --> 01:02:20.399
Faculty (Olympus): It could be things like, you know, the amount ofâ€¦ so suppose you go to catch a bus, what is the amount of time you take

445
01:02:20.770 --> 01:02:24.060
Faculty (Olympus): What is the amount of time you have to wait?

446
01:02:24.370 --> 01:02:26.279
Faculty (Olympus): Or it could beâ€¦

447
01:02:26.280 --> 01:02:27.000
Samar .: Come on.

448
01:02:27.000 --> 01:02:28.790
Ashish Kumar .: Weight of a person. Weight of a person.

449
01:02:28.790 --> 01:02:33.640
Faculty (Olympus): A person, or it could be, you know, how much time do you take to cover 100 meters?

450
01:02:33.830 --> 01:02:41.229
Faculty (Olympus): So, things of that kind, which don't have, like, so, think about reels, for example, things which are over reals.

451
01:02:42.360 --> 01:02:44.379
Gaurav Singh .: Okay. Okay. Yeah.

452
01:02:44.380 --> 01:02:46.740
Faculty (Olympus): Yeah, Rahul?

453
01:02:47.280 --> 01:03:00.370
Rahul Joshi .: Sir, if you, scroll a little bit up, actually, where point number 3, yeah. So, what will be the formula if A is, also, like, let's say X is less than or equal to A, as well as less than or equal to B?

454
01:03:00.370 --> 01:03:15.620
Faculty (Olympus): Yeah, very good. So, so A less than equal to X, less than equal to B. Right? For discrete random variables, we had seen there is a difference between A, whether each of these inequalities is strict or not, right? It can be different.

455
01:03:15.720 --> 01:03:21.549
Faculty (Olympus): Depending on, whether this is true or not. Here, in this case, I mean, I can think of this

456
01:03:21.770 --> 01:03:28.670
Faculty (Olympus): asâ€¦ the probability of A less than X, less than equal to B,

457
01:03:28.780 --> 01:03:32.600
Faculty (Olympus): plus the probability of X being exactly equal to A.

458
01:03:33.730 --> 01:03:35.019
Rahul Joshi .: Yep, yep, yep.

459
01:03:35.020 --> 01:03:49.290
Faculty (Olympus): But because for a continuous random variable, you already have this to beâ€¦ you always have this to be 0, so this is always the same. So for a continuous random variable, you don't have to worry. All of these inequalities, whether these are strict or not strict, they're all the same.

460
01:03:49.290 --> 01:03:50.740
Rahul Joshi .: Even it is equal to B.

461
01:03:50.740 --> 01:03:51.290
Faculty (Olympus): Yeah, yeah.

462
01:03:51.290 --> 01:03:52.499
Rahul Joshi .: greater than B is also the same, right.

463
01:03:52.500 --> 01:04:00.849
Faculty (Olympus): It doesn'tâ€¦ doesn't matter, so this is always going to beâ€¦ A to B of FXZDZ.

464
01:04:01.060 --> 01:04:06.960
Faculty (Olympus): Because whether the boundary is included or not contributes nothing to the probability, because

465
01:04:07.130 --> 01:04:10.220
Faculty (Olympus): Of it being a continuous distribution and having this form.

466
01:04:10.540 --> 01:04:11.410
Rahul Joshi .: Thank you so much, Siddhar.

467
01:04:11.410 --> 01:04:14.340
Faculty (Olympus): Okay? Yash Swapnil?

468
01:04:14.740 --> 01:04:28.000
Swapnil Sankla .: Yeah, sir, the fourth rule, when your probability of X equal to A is 0, is it 0 or 10s to 0? Because the DZ is not a 0, it always tends to 0.

469
01:04:28.000 --> 01:04:38.600
Faculty (Olympus): Huh, but DZ is, it's not aboutâ€¦ so, when I say X equal to A, I'm not saying X close to A. I'm saying X exactly taking the value A.

470
01:04:38.940 --> 01:04:49.829
Faculty (Olympus): Okay? That probability is zero, because you can think of that as integrating a very narrow band around A, but then taking the limit of the size of that band going to 0.

471
01:04:49.940 --> 01:04:54.040
Faculty (Olympus): So, like I said, if I take thatâ€¦ if I denote

472
01:04:54.400 --> 01:04:59.910
Faculty (Olympus): this quantity, I canâ€¦ I can think of this quantity asâ€¦

473
01:05:01.040 --> 01:05:05.080
Faculty (Olympus): The limit as delta tends to zero off

474
01:05:05.310 --> 01:05:12.729
Faculty (Olympus): the probability that X belongs to A minus delta 2A.

475
01:05:12.920 --> 01:05:18.270
Faculty (Olympus): If I do that, that probabilityâ€¦ thisâ€¦ when you take the limit, this is going to go to zero.

476
01:05:18.660 --> 01:05:24.169
Faculty (Olympus): Right? So this probability is the probability of X being exactly equal to A. That is 0.

477
01:05:25.080 --> 01:05:26.220
Swapnil Sankla .: Okay, thank you.

478
01:05:26.220 --> 01:05:26.830
Faculty (Olympus): Okay?

479
01:05:27.420 --> 01:05:30.520
Faculty (Olympus): Yeah, summer?

480
01:05:31.650 --> 01:05:39.420
Samar .: Yeah, so partially my question is answered, sir. Like, I was thinking, same, like, when we are talking about this A to B, this is more of an areaâ€¦

481
01:05:39.440 --> 01:05:54.229
Samar .: Which we calculate our indication. From CDF point of view, this will be, again, similar thing, right? Like, at the end, the probability is 1, and when we have to calculate the, let's say, less than A, we use the same how we are doing.

482
01:05:54.230 --> 01:06:03.340
Faculty (Olympus): Yeah, so probability of X less than A is the same as probability of X less than equal to A. Again, unlike discrete random variables, because there are no jumps.

483
01:06:03.980 --> 01:06:07.599
Samar .: This will be smooth. It'll always be smooth.

484
01:06:09.900 --> 01:06:12.139
Faculty (Olympus): Okay? Naina?

485
01:06:13.780 --> 01:06:34.500
Naina Punjwani .: Professor, the question was slightly, you know, linked to this, as well as, not linked to this, I can say. I was just trying to understand the difference between the discrete variable and, the linear equation that is Y is equals to MX plus C. So, even in the linear equation, the bar graph

486
01:06:34.500 --> 01:06:40.660
Naina Punjwani .: which you have shown, can go up and down, right? There could be a plus or minus in the M variable.

487
01:06:40.660 --> 01:06:48.049
Naina Punjwani .: So, what would be the difference between this linear, linear equation and this equation?

488
01:06:48.750 --> 01:06:52.069
Faculty (Olympus): Sorry, what is the linear equation,

489
01:06:52.070 --> 01:06:59.049
Naina Punjwani .: the linear equation, that is Y is equal to MX plus C. So, there could be a M, you know.

490
01:06:59.250 --> 01:07:04.889
Naina Punjwani .: If you plot that, this again comes to the same, graph, right?

491
01:07:06.310 --> 01:07:08.670
Naina Punjwani .: Which you have just shown on the screen.

492
01:07:09.450 --> 01:07:10.260
Faculty (Olympus): This scratch?

493
01:07:10.260 --> 01:07:11.899
Vivek Sahu .: You mean negative function?

494
01:07:13.370 --> 01:07:21.050
Naina Punjwani .: No, negative as well as positive, no? It canâ€¦ the linear, linear expression is just the line which is shown similar to this, right?

495
01:07:22.030 --> 01:07:22.310
Naina Punjwani .: Oh.

496
01:07:22.820 --> 01:07:25.650
Faculty (Olympus): Yeah, I don't know whatâ€¦

497
01:07:25.650 --> 01:07:26.510
Abhishek .: It won't be occurring.

498
01:07:26.510 --> 01:07:27.389
Rahul Saini .: Otherwise, no, no.

499
01:07:27.390 --> 01:07:28.899
Abhishek .: But it won't be a curve.

500
01:07:32.180 --> 01:07:47.339
Faculty (Olympus): Y equals MX plus C isâ€¦ I mean, if you're asking me, is mx plus c a valid density function, then it is not a valid density function, because the integral of that over the entire line is 1.

501
01:07:47.390 --> 01:07:48.610
Soumen Deb .: Yeah, it's more than one.

502
01:07:48.610 --> 01:07:54.820
Faculty (Olympus): So it has to be, for itâ€¦ for something to be a valid density function, firstly, it has to be positive.

503
01:07:55.360 --> 01:08:01.519
Faculty (Olympus): Or sorry, non-negative, and the integral over the entire real line has to be equal to 1.

504
01:08:03.420 --> 01:08:04.190
Faculty (Olympus): Okay?

505
01:08:04.330 --> 01:08:12.399
Faculty (Olympus): Yeah, I don't know whether I'm following your question exactly, but maybe we can take this at the end if you still are unclear about it.

506
01:08:12.400 --> 01:08:13.310
Naina Punjwani .: Yeah, okay.

507
01:08:13.310 --> 01:08:16.580
Faculty (Olympus): Okay, okay. Prachiki Kumari?

508
01:08:17.359 --> 01:08:23.369
Lad Prachikumari Vijaykumar .: Sir, what is Z here, in first and second property you have mentioned, soâ€¦

509
01:08:23.370 --> 01:08:26.479
Faculty (Olympus): So, Z is just the variable over which I'm integrating.

510
01:08:26.600 --> 01:08:27.680
Faculty (Olympus): I mean, this isâ€¦

511
01:08:27.689 --> 01:08:29.689
Rahul Saini .: This could be anything. Dora!

512
01:08:29.689 --> 01:08:34.359
Faculty (Olympus): So, it could be anything, yeah.

513
01:08:34.790 --> 01:08:38.429
Lad Prachikumari Vijaykumar .: Like, earlier, we are using X, right? So it is same like X.

514
01:08:38.430 --> 01:08:41.679
Faculty (Olympus): Yeah, yeah, yeah, yeah. This is just an integrating variable.

515
01:08:41.920 --> 01:08:42.520
Lad Prachikumari Vijaykumar .: Okay.

516
01:08:43.090 --> 01:08:46.879
Faculty (Olympus): Okay, okay,

517
01:08:46.880 --> 01:08:57.570
Rahul Joshi .: Sir, just one question. Yeah. So, in the real life, sir, for the continuous random variable, how to get this much of a data to draft the function? Because

518
01:08:57.569 --> 01:09:09.560
Rahul Joshi .: It's quite possible, let's say if you take an example of a number of seconds it will take for a player to complete 100 meters race. So, it can be very close between, let's say, 9 to 10, if they are all good players.

519
01:09:09.560 --> 01:09:12.140
Rahul Joshi .: So how to really draft the function? Yeah, yeah.

520
01:09:12.140 --> 01:09:19.280
Faculty (Olympus): So, usually, you willâ€¦ you will have some amount of data, but then you essentially, interpolate.

521
01:09:19.399 --> 01:09:34.889
Faculty (Olympus): So, you will never have a full quantification of, you know, of the entire thing. You will have some data, and then maybe you will plot the data, and you will interpolate between them to get a density function, and use that density function to do prediction in the future.

522
01:09:35.460 --> 01:09:46.830
Rahul Joshi .: So is it, is itâ€¦ analogy is like, whatever is the data you have, let's say 100 players' data you have, you draft the probability mass function for 100 and just connect it to create aâ€¦

523
01:09:46.960 --> 01:09:49.970
Rahul Joshi .: what I meant to say, the line which is corresponding.

524
01:09:49.979 --> 01:10:03.739
Faculty (Olympus): Yeah, so maybe you take really, really tiny, you know, as tiny as possible, bins, and then you see how manyâ€¦ yeah, you kind of plot together the probability mass function, and then you smoothen that out.

525
01:10:03.890 --> 01:10:04.250
Rahul Joshi .: Correct.

526
01:10:04.250 --> 01:10:06.460
Faculty (Olympus): To create a density function.

527
01:10:07.670 --> 01:10:08.260
Rahul Joshi .: Thank you.

528
01:10:08.800 --> 01:10:20.759
Faculty (Olympus): Okay, okay, so let's look at some examples. Maybe these will also clarify, some of the questions. So let's look at some examples of,

529
01:10:20.950 --> 01:10:29.710
Faculty (Olympus): commonly found, probability mass functions. So, the first one, which is the most common, is called a uniform

530
01:10:30.860 --> 01:10:39.440
Faculty (Olympus): distribution, so usually this uniform distribution is associated with an interval A to B. A and B might be some real numbers.

531
01:10:39.690 --> 01:10:42.060
Faculty (Olympus): And this is supposed to mimic

532
01:10:42.190 --> 01:10:53.220
Faculty (Olympus): choosing a random number between A and B, or a random number in the interval A to B, okay? So the density associated with this uniform

533
01:10:53.730 --> 01:10:59.940
Faculty (Olympus): A, B, Random variable is given by 1 upon B minus A.

534
01:11:00.210 --> 01:11:07.450
Faculty (Olympus): for X, betweenâ€¦ A to B.

535
01:11:07.590 --> 01:11:11.630
Faculty (Olympus): And, it is 0 outside this interval.

536
01:11:11.960 --> 01:11:18.099
Faculty (Olympus): Okay? So the density looks something like this. If this is A, this is B.

537
01:11:18.220 --> 01:11:21.689
Faculty (Olympus): The density is zero everywhere else.

538
01:11:21.930 --> 01:11:24.650
Faculty (Olympus): And then it jumpsâ€¦ It isâ€¦

539
01:11:24.820 --> 01:11:29.359
Faculty (Olympus): 1 by B minus A in this interval, and then it is 0 outside the interval.

540
01:11:33.230 --> 01:11:41.689
Faculty (Olympus): Okay? So you can see this is a valid density, it is a non-negative function, and if you look at the area under this curve, it is indeed 1.

541
01:11:41.690 --> 01:11:55.790
Faculty (Olympus): Right? The area of the rectangle is indeed 1. So this is a uniform, this is called a uniform, distribution, or a uniform random variable. This is its density. What would its CDF look like?

542
01:11:56.660 --> 01:12:02.890
Faculty (Olympus): Right? So, the CDF, is given by?

543
01:12:03.950 --> 01:12:06.370
Faculty (Olympus): The integral of the density function.

544
01:12:09.090 --> 01:12:12.419
Faculty (Olympus): promâ€¦ minus infinity to X.

545
01:12:12.530 --> 01:12:20.580
Faculty (Olympus): Now, in this case, Firstly, you can argue that this CDF value is going to be 0,

546
01:12:20.810 --> 01:12:22.539
Faculty (Olympus): all the way up to A.

547
01:12:23.300 --> 01:12:31.790
Faculty (Olympus): Right? All the way up to A. Because the probability that X is less than equal to A is, of course, 0. You only take values between A to B.

548
01:12:32.670 --> 01:12:48.530
Faculty (Olympus): And we can also argue that for any value of X larger than B, it is going to be 1, because probability of X less than equal to, let's say, anything larger than B is going to be 1, because we onlyâ€¦ so you are going to beâ€¦

549
01:12:48.700 --> 01:12:53.289
Faculty (Olympus): Somewhere like this, right? It's going to be 0 before A, and 1 after B.

550
01:12:53.480 --> 01:12:56.669
Faculty (Olympus): How does it change from A to B? Now.

551
01:12:57.070 --> 01:13:08.080
Faculty (Olympus): this integral, right? We are integrating from minus infinity to X, but I know that if I take X betweenâ€¦ so I'm looking at some X between A to B,

552
01:13:09.200 --> 01:13:16.399
Faculty (Olympus): this isâ€¦ the value of the density is 0 before A, and 0 after B. So the onlyâ€¦

553
01:13:16.540 --> 01:13:20.059
Faculty (Olympus): Contribution from the integral is from A to X.

554
01:13:20.380 --> 01:13:21.240
Faculty (Olympus): offâ€¦

555
01:13:21.430 --> 01:13:28.190
Faculty (Olympus): And what is the density in this region? The density is a fixed number, it is 1 by B minus A in this entire interval.

556
01:13:28.840 --> 01:13:35.859
Faculty (Olympus): Right? So this is going to be exactly X minus A upon B minus A.

557
01:13:36.060 --> 01:13:54.789
Faculty (Olympus): And this is going to be true for any X between A to B. So you can see atâ€¦ if I plug in X equal to A, this gives me value 0, which is here. If you plug X equals B, this gives me value 1, which is here, right? And in between, you are essentially connected by a

558
01:13:55.770 --> 01:13:56.799
Faculty (Olympus): Straight line.

559
01:13:57.020 --> 01:14:06.429
Faculty (Olympus): So this is how the CDF of a uniformly distributed random variable between A to B looks like. It's just the integral of a constant density.

560
01:14:06.840 --> 01:14:16.360
Faculty (Olympus): Okay? Now, where is this uniform random variable? Where will you encounter it? So, like I said, one place where you might find it is, for example.

561
01:14:16.750 --> 01:14:31.619
Faculty (Olympus): let's say waiting times. So, this is, this could be the waiting time inâ€¦ for example, youâ€¦ there is a scheduled service, like, for example, there is a bus which comes every 10 minutes, and let's say you arrive at a random

562
01:14:31.670 --> 01:14:48.670
Faculty (Olympus): time in between some two scheduled times. Let's say 10â€¦ 10 o'clock there is a bus, and then 10.10, you have another bus, and let's say you arrive at a random time in between, then your waiting time is going to be uniformly distributed between 0 to 10 minutes.

563
01:14:48.730 --> 01:14:55.599
Faculty (Olympus): Right? Because there is a scheduled bus at every 10 minutes, so you might have a random waiting time ofâ€¦

564
01:14:56.340 --> 01:15:02.139
Faculty (Olympus): between 0 to 10 minutes. Another place where uniform random variables comes, and this is something you might

565
01:15:02.660 --> 01:15:12.890
Faculty (Olympus): actually encounter when you do neural networks is that often in neural networks, we'll start with some initialization phase for the weights of the neurons.

566
01:15:13.020 --> 01:15:20.240
Faculty (Olympus): And, oftentimes we will initialize them with just, random numbers between minus 1 to 1.

567
01:15:20.360 --> 01:15:35.479
Faculty (Olympus): Okay, so you might choose the uniform minus 1, distribution to initialize the weights of a neural network, and then from there on, you will use some optimization algorithm to train the neural network. So that might be an initialization point.

568
01:15:35.720 --> 01:15:42.410
Faculty (Olympus): Forâ€¦ or a way to initialize the weights of a neuralâ€¦ of a neural network.

569
01:15:42.700 --> 01:15:46.470
Faculty (Olympus): Okay? Okay.

570
01:15:46.470 --> 01:15:49.300
Abhineet Bansal: Can you explain this once again, sir? Please, mist it out.

571
01:15:49.300 --> 01:15:51.359
Faculty (Olympus): Explain what,

572
01:15:51.360 --> 01:15:53.219
Abhineet Bansal: The first part of the example, sir.

573
01:15:53.570 --> 01:16:00.139
Faculty (Olympus): Yeah, yeah. So, okay, let meâ€¦ so, you mean the uniform distribution density?

574
01:16:00.380 --> 01:16:01.390
Abhineet Bansal: Correct, yes.

575
01:16:02.140 --> 01:16:15.210
Faculty (Olympus): Okay, so the density of a uniform distribu- thisâ€¦ so a uniform distributed random variable is specified by an interval, A to B, okay? And it is mimicking, essentially, choosing a random number in that interval.

576
01:16:15.550 --> 01:16:24.230
Faculty (Olympus): Okay, so the density, maybe the way I shâ€¦ this is a little bit of a problem in terms of notation. Let's say this isâ€¦

577
01:16:24.390 --> 01:16:33.260
Faculty (Olympus): FX evaluated at X, okay? So this is for a uniform AB random variable, which is sometimes denoted as U

578
01:16:33.560 --> 01:16:34.530
Faculty (Olympus): A. B.

579
01:16:35.420 --> 01:16:39.850
Faculty (Olympus): Okay? Its density is 1 by B minus A. Ifâ€¦

580
01:16:40.030 --> 01:16:45.630
Faculty (Olympus): X is between A to B, and it is 0 everywhere else, meaning the density looks something like this.

581
01:16:45.760 --> 01:16:49.659
Faculty (Olympus): It is 0 outside the interval, and within the interval, it's flat.

582
01:16:49.840 --> 01:16:58.560
Faculty (Olympus): It's 1 upon B minus A. Okay, so that kind of mimics the fact that all values between A to B are equally likely.

583
01:16:59.120 --> 01:16:59.830
Faculty (Olympus): Okay?

584
01:17:00.020 --> 01:17:08.050
Faculty (Olympus): And, so that's the density function, and to compute the CDF, you just have to integrate out the density function

585
01:17:08.130 --> 01:17:16.879
Faculty (Olympus): From minus infinity to X, but in this case, because the density only is positive from Aâ€¦ between A to B,

586
01:17:16.930 --> 01:17:31.480
Faculty (Olympus): The valid integral is just A to X, right? Outside, if I do minus infinity to A, that integral is just going to be 0, because the density itself is 0 everywhere in that portion, right? So what matters is the integral from A to X,

587
01:17:31.750 --> 01:17:43.669
Faculty (Olympus): And that turns out to just have this linear form. So between A to B, you will have this linear form, and before A, it is going to be 0. After B, it is going to be clipped at 1.

588
01:17:45.050 --> 01:17:47.999
Rahul Joshi .: So, so, sir, just one, one, one question.

589
01:17:48.000 --> 01:17:53.130
Faculty (Olympus): Can I go in order? Can I just ask? Sorry, sorry. Yeah, yeah, I'll come to you. Yeah, Gaurav?

590
01:17:54.890 --> 01:18:06.379
Gaurav Singh .: So Professor Lake, you, in the definition, basically, you talked about that, almost, differentiable,

591
01:18:06.380 --> 01:18:12.939
Faculty (Olympus): So, I said that it is differentâ€¦ it is continuous everywhere, and it is differentiable almost everywhere.

592
01:18:13.240 --> 01:18:13.830
Gaurav Singh .: Correct.

593
01:18:13.830 --> 01:18:14.600
Faculty (Olympus): Soâ€¦

594
01:18:14.600 --> 01:18:15.070
Gaurav Singh .: Soâ€¦

595
01:18:15.320 --> 01:18:16.139
Faculty (Olympus): Hi,

596
01:18:16.140 --> 01:18:18.620
Gaurav Singh .: case A and B, it will not be differential.

597
01:18:18.620 --> 01:18:23.690
Faculty (Olympus): will not be differentiable. Yeah, that's what I meant. So sometimes you will have these points whereâ€¦

598
01:18:23.970 --> 01:18:27.400
Faculty (Olympus): They areâ€¦ it is non-differentiable, but these are going to beâ€¦

599
01:18:27.950 --> 01:18:30.720
Faculty (Olympus): Very few points you can think of. They'll have no mass.

600
01:18:31.020 --> 01:18:35.030
Gaurav Singh .: Okay, and second question is,

601
01:18:35.710 --> 01:18:39.799
Gaurav Singh .: I mean, when we define this, ran,

602
01:18:40.480 --> 01:18:50.960
Gaurav Singh .: this variable, that 1 by B minus A. Make sure that the integration across the real number should be 1.

603
01:18:51.100 --> 01:18:51.610
Faculty (Olympus): Yeah.

604
01:18:52.260 --> 01:18:58.010
Gaurav Singh .: And that's how we define, basically, right? Because there is noâ€¦ I meanâ€¦

605
01:18:58.540 --> 01:19:10.580
Gaurav Singh .: in case of, discrete variables, we have a way to define for every particular random variable some function way we can represent. But here.

606
01:19:11.310 --> 01:19:15.970
Gaurav Singh .: Since we don't have anything at a particular value of a.

607
01:19:15.970 --> 01:19:16.540
Saurav kumar: And again.

608
01:19:16.540 --> 01:19:26.289
Gaurav Singh .: line number. So, we define the function itself in such a way that our total integration across the real line should be 1.

609
01:19:26.290 --> 01:19:31.619
Faculty (Olympus): Yeah, so a valid density function is a non-negative function whose integral over the real line is 1.

610
01:19:31.960 --> 01:19:33.220
Gaurav Singh .: Okay, okay.

611
01:19:33.220 --> 01:19:35.279
Faculty (Olympus): Just how our density function is described.

612
01:19:35.820 --> 01:19:36.480
Gaurav Singh .: Okay.

613
01:19:37.080 --> 01:19:37.680
Faculty (Olympus): Okay.

614
01:19:38.390 --> 01:19:41.829
Faculty (Olympus): Okay, yeah, Abhineet?

615
01:19:42.790 --> 01:19:47.839
Abhineet Bansal: Just wanted to understand the last part, so you're integrating from A to X. Why not A to B?

616
01:19:48.350 --> 01:19:53.800
Faculty (Olympus): because I'm evaluating the CDF at X, right? Soâ€¦ Ifâ€¦

617
01:19:54.050 --> 01:19:58.059
Faculty (Olympus): So, CDF of X is the integral from minus infinity to X.

618
01:19:58.670 --> 01:20:04.220
Faculty (Olympus): This is the probability of X being less than equal to some number X.

619
01:20:05.610 --> 01:20:07.119
Abhineet Bansal: Got it, got it. Okay.

620
01:20:07.120 --> 01:20:07.680
Faculty (Olympus): Yeah.

621
01:20:08.460 --> 01:20:10.470
Faculty (Olympus): Okay, yeah, Rahul?

622
01:20:10.470 --> 01:20:28.199
Rahul Joshi .: So, sir, in the example which you took, 10 minutes waiting time maximum, okay? So, whenever we say, X minus A, let's say X value is 3, 3 minutes waiting time, okay? So, 3 minus A, it'll be 0.3. So, what is the exact meaning of 0.3 here?

623
01:20:28.620 --> 01:20:29.720
Rahul Joshi .: Is it, like, a 30â€¦

624
01:20:29.720 --> 01:20:31.690
Faculty (Olympus): A is 0.3, Y, whyâ€¦

625
01:20:31.690 --> 01:20:34.780
Rahul Joshi .: what I meant to say is that, let's say A0B10.

626
01:20:34.870 --> 01:20:35.540
Faculty (Olympus): Yeah, yeah.

627
01:20:35.540 --> 01:20:40.140
Rahul Joshi .: The 3 minutes waiting time means 3 minus 0 upon 10 minus 0, which isâ€¦ Yeah.

628
01:20:40.140 --> 01:20:44.960
Faculty (Olympus): So what this is saying is that the probability that you will have at most

629
01:20:45.120 --> 01:20:48.310
Faculty (Olympus): 3 minutes of waiting time is 0.3.

630
01:20:49.020 --> 01:20:51.840
Faculty (Olympus): Soâ€¦

631
01:20:52.000 --> 01:21:02.199
Faculty (Olympus): Essentially, the probability of, having, you know, or probability of waiting for less than 3 minutes.

632
01:21:02.430 --> 01:21:08.540
Faculty (Olympus): Is, 0.3, or one-third of the time you will have a waiting time less than 3 minutes.

633
01:21:08.950 --> 01:21:11.259
Faculty (Olympus): Right? Because this is the CDF value.

634
01:21:11.820 --> 01:21:17.520
Faculty (Olympus): This corresponds to probability of X being less than equal to whatever X you are plugging in.

635
01:21:18.690 --> 01:21:26.340
Rahul Joshi .: Okay, so just to confirm, whenever you arrive, there is a probability of 30% that you will have to wait up to 3 minutes.

636
01:21:26.600 --> 01:21:28.439
Faculty (Olympus): Yeah, wait less than 3 minutes.

637
01:21:29.600 --> 01:21:30.409
Rahul Joshi .: Makes sense, thank you.

638
01:21:31.010 --> 01:21:31.860
Faculty (Olympus): Okay?

639
01:21:31.970 --> 01:21:33.920
Faculty (Olympus): Harshad?

640
01:21:34.840 --> 01:21:46.010
Harshad Dilip Behere .: Yeah, so Professor, this could be a very fundamental question, but when weâ€¦ the last line, when we say integral over A2X, 1 by B minus A, right? So, essentially, we are doing F of A minus F of X, is it?

641
01:21:46.250 --> 01:21:48.110
Harshad Dilip Behere .: Or F of X minus F of A.

642
01:21:48.110 --> 01:21:51.720
Faculty (Olympus): F of X minus, Soâ€¦

643
01:21:52.260 --> 01:21:58.829
Faculty (Olympus): Iâ€¦ yeah, we are thinking of that asâ€¦ or I can think of that as capâ€¦ yeah, capital F ofâ€¦

644
01:21:59.400 --> 01:22:07.150
Faculty (Olympus): No, sorry, what are youâ€¦ so you can think of that as capital F of X,

645
01:22:07.400 --> 01:22:12.729
Faculty (Olympus): X, or evaluated at X, minus capital F of X, evaluated at A.

646
01:22:13.170 --> 01:22:13.720
Harshad Dilip Behere .: Okay.

647
01:22:13.720 --> 01:22:16.390
Faculty (Olympus): But capital F of X evaluated at A is just 0.

648
01:22:18.130 --> 01:22:18.780
Harshad Dilip Behere .: Okay.

649
01:22:18.780 --> 01:22:19.500
Faculty (Olympus): Right, soâ€¦

650
01:22:19.500 --> 01:22:22.540
Harshad Dilip Behere .: That is how we have defined it at the start, is it? Okay.

651
01:22:22.540 --> 01:22:24.590
Faculty (Olympus): Yeah, yeah. So, the definition ofâ€¦

652
01:22:24.980 --> 01:22:35.239
Faculty (Olympus): FX, I mean, that is the defâ€¦ this is by the definition of a continuous distribution, or a continuous random variable, that it'sâ€¦ CDF can be expressed in this way.

653
01:22:36.820 --> 01:22:38.700
Harshad Dilip Behere .: Okay, thank you. Thank you.

654
01:22:39.190 --> 01:22:41.900
Faculty (Olympus): Okay, let me do another example.

655
01:22:42.080 --> 01:22:50.050
Faculty (Olympus): So let's do one more. So another possible example is an exponential random variable.

656
01:22:50.440 --> 01:23:05.990
Faculty (Olympus): So this is, again, a very commonly used random variable. It's denoted as XP, usually, and it is associated with one parameter lambda, which is something greater than zero, some non-negative parameter lambda.

657
01:23:06.200 --> 01:23:12.050
Faculty (Olympus): Now, the density ofâ€¦ so unlike, for example, uniform random variable, which was used to mimic

658
01:23:12.630 --> 01:23:28.500
Faculty (Olympus): a choice where, you know, you have, like, an interval and all values are equally likely. An exponential random variable is one where smaller values are more likely than higher values, so its density also reflects that. So its density is given by

659
01:23:28.850 --> 01:23:34.120
Faculty (Olympus): it is lambda times E raised to minus lambda X.

660
01:23:34.270 --> 01:23:36.730
Faculty (Olympus): for X, non-negative.

661
01:23:36.860 --> 01:23:50.499
Faculty (Olympus): And it is zero otherwise. Okay, so it's only for non-negative values, and the density decreases exponentially. So, if I plot this density, it is going to look something like this.

662
01:23:53.980 --> 01:23:58.510
Faculty (Olympus): Okay, so this is, like, your density, this is your X,

663
01:23:59.320 --> 01:24:11.819
Faculty (Olympus): Right, and this is supposed to be lambda times V is 2 minus lambda X. So this is how your FX is going to look like. Now, how would your CDF look like? So, again, to compute

664
01:24:12.290 --> 01:24:13.400
Faculty (Olympus): effects.

665
01:24:13.530 --> 01:24:20.170
Faculty (Olympus): evaluated at X, you will integrate out the density.

666
01:24:20.710 --> 01:24:24.899
Faculty (Olympus): over the corresponding interval. Again, the density is 0 for

667
01:24:25.160 --> 01:24:33.910
Faculty (Olympus): negative values of Z, so what matters is integral from 0 to X of the density, which is lambda times

668
01:24:34.080 --> 01:24:37.200
Faculty (Olympus): E raised to minus lambda Z.

669
01:24:39.360 --> 01:24:49.859
Faculty (Olympus): BZ, okay? If you do this integral, I'm not going to do it here, but you canâ€¦ if you compute this integral, it's going to be 1 minusâ€¦

670
01:24:50.140 --> 01:25:05.740
Faculty (Olympus): E raised to minus lambda X. Okay, and this is, of course, for X greater than equal to 0. For X less than equal to 0, the CDF value is going to be 0, because for an exponential random variable, you only have,

671
01:25:06.040 --> 01:25:14.340
Faculty (Olympus): the density is non-zero only for positive values of X, okay? So the CDF is going toâ€¦

672
01:25:14.640 --> 01:25:17.360
Faculty (Olympus): look something like this. It's going to beâ€¦

673
01:25:17.770 --> 01:25:24.579
Faculty (Olympus): 0 all the way to zero, and then it'll behave like 1 minus E raised 2 minus lambda. So it's going to tend

674
01:25:25.100 --> 01:25:29.629
Faculty (Olympus): towards 1, as you increase the value of X.

675
01:25:30.480 --> 01:25:32.690
Faculty (Olympus): Okay, it's going to go towards 1.

676
01:25:33.480 --> 01:25:48.480
Faculty (Olympus): Okay, so where is, exponential random variable? Where does it come up? It comes upâ€¦ it is, like, the most common model for, modeling service times in any kind of queue.

677
01:25:48.480 --> 01:25:58.050
Faculty (Olympus): So, for example, this could be, okay, if you are waiting in a queue at the supermarket, how much time does a particular server take?

678
01:25:58.100 --> 01:26:02.269
Faculty (Olympus): To complete one, person's checkout.

679
01:26:02.330 --> 01:26:05.730
Faculty (Olympus): Usually, that is modeled as an exponential random variable.

680
01:26:05.830 --> 01:26:15.660
Faculty (Olympus): Similarly, it is used for modeling failure probability. So, let's say you look at the lifetime of a certain electronic component, orâ€¦

681
01:26:15.780 --> 01:26:25.699
Faculty (Olympus): let's say some computer hardware. Again, exponential distribution is often used to model lifetimes, of, such components.

682
01:26:25.890 --> 01:26:27.959
Faculty (Olympus): It is also used

683
01:26:28.420 --> 01:26:47.080
Faculty (Olympus): for example, in financial applications. So, if you recall, in the very first class, we had this financial application where we had toâ€¦ a company was a loan company, and it had to decide whether to give loan to a particular individual or not, and that was based on the

684
01:26:47.250 --> 01:26:55.840
Faculty (Olympus): their daily spend, right? And we were assuming that the daily spend is

685
01:26:55.860 --> 01:27:09.920
Faculty (Olympus): some exponential distributed random variable with some parameter lambda. So that exactly corresponds to this kind of a density. So again, it is used to model these kind of financial outlays as well.

686
01:27:09.920 --> 01:27:22.440
Faculty (Olympus): Because again, for an individual, usually, you know, the daily spends will probably be small, but every now and then they might make a big spend, and you want to understand what is the probability of them making

687
01:27:22.440 --> 01:27:33.479
Faculty (Olympus): a certain large spend. So, if you recall, there exactly, we were interested in finding what is the probability that this individual spends more than 2,000 rupees in a particular day.

688
01:27:33.480 --> 01:27:46.000
Faculty (Olympus): If this probability was going to be larger than pointâ€¦ than 5%, then we'll reject the loan. If it's smaller than 5%, then we will approve the loan. So this exactly corresponds to 1 minus the CDF value

689
01:27:46.130 --> 01:27:56.829
Faculty (Olympus): of this exponential distributed random variable evaluated at 2000, 1 minus the CDF is exactly E raised to minus lambda times 2000.

690
01:27:57.210 --> 01:28:12.820
Faculty (Olympus): Right? So there we had figured out some estimate of lambda, you just plug that in, whatever number you get, that is your estimate ofâ€¦ for the individual, for the probability that this individual is going to spend too much money in a day, and so is a high risk.

691
01:28:13.740 --> 01:28:21.790
Faculty (Olympus): So this is how, for example, the exponential distribution comes into play. Final thing about an exponential distribution.

692
01:28:22.020 --> 01:28:30.809
Faculty (Olympus): So, if you recall, for geometric, when we were discussing geometric random variables, I mentioned that it is the only discrete random variable that

693
01:28:30.980 --> 01:28:35.750
Faculty (Olympus): That, has the memory-less property.

694
01:28:35.890 --> 01:28:44.099
Faculty (Olympus): Similarly, exponential distribution is the only continuous random variable which has memory-less property.

695
01:28:44.730 --> 01:28:49.739
Faculty (Olympus): Which is also why it is very popular in applications like,

696
01:28:50.210 --> 01:29:00.459
Faculty (Olympus): like, queuing theory, service times, and so on. So, for this random variable as well, the probability that X is greater than S plus T

697
01:29:00.480 --> 01:29:11.719
Faculty (Olympus): given that X is greater than T, exactly matches the probability that X is greater than S. Okay, this is something that you should be able to, in fact,

698
01:29:12.500 --> 01:29:17.759
Faculty (Olympus): proof, now. You canâ€¦ you can try showing that this is indeed

699
01:29:18.090 --> 01:29:25.520
Faculty (Olympus): true, okay? You just have to use the formula for conditional probability, and

700
01:29:25.700 --> 01:29:30.110
Faculty (Olympus): Evaluate the corresponding integrals corresponding to these events.

701
01:29:30.370 --> 01:29:31.060
Faculty (Olympus): Okay?

702
01:29:31.250 --> 01:29:36.500
Faculty (Olympus): Okay, again, yeah, maybe I'll take a couple of questions.

703
01:29:36.960 --> 01:29:38.140
Faculty (Olympus): Summer?

704
01:29:39.960 --> 01:29:45.960
Samar .: Yes, sir, sir, if you just scroll up in the uniform distribution entity, there is one.

705
01:29:45.960 --> 01:29:49.190
Faculty (Olympus): Can I then, can we take this at the end? Yeah?

706
01:29:49.190 --> 01:30:07.920
Samar .: Oh, okay. I think these are related, maybe, the question was, like, here also you have drawn this CDF, and here also you have drawn this graph, like, so here, I just want to understand, like, after B, the density is zero, then what does this constant light show in that graph?

707
01:30:07.920 --> 01:30:22.860
Faculty (Olympus): So what it is showing is thatâ€¦ what does CDF mean, right? It says the probability of X less than equal to X. So think of, for example, so what is the probability of X being less than equal to B for this random variable?

708
01:30:24.290 --> 01:30:28.030
Faculty (Olympus): this random variable will only take values between A and B.

709
01:30:28.030 --> 01:30:28.560
Samar .: Amita.

710
01:30:28.560 --> 01:30:31.380
Faculty (Olympus): So what is the probability that X is less than equal to B?

711
01:30:31.510 --> 01:30:32.640
Faculty (Olympus): It is going to be 1.

712
01:30:32.640 --> 01:30:34.700
Samar .: Okay, yeah.

713
01:30:34.700 --> 01:30:39.570
Faculty (Olympus): If I take X less than equal to B plus 10, again, it's going to be 1.

714
01:30:40.070 --> 01:30:47.169
Faculty (Olympus): So that is what this is saying, that theâ€¦ that your probability that X is less than equal to anything greater than B is 1.

715
01:30:49.040 --> 01:30:51.179
Samar .: Okay, okay, yep, thank you.

716
01:30:51.180 --> 01:30:51.850
Faculty (Olympus): Okay?

717
01:30:51.960 --> 01:30:53.380
Faculty (Olympus): Yeah, Sajith?

718
01:30:55.860 --> 01:31:02.449
Sajith K N .: Yeah, also on to that uniform continuity. I was asking you, thinking the same, same question.

719
01:31:02.660 --> 01:31:08.410
Sajith K N .: Howâ€¦ whyâ€¦ why do we take the CDF again? Because we have a PDFâ€¦ we areâ€¦

720
01:31:08.610 --> 01:31:28.369
Faculty (Olympus): So, all we're saying is that you can translate from the density to the CDF. You might beâ€¦ I mean, you might naturally have events that you're interested in where the CDF is important, like, for example, something like this, right? If I have to compute this, this is exactly 1 minus the CDF value.

721
01:31:28.490 --> 01:31:31.260
Faculty (Olympus): So I might want to compute the CDF value.

722
01:31:32.670 --> 01:31:39.130
Faculty (Olympus): So, just like for discrete random variables, you can switch fromâ€¦ they are equivalent descriptions.

723
01:31:39.310 --> 01:31:49.809
Faculty (Olympus): PMF and CDF were equivalent descriptions. Similarly, for continuous random variables, the density and CDF are equivalent descriptions. You can go from one to the other.

724
01:31:50.370 --> 01:31:56.200
Faculty (Olympus): So, if you have the density, you can integrate and get the CDF. If you have the CDF, differentiate.

725
01:31:56.500 --> 01:31:57.049
Sajith K N .: And get.

726
01:31:57.050 --> 01:31:58.320
Faculty (Olympus): theâ€¦ get the.

727
01:31:58.320 --> 01:32:00.389
Sajith K N .: Oh, okay, okay, okay.

728
01:32:01.230 --> 01:32:01.950
Faculty (Olympus): Okay?

729
01:32:02.440 --> 01:32:06.829
Faculty (Olympus): Okay, let's maybe do one last example.

730
01:32:07.180 --> 01:32:08.640
Faculty (Olympus): Then we'll conclude.

731
01:32:08.640 --> 01:32:18.389
Rahul Joshi .: Sorry, sir, just one question. What is theâ€¦ do we have a formula for CDF and PDF, just in case of exponential distribution?

732
01:32:18.900 --> 01:32:23.750
Faculty (Olympus): Yeah, yeah, so this is what, so this, theâ€¦ this is the density.

733
01:32:24.850 --> 01:32:28.290
Faculty (Olympus): And, this is theâ€¦ CDF.

734
01:32:30.020 --> 01:32:31.590
Rahul Joshi .: Okay, okay, fine.

735
01:32:32.090 --> 01:32:37.589
Rahul Joshi .: And in the density function, it's a sum, or it is what in the first notation is, it is a sum.

736
01:32:37.590 --> 01:32:43.579
Faculty (Olympus): No, so, okay, yeah, yeah, sorry, so this is, this represents cases.

737
01:32:43.800 --> 01:32:58.020
Faculty (Olympus): Okay, so there are two different cases, maybe let me draw this again. So usually thisâ€¦ this represents cases. What this is saying is that this density for X greater than equal to 0, for the case of X greater than equal to 0, it is this value.

738
01:32:58.450 --> 01:33:03.459
Faculty (Olympus): If X is otherwise, meaning if X is less than 0, then it is 0.

739
01:33:04.430 --> 01:33:08.800
Faculty (Olympus): So you have a function of this type. For X less than 0, there is no density.

740
01:33:09.770 --> 01:33:13.489
Faculty (Olympus): It is only non-negative for X greater than 0.

741
01:33:15.110 --> 01:33:15.800
Rahul Joshi .: Oh, okay.

742
01:33:15.800 --> 01:33:17.509
Faculty (Olympus): Okay, so it is just defining

743
01:33:17.700 --> 01:33:22.079
Faculty (Olympus): Two different cases, what the density is under the two different regimes.

744
01:33:22.910 --> 01:33:23.650
Rahul Joshi .: Okay.

745
01:33:23.650 --> 01:33:24.270
Faculty (Olympus): Okay?

746
01:33:24.550 --> 01:33:28.320
Rahul Joshi .: So that's the reason it isâ€¦ it's not divisible by zero, it is just a notation.

747
01:33:28.320 --> 01:33:32.740
Faculty (Olympus): No, there is no divisibility here. It's just two different cases.

748
01:33:33.220 --> 01:33:33.890
Rahul Joshi .: Okay.

749
01:33:35.270 --> 01:33:36.360
Faculty (Olympus): Okay?

750
01:33:36.650 --> 01:33:42.260
Faculty (Olympus): Okay, so the last example I want to do is a Gaussian distribution.

751
01:33:44.110 --> 01:33:49.139
Faculty (Olympus): This is also sometimes referred to as the normal distribution.

752
01:33:50.160 --> 01:33:54.260
Faculty (Olympus): Okay? So, for the Gaussian distribution,

753
01:33:56.200 --> 01:33:59.380
Faculty (Olympus): This is represented usually by this N.

754
01:33:59.500 --> 01:34:04.470
Faculty (Olympus): And it is specified by two parameters, mu and sigma square.

755
01:34:04.870 --> 01:34:09.979
Faculty (Olympus): Mu, is supposed to be some real number.

756
01:34:10.300 --> 01:34:21.600
Faculty (Olympus): And this sigma square, the sigma is, supposed to be some non-negative real number. Okay? Some non-negative real number, it is greater than zero.

757
01:34:23.410 --> 01:34:38.210
Faculty (Olympus): Okay, so the density function corresponding to a Gaussian distribution with parameters mu and sigma square is given by 1 by sigma square root 2 pi.

758
01:34:38.960 --> 01:34:50.289
Faculty (Olympus): exponentialâ€¦ minusâ€¦ X minus mu square by 2 sigma squared. Okay, and this is true for all X

759
01:34:50.580 --> 01:34:56.550
Faculty (Olympus): In the real line. So for every value of X, this is what the density function looks like.

760
01:34:56.740 --> 01:35:14.609
Faculty (Olympus): Now, if you plot this density function, it'll look something like this. You will have this mu, that is what the density function is going to be centered at, that is where the density is going to be the highest, and then it'll decay something like this, right? So this bell curve is something all of you might have seen.

761
01:35:14.690 --> 01:35:19.019
Faculty (Olympus): Right? So this is what this density looks like.

762
01:35:19.330 --> 01:35:26.990
Faculty (Olympus): Now, the CDFâ€¦ Of aâ€¦ for a Gaussian random variable.

763
01:35:27.260 --> 01:35:30.970
Faculty (Olympus): There isâ€¦ it's usually denoted by this phi function.

764
01:35:31.050 --> 01:35:40.180
Faculty (Olympus): X. There is no closed-form solution for the CDF, okay? Unlike, for example, the uniform distribution or the exponential distribution.

765
01:35:40.180 --> 01:35:53.259
Faculty (Olympus): The CDF of a Gaussian distribution has no closed form, that integral does not have a closed form. There are numerical tables for evaluating the CDF value at different points. So these numerical tables are available, and

766
01:35:53.480 --> 01:35:57.970
Faculty (Olympus): Also, there are bounds which are available, but there is no closed form for this.

767
01:35:58.380 --> 01:36:00.950
Faculty (Olympus): Now, for Gaussian distribution,

768
01:36:01.310 --> 01:36:15.030
Faculty (Olympus): It is applied widely, it's probably the most used distribution. It is used to model any situation where most values are close to a certain value which represents mu.

769
01:36:15.040 --> 01:36:32.669
Faculty (Olympus): And you have some variation around that mu. So, for example, it could be, let's say, you know, the height of people, or in this cohort, or it could be, again, the grades that people get in a certain class.

770
01:36:32.890 --> 01:36:41.180
Faculty (Olympus): Anything of that kind. Usually, people try and model that as a Gaussian distribution, centered at some value.

771
01:36:41.600 --> 01:36:46.380
Faculty (Olympus): A place where you will probably encounter it is when you do linear regression.

772
01:36:46.560 --> 01:37:06.550
Faculty (Olympus): you will see that theâ€¦ so, usually in linear regression, you model the relationship between the output variable and a feature variable as something like this. So, it is Y equals some A times Xi plus epsilon i, which is where this epsilon i is supposed to denote some noise.

773
01:37:06.550 --> 01:37:17.030
Faculty (Olympus): And this noise is usually modeled as a Gaussian random variable with parameters 0 and maybe some sigma square, where the sigma square is some small number, okay?

774
01:37:17.230 --> 01:37:22.569
Faculty (Olympus): And when you have this kind of a Gaussian, distributed noise.

775
01:37:22.860 --> 01:37:28.009
Faculty (Olympus): Then one can show that the usual, you will learn these,

776
01:37:28.050 --> 01:37:44.040
Faculty (Olympus): kind of ordinary least squares kind of ways of doing linear regression, they're very much related to the noise being modeled as a Gaussian. Okay, so it comes naturally from there. This Gaussian distribution is really one of those distributions which is very, very widely used.

777
01:37:44.640 --> 01:37:45.370
Faculty (Olympus): Okay?

778
01:37:45.470 --> 01:37:48.920
Faculty (Olympus): Often used to model noise, essentially.

779
01:37:49.090 --> 01:37:58.339
Faculty (Olympus): Okay? And we'll see itâ€¦ one reason it is used heavily is because it has many nice properties, and we'll come across some of those properties. So, for example.

780
01:37:58.480 --> 01:38:13.299
Faculty (Olympus): If you take, like, a sum of two independent Gaussians, that is also a Gaussian. If you apply a linear transformation to a Gaussian random variable, that also remains a Gaussian, and so on. So that's why it is widely used. So we'll come across some of those properties as we go along.

781
01:38:13.510 --> 01:38:21.760
Faculty (Olympus): Okay, okay, so yeah, in terms of technical content for today, we are done. I'll just take questions now.

782
01:38:22.250 --> 01:38:25.639
Faculty (Olympus): Y, Yash Somin?

783
01:38:28.050 --> 01:38:28.960
Soumen Deb .: Yeah, hi.

784
01:38:29.980 --> 01:38:34.400
Soumen Deb .: So, I just wanted to understand, this exponential is erased, right?

785
01:38:34.400 --> 01:38:34.890
Faculty (Olympus): Yeah.

786
01:38:34.890 --> 01:38:45.550
Soumen Deb .: I'm confused about this. And the below notation that you have written, the last line, that's Yi is equal to AXI, so what does I stand for?

787
01:38:45.550 --> 01:38:55.859
Faculty (Olympus): Oh, no, so this is just in linear regression, usually this isâ€¦ you have many, many data points, and you're trying to fit a line through those.

788
01:38:55.860 --> 01:38:56.380
Soumen Deb .: Hmm.

789
01:38:56.380 --> 01:39:06.559
Faculty (Olympus): So you have different, data points corresponding to labels and features, and you're trying to fit a line curve, so this corresponds to, like, the Ath data point.

790
01:39:07.160 --> 01:39:13.660
Faculty (Olympus): So in linear regression, usually you model the relationship as some linear transformation.

791
01:39:13.810 --> 01:39:18.460
Faculty (Olympus): But with some added noise. So that noise is usually modeled as Gaussian.

792
01:39:18.990 --> 01:39:20.980
Soumen Deb .: Okay, so my question is,

793
01:39:21.410 --> 01:39:30.019
Soumen Deb .: A line will be Y is equal to AX plus epsilon, which is correct, but if you try to do it around curves, it will be quadratic, right?

794
01:39:31.620 --> 01:39:43.040
Faculty (Olympus): So, linear regression inherently assumes a linear relationship between the output and the input. You are trying to fit a linear relationship between the output and the input.

795
01:39:43.150 --> 01:39:46.380
Faculty (Olympus): And you're trying to find the best linear relationship estimate.

796
01:39:48.500 --> 01:39:50.520
Soumen Deb .: Okay, so it assumes that it is a straight line.

797
01:39:50.790 --> 01:39:57.010
Faculty (Olympus): Yeah, yeah, yeah, you are assuming, or a matrix transformation, if, in general, you're doing somethingâ€¦

798
01:39:57.230 --> 01:40:02.780
Faculty (Olympus): Yeah, more general than a line, but it assumes a linear relationship.

799
01:40:03.820 --> 01:40:07.490
Soumen Deb .: And one last question. Can you just go a little bit above, theâ€¦

800
01:40:07.720 --> 01:40:17.319
Soumen Deb .: notation that you have written for this. So what does this stand for? This is a memoryless property. I mean, like, do you have any examples of this, or maybe we can go visit next class or something on this one?

801
01:40:17.490 --> 01:40:21.059
Faculty (Olympus): So, this is just a property of the exponential distribution.

802
01:40:21.610 --> 01:40:22.100
Soumen Deb .: Okay.

803
01:40:22.100 --> 01:40:26.489
Faculty (Olympus): So, for the exâ€¦ just like for,

804
01:40:27.070 --> 01:40:30.599
Faculty (Olympus): The geometric distribution, there was a memorylessness property.

805
01:40:30.750 --> 01:40:37.510
Faculty (Olympus): Similarly, the exponential distribution also follows a memoryless, memorylessness property.

806
01:40:37.710 --> 01:40:41.670
Faculty (Olympus): Okay, it's saying that the probability that X is greater than S plus T

807
01:40:41.850 --> 01:40:45.040
Faculty (Olympus): Given that X is already greater than t.

808
01:40:45.210 --> 01:40:54.829
Faculty (Olympus): This information of X being greater than T is essentially not changing your belief about how much more will youâ€¦ will X be than T.

809
01:40:55.310 --> 01:41:11.170
Faculty (Olympus): So, that probability is the same as the probability of X greater than S. In fact, okay, maybe this is because it's quite easy here, we can even show this quickly. So, recall that for an exponential distribution.

810
01:41:11.550 --> 01:41:13.920
Faculty (Olympus): the CDF.

811
01:41:14.610 --> 01:41:19.060
Faculty (Olympus): is 1 minus E raised 2 minus lambda X.

812
01:41:19.410 --> 01:41:31.600
Faculty (Olympus): For X greater than equal to 0. So, CDF is probability of X greater than equal to X. So, probability ofâ€¦ oh, sorry, the CDF is X less than equal to X.

813
01:41:31.950 --> 01:41:36.519
Faculty (Olympus): So if I have to write X greater than X, that is just 1 minus the CDF,

814
01:41:36.760 --> 01:41:42.040
Faculty (Olympus): This is 1 minus E is 2 minus lambda X for all X greater than or equal to zero, right?

815
01:41:42.220 --> 01:41:50.170
Faculty (Olympus): Now, for the memorylessness property, I was looking at probability of X greater than S plus T,

816
01:41:50.290 --> 01:41:57.490
Faculty (Olympus): given X greater thanâ€¦ S? Is that what I had done? Yeah. No, no, X greater than T.

817
01:41:57.780 --> 01:42:01.190
Faculty (Olympus): So, this is X greater than T.

818
01:42:01.320 --> 01:42:02.080
Faculty (Olympus): Right?

819
01:42:02.180 --> 01:42:12.950
Faculty (Olympus): what would this quantity be? So, conditional probability is X greater than S plus T. By the way, here, S, T, all are greater than 0.

820
01:42:13.130 --> 01:42:15.730
Faculty (Olympus): So this is X greater than T,

821
01:42:15.910 --> 01:42:19.560
Faculty (Olympus): divided by probability of X greater than t.

822
01:42:19.780 --> 01:42:20.580
Faculty (Olympus): Right?

823
01:42:20.780 --> 01:42:29.850
Faculty (Olympus): Now, the numerator, X is greater than S plus T, and X is greater than t is the same as X being greater than S plus T, right? That is the definingâ€¦

824
01:42:31.620 --> 01:42:40.060
Faculty (Olympus): condition here, so this is the probability of X greater than S plus T divided by X greater than t.

825
01:42:40.280 --> 01:42:42.059
Faculty (Olympus): Now, we can useâ€¦

826
01:42:42.810 --> 01:43:00.379
Faculty (Olympus): this, the 1 minus CDF value, that formula that we already have for exponential distribution, so this just becomes E raised to minus lambda S plus T divided by E raised to minus lambda T,

827
01:43:00.560 --> 01:43:03.620
Faculty (Olympus): Which is just E raised to minus lambda S.

828
01:43:04.140 --> 01:43:10.060
Faculty (Olympus): Now, what is E raised 2 minus lambda S? This is exactly the probability that X is greater than S.

829
01:43:10.820 --> 01:43:20.899
Faculty (Olympus): Right? So this is saying that the probability that X is greater than S plus T given X is greater than t is, in fact, the same as the probability of X is greater than S.

830
01:43:22.250 --> 01:43:24.569
Faculty (Olympus): Okay, that's exactly the memorylessness property.

831
01:43:25.710 --> 01:43:26.430
Soumen Deb .: Okay.

832
01:43:26.430 --> 01:43:29.200
Faculty (Olympus): Okay, so that holds for exponential distributions.

833
01:43:30.700 --> 01:43:31.390
Soumen Deb .: Thank you.

834
01:43:31.390 --> 01:43:33.530
Faculty (Olympus): Okay? Okay, Sanket?

835
01:43:37.010 --> 01:43:58.160
Sanket Samant .: Yeah, hi, Professor. One thing I wanted to know, that in the uniform distribution, we have taken an example where the slope is positive, I mean, increasing from A to B, right? So, is there any possibility that the slope is negative? I mean, before A, the probability is 1, then after B, the probability is 0.

836
01:43:58.160 --> 01:44:06.410
Faculty (Olympus): So, see, it never can be, right? A CDF, by definition, is a monotonically non-decreasing function.

837
01:44:06.690 --> 01:44:07.470
Sanket Samant .: Okay.

838
01:44:07.470 --> 01:44:09.560
Faculty (Olympus): So, I mean, this is not,

839
01:44:09.910 --> 01:44:17.030
Faculty (Olympus): This is coming from the fact that we are integrating from minus infinity to higher and higher values.

840
01:44:17.190 --> 01:44:19.410
Faculty (Olympus): So, you can never have a negative slope.

841
01:44:19.800 --> 01:44:22.020
Faculty (Olympus): CDF always is non-decreasing.

842
01:44:22.910 --> 01:44:23.840
Sanket Samant .: Okay, okay.

843
01:44:23.840 --> 01:44:26.959
Faculty (Olympus): So, you will alwaysâ€¦ you will never have a negative slope.

844
01:44:27.730 --> 01:44:42.430
Sanket Samant .: And, yeah, so there is one more, supplemented out from this, that, the, distribution that we have seen, right, in the example, are always starting from zero. So is there any examples that when we areâ€¦ will be using the negative values.

845
01:44:42.430 --> 01:44:48.770
Faculty (Olympus): Yeah, so Gaussian distribution is, over, all values of R.

846
01:44:48.950 --> 01:44:54.450
Faculty (Olympus): Okay. It's not only for, positive values of X. It's defined over the entire real line.

847
01:44:54.450 --> 01:44:58.569
Sanket Samant .: Oh, okay, okay, okay. Works. Done. Thanks, thanks, Professor.

848
01:44:58.570 --> 01:45:00.930
Faculty (Olympus): Okay? Yeah, Ravi Kumar?

849
01:45:03.340 --> 01:45:17.440
Ravi Kumar Pathak .: Sir, my question is a little generic over here. So, in exam point of view, are we going to prove all this, or it is something that will be slightly different? It willâ€¦ the questionsâ€¦ just wanted to understand, like, do we need toâ€¦

850
01:45:17.440 --> 01:45:19.529
Faculty (Olympus): What kind of things here?

851
01:45:19.530 --> 01:45:26.930
Ravi Kumar Pathak .: So, these, distributions, so do we need to, basically solve, and then memorize these,

852
01:45:26.930 --> 01:45:39.329
Faculty (Olympus): No, no, you don't have to memorize any distributions. You will be given a sheet which has all the distributions that are needed listed right there. You don't have to memorize any expressions.

853
01:45:39.330 --> 01:45:47.949
Faculty (Olympus): But you should know what a PDF means, what does it represent, how do you go from PDF to CDF, how do you go from PDF to PDF?

854
01:45:48.210 --> 01:45:58.619
Faculty (Olympus): what are their interpretations? If I give you an event, if I say, okay, I have an exponential distributed random variable, and I want to find the probability that X is greater than 100,

855
01:45:58.790 --> 01:46:02.939
Faculty (Olympus): You should know how to use the density expression to compute that value.

856
01:46:04.400 --> 01:46:04.790
Ravi Kumar Pathak .: Okay.

857
01:46:04.790 --> 01:46:09.170
Faculty (Olympus): Okay? Theâ€¦ the, density will be provided to you.

858
01:46:09.600 --> 01:46:12.110
Faculty (Olympus): You don't have to memorize that density.

859
01:46:13.180 --> 01:46:24.929
Ravi Kumar Pathak .: Okay, and then will there be kind of any, use case scenario where we need to apply, like, which exactly these one of the, distributions will be most applicable, or something like that?

860
01:46:24.930 --> 01:46:31.639
Faculty (Olympus): So, again, I don't know, I can't predict the future about what we'll exactly ask, but, I mean, it'llâ€¦

861
01:46:32.440 --> 01:46:37.800
Faculty (Olympus): It'll not be something that, you cannot answer if you have understood the concept.

862
01:46:38.000 --> 01:46:45.229
Faculty (Olympus): Right? So, if I ask something like, you know, I am,

863
01:46:46.190 --> 01:46:55.079
Faculty (Olympus): I don't know, I'mâ€¦ let's say, I'mâ€¦ I'm plotting, the curve for,

864
01:46:55.240 --> 01:46:58.109
Faculty (Olympus): Profit or loss on a particular day.

865
01:46:58.240 --> 01:47:01.169
Faculty (Olympus): Is exponential distribution a good model?

866
01:47:01.380 --> 01:47:11.080
Faculty (Olympus): Right? So clearly, profit-loss means you can have positive values, negative values, but exponential distribution only has positive values, so maybe it's not a good model.

867
01:47:11.300 --> 01:47:18.250
Faculty (Olympus): So, as long as I think you understand what is going on, what do these distributions represent.

868
01:47:18.450 --> 01:47:20.490
Faculty (Olympus): What does the density represent?

869
01:47:20.820 --> 01:47:22.529
Faculty (Olympus): You should be okay.

870
01:47:22.680 --> 01:47:32.009
Faculty (Olympus): If it's an open-ended question, then, I mean, it is an open-ended question, then we willâ€¦ if there is no definite answer, then we'll also grade answers that way.

871
01:47:32.210 --> 01:47:38.089
Faculty (Olympus): Meaning, we'll takeâ€¦ we'll take whatever you can, as any reasonable answer as a good answer.

872
01:47:38.720 --> 01:47:40.410
Ravi Kumar Pathak .: Good, thank you, thank you very much.

873
01:47:40.410 --> 01:47:41.010
Faculty (Olympus): Okay?

874
01:47:41.270 --> 01:47:42.639
Faculty (Olympus): Siddharth?

875
01:47:43.140 --> 01:47:50.380
Siddharth Digambar Kulkarni .: Yes, sir. The CDF of this normal would be integral of this PDF, right?

876
01:47:50.380 --> 01:47:50.740
Faculty (Olympus): Yeah, yeah.

877
01:47:50.740 --> 01:47:54.469
Siddharth Digambar Kulkarni .: Jain this is, not ableâ€¦ we'll not be able to integrate this.

878
01:47:54.470 --> 01:47:58.000
Faculty (Olympus): Yeah, we don't have a close-form solution for this integral.

879
01:47:58.140 --> 01:48:00.899
Faculty (Olympus): This E raised to minus X square kind of integral.

880
01:48:01.350 --> 01:48:02.260
Siddharth Digambar Kulkarni .: Okay.

881
01:48:02.780 --> 01:48:03.460
Faculty (Olympus): Yeah.

882
01:48:03.670 --> 01:48:13.779
Siddharth Digambar Kulkarni .: And a second thing in the, exponential distribution, in that PDF, it is 130 at, lambda, right?

883
01:48:15.340 --> 01:48:16.800
Faculty (Olympus): No, no, so this isâ€¦

884
01:48:16.800 --> 01:48:18.520
Siddharth Digambar Kulkarni .: No harm.

885
01:48:19.590 --> 01:48:27.539
Faculty (Olympus): So, this is lambda times e raised to minus lambda X. So, it'll go to 0 only as x tends to infinity.

886
01:48:27.540 --> 01:48:31.200
Siddharth Digambar Kulkarni .: Yes, yes. But if X is 0, then it will become lambda.

887
01:48:31.200 --> 01:48:36.149
Faculty (Olympus): Lambda, haha. Yeah, yeah, you're right. So, at X equal to 0, this value is lambda.

888
01:48:36.620 --> 01:48:40.390
Siddharth Digambar Kulkarni .: And then it will never touch the x-axis.

889
01:48:40.390 --> 01:48:43.300
Faculty (Olympus): No, it'll never touch the x-axis, and it will only touch

890
01:48:43.420 --> 01:48:46.380
Faculty (Olympus): get to zero as extends to infinity.

891
01:48:46.580 --> 01:48:47.420
Siddharth Digambar Kulkarni .: Very cool.

892
01:48:48.830 --> 01:48:49.430
Faculty (Olympus): Okay?

893
01:48:49.950 --> 01:48:51.090
Faculty (Olympus): Yeah, Naina?

894
01:48:52.820 --> 01:49:02.000
Naina Punjwani .: Professor, can you scroll down? I need to undersâ€¦ ifâ€¦ and if you can explain, if you have time, you can explain the question again, ifâ€¦

895
01:49:02.440 --> 01:49:04.499
Naina Punjwani .: I think I missed it, yeah.

896
01:49:04.500 --> 01:49:20.589
Faculty (Olympus): So, the Gaussian distribution, it's, characterized by two parameters, mu and sigma square. Mu is some real number, and the sigma is supposed to be some non, non-negative value, okay? Usually a positive value.

897
01:49:20.950 --> 01:49:21.690
Faculty (Olympus): Okay?

898
01:49:21.860 --> 01:49:26.669
Faculty (Olympus): And the density is, given, by thisâ€¦

899
01:49:26.990 --> 01:49:34.549
Faculty (Olympus): formula, so this is essentiallyâ€¦ there is a constant outside, 1 by sigma square root 2 pi, and then you are doing an exponential of

900
01:49:34.750 --> 01:49:39.779
Faculty (Olympus): This quadratic function, minus X minus mu square by 2 sigma square.

901
01:49:40.010 --> 01:49:45.189
Faculty (Olympus): And it looks something like this. So it'sâ€¦ it's centered around this value mu.

902
01:49:45.400 --> 01:49:53.959
Faculty (Olympus): And, if you increase the valueâ€¦ so you can thinkâ€¦ roughly, you can think of this sigma as, like, the width

903
01:49:54.460 --> 01:50:07.049
Faculty (Olympus): some sort of effective width of this curve. So if sigma is large, then this, this curve is going to be more spread out. If sigma is small, then the curve is going to be more peaky at mu.

904
01:50:07.210 --> 01:50:11.660
Faculty (Olympus): Okay? That's how the density function looks like when you plot it.

905
01:50:12.700 --> 01:50:18.749
Faculty (Olympus): And, of course, when you integrate this, again, over the entire rail line, you will get one.

906
01:50:18.870 --> 01:50:28.130
Faculty (Olympus): So the area under the curve is going to be 1. If you want to find the CDF, there is no closed form for this CDF, which means we can't do, like, an integralâ€¦

907
01:50:28.750 --> 01:50:40.730
Faculty (Olympus): any partial integral of thisâ€¦ of this function, erase to minus X squared. There is no closed form for that, unlike the uniform distribution or the exponential distribution, for example.

908
01:50:41.360 --> 01:50:50.840
Faculty (Olympus): And then, yeah, then I was just describing that this Gaussian distribution is widely used, especially to model noise in various kinds of systems.

909
01:50:51.960 --> 01:51:00.599
Naina Punjwani .: Okay, so the examples would be related to, or the sums which we would do will be related to something like noise frequency or something?

910
01:51:01.690 --> 01:51:02.280
Faculty (Olympus): I mean,

911
01:51:02.280 --> 01:51:03.710
Naina Punjwani .: Sound waves or something?

912
01:51:03.710 --> 01:51:16.610
Faculty (Olympus): Yeah, so for example, in communication systems, if you transmit something, what you receive is that thing, whatever signal you have transmitted, plus some noise. So this Gaussian distribution is used often to model that noise.

913
01:51:16.770 --> 01:51:25.230
Faculty (Olympus): and similarly, in linear regression, for example, you have labels, and they have some relationship

914
01:51:25.390 --> 01:51:36.839
Faculty (Olympus): to the features, and the relationship, again, is someâ€¦ there might be some functional relationship plus some noise. And again, Gaussian distribution is used to model that noise value.

915
01:51:39.190 --> 01:51:55.829
Naina Punjwani .: So, that's what my question is. Are we going to have sums related to this as well? Because, we didn't discuss on any, sums or implementation of this, formula, so is it something like noise suppression, sums, or something would come in for this?

916
01:51:55.830 --> 01:52:02.020
Faculty (Olympus): No, so usuallyâ€¦ I mean, it will, again, be maybe something like, you know, you might have aâ€¦

917
01:52:02.220 --> 01:52:10.869
Faculty (Olympus): A Gaussian distributed random variable, and maybe we'll askâ€¦ we might ask something like.

918
01:52:11.330 --> 01:52:13.080
Faculty (Olympus): Okay, what is the prob- soâ€¦

919
01:52:13.200 --> 01:52:32.039
Faculty (Olympus): For example, it could be something of the form, what is the probability that, what you receive is more than some number, or we'll see later on that when you do estimation with caution, noise, there is a certain kind of, estimator that comes up.

920
01:52:32.360 --> 01:52:40.220
Faculty (Olympus): So, what would be the value of that estimator? And things of that kind. So, something that uses this Gaussian distribution density.

921
01:52:40.480 --> 01:52:57.350
Faculty (Olympus): Of course, you can't, like I said, you don't have closed form for the CDF, so maybe there will be numerical values that we provide for the CDF distributionâ€¦ for the CDF function, and then you have to just do some computations using that. Maybe that might be one kind of question that comes up.

922
01:52:59.220 --> 01:53:00.310
Naina Punjwani .: Okay, thank you.

923
01:53:00.310 --> 01:53:05.199
Faculty (Olympus): Yeah, yeah, so as we go along, we'll see some of theseâ€¦ how these densities play a role.

924
01:53:06.520 --> 01:53:07.890
Faculty (Olympus): In various things.

925
01:53:09.090 --> 01:53:26.159
Naina Punjwani .: So, just to add on to this, so, Professor, when we are saying on the syllabus part for the midterm, so, the one you teach, but one the, which, you know, TA has reached. So, the syllabus would be till where the TA has reached, right? Notâ€¦

926
01:53:26.320 --> 01:53:29.719
Naina Punjwani .: The one still syllabus, where you have reached.

927
01:53:30.540 --> 01:53:38.939
Faculty (Olympus): Not quite. We haven't made any decision on that. We will try and keep the TA sessions also in line with

928
01:53:39.230 --> 01:53:52.290
Faculty (Olympus): what we are covering. So, I might not doâ€¦ I mean, I mightâ€¦ if we haven't reached a TA session where we have covered these topics, then I'll just maybe do some things on my own here as well.

929
01:53:52.580 --> 01:53:58.160
Faculty (Olympus): But, usually we'll keepâ€¦ try and keep the TA sessions also in line with

930
01:53:58.260 --> 01:54:04.350
Faculty (Olympus): What we have covered. So, for example, today TAs are also going to do some amount of random variables, and so on.

931
01:54:06.250 --> 01:54:11.989
Naina Punjwani .: Okay. Yeah. But those are basic sums, which might not include these, portion.

932
01:54:12.090 --> 01:54:12.630
Naina Punjwani .: Awesome.

933
01:54:12.630 --> 01:54:18.370
Faculty (Olympus): Maybe, yeah, they'll probably be more about probability mass function and discrete random variables than continuous.

934
01:54:18.730 --> 01:54:31.569
Faculty (Olympus): But, yeah, we will also post, for example, the next, homework and more problem, sums, so that by next TA session, you would be solving things related to

935
01:54:31.830 --> 01:54:33.990
Faculty (Olympus): Continuous distributed random variants.

936
01:54:36.230 --> 01:54:36.989
Naina Punjwani .: Good, thank you.

937
01:54:36.990 --> 01:54:43.429
Faculty (Olympus): Yeah, I mean, yeah, don't worry. In terms of the exam, youâ€¦ we will cover topics where you have had practice.

938
01:54:46.380 --> 01:54:47.050
Faculty (Olympus): Yeah.

939
01:54:48.300 --> 01:54:52.000
Faculty (Olympus): Okay, yeah, Prachiki Kumari?

940
01:54:52.650 --> 01:55:06.190
Lad Prachikumari Vijaykumar .: Sir, here written sigma greater than 0, but if all of our, our X value is, same as this, mu, then sigma square should be 0, right?

941
01:55:08.190 --> 01:55:10.599
Faculty (Olympus): No, so Sigma is,

942
01:55:10.870 --> 01:55:19.369
Faculty (Olympus): a parameter that is, that defines the Gaussian distributed, no, the Gaussian distribution. So, I mean, ifâ€¦

943
01:55:19.900 --> 01:55:28.990
Faculty (Olympus): if you have a dataset where all the values are mu, there is nothing really random about it then, right? I would not use a Gaussian distribution to model that dataset.

944
01:55:29.300 --> 01:55:31.879
Faculty (Olympus): If there isâ€¦ if everything isâ€¦ isâ€¦

945
01:55:32.130 --> 01:55:39.219
Faculty (Olympus): mu, then really is Gaussian distribution a good model? Is anyâ€¦ there doesn't seem to be any randomness in the system then, right?

946
01:55:39.710 --> 01:55:41.160
Lad Prachikumari Vijaykumar .: Okay.

947
01:55:41.160 --> 01:55:42.510
Faculty (Olympus): I wouldn't use that then.

948
01:55:43.750 --> 01:55:48.639
Lad Prachikumari Vijaykumar .: Okay, okay, so itâ€¦ so it always greater than Z.

949
01:55:48.640 --> 01:55:53.919
Faculty (Olympus): Yeah, greater than zero is whatâ€¦ where it makes sense to define something like this.

950
01:55:54.540 --> 01:55:56.629
Lad Prachikumari Vijaykumar .: Okay, okay, thank you, Sinha.

951
01:55:56.630 --> 01:55:57.360
Faculty (Olympus): Okay?

952
01:55:57.800 --> 01:55:59.020
Faculty (Olympus): Harshad?

953
01:56:00.300 --> 01:56:15.890
Harshad Dilip Behere .: Yeah, good afternoon. So, Professor, I might be oversimplifying the thing here, but when we talked about a discrete random variable, it is something like we have a fixed value like integers, right? And when we talked about this continuous, we may have a float value like 0.1, 0.2, 0.3.

954
01:56:16.210 --> 01:56:17.010
Faculty (Olympus): Sure.

955
01:56:17.190 --> 01:56:19.080
Harshad Dilip Behere .: I mean, is that the correct understanding?

956
01:56:19.080 --> 01:56:23.810
Faculty (Olympus): I mean, yeah, so you don't have, like, a countable set of

957
01:56:24.030 --> 01:56:36.340
Faculty (Olympus): or a finite set of possibilities now. You have an uncountableâ€¦ uncountably infinite number of possibilities. Whenever that happens, that's when you have continuous distribution.

958
01:56:36.410 --> 01:56:42.839
Harshad Dilip Behere .: And we are in a position to find out the probability of any given point between that start and end, is it?

959
01:56:42.840 --> 01:56:45.689
Faculty (Olympus): I mean, the probability of any given point is zero, right?

960
01:56:45.690 --> 01:56:46.190
Harshad Dilip Behere .: Okay.

961
01:56:46.190 --> 01:56:54.799
Faculty (Olympus): So, if I ask you, you know, you select a random number between 0 to 1, what is the probability that you will select 0.333?

962
01:56:55.320 --> 01:56:59.309
Faculty (Olympus): The probability of selecting exactly 0.333 is 0.

963
01:56:59.750 --> 01:57:06.580
Faculty (Olympus): But if you ask me what is the probability of selecting a number between 0.3 and 0.35, that I can answer.

964
01:57:07.150 --> 01:57:11.170
Harshad Dilip Behere .: So inâ€¦ oh, that is how weâ€¦ I mean, that is inside the continuous random variable.

965
01:57:11.170 --> 01:57:11.960
Faculty (Olympus): Yeah, yeah.

966
01:57:11.960 --> 01:57:13.859
Harshad Dilip Behere .: But in Descript, we have a fixed value, and we.

967
01:57:13.860 --> 01:57:27.950
Faculty (Olympus): So, for discrete, yeah, the way we define things are, okay, these are the possibilities, and that number of possibilities is something that is finite, and for each such possibility, I tell you exactly what the probability is.

968
01:57:27.950 --> 01:57:28.500
Harshad Dilip Behere .: Okay, huh.

969
01:57:28.500 --> 01:57:31.079
Faculty (Olympus): That is just the definition of a discrete random variable.

970
01:57:31.300 --> 01:57:32.080
Harshad Dilip Behere .: Thank you.

971
01:57:32.710 --> 01:57:33.340
Faculty (Olympus): Okay.

972
01:57:34.610 --> 01:57:38.490
Faculty (Olympus): Yes, Savo Suresh?

973
01:57:38.910 --> 01:57:40.790
Savalo Suresh Naroji .: Hey, hi, Seth. Hi.

974
01:57:41.170 --> 01:57:44.619
Savalo Suresh Naroji .: In Gaussian distribution, which we see.

975
01:57:44.760 --> 01:57:50.159
Savalo Suresh Naroji .: Does mu and sigma represent anything, or it can be,

976
01:57:50.160 --> 01:58:07.360
Faculty (Olympus): But they do represent something. So we haven't yet come to that, but mu represents, like, the mean value or the expected value of the random variable. Sigma square represents the variance, or the level of uncertainty that is there. So we will come to those things. Theyâ€¦ theyâ€¦ theyâ€¦

977
01:58:07.430 --> 01:58:13.320
Faculty (Olympus): They'reâ€¦ yeah, they turn out to be something that represent these kind of quantities.

978
01:58:14.320 --> 01:58:19.569
Savalo Suresh Naroji .: So, and in the exponential, does Lambda represent anything?

979
01:58:19.570 --> 01:58:23.139
Faculty (Olympus): So, again, in the exponential case, it turns out that

980
01:58:23.620 --> 01:58:31.400
Faculty (Olympus): the expected value is, like, 1 by lambda. So if lambda is large, then you are more likely to take small values.

981
01:58:31.800 --> 01:58:36.479
Faculty (Olympus): If lambda is small, then you are more likely to take slightly higher values.

982
01:58:37.510 --> 01:58:40.690
Savalo Suresh Naroji .: Meaning, how do we choose Lambda? Is it something like mainâ€¦

983
01:58:40.900 --> 01:58:50.519
Faculty (Olympus): So, again, yeah, so if I had to fit a distribution, one way of fitting that would be I would calculate, like, the average value of my data set.

984
01:58:50.820 --> 01:58:55.430
Faculty (Olympus): And, that I would map to 1 by lambda hat.

985
01:58:55.830 --> 01:59:00.030
Faculty (Olympus): Because 1 by lambda hat is, like, the mean value of an exponential distribution.

986
01:59:02.190 --> 01:59:05.750
Faculty (Olympus): So, that's how I would estâ€¦ I mean, that is one way of estimating lambda.

987
01:59:06.720 --> 01:59:07.910
Savalo Suresh Naroji .: Thanks.

988
01:59:08.770 --> 01:59:11.869
Faculty (Olympus): Okay, yashi Siddharth?

989
01:59:12.260 --> 01:59:20.890
Siddharth Digambar Kulkarni .: Yes, sir, you're saying that, that, that regression part? So, I don't know what is regression, but what I have.

990
01:59:20.890 --> 01:59:22.170
Faculty (Olympus): Then, don't worry about it.

991
01:59:22.170 --> 01:59:34.390
Siddharth Digambar Kulkarni .: But what I understood from this is that suppose we have a set of points, and we make a line to simulate those points, then the deviation of the points from that line

992
01:59:34.540 --> 01:59:38.120
Siddharth Digambar Kulkarni .: He's following. He's following the Ghosh.

993
01:59:38.120 --> 01:59:39.500
Faculty (Olympus): Yeah, yeah, yeah.

994
01:59:39.500 --> 01:59:41.439
Siddharth Digambar Kulkarni .: Okay, okay, right, right.

995
01:59:43.020 --> 01:59:43.590
Faculty (Olympus): Okay.

996
01:59:44.400 --> 01:59:47.880
Faculty (Olympus): Yeahâ€¦ Charles?

997
01:59:50.110 --> 02:00:01.260
Charles Ravi Kiran Mutsu .: Now, Professor, I have a different question. This is regarding submission of the assignment. So, this has to be done in the,

998
02:00:01.760 --> 02:00:15.200
Charles Ravi Kiran Mutsu .: Olympus portal, like, the Greater Portal, right? Like, so it says that there is, like, a test kind of thing, and then it says that you have to upload PDF, which of it is something we have to do, it's a bit confusing.

999
02:00:15.380 --> 02:00:19.889
Faculty (Olympus): Yeah, I think the great learning guys can, answer that.

1000
02:00:19.890 --> 02:00:21.000
Faculty (Olympus): Yeah, man.

1001
02:00:21.000 --> 02:00:21.510
Faculty (Olympus): Yeah.

1002
02:00:22.400 --> 02:00:24.900
Faculty (Olympus): So, if you go in theâ€¦

1003
02:00:25.360 --> 02:00:34.440
Faculty (Olympus): quiz section, like, the first four questions, you have to leave empty, and in the fifth question, they have asked you to upload the PDF submission.

1004
02:00:34.730 --> 02:00:41.899
Faculty (Olympus): So, your handwritten notes or typed notes, whichever you have, in PDF format, you have to submit there, in the fifth question.

1005
02:00:42.100 --> 02:00:42.699
Charles Ravi Kiran Mutsu .: Well, doctor.

1006
02:00:42.700 --> 02:00:44.580
Faculty (Olympus): We'll leave the first four versions empty.

1007
02:00:44.880 --> 02:00:45.420
Charles Ravi Kiran Mutsu .: butter.

1008
02:00:45.670 --> 02:00:50.380
Dinesh Devnath Yadav .: So, in fifth question, right, so do we have the link to upload, right? Correct?

1009
02:00:50.910 --> 02:00:54.840
Dinesh Devnath Yadav .: Only the fifth question. There will be some link, right?

1010
02:00:55.700 --> 02:01:03.279
Faculty (Olympus): Yeah, in that, you will have an option to upload, your submissions. You have to upload in PDF format.

1011
02:01:03.280 --> 02:01:05.359
Dinesh Devnath Yadav .: Okay, okay, got it. Thank you.

1012
02:01:05.360 --> 02:01:13.979
Lad Prachikumari Vijaykumar .: Sir, I added in first four questions, I added, my final answer, so will it be not impact, no?

1013
02:01:14.140 --> 02:01:23.110
Faculty (Olympus): That won't be considered, but it's fine. You can leave empty, write something, it doesn't matter much. We'll be only looking at your PDF.

1014
02:01:23.110 --> 02:01:23.640
Lad Prachikumari Vijaykumar .: Speed to you.

1015
02:01:23.640 --> 02:01:27.090
Faculty (Olympus): And if answers are correct there, we will grade according to that.

1016
02:01:27.270 --> 02:01:29.429
Lad Prachikumari Vijaykumar .: Okay, fine. Yeah, thank you.

1017
02:01:31.710 --> 02:01:32.740
Faculty (Olympus): Okay,

1018
02:01:32.740 --> 02:01:34.460
Savalo Suresh Naroji .: There are only 4 questions.

1019
02:01:36.710 --> 02:01:44.869
Faculty (Olympus): Yeah, yeah, so I think what he's saying is, the four questions are stated there, just ignore those four, go to the fifth question, and upload your PDF there.

1020
02:01:52.750 --> 02:01:57.489
Faculty (Olympus): Ravi Kumar, do you have a question?

1021
02:01:59.640 --> 02:02:01.040
Faculty (Olympus): Okay, Anne?

1022
02:02:01.840 --> 02:02:07.510
Ann G. .: Sir, I was just wondering why Olympus has such a complicated system for submitting the homework.

1023
02:02:09.300 --> 02:02:13.109
Faculty (Olympus): Okay, I'll let great learning guys handle that, yeah.

1024
02:02:13.110 --> 02:02:14.280
Ann G. .: Okay, thank you.

1025
02:02:15.030 --> 02:02:15.660
Faculty (Olympus): Richard.

1026
02:02:18.300 --> 02:02:20.360
Faculty (Olympus): Rahul,

1027
02:02:20.360 --> 02:02:31.360
Rahul Joshi .: Yes, sir, yeah. So if you go to the Gaussian distribution, where there is a bell curve, so, in theâ€¦ I have a question about the values which are negative.

1028
02:02:31.370 --> 02:02:32.280
Faculty (Olympus): Yup.

1029
02:02:32.280 --> 02:02:37.440
Rahul Joshi .: What exactly it means, like, the area below the negative part of the bell curve?

1030
02:02:37.630 --> 02:02:38.220
Rahul Joshi .: Well, soâ€¦

1031
02:02:38.220 --> 02:02:42.499
Faculty (Olympus): So, I mean, the bell curve itself, meaning the density value is not negative.

1032
02:02:42.920 --> 02:02:43.300
Rahul Joshi .: Yep.

1033
02:02:43.300 --> 02:02:48.479
Faculty (Olympus): Right? It is theseâ€¦ these valâ€¦ the X values are negative here.

1034
02:02:48.720 --> 02:02:52.889
Faculty (Olympus): Right? But the value of the density function is still positive here.

1035
02:02:53.310 --> 02:02:54.760
Rahul Joshi .: Yeah, so my question is.

1036
02:02:54.760 --> 02:02:55.930
Faculty (Olympus): Everything hereâ€¦

1037
02:02:57.250 --> 02:03:11.440
Rahul Joshi .: Yeah, so the probability will be more than zero, that is understood, but my question is, whenever we are taking an example of a height, okay, where the heights can vary, what is theâ€¦ see, because there will be a situation where the values will never be negative, right?

1038
02:03:11.670 --> 02:03:12.320
Faculty (Olympus): Sure.

1039
02:03:12.680 --> 02:03:13.940
Rahul Joshi .: In that case, is it likeâ€¦

1040
02:03:13.940 --> 02:03:22.870
Faculty (Olympus): For example, height, and you say, if you try and model the height as a Gaussian distribution.

1041
02:03:22.940 --> 02:03:40.989
Faculty (Olympus): That itself might not be, let's say, if you ask me, is it exactly a good model, then maybe not, because heights can never be negative, so maybe that is not a good model. But one thing that you can do is you can think of, like, the average, suppose, you know, you have,

1042
02:03:41.000 --> 02:03:44.150
Faculty (Olympus): N people. X1, X2, Xn.

1043
02:03:44.180 --> 02:03:48.400
Faculty (Olympus): Right? Maybe I'll take the average of these guys, let's call that X bar.

1044
02:03:48.560 --> 02:03:53.209
Faculty (Olympus): And I will model the deviation from X bar as Gaussian. Soâ€¦

1045
02:03:53.320 --> 02:03:57.360
Faculty (Olympus): the height of any individual minus X bar.

1046
02:03:57.640 --> 02:03:59.680
Faculty (Olympus): This I will model as a Gaussian.

1047
02:03:59.910 --> 02:04:13.829
Faculty (Olympus): Now, this can be either positive or negative, right? Height can be that larger than X bar or smaller than X bar, and maybe this is a better model for the Gaussian, or a better fit to Gaussian than just the height itself, because like you said.

1048
02:04:14.020 --> 02:04:24.320
Faculty (Olympus): Heights cannot be negative, so if I am being really, you know, strict about it, then maybe Gaussian is not exactly a good fit for that.

1049
02:04:24.840 --> 02:04:42.419
Faculty (Olympus): But, sometimes you still modelâ€¦ model it because the probability of going really negative is going to be small, and so on. I mean, so yeah, it depends. But if I have to be consistent, really, I really want to be consistent, then one way of doing that is maybe look at the deviation from the average.

1050
02:04:42.740 --> 02:04:46.710
Faculty (Olympus): And then use that as your Gaussian distribution.

1051
02:04:47.060 --> 02:05:02.110
Rahul Joshi .: So, so is itâ€¦ is it a very strict rule that if there are values, let's say if you are just doing height, not the difference between the mean and height, then if itâ€¦ if the possibility of negative values is zero, then we should not use Gaussian. Is itâ€¦ is it that strict, orâ€¦

1052
02:05:02.110 --> 02:05:18.240
Faculty (Olympus): So, itâ€¦ I mean, it matters. What it depends on is, yeah, it's up to you, you know? People do model things which are not necessarily going to be negative also as Gaussians, under kind of the assumption that, you know.

1053
02:05:18.350 --> 02:05:27.090
Faculty (Olympus): Your mu is large enough such that the density values, or the area under the curve beyond, which is in the negative part, is going to actually be very small.

1054
02:05:27.230 --> 02:05:36.869
Faculty (Olympus): So maybe it won't matter when you're doing the calculations. But if youâ€¦ I mean, it is up to me, right? If I'm really trying to be strict about it, then I would

1055
02:05:37.030 --> 02:05:39.960
Faculty (Olympus): Kind of maybe subtract out the mean, and then look at

1056
02:05:40.260 --> 02:05:44.510
Faculty (Olympus): That part and seeâ€¦ because that can then go both ways.

1057
02:05:44.950 --> 02:05:47.089
Rahul Joshi .: Okay, makes sense, yeah. Excellent.

1058
02:05:47.750 --> 02:05:50.500
Faculty (Olympus): Okay, Anne, do you still have a question?

1059
02:05:51.670 --> 02:05:53.069
Ann G. .: No, sorry. Aloha.

1060
02:05:53.750 --> 02:05:55.340
Faculty (Olympus): Alright,

1061
02:05:56.840 --> 02:06:07.349
Faculty (Olympus): I'll end then, and yeah, I'll see you guys on Tuesday. You do have your TA sessions today and tomorrow, so please do try and attend that.

1062
02:06:07.620 --> 02:06:08.430
Faculty (Olympus): Thank you so much.

1063
02:06:08.840 --> 02:06:09.750
Dinesh Devnath Yadav .: Thank you, Tyler.

1064
02:06:09.750 --> 02:06:12.250
Faculty (Olympus): Yeah, thanks. Okay, bye.

1065
02:06:12.470 --> 02:06:13.340
Ravi Kumar Pathak .: Thank you.

