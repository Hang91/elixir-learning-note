# elixir-learning-note

System_time unit

In elixir doc, System.system_time(unit) made me confused. Unit is not explained in the doc. 
Actually, unit is several atoms, which hash been defined in Erlang.
:native, :second, :millisecond, :microsecond, :nanosecond. 
The :native value is a special one that means the highest resultion available to the runtime system.

Outout a list
IO.inspect [10,10], charlists: :as_lists
