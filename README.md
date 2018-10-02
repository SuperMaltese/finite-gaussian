# gaussian
Calculates solution to a system of linear equations mod m using Gaussian Elimination  
m should be prime  
<h2>Inputs</h2>
<ul>
<li>Number of equations</li>
<li>Modulo m</li>
<li>Coefficients of equation 1</li>
<li>Coefficients of equation 2</li>
<li>etc...</li>
<li>Empty Line</li>
<li>Last column of matrix</li>

<h2>Output</h2>
Solutions to variables, in order

<h2>Example</h2>
<table>
  <tr>
    <th>1</th>
    <th>1</th>
    <th>1</th>
    <th>1</th>
    <th>4</th>
    <th></th>
    <th>4</th>
  </tr>
  <tr>
  <th>2</th>
  <th>3</th>
  <th>5</th>
  <th>4</th>
  <th>1</th>
  <th></th>
  <th>3</th>
  </tr>
  <tr>
  <th>2</th>
  <th>3</th>
  <th>4</th>
  <th>6</th>
  <th>5</th>
  <th></th>
  <th>2</th>
  </tr>
  <tr>
  <th>1</th>
  <th>2</th>
  <th>3</th>
  <th>4</th>
  <th>5</th>
  <th></th>
  <th>1</th>
  </tr>
  <tr>
  <th>1</th>
  <th>4</th>
  <th>2</th>
  <th>3</th>
  <th>5</th>
  <th></th>
  <th>5</th>
  </tr>

If the above is the matrix you wish to solve mod 7, the input should be like this:  
5
7
1 1 1 1 4
2 3 5 4 1
2 3 4 6 5
1 2 3 4 5
1 4 2 3 5

4 3 2 1 5
