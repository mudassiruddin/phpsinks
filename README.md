# PHPsinks
linux cmd one liner to grep PHP sinks from source code.

#### One linner
```
grep  -l -r 'exec\|passthru\|system\|shell_exec' . | while read line; do grep --color -r 'exec\|passthru\|system\|shell_exec' $line; done
```
## Sources
Please feel free to issue pull requests with New sources

## Contact me 
* Gmail : syedmudassiruddinalvi@gmail.com
* Twitter : SyedMudassirud2
* Instagram  : lvomer
