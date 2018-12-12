# memo

## Clone
`$ git clone https://github.com/BiggieBoo18/memo.git <INSTALLDIR>`

## Setup
`$ export PATH="<INSTALLDIR>:$PATH"`  
`$ memo --setdir <MEMODIR(example:$HOME/Document/memo)>`

## Show memo list
`$ memo`  
or  
`$ memo -ls`

## Write memo
`$ memo -w <FILENAME>`  
###### NOTE:Currently emacs launches

## Show memo
`$ memo -s <FILENAME>`  
examples:  
`$ memo -s "example.memo"`  
`$ memo -s "<MEMODIR>/example.memo"`  
`$ memo -s "*.memo"`  
###### NOTE:Single-quote or Double-quote is necessary
