#Accessing global variable from a function

https://groups.google.com/forum/#!topic/comp.lang.ruby/UI9ipuFNVTw


Global variables start with a "$" so just write
def func
    puts $i
end
$i = 5
func

