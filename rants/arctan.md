<head>
<script type="text/javascript" id="MathJax-script" async
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js">
</script>
</head>

# A neat trick with inverse trigonometric functions
[..](..)\
published 2022-04-01

Disclaimer: no, this is not an April Fool's joke.

Update 2022-04-28: Michael Penn just did a video on solving a differential equation with a similar technique, go check it out [here](https://www.youtube.com/watch?v=ZE4jPfJyZAI).

## Bullshit, don't read

So I was practicing STEP while my brain was malfunctioning (at this point it might be the norm, so I guess functioning as normal?) and struggled to combine 2 arctangent expressions. Being the pussy I am, I checked the hints and wondered why I have never come across this before.

## The 'Trick'
Suppose I want to simplify \\(\arctan a + \arctan b\\), for \\(a, b\\) in the domain, one should consider \\(\tan(\arctan a + \arctan b)\\) and apply the compound angle formula. We obtain
\\[\arctan a + \arctan b = \arctan \left( \frac{a + b}{1-ab} \right).\\]
Unfortunately, this suffers from problems of the range of \\(ab\\). The above formula works only for \\(ab<1\\) due to signs and periods and stuff. For \\(ab > 1\\), we have the following cases:

For \\(a,b>0\\), we have 
\\[ \arctan a + \arctan b = \arctan\left(\frac{a+b}{1-ab}\right) + \pi \\]

For \\(a,b<0\\), we have
\\[ \arctan a + \arctan b = \arctan\left(\frac{a+b}{1-ab}\right) - \pi \\]
The proof is left as an exercise to the reader or you may consult these links on MathStackExchange, which explain things much clearer than I do: [https://math.stackexchange.com/questions/1724348/what-is-arctanx-arctany](https://math.stackexchange.com/questions/1724348/what-is-arctanx-arctany), and [https://math.stackexchange.com/questions/326334/a-question-about-the-arctangent-addition-formula](https://math.stackexchange.com/questions/326334/a-question-about-the-arctangent-addition-formula).

Do note that 
\\[\tan\left(\arctan a +\arctan b\right) = \frac{a+b}{1-ab}\\]
works for all \\(a, b\\) though.

Naturally, we may repeat this with similar functions and produce the following results:

\\[ \sin(\arcsin a + \arcsin b) = a\sqrt{1-b^2} + b\sqrt{1-a^2} \text{ for } a, b \in [-1,1]\\]

\\[ \sin(\arcsin a + \arccos b) = ab + \sqrt{(1-a^2)(1-b^2)} \text{ for } a, b \in [-1,1]\\]
Similar results may be derived for other trigonometric functions.

We now turn our attention to hyperbolic trigonometric functions. Actually, no, we are not going to do that since that is just logarithms.
