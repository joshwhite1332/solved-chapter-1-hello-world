Download Link: https://assignmentchef.com/product/solved-chapter-1-hello-world
<br>
<a href="https://www.youtube.com/playlist?list=PLhOuww6rJJNP7UvTeF6_tQ1xcubAs9hvO" rel="nofollow">https://www.youtube.com/playlist?list=PLhOuww6rJJNP7UvTeF6_tQ1xcubAs9hvO</a>

Write a program to enthusiastically greet the world:

<pre><code>$ ./hello.pyHello, World!</code></pre>

The program should also accept a name given as an optional <code>--name</code> parameter:

<pre><code>$ ./hello.py --name UniverseHello, Universe!</code></pre>

The program should produce documentation for <code>-h</code> or <code>--help</code>:

<pre><code>$ ./hello.py -husage: hello.py [-h] [-n str]Say hellooptional arguments:  -h, --help          show this help message and exit  -n str, --name str  The name to greet (default: World)</code></pre>

Run <code>pytest -xv test.py</code> (or <code>make test</code>) to ensure you pass all the tests:

<pre><code>$ make testpytest -xv test.py============================= test session starts ==============================...collected 4 itemstest.py::test_exists PASSED                                              [ 25%]test.py::test_usage PASSED                                               [ 50%]test.py::test_default PASSED                                             [ 75%]test.py::test_input PASSED                                               [100%]============================== 4 passed in 0.41s ===============================</code></pre>