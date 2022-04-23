# arithmetic-expression-in-binary-tree
<h3> i did this exercise just for fun to learning recursive descent with binary tree</h3>
<h3> i did another version just with recursive https://github.com/maxime-42/arithmetic_expression_evalution </h3>

<h3>-The purpose of this program is to do arithmetic expressions</h3>
<h3> computation as well as computation priority management</h3>

<h3> -I make two versions for the evaluation of an arithmetical expression:</h3>
<h3> - abstract syntax tree (AST)</h3>
<h3> - recursive descends</h3>


<h4>arithmetic_expression_evalution</h4>
<h4>-The purpose of this program is to do arithmetic expressions</h4>
<h4>computation as well as computation priority management</h4>

<h4>-I make two versions for the evaluation of an arithmetical expression:</h4>
<h4>- abstract syntax tree (AST)</h4>
<h4>- recursive descends</h4>

<h4>-I used the following grammar:</h4>
<h4>E -> T E'</h4>
<h4>E'-> + T E' | - T E' | ε</h4>
<h4>T -> F T'</h4>
<h4>T'-> * F T' | / F T' | % F T' | ε</h4>
<h4>F -> (E) | id</h4>

<h4>-to compute an arithmetical expression you must compile all the c files like this:</h4>
<h4>compile-> gcc -Wall -Wextra -Werror * .c</h4>
<h4>execute -> ./a.aout "1 + 1"</h4>

<h4>-for recursive descends I did not implement the modulo operator :)</h4>

<h4>-I helped myself with the following tutorials:</h4>
<h4>https://www.strchr.com/expression_evaluator</h4>
<h4>https://ruslanspivak.com/lsbasi-part7/</h4>
<h4>https://www.geeksforgeeks.org/evaluation-of-expression-tree/</h4>
