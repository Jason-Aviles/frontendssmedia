<section class="question-view__instruction"><div class="candidate-rich-text"><div id="4oq9iap6o67-instruction"><p><span style="font-size:18px;"><span style="font-family:Verdana,Geneva,sans-serif;">This is the only required section of this Assessment. To qualify for this position you need to be able to successfully write this simple array to matrix transformation program. It's not a difficult problem and if you select a high level language like Java or Python or Javascript, then it won't take a lot of code to write this program. If you choose to write it in C or another low level language, it could take a lot of code. You are free to write this program in any computer language of your choice.&nbsp;</span></span></p>

<p>&nbsp;</p>

<p><span style="font-size:18px;"><span style="font-family:Verdana,Geneva,sans-serif;">Hints for passing this assessment :</span></span></p>

<ol>
	<li><span style="font-size:18px;"><span style="font-family:Verdana,Geneva,sans-serif;">Take your time and write the code like a professional.</span></span></li>
	<li><span style="font-size:18px;"><span style="font-family:Verdana,Geneva,sans-serif;">Be kind to the assessment graders - make the code easy to read and understand.&nbsp;</span></span></li>
	<li><span style="font-size:18px;"><span style="font-family:Verdana,Geneva,sans-serif;">Coding syntax is not important but readability and good logic is. For example, we don't care if you miss a semicolon or if you misspell something.</span></span></li>
	<li><span style="font-size:18px;"><span style="font-family:Verdana,Geneva,sans-serif;">Get the logic right.&nbsp; Our graders will NOT try to compile and run your code. But they will analyze it in their minds, and they will determine if your&nbsp;code would deliver the desired output.&nbsp;</span></span></li>
	<li><span style="font-size:18px;"><span style="font-family:Verdana,Geneva,sans-serif;">Most of all, have fun! We are looking for people who have a core passion to solve puzzles and to make the&nbsp;world better by applying their engineering talents.&nbsp; By evaluating the way a person writes code and communicates, it is easy to determine if the person truly enjoys his/her profession.&nbsp;</span></span></li>
</ol>

<p>&nbsp;</p>

<p><span style="font-size:18px;"><span style="font-family:Verdana,Geneva,sans-serif;">Write a program that does the following:</span></span></p>

<p>&nbsp;</p>

<p><span style="font-size:18px;"><span style="font-family:Verdana,Geneva,sans-serif;">Given a string variable: StrRates</span></span></p>

<p>&nbsp;</p>

<p><span style="font-size:18px;"><span style="font-family:Verdana,Geneva,sans-serif;">StrRates is a string with delimited list of numbers. This list can be of arbitrary length. The pattern of this list is:</span></span></p>

<p><span style="font-size:18px;"><span style="font-family:Verdana,Geneva,sans-serif;">Rate1 "," Price 1,1 "," ... Raten "," Price1,n ":L" LockPeriod1 ";" ... Rate2 "," Pricem,2 "," ... Raten "," Pricem,n ":L" LockPeriodm ";"</span></span></p>

<p>&nbsp;</p>

<p><span style="font-size:18px;"><span style="font-family:Verdana,Geneva,sans-serif;">The Objective of the Program is to transform this string into the following two-dimensional matrix and display it as an html page. So the output should look like this:</span></span></p>

<p>&nbsp;</p>

<p><span style="font-size:18px;"><span style="font-family:Verdana,Geneva,sans-serif;"><img data-embed="true" data-src="/uploads/354446/4a844d07-2a53-45e9-883f-d8a3157296aa.png" src="https://mettl.com/uploads/354446/4a844d07-2a53-45e9-883f-d8a3157296aa.png"></span></span></p>

<p>&nbsp;</p>

<p><span style="font-size:18px;"><span style="font-family:Verdana,Geneva,sans-serif;">Here is an example input value: "5.0,100,5.5,101,6.0,102:L10;5.0,99,5.5,100,6.0,101:L20;"</span></span></p>

<p><span style="font-size:18px;"><span style="font-family:Verdana,Geneva,sans-serif;">The result will be an HTML page with a table that looks something like this:</span></span></p>

<p>&nbsp;</p>

<p><span style="font-size:18px;"><span style="font-family:Verdana,Geneva,sans-serif;"><img data-embed="true" data-src="/uploads/354446/3e401097-e68f-43f6-9118-8558168edc0a.png" src="https://mettl.com/uploads/354446/3e401097-e68f-43f6-9118-8558168edc0a.png"></span></span></p>
</div></div></section>
var input = "";
process.stdin.on("data", function (chunk) {
    input += chunk;
});
process.stdin.on("end", function () {
    // now we can read/parse input
});





<section class="question-view__instruction"><div class="candidate-rich-text"><div id="1kqipdpf0bp-instruction"><p>Given are two tables (loan and borrower) as diagramed below:</p>

<p>&nbsp;</p>

<p><img data-embed="true" data-src="/uploads/354446/818c386b-85e2-4942-80d5-7a06064d2248.png" src="https://mettl.com/uploads/354446/818c386b-85e2-4942-80d5-7a06064d2248.png"></p>

<p>&nbsp;</p>

<p>Write an SQL query that will list all loans and the number of borrowers per loan.</p>

<p>&nbsp;</p>

<p><img data-embed="true" data-src="/uploads/354446/be363164-7d55-41bf-a947-1e73f71592e6.png" src="https://mettl.com/uploads/354446/be363164-7d55-41bf-a947-1e73f71592e6.png"></p>

<p>&nbsp;</p>

<p>Filter the above list and show only the loans that have more than one borrower.<br>
For example:</p>

<p>&nbsp;</p>

<p><img data-embed="true" data-src="/uploads/354446/1f735ae2-1b53-4ffe-9814-b51f6f3b7e6d.png" src="https://mettl.com/uploads/354446/1f735ae2-1b53-4ffe-9814-b51f6f3b7e6d.png"></p>

<p>&nbsp;</p>

<p><img data-embed="true" data-src="/uploads/354446/6ec091ee-412e-4535-b137-9eae6d49a730.png" src="https://mettl.com/uploads/354446/6ec091ee-412e-4535-b137-9eae6d49a730.png"></p>

<p>&nbsp;</p>

<p>A properly written SQL query will have the output of&nbsp;</p>

<p>&nbsp;</p>

<p><img data-embed="true" data-src="/uploads/354446/ec7a15c1-1c90-4700-a5d1-572dd026c6b6.png" src="https://mettl.com/uploads/354446/ec7a15c1-1c90-4700-a5d1-572dd026c6b6.png"></p>
</div></div></section>




<section class="question-view__instruction"><div class="candidate-rich-text"><div id="f9lftgr775-instruction"><p>What will the output of each printf be?</p>

<pre><code class="language-cpp">int f(void)
{
int *p=10; printf("%d",p);
printf("%d",*p);
printf("%d",&amp;p);
}</code></pre>

<p>&nbsp;</p>
</div></div></section>


<section class="question-view__instruction"><div class="candidate-rich-text"><div id="7qp1bhqhl29-instruction"><p>&nbsp;&nbsp;&nbsp;&nbsp;</p>

<p>What will the output of each printf be?</p>

<pre><code class="language-cpp">void f(void)
{
int * p = malloc(sizeof(int)); int x = *p;
int **y = &amp;p;

printf("%d\n",x);
*p=1000;
printf("%d\n",x);
printf("%d\n",*y);
}</code></pre>

<p>&nbsp;</p>
</div></div></section>


<section class="question-view__instruction"><div class="candidate-rich-text"><div id="ak4jsjon2fr-instruction"><pre><code class="language-cpp">#define TYPE_INT	1	
#define TYPE_DOUBLE	2	
#define TYPE_CHAR	3	
#define TYPE_STRING	4	// null terminated string


char *f(void * p, unsigned int uiOffset, unsigned int uiType)
{
}
</code></pre>

<p>The variable p is a pointer to some memory.</p>

<p>The variable uiOffset is the number of bytes from p where a value of type uiType is stored. The variable uiType stores the value of one of the four defines above.</p>

<p>&nbsp;</p>

<p>Write the above function. It needs to return a string buffer which is the ASCII representation of the value.</p>

<p>For example, if uiType was 1 and if the number 10 was stored in p then this function would return the string "10".</p>

<p>&nbsp;</p>
</div></div></section>





<section class="question-view__instruction"><div class="candidate-rich-text"><div id="ehfe2s6nhlb-instruction"><pre><code class="language-cpp">int f(void)
{
char c;
char *p = "ABC";

}</code></pre>

<p>Complete this function:</p>

<p>&nbsp;</p>

<p>Move the first four bits (i.e. most significant) and the last four bits (i.e. least significant) of the value of the pointer variable, P, into the first 4 bits and last 4 bits of the variable c. Assume Linux on an Intel 32 bit processor.</p>
</div></div></section>






<section class="question-view__instruction"><div class="candidate-rich-text"><div id="bfgm9lfja5t-instruction"><pre><code class="language-cpp">int i=10; int n;

n=write (so,"SENDING INTERGER", 16);
n=write (so,&amp;i, sizeof(i));</code></pre>

<p>Assume the variable SO is an integer which is a handle to a valid socket which is connected to another computer of unknown hardware configuration.</p>

<p>&nbsp;</p>

<p>3a.&nbsp; What is wrong with the following code. (hint: There is nothing wrong with the syntax. This question tests your conceptual understanding)?</p>

<p>3b.&nbsp; Suggest a better implementation.</p>
</div></div></section>