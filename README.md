https://itsvetobaby.github.io/gattling/

Gun x bitcoin repo


VERY HACKY


If your a new user press Sign Up, then Sign in. If nothing happens press Sign In again. <br>
Else press Sign In. <br>
Experimental, non-production hack for using Gun.js's user auth system to generate keys. See lines 22-32 ./js/coinbin.js <br>
A different user/password pair will generate a new pair of keys. <br>
This is not a place to store crypto, just somthing to fiddle with, and develop for your own purposes. <br>
PLEASE test before integrating. No package installation required, just: <br>
 <br>
```
npx serve
```

drag and dropping index.html into your browser will work too 


<hr>

Why would i want to use this?

Gun has a roughly 5 line user set-up template, its amazing. I highjacked it so you can bring coinbin into your gun app without any extra work. 

And when you want to record transaction data you can user.put("transactions").set(transaction_obj).
