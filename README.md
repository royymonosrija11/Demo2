# for testing purpose
from feature1
#complexity of number to words is O(1)

1.class name: NumberToWordsConverter<br>
2.__init__: this constructor initializes two lists "one" and "tens"<br>
3.method num_to_word: converts a number which is less than 100 and appends suffix accordingly(crore,lakh,thousands,hundred) <br>
if n is greater than 19 it uses the list "tens" for the tens place and the list "one" for the units place.<br>
if n is less than 19 it directly uses "one" list.<br>
then it appends suffix s if n is not zero.<br>
4.method convert_to_words: it converts the whole number by breaking it down to crore,lakh,thousands,hundreds and reminder.<br>
we used integer division "//" here to get the integer part and not the remainder.<br>
after crore part we did %100 to get only the lakh part or thousands part and so on by discarding the next greater part.<br>
it uses num_to_word method for each part of the number.<br>
it adds "and" if the number is greater than 100 and not divisible by 100<br>
5.Sample input: 48920122<br>
Sample output : four crore eighty nine lakh twenty thousand one hundred and twenty two<br>

#complexity of fibonacci series using numpy is O(n)

1.class name: Fibonacci
2.__init__: this constructor initializes a list named series with n number of zeros.
3.method generate_series: if n>0 initialize first element with 0,if n>1 initialize second element with 1 then for i from 2 to n-1 initializes ith element as the sum of previous two elements.
then the method returns the list itself.
4.Sample input: 7
Sample output: 0 1 1 2 3 5 8


