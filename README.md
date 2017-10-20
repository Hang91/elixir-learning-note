# elixir-learning-note

System_time unit

In elixir doc, System.system_time(unit) made me confused. Unit is not explained in the doc. 
Actually, unit is several atoms, which has been defined in Erlang.
:native, :second, :millisecond, :microsecond, :nanosecond. 
The :native value is a special one that means the highest resolution available to the runtime system.

Outout a list

IO.inspect [10,10], charlists: :as_lists

Difference between Process.exit(pid,:normal) and Process.exit(pid,:kill) is still unclear

Start a project of elixir:

mix new (name of project)

command line start: 

def escript do

  [main_module: name of main_module]
  
end

mix escript.build
./(name of main_module) arguments


