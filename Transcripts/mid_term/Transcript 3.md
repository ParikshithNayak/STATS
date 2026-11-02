WEBVTT

1
00:05:27.190 --> 00:05:32.980
Faculty (Olympus): Hi, is anyone there from the Great Learning Team, or any of the TAs?

2
00:05:49.340 --> 00:05:52.449
Faculty (Olympus): Am I audible? Can someone confirm?

3
00:05:52.920 --> 00:05:53.830
Anita Menon .: Yes, you're audible.

4
00:05:53.830 --> 00:05:54.480
Snehal Mane: Yes, profile.

5
00:05:54.480 --> 00:05:55.530
Boopathy Sivathanu .: Costa, yes.

6
00:05:55.530 --> 00:06:00.640
Faculty (Olympus): Okay? And, can you please also let me share my screen andâ€¦

7
00:06:16.250 --> 00:06:19.500
Faculty (Olympus): Duh, you can see my screen,

8
00:06:25.810 --> 00:06:26.520
Simit Bhargava .: Yes.

9
00:06:27.300 --> 00:06:28.660
Faculty (Olympus): Okay,

10
00:06:35.320 --> 00:06:37.530
Faculty (Olympus): For some reason, this is notâ€¦

11
00:09:06.690 --> 00:09:09.120
Simit Bhargava .: Professor, if you're speaking, you're not audible.

12
00:09:10.110 --> 00:09:15.170
Faculty (Olympus): No, no, I'm not. We'll start in a couple of minutes.

13
00:11:34.920 --> 00:11:41.010
Faculty (Olympus): Okay, soâ€¦ Good morning, everyone. Let's, begin.

14
00:11:41.490 --> 00:11:50.469
Faculty (Olympus): So, last time, we saw, we defined the notion of a probability space.

15
00:11:50.980 --> 00:12:03.570
Faculty (Olympus): Right, and this included a sample space omega, which contains the various observations that we can see, or the collection of observations that we can make from our random experiment.

16
00:12:03.810 --> 00:12:10.679
Faculty (Olympus): Then we had, F, which was the collection of events. Every event was, like, a subset

17
00:12:10.940 --> 00:12:18.770
Faculty (Olympus): omega and F was, like, a collection of events to which we assignâ€¦ want to assign probability, or the events that we are interested in.

18
00:12:19.020 --> 00:12:31.490
Faculty (Olympus): And then we had a notion of a probability measure, which assigns values to these events, and we saw that this probability measure is a function which has to satisfy some properties.

19
00:12:31.660 --> 00:12:32.490
Faculty (Olympus): Right.

20
00:12:32.970 --> 00:12:49.559
Faculty (Olympus): So, we did that, and then we saw that, we just, defined, the three properties, or three axioms, and, the first one was just that, the probability assigned to the null set has to be zero, second one was

21
00:12:49.590 --> 00:12:53.360
Faculty (Olympus): That the probability assigned to the entire universe

22
00:12:53.460 --> 00:12:56.540
Faculty (Olympus): Or the sample space has to be 1, and the third one

23
00:12:56.810 --> 00:13:01.260
Faculty (Olympus): was, that if A and B are disjoint.

24
00:13:01.550 --> 00:13:07.439
Faculty (Olympus): then A union B has to have a probability which is the sum of the two.

25
00:13:07.800 --> 00:13:11.690
Faculty (Olympus): This is ifâ€¦ A, B, are disjoint.

26
00:13:12.380 --> 00:13:13.090
Faculty (Olympus): Right.

27
00:13:13.200 --> 00:13:24.529
Faculty (Olympus): So on the basis of these, we then looked at a few more properties. For example, we saw that then any probability measure has to satisfy

28
00:13:24.700 --> 00:13:31.310
Faculty (Olympus): this property corresponding to the complement of an event. And, also, if

29
00:13:31.430 --> 00:13:37.229
Faculty (Olympus): A is a subset of B, then any probability measure has to satisfy

30
00:13:38.390 --> 00:13:45.099
Faculty (Olympus): this property as well. And then the final thing we had seen was this notion of

31
00:13:45.570 --> 00:13:55.970
Faculty (Olympus): In general, if A and B are non-disjoint, then probability of A union B is PA plus PB minusâ€¦

32
00:13:56.090 --> 00:13:58.140
Faculty (Olympus): B, A. Intersection B.

33
00:13:59.110 --> 00:14:09.239
Faculty (Olympus): Okay, so these are some properties. Now, here we were looking at the union of two events, and I had mentioned that in general, if,

34
00:14:09.740 --> 00:14:21.840
Faculty (Olympus): there is, there are more thanâ€¦ if you're looking at the probability associated with the union of more than, two events, there is this inclusion-exclusion formula. So let's maybeâ€¦ that'sâ€¦ that'sâ€¦

35
00:14:21.880 --> 00:14:30.889
Faculty (Olympus): That can be our starting point today. So this is something that I'll just mention. This is there in the notes, but I just want to mention this inclusion.

36
00:14:31.690 --> 00:14:33.100
Faculty (Olympus): Exclusion.

37
00:14:34.080 --> 00:14:38.950
Faculty (Olympus): formula. So, what it allows you to do is it allows you to express

38
00:14:39.570 --> 00:14:44.480
Faculty (Olympus): the probability of the union of any n events.

39
00:14:45.050 --> 00:14:53.829
Faculty (Olympus): as, so this can be written as the sum of individual PAIs, so I going from 1 to N.

40
00:14:53.970 --> 00:15:00.370
Faculty (Olympus): So your first term is positive, then you subtract something from it. So the second one is minus

41
00:15:00.660 --> 00:15:04.010
Faculty (Olympus): You will subtract over all pairs.

42
00:15:05.220 --> 00:15:21.029
Faculty (Olympus): AI intersection A. So, the probability of the pairwise intersection, you will subtract that out. So, if there are n, overall events, then the number of elements that are there in this sum is going to be N choose 2.

43
00:15:21.230 --> 00:15:23.469
Faculty (Olympus): Right? All possible pairs.

44
00:15:23.800 --> 00:15:30.039
Faculty (Olympus): Then, you will add to this the sum of all possible triples.

45
00:15:31.340 --> 00:15:49.759
Faculty (Olympus): AI intersection Aj intersection AK. And you will keep going on. So you will keep having these alternating terms, one with a negative sign, then a positive sign, then a negative sign again, and so on, till the last one, which is going to be minus 1 to the power n plus 1.

46
00:15:50.440 --> 00:15:51.520
Faculty (Olympus): timesâ€¦

47
00:15:54.730 --> 00:16:03.050
Faculty (Olympus): Summationâ€¦ A1, intersection A2, till intersection AN.

48
00:16:03.420 --> 00:16:08.369
Faculty (Olympus): Okay, sorry, there is no sum here, there is only one term, which is the last term.

49
00:16:09.130 --> 00:16:17.070
Faculty (Olympus): This is justâ€¦ one term, which just corresponds to the intersection of all theâ€¦ all the n, elements.

50
00:16:17.190 --> 00:16:34.100
Faculty (Olympus): Right? So, you'reâ€¦ you are trying to compute the probability of the union of n events, right? And so that can be expressed as first probâ€¦ individual probabilities, some of the individual probabilities, then you subtract from those

51
00:16:34.890 --> 00:16:46.420
Faculty (Olympus): the sum of the pairwise intersections, then you add back the sum of the pairwiseâ€¦ some of the triples, and so on. So you keep flipping, and this is, like, an exact formula.

52
00:16:46.550 --> 00:16:58.339
Faculty (Olympus): Now, where willâ€¦ firstly, I mean, a few things to note here. One, if you really have to compute this probability, you can see that if n is large, this is going to be a mess to compute.

53
00:16:58.660 --> 00:17:05.779
Faculty (Olympus): Right? But it is an exact formula. If you have enough computation power, you can do all of these.

54
00:17:05.910 --> 00:17:12.549
Faculty (Olympus): Where will it be used? So, we were talking about these balls and bins type of problems, right? So, suppose if you have

55
00:17:13.050 --> 00:17:15.740
Faculty (Olympus): A hundred balls.

56
00:17:16.050 --> 00:17:20.280
Faculty (Olympus): And you are placing them in some 20 bins.

57
00:17:20.349 --> 00:17:23.730
Faculty (Olympus): At random. So every ball, you're choosing one of the 20 bins.

58
00:17:23.790 --> 00:17:40.649
Faculty (Olympus): and you are placing, them in random, and you are interested in probableâ€¦ of the probability that there exists, okay, thisâ€¦ this notation is, there exists, this, kind of flipped E isâ€¦ is a notation for there exists, an empty pin.

59
00:17:42.210 --> 00:17:42.980
Faculty (Olympus): Right?

60
00:17:43.220 --> 00:17:53.490
Faculty (Olympus): So, we were writing this as the probability of a union of events corresponding to each individual bin being empty. So now there are going to be

61
00:17:53.870 --> 00:17:55.880
Faculty (Olympus): 20 such events.

62
00:17:56.100 --> 00:17:56.890
Faculty (Olympus): Right?

63
00:17:57.010 --> 00:18:08.709
Faculty (Olympus): So, there are 20 bins. Each of the bins could potentially be empty, and I want to find the probabilityâ€¦ I want to find exactly this probability. Now, if I wanted to find this probability, you can.

64
00:18:08.710 --> 00:18:21.289
Faculty (Olympus): But then you will have to compute all of these terms. There are going to be 20 such. First, there will be the individual probabilities, then the pairwise probabilities, then the triples, and so on, till the intersection of 20 events.

65
00:18:21.310 --> 00:18:26.819
Faculty (Olympus): Right? So you can see, if you want to really compute it, you can, but it is going to be a mess.

66
00:18:27.080 --> 00:18:31.310
Faculty (Olympus): Which is why we often use the tool of bounds.

67
00:18:31.540 --> 00:18:34.080
Faculty (Olympus): Okay, we often use the tool of bounds.

68
00:18:34.550 --> 00:18:42.049
Faculty (Olympus): We won't work, directly with this formula, but instead we'll work with upper bounds and lower bounds

69
00:18:42.270 --> 00:18:43.760
Faculty (Olympus): on this quantity.

70
00:18:44.300 --> 00:18:53.820
Faculty (Olympus): Now, this inclusion-exclusion principle, one, it gives you, like, an exact formula, but the other thing which it also gives you is that it gives you directly bounds as well.

71
00:18:53.980 --> 00:19:00.669
Faculty (Olympus): How does that work? So, it works in the following way. If you only include the first term, which is

72
00:19:01.180 --> 00:19:02.890
Faculty (Olympus): Which is this part.

73
00:19:03.110 --> 00:19:05.210
Faculty (Olympus): Yeah, you ignore everything else.

74
00:19:06.830 --> 00:19:20.119
Faculty (Olympus): Then it turns out that just taking this part is an upper bound on the original term, on the LHS, on the left-hand side. Okay, if you only take the sum of the probabilities, individual probabilities, then it turns out that's an upper bound.

75
00:19:20.570 --> 00:19:24.619
Faculty (Olympus): If you take the first summation and also

76
00:19:24.970 --> 00:19:31.269
Faculty (Olympus): the second summation, meaning you are subtracting something from it, right? Then it turns out it's a lower bound.

77
00:19:31.530 --> 00:19:38.539
Faculty (Olympus): And you can keep going on. If you also include the third term, then it is again an upper bound, and so on.

78
00:19:38.660 --> 00:19:50.100
Faculty (Olympus): Okay, so I will just maybe quickly write this down. These are called These are calledâ€¦ theâ€¦ Bornâ€¦

79
00:19:50.930 --> 00:19:54.140
Faculty (Olympus): Perroniâ€¦ inequalities.

80
00:19:54.810 --> 00:20:08.439
Faculty (Olympus): Okay, and all they say is that if you keep adding and subtraâ€¦ if you keep taking, different terms from the inclusion-exclusion formula, you keep getting upper and lower bounds, okay? So, the first one.

81
00:20:08.560 --> 00:20:15.679
Faculty (Olympus): is calledâ€¦ also called the union bound, where you only take the first summation. So it says the probability of the union

82
00:20:15.870 --> 00:20:18.049
Faculty (Olympus): It's always less than equal to

83
00:20:18.320 --> 00:20:21.430
Faculty (Olympus): The summation of the individual probabilities.

84
00:20:22.660 --> 00:20:31.469
Faculty (Olympus): The second Bonferroni inequality is a lower bound. It says, okay, now if you take

85
00:20:32.870 --> 00:20:38.010
Faculty (Olympus): The first term, but you also take the second term, so you're subtracting something, right?

86
00:20:38.940 --> 00:20:51.849
Faculty (Olympus): So, it's going to be greater than equal to the summation of PAIs, minusâ€¦ The pairwise intersection probabilities.

87
00:20:52.040 --> 00:20:56.820
Faculty (Olympus): If you go further, so if you look at the third Bonferroni, that means

88
00:20:57.370 --> 00:21:02.630
Faculty (Olympus): That you are including the first three summations, then it's again an upper bound.

89
00:21:04.120 --> 00:21:10.560
Faculty (Olympus): So it's less than equal to summation PAI minus mission P.

90
00:21:12.720 --> 00:21:14.549
Faculty (Olympus): plus the triples.

91
00:21:19.750 --> 00:21:28.609
Faculty (Olympus): Okay? So what it helps you do is, it's very difficult to compute the inclusion-exclusion principle directly, so often we use the medium of

92
00:21:28.610 --> 00:21:40.560
Faculty (Olympus): bounds to get an idea of what that probability is, okay? We can't get the exact value, it's too complicated, so we instead use upper and lower bounds to kind of get a sense of where this probability lies.

93
00:21:40.560 --> 00:21:53.150
Faculty (Olympus): Okay? So, let's look at, for example, the particular example that we were talking about. So, 100 balls, 20 bins. It's very difficult, like I said, if you want to compute exactly the probability of

94
00:21:53.260 --> 00:22:06.610
Faculty (Olympus): of an empty bin, but let's see if we can use these union bounds and the second bond Feroni, and so on, howâ€¦ what kind of bounds do they give us, right? So, for example.

95
00:22:07.240 --> 00:22:15.580
Faculty (Olympus): Let's try and do that. So again, just to recall, we haveâ€¦ 100 balls.

96
00:22:15.810 --> 00:22:21.280
Faculty (Olympus): Each ball is dropped into 1 out of the 20 bins at random.

97
00:22:21.640 --> 00:22:29.530
Faculty (Olympus): Right? So, what willâ€¦ what will the union bound tell me? It says that the probability of there being an empty bin

98
00:22:30.610 --> 00:22:40.190
Faculty (Olympus): So, i equals 1 to 20 is less than equal toâ€¦ Summation ofâ€¦ Each individual bin being empty.

99
00:22:40.410 --> 00:22:43.920
Faculty (Olympus): What will the probability of a particular bin being empty?

100
00:22:44.080 --> 00:22:50.079
Faculty (Olympus): So, let's say if I was 1. So, what is the probability that the first bin is empty?

101
00:22:50.770 --> 00:22:55.110
Faculty (Olympus): Right? The probability that the first bin is empty is that

102
00:22:55.330 --> 00:23:07.840
Faculty (Olympus): The first ball should select 1 out of the other 20 bins, so anything apart from bin 1 should be selected. Similarly, the second ball should also select any one out of the remaining 19 bins.

103
00:23:07.840 --> 00:23:15.870
Faculty (Olympus): Third ball should select any one out of the remaining 19 bins, right? It should not select the first bin. So it'll be this to the power 100.

104
00:23:15.870 --> 00:23:24.769
Faculty (Olympus): all of these values are going to be the same. So probability of A2 will also be the same, probability of A3 will also be the same. So the upper bound will just be

105
00:23:25.720 --> 00:23:27.540
Faculty (Olympus): 20 times.

106
00:23:27.650 --> 00:23:34.049
Faculty (Olympus): 19 by 20 to the power 100, which, roughlyâ€¦

107
00:23:34.170 --> 00:23:39.679
Faculty (Olympus): I had done this calculation beforehand. This is roughly 0.118.

108
00:23:40.240 --> 00:23:48.359
Faculty (Olympus): Okay, so this is telling me that the probability that there exists an empty bin is upper bounded by 0.118.

109
00:23:48.780 --> 00:23:54.409
Faculty (Olympus): Okay? What about a lower bound? So I can use the second Gonferroni to get a lower bound.

110
00:23:54.790 --> 00:24:02.850
Faculty (Olympus): So this is greater than equal to this first term, right? The summation, PAIs.

111
00:24:07.180 --> 00:24:11.260
Faculty (Olympus): But then, you haveâ€¦ the intersections.

112
00:24:12.310 --> 00:24:15.639
Faculty (Olympus): Right, and this is over all pairs.

113
00:24:15.930 --> 00:24:27.039
Faculty (Olympus): So, again, the first term we saw is roughly 0.118. What can we say about the second term? So, there are going to be, 20 choose 2 terms.

114
00:24:27.260 --> 00:24:37.800
Faculty (Olympus): terms in that summation, all of them are going to be the same. Now, so let's think about what is the probability of bin 1 being empty and bin 2 being empty.

115
00:24:37.980 --> 00:24:47.480
Faculty (Olympus): So both bin 1, no balls land in bin 1, no balls land in bin 2. Both of these have to be true. So that, again, means that they haveâ€¦ each ball has to land in

116
00:24:47.680 --> 00:24:55.449
Faculty (Olympus): one of the 18 bins, so 18 by 20 to the bar 100. Okay, so this is going to be 18 by 20â€¦

117
00:24:55.820 --> 00:24:57.530
Faculty (Olympus): To the power 100.

118
00:24:57.910 --> 00:25:00.760
Faculty (Olympus): So, you are going to do 0.118 minusâ€¦

119
00:25:01.570 --> 00:25:13.160
Faculty (Olympus): This number, again, one can do that computation, it turns out roughly to be 0.11, I think 33, yeah.1133.

120
00:25:13.290 --> 00:25:20.150
Faculty (Olympus): Okay, so what this is saying, theseâ€¦ just using these two inequalities, we have that the probability of the union

121
00:25:20.430 --> 00:25:27.520
Faculty (Olympus): Is less than equal to 0.118, and it is greater than equal to 0.1133.

122
00:25:27.980 --> 00:25:42.790
Faculty (Olympus): Okay? So, for that, we didn't have to compute the entire inclusion-exclusion principle. Already, these are quite close. In fact, if you do the full computation, it turns out that the exact value is roughly 0.1134.

123
00:25:43.240 --> 00:25:51.960
Faculty (Olympus): Okay, so you are quite, quite close already by just using, these two bounds. Okay, so these bounds are really, really useful.

124
00:25:52.100 --> 00:26:04.020
Faculty (Olympus): to get a sense of these probabilities without actually doing the full computation of the union, okay? So that's the main, idea.

125
00:26:04.650 --> 00:26:13.590
Faculty (Olympus): I can, I'll take a few quick questions. We are now done in terms of what I wanted to say for the probability space.

126
00:26:14.000 --> 00:26:19.919
Faculty (Olympus): and general properties of probability spaces. We will now move on to the notion of

127
00:26:20.110 --> 00:26:30.410
Faculty (Olympus): of, conditional, probability, okay? So that's where, we will go to, Next.

128
00:26:32.380 --> 00:26:39.480
Faculty (Olympus): Okay, let's see, yeah, PALAK?

129
00:26:49.870 --> 00:26:52.779
Faculty (Olympus): Palak, I'm unable to hear you,

130
00:26:53.040 --> 00:26:57.819
Faculty (Olympus): Maybe we move to someone else, and then you fix and come back? Gaurav?

131
00:26:58.650 --> 00:27:07.739
Gaurav Singh .: Yes, soâ€¦ in the, in the overall formula, you have mentioned, can you go up where you have mentioned the formula for theâ€¦

132
00:27:07.740 --> 00:27:08.370
Faculty (Olympus): Yeah.

133
00:27:08.650 --> 00:27:21.900
Gaurav Singh .: inclusion-exclusion principle. Here, the intersection, the two intersection, AI intersection Aj summation, I is less than J. It should be I is not equal to J, right?

134
00:27:22.060 --> 00:27:27.239
Faculty (Olympus): Yeah, so, the thing is that, weâ€¦ so, we are looking,

135
00:27:28.170 --> 00:27:40.409
Faculty (Olympus): only at pairsâ€¦ so, the pair, for example, 1,2 and 2,1 has to be counted exactly once. I don't want to count them separately. Otherwise, that is over-counting, then it's not correct.

136
00:27:40.810 --> 00:27:43.590
Faculty (Olympus): Okay, so that's why this aisle less than J.

137
00:27:43.690 --> 00:27:53.769
Faculty (Olympus): If you think of all pairs, then, you know, if you treat 1,2 and 2,1 as separate pairs, then it's not n choose 2, then it's n times n minus 1, so that's why I listed.

138
00:27:53.770 --> 00:27:56.110
Gaurav Singh .: All the combination will be covered. Okay, got it, got it.

139
00:27:56.110 --> 00:27:56.650
Faculty (Olympus): Same thing.

140
00:27:56.650 --> 00:28:02.290
Gaurav Singh .: And second thing, I understand the, upper bound ofâ€¦

141
00:28:02.490 --> 00:28:19.529
Gaurav Singh .: PAI union, I mean, union of all the AIs, which is less than or equal to summation of probabilities of AIs. Yeah. But lower bound, can you re-explain, please?

142
00:28:19.690 --> 00:28:36.939
Faculty (Olympus): So, okay. So, yeah, I mean, one good thing, that Iâ€¦ you reminded me was, one thing I should point out is, in the notes, this is written as minus 1 to the power n. That's a mistake, it should be minus 1 to the power n plus 1, okay?

143
00:28:36.980 --> 00:28:43.889
Faculty (Olympus): So that's just something, I wanted to highlight. Now, coming toâ€¦

144
00:28:44.010 --> 00:29:02.590
Faculty (Olympus): the upper bound? Yeah, so the upper bound is this quantity, and now ifâ€¦ what we are saying is that if you include the first two terms of theâ€¦ of the inclusion-exclusion, then you get a lower bound, right? Now, it is this quantity minus something.

145
00:29:03.090 --> 00:29:17.150
Faculty (Olympus): So, I'm not giving a proof of this. Thisâ€¦ all of this requires a proof. You have to show that, you know, this is indeed a lower bound, which means all the terms after the pairwise are somehow, positive terms. You have to argue that.

146
00:29:17.300 --> 00:29:19.039
Faculty (Olympus): I'm not proving that here.

147
00:29:19.460 --> 00:29:29.389
Faculty (Olympus): Okay. Okay, so similarly, it turns out that if you then go and also include the third terms, the triples, then you again get an upper bound. All of that requires a proof.

148
00:29:29.820 --> 00:29:31.240
Faculty (Olympus): I'm not proving it.

149
00:29:32.030 --> 00:29:42.430
Rahul Joshi .: So, just one question. So, whenever you say third, upper bound, is it correct understanding that it will be slightly, lower than the first per bound?

150
00:29:42.820 --> 00:29:43.739
Rahul Joshi .: I mean, thatâ€¦

151
00:29:44.020 --> 00:29:56.979
Faculty (Olympus): Notâ€¦ not always. It depends, right, how theseâ€¦ whether the negative part was sufficiently larger than the positive part, then you would have done better than the union bound. So it doesn't always happen that way.

152
00:29:57.300 --> 00:30:06.649
Faculty (Olympus): But all of these, all theâ€¦ the union bound, the third bond Feroni, the fifth bond Ferroni, all of these give upper bounds. You can then choose the best upper bound.

153
00:30:07.160 --> 00:30:10.729
Rahul Joshi .: Okay, so any upper bound can be highest as compared to any previous.

154
00:30:10.730 --> 00:30:15.000
Faculty (Olympus): Yeah, yeah, yeah, yeah, yeah, yeah. So that depends on the actual scenario.

155
00:30:15.780 --> 00:30:17.990
Faculty (Olympus): Okay, yeah, Bipin?

156
00:30:20.220 --> 00:30:25.980
Bipin Karyakarte .: Okay, so, if you can scroll down, and theâ€¦ yeah.

157
00:30:26.200 --> 00:30:44.820
Bipin Karyakarte .: I understood the upper bound concept, but the lower bound concept, I didn't quite get it. Two things. One is that you directly used the Bonferrani inequality number 2, right? Why specifically that? I probably am missing something there.

158
00:30:44.820 --> 00:30:49.659
Faculty (Olympus): So, I mean, the Bonferroni inequality number 2 gives us a lower bound.

159
00:30:49.990 --> 00:31:05.369
Faculty (Olympus): And, you could have used the fourth inequality also, but that would require even more computation, right? Then you will have to also deal with the triples and the intersection of four elements. So I want to use, like, the simplest one, which gives me a lower bound.

160
00:31:05.430 --> 00:31:15.739
Faculty (Olympus): So the simplest one that gives me a lower bound is the second one, where I only have to worry about the marginal probabilities and the probability of pairwise intersections. I don't have to worry about that.

161
00:31:15.740 --> 00:31:19.769
Bipin Karyakarte .: Yeah, and in the last line, you used 18 upon 20, right?

162
00:31:19.770 --> 00:31:20.320
Faculty (Olympus): Yeah, yeah.

163
00:31:20.350 --> 00:31:23.260
Bipin Karyakarte .: Why 18? I missed that part.

164
00:31:23.260 --> 00:31:35.160
Faculty (Olympus): Because we are talking about the event that bin 1 and bin 2 are both empty, which means all balls should beâ€¦ should land up in one of the other 18 bins.

165
00:31:35.160 --> 00:31:35.950
Bipin Karyakarte .: Okay, okay, okay.

166
00:31:35.950 --> 00:31:37.649
Faculty (Olympus): that by 18 upon 20.

167
00:31:38.220 --> 00:31:39.030
Bipin Karyakarte .: Okay, man.

168
00:31:39.030 --> 00:31:41.240
Faculty (Olympus): Okay? Thank you. Abhineet?

169
00:31:42.500 --> 00:31:47.579
Abhineet Bansal: Sir, I just wanted a clarification, what does this 22 represent? I mean, how does that come?

170
00:31:47.990 --> 00:31:51.030
Faculty (Olympus): what represent? 22. For 22 Stu.

171
00:31:51.750 --> 00:31:53.389
Abhineet Bansal: Yeah, how's that?

172
00:31:53.390 --> 00:31:57.269
Faculty (Olympus): Yeah, yeah, so that is, like, the number of, distinct pairs.

173
00:31:57.320 --> 00:32:13.840
Faculty (Olympus): Right? Thisâ€¦ you areâ€¦ you are summing over all possible pairs. So inâ€¦ inâ€¦ amongst 20, you will have pairs i could be 1, J could be 2, I could be 1, J could be 3, i could be 1, J could be 4, and so on. So there are so many pairs, right?

174
00:32:14.400 --> 00:32:19.050
Faculty (Olympus): In, in this summit, How 20 choose 2?

175
00:32:19.750 --> 00:32:20.340
Abhineet Bansal: Yes.

176
00:32:20.340 --> 00:32:26.660
Faculty (Olympus): Yeah, please, look that up. Just look up binomial coefficients, you will see whyâ€¦ where that comes from.

177
00:32:27.870 --> 00:32:32.810
Faculty (Olympus): Just look up binomial coefficients, you will see where this 20 choose 2 comes from.

178
00:32:34.310 --> 00:32:34.980
Faculty (Olympus): Yep.

179
00:32:35.910 --> 00:32:37.570
Faculty (Olympus): Okay, varun?

180
00:32:42.380 --> 00:32:43.890
Faculty (Olympus): varun Kumar.

181
00:32:44.740 --> 00:32:58.980
varun kumar .: Yeah, hi, Profess. So, I just wanted to understand, the practical implication and practical uses of this concept of upper bound and lower bound. Calculation, I mean, theoretically, we are calculating, which is fine.

182
00:32:59.200 --> 00:33:18.139
Faculty (Olympus): Yeah, yeah, I mean, like I said, balls and bins is a problem by itself, which has many, many applications, one of them being load balancing. So, if you were trying to do some load balancing, then you will actually use these calculations, because the number of servers is not going to be just 20.

183
00:33:18.140 --> 00:33:31.420
Faculty (Olympus): Right? In an actual data center, the number of servers runs into the hundreds, the thousands. If I actually have to try and compute the probability of there being an idle server, it's going to be impossible to do.

184
00:33:32.070 --> 00:33:39.280
Faculty (Olympus): So, these bounds are very, very useful, then, to get a sense of, you know, what that quantity is.

185
00:33:40.650 --> 00:33:41.440
varun kumar .: Okay.

186
00:33:41.440 --> 00:33:41.980
Faculty (Olympus): Yeah.

187
00:33:42.420 --> 00:33:44.270
varun kumar .: Are we going to useâ€¦ I'm going further?

188
00:33:44.270 --> 00:33:52.089
Faculty (Olympus): We are, yeah, yeah, yeah, yeah, we are going to be keepâ€¦ I mean, this union bound is going to come up again and again, so you will see many more applications of these things.

189
00:33:52.360 --> 00:33:53.800
varun kumar .: Oh, yeah.

190
00:33:53.800 --> 00:33:55.140
Faculty (Olympus): Okay, Abhishek?

191
00:33:55.700 --> 00:33:57.280
Faculty (Olympus): Abhishek Raghuvanshihi.

192
00:33:58.380 --> 00:34:09.469
Abhishek Raghuvanshi .: Yeah, I'm a bit confused about the final calculation you have done. So, 18 by 20, I have understood, which will be for the probability of each of the pairs, and that is true.

193
00:34:09.670 --> 00:34:16.530
Abhishek Raghuvanshi .: But, I think the number of items in this summation, will theyâ€¦ will they not beâ€¦

194
00:34:16.940 --> 00:34:19.070
Abhishek Raghuvanshi .: I think,

195
00:34:19.429 --> 00:34:20.489
Faculty (Olympus): Again, if the number.

196
00:34:20.489 --> 00:34:21.139
Abhishek Raghuvanshi .: 18?

197
00:34:21.350 --> 00:34:32.749
Faculty (Olympus): No, because you're going over all possible pairs, right? Not just the pair starting with i equals 1. There is also 2,4, 2,5â€¦ like I said, just maybe read up on binomial.

198
00:34:32.750 --> 00:34:35.919
Abhishek Raghuvanshi .: Okay, so that is true for all commissions.

199
00:34:35.920 --> 00:34:36.650
Faculty (Olympus): Yay.

200
00:34:36.650 --> 00:34:37.440
Abhishek Raghuvanshi .: Yep.

201
00:34:37.500 --> 00:34:48.949
Faculty (Olympus): Okay, sorry, so I have to move forward. For the remaining people, I'll take them, take the questions at the end, okay? Okay, so let's, let's go ahead.

202
00:34:51.520 --> 00:34:58.359
Faculty (Olympus): So, we have defined, the notion of, of a probability space.

203
00:34:58.360 --> 00:35:14.149
Faculty (Olympus): Now, often, inâ€¦ or at least inâ€¦ many of the times, we are going to look at, probabilityâ€¦ we'll look at a discrete, probability space. Now, what do I mean by a discrete probability space?

204
00:35:14.190 --> 00:35:20.090
Faculty (Olympus): So often, we will look at scenarios where this omega is either finite.

205
00:35:21.090 --> 00:35:27.059
Faculty (Olympus): Okay? Or even if it is finite, it's like a list, okay? Which is sometimes called countable.

206
00:35:27.450 --> 00:35:41.430
Faculty (Olympus): So, if youâ€¦ so think ofâ€¦ if you don't know what countable is, just think of, like, the set of integers, right? A set of integers is not finite, but it's a list. You can always write it down. So, when that is the case.

207
00:35:41.780 --> 00:35:45.430
Faculty (Olympus): The easiest way to define a probability space

208
00:35:45.560 --> 00:35:57.159
Faculty (Olympus): is that you define the probability associated with the singletons, meaning single elements in your, in your sample space. So, for any i.

209
00:35:57.370 --> 00:36:04.800
Faculty (Olympus): In your sample space, we will have a notion of what the probability associated with just that singleton is.

210
00:36:05.100 --> 00:36:23.820
Faculty (Olympus): And the probability associated with any subset will just be equal to the sum of the probability of the elements which belong to that subset. So, for example, if your subset was, let's say, if your omega was the set of integers, 1, 2,

211
00:36:24.150 --> 00:36:39.079
Faculty (Olympus): 3, and so on, right? This could be, for example, an experiment where I am seeing how many tosses I need before I see the first heads. Then, all of these are possible observations. One toss is needed, or two tosses are needed, third three tosses are needed, and so on.

212
00:36:39.440 --> 00:36:45.189
Faculty (Olympus): And maybe I'll define this probabâ€¦ these PIs, to beâ€¦

213
00:36:45.740 --> 00:36:56.990
Faculty (Olympus): maybe, let's say, 1 by 2 to the N, something like that. So these PIs have to be so that they sum up to 1. I think 1 by 2 to the end sums up to 1.

214
00:36:57.210 --> 00:37:02.750
Faculty (Olympus): Yeah, I think so, but whatever, just choose these, maybe let me not

215
00:37:03.030 --> 00:37:12.460
Faculty (Olympus): write it that way. Let's say I choose it as someâ€¦ some quantity, AN, whichâ€¦ or AI, such that

216
00:37:12.690 --> 00:37:18.589
Faculty (Olympus): the summation of AI when you take i going from 1 to infinity is 1.

217
00:37:18.890 --> 00:37:33.080
Faculty (Olympus): Okay? If you do that, then the probability associated with, let's say, the subset 1,2. So now I'm interested in the event that the number of tosses required to see the first heads was either 1 or 2.

218
00:37:33.540 --> 00:37:38.409
Faculty (Olympus): Then that, we will define asâ€¦ P1 plus P2.

219
00:37:38.630 --> 00:37:45.919
Faculty (Olympus): Similarly, if it wasâ€¦ Let's say the subset was 3, 4, 5â€¦ Then it'll beâ€¦

220
00:37:46.080 --> 00:37:49.510
Faculty (Olympus): P3 plus P4 plus P5.

221
00:37:49.750 --> 00:37:58.340
Faculty (Olympus): Okay? Soâ€¦ This is, like, the most common way of defining a probability space.

222
00:37:58.340 --> 00:38:11.510
Faculty (Olympus): especially when the sample space is either finite, or it can be written down as a list, then you just mentionâ€¦ then the way to define the probability space is you just specify what the Singleton probabilities are.

223
00:38:11.510 --> 00:38:16.550
Faculty (Olympus): And then for any set, you define the probability as just the sum

224
00:38:17.040 --> 00:38:21.950
Faculty (Olympus): Of the individual probabilities of elements belonging to that set.

225
00:38:22.050 --> 00:38:30.060
Faculty (Olympus): Okay? This is not very critical, to understand, but this is just something I want to mention.

226
00:38:30.180 --> 00:38:42.229
Faculty (Olympus): Okay? So now, we are done with this notion of a probability space. I want to define, a notion of conditional probability and talk aboutâ€¦ talk about that.

227
00:38:42.360 --> 00:38:47.090
Faculty (Olympus): Okay, so that is kind of the main thing toâ€¦ main next topic to talk about.

228
00:38:47.770 --> 00:38:49.879
Kedar Digambar Gokhale .: Just a quick one, 3.

229
00:38:50.320 --> 00:38:52.860
Faculty (Olympus): Okay, yeah.

230
00:38:54.300 --> 00:38:59.800
Kedar Digambar Gokhale .: Just a quick one. These individual Singhalton probabilities need not be equal, right?

231
00:38:59.800 --> 00:39:02.329
Faculty (Olympus): No, no, need not be equal, they just have to sum up to 1.

232
00:39:03.370 --> 00:39:04.390
Kedar Digambar Gokhale .: Perfect, thank you.

233
00:39:05.800 --> 00:39:08.470
Faculty (Olympus): Okay, so conditional probability.

234
00:39:10.350 --> 00:39:19.789
Faculty (Olympus): Okay, so what is the notion of conditional probability? Let's say we have a sample space which contains 10 points, okay? And let's sayâ€¦

235
00:39:20.080 --> 00:39:23.820
Faculty (Olympus): That all of these points are equally likely.

236
00:39:26.500 --> 00:39:32.240
Faculty (Olympus): So now I have this discrete probability space, and I'm saying that

237
00:39:32.370 --> 00:39:36.009
Faculty (Olympus): All of these points are equally likely, which means

238
00:39:36.390 --> 00:39:53.860
Faculty (Olympus): think of the random experiment essentially picking one of these points equally likely, okay? One of these points at random. And like we said, the probability associated with any subset or any event is just going to be the size of that event divided by 10.

239
00:39:54.110 --> 00:40:01.549
Faculty (Olympus): Why? Because every element is going to haveâ€¦ every singleton is going to have a probability of 1 by 10.

240
00:40:01.580 --> 00:40:16.579
Faculty (Olympus): And the probability of the event E is just going to be the sum of theseâ€¦ some of the probabilities of the individual singletons. Each individual singleton has probability 1 by 10, so the probability of any event E

241
00:40:17.330 --> 00:40:30.100
Faculty (Olympus): which is a subset of omega is going to be mod E by 10, right? So, for example, if you have, let's say, the event A, which is, like, this subset, okay, this is, let's say, event A.

242
00:40:30.290 --> 00:40:31.100
Faculty (Olympus): A.

243
00:40:31.680 --> 00:40:39.390
Faculty (Olympus): Okay? And, let's say the event B is, this subset.

244
00:40:41.090 --> 00:40:50.299
Faculty (Olympus): Okay, the green one is event B. Then I know that the probability associated with A is 5 by 10, or 1 half.

245
00:40:50.780 --> 00:40:58.550
Faculty (Olympus): And the probability associated with B is 4 by 10, Orâ€¦ 2x5.

246
00:40:59.590 --> 00:41:01.319
Faculty (Olympus): Right? Nowâ€¦

247
00:41:01.330 --> 00:41:11.289
Faculty (Olympus): in conditional probability, we often think about how my beliefâ€¦ I mean, when I say probability of A, that is, like, my belief of

248
00:41:11.290 --> 00:41:31.489
Faculty (Olympus): how likely A isâ€¦ the event A is, to occur, right? If I say the probability of A is 1 half, that is roughly saying that if I conduct, you know, if I do this experiment of choosing a point at random from these 10, and I conduct, let's say, a thousand such experiments one after the other.

249
00:41:31.490 --> 00:41:35.119
Faculty (Olympus): Roughly half of the times, I will pick something from A.

250
00:41:35.490 --> 00:41:47.280
Faculty (Olympus): Similarly, when I say probability of B is 2 by 5, that says that if I again conduct, let's say, this random experiment of picking one of these points at random from this omega.

251
00:41:47.420 --> 00:41:56.309
Faculty (Olympus): a million times, roughly 2 by 5 of that times, I will pick something from B.

252
00:41:56.420 --> 00:42:11.939
Faculty (Olympus): Right? So this is, like, my belief about how likely this event is. And conditional probability isâ€¦ is essentially tells us what isâ€¦ how does our belief change whenâ€¦ about one event, when I know some other event has happened.

253
00:42:12.060 --> 00:42:15.150
Faculty (Olympus): Okay? So let's take these two events, A and B,

254
00:42:15.590 --> 00:42:19.980
Faculty (Olympus): Suppose I tell you that the event B occurred.

255
00:42:20.900 --> 00:42:26.749
Faculty (Olympus): Okay? What does that tell me? That tells me that, one of these four

256
00:42:27.030 --> 00:42:35.419
Faculty (Olympus): elements must have been picked, right? Either this element, or this element, or this element, or this element.

257
00:42:35.880 --> 00:42:47.960
Faculty (Olympus): Right? One of these four elements, must have been picked, and all of these elements are equally likely. So now, if I ask you that given that B occurred.

258
00:42:48.460 --> 00:42:57.800
Faculty (Olympus): Can you say something about, how likely A is to occur? How likely isâ€¦ A.

259
00:42:58.030 --> 00:42:59.030
Faculty (Olympus): to occur.

260
00:43:00.920 --> 00:43:01.460
Faculty (Olympus): Right?

261
00:43:01.460 --> 00:43:01.990
Rahul Joshi .: percent.

262
00:43:01.990 --> 00:43:15.960
Faculty (Olympus): Now, if you knowâ€¦ if you know that B occurred, then, like I said, there areâ€¦ one of these four possibilities must have happened. All of those four possibilities are equal. Two of those possibilities, namely.

263
00:43:16.150 --> 00:43:27.119
Faculty (Olympus): let's say these two, right? Two of those possibilities actually belong to A. Two of them don't belong to A. So the numberâ€¦ number of elements

264
00:43:28.080 --> 00:43:45.329
Faculty (Olympus): that the probability is going to be the number of elements that belong to B, but also belong to A, divided by the number of elements that belong to B, which in this particular case is 2x4 or 1 by 2.

265
00:43:45.440 --> 00:43:49.989
Faculty (Olympus): Right? Soâ€¦ In, in this particular case.

266
00:43:50.130 --> 00:43:58.720
Faculty (Olympus): You write down, this is like aâ€¦ this is like a proxy for what the conditional probability is.

267
00:43:59.350 --> 00:44:01.300
Faculty (Olympus): of A given B.

268
00:44:01.590 --> 00:44:18.729
Faculty (Olympus): Now, if I divide this, the numerator by the size of omega, and I also divide the denominator by the size of omega, then in this particular case, this is exactly the probability of A intersection B divided by the probability of B.

269
00:44:19.750 --> 00:44:24.660
Faculty (Olympus): Okay? And this quantity is defined As?

270
00:44:24.860 --> 00:44:29.120
Faculty (Olympus): the conditional probability of A given B.

271
00:44:29.990 --> 00:44:34.630
Faculty (Olympus): Okay? So, theâ€¦ The definition of

272
00:44:34.740 --> 00:44:45.909
Faculty (Olympus): The conditional probability of A given B for any probability space is the probability of A intersection B divided by probability of B.

273
00:44:46.010 --> 00:44:59.799
Faculty (Olympus): Okay? And the intuition is, like I said before, when I knowâ€¦ when we talk about conditional probability, what we are asking is, if I give you the information that this event B happened, how does that change

274
00:44:59.910 --> 00:45:03.180
Faculty (Olympus): your belief about whether A happened or not.

275
00:45:03.310 --> 00:45:08.990
Faculty (Olympus): Okay, so that is what this conditional probability is trying to mimic.

276
00:45:10.250 --> 00:45:17.930
Faculty (Olympus): Okay, let's maybe look at an example. So let's say we have, two coins.

277
00:45:18.600 --> 00:45:33.499
Faculty (Olympus): Okay, C1 and C2. C1 is a fair coin, which means it's equally likely to show, heads or tails, but C2 is the Chollet coin, it has heads on both sides.

278
00:45:34.040 --> 00:45:35.110
Faculty (Olympus): Okay?

279
00:45:35.240 --> 00:45:39.839
Faculty (Olympus): And, my experiment is that I first choose

280
00:45:40.250 --> 00:45:42.420
Faculty (Olympus): One of these coins at random.

281
00:45:44.550 --> 00:45:47.370
Faculty (Olympus): Okay, and then I toss it once.

282
00:45:50.070 --> 00:46:00.460
Faculty (Olympus): Okay, so my sample space is essentially a choice of a coin, and whether I see Heads or tails?

283
00:46:02.820 --> 00:46:07.370
Faculty (Olympus): So, these are the four possibilities Of my experiment.

284
00:46:08.120 --> 00:46:08.840
Faculty (Olympus): Right?

285
00:46:09.590 --> 00:46:19.570
Faculty (Olympus): Now, what would be a natural, natural probability, measure here? So.

286
00:46:19.570 --> 00:46:34.139
Faculty (Olympus): if you choose either of theâ€¦ choosing either of the coins is equally likely, right? C1 and C2 are both equally likely. So, the mass associated with these two should be half, and the mass associated with these two should also be half.

287
00:46:34.330 --> 00:46:41.759
Faculty (Olympus): Right? Now, in the case of coin 1, it's a fair coin, so it's equally likely to give us heads or tails.

288
00:46:41.760 --> 00:46:44.410
Sajith K N .: Should not be a tale, right? Can beâ€¦ you don't worry, right?

289
00:46:44.410 --> 00:46:58.950
Faculty (Olympus): Let meâ€¦ let me complete, please, and thenâ€¦ then we'll come to questions. So, these are all possible outcomes. The probability of C1H is 1 by 4, C1T is 1 by 4,

290
00:46:59.600 --> 00:47:15.260
Faculty (Olympus): In the case of C2H and C2T, we saw that, it is tails on both sides, right? So, sorry, heads on both sides, so all the probability is associated with C2H, and the chance of C2T is 0.

291
00:47:15.410 --> 00:47:31.590
Faculty (Olympus): Right? This is our underlying probability measure. So this is the probability associated with each of these singletons, and once we know the probability associated with the singletons, then we can compute the probability associated with any event, right? Now.

292
00:47:31.890 --> 00:47:35.129
Faculty (Olympus): Suppose the events that we define

293
00:47:35.390 --> 00:47:44.820
Faculty (Olympus): suppose we look at the following events, okay? So, event E Is that we observe tails.

294
00:47:45.700 --> 00:47:50.800
Faculty (Olympus): Event A1 is that we choose coin

295
00:47:51.790 --> 00:47:56.819
Faculty (Olympus): And event A2 is that we chooseâ€¦ Coin 2.

296
00:47:57.990 --> 00:48:13.580
Faculty (Olympus): Right? Now, all of these are events, which means they should all be subsets of the sample space. So, let's say, observe tails. What subset does it correspond to? So, it corresponds to the subset C1T comma C2T.

297
00:48:14.240 --> 00:48:24.249
Faculty (Olympus): Right? This is where tails is observed. Choosing coin 1, what does that correspond to? That corresponds to the subset C1T, C1H.

298
00:48:24.960 --> 00:48:33.610
Faculty (Olympus): Similarly, choosing coin 2 corresponds to the subset Câ€¦ C2Tâ€¦ and C2H.

299
00:48:34.480 --> 00:48:42.910
Faculty (Olympus): Right? So I can compute all of these individual probabilities from here. For example, The probability ofâ€¦

300
00:48:43.070 --> 00:48:54.480
Faculty (Olympus): Observing tails isâ€¦ isâ€¦ the probability is going to be the probability of associated with C1T,

301
00:48:54.750 --> 00:49:01.479
Faculty (Olympus): plus the probability associated with C2T, This is 1 4th.

302
00:49:02.030 --> 00:49:07.169
Faculty (Olympus): This is 0, so the probability of observing tails is 1 fourth.

303
00:49:07.890 --> 00:49:22.479
Faculty (Olympus): Similarly, you can check that the probability of choosing coin 1 is going to be 1 half, and the probability of choosing coin 2 is also going to be 1 half, right? Because we are equally likely to choose either coin 1 or coin 2.

304
00:49:22.610 --> 00:49:33.799
Faculty (Olympus): Right? Okay, fine, so these marginal probabilities are all there, right? What if, we ask, okay, what is the probability of observing

305
00:49:34.780 --> 00:49:43.800
Faculty (Olympus): tailsâ€¦ Givenâ€¦ we choseâ€¦ Coin 1.

306
00:49:44.510 --> 00:49:54.500
Faculty (Olympus): Right? Now I'm giving you this observation. So now, this is about a conditional probability. So this is the probability of observing tails conditioned on

307
00:49:54.890 --> 00:49:56.529
Faculty (Olympus): Choosing coin one.

308
00:49:57.610 --> 00:49:58.380
Faculty (Olympus): Right?

309
00:49:58.920 --> 00:50:05.680
Faculty (Olympus): whatâ€¦ intuitively, what do we think this probability should be? So if I tell you that we have chosen the fair coin.

310
00:50:05.950 --> 00:50:24.239
Faculty (Olympus): How does half, right? So you would expect that, that we should get half. So let's just see whether our definition also gives us the same thing. So, by definition, this is the probability of E intersection A1 divided by P of A1.

311
00:50:24.390 --> 00:50:32.510
Faculty (Olympus): Right? P of A1, we have already computed, that is 1 half. What is E intersection A1, right? So, E isâ€¦

312
00:50:32.850 --> 00:50:39.820
Faculty (Olympus): this subset, A1 is this subset. What is E intersection A1? The common element is C1T.

313
00:50:40.320 --> 00:50:50.419
Faculty (Olympus): And what is the measure associated with C1T? It is exactly 1 by 4. So this is going to be probability associated with C1T,

314
00:50:51.140 --> 00:50:58.370
Faculty (Olympus): which is 1 fourth, so you get 1x4 by 1 half, which is 1 half, right? So it does make sense.

315
00:50:58.840 --> 00:51:03.989
Faculty (Olympus): Similarly, if you compute probability of E conditioned on A2,

316
00:51:04.120 --> 00:51:23.109
Faculty (Olympus): Meaning, youâ€¦ what is the probability of observing tails? Given you chose coin 2, you shouldâ€¦ you should expect to see a 0, right? And that is indeed what is going to happen if you place this, because the intersection will contain the element C to T, and that has probability 0.

317
00:51:23.320 --> 00:51:29.519
Faculty (Olympus): Okay? So, in general, the main thing to notice is that, or to note, is that if you take any

318
00:51:29.660 --> 00:51:43.399
Faculty (Olympus): pair, or if you have any pair of events from your probability space, the conditional probability is defined as the ratio of the probability associated with the intersection

319
00:51:43.710 --> 00:51:51.440
Faculty (Olympus): and the probab- marginal probability of the conditioning event, okay? That is the main, main thing to keep here.

320
00:51:51.920 --> 00:52:00.660
Faculty (Olympus): Okay, I'll take a few quick questions, and then we'll move on to some properties of conditional probability.

321
00:52:01.670 --> 00:52:03.780
Faculty (Olympus): Okay, Sachin Mury.

322
00:52:06.430 --> 00:52:09.590
Sachin More .: Yep, Professor, quick question. If you scroll up a bit.

323
00:52:09.590 --> 00:52:10.120
Faculty (Olympus): Yeah.

324
00:52:11.450 --> 00:52:14.479
Sachin More .: A bit more. Before, just to give you the example.

325
00:52:14.660 --> 00:52:15.180
Faculty (Olympus): Yeah.

326
00:52:15.940 --> 00:52:22.620
Sachin More .: Yes, what you mentioned is probability of phase 5 by 10, that's half.

327
00:52:22.620 --> 00:52:22.980
Faculty (Olympus): Yeah.

328
00:52:22.980 --> 00:52:32.639
Sachin More .: But, and then you said probability of B is 4x10, that is 2x2x5. How did 2x5 appear here? Sorry, I had a network glitch, so didn't get it exactly.

329
00:52:32.640 --> 00:52:36.080
Faculty (Olympus): Oh, no, just 4x10 is the same as 2x5, that's it.

330
00:52:36.080 --> 00:52:37.440
Sachin More .: No, no, how did youâ€¦ how did.

331
00:52:37.440 --> 00:52:47.800
Faculty (Olympus): Oh, how did I select 4x10? How did I get 4x10? Because B has 4 elements. That's it. All these elements are equally likely, and B has 4 elements.

332
00:52:48.470 --> 00:52:51.609
Faculty (Olympus): So the probability is 4 by 10.

333
00:52:51.610 --> 00:52:53.220
Sachin More .: Got it, yeah, got it.

334
00:52:53.220 --> 00:52:55.210
Faculty (Olympus): Okay? Okay, Sakshi?

335
00:52:57.470 --> 00:53:07.220
Sakshi Singh .: Yeah, Prof, my, question is answered. I just have one request, can you please share such exercises for practice with us?

336
00:53:07.820 --> 00:53:25.599
Faculty (Olympus): Sure, yeah, yeah, yeah, we will, shareâ€¦ in fact, in your TA session today, you will get to do some of these, but we will also share a practice sheet, going forward. Yeah, yeah. So you will, I think, do some of these problems, problems of these type today, but a practice sheet will also be shared.

337
00:53:25.600 --> 00:53:29.769
Sakshi Singh .: Yeah, because this is one of the questions, but there are a number of questions that.

338
00:53:29.770 --> 00:53:33.680
Faculty (Olympus): Yeah, yeah, yeah, of course, of course, of course, yeah, yeah, yeah. We will share practice sheets.

339
00:53:34.840 --> 00:53:38.920
Faculty (Olympus): Okay? Krishnaâ€¦ Krishna Pandey?

340
00:53:39.110 --> 00:53:44.939
Krishna Pandey .: Yeah, hi, Professor. My question is, I can get why the event of A2 is equal to 0.

341
00:53:45.940 --> 00:53:49.449
Faculty (Olympus): Y eventâ€¦ no, event A2 is not 0.

342
00:53:50.060 --> 00:53:52.209
Faculty (Olympus): A2 is choosing coin 2.

343
00:53:52.670 --> 00:53:54.880
Faculty (Olympus): It is about the probability ofâ€¦

344
00:53:55.110 --> 00:53:59.099
Faculty (Olympus): Observing tails given that you have chosen coin 2.

345
00:54:00.640 --> 00:54:02.470
Faculty (Olympus): Is that what you're asking?

346
00:54:02.470 --> 00:54:03.280
Krishna Pandey .: Yes.

347
00:54:03.280 --> 00:54:10.369
Faculty (Olympus): Yeah, so again, if I, for example, compute this, this is going to be E intersection A2 divided by

348
00:54:10.570 --> 00:54:12.719
Faculty (Olympus): PA2, that is by definition.

349
00:54:12.870 --> 00:54:16.189
Faculty (Olympus): Now, you look at the two events, E,

350
00:54:16.370 --> 00:54:22.179
Faculty (Olympus): and you look at A2. What is the common element? The only common element is C2T.

351
00:54:23.900 --> 00:54:37.609
Faculty (Olympus): And C2T has measure 0, right? Because C2 is a coin which has heads on both sides, so the natural measure was 0 with it. So this is going to be probability associated with the Singleton C2T,

352
00:54:37.800 --> 00:54:41.690
Faculty (Olympus): divided by PA2, which is just going to be 0.

353
00:54:42.200 --> 00:54:43.380
Krishna Pandey .: Okay, understood, thank you.

354
00:54:43.380 --> 00:54:46.600
Faculty (Olympus): Okay, alright, maybe last question, Sameep?

355
00:54:48.710 --> 00:54:54.089
Sameep Jain .: Professor, can you explain, the sample space you created for this question?

356
00:54:54.280 --> 00:55:12.180
Faculty (Olympus): So, the sample space, the experiment was choosing one coin amongst the two, and then tossing it once and observing whether we see a heads or a tails. So, there are four possibilities overall, right? You choose coin one, you observe heads, or you choose coin one, observe a tails.

357
00:55:12.430 --> 00:55:23.530
Faculty (Olympus): or you choose coin to observe heads, choose coin to observe tails. There are four possible outcomes for this experiment, so thatâ€¦ those are the ones that areâ€¦ form our sample space.

358
00:55:24.170 --> 00:55:30.600
Sameep Jain .: And we, are choosing a coin, tail, for this conditional probability, right?

359
00:55:30.900 --> 00:55:41.940
Faculty (Olympus): Yeah, thatâ€¦ I mean, that's just one event. We have defined three events, and we are trying to find the conditional probability of event E given A1 and given A2 separately.

360
00:55:42.990 --> 00:55:43.550
Sameep Jain .: Okay.

361
00:55:44.690 --> 00:55:55.230
Faculty (Olympus): Okay, alright, let's, move forward. So, now I want to coverâ€¦ Some properties of conditional probability.

362
00:56:02.330 --> 00:56:11.660
Faculty (Olympus): Okay, so there are three main, properties. One is called the multiplicative Rule?

363
00:56:11.960 --> 00:56:17.560
Faculty (Olympus): The second is calledâ€¦ The law of total probability

364
00:56:19.400 --> 00:56:22.350
Faculty (Olympus): And the third one is called Bayes Rule.

365
00:56:23.170 --> 00:56:30.570
Faculty (Olympus): We will cover all of these, one by one. Okay, so let's, let's start withâ€¦

366
00:56:30.730 --> 00:56:32.470
Faculty (Olympus): The multiplicative rule.

367
00:56:37.900 --> 00:56:41.239
Faculty (Olympus): So, the multiplicative rule, all it says is that,

368
00:56:41.440 --> 00:56:49.289
Faculty (Olympus): it tries to express the probability of intersection of events in terms of conditional probabilities, soâ€¦

369
00:56:49.330 --> 00:57:02.839
Faculty (Olympus): We can always write probability of A intersection B. This is just by definition. Probability of A intersection B is the same as probability of A times the probability of B

370
00:57:03.000 --> 00:57:07.160
Faculty (Olympus): condition on A, right? This is just by the definition of

371
00:57:07.330 --> 00:57:24.410
Faculty (Olympus): this probability, of the conditional probability. If you take P of A to the other side, that is exactly the definition of conditional probability, so this always holds true. Similarly, you could have also written this as probability of B times the conditional probability of A given B.

372
00:57:24.840 --> 00:57:38.580
Faculty (Olympus): Alright? So this is just, by definition. Now, if I take probability of now, instead of 2 events, if I take probability of, let's say, 3 events, A intersection B, intersection C,

373
00:57:38.720 --> 00:57:44.829
Faculty (Olympus): then I can write this asâ€¦ I can show that this is the same as probability of A,

374
00:57:44.990 --> 00:57:52.879
Faculty (Olympus): times conditional probability of B given A times the conditional probability of C given

375
00:57:53.230 --> 00:57:57.800
Faculty (Olympus): Let me write this asâ€¦ A intersection.

376
00:58:00.470 --> 00:58:08.409
Faculty (Olympus): Okay? So I can write the probability of this intersection as a product of one marginal term, and then successive

377
00:58:08.610 --> 00:58:18.570
Faculty (Olympus): conditional probabilities. And in general, if you have the probability of the intersection of some n events.

378
00:58:18.900 --> 00:58:27.410
Faculty (Olympus): then you can always write this as probability of A1 times A product of conditional probabilities.

379
00:58:27.930 --> 00:58:43.099
Faculty (Olympus): So this is, the Nâ€¦ AI conditioned onâ€¦ A1, intersection A2, tillâ€¦ AI minus 1.

380
00:58:43.480 --> 00:58:53.680
Faculty (Olympus): Okay, so this is what the multiplicative rule stands for. So all it's saying is that you can express the probability of the intersection as the probability of

381
00:58:53.780 --> 00:59:04.459
Faculty (Olympus): A1 times a product of conditional probabilities, okay? So this, it's not, difficult toâ€¦

382
00:59:04.460 --> 00:59:26.629
Faculty (Olympus): prove this. The proof is there in the notes. I won't go over the proof in the class, but at least for the three case, the proof is there in the notes if you're interested to look at it. Okay, so all this is doing is it's telling us how to express the probability of intersection in terms of a product of, essentially, conditional probabilities.

383
00:59:27.110 --> 00:59:36.849
Faculty (Olympus): Okay? We'll see how the multiplicative rule gets used. Okay, let's go to the second one.

384
00:59:39.960 --> 00:59:46.060
Faculty (Olympus): So, the second one is called the Law of Total Probability.

385
00:59:46.380 --> 00:59:53.100
Faculty (Olympus): Okay? So what it says is the following. Suppose You have this sample space.

386
00:59:53.730 --> 00:59:56.149
Faculty (Olympus): Okay, and let's say there is a particular event.

387
00:59:56.480 --> 00:59:57.700
Faculty (Olympus): A.

388
00:59:58.390 --> 01:00:00.630
Faculty (Olympus): Whose probability you are interested in.

389
01:00:00.870 --> 01:00:06.480
Faculty (Olympus): Okay? Andâ€¦ you haveâ€¦ some other events.

390
01:00:07.440 --> 01:00:08.390
Faculty (Olympus): Okay.

391
01:00:08.550 --> 01:00:13.190
Faculty (Olympus): which are B1, B2 and B3.

392
01:00:13.560 --> 01:00:20.180
Faculty (Olympus): Now, these other events, these BIs, Okay? They form a partition.

393
01:00:22.250 --> 01:00:38.179
Faculty (Olympus): a partition of the sample space. What does it mean that BI isâ€¦ that these events BI form a partition of the sample space? For them to form a partition, you need that the union of all these BIs should be the entire sample space.

394
01:00:38.480 --> 01:00:47.039
Faculty (Olympus): And any twoâ€¦ of these BIs, okay? Any two of these BIs, let's say BI intersection BJ,

395
01:00:47.280 --> 01:00:53.450
Faculty (Olympus): should be null, meaning these should be disjoint. So, these BIs, are disjoint.

396
01:00:53.880 --> 01:00:57.349
Faculty (Olympus): So, if you have a collection of events which are disjoint.

397
01:00:57.880 --> 01:01:11.329
Faculty (Olympus): pairwise disjoint, and their union forms the entire sample space, then they are called a partition of omega, okay? So now, the law of total probability essentially tries to express

398
01:01:11.480 --> 01:01:13.799
Faculty (Olympus): this probability of A,

399
01:01:13.860 --> 01:01:33.189
Faculty (Olympus): In terms ofâ€¦ in terms of the conditional probability of A given these PIs, okay? How does it do that? So, if you see the probability of A, right, you have 3 intersection places here. You have the intersection of A and B1,

400
01:01:33.400 --> 01:01:41.509
Faculty (Olympus): You have the intersection of A and B2, and then finally, you have the intersection of A and B3.

401
01:01:41.870 --> 01:01:55.210
Faculty (Olympus): Right? All of these intersections, so these A intersection B1 is disjoint from A intersection B2, and is disjoint from A intersection B3. Because B1, B2, B3 are all disjoint.

402
01:01:55.330 --> 01:02:03.799
Faculty (Olympus): And all elements of A belong to one of these intersections. So we can write the probability of A as

403
01:02:04.130 --> 01:02:05.310
Faculty (Olympus): the sumâ€¦

404
01:02:05.950 --> 01:02:22.799
Faculty (Olympus): over, so let's say if there were I, this, this collection or this partition was indexed by I, then this is the same as A intersection BI, the sum of probability of A intersection BI,

405
01:02:22.920 --> 01:02:27.889
Faculty (Olympus): Now, I can write the probability of A intersection BI asâ€¦

406
01:02:28.250 --> 01:02:35.490
Faculty (Olympus): the probability of BI times the conditional probability of a given BI.

407
01:02:35.760 --> 01:02:38.519
Faculty (Olympus): This is called the law of total probability.

408
01:02:39.000 --> 01:02:40.830
Faculty (Olympus): probability of A.

409
01:02:41.000 --> 01:02:42.949
Faculty (Olympus): Is equal to the sum

410
01:02:43.150 --> 01:03:02.950
Faculty (Olympus): of these intersection probabilities across the partition, which is further written down, in this particular form. So, how to read this, this expression? This is saying the probability of A can be written as a weighted combination of these conditional probabilities, A given BIs.

411
01:03:03.110 --> 01:03:21.370
Faculty (Olympus): Okay? Not just weighted. In fact, theseâ€¦ if you look at these weights, if you think of these P of Bi's as the weights, the P of Bi's sum up to 1, right? So this is like a convex combination of these conditional probabilities. So I can writeâ€¦ I can express the probability of any event A

412
01:03:21.540 --> 01:03:33.140
Faculty (Olympus): in terms of conditional probabilities of A given element, or given events of a partition of the sample space. I can do that for any partition of my sample space.

413
01:03:33.660 --> 01:03:43.050
Faculty (Olympus): Okay? Let me maybe give an example, and then, I'll take questions about this, okay? So let's look at a particular

414
01:03:43.510 --> 01:03:57.539
Faculty (Olympus): example. In particular, let's go back to our two coins example, okay? So, again, C1, C2 were our two coins, we were choosing one of them at random, and then the event E

415
01:03:57.910 --> 01:04:01.689
Faculty (Olympus): Was that you observe tales.

416
01:04:04.590 --> 01:04:17.670
Faculty (Olympus): Right? Now, suppose I'm interested in finding the probability of observing tails. This is something we had, calculated before, but now we will try and do that using the law of total probability.

417
01:04:17.760 --> 01:04:29.870
Faculty (Olympus): So, let me define. So, if Iâ€¦ if I want to express this in terms of law of total probability, I need some, events which areâ€¦ which form a partition of my sample space.

418
01:04:30.220 --> 01:04:36.580
Faculty (Olympus): Right? So, notice that the two events, A1 and A2, actually partition.

419
01:04:38.230 --> 01:04:50.940
Faculty (Olympus): your sample space. Why is that? A1 was choosing coin 1, right? That corresponds to the elements C1Tâ€¦

420
01:04:51.120 --> 01:04:53.540
Faculty (Olympus): and C1H.

421
01:04:54.280 --> 01:05:02.060
Faculty (Olympus): And A2 corresponds to choosing coin 2, that corresponds to C2H, C2T.

422
01:05:02.780 --> 01:05:18.190
Faculty (Olympus): Right? So if you see A1 and A2, their union is the entire sample space, and they are disjoint. They are pairwise disjoint. So A1 and A2 indeed partition the sample space, which means I can write

423
01:05:18.480 --> 01:05:23.569
Faculty (Olympus): P of E asâ€¦ P of A1 times

424
01:05:24.010 --> 01:05:29.629
Faculty (Olympus): the conditional probability of E given A1, plus P of A2â€¦

425
01:05:29.840 --> 01:05:34.189
Faculty (Olympus): times the conditional probability of E given A2.

426
01:05:35.000 --> 01:05:45.720
Faculty (Olympus): What is the probability of A1? The probability of A1 is the probability that you choose coin 1, that is with half probability. What is the probability

427
01:05:46.030 --> 01:05:52.019
Faculty (Olympus): That you observe a tales given that the first coin was chosen, or the fair coin was chosen.

428
01:05:52.200 --> 01:05:55.530
Faculty (Olympus): This was, again, 1 half. We had calculated this quantity.

429
01:05:55.870 --> 01:06:00.199
Faculty (Olympus): What is the probability that you choose coin 2? Again, 1 half.

430
01:06:00.500 --> 01:06:08.010
Faculty (Olympus): What is the probability that you observe a tails given that you have chosen the biased coin? This is zero.

431
01:06:08.010 --> 01:06:08.770
Tushar Sachdev .: Sweetened.

432
01:06:08.770 --> 01:06:10.350
Faculty (Olympus): So, this is going to beâ€¦

433
01:06:10.720 --> 01:06:20.600
Faculty (Olympus): 1 by 4. This is exactly what we had seen before as well, right? So we haveâ€¦ we can calculate this probability of, any event.

434
01:06:20.740 --> 01:06:37.650
Faculty (Olympus): as essentially this weighted combination or convex combination of these conditional probabilities, the only thing to keep in mind is that the sets that you are conditioning over, right, they should form a partition of your underlying sample space.

435
01:06:37.650 --> 01:06:46.919
Faculty (Olympus): If you can do that, then you can always write them as this convex combination of conditional probabilities, okay?

436
01:06:46.970 --> 01:06:56.270
Faculty (Olympus): okay, yeah, I'll take a couple of questions. Yeah, Gaurav Singh?

437
01:06:58.730 --> 01:07:04.210
Gaurav Singh .: So, Professor, like, it's related to discrete,

438
01:07:04.350 --> 01:07:16.310
Gaurav Singh .: discrete sample space, which you have talked about. Yeah. just one question, like, in discrete scenario, the probabilities will be always kind of a geometric progression, orâ€¦ No, no.

439
01:07:16.410 --> 01:07:18.660
Faculty (Olympus): They don't have to be, they can be anything.

440
01:07:19.150 --> 01:07:19.770
Gaurav Singh .: Okay.

441
01:07:19.770 --> 01:07:25.280
Faculty (Olympus): All that they haveâ€¦ any probability measure, anyâ€¦ the only thing that it has to satisfy are the three axioms.

442
01:07:26.290 --> 01:07:27.270
Gaurav Singh .: Okay, got it.

443
01:07:27.270 --> 01:07:28.270
Faculty (Olympus): Yep.

444
01:07:28.380 --> 01:07:30.920
Faculty (Olympus): Okay, Sanket? Sanket Shah?

445
01:07:31.210 --> 01:07:40.510
sanket shah .: Yeah, so, if just you can explain me that Ken statement of, the first law.

446
01:07:40.640 --> 01:07:42.120
sanket shah .: that multiâ€¦

447
01:07:42.340 --> 01:07:56.420
sanket shah .: Applicative one. Yeah, that A intersection, B intersection C. So I got the first one. So, just if you can explain with an, example of A intersection, B intersection C.

448
01:07:56.680 --> 01:08:05.039
Faculty (Olympus): No, so, I mean, this is theâ€¦ this is what the formula turns out to be. If youâ€¦ are you asking for a proof of why this is the case?

449
01:08:05.500 --> 01:08:12.880
sanket shah .: No, I just actually wanted toâ€¦ understand that, fromâ€¦

450
01:08:13.510 --> 01:08:18.739
sanket shah .: An example. So, like, Madam Bhavâ€¦ what is it? It's likeâ€¦

451
01:08:18.740 --> 01:08:31.490
Faculty (Olympus): So it's, Okay, let's maybe try, soâ€¦ So,

452
01:08:36.810 --> 01:08:46.529
Faculty (Olympus): Okay, so maybe, let's say if we are, tossing a coin, 3 timesâ€¦ Right?

453
01:08:46.700 --> 01:08:59.659
Faculty (Olympus): And these eventsâ€¦ Eâ€¦ Bc correspond to, observing, I don't know, heads in TOS1.

454
01:09:00.180 --> 01:09:03.369
Faculty (Olympus): B corresponds to observing the heads in TOSS 2.

455
01:09:04.000 --> 01:09:07.630
Faculty (Olympus): And C corresponds to observing heads in TOS 3.

456
01:09:07.899 --> 01:09:08.349
sanket shah .: Right?

457
01:09:08.550 --> 01:09:15.509
Faculty (Olympus): So what this is saying is that if you want to now find the probability that you observe a heads in all three tosses.

458
01:09:15.649 --> 01:09:16.179
sanket shah .: Hmm.

459
01:09:16.180 --> 01:09:29.949
Faculty (Olympus): You can write that as the probability of observing a heads in TOS 1 times the conditional probability of observing a heads in TOS 2, given that you observed a heads in TOSS 1.

460
01:09:30.640 --> 01:09:35.660
Faculty (Olympus): times the probability that you observe heads in TOS 3, given

461
01:09:35.910 --> 01:09:39.810
Faculty (Olympus): that you observe heads in both tosses 1 and 2.

462
01:09:40.210 --> 01:09:51.889
Faculty (Olympus): Okay? Now, if your tosses are independent, right? Ifâ€¦ we'll come to exactly what we mean by independent, but roughly, if, you know, one toss does not impact the second toss.

463
01:09:51.890 --> 01:09:54.550
sanket shah .: It is called as independent, right?

464
01:09:54.700 --> 01:10:09.390
Faculty (Olympus): So then these, these will roughly be the same as the probability of B. But suppose if, you know, if you are, something like, if once you have tossed the coin as, and you get a heads, it is less likely to get a heads again.

465
01:10:09.720 --> 01:10:12.530
Faculty (Olympus): Then these conditional probabilities will change.

466
01:10:12.680 --> 01:10:19.439
Faculty (Olympus): Right? Theseâ€¦ given that you have observed two heads in a row, what is the probability that you observe the third heads again?

467
01:10:19.920 --> 01:10:28.930
Faculty (Olympus): So, that might be different than the marginal probability of observing ahead. So, that is what itâ€¦ that is what it means.

468
01:10:29.470 --> 01:10:33.240
sanket shah .: Okay, Professor, yeah. Thank you so much for this. Sure.

469
01:10:33.450 --> 01:10:35.690
Faculty (Olympus): Yeah, Siddhesh?

470
01:10:36.500 --> 01:10:51.889
Siddhesh Dinesh Kadam .: Yes, so if you scroll up, I just, understood the concept, but I'm trying to read it through how you've written it. Yeah, you'll hear. So, there you've written this, example, right, a summation of I belonging to capital I.

471
01:10:51.890 --> 01:10:52.260
Faculty (Olympus): Yep.

472
01:10:52.260 --> 01:10:54.969
Siddhesh Dinesh Kadam .: All I understand is 3 in this case, right?

473
01:10:54.970 --> 01:10:57.290
Faculty (Olympus): I mean, in this, yeah, yeah, in this case, it is 3.

474
01:10:57.290 --> 01:11:03.820
Siddhesh Dinesh Kadam .: the three. But why is it belonging to I are not equal? Like, we typically write i is equal toâ€¦

475
01:11:03.820 --> 01:11:09.169
Faculty (Olympus): No, no, no, so this capital I is supposed to be the index set, meaningâ€¦

476
01:11:09.170 --> 01:11:09.780
Siddhesh Dinesh Kadam .: excerpt.

477
01:11:09.780 --> 01:11:18.179
Faculty (Olympus): So, in this particular example, it's I isâ€¦ the set 1, comma, 2, comma 3.

478
01:11:18.320 --> 01:11:27.669
Faculty (Olympus): Right? So, you are going to sum over all elements of i. So this, this notation, maybe this is a little unclear, let me write this cleanly.

479
01:11:28.020 --> 01:11:39.539
Faculty (Olympus): This is, like, a small E. This notation stands for I is an element of capital I. So you're goingâ€¦ summing over all the elements of capital I, right? You're first looking at A.

480
01:11:39.960 --> 01:11:49.380
Siddhesh Dinesh Kadam .: the way we read it is that I, I captures all the events into thatâ€¦ yeah, so I think I understand now. Yeah. Okay.

481
01:11:49.380 --> 01:11:51.089
Faculty (Olympus): Okay, Harshad?

482
01:11:51.420 --> 01:12:05.799
Harshad Dilip Behere .: Yeah, good afternoon, Professor. Yeah. So, can you scroll down a little bit here? Yeah. I think that's C1C2 example. So, I think in C1C2, when we are saying coin one, coin 2, we are just going to select one coin and toss it. We are not tossing two coins at the same.

483
01:12:05.800 --> 01:12:08.740
Faculty (Olympus): No, no, no. No, we select a coin first, and then we toss it.

484
01:12:08.740 --> 01:12:11.639
Harshad Dilip Behere .: And that is where we say it's a 1.5 into one and a half.

485
01:12:11.640 --> 01:12:12.470
Faculty (Olympus): Yeah, yeah, yeah.

486
01:12:12.770 --> 01:12:13.430
Harshad Dilip Behere .: Okay.

487
01:12:14.040 --> 01:12:15.130
Harshad Dilip Behere .: Right, thank you.

488
01:12:15.130 --> 01:12:17.530
Faculty (Olympus): Okay, Devendra Parmar?

489
01:12:22.440 --> 01:12:24.040
Faculty (Olympus): Okay, Sajith?

490
01:12:26.450 --> 01:12:33.520
Sajith K N .: Yeah, on the second rule, right, that, multiplicative rule. Yeah. You can alsoâ€¦ can you go there?

491
01:12:36.880 --> 01:12:39.830
Sajith K N .: Yeah, we can also use rewrite Pâ€¦

492
01:12:40.020 --> 01:12:43.309
Sajith K N .: P of B and P, P, given B.

493
01:12:43.700 --> 01:12:46.909
Sajith K N .: Like that also, right? Then what is the last one, then?

494
01:12:47.810 --> 01:12:57.029
Faculty (Olympus): No, so then youâ€¦ I mean, you go in that order, so you can write this as P of A times P of C conditioned on A times P of B condition on A intersection C.

495
01:12:59.040 --> 01:13:02.150
Faculty (Olympus): So, yeah, how you order it is, I mean, up to you.

496
01:13:02.640 --> 01:13:04.059
Faculty (Olympus): We're gonna order them anywhere.

497
01:13:04.060 --> 01:13:06.320
Sajith K N .: If you have a rewrite, I have to order that inâ€¦

498
01:13:06.320 --> 01:13:09.450
Faculty (Olympus): Yeah, yeah, yeah. All of them have to be ordered appropriately.

499
01:13:09.980 --> 01:13:10.710
Sajith K N .: Okay.

500
01:13:10.710 --> 01:13:12.600
Faculty (Olympus): Yeah, you can fix any order.

501
01:13:12.600 --> 01:13:19.870
Sajith K N .: And also, the third one, how does it, how the IE is equal to 2? Is it 2, or what is it?

502
01:13:20.660 --> 01:13:24.060
Faculty (Olympus): In this example, in this example,

503
01:13:24.060 --> 01:13:26.970
Sajith K N .: No, that's the question, the question summation, right?

504
01:13:27.170 --> 01:13:28.240
Sajith K N .: The third one.

505
01:13:29.470 --> 01:13:30.399
Sajith K N .: Let's scroll up.

506
01:13:30.770 --> 01:13:31.980
Faculty (Olympus): Scroll upâ€¦

507
01:13:32.390 --> 01:13:45.060
Faculty (Olympus): Okay, why I equals 2? Because the first one, the probability of A1 is already there, right? So, the second element will now be A2 conditioned on A1, so you start from the second one.

508
01:13:45.060 --> 01:13:46.050
Sajith K N .: Not only.

509
01:13:46.050 --> 01:13:46.610
Faculty (Olympus): Yeah.

510
01:13:46.950 --> 01:13:49.360
Faculty (Olympus): Okay? Kedar?

511
01:13:51.500 --> 01:14:02.000
Kedar Digambar Gokhale .: In conditional probability, we say that the event which has been occurred, based on that, we try to calculate, right? So, doâ€¦

512
01:14:02.120 --> 01:14:12.979
Kedar Digambar Gokhale .: We also look at the trend of the event which has happened, because that trend also might give someâ€¦ might have some influence on upcoming probability.

513
01:14:12.980 --> 01:14:20.310
Faculty (Olympus): No, so again, I mean, yeah, maybe this is a much more general and philosophical question. Let's, maybe take it at the end.

514
01:14:21.180 --> 01:14:21.939
Dinesh Devnath Yadav .: Oh, okay.

515
01:14:21.940 --> 01:14:22.580
Kedar Digambar Gokhale .: Okay.

516
01:14:22.580 --> 01:14:24.020
Faculty (Olympus): Okay, Sanket?

517
01:14:26.890 --> 01:14:32.299
sanket shah .: Iâ€¦ yeah, Iâ€¦ I have, Siddharth.

518
01:14:32.600 --> 01:14:33.260
Faculty (Olympus): Okay, alright.

519
01:14:33.260 --> 01:14:34.430
sanket shah .: Yeah, I already have one.

520
01:14:34.430 --> 01:14:39.349
Faculty (Olympus): Okay, alright. Okay, so let's, move to the third, property.

521
01:14:40.180 --> 01:14:43.799
Faculty (Olympus): So this third property is called the Bayes Rule.

522
01:14:44.030 --> 01:14:59.799
Faculty (Olympus): It's one of the most important properties of conditional probability, and it's also widely used. I mean, it's theâ€¦ it forms the basis of, you might have heard of this Bayesian inference in machine learning, so it forms the basis of that.

523
01:14:59.800 --> 01:15:09.329
Faculty (Olympus): So, what itâ€¦ roughly speaking, what it, means is the following. So, useâ€¦ let's say there is some event, and you are starting with some belief.

524
01:15:09.340 --> 01:15:14.660
Faculty (Olympus): about how likely that event is. So, often that is called, like, the prior belief.

525
01:15:15.520 --> 01:15:30.439
Faculty (Olympus): about that event, right? So, for example, it could beâ€¦ I might have some prior belief on whether it is going to rain tomorrow or not, right? I have some belief in my mind about how likely is it to rainâ€¦ that it'll rain tomorrow.

526
01:15:30.560 --> 01:15:37.129
Faculty (Olympus): Now, what happens is that I will observe some data, or some event.

527
01:15:37.980 --> 01:15:45.029
Faculty (Olympus): And then, based on this data or this event, I will update my belief.

528
01:15:46.220 --> 01:15:47.960
Faculty (Olympus): I will update my belief.

529
01:15:48.780 --> 01:15:53.159
Faculty (Olympus): Okay? Given that I have observed some data, or I have observed some event.

530
01:15:53.230 --> 01:16:02.139
Faculty (Olympus): Right? How should I update this belief? So, suppose it rains today, then I will update my belief on whether it is going to rain tomorrow or not.

531
01:16:02.140 --> 01:16:23.110
Faculty (Olympus): Right? So, you can see how this plays a role in machine learning. You might have some prior aboutâ€¦ or about some event, and then you gather some data, and then conditioned on the data, you update your belief about how likely is it that a certain event is going to occur. So, how exactly should we update that prior?

532
01:16:23.110 --> 01:16:25.330
Faculty (Olympus): Right? That is what Bayes' Rule tells us.

533
01:16:25.420 --> 01:16:32.920
Faculty (Olympus): So, again, let's say we haveâ€¦ so, the formal statement is as follows. Again, we have

534
01:16:33.040 --> 01:16:37.250
Faculty (Olympus): a particular event A, and we have a partition.

535
01:16:37.530 --> 01:16:43.380
Faculty (Olympus): A collection of events that partition the sample space.

536
01:16:44.070 --> 01:16:45.170
Faculty (Olympus): Right?

537
01:16:45.630 --> 01:16:58.389
Faculty (Olympus): then, probability of these BIs, each of these BIs, is like my, initial belief, or prior, about how likely any of these BIs is to occur.

538
01:17:00.640 --> 01:17:01.670
Faculty (Olympus): Okay?

539
01:17:01.840 --> 01:17:09.960
Faculty (Olympus): Nowâ€¦ if I say that eventâ€¦ if I know that event A occurs, then I can look atâ€¦

540
01:17:10.270 --> 01:17:17.600
Faculty (Olympus): the conditional probability of BI given A, and that is going to be my updated belief.

541
01:17:17.740 --> 01:17:20.010
Faculty (Olympus): aboutâ€¦ B.I.

542
01:17:20.480 --> 01:17:30.079
Faculty (Olympus): Okay? About how likely is it that BI is going to occur. So I can write this probability of BI given A.

543
01:17:30.660 --> 01:17:39.440
Faculty (Olympus): As, by definition, this is BI intersection A divided by probability of A.

544
01:17:40.210 --> 01:17:44.150
Faculty (Olympus): Which one can write as the probability of

545
01:17:44.700 --> 01:17:47.660
Faculty (Olympus): BI, which was my prior

546
01:17:48.180 --> 01:17:52.400
Faculty (Olympus): times the conditional probability of A given BI,

547
01:17:52.940 --> 01:17:59.280
Faculty (Olympus): divided byâ€¦ now, what is P of A? Because BIs form a partition.

548
01:17:59.530 --> 01:18:06.670
Faculty (Olympus): Then, from the law of total probability, I know that I can write this as summation INI

549
01:18:07.470 --> 01:18:10.489
Faculty (Olympus): Probability ofâ€¦ or let me call this J.

550
01:18:10.640 --> 01:18:13.280
Faculty (Olympus): BJâ€¦ diamonds.

551
01:18:13.450 --> 01:18:15.540
Faculty (Olympus): P ofâ€¦ A.

552
01:18:15.780 --> 01:18:17.370
Faculty (Olympus): Given Vijay.

553
01:18:17.470 --> 01:18:21.860
Faculty (Olympus): Okay? This is the statement ofâ€¦ Bayes Rule.

554
01:18:23.320 --> 01:18:26.169
Faculty (Olympus): Okay, this is the statement of Bayes' rule.

555
01:18:26.980 --> 01:18:29.000
Faculty (Olympus): So, you are starting with

556
01:18:29.650 --> 01:18:45.980
Faculty (Olympus): two things. One, you have some event A. Think of this as, you can think of this as the event, or you can think of this as data that you're going to collect, or observations that you're going to collect. BIs are some events which partition your entire sample space.

557
01:18:46.830 --> 01:18:50.490
Faculty (Olympus): Now, the P of BI is your initial belief

558
01:18:50.750 --> 01:18:56.430
Faculty (Olympus): about, the event BI, and BI conditioned on A is

559
01:18:56.530 --> 01:19:12.049
Faculty (Olympus): now I know that A has occurred, or A represents the data that I have collected. How does that impact my belief about BI, right? And Bayes' rule says that this P of BI conditioned on A can be written as

560
01:19:12.160 --> 01:19:16.169
Faculty (Olympus): the original belief or prior that you had about BI,

561
01:19:16.590 --> 01:19:23.090
Faculty (Olympus): And then this, how likely is the observation given BI had occurred?

562
01:19:23.390 --> 01:19:36.589
Faculty (Olympus): Okay? So this is sometimes called the likelihood. Okay, this second term is sometimes called the likelihood of the data or the observations that you are seeing, given that the underlying event BI occurred.

563
01:19:37.040 --> 01:19:48.709
Faculty (Olympus): That is your numerator, and the denominator is just the probability of A, which is written in this particular form via the law of total probability.

564
01:19:49.080 --> 01:20:00.289
Faculty (Olympus): Okay? So this is what Bayes' rule is. Let's maybe see an example, to see how this might be used, and then, then I can take some questions.

565
01:20:00.900 --> 01:20:18.639
Faculty (Olympus): Okay? So, again, we'llâ€¦ we'll go back to our same favorite, example. We have two coins, and, let's say, A1 was, we had these events, A1, A2, representing whether you choose coin 1 or coin 2, and event E,

566
01:20:18.640 --> 01:20:25.810
Faculty (Olympus): was, that we observe a tails, let's look at the event e complement, right? This is observing heads.

567
01:20:28.300 --> 01:20:30.780
Faculty (Olympus): Okay? So,

568
01:20:31.920 --> 01:20:50.870
Faculty (Olympus): if I look at the probability of E complement, right, this is 1 minus the probability of observing, tails, which we had computed was 1 fourth. So this is 1 minus 1 by 4, which is 3 fourths, okay? So this isâ€¦ this E probability of observing heads

569
01:20:51.060 --> 01:21:10.119
Faculty (Olympus): that this is my initial belief about observing heads, right? If I ask you before choosing a coin, I ask you what is the chance that at the end of this experiment I will observe a heads, you will say 3x4 is the chance that you will observe a heads at the end of this experiment. Now.

570
01:21:10.600 --> 01:21:20.250
Faculty (Olympus): How does this, suppose I tell you, I, I ask, I, I tell you that this event E complement is true.

571
01:21:21.510 --> 01:21:22.280
Faculty (Olympus): Right?

572
01:21:22.730 --> 01:21:30.360
Faculty (Olympus): Then how does that change my belief about whether coin 1 was chosen, Or coin 2 was chosen.

573
01:21:34.030 --> 01:21:37.470
Faculty (Olympus): Okay? So, initially, I know that

574
01:21:37.580 --> 01:21:42.639
Faculty (Olympus): The probability of choosing coin 1 is the same as probability of choosing coin 2,

575
01:21:42.920 --> 01:21:50.920
Faculty (Olympus): Which is half, right? That is the belief about whether you will end up choosing coin 1 or coin 2. But now, suppose I tell you

576
01:21:51.200 --> 01:21:59.970
Faculty (Olympus): thatâ€¦ actually, I've seen whatâ€¦ I don't know what coin was chosen, but I know that I observed the heads at the end of this experiment.

577
01:22:00.080 --> 01:22:01.170
Faculty (Olympus): Nowâ€¦

578
01:22:01.370 --> 01:22:08.350
Faculty (Olympus): How likely is it that you had chosen coin 1 versus how likely is it that you had chosen coin 2?

579
01:22:08.510 --> 01:22:22.919
Faculty (Olympus): Okay? So now, suppose I want to find this updated belief, right? I can use Bayes' rule for that. So this is going to be, by definition, this is probability of A1 intersection E complement.

580
01:22:23.030 --> 01:22:26.100
Faculty (Olympus): Divided by probability of E complement.

581
01:22:26.290 --> 01:22:34.290
Faculty (Olympus): What is A1 and E complement? So this is going to be the probability of associated with C1H.

582
01:22:35.540 --> 01:22:38.880
Faculty (Olympus): And E complement, we know, was 3x4.

583
01:22:39.810 --> 01:22:46.709
Faculty (Olympus): So this is going to beâ€¦ C1H is 1x4, so this becomes 1x4x3x4.

584
01:22:46.830 --> 01:22:48.830
Faculty (Olympus): Which is 1 3rd.

585
01:22:49.740 --> 01:22:55.689
Faculty (Olympus): Similarly, what is the probability that coin 2 was chosen, given that we observed a heads?

586
01:22:56.670 --> 01:23:03.690
Faculty (Olympus): It is E2 intersection E complement, Divided byâ€¦ Compliment.

587
01:23:03.870 --> 01:23:12.870
Faculty (Olympus): Now, E2 intersection E complement is, is, just probability of C2H,

588
01:23:13.790 --> 01:23:18.179
Faculty (Olympus): But because coin 2 was a biased coin.

589
01:23:18.360 --> 01:23:24.940
Faculty (Olympus): C2H had probability 1 by 2, so this is going to be 1x2x3x4, which is 2x3.

590
01:23:25.270 --> 01:23:27.029
Faculty (Olympus): Okay? Soâ€¦

591
01:23:27.250 --> 01:23:35.119
Faculty (Olympus): The main thing to note here is before the experiment, okay, before the experiment, you were equally likely

592
01:23:35.200 --> 01:23:54.159
Faculty (Olympus): to choose coin 1 or coin 2, right? If before the experiment you asked me that, okay, what do you think is the likelihood that we will choose coin 1 in this experiment, I would say 1 half, and if you ask me what is the likelihood that you would choose coin 2 in the experiment, I would have chosenâ€¦ I would have said 1 half.

593
01:23:54.290 --> 01:24:00.200
Faculty (Olympus): But now, suppose I give you this information, that actually in this experiment, we observe a heads.

594
01:24:00.910 --> 01:24:12.500
Faculty (Olympus): Now, this changes your belief about whether coin 1 was chosen or coin 2 was chosen. In this case, because coin 2, we know, always gives a heads, so we are going to be more likely

595
01:24:12.720 --> 01:24:17.309
Faculty (Olympus): To say that coin 2 was chosen as compared to coin 1.

596
01:24:18.260 --> 01:24:32.569
Faculty (Olympus): Right? So now, our probability, our belief changes. Now, our likelihood of having selected coin 2 is 2 by 3, and likelihood of selecting coin 1 isâ€¦

597
01:24:32.690 --> 01:24:33.750
Faculty (Olympus): One by three.

598
01:24:34.220 --> 01:24:35.030
Faculty (Olympus): Okay?

599
01:24:35.860 --> 01:24:53.320
Faculty (Olympus): if I had doneâ€¦ if I had asked the same experiment, but said instead of E complement, had chosen E, which is, I said that we observed a tails, right? Then theâ€¦ then we would have immediately known that it has to be coin 1, right? This belief would have gone from half-half to 1, 0.

600
01:24:53.690 --> 01:25:08.420
Faculty (Olympus): Because you know that coin 1â€¦ coin 2 can never give a tails, right? So there, the change would have been even more drastic. You would have gone from half a half to 1-0. Because the moment I tell you that there was a tails, you know that that coin 1 must have been chosen.

601
01:25:08.500 --> 01:25:19.699
Faculty (Olympus): Right? So this isâ€¦ this is what Bayes Rule does. It tells you how to update your belief about some event, given that some other event or some other data has been observed.

602
01:25:20.160 --> 01:25:23.949
Faculty (Olympus): Okay? Okay. Yeah, so,

603
01:25:24.280 --> 01:25:31.030
Faculty (Olympus): I will, I'll stop here, and I'll, I'll, take, any further, questions.

604
01:25:32.390 --> 01:25:33.590
Faculty (Olympus): Okay, PALAK?

605
01:25:38.560 --> 01:25:39.870
Faculty (Olympus): Okay,

606
01:25:45.320 --> 01:25:50.950
Faculty (Olympus): Yeah, PALAK, I still can't, hear, you. Gaurav? Gaurav Singh?

607
01:25:51.260 --> 01:26:09.110
Gaurav Singh .: Yeah, Professor, like, I was just wondering, like, for PA1 given EC, it came 1x3, and A2 given head was there, 2 by 3. So, the summation of the both is 1, right? So.

608
01:26:09.840 --> 01:26:17.789
Gaurav Singh .: I mean, how come it is possible that this is one when we have not even think about the tail?

609
01:26:20.840 --> 01:26:30.200
Gaurav Singh .: part of it. So, covering all the heads, giving me summation as one. So, I couldn't understand the logic behind it.

610
01:26:30.200 --> 01:26:38.399
Faculty (Olympus): the logic behind why? The logic behind what? A1 and A2 summing up toâ€¦ these conditional probabilities summing up to 1?

611
01:26:38.400 --> 01:26:46.720
Gaurav Singh .: One, yeah, and, the, the, the, dependency is EC represents

612
01:26:46.980 --> 01:26:49.230
Gaurav Singh .: that I have observed ahead, right?

613
01:26:49.230 --> 01:26:50.070
Faculty (Olympus): Yeah, yeah.

614
01:26:50.070 --> 01:26:52.350
Gaurav Singh .: Given,

615
01:26:52.920 --> 01:27:02.420
Gaurav Singh .: head has come, then the coin 1 has come, and head has come, then coin 2 has come. The summation of the probability is 1. Yeah. Right?

616
01:27:02.420 --> 01:27:20.549
Faculty (Olympus): So, I mean, those are twoâ€¦ those are the only two options, right? If you think about it, so even given, let's say, you observer heads, the two possibilities are you could have chosen coin one, or you could have chosen coin 2. There is no other possibility, there is no other coin.

617
01:27:21.660 --> 01:27:31.639
Gaurav Singh .: But initial sample space when, quine one can have tail, right? So, the tail event has not been covered in this. Becauseâ€¦

618
01:27:31.640 --> 01:27:38.249
Faculty (Olympus): So, yeah, yeah, because we are looking at conditional probabilities. So, okay, this is not, something Iâ€¦

619
01:27:38.690 --> 01:27:46.630
Faculty (Olympus): Iâ€¦ I covered here, it's, there in the notes. These conditional probabilities are also, you canâ€¦

620
01:27:46.990 --> 01:27:56.469
Faculty (Olympus): a conditional probability also forms a valid, probability distribution, okay? So, if you

621
01:27:56.600 --> 01:28:01.549
Faculty (Olympus): Take, let's say, any, so,

622
01:28:02.210 --> 01:28:09.940
Faculty (Olympus): So, okay, so if I have some sample space omega FP, okay, and you select any event B,

623
01:28:10.380 --> 01:28:14.349
Faculty (Olympus): So, B is one of these events in F, okay? It's some event.

624
01:28:15.630 --> 01:28:20.739
Faculty (Olympus): some event. The only thing is that this, let's say, has positive probability.

625
01:28:21.580 --> 01:28:29.479
Faculty (Olympus): Now, if you define, okay, if you define, PB, As another new function.

626
01:28:29.940 --> 01:28:34.509
Faculty (Olympus): Which is defined as follows. So, PB of, let me rewrite this.

627
01:28:38.130 --> 01:28:44.640
Faculty (Olympus): So, let's define a new function, PB of A.

628
01:28:45.100 --> 01:28:57.730
Faculty (Olympus): as P of A condition on B, okay? So this is now for any Anyâ€¦ eventâ€¦ A in F.

629
01:28:58.140 --> 01:29:06.020
Faculty (Olympus): Then, this new function, PB, okay, is also A valid probability measure.

630
01:29:08.410 --> 01:29:13.959
Faculty (Olympus): Valid probability. Which means that it also satisfies all the axioms.

631
01:29:14.090 --> 01:29:19.570
Faculty (Olympus): ofâ€¦ a probability measure, which means that if I look at PB

632
01:29:20.310 --> 01:29:25.440
Faculty (Olympus): if I look at the conditional probability of the null set.

633
01:29:25.670 --> 01:29:27.299
Faculty (Olympus): This is going to be 0.

634
01:29:27.630 --> 01:29:30.450
Faculty (Olympus): If I look at the conditional probability of

635
01:29:30.780 --> 01:29:34.269
Faculty (Olympus): Omega. It's going to be 1.

636
01:29:34.540 --> 01:29:41.810
Faculty (Olympus): And if you have, let's say, two events, A1, A2, which are disjoint, thenâ€¦

637
01:29:41.990 --> 01:29:49.889
Faculty (Olympus): the conditional probability of A1 union A2 will be the sum of the individual conditional probabilities.

638
01:29:53.720 --> 01:30:02.999
Faculty (Olympus): Okay? So, if you now think of, for example, this, A1 and A2, right?

639
01:30:03.110 --> 01:30:06.249
Faculty (Olympus): So, B corresponds to your E complement.

640
01:30:06.560 --> 01:30:07.070
Gaurav Singh .: Yeah.

641
01:30:07.070 --> 01:30:11.600
Faculty (Olympus): Okay? A1 and A2 are my, these two probabilities.

642
01:30:11.770 --> 01:30:12.400
Gaurav Singh .: Correct.

643
01:30:12.400 --> 01:30:25.079
Faculty (Olympus): Right? This is saying that the sum of those conditional probabilities will be the conditional probability corresponding to A1 union A2. What is A1 union A2? A1 union A2 is exactly omega, right?

644
01:30:25.480 --> 01:30:29.399
Faculty (Olympus): Choosing coin 1 or coin 2 covers the entire sample space.

645
01:30:30.160 --> 01:30:30.740
Faculty (Olympus): So thisâ€¦

646
01:30:30.740 --> 01:30:35.440
Gaurav Singh .: Given me, right, sir, givenâ€¦ given B, right,

647
01:30:35.440 --> 01:30:36.180
Faculty (Olympus): Yeah?

648
01:30:36.780 --> 01:30:37.800
Gaurav Singh .: So,

649
01:30:37.800 --> 01:30:41.430
Faculty (Olympus): But givenâ€¦ given theâ€¦ so this is also true.

650
01:30:41.620 --> 01:30:47.799
Faculty (Olympus): So, probability that you choose something from the universe, given B, is still 1.

651
01:30:48.230 --> 01:30:53.050
Faculty (Olympus): You're going to choose something from the universe. So this is also a valid probability measure.

652
01:30:54.290 --> 01:30:54.990
Gaurav Singh .: Okay.

653
01:30:55.150 --> 01:31:01.799
Faculty (Olympus): Okay? Again, this is, not something I went into, yeah, I thought it might not beâ€¦

654
01:31:01.920 --> 01:31:13.439
Faculty (Olympus): critical, but, given that you've raised the question, I should say, so the main thing is to note that, conditional probabilities are alsoâ€¦ so if you condition on a particular event.

655
01:31:13.870 --> 01:31:18.100
Faculty (Olympus): And then you look at the conditional probability as a new function, right?

656
01:31:18.520 --> 01:31:31.219
Faculty (Olympus): assigns values to different, events, that also forms a valid probability measure, okay? Again, this is there in the notes, so if you want to look at the proof, etc, that is all there in the notes.

657
01:31:31.780 --> 01:31:32.620
Gaurav Singh .: textbooks.

658
01:31:32.620 --> 01:31:33.340
Faculty (Olympus): Okay.

659
01:31:33.810 --> 01:31:36.020
Faculty (Olympus): Nana?

660
01:31:42.110 --> 01:31:57.900
Naina Punjwani: Professor, this, document which you are sharing, I had a concern with that. I am not able to take a print of it. So, you know, the each theorem which you are presenting here, or, so, to differentiate it,

661
01:31:58.310 --> 01:32:03.240
Naina Punjwani: Can it be page-wise so that we are able to differentiate what we learned?

662
01:32:03.780 --> 01:32:08.260
Faculty (Olympus): You mean, this particular, what I'm writing right now?

663
01:32:08.580 --> 01:32:10.540
Naina Punjwani: Yes, yes, Professor.

664
01:32:10.990 --> 01:32:13.570
Faculty (Olympus): So I shared a PDF of this.

665
01:32:13.680 --> 01:32:15.489
Faculty (Olympus): I will share a PDFâ€¦

666
01:32:15.490 --> 01:32:23.499
Naina Punjwani: check the print preview of the PDF now? Yes, Professor, it's very weird. It will not come in A4 sheet.

667
01:32:25.160 --> 01:32:25.740
Faculty (Olympus): Oh, jeez.

668
01:32:25.740 --> 01:32:27.519
Vivek Sahu .: What I'm saying is there's no page break.

669
01:32:28.010 --> 01:32:29.050
Faculty (Olympus): Correct. Yes.

670
01:32:29.050 --> 01:32:30.259
Vivek Sahu .: Pretty much your share.

671
01:32:31.800 --> 01:32:35.889
Faculty (Olympus): I see. Okay, it doesn't have a page break.

672
01:32:36.550 --> 01:32:46.539
Faculty (Olympus): Okay, I don't know of a solution off the top of my head. I'mâ€¦ yeah, I can try and figure something out, where I split it into different pages, andâ€¦

673
01:32:46.540 --> 01:32:48.090
Bipin Karyakarte .: Actually, Professorâ€¦

674
01:32:48.090 --> 01:32:48.880
Faculty (Olympus): for that.

675
01:32:48.880 --> 01:32:58.469
Bipin Karyakarte .: Actually, Professor, if these handwritten notes are fed to ChatGPT or something like that, it creates a very nice Word document or a PDF. I have tried that.

676
01:32:58.470 --> 01:33:10.079
Faculty (Olympus): Okay, yeah, yeah, I'm sure it'll work, but in any case, I will, just to make things easier, I'll look up some way of converting it into a PDF with page breaks.

677
01:33:10.270 --> 01:33:11.180
Faculty (Olympus): That's okay.

678
01:33:12.730 --> 01:33:15.520
Faculty (Olympus): Okay? Yeah, Samruddhi?

679
01:33:19.250 --> 01:33:25.719
Samruddhi Sheth .: Sir, I want to ask a question as, with respect to the exam, per se. I mean, are we.

680
01:33:25.720 --> 01:33:32.380
Faculty (Olympus): Can weâ€¦ can we take that at the very end? Let's first maybe look at the technical material? Yeah, sure. Okay, Harshad,

681
01:33:33.460 --> 01:33:39.440
Harshad Dilip Behere .: Yeah, so Professor, here, I was trying to understand, when we choose a coin too, right.

682
01:33:39.440 --> 01:33:40.000
Faculty (Olympus): Mhmhm.

683
01:33:40.000 --> 01:33:44.690
Harshad Dilip Behere .: our probability of getting hit is always 1, right? I mean, there's no other choice.

684
01:33:44.690 --> 01:33:45.260
Faculty (Olympus): Yeah.

685
01:33:45.260 --> 01:33:49.770
Harshad Dilip Behere .: So then, why we say P of C2 comma H is equal to half, actually?

686
01:33:52.500 --> 01:33:54.669
Harshad Dilip Behere .: In thisâ€¦ in the screen only, the last.

687
01:33:54.670 --> 01:34:01.970
Faculty (Olympus): So, so, see, that is, the probability of choosing coin 2 and getting the hits.

688
01:34:02.630 --> 01:34:04.100
Faculty (Olympus): Right? Soâ€¦

689
01:34:04.210 --> 01:34:12.429
Faculty (Olympus): That probability is going to be half, right? Youâ€¦ because the choice of coin 2, you are equally likely to choosing either coin 1 or coin 2.

690
01:34:13.660 --> 01:34:14.170
Harshad Dilip Behere .: Okay.

691
01:34:14.170 --> 01:34:18.190
Faculty (Olympus): So, withâ€¦ with C2, H is the only possibility.

692
01:34:18.290 --> 01:34:21.659
Faculty (Olympus): But C2H cannot have probability 1.

693
01:34:21.810 --> 01:34:25.140
Faculty (Olympus): Right? C2H will have half probability.

694
01:34:25.290 --> 01:34:30.680
Faculty (Olympus): Because there is also C1H, C1T, they have to have probabilities 1 fourth, 1 4th.

695
01:34:31.250 --> 01:34:39.530
Faculty (Olympus): So this, this is not a conditional probability, this is the probability associated with the singleton that you choose coin 2 and you observe a heads.

696
01:34:40.580 --> 01:34:47.690
Harshad Dilip Behere .: Okay, so we, cannot say that, you know, probability of choosing C2 multiplied by probability of choosing head, that's not going to be there, right?

697
01:34:47.690 --> 01:34:52.949
Faculty (Olympus): No, no, no, no, because this is just the probability associated with that singleton.

698
01:34:53.510 --> 01:34:54.320
Harshad Dilip Behere .: Right?

699
01:34:54.320 --> 01:34:56.770
Faculty (Olympus): That isâ€¦ that is overall 1 half.

700
01:34:57.100 --> 01:35:00.939
Faculty (Olympus): The rest of the 1 half mass is with the C1H and C1T.

701
01:35:02.480 --> 01:35:04.230
Harshad Dilip Behere .: Okay, fine, got it, thank you.

702
01:35:04.230 --> 01:35:09.080
Faculty (Olympus): Yeah? Okay, abhishek? Abhishek Agarwal?

703
01:35:09.080 --> 01:35:18.689
Abhishek Agrawal .: Yes, hi, Professor. So, I had a question, is like, the choosing of the coin actually happened before, observing heads or tails.

704
01:35:18.860 --> 01:35:21.630
Abhishek Agrawal .: So, how can it update? Or howâ€¦

705
01:35:22.040 --> 01:35:27.150
Abhishek Agrawal .: Seeing heads or tails can update, choosing of the coin probability.

706
01:35:27.150 --> 01:35:42.530
Faculty (Olympus): So, this is about how I pose the question, right? So, let's say this, this, I was running the experiment, okay? I, in a particular room, I chose one of the two coins, and I tossed it, right?

707
01:35:42.530 --> 01:35:51.620
Faculty (Olympus): And then I came out, and I don't tell you anything else, and I just ask you, you know, how likely is it that the experiment that I just ran, I chose coin one?

708
01:35:52.310 --> 01:35:55.389
Faculty (Olympus): If I don't tell you anything, you will say, yeah, half.

709
01:35:55.970 --> 01:36:04.439
Faculty (Olympus): But I come out, and I tell you, you know, I observed the heads, now how likely do you think I had seen coin one?

710
01:36:05.230 --> 01:36:09.060
Faculty (Olympus): Okay. So now yourâ€¦ your probability changes, right?

711
01:36:09.450 --> 01:36:22.520
Faculty (Olympus): So it is, there isâ€¦ we're not thinking about the temporal aspect here. This is about what information do you have, and how does that change your belief about what, whether something happened or not.

712
01:36:22.980 --> 01:36:30.089
Abhishek Agrawal .: Okay, so it's just a belief, not theâ€¦ because this PA1, we actually got it from the sample space, so.

713
01:36:30.090 --> 01:36:31.049
Faculty (Olympus): Yeah, yeah, yeah.

714
01:36:31.050 --> 01:36:32.990
Abhishek Agrawal .: We shoot images, same, right?

715
01:36:32.990 --> 01:36:37.570
Faculty (Olympus): Yeah, yeah, I mean, this is about belief. This is about how likely do you think

716
01:36:37.700 --> 01:36:39.749
Faculty (Olympus): Something would have happened.

717
01:36:40.490 --> 01:36:41.510
Abhishek Agrawal .: Got it, thank you.

718
01:36:41.510 --> 01:36:43.600
Faculty (Olympus): Okay, Sajith?

719
01:36:46.830 --> 01:36:55.250
Sajith K N .: Yeah, sir, one question. So, so can we rewrite the second form, like, prior likelihood and total probability?

720
01:36:56.280 --> 01:36:58.769
Sajith K N .: Is that possible to write in this case also?

721
01:36:59.810 --> 01:37:03.650
Faculty (Olympus): Oh, you mean, like, this probability of E complement?

722
01:37:05.360 --> 01:37:09.720
Faculty (Olympus): You mean, can I write that in terms of the conditional probabilities?

723
01:37:12.790 --> 01:37:15.179
Faculty (Olympus): I'm not sure what Iâ€¦ what you mean.

724
01:37:15.180 --> 01:37:15.570
Sajith K N .: Yeah.

725
01:37:15.900 --> 01:37:16.990
Faculty (Olympus): The formula?

726
01:37:17.380 --> 01:37:29.979
Faculty (Olympus): You can write that. We had already done that before, so I didn't rewrite it. So, we had already, computed this probability of E by using that law of total probability, so I didn't write it again.

727
01:37:30.270 --> 01:37:32.740
Faculty (Olympus): But you can do that.

728
01:37:33.460 --> 01:37:33.870
Sajith K N .: Oh, okay.

729
01:37:33.870 --> 01:37:37.979
Faculty (Olympus): Right? So you could write that probability of E complement in this form.

730
01:37:39.450 --> 01:37:40.420
Faculty (Olympus): by taking.

731
01:37:40.670 --> 01:37:41.330
Sajith K N .: theâ€¦

732
01:37:41.330 --> 01:37:43.610
Faculty (Olympus): Vijay's to be the various AIs.

733
01:37:45.480 --> 01:37:46.100
Sajith K N .: Okay.

734
01:37:46.100 --> 01:37:48.100
Faculty (Olympus): Yeah, yeah, that is how you would compute.

735
01:37:48.420 --> 01:37:48.980
Sajith K N .: Yeah.

736
01:37:50.310 --> 01:37:53.049
Faculty (Olympus): Okay, Siddheshâ€¦

737
01:37:55.490 --> 01:37:57.890
Siddhesh Dinesh Kadam .: Yes. So,

738
01:37:58.280 --> 01:38:11.300
Siddhesh Dinesh Kadam .: ifâ€¦ so this is updating Belief Red, and because you gave that example of machine learning, right? Yeah. If we were to run this multiple times, wouldn't the belief be updated to always select,

739
01:38:11.530 --> 01:38:12.420
Siddhesh Dinesh Kadam .: A2.

740
01:38:12.580 --> 01:38:17.020
Siddhesh Dinesh Kadam .: So that our condition of having the heads is satisfied.

741
01:38:17.290 --> 01:38:27.630
Faculty (Olympus): I mean, if you keep, observing heads, I mean, here, it depends. If youâ€¦ so suppose, okay, suppose you choose the coin only once.

742
01:38:28.160 --> 01:38:32.530
Faculty (Olympus): Okay, and then once you've chosen the coin, you will keep tossing that coin.

743
01:38:33.100 --> 01:38:33.840
Faculty (Olympus): Right?

744
01:38:33.840 --> 01:38:34.460
Siddhesh Dinesh Kadam .: Alright.

745
01:38:34.460 --> 01:38:40.719
Faculty (Olympus): Now, if I, tell you that, okay, this is a good, maybe goodâ€¦

746
01:38:40.830 --> 01:38:45.120
Faculty (Olympus): So, suppose you choose, one coin.

747
01:38:47.680 --> 01:38:54.530
Faculty (Olympus): Okay? And you toss itâ€¦ Twice, and you observe heads both times.

748
01:38:57.460 --> 01:39:04.730
Faculty (Olympus): Right? And you again ask me what is the probability that I would have chosen coin 1, given

749
01:39:05.100 --> 01:39:08.100
Faculty (Olympus): that I observed this heads-heads.

750
01:39:08.430 --> 01:39:14.359
Faculty (Olympus): And what is the probability of that I had chosen coin 2, given I observed 2 heads?

751
01:39:15.060 --> 01:39:20.819
Faculty (Olympus): Right? When I tossed the coin once, the belief changed to 1x3, 2x3.

752
01:39:21.360 --> 01:39:26.119
Faculty (Olympus): Right? Whatâ€¦ what do you think would happen if I talkâ€¦ if I nowâ€¦ so the choâ€¦

753
01:39:26.230 --> 01:39:29.829
Faculty (Olympus): Choice of the coin is fixed once and for all.

754
01:39:30.170 --> 01:39:32.829
Faculty (Olympus): And I'm telling you that I observed 2 heads.

755
01:39:33.880 --> 01:39:34.770
Faculty (Olympus): Right?

756
01:39:34.770 --> 01:39:44.270
Siddhesh Dinesh Kadam .: So, you'll end up choosing, so it puts skew starts lookingâ€¦ say, if we talk purely from iterative basis, we'll do a skewing towards 1 for A2.

757
01:39:44.270 --> 01:39:55.289
Faculty (Olympus): Exactly. So, what is going to happen is, as you collect more and more evidence in favor of A2, you are going to spread more and more. So it was 1x3, 2x3, then it's going to further spread out.

758
01:39:55.290 --> 01:39:56.250
Siddhesh Dinesh Kadam .: Pradeep design.

759
01:39:56.250 --> 01:40:03.000
Faculty (Olympus): So, 1x3 will become smaller, 2x3 will become higher, and it'll start going towards, 0 and 1.

760
01:40:03.320 --> 01:40:11.229
Faculty (Olympus): So this is a good, actually, exercise to compute. See if you can work out what it'll be if you observe two heads.

761
01:40:11.300 --> 01:40:23.509
Faculty (Olympus): Instead of one. So you've chosen a coin, but now your experiment says you choose a coin, and then you toss it twice, and we are askingâ€¦ we observe that both of these tosses gave you heads.

762
01:40:24.080 --> 01:40:26.609
Faculty (Olympus): What is your belief now about Coinbun?

763
01:40:26.760 --> 01:40:29.270
Faculty (Olympus): Or whether coin 1 was chosen or coin 2 was chosen.

764
01:40:30.940 --> 01:40:31.770
Faculty (Olympus): Okay?

765
01:40:32.280 --> 01:40:34.390
Faculty (Olympus): Okay, Devendra?

766
01:40:37.220 --> 01:40:45.859
Devendra Parmar .: Yes, sir. Sir, my question was related to one recent question which was asked. Given the second coin has been chosen, and we get heads.

767
01:40:46.130 --> 01:40:51.409
Devendra Parmar .: So, how is the probability half instead of 1? So, could it be looked at like this?

768
01:40:51.410 --> 01:40:58.180
Faculty (Olympus): So, so, Sarika, one second, huh? This isâ€¦ it's not that thing, it'sâ€¦ this isâ€¦ this doesn't correspond toâ€¦

769
01:40:59.240 --> 01:41:03.829
Faculty (Olympus): given coin to observing heads. This is not that probability.

770
01:41:04.720 --> 01:41:05.729
Faculty (Olympus): Okay, this is the.

771
01:41:05.730 --> 01:41:06.770
Devendra Parmar .: Possibility?

772
01:41:07.790 --> 01:41:08.959
Devendra Parmar .: Yes, sir, go ahead.

773
01:41:08.960 --> 01:41:18.290
Faculty (Olympus): So this is the probability associated with this element, C2H, which corresponds to C2 being chosen and heads being observed.

774
01:41:19.060 --> 01:41:21.519
Faculty (Olympus): Okay, it's not a conditional probability.

775
01:41:22.690 --> 01:41:29.120
Devendra Parmar .: Okay, can it be looked like this? Like, choosing a coin? Choosing the second coin gives the probability of half.

776
01:41:30.000 --> 01:41:35.480
Devendra Parmar .: And then, once we chose the second coin, then multiply it by that, 1. That is, we will get heads only.

777
01:41:35.480 --> 01:41:39.869
Faculty (Olympus): Yeah, yeah. So you can think of it via, for example, the multiplicative rule.

778
01:41:40.900 --> 01:41:41.809
Devendra Parmar .: Okay, sir, thank you.

779
01:41:41.860 --> 01:41:46.510
Faculty (Olympus): So, you can think of that as saying probability of observeâ€¦ probability ofâ€¦

780
01:41:46.630 --> 01:42:03.490
Faculty (Olympus): Choosing coin 2 and observing heads can be thought of as the probability of choosing coin 2 times the conditional probability of heads given coin 2 was chosen. Now, the probability of observing heads given coin 2 is just 1.

781
01:42:03.850 --> 01:42:06.579
Faculty (Olympus): And probability of choosing coin 2 is half.

782
01:42:07.910 --> 01:42:09.559
Devendra Parmar .: Got it. Okay, thank you, sir.

783
01:42:09.560 --> 01:42:17.470
Faculty (Olympus): Yeah. Okay, yeah, I don't know. Nana, do you still have another question?

784
01:42:23.130 --> 01:42:26.019
Faculty (Olympus): Okay, it's not, Gaurav?

785
01:42:26.020 --> 01:42:27.229
Naina Punjwani: What do Iâ€¦

786
01:42:27.750 --> 01:42:29.060
Faculty (Olympus): Okay, I see, okay.

787
01:42:29.300 --> 01:42:34.729
Faculty (Olympus): Okay, yeah, Samrati, now, now perhaps you can ask,

788
01:42:38.050 --> 01:42:48.810
Samruddhi Sheth .: Yeah, this was about the exam, per se. I really want to understand how and what exactly will be there in our exams, because

789
01:42:48.890 --> 01:42:58.130
Samruddhi Sheth .: As much as I understand, we have been, learning, or probably understanding multiple theorems and ending up to a formula.

790
01:42:58.440 --> 01:42:58.960
Faculty (Olympus): Yeah.

791
01:42:59.190 --> 01:43:12.440
Samruddhi Sheth .: So, do we need to actually, mug up those formulas and end up to a resolution whereâ€¦ which, to be applied at what problem? Is that what is expected from us in an exam?

792
01:43:12.440 --> 01:43:25.950
Faculty (Olympus): No, so youâ€¦ you don't have to mug up formulas. Most likely, in yourâ€¦ so, definitely in your Nsem exam, which is going to be in person, we will even allow you to bring your notes, etc.

793
01:43:26.000 --> 01:43:46.630
Faculty (Olympus): In your midsem exam exam, there will be probably a sheet which will be shared by us, which contains all these formulas, so you don't have to mug up any formulas. But you have to understand, I mean, the formulas will be there, but which one should you apply, or which one is applicable, how to use what? That is what you have to learn.

794
01:43:46.960 --> 01:43:47.670
Samruddhi Sheth .: Okay, got me.

795
01:43:47.670 --> 01:43:55.919
Faculty (Olympus): So, when should I use Bayes' rule? When should I use the law of total probability? These are the things that you have to learn. But you don't have to mug up formulas, no.

796
01:43:55.920 --> 01:43:57.780
Samruddhi Sheth .: Yeah, okay, thank you, sir.

797
01:43:57.780 --> 01:44:00.090
Faculty (Olympus): Yeah, okay. Vivekâ€¦

798
01:44:00.780 --> 01:44:16.509
Vivek Sahu .: Yeah, Professor, I bought the book, Sheldon Ross book, so I think it is very extensive, so should I be just going through your, you know, lecture and pick up those, details from the book and read it up, or should I be reading the whole book?

799
01:44:16.630 --> 01:44:17.589
Faculty (Olympus): No, I mean.

800
01:44:17.590 --> 01:44:33.980
Bipin Karyakarte .: Professor, I have a similar question. I was waiting for the end of the lecture. See, basically, there is a lot of preparatory work that we need to do. I tried a few things, but I obviously need a lot more understanding of basic things. From that angle.

801
01:44:33.980 --> 01:44:40.770
Bipin Karyakarte .: Ross' book is actually 850 pages, so any specific chapters, like Chapter 1, 2, 8.

802
01:44:40.770 --> 01:45:00.409
Faculty (Olympus): Yeah, yeah, so, I mean, whenever I'm posting anything, I'm also mentioning the corresponding chapters. Okay. Those are the chapters that you have toâ€¦ that we are going through. As we go through material, those are the chapters where this relevant content is. So, I don't expect you to read the Raw's book end-to-end.

803
01:45:00.410 --> 01:45:02.189
Faculty (Olympus): Of course not, no, no.

804
01:45:02.190 --> 01:45:27.189
Bipin Karyakarte .: That is one thing, that is one thing, Professor, but there are obviously certain things which we should know as a fundamental understanding, so that, you know, we can relate to what you are saying in the class. So, are there any specific, either in the Ross book itself, any specific topics, or any specific chapters, or any other material which we can read to prepare ourselves in order to attend? Because all of, probably a lot of people have left statistics long

805
01:45:27.190 --> 01:45:27.960
Bipin Karyakarte .: Rachel?

806
01:45:27.960 --> 01:45:28.360
Faculty (Olympus): pusher.

807
01:45:28.360 --> 01:45:29.629
Bipin Karyakarte .: How do we prepare ourselves?

808
01:45:29.630 --> 01:45:41.250
Faculty (Olympus): So, the Ross book is also, kind of tailored in a way where we slowly build up, things, and that is how I also want to go. So, I would sayâ€¦

809
01:45:41.380 --> 01:46:00.299
Faculty (Olympus): yeah, whatever material, for example, I'm sharing, plus the pointers that I'm giving to the various sections, that is the material that you should try and read. And the second most important thing is, please attend TA sessions. Practicing problems will be the most important thing, because that, I mean.

810
01:46:00.400 --> 01:46:08.710
Faculty (Olympus): It'll alsoâ€¦ one, itâ€¦ one, it'll give you thisâ€¦ get you back into that mode of problem solving, which, like you were saying, maybe many of you have, notâ€¦

811
01:46:09.080 --> 01:46:27.330
Faculty (Olympus): encountered in a while. But secondly, also, it will give you more confidence, more understanding about the general math as well, or the theorems as well, how they can be used, where they can be used, and so on. So please make sure you do the problems, and you go to the TA sessions.

812
01:46:27.330 --> 01:46:31.910
Faculty (Olympus): And when we share the problem sheets, you try and attempt as many of them as possible, and so on.

813
01:46:32.000 --> 01:46:45.329
Faculty (Olympus): So, again, for the TA sessions, we'll have these two, like I said, two parallel sessions. One will be a little slower, where they go slowly over all topics, all steps, and the other one will be a little faster, whereâ€¦

814
01:46:46.000 --> 01:46:55.259
Faculty (Olympus): If you are, kind of, if you know, if you have prior experience, then you can join that one, and that'll just be a little quicker.

815
01:46:55.810 --> 01:47:02.520
Vivek Sahu .: So, Professor, maybe I missed it. Does your note indicate where toâ€¦ which thing to read in Ross book for theâ€¦

816
01:47:02.520 --> 01:47:15.630
Faculty (Olympus): So, the announcement will say, the announcement email where I attach my notes, that always mentions which chapters I'mâ€¦ I mean, where the topics are. The material will not probably be the same.

817
01:47:15.830 --> 01:47:18.529
Faculty (Olympus): But, the topics are there.

818
01:47:19.160 --> 01:47:20.860
Vivek Sahu .: in the Great Learning website.

819
01:47:20.860 --> 01:47:22.850
Faculty (Olympus): Yeah, yeah, yeah, yeah, yeah, yeah.

820
01:47:23.190 --> 01:47:28.290
Vivek Sahu .: Maybe I missed it, I don't know if other people have noticed this. I will check, yeah.

821
01:47:28.290 --> 01:47:34.139
Dinesh Devnath Yadav .: Actually, I was checking the notes, handwritten notes, but that is not included. Maybe, I can.

822
01:47:34.140 --> 01:47:42.550
Faculty (Olympus): Yeah, it's not there in the handwritten notes, but the email has pointers to which chapters the topics are from.

823
01:47:42.560 --> 01:47:44.199
Dinesh Devnath Yadav .: Thank you. Thank you, Prasan.

824
01:47:44.200 --> 01:47:47.840
Faculty (Olympus): Okay? Yeah, Rahulâ€¦ Joshi?

825
01:47:49.620 --> 01:47:52.620
Rahul Joshi .: Professor, just one question, long background.

826
01:47:52.620 --> 01:47:53.260
Faculty (Olympus): Sorry.

827
01:47:53.580 --> 01:48:11.270
Faculty (Olympus): By the way, sorry. So, by the way, for others, if, unless you're waiting to ask me or you want to hear, the material for today is done, so if you want to leave, please feel free to, leave. We will continue next time, on,

828
01:48:11.400 --> 01:48:25.939
Faculty (Olympus): I think I will probably do one example on conditional probability, maybe, but otherwise we will move towards, some counting and sampling, and then we'll go ahead.

829
01:48:26.460 --> 01:48:35.030
Faculty (Olympus): Sorry, no, next time, I think, is the independence between events, and then we'll go to counting and sampling. Okay, yeah, sorry, sorry, you go ahead.

830
01:48:35.320 --> 01:48:49.340
Rahul Joshi .: Yeah, yeah, thanks, Professor. Just one question. So, long back, maybe 20 years back, I have done some statistics using a book called Levin and Rubin, which covers more or less all these topics. Is it okay if I continue to use.

831
01:48:49.340 --> 01:48:57.869
Faculty (Olympus): Yeah, yeah, yeah, I mean, yeah, yeah, I don't have anything specific about Ross, per se. If you are more comfortable with that book, please go ahead. That's okay.

832
01:48:57.870 --> 01:48:59.610
Rahul Joshi .: Okay, okay, thank you, sir.

833
01:48:59.610 --> 01:49:03.560
Faculty (Olympus): Sure. Yeah, Prachiki Kumari,

834
01:49:04.040 --> 01:49:10.830
Lad Prachikumari Vijaykumar .: Sir, do we have any NPTL courses for this topic, so I can prefer in future,

835
01:49:10.960 --> 01:49:12.790
Faculty (Olympus): If yoursâ€¦

836
01:49:13.140 --> 01:49:14.300
Lad Prachikumari Vijaykumar .: If you are sentâ€¦

837
01:49:14.750 --> 01:49:34.559
Faculty (Olympus): I think I, yeah, I don't recall whether weâ€¦ whether I mentioned inâ€¦ in the first, lecture where we put up the references, I think I might have mentioned two courses. One NPTEL course is by, Professor Krishna Jagannathan, at IIT Madras.

838
01:49:37.030 --> 01:49:45.759
Faculty (Olympus): I mean, yeah, theseâ€¦ the NPTIL courses are full semester-long courses targeted towards undergraduate and graduate students, so it will be very extensive.

839
01:49:46.130 --> 01:49:53.150
Faculty (Olympus): It'll be very detailed, so if that is something that you prefer, Piya, please, please look up

840
01:49:53.360 --> 01:50:02.730
Faculty (Olympus): That there is also the MIT OCW, there is a course, I think that linkâ€¦ those links are also there, if I remember correctly, inâ€¦

841
01:50:02.830 --> 01:50:09.110
Faculty (Olympus): in the first, lecture slides, I might have that,

842
01:50:09.110 --> 01:50:09.600
Lad Prachikumari Vijaykumar .: Oh, goodness.

843
01:50:09.600 --> 01:50:13.239
Faculty (Olympus): Just give me a second, I can, look that up.

844
01:50:13.830 --> 01:50:15.590
Faculty (Olympus): One second nowâ€¦

845
01:50:21.220 --> 01:50:29.129
Faculty (Olympus): Yeah, those two courses are, in fact, there in that online resources last slide of Lecture 1, if you go there, the two courses are mentioned.

846
01:50:29.610 --> 01:50:31.930
Lad Prachikumari Vijaykumar .: Okay, okay, sir, thank you very much.

847
01:50:31.930 --> 01:50:37.219
Faculty (Olympus): Yeah? Okay. Jawahar in Ugopal?

848
01:50:37.470 --> 01:50:43.150
Jawahar Venugopal .: Yeah, hi, Professor. So, regarding all these, formulas.

849
01:50:43.150 --> 01:50:43.510
Faculty (Olympus): Yeah.

850
01:50:43.510 --> 01:50:53.129
Jawahar Venugopal .: So, they're usually associated with, some proof also, right? Like, how they are derived, and I think from an understanding perspective, yes.

851
01:50:53.130 --> 01:50:53.700
Faculty (Olympus): Yeah.

852
01:50:53.700 --> 01:51:03.200
Jawahar Venugopal .: It is good that we go through it, but from an exam point of view, will it be required that, we might have to prove any of these, formulas?

853
01:51:03.200 --> 01:51:19.230
Faculty (Olympus): Yeah, so you can assume whatever we are covering, you can assume that as given. So itâ€¦ yeah, you won't have to prove the law of total probability, or Bayes' rule. Those areâ€¦ those you can assume as given. We might ask you to prove something else.

854
01:51:19.290 --> 01:51:29.540
Faculty (Olympus): Right? Something maybe on top of it. Using these formulas, you might be able to useâ€¦ you might be asked to use these formulas, or you might be asked to prove something small using these formulas.

855
01:51:29.650 --> 01:51:33.079
Faculty (Olympus): But, these formulas by themselves, you can assume as given.

856
01:51:35.130 --> 01:51:44.100
Faculty (Olympus): If you're interested in the proof, the proof, like I said, are there in the notes. Please feel free to see the proofs if you feel, yeah, if you're interested.

857
01:51:45.510 --> 01:51:46.530
Jawahar Venugopal .: Thank you, thank you.

858
01:51:46.530 --> 01:51:49.310
Faculty (Olympus): Yeah, okay. Vallab Mulye?

859
01:51:49.700 --> 01:52:04.790
Vallabh Mulye: Yeah, hi, good afternoon, Professor. Sir, you mentioned, twice the emails that you sent for the notes. Honestly, I get the emails only from this, great learning about the schedule, the meeting invites, so is there any otherâ€¦

860
01:52:04.790 --> 01:52:14.089
Faculty (Olympus): There areâ€¦ so on the portal, there is an announcements section. I don't know whether those actually show up as emails for you. Maybe you have to go to the portal and see the announcements section.

861
01:52:14.360 --> 01:52:14.960
Vallabh Mulye: Okay.

862
01:52:14.960 --> 01:52:18.810
Faculty (Olympus): I don't know how Great Learningâ€¦ I don't know whether someone from Great Learning is here.

863
01:52:19.330 --> 01:52:20.039
Faculty (Olympus): You've beenâ€¦

864
01:52:20.040 --> 01:52:25.569
Shikhar .: notification bell there, it will redirect you to all the announcements and emails which are there.

865
01:52:25.680 --> 01:52:27.160
Shikhar .: There you can see.

866
01:52:27.530 --> 01:52:28.060
Faculty (Olympus): Yeah.

867
01:52:29.620 --> 01:52:30.220
Vallabh Mulye: Great.

868
01:52:30.570 --> 01:52:31.010
Faculty (Olympus): Yep.

869
01:52:31.010 --> 01:52:31.730
Vallabh Mulye: Thank you.

870
01:52:31.730 --> 01:52:34.090
Faculty (Olympus): Okay? Sridh Pandey?

871
01:52:36.280 --> 01:52:55.129
Kshitij Pandey .: Yes, good afternoon, sir. I was just going through the three properties you just mentioned. So, I've come to the conclusion that the multiplication rule and the law of probability, if you combine them, it comes out to be Bayes' rule. Bayes' rule is nothing special or different. Is my conclusion correct? Or is there some difference?

872
01:52:55.630 --> 01:53:08.309
Faculty (Olympus): I mean, there is nothing special in the sense it, yeah, it is a compâ€¦ you can use the Bayesâ€¦ yeah, so Bayes Rule just comes from the definition of conditional probability. There is, nothing more to it.

873
01:53:08.550 --> 01:53:15.930
Faculty (Olympus): It is, it has a certain interpretation, which I think is why,

874
01:53:16.720 --> 01:53:31.759
Faculty (Olympus): why it is, it gets this kind of attention, and the interpretation is in terms of how should you update the belief when you observe some data. But by itself, if you know the multiplicative rule and you know the law of total probability, then there is no proof

875
01:53:32.020 --> 01:53:40.070
Faculty (Olympus): There is no kind of non-trivial proof for Bayes' rule. Bayes' rule is just immediate by just using theâ€¦ these two properties.

876
01:53:40.480 --> 01:53:41.150
Faculty (Olympus): Yeah.

877
01:53:41.370 --> 01:53:42.550
Kshitij Pandey .: Okay, thank you.

878
01:53:43.200 --> 01:53:46.060
Faculty (Olympus): Okay, varun Kumar?

879
01:53:48.570 --> 01:54:05.709
varun kumar .: Hey, hi, Professor. So, one thing, I mean, going through books and all is, you know, very comâ€¦ it needs comprehensive, for that, people who need comprehensive understanding. So, my understandingâ€¦ my question is, canâ€¦ if I go through what you are teaching in this class, per se, let's say.

880
01:54:06.470 --> 01:54:21.680
varun kumar .: Is thatâ€¦ and if anything I'm not understanding in this class, I can attend TA also, but let's say I'm trying to understand through ChatGPT, Cloud or something. Is that enough? Because, you know, I can'tâ€¦ I don't want to be master in probability.

881
01:54:21.810 --> 01:54:25.570
varun kumar .: I can't be, I know. So, for that matter, is that enough?

882
01:54:25.570 --> 01:54:38.729
Faculty (Olympus): I mean, if you ask me my personal preference, I always prefer books, because they have a specificâ€¦ I mean, it matters how you present the material, right? And, how it builds up through

883
01:54:38.840 --> 01:54:51.410
Faculty (Olympus): When, when you're, when we are writing, so I would definitely, get, definitely recommend looking at the book and going through the chapters, andâ€¦

884
01:54:51.460 --> 01:55:08.920
Faculty (Olympus): Yeah, I mean, unless I think that amount of time and effort is invested in definitely this type of a course, which is mathematical, I don't know how much you'll be able to gain from it. So it'll take you to some place, yes, if you read, you know, if you attend my sessions, you go to the TA sessions.

885
01:55:08.920 --> 01:55:15.760
Faculty (Olympus): You use whatever online resources. Yeah, all of them are, of course, also possible ways of doing it, and you have to figure out what works for you.

886
01:55:16.040 --> 01:55:21.930
Faculty (Olympus): But, yeah, I would definitelyâ€¦ if you ask my personal opinion, Iâ€¦ yeah, I would definitely recommend goingâ€¦

887
01:55:21.930 --> 01:55:33.330
varun kumar .: I mean, I don't have any preference that I should go with online courses, online things only, but what I'm noticing here is, when I'm looking for books, I'm seeing that 10 recommendations of books.

888
01:55:33.330 --> 01:55:40.560
Faculty (Olympus): No, no, but we have already recommended, I've already given you recommendations. You don't have to necessarily search for new unless you want to.

889
01:55:40.790 --> 01:55:50.240
Faculty (Olympus): There is already a recommended book, and we always point to chapters from that book. There are other recommendations also if you're interested in seeing more things.

890
01:55:50.570 --> 01:56:01.829
varun kumar .: So, becauseâ€¦ let me be very specific. So, in today's class itself, I see that there are 5 recommendations, recommended book mentioned in this chat.

891
01:56:02.330 --> 01:56:03.810
varun kumar .: The first one is the.

892
01:56:03.810 --> 01:56:17.690
Faculty (Olympus): No, no, see, those are not my recommendations, so these might be books that areâ€¦ that your colleagues are recommending. None of these have anything to do with me. I haven't made any recommendation. I made my recommendations very clear in the first lecture itself.

893
01:56:18.000 --> 01:56:27.669
Faculty (Olympus): about what book I would recommend, and there are other resources as well. Of course, different people might be recommending different books, and yeah, you have to.

894
01:56:27.670 --> 01:56:29.409
varun kumar .: No, I thought it is coming fromâ€¦

895
01:56:29.410 --> 01:56:35.190
Faculty (Olympus): No, no, it's not, I don't think, at least I haven't, I haven't mentioned any other books.

896
01:56:36.670 --> 01:56:37.930
varun kumar .: Yeah. Okay, fine.

897
01:56:37.930 --> 01:56:38.530
Faculty (Olympus): Okay.

898
01:56:38.950 --> 01:56:42.580
Faculty (Olympus): Okay, devendra Parmar?

899
01:56:45.480 --> 01:56:50.850
Devendra Parmar .: Yes, sir. Sir, can you please scroll to the end part of the second rule?

900
01:56:51.380 --> 01:56:56.080
Faculty (Olympus): Second rule, so, hereâ€¦

901
01:56:58.150 --> 01:57:06.440
Devendra Parmar .: Sir, little about it? Yes, sir, this green portion, yes, sir. This calculation had little down. Okay. Can you please scroll a little down?

902
01:57:09.370 --> 01:57:11.390
Devendra Parmar .: The end calculation of it.

903
01:57:11.390 --> 01:57:13.120
Faculty (Olympus): Okay. This?

904
01:57:13.410 --> 01:57:24.560
Devendra Parmar .: Yes, sir. Sir, just wanted to ask this 1 by 4, it's the sumâ€¦ it's the multiplication of this first part, right? Yeah. P , and not that plus 1 by 2 included in that.

905
01:57:24.560 --> 01:57:28.690
Faculty (Olympus): No, no, no, the plus 1 by 2 is getting multiplied by a 0, right? Soâ€¦

906
01:57:29.010 --> 01:57:31.220
Devendra Parmar .: Okay, got it, got it, yes.

907
01:57:31.510 --> 01:57:33.909
Devendra Parmar .: Vottage. Okay, thank you. Okay.

908
01:57:34.450 --> 01:57:36.850
Faculty (Olympus): Harshadâ€¦

909
01:57:37.490 --> 01:57:49.650
Harshad Dilip Behere .: Thank you, Professor, for staying back so long. So, this is with respect to exam. As you mentioned, that we are not supposed to be asking it to prove these theorems, right, in the exam, because we have to readily use this formula.

910
01:57:49.670 --> 01:57:50.380
Faculty (Olympus): Yeah.

911
01:57:50.380 --> 01:58:10.220
Harshad Dilip Behere .: be available like an open notebook. So, is it all aboutâ€¦ I mean, there could be multiple formulas or multiple formations which may give a same answer. So, is it about judging a right formation formula, and is it something like, you're going to check our scales, saying how best, you know, we are able to apply this to the given.

912
01:58:10.220 --> 01:58:24.489
Faculty (Olympus): Yeah, yeah. So, for example, I mean, there might be a question which is about finding the probability. There, you know, you're running some data science experiment, and you observe some event, or there is some event of interest.

913
01:58:24.490 --> 01:58:32.069
Faculty (Olympus): And we ask you, what is the probability of this event, right? Now, it doesn't say that, you know, you have to see that event and

914
01:58:32.210 --> 01:58:49.270
Faculty (Olympus): kind of think about howâ€¦ what is the best way of computing the probability of that event? Is that eventâ€¦ can it be written as a union of some smaller events, and then maybe you can use the inclusion-exclusion, or you can use union-bound, right? That might be one possibility. Orâ€¦

915
01:58:49.550 --> 01:59:08.060
Faculty (Olympus): can that eventâ€¦ is its complement easier to analyze? So then maybe you have to go look at the complement, and if that is easy to analyze, then you can compute the probability of the original event, and so on. So, I mean, it is aboutâ€¦ it is not going to say, use this formula to compute this probability. That is not how, at least.

916
01:59:08.480 --> 01:59:22.629
Faculty (Olympus): That is not how we are going to test, but it is also not about testing whether you remember all the formulas in the world. So that is not what we are trying to test either. It is about, you know, when encountered with, let's say, a problem.

917
01:59:22.770 --> 01:59:30.109
Faculty (Olympus): Will you be able to, utilize the tools that you have learned In the best possible way.

918
01:59:30.950 --> 01:59:36.750
Harshad Dilip Behere .: Yeah, so is there a possibility that, you know, there are more than one tools which can give you the right answers?

919
01:59:36.750 --> 01:59:41.739
Faculty (Olympus): Yeah, yeah, yeah. So, I mean, if you think about, let's say, a simple question like,

920
01:59:42.050 --> 01:59:46.350
Faculty (Olympus): You toss a coin 3 times, and I ask you.

921
01:59:46.480 --> 02:00:00.960
Faculty (Olympus): Do you see a heads in any one of these tosses, right? Now, you can write this as a union. You can say, okay, this is the union of seeing a heads in the first toss, then second toss, then third toss. That is one way.

922
02:00:01.200 --> 02:00:06.349
Faculty (Olympus): But you can also say, I'll look at the complement, which says the probability that I see no heads.

923
02:00:06.720 --> 02:00:12.849
Faculty (Olympus): I see your tails all the time. So now, clearly, the second choice is slightly better, it's easier, it's a one-shot thing.

924
02:00:13.050 --> 02:00:15.060
Faculty (Olympus): You can immediately do it.

925
02:00:15.480 --> 02:00:19.920
Faculty (Olympus): Soâ€¦ so yeah, that's the kind ofâ€¦ and this will only come from practice.

926
02:00:20.850 --> 02:00:22.280
Harshad Dilip Behere .: Sure, thank you so much.

927
02:00:22.280 --> 02:00:22.910
Faculty (Olympus): Sure.

928
02:00:23.210 --> 02:00:25.589
Faculty (Olympus): Okay, Siddharthâ€¦

929
02:00:25.970 --> 02:00:31.880
Siddharth Digambar Kulkarni .: So, from practice only, I wanted to know, will there be any practice assignments?

930
02:00:31.880 --> 02:00:34.890
Faculty (Olympus): Yeah, yeah, yeah, we'll share a practice sheet, I'll share a practice.

931
02:00:34.890 --> 02:00:38.600
Siddharth Digambar Kulkarni .: I think that will bring more confidence to us.

932
02:00:38.600 --> 02:00:50.090
Faculty (Olympus): Yeah, yeah, yeah. I mean, now I think we've covered enough material that I can share a practice sheet, and you will have a material to do, but in the TA session also, they will solve problems. But we will have a practice sheet, and there will also be homework.

933
02:00:50.090 --> 02:00:52.610
Siddharth Digambar Kulkarni .: alone gives more confidence, right?

934
02:00:52.610 --> 02:00:54.589
Faculty (Olympus): Oh, sure. Sure, yeah, I agree.

935
02:00:54.810 --> 02:00:55.860
Siddharth Digambar Kulkarni .: Okay, okay.

936
02:00:57.050 --> 02:00:57.700
Faculty (Olympus): Okay.

937
02:00:58.320 --> 02:01:01.670
Faculty (Olympus): Gaurav, do you have a question?

938
02:01:01.670 --> 02:01:08.880
Gaurav Singh .: Yes, Prof, like, in this particular example, whatâ€¦ what we can call as a prior belief

939
02:01:09.240 --> 02:01:28.969
Gaurav Singh .: And what is my updated belief? Basically, prior belief was that I'll be getting coin with probability of 1x2, and now the updated belief is 1x3 and 2x3. I mean, I'm just trying to correlate with the way we started this topic, right?

940
02:01:28.970 --> 02:01:37.270
Faculty (Olympus): Yeah, so, I mean, we areâ€¦ the priorâ€¦ so, we are thinkâ€¦ the prior belief is about which of the two coins was chosen.

941
02:01:37.700 --> 02:01:50.270
Faculty (Olympus): That is what we had started with, and then having observed, if I tell you that the observation was a heads, then that changes your belief about, you know, whether coin 1 was chosen or coin 2 was chosen.

942
02:01:50.790 --> 02:01:55.139
Faculty (Olympus): So, yeah, that is what we are thinking about here.

943
02:01:55.720 --> 02:01:56.470
Faculty (Olympus): Okay.

944
02:01:56.840 --> 02:01:57.750
Gaurav Singh .: Thanks, Professor.

945
02:01:58.100 --> 02:01:58.770
Faculty (Olympus): Okay.

946
02:01:59.130 --> 02:02:03.680
Faculty (Olympus): Alright, okay, so we'll end here, and we'll meet next time.

947
02:02:03.830 --> 02:02:04.570
Faculty (Olympus): Bye.

