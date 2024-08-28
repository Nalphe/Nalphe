# Hello World 👋

I'm Joe, 

I've been learning the basics of programming for a few months, particulalry focusing on JS, but also exploring the basics of Python, Bash, SQL, React. I'm excited to keep learning and growing my understanding!

## My Journey so far

### FreeCodeCamp
   - Starting from scratch I learned the bascis of HTML, CSS and JS
   - From there I really started to grow in confidence making frontent projects, using JS, HTML and React
   - Learned about version management and the basics of using Git to branch and review changes to code
   - Proudest moment: Using JS to access an API and make a Pokemon Searcher App for certification in my JS project

Certificates:

[Responsive Web Design](https://www.freecodecamp.org/certification/nalphe/responsive-web-design)

[JS: Data Algorithims and Structures](https://www.freecodecamp.org/certification/nalphe/javascript-algorithms-and-data-structures-v8)

Some of my projects can be viewed here:
[![image with some of my projects, displayed are my javascript pokedex, react drum machcine and react calculator](https://github.com/user-attachments/assets/ced38bed-fe30-4650-a1e6-f6036f0afa4a)](https://codepen.io/Joseph-Phelan-the-solid/full/zYVLrmN)


### CodeSignal and CodeArcade
Building on my experience in FreeCodeCamp, I started to complete challenges on CodeArcade
![Image showing progress within categories of data structure outlined, arrays, lined lists, hash tables, trees (basic) heaps, stacks and queues!](https://raw.githubusercontent.com/Nalphe/Image-Hosting/main/data%20structures.png "My Progression through data alorithims and structures")

I've been working on completing the intervew training, which has really grown my knowledge of data structures. I've:
   - Learned how to make basic data structures, including Heaps, Tries, Stacks and linked lists.
   - Learned how to complete both in-order and pre-order traversal of trees

My proudest moments
   - Getting to grips with algorithtims to reverse linked lists
   - Understanding Morris In-Order-Tree Traversal

Here's a Trie I made!
`    

    class TrieNode {
         constructor() {
             this.child = {};
             this.wordEnd = false;
         }
     }
     
     class Trie {
         constructor() {
             this.root = new TrieNode();
         }
         
         insert(word) {
             let node = this.root
             for (let i = 0; i < word.length; i++) {
                 let x = word[i];
                 if (!node.child[x]) {
                    node.child[x] = new TrieNode();
                 }
                 node = node.child[x]
                 }
             node.wordEnd = true
         }
        
         search(word) {
             let node = this.root
             for (let i = 0; i < word.length; i++) {
                 let x = word[i]
                 if (!node.child[x]) {
                     return false 
                 }
                 node = node.child[x]
             }
         return node.wordEnd
         }
  `
