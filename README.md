# PHPsinks
linux cmd one liner to grep PHP sinks from source code.

#### One linner for RCE
```
grep  -l -r 'exec\|passthru\|system\|shell_exec' . | while read line; do grep --color -r 'exec\|passthru\|system\|shell_exec' $line; done
```

#### One linner for LFI/RFI
```
grep  -l -r 'include\|require' . | while read line; do grep --color -r 'include\|require' $line; done
```
## Sources
Please feel free to issue pull requests with New sources

## Contact me 
* Gmail : syedmudassiruddinalvi@gmail.com
* Twitter : SyedMudassirud2
* Instagram  : lvomer
