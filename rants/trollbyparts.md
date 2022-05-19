<head>
<script type="text/javascript" id="MathJax-script" async
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js">
</script>
</head>

# Troll Integration By Parts
published 2022-05-06

Have you ever wondered what happens if you let \\(u = c\\) for a constant \\(c\\)? Isn't \\(du\\) just 0? Here is a way to comprehend it dont laugh at me idk analysis.

Consider
\\[\int f(x) \ dx.\\]

Let \\(u\\) be a constant and \\(dv = f(x) \ dx \\) and \\(F(x)\\) be a primitive function of \\( f(x) \\). So we have

\\[
    \int f(x) dx = u^{-1}\int  u \ dv  \\
    = u^{-1} \left( uv - \int v \ du \right) \\
    = v - 0 = F(x) + C.
\\]

Notice also that
\\[\int f(x) dx = \int dv = v = F(x) + C.\\]

So basically you did nothing. :)