# leetcode<br>
　　This is my first time of challenging leetcode, of course it's a hard time for me. Such as this problem, I have undergone these period of times.<br>
1.<br>　
First, I used C language to solve it, but I failed when I meet negative numbers cause the array index has no negative number. So then I turned to learn STL. Fortunately, I learned C++ in this term, so it spent a little time to handle the map container. Thirdly, I use map container to solve this problem, but you know, map container has no repeated elements, so I search another way to solve it. And then I see the unordered_map container, but my codeblocks doesn't support it. Luckily, it's easy to solve by Google. At last, I spent a lot of time to solve the extream case and I overcome it. Finally!!!!!!!<br>
　　The thread of this problem is hash. It uses index skillfully. But at the last period, I meet this problem. When the nums is [3,3] and the target is 6, my function return [1,1] at that time, so it useful to add a condition of "m[t]!=i" in "if()".<br>
I don't want to give unnecessary details cause it has a lot on the website. So I write these sentences to mark this first time.<br>
　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　2017.6.3<br>
2.<br>
The second problem gives me a tip, if you can list the condition in a parallel way, you won't write them with a nesting way. I don't know what's wrong if I write the conditions with nesting, but only if I list them in one "if()", the program adopted. Why???<br>
3.<br>
What I did was complying with the question, step by step and slove it.<br>
4.<br>
I list two solutions, cause my solution was too bad. The simple one may think about a little time.<br>
　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　2017.6.4<br>
5.<br>
This one I gave three solutions. The first is my original version, it still sucks. The second one came from the third one, I imitated the third one to change imporve my original version. The "i++" from the third one in the "if()" is so good, it means if the last one has been planted, you can not consider the next one, so you can skip it.<br>

6.<br>
This one used O(n) time and O(1) space. If Hash, it will be O(n) space and O(1) time.
　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　2017.6.5<br>
7.<br>
This one took me a long time. What my fault is I put "record=0" to else statement. That is a logical error, if there has a longer consecutive one than you choose now, you can't set the "record" to zero. So the next consecutive one will add one at the basic of the last one you don't set to zero.<br>
