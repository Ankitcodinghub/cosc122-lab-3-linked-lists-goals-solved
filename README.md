# cosc122-lab-3-linked-lists-goals-solved
**TO GET THIS SOLUTION VISIT:** [COSC122  Lab 3-Linked Lists Goals Solved](https://www.ankitcodinghub.com/product/cosc122-lab-3-linked-lists-goals-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;100070&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COSC122&nbsp; Lab 3-Linked Lists Goals Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
COSC122&nbsp; Lab 3

Linked Lists Goals

This lab will provide you with some practice with Linked Lists. In this lab you will: • implementstackandqueuedatastructuresusinglinkedlistsand

• workwithalinkedliststructureforcountingcharacters

Preparation

<ul>
<li>YoushouldbefamiliarwiththeLinkedListmaterialinChapter3ofthetextbookbeforeattempt- ing this lab (online link here).</li>
<li>We’llbeusingstacksandqueuesagain,somakesureyouarefamiliarwiththemfromtheprevious topic.
Implementing a Stack and a Queue

The provided linked_list_structures module contains two skeleton classes: Stack and Queue that use a linked list to implement the interfaces for working with a stack and a queue. However, they’re missing implementations for the most important methods: push, pop, peek, enqueue and dequeue!

Remember that a stack is ‘last-in–first-out’ (LIFO), and a Queue is ‘first-in–first-out’ (FIFO). The stack implementation should push and pop items from the head of the list; with the queue implemen- tation it works out easiest if items are enqueued at the tail and dequeued from the head of the list.

Your initial task is to:
</li>
</ul>
<ul>
<li>CompletethemissingimplementationsforboththeStackandQueueclassesinthelinked_list_structures module.
<ul>
<li>– &nbsp;TheStackandQueuemustbeimplementedasalinkedlistsofNodeobjectsandaNodeclass is defined at the start of the linked_list_structures module—check it out now.</li>
<li>– &nbsp;The doctests for the Stack and Queue class not only check that you are using linked lists, they give you some indication of how to use the linked lists.</li>
<li>– &nbsp;Theheadofthelinkedlistwilleffectivelybethetopofastackorthefrontofaqueue.</li>
<li>– &nbsp;Each Node holds an item and a pointer to the next Node object (which will be None if there
is nothing after it).
</li>
</ul>
</li>
<li>Implementthe__len__methodssothattheyreturnthenumberofnodesinthestack/queue.Re- member Python will interpret len(q) as q.__len__(), ie, so we don’t need to call q.__len__() directly when using our stacks/queues.
It is important to test the extreme cases such as deleting from a list of 1 item, adding to a list of 0 items etc. Most of these cases are included in the doc tests (but not all). When you have completed the Stack and Queue classes you can test them with the doctests (by running the file in Wing) and/or by manually experimenting with the classes, for example:
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
&gt;

</div>
<div class="column">
‘c’

Once you have implemented these, complete Linky stacks and queues questions in Lab Quiz 3.

</div>
</div>
<div class="layoutArea">
<div class="column">
&gt;&gt;&gt; from linked_list_structures import Stack &gt;&gt;&gt; s = Stack()

&gt;&gt;&gt; s.push(‘a’)

&gt;&gt;&gt; print(s)

</div>
<div class="column">
&gt;&gt;&gt; from linked_list_structures import Queue &gt;&gt;&gt; q = Queue()

&gt;&gt;&gt; q.enqueue(‘a’)

&gt;&gt;&gt; print(q)

</div>
</div>
<div class="layoutArea">
<div class="column">
Stack: head/top

<ul>
<li>&gt;&gt;&gt; &nbsp;s.pop() ‘a’</li>
<li>&gt;&gt;&gt; &nbsp;print(s)

Stack: head/top

&gt;&gt;&gt; s.push(‘b’)

&gt;&gt;&gt; print(s)

Stack: head/top

&gt;&gt;&gt; s.push(‘c’)

&gt;&gt;&gt; len(s) 23</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
s.peek() print(s)

</div>
</div>
<div class="layoutArea">
<div class="column">
-&gt;a-&gt;None

-&gt; None

-&gt;b-&gt;None

</div>
<div class="column">
Queue: head/front -&gt; a -&gt; None &gt;&gt;&gt; len(q)

1

&gt;&gt;&gt; q.enqueue(‘b’)

&gt;&gt;&gt; print(q)

Queue: head/front -&gt; a -&gt; b -&gt; None

&gt;&gt;&gt; q.enqueue(‘c’)

&gt;&gt;&gt; print(q)

Queue: head/front -&gt; a -&gt; b -&gt; c -&gt; None

<ul>
<li>&gt;&gt;&gt; &nbsp;len(q)</li>
<li>&gt;&gt;&gt; &nbsp;q.dequeue() ‘a’</li>
<li>&gt;&gt;&gt; &nbsp;print(q)

Queue: head/front -&gt; b -&gt; c -&gt; None</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
&gt;&gt;&gt;

‘c’

&gt;&gt;&gt;

Stack: head/top -&gt; c -&gt; b -&gt; None &gt;&gt;&gt; s.pop()

</div>
</div>
<div class="layoutArea">
<div class="column">
Now that you have working stack and queue data structures, you should make the enqueue method faster by adding a tail pointer, pointing to the end of the list.

• Openthemodulequeue2.py.

• Complete the queue class so that it uses both head and tail pointers. You should be able to copy most of your code over from your previous queue but you will need to re-write the enqueue and dequeue methods—we have supplied new doctests that will check your code deals with the head and tail pointers appropriately.

&gt; When you have this new version worksing, complete the Heads and Tails questions in Lab Quiz 3. Calculating Letter Frequencies

The next task is to read a text corpus (collection of text) and produce the statistics counting the number of times each character (or pair of characters) appeared in the text using a linked list.

To see applications of this type of analysis, check out Frequency Analysis on Wikipedia. 1 Frequency information can be used to help with predictive text on cellphones, email completion in your email client, etc. For example:

• Ifsomeonetypes’t’whatisthemostlikelynextcharacter?

• Whatisthemostlikelycharacterafter’ther’hasbeentyped?

FreqList overview

Each FreqNode in the list will store the following values:

1. anitem(suchasacharacterorpairofcharacters),and

2. afrequency—thenumberoftimestheitemhasbeenseeninthetext. 3. anext_nodepointerthatpointstothenextFreqNodeinthelist.

Important Notes:

1. Initiallythelinkedlistisempty(theheadpointstoNone).

2. We will start by doing frequencies for characters but will move on to calculating frequencies for pairs of characters, so your methods should not assume we are always using single characters.

1 http://en.wikipedia.org/wiki/Frequency_analysis 2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
FreqList

</div>
</div>
<div class="layoutArea">
<div class="column">
Instance Variables:

</div>
</div>
<div class="layoutArea">
<div class="column">
Instance Variables:

</div>
</div>
<div class="layoutArea">
<div class="column">
head:

</div>
</div>
<div class="layoutArea">
<div class="column">
head:

</div>
</div>
<div class="layoutArea">
<div class="column">
Methods

</div>
</div>
<div class="layoutArea">
<div class="column">
Methods

</div>
</div>
<div class="layoutArea">
<div class="column">
get_item_frequency

</div>
</div>
<div class="layoutArea">
<div class="column">
get_xy_for_plot

</div>
</div>
<div class="layoutArea">
<div class="column">
get_xy_for_plot

</div>
</div>
<div class="layoutArea">
<div class="column">
__repr__

</div>
</div>
<div class="layoutArea">
<div class="column">
__repr__

</div>
</div>
<div class="layoutArea">
<div class="column">
__len__

</div>
</div>
<div class="layoutArea">
<div class="column">
__len__

</div>
</div>
<div class="layoutArea">
<div class="column">
FreqNode FreqNode

</div>
</div>
<div class="layoutArea">
<div class="column">
item: ‘h’

</div>
</div>
<div class="layoutArea">
<div class="column">
item: ‘h’

</div>
</div>
<div class="layoutArea">
<div class="column">
frequency: 1

</div>
</div>
<div class="layoutArea">
<div class="column">
frequency: 1

</div>
</div>
<div class="layoutArea">
<div class="column">
__init__

</div>
</div>
<div class="layoutArea">
<div class="column">
__init__

</div>
</div>
<div class="layoutArea">
<div class="column">
add

</div>
</div>
<div class="layoutArea">
<div class="column">
add

</div>
</div>
<div class="layoutArea">
<div class="column">
get_item_frequency

</div>
</div>
<div class="layoutArea">
<div class="column">
next_node:

</div>
</div>
<div class="layoutArea">
<div class="column">
next_node:

</div>
</div>
<div class="layoutArea">
<div class="column">
item: ‘t’

</div>
</div>
<div class="layoutArea">
<div class="column">
item: ‘t’

</div>
</div>
<div class="layoutArea">
<div class="column">
frequency: 1

</div>
</div>
<div class="layoutArea">
<div class="column">
frequency: 1

</div>
</div>
<div class="layoutArea">
<div class="column">
next_node:

</div>
</div>
<div class="layoutArea">
<div class="column">
next_node:

</div>
</div>
<div class="layoutArea">
<div class="column">
None

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Program output

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 1: Simple object model overview

</div>
</div>
<div class="layoutArea">
<div class="column">
The output from your program should look like the following (for letter pairs):

1: ‘t’=12345 2: ‘e’=12222 3: ‘th’ = 12013 4: ‘he’ = 11987 … etc

<ul>
<li>Thefirstnumberineachlineistheindexnumberoftheletter(orgroupofletters).</li>
<li>Thelastnumberisthefrequency(forexamplethefirstlinehasanindexon1,andshowsthatthe
letterpair’t ’hasafrequencyof12345).
</li>
<li>Theindexnumbershowsyoutheorderinwhichtheitemsarestoredinthelinkedlist.</li>
<li>The index number also shows the frequency rank in the case of the sorted frequency list. The example output is taken from a sorted frequency list and therefore the most frequent pair was ‘t ‘ and the second most frequent was ‘ e’.</li>
<li>NodistinctionshouldbemadebetweenUPPERCASEandlowercaseletters.
Counting the frequencies—overview

The letter_frequencies module provides some skeleton code. For each item in the text, your program should:

• checkwhetheritalreadyexistsinthelist.

– Ifso,incrementitsfrequencycountby1.

– Ifnotthenaddanodetothelinkedlist(initiallyaddatthestartofthelistasthiswillbethe quickest way to add the node) for that item and set its frequency count to 1.

Three sample text files are given in le_rire.txt, ulysses.txt, and war_and_peace.txt – listed from smallest to largest file-size. Tolstoy’s War and Peace is one of the longest novels ever written, weigh- ing in at around half a million words, but it is less than half the size of Proust’s In Search of Lost Time, which has around 1.2 million words 2.

2It’s too bad that In Search of Lost Time is not available on project Gutenberg. 3
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Single Character Frequencies

You are required to:

<ul>
<li>CompletetheaddmethodintheUnsortedFreqListclassintheletter_frequenciesmodule.</li>
<li>Run it on all the sample text files to provide the counts for each letter in each corpus (eg, to run onle_rire.txtyoushoulduncommentrun_tests(“le_rire.txt”, verbose=True)inthemainfunc- tion and, if needed, un-comment the line in the run_tests function that adds the UnsortedFreqList test for single characters to the list of tests to run, ie, the run_settings.append((UnsortedFreqList, 1, verbose))).
We recommend testing your programs fully with le_rire.txt before you move on to the longer files. You can ignore the doctest errors for other functions at this stage. Your output from a single character run, with UnsortedFreqList, should give you something like the left column of the following table.
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
&gt;

</div>
<div class="column">
<ul>
<li>ImplementtheaddmethodintheNicerUnsortedFreqListclass.Thisclassshouldaddnewitemsto the end of the list rather than the beginning. Adding an item to the end of the list will take longer than adding to the start of the list but, as the name suggests, this works better overall. See the right column of the above output.</li>
<li>Comparethespeedofthisnicermethodtothespeedoftheoriginalmethod.</li>
<li>Thinkabouthowmanytimesnewletterswillbeaddedtothefrequencylistinthecourseofpro- cessing a document and the position of characters such as ‘t’, ‘h’ and ‘e’ in the frequency list. Explain why inserting new letters at the end of the list vs. the beginning is likely to speed up corpus processing.
After implementing the new add method, complete the Simple character frequencies questions in Lab Quiz 3.
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
————————————————– Tests for: le_rire.txt

Doc size: 246941 chars ————————————————– 1 char(s) -&gt; t = 0.8862s (40 items)

Unsorted Frequency List ———————————–

1: ‘@’=2 2: ‘%’=1 3: ‘/’ = 26 4: ‘!’ = 43 5: ‘”‘=262 6: ‘;’ = 159 7: ‘?’ = 89 8: ‘q’=194 9: ‘x’=387 10: ‘z’ = 24

11: ”’ = 112 12: ‘*’ = 28 13: ‘#’ = 1

14: ‘.’ = 1851 15: ‘v’ = 1897 16: ‘d’ = 6114 17: ‘w’ = 3824 18: ‘,’ = 3178 19: ‘i’ = 15917 20: ‘m’ = 5441 21: ‘y’ = 3461 22: ‘s’ = 13342 23: ‘:’ = 181 24: ‘a’ = 15336 25: ‘l’ = 7836 26: ‘f’ = 4953 27: ‘k’ = 1001 28: ‘b’ = 2846 29: ‘n’ = 13878 30: ‘u’ = 5545 31: ‘g’ = 4055 32: ‘c’ = 6811 33: ‘j’ = 294 34: ‘o’ = 15142 35: ‘r’ = 11188 36: ‘p’ = 3679 37:”=42837 38: ‘e’ = 24941 39: ‘h’ = 10597 40: ‘t’ = 19468

Your next challenge is now to:

</div>
<div class="column">
————————————————– Tests for: le_rire.txt

Doc size: 246941 chars ————————————————– 1 char(s) -&gt; t = 0.4403s (40 items)

Nicer Unsorted Frequency List ———————————–

1: ‘t’ = 19468 2: ‘h’ = 10597 3: ‘e’ = 24941 4: ”=42837 5: ‘p’=3679 6: ‘r’ = 11188 7: ‘o’ = 15142 8: ‘j’=294 9: ‘c’=6811

10: ‘g’ = 4055

11: ‘u’ = 5545

12: ‘n’ = 13878

13: ‘b’ = 2846

14: ‘k’ = 1001

15: ‘f’ = 4953

16: ‘l’ = 7836

17: ‘a’ = 15336 | 18: ‘:’ = 181

19: ‘s’ = 13342 20: ‘y’ = 3461 21: ‘m’ = 5441 22: ‘i’ = 15917 23: ‘,’ = 3178 24: ‘w’ = 3824 25: ‘d’ = 6114 26: ‘v’ = 1897 27: ‘.’ = 1851 28:’#’=1 29:’*’=28 30: ”’ = 112 31:’z’=24 32: ‘x’ = 387 33: ‘q’ = 194 34:’?’=89 35: ‘;’ = 159 36: ‘”‘ = 262 37:’!’=43 38:’/’=26 39:’%’=1 40:’@’=2

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
Character Pair Frequencies

Now that you have your code running for single characters, do the following:

<ul>
<li>Runitforcharacterpairs
<ul>
<li>– &nbsp;forexamplebyun-commentingrun_settings.append((UnsortedFreqList, 2, verbose))</li>
<li>– &nbsp;ThereshouldbeamorenoticeablegapbetweentheUnsortedFreqListandtheNicerUnSortedFreqList
.
</li>
</ul>
</li>
<li>Complete the SortedFreqList to calculate the letter frequencies and store the nodes from highest frequency count to lowest.
<ul>
<li>– &nbsp;Thisisusuallyfasterbecausethemajorityofcharactersbeingincrementedwillbenearthe front of the list. To keep the list in order you will need to move nodes to their sorted position when needed.</li>
<li>– &nbsp;Ifanodehasitscountincrementedanditscountisnowgreaterthanthenodebeforeitthen the node needs to be moved. It will obviously need to be before the previous node but it may need to go further as their may be many nodes with the same frequency as the previous node.</li>
<li>– &nbsp;The way we recommend moving an updated node to its correct position by ’unlinking the node from the list, keeping a pointer to it. Then inserting it back into the list in the correct position.</li>
<li>– &nbsp;IMPORTANTNOTE:wesupplythe_insert_in_ordermethodthatwillhelpwiththisapproach. Please read the comments in the add and _insert_in_order methods so you understand how

and when to use the _insert_in_order, for example, you will never need to use _insert_in_order

on an empty list as a node can’t have higher frequency than its previous node if the list is empty.
</li>
</ul>
</li>
<li>Compare the timings of your SortedFreqList, UnsortedFreqList and NicerUnsortedFreqList imple- mentations.
– WhyisSortedFreqListonlyslightlyfasterthantheNicerUnsortedFreqList?
</li>
</ul>
&gt; After implementing this, complete the Sorted Frequencies questions in web quiz 3.

Extras

<ul>
<li>To get a graphical representation of the frequencies use the plot_freq_list function provided in the source file. Only plot one graph per run – python will give you grief if you try more. We recom- mend only graphing the single character frequencies as the graph for character pairs will have far too many x-axis items! If you get a crash when running graphs you may need to restart the python shell in Wing, to do this simply click on the options button in the shell window and select restart shell…</li>
<li>ImplementaFrequencyDictionarythatstoresfrequenciesinaPythondictionaryandseehowwell it stacks up versus the SortedFreqList. The timings should show why this the way most people would build the frequency values in the real-world.</li>
<li>Write a function such as make_sorted_words_freq_list to calculate the frequencies of words in the documents. For simplicity assume a word is any set of characters between spaces, eg, in ‘Wiggle and Woggle are two, very strange, dances.’ we would consider ‘two,’ and ‘strange,’ to be words, along with the more obvious words such as Wiggle and are. Basically using .split() will return the list of words that you want. But you may be able to process the files quicker if you scan through, character by character, building words and adding to the freq_list as you go—this saves building a huge list of words before you start processing.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
• Another approach to implementing the SortedFreqList is to use a doubly linked list and move back through the list until the appropriate spot is found and insert the node there—this should be slightly quicker when moving nodes as it won’t have to go all the way back to the start of the list each time. But, you will need to rewrite your nodes to have two links and make sure that both links are updated properly when operating on lists of them. Making a version that uses this approach is a good exercise for more motivated students. Take a copy of your code and change your implementation to use a doubly linked list. Note: don’t submit this code to the quiz question – use the singly linked list implementation (the quiz server will provide the Node class as given in the original lab code…).

</div>
</div>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</div>
