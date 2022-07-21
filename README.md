# TrustIssuewithsetTimeout
Go live in vs code open chrome or youe default web browser .\n
Go to the developer option in chrome web browser, \n
You will notice that how setTimeout sometimes give late output.\n
Here the while loop take 10 seconds to complete and setTimeout is of 5 sec and hence the call stack is not empty. So the setTimeout will ave to wait for call stack to empty first then the event loop will push the function cb from the callback queue to call stack and finally "callback" is printed.
