# -

立即执行函数

1. 函数的函数声明、函数表达式、匿名函数

    //函数声明
    function log（args） {    
      console.log(agrs);
    }

    //函数表达式
    const log = function(args)    
      console.log(args);
    }

    //匿名函数
    function（args）{        
      console.log(agrs);
    }

2. 立即执行函数的两种形式

    (function(){})()
    (function(){}())

一种一个小括号包含一个匿名函数，后面跟一个小括号。一种一个匿名函数后面跟一个小括号，然后再包在一个小括号内。两种立即执行函数等价。
注意匿名函数后面一定要跟小括号，而且里面的函数一定是匿名函数，而不是函数表达式。

