# Ruby NoMethodError: Uncommon Cause in Instance Variable Access

This repository demonstrates a subtle cause of `NoMethodError` in Ruby related to accessing instance variables indirectly and unexpectedly raising exceptions when attempting to call undefined methods.  The example showcases a clear way to encounter this error and highlights best practices to avoid it. 

The code in `bug.rb` showcases the error and the solution in `bugSolution.rb` demonstrates best practices for preventing this error.  This is especially important when handling external inputs or data where method existence can't be guaranteed.