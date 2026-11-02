WEBVTT

1
00:03:52.770 --> 00:03:57.779
Faculty (Olympus): Hi, I hope I'm audible and my screen is visible.

2
00:03:58.720 --> 00:04:00.270
Faculty (Olympus): Someone confirm, orâ€¦

3
00:04:19.149 --> 00:04:20.450
Faculty (Olympus): Hello?

4
00:05:49.360 --> 00:05:52.349
Rupal Makhijani: Hi, Professor Onikum. Everything is okay and visible.

5
00:05:53.300 --> 00:05:54.740
Faculty (Olympus): Okay, alright, thanks.

6
00:06:09.470 --> 00:06:13.520
Faculty (Olympus): By the way, if there are any questions, I'm happy to take them while we wait.

7
00:09:57.570 --> 00:10:01.419
Faculty (Olympus): Okay, let's, begin,

8
00:10:01.870 --> 00:10:07.640
Faculty (Olympus): So last time we had, talked about this notion of expectation.

9
00:10:07.960 --> 00:10:12.490
Faculty (Olympus): And, we willâ€¦ begin byâ€¦

10
00:10:12.980 --> 00:10:17.519
Faculty (Olympus): Again, maybe starting with that, maybe do one,

11
00:10:17.910 --> 00:10:21.590
Faculty (Olympus): One more example of, expectation.

12
00:10:21.770 --> 00:10:24.259
Faculty (Olympus): And, of a random variable.

13
00:10:25.120 --> 00:10:32.500
Faculty (Olympus): Right? And then we will, go on to the notion of variance. That's the plan for today. So, just to recall.

14
00:10:32.620 --> 00:10:34.490
Faculty (Olympus): The notion ofâ€¦

15
00:10:35.140 --> 00:10:43.590
Faculty (Olympus): expectation of a random variable, so if X is a random variable, and let's say if it is a discrete random variable, so if X isâ€¦

16
00:10:44.000 --> 00:10:47.840
Faculty (Olympus): discrete, and has a certain PMF PX.

17
00:10:48.170 --> 00:10:51.570
Faculty (Olympus): then the expected value of X,

18
00:10:52.160 --> 00:10:58.500
Faculty (Olympus): is given by summation k times PXK.

19
00:10:58.610 --> 00:11:07.299
Faculty (Olympus): Right, and K goes over whatever the support of X is. So, whatever different values that X can take, you are essentially looking at

20
00:11:07.660 --> 00:11:10.779
Faculty (Olympus): The weighted average of those values.

21
00:11:11.110 --> 00:11:20.610
Faculty (Olympus): Okay? Similarly, ifâ€¦ this is if X is discrete, if X is continuous, which means it has a certain density, a PDF FX,

22
00:11:21.020 --> 00:11:28.810
Faculty (Olympus): Then, the expected value of X is given by the integral of X.

23
00:11:30.280 --> 00:11:35.320
Faculty (Olympus): FX DXâ€¦ Or from minus infinity to infinity.

24
00:11:36.060 --> 00:11:44.349
Faculty (Olympus): Okay? So this is what the expected value of a random variable is, and if you recall, we essentially argued that this is supposed to

25
00:11:44.510 --> 00:12:01.879
Faculty (Olympus): mimic or indicate that if you take many, many samples from this distribution, what is, like, the average value that you will perhaps see? Okay, that average value will be essentially close to the expectation of X. That is the idea. So that is what is the operational meaning

26
00:12:01.880 --> 00:12:09.129
Faculty (Olympus): of, either of these formulas, okay? The operational meaning is, like, this is theâ€¦ if you do many, many

27
00:12:09.380 --> 00:12:18.020
Faculty (Olympus): If you take many, many samples from this distribution, the average value will be essentially close to this expectation. That's what we expect.

28
00:12:18.100 --> 00:12:28.910
Faculty (Olympus): Okay? Now, last time in the example, we also did, inâ€¦ we had a random variable D, which was the demand.

29
00:12:28.910 --> 00:12:40.059
Faculty (Olympus): right, the random demand, and then we were interested in the expected value of a certain function of that demand. So I just want to kind of highlight that as well. So if you have X, which is a random variable.

30
00:12:41.180 --> 00:12:46.120
Faculty (Olympus): Then, you can takeâ€¦ But yeah.

31
00:12:47.370 --> 00:12:53.289
Faculty (Olympus): You can take a function of that random variable, G ,

32
00:12:53.680 --> 00:13:11.599
Faculty (Olympus): Okay, so this G , think of that as another random variable, Y. Okay, this is just a function of this random variable. For example, this could be if x is your random variable, this function could be X squared, right? And let's say you are interested in the expected value of G of X.

33
00:13:12.900 --> 00:13:24.720
Faculty (Olympus): then that, again, is very, very similar. All that happens is that this K and this X gets replaced by G of K and G of X. That's it. So if, again, if

34
00:13:24.890 --> 00:13:28.830
Faculty (Olympus): The G of X is a discrete random variable.

35
00:13:29.080 --> 00:13:37.780
Faculty (Olympus): Then this quantity is going to be summationâ€¦ G of K timesâ€¦ PXK?

36
00:13:39.120 --> 00:13:45.550
Faculty (Olympus): K in the support of X. Similarly, if it's continuous, this is going to beâ€¦

37
00:13:45.730 --> 00:13:51.980
Faculty (Olympus): Integral G of X times the densityâ€¦ integrated.

38
00:13:52.370 --> 00:14:08.459
Faculty (Olympus): over the real, okay, over minus infinity to infinity. That's it. And the idea is, again, the sameâ€¦ think of what expected value of G of X means. It means, roughly, if youâ€¦ if you're getting X from some distribution, and you look at this function of X,

39
00:14:08.460 --> 00:14:14.419
Faculty (Olympus): What is, like, the average value of the function that you expect to see if you take many, many samples from X?

40
00:14:14.700 --> 00:14:20.110
Faculty (Olympus): What is the average value of G of X? So again, it'sâ€¦ for every K,

41
00:14:20.110 --> 00:14:34.429
Faculty (Olympus): this is the probability that you see K, or this is, like, the fraction of times that you expect to see K, and this is the function value corresponding to that, right? So you're looking at the weighted average of these function values, where the weight is exactly

42
00:14:34.430 --> 00:14:41.330
Faculty (Olympus): the fraction of times, or the probability associated with that point. The same thing kind of goes through for

43
00:14:41.740 --> 00:14:44.890
Faculty (Olympus): The case of continuous random variables as well.

44
00:14:45.090 --> 00:15:06.349
Faculty (Olympus): Okay, so this is what we had done so far. We had just looked at the notion of expectation of a random variable, and then we had done a couple of examples. We had looked at what the expected value will be for some particular distributions, and then we had done a few examples of that. Okay, so I'm going to just do maybe one

45
00:15:06.350 --> 00:15:09.529
Faculty (Olympus): More example. Today, this is related to

46
00:15:10.300 --> 00:15:15.410
Faculty (Olympus): An application of expectation that you will probably see when you do

47
00:15:15.460 --> 00:15:31.430
Faculty (Olympus): you know, any sort of machine learning, or even in your introductory linear regression, or something like that, you will see such things happening, where you are training a neural network, or you're training a model. You often have

48
00:15:31.840 --> 00:15:43.289
Faculty (Olympus): a big dataset, but you actually don't work with the entire dataset. You look at the notion of a mini-batch, and you sample some points randomly from that training dataset, which is called a mini-batch.

49
00:15:43.400 --> 00:15:48.519
Faculty (Olympus): So, I want to comeâ€¦ kind of discuss one such example.

50
00:15:48.680 --> 00:15:53.599
Faculty (Olympus): Of, of a very simple, linear regression model.

51
00:15:53.760 --> 00:15:59.120
Faculty (Olympus): Okay, so think of a very simple, and this is like a scalar linear regression model.

52
00:16:03.650 --> 00:16:13.459
Faculty (Olympus): Okay, so suppose, we want to learn this model, which isâ€¦ Y equals WX.

53
00:16:14.670 --> 00:16:32.600
Faculty (Olympus): Okay, so, this is the model that I want to learn. I have some training data, so I want to find, like, the best choice of W, which fits my model, okay? And let's say my training data is, this is X, this is Y, so I have 4 training points.

54
00:16:33.090 --> 00:16:38.120
Faculty (Olympus): let's say 1, 2, 3, and 4. The training pointsâ€¦

55
00:16:38.350 --> 00:16:48.360
Faculty (Olympus): The training data is as follows. It's 1, 2, comma 5â€¦ 3, comma 6â€¦

56
00:16:48.540 --> 00:16:57.169
Faculty (Olympus): and 4, comma 9, right? So this is some data that I have, okay? Maybe X is, like, could be, for example.

57
00:16:57.170 --> 00:17:11.480
Faculty (Olympus): the amount of budget you spend on advertising, and Y could perhaps be the sales that you make, right? Or X could be the number of hours that you put in

58
00:17:11.490 --> 00:17:30.420
Faculty (Olympus): To study, and Y could be the score you get. Okay, so something like that, and we are trying to learn this relationship, which is essentially specified by this W. So this is the usual standard linear regression model, except that we are working with just scalars, okay? And we have, let's say, some training data, which has just 4 points.

59
00:17:30.720 --> 00:17:33.439
Faculty (Olympus): And I want to learn a good value of W.

60
00:17:33.840 --> 00:17:41.319
Faculty (Olympus): Right? So the way things work in linear regression is you're going to now look at, essentially, you will try and define a loss function.

61
00:17:41.520 --> 00:17:46.420
Faculty (Olympus): So, a loss functionâ€¦ Whoa.

62
00:17:46.950 --> 00:17:54.820
Faculty (Olympus): forâ€¦ computed for everyâ€¦ each of these data points, Xi comma Yi. So, over Xi comma Yi.

63
00:17:54.970 --> 00:18:03.450
Faculty (Olympus): The lossâ€¦ we are going to work with the squared loss, which is defined as by 2â€¦ Yi minusâ€¦

64
00:18:03.970 --> 00:18:13.520
Faculty (Olympus): W times Xi squared. Okay, so this is the standard squared loss that isâ€¦ used often.

65
00:18:13.570 --> 00:18:21.639
Faculty (Olympus): in linear regression. So the goal is, you want to choose a W, which minimizes, like, the sum of this loss

66
00:18:21.690 --> 00:18:37.410
Faculty (Olympus): over all theâ€¦ over the various training points that you have. That is your goal. You want to minimize this overall training loss, you want to figure out a value of W star, which minimizes this overall loss. So how do we do that? The way we do that is you will use some kind of

67
00:18:37.790 --> 00:18:44.230
Faculty (Olympus): gradient algorithm, right, which willâ€¦ whichâ€¦ where you will start with some initial W,

68
00:18:44.230 --> 00:19:00.720
Faculty (Olympus): And then you will takeâ€¦ you will keep moving in the gradient direction of the squared loss, and then hopefully you will reach, like, the optimum value of W. That is how any, gradient algorithm works, and these are the popular ones, like gradient descent, any of those algorithms, works in this form.

69
00:19:00.750 --> 00:19:04.519
Faculty (Olympus): Right? So theâ€¦ so suppose we are in one such iteration.

70
00:19:04.580 --> 00:19:16.290
Faculty (Olympus): So the way the iteration works is you will have some value at the beginning of the round, let's say you have a particular value of W, let's call that W tilde, and let's fix that to just be 2.

71
00:19:16.870 --> 00:19:24.579
Faculty (Olympus): Okay? So what you are going to do is you're going to look at the gradient of this, of this loss function.

72
00:19:24.930 --> 00:19:39.830
Faculty (Olympus): So, GI, which is the gradient for the i-th data point, is going to be the computation of the derivative of this loss function with respect to W of LIW.

73
00:19:40.120 --> 00:19:44.190
Faculty (Olympus): Okay, and we are going to evaluate that at the current

74
00:19:44.970 --> 00:19:47.529
Faculty (Olympus): our current estimate of W, which is 2.

75
00:19:47.740 --> 00:19:49.199
Faculty (Olympus): Okay, so in this case.

76
00:19:49.400 --> 00:20:02.099
Faculty (Olympus): you can see that the gradient is actually very simple. If you just take the derivative of this expression with respect to W, you just getâ€¦ so GI is just going to beâ€¦

77
00:20:02.450 --> 00:20:06.899
Faculty (Olympus): 2 timesâ€¦ let me rewrite this.

78
00:20:07.190 --> 00:20:18.470
Faculty (Olympus): Soâ€¦ this is going to beâ€¦ 2â€¦ No.

79
00:20:18.650 --> 00:20:19.990
Siddharth Digambar Kulkarni .: In a sexy, right?

80
00:20:22.270 --> 00:20:28.909
Faculty (Olympus): So it's minus Xi times YI minus WXI.

81
00:20:29.550 --> 00:20:35.069
Faculty (Olympus): evaluated again at W tilde being 2, so this is going to beâ€¦

82
00:20:40.530 --> 00:20:46.080
Faculty (Olympus): XIâ€¦ Timesâ€¦ 2XI minus Yi.

83
00:20:46.190 --> 00:20:50.580
Faculty (Olympus): Okay, so this is the value of the gradient for each data point.

84
00:20:50.890 --> 00:20:51.960
Faculty (Olympus): Aye.

85
00:20:51.960 --> 00:20:54.110
Atul Ashok Kumar Gupta .: Mr. Could you explain the gradient again?

86
00:20:54.110 --> 00:20:58.159
Faculty (Olympus): Yeah, so, we are taking this particular loss function.

87
00:20:58.430 --> 00:21:02.280
Faculty (Olympus): Okay, and I'm looking at the derivative of that with respect to W.

88
00:21:02.620 --> 00:21:06.630
Faculty (Olympus): So the derivative of that with respect to W is exactly this quantity.

89
00:21:07.610 --> 00:21:19.230
Faculty (Olympus): Okay? So, you have Yi minus WXI whole squared, so when you take the derivative of that, you firstly get 2 times YI minus WXI, the 2 cancels off

90
00:21:19.270 --> 00:21:28.460
Faculty (Olympus): with this particular 2, so that gives you the Yi minus WXI, and then inside you have minus WXI, so that gives you the further minus Xi.

91
00:21:28.820 --> 00:21:43.099
Faculty (Olympus): Okay, so that evaluated at the current estimate of W, which isâ€¦ which we are assuming to be 2, gives me this as my gradient value. So for the main thing to note here, if you haven't seen this before, it's no problem. The main thing is.

92
00:21:43.100 --> 00:21:49.729
Faculty (Olympus): associated with every data point, you have a certain gradient value, okay? That is the important thing. So now.

93
00:21:49.760 --> 00:21:50.450
Faculty (Olympus): itâ€¦ I canâ€¦

94
00:21:51.160 --> 00:21:54.849
Rahul Joshi .: Just one question. Why we are dividing by 2 to the square?

95
00:21:54.850 --> 00:22:09.510
Faculty (Olympus): That's just aâ€¦ that's just a way, sometimes people define gradient, because thenâ€¦ sorry, define the loss function, because then the gradient becomes easy. You don't have to necessarilyâ€¦ I mean, this is my definition of the loss function. I canâ€¦ I'm dividing it by 2.

96
00:22:09.510 --> 00:22:12.890
Siddharth Digambar Kulkarni .: Doesn't matter. When we differentiate the two cancels off.

97
00:22:12.890 --> 00:22:16.850
Faculty (Olympus): So the two cancels off, that's why it just makes things easier. That's it.

98
00:22:16.850 --> 00:22:20.599
Atul Ashok Kumar Gupta .: Purveh, could you explain the gradient again, here, the derivative of it?

99
00:22:20.600 --> 00:22:35.960
Faculty (Olympus): So, maybe, let me go throughâ€¦ like I said, I mean, if you don't follow why the gradient is this form, it's not a problem, at least for now. I will come back to it if you still need it, okay? It's just a calculation of derivative, there is nothing else there.

100
00:22:36.790 --> 00:22:41.870
Faculty (Olympus): So, the main thing to note here is that, you have

101
00:22:41.980 --> 00:22:59.029
Faculty (Olympus): 4 data points. You have, this is your data point 1, 2, 3, and 4, and each of them has a certain Xi value, a certain Yi value, and now we also have a certain gradient value associated with every data point.

102
00:22:59.330 --> 00:23:06.319
Faculty (Olympus): Okay, so if I just fill in those values, so this was 1, 0, it was 2, 5,

103
00:23:06.480 --> 00:23:10.370
Faculty (Olympus): 3, 6, and 4, 9.

104
00:23:10.510 --> 00:23:22.249
Faculty (Olympus): If you fill in those gradient values, for example, at, in the first gradient, Xi is 1, Yi is 0, so you can see that the gradient value is going to be 2.

105
00:23:22.740 --> 00:23:24.900
Faculty (Olympus): Similarly, for the second one.

106
00:23:25.200 --> 00:23:36.390
Faculty (Olympus): Xi is 2, and YI is 5, so in that case, Xi is 2, so this becomes 2 times 2 minusâ€¦

107
00:23:36.530 --> 00:23:39.960
Faculty (Olympus): 5â€¦ Which is, minus 2.

108
00:23:40.090 --> 00:23:40.920
Faculty (Olympus): Right.

109
00:23:41.240 --> 00:23:44.630
Faculty (Olympus): Similarly, if you compute the others, you are going to get these.

110
00:23:45.320 --> 00:24:00.950
Faculty (Olympus): Okay, so this is what the gradient forâ€¦ of this loss function, of the squared loss function for each of the data points is. Now, if you take any gradient-based algorithm, usually what'll happen is, if you evaluate

111
00:24:03.180 --> 00:24:09.940
Faculty (Olympus): So, in each round, you will evaluate the gradient overâ€¦

112
00:24:10.380 --> 00:24:21.679
Faculty (Olympus): the dataset. So if you could evaluate it over the entire dataset, then theâ€¦ then what the full gradient would have been would have been the average of the gradient values

113
00:24:23.080 --> 00:24:25.609
Faculty (Olympus): Over the elements of your dataset.

114
00:24:26.370 --> 00:24:41.680
Faculty (Olympus): So this would have been the full gradient that we would have liked to evaluate. If we had access to the whole data set, or if the dataset was not very large, then usually you will want to evaluate this average gradient over the entire dataset.

115
00:24:41.680 --> 00:24:48.699
Faculty (Olympus): Okay, so in this particular case, the average is justâ€¦ so 2 minus 2 plus 0 minus 4 divided by 4, which is

116
00:24:49.140 --> 00:24:51.790
Faculty (Olympus): minus 1. Okay, so this is my full gradient.

117
00:24:52.260 --> 00:24:56.239
Faculty (Olympus): For this particular loss function and this particular dataset.

118
00:24:56.640 --> 00:25:11.500
Faculty (Olympus): Okay? So, okay, let me maybe take a couple of questions. If the setting is unclear, I can talk about that now. But like I said, the main thing to note is you have some

119
00:25:11.710 --> 00:25:24.960
Faculty (Olympus): linear regression model, we are working with a very simple scalar linear regression model. There is one scalar we want to estimate, which is W. The way we want to estimate is we have this notion of a loss function, which is the squared loss

120
00:25:25.520 --> 00:25:33.660
Faculty (Olympus): we want to select a value of W, which minimizes the overall squared loss across these four data points.

121
00:25:33.810 --> 00:25:49.479
Faculty (Olympus): The way one does that, using gradient-based algorithms, is you compute the gradient at each individual data point, and then ideally, you want to compute the full gradient, which is, like, the average of those four gradients, and usually what will happen is.

122
00:25:49.480 --> 00:25:55.809
Faculty (Olympus): In this next step, you will move in the direction of your gradient. So what you will do is.

123
00:25:55.810 --> 00:26:10.530
Faculty (Olympus): you will take your, let's say, W double tilde will be W tilde, which was my previous steps, or previous estimate of W, which we had estimated to be 2, minus some step size times the

124
00:26:10.640 --> 00:26:11.770
Faculty (Olympus): gradient.

125
00:26:12.280 --> 00:26:17.199
Faculty (Olympus): That is what one would usually do, something of this kind, is what one would usually do.

126
00:26:17.540 --> 00:26:27.709
Faculty (Olympus): Okay, so for the purposes of what I'm going to talk about, all you need to understand is that there are 4 data points, and there is a certain gradient

127
00:26:27.930 --> 00:26:39.019
Faculty (Olympus): value for each of these data points. That's all that weâ€¦ you want to really understand, and the fact that you are interested in the average of these four values, okay?

128
00:26:39.360 --> 00:26:52.499
Faculty (Olympus): So beyond that, if you're not following, it's okay. This is something you will do when you lookâ€¦ when you study linear regression in yourâ€¦ in one of your courses, okay? Okay, let me look at a few quick questions. Sameer?

129
00:26:52.840 --> 00:27:07.239
Sameer Sawant .: Yeah, thank you, Professor. Professor, just one question, it's this generic one. After our first assignment solutions, and now as we are working on, random variables, and the further on, my question is with respect to Sheldon Ross' book.

130
00:27:07.240 --> 00:27:10.170
Faculty (Olympus): Can weâ€¦ can we take that seriously? Okay, okay, thank you, thank you.

131
00:27:10.390 --> 00:27:12.210
Faculty (Olympus): Okay, Manu?

132
00:27:12.440 --> 00:27:24.280
Manu Gupta .: Good morning, Professor. Yeah. So, you have started here as a W, in Quarter 2. So, ma'am, how, in this assumption, it started?

133
00:27:24.280 --> 00:27:33.790
Faculty (Olympus): The way these algorithms work is that you start with some estimate of W, and you keep moving in the direction of the gradient.

134
00:27:34.120 --> 00:27:40.040
Faculty (Olympus): The negative gradient. And you keep going in that direction, andâ€¦

135
00:27:40.040 --> 00:27:56.839
Faculty (Olympus): Because the loss is supposed to decrease in that direction. So you keep going down in that direction. So you will keep updating every round, you will update your estimate of W, and the hope is that you will reach, finally, a value of W, which is close to the optimal value.

136
00:27:57.340 --> 00:27:58.530
Faculty (Olympus): So, in every stepâ€¦

137
00:27:58.530 --> 00:27:59.450
Manu Gupta .: And you're a woman.

138
00:27:59.450 --> 00:28:06.139
Faculty (Olympus): You could have started anywhere. I just assumed that W tilde to be 2 in this round, but yeah, it could have been anywhere.

139
00:28:06.630 --> 00:28:11.760
Faculty (Olympus): Usually, people will do some random assignment, or something like that. It's okay.

140
00:28:13.530 --> 00:28:15.440
Faculty (Olympus): Okay, Anne?

141
00:28:16.770 --> 00:28:27.569
Ann G. .: Sir, we just had a discussion on linear regression in our PML course beforeâ€¦ PML class before this. We talked about getting a set of points, a line through a set of points.

142
00:28:27.570 --> 00:28:28.220
Faculty (Olympus): Huh.

143
00:28:28.220 --> 00:28:38.429
Ann G. .: So am I right in correlating that omega is the perpendicular distance of the point from the line, the sum of all the perpendicular distance from the line?

144
00:28:38.680 --> 00:28:45.719
Faculty (Olympus): That is supposed to be your residual, so thisâ€¦ this W is supposed to be, like, the description of your line.

145
00:28:46.040 --> 00:28:47.140
Siddharth Digambar Kulkarni .: No, it's load.

146
00:28:47.140 --> 00:28:49.049
Faculty (Olympus): Slope, yeah.

147
00:28:49.050 --> 00:28:50.970
Ann G. .: Okay. So theseâ€¦

148
00:28:51.670 --> 00:29:02.440
Faculty (Olympus): So theâ€¦ the squared loss, so the overall squared loss is going to be, essentially, the sum over the four data points here.

149
00:29:03.130 --> 00:29:10.480
Faculty (Olympus): of this half Yi minus WXI squared, right? So these are your squared distances.

150
00:29:11.120 --> 00:29:13.320
Faculty (Olympus): So that is how you're defining your loss.

151
00:29:14.760 --> 00:29:15.400
Ann G. .: Okay, soâ€¦

152
00:29:15.400 --> 00:29:19.379
Faculty (Olympus): It could be, like, the average of the four, or it could just be the sum of the four.

153
00:29:19.750 --> 00:29:21.990
Faculty (Olympus): Those are, like, your residuals.

154
00:29:23.430 --> 00:29:25.269
Ann G. .: Okay, I'll think about it, sir, thank you.

155
00:29:25.520 --> 00:29:26.520
Faculty (Olympus): Okay?

156
00:29:27.640 --> 00:29:37.570
Siddharth Digambar Kulkarni .: reduce the residual, you have to differentiate it with W, and then equate it to 0. That will reduce your error, right, sir?

157
00:29:37.570 --> 00:29:47.000
Faculty (Olympus): Yeah, let's, let'sâ€¦ let's, you know, if we want to say something, let's please raise our hands and, wait.

158
00:29:47.330 --> 00:29:47.980
Siddharth Digambar Kulkarni .: conferences.

159
00:29:47.980 --> 00:29:56.890
Faculty (Olympus): Okay? Yeah, but yeah, you're right. I mean, ultimately, this is like my loss function, and I want to choose a value of W that minimizes that loss function. That's the idea.

160
00:29:57.630 --> 00:29:58.380
Faculty (Olympus): Okay.

161
00:29:58.840 --> 00:30:17.890
Faculty (Olympus): Okay, so letâ€¦ let me move on. So since you have seen this somewhat before, essentially, this is exactly linear regression. We haveâ€¦ what you might not have seen isâ€¦ isâ€¦ I don't know whether you guys have seen gradient-based methods to approach

162
00:30:18.040 --> 00:30:37.789
Faculty (Olympus): the optimum solution, okay? Maybe that has not been done yet, but that is, like, again, something standard. You willâ€¦ you will see that, how to essentially compute that, or approach that optimal choice of W star. One way ofâ€¦ one very popular way of doing that is via gradient-based methods, where you start with some estimate.

163
00:30:37.820 --> 00:30:39.519
Faculty (Olympus): You evaluate the loss.

164
00:30:39.680 --> 00:30:50.939
Faculty (Olympus): At that estimate, you take the gradient of the loss and then move in the direction of the negative gradient so that your loss is decreasing in that direction.

165
00:30:50.940 --> 00:31:00.330
Faculty (Olympus): Okay, and you keep updating your W that way, okay? Okay, so for the purposes of this example, all you need to understand is that there are 4 data points.

166
00:31:00.530 --> 00:31:08.729
Faculty (Olympus): there is a certain gradient value, GI, corresponding to each of these data points, and you are interested in this average of these four data points.

167
00:31:09.140 --> 00:31:16.860
Faculty (Olympus): Average of the gradient value, okay? So thatâ€¦ that average is minus 1. Now, often what'll happen is here we had only 4

168
00:31:16.940 --> 00:31:35.040
Faculty (Olympus): data points, or our dataset size was only 4. Of course, in a real dataset, this is going to be in the orders of millions and so on, right? So, if I have to compute a gradient for every data point in, like, a huge dataset, that is too much, and that you have to do every iteration.

169
00:31:35.340 --> 00:31:41.960
Faculty (Olympus): So, the way people usually do it is they willâ€¦ selectâ€¦ a mini batch.

170
00:31:44.540 --> 00:31:46.249
Faculty (Olympus): From your dataset.

171
00:31:49.720 --> 00:32:06.410
Faculty (Olympus): So, all that happens in a mini-batch is, essentially, you select a few of the data samples at random, usually, and you only evaluate the average of the gradient over thoseâ€¦ that mini-batch. You don't evaluate it over the entire dataset.

172
00:32:06.620 --> 00:32:07.440
Faculty (Olympus): Okay?

173
00:32:07.770 --> 00:32:17.989
Faculty (Olympus): So, let's look at a very extreme example, where we, just select one data point

174
00:32:20.220 --> 00:32:24.569
Faculty (Olympus): at random. Okay, so the size of my minibatch is just 1.

175
00:32:25.010 --> 00:32:25.890
Faculty (Olympus): Okay?

176
00:32:26.270 --> 00:32:44.490
Faculty (Olympus): Now, so theâ€¦ let's say the G is, the gradient, correspondingâ€¦ to myâ€¦ selectedâ€¦ Data point.

177
00:32:47.280 --> 00:32:55.770
Faculty (Olympus): Okay, so the first thing to note is that now I am selecting only one out of the four data points, right? And I'm selecting that uniformly at random.

178
00:32:56.660 --> 00:33:14.430
Faculty (Olympus): And G is the gradient corresponding to my selected data point, okay? So, firstly, this G is now itself a random variable, right? It is not something that is deterministic, it is itself a random variable. What are the values that this G can take?

179
00:33:14.650 --> 00:33:17.379
Faculty (Olympus): Right? So G can be any one of these

180
00:33:17.620 --> 00:33:24.239
Faculty (Olympus): 4 values, right? It can be either 2, or minus 2, or 0, or minus 4.

181
00:33:24.360 --> 00:33:36.209
Faculty (Olympus): So let's put those downâ€¦ those values down. It can be 2 minus 2, 0, or minus 4. And what is theâ€¦ whatâ€¦ what areâ€¦ so this is, like, the support of G.

182
00:33:36.360 --> 00:33:49.410
Faculty (Olympus): what areâ€¦ what isâ€¦ howâ€¦ if I want to describe the PMF of G, I have to figure out what the probability of each of these gradients, coming up is, right? So what is the probability that the gradient is 2?

183
00:33:49.550 --> 00:34:00.889
Faculty (Olympus): The probability of the gradient is 2 is if the first data point is selected. If this data point is selected, then my gradient capital G is going to be 2.

184
00:34:01.190 --> 00:34:19.169
Faculty (Olympus): On the other hand, if this data point is selected, it is going to be minus 2, and so on. Now, I have assumed that each of these data points are selected uniformly at random, so each of these values is going to be selected with probability 1 by 4.

185
00:34:22.500 --> 00:34:30.489
Faculty (Olympus): Okay, so the gradient now over this mini batch of size 1 is firstly a random quantity.

186
00:34:31.010 --> 00:34:40.680
Faculty (Olympus): And itâ€¦ there is a certain PMF of that random quantity, which we have described. It can be either one of these four values, each equally likely.

187
00:34:40.989 --> 00:34:41.770
Faculty (Olympus): Okay?

188
00:34:41.770 --> 00:35:02.169
Faculty (Olympus): So now, I mean, I wanted theâ€¦ I was interested in this full gradient, which was the average of those four values. Instead, I am now doing this random quantity, so each time I'm maybe pointing in some random direction, which does not agree with my G full, so why do people use that?

189
00:35:02.350 --> 00:35:13.279
Faculty (Olympus): One reason people use that is that you canâ€¦ youâ€¦ we are right that this is a random quantity, but we can always talk about the expected gradient, or the expected direction.

190
00:35:13.570 --> 00:35:16.079
Faculty (Olympus): What is the expected gradient in this case?

191
00:35:16.330 --> 00:35:25.660
Faculty (Olympus): Right? Again, recall, the expected gradient is essentially, you look at each possible value, multiply it by its corresponding probability, and sum it up.

192
00:35:25.780 --> 00:35:36.239
Faculty (Olympus): In this particular case, because all the values are equally likely, this is going to be exactly 1 by 4 times 2 minus 2 plus 0

193
00:35:36.400 --> 00:35:37.610
Faculty (Olympus): minus 4.

194
00:35:37.790 --> 00:35:38.520
Faculty (Olympus): Right?

195
00:35:38.770 --> 00:35:44.280
Faculty (Olympus): But notice, this is exactlyâ€¦ G full. This is going to be equal toâ€¦

196
00:35:44.400 --> 00:35:47.490
Faculty (Olympus): minus 1. This is exactly my full gradient.

197
00:35:48.260 --> 00:36:03.980
Faculty (Olympus): Right? So, the reason people work with mini-batches is that you cannot evaluate the entire gradient over the whole huge data set. But if I select some random sample, in this particular case, I selected just one random data point, right?

198
00:36:04.340 --> 00:36:17.929
Faculty (Olympus): on average, or in expectation, I am going to match G full. I am going to match the full gradient, okay? So maybe in every direction, I will not exactly go down the direction of my full gradient.

199
00:36:18.050 --> 00:36:26.549
Faculty (Olympus): But on average, if you look at many, many iterations of this iterative algorithm, you are going to move roughly in the correct direction.

200
00:36:26.740 --> 00:36:41.589
Faculty (Olympus): That is why all these algorithms with mini-batches instead of full sampling work, because maybe the gradient in every iteration does not exactly match the full gradient, but on average, you are, in fact, going in the right direction.

201
00:36:42.500 --> 00:36:43.770
Faculty (Olympus): So that's the idea.

202
00:36:44.000 --> 00:36:49.049
Faculty (Olympus): Now, before I take questions, I want to generalize this a little bit.

203
00:36:49.290 --> 00:37:04.389
Faculty (Olympus): Okay, so right now, we tookâ€¦ we said, okay, we are going to just take one random sample, and G will just be the gradient corresponding to that one random sample, okay? Let'sâ€¦ let's generalize this a little bit. Let's say I now selectâ€¦

204
00:37:06.030 --> 00:37:08.530
Faculty (Olympus): 2.

205
00:37:09.330 --> 00:37:10.950
Faculty (Olympus): points.

206
00:37:13.230 --> 00:37:17.190
Faculty (Olympus): At random, and this is, let's say, with replacement.

207
00:37:17.750 --> 00:37:21.379
Faculty (Olympus): Okay, which meansâ€¦ I select one point.

208
00:37:21.790 --> 00:37:31.080
Faculty (Olympus): I look at the gradient corresponding to that point, I again select anotherâ€¦ one more point, and each of these points is 1 out of the four, equally likely.

209
00:37:31.210 --> 00:37:40.750
Faculty (Olympus): So, maybe you select the same point twice. That is also a possibility. Okay? So now, let's say G1 is the gradient corresponding to the first

210
00:37:41.020 --> 00:37:50.010
Faculty (Olympus): G2 is the gradient corresponding to the second selection, both of these are random quantities, and let's say I am going to define my G-bar

211
00:37:50.280 --> 00:37:55.750
Faculty (Olympus): to beâ€¦ The average of the two selected gradients.

212
00:37:56.360 --> 00:38:10.390
Faculty (Olympus): Okay, so it is G1 plus G2 by 2. I have selected two random points out of the four. I have selected two points. I selected one point at random out of the 4, then I selected, again, one more point at random out of the 4.

213
00:38:10.510 --> 00:38:19.790
Faculty (Olympus): Okay? And the, my gradient now is the average of these two values. Okay? So what are the possibilities for G-bar now?

214
00:38:20.380 --> 00:38:21.260
Faculty (Olympus): Okay?

215
00:38:22.000 --> 00:38:31.609
Faculty (Olympus): So, or let's say, what are theâ€¦ yeah, let's, say what are the possibilities of G-bar? So again, if you look at Gbar.

216
00:38:31.830 --> 00:38:37.700
Faculty (Olympus): Now, G1 and G2 Can each take 4 values.

217
00:38:37.910 --> 00:38:48.410
Faculty (Olympus): Right? And we are looking at this pair G1, G2. So overall, there are, in fact, 16 values that this pair G1, G2 could have taken. So let's draw those 16 values.

218
00:38:48.710 --> 00:39:07.899
Faculty (Olympus): Okay? Let's say this is my G1, this is my G2, so G1 can be either 2, or 0, or minus 2, or minus 4. These were the four gradient values. Similarly, G2 can also be 2, or 0, or minus 2, or minus 4.

219
00:39:08.370 --> 00:39:14.589
Faculty (Olympus): Right? These are the, 4 possible values for G1, 4 possible values of G2.

220
00:39:14.710 --> 00:39:20.789
Faculty (Olympus): Now, for every such pair, We can compute what the average gradient would have been.

221
00:39:20.990 --> 00:39:25.190
Faculty (Olympus): Right? So, for example, if G1, G2 were both 2,

222
00:39:25.350 --> 00:39:27.450
Faculty (Olympus): Then the average would have been 2.

223
00:39:27.600 --> 00:39:32.429
Faculty (Olympus): If G1 was 2 and G2 was 0, the average would have been 1.

224
00:39:32.750 --> 00:39:39.709
Faculty (Olympus): If G1 was 2, and G2 was minus 2, the average would have been 0, and so on, right? So I can fill this

225
00:39:39.870 --> 00:39:41.590
Faculty (Olympus): matrix up.

226
00:39:42.280 --> 00:39:46.859
Faculty (Olympus): So these are just the average values, that's all I'm putting down here.

227
00:39:47.250 --> 00:39:53.860
Faculty (Olympus): Okay, so what they correspond to is that if a particular pair is chosen, what would

228
00:39:54.410 --> 00:39:57.929
Faculty (Olympus): The average gradient would have been in that case.

229
00:39:58.450 --> 00:40:03.010
Faculty (Olympus): So, these are the differentâ€¦ values.

230
00:40:04.790 --> 00:40:10.970
Faculty (Olympus): Okay? So, each of these values, each of theseâ€¦ Values in this matrix.

231
00:40:11.750 --> 00:40:15.870
Faculty (Olympus): correspond toâ€¦ GI plus GJ by 2.

232
00:40:16.220 --> 00:40:20.250
Faculty (Olympus): Okay, what is the firâ€¦ what isâ€¦ what was the value of G1 here?

233
00:40:20.460 --> 00:40:37.439
Faculty (Olympus): orâ€¦ and what was the value of G2 corresponding to this point, and the average of the 2 is what the element in the matrix shows. Okay? So, now you can see what G bar is now a random variable. This is my random variable. What are the values that G bar can take?

234
00:40:38.660 --> 00:40:52.530
Faculty (Olympus): So, G bar is, again, a discrete random variable. What are the values that it can take? What is its support? Its support isâ€¦ it can look atâ€¦ it can be minus 4, or minus 3.

235
00:40:52.700 --> 00:41:00.970
Faculty (Olympus): Minus 2, minus 1, 0, 1, Right? These are the values.

236
00:41:01.420 --> 00:41:03.330
Faculty (Olympus): That it can take.

237
00:41:04.820 --> 00:41:05.920
Faculty (Olympus): G-Bar.

238
00:41:06.290 --> 00:41:20.820
Faculty (Olympus): Okay, very good. Now, what is the PMF corresponding to this G-bar? So, I have to now figure out what is the probability that G-bar takes any of these values, right? Each of these values. So, again, see, in this particular case.

239
00:41:20.940 --> 00:41:30.590
Faculty (Olympus): G bar is minus 4 only in one location. It'll be minus 4 only if G1 is minus 4, and G2 is minus 4.

240
00:41:30.910 --> 00:41:44.559
Faculty (Olympus): Right? G1 is minus 4 with probability 1 by 4. G2 is minus 4, again, with probability 1 by 4, so the overall probability corresponding to G bar being minus 4 is 1 by 16.

241
00:41:46.050 --> 00:41:48.589
Faculty (Olympus): What about, minus 3?

242
00:41:49.010 --> 00:41:51.480
Faculty (Olympus): Minus 3 can either occur here.

243
00:41:51.730 --> 00:42:00.080
Faculty (Olympus): or here. So there are two different equally likely possibilities, where G bar can be minus 3, so this becomesâ€¦

244
00:42:00.450 --> 00:42:03.789
Faculty (Olympus): 2x16, What about minus 2?

245
00:42:04.250 --> 00:42:06.850
Faculty (Olympus): Minus 2 isâ€¦ here.

246
00:42:07.150 --> 00:42:12.460
Faculty (Olympus): It's here, it's hereâ€¦ That's it. So, 3 by 16.

247
00:42:13.660 --> 00:42:22.600
Faculty (Olympus): Similarly, minus 1, you can see, is in 4 positions, so it's going to beâ€¦ 4x16.

248
00:42:22.990 --> 00:42:27.110
Faculty (Olympus): 0 is in 3 positions, so again, 3 by 16.

249
00:42:27.250 --> 00:42:35.689
Faculty (Olympus): One isâ€¦ In one position, no. Two positions. Two positions, so it's 2x16.

250
00:42:35.760 --> 00:42:50.599
Faculty (Olympus): And 2, again, is in one position, so it's 1 by 16. So, a few things to notice here. So, firstly, if this is a valid PMF, the sum should be 1, so let's just confirm that. It's 1 plus 2, 3, plus 3, 6, 4, 10,

251
00:42:50.730 --> 00:42:59.490
Faculty (Olympus): plus 616, divided by 60. So it is indeed a valid PMF. The second thing to note is you can see that now you are more likely

252
00:42:59.570 --> 00:43:14.830
Faculty (Olympus): to take the values minus 2, minus 1, zeros. The values have centered around minus 2, minus 1, 0. It is not uniformly, equally likely to take all world values. The values are getting centered, or concentrated towards the center.

253
00:43:15.290 --> 00:43:28.740
Faculty (Olympus): Okay? Now, again, you can ask, now I have a G bar, I have a PMF corresponding to G bar, G-bar is a random variable indeed. What is the expected value of G-bar?

254
00:43:31.480 --> 00:43:34.339
Faculty (Olympus): Sorry, what is the expected value?

255
00:43:34.600 --> 00:43:36.360
Faculty (Olympus): of Gbar.

256
00:43:36.600 --> 00:43:41.160
Faculty (Olympus): Right? Again, recall that our full gradient was minus 1.

257
00:43:41.410 --> 00:43:44.309
Faculty (Olympus): We have decided to take two samples.

258
00:43:44.420 --> 00:43:51.350
Faculty (Olympus): Independent samples from these four, and we are just averaging the gradient corresponding to those two random samples.

259
00:43:51.450 --> 00:44:05.710
Faculty (Olympus): Okay? And now we are looking at the expected value of that average gradient, right? So again, how do we compute that? We are going to sum all of these up, which means you're going to do minus 4 times 1 by 16,

260
00:44:05.970 --> 00:44:09.110
Faculty (Olympus): Minus 3 times 2 by 16.

261
00:44:09.870 --> 00:44:17.810
Faculty (Olympus): Minus 2 times 3 by 16, minusâ€¦ 4x16.

262
00:44:18.100 --> 00:44:23.149
Faculty (Olympus): And then there is a plus 0 times 3 by 16.

263
00:44:23.910 --> 00:44:32.970
Faculty (Olympus): Plus 1 times 2 by 16, And then finally, plusâ€¦ 2 times 1 by 60.

264
00:44:33.440 --> 00:44:34.300
Faculty (Olympus): Okay?

265
00:44:34.720 --> 00:44:42.959
Faculty (Olympus): So, how much will this all be? So you do minus 4 minus 6, minus 4 minus 6, which is minus 10,

266
00:44:43.070 --> 00:44:46.490
Faculty (Olympus): minus Which is minus 16.

267
00:44:46.640 --> 00:44:50.699
Faculty (Olympus): minus 20, This is just 0.

268
00:44:51.070 --> 00:44:57.020
Faculty (Olympus): minus 18 minus 16. So you get minus 16 by 16, which is, again.

269
00:44:58.150 --> 00:45:01.550
Faculty (Olympus): minus 1, which is exactly G full.

270
00:45:03.170 --> 00:45:06.710
Faculty (Olympus): Okay? So, indeed, the expected value

271
00:45:07.390 --> 00:45:09.649
Faculty (Olympus): When you doâ€¦ when you take

272
00:45:09.890 --> 00:45:18.820
Faculty (Olympus): two random samples instead of just one single sample, you still get the inexpectation, you still see theâ€¦

273
00:45:19.500 --> 00:45:34.459
Faculty (Olympus): in expectation, you still match the full gradient, okay? So, as long asâ€¦ if you take any R independent samples with replacement from a data set, and you just compute the average of the R at random samples.

274
00:45:34.620 --> 00:45:47.500
Faculty (Olympus): in expectation, you will always match the full gradient over the entire dataset, okay? This is why people work with mini-batches, and it'sâ€¦ the algorithms still work, because

275
00:45:47.760 --> 00:45:50.410
Faculty (Olympus): Firstly, you cannot compute the full gradient.

276
00:45:50.560 --> 00:46:04.999
Faculty (Olympus): So you do random sampling, and while the gradient that you compute over the random sample is indeed a random quantity, and it does not exactly match the full gradient, it matches the full gradient, at least in expectation.

277
00:46:05.500 --> 00:46:13.320
Faculty (Olympus): Okay? So that's the idea, that this is one place where, expectation plays a key role,

278
00:46:13.460 --> 00:46:16.640
Faculty (Olympus): Inâ€¦ inâ€¦ in terms of algorithms that we use.

279
00:46:17.470 --> 00:46:19.270
Faculty (Olympus): Okay,

280
00:46:19.610 --> 00:46:29.369
Faculty (Olympus): Yeah, so, okay, Iâ€¦ this is what Iâ€¦ the example that I wanted to discuss. One last point before I take questions is

281
00:46:29.590 --> 00:46:35.090
Faculty (Olympus): This is something I want toâ€¦ want you to keep in mind, okay? When we took one sample.

282
00:46:35.690 --> 00:46:39.610
Faculty (Olympus): we got the expected value to be G full.

283
00:46:39.920 --> 00:46:48.790
Faculty (Olympus): When we took 2 samples, we again got the expected value to be G. Full. If I take 3 samples, I'll also get G full as the expectation.

284
00:46:49.000 --> 00:46:54.430
Faculty (Olympus): So, what is the point? I mean, why do I need to take more than one sample at all?

285
00:46:54.710 --> 00:47:13.410
Faculty (Olympus): Okay, why should I ever take more than one random sample? Okay, so we're going to discuss that in a little bit, but that is something I want you to keep in mind. In terms of expectation, whether you take one random sample, or you take two random samples with replacement, or you take three random samples with replacement, in terms of expectation, they are all the same.

286
00:47:13.940 --> 00:47:18.780
Faculty (Olympus): Okay? Okay, let's, let me take some questions. Yeah, Prachi?

287
00:47:20.490 --> 00:47:30.259
Lad Prachikumari Vijaykumar .: Sir, I want to know that, W double tail sign equal to W-tailed. Could you please, explain this one?

288
00:47:30.260 --> 00:47:36.160
Faculty (Olympus): So this is just, this is what is called the gradient descent algorithm.

289
00:47:36.650 --> 00:47:46.520
Faculty (Olympus): Okay, this is an algorithm which is used toâ€¦ this is an iterative algorithm which is used to find, essentially, the optimal value of W.

290
00:47:46.670 --> 00:47:57.659
Faculty (Olympus): And, this justâ€¦ it's an iterative algorithm. So you start with one estimate, W tilde, you evaluate the gradient, and then you move in a certain direction. You update your value of W, and you keep going on.

291
00:47:58.040 --> 00:48:11.559
Faculty (Olympus): Till, essentially, you know, your gradient becomes very small, or you have converged, you keep doing thisâ€¦ these steps. This is what is called a gradient descent algorithm. You will see this in one of your ML classes.

292
00:48:12.720 --> 00:48:13.730
Lad Prachikumari Vijaykumar .: Yes.

293
00:48:13.730 --> 00:48:14.729
Faculty (Olympus): So if you're not followingâ€¦

294
00:48:14.730 --> 00:48:18.339
Lad Prachikumari Vijaykumar .: Not divot by W star sign.

295
00:48:18.340 --> 00:48:29.339
Faculty (Olympus): So, W star, I was reserving that for, like, the optimal value. So, the hope is that as you keep doing these iterations, you will converge towards W star.

296
00:48:30.320 --> 00:48:31.450
Lad Prachikumari Vijaykumar .: Okay.

297
00:48:31.450 --> 00:48:32.020
Faculty (Olympus): Yeah.

298
00:48:32.820 --> 00:48:34.250
Lad Prachikumari Vijaykumar .: Okay, thank you, sir.

299
00:48:34.250 --> 00:48:34.750
Faculty (Olympus): Yeah.

300
00:48:35.130 --> 00:48:37.609
Faculty (Olympus): Swapnil?

301
00:48:39.300 --> 00:48:42.380
Swapnil Sankla .: Yes, sir, if you can scroll back to the mini batchâ€¦

302
00:48:42.380 --> 00:48:42.970
Faculty (Olympus): Yeah.

303
00:48:43.990 --> 00:48:51.460
Swapnil Sankla .: Yeah, here, though we are talking about the mini batch, but we ended up taking the G for all the 4 samples.

304
00:48:51.850 --> 00:48:58.669
Swapnil Sankla .: That we will not usually know if we are taking a mini-batch rate. So I did not follow,

305
00:48:58.670 --> 00:49:04.919
Faculty (Olympus): No, no, so, you were saying we wouldn't know the gradient,

306
00:49:05.480 --> 00:49:15.180
Swapnil Sankla .: No, no, my point is, when we are doing a mini-batch, we want the gradient for all theâ€¦ each and every value. However, in this formula, we ended up calculating minus.

307
00:49:15.180 --> 00:49:15.590
Faculty (Olympus): Hahaha.

308
00:49:16.000 --> 00:49:17.430
Swapnil Sankla .: Based on all four values.

309
00:49:17.430 --> 00:49:23.730
Faculty (Olympus): Okay, okay, so, this isâ€¦ thisâ€¦ this expected gradient is not something that is needed for the algorithm.

310
00:49:23.940 --> 00:49:31.590
Faculty (Olympus): The algorithm will just take the, the random quantity, which is either G or which is G1 plus G2 by 2.

311
00:49:31.720 --> 00:49:38.419
Faculty (Olympus): So, the way the algorithm works is you choose two random samples, compute the gradient only at those two.

312
00:49:38.550 --> 00:49:44.200
Faculty (Olympus): those two random samples. Onlyâ€¦ andâ€¦

313
00:49:44.380 --> 00:49:50.959
Faculty (Olympus): Average them out, and then update your estimate. Again, take two random data points.

314
00:49:54.600 --> 00:49:59.259
Faculty (Olympus): So, the algorithm doesn't require the computation of the expectation.

315
00:49:59.450 --> 00:50:00.480
Faculty (Olympus): So you all that weâ€¦

316
00:50:00.480 --> 00:50:01.510
Swapnil Sankla .: doing it, you are.

317
00:50:01.510 --> 00:50:08.579
Faculty (Olympus): Yeah, yeah, so we are just using it to illustrate why this works, or if you're tryingâ€¦ if you actually try and do the analysis

318
00:50:08.580 --> 00:50:23.850
Faculty (Olympus): of gradient descent and try to argue things like, you know, how much time will it take to converge, or will it converge to the true optimum value? Then you will use the fact that, in fact, in every step in expectation, I am moving in the right direction.

319
00:50:23.870 --> 00:50:24.700
Faculty (Olympus): Soâ€¦

320
00:50:24.910 --> 00:50:31.810
Faculty (Olympus): Indeed, the algorithm will converge to the right point. So this is only part of the analysis, it's not part of the algorithm.

321
00:50:31.810 --> 00:50:32.850
Swapnil Sankla .: About it. Thank you.

322
00:50:32.850 --> 00:50:35.619
Faculty (Olympus): Okay. Abhishek?

323
00:50:37.030 --> 00:50:37.710
Abhishek .: That isâ€¦

324
00:50:38.160 --> 00:50:38.770
Faculty (Olympus): Yeah.

325
00:50:38.970 --> 00:50:46.510
Abhishek .: approaching these algorithms or the process and the questions. Maybe if not relevant, then I can take it up at the end of the session.

326
00:50:46.510 --> 00:50:49.770
Faculty (Olympus): Yeah, sure, let's do that at the end. Sure. Rahul?

327
00:50:51.310 --> 00:50:54.900
Rahul Joshi .: So, can you go to the calculation of the gradient, formula?

328
00:50:55.690 --> 00:50:57.830
Faculty (Olympus): thisâ€¦

329
00:50:57.830 --> 00:51:02.309
Rahul Joshi .: meeting gap. Huh. Not this one, the original one, yeah.

330
00:51:02.840 --> 00:51:03.580
Rahul Joshi .: someâ€¦

331
00:51:04.270 --> 00:51:06.059
Faculty (Olympus): This is the original one.

332
00:51:07.560 --> 00:51:09.199
Faculty (Olympus): You mean this here?

333
00:51:10.930 --> 00:51:12.159
Rahul Joshi .: Yes, yes, yes.

334
00:51:12.160 --> 00:51:12.620
Faculty (Olympus): Soâ€¦

335
00:51:12.620 --> 00:51:25.210
Rahul Joshi .: So, ultimately, in the context of one point, which is, let's say, 1,0X and Y, gradient is the point where this formula will give the least value, right? Y1 minus

336
00:51:25.520 --> 00:51:27.810
Rahul Joshi .: WXI bracket square by 2, right?

337
00:51:28.630 --> 00:51:37.759
Faculty (Olympus): No, no, we are just taking theâ€¦ we are not equating this to 0 or anything, we're just computing the derivative and computing the value of the derivative.

338
00:51:39.900 --> 00:51:46.649
Rahul Joshi .: It means what exactly gradient indicates here? Let's say if the X is 1 and Y is 0, what exactly 2 indicates?

339
00:51:48.160 --> 00:51:52.730
Faculty (Olympus): All that indicates is, it's like theâ€¦

340
00:51:52.860 --> 00:52:07.529
Faculty (Olympus): you should think of that as, like, the slope of the loss function at that point, or what is, like, the degree of change of the loss function. If you move around the value 1, how much will the loss function change by?

341
00:52:07.950 --> 00:52:10.659
Faculty (Olympus): So that's what the gradient is supposed to indicate.

342
00:52:13.130 --> 00:52:16.800
Rahul Joshi .: But, sir, in the context of one point, we don't know the function, right?

343
00:52:17.040 --> 00:52:28.279
Faculty (Olympus): No, so that is what the loss function is, right? The loss function is defined for every data point, and then what you are trying to usually minimize is, like, the average of the loss across the entire dataset.

344
00:52:30.610 --> 00:52:40.869
Faculty (Olympus): So this would be, like, your overall loss function. There is a loss function defined for every data point, and then you're looking at the average loss across the four data points.

345
00:52:42.230 --> 00:52:44.330
Faculty (Olympus): Or across the entire dataset.

346
00:52:46.910 --> 00:52:51.050
Faculty (Olympus): So, what you are interested in is in this full gradient.

347
00:52:51.870 --> 00:52:59.630
Faculty (Olympus): So you compute the gradient value at everyâ€¦ at every data point, and then the average of that is what you're interested in.

348
00:52:59.740 --> 00:53:09.309
Faculty (Olympus): And if you actually use the full gradient, then you will, depending on what your loss function is, you will potentially converge towards the optimal value.

349
00:53:10.940 --> 00:53:24.769
Faculty (Olympus): But we don't want to find, or we cannot find that full gradient, because that is just computationally too intensive. So instead, we sample a few random data points, and only compute the average of the gradient on those data points.

350
00:53:27.870 --> 00:53:28.620
Faculty (Olympus): Okay?

351
00:53:29.370 --> 00:53:35.920
Rahul Joshi .: And we are validating that. Whether it is 1 point, or 2 point, or 4 point, the average holds good, right, every time.

352
00:53:35.920 --> 00:53:43.690
Faculty (Olympus): So we are saying that, okay, this is going to be some random quantity, but in expectation, at least, it is going to be exactly equal to G4.

353
00:53:47.360 --> 00:53:48.060
Faculty (Olympus): Okay?

354
00:53:48.530 --> 00:53:57.070
Rahul Joshi .: And here, so G, full means what exactly? Because it's a function, right? So, at a particular data point, there is a value of G, right? It is not, like, something generic G, right?

355
00:53:57.810 --> 00:54:02.900
Faculty (Olympus): Yeah, yeah, for every data point, there is a certain value, and G4 is just the average of those values.

356
00:54:04.050 --> 00:54:11.190
Faculty (Olympus): So here, the gradient is just a scalar, but in general, gradients would have been vectors, and you would have looked at the average vector.

357
00:54:12.880 --> 00:54:23.229
Rahul Joshi .: So, in the example, which you gave, like, let's say if it's the left-hand side is the amount of the effort you put, and Y is a score, then what exactly in that context, average G means?

358
00:54:23.630 --> 00:54:35.930
Faculty (Olympus): See, again, I mean, I don't want to actually, go into that direction, because that is not really the point of this course, right? You will see all of this in your, in one of these ML classes.

359
00:54:36.200 --> 00:54:48.589
Faculty (Olympus): So, perhaps just wait for that. All I wanted to say was that this G4 isâ€¦ or the gradient over the entire dataset is what one is usually interested in, but cannot compute.

360
00:54:48.630 --> 00:55:01.889
Faculty (Olympus): Instead, you use random sampling to compute an estimate of that GFUL, which matches G-Full in expectation. That's it. What the interpretation of GFOL is, why is it useful, all of that is actually

361
00:55:02.020 --> 00:55:05.560
Faculty (Olympus): Yeah, that will be the content of one of your ML courses.

362
00:55:07.870 --> 00:55:08.540
Faculty (Olympus): Okay.

363
00:55:08.910 --> 00:55:10.869
Faculty (Olympus): Okay, summer?

364
00:55:12.490 --> 00:55:19.450
Samar .: So, my question is around this gradient functionality, where you have defined this squared loss function. Yeah.

365
00:55:19.850 --> 00:55:25.659
Samar .: So is this the standard one, sir, or it's more, like, used for this particular example?

366
00:55:25.660 --> 00:55:32.529
Faculty (Olympus): No, squared loss is a very standard function, especially for linear regression. It's maybe the default loss function.

367
00:55:32.800 --> 00:55:37.469
Samar .: Okay, so whenever we have to find this gradient, we canâ€¦ Apply this one.

368
00:55:38.260 --> 00:55:44.470
Faculty (Olympus): Yeah, sure, yeah. There might be other loss functions as well that people use, but this is definitely one popular one.

369
00:55:45.310 --> 00:55:45.920
Samar .: Okay.

370
00:55:46.980 --> 00:55:49.809
Faculty (Olympus): Okay, yeah, Charles Ravi?

371
00:55:51.240 --> 00:55:59.080
Charles Ravi Kiran Mutsu .: Yeah, hi, Professor, good morning. So can you, explain a little bit about the loss function and,

372
00:55:59.080 --> 00:56:06.980
Faculty (Olympus): So, again, I don't want to go there. I can do that at the very end, but that is not the point of this, in the context of our course.

373
00:56:06.980 --> 00:56:07.710
Charles Ravi Kiran Mutsu .: Okay.

374
00:56:07.710 --> 00:56:10.540
Faculty (Olympus): Yeah, but weâ€¦ I'm happy to take that at the end if you want.

375
00:56:10.710 --> 00:56:11.650
Charles Ravi Kiran Mutsu .: No worries here. Thanks.

376
00:56:11.650 --> 00:56:16.929
Faculty (Olympus): Okay, sure. Okay, okay, let's move on. Soâ€¦

377
00:56:17.060 --> 00:56:27.789
Faculty (Olympus): So, yeah, main thing I want you to keep in mind is that, we were interested in this kind of average of values over an entire dataset.

378
00:56:28.400 --> 00:56:34.339
Faculty (Olympus): That would have been difficult to compute, so we decided to subsample a few values, and just compute

379
00:56:34.490 --> 00:56:36.700
Faculty (Olympus): Average of those random samples.

380
00:56:36.970 --> 00:56:50.530
Faculty (Olympus): We saw that whether you sample one data point, or you sample two data points and take the average, or you sample three data points and take the average, always in expectation, you are always equal to G4, okay?

381
00:56:51.780 --> 00:56:55.160
Faculty (Olympus): Okay, soâ€¦ With this, we willâ€¦

382
00:56:55.160 --> 00:57:03.299
Rahul Joshi .: Can I, can I, can I just ask one question? Can you, can you just, explain one data point, and it is equivalent to the JUFUL?

383
00:57:04.250 --> 00:57:10.690
Faculty (Olympus): Yeah, that's what this was, right? So, this is the gradient corresponding to the selected data point.

384
00:57:10.890 --> 00:57:15.380
Faculty (Olympus): This gradient can take 4 different values, each equally likely.

385
00:57:15.780 --> 00:57:20.089
Faculty (Olympus): And so the expected value just becomes 1 by 4 times

386
00:57:20.330 --> 00:57:23.139
Faculty (Olympus): the sum, which is exactly G full.

387
00:57:24.280 --> 00:57:26.249
Rahul Joshi .: Okay, got it, dear. Thank you, sir.

388
00:57:26.250 --> 00:57:26.820
Faculty (Olympus): Okay.

389
00:57:27.900 --> 00:57:31.539
Faculty (Olympus): Okay, so we are now going to talk about

390
00:57:31.820 --> 00:57:43.879
Faculty (Olympus): Another quantity, which is another function of the underlying distribution, which is also very useful and very widely used, which is the notion of variance.

391
00:57:44.240 --> 00:58:04.050
Faculty (Olympus): Okay? So, just like expectation had a certain operational meaning, right? Its operational meaning was that if you take many, many samples from the distribution, this is, like, the average value that you will get. Similarly, variance essentially is used to capture the notion of a spread

392
00:58:04.460 --> 00:58:05.840
Faculty (Olympus): offer distribution.

393
00:58:09.380 --> 00:58:18.390
Faculty (Olympus): Okay? So, the idea is, and this is spread of a distribution around It'sâ€¦ expectationâ€¦

394
00:58:18.750 --> 00:58:34.339
Faculty (Olympus): Or around what expectation is also sometimes called the mean. So, around its mean, or around its expectation. So, the idea is that if the variance is small, then you expect that when you take multiple samples from this distribution.

395
00:58:34.340 --> 00:58:39.119
Faculty (Olympus): The samples are more or less going to be very, very close to the expected value.

396
00:58:39.550 --> 00:58:43.889
Faculty (Olympus): Or very, very close to the expectation. But when the variance is large.

397
00:58:44.200 --> 00:58:55.739
Faculty (Olympus): then you expect that samples are going to be spread out, okay? Not all of them are going to be close to the expected value. They're going to be more spread out across a larger range.

398
00:58:55.960 --> 00:59:05.179
Faculty (Olympus): So that's what variance, is trying to encode. And, we'll come to the actual definition.

399
00:59:05.310 --> 00:59:10.280
Faculty (Olympus): So, we will often denote the variance of a random variable by var of x.

400
00:59:10.400 --> 00:59:14.250
Faculty (Olympus): And, this variance is always non-negative.

401
00:59:14.540 --> 00:59:20.700
Faculty (Olympus): And the square root of the variance of X is called the standard deviation.

402
00:59:22.130 --> 00:59:23.000
Faculty (Olympus): Okay?

403
00:59:23.230 --> 00:59:33.039
Faculty (Olympus): Now, the definition of variance, so if you have X as some random variable, then the variance of X is defined as

404
00:59:33.280 --> 00:59:38.799
Faculty (Olympus): the expected value, of X, minus mu Xâ€¦

405
00:59:39.040 --> 00:59:48.900
Faculty (Olympus): squared, where I'm going to use this mu X to just denote the expected value of X, okay? I justâ€¦ this is just for ease of notation, that's it.

406
00:59:49.320 --> 00:59:56.680
Faculty (Olympus): Okay? So variance is the expected value of X minus mu X whole squared.

407
00:59:58.310 --> 01:00:02.959
Faculty (Olympus): Okay, so you can see exactly what this is doing. So X minus mu X

408
01:00:03.220 --> 01:00:11.360
Faculty (Olympus): is like, or X minus mu X squared, you can think of as the squared Deviation.

409
01:00:12.080 --> 01:00:14.760
Faculty (Olympus): of X from the mean.

410
01:00:15.140 --> 01:00:21.390
Faculty (Olympus): Right? And then you are looking at the average of that value as you take more and more samples.

411
01:00:21.500 --> 01:00:27.210
Faculty (Olympus): Okay, so first thing to note is Theâ€¦ that the variance

412
01:00:27.840 --> 01:00:45.039
Faculty (Olympus): of X is definitely non-negative, right? You're taking the expected value of a square, squared, function, so clearly that is always going to be non-negative. X minus mu X squared is always non-negative, so even if you take the expectation, you're going to get something which is non-negative.

413
01:00:45.380 --> 01:00:51.970
Faculty (Olympus): The other thingâ€¦ To keep in mind is that the variance of X.

414
01:00:52.160 --> 01:00:58.539
Faculty (Olympus): Can also be written as the expected value of X squared minusâ€¦

415
01:00:58.940 --> 01:01:02.300
Faculty (Olympus): mu X squared, minus the square of the expectation.

416
01:01:02.940 --> 01:01:04.710
Faculty (Olympus): Okay? Soâ€¦

417
01:01:04.900 --> 01:01:13.879
Faculty (Olympus): I will maybeâ€¦ okay, I'll do a quick proof of this, but I won't go too much into detail. So, the variance, by definition.

418
01:01:14.170 --> 01:01:17.620
Faculty (Olympus): is X minus mu X full squared.

419
01:01:18.130 --> 01:01:25.269
Faculty (Olympus): Which isâ€¦ And now, if I open up this inside, if I expand that, I get X square.

420
01:01:25.990 --> 01:01:32.130
Faculty (Olympus): plus mu X squared minus 2 times X mu X.

421
01:01:32.820 --> 01:01:33.700
Faculty (Olympus): Okay?

422
01:01:33.800 --> 01:01:38.800
Faculty (Olympus): Now, the expected value of a sum,

423
01:01:38.850 --> 01:01:53.620
Faculty (Olympus): is, in fact, equal to sum of expectations. We will come to this a little later, maybe in the next class. We will talk about this in a little later. But in general, expectation is a linear operator, so the expected value of a sum of

424
01:01:53.620 --> 01:01:59.480
Faculty (Olympus): terms is the same as the sum of the individual expectation, okay? So this can be written as

425
01:01:59.670 --> 01:02:02.960
Faculty (Olympus): X summation of expected value of X squared.

426
01:02:03.230 --> 01:02:12.509
Faculty (Olympus): plusâ€¦ Expected value of mu X squared, minusâ€¦ 2 times expected value of

427
01:02:12.650 --> 01:02:20.239
Faculty (Olympus): X mu X, okay? Now, this is expected value of X squared, so this is what matches

428
01:02:20.540 --> 01:02:22.109
Faculty (Olympus): What we had before.

429
01:02:22.660 --> 01:02:29.860
Faculty (Olympus): Expected value of mu X squared. Mu X squared is just a constant, right? So there is no randomness there.

430
01:02:30.050 --> 01:02:37.159
Faculty (Olympus): So, expected value of mu X squared is just mu X squared. So, this becomes expected value

431
01:02:37.390 --> 01:02:39.369
Faculty (Olympus): of X squared.

432
01:02:40.620 --> 01:02:51.530
Faculty (Olympus): plus mu X squared minusâ€¦ again, here, the mu X is a constant, so that comes out. 2 mu X times expected value of X.

433
01:02:52.470 --> 01:03:01.630
Faculty (Olympus): But expected value of X was exactly mu X itself. So, you are going to get mu X squared minus 2 times mu X squared, so you get

434
01:03:01.910 --> 01:03:08.969
Faculty (Olympus): Overall, expected value of X squared minus mu X squared.

435
01:03:09.100 --> 01:03:15.489
Faculty (Olympus): Okay, so this is just an alternate way of writing the variance. The variance is defined as

436
01:03:16.500 --> 01:03:29.669
Faculty (Olympus): this formula, it's the expected value of the square deviation around the mean. When you expand it out, you can also write this as the expected value of X squared, which is just the expected value of a function of X.

437
01:03:30.030 --> 01:03:39.070
Faculty (Olympus): minus squared of the expectation. Thisâ€¦ this kind of an expression sometimes is useful when you're computing the variance, okay?

438
01:03:39.390 --> 01:03:46.699
Faculty (Olympus): Okay, so this is our definition, this is how we define variants. Let's maybe do a couple of examples.

439
01:03:47.840 --> 01:03:55.139
Faculty (Olympus): Soâ€¦ Example 1, let's look at X being a Bernoulli.

440
01:03:55.340 --> 01:04:04.969
Faculty (Olympus): P random variable, okay? So, to recall, this meansâ€¦ what this means is X is equal to 1 with probability P,

441
01:04:05.210 --> 01:04:10.370
Faculty (Olympus): And X is equal to 0 with probability 1 minus P.

442
01:04:10.540 --> 01:04:18.609
Faculty (Olympus): Right? We have already seen that the expected value of X in this case, which is mu X, is just going to be P.

443
01:04:19.080 --> 01:04:23.800
Faculty (Olympus): Right? Now, suppose I want to find the variance of X,

444
01:04:24.130 --> 01:04:31.730
Faculty (Olympus): I have saidâ€¦ we have shown this is equal to expected value of X squared minus mu X squared.

445
01:04:32.010 --> 01:04:40.269
Faculty (Olympus): which is going to be expected value of X squared minus mu X is P, so this is going to be P squared.

446
01:04:40.390 --> 01:04:47.430
Faculty (Olympus): So what I need to find is the expected value of X squared for a Bernoulli P random variable, okay? Soâ€¦

447
01:04:47.780 --> 01:04:52.109
Faculty (Olympus): Expected value of X squared for a Bernoulli P random variable.

448
01:04:52.500 --> 01:05:05.309
Faculty (Olympus): is going to be. So, recall that for any random variable, it is given byâ€¦ so X squared here, you can think of as your function G of X, right? So this is, in general, supposed to be

449
01:05:05.720 --> 01:05:08.869
Faculty (Olympus): You go over all values that it can take.

450
01:05:08.990 --> 01:05:14.740
Faculty (Olympus): And then the corresponding PMF values. And then you are summing overâ€¦ the support set.

451
01:05:15.120 --> 01:05:21.739
Faculty (Olympus): So in this case, the support set is only 1 and 0. So what is the value of the function when x is 1?

452
01:05:21.860 --> 01:05:25.710
Faculty (Olympus): X square is also 1, so that is going to be 1 times P,

453
01:05:26.280 --> 01:05:29.549
Faculty (Olympus): And what is going to be the value of the function when x is 0?

454
01:05:29.680 --> 01:05:34.209
Faculty (Olympus): Again, X squared is also going to be 0, so this is going to also be 0.

455
01:05:35.050 --> 01:05:41.300
Faculty (Olympus): So the expected value of X squared is also going to be P in this case.

456
01:05:42.050 --> 01:05:46.210
Faculty (Olympus): Okay, so now we canâ€¦ Plug that in here.

457
01:05:46.410 --> 01:05:52.329
Faculty (Olympus): And we get that the variance of a Bernoulli P random variable is going to beâ€¦

458
01:05:52.470 --> 01:06:00.350
Faculty (Olympus): P minus P squared, or in other words, P times 1 minus P. So, for anâ€¦ for

459
01:06:01.140 --> 01:06:05.650
Faculty (Olympus): a Bernoulli Pâ€¦ random variable X.

460
01:06:05.840 --> 01:06:10.299
Faculty (Olympus): Its variance is given by P times 1 minus P.

461
01:06:10.880 --> 01:06:16.530
Faculty (Olympus): Okay? Let's see how this looks, okay? So, how does this curve look like?

462
01:06:16.940 --> 01:06:21.600
Faculty (Olympus): So P timesâ€¦ this is, on the x-axis, I have P,

463
01:06:21.820 --> 01:06:28.309
Faculty (Olympus): On the y-axis, I have the variance of Bernoulli P, which is P times 1 minus P.

464
01:06:28.470 --> 01:06:32.330
Faculty (Olympus): So, at P equals 0, this quantity is going to be 0.

465
01:06:32.550 --> 01:06:39.799
Faculty (Olympus): At P equals 1, also this quantity is going to be 0, and in between, it'll have this form.

466
01:06:39.990 --> 01:06:43.019
Faculty (Olympus): Okay, it'll increase, and then go back to zero.

467
01:06:43.380 --> 01:06:47.420
Faculty (Olympus): And its peak is going to be at 1 half.

468
01:06:48.080 --> 01:06:51.209
Faculty (Olympus): Okay, that is where it is going to have its highest value.

469
01:06:51.770 --> 01:07:01.150
Faculty (Olympus): Now, let's think about what this means, right? So what does varianceâ€¦ what is variance supposed to indicate? Variance is supposed to indicate the spread of values.

470
01:07:01.400 --> 01:07:06.140
Faculty (Olympus): Okay? So if all the values are very, very similar to each other, the variance is going to be small.

471
01:07:06.480 --> 01:07:18.800
Faculty (Olympus): If the values are spread out, then the variance is going to be large. So think about the case where P is equal to 0, right? Suppose you take many samples from a Bernoulli zero random variable. What do you expect to see?

472
01:07:19.290 --> 01:07:27.310
Faculty (Olympus): you expect to see only zeros, right? If P is 0, the probability of a heads is zero. So, all the samples are going to be 0.

473
01:07:27.660 --> 01:07:29.939
Faculty (Olympus): Similarly, if P is equal to 1,

474
01:07:30.080 --> 01:07:44.439
Faculty (Olympus): All the samples are going to be 1s, right? So again, there is no variation. That's why the variance is 0 when P is either 0 or 1, or the variance is very, very small when P is very, very skewed towards 0 or 1.

475
01:07:45.510 --> 01:07:47.920
Faculty (Olympus): The value of the variance is highest.

476
01:07:48.050 --> 01:07:55.009
Faculty (Olympus): when you'reâ€¦ coin, or, you know, when you're Bernoulli, Pâ€¦ the p-value is, in fact, half.

477
01:07:55.440 --> 01:07:59.449
Faculty (Olympus): Which means you are equally likely to generate zeros or ones.

478
01:07:59.590 --> 01:08:02.309
Faculty (Olympus): That's when the variation is going to be maximum.

479
01:08:02.760 --> 01:08:08.010
Faculty (Olympus): That's why we are seeing the variance, we are seeing it to peak at 1 half.

480
01:08:08.650 --> 01:08:09.390
Faculty (Olympus): Okay?

481
01:08:09.590 --> 01:08:24.380
Faculty (Olympus): So, anyways, this is kind of the calculation, and one can calculate this for any kind of distribution for a Bernoulli P random variable. This is what the variance looks like. Let me do one more example, and then I'll take some questions.

482
01:08:24.680 --> 01:08:32.370
Faculty (Olympus): So, let's do another example. Let's say I take a uniform A, B,

483
01:08:32.569 --> 01:08:39.999
Faculty (Olympus): random variable, okay? So now this has a certainâ€¦ this is a continuous, random variable, so it has a density.

484
01:08:40.380 --> 01:08:41.720
Faculty (Olympus): And,

485
01:08:42.149 --> 01:08:54.930
Faculty (Olympus): its density is given by its 1 upon B minus A if X is between A and B, and it is 0 everywhere else.

486
01:08:55.500 --> 01:08:56.290
Faculty (Olympus): Right?

487
01:08:57.149 --> 01:09:04.569
Faculty (Olympus): So, again, I can, ask what is the variance of this random variable? Soâ€¦

488
01:09:05.310 --> 01:09:12.229
Faculty (Olympus): We have the formula. This is the expected value of U squared minus muâ€¦

489
01:09:13.109 --> 01:09:18.310
Faculty (Olympus): U square, or let me maybe just write this explicitly.

490
01:09:18.760 --> 01:09:23.060
Faculty (Olympus): minus square of the expected value of U.

491
01:09:23.330 --> 01:09:30.930
Faculty (Olympus): So, the expected value of U is something we had done last time. For a uniform random variable, the density looksâ€¦

492
01:09:31.180 --> 01:09:36.019
Faculty (Olympus): like this, right? The density is 0 everywhere, then it is 1 by B minus A,

493
01:09:36.340 --> 01:09:40.659
Faculty (Olympus): From A to B, so the average value is exactly the midpoint.

494
01:09:40.770 --> 01:09:44.710
Faculty (Olympus): Which isâ€¦ A plus B by 2.

495
01:09:45.090 --> 01:09:52.189
Faculty (Olympus): Okay, so I know what this quantity is going to be. This quantity is going to be A plus B by 2

496
01:09:52.330 --> 01:09:57.460
Faculty (Olympus): whole squared, right? So the second term is clear to me, now I just have to evaluate the first term.

497
01:09:58.130 --> 01:10:02.569
Faculty (Olympus): Okay? So again, the expected value of U square

498
01:10:03.870 --> 01:10:10.899
Faculty (Olympus): This is just a function of U, so this is just going to be the integral from A to B of

499
01:10:11.750 --> 01:10:17.210
Faculty (Olympus): X squared times

500
01:10:17.540 --> 01:10:30.680
Faculty (Olympus): the density of the uniform random variable times dx. The density is just 1 by B minus A. That becomes 1 by B minus A, the integral of X squared dx.

501
01:10:31.090 --> 01:10:35.840
Faculty (Olympus): The integral x squared is just X cubed by 3,

502
01:10:36.120 --> 01:10:44.720
Faculty (Olympus): We are going to evaluate that at B and A, and then you have a 1 by B minus A, okay? So this is going to be B cubed

503
01:10:44.850 --> 01:10:50.969
Faculty (Olympus): minus A cubedâ€¦ by 3 times B minus A.

504
01:10:51.560 --> 01:10:55.549
Faculty (Olympus): Okay? So this is what expected value of U squared is.

505
01:10:55.750 --> 01:11:04.639
Faculty (Olympus): I have that, I have the second term, which is the square of the expectation, I just have to subtract the two out. Okay, so I'm not going to do that math here.

506
01:11:04.750 --> 01:11:10.599
Faculty (Olympus): This, you can confirm the variance of U, It's just going to beâ€¦

507
01:11:11.360 --> 01:11:25.069
Faculty (Olympus): when you simplify all of that, you get B minus A square by 12. That is what the variance of a uniform AB random variable turns out to be. Okay? So again, there are a few things to note here.

508
01:11:25.280 --> 01:11:33.170
Faculty (Olympus): Supposeâ€¦ you take a uniform AB random variable, Okay?

509
01:11:33.380 --> 01:11:36.250
Faculty (Olympus): It is going to have a density which looks like this.

510
01:11:36.890 --> 01:11:48.829
Faculty (Olympus): Right? Suppose I take, and the expected value, like I said, is going to be A plus B by 2. That is what the expected value of this random variable is going to be. Let's take another random variable.

511
01:11:49.270 --> 01:12:03.409
Faculty (Olympus): who'sâ€¦ which is, again, uniform, but over a larger range, okay? Let's say this is A prime, this is B prime, and let's say this is such that the midpoint is still the same. A prime plus B prime by 2 is also

512
01:12:03.570 --> 01:12:08.430
Faculty (Olympus): equal to A plus B by 2. So the midpoint is the same, but the range is larger.

513
01:12:08.940 --> 01:12:09.740
Faculty (Olympus): Right?

514
01:12:09.850 --> 01:12:20.659
Faculty (Olympus): So now, the expected value of the uniform AB distribution is going to be the same as the expected value of the uniform A prime, B prime distribution.

515
01:12:20.820 --> 01:12:23.250
Faculty (Olympus): But which one will have higher variance?

516
01:12:23.440 --> 01:12:43.329
Faculty (Olympus): Alright? So again, the variance depends on the length of the interval, right? The variance depends on B minus A squared. So clearly, B prime minus A prime is larger, so its variance is also going to be larger. And this, you should also see geometrically by the fact that the spread of this distribution is definitely larger

517
01:12:43.330 --> 01:12:50.080
Faculty (Olympus): than the spread of the uniform AB distribution, so you expect the values to also be more spread out.

518
01:12:50.160 --> 01:12:58.129
Faculty (Olympus): in the green distribution than the blue one, right? So, the variance of a uniform random variable increases with the range

519
01:12:58.290 --> 01:13:01.259
Faculty (Olympus): Or the interval over which the values are spread.

520
01:13:02.060 --> 01:13:02.890
Faculty (Olympus): Okay?

521
01:13:03.060 --> 01:13:17.599
Faculty (Olympus): So, again, we have done this variance calculation for a few, examples here. One can compute, similarly, the variance for many different distributions. In particular, one that you should note is that for a Gaussian distribution.

522
01:13:17.680 --> 01:13:25.380
Faculty (Olympus): with parameters mu and sigma square. I don't know if I mentioned this last time, so if you have a Gaussian distribution.

523
01:13:26.000 --> 01:13:31.449
Faculty (Olympus): With parameters mu and sigma square, the expected value turns out to be mu.

524
01:13:31.980 --> 01:13:35.540
Faculty (Olympus): And the sigma square is the variance.

525
01:13:36.100 --> 01:13:37.390
Faculty (Olympus): the random variable.

526
01:13:39.210 --> 01:13:51.240
Faculty (Olympus): Okay, so itâ€¦ if you compute the variance of the density corresponding to such a Gaussian distribution, it will indeed turn out to be sigma squared. And the mean value turns out to be the first parameter, which is mu.

527
01:13:51.760 --> 01:13:52.560
Faculty (Olympus): Okay?

528
01:13:53.090 --> 01:13:57.230
Faculty (Olympus): Okay, so that's what I wanted to say about,

529
01:13:57.680 --> 01:14:04.479
Faculty (Olympus): about variants, I canâ€¦ I can take a couple of questions, and then maybe we'llâ€¦ we'll go back to our,

530
01:14:05.170 --> 01:14:10.499
Faculty (Olympus): are, our questionâ€¦ our, example of a mini batch.

531
01:14:10.910 --> 01:14:12.120
Faculty (Olympus): Okay, yeah, Rahul?

532
01:14:13.640 --> 01:14:22.149
Rahul Joshi .: So, sir, as I understood, variance is the expected value minus mean bracket square, right? That is the variance, right, in the context of that particular value, isn't it?

533
01:14:22.150 --> 01:14:25.889
Faculty (Olympus): So, the variance is, defined as this, yeah.

534
01:14:27.770 --> 01:14:29.730
Rahul Joshi .: Yeah, so X is the,

535
01:14:30.640 --> 01:14:31.660
Faculty (Olympus): X is the underwear.

536
01:14:31.660 --> 01:14:32.250
Rahul Joshi .: Nope.

537
01:14:32.590 --> 01:14:35.849
Rahul Joshi .: Random variable minus mean, bracket square, right?

538
01:14:35.850 --> 01:14:36.460
Faculty (Olympus): Yeah.

539
01:14:37.410 --> 01:14:41.649
Rahul Joshi .: So, if there are multiple random variables, then is it a summation of that?

540
01:14:41.650 --> 01:14:47.429
Faculty (Olympus): No, no. So, withâ€¦ we haven't yet talked about multiple random variables and how to define

541
01:14:47.590 --> 01:14:52.369
Faculty (Olympus): Things in that context, we will come to that,

542
01:14:52.370 --> 01:14:52.950
Rahul Joshi .: Oh, okay.

543
01:14:52.950 --> 01:14:58.030
Faculty (Olympus): Maybe in next class, we'll talk about random vectors and multiple random variables.

544
01:15:00.680 --> 01:15:14.120
Rahul Joshi .: No, sorry, my question wasâ€¦ I'm going to say X is the random variable from the context of this dataset. Let's say marks of a student, so every student will have a different mark, so each is a random variable.

545
01:15:14.120 --> 01:15:21.990
Rahul Joshi .: And then there is a mean. So, whenever we say X minus mean bracket squares for that particular student, that is the variance, right?

546
01:15:22.630 --> 01:15:25.640
Faculty (Olympus): No, no, the variance is over a distribution.

547
01:15:26.240 --> 01:15:30.890
Faculty (Olympus): Right? The variance is for a distribution, so if the marks are forâ€¦

548
01:15:31.330 --> 01:15:41.900
Faculty (Olympus): If theâ€¦ if, let's say, the marks of different students in a class, eachâ€¦ if each is being generated from someâ€¦ or you are modeling that to be generated from some distribution.

549
01:15:42.070 --> 01:15:57.640
Faculty (Olympus): then the variance is like the, is, like the spread across the values across different students. So suppose, let's say theâ€¦ I say that the marks, or theâ€¦ the score that

550
01:15:58.690 --> 01:16:08.000
Faculty (Olympus): score ofâ€¦ students, isâ€¦ behaves like, let's say, a Gaussian distribution with mean mu.

551
01:16:08.180 --> 01:16:12.070
Faculty (Olympus): value sigma squared. Oh, let's, in fact, give them some values. So, meanâ€¦

552
01:16:13.530 --> 01:16:19.949
Faculty (Olympus): 10 and sigma squared, let's say, being 1. What this is saying is that different students

553
01:16:20.090 --> 01:16:22.430
Faculty (Olympus): Okay, different students. So, student 1,

554
01:16:22.670 --> 01:16:29.740
Faculty (Olympus): will get one sample from this distribution, so maybe they get the value 11. Student 2 might get the valueâ€¦

555
01:16:29.880 --> 01:16:35.690
Faculty (Olympus): 12. Student 3 might get 9, student 4 might get 15, and so on.

556
01:16:36.380 --> 01:16:43.769
Faculty (Olympus): Okay? If I take the average of these values across many, many, many students, then that average will be close to 10.

557
01:16:44.700 --> 01:16:45.240
Rahul Joshi .: Yep.

558
01:16:45.630 --> 01:16:51.490
Faculty (Olympus): And if I compute the sum of Xi minus that average.

559
01:16:51.610 --> 01:16:55.939
Faculty (Olympus): Okay? Whatever that average, so in the average in this case is, like, 10.

560
01:16:56.920 --> 01:17:02.590
Faculty (Olympus): squared, and then I look at the average value, which is, let's say, across whatever N students.

561
01:17:02.800 --> 01:17:06.039
Faculty (Olympus): Then this will be close to the variance, which is 1.

562
01:17:08.070 --> 01:17:14.369
Faculty (Olympus): So this is, like, the average deviation squared, average deviation from the mean squared.

563
01:17:15.340 --> 01:17:22.809
Rahul Joshi .: Yeah, so whenever we say variance, is it variance in the context of one student, or it is always referred as the average variance?

564
01:17:22.810 --> 01:17:34.169
Faculty (Olympus): This isâ€¦ so average variance is always for a distribution. So, I mean, for a particular student, I don't know, there isâ€¦ I mean, if you're looking at a data set, then the variance is across that data set.

565
01:17:36.650 --> 01:17:45.629
Rahul Joshi .: So here, the average of the variance means XI minus mean bracket square divided by 4 in this case. That is the variance, right, for thisâ€¦

566
01:17:45.630 --> 01:17:47.319
Faculty (Olympus): It's like the empirical variance.

567
01:17:48.150 --> 01:17:48.670
Rahul Joshi .: Correct, okay.

568
01:17:48.670 --> 01:17:56.789
Faculty (Olympus): Yeah, I mean, there is no notion of a data set as such, but if you're thinking about the empirical meaning of this quantity, then that is what it would be.

569
01:17:58.070 --> 01:18:02.760
Faculty (Olympus): Right? Because there has to be some notion of a mean. With one student, there is no notion of a mean.

570
01:18:03.550 --> 01:18:11.249
Faculty (Olympus): It could be if there is one student, and that student is taking multiple tests, and maybe across tests, you can talk about variance.

571
01:18:13.130 --> 01:18:14.519
Faculty (Olympus): Right? And so on.

572
01:18:14.830 --> 01:18:15.730
Faculty (Olympus): Okay?

573
01:18:16.060 --> 01:18:18.020
Faculty (Olympus): Yeah, Abhineet?

574
01:18:18.450 --> 01:18:22.619
Abhineet Bansal: So, can you scroll back to the first example, where you're talking about the Bernali randomly.

575
01:18:22.620 --> 01:18:23.889
Faculty (Olympus): Yeah, yeah. Yeah.

576
01:18:23.890 --> 01:18:33.319
Abhineet Bansal: Can you help me with this calculation of how, expectation of X squared, summation of GK and PXK came out to be 1 into P plus 0?

577
01:18:33.630 --> 01:18:49.030
Faculty (Olympus): Yeah, yeah, so here, there are only two values, right? So, you can think of this as, so the first value is, is, X equals 1, so you have one square.

578
01:18:49.210 --> 01:18:50.730
Faculty (Olympus): That is G of X.

579
01:18:51.120 --> 01:18:53.780
Faculty (Olympus): Right? When Xâ€¦ when K is 1,

580
01:18:54.080 --> 01:18:56.839
Faculty (Olympus): then G of K is 1 squared.

581
01:18:57.530 --> 01:18:59.170
Faculty (Olympus): Is that okay?

582
01:18:59.770 --> 01:19:01.220
Abhineet Bansal: Also, I'm getting that.

583
01:19:01.220 --> 01:19:05.760
Faculty (Olympus): Yeah, so, I mean, we are calculating the expected value of X squared, right?

584
01:19:06.770 --> 01:19:12.169
Faculty (Olympus): let's say X takes the value K, then K square is 1, 1 squared.

585
01:19:12.570 --> 01:19:13.240
Abhineet Bansal: Okay.

586
01:19:13.370 --> 01:19:17.629
Faculty (Olympus): So 1 square isâ€¦ times the probability of that happening, which is P.

587
01:19:17.910 --> 01:19:22.370
Faculty (Olympus): The probability that associated with K equals 1 is exactly P.

588
01:19:24.350 --> 01:19:25.620
Abhineet Bansal: Andâ€¦ and the Knicks?

589
01:19:25.620 --> 01:19:30.620
Faculty (Olympus): The next one is, okay, the value is 0 squared times 1 minus p.

590
01:19:33.210 --> 01:19:33.820
Faculty (Olympus): Right?

591
01:19:33.820 --> 01:19:36.540
Abhineet Bansal: k value coming out to be P, sir? That is what is confusing.

592
01:19:36.540 --> 01:19:42.890
Faculty (Olympus): No, no, this PXK. So, PXK, is the probability, that is theâ€¦ our PMF, right?

593
01:19:42.890 --> 01:19:43.460
Abhineet Bansal: Yes.

594
01:19:43.460 --> 01:19:51.269
Faculty (Olympus): So, K can either be 0 or 1, so we are asking, what is the probability that X takes the value 1? It is by definition P.

595
01:19:51.560 --> 01:19:56.180
Faculty (Olympus): Yes. Similarly, what is the probability that X takes the value 0? It is 1 minus P.

596
01:19:57.880 --> 01:19:58.710
Abhineet Bansal: Okay, okay.

597
01:19:58.710 --> 01:20:03.690
Faculty (Olympus): We are taking k squared times the probability of X taking the value 1,

598
01:20:03.790 --> 01:20:08.670
Faculty (Olympus): plus 0 square times the value probability that X takes the value 0.

599
01:20:09.460 --> 01:20:19.549
Abhineet Bansal: Got it. And so, from a very exam point of view, are we supposed to learn the value of what variance of X is, or are we expected to derive this calculation of

600
01:20:19.900 --> 01:20:22.779
Abhineet Bansal: that the variance of X is P into 1 minus P.

601
01:20:24.290 --> 01:20:42.099
Faculty (Olympus): I mean, for distributions which are common, you know, we will usually provide, this thing, but if I want you to, kind of evaluate the valueâ€¦ so it depends, I mean, if the question wantsâ€¦ needs you to evaluate the variance of a certain distribution, then that is what you will be asked.

602
01:20:43.290 --> 01:20:55.399
Faculty (Olympus): But if you're asking me, yeah, do I have to remember the variance of all of these distributions, then no, I think, yeah, usually we'll give you a sheet which will have variance. If we require you to directly use the variance somewhere.

603
01:20:55.590 --> 01:21:03.360
Faculty (Olympus): then maybe we'll provide that in the sheet. You don't have to remember everything, but these are some things that you should know how to derive.

604
01:21:03.700 --> 01:21:10.399
Faculty (Olympus): Because, yeah, I mean, there might be a question which is about deriving the variance of a certain distribution, you should know how to do that.

605
01:21:11.200 --> 01:21:22.799
Abhineet Bansal: And in the second example, sir, where you've calculated that, can you scroll down, sir? Mu of u. It was actually where you substituted, this expected value of expected square of U.

606
01:21:23.040 --> 01:21:28.500
Abhineet Bansal: How did youâ€¦ how did you replace that with, square of mean.

607
01:21:29.020 --> 01:21:31.970
Abhineet Bansal: Isn't that supposed to be mu square, mu U square?

608
01:21:32.730 --> 01:21:37.519
Faculty (Olympus): No, no, this isâ€¦ thisâ€¦ this quantity is exactly square of the expected value.

609
01:21:40.320 --> 01:21:45.659
Faculty (Olympus): So the expected value is A plus B by 2. This is exactly the square of the expected value.

610
01:21:47.770 --> 01:21:49.460
Faculty (Olympus): Which is A plus B by 2.

611
01:21:49.920 --> 01:21:53.120
Abhineet Bansal: Isn'tâ€¦ in the variance formula, shouldn't it be the square of the mean?

612
01:21:54.070 --> 01:21:57.170
Faculty (Olympus): It is the square of the mean. A plus B by 2 is square, yeah.

613
01:21:57.170 --> 01:21:58.810
Abhineet Bansal: Okay, okay, got it back. Thanks.

614
01:21:58.810 --> 01:22:00.340
Faculty (Olympus): Okay. Anâ€¦

615
01:22:01.320 --> 01:22:06.549
Ann G. .: Sir, do open-loop distributions doâ€¦ are they expected to have variance?

616
01:22:07.200 --> 01:22:08.150
Ann G. .: What do you mean?

617
01:22:08.150 --> 01:22:09.300
Faculty (Olympus): by open.

618
01:22:09.300 --> 01:22:12.070
Ann G. .: Something like, exponential distribution.

619
01:22:12.330 --> 01:22:26.760
Faculty (Olympus): Yeah, yeah, an exponential distribution also has a variance, soâ€¦ For an exponential distribution, soâ€¦

620
01:22:29.420 --> 01:22:41.360
Faculty (Olympus): Yeah, I'm trying to recall if it is, 1 by lambda or 1 by lambda square. Okay, yeah, so I won't say what it is, but this is something, yeah, maybe this is something for you guys to work out.

621
01:22:41.480 --> 01:22:47.909
Faculty (Olympus): It does have a varâ€¦ it does have a variance. I think it is either 1 by lambda or 1 by lambda square, I don't remember now.

622
01:22:48.270 --> 01:22:50.169
Faculty (Olympus): But it does have a bit.

623
01:22:50.170 --> 01:23:00.860
Ann G. .: I'm more curious about how it looks. Like, you illustrated how it looks for uniform distribution in the graph, the variance. I'm just curious when the distribution is endless, how would it look in.

624
01:23:00.860 --> 01:23:15.220
Faculty (Olympus): Yeah, yeah, so, again, so I don't remember whether this is 1 by lambda or 1 by lambda square. In either case, the variance is someâ€¦ you can see that it is inversely proportional

625
01:23:15.380 --> 01:23:18.549
Faculty (Olympus): 2, lambda, which means that the variance

626
01:23:19.460 --> 01:23:22.529
Faculty (Olympus): goes down as lambda goes up.

627
01:23:22.690 --> 01:23:29.290
Faculty (Olympus): Okay? And the reason for that, again, so if you take, for example, the exponential distribution.

628
01:23:29.490 --> 01:23:42.559
Faculty (Olympus): Right? The density looks like lambda times e raised to minus lambda X. Okay? So suppose you take, if you take a small lambda, let's sayâ€¦ let me say lambda equals 1, maybe.

629
01:23:43.310 --> 01:23:48.630
Faculty (Olympus): Okay, this isâ€¦ maybe the density will look something like this. I'm plotting the density

630
01:23:48.780 --> 01:23:52.969
Faculty (Olympus): of an exponential random variable with parameter lambda, okay?

631
01:23:53.230 --> 01:23:56.440
Faculty (Olympus): On the other hand, if you take lambda to be larger.

632
01:23:56.660 --> 01:24:00.979
Faculty (Olympus): Then the density will look maybe something like this. It willâ€¦

633
01:24:03.200 --> 01:24:06.979
Faculty (Olympus): So, if you takeâ€¦ this is corresponding to, let's say, lambda equals 2.

634
01:24:07.670 --> 01:24:19.589
Faculty (Olympus): Okay? Theâ€¦ the decay is much, much sharper in density when lambda is larger. This E raised to minus lambda X decreases very, very quickly if your lambda value is large.

635
01:24:19.950 --> 01:24:26.589
Faculty (Olympus): So what happens is, youâ€¦ when your lambda is large, most of your values are going to get concentrated

636
01:24:26.730 --> 01:24:37.249
Faculty (Olympus): Here, towards the smaller side. Your spread is going to become smaller. The density is, of course, never going to be zero, it's always going to be something positive, but because

637
01:24:37.430 --> 01:24:42.930
Faculty (Olympus): It decays so rapidly, the chance of you getting a high value becomes very, very small.

638
01:24:43.640 --> 01:24:59.490
Faculty (Olympus): So, in the case where lambda is slightly larger, there isâ€¦ the spread is larger, because the density does not decay as quickly, but when lambda is large, the spread is becomeâ€¦ the spread becomes much, much smaller, because the density just decays very, very rapidly.

639
01:25:00.520 --> 01:25:03.930
Ann G. .: Doesn't variants take all the data points in the sample?

640
01:25:04.260 --> 01:25:11.600
Faculty (Olympus): Yeah, yeah, so everything willâ€¦ willâ€¦ you're right, it'llâ€¦ everything will be involved, so if I have to compute this variance.

641
01:25:12.050 --> 01:25:15.069
Faculty (Olympus): Of this, it will indeed beâ€¦

642
01:25:15.520 --> 01:25:30.959
Faculty (Olympus): theâ€¦ so you will have to look atâ€¦ so we do X minus mean squared, right? So mean of aâ€¦ of aâ€¦ an exponential random variable is 1 by lambda, so you will have something like this, times the density.

643
01:25:31.050 --> 01:25:46.259
Faculty (Olympus): which is lambda ease to minus lambda X DX. Okay? So you are right that you will now take this integral, the variance, by definition, is this integral, okay? It is the expected value of X minus mu X whole square.

644
01:25:46.300 --> 01:25:52.170
Faculty (Olympus): This quantity is exactly your mu X. So we are taking the expected value of this function.

645
01:25:52.250 --> 01:26:08.640
Faculty (Olympus): Right? So that is the function, this is your density, and then you are integrating thisâ€¦ this product, right? So, you are, indeed, you are taking 0 to infinity, so thisâ€¦ this quantity is indeed going to become larger and larger as x becomes larger.

646
01:26:08.790 --> 01:26:14.679
Faculty (Olympus): But see that the corresponding density goes down even faster. It goes down exponentially fast.

647
01:26:15.180 --> 01:26:18.329
Faculty (Olympus): So, the first term is increasing linearly.

648
01:26:18.670 --> 01:26:21.330
Faculty (Olympus): But the second term is decreasing exponentially.

649
01:26:21.570 --> 01:26:28.149
Faculty (Olympus): So overall, the smaller values are what are going to contribute more. That's why the integral becomes finite.

650
01:26:29.360 --> 01:26:30.380
Ann G. .: Okay, makes sense.

651
01:26:30.380 --> 01:26:37.750
Faculty (Olympus): Yeah, so you have an increasing X minus mu X, but you have a rapidly decreasing exponential function that it is multiplying.

652
01:26:39.240 --> 01:26:41.369
Faculty (Olympus): So the overall thing becomes finite.

653
01:26:41.610 --> 01:26:42.670
Ann G. .: Yeah, thank you, sir.

654
01:26:42.670 --> 01:26:43.460
Faculty (Olympus): Okay?

655
01:26:43.860 --> 01:26:45.230
Faculty (Olympus): Tushar?

656
01:26:45.730 --> 01:26:46.759
Tushar Sachdev .: Good afternoon, sir.

657
01:26:46.760 --> 01:26:47.370
Faculty (Olympus): Yeah.

658
01:26:47.370 --> 01:27:03.120
Tushar Sachdev .: Sir, if variance is measured in squared units, how does it affect interpretability compared to standard deviation? And, also one more follow-up. When is variance mathematically preferred over standard deviation?

659
01:27:04.390 --> 01:27:15.179
Faculty (Olympus): I mean, variance and standard deviation are very much, tied together. One is just the square root of the other. Like you said, the variance isâ€¦ soâ€¦

660
01:27:15.480 --> 01:27:26.709
Faculty (Olympus): the varianceâ€¦ empirically, if I'm thinking about a dataset and what the empirical variance would be, it'll be something like this, right? So, like you said, it's like the squaredâ€¦

661
01:27:26.860 --> 01:27:35.729
Faculty (Olympus): the average of the squared deviation. So, essentially, if I have to find, okay, I want to say what values of X are likely.

662
01:27:35.960 --> 01:27:40.300
Faculty (Olympus): Right? If the varianceâ€¦ so if I want to kind ofâ€¦

663
01:27:40.410 --> 01:27:51.659
Faculty (Olympus): think about deviation in terms of X, then I will think about deviation as, like, you know, X will maybe lieâ€¦ most of the X will lie between

664
01:27:51.980 --> 01:27:58.150
Faculty (Olympus): The mean value minus some multiple of the standard deviation.

665
01:27:59.150 --> 01:28:06.749
Faculty (Olympus): and the mean value plus some multiple of the standard deviation. That is how I want to think about things. If myâ€¦

666
01:28:06.750 --> 01:28:07.200
Tushar Sachdev .: Lisa.

667
01:28:07.200 --> 01:28:20.509
Faculty (Olympus): If, you know, I was trying to come up with a range, then I would want to do something in terms of standard deviation, because that is whatâ€¦ where X plays a role. Variance by itself is things in terms of X squared.

668
01:28:20.940 --> 01:28:21.770
Tushar Sachdev .: Okay, sir.

669
01:28:21.770 --> 01:28:22.310
Faculty (Olympus): Yeah.

670
01:28:22.320 --> 01:28:23.389
Tushar Sachdev .: Thank you, sir.

671
01:28:23.390 --> 01:28:24.040
Faculty (Olympus): Okay?

672
01:28:24.250 --> 01:28:27.160
Faculty (Olympus): Yeah, Abhishek Agarwal?

673
01:28:27.620 --> 01:28:45.350
Abhishek Agrawal .: Yeah, hi, sir. So, I was just looking at this Bernoulli, distribution, the variance calculation. So, suppose, there's a fairâ€¦ so, yeah, at this graph. So, we are saying, like, when the probability is half, then the variance will be maximum. Yeah.

674
01:28:45.590 --> 01:28:48.589
Abhishek Agrawal .: So, that means, like, a fair coin will haveâ€¦

675
01:28:48.940 --> 01:28:58.390
Abhishek Agrawal .: the, outcomes which are more varied, outcomes. And, if it is a biased coin, then the outcomes will be, like.

676
01:28:58.450 --> 01:29:11.540
Abhishek Agrawal .: Less variance. Yeah, less variance. So, does it, like, say, like, about the fairness of the, system, which is, like, we are, the variance indicates, kind of, a fairness of the, system we are, looking at?

677
01:29:11.850 --> 01:29:12.480
Abhishek Agrawal .: Allâ€¦

678
01:29:12.480 --> 01:29:12.860
Faculty (Olympus): the fact.

679
01:29:12.860 --> 01:29:13.600
Abhishek Agrawal .: factors.

680
01:29:13.890 --> 01:29:20.490
Faculty (Olympus): Yeah, so, I mean, the variance by itself is only talking about variability in the values, right? The spread of the values.

681
01:29:20.600 --> 01:29:30.450
Faculty (Olympus): We mightâ€¦ in this case, because, yeah, we are talking about these two possible values, and maybe, I mean, yeah, whether you call it fair or not.

682
01:29:30.670 --> 01:29:32.430
Faculty (Olympus): Depends on the context.

683
01:29:32.600 --> 01:29:50.150
Faculty (Olympus): But variance by itself is just encoding variability in the values. If the variability is small, the variance is going to be small. If the variability is large, right, meaning things essentially areâ€¦ look more random, then the variance is going to be large.

684
01:29:50.660 --> 01:29:56.819
Abhishek Agrawal .: Okay, so, yeah, in case of, like, a biased coin, like, there isâ€¦ since theâ€¦ suppose the weight, one side is more heavy.

685
01:29:56.820 --> 01:29:57.190
Faculty (Olympus): Yeah.

686
01:29:57.190 --> 01:30:05.030
Abhishek Agrawal .: So that's why it'sâ€¦ so, yeah, we can just, like, infer something like that. Some factor is, like, moving the values towards one side.

687
01:30:05.030 --> 01:30:08.470
Faculty (Olympus): One side, yeah, you have a skewed distribution.

688
01:30:08.780 --> 01:30:09.740
Abhishek Agrawal .: Thank you.

689
01:30:09.740 --> 01:30:12.940
Faculty (Olympus): Okay. Yeah, Abhishek Raghuvanshi?

690
01:30:16.210 --> 01:30:29.280
Abhishek Raghuvanshi .: Yeah, Professor, so in the earlier example of that mini-batch we were talking, so it doesâ€¦ the same thing will hold true in case we even do any kindâ€¦ other kind of sampling.

691
01:30:29.280 --> 01:30:32.050
Faculty (Olympus): I'll come to that mini-batch example in just a second.

692
01:30:32.310 --> 01:30:32.840
Abhishek Raghuvanshi .: Okay.

693
01:30:33.030 --> 01:30:33.530
Faculty (Olympus): Yeah.

694
01:30:35.290 --> 01:30:38.029
Faculty (Olympus): Okay, Rahul, do you still have a question?

695
01:30:38.030 --> 01:30:54.950
Rahul Joshi .: Just one question, sir. So, what we understood is that the variance is individual value minus mean bracket square and average of that. If you can go at the bottom of your sheet, are you multiplying it by the probability as well, in that probability of occurrence as well?

696
01:30:55.940 --> 01:30:56.970
Faculty (Olympus): It's good.

697
01:30:56.970 --> 01:31:02.040
Rahul Joshi .: at the bottom of the, I think, at the last, like, very bottom of theâ€¦

698
01:31:03.270 --> 01:31:03.910
Faculty (Olympus): thisâ€¦

699
01:31:03.910 --> 01:31:08.760
Rahul Joshi .: Yeah, so this isâ€¦ yeah, this is the probability, right? Lambda i a res to powerâ€¦

700
01:31:08.760 --> 01:31:10.270
Faculty (Olympus): That is the density.

701
01:31:11.790 --> 01:31:15.659
Rahul Joshi .: Yeah, so why we are multiplying by density, you have to just checkâ€¦

702
01:31:16.150 --> 01:31:22.760
Faculty (Olympus): No, so Iâ€¦ variance is what? Variance of X is the expected value ofâ€¦

703
01:31:23.100 --> 01:31:26.420
Faculty (Olympus): X minus mu X squared, right?

704
01:31:27.850 --> 01:31:31.160
Faculty (Olympus): So I can think of this as a function of X,

705
01:31:32.640 --> 01:31:34.630
Faculty (Olympus): Right? It's just a function of X.

706
01:31:35.460 --> 01:31:36.030
Rahul Joshi .: Yep.

707
01:31:36.200 --> 01:31:41.609
Faculty (Olympus): For any function of X, we have said that if it's a continuous function, it'sâ€¦

708
01:31:41.910 --> 01:31:46.379
Faculty (Olympus): Average value is just G of X times the density.

709
01:31:46.750 --> 01:31:48.130
Faculty (Olympus): times DX.

710
01:31:49.200 --> 01:31:50.040
Faculty (Olympus): Right?

711
01:31:50.570 --> 01:31:59.650
Faculty (Olympus): So that is exactly what this is. I am replacing the function is exactly x minus mu X squared, so this isâ€¦

712
01:31:59.850 --> 01:32:05.870
Faculty (Olympus): X minus mu X Squared, times whatever the density is.

713
01:32:06.920 --> 01:32:07.950
Faculty (Olympus): DX.

714
01:32:09.180 --> 01:32:12.470
Faculty (Olympus): So in this particular case, for the case of an exponential.

715
01:32:12.690 --> 01:32:26.300
Faculty (Olympus): this wasâ€¦ because mu X is 1 by lambda, the function becomes X minus 1 by lambda squared. The density is lambda times e raised to minus lambda X from 0 to infinity, so that's what we are integrating.

716
01:32:29.280 --> 01:32:47.479
Rahul Joshi .: Sorry, sir, just one question. So, in the, in the first part, where you mentioned expected value of X minus mu X bracket square, is it, the expected value of X has to be calculated first, and then individual value has to be, deducted from mean and then bracket square, right? Is it, like, e of x?

717
01:32:47.560 --> 01:33:03.930
Faculty (Olympus): No, it is expected value of this whole function, x minus mu X square. We just said that this variance can also be written as expected value of X squared minus mu X squared. Both of these are equivalent definitions of variance.

718
01:33:05.280 --> 01:33:09.780
Faculty (Olympus): They're both the same quantities. So if you evaluate, this.

719
01:33:10.190 --> 01:33:13.869
Faculty (Olympus): Or you evaluate this, you're going to get the same answer.

720
01:33:15.150 --> 01:33:19.840
Rahul Joshi .: So, so here you are calculating expected value of variance, not expected value of X, right?

721
01:33:21.780 --> 01:33:30.850
Faculty (Olympus): No, so maybe, again, let's take this at the end. I don't think, yeah, I don't think I'm getting what your exact question is. Let's maybe take it at the end.

722
01:33:31.470 --> 01:33:32.020
Faculty (Olympus): Okay? Okay.

723
01:33:32.020 --> 01:33:32.720
Rahul Joshi .: It finds it, yeah.

724
01:33:32.720 --> 01:33:38.950
Faculty (Olympus): Okay, alright, so let me come back to, the minibatch example.

725
01:33:42.070 --> 01:33:46.000
Faculty (Olympus): So, if you recall, we had these four

726
01:33:46.530 --> 01:33:49.530
Faculty (Olympus): gradient values, right? We had someâ€¦

727
01:34:01.020 --> 01:34:12.530
Faculty (Olympus): So, we had some Xi, some Yi, and then we had these 4 gradient values, which, if I remember correctly, were 2, minus 2, 0, and minus 4, right? And then we wereâ€¦

728
01:34:12.710 --> 01:34:17.820
Faculty (Olympus): We sampled, first we did one sample, One random sample.

729
01:34:19.780 --> 01:34:22.949
Faculty (Olympus): And then we didâ€¦ we'llâ€¦ we got oneâ€¦

730
01:34:23.160 --> 01:34:27.020
Faculty (Olympus): G-value, we saw that the expected G-value

731
01:34:27.310 --> 01:34:36.039
Faculty (Olympus): was indeed equal to G full, okay? So this is what the expected G value is. Whatâ€¦ what is the variance of this G, okay?

732
01:34:36.180 --> 01:34:39.910
Faculty (Olympus): What is the variance corresponding to this random G?

733
01:34:40.400 --> 01:34:57.549
Faculty (Olympus): Okay? What would that variance tell me? That would tell me that, okay, in expectation, if I take the, you know, take this random gradient many, many times, in expectation, I'm actually going to be close to the full gradient. But how much variation will I see? Will G keep changing a lot?

734
01:34:57.630 --> 01:35:15.429
Faculty (Olympus): Or will G be very, very close to G full? Almost always, right? So that is what the variance should tell me. So if I take one random sample, and I ask what is the variance of G, again, this I can write as the expected value of G squared minus

735
01:35:15.590 --> 01:35:17.589
Faculty (Olympus): Square of the expected value.

736
01:35:18.740 --> 01:35:35.270
Faculty (Olympus): Right? Again, G full was minus 1, so I know that the square of the expected value is exactly 1. I just have to compute the expected value of G squared. So what is the expected value of G squared in this case? Right? If you take one sample. So.

737
01:35:35.740 --> 01:35:49.890
Faculty (Olympus): Recall that G takes values which are 2 Minus 2, 0â€¦ minus 4â€¦ eachâ€¦ With probability 1 by 4.

738
01:35:50.530 --> 01:35:56.500
Faculty (Olympus): So, the expected valueâ€¦ ofâ€¦ G squared.

739
01:35:56.660 --> 01:35:59.109
Faculty (Olympus): It's going to be for 2â€¦

740
01:35:59.270 --> 01:36:02.340
Faculty (Olympus): The contribution is 4 times 1 by 4.

741
01:36:02.750 --> 01:36:08.360
Faculty (Olympus): From minus 2, again, it's 4 times 1 by 4, from 0â€¦

742
01:36:08.520 --> 01:36:10.859
Faculty (Olympus): It's 0 times 1 by 4,

743
01:36:10.970 --> 01:36:15.630
Faculty (Olympus): And from minus 4, it is 16 times 1 by 4.

744
01:36:15.970 --> 01:36:19.010
Faculty (Olympus): That is the expected value of G squared.

745
01:36:19.130 --> 01:36:24.730
Faculty (Olympus): So, that's going to be 1 plus 1, 2 plus 4, 6.

746
01:36:25.010 --> 01:36:27.740
Faculty (Olympus): Okay, so this is the expected value of G squared.

747
01:36:27.880 --> 01:36:33.999
Faculty (Olympus): And I already have square of the expectation, so if I take one random sample, the variance

748
01:36:34.570 --> 01:36:38.569
Faculty (Olympus): of G is 6 minus 1, which is 5.

749
01:36:38.880 --> 01:36:42.489
Faculty (Olympus): Okay? So this is how much variation you will see.

750
01:36:42.650 --> 01:36:46.360
Faculty (Olympus): Okay? On average, if you take one random sample.

751
01:36:46.690 --> 01:36:54.689
Faculty (Olympus): Now, let's takeâ€¦ let'sâ€¦ we had seen one random sample, the expected value is G4, variance is 5.

752
01:36:55.180 --> 01:36:58.370
Faculty (Olympus): Now, let's extend this to two random samples.

753
01:37:03.630 --> 01:37:11.979
Faculty (Olympus): Okay? So again, recall how this worked. We took two independent random samples from the four possibilities, right?

754
01:37:12.520 --> 01:37:30.960
Faculty (Olympus): And, we, saw that weâ€¦ what we consider is G1 plus G2 by 2, that is our overall random variable G bar, and we saw that the expected value of G bar is also equal to G full

755
01:37:31.480 --> 01:37:33.040
Faculty (Olympus): Which is minus 1.

756
01:37:33.400 --> 01:37:41.999
Faculty (Olympus): Okay? Soâ€¦ Again, I can talk about the variance of G-bar, which is going to be expected value

757
01:37:42.240 --> 01:37:48.249
Faculty (Olympus): of G bar squared minus square of its expected value.

758
01:37:49.550 --> 01:37:56.730
Faculty (Olympus): Now, again, the square of the expected value is again G-full, which is minus 1, so I know that this second term is definitely going to be 1.

759
01:37:57.020 --> 01:38:02.040
Faculty (Olympus): The only question is, what is going to be this expected value of G bar squared?

760
01:38:02.450 --> 01:38:09.349
Faculty (Olympus): Okay? So again, we had done this thing, we had lookedâ€¦ we had a certain PMF for G-Bar.

761
01:38:11.070 --> 01:38:17.480
Faculty (Olympus): Right? We saw that Gbar can take values ranging from minus 4, minus 3,

762
01:38:17.680 --> 01:38:21.400
Faculty (Olympus): It's 2 minus 1, 0, 1, 2.

763
01:38:21.500 --> 01:38:24.359
Faculty (Olympus): Right, and then there were some PMF values here.

764
01:38:25.200 --> 01:38:26.010
Faculty (Olympus): Right?

765
01:38:26.260 --> 01:38:44.130
Faculty (Olympus): So, you canâ€¦ I'm not going to do this calculation here, I'll share a sheet later on where all these calculations are there, but you can certainly compute the expected value of G-bar square directly from that PMF. Just like we did for a single random variable, you can compute the expected value of G bar square.

766
01:38:44.320 --> 01:38:47.159
Faculty (Olympus): What it turns out to be is 7x2.

767
01:38:47.480 --> 01:38:50.710
Faculty (Olympus): Okay? So, what does this imply? This impliesâ€¦

768
01:38:50.850 --> 01:38:58.890
Faculty (Olympus): that the variance of G-bar is going to be 7 by 2 minus 1, Which is 5x2.

769
01:38:59.810 --> 01:39:00.530
Faculty (Olympus): Okay?

770
01:39:00.730 --> 01:39:05.920
Faculty (Olympus): Soâ€¦ what is the upshot of all of this? If you take one random sample.

771
01:39:09.020 --> 01:39:12.530
Faculty (Olympus): You look at its expected value, you look at the variance.

772
01:39:13.110 --> 01:39:15.480
Faculty (Olympus): And you take two random samples.

773
01:39:18.050 --> 01:39:24.399
Faculty (Olympus): You look at its expected value, you look at the variance. The expected value for both of these cases

774
01:39:25.180 --> 01:39:26.930
Faculty (Olympus): is going to be G4.

775
01:39:27.360 --> 01:39:28.110
Faculty (Olympus): Right?

776
01:39:28.310 --> 01:39:47.900
Faculty (Olympus): If the expected value in both of the cases is G-full, why do people take more than one sample in a mini-batch? The reason they do that is that if you take one random simp sample, you get a varianceâ€¦ in this particular case, the variance was 5, whereas if you took two random samples, your variance decreases by a factor of 2.

777
01:39:48.640 --> 01:39:53.349
Faculty (Olympus): If I took 3 random samples, my variance is going to decrease by a factor of 3, and so on.

778
01:39:53.680 --> 01:39:54.550
Faculty (Olympus): Okay?

779
01:39:54.710 --> 01:40:11.350
Faculty (Olympus): So the reason why we take more samples than just one, even though the expectation remains the same, in expectation, all of these are going to match GFUL. The reason that weâ€¦ you take more samples, as many samples as, you know, computationally you can.

780
01:40:11.360 --> 01:40:24.849
Faculty (Olympus): is to reduce the variance in your gradient. You don't want the gradient to keep fluctuating. If the gradient keeps fluctuating, then you're going in one direction at one time, then you're going in a completely different direction, then again another direction.

781
01:40:24.850 --> 01:40:35.750
Faculty (Olympus): So, your convergence will just take longer. You will reach there at the end, but your convergence will just take much longer if your variance is larger. So, in general, you want to keep the variance small.

782
01:40:35.950 --> 01:40:47.459
Faculty (Olympus): That's why you take more, as many sampleâ€¦ moreâ€¦ not just one sample in your mini-batch, you take many more samples in your mini batch, as much as, computationally, you can.

783
01:40:47.630 --> 01:40:48.460
Faculty (Olympus): Okay?

784
01:40:48.680 --> 01:40:59.910
Faculty (Olympus): Okay, so yeah, that's what I wanted to, show you, that, okay, you can have situations wherein, you know, expectation, maybe different estimates can be the same.

785
01:41:00.810 --> 01:41:08.819
Faculty (Olympus): But, they can be very different in terms of variance, and that is how oneâ€¦ I mean, this is one way of comparing different estimators of the same quantity.

786
01:41:08.940 --> 01:41:17.469
Faculty (Olympus): Right? They might all have the same expectation, but if the variance of one is smaller than the other, then usually we prefer that.

787
01:41:18.180 --> 01:41:36.669
Faculty (Olympus): Okay, yeah, so yeah, with that, I'll end in terms of the technical content for today. So, we saw expectation last time. We started with an example of expectation that you will encounter in practice in terms of training of models and working with mini-batches.

788
01:41:36.760 --> 01:41:46.720
Faculty (Olympus): We then looked at the concept of variance, which encodes the spread, or the variability of a distribution. Howâ€¦ how different,

789
01:41:46.790 --> 01:41:58.150
Faculty (Olympus): Or how much difference will you see if you take many samples from this distribution? Will the samples all be very, very close to the mean value, or will they be spread out? That's what variance is encoding.

790
01:41:58.260 --> 01:42:05.790
Faculty (Olympus): We computed the variance for a couple of distributions, and then we saw, again, the impact of variance in terms of estimation.

791
01:42:06.370 --> 01:42:12.299
Faculty (Olympus): Okay, yeah, so I'mâ€¦ I'll take some questions now. Yeah, Gaurav Singh?

792
01:42:13.380 --> 01:42:29.959
Gaurav Singh .: Yeah, Professor, so since, you mentioned here, for example, take more number of random samples, which will, anyways, the expectation is not going to change, but the variance will reduce. Yeah. So, somebody asked that question that

793
01:42:29.960 --> 01:42:42.830
Gaurav Singh .: whether we should have, you know, more variants to, have more fair data. It may be dependent on theâ€¦ what we want from, as a result.

794
01:42:42.830 --> 01:42:43.399
Faculty (Olympus): Yeah, yeah, yeah.

795
01:42:43.400 --> 01:42:52.399
Gaurav Singh .: for example, in this case, the variants, we want less. Correct. That we getâ€¦ come up with, you know, samples which give me.

796
01:42:52.400 --> 01:42:53.150
Faculty (Olympus): Better estimate.

797
01:42:53.150 --> 01:42:54.280
Gaurav Singh .: Better, yeah, better.

798
01:42:54.280 --> 01:43:06.570
Faculty (Olympus): Yeah, yeah, you're right. So, yeah, you might want toâ€¦ sometimes you want higher variance when, for example, suppose, you know, you are in this situationâ€¦ so, even, even, let's say.

799
01:43:06.980 --> 01:43:26.670
Faculty (Olympus): when we have, language models which are generating synthetic data, I don't want the variance to be too small, because then that means I am generating, essentially, there is no randomness in the text, right? But when I, suppose, if I query an LLM, the same thing two times, I get a different answer.

800
01:43:26.780 --> 01:43:34.209
Faculty (Olympus): And the reason they keep it that way is that you don't want the variance to be absolutely zero. You do want some sort of variability in the response.

801
01:43:35.920 --> 01:43:44.329
Faculty (Olympus): So, yeah, it depends what you areâ€¦ what your goal is. Do you want the variance to be larger, or do you want the variance to be small, or do you want it somewhere in between?

802
01:43:44.570 --> 01:43:46.809
Faculty (Olympus): All of that depends on the code.

803
01:43:47.360 --> 01:43:48.380
Gaurav Singh .: Thanks for the explanation.

804
01:43:48.900 --> 01:43:50.460
Faculty (Olympus): Okay, Devendra?

805
01:43:52.050 --> 01:44:01.989
Devendra Parmar .: Good afternoon, sir. Sir, just one request, can you please re-explain the last part of that exponential distribution with respect to the calculation of variance?

806
01:44:02.310 --> 01:44:04.690
Faculty (Olympus): Okay, here?

807
01:44:05.070 --> 01:44:05.939
Devendra Parmar .: Yes, sir.

808
01:44:06.200 --> 01:44:06.850
Faculty (Olympus): Huh.

809
01:44:07.010 --> 01:44:14.150
Devendra Parmar .: First term was increasing linearly, but the second term was decreasingâ€¦ decaying exponentially.

810
01:44:14.150 --> 01:44:14.780
Faculty (Olympus): Yeah.

811
01:44:14.780 --> 01:44:15.800
Devendra Parmar .: donations.

812
01:44:15.800 --> 01:44:35.270
Faculty (Olympus): So, I think theâ€¦ okay, if I understood, I think it was Anne's question, what I understood was, that, her, concern was that if I look at the variance, right, of, of anâ€¦ of a random variable which has a support, does not have a bounded support.

813
01:44:35.280 --> 01:44:44.379
Faculty (Olympus): Right? If, for example, like, an exponential distribution, it can, in general, take values all the way from 0 to infinity, so how would the variance be bounded?

814
01:44:44.500 --> 01:44:52.980
Faculty (Olympus): So, what I was saying was that in the variance computation, you have, two terms, right? One is,

815
01:44:53.290 --> 01:45:02.210
Faculty (Olympus): this X minus mu X squared, when that is getting multiplied by their corresponding density value, and then you are taking the integral.

816
01:45:02.640 --> 01:45:11.480
Faculty (Olympus): Right? So this first part, indeed, when X is large, this first part is going to be increasing. It's going to linearly increase with X.

817
01:45:12.310 --> 01:45:13.780
Faculty (Olympus): Whereasâ€¦ soâ€¦

818
01:45:14.320 --> 01:45:24.739
Faculty (Olympus): However, so that is a problem, right? If youâ€¦ if you're integrating somethingâ€¦ if you were, for example, integrating just X, then the integral would have been infinity.

819
01:45:25.040 --> 01:45:40.790
Faculty (Olympus): But the point is that you are multiplying that by a much, much faster decaying random, quantity, a decayingâ€¦ much, much faster decaying function. This exponential function E raised to minus lambda X, is going to balance, more than balance out the increasing X.

820
01:45:41.140 --> 01:45:49.220
Faculty (Olympus): So overall, when you write X times E raised to minus lambda X, usually it'll increase a little bit, but then very, very quickly go down.

821
01:45:49.460 --> 01:45:59.329
Faculty (Olympus): So that's why one can expect this integral to indeed be finite. This quantity might be increasing, but this quantity is rapidly decreasing as X becomes large.

822
01:46:01.100 --> 01:46:02.300
Faculty (Olympus): Okay, yeah.

823
01:46:02.470 --> 01:46:03.629
Devendra Parmar .: Yeah, thank you.

824
01:46:03.630 --> 01:46:04.210
Faculty (Olympus): Okay.

825
01:46:04.460 --> 01:46:06.090
Faculty (Olympus): Abhishek?

826
01:46:12.360 --> 01:46:18.700
Abhishek Raghuvanshi .: Yeah, Professor, that was the original question, for theâ€¦ this mini-tapâ€¦

827
01:46:18.700 --> 01:46:19.370
Abhishek .: Okay, hello.

828
01:46:19.370 --> 01:46:21.950
Faculty (Olympus): Sorry, I was talking to the other Abhisheh.

829
01:46:23.460 --> 01:46:27.820
Abhishek .: Okay, so, sir, sorry, I was speaking on mute, so,

830
01:46:28.330 --> 01:46:48.680
Abhishek .: on approaching the questions, considering that we'll have the formula sheet even, in the exam or with exams, considering it has too many formulas and too many algorithms or theorems to be applied, how we approach such questions on that, which is the best method to apply for certain questions? For example, this,

831
01:46:48.680 --> 01:46:53.649
Abhishek .: Here, applied FPMFs and, lambda functions at all, soâ€¦

832
01:46:53.710 --> 01:46:56.319
Abhishek .: How we approach the questions overall.

833
01:46:56.320 --> 01:47:05.939
Faculty (Olympus): So, I mean, there is no substitute for practice here. So, like I said, I mean, we areâ€¦ we areâ€¦ we are going to,

834
01:47:06.760 --> 01:47:09.580
Faculty (Olympus): You're not going to be required to remember everything.

835
01:47:10.180 --> 01:47:15.799
Faculty (Olympus): But, the only way to kind of get comfortable with any of this isâ€¦ isâ€¦

836
01:47:15.910 --> 01:47:17.979
Faculty (Olympus): Computing things on your own.

837
01:47:18.750 --> 01:47:25.549
Abhishek .: Will there be, any hints that we can guess from questions that, okay, this is something what we need to apply?

838
01:47:25.550 --> 01:47:34.850
Faculty (Olympus): I can't say that directly. Right now, I can't commit one way or the other. But I think, yeah, in terms of action.

839
01:47:35.040 --> 01:47:36.070
Faculty (Olympus): for yourâ€¦

840
01:47:36.070 --> 01:47:36.550
Abhishek .: Huh.

841
01:47:37.000 --> 01:47:54.080
Faculty (Olympus): It is to practice as much as possible. The more you work these things out, for example, even things like we are doing in class, I'm not able to always do computations. For example, the variance of an exponential random variable, right? We already have, I've explicitly said it. Now, it's about actually

842
01:47:54.180 --> 01:48:07.019
Faculty (Olympus): doing that computation, verifying it, is it indeed the right variance? So do the computation on your own, and then just check, verify online whether this is indeed what the exponential variance of an exponential random variable is.

843
01:48:07.260 --> 01:48:21.340
Faculty (Olympus): Sure. But yeah, there isâ€¦ And furthermore, I mean, like I said, this variance can either be computed in this way, or you can also compute it as the expected value of X squared minus mu X squared.

844
01:48:21.540 --> 01:48:27.859
Faculty (Olympus): So, you should try those Theseâ€¦ this computation and this computation, and see whether you get the same answer.

845
01:48:29.460 --> 01:48:30.290
Abhishek .: Okay.

846
01:48:30.290 --> 01:48:32.329
Faculty (Olympus): So, so yeah, I mean, yeah, I think it'sâ€¦

847
01:48:32.330 --> 01:48:48.519
Abhishek .: And one last, one last, if you canâ€¦ means you do provide the samples, but they're not in question format, so if you can correlate to that, how the questions will look like for similar things, one question, then it will also help.

848
01:48:48.610 --> 01:48:52.839
Abhishek .: Understanding on applying the theorems and algorithms.

849
01:48:53.160 --> 01:48:54.489
Faculty (Olympus): Sorry, I didn't get what you.

850
01:48:54.490 --> 01:49:02.019
Abhishek .: You provide those samples, and then you walk through with us that how the probability or, the variance orâ€¦ variance will look likeâ€¦ look like.

851
01:49:02.020 --> 01:49:02.920
Faculty (Olympus): Oh, look like.

852
01:49:03.210 --> 01:49:08.089
Abhishek .: But if you can proceed it in terms of how the question will look like.

853
01:49:08.090 --> 01:49:16.159
Faculty (Olympus): No, no, so I really don't want to tailor myâ€¦ what I teach in terms of what the exam is going to be. This is not that kind of a course at all.

854
01:49:16.780 --> 01:49:24.789
Faculty (Olympus): So that would be completely, a different course, where, if I was tailoring what I teach toâ€¦

855
01:49:24.790 --> 01:49:29.500
Abhishek .: Just to give a zest, okay, that's how the questions are formatted.

856
01:49:29.500 --> 01:49:30.389
Faculty (Olympus): Cool, let's in general.

857
01:49:30.390 --> 01:49:32.569
Abhishek .: In general, a way, notâ€¦

858
01:49:33.120 --> 01:49:44.570
Faculty (Olympus): So, I mean, I think in terms of questions or problem solving, the TA session is supposed to be more tailored towards that than the lecture session.

859
01:49:44.650 --> 01:49:58.650
Faculty (Olympus): I think the lecture Session is more about just giving you concepts and, explaining things via examples, trying to link it maybe to someâ€¦ some, other courseâ€¦ what you might see in other courses, and so on.

860
01:49:58.830 --> 01:50:04.350
Faculty (Olympus): Yeah, I wouldn't want to spend too much time on exam questions or problem solving here.

861
01:50:05.070 --> 01:50:15.979
Abhishek .: not related to exam questions, but in general, how the question in general looks like, was my question, butâ€¦ Okay, yeah, sure, I'll do that. Okay.

862
01:50:15.980 --> 01:50:18.719
Faculty (Olympus): Alright, yeah, Vamsi,

863
01:50:19.670 --> 01:50:29.499
Vamsi Krishna Mutnuri .: Sir, my question is not on a similar line, but so, when you gave the first homework, you know, it wasâ€¦ it was stated in front theâ€¦

864
01:50:29.500 --> 01:50:44.730
Vamsi Krishna Mutnuri .: the domain which the question came from, or the chapter which it came. For example, like, independence, counting and sampling, and like that. I'm very sure the main, the main, the same exams won't be like that, and we have to figure out which, theorem to be used, which formula to be used.

865
01:50:45.160 --> 01:50:58.990
Vamsi Krishna Mutnuri .: So, you know, that is kind of probably what the earlier, question was about. And my question was, like, do we have, any references where we have some

866
01:50:59.290 --> 01:51:09.519
Vamsi Krishna Mutnuri .: Info on, like, small tips where, what kind ofâ€¦ in what kind of problems, what kind of theoryâ€¦ theorems or,

867
01:51:09.520 --> 01:51:21.610
Vamsi Krishna Mutnuri .: formulas to be applied, like, you know, any kind of references, or small books, or any online, books, or anything, or articles, which can give us a clue where, for a given situation, this

868
01:51:21.610 --> 01:51:31.249
Vamsi Krishna Mutnuri .: probability concept is the right, like, where a binomial should be taken, where a random variable should be taken, where an expected value should be taken, orâ€¦ I mean, I hope you got my point.

869
01:51:31.440 --> 01:51:38.000
Faculty (Olympus): Yeah, so, I mean, I don't think there is one reference like that. There isâ€¦ again, if you want

870
01:51:38.740 --> 01:51:54.589
Faculty (Olympus): practice problems. There is one reference that I think Iâ€¦ there is, that I have provided, which is 1000 problems in probability. That'll give you some, I think, practice problems, if that is what you're looking for.

871
01:51:54.740 --> 01:52:00.910
Faculty (Olympus): The other, thing is that these books also, all the books have practice problems, example problems that are being solved.

872
01:52:00.910 --> 01:52:01.989
Vamsi Krishna Mutnuri .: Ross has problems.

873
01:52:01.990 --> 01:52:11.739
Faculty (Olympus): Yeah, so the other book also that is mentioned in, I think, the first lecture, where the references were mentioned, there, this 1000 Problems in Probability is also mentioned.

874
01:52:12.240 --> 01:52:16.670
Faculty (Olympus): So that is also a resource for problems, if that is what you're looking for.

875
01:52:17.440 --> 01:52:24.650
Vamsi Krishna Mutnuri .: Okay, sir. And just one small extension of this question is that, I mean, again, it's regarding the exams,

876
01:52:24.650 --> 01:52:41.580
Vamsi Krishna Mutnuri .: that are weâ€¦ you know, what is the right way to attempt a question? Should we, like, you know, start from the very beginning, what theorem has to be applied, you know, writing all these formulas which you are showing us here, and then solving the problem, and is there any,

877
01:52:41.580 --> 01:52:45.120
Vamsi Krishna Mutnuri .: Cognizance given to the formula that has to be

878
01:52:45.190 --> 01:52:53.420
Vamsi Krishna Mutnuri .: expectedâ€¦ is the formula expected from us to be written in the correct way? I mean, I know it's a naive question, but if you can throw some light on that.

879
01:52:54.530 --> 01:52:57.290
Faculty (Olympus): Soâ€¦

880
01:52:57.430 --> 01:53:08.129
Faculty (Olympus): I mean, yeah, we would just like toâ€¦ in terms of the exam, I think we would like to test more, maybe, you know, whether the concepts have been understood

881
01:53:08.520 --> 01:53:15.350
Faculty (Olympus): Or if, you know, if there is a problem where you have to compute something, are you able toâ€¦

882
01:53:15.510 --> 01:53:18.440
Faculty (Olympus): At least identify what is to be computed.

883
01:53:18.750 --> 01:53:23.050
Faculty (Olympus): Or what does the expectation of a random variable mean?

884
01:53:23.350 --> 01:53:43.159
Faculty (Olympus): So if I give youâ€¦ if I talk about, let's say, the demand, ofâ€¦ let's say, the data demand in aâ€¦ in a certain city, and I talk about things like, okay, I have to find the probability that the data, demand crosses

885
01:53:43.380 --> 01:53:44.880
Faculty (Olympus): A certain threshold.

886
01:53:45.040 --> 01:53:55.760
Faculty (Olympus): Right? Then you should be able to identify the fact that, okay, data demand crosses a certain threshold means the probability that the data is greater than equal to something. That's what I have to find.

887
01:53:56.280 --> 01:53:58.820
Faculty (Olympus): This isâ€¦ this can be related toâ€¦

888
01:53:58.990 --> 01:54:05.450
Faculty (Olympus): The cumulative distribution function, which is probability that the data demand is less than equal to something.

889
01:54:05.990 --> 01:54:09.419
Faculty (Olympus): So then Iâ€¦ I should be working with the CDF.

890
01:54:09.910 --> 01:54:17.909
Faculty (Olympus): So, at this level, that is the kind of understanding we would like toâ€¦ we would like you to have.

891
01:54:19.010 --> 01:54:19.360
Vamsi Krishna Mutnuri .: Understood.

892
01:54:19.730 --> 01:54:32.599
Vamsi Krishna Mutnuri .: This is exactly what I wanted to know. This is exactly that if the concepts, if you can identify the concept ofâ€¦ behind the question, I mean, the intent behind the question, and if we can reach to that concept, and probably we might not be able toâ€¦

893
01:54:32.600 --> 01:54:40.550
Vamsi Krishna Mutnuri .: you know, justify the concept in terms of the computation. Will that be considered as an affirmative response, and some marks B will be considered for that?

894
01:54:40.550 --> 01:54:56.240
Faculty (Olympus): Yeah, yeah, yeah, yeah, yeah, yeah, if youâ€¦ so there will, of course, definitely be marks for actually reaching some point, and then making a computational error, versus at least reaching the right concept, or writing the right formula. There will be all of that.

895
01:54:57.030 --> 01:54:58.090
Vamsi Krishna Mutnuri .: Thank you, sir, thank you.

896
01:54:58.090 --> 01:55:01.260
Faculty (Olympus): Yeah, okay. Yeah, Manu?

897
01:55:04.970 --> 01:55:15.590
Manu Gupta .: Yes, sir. So, containing to the previous point, can you share in your views how will the pattern of mid-exams, midterm exams.

898
01:55:15.800 --> 01:55:20.260
Manu Gupta .: And we areâ€¦ are we supposed to write the answers out to a broad?

899
01:55:22.580 --> 01:55:37.319
Faculty (Olympus): Iâ€¦ yeah, I mean, I don't know exactly what theâ€¦ how this is going to work, that is something for great learning, but the questions will be, they will not be objective questions, they will be subjective questions, so you will have to write and upload it, I'm guessing.

900
01:55:38.320 --> 01:55:42.450
Faculty (Olympus): So you'll have to prepare solutions, and then upload a scan of those solutions.

901
01:55:42.790 --> 01:55:46.580
Manu Gupta .: So, will it be a liveâ€¦ live exams?

902
01:55:46.580 --> 01:55:52.340
Faculty (Olympus): I think so. Again, that is a question for Great Learning. I don't know how exactly they conduct the mid-sims.

903
01:55:52.780 --> 01:56:00.319
Faculty (Olympus): Soâ€¦ yeah, I'm not aware of the exact, forâ€¦ how exactly that is done.

904
01:56:03.130 --> 01:56:04.410
Faculty (Olympus): Okay, Sameer?

905
01:56:05.680 --> 01:56:22.769
Sameer Sawant .: Yeah, hi, Professor, thanks. So, Professor, it's, more, again, I think, the question I'm just looking for is, as we look at the concept, right, and we want to apply it, after the first, homework which we saw, I felt it that I had to do a lot of research in a way

906
01:56:22.770 --> 01:56:43.090
Sameer Sawant .: I mean, I refer to the classes to understand the concept, but sometimes, you know, we need to spend more time to underline theâ€¦ understand the underlined core concept at times, you know, through web and all. And when I refer to the Sheldon Ross book, it felt like it's more equational, and certainly from an application mathematical perspective, but the conceptual part.

907
01:56:43.090 --> 01:56:58.249
Sameer Sawant .: Professor, that takes a while to kick in, you know, to understand that part. So, what I'm trying to understand is, is there any reference material much more, to give that detail of theory, more than it goes to the equation part of it?

908
01:56:59.630 --> 01:57:03.520
Charles Ravi Kiran Mutsu .: Can I take a stab at it? Yeah.

909
01:57:04.270 --> 01:57:14.670
Charles Ravi Kiran Mutsu .: Sameer, so one thing what I am also trying to do is, like, use any of the AI tools, to basically give

910
01:57:14.850 --> 01:57:28.759
Charles Ravi Kiran Mutsu .: the highlights of all these various topics, and sequentially, like, a distributed tree kind of a structure, how we can interpret. So, let's say if there are

911
01:57:28.900 --> 01:57:44.980
Charles Ravi Kiran Mutsu .: random variables, we have discrete, we have continuous, and in whichâ€¦ in each of these, like, discrete, what are the various functions that we can use, versus in continuous, what are the various functions that we can use? And, andâ€¦ and canâ€¦

912
01:57:45.120 --> 01:57:53.100
Charles Ravi Kiran Mutsu .: And let's say when we start from Bernoullis to geometric series to, you know, each of these other functions.

913
01:57:53.620 --> 01:57:57.339
Charles Ravi Kiran Mutsu .: conceptually, likeâ€¦ like how you mentioned, like, in whichâ€¦

914
01:57:57.450 --> 01:58:01.080
Charles Ravi Kiran Mutsu .: Area, or, like, in which aspect we should apply this.

915
01:58:01.220 --> 01:58:07.420
Charles Ravi Kiran Mutsu .: To, no, andâ€¦ Is something that it can elaborate.

916
01:58:07.880 --> 01:58:12.580
Charles Ravi Kiran Mutsu .: you know, either it is Claude, Gemini, anywhere, like, you know, you canâ€¦ it can basically break it down.

917
01:58:12.960 --> 01:58:22.000
Charles Ravi Kiran Mutsu .: And also, you can ask, saying that, hey, give me a problem, and help me identify those data points that can help me identify which

918
01:58:22.200 --> 01:58:39.809
Charles Ravi Kiran Mutsu .: concept that I should be applying. So, let's say, for, I think, in geometric series, the first occurrence is something thatâ€¦ which we would look for, versus when we are looking for a binomialâ€¦ binomial function, we will look in a set of occurrences, how many successes you have.

919
01:58:40.010 --> 01:58:49.780
Charles Ravi Kiran Mutsu .: Right? So it can definitely help break down, and give a kind of a structure. It's something which I have tried, and I felt

920
01:58:49.920 --> 01:58:58.289
Charles Ravi Kiran Mutsu .: more comfortable now when I'm looking at these, at the classes, professor, like, you know, I'm able to consume it a little better.

921
01:58:58.630 --> 01:59:16.129
Charles Ravi Kiran Mutsu .: So, I think we definitely need to have that pre-prep, to have, that understanding, and still a couple of gaps, Professor. One is the integral, and the other is theâ€¦ is something which I'm yet toâ€¦

922
01:59:16.870 --> 01:59:22.899
Charles Ravi Kiran Mutsu .: brush up so that, like, you know, when I'm following theseâ€¦ things, like, More naturally understandable.

923
01:59:23.200 --> 01:59:23.890
Faculty (Olympus): Yeah, yeah.

924
01:59:24.710 --> 01:59:30.540
Charles Ravi Kiran Mutsu .: Hope it, you know, helps, or, like, we can connect offline to, like, Saurav asked the question.

925
01:59:31.280 --> 01:59:31.860
Faculty (Olympus): Okay.

926
01:59:32.990 --> 01:59:35.199
Faculty (Olympus): Okay, Prachiki Kumari?

927
01:59:35.550 --> 01:59:45.419
Lad Prachikumari Vijaykumar .: Sir, for that poison distribution, that, expectation of X and variance both are same, right, lambda?

928
01:59:45.420 --> 01:59:46.160
Faculty (Olympus): Yeah, yeah.

929
01:59:46.160 --> 01:59:54.879
Lad Prachikumari Vijaykumar .: Could you please explain the significance of that, like, how it is same? Something using graph, orâ€¦

930
01:59:56.150 --> 02:00:08.039
Faculty (Olympus): I don't think there is, yeah, there is anything else other than that's how it turns out to be. I'm not aware of any explanation or any intuition behind why the expected value and the variance should be the same.

931
02:00:08.750 --> 02:00:11.769
Faculty (Olympus): Iâ€¦ Iâ€¦ yeah, at least I'm not aware of anyâ€¦

932
02:00:12.170 --> 02:00:26.939
Faculty (Olympus): intuitive reason for why the expectation and the variance should actually turn out to be the same. It's just that the distribution is such that when you compute these two quantities, they just turn out to be the same. Yeah, that's what I know of. I don't know if there is some intuition behind it.

933
02:00:27.840 --> 02:00:40.430
Lad Prachikumari Vijaykumar .: And, sir, I guess before to lecture, you given one example, like, that, exponential we can use for time-related,

934
02:00:41.000 --> 02:00:42.819
Lad Prachikumari Vijaykumar .: That undertime you given when.

935
02:00:42.820 --> 02:00:45.790
Faculty (Olympus): Yeah, some, maybe lifetime.

936
02:00:46.150 --> 02:00:50.159
Faculty (Olympus): Maybe lifetime of, of,

937
02:00:50.320 --> 02:00:55.900
Faculty (Olympus): Or was it about, service times, No?

938
02:00:56.360 --> 02:00:58.570
Lad Prachikumari Vijaykumar .: Just a second, I haven't.

939
02:00:58.570 --> 02:01:01.320
Charles Ravi Kiran Mutsu .: Yeah, what's this?

940
02:01:01.450 --> 02:01:02.110
Charles Ravi Kiran Mutsu .: What's theâ€¦

941
02:01:02.110 --> 02:01:03.400
Lad Prachikumari Vijaykumar .: As waiting time.

942
02:01:03.400 --> 02:01:04.219
Faculty (Olympus): Okay.

943
02:01:04.660 --> 02:01:16.750
Lad Prachikumari Vijaykumar .: No, in uniformly distributed, you're given that bus waiting time. So, how it is related to uniform, distribution, just, could you please, that example?

944
02:01:17.460 --> 02:01:31.850
Faculty (Olympus): I don't recall the exact example, but I think maybe what it might have been is if, let's say, there is a bus that comes every 5 minutes, okay? Let's say this is, 10 o'clock, then 10, 5â€¦

945
02:01:32.100 --> 02:01:34.070
Faculty (Olympus): 10, 10, and so on.

946
02:01:34.640 --> 02:01:35.040
Lad Prachikumari Vijaykumar .: Hmm.

947
02:01:35.040 --> 02:01:41.700
Faculty (Olympus): So, if you arrive at a random time somewhere here, okay, so your arrival time

948
02:01:41.860 --> 02:01:48.000
Faculty (Olympus): Let's say is uniform between 10 o'clock and 10.05.

949
02:01:48.710 --> 02:01:50.350
Faculty (Olympus): Somewhere you arrive.

950
02:01:50.350 --> 02:01:51.600
Lad Prachikumari Vijaykumar .: Hmm. Yeah.

951
02:01:52.420 --> 02:01:55.229
Faculty (Olympus): The question is, what is the waiting time?

952
02:01:57.600 --> 02:02:01.110
Lad Prachikumari Vijaykumar .: Or that we are using, exponential or,

953
02:02:01.110 --> 02:02:05.369
Faculty (Olympus): We were using a uniform distribution. I mean, in this case, it'll be uniform.

954
02:02:05.990 --> 02:02:19.510
Lad Prachikumari Vijaykumar .: how I canâ€¦ I mean, I'm just confused about exponential and unifâ€¦ this uniform distribution for this particular example. I cannot get differentâ€¦

955
02:02:19.510 --> 02:02:22.929
Faculty (Olympus): So, exponentialâ€¦ I mean, for an exponential distribution.

956
02:02:23.330 --> 02:02:29.219
Faculty (Olympus): An exponential distribution can take any value between Larger than zero, right?

957
02:02:29.500 --> 02:02:30.430
Lad Prachikumari Vijaykumar .: Yes.

958
02:02:30.430 --> 02:02:33.970
Faculty (Olympus): Clearly, here, the waiting time cannot be more than 5 minutes.

959
02:02:35.650 --> 02:02:36.170
Lad Prachikumari Vijaykumar .: a child.

960
02:02:36.170 --> 02:02:40.919
Faculty (Olympus): Right? So, it cannot be modeled well by an exponential distribution, certainly.

961
02:02:41.430 --> 02:02:48.529
Faculty (Olympus): If there areâ€¦ if there areâ€¦ if there was aâ€¦ a situation where, you know, the amount of time required

962
02:02:48.560 --> 02:03:04.579
Faculty (Olympus): could be very, very large. There was no bound on the amount of time required, then an exponential distribution is a better model. For example, if you are at a grocery store, right, and you are just waiting for the next server.

963
02:03:04.750 --> 02:03:21.370
Faculty (Olympus): So, beforehand, I don't know how much amount of time that server is going to need. It's not like, you know, every server is going to get done within exactly 1 minute. It depends on how much, you know, how much the person in front of me, how many items they have.

964
02:03:21.600 --> 02:03:27.009
Faculty (Olympus): Maybe some items that they have do not have the right tag, so it might take more and more time.

965
02:03:27.290 --> 02:03:32.020
Faculty (Olympus): Or there is some confusion about some of the items. So there is no clear upper bound there.

966
02:03:32.150 --> 02:03:39.320
Faculty (Olympus): So usually in those kind of systems, you can use, exponential distribution to model the service time.

967
02:03:39.420 --> 02:03:44.330
Faculty (Olympus): But a situation like this, where there is, like, a clear bound, right, on how much

968
02:03:44.520 --> 02:03:47.609
Faculty (Olympus): Your waiting time can be, at most.

969
02:03:47.890 --> 02:03:51.799
Faculty (Olympus): There, an exponential distribution might not be the right model.

970
02:03:53.010 --> 02:03:54.359
Lad Prachikumari Vijaykumar .: Gotcha, okay.

971
02:03:54.720 --> 02:03:55.390
Faculty (Olympus): Yeah.

972
02:03:55.390 --> 02:04:02.999
Vamsi Krishna Mutnuri .: Sir, can we say that, you know, this bus comes and leaves at a certain time, so there is a time frame, and that is why we should use a uniform distribution?

973
02:04:03.530 --> 02:04:09.499
Faculty (Olympus): So here, I mean, also, thisâ€¦ it has the factâ€¦ there are two things. One, that it has a boundedâ€¦

974
02:04:09.650 --> 02:04:13.620
Faculty (Olympus): Your waiting time is bounded between 0 to 5 minutes.

975
02:04:13.770 --> 02:04:26.109
Faculty (Olympus): So, certainly, you should have a distribution which is on that support, right? Your distribution, your waiting time distribution should haveâ€¦ should be a density which is supported between 0 to 5 minutes.

976
02:04:26.290 --> 02:04:34.060
Faculty (Olympus): Right? Now, should it be uniform, or should it be something which is non-uniform?

977
02:04:34.510 --> 02:04:42.739
Faculty (Olympus): That depends on, you know, on the particular problem here, because if I say that I arrive at a random time.

978
02:04:43.100 --> 02:04:51.170
Faculty (Olympus): then I'm equally likely to have a waiting time of 1 minute, and I'm equally likely to have a waiting time of 5 minutes, right? I might arrive

979
02:04:51.440 --> 02:05:00.179
Faculty (Olympus): I'm equally likely to arrive somewhere here, and I'm equally likely to arrive somewhere here. So that's why maybe a uniform waiting time is a good model.

980
02:05:00.660 --> 02:05:06.430
Faculty (Olympus): But if that was not exactly the case, then we would possibly have a different model.

981
02:05:06.910 --> 02:05:09.710
Lad Prachikumari Vijaykumar .: And can it be normal distribution?

982
02:05:09.880 --> 02:05:17.610
Faculty (Olympus): So, again, ifâ€¦ it cannot be an exact normal distribution because your waiting time cannot really be negative, right?

983
02:05:18.300 --> 02:05:18.790
Faculty (Olympus): No.

984
02:05:18.790 --> 02:05:20.590
Lad Prachikumari Vijaykumar .: Okay. Soâ€¦

985
02:05:20.590 --> 02:05:28.500
Faculty (Olympus): It is not like people don't use the normal distribution for waiting times. They will, but then you have to be aware of the fact that it is not an exact match.

986
02:05:29.240 --> 02:05:37.989
Faculty (Olympus): Okay, so the fact thatâ€¦ so sometimes people use truncated Gaussian instead of the full Gaussian distribution, so they will not allow

987
02:05:38.110 --> 02:05:44.300
Faculty (Olympus): negative values, they will just truncate the Gaussian and normalize it so that it remains a density.

988
02:05:45.500 --> 02:05:45.870
Lad Prachikumari Vijaykumar .: Okay.

989
02:05:45.870 --> 02:05:57.140
Faculty (Olympus): So, yeah, all of those things you have to take into account when you are creating your model. You have to be aware, at least, of the fact that whether you're modeling the important things or you're not modeling the important characteristics.

990
02:05:58.040 --> 02:06:11.070
Lad Prachikumari Vijaykumar .: Okay, and, sir, last, like, for medium, 15 marks, so what is the exam duration, like, one and a half hours, or one hour, likeâ€¦

991
02:06:11.070 --> 02:06:20.390
Faculty (Olympus): I don't recall, I haven't yet decided that, we will, we will announce it, what the duration will be.

992
02:06:21.090 --> 02:06:22.360
Lad Prachikumari Vijaykumar .: Okay.

993
02:06:22.360 --> 02:06:31.959
Vamsi Krishna Mutnuri .: a small extension on the same question of the bus. What if we ask that a person arrived at 10.5, and what is the probability that the bus has left?

994
02:06:32.780 --> 02:06:34.220
Vamsi Krishna Mutnuri .: Then, whatâ€¦

995
02:06:34.670 --> 02:06:43.900
Faculty (Olympus): So here, I mean, the busâ€¦ bus leaves at fixed times, right? There is no randomness in the bus when the bus comes and when the bus leaves.

996
02:06:44.520 --> 02:06:56.200
Faculty (Olympus): If there was randomness in that, then sure, you can ask this question, but weâ€¦ theâ€¦ at least the setup that we were talking about, there is no randomness in the busâ€¦ in the arrival and departure of the bus.

997
02:06:56.780 --> 02:06:59.269
Faculty (Olympus): The randomness was only in when you arrive.

998
02:06:59.920 --> 02:07:05.129
Faculty (Olympus): So, if you tell me that you have arrived at 10.5, then you will catch the bus.

999
02:07:05.560 --> 02:07:08.940
Faculty (Olympus): But if you arrive at 10-6, then you would have missed the bus.

1000
02:07:10.780 --> 02:07:11.939
Vamsi Krishna Mutnuri .: Understood, sir, understood.

1001
02:07:11.940 --> 02:07:12.860
Faculty (Olympus): Yeah.

1002
02:07:13.730 --> 02:07:16.370
Faculty (Olympus): Okay, rahul?

1003
02:07:17.290 --> 02:07:40.919
Rahul Joshi .: Sorry, just one question. Weâ€¦ using the probability mass function, we calculate, what is the particular probability for value, let's say, for 10 probabilities point for you, for 11, whatever, by using various distributions. But, each distribution, depending on the data, has some variance, right? So these variance formulas areâ€¦

1004
02:07:41.000 --> 02:07:44.330
Rahul Joshi .: To, calculate theâ€¦

1005
02:07:44.440 --> 02:07:53.199
Rahul Joshi .: I'm going to say, expected variance, or it is actual variance for the data, because I'm a little confused, in that context.

1006
02:07:53.200 --> 02:07:59.919
Faculty (Olympus): So, I mean, see, there are two different things which I think are getting mixed up here. One is, there isâ€¦

1007
02:08:00.160 --> 02:08:10.190
Faculty (Olympus): Probability distribution, There is a random variable, there is a probability distribution, and the variance is justâ€¦

1008
02:08:10.400 --> 02:08:23.849
Faculty (Olympus): You can think of that as, like, a function of the probability distribution, if you want the PMF. Let's say if X was discrete, then there is a PMF, the function isâ€¦ the variance is just a function of the PMF.

1009
02:08:24.290 --> 02:08:35.830
Faculty (Olympus): It is just an actual constant, right? It is expected value of X squared minus mu X squared. If I give you the probability distribution, you will be able to compute this quantity.

1010
02:08:37.330 --> 02:08:37.800
Faculty (Olympus): Okay.

1011
02:08:37.800 --> 02:08:43.480
Rahul Joshi .: here, expected value. Expected value itself is calculated based on the PMF, right?

1012
02:08:43.740 --> 02:08:51.460
Faculty (Olympus): Yeah, yeah, so this isâ€¦ this is also computed from the PMF, this is also computed from the PMF. I give you the PMF, you can compute this quantity.

1013
02:08:53.000 --> 02:08:55.620
Rahul Joshi .: Can you take a small example and explain that, sir, if you don't mind?

1014
02:08:55.620 --> 02:09:03.000
Faculty (Olympus): Yeah, I mean, like we did for the uniform distribution, right? I tell you that X is

1015
02:09:03.440 --> 02:09:11.030
Faculty (Olympus): distributed uniform between A and B, you can compute the average value to be A plus B by 2,

1016
02:09:11.520 --> 02:09:25.289
Faculty (Olympus): you can compute the expected value of X squared, that was, I think, B cubed minus A cubed by 3 times B minus A, and so you can combine these two things and get the variance.

1017
02:09:29.290 --> 02:09:35.110
Faculty (Olympus): So, all of this calculation is just being done from the fact that I gave you the distribution.

1018
02:09:36.260 --> 02:09:37.820
Faculty (Olympus): There is no data, nothing.

1019
02:09:37.820 --> 02:09:38.480
Rahul Joshi .: detected

1020
02:09:38.770 --> 02:09:50.600
Rahul Joshi .: Yeah, so here, expected value of X squared, because A and B is fixed, right? A and B is given already. Yeah, yeah. So, and then the actual random variable can be anywhere between A and B.

1021
02:09:50.790 --> 02:09:51.530
Faculty (Olympus): Correct.

1022
02:09:51.530 --> 02:10:02.830
Rahul Joshi .: Isn't it? So whenever we are calculating the expected value of X squared, okay, let's say A is 2 and P is 3, and a random variable is, let's say, 2.1.

1023
02:10:03.160 --> 02:10:07.540
Rahul Joshi .: So, 2.1 square, is it going to be exactly same asâ€¦

1024
02:10:07.540 --> 02:10:12.590
Faculty (Olympus): No, no, random variable is not 2. What do you mean random variable is 2.1?

1025
02:10:13.990 --> 02:10:17.370
Rahul Joshi .: means a random variable can be any value between A and B, right?

1026
02:10:17.790 --> 02:10:21.650
Faculty (Olympus): So, there is a certainâ€¦ firstly, I mean, there is a certainâ€¦

1027
02:10:21.780 --> 02:10:29.650
Faculty (Olympus): probability associated with the random variable taking values in different intervals, right? Like you said, I mean, this can beâ€¦

1028
02:10:30.200 --> 02:10:36.450
Faculty (Olympus): a value between A to B, the probability that it lies somewhere here.

1029
02:10:37.550 --> 02:10:49.479
Faculty (Olympus): is going to be whatever the length of that interval is. Similarly, the probability that it lies somewhere here is going to be proportional to the length of that interval, and so on.

1030
02:10:49.820 --> 02:11:01.089
Faculty (Olympus): Right? So, when I say expected value of X squared, you are computing, you're averaging over all the different values that it can take, along with the corresponding probabilities.

1031
02:11:01.570 --> 02:11:07.450
Faculty (Olympus): Right? I mean, for aâ€¦ for aâ€¦ this is better seen in, maybe, if X as a PMF.

1032
02:11:07.800 --> 02:11:08.660
Faculty (Olympus): Right?

1033
02:11:08.800 --> 02:11:09.470
Faculty (Olympus): Soâ€¦

1034
02:11:09.470 --> 02:11:09.980
Rahul Joshi .: Yep.

1035
02:11:11.000 --> 02:11:18.169
Faculty (Olympus): when we say expected value of X square, we are seeing, okay, what are the different values that X square can take?

1036
02:11:18.500 --> 02:11:29.940
Faculty (Olympus): Okay, so suppose ifâ€¦ if the PMF wasâ€¦ let's say, X can take values 0, 1, and 2, with probability 1 by 4, 1 by 2, 1 by 4.

1037
02:11:30.170 --> 02:11:38.210
Faculty (Olympus): So you are seeing, when you ask me what is the expected value of X squared, I'm going to see what are the different values that X square can take. It can take a value 0,

1038
02:11:38.470 --> 02:11:41.029
Faculty (Olympus): The probability of that is 1 by 4.

1039
02:11:41.480 --> 02:11:43.559
Faculty (Olympus): It can take a value 1,

1040
02:11:43.770 --> 02:11:46.180
Faculty (Olympus): The probability of that is half.

1041
02:11:46.750 --> 02:11:53.729
Faculty (Olympus): It can take a value 4, the probability of that is 1 by 4. So this is the expected value of X squared.

1042
02:11:55.360 --> 02:12:02.199
Faculty (Olympus): It is seeing what are the different values that X squared can potentially take, and what are the corresponding probabilities.

1043
02:12:03.460 --> 02:12:05.569
Faculty (Olympus): And you're computing that average out.

1044
02:12:06.760 --> 02:12:12.639
Rahul Joshi .: So, so, okay, so whatever are these 0 into 1 by 4, that is the individual values X can take, right?

1045
02:12:12.640 --> 02:12:15.999
Faculty (Olympus): Yeah, so this is, like, 0 square, 1 square, and 2 square.

1046
02:12:19.150 --> 02:12:21.410
Rahul Joshi .: Skero Square, 1 square, andâ€¦

1047
02:12:21.410 --> 02:12:27.899
Faculty (Olympus): X square can either beâ€¦ X can be either 0, 1, 2, so X square can be either 0 square, or 1 square, or 2 square.

1048
02:12:28.920 --> 02:12:30.989
Faculty (Olympus): Right? This is 2 square.

1049
02:12:33.330 --> 02:12:39.799
Rahul Joshi .: Okay, or is it the calculation of this, like, 0 into 1x4 plus 1 into 1, and then the bracket square?

1050
02:12:39.800 --> 02:12:42.370
Faculty (Olympus): No, no, no. Expected value of X square.

1051
02:12:42.950 --> 02:12:46.879
Faculty (Olympus): This X square is the thing that I'm computing. That is this quantity.

1052
02:12:49.390 --> 02:12:50.759
Faculty (Olympus): That is this quantity.

1053
02:12:51.870 --> 02:12:58.010
Faculty (Olympus): I'm not computingâ€¦ what you are saying is going to be expectâ€¦ you compute expected value of X, and then you square it.

1054
02:12:58.320 --> 02:13:00.020
Faculty (Olympus): That is a different quantity.

1055
02:13:01.510 --> 02:13:02.839
Rahul Joshi .: Oh, that is a mean square, right?

1056
02:13:02.840 --> 02:13:04.389
Faculty (Olympus): That is the mean square.

1057
02:13:04.830 --> 02:13:08.239
Faculty (Olympus): The difference of these two is, in fact, going to give me the variance.

1058
02:13:12.700 --> 02:13:18.760
Rahul Joshi .: Yeah, now I understood. I got it, sir. Now I understood, yeah, thank you. Okay. This was a confusion I had for a long time, actually. I see.

1059
02:13:18.930 --> 02:13:19.610
Faculty (Olympus): Okay.

1060
02:13:20.200 --> 02:13:20.950
Rahul Joshi .: Thank you.

1061
02:13:20.950 --> 02:13:23.499
Faculty (Olympus): Okay, yeah, Harshad?

1062
02:13:23.710 --> 02:13:32.019
Harshad Dilip Behere .: Yeah, good afternoon, Professor. Now, just coming to this same example, when we say 0 squared into 1 by 4, this is according to a formula which we have seen earlier, right?

1063
02:13:32.020 --> 02:13:32.820
Faculty (Olympus): Yeah, yeah.

1064
02:13:32.860 --> 02:13:36.689
Harshad Dilip Behere .: I mean, this will vary based on distribution, am I right?

1065
02:13:36.690 --> 02:13:40.649
Faculty (Olympus): Yeah, yeah, yeah, this willâ€¦ this was only for this particular PMF.

1066
02:13:40.720 --> 02:13:55.600
Harshad Dilip Behere .: Right, and coming back to the bus example, I know that we discussed about normal versus continuous distribution, so is it quite possible that, you know, on a particular given scenario, there might be more than one or two distributions getting applied, and both of them are correct? Soâ€¦

1067
02:13:55.600 --> 02:14:14.489
Faculty (Olympus): Yeah, yeah, I mean, ultimately, it's a modeling thing. You know, some model might be a better fit to your data or your situation than other models. There could be multiple viable models, and then you tryâ€¦ yeah, you try to fit different distributions, and then you see which one fits the best.

1068
02:14:15.170 --> 02:14:23.549
Harshad Dilip Behere .: Yeah, I mean, tailoring this to, for example, a given question, so we can arrive at an answer via different ways, and both will be taken as incorrect answer.

1069
02:14:23.550 --> 02:14:34.389
Faculty (Olympus): Yeah, yeah, I mean, if we are takingâ€¦ if we have intentionally kept it vague, and we are saying, you choose a distribution, then of course, then we have to allow for possibleâ€¦ different possible answers.

1070
02:14:34.390 --> 02:14:35.120
Harshad Dilip Behere .: But ifâ€¦

1071
02:14:35.120 --> 02:14:38.940
Faculty (Olympus): If we are specifying the distribution, then we expect you to work with that distribution, yeah.

1072
02:14:39.270 --> 02:14:41.199
Harshad Dilip Behere .: Okay, fine. Thank you, Provost.

1073
02:14:42.010 --> 02:14:43.170
Faculty (Olympus): Devendra?

1074
02:14:43.970 --> 02:14:50.210
Devendra Parmar .: Sir, my question was, like, in last lectures, one of the last lectures, you had mentioned that

1075
02:14:50.410 --> 02:14:59.769
Devendra Parmar .: for a given data set, or for a given data, if we calculate the mean, then it is also called as some timely mean, right? Correct me if I'm wrong.

1076
02:15:00.030 --> 02:15:05.500
Devendra Parmar .: And this expectation is called as some statistical mean.

1077
02:15:05.500 --> 02:15:12.319
Faculty (Olympus): So, yeah, I was saying time averageâ€¦ Versus statistical average.

1078
02:15:12.890 --> 02:15:16.049
Devendra Parmar .: So, is the same applicable for this variance as well, sir?

1079
02:15:16.050 --> 02:15:18.359
Faculty (Olympus): Yeah, yeah, yeah. So there is the notion ofâ€¦

1080
02:15:18.720 --> 02:15:23.950
Faculty (Olympus): I mean, yeah, it's like, it's someâ€¦ so this time average is also sometimes called empirical average.

1081
02:15:25.040 --> 02:15:28.030
Faculty (Olympus): So, there is a notion of an empirical variance.

1082
02:15:30.500 --> 02:15:33.330
Faculty (Olympus): Versus statistical variance.

1083
02:15:34.990 --> 02:15:43.080
Faculty (Olympus): So, empirical variance would exactly be, okay, you have a dataset which has different values, X1, X2, X3,

1084
02:15:43.210 --> 02:15:44.369
Faculty (Olympus): And so on.

1085
02:15:44.910 --> 02:15:46.130
Faculty (Olympus): Till XN.

1086
02:15:47.450 --> 02:15:54.180
Faculty (Olympus): If I have to compute the empirical variance, what I'll do is I'll first compute the empirical mean.

1087
02:15:54.380 --> 02:15:57.259
Faculty (Olympus): Which is, let's say, mu Xâ€¦

1088
02:15:57.830 --> 02:16:01.630
Faculty (Olympus): bar. This is going to beâ€¦ the average.

1089
02:16:03.050 --> 02:16:06.859
Faculty (Olympus): of the n values, and then I will comâ€¦

1090
02:16:07.060 --> 02:16:15.150
Faculty (Olympus): for everyâ€¦ every point, I will compute what is the square deviation from this one. So it'll be Xi minus mu X bar.

1091
02:16:15.600 --> 02:16:21.090
Faculty (Olympus): squared. This is the deviation that data point I has from the average.

1092
02:16:21.210 --> 02:16:24.989
Faculty (Olympus): And then I'll look at the average of this over the N.

1093
02:16:25.560 --> 02:16:26.700
Faculty (Olympus): samples.

1094
02:16:26.920 --> 02:16:30.039
Faculty (Olympus): So this is going to be my empirical variance.

1095
02:16:30.690 --> 02:16:37.459
Faculty (Olympus): The statistical variance is more about having a certain, distribution according to which

1096
02:16:37.809 --> 02:16:50.369
Faculty (Olympus): each XI is getting, let's say, is distributed according to some FX, and then you are looking at the variance of this FX. So that is just a function of the distribution.

1097
02:16:50.780 --> 02:16:52.290
Devendra Parmar .: Got it, got it. So there is no dataâ€¦

1098
02:16:52.299 --> 02:16:53.209
Faculty (Olympus): involved there.

1099
02:16:53.879 --> 02:17:01.699
Devendra Parmar .: Okay. So, sir, one thing, can we say that if that, empirical variance for a particular distribution is larger.

1100
02:17:01.950 --> 02:17:02.280
Faculty (Olympus): Hmm.

1101
02:17:02.280 --> 02:17:12.260
Devendra Parmar .: Then, variants, like, if you draw, let's say, a huge number of samples from that distribution, then variants would also be relatively larger.

1102
02:17:12.850 --> 02:17:17.040
Faculty (Olympus): Yeah, so if you, if you, if you, for example, if there is a distribution.

1103
02:17:17.370 --> 02:17:19.830
Faculty (Olympus): Right? Whose variance is large.

1104
02:17:20.090 --> 02:17:23.380
Faculty (Olympus): And you draw many, many samples from that distribution.

1105
02:17:24.240 --> 02:17:29.059
Faculty (Olympus): Okay? And then you compute this empirical quantity, that is going to also be large.

1106
02:17:30.540 --> 02:17:31.450
Devendra Parmar .: Got it.

1107
02:17:31.459 --> 02:17:31.979
Faculty (Olympus): Yeah.

1108
02:17:32.420 --> 02:17:33.540
Devendra Parmar .: Okay, thank you, sir.

1109
02:17:33.540 --> 02:17:34.209
Faculty (Olympus): Okay.

1110
02:17:34.860 --> 02:17:38.600
Faculty (Olympus): Alright, okay, we'll end here. I'll see you guys next time.

1111
02:17:38.830 --> 02:17:39.900
Tushar Sachdev .: Thank you, Professor.

1112
02:17:40.059 --> 02:17:40.969
Faculty (Olympus): Yep, bye.

