# cz1007-assignment-5---character-strings-solved
**TO GET THIS SOLUTION VISIT:** [CZ1007 ASSIGNMENT 5 – CHARACTER STRINGS Solved](https://www.ankitcodinghub.com/product/cz1007-week-5-assignment-character-strings-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;114286&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CZ1007  ASSIGNMENT 5 – CHARACTER STRINGS Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Assignment on Coding Questions

For this assignment – you will need to answer 4 questions (randomly generated via APAS) from the following question list:

1. insertChar

2. locateFirstChar

3. longWordLength

4. countWords

5. cipherText

6. findMinMaxStr

7. maxCharToFront

8. longestStrInAr

9. strIntersect

10. findSubstring

11. countSubstring

Questions

1. (insertChar) Write the C function that takes in a string str1 as an argument, copies the contents of character string str1 into character string str2. In addition, the function also has a character parameter ch. For every three characters copied from str1 to str2, the character ch is inserted into str2. The function returns the resultant string to the calling function via call by reference. For example, if the string str1 is “abcdefg”, and the inserted character ch is ‘#’, then the resultant string str2 = “abc#def#g” will be returned to the calling function. The function prototype is given as follows:

void insertChar(char *str1, char *str2, char ch);

A sample program template is given below to test the function:

#include &lt;stdio.h&gt; #include &lt;string.h&gt;

void insertChar(char *str1, char *str2, char ch); int main()

{

char a[80],b[80]; char ch, *p;

printf(“Enter a string: “); fgets(a, 80, stdin); if (p=strchr(a,’ ‘)) *p = ”;

printf(“Enter a character to be inserted: “); ch = getchar(); insertChar(a,b,ch); printf(“insertChar(): “); puts(b); return 0;

}

void insertChar(char *str1, char *str2, char ch)

{

/* Write your code here */

}

Some sample input and output sessions are given below:

(1) Test Case 1:

Enter a string:

abc de

Enter a character to be inserted:

#

insertChar(): abc# de#

(2) Test Case 2:

Enter a string: abc

Enter a character to be inserted:

#

insertChar(): abc#

(3) Test Case 3:

Enter a string:

I am a boy.

Enter a character to be inserted:

$ insertChar(): I a$m a$ bo$y.

(4) Test Case 4:

Enter a string: hi

Enter a character to be inserted:

$ insertChar(): hi

2. (locateFirstChar) Write a C function that locates the first occurrence of ch in the string str. The function returns the index, or -1 if ch does not occur in the string. The function prototype is given as follows:

int locateFirstChar(char *str, char ch);

A sample program template is given below to test the function:

#include &lt;stdio.h&gt; #include &lt;string.h&gt;

int locateFirstChar(char *str, char ch); int main() {

char str[40], ch, *p;

printf(“Enter a string: “); fgets(str, 80, stdin); if (p=strchr(str,’ ‘)) *p = ”; printf(“Enter the target character: “); scanf(“%c”, &amp;ch);

printf(“locateFirstChar(): %d “, locateFirstChar(str, ch)); return 0; }

int locateFirstChar(char *str, char ch)

{

/* Write your code here */

}

Some sample input and output sessions are given below:

(1) Test Case 1

Enter a string: I am a boy Enter the target character: a

locateFirstChar(): 2

(2) Test Case 2

Enter a string:

I am a boy

Enter the target character: z

locateFirstChar(): -1

3. (longWordLength) Write a C function that accepts an English sentence as parameter, and returns the length of the longest word in the sentence. For example, if the sentence is “I am happy.”, then the length of the longest word “happy” in the sentence 5 will be returned. Assume that each word is a sequence of English letters. The function prototype is given as follows:

int longWordLength(char *s);

A sample program template is given below to test the function:

#include &lt;stdio.h&gt; #include &lt;string.h&gt; int longWordLength(char *s); int main() {

char str[80], *p;

printf(“Enter a string: “); fgets(str, 80, stdin); if (p=strchr(str,’ ‘)) *p = ”;

printf(“longWordLength(): %d “, longWordLength(str)); return 0; }

int longWordLength(char *s)

{

/* Write your code here */

}

Some test input and output sessions are given below:

(1) Test Case 1:

Enter a string:

I am happy. longWordLength(): 5

(2) Test Case 2:

Enter a string:

There are forty students in the class.

longWordLength(): 8

(3) Test Case 3:

Enter a string:

Good day!

longWordLength(): 4

(4) Test Case 4:

Enter a string: Hello longWordLength(): 5

4. (countWords) Write a function that accepts a string s as its parameter. The string contains a sequence of words separated by spaces. The function then displays the number of words in the string. The function prototype is given as follows:

int countWords(char *s);

A sample program template is given below to test the function:

#include &lt;stdio.h&gt; #include &lt;string.h&gt; int countWords(char *s); int main() {

char str[50], *p;

printf(“Enter the string: “); fgets(str, 80, stdin); if (p=strchr(str,’ ‘)) *p = ”; printf(“countWords(): %d”, countWords(str)); return 0; }

int countWords(char *s)

{

/* Write your code here */

}

A sample input and output session is given below:

(1) Test Case 1:

Enter the string:

How are you? countWords(): 3

(2) Test Case 2:

Enter the string: There are 12 dollars.

countWords(): 4

(3) Test Case 3:

Enter the string: Oneword countWords(): 1

5. (cipherText) Cipher text is a popular encryption technique. What we do in cipher text is that we can encrypt each apha (‘a’ .. ‘z’, ‘A’ .. ‘Z’) character with +1. For example, “Hello” can be encrypted with +1 cipher to “Ifmmp”. If a character is ‘z’ or ‘Z’, the corresponding encrypted character will be ‘a’ or ‘A’ respectively. For other characters, no encryption is performed. We use call by reference in the implementation. Write the C functions cipher() and decipher() with the following function prototypes:

void cipher(char *s); void decipher(char *s);

A sample program template is given below to test the functions:

#include &lt;stdio.h&gt;

#include &lt;string.h&gt; #include &lt;ctype.h&gt; void cipher(char *s); void decipher(char *s); int main() {

char str[80], dummychar, *p; int choice;

printf(“Select one of the following options: “); printf(“1: cipher() “); printf(“2: decipher() “); printf(“3: exit() “);

do {

printf(“Enter your choice: “); scanf(“%d”, &amp;choice); switch (choice) { case 1: scanf(“%c”,&amp;dummychar); printf(“Enter the string: “); fgets(str, 80, stdin); if (p=strchr(str,’ ‘)) *p = ”; printf(“To cipher: %s -&gt; “, str); cipher(str); printf(“%s “, str); break; case 2: scanf(“%c”,&amp;dummychar); printf(“Enter the string: “); fgets(str, 80, stdin); if (p=strchr(str,’ ‘)) *p = ”; printf(“To decipher: %s -&gt; “, str); decipher(str); printf(“%s “, str); break; default: break;

}

} while (choice &lt; 3); return 0; } void cipher(char *s)

{

/* Write your program code here */

}

void decipher(char *s)

{

/* Write your program code here */

}

Some sample input and output sessions are given below:

(1) Test Case 1:

Select one of the following options:

1: cipher()

2: decipher()

3: exit()

Enter your choice:

1

Enter the string:

123a

To cipher: 123a -&gt; 123b Enter your choice:

3

(2) Test Case 2:

Select one of the following options:

1: cipher()

2: decipher()

3: exit()

Enter your choice:

2

Enter the string:

123b

To decipher: 123b -&gt; 123a Enter your choice:

3

(3) Test Case 3:

Select one of the following options:

1: cipher()

2: decipher()

3: exit()

Enter your choice:

1

Enter the string: abcxyz

To cipher: abcxyz -&gt; bcdyza Enter your choice:

2

Enter the string: bcdyza

To decipher: bcdyza -&gt; abcxyz Enter your choice:

3

(4) Test Case 4:

Select one of the following options:

1: cipher()

2: decipher()

3: exit()

Enter your choice:

1

Enter the string:

HELLO Hello

To cipher: HELLO Hello -&gt; IFMMP Ifmmp Enter your choice:

2

Enter the string:

IFMMP Ifmmp

To decipher: IFMMP Ifmmp -&gt; HELLO Hello Enter your choice:

3

6. (longestStrInAr) Write a C function that takes in an array of strings str and size (&gt;0) as paramters, and returns the longest string and also the length of the longest string via the pointer parameter length. If two or more strings have the same longest string length, then the first appeared string will be retruned to the calling function. For example, if size is 5 and the array of strings is {“peter”, “john”, “mary”, “jane”, “kenny”}, then the longest string is “peter” and the string length is 5 will be returned to the calling function. The function prototype is:

char *longestStrInAr(char str[N][40], int size, int *length);

A sample program template is given below to test the function:

#include &lt;stdio.h&gt;

#include &lt;string.h&gt; #define N 20

char *longestStrInAr(char str[N][40], int size, int *length); int main() {

int i, size, length;

char str[N][40], first[40], last[40], *p, *result;

char dummychar;

printf(“Enter array size: “); scanf(“%d”, &amp;size); scanf(“%c”, &amp;dummychar); for (i=0; i&lt;size; i++) { printf(“Enter string %d: “, i+1); fgets(str[i], 40, stdin);

if (p=strchr(str[i],’ ‘)) *p = ”;

}

result = longestStrInAr(str, size, &amp;length);

printf(“longest: %s length: %d “, result, length); return 0; }

char *longestStrInAr(char str[N][40], int size, int *length)

{

/* Write your code here */

}

Some sample input and output sessions are given below:

(1) Test Case 1:

Enter array size: 4

Enter string 1:

Kenny

Enter string 2:

Mary

Enter string 3:

Peter

Enter string 4: Sun longest: Kenny length: 5

(2) Test Case 2:

Enter array size:

2

Enter string 1:

Sun

Enter string 2: Mary longest: Mary length: 4

7. (findMinMaxStr) Write a C function that reads in words separated by space, finds the first and last words according to ascending alphabetical order (based on ASCII values), and returns them to the calling function through the string parameters first and last. The calling function will then print the first and last strings on the screen. The function prototype is given as follows:

void findMinMaxStr(char word[][40], char *first, char *last, int size);

A sample program template is given below to test the function:

#include &lt;stdio.h&gt;

#include &lt;string.h&gt; #define SIZE 10

void findMinMaxStr(char word[][40], char *first, char *last, int size); int main() {

char word[SIZE][40];

char first[40], last[40]; int i, size;

printf(“Enter size: “); scanf(“%d”, &amp;size);

printf(“Enter %d words: “, size); for (i=0; i&lt;size; i++) scanf(“%s”, word[i]);

findMinMaxStr(word, first, last, size);

printf(“First word = %s, Last word = %s “, first, last); return 0; }

void findMinMaxStr(char word[][40], char *first, char *last, int size)

{

/* Write your program code here */

}

Some sample input and output sessions are given below:

(1) Test Case 1:

Enter size: 4

Enter 4 words:

Peter Paul John Mary

First word = John, Last word = Peter

(2) Test Case 2:

Enter size:

1

Enter 1 words:

Peter

First word = Peter, Last word = Peter

(3) Test Case 3:

Enter size:

2

Enter 2 words:

Peter Mary

First word = Mary, Last word = Peter

8. (maxCharToFront) Write a C function that accepts a character string str as parameter, finds the largest character from the string, and moves it to the beginning of the string. E.g., if the string is “adecb”, then the string will be “eadcb” after executing the function. The string will be passed to the caller via call by reference. If more than one largest character is in the string, then the first appearance of the largest character will be moved to the beginning of the string. For example, if the string is “adecbe”, then the resultant string will be “eadcbe”. The function prototype is given as follows:

void maxCharToFront(char *str);

A sample program template is given below to test the function:

#include &lt;stdio.h&gt; #include &lt;string.h&gt; void maxCharToFront(char *str); int main() {

char str[80], *p;

printf(“Enter a string: “); fgets(str, 80, stdin); if (p=strchr(str,’ ‘)) *p = ”; printf(“maxCharToFront(): “); maxCharToFront(str); puts(str); return 0; }

void maxCharToFront(char *str)

{

/* Write your code here */

}

Some test input and output sessions are given below:

(1) Test Case 1:

Enter a string: adebc

maxCharToFront(): eadbc

(2) Test Case 2:

Enter a string: agfcdeg

maxCharToFront(): gafcdeg

(3) Test Case 3:

Enter a string: cba

maxCharToFront(): cba

(4) Test Case 4:

Enter a string: ab

maxCharToFront(): ba

void strIntersect(char *str1, char *str2, char *str3);

A sample program template is given below to test the function:

#include &lt;stdio.h&gt;

void strIntersect(char *str1, char *str2, char *str3); int main() {

char str1[50],str2[50],str3[50];

printf(“Enter str1: “); scanf(“%s”,str1); printf(“Enter str2: “); scanf(“%s”,str2); strIntersect(str1, str2, str3); if (*str3 == ”)

printf(“strIntersect(): null string “); else

printf(“strIntersect(): %s “, str3); return 0; }

void strIntersect(char *str1, char *str2, char *str3)

{

/* Write your code here */

}

Some sample input and output sessions are given below:

(1) Test Case 1:

Enter str1:

abcde Enter str2: dec

strIntersect(): cde

(2) Test Case 2:

Enter str1: abcdefghijk Enter str2:

akdhf

strIntersect(): adfhk

(3) Test Case 3:

Enter str1:

abc Enter str2: def

strIntersect(): null string

10. (findSubstring) Write a C function that takes two character string arguments, str and substr as input and returns 1 if substr is a substring of str (i.e. if substr is contained in str) and 0 if not. For example, the function will return 1 if substr is “123” and str is “abc123xyz”, but it will return 0 if otherwise. Note that for this question you are not allowed to use any string functions from the standard C library. The prototype of the function is given below:

int findSubstring(char *str, char *substr);

A sample program template is given below to test the function:

#include &lt;stdio.h&gt;

#include &lt;string.h&gt; #define INIT_VALUE 999

int findSubstring(char *str, char *substr); int main() {

char str[40], substr[40], *p; int result = INIT_VALUE;

printf(“Enter the string: “); fgets(str, 80, stdin); if (p=strchr(str,’ ‘)) *p = ”; printf(“Enter the substring: “); fgets(substr, 80, stdin); if (p=strchr(substr,’ ‘)) *p = ”; result = findSubstring(str, substr); if (result == 1)

printf(“findSubstring(): Is a substring “);

else if ( result == 0)

printf(“findSubstring(): Not a substring “); else

printf(“findSubstring(): An error “); return 0; }

int findSubstring(char *str, char *substr) {

/* Write your code here */

}

Some test input and output sessions are given below:

(1) Test Case 1:

Enter the string:

abcde fgh

Enter the substring: abc

findSubstring(): Is a substring

(2) Test Case 2:

Enter the string:

abcdefgh

Enter the substring: bc

findSubstring(): Is a substring

(3) Test Case 3:

Enter the string:

abcde f

Enter the substring: cdef

findSubstring(): Not a substring

(4) Test Case 4:

Enter the string:

abcdef

Enter the substring: xy

findSubstring(): Not a substring

int countSubstring(char str[], char substr[]);

A sample program template is given below to test the function:

#include &lt;stdio.h&gt;

#include &lt;string.h&gt; #define INIT_VALUE -1

int countSubstring(char str[], char substr[]); int main() {

char str[80], substr[80], *p; int result=INIT_VALUE;

printf(“Enter the string: “); fgets(str, 80, stdin); if (p=strchr(str,’ ‘)) *p = ”; printf(“Enter the substring: “); fgets(substr, 80, stdin); if (p=strchr(substr,’ ‘)) *p = ”; result = countSubstring(str, substr); printf(“countSubstring(): %d “, result); return 0;

}

int countSubstring(char str[], char substr[])

{

/* Write your program code here */

}

Some test input and output sessions are given below:

(1) Test Case 1:

Enter the string:

abcdef Enter the substring: dd

countSubstring(): 0

(2) Test Case 2:

Enter the string: abcabcabc cbaf Enter the substring: abc countSubstring(): 3

(3) Test Case 3:

Enter the string:

babababaabf Enter the substring: ab

countSubstring(): 4
