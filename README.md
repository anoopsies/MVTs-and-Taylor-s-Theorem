<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Quiz 05: Mean Value Theorems and Taylor's Theorem(by Anoop S V)</title>
  <script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
  <script id="MathJax-script" async
    src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
  <style>
    body { font-family: Arial, sans-serif; margin: 20px; }
    .question { margin-bottom: 20px; }
    button { padding: 10px; background: #007BFF; color: white; border: none; cursor: pointer; border-radius: 5px; }
    button:hover { background: #0056b3; }
    #result { margin-top: 20px; font-weight: bold; }
    .correct { color: green; }
    .incorrect { color: red; }
  </style>
</head>
<body>
  <h2>Quiz: Taylor Series, Maclaurin Series, and Mean Value Theorems</h2>
  <form id="quizForm">

    <div class="question">
      <p>1. The Maclaurin series expansion of \(e^x\) is:</p>
      <label><input type="radio" name="q1" value="b"> \(\sum_{n=0}^{\infty} \frac{(-x)^n}{n!}\)</label><br>
      <label><input type="radio" name="q1" value="a"> \(\sum_{n=0}^{\infty} \frac{x^n}{n!}\)</label><br>
      <label><input type="radio" name="q1" value="c"> \(\sum_{n=1}^{\infty} \frac{x^n}{n}\)</label><br>
      <label><input type="radio" name="q1" value="d"> None of these</label>
    </div>

    <div class="question">
      <p>2. The Taylor polynomial of degree 3 for \(f(x) = \sin x\) at \(x=0\) is:</p>
      <label><input type="radio" name="q2" value="d"> \(x\)</label><br>
      <label><input type="radio" name="q2" value="b"> \(x - \frac{x^2}{2}\)</label><br>
      <label><input type="radio" name="q2" value="c"> \(1 + x\)</label><br>
      <label><input type="radio" name="q2" value="a"> \(x - \frac{x^3}{6}\)</label>
    </div>

    <div class="question">
      <p>3. Rolle’s theorem applies if \(f\) is continuous on \([a,b]\), differentiable on \((a,b)\), and:</p>
      <label><input type="radio" name="q3" value="c"> \(f\) is bounded</label><br>
      <label><input type="radio" name="q3" value="b"> \(f'(a)=f'(b)\)</label><br>
      <label><input type="radio" name="q3" value="a"> \(f(a)=f(b)\)</label><br>
      <label><input type="radio" name="q3" value="d"> None of these</label>
    </div>

    <div class="question">
      <p>4. According to Lagrange’s Mean Value Theorem, there exists \(c \in (a,b)\) such that:</p>
      <label><input type="radio" name="q4" value="d"> None of these</label><br>
      <label><input type="radio" name="q4" value="a"> \(f'(c) = \frac{f(b)-f(a)}{b-a}\)</label><br>
      <label><input type="radio" name="q4" value="c"> \(f'(c) = \frac{f(b)}{f(a)}\)</label><br>
      <label><input type="radio" name="q4" value="b"> \(f'(c) = f(b)-f(a)\)</label>
    </div>

    <div class="question">
      <p>5. The Maclaurin series for \(\cos x\) is:</p>
      <label><input type="radio" name="q5" value="d"> None of these</label><br>
      <label><input type="radio" name="q5" value="a"> \(\sum_{n=0}^{\infty} (-1)^n \frac{x^{2n}}{(2n)!}\)</label><br>
      <label><input type="radio" name="q5" value="c"> \(\sum_{n=1}^{\infty} \frac{x^n}{n!}\)</label><br>
      <label><input type="radio" name="q5" value="b"> \(\sum_{n=0}^{\infty} (-1)^n \frac{x^{2n+1}}{(2n+1)!}\)</label>
    </div>

    <div class="question">
      <p>6. Let \(f(x)=x^2\) and \(g(x)=x+1\) on \([0,1]\). By Cauchy’s Mean Value Theorem, there exists \(c \in (0,1)\) such that:</p>
      <label><input type="radio" name="q6" value="d"> None of these</label><br>
      <label><input type="radio" name="q6" value="b"> \(f'(c)=g'(c)\)</label><br>
      <label><input type="radio" name="q6" value="c"> \(f(c)=g(c)\)</label><br>
      <label><input type="radio" name="q6" value="a"> \((f(1)-f(0))g'(c) = (g(1)-g(0))f'(c)\)</label>
    </div>

    <div class="question">
      <p>7. The Taylor series of \(\ln(1+x)\) about \(x=0\) (Maclaurin series) is:</p>
      <label><input type="radio" name="q7" value="d"> None of these</label><br>
      <label><input type="radio" name="q7" value="a"> \(\sum_{n=1}^{\infty} (-1)^{n+1}\frac{x^n}{n}\)</label><br>
      <label><input type="radio" name="q7" value="c"> \(\sum_{n=1}^{\infty} \frac{x^n}{n}\)</label><br>
      <label><input type="radio" name="q7" value="b"> \(\sum_{n=0}^{\infty} \frac{x^n}{n!}\)</label>
    </div>

    <div class="question">
      <p>8. Using the 2nd-degree Taylor polynomial of \(\cos x\) at \(x=0\), approximate \(\cos(0.5)\).</p>
      <label><input type="radio" name="q8" value="b"> \(0.5\)</label><br>
      <label><input type="radio" name="q8" value="c"> \(0.770\)</label><br>
      <label><input type="radio" name="q8" value="a"> \(0.875\)</label><br>
      <label><input type="radio" name="q8" value="d"> \(1.0\)</label>
    </div>

    <div class="question">
      <p>9. Which of the following is a necessary condition for Rolle’s theorem?</p>
      <label><input type="radio" name="q9" value="a"> \(f\) must be continuous on \([a,b]\)</label><br>
      <label><input type="radio" name="q9" value="d"> All of the above</label><br>
      <label><input type="radio" name="q9" value="c"> \(f(a)=f(b)\)</label><br>
      <label><input type="radio" name="q9" value="b"> \(f\) must be differentiable on \((a,b)\)</label>
    </div>

    <div class="question">
      <p>10. If \(f(x)=x^2\) on \([0,2]\), by Rolle’s theorem, there exists \(c\) such that:</p>
      <label><input type="radio" name="q10" value="b"> \(f'(c)=2\)</label><br>
      <label><input type="radio" name="q10" value="a"> \(f'(c)=0\)</label><br>
      <label><input type="radio" name="q10" value="d"> None of these</label><br>
      <label><input type="radio" name="q10" value="c"> Rolle’s theorem does not apply</label>
    </div>

    <button type="button" onclick="checkAnswers()">Submit</button>
  </form>

  <div id="result"></div>

  <script>
    const correctAnswers = {
      q1: "a",
      q2: "a",
      q3: "a",
      q4: "a",
      q5: "a",
      q6: "a",
      q7: "a",
      q8: "a",
      q9: "d",
      q10: "c"
    };

    function checkAnswers() {
      let score = 0;
      let resultHTML = "<h3>Results:</h3>";

      for (let q in correctAnswers) {
        let userAnswer = document.querySelector(`input[name="${q}"]:checked`);
        if (userAnswer) {
          if (userAnswer.value === correctAnswers[q]) {
            score++;
            resultHTML += `<p>Question ${q.substring(1)}: <span class="correct">Correct</span></p>`;
          } else {
            resultHTML += `<p>Question ${q.substring(1)}: <span class="incorrect">Incorrect</span></p>`;
          }
        } else {
          resultHTML += `<p>Question ${q.substring(1)}: <span class="incorrect">Not answered</span></p>`;
        }
      }

      resultHTML += `<p><strong>Total Score: ${score} / ${Object.keys(correctAnswers).length}</strong></p>`;
      document.getElementById("result").innerHTML = resultHTML;
    }
  </script>
</body>
</html>
