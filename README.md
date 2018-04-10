## Solidity-Go-Parser
Parser for solidity in go lang based on solidity grammar using antlr4

#### Run your parser

* Put your solidity code in [contract file]( https://github.com/phunsukwangdu/Solidity-Go-Parser/blob/master/contract )
* Run as ``` go run parser.go contract ```
#### Sample 
* For simple contract ``` contract hyperledger {
     function hello_world() {}} ```

* Output:- 
```
contracthyperledger{functionhello_world(){}}<EOF>
contracthyperledger{functionhello_world(){}}
hyperledger
functionhello_world(){}
functionhello_world(){}
hello_world
()

{}


```
