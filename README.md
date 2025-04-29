# csc1302-lab-14--arraylist-practice-solved
**TO GET THIS SOLUTION VISIT:** [CSC1302 Lab 14- ArrayList Practice Solved](https://www.ankitcodinghub.com/product/csc-1302-principles-of-computer-science-ii-solved-39/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;114056&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSC1302 Lab 14- ArrayList Practice Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Purpose:

The ArrayList class is the part of Java Collection Framework. This class implements the List interface provided by the Collection framework. Here are features or key points about the

ArrayList in Java:

1. The ArrayList grow and sink dynamically when we add/remove elements from it.

2. ArrayList use the array as an internal data structure to store element.

3. This provides flexibility to use elements using the indexes.

4. ArrayList allows to store duplicate values including “null” values.

5. It is an ordered collection i.e. it maintains the insertion order.

6. Java ArrayList supports Generics.

7. It only allows objects in the ArrayList. For primitives values like int, long etc. use the wrapper classes.

8. Java ArrayList Iterator and ListIterator implementation is fail-fast.

9. ArrayList is not thread safe. We need to apply synchronization if multiple threads will change

ArrayList at the same time.

Task:

Write a program called ArrayList_Practice. In this program, please do the following operations.

1. Complete a method called RedundantCharacterMatch(ArrayList&lt;Character&gt; YourFirstName): the parameter of this method is an ArrayList&lt;Character&gt; whose elements are the characters in your first name (they should be in the order appear in your first name, e.g., if your first name is bob, then the ArrayList&lt;Char&gt; includes ‘b’, ‘o’, ‘b’.). The method will check whether there exists duplicate characters in your name and return the index of those duplicate characters. For example, when using bob as first name, it will return b: 0, 2.

2. Create an ArrayList&lt;Character&gt; NameExample. All the characters of your first name will appear twice in this ArrayList. For example, if your first name is bob, then NameExample will include the following element {b,o,b,b,o,b}. Then, please use NameExample as parameter for the method RedundantCharacterMatch(). If your first name is bob, the results that print in the console will be

b: 0, 2, 3, 5 o: 1, 4

Criteria:

1. Upload all of the .java and the .class files to the CSc1302 dropbox on http:// icollege.gsu.edu.

3. Please comment the important lines in the .java file as shown in the template. The important lines including but not limited to i) variables, ii) for-loop, iii) while-loop, iv) if-else statement, iv) methods. Please use your own words to describe what is your purpose to write this line. A .java file without comment will be graded under a 40% penalty.

4. Make sure that both the .java and .class files are named and uploaded to icollege correctly. If any special package is used in the program, be sure to upload the package too. Should you use any other subdirectory (whatsoever) your program would not be graded, and you will receive a 0 (zero).

5. No copying allowed. If it is found that students copy from each other, all of these programs will get 0.

Considering the difficulty of this lab, the code is listed below; when you cannot come up with a solution, please try to understand the code below and write comments.

package labs;

import java.util.ArrayList; import java.util.Arrays;

public class Lab15 { public static void main(String[] args){

ArrayList&lt;Character&gt; name = new ArrayList&lt;Character&gt;(); name.add(‘b’); name.add(‘o’); name.add(‘b’);

ArrayList&lt;Character&gt; name1 = new ArrayList&lt;Character&gt;(); name1.add(‘b’); name1.add(‘o’); name1.add(‘b’); name1.add(‘b’); name1.add(‘o’); name1.add(‘b’); String a = “b”;

RCM(name1);

}

public static void RCM(ArrayList&lt;Character&gt; name){ ArrayList&lt;String[]&gt; Temp = new ArrayList&lt;String[]&gt;(); for(int i = 0; i&lt;name.size();i++){ int judge = CheckNumber(Temp, name.get(i)); if(judge== -1){

String[] newString = new String[2]; newString[0] = name.get(i) +””; newString[1] = i +””; Temp.add(newString);

}

else{

String[] tempString = Temp.get(judge); tempString[1] = tempString[1] + i;

Temp.set(judge, tempString);

}

}

for(String[] x : Temp)

System.out.println(Arrays.toString(x)); }

public static int CheckNumber(ArrayList&lt;String[]&gt; Temp, char a){ for(String[]x:Temp){ if(x[0].matches(a +””)){ return Temp.indexOf(x);

}

}

return -1;

}

}
