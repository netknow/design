# design
Brainstorm the requirements of the project, that would eventually form the design.

Requirements:

1. Input the the system: Subject to learn
2. Output: An index of weblinks(articles, streaming videos, wikipedia, code excerpts, books, etc..)
3. Constraints: Every index item(its like a topic in an index of a book) is dynamic to provide optimum amount of information at that level of abstraction.
4. Users can rate the index items for quality, completeness.
5. Users can attach questions to an index item.
6. Users can highlight key concepts in the initial topic and personalize their learning.
7. Users can checkout an index item, add more content to it and then publish their own branches.

Initial suggestion:
Just like the way Ted-Ed(http://ed.ted.com/) does it, a new topic of study can be initiated as the input to the system. The business logic starts from here.

Invite ideas: Need a machine learning algorithm to provide the table of contents under the initial node.
might help: The stochastic page rank algorithm ran on the search strings, which are based on the questions raised on the parent topic, or the key concepts in the parent topic.

Every index in the table of contents could be a max-heap of URLs, max property of the heap is the metric, quality(as determined by user votes)

