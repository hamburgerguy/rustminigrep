# rustminigrep
A grep (globally search for a regular expression and print matching lines)  repo, made in rust, slightly personalized. MUST HAVE RUST DOWNLOADED . To run, download the files to a directory with text files you want to use the grep on then from the terminal type in the command 

$ cargo run (query) (filename) 
 
The query is the word or string to search for and filename is the file to search through. Case sensitivity is able to be toggled with 

$ CASE_INSENSITIVE=1 cargo run (query) (filename) 
  
can output results as well with 
  
$ cargo run > (outputfilename)
  
 have fun!
  

