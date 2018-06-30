# CPU --- OS Assignment 3

If compiled with -DEBUG, when run it should produce the following
output (approximately):

$ ./CPU ./myscript ./myscript ./myscript  
state:        3  
name:         IDLE  
pid:          17961  
ppid:         17959  
interrupts:   0  
switches:     0  
started:      0  
in CPU.cc at 260 at beginning of send_signals getpid() = 17960  
in CPU.cc at 265 sending signal = 14  
in CPU.cc at 266 to pid = 17959  
In ISR stopped:     17961  
---- entering scheduler  
running NEW process  
continuing    17962  
---- leaving scheduler  
Process 17962 1  
in CPU.cc at 265 sending signal = 14  
in CPU.cc at 266 to pid = 17959  
In ISR stopped:     17962  
---- entering scheduler  
running NEW process  
continuing    17964  
---- leaving scheduler  
Process 17964 1  
in CPU.cc at 265 sending signal = 14  
in CPU.cc at 266 to pid = 17959  
In ISR stopped:     17964  
---- entering scheduler  
running NEW process  
continuing    17966  
---- leaving scheduler  
Process 17966 1  
in CPU.cc at 265 sending signal = 14  
in CPU.cc at 266 to pid = 17959  
In ISR stopped:     17966  
---- entering scheduler  
running READY process  
a switch has occurred  
continuing    17962  
---- leaving scheduler  
Process 17962 2  
in CPU.cc at 265 sending signal = 14  
in CPU.cc at 266 to pid = 17959  
In ISR stopped:     17962  
---- entering scheduler  
running READY process  
a switch has occurred  
continuing    17964  
---- leaving scheduler  
Process 17964 2  
in CPU.cc at 265 sending signal = 14  
in CPU.cc at 266 to pid = 17959  
In ISR stopped:     17964  
---- entering scheduler  
running READY process  
a switch has occurred  
continuing    17966  
---- leaving scheduler  
Process 17966 2  
in CPU.cc at 265 sending signal = 14  
in CPU.cc at 266 to pid = 17959  
In ISR stopped:     17966  
---- entering scheduler  
running READY process  
a switch has occurred  
continuing    17962  
---- leaving scheduler  
Process 17962 3  
in CPU.cc at 265 sending signal = 14  
in CPU.cc at 266 to pid = 17959  
In ISR stopped:     17962  
---- entering scheduler  
running READY process  
a switch has occurred  
continuing    17964  
---- leaving scheduler  
Process 17964 3  
in CPU.cc at 265 sending signal = 14  
in CPU.cc at 266 to pid = 17959  
In ISR stopped:     17964  
---- entering scheduler  
running READY process  
a switch has occurred  
continuing    17966  
---- leaving scheduler  
Process 17966 3  
in CPU.cc at 265 sending signal = 14  
in CPU.cc at 266 to pid = 17959  
In ISR stopped:     17966  
---- entering scheduler  
running READY process  
a switch has occurred  
continuing    17962  
---- leaving scheduler  
Process 17962 4  
in CPU.cc at 265 sending signal = 14  
in CPU.cc at 266 to pid = 17959  
In ISR stopped:     17962  
---- entering scheduler  
running READY process  
a switch has occurred  
continuing    17964  
---- leaving scheduler  
Process 17964 4  
in CPU.cc at 265 sending signal = 14  
in CPU.cc at 266 to pid = 17959  
In ISR stopped:     17964  
---- entering scheduler  
running READY process  
a switch has occurred  
continuing    17966  
---- leaving scheduler  
Process 17966 4  
in CPU.cc at 265 sending signal = 14  
in CPU.cc at 266 to pid = 17959  
In ISR stopped:     17966  
---- entering scheduler  
running READY process  
a switch has occurred  
continuing    17962  
---- leaving scheduler  
Process 17962 5  
in CPU.cc at 265 sending signal = 14  
in CPU.cc at 266 to pid = 17959  
In ISR stopped:     17962  
---- entering scheduler  
running READY process  
a switch has occurred  
continuing    17964  
---- leaving scheduler  
Process 17964 5  
in CPU.cc at 265 sending signal = 14  
in CPU.cc at 266 to pid = 17959  
In ISR stopped:     17964  
---- entering scheduler  
running READY process  
a switch has occurred  
continuing    17966  
---- leaving scheduler  
Process 17966 5  
in CPU.cc at 265 sending signal = 14  
in CPU.cc at 266 to pid = 17959  
In ISR stopped:     17966  
---- entering scheduler  
running READY process  
a switch has occurred  
continuing    17962  
---- leaving scheduler  
---- entering process_done  
process exited:  
state:        4  
name:         ./myscript  
pid:          17962  
ppid:         17959  
interrupts:   5  
switches:     5  
started:      1  
total system time:       15  
---- leaving process_done  
in CPU.cc at 265 sending signal = 14  
in CPU.cc at 266 to pid = 17959  
In ISR stopped:     17961  
---- entering scheduler  
running READY process  
a switch has occurred  
continuing    17964  
---- leaving scheduler  
---- entering process_done  
process exited:  
state:        4  
name:         ./myscript  
pid:          17964  
ppid:         17959  
interrupts:   5  
switches:     5  
started:      2  
total system time:       15  
---- leaving process_done  
in CPU.cc at 265 sending signal = 14  
in CPU.cc at 266 to pid = 17959  
In ISR stopped:     17961  
---- entering scheduler  
running READY process  
a switch has occurred  
continuing    17966  
---- leaving scheduler  
---- entering process_done  
process exited:  
state:        4  
name:         ./myscript  
pid:          17966  
ppid:         17959  
interrupts:   5  
switches:     5  
started:      3  
total system time:       15  
---- leaving process_done  
in CPU.cc at 265 sending signal = 14  
in CPU.cc at 266 to pid = 17959  
In ISR stopped:     17961  
---- entering scheduler  
continuing    17961  
---- leaving scheduler  
in CPU.cc at 265 sending signal = 14  
in CPU.cc at 266 to pid = 17959  
in CPU.cc at 270 at end of send_signals  
In ISR stopped:  
Terminated: 15  
---------------------------------------------------------------------------  
