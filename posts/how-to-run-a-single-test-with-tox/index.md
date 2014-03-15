<!-- 
.. title: How to Run a Single Test With Tox
.. slug: how-to-run-a-single-test-with-tox
.. date: 2014/03/07 04:49:53
.. tags: python,testing,cli
.. link: 
.. description: 
.. type: text
-->

I have to run a single python test once in a while and keep forgetting how to do it with Tox.

Here it is:

```bash
tox -e py27 -- project_name_here.tests.folder_name1_here.folder_name2_here.test_file_name_here.TestClassName.test_method_name
```

Hope this helps someone else.

Happy bit twiddling.