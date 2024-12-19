# Vector Sort

The purpose of this program is to sort a datafile of vectors in acending order. While the default delimiters are '(', ')', and '\n', they of course can be adapted to your needs.  

### **Build:**  
Because the program is relatively simple, it can be built with the following command:  
  
```gcc vector.c -o vector```  

### **Example Input**  
Although other delimiters can be specified by editting the _DELIMITERS_ definition, the default delimiters expect input file contents to be in the format:

```(0,0,0)(1,1,1)(x,y,value)...```

### **Example Usage:**  
  
```./vector -i file.vector```  
  
### **Other flags**  
  
  -o:   Specify an output file.  
  -v:   Enable verbose mode.  
  -h:   Prints some _not so very helpful_ help information.  
