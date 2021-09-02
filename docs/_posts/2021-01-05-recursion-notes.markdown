---
layout: post
title:  "Recursion notes"
date:   2021-01-05 01:00:38 +0530
categories: jekyll update
---
<link rel="stylesheet" href="/css/table.css">
<link rel="stylesheet" href="/css/image.css">
---
<div id="toc_container">
<p class="toc_title">Contents</p>
<ul class="toc_list">
  <li><a href="#goal_of_this_blog">0: Goal of this Blog</a></li>
  <li><a href="#introduction">1: Basic Concepts</a></li>
  <ul>
    <li><a href="#what_is_recursion">1.1 What is Recursion?</a></li>
    <li><a href="#recursion_traversal">1.2 Recursion Traversals</a></li>
  </ul>
  <li><a href="#linked_list_chapter">2: Linked List Recursion</a></li>
  <ul>
    <li><a href="#link_list_single_list_reversal">2.1 Post Recursion</a></li>
    <li><a href="#link_list_add_two_numbers">2.2 Pre Recursion</a></li>
  </ul>
  <li><a href="#linked_list_chapter">3: Tree Recursion</a></li>
  <ul>
    <li><a href="#unique_binary_search_tree_ii">3.1 Unique Binary Search Trees II</a></li>
    
  </ul>
  <!-- <li><a href="#prob1">2: Fibo series</a></li>
  <li><a href="#prob2">3: LinkList</a></li>
  <ul>
    <li><a href="#Second_Sub_Point_1">2.1 reversal of linklist</a></li>
  </ul> -->
</ul>
</div>


{% include_relative recursion/introduction.html %}

<!-- LinkList section -->
{% include_relative recursion/linked_list_chapter.html %}
{% include_relative recursion/linked_list_single_list_reversal.html %}
{% include_relative recursion/linked_list_add_two_numbers.html %}

<!-- Tree section -->
{% include_relative tree/unique_binary_search_trees_ii.html %}









<!-- TEMPLATE BELOW -->
<!-- =============================================================================================== -->
<!-- <div id="prob1"></div>
* Problem 1
---
---
<div style="background-color: #EEEEFF">

<b>Problem</b>: Find fibo series
<br />

<b>Recursion math notation</b>: 
<img src="/images/prob1/mathnotation1.jpg" alt="Double LinkList diagram">

<br />
<b>Recursion Visual</b>: 
<img src="/images/prob1/recursion1.jpg" alt="Double LinkList diagram">
<br />

<br />
<b>Iteration Visual</b>: 
<img src="/images/prob1/iteration1.jpg" alt="iteration visual">
<br />
</div>
<table class="center" >
  <tr>
    <th>
      Recursion
    </th>
    <th>
      Iteration
    </th>
  </tr>
  <tr>
    <td class="inner">
{% highlight c++ %}
void dfs()
{
  for(int i = 0; i < n; i++)
  {
    cout << "hello";
  }
}
{% endhighlight %}
    </td>
    <td>
{% highlight c++ %}
void dfs(int i, int b, int c, int d)
{
if(i <= 0)
  return;
else
  dfs(i-1, b-1);
}
{% endhighlight %}
    </td>
  </tr>
</table>
 --><!-- =============================================================================================== -->

