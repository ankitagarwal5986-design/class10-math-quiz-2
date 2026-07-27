# class10-math-quiz-2
Class 10 NCERT/MATH/ 20 Min/ challenge/ Chapter Wise
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Class 10 NCERT Mathematics - Master Board Practice Quiz</title>
    <style>
        :root {
            --primary: #1a365d;
            --secondary: #2b6cb0;
            --accent: #3182ce;
            --bg-light: #f7fafc;
            --card-bg: #ffffff;
            --text-dark: #2d3748;
            --border: #e2e8f0;
            --success: #38a169;
            --danger: #e53e3e;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--bg-light);
            color: var(--text-dark);
            margin: 0;
            padding: 0;
            line-height: 1.5;
        }

        .navbar {
            position: sticky;
            top: 0;
            background: var(--primary);
            color: white;
            padding: 12px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 2px 10px rgba(0,0,0,0.15);
            z-index: 1000;
        }

        .navbar h1 {
            margin: 0;
            font-size: 1.2rem;
            font-weight: 700;
        }

        .chapter-nav {
            background: #edf2f7;
            padding: 10px 20px;
            overflow-x: auto;
            white-space: nowrap;
            border-bottom: 1px solid var(--border);
        }

        .chip {
            display: inline-block;
            padding: 6px 14px;
            margin-right: 8px;
            background: white;
            border: 1px solid #cbd5e0;
            border-radius: 20px;
            font-size: 0.85rem;
            font-weight: 600;
            color: var(--secondary);
            cursor: pointer;
            text-decoration: none;
            transition: all 0.2s ease;
        }

        .chip:hover, .chip.active {
            background: var(--secondary);
            color: white;
            border-color: var(--secondary);
        }

        .container {
            max-width: 900px;
            margin: 20px auto;
            padding: 0 15px;
        }

        .chapter-card {
            background: var(--card-bg);
            border-radius: 8px;
            border: 1px solid var(--border);
            margin-bottom: 30px;
            box-shadow: 0 4px 6px -1px rgba(0,0,0,0.05);
            overflow: hidden;
            scroll-margin-top: 80px;
        }

        .chapter-header {
            background: var(--primary);
            color: white;
            padding: 12px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .chapter-header h2 {
            margin: 0;
            font-size: 1.1rem;
        }

        .question-box {
            padding: 18px;
            border-bottom: 1px solid var(--border);
        }

        .question-box:last-child {
            border-bottom: none;
        }

        .q-meta {
            display: flex;
            justify-content: space-between;
            margin-bottom: 8px;
            font-size: 0.85rem;
            color: #718096;
            font-weight: 600;
        }

        .badge {
            background: #ebf8ff;
            color: var(--secondary);
            padding: 2px 8px;
            border-radius: 4px;
        }

        .q-text {
            font-weight: 600;
            color: #1a202c;
            margin-bottom: 12px;
        }

        .math {
            font-family: 'Times New Roman', Times, serif;
            font-style: italic;
            font-size: 1.05rem;
        }

        .btn-toggle {
            background: #edf2f7;
            border: 1px solid #cbd5e0;
            color: var(--secondary);
            padding: 6px 12px;
            border-radius: 4px;
            font-size: 0.85rem;
            font-weight: 600;
            cursor: pointer;
            margin-top: 10px;
            transition: background 0.2s;
        }

        .btn-toggle:hover {
            background: #e2e8f0;
        }

        .solution-panel {
            display: none;
            margin-top: 12px;
            padding: 12px;
            background: #f7fafc;
            border-left: 4px solid var(--accent);
            border-radius: 0 4px 4px 0;
            font-size: 0.9rem;
        }

        .solution-panel.show {
            display: block;
        }

        footer {
            text-align: center;
            padding: 20px;
            font-size: 0.85rem;
            color: #718096;
            border-top: 1px solid var(--border);
            margin-top: 40px;
        }
    </style>
</head>
<body>

    <div class="navbar">
        <h1>CBSE Class 10 NCERT Mathematics — Master Quiz</h1>
        <button class="btn-toggle" style="margin:0; background:white; color:var(--primary);" onclick="toggleAllSolutions()">Toggle All Solutions</button>
    </div>

    <div class="chapter-nav">
        <a class="chip" href="#ch1">Ch 1: Real Numbers</a>
        <a class="chip" href="#ch2">Ch 2: Polynomials</a>
        <a class="chip" href="#ch3">Ch 3: Linear Equations</a>
        <a class="chip" href="#ch4">Ch 4: Quadratics</a>
        <a class="chip" href="#ch5">Ch 5: AP</a>
        <a class="chip" href="#ch6">Ch 6: Triangles</a>
        <a class="chip" href="#ch7">Ch 7: Coordinate Geo</a>
        <a class="chip" href="#ch8">Ch 8: Trigonometry</a>
        <a class="chip" href="#ch9">Ch 9: Applications of Trig</a>
        <a class="chip" href="#ch10">Ch 10: Circles</a>
        <a class="chip" href="#ch11">Ch 11: Areas & Circles</a>
        <a class="chip" href="#ch12">Ch 12: Surface Areas</a>
        <a class="chip" href="#ch13">Ch 13: Statistics</a>
        <a class="chip" href="#ch14">Ch 14: Probability</a>
    </div>

    <div class="container">

        <!-- CHAPTER 1 -->
        <div class="chapter-card" id="ch1">
            <div class="chapter-header">
                <h2>Chapter 1: Real Numbers</h2>
                <span>15 Marks | 5 Questions</span>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 1</span><span class="badge">1 Mark</span></div>
                <div class="q-text">If two positive integers <span class="math">a</span> and <span class="math">b</span> are written as <span class="math">a = x<sup>3</sup>y<sup>2</sup></span> and <span class="math">b = xy<sup>3</sup></span>, where <span class="math">x, y</span> are prime numbers, then find <span class="math">HCF(a, b)</span> and <span class="math">LCM(a, b)</span>.</div>
                <button class="btn-toggle" onclick="toggleSolution('s1_1')">Show Solution</button>
                <div class="solution-panel" id="s1_1"><strong>Answer:</strong> HCF = <span class="math">xy<sup>2</sup></span>, LCM = <span class="math">x<sup>3</sup>y<sup>3</sup></span>. <br><em>Explanations: Take lowest power for HCF and highest power for LCM of prime factors.</em></div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 2</span><span class="badge">2 Marks</span></div>
                <div class="q-text">Prove that <span class="math">&radic;2</span> is an irrational number using the method of contradiction.</div>
                <button class="btn-toggle" onclick="toggleSolution('s1_2')">Show Solution</button>
                <div class="solution-panel" id="s1_2"><strong>Solution:</strong> Assume <span class="math">&radic;2 = p/q</span> where <span class="math">p, q</span> are coprime integers. Squaring gives <span class="math">p<sup>2</sup> = 2q<sup>2</sup> &rArr; 2</span> divides <span class="math">p</span>. Let <span class="math">p = 2c &rArr; 4c<sup>2</sup> = 2q<sup>2</sup> &rArr; q<sup>2</sup> = 2c<sup>2</sup> &rArr; 2</span> divides <span class="math">q</span>. This contradicts that <span class="math">p, q</span> are coprime. Hence <span class="math">&radic;2</span> is irrational.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 3</span><span class="badge">3 Marks</span></div>
                <div class="q-text">Find the HCF and LCM of <span class="math">12, 15,</span> and <span class="math">21</span> using prime factorization. Verify if <span class="math">HCF &times; LCM = Product</span> holds for 3 numbers.</div>
                <button class="btn-toggle" onclick="toggleSolution('s1_3')">Show Solution</button>
                <div class="solution-panel" id="s1_3"><strong>Solution:</strong> <span class="math">12 = 2<sup>2</sup> &times; 3</span>, <span class="math">15 = 3 &times; 5</span>, <span class="math">21 = 3 &times; 7</span>. <br>HCF = 3, LCM = 420. <br><span class="math">HCF &times; LCM = 1260</span>, Product = 37800. The relation <strong>does not hold</strong> for 3 numbers.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 4</span><span class="badge">4 Marks</span></div>
                <div class="q-text">A sweet seller has 420 Kaju burfis and 130 Badam burfis. She wants to stack them equally to take least area. (i) Max burfis per stack? (ii) Total stacks?</div>
                <button class="btn-toggle" onclick="toggleSolution('s1_4')">Show Solution</button>
                <div class="solution-panel" id="s1_4"><strong>Solution:</strong> (i) <span class="math">HCF(420, 130) = 10</span> burfis per stack. <br>(ii) Total stacks = <span class="math">420/10 + 130/10 = 42 + 13 = 55</span> stacks.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 5</span><span class="badge">5 Marks</span></div>
                <div class="q-text">Prove that <span class="math">5 &minus; 2&radic;3</span> is irrational, given <span class="math">&radic;3</span> is irrational. State if sum/diff of rational and irrational is always irrational.</div>
                <button class="btn-toggle" onclick="toggleSolution('s1_5')">Show Solution</button>
                <div class="solution-panel" id="s1_5"><strong>Solution:</strong> Let <span class="math">5 &minus; 2&radic;3 = r &rArr; &radic;3 = (5 &minus; r)/2</span>. Since RHS is rational and LHS is irrational, contradiction proved. Yes, sum/difference is <strong>always irrational</strong>.</div>
            </div>
        </div>

        <!-- CHAPTER 2 -->
        <div class="chapter-card" id="ch2">
            <div class="chapter-header">
                <h2>Chapter 2: Polynomials</h2>
                <span>15 Marks | 5 Questions</span>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 1</span><span class="badge">1 Mark</span></div>
                <div class="q-text">If one zero of <span class="math">p(x) = (k &minus; 1)x<sup>2</sup> + kx + 1</span> is <span class="math">&minus;3</span>, find <span class="math">k</span>.</div>
                <button class="btn-toggle" onclick="toggleSolution('s2_1')">Show Solution</button>
                <div class="solution-panel" id="s2_1"><strong>Solution:</strong> Substitute <span class="math">x = &minus;3</span>: <span class="math">(k &minus; 1)9 &minus; 3k + 1 = 0 &rArr; 6k &minus; 8 = 0 &rArr; k = 4/3</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 2</span><span class="badge">2 Marks</span></div>
                <div class="q-text">Find zeroes of <span class="math">p(x) = 4s<sup>2</sup> &minus; 4s + 1</span> and verify zero-coefficient relations.</div>
                <button class="btn-toggle" onclick="toggleSolution('s2_2')">Show Solution</button>
                <div class="solution-panel" id="s2_2"><strong>Solution:</strong> <span class="math">(2s &minus; 1)<sup>2</sup> = 0 &rArr; s = 1/2, 1/2</span>. Sum = 1 = -b/a; Product = 1/4 = c/a. Verified.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 3</span><span class="badge">3 Marks</span></div>
                <div class="q-text">If <span class="math">&alpha;, &beta;</span> are zeroes of <span class="math">2x<sup>2</sup> &minus; 5x + 7</span>, find a quadratic polynomial with zeroes <span class="math">2&alpha; + 3&beta;</span> and <span class="math">3&alpha; + 2&beta;</span>.</div>
                <button class="btn-toggle" onclick="toggleSolution('s2_3')">Show Solution</button>
                <div class="solution-panel" id="s2_3"><strong>Solution:</strong> <span class="math">&alpha; + &beta; = 5/2, &alpha;&beta; = 7/2</span>. New Sum = <span class="math">5(&alpha;+&beta;) = 25/2</span>. New Product = <span class="math">6[(&alpha;+&beta;)<sup>2</sup> &minus; 2&alpha;&beta;] + 13&alpha;&beta; = 41</span>. Polynomial: <span class="math">k(2x<sup>2</sup> &minus; 25x + 82)</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 4</span><span class="badge">4 Marks</span></div>
                <div class="q-text">If <span class="math">&alpha;, &beta;</span> are zeroes of <span class="math">f(x) = x<sup>2</sup> &minus; p(x + 1) &minus; c</span>: (i) Prove <span class="math">(&alpha;+1)(&beta;+1) = 1 &minus; c</span>. (ii) Find <span class="math">c</span> if <span class="math">(&alpha;+1)(&beta;+1) = 0</span>.</div>
                <button class="btn-toggle" onclick="toggleSolution('s2_4')">Show Solution</button>
                <div class="solution-panel" id="s2_4"><strong>Solution:</strong> <span class="math">&alpha;+&beta; = p, &alpha;&beta; = &minus;(p+c)</span>. (i) <span class="math">(&alpha;+1)(&beta;+1) = &alpha;&beta; + (&alpha;+&beta;) + 1 = &minus;p &minus; c + p + 1 = 1 &minus; c</span>. (ii) <span class="math">1 &minus; c = 0 &rArr; c = 1</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 5</span><span class="badge">5 Marks</span></div>
                <div class="q-text">If the squared difference of zeroes of <span class="math">f(x) = x<sup>2</sup> + px + 45</span> is 144, find <span class="math">p</span>.</div>
                <button class="btn-toggle" onclick="toggleSolution('s2_5')">Show Solution</button>
                <div class="solution-panel" id="s2_5"><strong>Solution:</strong> <span class="math">(&alpha; &minus; &beta;)<sup>2</sup> = (&alpha; + &beta;)<sup>2</sup> &minus; 4&alpha;&beta; = 144 &rArr; (&minus;p)<sup>2</sup> &minus; 4(45) = 144 &rArr; p<sup>2</sup> = 324 &rArr; p = &plusmn;18</span>.</div>
            </div>
        </div>

        <!-- CHAPTER 3 -->
        <div class="chapter-card" id="ch3">
            <div class="chapter-header">
                <h2>Chapter 3: Pair of Linear Equations in Two Variables</h2>
                <span>15 Marks | 5 Questions</span>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 1</span><span class="badge">1 Mark</span></div>
                <div class="q-text">Find <span class="math">k</span> for infinitely many solutions: <span class="math">2x + 3y = 7</span> and <span class="math">(k + 1)x + (2k &minus; 1)y = 4k + 1</span>.</div>
                <button class="btn-toggle" onclick="toggleSolution('s3_1')">Show Solution</button>
                <div class="solution-panel" id="s3_1"><strong>Solution:</strong> <span class="math">2/(k+1) = 3/(2k&minus;1) &rArr; 4k &minus; 2 = 3k + 3 &rArr; k = 5</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 2</span><span class="badge">2 Marks</span></div>
                <div class="q-text">Solve: <span class="math">217x + 131y = 913</span> and <span class="math">131x + 217y = 827</span>.</div>
                <button class="btn-toggle" onclick="toggleSolution('s3_2')">Show Solution</button>
                <div class="solution-panel" id="s3_2"><strong>Solution:</strong> Add: <span class="math">x + y = 5</span>. Subtract: <span class="math">x &minus; y = 1</span>. Solving gives <span class="math">x = 3, y = 2</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 3</span><span class="badge">3 Marks</span></div>
                <div class="q-text">5 yrs ago Nuri was 3 times as old as Sonu. 10 yrs later Nuri will be twice as old. Find present ages.</div>
                <button class="btn-toggle" onclick="toggleSolution('s3_3')">Show Solution</button>
                <div class="solution-panel" id="s3_3"><strong>Solution:</strong> <span class="math">x &minus; 3y = &minus;10</span> and <span class="math">x &minus; 2y = 10 &rArr; y = 20, x = 50</span>. Nuri = 50 yrs, Sonu = 20 yrs.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 4</span><span class="badge">4 Marks</span></div>
                <div class="q-text">Sum of 2-digit number and its reverse is 66. Digits differ by 2. Find numbers.</div>
                <button class="btn-toggle" onclick="toggleSolution('s3_4')">Show Solution</button>
                <div class="solution-panel" id="s3_4"><strong>Solution:</strong> <span class="math">x + y = 6</span>. Case 1: <span class="math">x &minus; y = 2 &rArr; 42</span>. Case 2: <span class="math">y &minus; x = 2 &rArr; 24</span>. Numbers: 42 and 24.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 5</span><span class="badge">5 Marks</span></div>
                <div class="q-text">Solve <span class="math">2x &minus; y = 2</span> and <span class="math">4x &minus; y = 4</span> graphically. Find y-axis triangle vertices and area.</div>
                <button class="btn-toggle" onclick="toggleSolution('s3_5')">Show Solution</button>
                <div class="solution-panel" id="s3_5"><strong>Solution:</strong> Vertices: <span class="math">(1, 0), (0, &minus;2), (0, &minus;4)</span>. Base on y-axis = 2, Height = 1. Area = <span class="math">1/2 &times; 2 &times; 1 = 1 sq. unit</span>.</div>
            </div>
        </div>

        <!-- CHAPTER 4 -->
        <div class="chapter-card" id="ch4">
            <div class="chapter-header">
                <h2>Chapter 4: Quadratic Equations</h2>
                <span>15 Marks | 5 Questions</span>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 1</span><span class="badge">1 Mark</span></div>
                <div class="q-text">Find <span class="math">k</span> for equal real roots: <span class="math">kx(x &minus; 2) + 6 = 0</span>.</div>
                <button class="btn-toggle" onclick="toggleSolution('s4_1')">Show Solution</button>
                <div class="solution-panel" id="s4_1"><strong>Solution:</strong> <span class="math">D = (&minus;2k)<sup>2</sup> &minus; 4(k)(6) = 0 &rArr; 4k(k &minus; 6) = 0 &rArr; k = 6</span> (since <span class="math">k &ne; 0</span>).</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 2</span><span class="badge">2 Marks</span></div>
                <div class="q-text">Solve by factorization: <span class="math">&radic;3 x<sup>2</sup> + 10x + 7&radic;3 = 0</span>.</div>
                <button class="btn-toggle" onclick="toggleSolution('s4_2')">Show Solution</button>
                <div class="solution-panel" id="s4_2"><strong>Solution:</strong> <span class="math">&radic;3 x<sup>2</sup> + 3x + 7x + 7&radic;3 = 0 &rArr; (x + &radic;3)(&radic;3 x + 7) = 0 &rArr; x = &minus;&radic;3, &minus;7/&radic;3</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 3</span><span class="badge">3 Marks</span></div>
                <div class="q-text">Solve for <span class="math">x</span>: <span class="math">ab x<sup>2</sup> + (b<sup>2</sup> &minus; ac) x &minus; bc = 0</span>.</div>
                <button class="btn-toggle" onclick="toggleSolution('s4_3')">Show Solution</button>
                <div class="solution-panel" id="s4_3"><strong>Solution:</strong> <span class="math">bx(ax + b) &minus; c(ax + b) = 0 &rArr; (ax + b)(bx &minus; c) = 0 &rArr; x = &minus;b/a, c/b</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 4</span><span class="badge">4 Marks</span></div>
                <div class="q-text">Solve: <span class="math">1/(x+4) &minus; 1/(x&minus;7) = 11/30</span>.</div>
                <button class="btn-toggle" onclick="toggleSolution('s4_4')">Show Solution</button>
                <div class="solution-panel" id="s4_4"><strong>Solution:</strong> <span class="math">&minus;11/(x<sup>2</sup> &minus; 3x &minus; 28) = 11/30 &rArr; x<sup>2</sup> &minus; 3x + 2 = 0 &rArr; x = 1, 2</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 5</span><span class="badge">5 Marks</span></div>
                <div class="q-text">Motorboat speed 18 km/h in still water takes 1 hr more to go 24 km upstream than downstream. Find stream speed.</div>
                <button class="btn-toggle" onclick="toggleSolution('s4_5')">Show Solution</button>
                <div class="solution-panel" id="s4_5"><strong>Solution:</strong> <span class="math">24/(18&minus;x) &minus; 24/(18+x) = 1 &rArr; x<sup>2</sup> + 48x &minus; 324 = 0 &rArr; (x+54)(x&minus;6) = 0 &rArr; x = 6 km/h</span>.</div>
            </div>
        </div>

        <!-- CHAPTER 5 -->
        <div class="chapter-card" id="ch5">
            <div class="chapter-header">
                <h2>Chapter 5: Arithmetic Progressions</h2>
                <span>15 Marks | 5 Questions</span>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 1</span><span class="badge">1 Mark</span></div>
                <div class="q-text">Find 11th term from last term of AP: 10, 7, 4, ..., -62.</div>
                <button class="btn-toggle" onclick="toggleSolution('s5_1')">Show Solution</button>
                <div class="solution-panel" id="s5_1"><strong>Solution:</strong> <span class="math">L = &minus;62, d = &minus;3</span>. 11th term from end = <span class="math">&minus;62 &minus; 10(&minus;3) = &minus;32</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 2</span><span class="badge">2 Marks</span></div>
                <div class="q-text">If <span class="math">S<sub>n</sub> = 3n<sup>2</sup> + 5n</span>, find <span class="math">k</span>-th term and 15th term.</div>
                <button class="btn-toggle" onclick="toggleSolution('s5_2')">Show Solution</button>
                <div class="solution-panel" id="s5_2"><strong>Solution:</strong> <span class="math">a<sub>k</sub> = S<sub>k</sub> &minus; S<sub>k&minus;1</sub> = 6k + 2</span>. <span class="math">a<sub>15</sub> = 6(15) + 2 = 92</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 3</span><span class="badge">3 Marks</span></div>
                <div class="q-text">Find the sum of all three-digit natural numbers divisible by 7.</div>
                <button class="btn-toggle" onclick="toggleSolution('s5_3')">Show Solution</button>
                <div class="solution-panel" id="s5_3"><strong>Solution:</strong> AP: 105, 112, ..., 994 (<span class="math">n = 128</span>). Sum = <span class="math">64 &times; (105 + 994) = 70,336</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 4</span><span class="badge">4 Marks</span></div>
                <div class="q-text">If <span class="math">a<sub>m</sub> = 1/n</span> and <span class="math">a<sub>n</sub> = 1/m</span>, prove <span class="math">a<sub>mn</sub> = 1</span> and find <span class="math">S<sub>mn</sub></span>.</div>
                <button class="btn-toggle" onclick="toggleSolution('s5_4')">Show Solution</button>
                <div class="solution-panel" id="s5_4"><strong>Solution:</strong> Solving gives <span class="math">a = 1/mn, d = 1/mn</span>. <span class="math">a<sub>mn</sub> = 1/mn + (mn&minus;1)/mn = 1</span>. <span class="math">S<sub>mn</sub> = (mn+1)/2</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 5</span><span class="badge">5 Marks</span></div>
                <div class="q-text">Delay penalty: ₹200 for day 1, ₹250 for day 2, increasing by ₹50 daily. Find penalty for 30 days delay.</div>
                <button class="btn-toggle" onclick="toggleSolution('s5_5')">Show Solution</button>
                <div class="solution-panel" id="s5_5"><strong>Solution:</strong> <span class="math">a = 200, d = 50, n = 30</span>. <span class="math">S<sub>30</sub> = 15 [400 + 29(50)] = 15 &times; 1850 = ₹27,750</span>.</div>
            </div>
        </div>

        <!-- CHAPTER 6 -->
        <div class="chapter-card" id="ch6">
            <div class="chapter-header">
                <h2>Chapter 6: Triangles</h2>
                <span>15 Marks | 5 Questions</span>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 1</span><span class="badge">1 Mark</span></div>
                <div class="q-text">In <span class="math">&Delta;ABC</span>, <span class="math">DE || BC</span> with <span class="math">AD = x, DB = x&minus;2, AE = x+2, EC = x&minus;1</span>. Find <span class="math">x</span>.</div>
                <button class="btn-toggle" onclick="toggleSolution('s6_1')">Show Solution</button>
                <div class="solution-panel" id="s6_1"><strong>Solution:</strong> BPT: <span class="math">x/(x&minus;2) = (x+2)/(x&minus;1) &rArr; x<sup>2</sup> &minus; x = x<sup>2</sup> &minus; 4 &rArr; x = 4</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 2</span><span class="badge">2 Marks</span></div>
                <div class="q-text">Pole of 6 m casts 4 m shadow. At same time tower casts 28 m shadow. Find tower height.</div>
                <button class="btn-toggle" onclick="toggleSolution('s6_2')">Show Solution</button>
                <div class="solution-panel" id="s6_2"><strong>Solution:</strong> AA similarity: <span class="math">6/h = 4/28 &rArr; h = 42 m</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 3</span><span class="badge">3 Marks</span></div>
                <div class="q-text">In trapezium <span class="math">ABCD (AB || DC)</span>, diagonals intersect at <span class="math">O</span>. Show <span class="math">AO/BO = CO/DO</span>.</div>
                <button class="btn-toggle" onclick="toggleSolution('s6_3')">Show Solution</button>
                <div class="solution-panel" id="s6_3"><strong>Solution:</strong> Draw <span class="math">EO || AB</span>. BPT in <span class="math">&Delta;ADC</span> and <span class="math">&Delta;DAB</span> gives <span class="math">AO/CO = BO/DO &rArr; AO/BO = CO/DO</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 4</span><span class="badge">4 Marks</span></div>
                <div class="q-text">Girl 90 cm tall walks at 1.2 m/s away from 3.6 m lamp-post. Find shadow length after 4 s (NCERT Ex 7).</div>
                <button class="btn-toggle" onclick="toggleSolution('s6_4')">Show Solution</button>
                <div class="solution-panel" id="s6_4"><strong>Solution:</strong> <span class="math">BD = 4.8 m</span>. <span class="math">&Delta;ABE ~ &Delta;CDE &rArr; (4.8+x)/x = 3.6/0.9 = 4 &rArr; 3x = 4.8 &rArr; x = 1.6 m</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 5</span><span class="badge">5 Marks</span></div>
                <div class="q-text">Medians <span class="math">AD, PM</span> of <span class="math">&Delta;ABC ~ &Delta;PQR</span>. Prove (i) <span class="math">&Delta;ABD ~ &Delta;PQM</span> (ii) <span class="math">AB/PQ = AD/PM</span>.</div>
                <button class="btn-toggle" onclick="toggleSolution('s6_5')">Show Solution</button>
                <div class="solution-panel" id="s6_5"><strong>Solution:</strong> (i) <span class="math">AB/PQ = BC/QR = (2BD)/(2QM) = BD/QM</span> and <span class="math">&ang;B = &ang;Q &rArr; &Delta;ABD ~ &Delta;PQM</span> (SAS). (ii) Corresponding sides ratio gives <span class="math">AB/PQ = AD/PM</span>.</div>
            </div>
        </div>

        <!-- CHAPTER 7 -->
        <div class="chapter-card" id="ch7">
            <div class="chapter-header">
                <h2>Chapter 7: Coordinate Geometry</h2>
                <span>15 Marks | 5 Questions</span>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 1</span><span class="badge">1 Mark</span></div>
                <div class="q-text">Find distance between <span class="math">A(a, b)</span> and <span class="math">B(&minus;a, &minus;b)</span>.</div>
                <button class="btn-toggle" onclick="toggleSolution('s7_1')">Show Solution</button>
                <div class="solution-panel" id="s7_1"><strong>Solution:</strong> <span class="math">&radic;[(&minus;2a)<sup>2</sup> + (&minus;2b)<sup>2</sup>] = 2&radic;(a<sup>2</sup> + b<sup>2</sup>) units</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 2</span><span class="badge">2 Marks</span></div>
                <div class="q-text">Find point on x-axis equidistant from <span class="math">(2, &minus;5)</span> and <span class="math">(&minus;2, 9)</span>.</div>
                <button class="btn-toggle" onclick="toggleSolution('s7_2')">Show Solution</button>
                <div class="solution-panel" id="s7_2"><strong>Solution:</strong> <span class="math">(x&minus;2)<sup>2</sup> + 25 = (x+2)<sup>2</sup> + 81 &rArr; &minus;8x = 56 &rArr; x = &minus;7</span>. Point: <span class="math">(&minus;7, 0)</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 3</span><span class="badge">3 Marks</span></div>
                <div class="q-text">Find trisection points of segment joining <span class="math">(4, &minus;1)</span> and <span class="math">(&minus;2, &minus;3)</span>.</div>
                <button class="btn-toggle" onclick="toggleSolution('s7_3')">Show Solution</button>
                <div class="solution-panel" id="s7_3"><strong>Solution:</strong> Ratio 1:2 &rArr; <span class="math">(2, &minus;5/3)</span>. Ratio 2:1 &rArr; <span class="math">(0, &minus;7/3)</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 4</span><span class="badge">4 Marks</span></div>
                <div class="q-text">Find ratio in which y-axis divides <span class="math">(5, &minus;6)</span> and <span class="math">(&minus;1, &minus;4)</span> and point of intersection.</div>
                <button class="btn-toggle" onclick="toggleSolution('s7_4')">Show Solution</button>
                <div class="solution-panel" id="s7_4"><strong>Solution:</strong> <span class="math">x = 0 &rArr; &minus;k + 5 = 0 &rArr; k = 5</span> (Ratio 5:1). Point: <span class="math">(0, &minus;13/3)</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 5</span><span class="badge">5 Marks</span></div>
                <div class="q-text">Vertices of parallelogram: <span class="math">(1,2), (4,y), (x,6), (3,5)</span>. Find <span class="math">x, y</span> and diagonal lengths.</div>
                <button class="btn-toggle" onclick="toggleSolution('s7_5')">Show Solution</button>
                <div class="solution-panel" id="s7_5"><strong>Solution:</strong> Midpoints equal: <span class="math">x = 6, y = 3</span>. Diagonals: <span class="math">AC = &radic;41 units</span>, <span class="math">BD = &radic;5 units</span>.</div>
            </div>
        </div>

        <!-- CHAPTER 8 -->
        <div class="chapter-card" id="ch8">
            <div class="chapter-header">
                <h2>Chapter 8: Introduction to Trigonometry</h2>
                <span>15 Marks | 5 Questions</span>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 1</span><span class="badge">1 Mark</span></div>
                <div class="q-text">If <span class="math">15 cot A = 8</span>, find <span class="math">sin A</span> and <span class="math">sec A</span>.</div>
                <button class="btn-toggle" onclick="toggleSolution('s8_1')">Show Solution</button>
                <div class="solution-panel" id="s8_1"><strong>Solution:</strong> Hypotenuse = 17. <span class="math">sin A = 15/17</span>, <span class="math">sec A = 17/8</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 2</span><span class="badge">2 Marks</span></div>
                <div class="q-text">If <span class="math">tan(A+B) = &radic;3</span> and <span class="math">tan(A&minus;B) = 1/&radic;3</span>, find acute angles <span class="math">A, B</span>.</div>
                <button class="btn-toggle" onclick="toggleSolution('s8_2')">Show Solution</button>
                <div class="solution-panel" id="s8_2"><strong>Solution:</strong> <span class="math">A + B = 60&deg;, A &minus; B = 30&deg; &rArr; A = 45&deg;, B = 15&deg;</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 3</span><span class="badge">3 Marks</span></div>
                <div class="q-text">If <span class="math">3 cot A = 4</span>, check if <span class="math">(1&minus;tan<sup>2</sup>A)/(1+tan<sup>2</sup>A) = cos<sup>2</sup>A &minus; sin<sup>2</sup>A</span>.</div>
                <button class="btn-toggle" onclick="toggleSolution('s8_3')">Show Solution</button>
                <div class="solution-panel" id="s8_3"><strong>Solution:</strong> LHS = <span class="math">(1&minus;9/16)/(1+9/16) = 7/25</span>. RHS = <span class="math">16/25 &minus; 9/25 = 7/25</span>. Equal (Yes).</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 4</span><span class="badge">4 Marks</span></div>
                <div class="q-text">Prove: <span class="math">(sin A + cosec A)<sup>2</sup> + (cos A + sec A)<sup>2</sup> = 7 + tan<sup>2</sup>A + cot<sup>2</sup>A</span>.</div>
                <button class="btn-toggle" onclick="toggleSolution('s8_4')">Show Solution</button>
                <div class="solution-panel" id="s8_4"><strong>Solution:</strong> Expand: <span class="math">(sin<sup>2</sup>A+cos<sup>2</sup>A) + cosec<sup>2</sup>A + sec<sup>2</sup>A + 2(1) + 2(1) = 1 + 4 + (1+cot<sup>2</sup>A) + (1+tan<sup>2</sup>A) = 7 + tan<sup>2</sup>A + cot<sup>2</sup>A</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 5</span><span class="badge">5 Marks</span></div>
                <div class="q-text">Prove: <span class="math">tan &theta; / (1 &minus; cot &theta;) + cot &theta; / (1 &minus; tan &theta;) = 1 + sec &theta; cosec &theta;</span>.</div>
                <button class="btn-toggle" onclick="toggleSolution('s8_5')">Show Solution</button>
                <div class="solution-panel" id="s8_5"><strong>Solution:</strong> Convert to sin/cos: <span class="math">(sin<sup>3</sup>&theta; &minus; cos<sup>3</sup>&theta;) / [sin&theta;cos&theta;(sin&theta;&minus;cos&theta;)] = (1 + sin&theta;cos&theta;) / (sin&theta;cos&theta;) = 1 + sec&theta;cosec&theta;</span>.</div>
            </div>
        </div>

        <!-- CHAPTER 9 -->
        <div class="chapter-card" id="ch9">
            <div class="chapter-header">
                <h2>Chapter 9: Some Applications of Trigonometry</h2>
                <span>15 Marks | 5 Questions</span>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 1</span><span class="badge">1 Mark</span></div>
                <div class="q-text">Pole 6 m high casts <span class="math">2&radic;3 m</span> shadow. Find sun elevation.</div>
                <button class="btn-toggle" onclick="toggleSolution('s9_1')">Show Solution</button>
                <div class="solution-panel" id="s9_1"><strong>Solution:</strong> <span class="math">tan &theta; = 6 / (2&radic;3) = &radic;3 &rArr; &theta; = 60&deg;</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 2</span><span class="badge">2 Marks</span></div>
                <div class="q-text">Rope 20 m long tied at 30° to ground. Find pole height.</div>
                <button class="btn-toggle" onclick="toggleSolution('s9_2')">Show Solution</button>
                <div class="solution-panel" id="s9_2"><strong>Solution:</strong> <span class="math">sin 30&deg; = h / 20 &rArr; h = 10 m</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 3</span><span class="badge">3 Marks</span></div>
                <div class="q-text">Broken tree top touches ground at 30° at distance 8 m from base. Find total tree height.</div>
                <button class="btn-toggle" onclick="toggleSolution('s9_3')">Show Solution</button>
                <div class="solution-panel" id="s9_3"><strong>Solution:</strong> Standing <span class="math">h = 8/&radic;3</span>, broken <span class="math">x = 16/&radic;3</span>. Total <span class="math">= 24/&radic;3 = 8&radic;3 m &approx; 13.86 m</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 4</span><span class="badge">4 Marks</span></div>
                <div class="q-text">7 m high building: top tower elevation 60°, foot depression 45°. Find tower height.</div>
                <button class="btn-toggle" onclick="toggleSolution('s9_4')">Show Solution</button>
                <div class="solution-panel" id="s9_4"><strong>Solution:</strong> Base distance = 7 m. Upper tower = <span class="math">7&radic;3 m</span>. Total height = <span class="math">7(1 + &radic;3) m &approx; 19.12 m</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 5</span><span class="badge">5 Marks</span></div>
                <div class="q-text">75 m high lighthouse observes two ships at 30° and 45° depression. Find distance between ships.</div>
                <button class="btn-toggle" onclick="toggleSolution('s9_5')">Show Solution</button>
                <div class="solution-panel" id="s9_5"><strong>Solution:</strong> <span class="math">d<sub>1</sub> = 75 m, d<sub>2</sub> = 75&radic;3 m</span>. Distance = <span class="math">75(&radic;3 &minus; 1) m &approx; 54.9 m</span>.</div>
            </div>
        </div>

        <!-- CHAPTER 10 -->
        <div class="chapter-card" id="ch10">
            <div class="chapter-header">
                <h2>Chapter 10: Circles</h2>
                <span>15 Marks | 5 Questions</span>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 1</span><span class="badge">1 Mark</span></div>
                <div class="q-text">Distance OP = 13 cm, radius = 5 cm. Find tangent length.</div>
                <button class="btn-toggle" onclick="toggleSolution('s10_1')">Show Solution</button>
                <div class="solution-panel" id="s10_1"><strong>Solution:</strong> <span class="math">PQ = &radic;(13<sup>2</sup> &minus; 5<sup>2</sup>) = 12 cm</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 2</span><span class="badge">2 Marks</span></div>
                <div class="q-text">If <span class="math">&ang;POQ = 110&deg;</span> for tangents TP, TQ, find <span class="math">&ang;PTQ</span>.</div>
                <button class="btn-toggle" onclick="toggleSolution('s10_2')">Show Solution</button>
                <div class="solution-panel" id="s10_2"><strong>Solution:</strong> <span class="math">&ang;PTQ = 180&deg; &minus; 110&deg; = 70&deg;</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 3</span><span class="badge">3 Marks</span></div>
                <div class="q-text">Quadrilateral ABCD circumscribes a circle. Prove <span class="math">AB + CD = AD + BC</span>.</div>
                <button class="btn-toggle" onclick="toggleSolution('s10_3')">Show Solution</button>
                <div class="solution-panel" id="s10_3"><strong>Solution:</strong> Sum of equal tangent segments from vertices: <span class="math">AP+BP + CR+DR = AS+DS + BQ+CQ &rArr; AB+CD = AD+BC</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 4</span><span class="badge">4 Marks</span></div>
                <div class="q-text">Prove angle between two tangents from external point is supplementary to angle subtended at centre.</div>
                <button class="btn-toggle" onclick="toggleSolution('s10_4')">Show Solution</button>
                <div class="solution-panel" id="s10_4"><strong>Solution:</strong> In quad OAPB, <span class="math">&ang;OAP = &ang;OBP = 90&deg; &rArr; &ang;APB + &ang;AOB = 180&deg;</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 5</span><span class="badge">5 Marks</span></div>
                <div class="q-text">&Delta;ABC circumscribes r=4cm circle. Contact D divides BC into 8cm and 6cm. Find AB, AC.</div>
                <button class="btn-toggle" onclick="toggleSolution('s10_5')">Show Solution</button>
                <div class="solution-panel" id="s10_5"><strong>Solution:</strong> Equating Heron's area and inradius area: <span class="math">16(x+14)<sup>2</sup> = 48x(x+14) &rArr; x = 7</span>. <span class="math">AB = 15 cm, AC = 13 cm</span>.</div>
            </div>
        </div>

        <!-- CHAPTER 11 -->
        <div class="chapter-card" id="ch11">
            <div class="chapter-header">
                <h2>Chapter 11: Areas Related to Circles</h2>
                <span>15 Marks | 5 Questions</span>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 1</span><span class="badge">1 Mark</span></div>
                <div class="q-text">Find perimeter of sector with r = 14 cm, angle = 45°.</div>
                <button class="btn-toggle" onclick="toggleSolution('s11_1')">Show Solution</button>
                <div class="solution-panel" id="s11_1"><strong>Solution:</strong> Arc <span class="math">l = 11 cm</span>. Perimeter = <span class="math">11 + 2(14) = 39 cm</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 2</span><span class="badge">2 Marks</span></div>
                <div class="q-text">14 cm minute hand sweeps area in 5 mins. Find area.</div>
                <button class="btn-toggle" onclick="toggleSolution('s11_2')">Show Solution</button>
                <div class="solution-panel" id="s11_2"><strong>Solution:</strong> <span class="math">&theta; = 30&deg;</span>. Area = <span class="math">(30/360) &times; (22/7) &times; 196 = 154/3 cm<sup>2</sup> &approx; 51.33 cm<sup>2</sup></span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 3</span><span class="badge">3 Marks</span></div>
                <div class="q-text">Two 25 cm wipers sweep 115°. Find total cleaned area.</div>
                <button class="btn-toggle" onclick="toggleSolution('s11_3')">Show Solution</button>
                <div class="solution-panel" id="s11_3"><strong>Solution:</strong> <span class="math">2 &times; (115/360) &times; (22/7) &times; 625 = 158125 / 126 cm<sup>2</sup> &approx; 1254.96 cm<sup>2</sup></span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 4</span><span class="badge">4 Marks</span></div>
                <div class="q-text">r = 15 cm, angle = 60°. Find minor and major segment areas (&pi;=3.14, &radic;3=1.73).</div>
                <button class="btn-toggle" onclick="toggleSolution('s11_4')">Show Solution</button>
                <div class="solution-panel" id="s11_4"><strong>Solution:</strong> Minor Segment = <span class="math">117.75 &minus; 97.3125 = 20.4375 cm<sup>2</sup></span>. Major Segment = <span class="math">706.5 &minus; 20.4375 = 686.0625 cm<sup>2</sup></span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 5</span><span class="badge">5 Marks</span></div>
                <div class="q-text">Horse tied with 5 m rope in 15 m square field. Find (i) grazing area (ii) increase if rope is 10 m.</div>
                <button class="btn-toggle" onclick="toggleSolution('s11_5')">Show Solution</button>
                <div class="solution-panel" id="s11_5"><strong>Solution:</strong> (i) Quadrant area (r=5) = <span class="math">19.625 m<sup>2</sup></span>. (ii) Quadrant area (r=10) = <span class="math">78.5 m<sup>2</sup> &rArr; Increase = 58.875 m<sup>2</sup></span>.</div>
            </div>
        </div>

        <!-- CHAPTER 12 -->
        <div class="chapter-card" id="ch12">
            <div class="chapter-header">
                <h2>Chapter 12: Surface Areas and Volumes</h2>
                <span>15 Marks | 5 Questions</span>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 1</span><span class="badge">1 Mark</span></div>
                <div class="q-text">2 cubes of 64 cm³ volume joined end to end. Find cuboid surface area.</div>
                <button class="btn-toggle" onclick="toggleSolution('s12_1')">Show Solution</button>
                <div class="solution-panel" id="s12_1"><strong>Solution:</strong> <span class="math">a = 4 cm &rArr; l = 8, b = 4, h = 4</span>. Area = <span class="math">2(32 + 16 + 32) = 160 cm<sup>2</sup></span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 2</span><span class="badge">2 Marks</span></div>
                <div class="q-text">Hollow hemisphere (diam 14 cm) mounted by cylinder. Total height 13 cm. Find inner SA.</div>
                <button class="btn-toggle" onclick="toggleSolution('s12_2')">Show Solution</button>
                <div class="solution-panel" id="s12_2"><strong>Solution:</strong> <span class="math">r = 7 cm, h = 6 cm</span>. Area = <span class="math">2&pi;r(r+h) = 2 &times; (22/7) &times; 7 &times; 13 = 572 cm<sup>2</sup></span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 3</span><span class="badge">3 Marks</span></div>
                <div class="q-text">Cone (r=3.5 cm) on hemisphere. Total height 15.5 cm. Find TSA.</div>
                <button class="btn-toggle" onclick="toggleSolution('s12_3')">Show Solution</button>
                <div class="solution-panel" id="s12_3"><strong>Solution:</strong> <span class="math">h = 12 cm &rArr; l = 12.5 cm</span>. TSA = <span class="math">&pi;r(l + 2r) = (22/7) &times; 3.5 &times; 19.5 = 214.5 cm<sup>2</sup></span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 4</span><span class="badge">4 Marks</span></div>
                <div class="q-text">Cylinder (h=10 cm, r=3.5 cm) scooped out at both ends with hemispheres. Find TSA.</div>
                <button class="btn-toggle" onclick="toggleSolution('s12_4')">Show Solution</button>
                <div class="solution-panel" id="s12_4"><strong>Solution:</strong> TSA = <span class="math">2&pi;rh + 2(2&pi;r<sup>2</sup>) = 2&pi;r(h + 2r) = 22 &times; 17 = 374 cm<sup>2</sup></span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 5</span><span class="badge">5 Marks</span></div>
                <div class="q-text">45 Gulab jamuns (5 cm length, 2.8 cm diam). Find sugar syrup volume at 30% of total volume.</div>
                <button class="btn-toggle" onclick="toggleSolution('s12_5')">Show Solution</button>
                <div class="solution-panel" id="s12_5"><strong>Solution:</strong> Vol(1) = <span class="math">25.05 cm<sup>3</sup></span>. Vol(45) = <span class="math">1127.25 cm<sup>3</sup></span>. Syrup = <span class="math">30% of 1127.25 &approx; 338 cm<sup>3</sup></span>.</div>
            </div>
        </div>

        <!-- CHAPTER 13 -->
        <div class="chapter-card" id="ch13">
            <div class="chapter-header">
                <h2>Chapter 13: Statistics</h2>
                <span>15 Marks | 5 Questions</span>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 1</span><span class="badge">1 Mark</span></div>
                <div class="q-text">If Mode = 15 and Mean = 27, find Median.</div>
                <button class="btn-toggle" onclick="toggleSolution('s13_1')">Show Solution</button>
                <div class="solution-panel" id="s13_1"><strong>Solution:</strong> <span class="math">3 Median = Mode + 2 Mean = 15 + 54 = 69 &rArr; Median = 23</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 2</span><span class="badge">2 Marks</span></div>
                <div class="q-text">Find Mean for classes 10-25, 25-40, 40-55, 55-70, 70-85 with frequencies 2, 3, 7, 6, 2.</div>
                <button class="btn-toggle" onclick="toggleSolution('s13_2')">Show Solution</button>
                <div class="solution-panel" id="s13_2"><strong>Solution:</strong> <span class="math">&Sigma;f<sub>i</sub>x<sub>i</sub> = 995, &Sigma;f<sub>i</sub> = 20 &rArr; Mean = 49.75</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 3</span><span class="badge">3 Marks</span></div>
                <div class="q-text">Find Mode for ages 5-15, 15-25, 25-35, 35-45, 45-55, 55-65 with frequencies 6, 11, 21, 23, 14, 5.</div>
                <button class="btn-toggle" onclick="toggleSolution('s13_3')">Show Solution</button>
                <div class="solution-panel" id="s13_3"><strong>Solution:</strong> Modal class = 35-45. <span class="math">Mode = 35 + [(23&minus;21)/(46&minus;35)] &times; 10 = 36.82 years</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 4</span><span class="badge">4 Marks</span></div>
                <div class="q-text">Find Median for ages 20-25, 25-30, 30-35, 35-40, 40-45, 45-50 with frequencies 6, 18, 21, 33, 14, 8.</div>
                <button class="btn-toggle" onclick="toggleSolution('s13_4')">Show Solution</button>
                <div class="solution-panel" id="s13_4"><strong>Solution:</strong> <span class="math">N/2 = 50</span>. Median class = 35-40. <span class="math">Median = 35 + [(50&minus;45)/33] &times; 5 = 35.76 years</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 5</span><span class="badge">5 Marks</span></div>
                <div class="q-text">Median = 525, Total N = 100. Find missing frequencies <span class="math">x, y</span>.</div>
                <button class="btn-toggle" onclick="toggleSolution('s13_5')">Show Solution</button>
                <div class="solution-panel" id="s13_5"><strong>Solution:</strong> <span class="math">x + y = 35</span>. Median formula gives <span class="math">x = 9 &rArr; y = 26</span>.</div>
            </div>
        </div>

        <!-- CHAPTER 14 -->
        <div class="chapter-card" id="ch14">
            <div class="chapter-header">
                <h2>Chapter 14: Probability</h2>
                <span>15 Marks | 5 Questions</span>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 1</span><span class="badge">1 Mark</span></div>
                <div class="q-text">If <span class="math">P(E) = 0.05</span>, find <span class="math">P(E')</span>.</div>
                <button class="btn-toggle" onclick="toggleSolution('s14_1')">Show Solution</button>
                <div class="solution-panel" id="s14_1"><strong>Solution:</strong> <span class="math">P(E') = 1 &minus; 0.05 = 0.95</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 2</span><span class="badge">2 Marks</span></div>
                <div class="q-text">52 card deck. Find probability of (i) Red king (ii) Face card.</div>
                <button class="btn-toggle" onclick="toggleSolution('s14_2')">Show Solution</button>
                <div class="solution-panel" id="s14_2"><strong>Solution:</strong> (i) <span class="math">2/52 = 1/26</span>. (ii) <span class="math">12/52 = 3/13</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 3</span><span class="badge">3 Marks</span></div>
                <div class="q-text">90 discs (1 to 90). Find probability of (i) 2-digit number (ii) Perfect square (iii) Divisible by 5.</div>
                <button class="btn-toggle" onclick="toggleSolution('s14_3')">Show Solution</button>
                <div class="solution-panel" id="s14_3"><strong>Solution:</strong> (i) <span class="math">81/90 = 9/10</span>. (ii) <span class="math">9/90 = 1/10</span>. (iii) <span class="math">18/90 = 1/5</span>.</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 4</span><span class="badge">4 Marks</span></div>
                <div class="q-text">Two dice thrown. Find probability sum is (i) Equal to 8 (ii) Less than or equal to 12.</div>
                <button class="btn-toggle" onclick="toggleSolution('s14_4')">Show Solution</button>
                <div class="solution-panel" id="s14_4"><strong>Solution:</strong> (i) <span class="math">5/36</span>. (ii) <span class="math">36/36 = 1</span> (Sure Event).</div>
            </div>
            <div class="question-box">
                <div class="q-meta"><span>Question 5</span><span class="badge">5 Marks</span></div>
                <div class="q-text">12 defective, 132 good pens. (i) P(Good pen)? (ii) If 6 defective added, find new P(Defective).</div>
                <button class="btn-toggle" onclick="toggleSolution('s14_5')">Show Solution</button>
                <div class="solution-panel" id="s14_5"><strong>Solution:</strong> (i) <span class="math">132/144 = 11/12</span>. (ii) New defective = 18, Total = 150 &rArr; <span class="math">18/150 = 3/25</span>.</div>
            </div>
        </div>

    </div>

    <footer>
        CBSE Class 10 NCERT Mathematics Board Exam Series — Complete 14 Chapters Master Practice Document
    </footer>

    <script>
        function toggleSolution(id) {
            var panel = document.getElementById(id);
            if (panel.classList.contains('show')) {
                panel.classList.remove('show');
            } else {
                panel.classList.add('show');
            }
        }

        function toggleAllSolutions() {
            var panels = document.querySelectorAll('.solution-panel');
            var anyHidden = false;
            panels.forEach(function(p) {
                if (!p.classList.contains('show')) {
                    anyHidden = true;
                }
            });

            panels.forEach(function(p) {
                if (anyHidden) {
                    p.classList.add('show');
                } else {
                    p.classList.remove('show');
                }
            });
        }
    </script>
</body>
</html>
