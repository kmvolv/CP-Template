# CP-Template
A useful template for competitive programming containing commonly used functions with optimal time complexity as well as nifty templates to make implementation a lot faster.

Here's a brief description of the functions and templates used :

- ```powa()``` : Calculates the value of a<sup>n</sup> using [Binary Exponentiation](https://cp-algorithms.com/algebra/binary-exp.html). Takes m = mod (10<sup>9</sup> + 7) as an argument in case [Modular Exponentiation](https://www.geeksforgeeks.org/modular-exponentiation-power-in-modular-arithmetic/) is to be implemented. Do note that this function carries out Binary Exponentiation by default, in order to implement Modular Exponentation just uncomment ```x %= m``` at both of its occurences.
- ```dectobin()``` : Takes an integer as its only argument and return its binary representation in the form of a string. For example, if I give 5 as the argument to this function, the string ```"101"``` is returned. Really useful for problems involving bitwise operators.
- The template ```pbds``` is used to implement a **P**olicy **B**ased **D**ata **S**tructure, more about which you can check out [here](https://www.geeksforgeeks.org/policy-based-data-structures-g/). There are a few additional header files to be included in order to implement this, you can have a look at [this video](https://youtu.be/IWyIwLFucU4) for a well detailed explanation on the same. 
- The ```ostream``` and ```istream``` templates are used to input/output the contents of an vector in just a single line - ```cin>>(vector_name)``` / ```cout<<(vector_name)```. Please make sure that you have initialized the size of the vector if you are inputting it using this template. 

There are a few more templates present but they hardly ever get used, so it would be better to just omit them for now. 

Some of the hash defines used :
- ```all(x)``` : Super useful when using the STL ```sort()``` function since it saves the effort of writing ```x.begin(),x.end()```.
- ```fastio``` : A necessity especially in the field of Competitive Programming. The time saved using this is astronomical. [Here's an article on the same](https://www.geeksforgeeks.org/fast-io-for-competitive-programming/)
- ```sz(q)``` : Used to find the size of a data structure ```q```, mainly used when iterating through the elements of a data structure you don't explicitly know the size of.

Hope this summarizes the template well enough, you can always reach out to me if you'd like to suggest any changes or make any contributions of your own - that would be much appreciated. Many thanks to [Aneesh](https://github.com/aneesh2312) for sharing his template on his profile, this is essentially a modification of that. Without his contribution I wouldn't even be typing this!

Thanks a lot for reading through everything I've typed, hope you have a great day ahead! : )
