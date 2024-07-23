# for testing purpose
from feature1
#complexity of number to words is O(1)

1.class name: NumberToWordsConverter
2.__init__: this constructor initializes two lists "one" and "tens"
3.method num_to_word: converts a number which is less than 100 and appends suffix accordingly(crore,lakh,thousands,hundred) 
if n is greater than 19 it uses the list "tens" for the tens place and the list "one" for the units place.
if n is less than 19 it directly uses "one" list.
then it appends suffix s if n is not zero.
4.method convert_to_words: it converts the whole number by breaking it down to crore,lakh,thousands,hundreds and reminder.
we used integer division "//" here to get the integer part and not the remainder.
after crore part we did %100 to get only the lakh part or thousands part and so on by discarding the next greater part.
it uses num_to_word method for each part of the number.
it adds "and" if the number is greater than 100 and not divisible by 100
5.Sample input: 48920122
Sample output : four crore eighty nine lakh twenty thousand one hundred and twenty two

#complexity of fibonacci series using numpy is O(n)


