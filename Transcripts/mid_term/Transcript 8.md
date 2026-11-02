WEBVTT

1
00:12:52.500 --> 00:12:59.360
Faculty (Olympus): Hi, Rupal, can you please confirm if you can hear me okay, and my screen is visible?

2
00:12:59.550 --> 00:13:02.530
Rupal Makhijani: Yes, so I can hear you, and screen is okay.

3
00:13:02.530 --> 00:13:03.779
Faculty (Olympus): Alright, okay, thanks.

4
00:13:06.720 --> 00:13:13.289
Faculty (Olympus): Okay, while we wait, I'm happy to take any questions that might be there.

5
00:13:21.630 --> 00:13:28.719
Akash Deep Sharma .: Hey, Professor, this is Akash. I just posted, one question, not for you, for, for, great learning guys, for Rupal.

6
00:13:46.070 --> 00:13:56.530
Rupal Makhijani: Hi, so whatever the queries that you may have for us, for Great Learning to be specific, that will be catered post-session. So, either you can call me, drop me an email, or connect with me via WhatsApp.

7
00:13:56.690 --> 00:14:00.970
Rupal Makhijani: But during the session time, we'll focus on the academic concerns only.

8
00:18:24.980 --> 00:18:26.550
Faculty (Olympus): Yeah, Shirley, please go ahead.

9
00:18:27.070 --> 00:18:31.510
Shirley Menezes .: Sam, will you be covering normal random variable as well?

10
00:18:32.370 --> 00:18:33.060
Faculty (Olympus): COVIDâ€¦

11
00:18:33.060 --> 00:18:34.009
Shirley Menezes .: Good exit.

12
00:18:35.040 --> 00:18:40.680
Faculty (Olympus): Yeah, we did discuss the normalâ€¦ so normal random variability, same as Gaussian.

13
00:18:41.110 --> 00:18:42.220
Shirley Menezes .: Oh, okay, okay.

14
00:18:42.220 --> 00:18:42.840
Faculty (Olympus): names.

15
00:18:43.310 --> 00:18:46.399
Shirley Menezes .: Okay, okay. Yeah. Thanks, thank you.

16
00:18:46.400 --> 00:18:59.800
Faculty (Olympus): you might, encounter standard normal distributed, distributed random variable, which just means normal random variable or Gaussian random variable, but with mean 0 and variance 1.

17
00:19:00.550 --> 00:19:04.910
Faculty (Olympus): Okay. That's called standard normal, so it'sâ€¦ normal is just the same as Gaussian.

18
00:19:05.540 --> 00:19:08.969
Shirley Menezes .: Okay, alrighty, that's where I got confused. Thank you, sir.

19
00:19:08.970 --> 00:19:09.510
Faculty (Olympus): Sure.

20
00:20:12.150 --> 00:20:15.990
Faculty (Olympus): Okay, let's get started.

21
00:20:16.550 --> 00:20:24.369
Faculty (Olympus): Before maybe we begin, if there are any quick questions, please feel free to ask now.

22
00:20:25.130 --> 00:20:31.910
Faculty (Olympus): Yeah, maybe I'll wait for a minute, and then we'll begin with expectation.

23
00:20:32.740 --> 00:20:45.400
PALAK GOEL .: Good evening, Professor. I had one caution on the caution distribution that we did last semâ€¦ last and last lecture. So, the formula that you have given for f of x

24
00:20:45.400 --> 00:20:54.359
PALAK GOEL .: I mean, are we gonna use that kind of formulas during the course, or is it, like, we are just gonna plug in the numbers, or are we just understanding the distribution?

25
00:20:55.770 --> 00:21:01.939
Faculty (Olympus): So, I mean, that is how the density is defined for the Gaussian distribution.

26
00:21:02.060 --> 00:21:11.329
Faculty (Olympus): We will use, so, of course, that is what that distribution hasâ€¦ Various properties.

27
00:21:11.780 --> 00:21:22.050
Faculty (Olympus): And some of them we'll see today. For example, the Gaussian distribution is, specified withâ€¦ by these two parameters, mu and sigma square.

28
00:21:22.120 --> 00:21:40.040
Faculty (Olympus): what are the operational meanings of that mu, what is the operational meaning of sigma square? Plus, you know, what happens if you combine Gaussians, and so on. So, yeah, there'll be several different things which come out of that expression, or the way that density is defined.

29
00:21:42.220 --> 00:21:51.330
Faculty (Olympus): But yeah, I mean, ultimately, it's an expression. It turns out to have several nice properties, which is why Gaussian distributions are used all the time.

30
00:21:51.580 --> 00:21:55.560
Faculty (Olympus): So it'll comeâ€¦ I mean, especially the Gaussian distribution will come again and again.

31
00:21:56.480 --> 00:22:17.190
PALAK GOEL .: No, no, that's understood that we will have the normal distribution coming up. We also have normal distribution coming up in our fields as well, if you're doing Monte Carlo or anything. What I wanted to understand was, is it is one thing to understand what the distribution is, how is it defined? And it's totally different to understand, you know, to remember the density and use it in formulas and stuff.

32
00:22:18.550 --> 00:22:32.170
Faculty (Olympus): Yeah, I mean, you don't have to, if you're asking me, yeah, do youâ€¦ do you necessarily have to remember the density? No, I mean, yeah, it's not necessarily needed, but I think as an

33
00:22:32.630 --> 00:22:39.659
Faculty (Olympus): Yeah, because you will again and again use it, it'll automatically happen that you will remember the form.

34
00:22:40.020 --> 00:22:45.419
Faculty (Olympus): But yeah, it's not something that is absolutely critical that you remember the density from. No, not really.

35
00:22:45.660 --> 00:22:47.350
PALAK GOEL .: Oh, thank you.

36
00:22:47.540 --> 00:23:01.459
Faculty (Olympus): Okay, okay, let's begin. So we are going to, so we've talked about, so far, we've talked about the notion of a random variable. We have, seen that random variables are defined, byâ€¦

37
00:23:01.810 --> 00:23:09.759
Faculty (Olympus): So, we have talked about random variables, we have seen the notion of a cumulative distribution function, which is associated with

38
00:23:09.910 --> 00:23:24.509
Faculty (Olympus): every random variable. We then saw two different types of random variables, a discrete random variable and continuous random variable. We saw that discrete random variables can equivalently be defined via their probability mass function.

39
00:23:24.780 --> 00:23:33.420
Faculty (Olympus): Continuous random variables can equivalently be defined via the probability density function, right? And discrete random variables are roughly those which have

40
00:23:33.700 --> 00:23:38.170
Faculty (Olympus): Finite support, or countable support, and continuous random variables.

41
00:23:38.500 --> 00:23:43.030
Faculty (Olympus): Those which don't necessarily have this finite, support.

42
00:23:43.180 --> 00:23:43.960
Faculty (Olympus): Right?

43
00:23:44.120 --> 00:23:54.410
Faculty (Olympus): So, we know how to characterize random variables. Today, we are going to start with the notion of the expected value, or the expectation of a random variable.

44
00:24:01.320 --> 00:24:07.329
Faculty (Olympus): Okay? So, like we know, a random variable, essentially.

45
00:24:07.510 --> 00:24:19.249
Faculty (Olympus): will takeâ€¦ it's a function which takes elements from a sample space and gives a real number, right, or a real value

46
00:24:20.680 --> 00:24:23.409
Faculty (Olympus): To every experiment that you conduct.

47
00:24:24.480 --> 00:24:25.220
Faculty (Olympus): Right.

48
00:24:26.460 --> 00:24:30.820
Faculty (Olympus): And, the expectation of a random variable

49
00:24:31.730 --> 00:24:34.689
Faculty (Olympus): When we talk about expectation of

50
00:24:35.270 --> 00:24:44.259
Faculty (Olympus): a random variable. What it is trying to do is it's trying to mimic Kind of the average

51
00:24:44.900 --> 00:24:54.859
Faculty (Olympus): Of the values One expects to see if you draw from this random variable many, many times.

52
00:24:55.210 --> 00:25:07.620
Faculty (Olympus): So, one expects to seeâ€¦ If we drawâ€¦ multiple samples, Multiple samples.

53
00:25:08.470 --> 00:25:23.930
Faculty (Olympus): from the random variable, or from the distribution corresponding to the random variable. So if I draw many, many samples, what is the average value that I expect to see of those samples, right? That is what the expected value of a random variable seeks

54
00:25:24.160 --> 00:25:32.589
Faculty (Olympus): to mimic or seeks to formalize. So, here, here is the motivation. Let's say, let's take X to be a discrete random variable.

55
00:25:33.180 --> 00:25:35.750
Faculty (Olympus): Right? Which means that there is someâ€¦

56
00:25:35.960 --> 00:25:41.200
Faculty (Olympus): support set of X. These are the values that X takes, let's say.

57
00:25:41.680 --> 00:25:42.430
Faculty (Olympus): Okay?

58
00:25:43.230 --> 00:25:52.529
Faculty (Olympus): Now, let's say I draw n samples, or I do N experiments, or I draw n samples.

59
00:25:52.820 --> 00:25:56.570
Faculty (Olympus): from the distribution, or the PMF associated with X.

60
00:25:56.760 --> 00:26:05.040
Faculty (Olympus): Right? And when I do that, let's say for every element k in the support set, I get NKâ€¦

61
00:26:05.200 --> 00:26:14.499
Faculty (Olympus): observations. Which means, in NK of the experiments, the random variable, when I draw a sample from it, I get the value K.

62
00:26:14.880 --> 00:26:18.350
Faculty (Olympus): Right? So summation of NK is going to be N.

63
00:26:18.910 --> 00:26:32.570
Faculty (Olympus): Right? For every element in the support set, let's say I get NK observations. For example, if X was a discrete random variable whose support was 0, 1, 2, then N0 correspondâ€¦ and you, let's say, do

64
00:26:32.570 --> 00:26:45.910
Faculty (Olympus): N, you draw n samples of this, random variable, then N0 says how many times you observe 0, n1 says how many times you observe 1, N2 says how many times you observed 2.

65
00:26:46.320 --> 00:26:52.139
Faculty (Olympus): Okay? Now, if I talk about the average of these values.

66
00:26:52.910 --> 00:27:00.229
Faculty (Olympus): that you see, what would that be? Right? The average would be, you will sum over all the different values.

67
00:27:00.830 --> 00:27:02.630
Faculty (Olympus): It'll be K timesâ€¦

68
00:27:03.010 --> 00:27:12.939
Faculty (Olympus): NK, right? Because you observe K nk times, so the overall sum of the values that you see is going to be

69
00:27:13.050 --> 00:27:20.349
Faculty (Olympus): summation k times NK, and because we are looking at the average, we'll divide by the total number of times we did the sample.

70
00:27:20.710 --> 00:27:27.020
Faculty (Olympus): Right? So this is the average of the values. If I just rewrite this, this is summationâ€¦ Cheers.

71
00:27:27.270 --> 00:27:31.159
Faculty (Olympus): Summing over all different values that this random variable can take.

72
00:27:31.360 --> 00:27:34.789
Faculty (Olympus): K times NK by N.

73
00:27:35.430 --> 00:27:39.459
Faculty (Olympus): Right? Now, think about this quantity.

74
00:27:40.060 --> 00:27:42.869
Faculty (Olympus): What do you expect this quantity

75
00:27:43.300 --> 00:27:55.980
Faculty (Olympus): to look like as N becomes large, or as the number of samples that you have drawn becomes very, very large, what do you think will happen to the fraction of times you observe a particular value K?

76
00:27:56.250 --> 00:28:09.089
Faculty (Olympus): Right? So, if I think about the probability associated with K, right, what does the PMF tell us? The PMF tells us what is the probability, or PX,

77
00:28:09.810 --> 00:28:19.360
Faculty (Olympus): is the PMF. PXK tells me the probability that X is going to be equal to K when I draw a sample from it, right?

78
00:28:19.740 --> 00:28:20.560
Faculty (Olympus): Soâ€¦

79
00:28:20.680 --> 00:28:32.400
Faculty (Olympus): If you think about how we motivate, the notion of probability, this is essentially going to be close to the fraction of times you will observe the value K

80
00:28:32.550 --> 00:28:47.540
Faculty (Olympus): when you draw, many, many samples from this distribution, right? So as N becomes large, I expect this quantity to start becoming closer and closer to the PMF value associated with K.

81
00:28:47.950 --> 00:28:59.759
Faculty (Olympus): Right? The fraction of times you see the value K is going to become closer and closer to the probability value, or the PMF value that is associated with K.

82
00:28:59.940 --> 00:29:08.990
Faculty (Olympus): That is ourâ€¦ that is theâ€¦ kind of the whole notion behind probability, or that is how one intuitively understands probability.

83
00:29:09.890 --> 00:29:17.539
Faculty (Olympus): we will formalize this notion that NK by N actually becomes closer and closer to this value of the PMF,

84
00:29:17.990 --> 00:29:26.669
Faculty (Olympus): This is something that can be formalized, and we will talk about it in one of the lectures. This is done via this notion of law of large numbers. We'll come to that.

85
00:29:27.000 --> 00:29:43.330
Faculty (Olympus): But, that is the idea. So now, suppose n is very, very large, then essentially this quantity, this average of the values that you are seeing, is going to become closer and closer to summation k times PXK.

86
00:29:43.600 --> 00:29:47.839
Faculty (Olympus): And you're summing overâ€¦ All elements in the support.

87
00:29:48.350 --> 00:29:50.719
Faculty (Olympus): Okay? And this is exactlyâ€¦

88
00:29:51.300 --> 00:30:02.169
Faculty (Olympus): what is called the expected value of the random variable X. So this is the definition of the expected value of X for a discrete random variable.

89
00:30:02.730 --> 00:30:20.100
Faculty (Olympus): Okay? And the idea is, this quantity is essentially mimickingâ€¦ you should think of the expected value of a random variable asâ€¦ as exactly in this form. That thisâ€¦ you should think of that as, if I draw many, many samples from this distribution, right? What is the average

90
00:30:20.100 --> 00:30:30.490
Faculty (Olympus): value that I'll see. I sum up all the values that I've seen, divide them by the total number of samples, what would that quantity look like? Essentially, that quantity is going to look very much like

91
00:30:30.610 --> 00:30:32.189
Faculty (Olympus): This expected value.

92
00:30:32.680 --> 00:30:44.109
Faculty (Olympus): Okay? So that is what expectation is mimicking, or that is what the operational meaning of expectation is. Now, this is for a discrete random variable. For a continuous random variable.

93
00:30:44.970 --> 00:30:48.299
Faculty (Olympus): Also, things are very similar, so for a continuous

94
00:30:48.880 --> 00:30:51.849
Faculty (Olympus): random variable X, which is nowâ€¦

95
00:30:52.140 --> 00:30:56.310
Faculty (Olympus): defined according to a PDF, right, a density function.

96
00:30:56.460 --> 00:31:06.390
Faculty (Olympus): the expected value of X is just going to beâ€¦ the summation gets replaced by the integral, so you get summation X times

97
00:31:06.600 --> 00:31:07.790
Faculty (Olympus): the density.

98
00:31:09.020 --> 00:31:11.749
Faculty (Olympus): Yeah, and you sum it over the real numbers.

99
00:31:13.840 --> 00:31:18.479
Faculty (Olympus): Okay, so these are the two, definitions of

100
00:31:18.690 --> 00:31:24.130
Faculty (Olympus): Expectation, one for discrete random variables, and one for continuous random variables.

101
00:31:25.720 --> 00:31:37.409
Faculty (Olympus): Okay, so I will, do a few examples now, but maybe before, going to examples, let me quickly take a few questions. Yeah, Gaurav?

102
00:31:38.110 --> 00:31:43.239
Gaurav Singh .: Yeah, Professor, so isn't it, like, an expected value is a mean? Mean ofâ€¦

103
00:31:43.870 --> 00:31:47.089
Faculty (Olympus): So, you can think of this as a weighted average, yes.

104
00:31:47.090 --> 00:31:47.979
Gaurav Singh .: Mr. Devin, okay.

105
00:31:47.980 --> 00:31:56.240
Faculty (Olympus): average. So I'm looking at different values that this random variable can take, and I'm weighing them by the corresponding probability.

106
00:31:56.940 --> 00:31:58.389
Gaurav Singh .: Got it, got it.

107
00:31:58.390 --> 00:31:59.030
Faculty (Olympus): Yeah.

108
00:31:59.440 --> 00:32:01.610
Faculty (Olympus): Okay, Abhishek?

109
00:32:02.460 --> 00:32:08.009
Abhishek Agrawal .: Yeah, hello. So, I didn't get the meaning of, support. What is support?

110
00:32:08.010 --> 00:32:19.309
Faculty (Olympus): Support is just, what values can that random variable take? So, for example, if it's a Bernoulli random variable, then it can take values either 0 or 1. If it is,

111
00:32:19.310 --> 00:32:34.439
Faculty (Olympus): let's say a geometric random variable, then it can take values 1, 2, 3, 4, all natural numbers. If it's an exponential random variable, then it can take any positive real number, and so on. So that's what I mean by the support.

112
00:32:35.340 --> 00:32:40.280
Faculty (Olympus): Support means what are the possible different values that this random variable can take?

113
00:32:41.230 --> 00:32:43.340
Abhishek Agrawal .: Okay, okay, okay, thank you.

114
00:32:43.680 --> 00:32:44.610
Faculty (Olympus): Rahul?

115
00:32:47.400 --> 00:32:57.869
Rahul Joshi .: Sorry, sir, yeah, the question is, for the continuous random variable, we have to integrate the function, that is understood, but what will be theâ€¦ from what value to what value we have to integrate?

116
00:32:57.870 --> 00:33:02.339
Faculty (Olympus): Just the real line, so maybe, okay, letâ€¦ so this isâ€¦

117
00:33:03.250 --> 00:33:22.380
Faculty (Olympus): Ganges from minus infinity to infinity. Now, it could very well be that the density itself is zero in some part over this real line, right? For example, for an exponential distribution, we know that the density is positive only for positive values, so that part of the integral will just be 0.

118
00:33:22.840 --> 00:33:31.899
Faculty (Olympus): minus infinity to 0 will be 0, and you can then convert this integral back to just 0 to infinity. But in general, this is what the integral looks like.

119
00:33:35.440 --> 00:33:36.889
Faculty (Olympus): Does that answer your question?

120
00:33:36.890 --> 00:33:54.699
Rahul Joshi .: Sorry, just follow-up question, sir. So, if we have to calculate the expected value of the, continuous random variable, theâ€¦ do we have to doâ€¦ let's say if there is a function, which is, like, whatever is theâ€¦ whatever is that function, we have to fully integrate for minus infinity to.

121
00:33:54.700 --> 00:33:58.929
Faculty (Olympus): So, maybe let's do aâ€¦ I'll do a few examples, and then maybe this will be clear.

122
00:33:58.930 --> 00:33:59.780
Rahul Joshi .: Okay, fine, thank you.

123
00:33:59.940 --> 00:34:01.469
Faculty (Olympus): Sure. Abhineet?

124
00:34:02.300 --> 00:34:05.570
Abhineet Bansal: So, can you explain what is that dot in the bracket refers to?

125
00:34:05.570 --> 00:34:17.530
Faculty (Olympus): Oh, nothing, it's just, this is where the argument goes in, and nothing, it's just notation, there's notâ€¦ yeah, notâ€¦ it's just supposed to be the placeholder for the argument of that function.

126
00:34:17.719 --> 00:34:21.020
Faculty (Olympus): But yeah, and you don't have to worry about it, yeah.

127
00:34:22.690 --> 00:34:24.110
Faculty (Olympus): summer?

128
00:34:24.460 --> 00:34:37.569
Samar .: Yeah, so, sir, in this, continuous formula, random variable formula, this X represents the number of, kind of, samples,

129
00:34:38.070 --> 00:34:41.769
Faculty (Olympus): So here, I mean, I would say it's,

130
00:34:42.250 --> 00:35:00.500
Faculty (Olympus): So think of it like the different values that, the random variable can take, and it's weighing them byâ€¦ so think of, yeah, so maybe, again, so let's sayâ€¦ let's say that you have a density like this, okay? And, this is yourâ€¦

131
00:35:01.690 --> 00:35:09.380
Faculty (Olympus): X, and this is your density, right? So this isâ€¦ you're picking a certain value of X, and the weight

132
00:35:09.380 --> 00:35:23.129
Faculty (Olympus): is essentiallyâ€¦ you can think of that as, how much weight does that have, or how much probability do you have to get a value which is very, very close to X? That's like FX times DX, right?

133
00:35:23.230 --> 00:35:25.020
Faculty (Olympus): If you think of a very small.

134
00:35:25.020 --> 00:35:25.580
Samar .: Myâ€¦

135
00:35:25.580 --> 00:35:39.109
Faculty (Olympus): margin around X, that is the probability that you will get a value which is very close to X. And then you're summing over all possible such values, which essentially becomes an integral, because you're taking many, very, many, many thin strips.

136
00:35:39.580 --> 00:35:43.019
Samar .: So, in a way, we can also say it like that. It's aâ€¦

137
00:35:43.630 --> 00:35:50.629
Samar .: density of that parameter at a particular point. Like, when I say density, it's more like a count or something.

138
00:35:50.630 --> 00:36:01.529
Faculty (Olympus): Yeah, so it's not quite density, but yeah, I mean, you can roughly think of, okay, you are thinking about how likely it is to see a certain value.

139
00:36:01.570 --> 00:36:14.830
Faculty (Olympus): Not an actual value X, because we know the probability of seeing an actual value X for a continuous random variable is 0, but a value which is very close to X, or around X, and then you are adding many, all of those trips.

140
00:36:15.440 --> 00:36:16.380
Samar .: Okay, okay.

141
00:36:16.660 --> 00:36:19.040
Faculty (Olympus): So, so that's what it is.

142
00:36:19.460 --> 00:36:22.680
Faculty (Olympus): Okay, so let's, let's do some examples.

143
00:36:22.680 --> 00:36:38.659
Rahul Joshi .: Sorry, sir, just one question related to the function. Yeah. If you slightly scroll up, so here, the X into function X is fine, but then we have to integrate it only for that portion, wherever X is, right? Not like a complete,

144
00:36:38.660 --> 00:36:56.280
Faculty (Olympus): So, automatically, if FX is 0 somewhere, then the integral in that part is going to become 0, right? Let me do an example, you will see automatically this is coming up, okay? Okay, let's do some, examples. So, the most basic one that we saw was a uniform

145
00:36:56.760 --> 00:37:07.999
Faculty (Olympus): a random variable, right? So let's take a uniform AB random variable, which is a continuous distribution, which has the following density, right? It isâ€¦

146
00:37:09.580 --> 00:37:13.249
Faculty (Olympus): only non-negative in an interval A to B.

147
00:37:13.390 --> 00:37:30.029
Faculty (Olympus): and is 0 everywhere else, right? So, between A to B, it's going to be non-negative, and it's going to be 0 everywhere else. And what is going to be the value of this density in the interval A to B? It'll be 1 upon B minus A. Right?

148
00:37:30.060 --> 00:37:49.640
Faculty (Olympus): Why is that? Because overall, we know that the area under the density curve has to be 1, so the value of the density in this region A to B is going to be 1 upon B minus A. So this is how the density of a uniform AB random variable looks like. Now, what is going to be the

149
00:37:49.660 --> 00:37:51.830
Faculty (Olympus): expected value.

150
00:37:52.480 --> 00:37:55.939
Faculty (Olympus): of this uniform random variable, okay? Now.

151
00:37:56.130 --> 00:38:07.729
Faculty (Olympus): Before we do that calculation, I want you to think about this thing. What does a uniform AB random variable represent? It represents that you are drawing numbers

152
00:38:08.060 --> 00:38:16.880
Faculty (Olympus): randomly from this interval A to B, right? Every possible number between A to B is, like, equally likely, and you're drawing random numbers between A to B.

153
00:38:17.110 --> 00:38:25.329
Faculty (Olympus): Right? Suppose you do this many, many, many times. What is the average value of those numbers that you expect to see?

154
00:38:25.470 --> 00:38:26.340
Faculty (Olympus): Right?

155
00:38:26.350 --> 00:38:38.940
Faculty (Olympus): So think about that. If you draw many, many uniformlyâ€¦ many, many times you draw uniformly between A to B, what do you think the average of all those values is going to be?

156
00:38:38.950 --> 00:38:49.950
Faculty (Olympus): Right? Now, if we do that calculation, so according to our calculation, the expected value is going to be minus infinity to infinity X times

157
00:38:52.330 --> 00:39:07.210
Faculty (Olympus): FXXDX, right? This is our formula. Now, we already see that this density is 0 outside the interval A to B, right? So this integral is just going to be the integral from A to B,

158
00:39:07.350 --> 00:39:12.300
Faculty (Olympus): of X timesâ€¦ FXXâ€¦ DX.

159
00:39:12.700 --> 00:39:22.529
Faculty (Olympus): Now, within this interval A to B, the density remains constant, right? It is always 1 upon B minus A, so that comes out of the integral.

160
00:39:22.670 --> 00:39:27.140
Faculty (Olympus): And then you have A to B, X, DX,

161
00:39:28.100 --> 00:39:40.040
Faculty (Olympus): Now, what is this integral? This integral is A to BXTX just becomes 1 by B minus A. You have X square by 2, and then you are computing this

162
00:39:40.300 --> 00:39:44.070
Faculty (Olympus): at the limits B and A, so this becomesâ€¦

163
00:39:44.290 --> 00:39:53.549
Faculty (Olympus): B squared minus A square by 2 times B minus A, which is exactly A plus B by 2.

164
00:39:54.360 --> 00:40:04.959
Faculty (Olympus): Okay, so the expected value of a uniform AB random variable is A plus B by 2, which is exactly the midpoint of this interval.

165
00:40:05.110 --> 00:40:10.330
Faculty (Olympus): Right? Which makes sense, right? If you draw many, many samples uniformly between A to B,

166
00:40:10.510 --> 00:40:16.530
Faculty (Olympus): you expect the average of that to exactly be the midpoint of this interval, A to B.

167
00:40:17.000 --> 00:40:19.310
Faculty (Olympus): Right, which is A plus B by 2.

168
00:40:20.070 --> 00:40:20.930
Faculty (Olympus): Okay?

169
00:40:21.090 --> 00:40:27.939
Faculty (Olympus): Let me maybe do one more example, and thenâ€¦ then I'll take, some questions.

170
00:40:28.670 --> 00:40:37.250
Faculty (Olympus): Okayâ€¦ Let's do one more, example. Let's doâ€¦ Xâ€¦

171
00:40:37.500 --> 00:40:42.459
Faculty (Olympus): Let's do the simplest one, okay, a discrete random variable, which is Bernoulli P.

172
00:40:42.710 --> 00:40:49.320
Faculty (Olympus): Right? Now, for a Bernoulli P random variable, recall that our PMF is given by

173
00:40:49.880 --> 00:40:57.450
Faculty (Olympus): So, probability that X is equal to 1 is P, probability that X is equal to 0 is 1 minus P.

174
00:40:58.020 --> 00:41:04.910
Faculty (Olympus): Right? And these are the only two values that a Bernoulli random variable takes. So the expected value of X

175
00:41:05.190 --> 00:41:14.990
Faculty (Olympus): isâ€¦ Summation K in the support, K times the PMF corresponding to K.

176
00:41:15.170 --> 00:41:18.439
Faculty (Olympus): Which, in this case, is just going to be 1 timesâ€¦

177
00:41:18.780 --> 00:41:21.449
Faculty (Olympus): The probability that X is equal to 1,

178
00:41:22.180 --> 00:41:26.889
Faculty (Olympus): plus 0 times the probability that X is equal to 0.

179
00:41:27.030 --> 00:41:30.740
Faculty (Olympus): Right? What is this quantity? This quantity is just P,

180
00:41:30.970 --> 00:41:33.440
Faculty (Olympus): This quantity is 1 minus P,

181
00:41:34.020 --> 00:41:41.909
Faculty (Olympus): Right? But it is multiplied by a zero, so overall, the expected value of a Bernoulli P random variable is just going to be P.

182
00:41:44.720 --> 00:41:45.410
Faculty (Olympus): Okay?

183
00:41:46.330 --> 00:42:00.690
Faculty (Olympus): So this is what the expected value of a Bernoulli P random variable is going to be, which, again, makes sense, because, again, if you think about a Bernoulli 01, a Bernoulli p random variable, where P is the probability of seeing 1, and let's say you do

184
00:42:00.690 --> 00:42:07.530
Faculty (Olympus): N, a very large number of experiments, roughly P fraction of those experiments are going to give you a 1.

185
00:42:07.640 --> 00:42:18.139
Faculty (Olympus): everything else is going to give you a 0, right? So the average of those values is exactly going to be close to P, which is why we get the expected value of X to be P.

186
00:42:19.100 --> 00:42:20.050
Faculty (Olympus): Okay?

187
00:42:20.570 --> 00:42:29.490
Faculty (Olympus): Okay, Let's maybe, are there any, questions about this, summer?

188
00:42:30.310 --> 00:42:35.269
Faculty (Olympus): No? Okay. Abhineet, is there a question?

189
00:42:35.270 --> 00:42:37.330
Abhineet Bansal: Yes, sir. Can you scroll up, sir?

190
00:42:37.560 --> 00:42:45.470
Abhineet Bansal: Yeah. For the previous example? Can you explain the calculation, sir? After you took out 1 point B minus A from the integral after that.

191
00:42:45.470 --> 00:42:49.630
Faculty (Olympus): Yeah, so the integral of X DX is just X squared by 2.

192
00:42:49.770 --> 00:42:53.189
Faculty (Olympus): And then we are evaluating it at the two limits, B and A.

193
00:42:53.570 --> 00:42:56.810
Faculty (Olympus): So that becomes B squared minus A square by 2.

194
00:42:57.120 --> 00:43:01.599
Faculty (Olympus): And then B squared minus A square isâ€¦ this is the same asâ€¦

195
00:43:01.880 --> 00:43:04.469
Faculty (Olympus): B minus A times B plus A.

196
00:43:05.690 --> 00:43:10.239
Faculty (Olympus): So, the B minus A cancels out, and what you're left with is A plus B by 2.

197
00:43:11.870 --> 00:43:12.590
Abhineet Bansal: But it'sâ€¦

198
00:43:12.590 --> 00:43:13.170
Faculty (Olympus): Okay.

199
00:43:13.440 --> 00:43:15.140
Faculty (Olympus): Okay, Rahul?

200
00:43:17.190 --> 00:43:19.160
Rahul Joshi .: No, sir, you answered my question.

201
00:43:19.160 --> 00:43:19.890
Faculty (Olympus): Harshad?

202
00:43:20.520 --> 00:43:30.049
Harshad Dilip Behere .: Yeah, good evening, Professor. So, if you scroll down a bit here for the Bernalis example, so we took some over 1 and 0 because our support is 0 and 1, is it?

203
00:43:30.050 --> 00:43:33.519
Faculty (Olympus): Yeah, those are the only two values that a Bernoulli random variable takes.

204
00:43:34.120 --> 00:43:38.340
Harshad Dilip Behere .: Okay, so if it's a different thing, then we have to do, like, 1 plus 2â€¦ I mean, 1 to 8â€¦

205
00:43:38.340 --> 00:43:42.819
Faculty (Olympus): Whatever it might be, yeah, then whatever it is, then we have to do the support for that.

206
00:43:42.820 --> 00:43:43.939
Harshad Dilip Behere .: Okay, fine, thank you.

207
00:43:43.940 --> 00:43:44.510
Faculty (Olympus): Okay?

208
00:43:44.690 --> 00:43:49.559
Faculty (Olympus): Alright, let's maybe do a fewâ€¦ a couple more examples.

209
00:43:50.260 --> 00:43:53.729
Faculty (Olympus): So, of some of the distributions that we have seen.

210
00:43:53.780 --> 00:44:07.730
Faculty (Olympus): Right? So, one example is, we've seen an exponential distributed random variable with parameter lambda, right? Lambda is some parameter greater than zero, and the density of this

211
00:44:07.730 --> 00:44:23.699
Faculty (Olympus): random variable is lambda times e raised to minus lambda X, and the support is only non-negative values, alright? So, if I compute the expected value of X, that is just going to be

212
00:44:24.390 --> 00:44:32.539
Faculty (Olympus): the integral from 0 to infinity of X times the density, which is lambda times e raised to minus lambda X.

213
00:44:33.250 --> 00:44:35.819
Faculty (Olympus): DX, right? This is what theâ€¦

214
00:44:36.150 --> 00:44:48.019
Faculty (Olympus): density is, going to look like. Now, again, this is an integral, so this, this integral is going to be lambda times

215
00:44:48.880 --> 00:44:55.020
Faculty (Olympus): 0 to infinity of X times E raised to minus lambda X DX.

216
00:44:55.020 --> 00:45:07.429
Faculty (Olympus): Right? Now, I'm not going to do this integral here. This is something I want you to practice on your own. This is someâ€¦ this is just an integral that you have to do using integration by parts. Okay, this is high school calculus.

217
00:45:07.430 --> 00:45:21.910
Faculty (Olympus): Like I said, this is a technique that you need to understand well, how to do integration. I'm not going to do this, here in class. If you do this calculation, you will find that the overall expected value turns out to be exactly 1 by lambda.

218
00:45:22.440 --> 00:45:37.080
Faculty (Olympus): Okay, it turns out to be exactly 1 by lambda. So, for an exponential distributed random variable, its expected value is given by 1 by lambda. So, again, let's see why this makes sense. So, if you look at the density.

219
00:45:37.850 --> 00:45:49.120
Faculty (Olympus): of, an exponential random variable, itâ€¦ it is given by lambda times e raised to minus lambda X, so it decreases exponentially, right?

220
00:45:49.580 --> 00:45:58.769
Faculty (Olympus): It starts with high values and then goes down. Now, if lambda is large, right, if lambda is large, then this decrease is going to be very sharp.

221
00:45:59.020 --> 00:46:06.609
Faculty (Olympus): If la- so, for example, let's say this corresponds to maybe lambda being equal to 3,

222
00:46:06.960 --> 00:46:08.309
Faculty (Olympus): If you took

223
00:46:08.470 --> 00:46:20.820
Faculty (Olympus): lambda to be, let's say 1, then maybe the decrease is going to be slightly slower, okay? It's going to go down something like this. So maybe this corresponds to lambda equals 1, okay? Soâ€¦

224
00:46:21.490 --> 00:46:23.600
Faculty (Olympus): When lambda is larger.

225
00:46:23.600 --> 00:46:43.679
Faculty (Olympus): you are more likely to have smaller values than when lambda is smaller, right? Because the decay is faster when lambda is larger, so you're more likely to have smaller values, which is why the expected value also is smaller when lambda is larger. The expected value behavesâ€¦ goes down as lambda is larger.

226
00:46:43.680 --> 00:46:46.610
Faculty (Olympus): Okay, it's inversely proportional to the value of lambda.

227
00:46:47.180 --> 00:46:48.030
Faculty (Olympus): Okay?

228
00:46:48.300 --> 00:46:53.800
Faculty (Olympus): Okay, so this is for an exponential random variable.

229
00:46:56.520 --> 00:46:58.930
Faculty (Olympus): Let's do a discrete one.

230
00:46:59.070 --> 00:47:04.259
Faculty (Olympus): Let's again take one which comes up very often, which is a binomial

231
00:47:04.560 --> 00:47:12.549
Faculty (Olympus): NP random variable, right? We have talked about this random variable quite a lot. It is a random variable, which is essentially, like.

232
00:47:12.800 --> 00:47:14.820
Faculty (Olympus): You're doing n experiments.

233
00:47:14.940 --> 00:47:23.530
Faculty (Olympus): the probability of success of any one experiment is P, and N represents the number of successes that you see, right?

234
00:47:23.680 --> 00:47:36.049
Faculty (Olympus): So, we can compute theâ€¦ so again, the expected value ofâ€¦ and so what areâ€¦ what are the values that N can take? In this case, N can take,

235
00:47:39.000 --> 00:47:51.659
Faculty (Olympus): Either it can be 0, or it can be 1, or 2, all the way up to the total number of experiments that we are running. Any one of those values is feasible, so the expected value of N is going to be

236
00:47:52.130 --> 00:47:57.389
Faculty (Olympus): Exactlyâ€¦ K going from 0 to N.

237
00:47:57.760 --> 00:48:00.420
Faculty (Olympus): And thenâ€¦ K timesâ€¦

238
00:48:00.540 --> 00:48:09.540
Faculty (Olympus): the PMF associated with K for a binomial random variable. What is that? That is summation k equals 0 to n

239
00:48:10.010 --> 00:48:13.590
Faculty (Olympus): K timesâ€¦ And choose K.

240
00:48:14.990 --> 00:48:18.440
Faculty (Olympus): P to the K, 1 minus B.

241
00:48:19.020 --> 00:48:19.850
Faculty (Olympus): B.

242
00:48:20.430 --> 00:48:22.310
Faculty (Olympus): N minus K.

243
00:48:22.970 --> 00:48:26.930
Faculty (Olympus): Okay? So, this is the summation,

244
00:48:27.100 --> 00:48:40.010
Faculty (Olympus): Again, there are a few steps here. If you are interested, you can look at the steps in the notes. It's just a bunch of algebra with these binomial coefficients. This summationâ€¦

245
00:48:40.580 --> 00:48:44.399
Faculty (Olympus): turns out to exactly be N times P.

246
00:48:44.830 --> 00:48:52.140
Faculty (Olympus): Okay, so the expected value of a binomial random variable Okay.

247
00:48:53.280 --> 00:48:58.529
Faculty (Olympus): with parameters N and P is exactly N times P.

248
00:48:58.720 --> 00:49:07.270
Faculty (Olympus): Okay? Again, think about it. If you do n small n experiments, the probability of success of each individual experiment is P,

249
00:49:07.360 --> 00:49:19.260
Faculty (Olympus): Then, on average, if you think about how many successes you will see, it is going to exactly be N times P. Okay, so that's why the expected value turns out to be N times P.

250
00:49:20.150 --> 00:49:20.890
Faculty (Olympus): Okay?

251
00:49:21.160 --> 00:49:27.060
Faculty (Olympus): So, there was talk about, we had talked aboutâ€¦

252
00:49:27.180 --> 00:49:31.790
Faculty (Olympus): Gaussian or normal distributed random variables, soâ€¦

253
00:49:32.100 --> 00:49:39.719
Faculty (Olympus): A normal distributed random variable is specified by two parameters, mu and sigma squared.

254
00:49:40.270 --> 00:49:48.599
Faculty (Olympus): for this Gaussian distribution with parameters mu and sigma square, for which the density looks something like this, right? It looksâ€¦

255
00:49:49.260 --> 00:50:00.059
Faculty (Olympus): Something like this, where the peak is at mu and the density is symmetric around mu, the expected value turns out to be exactly mu.

256
00:50:00.670 --> 00:50:09.180
Faculty (Olympus): Okay, so this first parameter in any Gaussian distribution, in fact, represents the expected value of that distribution.

257
00:50:09.410 --> 00:50:10.100
Faculty (Olympus): Okay?

258
00:50:10.810 --> 00:50:27.379
Faculty (Olympus): So, again, I'll just, run through some of the distributions that we have talked about, so that we know what the expected value looks like for them. One more that we talked about was, geometric random variable.

259
00:50:27.870 --> 00:50:37.829
Faculty (Olympus): Right? So, let's say X is geometric with probability P. The PMF corresponding to this wasâ€¦

260
00:50:38.830 --> 00:50:45.140
Faculty (Olympus): P times 1 minus P to the power k minus 1, and the values that it can take

261
00:50:45.300 --> 00:50:49.609
Faculty (Olympus): Is either 1, 2, 3, and so on, right?

262
00:50:50.180 --> 00:51:03.579
Faculty (Olympus): What did a geometric random variable represent? It represented that if, let's say, the probability of seeing a heads is P, how many times will I have to toss the coin before I see my first heads, right?

263
00:51:03.760 --> 00:51:07.670
Faculty (Olympus): So, the probability that K is 1 isâ€¦

264
00:51:07.800 --> 00:51:12.560
Faculty (Olympus): You toss the coin once, and you land with a heads. So that is exactly P.

265
00:51:12.830 --> 00:51:31.280
Faculty (Olympus): what is the probability that K is 2? That means in the first toss, you see a tails, and then you see a heads. So you get exactly 1 minus P times P, and so on, right? So, requiring k tosses means you first see K-1 tails, and then you see a heads.

266
00:51:31.400 --> 00:51:44.150
Faculty (Olympus): Okay, that's the idea. So, again, X is a geometric random variable. The expected value of X will represent, on average, how many tosses do I have to do before I see my first heads.

267
00:51:44.240 --> 00:52:01.240
Faculty (Olympus): Or if youâ€¦ if this is an experiment, and the probability of, you know, whenever I do this experiment, the probability of seeing a success is P, this is like saying, how many times will I have to do this experiment before I see my first success? Right? So the experiment could, for example, beâ€¦

268
00:52:02.890 --> 00:52:17.810
Faculty (Olympus): me, maybe I am part of a sales team, and I am, making one call after another to try and speak to someone, and every time I make a call, maybe there is a certain probability P that someone picks up.

269
00:52:17.810 --> 00:52:25.590
Faculty (Olympus): So how many times will I, or how many calls will I have to make before I can finally speak to someone, right? So that's kind of a geometric random variable.

270
00:52:25.610 --> 00:52:36.819
Faculty (Olympus): Okay, so this, again, is, for this random variable, the expected value is going to be summation. Now, what are the values that it can take? It can go from 1 to infinity.

271
00:52:36.930 --> 00:52:43.870
Faculty (Olympus): Andâ€¦ The value is going to be K times P times 1 minus P,

272
00:52:44.570 --> 00:52:47.289
Faculty (Olympus): to the power k minus 1, this is what

273
00:52:47.740 --> 00:52:54.569
Faculty (Olympus): the series corresponds to, and the sum of this series is exactly 1 by P.

274
00:52:54.830 --> 00:52:59.700
Faculty (Olympus): Okay, so the expected value of a geometric random variable is exactly 1 by P.

275
00:53:00.720 --> 00:53:01.590
Faculty (Olympus): Okay?

276
00:53:02.130 --> 00:53:18.390
Faculty (Olympus): Okay, so yeah, these are some examples of random variables that we have seen before, and for these different random variables, we have computed the average values. So, again, I have done some of these calculations, and some of these calculations I have left.

277
00:53:18.490 --> 00:53:35.790
Faculty (Olympus): I want you to please try and, furnish some of the details here. All you need is, you need to know how to do integrals, and you need to know how to compute sums of series. Okay, these are the two things that one needs to know how to do.

278
00:53:35.800 --> 00:53:38.920
Faculty (Olympus): That's it, okay?

279
00:53:38.920 --> 00:53:54.450
Charu .: Sorry for interrupting in between. Could you please repeat in a slow pace? I was not able to understandâ€¦ I was only able to understand half of the class today. Okay. So can you please repeat in a, in a, in a slow pace?

280
00:53:54.720 --> 00:54:07.409
Faculty (Olympus): Okay, so, I maybe cannot go over everything, but if there is one example that you want to see, again, I can probably do that. Can you maybe point to one thing? The others, maybe we can take at the end.

281
00:54:07.760 --> 00:54:11.119
Charu .: Yeah, at least the last topic, which you were,

282
00:54:11.300 --> 00:54:22.549
Faculty (Olympus): The last one, the geometric one? Okay, so let me maybe do that. So, this X is a geometric random variable. This is one of the random variables we have seen before, right?

283
00:54:22.740 --> 00:54:32.619
Faculty (Olympus): It corresponds to a situation where you are, let's say, tossing a coin. The probability of seeing a heads in a particular toss is P.

284
00:54:32.910 --> 00:54:44.810
Faculty (Olympus): And X represents how many times will I have to toss before I see my first heads, right? So the PMF corresponding to this random variable is given by this expression.

285
00:54:45.360 --> 00:54:46.220
Faculty (Olympus): Okay?

286
00:54:46.370 --> 00:54:59.239
Faculty (Olympus): And the random variable can take values in the positive natural numbers, so it can be either 1, or 2, or 3, and so on. Okay, so this is the PMF. Now, given any PMF, we know how to compute its expected value.

287
00:54:59.240 --> 00:55:07.249
Faculty (Olympus): Its expected value is just k timesâ€¦ so this expected value of any random variable is you sum over all element

288
00:55:07.340 --> 00:55:09.250
Faculty (Olympus): Elements of the support.

289
00:55:09.410 --> 00:55:15.460
Faculty (Olympus): K times the corresponding PMF value. So that is what this expression is doing. That's it.

290
00:55:15.820 --> 00:55:16.550
Faculty (Olympus): Right?

291
00:55:16.880 --> 00:55:33.500
Faculty (Olympus): And my claim was that this summation of this series is exactly 1 by P. So this is something I'm leaving for you to, to verify on your own, okay? I'm not doing that calculation. This is just a summation of a series.

292
00:55:33.650 --> 00:55:35.620
Faculty (Olympus): Okay?

293
00:55:36.160 --> 00:55:43.529
Faculty (Olympus): So, yeah, here there are some steps that I have, knowingly left out, so that you can try and fill in those steps.

294
00:55:43.750 --> 00:55:51.309
Faculty (Olympus): So that's all we have done. All I've said is that if you sum up this infinite series, you get exactly 1 by P. That's it.

295
00:55:52.060 --> 00:55:52.880
Faculty (Olympus): Okay?

296
00:55:52.880 --> 00:55:53.480
Charu .: Thanks.

297
00:55:54.330 --> 00:55:59.420
Faculty (Olympus): Okay, yeah, okay, I can take a few questions. Yeah, Kanupriya?

298
00:56:02.510 --> 00:56:14.089
Kanupriya Saxena .: So, when we say the expected value is 1 by P, and because P lies between 0 to 1, so most of the time, the expected value would be greater than 1, you think.

299
00:56:15.040 --> 00:56:25.989
Faculty (Olympus): Yeah, so, because, I mean, if you think about it, the values that this random variable takes is always greater than equal to 1, right? It's neverâ€¦

300
00:56:25.990 --> 00:56:26.500
Kanupriya Saxena .: Exactly.

301
00:56:26.500 --> 00:56:29.809
Faculty (Olympus): Less than 1. So the average can never be less than 1.

302
00:56:30.640 --> 00:56:48.649
Faculty (Olympus): it can only be greater than equal to 1, and this random variable does takeâ€¦ there is some probability that it'll take a value larger than 1, and so, you will have an expected value which is greater than 1. The one thing to note here is thatâ€¦ so suppose

303
00:56:48.740 --> 00:56:58.349
Faculty (Olympus): think of a scenario where P is very small, which means the probability of seeing a success is really small, or the probability of seeing a heads is very small.

304
00:56:58.470 --> 00:57:12.289
Faculty (Olympus): If that is the case, you would expect to do many, many experiments before you see your first success, right? So that is also something that you see clearly from this expression. If your P is small, the expected number of experiments you'll have to do is larger.

305
00:57:12.530 --> 00:57:20.290
Faculty (Olympus): If your P is large, then the expected number of experiments you will need to do to see your first success is going to be smaller.

306
00:57:21.520 --> 00:57:22.440
Faculty (Olympus): Okay?

307
00:57:23.240 --> 00:57:25.150
Faculty (Olympus): Okay, Ashish?

308
00:57:25.850 --> 00:57:40.280
Ashish Kumar .: Yes, sir, in this geometric random variable, the value of k we have defined here is 1, 2, 3, or it can go up to infinity. So, most probably in a question, this, the number of experiments n will be defined.

309
00:57:40.650 --> 00:57:44.729
Ashish Kumar .: It, it won't be, like, infinitive. When we are some, somewhere,

310
00:57:44.880 --> 00:57:52.650
Ashish Kumar .: We are doing a sigma from K1 to infinity, and a normal question will be mostly be contained within a number of experiments we are doing, means the.

311
00:57:52.650 --> 00:57:53.049
Faculty (Olympus): I don't know.

312
00:57:53.410 --> 00:58:00.299
Faculty (Olympus): I mean, this is not, this is not the number of experiments. This is whatâ€¦ what can the value be in a given experiment?

313
00:58:00.900 --> 00:58:13.919
Faculty (Olympus): So, think about, the same scenario, right? You are, oneâ€¦ my one experiment is, Iâ€¦ I'm taking a coin, and I'm tossing it till I see my first heads. This is one experiment.

314
00:58:14.240 --> 00:58:19.949
Faculty (Olympus): Now, I might require 10, let's say, tosses before I see my first heads.

315
00:58:20.110 --> 00:58:28.499
Faculty (Olympus): Then I repeat the experiment, okay? I again pick up the coin, I again start tossing. Maybe this time, the first heads comes in the third

316
00:58:28.670 --> 00:58:29.530
Faculty (Olympus): Case.

317
00:58:29.770 --> 00:58:44.860
Faculty (Olympus): Right. In the third toss. Then I repeat, right? So every timeâ€¦ so, in a given experiment, it might take me 100 tosses before I see my first heads, or it might take me 3, or it might take me 15, or it might take me 17.

318
00:58:45.250 --> 00:58:46.030
Faculty (Olympus): Right?

319
00:58:46.330 --> 00:58:46.710
Ashish Kumar .: Okay.

320
00:58:46.710 --> 00:58:50.239
Faculty (Olympus): All of these are possibilities across different experiments.

321
00:58:51.140 --> 00:58:53.360
Ashish Kumar .: So this might take a very large value also.

322
00:58:53.360 --> 00:58:54.759
Faculty (Olympus): Yeah, yeah, yeah. That is what we.

323
00:58:54.760 --> 00:58:57.840
Ashish Kumar .: Signifying as a, the infinity.

324
00:58:57.840 --> 00:59:14.600
Faculty (Olympus): Yeah, yeah, yeah. So itâ€¦ I mean, you might have to keep going. Now, the probability of that happening is decreasing exponentially with K, right? The probability that you requireâ€¦ you will require, let's say, 100 tosses to see your first, heads is going to be P times 1 minus P to the power 99.

325
00:59:14.600 --> 00:59:15.100
Ashish Kumar .: Yes.

326
00:59:15.100 --> 00:59:22.310
Faculty (Olympus): So that is going to be very small, but it is non-zero. So there is some non-zero probability you will require 100 tosses to see your first heads.

327
00:59:22.310 --> 00:59:23.120
Ashish Kumar .: Which Kennel?

328
00:59:23.120 --> 00:59:27.609
Faculty (Olympus): happen, right? I mean, maybe you are in a particular scenario where somehow there is this

329
00:59:27.770 --> 00:59:32.659
Faculty (Olympus): Completely rare phenomena where you're just seeing tales after tails after tails.

330
00:59:33.520 --> 00:59:35.569
Ashish Kumar .: Okay, great. Thank you.

331
00:59:35.570 --> 00:59:37.400
Faculty (Olympus): Okay? Sajith?

332
00:59:40.400 --> 00:59:51.169
Sajith K N .: Yeah, I have the same question on the P. I think I end up getting it is, is that P is a total probability of their given experiment, right?

333
00:59:52.010 --> 00:59:53.440
Sajith K N .: Or is this included?

334
00:59:54.230 --> 01:00:07.999
Faculty (Olympus): So, in a given experiment, what is theâ€¦ so, I mean, there are two things here. One experiment in this particular case refers to me tossing the coin again and again till I see my first heads.

335
01:00:09.300 --> 01:00:15.130
Faculty (Olympus): So, inâ€¦ within one experiment, I am tossing the coin, potentially many times.

336
01:00:15.350 --> 01:00:19.729
Faculty (Olympus): And when I toss the coin once, the probability of seeing a heads is P.

337
01:00:21.170 --> 01:00:32.300
Faculty (Olympus): So, in a geometric random variable, the way to think about it is maybe experiment one, you pick the coin, you start tossing it. Toss 1, you get a tails.

338
01:00:33.470 --> 01:00:36.490
Faculty (Olympus): Toss 2, you again see a tails.

339
01:00:36.590 --> 01:00:43.360
Faculty (Olympus): toss 3, maybe you see a heads. So in this particular case, the value of this geometric random variable

340
01:00:43.500 --> 01:00:45.630
Faculty (Olympus): In the first toss is 3.

341
01:00:46.260 --> 01:00:58.670
Faculty (Olympus): Then you repeat your experiment. You again do this the next day. You start tossing coin again, maybe you see T, T, T, T, H now. So on the second day, the value was 5, and so on.

342
01:01:00.670 --> 01:01:06.279
Faculty (Olympus): Right? So on different days, you might require a different number of tosses to see your first heads.

343
01:01:07.470 --> 01:01:11.909
Faculty (Olympus): And the expected value of X is supposed to represent

344
01:01:12.200 --> 01:01:19.720
Faculty (Olympus): theâ€¦ kind of the average of all of these values. So if I do this experiment a hundred times, right?

345
01:01:20.010 --> 01:01:24.589
Faculty (Olympus): Iâ€¦ Going from 1 to 100.

346
01:01:25.310 --> 01:01:27.030
Faculty (Olympus): Or a thousand times.

347
01:01:27.210 --> 01:01:28.710
Faculty (Olympus): Then, on average.

348
01:01:29.320 --> 01:01:38.619
Faculty (Olympus): How many crosses did it take me before I saw the first hits? So that'sâ€¦ that's what roughly this expected value is supposed to mimic.

349
01:01:40.230 --> 01:01:41.240
Sajith K N .: Alright.

350
01:01:41.240 --> 01:01:42.360
Faculty (Olympus): Okay? Sanketh?

351
01:01:44.390 --> 01:01:57.619
Sanketh Chiplunkar .: Hello, sir. Sir, I have the same question in this one, in this geometric probability for the random variable. For the heads and tails experiment, is itâ€¦ is the value of P considered equal to 1 by 2, and thenâ€¦

352
01:01:57.880 --> 01:02:02.710
Faculty (Olympus): No, no, P can be any value. P can be any number between 0 to 1.

353
01:02:04.050 --> 01:02:11.329
Faculty (Olympus): So, if P is 1 by 2, that just means that heads and tails are equally likely, but P can be any number between 0 to 1.

354
01:02:12.890 --> 01:02:17.809
Faculty (Olympus): If P is small, then you will potentially need many, many tosses

355
01:02:18.090 --> 01:02:26.069
Faculty (Olympus): Or the expected value is going to be large. So it just indicates that, on average, you will require many tosses to see your first hits.

356
01:02:26.320 --> 01:02:33.959
Faculty (Olympus): And if P is closer to 1, then that just means that on average, you will require few tosses to see the first hits.

357
01:02:36.920 --> 01:02:38.370
Faculty (Olympus): Okay? Niraj?

358
01:02:39.230 --> 01:02:59.200
Niraj Kumar Mishra .: Sir, I have a very basic question. Okay, so, first of all, I would like to know if you have already a theorem to calculate the random variable and discrete variable. On top of that, why expected value is needed? So, and if you can give some, you know, explanation in realâ€¦ real world, how it is related to machine learning.

359
01:02:59.200 --> 01:03:06.339
Niraj Kumar Mishra .: then I think I can understand the concept. What is happening, I'm not able to understand the huge case of expected value.

360
01:03:06.740 --> 01:03:19.860
Faculty (Olympus): So, the expected value is supposed to, like I said, it's, it's supposed to be, to represent, when you draw, let's say,

361
01:03:20.010 --> 01:03:38.580
Faculty (Olympus): a sample from some distribution many, many times, what is, like, the average value that you will roughly get if you draw a sample many, many times from a given distribution, right? Then what is the average value that you will see? That is what the expected value is supposed to mimic.

362
01:03:38.600 --> 01:03:44.699
Faculty (Olympus): Okay? So, this could be, for example, suppose you are,

363
01:03:45.360 --> 01:03:51.010
Faculty (Olympus): sampling from some population, okay? Let's say we areâ€¦ I am,

364
01:03:51.360 --> 01:04:08.679
Faculty (Olympus): looking at, certain, maybe, maybe I'm even looking at a certain dataset, let's say, okay? So you have a certain dataset, and that dataset has, different, features. Maybe it is, related to

365
01:04:08.790 --> 01:04:21.009
Faculty (Olympus): let's just take one particular feature in this dataset, and I cannotâ€¦ so I cannot feed the entire training dataset

366
01:04:21.090 --> 01:04:31.159
Faculty (Olympus): to this, to my model, so maybe I will select a few, elements from this training set, right? This is how usually training happens. So you will have a huge

367
01:04:31.600 --> 01:04:32.640
Faculty (Olympus): dataset.

368
01:04:32.980 --> 01:04:33.810
Faculty (Olympus): Okay?

369
01:04:33.930 --> 01:04:41.840
Faculty (Olympus): And let's sayâ€¦ There is his X1, this is X2, And maybe this isâ€¦ X thousand.

370
01:04:42.360 --> 01:04:45.690
Faculty (Olympus): Okay, and let's say from this dataset, Iâ€¦

371
01:04:46.040 --> 01:04:58.300
Faculty (Olympus): pick one element at random from this dataset, right? So, let's say you pick one elementâ€¦

372
01:05:00.930 --> 01:05:02.390
Faculty (Olympus): From the dataset.

373
01:05:04.320 --> 01:05:09.209
Faculty (Olympus): Right? And let's call that element Z. Right? Now, think about Z.

374
01:05:09.560 --> 01:05:11.589
Faculty (Olympus): Z is a random variable.

375
01:05:11.770 --> 01:05:22.329
Faculty (Olympus): Right? Because it can take different values, and there is a certain probability that it takes different values. What are the values that Z can take? Z can either be equal to

376
01:05:22.710 --> 01:05:23.900
Faculty (Olympus): X1.

377
01:05:24.340 --> 01:05:26.329
Faculty (Olympus): Whatever the value of X1 is.

378
01:05:26.480 --> 01:05:33.819
Faculty (Olympus): or it can be equal to what X2 is, or it can be equal to what X3 is, and so on till x000.

379
01:05:33.960 --> 01:05:36.930
Faculty (Olympus): Right? It can be any one of these thousand values.

380
01:05:37.290 --> 01:05:45.030
Faculty (Olympus): What are the probabilities associated with each of them? What is the probability that Z takes the value equal to X1?

381
01:05:45.470 --> 01:05:50.249
Faculty (Olympus): The probability that Z takes a value equal to X1 is exactly 1 by 1000.

382
01:05:50.410 --> 01:06:03.110
Faculty (Olympus): The probability that Z takes a value equal to X2 is exactly 1 by 1000, and similarly, the probability that Z takes the value equal to X thousand is exactly 1 by 1000.

383
01:06:03.740 --> 01:06:20.530
Faculty (Olympus): Right? So this is like a discrete version of a uniform distribution. Z can take any one of these thousand values, and the probability of each of them is the same, 1 by 1,000, 1 by 1000, and so on. Right? So what is the expected value of Z?

384
01:06:23.370 --> 01:06:27.980
Faculty (Olympus): The expected value of Z is exactly, in this case, equal toâ€¦

385
01:06:28.450 --> 01:06:36.229
Faculty (Olympus): X1 plus X2 plus X3, all the way to X1000 divided by 1000.

386
01:06:36.550 --> 01:06:39.210
Faculty (Olympus): That is exactly the expected value of Z.

387
01:06:40.040 --> 01:06:43.029
Faculty (Olympus): So, you should think of this as, like, the average

388
01:06:43.310 --> 01:06:45.809
Faculty (Olympus): Of thisâ€¦ of the thousand values.

389
01:06:45.920 --> 01:06:49.860
Faculty (Olympus): Right? That is what this expected value of Z is representing.

390
01:06:50.320 --> 01:06:55.099
Faculty (Olympus): So, if I was training my model, and I justâ€¦ my batch size is just 1,

391
01:06:55.270 --> 01:07:00.779
Faculty (Olympus): Then, on average, I am picking one of these features, and that is what I'm feeding to the model.

392
01:07:00.890 --> 01:07:06.709
Faculty (Olympus): Right? So, the expected value of Z just represents the average of my entire dataset.

393
01:07:07.220 --> 01:07:08.889
Faculty (Olympus): That is what it represents.

394
01:07:09.220 --> 01:07:24.279
Niraj Kumar Mishra .: So, in this example, so the simple probability will be also 1, and the expected value is also 1, because it's X1X2 to 1000 divided by 1000. So, if I see the.

395
01:07:24.280 --> 01:07:32.450
Faculty (Olympus): No, no, it's not 1. X1 plus X2 till X000, I mean, X, these Xi's are any feature values, they are real numbers.

396
01:07:32.690 --> 01:07:45.889
Faculty (Olympus): Right? This could be theseâ€¦ the features could be maybe I'm modeling, like, the number of hours that a student studies, and the marks that they get, right? Maybe these are theâ€¦ so Xi's are the number of hours that

397
01:07:45.890 --> 01:07:56.730
Faculty (Olympus): these thousand students, each of these thousand student studies, and maybe the label corresponding, or the Y is the marks that they get, and I'm trying to fit a model between X and Y.

398
01:07:56.990 --> 01:07:58.729
Faculty (Olympus): Right? That might be myâ€¦

399
01:07:58.850 --> 01:08:07.350
Faculty (Olympus): task. So, in this case, the feature can beâ€¦ can be some number, which is the amount of hours that each of these guys studied.

400
01:08:08.220 --> 01:08:08.800
Faculty (Olympus): Soâ€¦

401
01:08:08.800 --> 01:08:13.280
Niraj Kumar Mishra .: conceptâ€¦ concept of Ajit means more or less clear, but if, I, I.

402
01:08:13.280 --> 01:08:24.519
Faculty (Olympus): So, I will, I will do one more example, which is related to, demand and supply, and maybe, maybe that'll also link, it'll give some sense of how

403
01:08:24.840 --> 01:08:26.569
Faculty (Olympus): It applies in practice.

404
01:08:27.040 --> 01:08:46.560
Niraj Kumar Mishra .: So, sir, one request, sir, because Iâ€¦ actually, I stopped, you know, doing mathematics 15 years back, right? So, when you start the lecture, if you can give the context, and what is the huge quiz of that topic, I think it will be very helpful, and try to relate with real-time examples, so that we canâ€¦ we can understand the things easily.

405
01:08:47.319 --> 01:09:02.769
Faculty (Olympus): Yeah, okay, I'll try that, but I mean, I really have to say that this is a mathematical course also, so yes, I will try and give you real-life examples, but ultimately, this is a math course, so if you don't

406
01:09:03.209 --> 01:09:15.549
Faculty (Olympus): keep up with the math, or you don't put in the effort with the math, you won't appreciate many of these things. So yes, I will, from my side, yeah, I will try and, try and give you some examples.

407
01:09:15.910 --> 01:09:16.709
Niraj Kumar Mishra .: Okay, sir, thank you.

408
01:09:17.010 --> 01:09:19.569
Faculty (Olympus): Okay, yeah, Niraj?

409
01:09:21.680 --> 01:09:23.719
Niraj Kumar Mishra .: No, no, I just asked the question. Sorry, okay.

410
01:09:23.970 --> 01:09:25.420
Faculty (Olympus): Okay, Vamsi?

411
01:09:28.229 --> 01:09:40.330
Vamsi Krishna Mutnuri .: Sir, this same example of tossing a coin and getting a success at the kth time is also being described in the binomial random variable, right? In common dispute random variable.

412
01:09:40.330 --> 01:09:46.690
Faculty (Olympus): No, no, in binomial random variables, things are a little different. You do N experiments, small n experiments.

413
01:09:46.830 --> 01:09:47.670
Faculty (Olympus): Okay?

414
01:09:47.970 --> 01:09:49.519
Vamsi Krishna Mutnuri .: It's multiple experiments, like.

415
01:09:49.529 --> 01:10:02.309
Faculty (Olympus): You are fixing the number of experiments. You are going to do small n experiments, and then you count how many amongst those N, were actually,

416
01:10:02.539 --> 01:10:19.299
Faculty (Olympus): how many successes did you get in the n experiments? So you don't do this sequentially till you hit the first success. You actually fix the number of experiments you're going to do. You're going to do small n experiments, and you see how many successes you get. So that's why that number can be between 0 to n.

417
01:10:21.190 --> 01:10:24.829
Vamsi Krishna Mutnuri .: Okay, and that's the reason we use the n choose k function there.

418
01:10:24.830 --> 01:10:25.780
Faculty (Olympus): Yeah, yeah, yeah.

419
01:10:26.020 --> 01:10:29.139
Vamsi Krishna Mutnuri .: And here it is, like, you know, getting the first success.

420
01:10:29.140 --> 01:10:30.220
Faculty (Olympus): Per success.

421
01:10:31.100 --> 01:10:32.109
Vamsi Krishna Mutnuri .: Okay, sir, thank you.

422
01:10:32.110 --> 01:10:32.630
Faculty (Olympus): Yeah.

423
01:10:32.840 --> 01:10:34.589
Faculty (Olympus): Okay, Manu?

424
01:10:36.430 --> 01:10:39.129
Manu Gupta .: Mohammed Say I'm out of it.

425
01:10:39.130 --> 01:10:39.730
Faculty (Olympus): Yeah.

426
01:10:40.270 --> 01:10:56.869
Manu Gupta .: Wow, so, so in that, I understand this, expected value, but, sir, in the case of continuous random variable, or I say, infinite disked, random variable, so the expected value is within the range-bound, thing of support, support X.

427
01:10:58.900 --> 01:11:14.059
Faculty (Olympus): Is it within the range? That's what you're asking? Yeah, yeah, yeah, it's going to be some number within this range of, whatever that range is. Now, if the range itself is infinite, right? So, for example.

428
01:11:14.250 --> 01:11:28.910
Faculty (Olympus): In the case of a geometric random variable, the range is potentially infinite. In the case of a Gaussian random variable, also the range is infinite. Now, in both of these cases, the expected value turned out to be finite.

429
01:11:29.440 --> 01:11:33.610
Faculty (Olympus): There can be random variables whose support is, let's say, the whole rail line.

430
01:11:33.750 --> 01:11:39.500
Faculty (Olympus): And for which the expected value is also infinite. There are some random variables like that.

431
01:11:39.610 --> 01:11:44.419
Faculty (Olympus): If you're interested, one ofâ€¦ one such random variable is called the Kaushi random variable.

432
01:11:44.810 --> 01:11:57.609
Faculty (Olympus): It's one of these, heavy-tailed distributions, which hasâ€¦ which finds some applications. For that random variable, it turns out that the expected value itself isâ€¦ can also be infinite.

433
01:11:59.290 --> 01:12:01.580
Faculty (Olympus): But in general, yeah, I mean, you cannot haveâ€¦

434
01:12:01.840 --> 01:12:11.500
Faculty (Olympus): Or you will not have a situation where the random variable has a finite support, and the expected value is infinite.

435
01:12:12.210 --> 01:12:16.809
Faculty (Olympus): That, yeah, because you are actually taking this weighted average of these values, right?

436
01:12:17.890 --> 01:12:26.450
Manu Gupta .: Yes, because if we calculate this expected value, so we can verify that, this belongs to the support X. Otherwise, the answer may be wrong.

437
01:12:26.900 --> 01:12:30.709
Faculty (Olympus): I mean, it'll not necessarily belong to the support, but it'll be within the support.

438
01:12:30.880 --> 01:12:39.870
Faculty (Olympus): Right? Okay. For example, I mean, for a binomial random variable, the support is only integers between 0 to n, but the expected value can be a real number.

439
01:12:40.630 --> 01:12:42.649
Faculty (Olympus): But it'll be between 0 and A.

440
01:12:44.300 --> 01:12:45.070
Manu Gupta .: I'll justâ€¦

441
01:12:45.070 --> 01:12:47.980
Faculty (Olympus): Right? Okay. Yeah, Charles?

442
01:12:49.930 --> 01:12:56.319
Charles Ravi Kiran Mutsu .: to prove that, what's the difference between

443
01:12:56.720 --> 01:13:05.430
Charles Ravi Kiran Mutsu .: like, mean and expected variable, because it looks a bit similar in certain distributions, like uniform or.

444
01:13:06.590 --> 01:13:14.200
Faculty (Olympus): Soâ€¦ I mean, yeah, sometimes the expectation is called the mean of the random variable as well,

445
01:13:14.340 --> 01:13:16.340
Faculty (Olympus): But theâ€¦ I mean.

446
01:13:17.110 --> 01:13:24.899
Faculty (Olympus): yeah, the way to think about it is the expectation is a statistical average, right? I'm just giving you a distribution, and you're computing

447
01:13:25.060 --> 01:13:27.509
Faculty (Olympus): A certain function of that distribution.

448
01:13:27.680 --> 01:13:28.630
Faculty (Olympus): Okay.

449
01:13:28.880 --> 01:13:36.930
Faculty (Olympus): And what it is trying to mimic is like a time average. If I take this distribution, I draw many, many samples from this distribution.

450
01:13:37.090 --> 01:13:42.160
Faculty (Olympus): And then I average those distributions out, or the mean value of all of those samples.

451
01:13:42.370 --> 01:13:47.340
Faculty (Olympus): That is going to be close to the statistical average, which is just the expectation.

452
01:13:48.260 --> 01:13:57.819
Faculty (Olympus): So that is kind of the motivation. You're given a distribution, you compute some function of that distribution. That gives you the statistical average, or the expectation.

453
01:13:58.040 --> 01:14:05.949
Faculty (Olympus): And that is supposed to be close to your time average, or your mean value, if you take many, many samples from that distribution.

454
01:14:07.260 --> 01:14:08.230
Faculty (Olympus): Got it.

455
01:14:08.430 --> 01:14:11.210
Charles Ravi Kiran Mutsu .: But they are two different concepts. They are two different concept.

456
01:14:11.210 --> 01:14:16.920
Faculty (Olympus): concepts, but they tendâ€¦ theyâ€¦ I mean, yeah, we'll come to this. Inâ€¦ in most cases.

457
01:14:17.420 --> 01:14:23.329
Faculty (Olympus): The statisticalâ€¦ or the time average converges to the statistical average.

458
01:14:23.850 --> 01:14:29.119
Faculty (Olympus): Which is why the expectationâ€¦ that is what the expectation is supposed to mimic.

459
01:14:29.920 --> 01:14:35.230
Charles Ravi Kiran Mutsu .: So, the expected variable Is the time average?

460
01:14:35.230 --> 01:14:38.930
Faculty (Olympus): Expectation, the time, if you take many, many samples.

461
01:14:39.240 --> 01:14:49.380
Faculty (Olympus): The time average, as you take more and more samples, is going to converge, or is going to come closer and closer to the statistical average, or the expectation.

462
01:14:49.440 --> 01:14:53.180
Charles Ravi Kiran Mutsu .: Got it, got it. Because it is covering most of the sample space as we are goingâ€¦

463
01:14:53.180 --> 01:14:58.709
Faculty (Olympus): Yeah, yeah, yeah. Yeah, so these things are going to become closer and closer and closer to this.

464
01:14:58.890 --> 01:14:59.460
Charles Ravi Kiran Mutsu .: God.

465
01:14:59.600 --> 01:15:00.160
Charles Ravi Kiran Mutsu .: Thank you.

466
01:15:00.370 --> 01:15:03.560
Faculty (Olympus): Okay? Yeah, one last question, Vidya?

467
01:15:05.840 --> 01:15:22.040
Vidya Gavel .: Hi, Professor. So, my question is related to weightage average, which you explained at the beginning. So, can you explain it a little bit more, and how does it impact, and how it is calculated?

468
01:15:22.040 --> 01:15:26.399
Vidya Gavel .: Like, how do you calculate theâ€¦ the weight of,

469
01:15:27.170 --> 01:15:31.629
Vidya Gavel .: Each, each, experiment or samples.

470
01:15:32.590 --> 01:15:36.329
Faculty (Olympus): Are you talking about,

471
01:15:36.330 --> 01:15:39.420
Vidya Gavel .: The expected value? Yeah.

472
01:15:39.560 --> 01:15:45.680
Vidya Gavel .: So at the beginning, when you were explaining theâ€¦ The mean,

473
01:15:46.170 --> 01:15:49.210
Vidya Gavel .: At the very beginning, I think, youâ€¦

474
01:15:49.210 --> 01:15:50.129
Faculty (Olympus): I mean, this isâ€¦

475
01:15:50.130 --> 01:15:57.739
Vidya Gavel .: You mentioned somewhere that it's not the mean, but rather it is a weightage average.

476
01:15:57.740 --> 01:16:05.780
Faculty (Olympus): Yeah, so, I mean, this is what I was talking about. So, the expected value of X in a discrete random variable is defined as this quantity.

477
01:16:05.780 --> 01:16:06.790
Vidya Gavel .: Right.

478
01:16:06.790 --> 01:16:15.850
Faculty (Olympus): times this weight. So for every value of k, you are considering a certain weight, which is the probability associated with that.

479
01:16:16.340 --> 01:16:28.730
Faculty (Olympus): Right? Now, if Iâ€¦ if I said just the average, then you would think of the average as being, like, you know, you will sum all the possible values of k and then divide by the size, or the number of such values.

480
01:16:28.930 --> 01:16:37.639
Faculty (Olympus): A weighted average means you don't assign the same weight to each of these values. For every value of k, you assign the weight PXK.

481
01:16:38.600 --> 01:16:39.140
Faculty (Olympus): Okay?

482
01:16:39.140 --> 01:16:40.210
Vidya Gavel .: Right.

483
01:16:40.210 --> 01:16:43.059
Faculty (Olympus): Some of these PX case is, of course, 1.

484
01:16:43.750 --> 01:16:57.199
Faculty (Olympus): So for every value of K, so for a K value whose PMF is small or which is rare, this weight is going to be small. For a value of k which is likely, more likely, this PXK is going to be large, and so on.

485
01:16:58.970 --> 01:17:04.799
Faculty (Olympus): So that's what I mean by a weighted average. For every value of K, you are giving it a certain weight.

486
01:17:04.800 --> 01:17:07.949
Vidya Gavel .: Okay, okay, got it. Thank you.

487
01:17:08.390 --> 01:17:14.690
Faculty (Olympus): Okay, let's do, one more, example, soâ€¦

488
01:17:15.650 --> 01:17:17.869
Faculty (Olympus): I'm going to try and,

489
01:17:18.480 --> 01:17:32.190
Faculty (Olympus): give you an example from, maybe demand and supply. I mean, this example might have other contexts as well. So suppose, you know, I'm an e-retailer, and I have to

490
01:17:32.660 --> 01:17:34.270
Faculty (Olympus): decide

491
01:17:34.570 --> 01:17:43.119
Faculty (Olympus): some quantity of, stock that I should keep for a certain product, okay? So I have to decide, how muchâ€¦

492
01:17:44.790 --> 01:17:47.430
Faculty (Olympus): Of a product to stock.

493
01:17:50.060 --> 01:18:03.619
Faculty (Olympus): to stock on a particular day, and let's call that quantity Q. The problem is, I mean, I don't know the demand. The demand for this product each day is something that is uncertain, so let's say the demand

494
01:18:04.330 --> 01:18:15.410
Faculty (Olympus): D is uncertain on a given day. It is random on each day, right? And for this particular example, let's just take D to be uniform

495
01:18:15.780 --> 01:18:21.609
Faculty (Olympus): between 0 to 100, okay? So the demand can be,

496
01:18:21.610 --> 01:18:35.850
Faculty (Olympus): some, number between 0 to 100, and it's uncertain, what this quantity is going to be. And I want to keep a certain product Q,

497
01:18:35.870 --> 01:18:45.390
Faculty (Olympus): Now, each, productâ€¦ for each product, there is going to be a certain cost. So, forâ€¦ eachâ€¦

498
01:18:45.870 --> 01:18:51.490
Faculty (Olympus): Productâ€¦ There is a certain cost, and there is a certain sale price.

499
01:18:52.940 --> 01:19:06.420
Faculty (Olympus): Okay, so the cost, let's assume that to be 60 rupees, and the sales price, let's assume that to be 100 rupees. And if Iâ€¦ if I getâ€¦ so if I getâ€¦

500
01:19:06.840 --> 01:19:10.989
Faculty (Olympus): a demand, right, which is less than Q,

501
01:19:11.270 --> 01:19:19.789
Faculty (Olympus): Then, essentially, what has happened is that I will sell D of these, objects, and the remaining ones are going to go to waste.

502
01:19:20.200 --> 01:19:32.739
Faculty (Olympus): If my demand is larger than Q, then I can only sell up to Q of them, and some of the requests are going to go unanswered, right? So I want to figure out what the optimal value

503
01:19:32.740 --> 01:19:47.960
Faculty (Olympus): of Q is so that I maximize my expected profit. That is what I want to do, okay? So let's try and see how one can compute something like that. So to do that, I need to come up with

504
01:19:48.120 --> 01:19:55.560
Faculty (Olympus): A notion of revenue on the day, right? How much revenue will I actually make on the day?

505
01:19:55.720 --> 01:20:03.490
Faculty (Olympus): Right? So, how many items can I sell? The number of items that I can sell is going to be the minimum of the demand.

506
01:20:03.730 --> 01:20:20.370
Faculty (Olympus): and the number of items that I actually stocked, right? The total quantity that I stocked, and the demand that I get, right? It is going to be the minimum of these two. Why the minimum? If the demand is smaller than how much I have stocked, then D is what you will be able to sell.

507
01:20:20.840 --> 01:20:34.839
Faculty (Olympus): If, the demand is larger than how much you have stocked, you will only be able to sell Q, right? Because that is how much stock you have. Even if the demand is larger, you cannot service that demand, because the total amount that you have stocked is Q.

508
01:20:34.840 --> 01:20:42.110
Faculty (Olympus): So the total amount that you can sell is minimum of D and Q, so the total revenue, because the

509
01:20:42.340 --> 01:20:56.830
Faculty (Olympus): per unit, you make 100 rupees, so the total amount of revenue that you make is 100 times the minimum of D and Q. Alright, so this is my revenue. What is my cost? The cost

510
01:20:57.110 --> 01:21:03.610
Faculty (Olympus): is just the total amount of units that I buy times the price of each unit.

511
01:21:04.010 --> 01:21:04.770
Faculty (Olympus): Right?

512
01:21:05.020 --> 01:21:14.590
Faculty (Olympus): So this is a fixed quantity, it just depends on how many units I buy, and how many, what is the cost of each unit. So the overall profit

513
01:21:15.020 --> 01:21:16.299
Faculty (Olympus): that I make.

514
01:21:16.460 --> 01:21:20.580
Faculty (Olympus): It's going to be 100 times the minimumâ€¦

515
01:21:20.750 --> 01:21:37.649
Faculty (Olympus): of D and Q minus 60 times Q. That is the overall profit that I make, right? Now, what do I want to do? Now, this quantity, this profit that I'm seeing is a random quantity. Why is it a random quantity? Because this D

516
01:21:37.770 --> 01:21:39.450
Faculty (Olympus): Is something that isâ€¦

517
01:21:40.020 --> 01:21:49.829
Faculty (Olympus): uncertain, right? It has a certain distribution. It is, something which is uncertain. It can be some real number between,

518
01:21:50.180 --> 01:21:55.749
Faculty (Olympus): Between, 0â€¦ between 0 to 100, right?

519
01:21:56.440 --> 01:22:04.390
Faculty (Olympus): So, how do I, what can I talk about? I can talk about expected profit.

520
01:22:04.570 --> 01:22:16.260
Faculty (Olympus): Right? So profit is a random variable. I can talk about the expected profit. It is going to have some expectation. So that is the expected value of this quantity, 100 times

521
01:22:16.400 --> 01:22:22.680
Faculty (Olympus): the minimum of D and Q, And then minus 6TQ.

522
01:22:22.910 --> 01:22:33.949
Faculty (Olympus): Why is the minus 60Q outside the expectation? Because 60 times Q isâ€¦ that Q is aâ€¦ is a fixed quantity. That's not something that is, changing.

523
01:22:33.950 --> 01:22:40.330
Abhishek .: E should be 0 to Q, right? Not 100. Because Q is our stock limit, right?

524
01:22:40.330 --> 01:22:48.329
Faculty (Olympus): No, so the demand that comes is not limited by my stock, right? People demand based onâ€¦ they don't know what my stock is.

525
01:22:48.500 --> 01:22:53.579
Faculty (Olympus): the demand is going to come. I will not be able to service any demand beyond Q.

526
01:22:53.720 --> 01:22:58.940
Faculty (Olympus): Which is whyâ€¦ the profitâ€¦ the revenue isâ€¦ has minimum of D and Q.

527
01:22:59.180 --> 01:23:02.790
Faculty (Olympus): But the devalue, the demand for my product, can be anything.

528
01:23:02.900 --> 01:23:05.510
Faculty (Olympus): That is not dependent on how much I have stocked.

529
01:23:06.750 --> 01:23:07.450
Faculty (Olympus): Great.

530
01:23:07.730 --> 01:23:16.769
Faculty (Olympus): So that's why that can be something between 0 to 100, right? If Iâ€¦ if my demand turns out to be more than what I have stocked, then I'm just losing some sales. I'mâ€¦ I'm just not.

531
01:23:16.770 --> 01:23:24.450
Abhishek .: 100 has to be less than or equal to Q, or it can be more than that as well.

532
01:23:27.060 --> 01:23:39.589
Faculty (Olympus): So I know that the demand is between 0 to 100, so there is no reason for me to actually stock more than 100, right? I know the demand isâ€¦ has this uniform distribution between 0 to 100.

533
01:23:41.200 --> 01:23:41.600
Abhishek .: Okay.

534
01:23:41.600 --> 01:23:44.250
Faculty (Olympus): Okay, soâ€¦

535
01:23:44.830 --> 01:23:58.659
Faculty (Olympus): So how do we compute this expected value, right? How do I compute this expected value? So, I have to see how this, how this quantity behaves, right? How this expected value behaves.

536
01:23:58.730 --> 01:24:08.390
Faculty (Olympus): So let's, let's try and, compute this expectation. So maybe let's see, in fact, keep this within the expectation itself, it's okay. It's the same thing.

537
01:24:08.510 --> 01:24:21.340
Faculty (Olympus): Okay? So I have to find the expected value of this, quantity. So, how do I do this expectation, right? So the way to do this expectation is you have to find

538
01:24:23.150 --> 01:24:35.540
Faculty (Olympus): the expected profit, the random variable is D, which is uniform between 0 to 100, right? So the way I will, okay, let me call thisâ€¦

539
01:24:36.240 --> 01:24:45.830
Faculty (Olympus): a function F of D and Q, right? So the expected value is going to be the integral

540
01:24:46.330 --> 01:24:50.310
Faculty (Olympus): of the values that D can take, which is 0 to 100.

541
01:24:50.860 --> 01:24:54.499
Faculty (Olympus): Right? Times this FDQ,

542
01:24:58.390 --> 01:24:59.050
Faculty (Olympus): Good.

543
01:25:00.560 --> 01:25:04.200
Faculty (Olympus): Fâ€¦ DQ times

544
01:25:04.340 --> 01:25:12.739
Faculty (Olympus): Okay, maybe this F is not a good, let's call this G, because we use F for density as well, so I don't want to do that.

545
01:25:12.930 --> 01:25:22.659
Faculty (Olympus): Let's call this G. Okay, so this G is just this function, I'm just using that to save on some notation. So this function GDQ times my density

546
01:25:23.880 --> 01:25:25.359
Faculty (Olympus): Of my demand.

547
01:25:25.820 --> 01:25:31.640
Faculty (Olympus): Right? I'm going to integrate that over all values that this demand can take between 0 to 100.

548
01:25:31.770 --> 01:25:43.780
Faculty (Olympus): Now, this FDD is supposed to be a uniform random variable between 0 to 100, right? It's a uniform distributed random variable, so that's just 1 by 100. So this is going to be 1 by 100

549
01:25:43.940 --> 01:25:49.830
Faculty (Olympus): The integral from 0 to 100, ofâ€¦ GDQâ€¦

550
01:25:50.140 --> 01:25:53.950
Faculty (Olympus): And then you are integrating it over the range of D.

551
01:25:54.320 --> 01:25:55.070
Faculty (Olympus): Okay?

552
01:25:55.480 --> 01:26:11.379
Faculty (Olympus): I hope things are clear till now. Now, notice that this function GDQ, right, it changes behavior depending on whether D is smaller than Q or D is larger than Q. So, we will have to split this integral into two parts.

553
01:26:12.330 --> 01:26:16.659
Faculty (Olympus): So, we will write this integral as 1 by 100, that's fine.

554
01:26:17.610 --> 01:26:24.649
Faculty (Olympus): Now, you look at the integral from 0 to D, and you see what value does GDQ take.

555
01:26:25.050 --> 01:26:27.490
Faculty (Olympus): So, if you are integrating

556
01:26:28.120 --> 01:26:37.340
Faculty (Olympus): Fromâ€¦ notâ€¦ sorry, not from 0 to D. D is the demand, so you integrate, let's say the first part is 0 to Q,

557
01:26:38.040 --> 01:26:43.979
Faculty (Olympus): of GDQ, DD, and the second part is Q

558
01:26:44.110 --> 01:26:48.439
Faculty (Olympus): to 100 of the same quantity, GDQ.

559
01:26:52.620 --> 01:26:53.370
Faculty (Olympus): Duty.

560
01:26:56.290 --> 01:26:59.799
Abhineet Bansal: So, can you explain this DD? So, why this DD?

561
01:27:00.440 --> 01:27:18.540
Faculty (Olympus): So that's just the, I mean, what was DX before? I mean, my variable is, D here, that's why it's GD. Maybe, yeah, because it was demand, so it has become D, youâ€¦ yeah, we can call that GX if you want, it's okay.

562
01:27:18.540 --> 01:27:21.629
Siddharth Digambar Kulkarni .: Have we considered Q as constant here?

563
01:27:21.970 --> 01:27:31.280
Faculty (Olympus): Q is a specific constant. This is something that I have stocked beforehand, right? So, Q is some constant. I'm trying to find the best value of Q. So, okay, let meâ€¦ let me try and avoidâ€¦

564
01:27:31.420 --> 01:27:32.370
Faculty (Olympus): someâ€¦

565
01:27:33.200 --> 01:27:43.989
Faculty (Olympus): notational issues here, so that it becomesâ€¦ I don't want this, to be confusing. Let's, take this to be X.

566
01:27:44.090 --> 01:27:44.870
Faculty (Olympus): Okay.

567
01:27:44.980 --> 01:27:50.200
Faculty (Olympus): So, my demand isâ€¦ is justâ€¦ I denote that by the variable X,

568
01:27:50.430 --> 01:27:59.269
Faculty (Olympus): Which means you are integrating with DX. X goes from over this interval.

569
01:28:04.950 --> 01:28:19.009
Faculty (Olympus): Yeah, I think I've replaced it everywhere. Okay, so let meâ€¦ let me come back to this. I don'tâ€¦ I don't want to lose people. So, the expected value of this profit, profit isâ€¦ is a random variable, because it has

570
01:28:19.200 --> 01:28:31.050
Faculty (Olympus): this minimum of D comma Q. D is a uniform random variable between 0 to 100, right? So that is the randomness. So I'm talking about the expected profit.

571
01:28:31.050 --> 01:28:47.579
Faculty (Olympus): My goal is to choose a value of Q that maximizes my expected profit. Okay, so think of Q as some constant right now. I will eventually choose a value of Q, or I will choose an amount to stock which maximizes my expected profit. That is my goal.

572
01:28:47.680 --> 01:28:59.879
Faculty (Olympus): So I have to first evaluate this expected value of profit as a function of Q, and then I will maximize that quantity. That is my goal. So I want to find the expected value of this function.

573
01:29:00.030 --> 01:29:03.049
Faculty (Olympus): Which depends on D, and it also depends on Q.

574
01:29:03.300 --> 01:29:06.810
Faculty (Olympus): Now, the randomness is only in D, right? Soâ€¦

575
01:29:07.100 --> 01:29:10.810
Faculty (Olympus): How do I compute the expected value? I takeâ€¦

576
01:29:10.980 --> 01:29:20.269
Faculty (Olympus): the value of G at every possible value of the demand. The demand values can vary from 0 to 100, so that is GXQ.

577
01:29:20.390 --> 01:29:28.889
Faculty (Olympus): Then you have the density of the demand, right? FDX, and then integrating with DX. This is exactly ourâ€¦ our,

578
01:29:28.970 --> 01:29:42.100
Faculty (Olympus): how we compute the expected value of a certain random variable, right? So, we are taking the function of the random variable, we are taking the density associated with our random variable, and then we are looking at DX.

579
01:29:42.630 --> 01:29:44.550
Faculty (Olympus): Okay? Soâ€¦

580
01:29:44.930 --> 01:30:03.629
Faculty (Olympus): That means we areâ€¦ because the density is just uniform, so theâ€¦ the density is just 1x100, all the way from 0 to 100. So that's why this 1 by 100 comes out, and what you are integrating is just this function GXQ. That's all we are integrating over DX. Now, this function

581
01:30:04.100 --> 01:30:11.100
Faculty (Olympus): behaves differently depending on whether X is smaller than Q, or X is larger than Q.

582
01:30:11.870 --> 01:30:12.730
Faculty (Olympus): Right?

583
01:30:12.920 --> 01:30:16.039
Faculty (Olympus): If X is smaller than Q, then the function

584
01:30:16.830 --> 01:30:20.850
Faculty (Olympus): is just going to be 100X minus 60q.

585
01:30:21.130 --> 01:30:26.519
Faculty (Olympus): If X is larger than Q, then the function is going to be 100Q minus 60q.

586
01:30:26.740 --> 01:30:34.480
Faculty (Olympus): Right? The function takes two different forms, depending on whether X is going to be larger than Q, or X is going to be smaller than Q.

587
01:30:34.690 --> 01:30:40.990
Faculty (Olympus): Right? So that is why we have split the integral into two parts. So let's evaluate these quantities.

588
01:30:41.110 --> 01:30:44.960
Faculty (Olympus): Soâ€¦ What does the function look like?

589
01:30:45.140 --> 01:30:49.119
Faculty (Olympus): when you change X from 0 to Q.

590
01:30:50.040 --> 01:31:00.340
Faculty (Olympus): So, when X is between 0 to Q, the minimum of X and Q is going to be X, so this isâ€¦ this function is going to be 0 to Q

591
01:31:00.770 --> 01:31:11.300
Faculty (Olympus): 100 timesâ€¦ X minus 60 times Qâ€¦ And then you are doingâ€¦ DX.

592
01:31:11.470 --> 01:31:23.990
Faculty (Olympus): That is what, we are doing, right? So again, this is, something that we can, compute. So this integral, the first integral is 100 times

593
01:31:24.620 --> 01:31:29.539
Faculty (Olympus): X squared by 2â€¦ Evaluated at 0 and Q.

594
01:31:29.800 --> 01:31:35.670
Faculty (Olympus): The second quantity is minus 60q, which is justâ€¦ independent of

595
01:31:36.020 --> 01:31:39.859
Faculty (Olympus): X, so this becomes just 1 times DX.

596
01:31:39.980 --> 01:31:45.980
Faculty (Olympus): Right? What is this quantity? This integral turns out to beâ€¦ 100 times.

597
01:31:46.710 --> 01:31:57.530
Faculty (Olympus): Q squared by 2 minusâ€¦ 60 timesâ€¦ Q squared, so this isâ€¦

598
01:31:57.650 --> 01:32:02.140
Faculty (Olympus): minus 10 times Q squared. Okay, so the first integral.

599
01:32:02.350 --> 01:32:05.060
Faculty (Olympus): The first integral, or this part.

600
01:32:05.350 --> 01:32:08.170
Faculty (Olympus): is minus 10 times Q squared.

601
01:32:08.620 --> 01:32:14.310
Faculty (Olympus): Okay, so we have computed the first integral, now we want to compute the second integral.

602
01:32:14.540 --> 01:32:21.940
Faculty (Olympus): What is the second integral? Now, the second integral isâ€¦ You are integratingâ€¦

603
01:32:23.330 --> 01:32:24.560
Siddharth Digambar Kulkarni .: 200.

604
01:32:24.560 --> 01:32:30.780
Faculty (Olympus): So, G, X, Q, Set GXâ€¦ Qâ€¦

605
01:32:31.090 --> 01:32:35.030
Faculty (Olympus): DX. Now you're integrating from Q to 100.

606
01:32:35.390 --> 01:32:41.240
Faculty (Olympus): Again, GXQ involves the minimum of X and Q, now X is larger than Q.

607
01:32:41.400 --> 01:32:48.090
Faculty (Olympus): So the minimum is just going to be Q. So, this is going to be integral from Q to 100 of

608
01:32:48.540 --> 01:32:52.460
Faculty (Olympus): 100 times Q minus 60 times Q.

609
01:32:53.060 --> 01:32:54.380
Faculty (Olympus): of DX.

610
01:32:54.650 --> 01:33:08.990
Faculty (Olympus): Which is justâ€¦ 40 timesâ€¦ Qâ€¦ Integralâ€¦ 1DXâ€¦ integrated from Q to 100, So this isâ€¦ 40Qâ€¦

611
01:33:09.650 --> 01:33:11.709
Faculty (Olympus): 100 minus Q.

612
01:33:12.080 --> 01:33:19.889
Faculty (Olympus): Right? That is what this second integral is, is going to look like.

613
01:33:20.430 --> 01:33:26.319
Faculty (Olympus): Okay? So now we can combine the two things, right? So now I have my first integral.

614
01:33:27.020 --> 01:33:36.920
Faculty (Olympus): I've computed that, I have computed my second integral, I can now combine the two quantities. So, what does the combination look like? So, my expected value

615
01:33:37.240 --> 01:33:38.720
Faculty (Olympus): of my profit.

616
01:33:39.780 --> 01:33:44.010
Faculty (Olympus): is 1 by 100, Times.

617
01:33:44.670 --> 01:33:51.900
Faculty (Olympus): the first, integral, which was minus 10Q squared, Right?

618
01:33:52.060 --> 01:34:00.910
Faculty (Olympus): plusâ€¦ The second integral, which wasâ€¦ 4000â€¦ Q minusâ€¦

619
01:34:01.110 --> 01:34:05.090
Faculty (Olympus): 40q squared, right? This is my overall

620
01:34:05.300 --> 01:34:13.889
Faculty (Olympus): integral, or overall expected profit, which if I rewrite, Is, is exactlyâ€¦

621
01:34:14.310 --> 01:34:17.329
Faculty (Olympus): So this is 40 times Q.

622
01:34:17.850 --> 01:34:24.130
Faculty (Olympus): And thenâ€¦ minusâ€¦ 0.5 times Q squared.

623
01:34:25.050 --> 01:34:30.870
Faculty (Olympus): Okay? So my expected profitâ€¦ Is now a function

624
01:34:31.150 --> 01:34:33.600
Faculty (Olympus): of Q. How much do I stock?

625
01:34:33.810 --> 01:34:41.830
Faculty (Olympus): Right? It gives me a quadratic function of Q, and I can now choose the value of Q that maximizes this quantity.

626
01:34:42.550 --> 01:34:43.350
Faculty (Olympus): Okay?

627
01:34:43.460 --> 01:34:57.349
Faculty (Olympus): So how do I do that? How do I maximize this quantity? The way to do that isâ€¦ one way is by taking the derivative and then setting it to zero. That is how you can maximize this quantity. So, if I want to maximize this quantity.

628
01:34:57.760 --> 01:35:06.610
Faculty (Olympus): then you do a derivative of this expected profit with respect to the variable Q, which is going to be 40 minus

629
01:35:07.430 --> 01:35:13.349
Faculty (Olympus): 2 times 0.5 times Q, Which is justâ€¦

630
01:35:13.710 --> 01:35:24.060
Faculty (Olympus): 40 minus Q, and then you set this derivative To 0, which gives meâ€¦ Q star is 40.

631
01:35:24.410 --> 01:35:29.279
Faculty (Olympus): So, the optimal Stock size is 40.

632
01:35:29.620 --> 01:35:49.279
Faculty (Olympus): This is the optimal value of stock that I should select, so that I maximize my expected profit, given this uncertain demand. Given that the demand is uniform between 0 to 100, and the cost price of each object is 60, the sale price of each object is 100.

633
01:35:49.420 --> 01:35:51.460
Faculty (Olympus): The optimal stock value?

634
01:35:51.590 --> 01:35:57.640
Faculty (Olympus): Porâ€¦ For me, to maximize my expected profit is 40.

635
01:35:57.790 --> 01:36:08.099
Faculty (Olympus): Okay? Let me go through these steps once more, and then I'll take questions, okay? So let's see exactlyâ€¦ let's go through the whole example onceâ€¦ once again.

636
01:36:08.120 --> 01:36:18.319
Faculty (Olympus): To remind ourselves what really happened here, okay? So we started with saying we have a retailer who has a certain, item that they sell.

637
01:36:18.560 --> 01:36:24.359
Faculty (Olympus): They have to decide how much of the product to stock on each day.

638
01:36:24.500 --> 01:36:32.209
Faculty (Olympus): They don't know how much demand is going to come on the next day. The demand is a uniform random variable between 0 to 100.

639
01:36:32.710 --> 01:36:41.289
Faculty (Olympus): The cost of every unit of the item is 60, and the sale price of every unit is $100.

640
01:36:41.400 --> 01:36:48.069
Faculty (Olympus): Okay? So the revenue that they can make on any given day is 100 times the minimum of D and Q.

641
01:36:48.640 --> 01:37:00.750
Faculty (Olympus): Right? If your demand is smaller than how much you have stocked, then you are only going to be able to send D units. If your demand is larger than how much you have stocked, you can only sell how much you have stocked.

642
01:37:00.750 --> 01:37:15.809
Faculty (Olympus): So the revenue is going to be 100 times Q. Okay, so the overall revenue is 100 times the minimum of D and Q. The cost is going to be 60 times the number of units that you stock. So my overall profit

643
01:37:15.850 --> 01:37:20.710
Faculty (Olympus): isâ€¦ is this number, right? My overall profit is this number.

644
01:37:20.890 --> 01:37:24.859
Faculty (Olympus): Now, this profit is a random variable, because T is a random quantity.

645
01:37:25.000 --> 01:37:36.280
Faculty (Olympus): So I can talk about the expected amount of profit. So, that is the expected value of this function, of this random variable. The only randomness is in D.

646
01:37:36.610 --> 01:37:46.529
Faculty (Olympus): Okay, the only randomness is in D. There is no other randomness here. Q is some fixed quantity, and D is the only thing that is varying randomly.

647
01:37:46.870 --> 01:37:51.370
Faculty (Olympus): So, the expected value of this profit We are denoting

648
01:37:51.480 --> 01:37:56.189
Faculty (Olympus): Whatever is inside these brackets, we are denoting by this function GDQ.

649
01:37:57.140 --> 01:38:02.089
Faculty (Olympus): We are computing now the expected value of the profit. So, the expected value of the profit isâ€¦

650
01:38:02.700 --> 01:38:11.289
Faculty (Olympus): the value of the function at any point x, Times the density ofâ€¦ Corresponding to that X.

651
01:38:11.410 --> 01:38:15.370
Faculty (Olympus): And then you are integrating it over all values that this X can take.

652
01:38:15.480 --> 01:38:23.640
Faculty (Olympus): Right? So X is a demand variable which can go from 0 to 100, so that's why we are integrating this out from 0 to 100.

653
01:38:24.030 --> 01:38:33.600
Faculty (Olympus): Now, X is a uni- the demand is a uniform random variable, so this density is just going to be 1 by 100 everywhere, so that's why this comes out.

654
01:38:34.120 --> 01:38:46.599
Faculty (Olympus): So now you have 1 by 100 times the integral of this function GXQ over the interval 0 to 100. Now, notice GXQ is a function which has this minimum of X comma Q.

655
01:38:46.770 --> 01:39:04.200
Faculty (Olympus): So if X is smaller than U, Q, you are going to get 100X minus 60q. If X is larger than Q, you are going to get 100q minus 60q. So that's why we split the integral into two parts, 0 to Q and Q to 100. We evaluate these two integrals.

656
01:39:04.200 --> 01:39:10.210
Rahul Joshi .: Why 100Q minus 60q? If theâ€¦ There is a surplus quantity.

657
01:39:10.360 --> 01:39:21.609
Faculty (Olympus): So, if your D is larger than Q, then this quantity is going to be 100 times Q, right? Because the minimum is going to be Q, if D is larger than Q.

658
01:39:23.030 --> 01:39:28.250
Faculty (Olympus): The minimum of the two quantities, D and Q, is good, so you get 100q minus 60q.

659
01:39:28.520 --> 01:39:29.889
Faculty (Olympus): Which is 40 cubed.

660
01:39:31.960 --> 01:39:32.740
Faculty (Olympus): Okay?

661
01:39:33.100 --> 01:39:47.689
Faculty (Olympus): So, now it's just a matter of evaluating these two integrals separately, which is what we have done. Okay, so the rest is just about separately calculating these two integrals, and finding the expected profit as a function of Q.

662
01:39:48.370 --> 01:39:57.360
Faculty (Olympus): Once you have that as a function of Q, then you are just finding the value of Q that maximizes this expected profit, and that turns out to be 40.

663
01:39:57.950 --> 01:40:06.590
Faculty (Olympus): Okay? So that's what we have done overall. Okay? So I'm going to now take questions. I know there were a lot of steps involved here.

664
01:40:07.140 --> 01:40:14.220
Faculty (Olympus): But, yeah, I hope this gives some operational meaning to why, where this expectation might come about, okay?

665
01:40:14.560 --> 01:40:18.040
Faculty (Olympus): Okay, yeah, Sunil?

666
01:40:22.050 --> 01:40:29.859
Sunil Rawat .: Yes, so, I'm a bit confused about the hundred that you took initially.

667
01:40:29.970 --> 01:40:35.729
Sunil Rawat .: I understand it's a demand, it's a uniform demand, or random demand between 1 to 100.

668
01:40:35.970 --> 01:40:36.510
Sunil Rawat .: Andâ€¦

669
01:40:36.510 --> 01:40:37.410
Faculty (Olympus): 0 to 100, yeah.

670
01:40:37.410 --> 01:40:43.020
Sunil Rawat .: 0 to 100, yes. And bases their demand, the entire calculation is taking place.

671
01:40:43.120 --> 01:40:43.860
Faculty (Olympus): Yeah.

672
01:40:44.070 --> 01:40:49.259
Sunil Rawat .: So, can this demand be a skewed demand? Let's say demand is alwaysâ€¦

673
01:40:49.740 --> 01:40:56.999
Faculty (Olympus): Yeah, yeah, this could be anything. This could beâ€¦ I have taken it to be a uniform random variable between 0 to 100.

674
01:40:57.120 --> 01:41:15.259
Faculty (Olympus): But this could be an exponential, maybe a truncated exponential, or it could be something which is non-uniform. Maybe we could have a certain value between 0 to 10, then certainâ€¦ you can have a different kind of probabilities for different ranges, and so on.

675
01:41:15.610 --> 01:41:19.870
Sunil Rawat .: Okay, so in that case, the optimal value will be different.

676
01:41:19.870 --> 01:41:26.459
Faculty (Olympus): be different. Definitely, it'll be different. It'll definitely be different. But the way to compute will exactly be the same.

677
01:41:27.060 --> 01:41:37.139
Faculty (Olympus): The only thing that changes is that the densityâ€¦ the only place where weâ€¦ where that comes up is here, right? The density here is 1 by 100, soâ€¦

678
01:41:37.330 --> 01:41:44.410
Faculty (Olympus): We took that out. Whatever that density would be, we will just have to plug that density in and compute these integrals.

679
01:41:45.080 --> 01:41:50.229
Sunil Rawat .: Okay, okay, so in this entire calculation, that density is uniform.

680
01:41:50.230 --> 01:41:51.080
Faculty (Olympus): Yeah, that's it.

681
01:41:51.080 --> 01:41:53.649
Sunil Rawat .: That's theâ€¦ that's the, I would say.

682
01:41:53.800 --> 01:41:58.830
Sunil Rawat .: a point that we need to remember, that if Saty is skewed, then calculateâ€¦

683
01:41:58.830 --> 01:42:02.290
Faculty (Olympus): Yeah, the calculation from there onwards is going to be different.

684
01:42:02.850 --> 01:42:03.550
Sunil Rawat .: Okay.

685
01:42:03.550 --> 01:42:05.929
Faculty (Olympus): And for different densities, your optimalâ€¦

686
01:42:06.110 --> 01:42:09.290
Faculty (Olympus): Your optimal queue is definitely going to be different.

687
01:42:10.650 --> 01:42:11.420
Sunil Rawat .: Got it.

688
01:42:11.420 --> 01:42:13.810
Faculty (Olympus): Right? Yeah, okay, Gaurav?

689
01:42:15.440 --> 01:42:29.649
Gaurav Singh .: Yeah, Professor, it's not a question, but the last point where you have taken the derivative to identify the maxima, I think we have to take a double derivative also to find out whether the double derivative is negative, then only it is maxima, otherwise it is.

690
01:42:29.980 --> 01:42:37.440
Faculty (Olympus): You're absolutely right. If I reallyâ€¦ yeah, I was a little bit sloppy here.

691
01:42:38.480 --> 01:42:48.309
Faculty (Olympus): So, yeah, if I want to confirm that this is indeed a maxima and not a minima, I have to take the double derivative and make sure that it's a maxima.

692
01:42:48.680 --> 01:42:49.520
Faculty (Olympus): You're right.

693
01:42:52.210 --> 01:42:54.100
Faculty (Olympus): Okay, summer?

694
01:42:54.920 --> 01:42:59.539
Samar .: Yeah, so two questions. So one is,

695
01:42:59.640 --> 01:43:14.469
Samar .: basically, when we say this demand is uniform, what does this mean? Like, whatever is demand on day one, it's gonna be same across the other days?

696
01:43:14.470 --> 01:43:21.090
Faculty (Olympus): No, I mean, so think, maybe, think, let's say, the product that I stock is,

697
01:43:21.390 --> 01:43:28.690
Faculty (Olympus): is, well, anything, I mean, is maybe, you know, dosa batter.

698
01:43:28.840 --> 01:43:29.720
Kedar Digambar Gokhale .: Yeah.

699
01:43:29.720 --> 01:43:39.759
Faculty (Olympus): That is what I stock, okay? So today, people asked, the demand was 50.5 kgs of dosa batter was requested today.

700
01:43:40.420 --> 01:43:52.899
Faculty (Olympus): Tomorrow, maybe it's a weekend, maybe it'll come out to be 65, next day it might be 75, someday it might be 63.5. So every day the demand might change, right?

701
01:43:53.260 --> 01:44:06.949
Faculty (Olympus): And so it doesn't have to be exactly the same demand every day. I have to plan for tomorrow, right? I have to soak my rice, I have to soak my dal, and decide how much do I prepare for tomorrow.

702
01:44:07.590 --> 01:44:08.240
Samar .: Hmm.

703
01:44:08.240 --> 01:44:17.260
Faculty (Olympus): So that is what this is about. We are trying to decide on each day, we are trying to decide how much to stock for the next day.

704
01:44:17.820 --> 01:44:25.590
Faculty (Olympus): And, like someone pointed out, I mean, yeah, we are, of courseâ€¦ I mean, this is, like, an example, so I'm saying that the demand isâ€¦ firstly, it isâ€¦

705
01:44:26.010 --> 01:44:43.509
Faculty (Olympus): Every day it is uniform between 0 to 100. It need not be uniform, maybe it is some other distribution. But that is something you can track, right? You can maybe look historically, and come up with an empirical distribution, and then use that to come up with the optimal quantity to stock.

706
01:44:44.560 --> 01:44:53.169
Samar .: Okay, okay. And the second question, is, like, maybe this Maxima thing, like, when you take, I think of thisâ€¦

707
01:44:53.170 --> 01:44:53.550
Faculty (Olympus): Yeah.

708
01:44:53.550 --> 01:45:00.839
Samar .: Gaurav suggested, double generated. Can you just elaborate what, what does that mean, actually? I couldn't follow.

709
01:45:00.840 --> 01:45:13.549
Faculty (Olympus): So, I mean, theâ€¦ so, in termsâ€¦ whenever we are trying to find out, let's say, settingâ€¦ when we are trying to find the maxima or a minima.

710
01:45:13.750 --> 01:45:28.469
Faculty (Olympus): There are two tests that one has to run. The first is the first derivative test, which just gives us kind of the first order condition that this is a critical point.

711
01:45:28.470 --> 01:45:39.419
Faculty (Olympus): Okay, which means this could either be a maxâ€¦ so it could either happen that this function that we have is a quadratic function, so it could either behave something like this, or it could behave something like this.

712
01:45:40.160 --> 01:45:40.960
Faculty (Olympus): Right?

713
01:45:41.120 --> 01:45:43.549
Faculty (Olympus): And depending on the two situations.

714
01:45:44.010 --> 01:45:49.270
Faculty (Olympus): The derivative will be 0, the first derivative will be 0 in either of the two cases.

715
01:45:49.400 --> 01:45:56.920
Faculty (Olympus): So now, if I want to say that, you know, this is indeed a maxima, then I have to do a second derivative test.

716
01:45:57.210 --> 01:46:04.340
Faculty (Olympus): And, if the second derivative is, I think, negative, then it's a maxima, and if the second derivative is positive, then it's a maxima.

717
01:46:04.340 --> 01:46:07.040
Gaurav Singh .: Yeah, if it is second derivative, negative, then it is maximum.

718
01:46:07.040 --> 01:46:08.580
Faculty (Olympus): So, in this case.

719
01:46:08.710 --> 01:46:20.690
Faculty (Olympus): The second derivative, meaning that you take the derivative again of this quantity, is going to be exactly minus 1. So it is negative, which means that this critical point that we have found is indeed a maxima.

720
01:46:21.560 --> 01:46:22.320
Samar .: Okay.

721
01:46:22.320 --> 01:46:25.869
Faculty (Olympus): So that'sâ€¦ so yeah, youâ€¦ yeah, you have to do both of those steps.

722
01:46:25.870 --> 01:46:27.750
Siddharth Digambar Kulkarni .: decreasing, slope is decreasing.

723
01:46:27.750 --> 01:46:29.770
Faculty (Olympus): Correct, yeah. Scope is decreasing.

724
01:46:29.770 --> 01:46:32.020
Samar .: Okay, thank you. Okay.

725
01:46:32.020 --> 01:46:33.000
Faculty (Olympus): Vinay?

726
01:46:34.220 --> 01:46:47.419
vinay kaisar: I just didn't get the, derivation where it went to 40Q minus 0.5, I need some of the elaboration between these two steps. That will help.

727
01:46:47.610 --> 01:46:49.609
Faculty (Olympus): So, in between which two steps?

728
01:46:49.610 --> 01:46:55.649
vinay kaisar: How you come with 40Q minus 0.5Q square from the above?

729
01:46:55.650 --> 01:47:06.440
Faculty (Olympus): Okay, okay. Okay, got it. So, this is where, we were, okay? We had split the integral into two parts, and we had a 1x100 outside.

730
01:47:07.100 --> 01:47:11.350
Faculty (Olympus): Then the first integral turned out to be minus 10Q squared.

731
01:47:11.350 --> 01:47:12.100
vinay kaisar: Right?

732
01:47:12.340 --> 01:47:16.660
Faculty (Olympus): And the second integral turned out to be 40Q times 100 minus Q.

733
01:47:17.610 --> 01:47:18.270
vinay kaisar: Mhmhm.

734
01:47:18.270 --> 01:47:25.440
Faculty (Olympus): Now, I've just put downâ€¦ put together those two quantities. This is my first integral, this is the value of the second integral.

735
01:47:25.740 --> 01:47:26.809
vinay kaisar: Yes, yes.

736
01:47:27.170 --> 01:47:29.510
Faculty (Olympus): And I have a 1x100 outside.

737
01:47:30.410 --> 01:47:30.950
vinay kaisar: Right.

738
01:47:30.950 --> 01:47:38.029
Faculty (Olympus): Right? So now, this 1 by 100 times 4000Q is exactly this 40Q.

739
01:47:39.980 --> 01:47:47.239
vinay kaisar: Like, mathematically, how you derive data. Actually, I'm unable to do it on pen and paper. That's why I was asked.

740
01:47:47.240 --> 01:47:51.690
Faculty (Olympus): And this is just 4000 divided by 100, so that is 40.

741
01:47:52.030 --> 01:47:53.670
vinay kaisar: Okay? So that is whatâ€¦

742
01:47:53.670 --> 01:47:58.099
Faculty (Olympus): Q, and then you have minus 50q squared divided by 100.

743
01:47:58.100 --> 01:47:58.890
vinay kaisar: Night.

744
01:47:58.890 --> 01:48:05.150
Faculty (Olympus): So that, that gives meâ€¦ 50 by 100 is 0.5, so that gives me the minus 0.5Q square.

745
01:48:06.080 --> 01:48:08.280
vinay kaisar: 50, 100, yes, yes, got it.

746
01:48:08.460 --> 01:48:12.849
Faculty (Olympus): Soâ€¦ so overall, this is whyâ€¦ this is the overall expected profit.

747
01:48:12.850 --> 01:48:14.449
vinay kaisar: Right, I'll solve it.

748
01:48:15.930 --> 01:48:17.860
Faculty (Olympus): Okay? Manu?

749
01:48:22.670 --> 01:48:37.569
Manu Gupta .: Yes, sir. Here, my point is a basic one later. Actually, howâ€¦ when you're giving this example, so while approaching to this example, how we can, define our random variable X?

750
01:48:38.220 --> 01:48:50.730
Manu Gupta .: Because if we define it right, the further steps will be right, but if we define it in the wrong way, then further, weâ€¦ it will be the wrong answer for the observation.

751
01:48:50.920 --> 01:48:57.689
Faculty (Olympus): I mean, here, the only, randomness is in the demand, right? There is no other randomness.

752
01:48:58.020 --> 01:49:09.330
Faculty (Olympus): So, we are just computing the revenue, and then the goal was to maximize the expected profit. So, the first step is to find an expression for the expected profit.

753
01:49:09.680 --> 01:49:10.530
Faculty (Olympus): Alright?

754
01:49:10.700 --> 01:49:16.089
Faculty (Olympus): So, the only randomness here is inâ€¦ is in the demand deed, nothing else is random.

755
01:49:17.500 --> 01:49:20.489
Faculty (Olympus): Soâ€¦ yeah, there is no realâ€¦

756
01:49:20.870 --> 01:49:27.060
Faculty (Olympus): I mean, yeah, there's no real confusion about where the randomness is. The only randomness here is in the demand.

757
01:49:28.790 --> 01:49:29.580
Manu Gupta .: Okay.

758
01:49:29.790 --> 01:49:30.370
Faculty (Olympus): Right?

759
01:49:30.590 --> 01:49:32.310
Manu Gupta .: Wellâ€¦ Heck.

760
01:49:34.090 --> 01:49:43.350
Faculty (Olympus): Okay, so by the way, in terms of technical content, we are done for today, so if you want to leave, please go ahead. I'll just take questions, now.

761
01:49:44.440 --> 01:49:47.489
Faculty (Olympus): Okay, yeah, Sonu?

762
01:49:50.290 --> 01:50:03.829
Sonu Kumar .: Yeah, hi, Professor. I'm sorry. So, what I have understand is, till now, is the expected value of, I mean, for the RV, whatever we are calculating right now. So, that is something,

763
01:50:03.910 --> 01:50:18.180
Sonu Kumar .: average outcome of the repeated experiment, whatever we are doing. So, till ZP, I was able to understand, but the last 3 or 4 examples, I couldn'tâ€¦ couldn't understand howâ€¦ where we are taking the averages,

764
01:50:18.420 --> 01:50:21.449
Sonu Kumar .: To fit our, topic.

765
01:50:21.780 --> 01:50:24.400
Sonu Kumar .: So that's one thing,

766
01:50:24.760 --> 01:50:30.680
Sonu Kumar .: If any example you couldâ€¦ yeah, tillâ€¦ yeah, yeah, yeah, here. Tillâ€¦ till here, I was able to understandâ€¦

767
01:50:30.980 --> 01:50:36.399
Sonu Kumar .: After that, any one example, if you could explain once more, because, yep.

768
01:50:37.830 --> 01:50:41.350
Faculty (Olympus): So you were able to understand till the geometric? That's what you're saying? Yes.

769
01:50:41.350 --> 01:50:42.700
Sonu Kumar .: Yes, yes, yes.

770
01:50:42.700 --> 01:50:43.090
Faculty (Olympus): Okay?

771
01:50:43.090 --> 01:50:48.640
Sonu Kumar .: After that, I was not able to correlate with the average. I mean, the expectation of the RV,

772
01:50:49.070 --> 01:50:58.490
Sonu Kumar .: And the definition of expectations is, it'sâ€¦ it should be the average of a long experiment. So after that, I was not able to correlate, I don't know.

773
01:50:58.490 --> 01:51:04.190
Faculty (Olympus): Okay, yeah, maybe let me see if I can resolve the others and then come back.

774
01:51:04.190 --> 01:51:05.190
Sonu Kumar .: Yep, sure.

775
01:51:05.860 --> 01:51:08.600
Faculty (Olympus): Okay, devendra?

776
01:51:11.580 --> 01:51:20.310
Devendra Parmar .: Yes, sir. Sir, my question is, that withâ€¦ from the integration perspective, do we have to,

777
01:51:20.480 --> 01:51:28.260
Devendra Parmar .: Like, learn the basics of soft integration, which we had learned in the high school, like, forâ€¦ different,

778
01:51:28.560 --> 01:51:30.330
Devendra Parmar .: Types of expressions.

779
01:51:30.440 --> 01:51:32.590
Devendra Parmar .: There are some standard formulas. Do we have.

780
01:51:32.590 --> 01:51:32.990
Faculty (Olympus): Yeah, yeah.

781
01:51:32.990 --> 01:51:36.329
Devendra Parmar .: Bard from there, orâ€¦ I mean, that isâ€¦

782
01:51:36.420 --> 01:51:41.209
Faculty (Olympus): No, no, I mean, that's all, yeah, you need to know how to do integration.

783
01:51:41.590 --> 01:51:43.279
Faculty (Olympus): Okay, yeah.

784
01:51:44.210 --> 01:51:59.350
Devendra Parmar .: Answer, second question is that, in the support set of binomial random variable, so S values of S and starts from 0, 1, 2, 3, shouldn't it start from 1? Because, like, 0 experimentsâ€¦

785
01:51:59.550 --> 01:52:01.189
Devendra Parmar .: Doesn't make any sense, likeâ€¦

786
01:52:01.190 --> 01:52:09.960
Faculty (Olympus): No, that's not the experiment, right? That is how many successes do you see in the n experiments? The number of experiments is fixed, it's N.

787
01:52:10.940 --> 01:52:11.330
Devendra Parmar .: Well, dude.

788
01:52:11.330 --> 01:52:15.539
Faculty (Olympus): The random variable is telling me how many successes did I see in DNA experiments.

789
01:52:16.090 --> 01:52:16.830
Devendra Parmar .: Got it.

790
01:52:16.830 --> 01:52:19.900
Faculty (Olympus): Yeah, so it can be any number between 0 to n.

791
01:52:20.230 --> 01:52:27.500
Devendra Parmar .: Got it. And sir, one last question is that, in the latest example of the retail shop which we took.

792
01:52:27.700 --> 01:52:41.899
Devendra Parmar .: In that example, we assume that the demand is uniformly distributed. Yeah. So, does it mean that the demand is, like, historically, if you see the data of that retail shop.

793
01:52:42.190 --> 01:52:48.759
Devendra Parmar .: The probability of the values of the demand between 0 to 100 would more or less be same.

794
01:52:48.760 --> 01:52:53.959
Faculty (Olympus): Yeah, yeah. So something like that is what I am assuming in that toy example.

795
01:52:54.970 --> 01:52:57.599
Devendra Parmar .: Got it. And, sir, one more last question.

796
01:52:57.830 --> 01:53:11.729
Devendra Parmar .: In the geometric random variable, the expected value is 1 by P, so can itâ€¦ its interpretation would beâ€¦ couldâ€¦ could its interpretation would be like this? That given the

797
01:53:11.880 --> 01:53:13.290
Devendra Parmar .: Coin is out.

798
01:53:13.970 --> 01:53:21.389
Devendra Parmar .: unbiased coin. So, it would be 1 by P, that is 0.5. That means, on an average, in 2.

799
01:53:21.390 --> 01:53:23.309
Faculty (Olympus): No, 1 by P would then be 2.

800
01:53:23.950 --> 01:53:35.920
Devendra Parmar .: 1 by P would be 1xâ€¦ willâ€¦ will be resolved to 2. Yeah. So, would itâ€¦ wouldâ€¦ can we say that? That inâ€¦ at least inâ€¦ on an average, in two tosses, we can get the heads?

801
01:53:36.710 --> 01:53:43.669
Faculty (Olympus): Roughly speaking, yeah, yeah, maybe, roughly, but,

802
01:53:44.160 --> 01:53:46.550
Faculty (Olympus): Yeah, why it is exactly 2â€¦

803
01:53:46.740 --> 01:53:50.330
Faculty (Olympus): In that case, yeah, roughly, I guess, yes.

804
01:53:51.210 --> 01:54:03.959
Devendra Parmar .: So, in case of an unbiasedâ€¦ in case of unbiased coin, where, let's say, the probability of heads is 0.9, so in that case, it would resultâ€¦ the expected value will result to something around 1.11, a probability.

805
01:54:03.960 --> 01:54:05.829
Faculty (Olympus): Yeah, yeah, yeah, yeah, yeah, yeah.

806
01:54:06.490 --> 01:54:08.990
Devendra Parmar .: Okay. Yes, sir. Thank you very much.

807
01:54:08.990 --> 01:54:09.700
Faculty (Olympus): Okay.

808
01:54:10.060 --> 01:54:15.060
Faculty (Olympus): Okay, yeah, Swapnil?

809
01:54:15.950 --> 01:54:27.849
Swapnil Sankla .: Yeah, Professor, can you explain one more time? Why did we split that integration? I followed that we areâ€¦ it's based on some MIN between the D and Q, but can youâ€¦

810
01:54:28.370 --> 01:54:29.000
Swapnil Sankla .: Later today.

811
01:54:29.000 --> 01:54:36.749
Faculty (Olympus): So, I mean, so you see this function GDQ, right? So this function is what is playing the role here.

812
01:54:37.260 --> 01:54:41.480
Faculty (Olympus): is the role of D, and X is changing from 0 to 100.

813
01:54:41.780 --> 01:54:42.580
Swapnil Sankla .: Correct.

814
01:54:42.580 --> 01:54:52.470
Faculty (Olympus): Right? Now, as X changes, this function has different forms, right? If X, or theâ€¦ if the D

815
01:54:52.750 --> 01:54:57.510
Faculty (Olympus): So, let me maybe write thisâ€¦ Gdq here.

816
01:54:57.750 --> 01:54:58.360
Swapnil Sankla .: Sure.

817
01:55:00.470 --> 01:55:07.920
Faculty (Olympus): So this wasâ€¦ 100 timesâ€¦ Minus 60 cubed.

818
01:55:08.680 --> 01:55:12.540
Faculty (Olympus): So, in this case, this GDQ ifâ€¦

819
01:55:12.950 --> 01:55:15.510
Faculty (Olympus): D is less than equal to Q.

820
01:55:15.770 --> 01:55:20.229
Faculty (Olympus): then this GDQ, the minimum of the two quantities is going to be D.

821
01:55:20.570 --> 01:55:25.270
Faculty (Olympus): This has become 100D minus 60Q. That is what the function looks like.

822
01:55:25.840 --> 01:55:29.979
Faculty (Olympus): But if D is larger than Q, then the minimum is going to be Q.

823
01:55:30.380 --> 01:55:35.290
Faculty (Olympus): Which means the function is going to be 100Q minus 60q, which is 40Q.

824
01:55:36.550 --> 01:55:44.019
Faculty (Olympus): Right? So now, what I'm doing is I'm integrating over different values of D, going from 0 to 100.

825
01:55:44.880 --> 01:55:57.109
Faculty (Olympus): I'm integrating this function over different values of D, going from 0 to 100. But the function itself takes two different forms, right? Between 0 to Q, it takes this form.

826
01:55:57.790 --> 01:56:00.829
Faculty (Olympus): And between Q200, it takes this form.

827
01:56:01.210 --> 01:56:02.160
Swapnil Sankla .: Got it.

828
01:56:02.160 --> 01:56:09.380
Faculty (Olympus): So that's why I have to split into two different integrals, and then I'm just computing the two different integrals separately.

829
01:56:09.380 --> 01:56:12.729
Rahul Joshi .: if the demand is more than Q, which is the second part, right?

830
01:56:12.730 --> 01:56:13.350
Faculty (Olympus): Huh.

831
01:56:13.700 --> 01:56:17.269
Rahul Joshi .: thenâ€¦ then it doesn't matter, right? You're not going to sell it.

832
01:56:18.410 --> 01:56:19.879
Faculty (Olympus): I'm not going to do what?

833
01:56:20.260 --> 01:56:24.240
Rahul Joshi .: So if theâ€¦ if your quantity is, let's say, Q, and the demand is more than Q.

834
01:56:24.590 --> 01:56:24.960
Faculty (Olympus): Yo.

835
01:56:24.960 --> 01:56:27.269
Rahul Joshi .: Beyond queue, you're not going to sell it anyway, right?

836
01:56:27.270 --> 01:56:30.530
Faculty (Olympus): Yeah, yeah, so your cost is going to be 100Q,

837
01:56:31.810 --> 01:56:36.139
Faculty (Olympus): Your, sorry, your, sale price is going to be 100Q.

838
01:56:36.640 --> 01:56:42.620
Faculty (Olympus): And your overall cost is 60Q. So your overall profit is 40Q. We are talking about profit, right?

839
01:56:42.620 --> 01:56:47.039
Rahul Joshi .: I understand that, but why my sell price is 100q? Because I'm not going to sell it, right, beyond Q.

840
01:56:47.390 --> 01:56:52.279
Faculty (Olympus): Yeah, yeah, so 100 was the sale price of every unit, and Q is what you have sold.

841
01:56:54.000 --> 01:56:56.540
Faculty (Olympus): It's not 100D, it is 100 cubed.

842
01:56:57.270 --> 01:56:59.100
Faculty (Olympus): Q is what you have stocked.

843
01:57:00.370 --> 01:57:01.359
Rahul Joshi .: Oh, okay, okay, okay.

844
01:57:01.630 --> 01:57:04.549
Faculty (Olympus): Right? So 100Q is what you're going to earn that day.

845
01:57:07.990 --> 01:57:08.830
Faculty (Olympus): Okay?

846
01:57:10.020 --> 01:57:11.490
Faculty (Olympus): Harshad?

847
01:57:12.210 --> 01:57:15.850
Harshad Dilip Behere .: Yeah, so Professor, if we go to this example, I have 3 questions, actually.

848
01:57:15.850 --> 01:57:16.300
Faculty (Olympus): Okay?

849
01:57:16.300 --> 01:57:20.489
Harshad Dilip Behere .: So, first in, we assume that the demand will be a uniform random variable, right?

850
01:57:20.490 --> 01:57:20.820
Faculty (Olympus): Yeah.

851
01:57:20.820 --> 01:57:29.480
Harshad Dilip Behere .: So, earlier we derived a formula that it would be A plus B divided by 2. So, I meanâ€¦ I mean, I may be simplifying a lot. We cannot apply that directly here.

852
01:57:29.480 --> 01:57:40.559
Faculty (Olympus): No, because I'm not talking about the expected value of the demand. The expected value of the demand is exactly 100 plus 0 by 2.

853
01:57:41.010 --> 01:57:41.830
Harshad Dilip Behere .: Okay.

854
01:57:41.830 --> 01:57:50.070
Faculty (Olympus): But we are notâ€¦ I'm not asking you the expected value of the demand, right? I am asking about the expected value of this function of the demand.

855
01:57:52.070 --> 01:57:54.229
Harshad Dilip Behere .: Which is essentially profit we are trying to calculate.

856
01:57:55.270 --> 01:57:59.860
Faculty (Olympus): So, you are going to look at different values that this function can take.

857
01:58:00.400 --> 01:58:09.060
Faculty (Olympus): and then, see, and then weigh that with the randomness of, associated with D.

858
01:58:09.620 --> 01:58:18.040
Faculty (Olympus): That's why, if you see, the expected value When we compute, Right here.

859
01:58:18.910 --> 01:58:28.589
Faculty (Olympus): It's not D times FDX, or it's not X times FDX DX. That would have been the case if it wasâ€¦ we were just calculating the expected value of the demand.

860
01:58:29.110 --> 01:58:33.160
Faculty (Olympus): But we are computing the expected value of this function of the demand.

861
01:58:33.330 --> 01:58:36.119
Harshad Dilip Behere .: And we don't know what's the nature of this function as of now.

862
01:58:36.450 --> 01:58:53.770
Faculty (Olympus): we know theâ€¦ thisâ€¦ this is the function, right? For different values of D, the function is going to behave like this, and then you are essentially looking at how thisâ€¦ how likely different values of D are. That is what you're doing with this density of FDX, and then you're integrating it out.

863
01:58:53.980 --> 01:58:59.830
Harshad Dilip Behere .: Yeah, no, what I mean is that we are not kind of labeling this GQ as either uniform random variable or some other variable where.

864
01:58:59.830 --> 01:59:11.939
Faculty (Olympus): No, no, because that might be something hard to do. I don't know what exactly the density of this GDQ is. I'm just computing the expected value. So, in general, if X is your random variable.

865
01:59:12.300 --> 01:59:20.189
Faculty (Olympus): And let's say you have a function g of x, and you are interested in computing the expected value of this function.

866
01:59:20.400 --> 01:59:26.210
Faculty (Olympus): Then the expected value of this function is justâ€¦ takeâ€¦

867
01:59:26.900 --> 01:59:30.799
Faculty (Olympus): For any given value of X, see what the function value is.

868
01:59:30.960 --> 01:59:37.629
Faculty (Olympus): Weigh that by the density of the function, and integrate it over all values that X can take.

869
01:59:38.070 --> 01:59:42.879
Harshad Dilip Behere .: Okay, and why we have said that inâ€¦ Sorry, the density is 1 by 100 here?

870
01:59:43.030 --> 01:59:44.000
Harshad Dilip Behere .: In this example.

871
01:59:44.000 --> 01:59:49.130
Faculty (Olympus): We just assumed that the demand is uniform between 0 to 100, soâ€¦

872
01:59:49.130 --> 01:59:51.110
Harshad Dilip Behere .: So that's an interval of 100 minusâ€¦

873
01:59:51.110 --> 01:59:52.200
Faculty (Olympus): 100 minus zero.

874
01:59:52.200 --> 01:59:53.770
Harshad Dilip Behere .: 1 by B minus A, or something like that.

875
01:59:53.770 --> 01:59:55.480
Faculty (Olympus): Yeah, yeah, yeah, 1 by B minus A.

876
01:59:55.480 --> 02:00:01.310
Harshad Dilip Behere .: Okay, and I could not understand the derivatives part. To derive the profit, why finally we did the derivatives there?

877
02:00:01.310 --> 02:00:05.350
Faculty (Olympus): So, now I have this expected profit as a function of Q,

878
02:00:05.530 --> 02:00:10.999
Faculty (Olympus): Okay. And I want to find the optimal Q, which will maximize this expression.

879
02:00:11.600 --> 02:00:12.510
Harshad Dilip Behere .: Okay.

880
02:00:12.510 --> 02:00:15.880
Faculty (Olympus): So this expression is going to have, if you look at this expression.

881
02:00:16.070 --> 02:00:20.390
Faculty (Olympus): Okay, it's going to look something like this. It's a quadratic function of Q.

882
02:00:20.610 --> 02:00:24.790
Faculty (Olympus): So it has a certain value, Q star, where it takes the largest value.

883
02:00:25.150 --> 02:00:27.279
Faculty (Olympus): And I want to find that Q star.

884
02:00:28.750 --> 02:00:29.510
Harshad Dilip Behere .: Okay.

885
02:00:29.630 --> 02:00:33.039
Harshad Dilip Behere .: So, like, like a standard rule, we have to apply derivatives there, is it?

886
02:00:33.040 --> 02:00:36.030
Faculty (Olympus): Yeah, yeah. So, the standard way toâ€¦

887
02:00:36.500 --> 02:00:53.820
Faculty (Olympus): kind of find the maximum is that you take theâ€¦ especially when you have this kind of a quadratic, or such a concave curve, is you take the first derivative, you set it to zero, and then you verify that the second derivative at Q star is negative, then it's a maxima.

888
02:00:54.280 --> 02:00:56.649
Harshad Dilip Behere .: Okay, sure. Thank you.

889
02:00:56.900 --> 02:00:57.470
Faculty (Olympus): Okay.

890
02:00:58.540 --> 02:01:00.710
Faculty (Olympus): Okay, Nishtha?

891
02:01:04.680 --> 02:01:14.660
Nishtha Dutta .: Yeah, Professor, I just wanted to understand that how we are gettingâ€¦ I got that how we are getting 40Q minus 0.5Q squared.

892
02:01:15.360 --> 02:01:21.140
Nishtha Dutta .: But how are we getting this 40 minus 2 into 0.5 into Q?

893
02:01:21.140 --> 02:01:21.830
Faculty (Olympus): Okay.

894
02:01:21.830 --> 02:01:22.890
Nishtha Dutta .: So we.

895
02:01:22.890 --> 02:01:34.440
Faculty (Olympus): So, like I said, to find the optimal point of this function, 40Q minus 0.5Q squared, we have to first take the derivative of that expression with respect to Q.

896
02:01:36.410 --> 02:01:43.159
Nishtha Dutta .: Okay, so while taking the derivative, are we putting any value, default value for Q?

897
02:01:43.160 --> 02:01:52.049
Faculty (Olympus): No, no. First, we are just taking the derivative with respect to Q. That gives me 40 minus Q. The derivative of this expression.

898
02:01:52.390 --> 02:01:55.350
Faculty (Olympus): is, with respect to Q, is 40 minus Q.

899
02:01:57.260 --> 02:01:58.080
Nishtha Dutta .: Okay.

900
02:01:58.080 --> 02:02:02.719
Faculty (Olympus): Okay? And then we are setting that derivative to 0 to get a value of Q.

901
02:02:03.860 --> 02:02:05.720
Faculty (Olympus): the optimal value of Q.

902
02:02:08.610 --> 02:02:13.140
Nishtha Dutta .: Oh, so this equation which you have written is the second derivative.

903
02:02:13.790 --> 02:02:17.099
Faculty (Olympus): No, this is the first derivative itself. This 40 minus Q.

904
02:02:17.100 --> 02:02:17.830
Nishtha Dutta .: Thank you.

905
02:02:17.830 --> 02:02:21.899
Faculty (Olympus): is the first derivative. I'm setting that first derivative to 0.

906
02:02:22.650 --> 02:02:23.400
Nishtha Dutta .: Oh, okay.

907
02:02:23.400 --> 02:02:25.500
Faculty (Olympus): gives me Q star to be 40.

908
02:02:25.690 --> 02:02:28.320
Nishtha Dutta .: Okay, okay, I got it, yeah, yeah, got it.

909
02:02:28.320 --> 02:02:28.850
Faculty (Olympus): Yep.

910
02:02:29.970 --> 02:02:32.999
Faculty (Olympus): Okay, Sajith?

911
02:02:38.450 --> 02:02:44.640
Sajith K N .: Yeah, I think youâ€¦ you have already answered. I have a question that 1 minus, B minus A.

912
02:02:44.640 --> 02:02:45.180
Faculty (Olympus): Okay.

913
02:02:45.180 --> 02:02:46.969
Sajith K N .: So that part of that uniform.

914
02:02:47.850 --> 02:02:49.860
Faculty (Olympus): Fine. Rahul?

915
02:02:50.800 --> 02:02:58.059
Rahul Joshi .: Yeah, sir, Akhil I'm still notâ€¦ I still do not understand the second part of the split, actually. So, can you just please explain it again? Soâ€¦

916
02:02:58.440 --> 02:03:02.580
Rahul Joshi .: So what I understood is, if the demand is less than the stock.

917
02:03:02.730 --> 02:03:03.170
Faculty (Olympus): Mhmhmh.

918
02:03:03.170 --> 02:03:11.519
Rahul Joshi .: And then your 100 is the selling price into demand, minus 60K, understood, okay? But when your demand is more than the stock.

919
02:03:12.040 --> 02:03:12.450
Faculty (Olympus): Yeah.

920
02:03:12.570 --> 02:03:17.380
Rahul Joshi .: At that time, you are not going to sell more than whatever you have in the stock, right?

921
02:03:17.600 --> 02:03:18.150
Faculty (Olympus): Yeah.

922
02:03:18.610 --> 02:03:25.620
Rahul Joshi .: Okay, so why we are considering profit in that case? That the profit is going to be zero, right? Beyond your stock quantity.

923
02:03:25.620 --> 02:03:33.680
Faculty (Olympus): No, but, I mean, if I earnâ€¦ if I buy something at 60 and sell it at 100, I'm always going to make profit.

924
02:03:34.130 --> 02:03:36.730
Rahul Joshi .: But the demand is not more than Q, right?

925
02:03:36.730 --> 02:03:40.440
Faculty (Olympus): So, whatever I have stocked, Suppose I have stockedâ€¦

926
02:03:40.760 --> 02:03:48.929
Faculty (Olympus): 5 kgs of Doosa batter today. It costed me 60 rupees per kg, and I sell it at 100 rupees per kg.

927
02:03:49.490 --> 02:03:54.980
Faculty (Olympus): Overall profit that I'm going to make is 40 times 10K, 10, right?

928
02:03:54.980 --> 02:04:00.160
Rahul Joshi .: But if the stock is, let's say, 5KG.

929
02:04:00.410 --> 02:04:01.000
Faculty (Olympus): Yeah.

930
02:04:01.150 --> 02:04:09.660
Rahul Joshi .: Then, you, up to 5KG, you will, 100T minus 1600. Okay, but beyond 5 kg, you're not going to sell it, right?

931
02:04:10.110 --> 02:04:13.859
Faculty (Olympus): Okay, so we have 100 times Q. Q is how much I have stocked.

932
02:04:14.420 --> 02:04:17.170
Faculty (Olympus): That is the amount that I'm going to be able to sell.

933
02:04:18.990 --> 02:04:23.650
Faculty (Olympus): 100 times Q is the amount of revenue that I make today, right?

934
02:04:24.720 --> 02:04:31.999
Faculty (Olympus): Whatever I have stocked. No, no, demand is not Q. Demand is D. Q is what I have stocked.

935
02:04:33.400 --> 02:04:38.619
Rahul Joshi .: Yeah, but if the demand is lesser than your stock, okay, then the first equation holds good, right?

936
02:04:38.620 --> 02:04:38.950
Faculty (Olympus): Yeah.

937
02:04:39.380 --> 02:04:50.969
Rahul Joshi .: But if your demand is more than what you have stocked, let's say you have stocked only 10KG of batter, and your demand is, let's say, 30 kg, you're not going to sell beyond 10 kg, right?

938
02:04:50.970 --> 02:05:01.090
Faculty (Olympus): Yeah, yeah, so let's do the calculation. Let's say your demand is 30 kgs, you have stocked 10 kgs, okay, what is going to be your revenue?

939
02:05:03.860 --> 02:05:08.080
Rahul Joshi .: So, revenue is, your selling price is 100, right?

940
02:05:08.080 --> 02:05:09.929
Faculty (Olympus): Yeah. 100 times 10.

941
02:05:10.510 --> 02:05:12.500
Rahul Joshi .: 100 time states, yeah, correct, yeah.

942
02:05:12.500 --> 02:05:14.119
Faculty (Olympus): And what is my cost?

943
02:05:14.920 --> 02:05:16.669
Faculty (Olympus): 60 times 10.

944
02:05:17.040 --> 02:05:17.570
Rahul Joshi .: Yep.

945
02:05:18.280 --> 02:05:20.400
Faculty (Olympus): So, my profitâ€¦

946
02:05:24.420 --> 02:05:26.699
Faculty (Olympus): Is exactly 40 times.

947
02:05:27.400 --> 02:05:28.130
Faculty (Olympus): 10.

948
02:05:30.110 --> 02:05:31.779
Faculty (Olympus): Right? 40 times Q.

949
02:05:32.380 --> 02:05:38.059
Rahul Joshi .: 40 times 10, provided you sell 10, more than 10, orâ€¦ provided you sell all 10, right?

950
02:05:38.460 --> 02:05:41.800
Faculty (Olympus): Yeah, yeah, but my demand is 30, so I will definitely sell 10.

951
02:05:41.800 --> 02:05:43.030
Rahul Joshi .: Yeah, that's okay, okay?

952
02:05:43.030 --> 02:05:45.929
Faculty (Olympus): Yeah, so 40 times Q, so that's what it is.

953
02:05:45.930 --> 02:05:47.779
Rahul Joshi .: That is the first part of the equation, right?

954
02:05:48.160 --> 02:05:50.869
Faculty (Olympus): No, no, that's the second part, 40 times Q, right?

955
02:05:51.980 --> 02:05:54.070
Faculty (Olympus): The demand was larger.

956
02:05:54.260 --> 02:05:55.690
Faculty (Olympus): Then queue here.

957
02:05:57.500 --> 02:05:58.060
Sonu Kumar .: Sorry.

958
02:05:58.060 --> 02:05:58.450
Rahul Joshi .: Ron.

959
02:05:58.450 --> 02:06:02.589
Sonu Kumar .: So, Q is between 0 and 1, is that correct?

960
02:06:02.810 --> 02:06:09.440
Faculty (Olympus): No, no. Q is a bitâ€¦ I mean, demand is between 0 to 100, Q is also some number between 0 to 100.

961
02:06:10.870 --> 02:06:11.730
Sonu Kumar .: So, thank you.

962
02:06:11.730 --> 02:06:16.040
Rahul Joshi .: Yeah, that's okay, okay? So if the demand is more than Q, thenâ€¦

963
02:06:17.060 --> 02:06:20.060
Faculty (Olympus): Then my overall profit is 40 times Q.

964
02:06:20.720 --> 02:06:27.190
Rahul Joshi .: 40 times, okay? And if the demand is less thanâ€¦ Oh, so first part of the integration is when demand is less than Q.

965
02:06:27.190 --> 02:06:28.050
Faculty (Olympus): Yeah, yeah.

966
02:06:28.300 --> 02:06:30.269
Rahul Joshi .: Okay, okay, got it, no. Or is something.

967
02:06:30.580 --> 02:06:31.380
Faculty (Olympus): Okay.

968
02:06:31.960 --> 02:06:33.780
Faculty (Olympus): Rashmi?

969
02:06:37.810 --> 02:06:44.140
Rashmi .: My question is, outside this labor, so maybe you could ask Rahul first, and then I can have the last.

970
02:06:44.140 --> 02:06:47.680
Faculty (Olympus): Okay, rahul, I answered your question, no?

971
02:06:47.680 --> 02:06:56.860
Rahul Joshi .: Yeah, sorry, one more question, sir. In the last part of the, topic, you said you, youâ€¦

972
02:06:57.000 --> 02:07:00.660
Rahul Joshi .: Good derivative of that, quantity, right? It's 40 or something.

973
02:07:00.660 --> 02:07:01.389
Faculty (Olympus): Yeah, yeah.

974
02:07:01.390 --> 02:07:03.699
Rahul Joshi .: 40 minus. Can you just explain that part again, please?

975
02:07:03.960 --> 02:07:13.650
Faculty (Olympus): Yeah, so we now have the expected profit as a function of Q, and I want to choose the optimal value of Q so that I maximize this function value.

976
02:07:14.130 --> 02:07:17.829
Faculty (Olympus): Yep, for different values of Q, this function is going to have different values.

977
02:07:18.050 --> 02:07:18.440
Rahul Joshi .: Yep.

978
02:07:18.440 --> 02:07:21.310
Faculty (Olympus): Okay, and this function is in fact going to look something like this.

979
02:07:22.400 --> 02:07:27.679
Faculty (Olympus): So, we are just trying to find a Q star value that maximizes the value of this function.

980
02:07:29.580 --> 02:07:34.989
Faculty (Olympus): So, the way to do that, usually, is you take the derivative, first derivative of the function.

981
02:07:35.220 --> 02:07:42.050
Faculty (Olympus): Which is what we do, which isâ€¦ which the first derivative will be 40 minus 2 times 0.5 times Q.

982
02:07:42.620 --> 02:07:43.160
Rahul Joshi .: Oh, okay.

983
02:07:43.730 --> 02:07:47.880
Faculty (Olympus): So that gives me 40 minus Q. I set the first derivative to 0.

984
02:07:49.440 --> 02:07:55.700
Sonu Kumar .: So purposes are instead just, solving this for TQ minus 0.5Q2, so for T will beâ€¦

985
02:07:56.090 --> 02:08:05.110
Sonu Kumar .: 40Q will remain same, then 0.5Q2 will become 2 cross 0.5Q, and Q will be taken out. That will become 40 minutes Q.

986
02:08:05.110 --> 02:08:17.270
Faculty (Olympus): I mean, yeah, in this particular case, yes, because it's a quadratic, so that's why it looks like that. In general, you have to take the first derivative, set it to zero, that gives you a stationary point, and then

987
02:08:17.520 --> 02:08:23.389
Faculty (Olympus): The thing that I didn't do was, you have to usually verify that this is a maxima, not a minima.

988
02:08:23.520 --> 02:08:34.120
Faculty (Olympus): To do that, you take the second derivative and make sure that it is negative, which is the case here. If you take the second derivative of this, or you take the derivative again, you're going to get minus 1.

989
02:08:34.930 --> 02:08:42.540
Faculty (Olympus): Okay, so just maybe read up on first derivative and second derivative tests of optimality. Yeah, this is fairly standard.

990
02:08:43.570 --> 02:08:44.110
Sonu Kumar .: Yep.

991
02:08:46.830 --> 02:08:47.520
Faculty (Olympus): Okay.

992
02:08:47.730 --> 02:08:51.140
Faculty (Olympus): Devendra, do you have a question?

993
02:08:51.140 --> 02:09:01.789
Devendra Parmar .: Yes, sir. Sir, just a trivial one. For this semester, along with basics of integration and derivatives, are we expected to know a little bit of limits as well?

994
02:09:03.120 --> 02:09:10.790
Faculty (Olympus): Sort of, yeah, it'll be useful if you know, limits. We might not explicitlyâ€¦

995
02:09:11.000 --> 02:09:20.550
Faculty (Olympus): you use it, but I think when I talk about, let's say, law of large numbers or something like that, it'll be useful if you know what limits mean.

996
02:09:20.850 --> 02:09:26.849
Faculty (Olympus): And maybe the limits of some general sequences, some simple sequences, if you know, it'll be helpful.

997
02:09:27.460 --> 02:09:31.440
Devendra Parmar .: Got it. But more calculations will be focused on integration and.

998
02:09:31.440 --> 02:09:35.370
Faculty (Olympus): Yeah, yeah, yeah, yeah, yeah. Integration, series, these kind of things.

999
02:09:36.130 --> 02:09:37.040
Devendra Parmar .: Thank you, sir.

1000
02:09:37.040 --> 02:09:46.389
Faculty (Olympus): Okay, okay, there was, someone who had asked before, about some explanation, I don't remember who,

1001
02:09:47.280 --> 02:09:49.150
Faculty (Olympus): I don't know if you still need it.

1002
02:09:51.160 --> 02:09:53.549
Faculty (Olympus): Okay. Rashmi?

1003
02:09:54.760 --> 02:10:11.529
Rashmi .: I actually wanted to ask one question. It has been asked several times, but now I needed it most, so I'm asking. I'm looking for one book that can help me, these concepts, understand, you know, I need extra help on these concepts, because again, I'm also doing it after a long time.

1004
02:10:11.530 --> 02:10:17.089
Rashmi .: And I have bought the book that you, told us before, First Force in Probability, from Sheldon Ross.

1005
02:10:17.450 --> 02:10:33.429
Rashmi .: What I wanted to understand was, is this the, actually slavice of this course that we expect the exam to, you know, come from, or is it more than that, or is this less than that? Can I just, you know, suffice with this book? What would you say?

1006
02:10:33.430 --> 02:10:39.400
Faculty (Olympus): So, yeah, for all the topics that we are covering, all of these topics are there in this book.

1007
02:10:39.670 --> 02:10:40.170
Rashmi .: Right.

1008
02:10:40.170 --> 02:10:44.809
Faculty (Olympus): So, I am usually, whenever I'm doing any topic, I'm also referring

1009
02:10:44.940 --> 02:10:50.000
Faculty (Olympus): I'm giving the reference for the corresponding sections of that book.

1010
02:10:50.400 --> 02:10:58.599
Faculty (Olympus): So, if you can follow the book, if you can look at some of the solved examples, if you do the exercises that we are sharing.

1011
02:10:59.040 --> 02:11:00.690
Faculty (Olympus): That is sufficient.

1012
02:11:02.120 --> 02:11:04.939
Rashmi .: Okay. That is a vision. So nothing outside from the book, right?

1013
02:11:04.940 --> 02:11:11.479
Faculty (Olympus): No, no, nothing outside from the book as such, no. If you can do all of those things, I think you'll be fine.

1014
02:11:11.660 --> 02:11:24.610
Rashmi .: And at times, Professor, I have seen that, you know, I started with a couple of chapters, and I saw that it has some littleâ€¦ some extra concepts also, some extra, you know, further concepts also from what you are,

1015
02:11:24.610 --> 02:11:25.670
Faculty (Olympus): Yeah, yeah.

1016
02:11:25.670 --> 02:11:27.759
Rashmi .: So is it good to skip those, orâ€¦

1017
02:11:27.760 --> 02:11:30.909
Faculty (Olympus): I mean, if you are, so they have a certain flow.

1018
02:11:31.250 --> 02:11:36.030
Faculty (Olympus): If you are short on time, then I would say maybe

1019
02:11:36.250 --> 02:11:43.310
Faculty (Olympus): or at least try and read, or focus on the particular sections that I have mentioned.

1020
02:11:43.500 --> 02:11:43.920
Rashmi .: Boom.

1021
02:11:43.920 --> 02:12:03.140
Faculty (Olympus): But of course, there is some amount of continuity that the book also assumes, so if you can read through those things, that'll be good, I think, in terms of just understanding everything, but if you are looking for the minimum to read, then I would say maybe focus on the sections that I'm mentioning.

1022
02:12:03.140 --> 02:12:05.349
Rashmi .: Sounds good, sounds good. Thank you so much, Sudhu.

1023
02:12:05.850 --> 02:12:06.590
Faculty (Olympus): Sure.

1024
02:12:06.820 --> 02:12:08.340
Faculty (Olympus): Yeah, Siddharth?

1025
02:12:08.810 --> 02:12:27.559
Siddharth Digambar Kulkarni .: It's, some, exaâ€¦ some, means, questions which, can help us to, gain, more experience. Can youâ€¦ canâ€¦ can the support team share some questions which we can solve and get some more, confidence regarding this?

1026
02:12:27.560 --> 02:12:31.119
Faculty (Olympus): Yeah, so we have just posted one problem sheet again.

1027
02:12:31.120 --> 02:12:32.090
Siddharth Digambar Kulkarni .: Okay.

1028
02:12:32.120 --> 02:12:38.319
Faculty (Olympus): Which has a lot of questions, and this problem sheet will be covered in the TA sessions, plus additional questions will also be done.

1029
02:12:38.700 --> 02:12:39.430
Siddharth Digambar Kulkarni .: Okay.

1030
02:12:39.430 --> 02:12:39.940
Faculty (Olympus): Yeah.

1031
02:12:41.820 --> 02:12:45.980
Faculty (Olympus): Okay, alright, so we'll end here today.

1032
02:12:46.180 --> 02:12:48.110
Faculty (Olympus): See you later. Bye.

