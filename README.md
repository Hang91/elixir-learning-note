# elixir-learning-note

#System_time unit

In elixir doc, System.system_time(unit) made me confused. Unit is not explained in the doc. 
Actually, unit is several atoms, which has been defined in Erlang.
:native, :second, :millisecond, :microsecond, :nanosecond. 
The :native value is a special one that means the highest resolution available to the runtime system.

#Outout a list

IO.inspect [10,10], charlists: :as_lists

Difference between Process.exit(pid,:normal) and Process.exit(pid,:kill) is still unclear

#Start a project of elixir:

mix new (name of project)

#command line compile

def escript do

  [main_module: name of main_module]
  
end

mix escript.build

./(name of main_module) arguments

#hash function and change digits

this blog well explained

https://www.djm.org.uk/posts/cryptographic-hash-functions-elixir-generating-hex-digests-md5-sha1-sha2/

# integer to 16 base char

String.at(Integer.to_string(int, 16), 0)



