# SequenceSelectScript
## introduction
This pipeline can select the correct sequence from the raw reads from pair-end sequence using filtering, matching, and blast methods.  
  
**DNAStorageSequence.py**  
  
Main script. Typing following command to getting more help informations.  
```
python3 DNAStorageSequence.py -h
```
## Usage
```
python DNAStorageSequence.py -p1 [PE1 fastq file] -p2 [PE2 fastq file] -f [default] -c [config path] -t [default]
```
## example  

**example/**  
  
Example files  
  
**example/run.sh**  
  
`sh run.sh`, use absolute path for each param.  
  
**example/config/**  
  
Contains configuration files containing primer information  
  
**example/data/**  
  
Pair-end sequence data for demo.  
  
**example/result**  
  
The demo result for validating program.
