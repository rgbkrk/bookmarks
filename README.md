# bookmarks

Because why would I store these in awkward menu bars. There may be rambling involved.

## Collections

* [RxJS Roundup](rxjs)

## Highly Recommended

### Full Stack Redux React Webpack crazy pants tutorial

You have to devote time to working through this tutorial:

http://teropa.info/blog/2015/09/10/full-stack-redux-tutorial.html

It bothered me at first - why would they want immutable data structures? Isn't working in memory faster? That's just it though! If you have an immutable data structure that is a tree and you update a single node, the rest of the tree is the same as before. The reason this is important is that comparison of two trees is a matter of pointer comparison rather than deep value comparison.
