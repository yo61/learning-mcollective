# learning_mcollective

## Overview 

This is a collection of files for r10k setup of the Puppet module used in the development of the book  
[![Learning MCollective cover](http://akamaicovers.oreilly.com/images/0636920032472/rc_cat.gif)](http://shop.oreilly.com/product/0636920032472.do)
>  O'Reilly Media, Inc  
>  ISBN: [978-1-4919-4567-4](http://shop.oreilly.com/product/0636920032472.do) 

## Description

This repository contains an example r10k configuration and a Puppetfile
for setting up the modules used in the Learning MCollective book.

Example hiera data files are in the hiera/ directory.

## Simple Setup

```
$ wget https://raw.githubusercontent.com/jorhett/learning-mcollective/master/r10k.conf
$ r10k deploy -c r10k.conf environment learning_mcollective -p

# optionally
$ puppet agent --test --environment learning_mcollective
```

This doc needs some love, I hope to get back to it soon.

## Bugs

If you report it, and I can replicate it I'll fix it.

If you have an idea for improvement I might do it.
If you create a Pull request it will happen faster.

I'm human and prone to overwork so response times vary. YMMV.
