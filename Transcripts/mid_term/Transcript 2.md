WEBVTT

1
00:04:55.560 --> 00:04:58.430
Faculty (Olympus): Hi Rupal, are you there?

2
00:04:59.960 --> 00:05:01.319
Rupal Makhijani: Yes, yes.

3
00:05:01.700 --> 00:05:05.780
Faculty (Olympus): Okay, just to confirm you're able to hear me fine?

4
00:05:05.780 --> 00:05:07.100
Rupal Makhijani: Yes, everything is okay.

5
00:05:07.650 --> 00:05:08.310
Faculty (Olympus): Okay.

6
00:05:08.910 --> 00:05:09.960
Faculty (Olympus): Ohâ€¦

7
00:07:23.870 --> 00:07:24.840
Rajesh Kumar Singh .: Good evening.

8
00:07:51.540 --> 00:07:55.469
Faculty (Olympus): Rupal, I hope my screen is visible.

9
00:07:55.790 --> 00:07:57.139
Rupal Makhijani: Yes, sir, it is.

10
00:07:57.640 --> 00:07:58.860
Faculty (Olympus): Okay, alright.

11
00:10:19.820 --> 00:10:23.840
Faculty (Olympus): Okay, we'll wait for maybe one more minute, and then we'll start.

12
00:11:11.980 --> 00:11:18.660
Faculty (Olympus): Okay, good evening, everyone. Let's, begin the class.

13
00:11:19.680 --> 00:11:32.339
Faculty (Olympus): So, before, we start, I want to share some information and also set a few ground rules for how we are going to proceed.

14
00:11:32.400 --> 00:11:41.790
Faculty (Olympus): So one thing I want to mention is, I shared, before this class, I shared some, handwritten notes with you.

15
00:11:42.070 --> 00:11:44.590
Faculty (Olympus): And also gave a pointer toâ€¦

16
00:11:44.720 --> 00:11:49.769
Faculty (Olympus): Maybe the chapters from the book, that might be relevant to what we covered today.

17
00:11:49.900 --> 00:12:00.470
Faculty (Olympus): So this is what, in general, I'll follow. Now, in the class, often I'll only cover a subset of what is there in the lecture notes. For example.

18
00:12:00.490 --> 00:12:09.889
Faculty (Olympus): There'll be a little more additional material in the notes, there will be some proofs of, you know, theorems or lemmas.

19
00:12:09.890 --> 00:12:23.920
Faculty (Olympus): That are there in the notes that I won't cover in class, but these are all there in the notes, if you want to look at them. If you have questions about them, then at the end of maybe one of these classes, you can ask me about them, but

20
00:12:23.920 --> 00:12:28.189
Faculty (Olympus): During the class, the idea will be more to give you the tools.

21
00:12:28.490 --> 00:12:34.950
Faculty (Olympus): And maybe explain the intuition behind them, and do some problems about how these tools might be applicable.

22
00:12:35.410 --> 00:12:41.890
Faculty (Olympus): We won't do a lot of proofs. That's theâ€¦ that's at least the agenda. Let's see.

23
00:12:43.430 --> 00:12:55.360
Faculty (Olympus): The second thing I want to say about the lectures is, again, I'm going to follow this pattern of covering some material and then stopping in between to take a few questions.

24
00:12:55.360 --> 00:13:11.069
Faculty (Olympus): Please make sure that the questions that you ask in between are directly relevant to the material that we have covered thus far, okay? Notâ€¦ notâ€¦ yeah, as, as closely related to theâ€¦ just the material that has been covered.

25
00:13:11.090 --> 00:13:30.029
Faculty (Olympus): questions about how this material might be relevant to a data science application, or something more, let's say, broader, or a bird's eye view, I'm happy to take those, but only at the end of the class, okay? So we don't want to break the flow. So, whatever is question is directly relevant to the material that wasâ€¦ that has been covered, let's only

26
00:13:30.030 --> 00:13:32.750
Faculty (Olympus): Take that up in between the sessions.

27
00:13:32.960 --> 00:13:46.509
Faculty (Olympus): Okay, finally, third thing the TAs have asked me to remind you is about your first TA session, starts, on Saturday. There will be two parallel sessions that happen. One will be a little more slow-paced.

28
00:13:46.510 --> 00:14:04.670
Faculty (Olympus): Where, again, questionsâ€¦ in both these TA sessions, essentially problems, if you have doubts, you can resolve those doubts with the TAs, and they will do a lot of problem solving. That's the idea. In the slowâ€¦ there will be two types of sessions going on in parallel. One will be slightly slower, where they'll go over every step.

29
00:14:04.690 --> 00:14:28.269
Faculty (Olympus): So they will maybe cover a fewer number of questions in that session, but they'll be very thorough with how they go over the steps, essentially. And in the faster one, it'll be a little more fast-paced. So maybe people who have seen these things before, might prefer the faster session, people who are not very familiar with it yet might start with the slower sessions, and as you become more familiar, you can always

30
00:14:28.270 --> 00:14:29.190
Faculty (Olympus): switch.

31
00:14:29.190 --> 00:14:36.840
Faculty (Olympus): In any case, both the recordings are going to be available to you at all times, so you can always follow either one, okay?

32
00:14:37.130 --> 00:14:42.979
Faculty (Olympus): Okay, so, yeah, with that, let's start,

33
00:14:43.260 --> 00:14:53.380
Faculty (Olympus): I hope my screen is visible to everyone. So, the plan today is to introduce the notion of

34
00:14:53.670 --> 00:15:02.720
Faculty (Olympus): probability space, And we will introduce what do we mean by probability.

35
00:15:02.880 --> 00:15:19.740
Faculty (Olympus): And, what are some of the properties of probability, etc. That's where we are going to start today. So, a probability space, consists of 3 objects, okay? And I'll describe these three objects, one by one.

36
00:15:19.910 --> 00:15:28.600
Faculty (Olympus): Okay, the first object, this is called omega.

37
00:15:28.800 --> 00:15:34.260
Faculty (Olympus): Okay, this symbol is called omega. This represents a sample space.

38
00:15:35.700 --> 00:15:42.109
Faculty (Olympus): Now, what does thisâ€¦ what do we mean by sample space? A sample space is simply the set

39
00:15:42.320 --> 00:15:47.340
Faculty (Olympus): of all possible Outcomes of your experiment.

40
00:15:49.100 --> 00:15:55.119
Faculty (Olympus): outcomesâ€¦ ofâ€¦ An experiment that you might be doing.

41
00:15:55.350 --> 00:16:00.660
Faculty (Olympus): Okay? For example, If you are tossing a coin.

42
00:16:01.540 --> 00:16:06.520
Faculty (Olympus): Right? And you just get to see which side the coin lands on.

43
00:16:06.780 --> 00:16:14.719
Faculty (Olympus): Then, you'reâ€¦ Omegaâ€¦ consists of two possibilities. It consists of heads.

44
00:16:14.850 --> 00:16:27.880
Faculty (Olympus): and tails, because these are the two possible outcomes of your experiment. You're tossing a coin, you're seeing which of these, sides it lands on, and so you have two possible outcomes, heads or tails.

45
00:16:28.300 --> 00:16:32.960
Faculty (Olympus): Now, let's say you again toss a coin, Right

46
00:16:33.480 --> 00:16:37.539
Faculty (Olympus): But you observe something more, so you observe

47
00:16:38.570 --> 00:16:42.330
Faculty (Olympus): Let's say the speed with which it hits.

48
00:16:42.670 --> 00:16:44.490
Faculty (Olympus): The floor, right?

49
00:16:44.750 --> 00:16:54.640
Faculty (Olympus): So you're not seeing now the side on which it is landing. What you're observing, or what your experiment is about, is what speed does the coin hit the floor with.

50
00:16:54.750 --> 00:16:59.669
Faculty (Olympus): Right? So in this particular case, omega is going to be the set of all

51
00:16:59.830 --> 00:17:07.989
Faculty (Olympus): positive real numbers, right? It's going to hit with some positive speed, so that is going to be our sample space, right?

52
00:17:08.720 --> 00:17:15.910
Faculty (Olympus): Sticking with the same, let's say, theme, let's say you toss a coin.

53
00:17:16.060 --> 00:17:24.619
Faculty (Olympus): But now, I keep tossing the coin, Tillâ€¦ I see my first heads.

54
00:17:25.550 --> 00:17:27.440
Faculty (Olympus): First, heads.

55
00:17:27.710 --> 00:17:32.270
Faculty (Olympus): Okay, this is my experiment. I keep tossing the coin till I see my first heads.

56
00:17:33.040 --> 00:17:42.380
Faculty (Olympus): So, again, all I'm doing, my observation is, how many times did I toss before I saw my first heads? So, in this case, my sample space.

57
00:17:42.380 --> 00:17:54.749
Faculty (Olympus): is going to be of the form, maybe I tossed it once, the first toss itself I got a heads, maybe the first toss I got a tails, then I got a heads, or it could be two times tails, then I got a heads, and so on.

58
00:17:55.180 --> 00:18:10.110
Faculty (Olympus): Okay, so now in this case, it's the set of all positive, integers, right? So depending on what my experiment is, what my observation is, what is it that I'm interested in, my underlying sample space might be different.

59
00:18:10.610 --> 00:18:18.049
Faculty (Olympus): And all theâ€¦ that the sample space consists of is itâ€¦ it is the set of all possible outcomes.

60
00:18:18.170 --> 00:18:31.310
Faculty (Olympus): of my experiment, okay? So it is just a set which has some elements, and it contains the set of all possible outcomes, right? So it couldâ€¦ so you can already see it can be something which is finite.

61
00:18:31.460 --> 00:18:50.659
Faculty (Olympus): Right? You only have two elements there, or it could be something which is truly infinite as well. So it could be the set of integers, or it could even be the set of real numbers, right? So all of that depends on how we define what our experiment is, how we define our sample space, or what are we interested in.

62
00:18:50.660 --> 00:18:52.769
Faculty (Olympus): So that is the set of outcomes.

63
00:18:52.900 --> 00:19:00.499
Faculty (Olympus): So that is the first, kind of element in this probability space. You define what your set of outcomes is.

64
00:19:00.840 --> 00:19:10.829
Faculty (Olympus): So, every experiment, every time you run the experiment, what are the possible outcomes? Now, the second quantity in a probability space is this F,

65
00:19:11.200 --> 00:19:16.020
Faculty (Olympus): Which is called a collection of events.

66
00:19:18.130 --> 00:19:20.100
Faculty (Olympus): Okay? Now, what is an event?

67
00:19:21.690 --> 00:19:26.540
Faculty (Olympus): So, an eventâ€¦ Is just a subset.

68
00:19:27.860 --> 00:19:33.440
Faculty (Olympus): of your sample space. Some subset of your sample space that you are interested in.

69
00:19:33.730 --> 00:19:45.070
Faculty (Olympus): Right? Some subset of the sample space that you might be interested in, and every such event is a subset of omega, right?

70
00:19:45.240 --> 00:20:00.540
Faculty (Olympus): Now, the collection of such events that you are interested in, that is what isâ€¦ this F denotes, okay? So what we are going to do is we are going to try and assign probability values to every element of F, meaning every such event

71
00:20:00.800 --> 00:20:07.140
Faculty (Olympus): we will assign some probability. That is what is going to happen next. So F is just a collection of events. For example.

72
00:20:07.730 --> 00:20:25.910
Faculty (Olympus): Right? Let's look at an example. So, let's say my sample space was this one, okay? Let me point this out. Let's say this was the experiment that I was running. My experiment was, I'll keep tossing the coin till I see my first heads, so my sample space was the collection of positive integers.

73
00:20:25.910 --> 00:20:36.060
Faculty (Olympus): What might be an interesting event in this sample space? One possible interesting event could be, the eventâ€¦

74
00:20:36.500 --> 00:20:45.980
Faculty (Olympus): could beâ€¦ I neededâ€¦ Or I need, greater than 5 tosses.

75
00:20:47.250 --> 00:20:59.500
Faculty (Olympus): Right? I needed greater than 5 tosses to see my first heads. That is my event that I'm interested in. What does that correspond to? So this is an event E, which will correspond to the

76
00:20:59.610 --> 00:21:05.520
Faculty (Olympus): the setâ€¦ 5, 6, 7, and so on, right?

77
00:21:05.900 --> 00:21:12.219
Faculty (Olympus): This set is my event, and it is a subset of my sample space.

78
00:21:12.950 --> 00:21:13.700
Faculty (Olympus): Right?

79
00:21:14.060 --> 00:21:24.860
Faculty (Olympus): Similarly, in the same sample space, another event, if this was, let's say, E1, another event, E2, could be that the number of tosses needed

80
00:21:25.860 --> 00:21:29.600
Faculty (Olympus): is odd. The number of tosses needed is odd.

81
00:21:29.800 --> 00:21:32.440
Faculty (Olympus): Again, this is a particular event.

82
00:21:32.840 --> 00:21:35.619
Faculty (Olympus): And this corresponds to

83
00:21:38.980 --> 00:21:47.859
Faculty (Olympus): Sorry, one second, there seems to be some issue withâ€¦ my pen, just a second.

84
00:22:06.060 --> 00:22:08.930
Faculty (Olympus): Okay, someâ€¦ oh, I got it.

85
00:22:10.600 --> 00:22:18.350
Faculty (Olympus): Yeah, so theâ€¦ sorry, so the number of tosses is odd, is, my second event, and now this corresponds toâ€¦

86
00:22:18.770 --> 00:22:20.259
Faculty (Olympus): E2 beingâ€¦

87
00:22:21.280 --> 00:22:32.869
Faculty (Olympus): What would this correspond to? It would correspond to 1, 3, 5, 7, and so on, right? Again, this E2 is a subset of your sample space.

88
00:22:32.970 --> 00:22:47.519
Faculty (Olympus): So, think of events as being some subset of your underlying sample space, and these are things that you might be interested in. So, for example, you might be interestedâ€¦ think of, for example, right now we are talking about these tosses.

89
00:22:47.520 --> 00:22:56.889
Faculty (Olympus): But maybe these could be experiments that you are running, right? Every time, and you keep running an experiment till you see a success.

90
00:22:56.890 --> 00:23:04.279
Faculty (Olympus): And you're asking, okay, how many times will I have to run this experiment at least 5 times to see my first success?

91
00:23:04.330 --> 00:23:15.750
Faculty (Olympus): Right? This could be maybe a marketing campaign where you're trying to recruit someone, or you're trying to see a sale, right? So how many people will I have to approach before I make my first sale?

92
00:23:15.830 --> 00:23:21.080
Faculty (Olympus): Right? So in that case, your sample space would exactly be something that looks like this.

93
00:23:21.370 --> 00:23:32.729
Faculty (Olympus): Right? And you might be interested in, okay, what is the event that you might be interested in is that you require more than 5 runs of the experiment to see your first success.

94
00:23:32.730 --> 00:23:45.129
Faculty (Olympus): Okay, so this could be an event that you might be interested in. So in any case, events are just subsets of your sample space. They are just a subset, a collection of some of the elements of your sample space.

95
00:23:45.360 --> 00:23:51.869
Faculty (Olympus): And every such subset is an event, and the F that we talk about

96
00:23:52.740 --> 00:24:02.700
Faculty (Olympus): Right? Is the collection of such events. Okay? Collection of events that you might be interested in. So this is the second part of your probability space.

97
00:24:02.760 --> 00:24:13.339
Faculty (Olympus): Okay? Omega was the sample space, F is a set where elements inâ€¦ which is just a collection of subsets. F is a collection of subsets.

98
00:24:13.420 --> 00:24:14.150
Faculty (Olympus): Fine.

99
00:24:14.340 --> 00:24:19.669
Faculty (Olympus): Okay? Now, the final thingâ€¦ So, now we haveâ€¦

100
00:24:20.000 --> 00:24:25.969
Faculty (Olympus): a sample space. We have a collection of subsets. Now we'll come

101
00:24:26.480 --> 00:24:32.470
Faculty (Olympus): to a probability measure on top of this space, okay? Now, what is P?

102
00:24:32.870 --> 00:24:37.660
Faculty (Olympus): This P is what is called a probabilityâ€¦ Measure.

103
00:24:42.240 --> 00:24:47.350
Faculty (Olympus): And what P does is it is just a function, okay? P is just a function.

104
00:24:47.880 --> 00:24:56.130
Faculty (Olympus): Which takes elements fromâ€¦ This F, meaning P just as input, takes an event.

105
00:24:56.290 --> 00:25:01.560
Faculty (Olympus): Any event, and it assigns to it a value between 0 and 1.

106
00:25:01.840 --> 00:25:07.150
Faculty (Olympus): Okay? So, this P, you can think of it as a function which takes in

107
00:25:07.430 --> 00:25:12.129
Faculty (Olympus): any event, E, which belongs to F, and then assigns it a value.

108
00:25:12.310 --> 00:25:17.819
Faculty (Olympus): which is between 0 and 1. Okay? It assigns it a value between 0 and 1.

109
00:25:18.740 --> 00:25:29.540
Faculty (Olympus): Okay? Now, it cannot be any function, right? It cannot be any function. It has to satisfy some properties. So, P is a function which takes

110
00:25:29.920 --> 00:25:39.120
Faculty (Olympus): Events as input, assigns them a value between 0 and 1, but it has to satisfy some properties.

111
00:25:40.700 --> 00:25:42.180
Faculty (Olympus): some properties.

112
00:25:42.310 --> 00:25:49.720
Faculty (Olympus): Okay, what are these properties that it must satisfy? So, these are very simple properties. The first property that it must satisfy

113
00:25:50.040 --> 00:25:51.250
Faculty (Olympus): is thatâ€¦

114
00:25:51.930 --> 00:26:06.500
Faculty (Olympus): one possible event, right, F just contains subsets of the sample space. So, one possible subset of a sample space is the null set, which means you don't choose any element from the sample space. So, if you look at the element.

115
00:26:06.540 --> 00:26:13.090
Faculty (Olympus): Whichâ€¦ whereâ€¦ if you take the null set, which means you don't take anyâ€¦ so this isâ€¦ this is the null set.

116
00:26:13.230 --> 00:26:16.209
Faculty (Olympus): This null set corresponds to an empty subset.

117
00:26:16.370 --> 00:26:20.530
Faculty (Olympus): So, to the empty subset, it must always assign value 0.

118
00:26:21.060 --> 00:26:26.020
Faculty (Olympus): Okay, this function must always assign value 0 to the empty subset.

119
00:26:27.480 --> 00:26:28.740
Faculty (Olympus): The secondâ€¦

120
00:26:29.020 --> 00:26:39.190
Faculty (Olympus): property it must satisfy is that if you take the entire sample space, right, if you take the entire sample space, that is again a subset of omega.

121
00:26:39.560 --> 00:26:42.539
Faculty (Olympus): It must assign to it the value 1.

122
00:26:43.200 --> 00:26:56.489
Faculty (Olympus): Okay? So to events in between, it has to assign some value between 0 and 1. If you choose the null set, which means you are choosing an event which is completely empty, has nothing, no element in it, it must get the value 0.

123
00:26:56.610 --> 00:26:58.709
Faculty (Olympus): If you choose all the elements.

124
00:26:59.060 --> 00:27:02.179
Faculty (Olympus): As your event, then it must get the value 1.

125
00:27:03.310 --> 00:27:12.580
Faculty (Olympus): These are two, and then the third one, the final one, is that if you take two events, A and B, which are disjoint.

126
00:27:12.790 --> 00:27:23.189
Faculty (Olympus): Which means they don't share any element, okay? This can also be written as A intersection B is null.

127
00:27:23.410 --> 00:27:31.110
Faculty (Olympus): Okay, they don't share any element with each other. If you getâ€¦ if you take two such events, Lynn!

128
00:27:31.750 --> 00:27:38.549
Faculty (Olympus): theâ€¦ Probability value that is assigned to the union of these two elements.

129
00:27:38.990 --> 00:27:43.440
Faculty (Olympus): Has to be equal to the sum of the individual values.

130
00:27:44.620 --> 00:27:49.550
Faculty (Olympus): Okay, let me spend a little bit of time, again, reiterating this. Soâ€¦

131
00:27:49.980 --> 00:27:52.700
Faculty (Olympus): Omega was our sample space, it was a set.

132
00:27:53.490 --> 00:28:06.759
Faculty (Olympus): Okay, then we looked at the notion of an event. Any event is just a subset of a samples, of the sample space. So, different events are different subsets of the sample space. F is a collection of all such subsets.

133
00:28:07.340 --> 00:28:13.119
Faculty (Olympus): Right? Now, the probability measure assigns values to every such subset.

134
00:28:13.270 --> 00:28:19.349
Faculty (Olympus): But it has to satisfy some axioms. It has to satisfyâ€¦ it cannot be any function. It has to satisfy some properties.

135
00:28:19.450 --> 00:28:26.389
Faculty (Olympus): it has to satisfy only three properties, okay? One, to the null set, it has to give the value 0.

136
00:28:27.070 --> 00:28:33.040
Faculty (Olympus): to theâ€¦ full universe, which is the sample space. It has to give the value 1.

137
00:28:33.260 --> 00:28:37.780
Faculty (Olympus): And if you take any two, sets from F,

138
00:28:37.960 --> 00:28:43.739
Faculty (Olympus): Which are disjoint, meaning they don't share, they don't share, any common elements.

139
00:28:43.870 --> 00:28:45.760
Faculty (Olympus): Right? Thenâ€¦

140
00:28:46.030 --> 00:28:57.269
Faculty (Olympus): to the union of those two elements. What do I mean by the union? So, if you haven't seen, or if you don't recall what the union is, this means it contains elements

141
00:28:58.640 --> 00:29:03.650
Faculty (Olympus): Whichâ€¦ belongâ€¦ toâ€¦

142
00:29:03.800 --> 00:29:22.150
Faculty (Olympus): either A or B. So if they belong to A, or they belong to B, or they belong to both, all of those elements are part of A union B, okay? So this is saying that the measure that isâ€¦ the probability that is assigned to A union B has to be equal to the sum

143
00:29:22.310 --> 00:29:24.389
Faculty (Olympus): Of their individual values.

144
00:29:25.020 --> 00:29:44.869
Faculty (Olympus): Okay? I saw there was some question about this P with the two legs, P with the single leg, it doesn't matter, okay? That's just a matter of notation, and there's nothingâ€¦ don't read anything into it, so don't worry about that. You can think of it as single leg, double leg, whatever, okay? That's just a matter of notation.

145
00:29:46.520 --> 00:29:52.030
Faculty (Olympus): Okay, so it only has to satisfy these three properties. There is nothing else thatâ€¦

146
00:29:52.130 --> 00:29:56.440
Faculty (Olympus): a probability space has to satisfy. So now let's maybe look

147
00:29:56.750 --> 00:30:14.840
Faculty (Olympus): at an example to see whatâ€¦ a simple example to illustrate what a probability space might look like, okay? Let's do that. So, let's go to the mostâ€¦ the simplest example, okay? So, here, I'm going to take my experiment.

148
00:30:15.140 --> 00:30:19.530
Faculty (Olympus): To be, I toss a coin, Andâ€¦

149
00:30:19.720 --> 00:30:26.609
Faculty (Olympus): I obsâ€¦ I justâ€¦ my experiment is, I observe the side that it lands on.

150
00:30:27.040 --> 00:30:33.149
Faculty (Olympus): Okay? So, what is going to be my sample space? My sample space is going to be either heads.

151
00:30:33.450 --> 00:30:34.650
Faculty (Olympus): Or tails.

152
00:30:35.750 --> 00:30:45.950
Faculty (Olympus): what are the events, the possible events, alright? So, the possible events areâ€¦ the null set, Right?

153
00:30:46.170 --> 00:30:52.670
Faculty (Olympus): It could be the entire sample space, which is heads and tails, and it could be

154
00:30:53.170 --> 00:30:58.490
Faculty (Olympus): the two singletons. Heads, And tails only.

155
00:30:58.730 --> 00:31:03.480
Faculty (Olympus): Right? These are the four possible subsets of omega.

156
00:31:03.590 --> 00:31:08.400
Faculty (Olympus): There are only 4 subsets possible of omega, and these are those 4 sets.

157
00:31:08.610 --> 00:31:11.789
Faculty (Olympus): Okay? Each of them corresponds to a different event.

158
00:31:12.040 --> 00:31:29.739
Faculty (Olympus): Right? Now let's try and construct a probability measure on this, on this space. So here is, the probability measure. I know already from the axioms, I know that the value that has to be assigned to the null set has to be 0.

159
00:31:30.210 --> 00:31:37.830
Faculty (Olympus): The value that has to be assigned to H, T, which is my entire sample space, has to be 1.

160
00:31:38.730 --> 00:31:39.570
Faculty (Olympus): Right?

161
00:31:39.690 --> 00:31:41.190
Faculty (Olympus): What is the value?

162
00:31:41.390 --> 00:31:49.050
Faculty (Olympus): that I can assign to Suppose, suppose I assign the value, P.

163
00:31:49.390 --> 00:31:50.270
Faculty (Olympus): Okay?

164
00:31:50.420 --> 00:31:54.190
Faculty (Olympus): to the Singleton H, to this element.

165
00:31:55.660 --> 00:31:58.120
Faculty (Olympus): To this element, I assign the value.

166
00:31:58.590 --> 00:32:01.820
Faculty (Olympus): P. P is some number between 0 and 1,

167
00:32:02.290 --> 00:32:08.749
Faculty (Olympus): Then, can I say something about what will be the value that will be assigned to the Singleton T?

168
00:32:08.930 --> 00:32:14.929
Faculty (Olympus): Right? I have already assigned a value to phi, which is 0, that is the first axiom of probability.

169
00:32:14.930 --> 00:32:15.600
Saurav Kumar: Goodbye.

170
00:32:15.600 --> 00:32:16.509
Faculty (Olympus): I already know.

171
00:32:16.510 --> 00:32:16.990
Saurav Kumar: That's.

172
00:32:16.990 --> 00:32:26.579
Faculty (Olympus): value 1 has to be assigned to H comma T, right? This is just the entire sample space. This is a set which contains H and T both.

173
00:32:27.790 --> 00:32:35.829
Faculty (Olympus): The third one, suppose I say that that value is some value P, some real number P between 0 and 1.

174
00:32:36.290 --> 00:32:43.000
Faculty (Olympus): What would be the value that this T will take? Is it fixed, or can it be some other value Q?

175
00:32:43.180 --> 00:32:46.809
Faculty (Olympus): Right? Now, let's think about, about that.

176
00:32:47.260 --> 00:32:48.710
Faculty (Olympus): Now, I knowâ€¦

177
00:32:49.310 --> 00:32:56.489
Faculty (Olympus): from the third axiom, right? From the third axiom, I know that if I take two sets which are disjoint.

178
00:32:56.790 --> 00:33:10.109
Faculty (Olympus): then their union has to have a measure which is equal to the sum of the individual values, right? Now, let'sâ€¦ let me apply this axiom, or this requirement, to the following A and B.

179
00:33:10.310 --> 00:33:12.079
Faculty (Olympus): Let's take A.

180
00:33:12.610 --> 00:33:21.309
Faculty (Olympus): to be the singleton H, meaning Singleton, I mean, just a set which has a single element. That's what a singleton is. And let's take B

181
00:33:21.680 --> 00:33:23.610
Faculty (Olympus): to be the Singleton T.

182
00:33:25.020 --> 00:33:28.999
Faculty (Olympus): If you do that, What is A union B?

183
00:33:29.120 --> 00:33:34.069
Faculty (Olympus): A union B is elements which are either in A or in B.

184
00:33:34.300 --> 00:33:39.879
Faculty (Olympus): Right? So it is H and T. This is exactly your overall sample space.

185
00:33:40.950 --> 00:33:42.050
Faculty (Olympus): Right?

186
00:33:42.150 --> 00:33:49.679
Faculty (Olympus): Second thing to note is A and B are disjoint. They don't share Any common elements.

187
00:33:49.890 --> 00:34:00.840
Faculty (Olympus): So if they don't share any common elements, then by the third axiom, I know that P of A union B has to be equal to P of A plus

188
00:34:00.990 --> 00:34:02.039
Faculty (Olympus): P of B.

189
00:34:03.520 --> 00:34:07.750
Faculty (Olympus): Right? This is my third requirement on any probability measure.

190
00:34:08.060 --> 00:34:17.979
Faculty (Olympus): So what will that tell us? That tells us P of A was Pâ€¦ wasâ€¦ was this proâ€¦ this number P, so I know that this is P.

191
00:34:18.350 --> 00:34:25.799
Faculty (Olympus): What can I say about P of A union B? A union B is the entire sample space, so this has to be equal to 1.

192
00:34:26.630 --> 00:34:28.830
Faculty (Olympus): Right? That is my second axiom.

193
00:34:29.170 --> 00:34:48.039
Faculty (Olympus): So, I know that the left-hand side is 1, the first element on the right-hand side is P, and this is the quantity that I wanted to find out. So, the probability that I assign any measure that assigns, has to assign to be the value 1 minus P.

194
00:34:49.350 --> 00:34:50.820
Faculty (Olympus): Okay, so ifâ€¦

195
00:34:51.060 --> 00:35:00.429
Faculty (Olympus): If you assign the value P to this guy, then the measure has to assign the value 1 minus P to T.

196
00:35:01.560 --> 00:35:15.519
Faculty (Olympus): Okay? So, any valid measure on thisâ€¦ for this particular omega, so if your omega is H, T, and your F is the collection of all these subsets.

197
00:35:20.430 --> 00:35:25.660
Faculty (Olympus): Then, any valid probability measure here has to assign the value 0,

198
00:35:26.180 --> 00:35:32.669
Faculty (Olympus): to this guy, has to assign the value 1 to this guy, can assign some real number P,

199
00:35:32.810 --> 00:35:37.919
Faculty (Olympus): to H, but then we'll have to assign 1 minus P to this guy.

200
00:35:39.330 --> 00:35:52.369
Faculty (Olympus): Okay? So you can check that this is what any valid probability measure will say. Okay? So this is what defines a probability space. A probability space consists of a sample space.

201
00:35:52.650 --> 00:36:08.980
Faculty (Olympus): It consists of a collection of events. Each event is just a subset of the sample space. So events are things that you might be interested in, right? For which you want to calculate probability, or to which you want to assign probability. And then, probability

202
00:36:09.950 --> 00:36:16.480
Faculty (Olympus): It's just a function which takes elements from your event set.

203
00:36:16.940 --> 00:36:22.729
Faculty (Olympus): and assign them value between 0 and 1, but they have to satisfy 3 axioms. That's it.

204
00:36:23.460 --> 00:36:24.260
Faculty (Olympus): Okay?

205
00:36:24.460 --> 00:36:39.060
Faculty (Olympus): All the other properties of a probability measure are just derived from these three axioms. They don't require anything else. Only from these three axioms, we will see so many, other properties of a probability measure come up.

206
00:36:39.340 --> 00:36:40.440
Faculty (Olympus): Okay?

207
00:36:40.740 --> 00:36:50.209
Faculty (Olympus): Okay, so now I'm going to take some questions. Again, please try and keep the questions limited to the material that we have just covered.

208
00:36:50.610 --> 00:37:02.180
Faculty (Olympus): I will not be able to take all the questions right now, so I'llâ€¦ I'll only waitâ€¦ try and take as many questions as I can, maybe in the next 5 minutes, and then we'll move on.

209
00:37:02.270 --> 00:37:14.580
Faculty (Olympus): At the end, again, I will wait, and we'll have some time to resolve any other questions that might be there. The second thing, please wait for me to ask you to call your name.

210
00:37:16.140 --> 00:37:25.360
Faculty (Olympus): Yeah, we don't want, otherwise it just becomes very hard to handle everyone, okay? I might be able to cover you now, I might not be able to cover you now, but please, adjust.

211
00:37:25.610 --> 00:37:27.739
Faculty (Olympus): Okay, yeah, Bipin?

212
00:37:30.540 --> 00:37:36.149
Bipin Karyakarte .: Okay, so Professor, if you can just go up a little bit, I have some confusion there.

213
00:37:36.620 --> 00:37:40.740
Bipin Karyakarte .: Yeah, yeah, yeah, that'sâ€¦ no, no. Yeah, yeah, that'sâ€¦ that's all, that's all, that's all.

214
00:37:40.740 --> 00:37:41.470
Faculty (Olympus): Okay?

215
00:37:41.470 --> 00:37:42.030
Bipin Karyakarte .: Yeah.

216
00:37:42.230 --> 00:37:49.310
Bipin Karyakarte .: Okay, so here we are saying our experiment is to toss a coin and observe which side is on the upside, right?

217
00:37:49.310 --> 00:37:49.810
Faculty (Olympus): Yeah.

218
00:37:49.810 --> 00:37:51.820
Bipin Karyakarte .: Head is up, or tail is up.

219
00:37:51.820 --> 00:37:52.530
Faculty (Olympus): Yeah, yeah, yeah.

220
00:37:52.800 --> 00:37:56.499
Bipin Karyakarte .: So, the universe is basically H comma T. That's fine.

221
00:37:57.010 --> 00:38:00.329
Bipin Karyakarte .: ifâ€¦ Set, that is, set of events.

222
00:38:00.330 --> 00:38:00.930
Faculty (Olympus): Hmm.

223
00:38:01.260 --> 00:38:02.380
Bipin Karyakarte .: Null set.

224
00:38:02.630 --> 00:38:11.220
Bipin Karyakarte .: Then the universal set, that is a complete sample space, and then Singleton H&T. Singleton H&T, I could understand.

225
00:38:11.410 --> 00:38:12.070
Faculty (Olympus): Yeah.

226
00:38:12.620 --> 00:38:19.449
Bipin Karyakarte .: How do you convert the null set into reality? Like, I toss a count, it never comes back, or something like that?

227
00:38:19.450 --> 00:38:23.720
Faculty (Olympus): So, yeah, yeah, I mean, these might be,

228
00:38:23.960 --> 00:38:29.900
Faculty (Olympus): So, an eventâ€¦ yeah, you can think of it that way, which is why it gets, like, a probability zero.

229
00:38:29.900 --> 00:38:33.109
Bipin Karyakarte .: That's fine, that's fine. Even I couldâ€¦ I could understand even that part.

230
00:38:33.430 --> 00:38:44.519
Bipin Karyakarte .: Second part, that is the universal, the sample space, age commodity, what does it mean in real terms? You toss a coin and it stands on the side so that both theâ€¦

231
00:38:44.520 --> 00:38:50.350
Faculty (Olympus): No, no, it'sâ€¦ so, by an event, you should think of your observation being part of that set.

232
00:38:50.550 --> 00:38:58.120
Faculty (Olympus): Right? So your observation is going to be either H or T, right? So, it'll always be part of the universe.

233
00:38:58.800 --> 00:39:00.230
Faculty (Olympus): So, think of the eventâ€¦

234
00:39:00.230 --> 00:39:07.370
Bipin Karyakarte .: But again, if that be the case, then H and T Singletons are already there, so why to take that H comedy again?

235
00:39:07.370 --> 00:39:10.179
Faculty (Olympus): No, no, so this is, again,

236
00:39:10.350 --> 00:39:12.619
Faculty (Olympus): This is to make sure that

237
00:39:13.160 --> 00:39:16.340
Faculty (Olympus): To the entire universe, you assign a value 1.

238
00:39:16.470 --> 00:39:27.900
Faculty (Olympus): Right? So, all we are saying, all the reason to include this is to say that to the entire universe, meaning you will get an observation from this universe, I assign the value 1.

239
00:39:28.300 --> 00:39:28.810
Bipin Karyakarte .: So,

240
00:39:28.810 --> 00:39:35.820
Faculty (Olympus): Which means I'm guaranteedâ€¦ I'm guaranteed to get an observation from amongst the universe. That's it.

241
00:39:35.820 --> 00:39:44.930
Bipin Karyakarte .: Okay, so which means that every F will mandatorily consist of one null set and one universal set, and then the other things, right?

242
00:39:44.930 --> 00:39:52.279
Faculty (Olympus): So we are takingâ€¦ think of F to be the collection of all possible subsets of yourâ€¦ of your sample space for now.

243
00:39:52.820 --> 00:40:00.010
Bipin Karyakarte .: Okay, got it, got it. So, basically, we have to always include null set and the universal set by default, and then all the other possibilities.

244
00:40:00.010 --> 00:40:01.299
Faculty (Olympus): All the other possible sites.

245
00:40:01.300 --> 00:40:02.210
Bipin Karyakarte .: Okay, fine, thank you.

246
00:40:02.210 --> 00:40:04.180
Faculty (Olympus): Okay, summer?

247
00:40:06.540 --> 00:40:12.349
Samar .: Hi, Professor. So myâ€¦ one other question is related to that only, that,

248
00:40:12.520 --> 00:40:24.700
Samar .: zero or null, probability. Like, if there is an experiment, there will be an outcome, right? So, what does zero represent?

249
00:40:24.700 --> 00:40:44.599
Faculty (Olympus): So, yeah, the null setâ€¦ I mean, theseâ€¦ the reason for including this, we areâ€¦ we are assigning probability zero to the null set anyways, okay? So there is a mathematical reason for including all sets, but you can thinkâ€¦ in any case, saying that there is no observation is getting the value 0. So that is not going to happen.

250
00:40:44.660 --> 00:40:46.000
Faculty (Olympus): Think of it that way.

251
00:40:46.000 --> 00:40:54.210
Samar .: Yeah, and one question on this F, which isâ€¦ we are calling as a collection of events, right? Yeah, yeah. Soâ€¦

252
00:40:54.370 --> 00:41:05.309
Samar .: Here, we have represented four, but there could be more events as well. For example, if I am observing two heads, one tail, head, tail, head, so those will also become part of this.

253
00:41:05.310 --> 00:41:10.939
Faculty (Olympus): So then, that is a different experiment, right? Right now, my experiment was, I tossed a coin oneâ€¦

254
00:41:10.940 --> 00:41:12.310
Samar .: Huh.

255
00:41:12.310 --> 00:41:26.390
Faculty (Olympus): Now, if your experiment is you're going to toss a coin two times, and you will observe the sequence, then your omega also changes. Your omega is now all possible, kind of, sequences that you can see.

256
00:41:26.890 --> 00:41:37.439
Faculty (Olympus): in two tosses. So you will have HH, HT, TT, HT, or TH, right? So your sample space itself changes then.

257
00:41:37.440 --> 00:41:42.469
Samar .: Okay, so with each experiment, we will have a separate omega?

258
00:41:42.470 --> 00:42:01.969
Faculty (Olympus): Once you have an omega, then for all practical purposes, at least through this course, you can think of F as being the collection of all possible subsets of your sample space. Whatever your sample space will be. If you toss a coin twice, then your sample space itself changes, right? Because the outcomes are nowâ€¦

259
00:42:02.300 --> 00:42:11.020
Faculty (Olympus): Now, no longer just HNT. They are HH, TT, TH, HT. There are 4 possibilities now in the sample space itself.

260
00:42:11.550 --> 00:42:20.119
Faculty (Olympus): So, in your F, when you look at all possible subsets of that sample space, there will now be 16 values, not just 4 values.

261
00:42:20.860 --> 00:42:21.699
Faculty (Olympus): So it'll grow.

262
00:42:21.700 --> 00:42:23.430
Samar .: Thank you. Yeah, thanks, Sachs.

263
00:42:23.830 --> 00:42:29.280
Faculty (Olympus): Okay, Rahul? Rahul Joshi?

264
00:42:29.280 --> 00:42:37.230
Rahul Joshi .: Yeah. Just one question, Professor. Why the third property, which is A union B equal to PA plus PB, is required in this case? Because

265
00:42:37.360 --> 00:42:43.279
Rahul Joshi .: Just having the first two conditions that null will be 0 and a full set will be 1 is sufficient.

266
00:42:43.280 --> 00:42:48.240
Faculty (Olympus): Yeah, yeah, so, I mean, in this particular case,

267
00:42:48.420 --> 00:43:05.140
Faculty (Olympus): Well, okay, if I, for example, take phi to have the value 0, HT to have the value 1, that comes from the first two properties, then H and T, the singletons, could have the values P and maybe some other Q.

268
00:43:06.090 --> 00:43:08.610
Faculty (Olympus): Right? If I don't have the third property.

269
00:43:08.830 --> 00:43:12.399
Faculty (Olympus): Then there is no restriction on them taking any values.

270
00:43:14.170 --> 00:43:14.900
Rahul Joshi .: Okay.

271
00:43:14.900 --> 00:43:15.560
Faculty (Olympus): Right?

272
00:43:15.780 --> 00:43:17.500
Faculty (Olympus): But we are trying toâ€¦

273
00:43:17.830 --> 00:43:28.190
Faculty (Olympus): essentially, these axioms are trying to get to something which might be natural, right? Youâ€¦ if you'reâ€¦ if your probâ€¦ if there are only two outcomes, and the probability of heads is P,

274
00:43:28.370 --> 00:43:31.400
Faculty (Olympus): then the probability of seeing a tail should be 1 minus P.

275
00:43:31.550 --> 00:43:42.199
Faculty (Olympus): Right? But if I don't have that third axiom inbuilt, then there'll be no restriction. You can choose any values between 0 and 1 for each of these subsets, there will be no restriction at all.

276
00:43:43.390 --> 00:43:49.500
Faculty (Olympus): So, you will not get something which is natural, and it will not satisfy the properties that we will soon see.

277
00:43:50.650 --> 00:43:56.630
Rahul Joshi .: Okay, and then, just to confirm, this is applicable for every experiment, right?

278
00:43:56.630 --> 00:44:16.529
Faculty (Olympus): Yeah, yeah, every possible experiment, the only thing we require are these three axioms. So we will soon see how only these three axioms will result in so many properties of probability that you might have seen before and are natural, but all of them just come from these three axioms, nothing more. We are not putting any other condition on our function.

279
00:44:18.260 --> 00:44:18.900
Rahul Joshi .: Okay.

280
00:44:18.900 --> 00:44:19.570
Faculty (Olympus): Okay?

281
00:44:19.720 --> 00:44:20.320
Rahul Joshi .: Thank you, sir.

282
00:44:20.320 --> 00:44:22.110
Faculty (Olympus): Okay, Saurabh?

283
00:44:25.060 --> 00:44:25.550
Gaurav Singh .: Professional.

284
00:44:25.550 --> 00:44:27.349
Saurabh Puranik .: We're doing them? Ohâ€¦

285
00:44:27.350 --> 00:44:27.700
Faculty (Olympus): caught up.

286
00:44:28.110 --> 00:44:29.450
Faculty (Olympus): Puranik,

287
00:44:29.850 --> 00:44:35.190
Saurabh Puranik .: Okay, okay. So, good evening, Professor. My only question is that,

288
00:44:35.580 --> 00:44:42.239
Saurabh Puranik .: If, sample space is H comma T, and the set of events are phi, H comma T, S, and T,

289
00:44:42.710 --> 00:44:48.160
Saurabh Puranik .: This state should be mutually exclusive and collectively exhaustive.

290
00:44:48.910 --> 00:44:49.779
Faculty (Olympus): Can I say?

291
00:44:49.950 --> 00:44:55.429
Faculty (Olympus): No, no, they areâ€¦ we are taking all the possible subsets of the sample space.

292
00:44:57.460 --> 00:45:00.970
Faculty (Olympus): All possible subsets of the sample space. That's what we are taking.

293
00:45:02.350 --> 00:45:10.689
Saurabh Puranik .: Soâ€¦ is it not the thing that, if we are giving each comma T as a 1, because it is H union T, right?

294
00:45:10.840 --> 00:45:17.080
Saurabh Puranik .: Yeah. Then H, the probability of H should be 0.5, and probability of T should be 0.5.

295
00:45:17.080 --> 00:45:29.759
Faculty (Olympus): No, no, that is only if you have aâ€¦ I mean, that is a particular probability measure, right? That is, if you have a fair coin, which is equally likely to show you heads and tails. But maybe your coin is more biased towards heads.

296
00:45:30.390 --> 00:45:30.970
Saurabh Puranik .: Hmmâ€¦

297
00:45:30.970 --> 00:45:32.019
Faculty (Olympus): So, need not be.

298
00:45:32.230 --> 00:45:35.019
Faculty (Olympus): Yeah, so this is covering everything. It's not onlyâ€¦

299
00:45:35.740 --> 00:45:40.370
Saurabh Puranik .: To make it generalized, you had given the speed. Yeah, yeah. Yeah, yeah. Thank you.

300
00:45:40.630 --> 00:45:49.010
Faculty (Olympus): Okay. Okay, last question, maybe, and, Niraj? Niraj Kumar Mishra?

301
00:45:50.910 --> 00:45:54.990
Niraj Kumar Mishra .: Yes, Professor, so my question is here, forâ€¦

302
00:45:55.160 --> 00:46:09.530
Niraj Kumar Mishra .: F, right? We have, four, subset here. Null subset, H and T, then H and T, right? So, null subset and H and T is a fixed value, 0 and 1, right?

303
00:46:10.200 --> 00:46:28.170
Faculty (Olympus): the probability measure, any probability measure, has to assign them 0 and 1 value, because null set always has to get 0. In this particular case, H comma T, this whole set, is the universe itself, so it has to get 1. So these two values get fixed by the first two axioms.

304
00:46:28.460 --> 00:46:38.490
Niraj Kumar Mishra .: Okay, the last two subset calculation, like A union B, I didn't get it quite, so if you can help to solve that problem.

305
00:46:38.490 --> 00:46:38.810
Faculty (Olympus): Soâ€¦

306
00:46:38.810 --> 00:46:41.210
Niraj Kumar Mishra .: Maybe it will be easier for me to understand.

307
00:46:41.210 --> 00:46:51.400
Faculty (Olympus): Let's maybe go through, furthermore, we will do some such calculations. If it's still not clear at the end, we'llâ€¦ you can always ask me, I'll go through that again.

308
00:46:51.400 --> 00:46:52.150
Niraj Kumar Mishra .: Okay, okay.

309
00:46:52.150 --> 00:47:09.679
Faculty (Olympus): Okay? All right, okay, so let's, move ahead. Like I said, yeah, at the end, I'm happy to take any further, questions. Okay, so we have, what we have looked at so far is we have defined

310
00:47:10.030 --> 00:47:25.849
Faculty (Olympus): the notion of a sample space, we have defined the notion of a collection of events, and we have defined the notion of a probability measure, which we have said is just any function which satisfies these three properties, okay? Only three properties.

311
00:47:25.900 --> 00:47:30.099
Faculty (Olympus): Now, let's see what are some of the implications of these three properties.

312
00:47:30.720 --> 00:47:34.210
Faculty (Olympus): So, the first implication is thatâ€¦

313
00:47:35.200 --> 00:47:49.229
Faculty (Olympus): If you have an element, a subset, or an event A, which belongs to F, okay, this notation is something I will use often. It isâ€¦ belongs to.

314
00:47:49.480 --> 00:47:56.989
Faculty (Olympus): Okay? So if A is an element of F, or A belongs to an F, in this particular case, all it means is A is an event.

315
00:47:57.180 --> 00:47:58.710
Faculty (Olympus): If A is an event.

316
00:47:58.820 --> 00:48:05.260
Faculty (Olympus): Right? Then you also have A complement. What is A complement? A complement isâ€¦ soâ€¦

317
00:48:06.120 --> 00:48:13.349
Faculty (Olympus): This is, let's say, your sample space. Suppose this is your subset.

318
00:48:13.480 --> 00:48:21.289
Faculty (Olympus): corresponding to A. Then everything in your sample space which is outside of A is A complement.

319
00:48:21.490 --> 00:48:28.040
Faculty (Olympus): This is A complement, right? So clearly, A and A complement, they are disjoint events, right?

320
00:48:28.170 --> 00:48:35.740
Faculty (Olympus): So, A complement is also a part of yourâ€¦ is also an event. It's also part of your, collection of events.

321
00:48:35.940 --> 00:48:39.650
Faculty (Olympus): Then, the claim is, thatâ€¦

322
00:48:39.810 --> 00:48:50.640
Faculty (Olympus): the probability of A complement assigned to A complement by any valid probability measure has to be equal to 1 minus the probability assigned to A.

323
00:48:50.760 --> 00:48:55.590
Faculty (Olympus): This condition has to always be satisfied by any valid probability measure.

324
00:48:55.880 --> 00:48:56.680
Faculty (Olympus): Okay?

325
00:48:57.410 --> 00:49:09.130
Faculty (Olympus): Notice that this is not something that was part of one of the axioms, okay? The claim is that this is just going to come directly from the obserâ€¦ from essentially what we have assumed to be true.

326
00:49:09.250 --> 00:49:12.110
Faculty (Olympus): Right? Okay? Now, howâ€¦

327
00:49:12.170 --> 00:49:29.659
Faculty (Olympus): I'll very quickly go through the proof. If you don't follow it, just don't worry about it. The reason this might be true, if I rewrite this, this is equivalently saying that probability of A complement plus the probability of A has to be equal to 1.

328
00:49:29.660 --> 00:49:34.460
Faculty (Olympus): Okay? Now, some of you might already see why this is true, so if Iâ€¦

329
00:49:34.550 --> 00:49:48.760
Faculty (Olympus): If I look at this side, this is the sum of the probabilities assigned to A and A complement. What did we say about A and A complement? A and A complement are disjoint.

330
00:49:52.630 --> 00:49:55.620
Faculty (Olympus): And what is the union of A and A complement?

331
00:49:55.870 --> 00:50:14.220
Faculty (Olympus): The union of A and A complement is exactly the sample space. So every element is either in A, or is itâ€¦ is in A complement. So, I know that the probability of A union A complement is just the probability of omega, which is equal to 1.

332
00:50:14.570 --> 00:50:15.560
Faculty (Olympus): Right?

333
00:50:15.910 --> 00:50:19.160
Faculty (Olympus): And because A and A complement areâ€¦

334
00:50:19.330 --> 00:50:27.059
Faculty (Olympus): disjoint sets, this is going to be equal to P of A plusâ€¦ P of A complement.

335
00:50:27.450 --> 00:50:31.699
Faculty (Olympus): Okay, so that's why, for any valid probability measure.

336
00:50:31.980 --> 00:50:35.510
Faculty (Olympus): You are going to have the sum of these probabilities.

337
00:50:35.740 --> 00:50:46.389
Faculty (Olympus): P of A plus P of A complement will always be equal to 1, or in other words, the probability of A complement will always be 1 minus the probability of A.

338
00:50:46.720 --> 00:50:54.069
Faculty (Olympus): Okay? So, the probability of the complement of an event is just 1 minus the probability of the event itself.

339
00:50:54.380 --> 00:51:03.049
Faculty (Olympus): Okay? That's, that's kind of the idea. So this is a property that just directly comes up because of the axioms that we have used.

340
00:51:03.410 --> 00:51:07.599
Faculty (Olympus): Okay, let's, look at one more property.

341
00:51:11.820 --> 00:51:17.620
Faculty (Olympus): So, the second property, is that, let's say, again, you look at two events, A and B,

342
00:51:17.880 --> 00:51:28.370
Faculty (Olympus): These are both subsets of omega, and suppose A is a subset of B, okay? This notation means is a subset.

343
00:51:30.740 --> 00:51:33.260
Faculty (Olympus): Graphically, what this means is the following.

344
00:51:33.890 --> 00:51:38.060
Faculty (Olympus): If you haveâ€¦ the set B,

345
00:51:38.210 --> 00:51:43.080
Faculty (Olympus): This is the subset, let's say, B, then A is contained inside B.

346
00:51:44.040 --> 00:51:52.650
Faculty (Olympus): Okay? So every element that is in A is also a part of B, but not vice versa, okay? So A is a subset of B,

347
00:51:52.890 --> 00:52:01.810
Faculty (Olympus): Then, this says that the probability assigned to A always has to be less than equal to the probability assigned to B.

348
00:52:02.380 --> 00:52:03.120
Faculty (Olympus): Okay.

349
00:52:03.700 --> 00:52:13.729
Faculty (Olympus): Always. Any valid probability measure has to satisfy this property, that the value that you assign to A has to be less than equal to the value that was assigned to B.

350
00:52:15.520 --> 00:52:19.540
Faculty (Olympus): Okay? So this also has to always hold true.

351
00:52:20.880 --> 00:52:21.640
Faculty (Olympus): Okay.

352
00:52:22.050 --> 00:52:26.419
Faculty (Olympus): Fine, let me see.

353
00:52:26.880 --> 00:52:30.859
Faculty (Olympus): Should weâ€¦ Yeah, maybe, maybe,

354
00:52:31.720 --> 00:52:38.739
Faculty (Olympus): Okay, let me do one more property, and thenâ€¦ then we can, talk about maybe some examples.

355
00:52:39.880 --> 00:52:40.600
Faculty (Olympus): Okay.

356
00:52:42.190 --> 00:52:45.139
Faculty (Olympus): So the third property is the following.

357
00:52:45.670 --> 00:52:46.819
Faculty (Olympus): It saysâ€¦

358
00:52:47.250 --> 00:52:57.500
Faculty (Olympus): that if you look at the probability of A union B, okay, now A and B are not necessarily disjoint, okay? They could haveâ€¦ they could be any two sets. For example.

359
00:52:57.780 --> 00:53:04.480
Faculty (Olympus): These could be of this form. You could haveâ€¦ A here, You could have B here.

360
00:53:04.770 --> 00:53:10.529
Faculty (Olympus): Right? So, A union B corresponds to all elements across the

361
00:53:10.820 --> 00:53:14.350
Faculty (Olympus): A or B, either in A or in B, right?

362
00:53:15.040 --> 00:53:24.859
Faculty (Olympus): And if you ask what is A intersection B, that is exactly all the elements which are both in A as well as in B. So, this part.

363
00:53:24.970 --> 00:53:39.410
Faculty (Olympus): In the intersection. That is A intersection B. Okay? Now, what is theâ€¦ what does the claim say? The claim says that this value is always going to be equal to P of A plus P of B

364
00:53:39.660 --> 00:53:43.640
Faculty (Olympus): minusâ€¦ P of A intersection B.

365
00:53:44.120 --> 00:53:46.539
Faculty (Olympus): Okay, this has to always hold true.

366
00:53:47.510 --> 00:53:49.420
Faculty (Olympus): Okay? Now, recall.

367
00:53:49.700 --> 00:54:01.420
Faculty (Olympus): Our third lemma said that if A and B are two disjoint events, then A union B, thisâ€¦ the probability of A union B has to be the sum of P of A and P .

368
00:54:01.740 --> 00:54:04.020
Faculty (Olympus): Right? It had known minus term.

369
00:54:04.380 --> 00:54:23.399
Faculty (Olympus): But that isâ€¦ that is okay, because it was always talking about disjoint events. So if disjoint events, then this is going to be null, and the probability assigned to null is 0, so that negative term is going to be 0. Okay? But this third property is for any two general events, and it says that the probability assigned to A union B

370
00:54:23.690 --> 00:54:28.759
Faculty (Olympus): is PA plus PB minus PA intersection B. It is always this quantity.

371
00:54:29.370 --> 00:54:30.180
Faculty (Olympus): Okay?

372
00:54:30.850 --> 00:54:45.309
Faculty (Olympus): So again, thisâ€¦ the proof of this directly follows from these, these lemmas, that proof is there in the notes if you're interested. But let'sâ€¦ let's just look at an example which illustrates some of these ideas, okay?

373
00:54:45.450 --> 00:54:55.670
Faculty (Olympus): Soâ€¦ let's look at this example. Suppose, I'm an e-commerce company, okay? And, I have a,

374
00:54:55.780 --> 00:55:12.610
Faculty (Olympus): a website as well as an app, and users connect with me on either the website or through the app. So either a desktop website or through an app. So let's say I'm looking at myâ€¦ a particular user, okay? I'm looking at a particular user.

375
00:55:12.700 --> 00:55:16.740
Faculty (Olympus): This is my experiment. I look at a user, and Iâ€¦

376
00:55:16.870 --> 00:55:26.970
Faculty (Olympus): Track whether the user is joining from a mobile, Or is joining, from a desktop.

377
00:55:28.720 --> 00:55:33.740
Faculty (Olympus): Soâ€¦ That is one part, and I track whether they make a purchase

378
00:55:33.980 --> 00:55:40.400
Faculty (Olympus): or they make no purchase, okay? So, mobileâ€¦ Mobile, no purchase.

379
00:55:42.410 --> 00:55:50.030
Faculty (Olympus): And join from desktop, Make a purchase, or they makeâ€¦ No purchase.

380
00:55:55.270 --> 00:55:58.580
Faculty (Olympus): Okay? These are the four possible outcomes.

381
00:55:58.770 --> 00:56:11.789
Faculty (Olympus): of my experiment. I look at a user, these are the four things that are possible with this user. So, I will just maybe use some shorthand. It'll be mobile purchase, mobile no purchase.

382
00:56:11.930 --> 00:56:17.010
Faculty (Olympus): Desktop purchase, desktop no purchase. Okay, this is my sample space.

383
00:56:17.270 --> 00:56:19.600
Faculty (Olympus): Now, suppose,

384
00:56:19.810 --> 00:56:27.519
Faculty (Olympus): I have a probability measure, which assigns the values to these singletons, are the following values, okay?

385
00:56:27.640 --> 00:56:31.570
Faculty (Olympus): These are, let's say .18.

386
00:56:33.470 --> 00:56:42.319
Faculty (Olympus): 0.42â€¦ Let's say 0.12â€¦ And point to it.

387
00:56:42.660 --> 00:56:43.430
Faculty (Olympus): Okay?

388
00:56:43.850 --> 00:56:48.620
Faculty (Olympus): These are the four values to these singletons that my probability measure assigns.

389
00:56:49.340 --> 00:56:50.050
Faculty (Olympus): Okay?

390
00:56:50.540 --> 00:57:01.349
Faculty (Olympus): And what happens to any subset? To any subset, let's say, for example, If the subset wasâ€¦ MP, MN.

391
00:57:01.530 --> 00:57:10.440
Faculty (Olympus): Right? What is this event? This event is the probability that user joinsâ€¦ from mobile.

392
00:57:13.830 --> 00:57:19.170
Faculty (Olympus): Okay? To this event, I will assign the value, which is a sum.

393
00:57:19.340 --> 00:57:34.800
Faculty (Olympus): Of these two individual values, soâ€¦ MPâ€¦ plusâ€¦ MNâ€¦ Which is going to beâ€¦ 0.18â€¦ plus 0.42â€¦

394
00:57:35.820 --> 00:57:49.730
Faculty (Olympus): Which is .6. Okay, that is how I'm defining my probability measure. Okay, first thing to check is, can this be a valid probability measure? To check that, you should see whether

395
00:57:50.080 --> 00:58:02.110
Faculty (Olympus): when you add all these singleton values, you should get one, right? Because the probability of MPâ€¦ MNâ€¦

396
00:58:02.350 --> 00:58:07.619
Faculty (Olympus): DPDN, this is the entire sample space, this should always be one.

397
00:58:07.620 --> 00:58:22.679
Faculty (Olympus): So that means, if I'm following this rule, that for any subset of the sample space, I will just add the individual Singleton values, I should get one when I add all of these. So you can check that this, if you sum all these up.

398
00:58:23.290 --> 00:58:26.819
Faculty (Olympus): You do indeed get 1.

399
00:58:27.790 --> 00:58:30.810
Faculty (Olympus): So, to the entire universe, you assign the value 1.

400
00:58:31.220 --> 00:58:36.580
Faculty (Olympus): Fine. Okay, let's continue with this. So, suppose nowâ€¦

401
00:58:37.470 --> 00:58:48.190
Faculty (Olympus): I ask, okay, what is the probability, thatâ€¦ The user makes a purchase.

402
00:58:48.370 --> 00:58:49.890
Faculty (Olympus): Makes a purchase.

403
00:58:51.700 --> 00:58:56.809
Faculty (Olympus): Right? What is this value? So this value corresponds to the event.

404
00:58:57.420 --> 00:59:00.530
Faculty (Olympus): User joins from mobile, makes a purchase.

405
00:59:00.790 --> 00:59:08.840
Faculty (Olympus): User joins from desktop, makes a purchase, right? From our way the probability measure is defined.

406
00:59:09.030 --> 00:59:15.249
Faculty (Olympus): We are taking this to be equal to the value assigned to the two singletons.

407
00:59:19.100 --> 00:59:22.889
Faculty (Olympus): What was the value assigned to MP? It was 0.18.

408
00:59:23.010 --> 00:59:28.970
Faculty (Olympus): and 0.12 to DP, right? So this value is 0.18,

409
00:59:29.260 --> 00:59:34.020
Faculty (Olympus): This value is point, what was it? 0.12.

410
00:59:34.650 --> 00:59:37.310
Faculty (Olympus): So the sum is 0.3.

411
00:59:37.640 --> 00:59:42.980
Faculty (Olympus): So the probability that the user makes a purchase is going to be 0.3, right?

412
00:59:43.800 --> 00:59:48.960
Faculty (Olympus): So, this is how the probability measure is defined.

413
00:59:49.110 --> 00:59:54.140
Faculty (Olympus): Now, if you ask me what is the probability that

414
00:59:54.360 --> 01:00:09.070
Faculty (Olympus): So, let's call these events something. Let's say event A wasâ€¦ User joinsâ€¦ from mobile, Event B wasâ€¦

415
01:00:09.400 --> 01:00:20.000
Faculty (Olympus): User makesâ€¦ Mixâ€¦ a purchase, Then we found that probability of A

416
01:00:20.250 --> 01:00:25.089
Faculty (Olympus): Was, in this particular example, it was 0.6.

417
01:00:26.540 --> 01:00:31.110
Faculty (Olympus): And probability of B wasâ€¦ 0.3.

418
01:00:31.690 --> 01:00:32.570
Faculty (Olympus): Right?

419
01:00:32.750 --> 01:00:39.969
Faculty (Olympus): Now, suppose I ask you what is the probability of A intersection B.

420
01:00:40.790 --> 01:00:53.310
Faculty (Olympus): So what does that correspond to? It corresponds to probability that user joins from mobile, And makes a purchase.

421
01:00:54.950 --> 01:00:56.520
Faculty (Olympus): makes a purchase.

422
01:00:58.560 --> 01:00:59.350
Faculty (Olympus): Right?

423
01:00:59.560 --> 01:01:07.490
Faculty (Olympus): Soâ€¦ What is the element that corresponds to user joining from mobile and making a purchase, right?

424
01:01:07.960 --> 01:01:14.370
Faculty (Olympus): From the sample space, if you look at this sample space, what are the elements that correspond to this?

425
01:01:14.630 --> 01:01:22.399
Faculty (Olympus): The element that corresponds to user joining from mobile and making a purchase is only this one singleton element, right? MP.

426
01:01:22.580 --> 01:01:29.189
Faculty (Olympus): And the value for that MP is 0.18. So, probability of A intersection B is going to be

427
01:01:31.320 --> 01:01:34.329
Faculty (Olympus): the Singleton MP, which is 0.18.

428
01:01:34.520 --> 01:01:35.300
Faculty (Olympus): Right?

429
01:01:35.720 --> 01:01:36.500
Faculty (Olympus): Okay?

430
01:01:36.710 --> 01:01:37.790
Faculty (Olympus): Nowâ€¦

431
01:01:37.910 --> 01:01:44.480
Faculty (Olympus): if you think aboutâ€¦ so youâ€¦ first thing to notice, for example, is that we know that A intersection B

432
01:01:44.680 --> 01:02:00.810
Faculty (Olympus): is a subset of A, and A intersection B is also a subset of B, right? So you can see that the value that is assigned to A intersection B, 0.18, is smaller than the value assigned to

433
01:02:01.070 --> 01:02:05.029
Faculty (Olympus): A, and it is also smaller than the value assigned to B.

434
01:02:05.180 --> 01:02:15.799
Faculty (Olympus): Right? So this, again, matches the fact that if A intersection B is a subset of A, then the value that is assigned to A intersection B should always be less than P .

435
01:02:15.800 --> 01:02:27.009
Faculty (Olympus): Similarly, if A intersection B is a subset of B, its value should be less than equal to B, and so on. So this example is, in fact, following those properties as well.

436
01:02:27.610 --> 01:02:29.490
Faculty (Olympus): Okay? Soâ€¦

437
01:02:29.710 --> 01:02:37.310
Faculty (Olympus): You canâ€¦ you can do all of these kind of calculations, using just the basic probability values, right?

438
01:02:37.710 --> 01:02:50.879
Faculty (Olympus): So this is, one, example. Maybe I'll take a couple ofâ€¦ just a couple of two quick questions, just to see if, things are clear, and thenâ€¦ then I'll, move forward.

439
01:02:51.030 --> 01:03:00.960
Faculty (Olympus): Tushar? We'll do one more example, so if this wasn't quite clear to you, just maybe wait for the next example and see if that is clearer. Tushar?

440
01:03:01.220 --> 01:03:02.569
Tushar Sachdev .: Yes, sir, am I audible?

441
01:03:02.570 --> 01:03:03.120
Faculty (Olympus): Yeah.

442
01:03:03.770 --> 01:03:22.080
Tushar Sachdev .: Sir, I have a question regarding the null set. So, in discrete sample space, event cannot occur, right? Like, say, if you are rolling a die, and we think that, okay, 7 will come, but a die has only 6 faces, so 7 cannot occur. So, it is a null set over there.

443
01:03:22.170 --> 01:03:37.989
Tushar Sachdev .: But, what if we have, instead of a discrete sample space, what if we have a continuous sample space, then event occurring, can the impossibleâ€¦ is it impossible that the event will occur, or does it occur in the, but as measure zero?

444
01:03:39.280 --> 01:03:44.910
Faculty (Olympus): Yeah, yeah, yeah, I get it, but I think this isâ€¦ maybe, yeah, let's take this at the very end.

445
01:03:45.140 --> 01:03:46.330
Tushar Sachdev .: Okay, sir. Okay, sir.

446
01:03:47.200 --> 01:03:50.750
Faculty (Olympus): Okay, Vamsi Krishna?

447
01:03:51.840 --> 01:04:05.390
Vamsi Krishna Mutnuri .: Sir, good evening, sir. Can you explain this, PE intersection B in this scenario where A is the user joining from mobile and making a purchase? Can you explain the functions one? So, you know, Iâ€¦

448
01:04:05.600 --> 01:04:11.300
Faculty (Olympus): So, A was the event that user joins from mobile.

449
01:04:11.710 --> 01:04:20.100
Faculty (Olympus): Right? So if you think of A as an event, so it has to be a subset of the sample space, right? So this event A corresponds to user

450
01:04:20.290 --> 01:04:22.859
Faculty (Olympus): Joining from mobile, making a purchase?

451
01:04:22.990 --> 01:04:29.780
Faculty (Olympus): User joining from mobile, not making a purchase, right? Because A event is only about user joining from mobile.

452
01:04:30.340 --> 01:04:34.830
Faculty (Olympus): Similarly, B event, Was user making a purchase?

453
01:04:35.820 --> 01:04:44.479
Faculty (Olympus): Right? So this corresponds to user joining from mobile making a purchase, user joining from desktop making a purchase.

454
01:04:44.520 --> 01:04:59.170
Faculty (Olympus): Now, if you look at A intersection B, which is user joining from mobile and making a purchase, you look at these two sets, and you look at its intersection. There is only one element which belongs to both of these sets, that is MP.

455
01:04:59.260 --> 01:05:02.920
Faculty (Olympus): So, that is what corresponds to my intersection.

456
01:05:03.470 --> 01:05:17.610
Faculty (Olympus): So that's why the probability of A intersection B is just the probability of this singleton MP. If the intersection had more, more elements, then those will also be included in the intersection, but in this particular case, the intersection is just a singleton.

457
01:05:18.960 --> 01:05:21.000
Faculty (Olympus): Understood, thank you. Yeah.

458
01:05:21.700 --> 01:05:31.409
Faculty (Olympus): Okay, alright, let's, let's move to one more example, okay, which might make, things, clearer.

459
01:05:31.840 --> 01:05:37.869
Bipin Karyakarte .: Professor, I don't have a question, but can you go up for a minute? I just want a specific clarity. Go up, go up.

460
01:05:39.120 --> 01:05:41.280
Bipin Karyakarte .: Go up, keep going.

461
01:05:41.770 --> 01:05:44.459
Bipin Karyakarte .: Aha, ha. So this one, the third one.

462
01:05:44.800 --> 01:05:45.400
Faculty (Olympus): Yeah.

463
01:05:45.620 --> 01:05:54.719
Bipin Karyakarte .: Yeah, probability of A union B is equal to probability of A plus probability of B minus probability of A intersection B. This part.

464
01:05:54.900 --> 01:05:59.160
Bipin Karyakarte .: I didn't exactly getâ€¦ so the next example that you take, try to give aâ€¦

465
01:05:59.160 --> 01:05:59.590
Faculty (Olympus): Yeah, yeah.

466
01:05:59.590 --> 01:06:00.899
Bipin Karyakarte .: Better explanation for this.

467
01:06:00.900 --> 01:06:01.949
Faculty (Olympus): Yeah, yeah, sure, sure.

468
01:06:05.080 --> 01:06:13.919
Faculty (Olympus): Okay? Let's take another example. Let's, consider the following case, okay? Let's say you have two balls.

469
01:06:14.520 --> 01:06:19.960
Faculty (Olympus): Okay? And these balls are of two different colors. Let's say we have a blue ball.

470
01:06:20.380 --> 01:06:22.550
Faculty (Olympus): And we have a green ball.

471
01:06:22.840 --> 01:06:29.060
Faculty (Olympus): Okay? And let's say I have two different baskets, or 2 bins.

472
01:06:29.410 --> 01:06:31.749
Faculty (Olympus): Okay, let's say this is bin 1.

473
01:06:34.100 --> 01:06:35.559
Faculty (Olympus): This is VIN 2.

474
01:06:38.110 --> 01:06:43.240
Faculty (Olympus): Okay? Nowâ€¦ My experiment is the following.

475
01:06:43.440 --> 01:06:46.310
Faculty (Olympus): I will take the first ball.

476
01:06:46.660 --> 01:06:54.399
Faculty (Olympus): Okay, maybe I'll take ballâ€¦ the blue ball, I will drop it inâ€¦ One of these two bins.

477
01:06:55.180 --> 01:07:08.860
Faculty (Olympus): equally likely, okay? So I will choose either bin 1 or bin 2, each with probability 1 half, and I'll drop it in either this bin or in that bin. One of the two bins, right?

478
01:07:08.930 --> 01:07:20.410
Faculty (Olympus): So maybe, for example, I toss a fair coin, it came up heads, and I decided to go with bin 1. So in that case, this ball is going to land up here.

479
01:07:20.470 --> 01:07:37.880
Faculty (Olympus): Right? I will do the same thing again. I will now independently go to the second ball, the green ball. I will repeat this process, right? I will choose one of the two bins at random, again, uniformly, equally likely, and I will select

480
01:07:38.600 --> 01:07:43.140
Faculty (Olympus): it to be dropped either in this bin or in this bin, right?

481
01:07:43.570 --> 01:07:48.830
Faculty (Olympus): So, it could happen that the second ball also lands up

482
01:07:49.060 --> 01:08:06.790
Faculty (Olympus): in this first bin, that is a possibility. Or it could be that one ball lands up, the blue ball comes up in bin 1, the green ball goes to bin 2, or it could be that the blue ball goes to bin 2, green ball goes to bin 1, or both balls land up in bin 2. All these four

483
01:08:07.070 --> 01:08:12.599
Faculty (Olympus): Possibilities are allâ€¦ are possible outcomes of my experiment.

484
01:08:13.050 --> 01:08:13.870
Faculty (Olympus): Okay?

485
01:08:14.300 --> 01:08:16.279
Faculty (Olympus): Right? So I have 2 balls.

486
01:08:16.750 --> 01:08:18.640
Faculty (Olympus): Different colored balls.

487
01:08:18.850 --> 01:08:36.769
Faculty (Olympus): For each ball, I choose one of the two bins, and I drop the ball in that bin. Then I go to the second ball, I do the same thing. I look at the two bins, and I drop the ball in one of the two bins, okay? Now, what is the event that I'm interested in? The event that I'm interested in isâ€¦

488
01:08:37.050 --> 01:08:44.100
Faculty (Olympus): there exists an empty bin.

489
01:08:45.180 --> 01:08:45.979
Faculty (Olympus): Okay?

490
01:08:46.479 --> 01:08:47.879
Faculty (Olympus): So, there is a bin.

491
01:08:48.439 --> 01:08:51.909
Faculty (Olympus): Which isâ€¦ which could either be VIN 1 or bin 2.

492
01:08:52.210 --> 01:08:58.789
Faculty (Olympus): But there exists one VIN, Which is empty, meaning no ball actually landed up in that bin.

493
01:08:59.540 --> 01:09:06.950
Faculty (Olympus): Okay? That is the event that I'm interested in, and I want to find the probability of this event happening.

494
01:09:07.470 --> 01:09:08.279
Faculty (Olympus): Okay?

495
01:09:08.840 --> 01:09:17.229
Faculty (Olympus): Now, before going through how to compute this probability, I want to give a sense of, you knowâ€¦

496
01:09:17.790 --> 01:09:32.539
Faculty (Olympus): This might seem like a toy problem. It's called the balls and bins problem. It's one of the most widely studied probability questions. It's very, very useful, to illustrate ideas, but it is also a problem which finds a lot of utility in practice.

497
01:09:32.680 --> 01:09:37.600
Faculty (Olympus): So, think of the balls as being jobs that are coming in a data center.

498
01:09:37.870 --> 01:09:53.419
Faculty (Olympus): Okay, and think of the bins as being servers in your data center, right? Now, often, you have toâ€¦ so these jobs are coming in, these might be compute jobs, or these might be requests for websites, and anything of that kind.

499
01:09:53.529 --> 01:09:56.860
Faculty (Olympus): And each of these jobs has to be assigned to some server.

500
01:09:57.080 --> 01:09:57.960
Faculty (Olympus): Okay?

501
01:09:58.210 --> 01:10:04.699
Faculty (Olympus): So, the simplest policy is you let the job come in, and you assign it randomly to one of the servers.

502
01:10:04.760 --> 01:10:23.690
Faculty (Olympus): Right? That is, like, the simplest policy, and it is, in fact, a policy which is practically very relevant, because it is very easy to implement. You don't have to keep track of how many jobs are at one server, and which server has what load, and so on. You're doing a completely stateless scheduling policy.

503
01:10:23.960 --> 01:10:36.610
Faculty (Olympus): And, what you are asking here is, okay, there are jobs coming in, I assign them randomly, each job I assign randomly to one of the servers, what is the probability that I end up with a server which is idle?

504
01:10:36.920 --> 01:10:43.490
Faculty (Olympus): Okay? What is the probability that I am actually wasting a resource by having an idle server which has no job to do?

505
01:10:43.720 --> 01:10:50.929
Faculty (Olympus): So, it is a load balancing question, okay? Very, very relevant, very important when you're doing data center networking.

506
01:10:51.200 --> 01:11:03.359
Faculty (Olympus): Okay? Okay, so anyways, but even beyond that, it's a very, important class of, probability problems, very useful to illustrate ideas, and also very fundamental.

507
01:11:03.550 --> 01:11:10.400
Faculty (Olympus): Okay, so coming back to the problem, we have two balls, blue ball, green ball. Blue ball, Iâ€¦

508
01:11:10.500 --> 01:11:23.180
Faculty (Olympus): look at it, put it in one of the bins at random. Second ball, I look at it, put it at one of the bins at random, and I'm asking what is the probability that there is one empty bin?

509
01:11:23.680 --> 01:11:24.600
Faculty (Olympus): Good.

510
01:11:24.790 --> 01:11:38.050
Faculty (Olympus): So, firstly, you should think of, okay, what are the possibilities for the number of empty bins, right? There could be zero empty bins, right? Bothâ€¦ how will that happen? That'll happen if one ball lands up

511
01:11:38.160 --> 01:11:41.399
Faculty (Olympus): In bin 1, the second ball lands up in bin 2.

512
01:11:41.540 --> 01:11:45.059
Faculty (Olympus): If that happens, then you will have zero empty bins.

513
01:11:45.410 --> 01:11:55.769
Faculty (Olympus): You can have one empty bin, maybe both the balls land up in bin 1, or both the balls land up in bin 2. Then you will have one empty bin. Can you have two empty bins?

514
01:11:56.180 --> 01:12:09.310
Faculty (Olympus): you cannot have two empty bins. I mean, the balls have to land up somewhere, so both bins cannot be empty in this case, right? So the possibility is either 0 empty bins, or 1 empty bin. So let's try and figure out theâ€¦

515
01:12:10.150 --> 01:12:12.729
Faculty (Olympus): probability of this event E.

516
01:12:13.530 --> 01:12:22.469
Faculty (Olympus): Okay? So, I can writeâ€¦ this event as a union of two events, E1, union E2.

517
01:12:23.040 --> 01:12:30.330
Faculty (Olympus): Okay? What is even? Even isâ€¦ The event that

518
01:12:34.290 --> 01:12:37.390
Faculty (Olympus): Bin 1â€¦ is empty.

519
01:12:39.220 --> 01:12:48.660
Faculty (Olympus): E2â€¦ Is the eventâ€¦ thatâ€¦ been 2â€¦ is empty.

520
01:12:50.320 --> 01:12:52.240
Faculty (Olympus): What am I interested in?

521
01:12:52.800 --> 01:12:59.960
Faculty (Olympus): I am interested in E1 union E2, meaning either bin 1 or bin 2 is

522
01:13:00.140 --> 01:13:04.160
Faculty (Olympus): is empty. That is what I'm interested in, right? Nowâ€¦

523
01:13:04.320 --> 01:13:10.969
Faculty (Olympus): we saw one of these properties, right? We saw that if you want to compute the probability of E1 union E2,

524
01:13:11.400 --> 01:13:15.650
Faculty (Olympus): It'll always be equal to the probability of E1,

525
01:13:16.170 --> 01:13:19.560
Faculty (Olympus): plus the probability of E2 minus

526
01:13:19.920 --> 01:13:26.269
Faculty (Olympus): the probability of E1 intersection E2. Thisâ€¦ this identity always has to hold true.

527
01:13:26.570 --> 01:13:34.100
Faculty (Olympus): I have to find this left-hand side. Let's try to compute that by going through the terms of the right-hand side.

528
01:13:34.390 --> 01:13:38.290
Faculty (Olympus): Okay, what is the probability that VIN 1 is empty?

529
01:13:38.810 --> 01:13:39.610
Faculty (Olympus): Right?

530
01:13:40.060 --> 01:13:46.229
Faculty (Olympus): The probability of bin 1 being empty is that both the balls chose VIN 2.

531
01:13:46.800 --> 01:13:48.979
Faculty (Olympus): Right? What is the probability of that?

532
01:13:49.520 --> 01:13:58.040
Faculty (Olympus): The firstâ€¦ the probability of that is, the first ball chose Bintu, and the second ball also chose Bintu.

533
01:13:58.700 --> 01:13:59.440
Faculty (Olympus): Right?

534
01:13:59.970 --> 01:14:03.929
Faculty (Olympus): This is only possible if both the balls chose bin 2.

535
01:14:04.400 --> 01:14:07.029
Faculty (Olympus): Right? So this is going to be 1x4.

536
01:14:08.540 --> 01:14:12.490
Faculty (Olympus): Okay, what is the probability that bin 2 is empty?

537
01:14:12.660 --> 01:14:18.510
Faculty (Olympus): Again, the probability that bin 2 is empty is both the balls choose bin 1.

538
01:14:18.890 --> 01:14:26.829
Faculty (Olympus): Right? So it isâ€¦ First ball chooses bin 1, and the second ball also chooses bin 1.

539
01:14:27.540 --> 01:14:29.700
Faculty (Olympus): Right? So again, 1x4.

540
01:14:30.340 --> 01:14:32.879
Faculty (Olympus): What is theâ€¦ this intersection?

541
01:14:33.150 --> 01:14:36.119
Faculty (Olympus): What is the probability that bin 1 is empty?

542
01:14:36.230 --> 01:14:38.310
Faculty (Olympus): And bin 2 is empty.

543
01:14:39.000 --> 01:14:48.730
Faculty (Olympus): Like we saw before, this is zero probability, because you cannot have both bin 1 being empty and bin 2 being empty, right? That cannot happen.

544
01:14:48.850 --> 01:14:51.180
Faculty (Olympus): So, this is going to be 0.

545
01:14:51.760 --> 01:14:54.319
Faculty (Olympus): Right? So, in this particular case.

546
01:14:54.430 --> 01:15:02.909
Faculty (Olympus): The probability of either bin 1 being empty or bin 2 being empty is going to be 1x4 plus 1 by 4.

547
01:15:03.120 --> 01:15:05.420
Faculty (Olympus): Which isâ€¦ One half.

548
01:15:05.710 --> 01:15:16.159
Faculty (Olympus): Okay, so when you have two bins, two balls, and you randomly assign each ball to one bin at random, then the probability that there exists

549
01:15:16.450 --> 01:15:23.789
Faculty (Olympus): An empty bin is 1 half. That's what is happening in the case of 2 balls, 2 bins.

550
01:15:24.450 --> 01:15:31.640
Faculty (Olympus): Okay? Let's try andâ€¦ so this was easy, right? Let's try and extend this to 3 balls and 3 bins.

551
01:15:31.640 --> 01:15:38.100
Rahul Joshi .: Sorry, sir, just one quick question. In this case, 1 by 2Y multiplied by 1 by 2Y, not addition?

552
01:15:38.100 --> 01:15:43.290
Faculty (Olympus): So because we are thinking aboutâ€¦ so, again, this isâ€¦

553
01:15:44.030 --> 01:15:52.249
Faculty (Olympus): about two independent decisions being made by the two balls, right? It cannot be 1 half plus one half, that will be one.

554
01:15:52.430 --> 01:16:04.799
Faculty (Olympus): Here, you are making the choice of ball 1 landing up in one bin, the second ball landing up in the other bin. So, if you want to think about it, you can think about it as the choices that,

555
01:16:04.890 --> 01:16:14.849
Faculty (Olympus): the blue ball and the green ball make. The choices that are possible, let's say, for the blue ball, could be

556
01:16:15.320 --> 01:16:18.649
Faculty (Olympus): bin 1, and the green ball also being bin 1.

557
01:16:18.930 --> 01:16:30.840
Faculty (Olympus): Maybe bin 1 for the blue ball, bin 2 for the green ball, then bin 2 for the blue ball, bin 1 for the green ball, and the final one, which was 2,2.

558
01:16:30.970 --> 01:16:36.029
Faculty (Olympus): Right? So in this particular experiment, this isâ€¦ these are the four possibilities.

559
01:16:36.330 --> 01:16:49.500
Faculty (Olympus): Right? And we are thinking of these four possibilities as essentially being equally likely, because we are doing a completely random experiment, right? Everyone is making independent choices, so each of these

560
01:16:50.310 --> 01:16:55.540
Faculty (Olympus): Possible configurations, you can think of them as happening with probability 1 fourth.

561
01:16:56.910 --> 01:16:57.710
Faculty (Olympus): Okay?

562
01:16:57.820 --> 01:17:01.730
Faculty (Olympus): That is, like, the easy answer,

563
01:17:01.920 --> 01:17:09.060
Faculty (Olympus): Because these are independent events, or independent decisions, that is why the probability is getting multiplied with each other.

564
01:17:09.060 --> 01:17:27.779
Faculty (Olympus): We will come to the notion of independence, in maybe the next class. There, it might become a little clearer why we are multiplying these two probabilities, okay? But for now, you can think of it this way. These are just two independent choices that are being made, so the probability is the product of those. Both of those choices have to hold true.

565
01:17:27.830 --> 01:17:31.830
Faculty (Olympus): It cannot be just one of those choices. Both of those choices have to hold true.

566
01:17:32.350 --> 01:17:33.140
Faculty (Olympus): Okay?

567
01:17:33.960 --> 01:17:38.050
Faculty (Olympus): Okay, let's, let's move forward. So let's nowâ€¦

568
01:17:38.830 --> 01:17:48.079
Faculty (Olympus): make this a little more complicated. So now I have 3 balls, 3 bins, okay? So I have, let's say, a black ball.

569
01:17:48.210 --> 01:17:53.419
Faculty (Olympus): I have a blue ball, And I have a green ball.

570
01:17:53.990 --> 01:17:54.840
Faculty (Olympus): Okay?

571
01:17:54.980 --> 01:18:05.460
Faculty (Olympus): Now, again, let's say I have to make, this, I have now 3 bins, again.

572
01:18:05.640 --> 01:18:06.470
Faculty (Olympus): Okay?

573
01:18:09.880 --> 01:18:20.400
Faculty (Olympus): I have 3 bins, and now I repeat the same experiment, right? I take, for the first ball, the black ball, I pick one of the 3 bins at random, drop the ball there.

574
01:18:20.530 --> 01:18:25.390
Faculty (Olympus): Then for the blue ball, I pick one of the three balls at random, drop it there.

575
01:18:25.500 --> 01:18:27.820
Faculty (Olympus): And for the green ball, again, makeâ€¦

576
01:18:28.000 --> 01:18:30.400
Faculty (Olympus): Choose one of the three balls at random.

577
01:18:30.710 --> 01:18:31.840
Faculty (Olympus): Drop it there.

578
01:18:32.080 --> 01:18:42.549
Faculty (Olympus): Okay? And again, let's say the event that I'm interested in isâ€¦ there exists An empty bin.

579
01:18:46.370 --> 01:18:47.220
Faculty (Olympus): Okay?

580
01:18:48.330 --> 01:19:00.110
Faculty (Olympus): Now, I suppose, again, I want to represent that as a union, so I will write it as I'll consider E1, E2, E3.

581
01:19:00.310 --> 01:19:01.790
Faculty (Olympus): E1 is the event.

582
01:19:01.970 --> 01:19:04.220
Faculty (Olympus): Bin 1 is empty.

583
01:19:06.810 --> 01:19:08.390
Faculty (Olympus): E2 is the event.

584
01:19:08.580 --> 01:19:09.719
Faculty (Olympus): VIN 2.

585
01:19:10.200 --> 01:19:11.380
Faculty (Olympus): is empty.

586
01:19:13.090 --> 01:19:16.780
Faculty (Olympus): And E3 is the event VIN 3.

587
01:19:17.110 --> 01:19:18.450
Faculty (Olympus): is empty.

588
01:19:19.390 --> 01:19:20.130
Faculty (Olympus): Okay?

589
01:19:21.130 --> 01:19:31.119
Faculty (Olympus): Can I express E, which is the event that there exists an empty bin? Can I express this event in terms of E1, E2, E3?

590
01:19:32.480 --> 01:19:36.439
Faculty (Olympus): Can anyone, one person, maybe, answer?

591
01:19:37.210 --> 01:19:43.190
Faculty (Olympus): Can I express the event that there exists an empty bin in terms of E1, E2, E3?

592
01:19:43.190 --> 01:19:48.260
Saurav Kumar: some of all of their probability and minusâ€¦ So, I'm just talking aboutâ€¦

593
01:19:48.260 --> 01:19:52.830
Faculty (Olympus): Okay, not talking about probability, I'm just talking about the event. So this is justâ€¦

594
01:19:52.830 --> 01:19:54.590
Bipin Karyakarte .: USA union, right?

595
01:19:54.590 --> 01:19:56.489
Soumen Deb .: Unit of all three, yeah, unit of all three.

596
01:19:56.490 --> 01:20:07.839
Faculty (Olympus): E1, union E2, union E3. Why is this the right choice? Because you will have an empty bin if either E1 was true, or E2 was true, or E3 was 2.

597
01:20:08.140 --> 01:20:08.950
Faculty (Olympus): Right?

598
01:20:09.290 --> 01:20:13.230
Faculty (Olympus): Even if any one of these three events is true.

599
01:20:13.350 --> 01:20:25.769
Faculty (Olympus): then you will definitely have an empty bill, okay? So now, myâ€¦ if I want to compute the probability of E, then I amâ€¦ now have to compute the union

600
01:20:26.470 --> 01:20:29.919
Faculty (Olympus): The probability associated with a union of 3.

601
01:20:30.440 --> 01:20:32.550
Faculty (Olympus): Events, not just two events.

602
01:20:32.830 --> 01:20:35.899
Faculty (Olympus): Now I have to compute the union of 3 events.

603
01:20:37.100 --> 01:20:49.880
Faculty (Olympus): Okay? So I'm moving beyond. For two events, I knew how to handle things, right? Now I'm going a little bit beyond. I'm goingâ€¦ now I need something to handle the union of three events.

604
01:20:50.330 --> 01:20:59.599
Faculty (Olympus): Okay? Soâ€¦ In fact, there is a way to handle that. This is called the inclusion-exclusion principle.

605
01:21:06.420 --> 01:21:13.499
Faculty (Olympus): Okay, so let me maybe first state this just for 3 events. So if you have any 3 events.

606
01:21:13.930 --> 01:21:19.099
Faculty (Olympus): And you want to ask, what is the probability associated with the union of three events?

607
01:21:19.530 --> 01:21:21.900
Faculty (Olympus): You can always write that asâ€¦

608
01:21:22.840 --> 01:21:26.220
Faculty (Olympus): The sum of the individual probabilities.

609
01:21:28.710 --> 01:21:34.550
Faculty (Olympus): Okay? You first add up the individual probabilities, Then you subtract.

610
01:21:35.390 --> 01:21:38.619
Faculty (Olympus): Each of the pairwise intersections.

611
01:21:38.920 --> 01:21:48.170
Faculty (Olympus): So, A1 Union Aâ€¦ A1 intersection A2, A2 intersection A3, and A1 intersection A3.

612
01:21:48.310 --> 01:21:55.630
Faculty (Olympus): You subtract these pairwise intersections, and then finally, you add the intersection of all the three.

613
01:21:59.580 --> 01:22:16.769
Faculty (Olympus): Okay? This is the general inclusion-exclusion principle formula. If you have 3 events, and you're taking the union of those 3 events, and you want to understand what is the probability of that union. You can express that as the sum of the individual probabilities.

614
01:22:16.910 --> 01:22:20.230
Faculty (Olympus): Then subtract out the pairwise intersections.

615
01:22:20.420 --> 01:22:23.290
Faculty (Olympus): And then finally, the intersection of all three.

616
01:22:23.550 --> 01:22:31.010
Faculty (Olympus): Okay? Let's try and do that to our setup, right? We wanted to find the probability

617
01:22:31.150 --> 01:22:34.249
Faculty (Olympus): of E1, union E2, union E3.

618
01:22:34.490 --> 01:22:36.939
Faculty (Olympus): Right? How will I do that?

619
01:22:37.080 --> 01:22:45.629
Faculty (Olympus): So, to do that, I have to first find this probability of E1. What is the probability that VIN 1

620
01:22:45.800 --> 01:22:47.090
Faculty (Olympus): is empty.

621
01:22:48.230 --> 01:22:48.689
Saurav Kumar: One word.

622
01:22:48.690 --> 01:22:52.929
Faculty (Olympus): The probability that bin 1 is empty. Now, remember, you have 3 bins.

623
01:22:53.500 --> 01:22:58.540
Faculty (Olympus): So the probability that bin 1 is empty is that the first ball

624
01:22:58.700 --> 01:23:02.140
Faculty (Olympus): went to the second bin, or the third bin.

625
01:23:02.550 --> 01:23:06.580
Faculty (Olympus): The second ball also went to the second bin, or the third bin.

626
01:23:06.720 --> 01:23:09.809
Faculty (Olympus): And the third ball also went to the second bin or the third bin.

627
01:23:10.270 --> 01:23:12.850
Faculty (Olympus): So, if you think about the first ball.

628
01:23:13.820 --> 01:23:19.739
Faculty (Olympus): it has two choices. It can go to eitherâ€¦ either BIN 2 or bin 3, both of those two choices are okay.

629
01:23:20.160 --> 01:23:25.280
Faculty (Olympus): Right? Because that ball is going to land up in somewhere other than bin 1.

630
01:23:25.680 --> 01:23:31.760
Faculty (Olympus): Right? Soâ€¦ 2x3â€¦ with 2x3 probability, it skips bin 1.

631
01:23:32.700 --> 01:23:33.600
Faculty (Olympus): Okay?

632
01:23:33.950 --> 01:23:39.729
Faculty (Olympus): Now, the second ball also has to skip bin 1, the third ball also has to skip bin 1.

633
01:23:39.730 --> 01:23:48.429
Kanupriya Saxena .: Can we also take it as 1 minus 1 by 3? Like, 1 by 3 is the chance of one ball landing into bin 1, soâ€¦

634
01:23:48.430 --> 01:23:58.439
Faculty (Olympus): Not quite, because then you are looking at a particular ball, right? There are three possible balls, so either of those three balls, if it lands up in the first bin, then there is a problem.

635
01:23:58.440 --> 01:24:13.609
Kanupriya Saxena .: I said it wrong. Possibility of a ball landing in bin 1 is 1x3, because there are three different balls. So, possibility of a ball landing in bin 1 is 1x3. So, possibility of a ball not landing in bin 1 is 1 minus 1 by 3, which gives 2x3.

636
01:24:13.610 --> 01:24:23.499
Faculty (Olympus): Yeah, yeah. So if you're asking, yeah, how this 2x3 comes in? Exactly, yeah. The probâ€¦ the probability of the ball landing in bin 1 is 1 by 3.

637
01:24:23.730 --> 01:24:30.010
Faculty (Olympus): And the probability of the ball not landing in bin 1 is 1 minus 1 by 3, which is 2x3, correct?

638
01:24:30.420 --> 01:24:43.419
Faculty (Olympus): Okay? So, this has to happen for the first ball, this has to then happen for the second ball, and this also has to happen for the third ball. So that's why the probability that bin 1 is empty is going to be the product of these three.

639
01:24:43.690 --> 01:24:56.739
Faculty (Olympus): Similarly, if you see what is the probability that bin 2 is empty, it's going to be exactly the same thing, right? There is no difference between either bin 1, or bin 2, or bin 3. They're all symmetric.

640
01:24:56.740 --> 01:25:04.520
Faculty (Olympus): So, probability of bin 2 being empty is going to be the same as the probability of bin 3 being empty.

641
01:25:04.580 --> 01:25:14.099
Faculty (Olympus): And the same as probability of bin 1 being empty. So individually, all of these are going to be equal to 8 by 27.

642
01:25:14.710 --> 01:25:19.859
Faculty (Olympus): Okay? So that takes care of these first summations.

643
01:25:20.460 --> 01:25:23.180
Faculty (Olympus): Right? Now we have to worry aboutâ€¦

644
01:25:23.470 --> 01:25:27.220
Faculty (Olympus): the pairwise intersections. So what is the probability

645
01:25:27.680 --> 01:25:30.770
Faculty (Olympus): of, let's say, E1 intersection E2.

646
01:25:31.190 --> 01:25:36.300
Faculty (Olympus): This is the probability that VIN 1 and VIN2.

647
01:25:36.430 --> 01:25:37.820
Faculty (Olympus): Both are empty.

648
01:25:39.650 --> 01:25:41.140
Faculty (Olympus): How can that happen?

649
01:25:41.400 --> 01:25:46.200
Faculty (Olympus): That can happen only if all the 3 balls land up in bin 3.

650
01:25:46.930 --> 01:25:50.049
Faculty (Olympus): So, ball 1 has to land up in bin 3.

651
01:25:50.240 --> 01:25:55.259
Faculty (Olympus): Ball 2 has to land up in bin 3. Ball 3 also has to land up in bin 3.

652
01:25:55.600 --> 01:25:56.950
Faculty (Olympus): So this becomesâ€¦

653
01:25:57.050 --> 01:26:07.200
Faculty (Olympus): 1 by 27. Again, it doesn't matter whether you take intersection of E1 and E2, or you take intersection of E2 and E3,

654
01:26:07.730 --> 01:26:13.330
Faculty (Olympus): The three terms are all going to be equal, they are going to be equal to 1 by 27.

655
01:26:13.680 --> 01:26:19.530
Faculty (Olympus): Okay? So that takes care of theseâ€¦ these pairwise intersections.

656
01:26:19.850 --> 01:26:26.990
Faculty (Olympus): The final one, Probability of E1 intersection E2, intersection E3.

657
01:26:27.430 --> 01:26:35.140
Faculty (Olympus): This is the probability that VIN 1 and been toâ€¦ and VIN 3.

658
01:26:35.280 --> 01:26:36.360
Faculty (Olympus): are empty.

659
01:26:37.190 --> 01:26:43.350
Faculty (Olympus): What is the probability of that happening? Zero. It cannot be anything else, so it has to be zero.

660
01:26:43.690 --> 01:26:49.619
Faculty (Olympus): Okay, so in this particular case, we can now do our calculation.

661
01:26:50.070 --> 01:26:55.850
Faculty (Olympus): The probability that there exists An empty bin.

662
01:26:57.910 --> 01:27:03.530
Faculty (Olympus): is the probability of E1, union E2, union E3,

663
01:27:03.740 --> 01:27:12.760
Faculty (Olympus): Which we can write as 8x27 plus 8 by 27 plus 8 by 27 minusâ€¦

664
01:27:13.340 --> 01:27:21.129
Faculty (Olympus): 1x27, plus 1x27, plus 1 by 27, plus zero.

665
01:27:22.420 --> 01:27:29.239
Faculty (Olympus): Okay, so this will, give what? This is, yeah, this is, like,

666
01:27:29.610 --> 01:27:33.210
Faculty (Olympus): So, 24 by 27 minusâ€¦

667
01:27:33.560 --> 01:27:46.060
Faculty (Olympus): 3x27, so that's, like, 21 by 27. So this is the probability that if you have 3 balls, 3 bins, you're randomly assigning these balls to bins, the probability that there will be an empty bin.

668
01:27:46.180 --> 01:27:46.950
Faculty (Olympus): Okay?

669
01:27:47.090 --> 01:28:02.579
Faculty (Olympus): So, the idea of illustrating all of this is that you can express, you can often express events as unions of smaller events, and there are formulas to compute the probability of a union in terms of smaller probabilities, probabilities of

670
01:28:02.580 --> 01:28:14.669
Faculty (Olympus): kind of, single probabilities of individual events, maybe their pairwise intersection, and so on, okay? So I gave you just the inclusion-exclusion formula for

671
01:28:14.750 --> 01:28:24.369
Faculty (Olympus): One, for, sorry, for, three events, but it canâ€¦ it is something that can be generalized to n events, that is there in theâ€¦

672
01:28:24.610 --> 01:28:43.569
Faculty (Olympus): in the text also, but I will maybe just reiterate at the beginning of the next class, I'll just give you the formula again, okay? But there is a general formula for computing the union ofâ€¦ the probability of the union of N events, okay? It's a little complicated, but there is a formula for that.

673
01:28:43.940 --> 01:28:47.960
Faculty (Olympus): Okay? So you can look up the inclusion-exclusion principle if you want.

674
01:28:48.500 --> 01:28:51.110
Faculty (Olympus): Okay, so we will,

675
01:28:51.910 --> 01:29:01.279
Faculty (Olympus): In terms of the material that I want to cover, we are done for today. If there are questions, then you can stay back, and I'll take those questions now.

676
01:29:01.910 --> 01:29:11.770
Faculty (Olympus): Again, let's maybe start with questions which are directly relevant to the last part, and then I can further take questions which are maybe more general.

677
01:29:11.990 --> 01:29:15.090
Faculty (Olympus): Okay, gaurav Singh?

678
01:29:16.270 --> 01:29:27.599
Gaurav Singh .: Yeah, Professor, like, in this particular problem, ball and win, the identity of the ball is not important, right? So,

679
01:29:28.330 --> 01:29:35.809
Gaurav Singh .: Basically, we are not creating the events with the, you know, which specific ball goes to which bin.

680
01:29:35.810 --> 01:29:51.799
Faculty (Olympus): Yeah, so, I mean, it might be someâ€¦ weâ€¦ the event that we were considering was not particularly interested in the identity of the ball, but you might consider events which are related toâ€¦ you might ask what is the probability that the blue ball does not go to bin 3?

681
01:29:51.970 --> 01:29:56.940
Faculty (Olympus): That's a valid event. You might be interested in that event, and then you can compute that value also.

682
01:29:57.360 --> 01:30:06.799
Gaurav Singh .: Okay. And second thing is that in both the, problem statement, we have considered the number of balls and the bins

683
01:30:07.320 --> 01:30:08.820
Gaurav Singh .: exactly same.

684
01:30:08.820 --> 01:30:16.629
Faculty (Olympus): Yeah, yeah. Not necessary. Yeah, that was again just for an example. You can generalize all of this to M balls, N bins.

685
01:30:17.230 --> 01:30:28.129
Faculty (Olympus): Very similar calculations, just that things will be a little more interesting. So, for example, if you had 2 balls and 3 bins, right.

686
01:30:28.350 --> 01:30:35.500
Faculty (Olympus): Then, the probability that there exists an empty bin He's oneâ€¦

687
01:30:35.780 --> 01:30:36.660
Gaurav Singh .: more, okay?

688
01:30:36.660 --> 01:30:39.519
Faculty (Olympus): No, it's 1, right? I mean, with 2 balls, you can never cover 3 bins.

689
01:30:39.520 --> 01:30:40.380
Gaurav Singh .: Yes.

690
01:30:40.380 --> 01:30:48.539
Faculty (Olympus): So, yeah, so it only makes sense if the number of balls is at least the number of bins, and so on. But yeah, you can do all kinds of generalizations.

691
01:30:48.800 --> 01:30:49.919
Gaurav Singh .: Got it. Thank you.

692
01:30:50.020 --> 01:30:51.699
Faculty (Olympus): Okay, Pradeep Kumar?

693
01:30:57.200 --> 01:31:03.920
Pradeep Kumar .: Yeah, Professor. So, I mean, the first question which I have, that I have from

694
01:31:04.620 --> 01:31:13.139
Pradeep Kumar .: probability, probability of, even intersection of E2, how we calculated that, that it would be 0.

695
01:31:14.330 --> 01:31:15.210
Faculty (Olympus): In, in the caseâ€¦

696
01:31:15.210 --> 01:31:16.380
Pradeep Kumar .: So, two ballsâ€¦

697
01:31:16.380 --> 01:31:17.190
Faculty (Olympus): two bins.

698
01:31:17.550 --> 01:31:19.800
Pradeep Kumar .: Yeah, that's right. Yeah, two gold, two wheels.

699
01:31:20.530 --> 01:31:21.350
Faculty (Olympus): So,

700
01:31:21.350 --> 01:31:22.330
Pradeep Kumar .: Oh, bye.

701
01:31:22.330 --> 01:31:28.120
Faculty (Olympus): even intersection E2â€¦ means that bin 1 is empty, and.

702
01:31:28.120 --> 01:31:28.570
Pradeep Kumar .: Agreed.

703
01:31:28.570 --> 01:31:29.380
Faculty (Olympus): Rin 2 is empty.

704
01:31:29.380 --> 01:31:30.240
Pradeep Kumar .: Aditya.

705
01:31:30.580 --> 01:31:31.779
Faculty (Olympus): Both the bins are empty.

706
01:31:31.780 --> 01:31:32.300
Pradeep Kumar .: Siddharth.

707
01:31:32.300 --> 01:31:34.900
Faculty (Olympus): Right? If E1 intersection E2 meansâ€¦

708
01:31:35.400 --> 01:31:39.559
Faculty (Olympus): Evenâ€¦ bin 1 is also empty, and bin 2 is also empty.

709
01:31:40.020 --> 01:31:41.639
Faculty (Olympus): But that cannot happen, becauseâ€¦

710
01:31:41.640 --> 01:31:42.250
Pradeep Kumar .: Sandeep.

711
01:31:42.250 --> 01:31:45.339
Faculty (Olympus): Youâ€¦ every ball has to go in at least one of the two bins.

712
01:31:46.320 --> 01:31:48.610
Faculty (Olympus): Right? So both the bins cannot be empty.

713
01:31:49.290 --> 01:31:55.329
Faculty (Olympus): So, this will correspond to the null set. Even intersection E2 will correspond to the null set.

714
01:31:57.850 --> 01:32:06.729
Pradeep Kumar .: Yeah, yeah, makes sense. One last question, how we, calculated, let's say, probability of A1, which is,

715
01:32:07.020 --> 01:32:12.480
Pradeep Kumar .: 2x3 into 2x3 into 2x3. For the question number, 4.

716
01:32:12.480 --> 01:32:13.060
Faculty (Olympus): For this one.

717
01:32:13.060 --> 01:32:14.250
Pradeep Kumar .: Yeah, goodbye.

718
01:32:14.770 --> 01:32:30.899
Faculty (Olympus): Yeah, so maybe think aboutâ€¦ so, okay, some of these things, I think, will be a little clearer when we do some of those calculations, if you haven't seen this before, but if you think of the bin 1 being empty, right, what do you need? You need.

719
01:32:30.900 --> 01:32:31.420
Pradeep Kumar .: Okay.

720
01:32:31.420 --> 01:32:37.849
Faculty (Olympus): The black bone, has to goâ€¦ has to not be in bin 1, notâ€¦

721
01:32:38.600 --> 01:32:47.509
Faculty (Olympus): In bin 1, and you also want the blue ball notâ€¦ In bin 1â€¦

722
01:32:48.790 --> 01:32:52.319
Faculty (Olympus): And the third ball also not in bin 1.

723
01:32:52.420 --> 01:32:56.110
Faculty (Olympus): Right? Now, you think about the black ball not in VIN1.

724
01:32:56.110 --> 01:32:56.900
Pradeep Kumar .: Everything's fine.

725
01:32:57.090 --> 01:33:00.599
Faculty (Olympus): So what is the probability that the black ball actually goes to bin 1?

726
01:33:00.950 --> 01:33:04.530
Faculty (Olympus): Itâ€¦ it is selecting one out of the three bins.

727
01:33:05.140 --> 01:33:10.210
Faculty (Olympus): uniformly, so the probability that it selects bin 1 is 1 by 3.

728
01:33:10.390 --> 01:33:19.320
Faculty (Olympus): So the probability that it does not select bin 1 is 1 minus 1 by 3, right? Probability of A complement is 1 minus probability of A.

729
01:33:19.700 --> 01:33:25.179
Faculty (Olympus): So the probability that it does not go to bin 1 is going to be 2 by 3.

730
01:33:26.110 --> 01:33:37.540
Faculty (Olympus): Similarly, the probability that the blue ball also does not go to bin 1 is going to be 2x3, and the green ball does not go to bin 1 is going to be 2x3. All of these happening together.

731
01:33:37.810 --> 01:33:43.219
Faculty (Olympus): Because they are independently happening, that is going to be the product of these three.

732
01:33:44.810 --> 01:33:45.810
Faculty (Olympus): That's why.

733
01:33:48.170 --> 01:33:49.000
Pradeep Kumar .: Thank you, John.

734
01:33:49.000 --> 01:33:50.639
Faculty (Olympus): Okay. Sajith?

735
01:33:51.810 --> 01:34:02.210
Sajith K N .: Hi. Good evening, sir. So, the probability, what we have found is, what is the probability of at least one empty bin, right?

736
01:34:02.210 --> 01:34:02.810
Faculty (Olympus): Yeah.

737
01:34:03.350 --> 01:34:06.759
Sajith K N .: So, what if we want to find out at least two MTPIN?

738
01:34:07.660 --> 01:34:23.670
Faculty (Olympus): Oh, yeah, yeah. Yeah, yeah, I mean, so you can compute those probabilities also. Then, for example, if you want to say there exist at least two empty bins, then I will defineâ€¦ one way of defining that would be you define

739
01:34:23.880 --> 01:34:27.180
Faculty (Olympus): an event corresponding to every pair of bins.

740
01:34:27.550 --> 01:34:32.610
Faculty (Olympus): So, either bin 1 and bin 2 are empty, Orâ€¦

741
01:34:32.610 --> 01:34:33.450
Sajith K N .: Yeah, possible.

742
01:34:33.450 --> 01:34:47.069
Faculty (Olympus): It's just going to be a complicated mess. That's it. But all of that can be computed. It's just that, yeah, you just have to take many more events, and then express them as a union, and do that.

743
01:34:47.320 --> 01:34:49.040
Sajith K N .: Same formula, right? We can experiment.

744
01:34:49.040 --> 01:34:59.210
Faculty (Olympus): Yeah, yeah, you just have to see whether you can express it as a union of some events, and whether youâ€¦ whether those individual probabilities you are able to compute easily.

745
01:34:59.600 --> 01:35:00.070
Sajith K N .: Mucky.

746
01:35:00.070 --> 01:35:05.939
Faculty (Olympus): So this is one way of doing things. It might not always be the best way, but this is one way of doing things.

747
01:35:06.170 --> 01:35:13.909
Faculty (Olympus): So if you express them as a union of smaller events, then you can use the inclusion-exclusion formula to compute these things.

748
01:35:15.650 --> 01:35:18.730
Faculty (Olympus): Okay? Yeah. Prachikumari?

749
01:35:18.730 --> 01:35:19.470
Lad Prachikumari Vijaykumar .: Pardon?

750
01:35:19.600 --> 01:35:23.469
Lad Prachikumari Vijaykumar .: Oh, Dame, what is the probabilityâ€¦

751
01:35:25.790 --> 01:35:27.650
Faculty (Olympus): Sorry, your voice is breaking.

752
01:35:31.120 --> 01:35:31.820
Lad Prachikumari Vijaykumar .: Hello?

753
01:35:32.090 --> 01:35:32.690
Faculty (Olympus): Yeah.

754
01:35:33.410 --> 01:35:34.700
Lad Prachikumari Vijaykumar .: Hello, I'm Audible.

755
01:35:34.700 --> 01:35:35.420
Faculty (Olympus): Yeah, yeah.

756
01:35:35.860 --> 01:35:41.780
Lad Prachikumari Vijaykumar .: Yeah, sir, so what is the probability of exactly one bin being empty?

757
01:35:42.680 --> 01:35:53.589
Faculty (Olympus): So, again, you can compute that, quantity, I mean, yeah, so you would want to do something likeâ€¦ I mean, yeah, it, it, itâ€¦

758
01:35:54.270 --> 01:36:01.210
Faculty (Olympus): won't be, maybe, the easiest of calculations. You have to go over possibilities, right? So, if exactly one

759
01:36:01.900 --> 01:36:10.180
Faculty (Olympus): You say exactly oneâ€¦ beenâ€¦ being empty, Soâ€¦

760
01:36:10.290 --> 01:36:12.860
Faculty (Olympus): Let's say if there were 3 bins, right?

761
01:36:14.150 --> 01:36:23.409
Faculty (Olympus): So, you have to see whatâ€¦ I mean, what are the possibilities? So, maybe if you ask me, okay, what is the probability that VIN 1

762
01:36:24.640 --> 01:36:33.050
Faculty (Olympus): is the one which is exactly empty, then you have to say bin 1 is empty, but bin 2, 3 are not empty.

763
01:36:35.510 --> 01:36:43.280
Faculty (Olympus): Right? Similarly, bin 2 is empty, but bin 1, bin 3 are not empty, so it might not be an easy calculation.

764
01:36:43.700 --> 01:36:51.690
Faculty (Olympus): might require, maybe this is not the best way of doing it. It might require some other way, of handling it.

765
01:36:51.820 --> 01:36:56.110
Faculty (Olympus): If you want to do exactly one bin, being empty.

766
01:36:57.460 --> 01:37:06.900
Saurabh Puranik .: Sir, it requires, like, exactly bin 1 is empty, then we have to consider, for example, bin 2, 2 balls.

767
01:37:07.110 --> 01:37:08.739
Saurabh Puranik .: Bintree, one ball.

768
01:37:08.990 --> 01:37:13.760
Faculty (Olympus): Yeah, so you have to thenâ€¦ yeah, so you have to do all kinds of combinations and seeâ€¦

769
01:37:13.890 --> 01:37:29.679
Faculty (Olympus): what works out. I don't know whether that is the only way to do it, I have to think about whether there are simpler ways. But sometimes, yeah, sometimes these calculations might just be messy. That's it. But I don'tâ€¦ I have to think if there is a simpler way. There might be other ways of doingâ€¦ for example.

770
01:37:30.060 --> 01:37:44.489
Faculty (Olympus): one way of often handling, so suppose you define this as your event A, right? So, sometimes what might happen is that event A might be a hard event, but A complement might be an easier event to handle.

771
01:37:45.090 --> 01:37:51.449
Faculty (Olympus): Okay? So, for example, in this case, you might ask, what is A complement? A complement isâ€¦

772
01:37:52.070 --> 01:37:57.330
Faculty (Olympus): that either no VIN is empty, or at least two bins are empty.

773
01:37:57.970 --> 01:38:02.960
Faculty (Olympus): Right? All three bins cannot be empty, soâ€¦ Either no VIN is empty.

774
01:38:03.120 --> 01:38:10.150
Faculty (Olympus): Which isâ€¦ which means every bin got one, one ball, right? Which is easy to compute.

775
01:38:10.440 --> 01:38:13.609
Faculty (Olympus): Or, there are two bins which are not empty.

776
01:38:13.740 --> 01:38:24.920
Faculty (Olympus): So again, that might be an easy calculation in the sense you can compute the probability of bin 2 and bin 3 being empty, right? That means all the 3 balls landed up in bin 1.

777
01:38:25.460 --> 01:38:35.540
Faculty (Olympus): Right? So, if you canâ€¦ you can write a complement as the union of all bins, not empty.

778
01:38:37.690 --> 01:38:49.230
Faculty (Olympus): unionâ€¦ 1, 2 empty, Union 2, 3, empty, Union 1-3MT.

779
01:38:50.560 --> 01:38:54.110
Faculty (Olympus): Right? These are the possibilities under which

780
01:38:54.670 --> 01:39:00.520
Faculty (Olympus): Exactly one VIN is not empty. I'm looking at the complement of the event that you were interested in.

781
01:39:01.070 --> 01:39:09.250
Faculty (Olympus): If you can compute the probability of A complement, then you know that the probability of A is just 1 minus the probability of A complement.

782
01:39:09.540 --> 01:39:14.030
Faculty (Olympus): Okay? So you can try and compute this probability. This is much easier in this case.

783
01:39:14.460 --> 01:39:15.340
Faculty (Olympus): Right?

784
01:39:15.510 --> 01:39:30.960
Faculty (Olympus): And once you have that, then you can go to one minute. So this is also one thing to keep in mind. Sometimes this might happen, that the event that you are looking at might be hard to directly attack, but the complement of that event might be easier.

785
01:39:31.560 --> 01:39:32.270
Faculty (Olympus): Okay?

786
01:39:33.990 --> 01:39:36.179
Faculty (Olympus): So, yeah, just something to try out.

787
01:39:38.700 --> 01:39:41.159
Faculty (Olympus): Okay, Satish Dwivedi?

788
01:39:43.120 --> 01:39:44.969
Satish Dwivedi .: Yeah, good evening, professional.

789
01:39:44.970 --> 01:39:45.500
Faculty (Olympus): Yo.

790
01:39:46.300 --> 01:39:59.800
Satish Dwivedi .: My question was, with regards to the formula itself. So, like, can you explain in a graphic way why, you know, we are, first subtracting all the complements, and then we are adding the,

791
01:40:00.130 --> 01:40:04.869
Satish Dwivedi .: the, intersection of all these.

792
01:40:05.630 --> 01:40:13.760
Faculty (Olympus): Yeah, that just comes out byâ€¦ I mean, yeah, the proof is via induction, so I can't directly give you,

793
01:40:13.880 --> 01:40:18.140
Faculty (Olympus): Okay, maybe one way of thinking about it is, soâ€¦

794
01:40:18.310 --> 01:40:20.339
Faculty (Olympus): You can think of this asâ€¦

795
01:40:21.120 --> 01:40:23.879
Faculty (Olympus): I mean, if I look at, let's say, a VIN diagram.

796
01:40:24.490 --> 01:40:29.580
Faculty (Olympus): So it's something like, you know, you're looking at the union of these three events.

797
01:40:29.910 --> 01:40:34.620
Faculty (Olympus): A, B, and C. So, you are first taking

798
01:40:34.780 --> 01:40:36.759
Faculty (Olympus): Kind of, you're summing up everything.

799
01:40:36.960 --> 01:40:42.350
Faculty (Olympus): Right? But if you sum up everything, then you are double counting the pairwise intersections.

800
01:40:43.600 --> 01:40:53.789
Faculty (Olympus): So you subtract those pairwise intersections, but then you have subtracted the common intersection of all three too many times. So you are just adding that back.

801
01:40:54.800 --> 01:41:01.849
Faculty (Olympus): So, I mean, this is something that one proves using induction, but that is the general idea. You want to compute the union.

802
01:41:01.910 --> 01:41:15.260
Faculty (Olympus): If you sum up all of them individually, then you are double counting the pairwise intersection, so you try and subtract that out, but if you then subtract all the pairwise intersections, then the common one, this part.

803
01:41:15.430 --> 01:41:21.610
Faculty (Olympus): Right, so if I erase all of these, so the one which is common to all three.

804
01:41:23.600 --> 01:41:26.929
Faculty (Olympus): this part. That is getting erased too many times.

805
01:41:27.090 --> 01:41:34.549
Faculty (Olympus): So then you add that back. That is the idea, but, the proof just follows by, via induction.

806
01:41:34.550 --> 01:41:40.860
Rahul Joshi .: with this analogy, you are subtracting it 3 times, right? That common area, so don't you have to add it 3 times?

807
01:41:40.910 --> 01:41:51.389
Faculty (Olympus): Yeah, yeah, so two of the times might be okay, and one of the time is the additional time that you have, subtracted. So, I mean, yeah, it comes out from the proof itself,

808
01:41:51.530 --> 01:41:54.099
Faculty (Olympus): How you have to balance those three.

809
01:41:55.900 --> 01:41:56.590
Faculty (Olympus): Yeah.

810
01:41:57.590 --> 01:41:58.310
Satish Dwivedi .: Yeah.

811
01:41:58.310 --> 01:42:01.569
Faculty (Olympus): This is a proof you can find anywhere,

812
01:42:01.900 --> 01:42:10.670
Faculty (Olympus): I don't know whether it is there in the book, but the inclusion-exclusion formula proof is available anywhere. The idea will exactly be what I just said.

813
01:42:12.100 --> 01:42:13.650
Satish Dwivedi .: Yeah, Damar, thank you.

814
01:42:13.920 --> 01:42:16.409
Faculty (Olympus): Okay. Manu Gupta?

815
01:42:19.710 --> 01:42:22.870
Manu Gupta .: I don'tâ€¦ Am I audible, Professor?

816
01:42:22.870 --> 01:42:23.590
Faculty (Olympus): Yeah, yeah.

817
01:42:24.170 --> 01:42:42.929
Manu Gupta .: So my point is regarding one analogy, which you mentioned during, this bar and bin problem, that we can, consider it as a job and server problem, and we can think of an event that a server rise idle during any job,

818
01:42:43.560 --> 01:43:01.750
Manu Gupta .: assignment. So, but inâ€¦ I think in real life, there are the more chances that a particular job is more biased towards any server or any, job assignment. Or I can say a board is more biased for 1 bin, 2bin in real life.

819
01:43:01.940 --> 01:43:07.210
Manu Gupta .: So, how we can make the significance in near life of this theorem?

820
01:43:07.690 --> 01:43:18.969
Faculty (Olympus): So, what I discussed directly is, of course, not relevant, butâ€¦ or not directly applicable, but like I said, I mean, balls and bins is a very classical problem that has been studied.

821
01:43:19.320 --> 01:43:24.589
Faculty (Olympus): One way of making it more relevant to the problem you are saying is to have a graph.

822
01:43:24.930 --> 01:43:29.880
Faculty (Olympus): Okay, so maybe there are 3 different jobs that came in. A green job.

823
01:43:30.100 --> 01:43:32.930
Faculty (Olympus): A black job, and a blue job.

824
01:43:33.060 --> 01:43:35.100
Faculty (Olympus): And let's say there are,

825
01:43:35.380 --> 01:43:51.040
Faculty (Olympus): I don't know, let's say there are, 4 servers, but like you said, maybe every ball cannot go in every bin, or cannot be solved by every server, okay? So, one way to represent that is via a graph.

826
01:43:51.510 --> 01:43:53.819
Faculty (Olympus): So, you say that this

827
01:43:54.730 --> 01:43:59.399
Faculty (Olympus): You design this via a graph, so this ball can only go to these two edges.

828
01:43:59.600 --> 01:44:03.500
Faculty (Olympus): The black ball can potentially only go to these two.

829
01:44:03.740 --> 01:44:08.299
Faculty (Olympus): And the blue ball can only go either here, Or there.

830
01:44:08.740 --> 01:44:18.109
Faculty (Olympus): Okay? And then, for every ball, now instead of choosing 1 out of all the 4 bins, you will choose 1 out of the bins to which it can go.

831
01:44:18.640 --> 01:44:19.460
Faculty (Olympus): Okay?

832
01:44:19.890 --> 01:44:29.510
Faculty (Olympus): So then, again, people study the same kind of object. They study what is the chance that there is an empty bin, which now depends on the underlying, this graph structure.

833
01:44:29.560 --> 01:44:47.569
Faculty (Olympus): They also study what is the maximum load, which meansâ€¦ what is the maximum number of balls that land up in a bin. That's, like, the maximum load on a server. Again, there are characterizations of that, and so on. So, it's a very classical problem, there are lots of variations of this problem that have been studied.

834
01:44:48.480 --> 01:44:53.689
Manu Gupta .: So Iâ€¦ yes, so my takeaway, we have to explicitly mention all the cases.

835
01:44:53.690 --> 01:45:09.970
Faculty (Olympus): Yeah, yeah, yeah. Yeah, so you have toâ€¦ I mean, howâ€¦ yeah, whether it applies to your problem or not, of course, depends, but you have toâ€¦ yeah, if it applies, there might be variants of this problem that are applicable, which might have to include the constraints that you have.

836
01:45:11.380 --> 01:45:12.370
Manu Gupta .: Okay, thank you.

837
01:45:12.370 --> 01:45:13.090
Faculty (Olympus): Yeah.

838
01:45:13.220 --> 01:45:16.499
Faculty (Olympus): Yeah, Vinayâ€¦

839
01:45:20.040 --> 01:45:39.209
vinay kaisar: Yes, my question is, we are discussing where the number of balls are finite. So, does our inclusion and exclusion principle explains when there are, not a finite number of balls? I mean an infinite number of balls, that is, queries coming on the server.

840
01:45:39.210 --> 01:45:44.460
vinay kaisar: might not be finite, and then I'll have to calculate

841
01:45:44.460 --> 01:45:52.410
vinay kaisar: what is the probability of, you know, load balancing? So, two lines, on thisâ€¦

842
01:45:52.970 --> 01:45:58.190
Faculty (Olympus): I don't know whether there is a version of the inclusion-exclusion principle for

843
01:45:58.350 --> 01:46:17.389
Faculty (Olympus): infinite union. The one that I know of, has, Nâ€¦ I mean, it has an N inbuilt into it. So it can be any N, but the N hasâ€¦ still has to be finite. I don't know if there is a version of inclusion-exclusion for.

844
01:46:17.690 --> 01:46:18.740
vinay kaisar: I mean,

845
01:46:18.740 --> 01:46:19.110
Faculty (Olympus): toâ€¦

846
01:46:19.110 --> 01:46:23.879
vinay kaisar: Do we have something in the syllabus, or this is the syllabus,

847
01:46:24.120 --> 01:46:39.370
Faculty (Olympus): Yeah, thisâ€¦ I mean, whatever I'm talking about isâ€¦ Okay. Yeah, so you don't have to worry about theâ€¦ if youâ€¦ yeah, I don't know whether there is something like that. I'm not sure. The formula that I have, in the notes is for, someâ€¦ for a finite N.

848
01:46:40.460 --> 01:46:52.539
vinay kaisar: Okay, one question out of this is, I am taking notes simultaneously, for your lectures, what do you suggest? Do we refer some book or take notes?

849
01:46:53.020 --> 01:46:54.450
vinay kaisar: That will beâ€¦ thank you.

850
01:46:55.920 --> 01:47:12.489
Faculty (Olympus): I mean, the book is, of course, always there. That is definitely a reference that you should use, because it'll have more content than what I can cover in the lecture. Plus, I'm going to share notes, like I said, before every lecture, and I'll also share

851
01:47:12.490 --> 01:47:20.719
Faculty (Olympus): whatever notes we prepared during this lecture. So, whatever I talked about during the lecture, that will also be shared after the class.

852
01:47:20.900 --> 01:47:24.309
Faculty (Olympus): All of theseâ€¦ I mean, you will have these, with you.

853
01:47:24.550 --> 01:47:43.539
Faculty (Olympus): at the end, I do suggest that you also, at least during the lecture, try and follow, although I agree that it might sometimes be hard and might be difficult to keep making notes while, while also listening to the lecture, but in my experience, it does help to write things down on your own as well.

854
01:47:43.710 --> 01:47:44.870
vinay kaisar: Right, thanks.

855
01:47:45.580 --> 01:47:47.140
Faculty (Olympus): Okay, Vidya?

856
01:47:49.400 --> 01:48:06.470
Vidya Gavel: So, hi Nikhil. I have a question regarding the, exams perspective. So, during the exam or in exam, we have to only solve the problems, or do we also need to prove these theorems or formulas?

857
01:48:06.820 --> 01:48:14.550
Faculty (Olympus): No, so, like I said, I mean, you will not have to prove, the formulas which we are not

858
01:48:14.550 --> 01:48:28.419
Faculty (Olympus): proving. You can assume everything that we do in class, that is, like, your starting point. So, for example, theâ€¦ the formula of probability of union being equal to sum minus intersection, that is something that you can assume as given to you.

859
01:48:28.740 --> 01:48:34.670
Faculty (Olympus): And then from there, you canâ€¦ you might be asked to prove something else, but that is something that is already given to you.

860
01:48:34.920 --> 01:48:37.409
Faculty (Olympus): So you don't have to worry about the proof of that.

861
01:48:37.650 --> 01:48:40.949
Dinesh Devnath Yadav .: Soâ€¦ Sorry, Professor, so my.

862
01:48:40.950 --> 01:48:41.830
Vidya Gavel: Great, thanks.

863
01:48:42.420 --> 01:48:50.940
Faculty (Olympus): Let's please wait, for your turn. Let me call so thatâ€¦ yeah, otherwise we go into problem.

864
01:48:52.020 --> 01:48:52.980
Vidya Gavel: Thanks, Nikil.

865
01:48:53.030 --> 01:48:56.100
Faculty (Olympus): Okay. Okay, Adityitya Agravan?

866
01:48:59.140 --> 01:49:00.330
Aditya Agarwal .: Oh, hello, sir.

867
01:49:00.330 --> 01:49:00.880
Faculty (Olympus): Yeah.

868
01:49:00.880 --> 01:49:11.119
Aditya Agarwal .: Sir, just one thing, regarding the scenario where we considered E1 intersection E2, intersection E3, and we assumed that it's gonna be zero.

869
01:49:11.220 --> 01:49:21.589
Aditya Agarwal .: So that assumption was coming from the fact that, weâ€¦ there will be no such scenarios where the ball cannotâ€¦ like, all the balls won't go inside any of the bins.

870
01:49:21.590 --> 01:49:22.380
Faculty (Olympus): Yeah, yeah.

871
01:49:23.150 --> 01:49:31.889
Aditya Agarwal .: So, likeâ€¦ but there can be a situation, you know, where we would assume that none of the balls went inside any of these three bins.

872
01:49:31.890 --> 01:49:41.800
Faculty (Olympus): So somehow the ball got dropped out of the system. Yeah, yeah, yeah, absolutely. So, for example, even in the case of load balancing, sometimes jobs might get dropped.

873
01:49:41.800 --> 01:49:52.589
Faculty (Olympus): Which means they don't go into any of the bins. So yeah, then in that case, you cannot assume A1 intersection A2, intersection A3 to be null. You have to have some way of accounting for that, for a job getting dropped.

874
01:49:52.950 --> 01:49:59.680
Faculty (Olympus): So usually, you will have some probabilistic model for that as well. Maybe with some probability, a job gets dropped.

875
01:49:59.900 --> 01:50:14.669
Faculty (Olympus): Now, with the remaining probability, it gets chosen intoâ€¦ thrown into one of theâ€¦ so, let's say with probability 1 fourth, a job gets dropped, so now the remaining 3 fourths probability, it is equally likely to choose one of the three bins.

876
01:50:14.740 --> 01:50:22.310
Faculty (Olympus): So then 1 4th, 1 4th, 1 fourth distributing among these throws, but with 1 4th probability, it gets dropped. So you have to then account for that.

877
01:50:22.620 --> 01:50:24.970
Aditya Agarwal .: Yeah, so this was more like a best-case scenario, or the.

878
01:50:24.970 --> 01:50:35.320
Faculty (Olympus): Yeah, yeah. This is, like, a vanillaâ€¦ this is, like, the most vanilla balls and bin problem. People, yeah, there are various variants of that, and depends on what your system is.

879
01:50:35.800 --> 01:50:36.720
Aditya Agarwal .: Thank you.

880
01:50:36.720 --> 01:50:38.749
Faculty (Olympus): Okay? Niraj?

881
01:50:39.900 --> 01:50:41.230
Faculty (Olympus): Niraj Mishra?

882
01:50:42.270 --> 01:50:54.129
Niraj Kumar Mishra .: Yes, Professor. So, I have a very basic question. In all three exercises, right, we have calculated some value, like 1 by 2, 2 by 3, and 1x3, right?

883
01:50:54.130 --> 01:50:54.640
Faculty (Olympus): Yeah, yeah.

884
01:50:54.640 --> 01:51:02.470
Niraj Kumar Mishra .: So, how did we calculate this, exact value, for, the respective probability of event subset?

885
01:51:03.300 --> 01:51:04.899
Faculty (Olympus): So, again, I mean.

886
01:51:05.110 --> 01:51:16.900
Faculty (Olympus): For example, when there were 3â€¦ when there was 2 balls, 2 bins, right, we were calculating the probability, let's say, of this ball landing up in bin

887
01:51:17.160 --> 01:51:18.340
Faculty (Olympus): 2.

888
01:51:18.480 --> 01:51:23.300
Faculty (Olympus): So, it is choosing one of the two bins uniformly.

889
01:51:23.430 --> 01:51:27.810
Faculty (Olympus): So it has half probability of landing here, half probability of landing here.

890
01:51:28.210 --> 01:51:33.210
Faculty (Olympus): Right? So the probability that this ball lands in bin 2 is 1 half.

891
01:51:33.860 --> 01:51:36.500
Faculty (Olympus): Similarly, if, for example, there were

892
01:51:36.630 --> 01:51:38.940
Faculty (Olympus): 2 balls, but 3 bins.

893
01:51:39.280 --> 01:51:44.659
Faculty (Olympus): And you ask, what is the probability that this ball lands up here? Now.

894
01:51:44.980 --> 01:52:01.510
Faculty (Olympus): There are 3 choices, right, for this ball to land up in. The probability that it chooses the third bin is 1x3, the probability that it chooses to land up in the second bin is 1x3, the probability that it chooses to land up in the first bin is 1x3.

895
01:52:02.570 --> 01:52:08.090
Faculty (Olympus): So, if you ask me what is the probability that it does not land up here.

896
01:52:08.720 --> 01:52:15.059
Faculty (Olympus): Right? Thatâ€¦ that probability is equal to the probability that it is either here or here.

897
01:52:15.230 --> 01:52:20.579
Faculty (Olympus): Which is then the sum of the two probabilities. So, 1 by 3 plus 1 by 3, 2 by 3.

898
01:52:22.060 --> 01:52:24.459
Faculty (Olympus): That's how we do these calculations.

899
01:52:26.280 --> 01:52:34.239
Faculty (Olympus): So, again, some of these calculations, as you go through the TA sessions, as you solve some of these problems, you will get more and more conversant with them.

900
01:52:34.560 --> 01:52:36.679
Faculty (Olympus): These will become easier and easier, yeah.

901
01:52:36.730 --> 01:52:38.190
Niraj Kumar Mishra .: Yeah, thank you, sir. Thanks.

902
01:52:38.190 --> 01:52:42.040
Faculty (Olympus): Okay. Yeah, Vamsi Krishna?

903
01:52:43.350 --> 01:52:47.190
Vamsi Krishna Mutnuri .: Sir, my question is on the A complement, if you can go a littleâ€¦

904
01:52:47.560 --> 01:52:50.620
Vamsi Krishna Mutnuri .: About. I, no, no, sir.

905
01:52:50.880 --> 01:52:52.820
Vamsi Krishna Mutnuri .: I'll drill down. Yes, here.

906
01:52:52.820 --> 01:52:53.350
Faculty (Olympus): Huh.

907
01:52:53.350 --> 01:53:00.900
Vamsi Krishna Mutnuri .: Here, now, A complementâ€¦ in this A complement equation, if, the set is all bins not empty.

908
01:53:01.180 --> 01:53:01.740
Faculty (Olympus): Yeah.

909
01:53:02.360 --> 01:53:05.789
Vamsi Krishna Mutnuri .: That means either one ofâ€¦ I mean, at least one,

910
01:53:06.750 --> 01:53:12.280
Vamsi Krishna Mutnuri .: The value of this should be zero, ideally, if we are looking for exactly the first bin to be empty, right?

911
01:53:12.740 --> 01:53:17.210
Faculty (Olympus): No, no, this is the event that all bins are not empty. That can happen, right?

912
01:53:17.650 --> 01:53:20.029
Faculty (Olympus): If every bin gets one ball.

913
01:53:20.320 --> 01:53:22.470
Faculty (Olympus): Then all builds are not empty.

914
01:53:23.620 --> 01:53:24.570
Vamsi Krishna Mutnuri .: Okay, okay.

915
01:53:24.570 --> 01:53:25.369
Faculty (Olympus): So that wouldâ€¦

916
01:53:25.370 --> 01:53:28.269
Vamsi Krishna Mutnuri .: So, where is the situation in this set whereâ€¦

917
01:53:28.530 --> 01:53:34.530
Vamsi Krishna Mutnuri .: You know, the probability of bin 1 precisely being empty in this set.

918
01:53:34.820 --> 01:53:36.369
Faculty (Olympus): In this, it is not there.

919
01:53:36.530 --> 01:53:41.500
Faculty (Olympus): I was trying to, I mean, someone was asking me about exactly one bin being empty.

920
01:53:41.770 --> 01:53:43.540
Faculty (Olympus): And I was saying that thisâ€¦

921
01:53:43.540 --> 01:53:45.180
Vamsi Krishna Mutnuri .: One bin, or first bin.

922
01:53:45.180 --> 01:53:53.720
Faculty (Olympus): So we are now looking at the complement of that event. So, the complement of exactly one bin being empty is that

923
01:53:54.060 --> 01:53:58.530
Faculty (Olympus): Either all bins are not empty, Orâ€¦

924
01:53:59.180 --> 01:54:02.240
Faculty (Olympus): There is more than one bin which is empty.

925
01:54:02.410 --> 01:54:05.180
Faculty (Olympus): Right? That is what the complement of A will be.

926
01:54:06.520 --> 01:54:12.730
Faculty (Olympus): So that is why it is either all bins not empty, or a pair of bins being empty.

927
01:54:14.440 --> 01:54:19.680
Faculty (Olympus): So maybe think a little bit about it. You will be able to see,

928
01:54:19.830 --> 01:54:30.970
Vamsi Krishna Mutnuri .: It is like, it is like more or less the other question which was asked by, Mr. Akshay Agarwal, like, you know, what is the chance of a job being dropped for a server? Probably it is the A compliment, right?

929
01:54:32.400 --> 01:54:40.460
Faculty (Olympus): No, I think he was asking about what is theâ€¦ I mean, we are assuming that every ball lands up in Italyâ€¦ I mean, lands up in a bin.

930
01:54:40.960 --> 01:54:49.069
Faculty (Olympus): he was asking what if a ball completely misses all the bin? Huh? It does not even land up in a bin. So that was what wasâ€¦ what we were talking about there.

931
01:54:49.070 --> 01:54:52.559
Vamsi Krishna Mutnuri .: So, we choose the A complement based upon the situation we have in.

932
01:54:52.560 --> 01:54:53.100
Faculty (Olympus): Yeah, yeah, yeah.

933
01:54:53.100 --> 01:54:53.810
Vamsi Krishna Mutnuri .: Mario.

934
01:54:53.810 --> 01:54:54.909
Faculty (Olympus): Yeah, yeah, of course.

935
01:54:55.280 --> 01:54:56.279
Vamsi Krishna Mutnuri .: Understood, thank you.

936
01:54:56.660 --> 01:54:59.209
Faculty (Olympus): Okay. Suyash, Singhal.

937
01:54:59.210 --> 01:55:01.159
Suyash Singhal .: Yeah, Professor, am I audible?

938
01:55:01.160 --> 01:55:01.810
Faculty (Olympus): Yeah.

939
01:55:02.570 --> 01:55:12.920
Suyash Singhal .: Because I would like to understand how does this formula modify when we talk about identical beings and identical bars. What I understand from this problem is that they are completely

940
01:55:12.990 --> 01:55:26.870
Suyash Singhal .: every item is a differentiated item, but let's say if we put a condition of identical with Z, we don't label any VIN like VIN 1, 0.2, 0.3, how does this formula translate into, and how does the VIN diagram come in that?

941
01:55:27.160 --> 01:55:30.830
Faculty (Olympus): I mean, in that case, thingsâ€¦ I mean, it depends on whatâ€¦

942
01:55:31.590 --> 01:55:38.340
Faculty (Olympus): you mean, right? It is stillâ€¦ we are still talking about,

943
01:55:38.770 --> 01:55:48.700
Faculty (Olympus): when I'd say there exists an empty bin, you can stillâ€¦ the bins necessarily need not be distinguishable.

944
01:55:48.960 --> 01:55:57.759
Faculty (Olympus): It depends on how I define my event, right? Here, the balls also, at least the way weâ€¦ the kind of events we were talking about.

945
01:55:57.760 --> 01:56:10.360
Faculty (Olympus): The balls need not be distinguishable either, but if I was talking about, let's say, a specific ball, I was saying ball 1 and ball 2 should not land up somewhere, then you would need the distinguishability of the balls as well.

946
01:56:10.590 --> 01:56:18.320
Faculty (Olympus): So, it depends on what your setup is and what is it that you are interested in, whether you require distinguishability of the bins or not.

947
01:56:18.960 --> 01:56:27.250
Suyash Singhal .: Okay, so in this problem, Professor, if let's say, I say that, okay, I need to find a probability for having a bin empty.

948
01:56:27.420 --> 01:56:33.220
Suyash Singhal .: And the VIN is not, like, the bins are not, distinguishable, like, they are similar.

949
01:56:33.360 --> 01:56:36.130
Suyash Singhal .: So, does the probability change?

950
01:56:37.030 --> 01:56:44.829
Faculty (Olympus): I don't think the way we are talking about the events changes, but it depends on how exactly we define things as well.

951
01:56:45.910 --> 01:56:46.590
Faculty (Olympus): Yeah.

952
01:56:46.900 --> 01:57:01.810
Suyash Singhal .: Okay, because I was thinking if we putâ€¦ if we don't put the VIN's label, then we'llâ€¦ we should not be selecting a particular VIN, because we are actually considering PE1, PE2, PE3, which are dependent on the VIN identities.

953
01:57:03.300 --> 01:57:11.309
Faculty (Olympus): Yeah, but I mean, if it is non-distinguishable, then, I mean, yeah, you have to see whatâ€¦ whether that event also makes sense, thenâ€¦

954
01:57:11.510 --> 01:57:13.320
Faculty (Olympus): Mt.

955
01:57:13.530 --> 01:57:14.370
Faculty (Olympus): Yeah.

956
01:57:14.920 --> 01:57:25.689
Faculty (Olympus): I mean, if you're not even distinguishing between these events, then how do you talk about a bin being empty? Are we thenâ€¦ I mean, then we have to talk about,

957
01:57:25.860 --> 01:57:28.509
Faculty (Olympus): how do I define the fact that

958
01:57:28.660 --> 01:57:36.559
Faculty (Olympus): ballâ€¦ how do I even select between the bins, right? So here, underlying, we are assuming that the ball selects one of the bins.

959
01:57:36.720 --> 01:57:42.710
Faculty (Olympus): But if we are saying that the bins are not even distinguishable, then what does it mean to say one of the bins?

960
01:57:43.380 --> 01:57:48.279
Faculty (Olympus): so, I think, yeah, it depends on what we mean exactly by that.

961
01:57:48.750 --> 01:57:49.710
Suyash Singhal .: Okay.

962
01:57:49.710 --> 01:57:50.310
Faculty (Olympus): Yeah.

963
01:57:51.550 --> 01:57:54.110
Faculty (Olympus): Okay, Samrati?

964
01:58:02.940 --> 01:58:05.969
Faculty (Olympus): Okay, rahul Joshi?

965
01:58:06.310 --> 01:58:26.159
Rahul Joshi .: Yeah, sorry, sir, I'm asking the similar question again. In that VIN diagram, there was a 3, intersection. Yeah. Yeah, so we, we, we reduced the common area, like, so the probability of A then plus B plus C, and then we intersection of A and B, and then that is reduced. But then why we added only once the

966
01:58:26.200 --> 01:58:28.200
Rahul Joshi .: combination of three, Deb Q3, because we.

967
01:58:28.200 --> 01:58:28.600
Faculty (Olympus): Mr.

968
01:58:28.600 --> 01:58:29.550
Rahul Joshi .: a few times.

969
01:58:29.860 --> 01:58:31.089
Rahul Joshi .: I did not get it properly.

970
01:58:31.090 --> 01:58:45.370
Faculty (Olympus): Yeah, I mean, I would say maybeâ€¦ yeah, I don't have the proof of this off the top of my head. It is something that I also will have to work out. Please try and look it up. If it's still confusing, then I'm happy to maybe chat next time.

971
01:58:45.560 --> 01:59:03.439
Faculty (Olympus): I don't recall what the proof of this is, but I remember the idea as being you're trying to find theâ€¦ you're trying to count all the elements which are there in one of the sets at least, and you first add all of them, subtract out the common intersections, and then you have to add something back again.

972
01:59:03.490 --> 01:59:05.720
Faculty (Olympus): At least that's what I, remember.

973
01:59:07.420 --> 01:59:08.980
Rahul Joshi .: Okay, fine. Yeah. Thank you.

974
01:59:09.540 --> 01:59:15.959
Faculty (Olympus): Okay, yeah, Siddharth Kulkarni?

975
01:59:15.960 --> 01:59:24.790
Siddharth Digambar Kulkarni .: Yes, sir. From what you just mentioned some time back, we can also visualize this problem as

976
01:59:24.980 --> 01:59:35.039
Siddharth Digambar Kulkarni .: at least one of the bins being empty, we can visualize this as 1 minusâ€¦ none of the bins are empty, right?

977
01:59:35.040 --> 01:59:35.600
Faculty (Olympus): Yep.

978
01:59:37.180 --> 01:59:38.160
Faculty (Olympus): It's a very hard problem.

979
01:59:38.160 --> 01:59:39.150
Siddharth Digambar Kulkarni .: to solve, right?

980
01:59:39.150 --> 01:59:44.829
Faculty (Olympus): No, no, that's a harder problem, right? Because there are many ways in which none of the bins are empty.

981
01:59:46.030 --> 01:59:48.050
Siddharth Digambar Kulkarni .: There is only one ball in each of the bins.

982
01:59:48.050 --> 01:59:56.019
Faculty (Olympus): In the case whereâ€¦ you're right, okay, sorry. In the case when there are equal number of balls and equal number of bins, it's an easy problem, you're right.

983
01:59:56.310 --> 02:00:12.599
Faculty (Olympus): But when the number of balls and bins are not the same, then it's a very hard problem. But you're right. In the case where there are equal number of balls and bins, the only way all the bins are non-empty is if there is exactly one ball in each of the bins.

984
02:00:13.340 --> 02:00:15.779
Siddharth Digambar Kulkarni .: Right, so that is an easier problem to solve, right?

985
02:00:15.780 --> 02:00:22.990
Faculty (Olympus): That is an easier problem to solve. Yeah, when balls and bins are bothâ€¦ there are equal number of balls and bins, that's an easier problem to solve, sure.

986
02:00:22.990 --> 02:00:26.420
Siddharth Digambar Kulkarni .: Just like what you were saying earlier, cut.

987
02:00:26.420 --> 02:00:27.609
Faculty (Olympus): Correct, correct, you're right.

988
02:00:27.920 --> 02:00:28.410
Siddharth Digambar Kulkarni .: Great.

989
02:00:28.410 --> 02:00:29.939
Faculty (Olympus): We can do it that way as well.

990
02:00:31.800 --> 02:00:33.690
Faculty (Olympus): Okay, Dinesh Yadav?

991
02:00:34.290 --> 02:00:51.550
Dinesh Devnath Yadav .: Yeah, hi, Professor. So my question is around the complicity of the questions, right? As you mentioned, right, so when the number of bins or walls are not same, so in that case, right, so the complicity increases, right? So, are we going to cover these types of problems in upcoming session?

992
02:00:51.550 --> 02:01:03.779
Faculty (Olympus): Yeah, let'sâ€¦ let's maybeâ€¦ so maybe wait for the next session. You are right, the problem becomesâ€¦ inherently becomes very hard, so one tries and comes up with bounds instead of exact values, and that's what we are going to discuss next.

993
02:01:04.210 --> 02:01:10.029
Dinesh Devnath Yadav .: Okay, so maybe, or maybe we can ask TA to cover all the things.

994
02:01:10.030 --> 02:01:18.640
Faculty (Olympus): No, it's just too complicated. It's just, it isâ€¦ it is not possible to do, in the sense it's a computationally hard problem.

995
02:01:18.820 --> 02:01:19.390
Dinesh Devnath Yadav .: Okay.

996
02:01:19.660 --> 02:01:21.839
Faculty (Olympus): That's why people use Bounce.

997
02:01:22.230 --> 02:01:24.790
Dinesh Devnath Yadav .: Okay, okay, thank you, thank you, Rashi.

998
02:01:24.790 --> 02:01:26.790
Faculty (Olympus): Yeah, Anurag Singh?

999
02:01:27.750 --> 02:01:38.549
Anurag Pratap Singh: Yeah, I think my question is already answered offline by Rupal. Okay. I joined a little bit late, so I was askingâ€¦ I missed a few lectures.

1000
02:01:38.600 --> 02:01:51.500
Anurag Pratap Singh: So, if I'm going through the recordings, is my attendance is going to be considered or not? So, she said yes, until you're watching the recordings, and thenâ€¦ then I think it's fine. That's okay. Yeah?

1001
02:01:51.500 --> 02:01:52.540
Faculty (Olympus): Okay, alright.

1002
02:01:52.540 --> 02:01:53.090
Anurag Pratap Singh: Yeah, thank you.

1003
02:01:53.090 --> 02:01:54.740
Faculty (Olympus): booking? Shivkum Kumar?

1004
02:01:56.920 --> 02:02:14.780
Shivkumar Gopalan .: Hey, hi, Professor. Actually, I put my query in chat, so it is regarding that, probability of having any, one bucket empty. So, would that be possible to you to read it, or should I, you know.

1005
02:02:15.830 --> 02:02:21.540
Faculty (Olympus): Iâ€¦ it's a little difficult, Iâ€¦ I don't know what exactlyâ€¦

1006
02:02:26.850 --> 02:02:33.690
Faculty (Olympus): Yeah, I don't know, I mean, so you said probability of having all 3 balls in one bucket is this?

1007
02:02:37.820 --> 02:02:42.929
Shivkumar Gopalan .: than havingâ€¦ All three walls in any two buckets.

1008
02:02:43.070 --> 02:02:52.480
Shivkumar Gopalan .: So, if we exclude these two, then the remaining is the probability of having any one bucket empty. Is that correct? Or is there anything I'm missing out?

1009
02:03:00.610 --> 02:03:08.239
Faculty (Olympus): So, I mean, you have to choose also which two buckets the balls go in, right? So, you have to look at the probability that

1010
02:03:08.700 --> 02:03:11.760
Faculty (Olympus): If you're calculating bin 1 being empty.

1011
02:03:11.970 --> 02:03:17.339
Faculty (Olympus): Then you have to see what is the probability that the three balls, each of them lands up in

1012
02:03:17.900 --> 02:03:19.830
Faculty (Olympus): The two remaining buckets.

1013
02:03:20.820 --> 02:03:24.369
Faculty (Olympus): So that is what 8x27 comes out to be.

1014
02:03:24.940 --> 02:03:26.660
Faculty (Olympus): It's not about theâ€¦

1015
02:03:26.660 --> 02:03:27.170
Shivkumar Gopalan .: Can you also?

1016
02:03:27.170 --> 02:03:30.830
Faculty (Olympus): to take into account the fact that there are choices for those two bins.

1017
02:03:31.860 --> 02:03:46.399
Manu Gupta .: Sir, I can comment here that if we look one as empty, then there's a chances of 8, points that 3 balls can go to 2 bins.

1018
02:03:46.400 --> 02:03:54.799
Manu Gupta .: But here, there will be one case, where all three bins may go in one bin, out of the two selected bins.

1019
02:03:55.300 --> 02:04:02.480
Manu Gupta .: So, that number we have to calculate, that is 6 number, 8 minus 2, and that is the probability that.

1020
02:04:02.480 --> 02:04:06.399
Faculty (Olympus): maybe, again, I think it is very confusing if weâ€¦

1021
02:04:06.550 --> 02:04:25.449
Faculty (Olympus): in doing this while speaking. My suggestion is, if there are particular, firstly, you should think about it, but if there is specific solutions which you feel would also have answered, please write them down, show them to the TA, and they can work it out with you.

1022
02:04:25.720 --> 02:04:31.170
Faculty (Olympus): Okay. Otherwise, I think, yeah, while speaking, there might be many, it's not very easy to follow.

1023
02:04:32.770 --> 02:04:33.770
Faculty (Olympus): Okay.

1024
02:04:34.780 --> 02:04:36.050
Shivkumar Gopalan .: Thanks, thanks for listening.

1025
02:04:36.180 --> 02:04:38.409
Faculty (Olympus): Sure. Harshad?

1026
02:04:38.780 --> 02:04:40.619
Harshad Dilip Behere .: Yeah, good evening, Professor. Am I audible?

1027
02:04:40.980 --> 02:04:41.860
Faculty (Olympus): Yeah, yeah.

1028
02:04:42.220 --> 02:04:56.139
Harshad Dilip Behere .: Yeah, so, does it make sense for us to list out the possibilities here, Professor? Like, we have B1, B2, B3 going to bucket 1, bucket 2, bucket 3? I mean, there could beâ€¦ I mean, with these three numbers, I think there are various possibilities.

1029
02:04:56.140 --> 02:05:03.090
Faculty (Olympus): Yeah, yeah, I mean, for a small problem, you can do that, but as the problem size becomes larger, it's going to become harder and harder to do.

1030
02:05:03.430 --> 02:05:07.829
Harshad Dilip Behere .: So, then we will have the formulas to do it accordingly?

1031
02:05:07.830 --> 02:05:15.130
Faculty (Olympus): There are formulas, and many times the formulas will also be very complicated, so you work with bounds. So we'll do that next time.

1032
02:05:15.130 --> 02:05:16.940
Harshad Dilip Behere .: Okay, sure. Thank you, perhaps.

1033
02:05:16.940 --> 02:05:18.790
Faculty (Olympus): Okay? Yeah, varun?

1034
02:05:20.200 --> 02:05:33.279
varun kumar .: Hey, hi, Professor, this is, so my question is not related to this technicality, I just wanted to know, like, for the other course, which is going parallel, we got something like, you know,

1035
02:05:33.400 --> 02:05:39.430
varun kumar .: Preparational courses, like, we were given some courses to do online.

1036
02:05:39.750 --> 02:05:51.499
varun kumar .: And did it, and that helped a lot. Now, coming to this probability, I'm doing it for, for more than 15 years after 15 years. And it is very, you know,

1037
02:05:51.620 --> 02:05:54.600
varun kumar .: difficult, I'm finding, to, you know, grasp everything.

1038
02:05:55.200 --> 02:05:59.199
varun kumar .: So, is there anything similar Iâ€¦ we can get, I mean, I can get, I would say.

1039
02:05:59.390 --> 02:06:02.770
varun kumar .: So that I can practice, I can learn in little slow.

1040
02:06:02.770 --> 02:06:03.860
Faculty (Olympus): I mean, I think,

1041
02:06:04.420 --> 02:06:11.059
Faculty (Olympus): Yeah, so that is why material is being shared ahead of time, and that is why the TA sessions are also there.

1042
02:06:11.080 --> 02:06:26.440
Faculty (Olympus): So, like I said, the TA sessions will help you, at least get practice on problem solving, and the slower session will go over more details, they will try and resolve as many doubts as possible. But ultimately, I think it is about spending some time with the material.

1043
02:06:26.580 --> 02:06:38.490
Faculty (Olympus): So, I am sharing my notes, I'm also sharing, trying, kind of the reference or the chapters of the books. Yeah, you haveâ€¦ ultimately, it's about spending time with it.

1044
02:06:38.860 --> 02:06:42.429
Faculty (Olympus): There's no easy way other than that.

1045
02:06:43.190 --> 02:06:47.770
varun kumar .: I mean, no, I mean, where is this material shared in advance?

1046
02:06:48.140 --> 02:06:56.960
Faculty (Olympus): It was there on the announcements, so I shared the notes, and I also shared the reference for the chapters. It was all there on the announcements.

1047
02:06:57.610 --> 02:06:59.370
varun kumar .: Okay. Of course.

1048
02:07:00.170 --> 02:07:00.950
Faculty (Olympus): Okay?

1049
02:07:01.180 --> 02:07:02.670
Faculty (Olympus): Yeah, Rahul?

1050
02:07:04.070 --> 02:07:05.870
Rahul Joshi .: No, no, actually, my question is answered, sorry.

1051
02:07:05.870 --> 02:07:07.370
Faculty (Olympus): Alright, okay, Gaurav?

1052
02:07:08.430 --> 02:07:22.069
Gaurav Singh .: Yes, sir, so, just, I have written out for the 2-ball, 2-bin, can we define our sample space? Just now I have pinned, like this, but if we define like this, probably,

1053
02:07:22.220 --> 02:07:29.690
Gaurav Singh .: identifying one empty VIN, only the first two occurrence, are representing

1054
02:07:29.940 --> 02:07:32.319
Gaurav Singh .: Are you able to see my ping just now?

1055
02:07:32.320 --> 02:07:42.829
Faculty (Olympus): I saw, again, I would suggest, maybe spending some time with the problem, and then, trying with the TA, where you will have more time.

1056
02:07:42.980 --> 02:07:48.770
Faculty (Olympus): To try and resolve whether that is a reasonable way. But maybe first, spend some time yourself.

1057
02:07:48.900 --> 02:07:54.649
Faculty (Olympus): On seeing whether that is, a feasible way of defining the sample space.

1058
02:07:55.640 --> 02:07:56.160
Gaurav Singh .: Got it.

1059
02:07:56.160 --> 02:08:01.960
Faculty (Olympus): Yeah, there are many ways of doing theseâ€¦ the same thing, but yeah, you have to see whether that makes sense.

1060
02:08:01.960 --> 02:08:04.310
Gaurav Singh .: But it doesn't seem to be giving the right answer either.

1061
02:08:04.310 --> 02:08:10.029
Faculty (Olympus): It could be. So, again, many of these things might seem midget, so spend some time with it.

1062
02:08:10.230 --> 02:08:12.699
Faculty (Olympus): See why it is not giving the right answer.

1063
02:08:13.680 --> 02:08:21.060
Faculty (Olympus): Okay, if you're not able to resolve, then maybe talk to the TA. If you're not able to resolve even there, then I'm happy to talk next time.

1064
02:08:22.200 --> 02:08:23.070
Gaurav Singh .: Sure. Thanks, bro.

1065
02:08:24.250 --> 02:08:29.600
Faculty (Olympus): Okay, alright, so, yeah, I'll see you guys, next time. Bye.

